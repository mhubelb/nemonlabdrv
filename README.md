# nemonlabdrv
general purpose label and barcode generator for Dymo and Brother label makers and printers. Of late it seems that the program calls for both companies have become more difficult to use than necessary and in may cases have poor examples to work with. This addresses many but probably not all uses of these label printers when called by a custom program.

This project was created using visual studio 2022. The executable nemonlabdrv.exe will output instructions at command line level with an argument of ?
The program uses zint.exe to generate the bar codes. This is covered under the "GNU General Public License version 3" license. 

It is expected that any program that uses this utility will call it by "shelling out" and executing the .exe file. No attempt has been made to make a callable library.

At this time the program assumes that the print size (such as label width and length) is set in the windows settings/properties for the specific printer. Future additions may include program control over these.
