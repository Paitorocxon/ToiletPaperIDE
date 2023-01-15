# ToiletPaperIDE
A small C# IDE for small C# Applications


Write small C# Code fast and lazy...


## Overview:
 - Fast Compiling
 - Precompile Code from Internet while compiling your source
 - Highlighting (For FastColoredTextBox Checkout https://github.com/PavelTorgashov/FastColoredTextBox. Epic! License -> https://raw.githubusercontent.com/PavelTorgashov/FastColoredTextBox/master/license.txt )
 - Autocomplete
 - Compressed Coding due tue Inplicate Crosspiler*
 
 By Crosspiler i mean the translation from inplicate Commands to valid C# Code.

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
