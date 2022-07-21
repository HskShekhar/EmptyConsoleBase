NOTE: It uses Command Variable extension (Id: rioj7.command-variable) so installing it is required.

Execute C# code inside a single file like scripts in Python and Java with each file having ite own Main() entry point.

C# does not allow a single file to be run as script like python or java without extensions which in many case are not reliable. Also the issues with these extensions are that even if they allow run there is always issues with debug mode which requires setting up path variables or additional configurations which are very lenthy and complex.

This console Application Template allows to create a console application having a main method in each class file which can be invoked at runtime dependig upon the focused file in code editor and execute that single file as if it were the only file present in entire application.

So users don't need to create multiple console applications for testing code in a file or call each class from Single Main entry point to test and debug.

It uses Command Variable extension (Id: rioj7.command-variable) to achieve this functionality.
