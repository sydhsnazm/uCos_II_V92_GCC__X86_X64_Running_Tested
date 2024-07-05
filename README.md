V2.92.2

> unresolved external symbol __imp__timeGetDevCaps@8

added WinMM.Lib to src
manually add winmm.lib to the project
by copy that library to current project directory
"Microsoft Library"
drive:\msvc\Windows Kits\10\Lib\10.0.26100.0\um\x64\WinMM.lib
build properties linker additional dependencies.


if you dont know how to set path to surrent source i suggest:
Put all sources under one project folder
set search directories compiler path to current project folder
set search directories linker path to current project folder

rebuild all
Enjoy
;)
