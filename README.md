# FPGA-Cat-Box-Signature-Files
This is a repository for Signature Analysis Files that are used with the FPGA Cat Box tool.

Eveyone is welcome to contribute and I have written software that interfaces with this Repository and allows you to edit the Signature Files.

The structure should be:

```
Manufacturer 
     |____ Game Title
               |_____ Signature Files
```               
               
For convenience sake, should use the common name of the manufacturer.  For example, instead of say Atari Games, just use Atari.

If there are multiple versions of a board, I would say create multiple Game Revision directories under the title directory.

For example:
```
  Atari
    |__ Dig Dug
           |__ Rev A
           |__ Rev B
```

If the board has multiple manufacturers such as Dig Dug has an Atari Version and Namco version, please create a Manufacturer specific directory and put the signatures under the approriate one.

For example:
```
  Atari
    |__ Dig Dug
           |__ Rev A
           |__ Rev B
  Namco
    |__ Dig Dug
```    
    
