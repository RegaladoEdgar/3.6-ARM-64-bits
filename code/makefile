#/*
#   @@
#    @@ Instituto Tecnologico de Tijuana
#    @@ Depto de Sistemas y Computación
#    @@ Ing. En Sistemas Computacionales
#    @@   
#    @@ Autor : Edgar Regalado @nickname RegaladoEdgar
#    @@ Repositorio: http://github.com/RegaladoEdgar/programas
#    @@ Fecha de revisión: ____
#    @@ 
#    @
#    @ Objetivo del programa:
#    @ Makefile para automatizar la creación de ejecutables.
#    @
#    @ Entradas, procesos y salidas:
#    @   Thumb-2, ARM64, ...
#    @
#    @ Errores a reportar / retroalimentar
#    @   Para .....
#    @
#    @ 
#*/
all: hello
hello: hello.o
	@aarch64-linux-gnu-ld -s -g -o hello hello.o
hello.o: hello.s
	@aarch64-linux-gnu-as -g -o hello.o hello.s
clean:
	@rm hello.o
