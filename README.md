SimpleCalc
==========

SimpleCalc is a basic set C# and VB.NET demo projects.  I use this in various introductory settings to demonstrate how .NET makes it easy to create re-usable code as well as how you can use .NET to create applications that run on a variety of platforms (console, desktop, tablet, phone, web, etc). 

There are a total of 16 projects in this SimpleCalc.sln solution. Eight of them are C# projects and eight of them are VB.NET projects.  The C# projects all start with the **SimpleCalc._CS_.&#x2A;** prefix, whereas the VB.NET projects all start with the **SimpleCalc._VB_.&#x2A;** prefix.  In each collection of projects there is a:

 - **&#x2A;.PortableLibrary** - This project contains the code for the Calculator class.  The Calculator class is a very basic sample calculator implementation.  It has two public properties named Number1 and Number2.  These two property values are used as the operands in the Add, Subtract, Multiply and Divide operation public methods.  
 - **&#x2A;.ConsoleApp** - is a Windows Console application that leverages the SimpleCalc.&#x2A;.PortableLibrary.Calculator class from above to perform calculations for the user
 - **&#x2A;.WPF** is a WPF calculator
 - **&#x2A;.WebForms** is an ASP.NET WebForms web site
 - **&#x2A;.WinForms** is a Windows Forms app
 - **&#x2A;.WinPhone** is a Windows Phone 8 app
 - **&#x2A;.WinStore** is a Windows 8 Store app
 - **&#x2A;.UnitTests** is a unit test project that tests the calculator operations

Enjoy!

Bret Stateham<br/>
Developer Evangelist<br/>
Bret.Stateham@microsoft.com<br/>
BretStateham.com<br/>
@BretStateham<br/>
