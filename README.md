# ToiletPaperIDE
A small C# IDE for small C# Applications


Write small C# Code fast and lazy...


## Overview:
 - Fast Compiling
 - Precompile Code from Internet while compiling your source
 - Highlighting (For FastColoredTextBox Checkout https://github.com/PavelTorgashov/FastColoredTextBox. Epic! License -> https://raw.githubusercontent.com/PavelTorgashov/FastColoredTextBox/master/license.txt )
 - Autocomplete
 - Compressed Coding due tue Inplicate Crosspiler*
 
 ![This is an image](https://raw.githubusercontent.com/Paitorocxon/ToiletPaperIDE/main/TP_IDE.gif)
 
 
 *By Crosspiler i mean the translation from inplicate Commands to valid C# Code.

Initially i've wrote it due to teh fact that i don't have time to go to google and look things up for cmd batch or sh!t like diz.
So makes it special?

Time consumption!
Using a file from the internet? Gotcha!
```
use "https://www.github.com/user/file.cs";
```
## Inplicate Crosspiler
Inplicate Crosspiler (Fancy words for "I do some work for you").
use
```
{{
 System.Console.WriteLine("Hello World");
 System.Console.ReadLine();
}}
 ```
 and it will work!
 
 
 ## Example of the "Power" of the ToiletPaper IDE:
 Fully Working C# Code:
 ```
using System;
use "https://raw.githubusercontent.com/Fabsology/testing/main/test5.cs";
namespace application {
    class Program {
        public static void Main(string[] args) {
            Hello.Hay();
            System.Console.ReadLine();
        }
       
    }
} 
 ```
 Which outputs:
 > Hello World!
 
 # So how's the chain?
 TP-IDE ❱ Inplicate ❱ csc.exe ❱ exe.exe
 
 
 # Completion? Around 5%?
 
 
 # What's on the list?
  - Stuff like:
   ```
   AdHocHttpServer MyServer = new AdHocHttpServer(80);
    while(MyServer.IsRunning()){
      MyServer.Body = "Something";
      Wait(20);
    }
   ```
  - To be continued!


 # Implicate Commands:
 
 ## Icon
Set Icon for your application
```
implicate.favicon = PATH;
```


 ## Compiling
 It will determine by itself whether it is a library or a simple exe.
 I mean i made it with a small overcomplexed RegEx... Should work, i guess.
Set compiling option for your application
```
implicate.output = MyApp.exe;
```
or
```
implicate.output = MyLib.dll;
```


## Use online source
```
use "URL";
```
OR
```
use "local.DLL_IN_SAME_FOLDER.dll";
```
By using a local dll, make sure the name is correct and the same as the namespace itself and by using the "local." prefix.
Example:
> use "MyLibrary.dll";
but the namespace is "pait.engine.somethingcool",
then it will not work! So name your DLLs to the namespace :)




 ## PLACEHOLDER (yet to come)
