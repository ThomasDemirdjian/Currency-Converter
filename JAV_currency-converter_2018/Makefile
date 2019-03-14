##
## EPITECH PROJECT, 2018
## Makefile
## File description:
## makefile
##


all:
	gradle build
	cp build/libs/JAV_currency-converter_2018.jar dist/
	mv dist/JAV_currency-converter_2018.jar dist/currency-converter-1.0.0.jar

build:	all

package:
	gradle assemble

run:
	gradle run

test:
	gradle test

deps:
	gradle dependencies

clean:
	gradle clean

re: 	clean all