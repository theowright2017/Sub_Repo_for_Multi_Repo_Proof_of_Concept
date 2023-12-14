This is the sub package intended to represent the Exams tab.

It utilises a global window assigned method in the form of stringToUppercase, reflecting similar variables and methods found in Termtime such as TimeHelper.
This shows that global values can still be accessed in an npm package from 'main'.

Also shown is the use of the Table component, defined in main and used in Sub.  It is injected as a dependency to encourage further decoupling and remove the risk of circular dependencies.
