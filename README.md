Makefile rules 

{all: compile project} 
{run: run executable} 
{clean: clean object files and zip/tar} 
{list: list all project's directories and files}
{zip/tar: compress project folder} 
{update: update makefile} 
{readme: generate this readme} 
{create: create project structure} 

{======================} 

{set \'debug=1\' to compile/run in debug mode} 
{set \'IN=*filename*\' to feed a file to the program} 
{set \'OUT=*filename*\' to write program output to designed file} 
{use \'CFLAGS+=*flags*\' to add *flags*} 

{set \'CC=*compiler*\' to change compiler} 
{set \'NAME=*name*\' to set project name} 
{use \'USER_LIBS=*libraries*\' to set user-defined libraries} 
