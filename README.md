# ARNOLDC

ArnoldC is an esoteric language based on Arnold Schwarzenegger's movie lines. Its creator, Lauri Hartikka, states that the project's motivation is to find new meanings from Arnold's movies through computer science. This is a fun way for Schwarzenegger's fans to reference iconic moments and lines. Not only that, people who are unfamiliar with his movies can learn more about the characters he had portrayed through this language.

Installing this only requires the following wget command:  
>wget http://lhartikk.github.io/ArnoldC.jar  


Files can then be compiled and ran with the following commands:  
>java -jar ArnoldC.jar <filename\>.arnoldc  
>java <filename\>

There are also online compilers that can be used:
>- [Try It Online](https://tio.run/#arnoldc) - recommended
>- [ArnoldC cyber simulator](http://mapmeld.com/ArnoldC/)  
>- [ArnoldC cyber simulator v2](http://mapmeld.com/ArnoldC/?v=2)

---

The following is the list of commands and their descriptions:  

- *@I LIED* -	False
- *@NO PROBLEMO* - True
- *BECAUSE I'M GOING TO SAY PLEASE* - If
- *BULLSHIT* - Else
- *YOU HAVE NO RESPECT FOR LOGIC* - EndIf
- *STICK AROUND* - While
- *CHILL* - EndWhile
- *GET UP* - Add
- *GET DOWN* - Subtract
- *YOU'RE FIRED* - Multiply
- *HE HAD TO SPLIT* - Divide
- *I LET HIM GO* - Modulo
- *YOU ARE NOT YOU YOU ARE ME* - Equal to
- *LET OFF SOME STEAM BENNET* - Greater than
- *CONSIDER THAT A DIVORCE* - Or
- *KNOCK KNOCK* - And
- *LISTEN TO ME VERY CAREFULLY* - DeclareMethod
- *GIVE THESE PEOPLE AIR* - NonVoidMethod
- *I NEED YOUR CLOTHES YOUR BOOTS AND YOUR MOTORCYCLE* - MethodArguments
- *I'LL BE BACK* - Return
- *HASTA LA VISTA, BABY* - EndMethodDeclaration
- *DO IT NOW* - CallMethod
- *GET YOUR ASS TO MARS* - AssignVariableFromMethodCall
- *HEY CHRISTMAS TREE* - DeclareInt
- *YOU SET US UP* - SetInitialValue
- *IT'S SHOWTIME* - BeginMain
- *YOU HAVE BEEN TERMINATED* - EndMain
- *TALK TO THE HAND* - Print
- *I WANT TO ASK YOU A BUNCH OF QUESTIONS AND I WANT TO HAVE THEM ANSWERED IMMEDIATELY* - ReadInteger
- *GET TO THE CHOPPER* - AssignVariable
- *HERE IS MY INVITATION* - SetValue
- *ENOUGH TALK* - EndAssignVariable
- *WHAT THE FUCK DID I DO WRONG* - ParseError

---
## Conventions
Keywords must be capitalised while variables are in lowercase. Each keyword is also written on a new line.
## Example
### Printing hello world  
Code:
>IT'S SHOWTIME   
TALK TO THE HAND "hello world"  
YOU HAVE BEEN TERMINATED

Output:
>hello world

The keyword "IT'S SHOWTIME" represents the start of the main method, while "YOU HAVE BEEN TERMINATED" signals the end. "TALK TO THE HAND" prints the string or the variable next to it. This keyword also automatically adds a line break after the printed statement.

Overall, the commands are just the same with Java but with different keywords. So far, the available commands are limited in this esoteric language, but it's still great in performing simple computations and projects.

### References
Hartikka, L. (2017, March 21). ArnoldC Quick Start. Retrieved from GitHub: https://github.com/lhartikk/ArnoldC/wiki/ArnoldC  
Hartikka, L. (2019, November 1). ArnoldC. Retrieved from GitHub: https://github.com/lhartikk/ArnoldC/wiki/ArnoldC

