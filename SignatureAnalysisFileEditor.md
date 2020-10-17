I have written a utility called the Signature Analysis File Editor that allows you to edit the files here and is integrated with Git Hub for downloading and uploading files.

You can download the lastest version from here:

http://forums.arcaderestoration.com/topics/20-Arcade-PCB-Debugger

The software is customizable in the following ways:

1) You can override the Text To Speech file to customize it to your likings.
2) You can override the default Signature File
3) You can override the default Headers.

To override these, you need to copy the approriate file from the application directory to:

Documents\ClassicSoft\SignatureAnalysisFileEditor

The files are:

DefaultSignatureFile.txt

This is just an empty signature file.  For example, you can put your Name in the Author header if you want.

DefaultSignatureHeadersFile.txt

This is the list of headers that are in a signature file.  There are comments in the default file that will give you further instructions. 

ValuesSpeechInfo.txt

This is the file that controls how the text to speech works.  It uses the WC3 Speech Synthesis Markup Language (SSML) to define how it works.
There are 4 substitutions that happen in the file.  {Location}, {Pin}, {Signal} and {Signature}.  These are replaced by the application with the real values for the selected signature line in the grid.
