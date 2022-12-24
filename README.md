# Project Hello World 🏳️‍🌈
Hello world in different Programming languages and even in speaking languages. Hello world file is the first programming file of every programmer.

- [Programming Language]()
- [Speaking Language]()

## Programming Language - 322
| Alphabet | 0 | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 |
| - | - | - | - | - | - | - | - | - | - | - |
| 0 | [A](#a-alphabet) | [B](#b-alphabet) | [C](#c-alphabet) | [D](#d-alphabet) | [E](#e-alphabet) | [F](#f-alphabet) | [G](#g-alphabet) | [H](#h-alphabet) | [I](#i-alphabet) | [J](#j-alphabet) |
| 1 | [K](#k-alphabet) | [L](#l-alphabet) | [M](#m-alphabet) | [N](#n-alphabet) | [O](#o-alphabet) | [P](#p-alphabet) | [Q](#q-alphabet) | [R](#r-alphabet) | [S](#s-alphabet) | [T](#t-alphabet) |
| 2 | [U](#u-alphabet) | [V](#v-alphabet) | [W](#w-alphabet) | [X](#x-alphabet) | [Y](#y-alphabet) | [Z](#z-alphabet) | [?](#number-and-symbole)
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
#### Basic – StarOffice/OpenOffice
<pre>sub main
 print "Hello, World!"
end sub</pre>

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

#### bc
<pre>"Hello, world!"</pre>
<pre>print "Hello, world!\n"</pre>
#### Bcpl
<pre>// Hello
GET "LIBHDR"
LET START () BE
$(
 WRITES ("Hello, World!*N")
$)</pre>
#### Beta
<pre>{ *** Hello ***}
(#
 do
 'Hello World!'-&gt;putLine
#)</pre>
#### BITGGAL AgileDog
<pre>T
1 "Hellow, World"
0</pre>
#### BITGGAL Jihwaja
<pre>J( 1 TM 5 ZV 3 "Hellow, world" )</pre>
#### Bliss
<pre>%TITLE 'HELLO_WORLD'
MODULE HELLO_WORLD (IDENT='V1.0', MAIN=HELLO_WORLD,
 ADDRESSING_MODE (EXTERNAL=GENERAL)) =
BEGIN
 LIBRARY 'SYS$LIBRARY:STARLET';
 EXTERNAL ROUTINE
 LIB$PUT_OUTPUT;
GLOBAL ROUTINE HELLO_WORLD =
BEGIN
 LIB$PUT_OUTPUT(%ASCID %STRING('Hello, World!'))
END;

END
ELUDOM</pre>
#### Boo
<pre>print "Hello, World!"</pre>
#### Burning Sand 2
<pre>WRITE ELEMENT:Earth 210 230 40 CENTER TEXT "Hello World!"</pre>

### C Alphabet
<hr>
<!----------------------->

#### C
<pre>#include &lt;stdio.h&gt;
int main(void){
    printf("Hello, world!\n");
    return 0;
}</pre>

#### C#
<pre>using System;
class HelloWorld{
	static void Main(){
		System.Console.WriteLine("Hello, World!");
	}
}</pre>

#### C++ (ISO)
<pre class="lang:c decode:true">#include &lt;iostream&gt;

int main(){
	std::cout &lt;&lt; "Hello, World!\n";
}</pre>
#### C++ / Cli
<pre>int main(){
	System::Console::WriteLine("Hello, World!");
}</pre>
#### C++ Managed (.Net)
<pre class="toolbar:2 lang:c++ decode:true">#using &lt;mscorlib.dll&gt;

using namespace System;
int wmain(){
	Console::WriteLine("Hello, World!");
}</pre>
#### C#
<pre class="toolbar:2 lang:c# decode:true">class HelloWorldApp{
	static void Main(){
		System.Console.WriteLine("Hello, world!");
	}
}</pre>
#### Caché Server Pages (CSP)
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
#### Caml light
<pre>(* Hello World *)

let hello =
	print_string "Hello World!";
	;;</pre>
#### CCL
<pre> call echo("Hello, world!")</pre>

#### Ceylon
<pre class="toolbar:2 lang:java decode:true ">shared void run() {
    print("Hello, World!");
}</pre>

#### Ch
<pre class=""> printf("Hello, world!\n");</pre>

#### Chapel
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
#### CHILL
<pre class="lang:default decode:true ">Hello:
MODULE

WRITETEXT(STDOUT, "Hello World!%/");

END Hello;</pre>
#### Chuck
<pre class="toolbar:2 lang:c decode:true"> &lt;&lt;&lt;"Hello World"&gt;&gt;&gt;</pre>

#### Chrome
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
#### Cil
<pre>.method public static void Main() cil managed{
	.entrypoint
	.maxstack 8
	ldstr "Hello, World!"
	call void [mscorlib]System.Console::WriteLine(string)
	ret
}</pre>
#### Clarion
<pre>PROGRAM
MAP
END
CODE
MESSAGE('Hello, world!!','Clarion')
RETURN</pre>
#### Clean
<pre>module hello

Start = "Hello, World!"</pre>
#### Clist
<pre>PROC 0
WRITE Hello, World!</pre>
#### Clipper
<pre>? "Hello, World!"</pre>
#### Clu
<pre>start_up = proc ()
	po: stream := stream$primary_output ()
	stream$putl (po, "Hello, World!")
end start_up</pre>

#### Cobol
<pre>IDENTIFICATION DIVISION.
PROGRAM-ID. HELLO-WORLD.

ENVIRONMENT DIVISION.

DATA DIVISION.

PROCEDURE DIVISION.
DISPLAY "Hello, World!".
STOP RUN.</pre>
#### Cocoa or GnuStep (Objective C)
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
#### ColdFusion
<pre class="toolbar:2 lang:xhtml decode:true">&lt;cfoutput&gt;Hello, World!&lt;/cfoutput&gt;</pre>

#### Comal
<pre>PRINT "Hello, World!"</pre>

#### ConTeXt
<pre>\starttext
Hello, world!
\stoptext</pre>
#### Crystal
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
#### Curl
<pre>{curl 3.0, 4.0 applet}
{curl-file-attributes character-encoding = "utf-8"}

Hello, World!</pre>
<!----------------------->

### D Alphabet
<hr>

<p>

#### <a name="Programming_Language_D"></a>D
<pre>import std.stdio ;
void main () {
 writef("Hello, World!");
}</pre>
#### D++
<pre>function main()
{
 screenput "Hello, World!";
}</pre>

#### DarkBasic
```
PRINT "HELLO WORLD"
TEXT 0,0,"Hello, World!"
WAIT KEY
```

#### Dart
<pre class="toolbar:2 lang:go decode:true ">main() {
  print('Hello World!');
}</pre>
#### Dataflex
<pre>/tela
Hello world
/*
clearscreen
page tela</pre>
#### dBase
<pre>* Hello World in dBase IV
? "Hello World!"</pre>
#### DC an arbitrary precision calculator
<pre>[Hello, world!]p</pre>
#### Dcl batch
<pre>$ write sys$output "Hello, World!"</pre>
#### DIV
<pre>PROGRAM hello;
  BEGIN
      write(0, 0, 0, 0, "Hello, world!");
      LOOP
          FRAME;
      END
  END</pre>
#### Delphi, Kylix
<pre>program Hello_World;
uses
	Windows;
	begin
		ShowMessage("Hello, World!");
	end.
</pre>
#### Doll
    <pre>this::operator()
    {
    	import system.cstdio;
    	puts("Hello, World!");
    }</pre>
#### Dream Maker
<pre class="toolbar:2 lang:default decode:true">mob
          Login()
              ..()
              world &lt;&lt; "Hello, world!"</pre>
#### Dylan
<pre>module: hello
        format-out("Hello, world!\n");
</pre>
</p>

### E Alphabet
<hr>
<!------------------------->

#### <a name="Programming_Language_E"></a>EAS 0.0.1.*
<pre>set disp to "Hello, world!"
set dispto to item unit 5 //5 = default screen
release disp into dispto.</pre>
<pre>import system ea.helloworld
wait</pre>
#### Ed and Ex (Ed extended)
<pre>a
hello World!
.
p</pre>
#### Eiffel
<pre>class HELLO_WORLD
    create make
  feature
      make is
      do
          io.put_string("Hello, world!%N")
      end -- make
  end -- class HELLO_WORLD</pre>
#### Elan
<pre>(* Elan *)
putline ("Hello World!");</pre>
#### Elixir
<pre class="lang:erlang decode:true ">iex&gt; IO.puts "Hello World!"</pre>
#### Elm
<pre class="toolbar:2 lang:haskell decode:true ">main =
    text "Hello"</pre>
#### Erlang
<pre>-module(hello).
-export([hello_world/0]).

hello_world() -&gt; io:fwrite("Hello, World!\n").</pre>
#### Euphoria
<pre>puts(1, "Hello, World!")</pre>

<!------------------------->
### F Alphabet
<hr>
<!------------------------->

#### <a name="Programming_Language_F"></a>F#
<pre>print_endline "Hello, World!"</pre>
<pre>printfn "Hello, world!</pre>
#### Factor
<pre>"Hello, World!" print</pre>
#### Ferite
<pre>uses "console";
Console.println("Hello, world!");</pre>
#### filePro
<pre> @once:
     mesgbox "Hello, world!" ; exit</pre>
#### Fjölnir
<pre class="lang:c decode:true">"halló" &lt; main
  {
     main -&gt;
     stef(;)
     stofn
         skrifastreng(;"Halló, veröld!"),
     stofnlok
  }
  *
  "GRUNNUR"
  ;</pre>
#### Focal
<pre>type "Hello, World!",!</pre>
<pre>t "Hello, world!",!</pre>
#### Focus
<pre>-TYPE Hello world</pre>
#### Forte TOOL
<pre>begin TOOL HelloWorld;
    includes Framework;
  HAS PROPERTY IsLibrary = FALSE;
    forward  Hello;
    -- START CLASS DEFINITIONS
    class Hello inherits from Framework.Object
    has public  method Init;
    has property
      shared=(allow=off, override=on);
      transactional=(allow=off, override=on);
      monitored=(allow=off, override=on);
      distributed=(allow=off, override=on);
    end class;  -- END CLASS DEFINITIONS
    -- START METHOD DEFINITIONS
    ------------------------------------------------------------
  method Hello.Init
  begin
  super.Init();
    task.Part.LogMgr.PutLine('Hello, world!');
  end method;
  -- END METHOD DEFINITIONS  HAS PROPERTY
      CompatibilityLevel = 0;
      ProjectType = APPLICATION;
      Restricted = FALSE;
      MultiThreaded = TRUE;
      Internal = FALSE;
      LibraryName = 'hellowor';
      StartingMethod = (class = Hello, method = Init);
    end HelloWorld;</pre>
#### Forth
<pre>: HELLO ( -- ) ." Hello, World!" CR ;
HELLO</pre>
<pre> CR ." Hello, world!" CR</pre>
#### Fortran
<pre> PROGRAM HELLO
	PRINT *, 'Hello, World!'
END</pre>
#### FreeBasic
<pre> PRINT "Hello World"
   SLEEP
   END</pre>
#### Fril
<pre> ?((pp "Hello, World!"))</pre>
#### Frink
<pre>println["Hello, World!"]</pre>
<!------------------------->

### G Alphabet
<hr>

#### <a name="Programming_Language_G"></a>Gambas
<pre>PUBLIC SUB Main()
 Print "Hello, World!"
END</pre>
<pre>PUBLIC SUB Main()
 Message.Info("Hello, World!")
END</pre>
#### Game Maker
<pre>draw_text(x,y,"Hello, world!")</pre>
<pre>show_message("Hello, world!")</pre>
#### GEMBase 4GL
<pre>procedure_form hello
    begin_block world
        print "Hello, world!"
    end_block
end_form</pre>
#### Generate HTML
<pre class="toolbar:2 lang:xhtml decode:true"> &lt;xsl:template match="/"&gt;
 &lt;html&gt;
 &lt;body&gt;
 &lt;h1&gt;Hello, World!&lt;/h1&gt;
 &lt;/body&gt;
 &lt;/html&gt;
 &lt;/xsl:template&gt;</pre>
#### Go Language
<pre class="lang:go decode:true">package main

import "fmt"

func main() {
	fmt.Println("Hello World")
}</pre>
#### GraalScript 1
<pre>if (created){
     echo Hello, world!;
}</pre>
#### GraalScript 2
<pre> function onCreated() {
     echo("Hello, world!");
 }</pre>
#### Groovy
<pre>println "Hello, world!"</pre>
#### Gtk+ in C++
<pre class="toolbar:2 lang:c++ decode:true">#include &lt;iostream&gt;
#include &lt;gtkmm/main.h&gt;
#include &lt;gtkmm/button.h&gt;
#include &lt;gtkmm/window.h&gt;
using namespace std;

class HelloWorld : public Gtk::Window {
public:
 HelloWorld();
 virtual ~HelloWorld();
protected:
 Gtk::Button m_button;
 virtual void on_button_clicked();
};

HelloWorld::HelloWorld()
: m_button("Hello, World!") {
 set_border_width(10);
 m_button.signal_clicked().connect(SigC::slot(*this,
 &amp;HelloWorld::on_button_clicked));
 add(m_button);
 m_button.show();
}

HelloWorld::~HelloWorld() {}

void HelloWorld::on_button_clicked() {
 cout &lt;&lt; "Hello, World!" &lt;&lt; endl;
}

int main (int argc, char *argv[]) {
 Gtk::Main kit(argc, argv);
 HelloWorld helloworld;
 Gtk::Main::run(helloworld);
 return 0;
}</pre>
#### Gtk# in C#
<pre>using Gtk;
using GtkSharp;
using System;

class Hello {

 static void Main()
 {
 Application.Init ();

 Window window = new Window("");
 window.DeleteEvent += cls_evn;
 Button close = new Button ("Hello world");
 close.Clicked += new EventHandler(cls_evn);

 window.Add(close);
 window.ShowAll();

 Application.Run ();

 }

 static void cls_evn(object obj, EventArgs args)
 {
 Application.Quit();
 }

}</pre>

### H Alphabet
<hr>


#### <a name="Programming_Language_H"></a>Haskell
<pre>main = putStrLn "Hello, world!"</pre>
<pre>module Main (main) where

main = putStrLn "Hello, World!"</pre>
#### Hack
<pre class="lang:php decode:true ">&lt;?hh
echo 'Hello World';
</pre>
#### haXe
<pre>class HelloWorldApp
{
      static function main()
      {
          trace("Hello, world!");
      }
}</pre>
#### Heron
<pre>program HelloWorld;
  functions {
    _main() {
      print_string("Hello, world!");
    }
  }
end</pre>
#### HLA (High Level Assembly)
<pre>program helloWorld;
#include("stdlib.hhf")
#begin helloWorld;

 stdout.put( "Hello World" nl );

 end helloWorld;</pre>
#### HP 33s
<pre>LBL H
SF 10
EQN
RCL H
RCL E
RCL L
RCL L
RCL O
R/S
RCL W
RCL O
RCL R
RCL L
RDL D
ENTER
R/S</pre>
#### HP-41, HP-42S
<pre>01 LBLTHELLO
02 THELLO, WORLD
03 PROMPT</pre>
#### Html
<pre class="toolbar:2 lang:xhtml decode:true">&lt;html&gt;
&lt;body&gt;
 Hello, World!
&lt;/body&gt;
&lt;/html&gt;</pre>
#### HTML 4.01 Strict
<pre class="lang:xhtml decode:true">&lt;!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01 Strict//EN" "http://www.w3.org/TR/html4/strict.dtd"&gt;
&lt;html&gt;
&lt;head&gt;
	&lt;meta http-equiv="Content-Type" content="text/html; charset=utf-8"&gt;
	&lt;title&gt;Hello, World!&lt;/title&gt;
&lt;/head&gt;
&lt;body&gt;
	&lt;p&gt;Hello, World!&lt;/p&gt;
&lt;/body&gt;
&lt;/html&gt;</pre>
#### HyperTalk
<pre>put "Hello, World!"</pre>
<pre>Answer "Hello, World!"</pre>

### I Alphabet
<hr>

#### <a name="Programming_Language_I"></a>Icon
<pre># In Icon
rocedure main()
 write("Hello world")
end</pre>
#### IDL
<pre>print,"Hello World!"</pre>
#### Inform 5/6
<pre>[ Main;
 "Hello, World!";
];</pre>
#### Inform 7
<pre>Hello World is a room.  The printed name is "Hello, world!"</pre>
#### Intercal
<pre> IN INTERCAL
 HELLO WORLD</pre>
#### Io
<pre>"Hello, world!" println</pre>
<pre>writeln("Hello, world!")</pre>
#### Iptscrae
<pre>ON ENTER {
 "Hello, " "World!" &amp; SAY
 }</pre>

### J Alphabet
<hr>

#### <a name="Programming_Language_J"></a>J
<pre>'Hello world'</pre>
<pre> 'Hello, world!' NB. echoes the string in interactive mode, doesn't work in script</pre>
<pre> 'Hello World!' 1!:2(2) NB. prints it to (2) - screen, (4) - stdout</pre>
#### Jal
<pre>include 16f877_20
include hd447804
   hd44780_clear
   hd44780 = "H"
   hd44780 = "e"
   hd44780 = "l"
   hd44780 = "l"
   hd44780 = "o"
   hd44780 = " "
   hd44780 = "W"
   hd44780 = "o"
   hd44780 = "r"
   hd44780 = "l"
   hd44780 = "d"
   hd44780 = "!"</pre>
#### Java
<pre>public class HelloWorld
   {
        public static void main(String[] args)
        {
             System.out.println("Hello, world!");
        }
   }</pre>
#### Java byte-code
<pre class="toolbar:2 lang:java decode:true">public class HelloWorld extends java.lang.Object{
  public HelloWorld();
   Code:
    0:   aload_0
    1:   invokespecial   #1; //Method java/lang/Object."&lt;init&gt;":()V
    4:   return  public static void main(java.lang.String[]);
   Code:
    0:   getstatic       #2; //Field java/lang/System.out:Ljava/io/PrintStream;
    3:   ldc     #3; //String Hello, world!
    5:   invokevirtual   #4; //Method java/io/PrintStream.println:(Ljava/lang/String;)V
    8:   return
  }</pre>
#### JavaFX
<pre>Frame {
     title: "Hello World JavaFX"
     width: 200
     content: Label {
        text: "Hello World"
     }
     visible: true
  }</pre>
<pre>var win = new Frame();
  win.title = "Hello World JavaFX";
  win.width = 200;
  var label = new Label();
  label.text = "Hello World";
  win.content = label;
  win.visible = true;</pre>
<pre>import java.lang.System;
System.out.println("Hello World");</pre>
<pre>println("Hello World");</pre>
#### Java Swing
<pre>import javax.swing.JOptionPane;

public class Hello
{
 public static void main(String[] args)
 {
 JOptionPane.showMessageDialog(null, "Hello, World!");
 }
}</pre>
#### Java SWT
<pre>import org.eclipse.swt.SWT;
import org.eclipse.swt.layout.RowLayout;
import org.eclipse.swt.widgets.Display;
import org.eclipse.swt.widgets.Shell;
import org.eclipse.swt.widgets.Label;</pre>
<pre>public class SWTHello {
 public static void main (String [] args) {
 Display display = new Display ();
 final Shell shell = new Shell(display);
 RowLayout layout = new RowLayout();
 layout.justify = true;
 layout.pack = true;
 shell.setLayout(layout);
 shell.setText("Hello, World!");
 Label label = new Label(shell, SWT.CENTER);
 label.setText("Hello, World!");
 shell.pack();
 shell.open ();
 while (!shell.isDisposed ()) {
 if (!display.readAndDispatch ()) display.sleep ();
 }
 display.dispose ();
 }
}</pre>
#### Java applet
<pre class="toolbar:2 lang:xhtml decode:true">&lt;HTML&gt;
&lt;HEAD&gt;
&lt;TITLE&gt;Hello world&lt;/TITLE&gt;
&lt;/HEAD&gt;
&lt;BODY&gt;

HelloWorld Program says:

&lt;APPLET CODE="HelloWorld.class" WIDTH=600 HEIGHT=100&gt;
&lt;/APPLET&gt;

&lt;/BODY&gt;
&lt;/HTML&gt;</pre>
<pre>import java.applet.*;
import java.awt.*;

public class HelloWorld extends Applet {
 public void paint(Graphics g) {
 g.drawString("Hello, World!", 100, 50);
 }
}</pre>
#### JavaScript
<pre>document.writeln('Hello, World!');</pre>
<pre>alert('Hello, world!');</pre>
<pre>print('Hello, world!');</pre>
<pre>WScript.Echo('Hello, world!');</pre>
<pre class="toolbar:2 lang:xhtml decode:true">&lt;a href="#" onclick="helloWorld(); return false;"&gt;Hello World Example&lt;/a&gt;</pre>
<pre class="toolbar:2 lang:xhtml decode:true">&lt;a href="#" onclick="alert('Hello, World!'); return false;"&gt;Hello World Example&lt;/a&gt;</pre>
#### JSP
<pre class="lang:js decode:true"> &lt;% out.println("Hello, world!"); %&gt;</pre>
<pre> Hello, world!</pre>
#### Joy
<pre class="">"Hello, world!\n" putchars .</pre>
#### Julia
<pre class="toolbar:2 lang:python decode:true">julia&gt; println("Hello world!")</pre>

#### Jquery
```
$("body").append("HELLO WORLD!");
```

### K Alphabet
<hr>

#### <a name="Programming_Language_K"></a>K
<pre>`0:"Hello world\n"</pre>
#### Kogut
<pre class="">WriteLine "Hello, World!"</pre>
#### Kotlin
<pre class="toolbar:2 lang:java decode:true">fun main(args: Array&lt;String&gt;) {
  val scope = "world"
  println("Hello, $scope!")
}</pre>
#### KPL (Kids Programming Language)
<pre>Program HelloWorld
     Method Main()
        ShowConsole()
        ConsoleWriteLine("Hello, world!")
     End Method
End Program</pre>

### L Alphabet
<hr>


#### <a name="Programming_Language_L"></a>Lasso
<pre>Output: 'Hello, world!';</pre>
<pre>Output('Hello, world!');</pre>
<pre>'Hello, world!';</pre>
#### LaTeX
<pre>\documentclass{article}
\begin{document}
 Hello, World!
\end{document}</pre>
#### Lexico Mobile (in spanish)
<pre>tarea muestre "Hola mundo !"</pre>
<pre>clase Saludo derivada_de Form
  publicos
  mensajes
  Saludo copie "Hola mundo !" en saludo.Text</pre>
#### Limbo
<pre>implement Command;
    include "sys.m"
      sys: Sys;
    include "draw.m";
    include "sh.m";
    init(nil: ref Draw-&gt;Context, nil: list of string)
  {
      sys = load Sys Sys-&gt;PATH;
      sys-&gt;print("Hello, world!!\n");
  }</pre>
#### Linden Scripting Language
<pre class="toolbar:2 lang:lisp decode:true">default
  {
      state_entry()
      {
          llSetText("Hello, World!" , &lt;0,0,0&gt; , 1.0);
      }
  }</pre>
#### Lingo (Macromedia Director scripting language)
<pre>on exitFrame me
    put "Hello, world!"
end</pre>
#### Linotte
<pre>Livre : HelloWorld
   Paragraphe : Affichage
   Actions :
     "Hello, World !" !</pre>
#### Lisaac
<pre class="toolbar:2 lang:default decode:true">section HEADER
 + name := HELLO_WORLD;
 - category := MACRO;
section INHERIT
 - parent_object:OBJECT := OBJECT;
section PUBLIC
 - make &lt;-
 (
 "Hello World !\n".print;
 );</pre>
 #### Lisp - Common Lisp
<pre class="lang:lisp decode:true">(format t "Hello World!~%")</pre>
<pre class="lang:lisp decode:true">(write-line "Hello World!")</pre>
<pre> "Hello World!"</pre>
#### Lisp - Scheme
<pre>(display "Hello, World!")</pre>
#### Lisp - Emacs Lisp
<pre> (print "Hello, World!")</pre>
#### Lisp - AutoLisp
<pre> (print "Hello, World!")</pre>
#### Lisp - XLisp
<pre> (print "Hello, World!")</pre>
#### Lisp - Arc
<pre>(prn "Hello, world!")</pre>
#### Logo
<pre>print [Hello World!]</pre>
<pre>pr [Hello World!]</pre>
<pre>messagebox [Hi] [Hello, world!</pre>
#### LPC
<pre>void create()
{
       write("Hello, world!\n");
}</pre>
#### Lua
<pre>print "Hello, World!"</pre>
#### LuaPSP
<pre>screen:print(1,1,"Hello, world!")
screen:flip()</pre>

### M Alphabet
<hr>


#### <a name="Programming_Language_M"></a>M (MUMPS)
<pre>W "Hello, world!"</pre>
#### M4
<pre>Hello, World!</pre>
#### Macsyma, Maxima
<pre>print("Hello, World!")$</pre>
#### Maple
<pre>&gt;&gt; print("Hello, World!");</pre>
#### Mathematica
<pre>(* Hello World in Mathematica *)
Print["Hello world"]</pre>
<pre>"Hello, world!"</pre>
#### Matlab
<pre>disp('Hello world')</pre>
<pre>fprintf('Hello, world!')</pre>
#### Maude
<pre>fmod HELLOWORLD is
protecting STRING .
 op helloworld : -&gt; String .
 eq helloworld = "Hello, World." .
endfm
red helloworld .</pre>
#### Max
<pre>max v2;
#N vpatcher 10 59 610 459;
#P message 33 93 63 196617 Hello World!;
#P newex 33 73 45 196617 loadbang;
#P newex 33 111 31 196617 print;
#P connect 1 0 2 0;
#P connect 2 0 0 0;
#P pop;</pre>
#### Maya Embedded Language
<pre>print( "Hello, world!\n" );</pre>
#### Microsoft Foundation Classes (in C++)
<pre class="toolbar:2 lang:c++ decode:true">#include &lt;afx.h&gt;
#include &lt;afxwin.h&gt;
class CHelloWin : public CWnd
{
  protected:
   DECLARE_MESSAGE_MAP()
   afx_msg void OnPaint(void)
   {
   CPaintDC dc(this);
   dc.TextOut(15, 3, TEXT("Hello, world!"), 13);
   }
};
     BEGIN_MESSAGE_MAP(CHelloWin, CWnd)
   ON_WM_PAINT()
  END_MESSAGE_MAP()
     class CHelloApp : public CWinApp
  {
   virtual BOOL InitInstance();
  };
  CHelloApp theApp;
  LPCTSTR wndClass;
     BOOL CHelloApp::InitInstance()
  {
   CWinApp::InitInstance();
   CHelloWin* hello = new CHelloWin();
   m_pMainWnd = hello;
   wndClass = AfxRegisterWndClass(CS_VREDRAW | CS_HREDRAW, 0, (HBRUSH)::GetStockObject(WHITE_BRUSH), 0);
   hello-&gt;CreateEx(0, wndClass, TEXT("Hello MFC"), WS_OVERLAPPEDWINDOW, CW_USEDEFAULT, CW_USEDEFAULT, 120, 50, NULL, NULL);
   hello-&gt;ShowWindow(SW_SHOW);
   hello-&gt;UpdateWindow();
   return TRUE;
  }</pre>
#### mIrc Script
<pre>echo Hello World</pre>
#### Model 204
<pre>BEGIN
PRINT 'Hello, World!'
END</pre>
#### Modula-2
<pre>MODULE Hello;

FROM InOut IMPORT WriteLn, WriteString;

BEGIN
 WriteString ("Hello, World!");
 WriteLn
END Hello.</pre>
#### Moo
<pre>notify(player, "Hello, World!");</pre>
#### Mouse
<pre>"Hello, World!"  $</pre>
#### Ms-Dos batch
<pre>@echo Hello, World!</pre>
#### Muf
<pre>: main
 me @ "Hello, World!" notify
;</pre>

### N Alphabet
<hr>


#### <a name="Programming_Language_N"></a>Natural
<pre>WRITE "Hello, World!"
END</pre>
#### Nemerle
<pre>System.Console.WriteLine("Hello, World!");</pre>
<pre>using System.Console;
    module HelloWorld
    {
       Main():void
       {
          WriteLine("Hello, world!");
       }
    }</pre>
#### NewtonScript
<pre>baseview :=
 {viewBounds: {left: -3, top: 71, right: 138, bottom: 137},
 viewFlags: 581,
 declareSelf: 'base,
 _proto: protoFloatNGo,
 debug: "baseview"
 };

textview := * child of baseview *
 {text: "Hello World!",
 viewBounds: {left: 33, top: 24, right: 113, bottom: 46},
 viewFlags: 579,
 _proto: protoStaticText,
 debug: "textview"
 };</pre>
#### Nice
<pre>void main(String[] args)
{
 println("hello world");
}</pre>
#### NOMAD (4GL)
<pre class="lang:c decode:true ">print "Hello World.";</pre>
#### NSIS
<pre>OutFile "HelloWorld.exe"
Name "Hello, world!"
Caption "Hello, world!"

Section Hello, world!
SectionEnd     

Function .onInit
      MessageBox MB_OK "Hello, world!"
      Quit
FunctionEnd</pre>

### O Alphabet
<hr>


#### <a name="Programming_Language_O"></a>Oberon
<pre>MODULE Hello;
 IMPORT Out;
BEGIN
 Out.String("Hello World!");
 Out.Ln
END Hello.</pre>
#### Object-Oriented C Version
<pre class="toolbar:2 lang:c decode:true">#import &lt;stdio.h&gt;
#import &lt;objc/Object.h&gt;
      @interface Hello : Object  {  }
  - hello;
  @end

      @implementation Hello
  - hello  {
     printf("Hello, world!\n");
  }
  @end
      int main(void)  {
     id obj;
     obj = [Hello new];
     [obj hello];
     [obj free];
     return 0;
  }</pre>
#### OPENSTEP/Cocoa Version
<pre class="toolbar:2 lang:default decode:true">#import &lt;Foundation/Foundation.h&gt;
     int main (int argc, const char * argv[])  {
     NSLog(@"Hello, world!");
     return 0;
  }</pre>
#### OCaml
<pre>print_endline "Hello World!"</pre>
#### Occam
<pre>#USE "course.lib"

PROC hello.world(CHAN OF BYTE screen!)
 out.string("Hello World!*n", 0, screen!)
:</pre>
#### Octave
<pre>printf("Hello World\n");</pre>
#### Opl
<pre>PROC hello:
 PRINT "Hello, world"
ENDP</pre>
#### Ops5
<pre>(object-class request
 ^action)

(startup
 (strategy MEA)
 (make request ^action hello)
)

(rule hello
 (request ^action hello)
 (write |Hello World!| (crlf))
)</pre>
#### Ops83
<pre>module hello (main)
{ procedure main( )
 {
 write() |Hello, World!|, '\n';
 };
};</pre>
#### Oz
<pre>{Browse 'Hello World!'}</pre>

### P Alphabet
<hr>


#### <a name="Programming_Language_P"></a>Parrot assembly language
<pre>print "Hello, World!\n"
end</pre>
#### Parrot intermediate representation
<pre>.sub hello :main
    print "Hello, world!!\n"
  .end</pre>
#### Pascal
<pre>program hello;

begin
writeln('Hello, World!');
end.</pre>
#### PAWN
<pre>main()
 {
      print("Hello World");
 }</pre>
#### Pdf
<pre class="toolbar:2 lang:default decode:true">%PDF-1.0
1 0 obj
&lt;&lt;
/Type /Catalog
/Pages 3 0 R
/Outlines 2 0 R
&gt;&gt;
endobj
2 0 obj
&lt;&lt;
/Type /Outlines
/Count 0
&gt;&gt;
endobj
3 0 obj
&lt;&lt;
/Type /Pages
/Count 1
/Kids [4 0 R]
&gt;&gt;
endobj
4 0 obj
&lt;&lt;
/Type /Page
/Parent 3 0 R
/Resources &lt;&lt; /Font &lt;&lt; /F1 7 0 R &gt;&gt;/ProcSet 6 0 R
&gt;&gt;
/MediaBox [0 0 612 792]
/Contents 5 0 R
&gt;&gt;
endobj
5 0 obj
&lt;&lt; /Length 44 &gt;&gt;
stream
BT
/F1 24 Tf
100 100 Td (Hello World) Tj
ET
endstream
endobj
6 0 obj
[/PDF /Text]
endobj
7 0 obj
&lt;&lt;
/Type /Font
/Subtype /Type1
/Name /F1
/BaseFont /Helvetica
/Encoding /MacRomanEncoding
&gt;&gt;
endobj
xref
0 8
0000000000 65535 f
0000000009 00000 n
0000000074 00000 n
0000000120 00000 n
0000000179 00000 n
0000000322 00000 n
0000000415 00000 n
0000000445 00000 n
trailer
&lt;&lt;
/Size 8
/Root 1 0 R
&gt;&gt;
startxref
553
%%EOF</pre>
#### Perl
<pre># Hello
print "Hello, World!\n";</pre>
#### Perl 6
<pre>say "Hello world";</pre>
#### PHP
<pre class="toolbar:2 lang:php decode:true">&lt;?php
 echo 'Hello, World!';
?&gt;</pre>
<pre class="toolbar:2 lang:php decode:true">&lt;?php
 print 'Hello, World!' . PHP_EOL;
?&gt;</pre>
<pre class="toolbar:2 lang:php decode:true">&lt;?='Hello, World!'?&gt;</pre>
#### Pike
<pre>int main() {
 write("Hello, World!\n");
 return 0;
}</pre>
#### Pilot
<pre>T:Hello, World!</pre>
#### Pl/Sql
<pre>-- start anonymous block
set serveroutput on size 10000000;
begin
 dbms_output.enable(1000000);
 dbms_output.put_line('Hello World!');
end;
-- end anonymous block</pre>
#### Pl/I
<pre>Test: proc options(main) reorder;
 put skip edit('Hello, World!') (a);
end Test;</pre>
#### Pop-11
<pre>'Hello world' =&gt;</pre>
#### PostScript
<pre>(Hello, world!\n) print</pre>
#### Pov-Ray
<pre class="toolbar:2 lang:default decode:true">#include "colors.inc"
camera {
 location &lt;3, 1, -10&gt;
 look_at &lt;3,0,0&gt;
}
light_source { &lt;500,500,-1000&gt; White }
text {
 ttf "timrom.ttf" "Hello World!" 1, 0
 pigment { White }
}</pre>
#### Processing
<pre>println("Hello, world!");</pre>
#### Profan
<pre>' Hello in Profan
cls
print "Hello World!"
waitkey</pre>
#### Progress
<pre>message "Hello World" view-as alert-box.</pre>
#### Prolog
<pre>:- write('Hello world'),nl.</pre>
#### Pure Data
<pre>#N canvas 0 0 300 300 10;
#X obj 100 100 loadbang;
#X msg 100 150 Hello, world!;
#X obj 100 200 print;
#X connect 0 0 1 0;
#X connect 1 0 2 0;</pre>
#### Protocol Buffers
<pre>message hello
{
  required string data = 1 [default="Hello World!"];
}</pre>
#### PureBasic
<pre>; In PureBasic console
OpenConsole()
 ConsoleTitle ("Hello World!")
 PrintN ("Hello World!")
CloseConsole()</pre>
#### Python
<pre>print "Hello, World!"</pre>

### Q Alphabet
<hr>

#### <a name="Programming_Language_Q"></a>Qt toolkit (C++)
<pre class="toolbar:2 lang:c++ decode:true">#include &lt;qapplication.h&gt;
#include &lt;qpushbutton.h&gt;
#include &lt;qwidget.h&gt;
#include &lt;iostream&gt;

class HelloWorld : public QWidget
{
 Q_OBJECT

public:
 HelloWorld();
 virtual ~HelloWorld();
public slots:
 void handleButtonClicked();
 QPushButton *mPushButton;
};

HelloWorld::HelloWorld() :
 QWidget(),
 mPushButton(new QPushButton("Hello, World!", this))
{
 connect(mPushButton, SIGNAL(clicked()), this, SLOT(handleButtonClicked()));
}

HelloWorld::~HelloWorld() {}

void HelloWorld::handleButtonClicked()
{
 std::cout &lt;&lt; "Hello, World!" &lt;&lt; std::endl;
}

int main(int argc, char *argv[])
{
 QApplication app(argc, argv);
 HelloWorld helloWorld;
 app.setMainWidget(&amp;helloWorld);
 helloWorld.show();
 return app.exec();
}</pre>
#### QuakeC
<pre>bprint("Hello World\n");</pre>
#### QuickBasic
<pre>REM Hello World in QuickBASIC
PRINT "Hello World!"
END</pre>

### R Alphabet
<hr>

#### <a name="Programming_Language_R"></a>R
<pre>cat("Hello world\n")</pre>

#### Ratfor
<pre>print *, 'hello, world'
end</pre>

#### RealBasic
<pre>' Hello
msgBox "Hello World!"</pre>

#### Rebol
<pre>print "Hello, World!"</pre>

#### Red
<pre class="toolbar:2 lang:scala decode:true ">Red [
    Title: "Simple hello world script"
]
print "Hello World!"</pre>

#### Refal
<pre class="toolbar:2 lang:default decode:true">$ENTRY GO{=&lt;Prout 'Hello, World!'&gt;;}</pre>

#### Rexx, ARexx, NetRexx, and Object REXX
<pre>say "Hello, World!"</pre>

#### Ring
<pre class="toolbar:2 lang:default decode:true">See "Hello, World!"

Put "Hello, World!"

Load "stdlib.ring"
Print("Hello, World!")</pre>

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
#### Robotic (MegaZeux)
<pre>* "Hello, world!"
end</pre>
#### Rpg
<pre> /FREE
 DSPLY 'Hello, World!';
 *InLR = *On;
 /END-FREE</pre>
<p>Traditional Syntax<span id="ezoic-pub-ad-placeholder-118" class="ezoic-adpicker-ad"></span></p>
<pre> d TestMessage
 c Const( 'Hello, World!' )
 c TestMessage DSPLY
 c EVAL *InLR = *On</pre>

#### Rpg Code
<p>Message Window</p>
<pre>mwin("Hello, World!")
wait()</pre>
<p>On Screen Text</p>
<pre>text(1,1"Hello, World!")
wait()</pre>

#### RPL (HP calculators)
<pre class="toolbar:2 lang:default decode:true">&lt;&lt;
       CLLCD
       "Hello, World!" 1 DISP
       0 WAIT
       DROP
&gt;&gt;</pre>

#### Rsl
<pre>[Hello World!];</pre>
#### RT Assembler
<pre>_name   Hello~World!
pause   Hello~World!
exit         _end</pre>

#### Rtf
<pre>{\rtf1\ansi\deff0
{\fonttbl {\f0 Courier New;}}
\f0\fs20 Hello, World!
}</pre>

#### RTML
<pre><strong>Hello</strong> ()
TEXT "Hello, world!"</pre>

#### Ruby
<pre class="">puts "Hello, World!"</pre>

#### Rust
<pre class="toolbar:2 lang:rust decode:true ">fn main() {
    println!("Hello, world!");
}</pre>

### S Alphabet
<hr>

#### <a name="Programming_Language_S"></a>S
<pre>cat("Hello world\n")</pre>
#### S-Lang
<pre>message("Hello, world!");</pre>
#### Sas
<pre>data _null_;
put 'Hello, World!';
run;</pre>
#### Sather
<pre>class HELLO_WORLD is
 main is
 #OUT+"Hello world\n";
 end;
end;</pre>
#### Scala
<pre>object HelloWorld with Application {
 Console.println("Hello, World!");
}</pre>
#### SCAR
<pre>program HelloWorld;
  begin
   WriteLn('Hello world!');
  end.</pre>
#### Scheme
<pre> (display "Hello world!")
   (newline)</pre>
#### Scriptol
<pre> print "Hello World!"</pre>
#### sed
<pre>sed -ne '1s/.*/Hello, World!/p'</pre>
#### Seed7
<pre>$ include "seed7_05.s7i";

const proc: main is func
 begin
 writeln("Hello, World!");
 end func;</pre>
#### Self
<pre>'Hello, World!' print.</pre>
#### Setl
<pre>-- Hello in Setl2

procedure Hello();
 print "Hello World!";
end Hello;</pre>
#### Simula
<pre>BEGIN
 OutText("Hello, World!");
 OutImage;
END</pre>
#### Smalltalk
<pre>Transcript show: 'Hello, World!'; cr</pre>
#### Smil
<pre class="toolbar:2 lang:xhtml decode:true">&lt;!-- Hello World in SMIL --&gt;
&lt;smil&gt;
 &lt;head&gt;
 &lt;layout&gt;
 &lt;root-layout width="300" height="160" background-color="white"/&gt;
 &lt;region id="text_region" left="115" top="60"/&gt;
 &lt;/layout&gt;
 &lt;/head&gt;
 &lt;body&gt;
 &lt;text src="data:,Hello%20World!" region="text_region"&gt;
 &lt;param name="fontFace" value="Arial"/&gt;
 &lt;/text&gt;
 &lt;/body&gt;
&lt;/smil&gt;</pre>
#### Sml
<pre>print "Hello, World!\n";</pre>
#### Snobol
<pre> OUTPUT = "Hello, World!"
END</pre>
#### ShadowScript
<pre class="toolbar:2 lang:default decode:true">'set up initial variables
  struct.follow
   {
    cpu.fan.speed(500.rpm)
    cpu.max.process(100)
   }
  &lt;
   logic.handle(0)
   int main()
   int var()
   array.max(100000000)
  &gt;
  'open and write the text in a free handle window
  open mainwin(io&lt;std&gt;) as free(1)
   {
    write.free(1).("Hello",&amp;sym," world",&amp;sym)(&amp;sym&lt;","&gt;&amp;sym&lt;"!"&gt;
    apply.free(1) to text
   }
  'reset the fan, cpu, and vars
  &lt;
   logic(std)
   fan(std.auto)
   cpu.max(auto)
   unint main()
   unint var()
   un.array.max(std)
  &gt;
  'end
  end
  .end/</pre>

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
#### Span
<pre class="toolbar:2 lang:c++ decode:true">class Hello {
 static public main: args {
 Console &lt;&lt; "Hello, World!\n";
 }
}</pre>
#### Spark
<pre>with Spark_IO;
--# inherit Spark_IO;
--# main_program;

procedure Hello_World
--# global in out Spark_IO.Outputs;
--# derives Spark_IO.Outputs from Spark_IO.Outputs;
is
begin
 Spark_IO.Put_Line (Spark_IO.Standard_Output, "Hello, World!", 0);
end Hello_World;</pre>
#### Spitbol
<pre> OUTPUT = "Hello, World!"
END</pre>
#### SSPL
<pre>1.0
  print Hello, World!
end</pre>
#### SPSS Syntax
<pre>ECHO "Hello, world!".</pre>

#### Sql
<pre>CREATE TABLE message (text char(15));
INSERT INTO message (text) VALUES ('Hello, World!');
SELECT text FROM message;
DROP TABLE message;</pre>

#### Starlet
<pre>RACINE: HELLO_WORLD.</pre>
<pre>NOTIONS:
HELLO_WORLD : ecrire("Hello, World!").</pre>

#### STATA
<p>Define program in script (.do-file) or at command line:<span id="ezoic-pub-ad-placeholder-120" class="ezoic-adpicker-ad"></span></p>
<pre>   program hello   /*Define Hello, world! program*/
          di "Hello, world!"
     end
       hello  /*run Hello, world! program*/</pre>
<pre>   di "Hello, world!"</pre>

#### SuperCollider
<pre>"Hello World".postln;</pre>

#### Svg
<pre class="toolbar:2 lang:xhtml decode:true">&lt;?xml version="1.0" encoding="utf-8" standalone="no"?&gt;
&lt;svg width="240" height="100" viewBox="0 0 240 100" zoomAndPan="disable"
 xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink"&gt;
 &lt;title&gt;Hello World&lt;/title&gt;
 &lt;g&gt;
 &lt;text x="10" y="50"&gt;Hello World&lt;/text&gt;
 &lt;animate attributeName='opacity' values='0;1' dur='4s' fill='freeze' begin="0s"/&gt;
 &lt;/g&gt;
&lt;/svg&gt;</pre>

#### Swift
<pre class="lang:swift decode:true ">print("hello world")</pre>

### T Alphabet
<hr>

#### <a name="Programming_Language_T"></a>T programming language
<pre>%begin @jump $main
%main.0 @echo %msg
%main.1 @end
%main.count 2
%msg Hello, world!</pre>
#### Tacl
<pre>?TACL HELLO
#OUTPUT Hello, World!</pre>
#### Tcl (Tool command language)
<pre>puts "Hello, World!"</pre>

#### Teco
<pre>!Hello in TECO
FTHello World$</pre>

#### Template Toolkit
<pre>[% GET "Hola mundo!"; %]</pre>

#### TeX
<pre>Hello world
\bye</pre>

#### Ti-Basic
<pre>10 REM Hello World in TI BASIC
20 REM for the TI99 series computer
100 CALL CLEAR
110 PRINT "HELLO WORLD"
120 GOTO 120</pre>

#### Tk
<pre>label .l -text "Hello World!"
pack .l</pre>

#### TOM (rewriting language)
<pre>public class HelloWorld {
   %include { string.tom }
   public final static void main(String[] args) {
     String who = "world";
     %match(String who) {
       "World" -&gt; { System.out.println("Hello, " + who + "!"); }
       _       -&gt; { System.out.println("Don't panic"); }
     }
   }</pre>

#### TSQL
<pre>Declare @Output varchar(16)
Set @Output='Hello, world!'
Select 'Output' = @Output</pre>
<pre>Select 'Hello, world!'
Print 'Hello, world!'</pre>

#### TTCN-3
<pre>module hello_world {
    control {
      log("Hello, world!");
    }
}</pre>

#### Turing
<pre>put "Hello, World!"</pre>

### U Alphabet
<hr>

#### <a name="Programming_Language_U"></a>Ubercode
<pre> Ubercode 1 class Hello
   public function main()
   code
     call Msgbox("Hello", "Hello, world!")
   end function
   end class</pre>
#### Uniface
<pre> message "Hello, world!"</pre>

#### Unix shell
<pre>echo 'Hello, World!'</pre>
<pre>cat &lt;&lt;'DELIM'
Hello, World!
DELIM</pre>
<pre>printf '%s'</pre>

#### UnrealScript
<pre>class HelloHUD extends HudBase;

simulated function DrawHudPassC (Canvas C)
{
 C.SetPos( 0.50*C.ClipX , 0.50*C.ClipY);
 C.DrawText("Hello World!");
}

defaultproperties
{
}</pre>

### V Alphabet
<hr>

#### <a name="Programming_Language_V"></a>Verilog
<pre>module main;

 initial
 begin
 $display("Hello, World");
 $finish ;
 end

 endmodule</pre>
#### VHDL
<pre>use std.textio.all;

ENTITY hello IS
END ENTITY hello;

ARCHITECTURE Scriptol OF hello IS
 CONSTANT message : string := "hello world";
BEGIN
 PROCESS
 variable L: line;
 BEGIN
 write(L, message);
 writeline(output, L);
 wait;
 END PROCESS;
END ARCHITECTURE Scriptol;</pre>
#### Visual Basic Script
<pre>WScript.Echo "Hello, world!"</pre>

#### VBA
<pre>Sub Main()
   MsgBox "Hello, world!"
End Sub</pre>

#### Visual Basic .Net 2003
<pre>Private Sub frmForm_Load(ByVal sender As Object, ByVal e As System.EventArgs) Handles MyBase.Load
 MessageBox.Show("Hello World!", "HELLO WORLD")
 Me.Close()
End Sub</pre>
<pre>Public Class MyApplication
 Shared Sub Main()
 MessageBox.Show("Hello World!", "HELLO WORLD")
 End Sub
End Class</pre>

#### Visual DialogScript
<pre>info Hello world!</pre>

#### Visual Prolog console program
<pre>#include @"pfc\console\console.ph"

goal
 console::init(),
 stdio::write("Hello, World!").</pre>
#### Vms
<pre>$ WRITE SYS$OUTPUT "Hello World!"</pre>

#### Vmrl
<pre>Shape
{
 geometry Text
 {string "Hello World!"}
}</pre>

### W Alphabet
<hr>

#### <a name="Programming_Language_W"></a>Windows API (C Language)
<pre class="toolbar:2 lang:c decode:true">#include &lt;windows.h&gt;
int WINAPI WinMain(HINSTANCE hInst, HINSTANCE hPrevInstance, LPSTR lpCmdLine,
 int nCmdShow)
{
 MessageBox(NULL, "Hello, World!", "", MB_OK);
 return 0;
}</pre>
#### Windows PowerShell
<pre>"Hello, world!"</pre>
<pre>Write-Host "Hello, world!"</pre>
<pre>echo "Hello, world!"</pre>
<pre>[System.Console]::WriteLine("Hello, world!")</pre>
#### Wscript
<pre>WScript.Echo("Hello World!");</pre>

### X Alphabet
<hr>

#### <a name="Programming_Language_X"></a>X++
<pre>class classHello
{
}

static void main(args Args)
{
 dialog dialog;
 dialog = new dialog();
 dialog.addText("Hello World!");
 dialog.run();
}</pre>
#### XAML/WPF
<pre class="toolbar:2 lang:xhtml decode:true">&lt;Page xmlns="http://schemas.microsoft.com/winfx/avalon/2005"&gt;
 &lt;TextBlock&gt;Hello, World!&lt;/TextBlock&gt;
&lt;/Page&gt;</pre>
#### XHTML 1.1
<pre class="toolbar:2 lang:xhtml decode:true">&lt;?xml version="1.0" encoding="UTF-8"?&gt;
&lt;!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.1//EN" "http://www.w3.org/TR/xhtml11/DTD/xhtml11.dtd"&gt;
&lt;html xmlns="http://www.w3.org/1999/xhtml" xml:lang="en"&gt;
 &lt;head&gt;
 &lt;title&gt;Hello&lt;/title&gt;
 &lt;/head&gt;
 &lt;body&gt;
 &lt;p&gt;Hello, World!&lt;/p&gt;
 &lt;/body&gt;
&lt;/html&gt;</pre>
#### XL
<pre>use XL.UI.CONSOLE
WriteLn "Hello, world!"</pre>
<pre>import IO = XL.UI.CONSOLE
IO.WriteLn "Hello, world!"</pre>
#### Xml
<pre class="toolbar:2 lang:xhtml decode:true">&lt;?xml version="1.0" encoding="ISO-8859-1"?&gt;
&lt;?xml-stylesheet type="text/xsl" href="HelloWorld.xsl" ?&gt;
&lt;!-- Hello in XML --&gt;
&lt;text&gt;
&amp;nbsp;&amp;nbsp;&amp;nbsp;&lt;string&gt;Hello, World!&lt;/string&gt;
&lt;/text&gt;</pre>
#### XQuery
<pre>(: Hello with XQuery :)
let $i := "Hello World!"
return $i</pre>
#### XS programming language
<pre class="toolbar:2 lang:xhtml decode:true">&lt;print&gt;Hello, world!&lt;/print&gt;</pre>
#### XSLT
<pre class="toolbar:2 lang:xhtml decode:true">&lt;xsl:template match="/"&gt;
 &lt;xsl:text&gt;Hello, World!&lt;/xsl:text&gt;
&lt;/xsl:template&gt;</pre>
#### XUL
<pre class="toolbar:2 lang:xhtml decode:true">&lt;?xml-stylesheet href="chrome://global/skin" type="text/css" ?&gt;
&lt;window xmlns="http://www.mozilla.org/keymaster/gatekeeper/there.is.only.xul"
 align="center" pack="center" flex="1"&gt;
 &lt;description&gt;Hello, World!&lt;/description&gt;
&lt;/window&gt;</pre>

### Y Alphabet
<hr>

#### <a name="Programming_Language_Y"></a>Yorick
<pre class="toolbar:2 lang:c decode:true">write, "Hello, world!";</pre>

### Z Alphabet
<hr>

<p><a name="Programming_Language_Z"></a></p>

#### Zebra Programming Language (ZPL)
<pre class="toolbar:2 lang:c highlight:0 decode:true">^XA
^LH30,6161
^FO20,10
^ADN,90,50
^FDWikipedia^FS
^XZ
</pre>
#### ZSH
<pre class="toolbar:2 lang:zsh decode:true">print Hello, world!</pre>

### Number and Symbole
<hr>

#### 4DOS Batch
<pre class="toolbar:2 lang:c highlight:0 decode:true"> @echo Hello, world</pre>

#### 4GL
<pre class="toolbar:2 lang:default decode:true">message "Hello, World!" with style = popup;</pre>

#### 4Test
<pre class="toolbar:2 lang:c decode:true">// Hello World in 4Test
testcase printHelloWorld()
    print("Hello World!")</pre>