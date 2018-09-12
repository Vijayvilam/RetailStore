# RetailStore
This repository has RetailsStore.csproj and TestRetailStore.csproj project files. Please download and keep them two different projects.
RetailsStore.csproj's source files are CUSTOMER.cs,USER.cs,SHOPPING CART.cs,Purchase.cs. Please add them into this project file.
TestRetailStore.csproj's source file UnitTest1.cs
Please have this two project in single solution(.sln) file.
Purchase.cs has the functions to perform BillGeneration and discount calculation function.
This functions can be invoked from UnitTest1.cs file to verify the test result.
RetailStore source files are generted from Shop.uml file which has class diagram 
The following is the procedure to set up Code Coverage in Visual Studio:

Double-click the "[Local].testsettings" file in the Solutions Items folder in the Solution Explorer window.
In the "Test Settings" dialog, choose the "Data and Diagnostics" item.
In the list of roles, select "Code Coverage" and immediately click the '"Configure" button.
In the "Code Coverage Detail" dialog select the assemblies to instrument for Code Coverage.
Run your test scenario and in the "Test Tools" toolbar, click the icon "Code Coverage Results".
Done.
