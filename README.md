# y86_processor_logism

I DID NOT CREATE THE PYTHON FILE THAT CONVERTS .yo files to .mem!!!

My implementation of the y86 processor architecture using the Logisim software. Included are the logisim circuit file, object code, memory images to be loaded into Logisim, and a python file that converts object code into memory images. 

To convert from object code to memory image, run the following command in the directory containing yo2mem.py and the object code:

python3 yo2mem.py file-name.yo file-namegit .mem

A memory image file (.mem) should now be created.

To load this into the logisim ROM module, simply right click the module and press the load image file and choose the created
.mem file.

A few programs have already been created in this repository to test.
