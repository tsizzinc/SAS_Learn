# SAS_Learn
%LET OutPath=C:\Users\tliu1\Documents\Work\;

OPTIONS DLCREATEDIR; /*This option allows nonexisting folders to be created*/

LIBNAME newdir "&OutPath";

LIBNAME res ("&OutPath.trying", "&OutPath.trying/something"); /*Here to define folders and subfolders*/
LIBNAME res clear; /*Bro you dont need no LIBNAME res stored*/
