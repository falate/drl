#
#                        8888888b.  8888888b.  888
#                        888  "Y88b 888   Y88b 888
#                        888    888 888    888 888
#                        888    888 888   d88P 888
#                        888    888 8888888P"  888
#                        888    888 888 T88b   888
#                        888  .d88P 888  T88b  888
#                        8888888P"  888   T88b 88888888
#
#                        /----------------------------\
#                        Data  Representation  Language
#                        \----------------------------/
#
#
#                   Designed and developed by Isdite Studio.
#
#--------------------------------------------------------------------------------
#
#  Simple, fast, hierarchical and object-oriented language for
#  processing and storing data.
#
#  C implementation (GNU Make script)
#
#  Version One
#
#  Written by Casper 'Falate' Fałat.
#
#--------------------------------------------------------------------------------
#
#  Copyright © Isdite Studio 2016.
#
#  This software is provided 'as-is', without any express or implied
#  warranty. In no event will the authors be held liable for any damages
#  arising from the use of this software.
#
#  Permission is granted to anyone to use this software for any purpose,
#  including commercial applications, and to alter it and redistribute it
#  freely, subject to the following restrictions:
#
#  1. The origin of this software must not be misrepresented; you must not
#      claim that you wrote the original software. If you use this software
#    in a product, an acknowledgement in the product documentation would be
#    appreciated but is not required.
#  2. Altered source versions must be plainly marked as such, and must not be
#      misrepresented as being the original software.
#  3. This notice may not be removed or altered from any source distribution.
#

CC=gcc # C language compiler.
AR=ar # Static library archiver.
CFLAGS= -Wall -pedantic -std=c99 -Os # C language compiler flags.
LIB=libDRL.a # Output library name.

$(LIB): DRL.o
	$(AR) rc $(LIB) DRL.o

DRL.o:
	$(CC) $(CFLAGS) -I../../ -c ../../DRL.c -o DRL.o
