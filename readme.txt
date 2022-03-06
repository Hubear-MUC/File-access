Attention:

The program opens and closes the file

  d.d

which must be stored in the same directory as the program itself.

If the file  d.d  does not exist, a segmentation fault might happen.

Usually the function  fopen()  returns a NULL- pointer if the file given as
first parameter could not be opened.
However at some implenentations of libc a segmentation fault might happen in
this case.

The program shows

  1
  
on the screen if the file  d.d  exists.

This program is certainly not very useful yet, however the intentions were to test some file access with these little programs as these are at the moment.

