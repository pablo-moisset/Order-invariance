# Order-invariance
Experiments based on Thebault and Fontaine

README.TXT
==========

1- System requirements

PC with Linux, Windows or OS X.
MATLAB. No toolboxes are required. The code is simple and should work
on pretty much every version of MATLAB but we have only tested it
using 2019a on Linux Mint v18.3 and OS X v10.15


2- Instalation

Unpack the provided file (ELE_Moisset_Ramos_Soto.tar.gz) in any
user directory. On a Unix-like system this can be done with

tar -xzf ELE_Moisset_Ramos_Soto.tar.gz

This should create a single directory ELE_Moisset_Ramos_Soto/ containing
all the needed files in less than a second.


3- Running the program

To replicate the experiments in the paper simply run main.m (in
ELE_Moisset_Ramos_Soto/) from MATLAB without any parameters.
Parameters used in the paper are already hardwired in the code. Expect a
running time of 1-2 hours. The program should generate the figure in the
paper just before exiting. It will also generate some .mat files with the
numerical data used to generate the figure. For reference, we included
the .mat files you should obtain.


4- Licence related issues

All program files were written by us and are in the public domain with
the exception of tight_subplot.m. This file was obtained from MATLAB central
and is used for formatting the plots. It has no code related to the numerical
experiment itself.


