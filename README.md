# Project Hello World 🏳️‍🌈
Hello world in different Programming languages and even in speaking languages. Hello world file is the first programming file of every programmer.

- [Programming Language]()
- [Speaking Language]()

## Programming Language - 73
| Alphabet | 0 | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 |
| - | - | - | - | - | - | - | - | - | - | - |
| 0 | [A](#a-alphabet) | [B](#b-alphabet) | [C](#c-alphabet) | [D](#d-alphabet) | [E](#e-alphabet) | [F](#f-alphabet) | [G](#g-alphabet) | [H](#h-alphabet) | [I](#i-alphabet) | [J](#j-alphabet) |
| 1 | [K](#k-alphabet) | [L](#l-alphabet) | [M](#m-alphabet) | [N](#n-alphabet) | [O](#o-alphabet) | [P](#p-alphabet) | [Q](#q-alphabet) | [R](#r-alphabet) | [S](#s-alphabet) | [T](#t-alphabet) |
| 2 | [U](#u-alphabet) | [V](#v-alphabet) | [W](#w-alphabet) | [X](#x-alphabet) | [Y](#y-alphabet) | [Z](#z-alphabet) |
### A Alphabet
<hr>

#### A+
```
[]<-’Hello World!’
```
#### Abap – SAP AG
```
WRITE 'Hello, World!'.
```
#### ABC
```
WRITE "Hello, world!"
```
#### ActionScript
```
trace("Hello, World!");
this.createTextField("hello_txt",0,10,10,100,20);
this.hello_txt.text="Hello, World!";
```
#### ActionScript 3
```
package{
    import flash.display.Sprite; 
    public class HelloWorld extends Sprite{
	public function HelloWorld(){
		trace("Hello, world!");
	}
    }
}
```
#### Ada
```
with TEXT_IO;
procedure HELLO is
begin
 TEXT_IO.PUT_LINE ("Hello, World!");
end HELLO;
```
#### Adobe Flex MXML
```
<?xml version="1.0" encoding="utf-8"?>
<mx:Application xmlns:mx="http://www.adobe.com/2006/mxml">
<mx:Label text="Hello, world!"/>
</mx:Application>
```
#### Algol
```
BEGIN DISPLAY("Hello World") END.
```
#### Algol 60
```
'BEGIN'
 'COMMENT' In Algol 60;
 OUTPUT(4,'(''('Hello World!')',/')')
'END
```
#### Algol 68
```
BEGIN
	print(("Hello, World!", newline))
END
( print("Hello, World!") )
```
#### Alma-0
```
Hello, World!
```
#### AmigaE
```
PROC main()
 WriteF('Hello, World!');
ENDPROC
```
#### AMX NetLinx
```
program_name = 'Hello'
define_start
send_string 0,'Hello World!'
```
#### Apl
```
'Hello, World!'
```
#### AppleScript
```
return "Hello, World!"
-- "Hello World!"
display dialog "Hello World!" buttons {"OK"} default button 1
```
#### Ascii
```
48 65 6C 6C 6F 2C 20 77 6F 72 6C 64 21 0D 0A
```
#### Asp
```
<%
    Response.Write("Hello, World!")
%>
<%="Hello, World!" %>
```
#### Asp.Net
```
Response.write("HELLO WOLRD!");
```
#### AspectJ
```
public aspect HelloWorld{
	pointcut mainCall() : call(public static void *.main(String[] args));
	before() : mainCall(){
		System.out.println( "Hello World!" );
	}
}
```
#### Assembly
```
 global _main
    extern _printf

    section .text
_main:
    push    message
    call    _printf
    add        esp, 4
message:
    db    'Hello World', 10, 0
```
#### Aassembler – 6502
```
MSG: .ASCIIZ "Hello, World!"
START: LDX #0
LOOP: LDA MSG,X ; load character
JSR $FFD2 ; output to current output device
INX
BNE @LOOP
RTS
```
#### Assembler – Intel x86, Dos, Tasm
```
MODEL SMALL
IDEAL
STACK 100H
DATASEG
MSG DB 'Hello, World!', 13, '
CODESEG
Start:
MOV AX, @data
MOV DS, AX
MOV DX, OFFSET MSG
MOV AH, 09H ; output ascii string
INT 21H
MOV AX, 4C00H
INT 21H
END Start
```
#### Assembler – Intel x86, Linux
```
SECTION .data
msg:
db "Hello, World!\n"
len equ $ - msg
SECTION .text
global start
start:
mov edx,len
mov ecx,msg
mov ebx,1
mov eax,4
int 0x80
mov ebx,0
mov eax,1
int 0x80
```
#### Assembler 68000:
```
move.l #helloworld,-(A7)
move #9,-(A7)
trap #1
addq.l #6,A7
move #0,-(A7)
trap #1
helloworld:
dc.b "Hello World!",$0d,$0a,0
```
#### Assembler – General-purpose fictional computer: MIX, MIXAL
```
General-purpose fictional computer: MIX, MIXAL

TERM    EQU    19          console device no. (19 = typewriter)
        ORIG   1000        start address
START   OUT    MSG(TERM)   output data at address MSG
        HLT                halt execution
MSG     ALF    "HELLO"
        ALF    " WORL"
        ALF    "D    "
        END    START       end of program
```
#### Arm, Risc OS:
```
.program
 ADR R0,message
 SWI "OS_Write0"
 SWI "OS_Exit"
.message
 DCS "Hello, World!"
 DCB 0
 ALIGN
 SWI"OS_WriteS":EQUS"Hello, World!":EQUB0:ALIGN:MOVPC,R14
 ```
#### AutoHotkey
```
MsgBox, "Hello, World!"
```
#### Autoit
```
MsgBox(1,'','Hello, World!')
```
#### Avenue – Scripting language for ArcView GIS
```
MsgBox("Hello, World!","aTitle")
```
#### Awk
```
# Hello

BEGIN { print "Hello, World!" }
```
### B Alphabet
<hr>

#### B
```
/* Hello */
main()
{
 extern a, b, c;
 putchar (a); putchar (b); putchar (c); putchar ('!*n');
}
a 'hell' ;
b 'o, w' ;
c 'orld' ;
```
#### Baan Tools
```
function main()
{
    message("Hello, world!")
}
```
#### Ball
```
write Hello, *s world *n
```
#### Bash
```
echo "Hello World"
```
#### Basic
```
10 PRINT "Hello, World!"
20 END
PRINT "Hello, World!"
? "Hello, World!"
PRINT "Hello, World!"
END
```
#### BlitzBasic
```
Print "Hello, world!"
WaitKey
```
#### Bro Lang
```
bro bro Bro bro bro Bro bro bro Bro bro bro Bro bro bro bro Bro bro bro Bro bro 
bro Bro bro bro bro bro bro bro bro Bro bro Bro bro Bro bro Bro bro bro bro bro 
bro bro bro bro Bro bro bro bro bro Bro bro bro bro bro bro bro bro Bro bro bro 
Bro bro bro bro bro bro bro Bro bro bro Bro bro bro Bro bro bro Bro bro bro Bro 
bro bro Bro bro bro Bro bro bro Bro bro bro Bro bro bro Bro bro bro Bro bro bro 
bro bro bro bro Bro bro bro bro Bro bro bro Bro bro bro Bro bro bro Bro bro bro 
bro bro bro bro bro Bro bro Bro bro bro bro bro bro bro bro bro Bro bro bro bro 
bro Bro bro bro bro bro bro bro bro Bro bro bro Bro bro bro Bro bro bro Bro bro 
bro Bro bro bro Bro bro bro bro bro bro bro Bro bro bro bro Bro bro bro Bro bro 
bro bro bro bro bro bro Bro bro Bro bro Bro bro Bro bro bro bro bro bro bro bro 
bro Bro bro bro bro bro Bro bro bro bro bro bro bro bro Bro bro Bro bro Bro bro 
bro bro bro bro bro Bro bro bro bro Bro bro bro Bro bro bro Bro bro bro Bro bro 
bro bro bro bro bro bro Bro bro Bro bro bro bro bro bro bro bro bro Bro bro bro 
bro bro Bro bro bro bro bro bro bro bro Bro bro bro Bro bro bro Bro bro bro Bro 
bro bro Bro bro bro bro bro bro bro Bro bro bro Bro bro bro Bro bro bro Bro bro 
bro bro bro bro bro Bro 
```

### C Alphabet
<hr>
<!----------------------->

#### C
<pre>#include &lt;stdio.h&gt;
int main(void){
    printf("Hello, world!\n");
    return 0;
}</pre>

#### C#</h4>
<pre>using System;
class HelloWorld{
	static void Main(){
		System.Console.WriteLine("Hello, World!");
	}
}</pre>

#### C++ (ISO)</h4>
<pre class="lang:c decode:true">#include &lt;iostream&gt;

int main(){
	std::cout &lt;&lt; "Hello, World!\n";
}</pre>
#### C++ / Cli</h4>
<pre>int main(){
	System::Console::WriteLine("Hello, World!");
}</pre>
#### C++ Managed (.Net)</h4>
<pre class="toolbar:2 lang:c++ decode:true">#using &lt;mscorlib.dll&gt;

using namespace System;
int wmain(){
	Console::WriteLine("Hello, World!");
}</pre>
#### C#</h4>
<pre class="toolbar:2 lang:c# decode:true">class HelloWorldApp{
	static void Main(){
		System.Console.WriteLine("Hello, world!");
	}
}</pre>
#### Caché Server Pages (CSP)</h4>
<pre class="lang:c decode:true">Class Test.Hello Extends %CSP.Page [ ProcedureBlock ]
{
     ClassMethod OnPage() As %Status
     {
         &amp;html&lt;&lt;html&gt;
         &lt;head&gt;
         &lt;/head&gt;
         &lt;body&gt;&gt;
         Write "Hello, world!",!
         &amp;html&lt;&lt;/body&gt;
         &lt;/html&gt;&gt;
         Quit $$OK
     }
}</pre>
#### Caml light</h4>
<pre>(* Hello World *)

let hello =
	print_string "Hello World!";
	;;</pre>
#### CCL</h4>
<pre> call echo("Hello, world!")</pre>
#### Ceylon</h4>
<pre class="toolbar:2 lang:java decode:true ">shared void run() {
    print("Hello, World!");
}</pre>
#### Ch</h4>
<pre class=""> printf("Hello, world!\n");</pre>
#### Chapel</h4>
<pre class="toolbar:2 lang:c decode:true ">writeln("Hello, world!");</pre>

#### Chicken
```
chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken
chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken
chicken chicken chicken chicken
chicken chicken chicken chicken chicken chicken chicken chicken chicken
chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken
chicken chicken chicken chicken chicken chicken chicken
chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken
chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken
chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken
chicken chicken chicken chicken
chicken chicken chicken
chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken
chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken
chicken chicken chicken
chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken
chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken
chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken
chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken
chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken
chicken chicken chicken chicken chicken chicken

chicken chicken chicken
chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken
chicken chicken chicken chicken
chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken
chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken
chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken
chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken
chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken
chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken
chicken chicken chicken chicken chicken chicken

chicken chicken chicken chicken
chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken
chicken chicken
chicken chicken
chicken chicken chicken chicken chicken chicken chicken chicken chicken
chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken
chicken chicken chicken chicken chicken chicken

chicken chicken
chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken
chicken chicken chicken chicken chicken chicken chicken
chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken
chicken chicken chicken chicken chicken chicken

chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken
chicken chicken chicken
chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken
chicken chicken chicken chicken chicken chicken chicken
chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken
chicken chicken chicken chicken chicken chicken

chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken
chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken
chicken chicken chicken
chicken chicken chicken chicken chicken chicken chicken chicken
chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken
chicken chicken chicken chicken chicken chicken
```
#### CHILL</h4>
<pre class="lang:default decode:true ">Hello:
MODULE

WRITETEXT(STDOUT, "Hello World!%/");

END Hello;</pre>
#### Chuck</h4>
<pre class="toolbar:2 lang:c decode:true"> &lt;&lt;&lt;"Hello World"&gt;&gt;&gt;</pre>
#### Chrome</h4>
<pre>namespace HelloWorld;
     interface
     type
    HelloClass = class
    public
      class method Main;
     end;
     implementation
     class method HelloClass.Main;
  begin
    System.Console.WriteLine('Hello, world!');
  end;

end.</pre>
#### Cil</h4>
<pre>.method public static void Main() cil managed{
	.entrypoint
	.maxstack 8
	ldstr "Hello, World!"
	call void [mscorlib]System.Console::WriteLine(string)
	ret
}</pre>
#### Clarion</h4>
<pre>PROGRAM
MAP
END
CODE
MESSAGE('Hello, world!!','Clarion')
RETURN</pre>
#### Clean</h4>
<pre>module hello

Start = "Hello, World!"</pre>
#### Clist</h4>
<pre>PROC 0
WRITE Hello, World!</pre>
#### Clipper</h4>
<pre>? "Hello, World!"</pre>
#### Clu</h4>
<pre>start_up = proc ()
	po: stream := stream$primary_output ()
	stream$putl (po, "Hello, World!")
end start_up</pre>
#### Cobol</h4>
<pre>IDENTIFICATION DIVISION.
PROGRAM-ID. HELLO-WORLD.

ENVIRONMENT DIVISION.

DATA DIVISION.

PROCEDURE DIVISION.
DISPLAY "Hello, World!".
STOP RUN.</pre>
#### Cocoa or GnuStep (Objective C)</h4>
<pre class="toolbar:2 lang:objc decode:true">#import &lt;Cocoa/Cocoa.h&gt;
@interface hello : NSObject {
}
@end

@implementation hello

-(void)awakeFromNib
{
	 NSRunAlertPanel(@"Message from your Computer", @"Hello, World!", @"Hi!",
	 nil, nil);
}

@end</pre>
#### ColdFusion</h4>
<pre class="toolbar:2 lang:xhtml decode:true">&lt;cfoutput&gt;Hello, World!&lt;/cfoutput&gt;</pre>
#### Comal</h4>
<pre>PRINT "Hello, World!"</pre>
#### ConTeXt</h4>
<pre>\starttext
Hello, world!
\stoptext</pre>
#### Crystal</h4>
<pre class="lang:python decode:true ">puts "Hello World!"

#Object Oriented Style

class Greeter
  def initialize(@name : String)
  end

  def salute
    puts "Hello #{@name}!"
  end
end

g = Greeter.new("world")
g.salute</pre>
#### Curl</h4>
<pre>{curl 3.0, 4.0 applet}
{curl-file-attributes character-encoding = "utf-8"}

Hello, World!</pre>
<!----------------------->

### D Alphabet
<hr>

#### DarkBasic
```
PRINT "HELLO WORLD"
TEXT 0,0,"Hello, World!"
WAIT KEY
```
#### Dart
```
main(){
	print('Hello World');
}
```
#### Delphi
```
program HelloWorld;
begin
  WriteLn('Hello World');
end.
```
### E Alphabet
<hr>

### F Alphabet
<hr>

#### F#
```
printfn "Hello World"
```
#### Fortran
```
program helloworld
    print *, "Hello World"
end program helloworld
```
### G Alphabet
<hr>

#### Go
```
println('Hello World");
```
### H Alphabet
<hr>

#### Haskell
```
module Main where

main :: IO ()
main = putStrLn "Hello World"
```
#### HTML
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <h1>Hello World!</h1>
</body>
</html>
```
### I Alphabet
<hr>

### J Alphabet
<hr>


#### Java
```
import java.io.*;

class GFG {
	public static void main (String[] args) {
	System.out.println("Hello World");
	}
}
```
#### Javascript
```
console.log("Hello World!");
```
#### Julia
```
println("Hello, World!")
```
#### Jquery
```
$("body").append("HELLO WORLD!");
```
### K Alphabet
<hr>


#### Kotlin
```
fun main(args: Array<String>){
	println("Hello World")
}
```
### L Alphabet
<hr>


#### Lisp
```
(print "Hello World")
```
#### Lua
```
print("HELLO WORLD!");
```
### M Alphabet
<hr>


#### Matlab
```
disp('Hello World');
```
### N Alphabet
<hr>

### O Alphabet
<hr>

### P Alphabet
<hr>

#### Pascal
```
program Hello;
begin
  writeln ('Hello, world.');
end.
```
#### Perl
```
#!/usr/bin/perl
print "Hello World";
```
#### PHP
```
echo "Hello World";
```
#### Python3
```
print("Hello World")
```
### Q Alphabet
<hr>

### R Alphabet
<hr>

#### R
```
cat('Hello World')
```
#### RISC processor: MIPS architecture
```
       .data
msg:     .asciiz "Hello, world!"
         .align 2
         .text
         .globl main
main:
         la $a0,msg
         li $v0,4
         syscall
         jr $ra
```
#### Ruby
```
puts 'Hello World'
```
#### Rust
```
fn main() {
 println!("Hello, World!");
}
```
### S Alphabet
<hr>

#### Scala
```
object HelloWorld extends App {
	printIn("Hello World")
}
```
#### Shakespeare
```
Do Not Adieu, a play in two acts.

Romeo, a young man with a remarkable patience.
Juliet, a likewise young woman of remarkable grace.
Ophelia, a remarkable woman much in dispute with Hamlet.
Hamlet, the flatterer of Andersen Insulting A/S.


                    Act I: Hamlet's insults and flattery.

                    Scene I: The insulting of Romeo.

[Enter Hamlet and Romeo]

Hamlet:
 You lying stupid fatherless big smelly half-witted coward!
 You are as stupid as the difference between a handsome rich brave
 hero and thyself! Speak your mind!

 You are as brave as the sum of your fat little stuffed misused dusty
 old rotten codpiece and a beautiful fair warm peaceful sunny summer's
 day. You are as healthy as the difference between the sum of the
 sweetest reddest rose and my father and yourself! Speak your mind!

 You are as cowardly as the sum of yourself and the difference
 between a big mighty proud kingdom and a horse. Speak your mind.

 Speak your mind!

[Exit Romeo]

                    Scene II: The praising of Juliet.

[Enter Juliet]

Hamlet:
 Thou art as sweet as the sum of the sum of Romeo and his horse and his
 black cat! Speak thy mind!

[Exit Juliet]

                    Scene III: The praising of Ophelia.

[Enter Ophelia]

Hamlet:

 Thou art as beautiful as the difference between Romeo and the square
 of a huge green peaceful tree. Speak thy mind!

 Thou art as lovely as the product of a large rural town and my amazing
 bottomless embroidered purse. Speak thy mind!

 Thou art as loving as the product of the bluest clearest sweetest sky
 and the sum of a squirrel and a white horse. Thou art as beautiful as
 the difference between Juliet and thyself. Speak thy mind!

[Exeunt Ophelia and Hamlet]


                    Act II: Behind Hamlet's back.

                    Scene I: Romeo and Juliet's conversation.

[Enter Romeo and Juliet]

Romeo:
 Speak your mind. You are as worried as the sum of yourself and the
 difference between my small smooth hamster and my nose. Speak your
 mind!

Juliet:
 Speak YOUR mind! You are as bad as Hamlet! You are as small as the
 difference between the square of the difference between my little pony
 and your big hairy hound and the cube of your sorry little
 codpiece. Speak your mind!

[Exit Romeo]

                    Scene II: Juliet and Ophelia's conversation.

[Enter Ophelia]

Juliet:
 Thou art as good as the quotient between Romeo and the sum of a small
 furry animal and a leech. Speak your mind!

Ophelia:
 Thou art as disgusting as the quotient between Romeo and twice the
 difference between a mistletoe and an oozing infected blister! Speak
 your mind!

[Exeunt]
```
#### Solidity
```
pragma solidity ^0.4.22;
contract helloWorld {
 function renderHelloWorld () public pure returns (string) {
 return 'Hello, World!';
 }
}
```
#### Swift
```
println('Hello World');
```
### T Alphabet
<hr>

#### TCL
```
puts "Hello World"
```
#### TypeScript
```
console.log 'Hello World'
```
### U Alphabet
<hr>

### V Alphabet
<hr>

#### VB.Net
```
Module HelloWorld
    Sub Main( )
        System.Console.WriteLine("HELLO WORLD!")
        End Sub
End Module
```
#### VB Script
```
MsgBox "HELLO WORLD!"
```
### W Alphabet
<hr>

### X Alphabet
<hr>

### Y Alphabet
<hr>

### Z Alphabet
<hr>

### Number and Symbole
<hr>