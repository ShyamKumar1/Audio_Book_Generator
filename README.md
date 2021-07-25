# Audio Book Generator
<hr>

### Description:
Reading book sometimes seems booring so let's make a small piece of code to read PDF for us.                   
### Installations:
We need the following packages to read and convert the text to speech from the PDF

`pip install pyttsx3` -> This package helps us to convert the text into speech<br>
`pip install pyPDF3` -> This package helps us to Read, Write and Merge the PDF files

And you can check out the remaining code <a href="https://github.com/ShyamKumar1/Audio_Book_Generator/blob/main/main.py">here</a> 
### Some common errors:
* `Xref table not zero-indexed` if you get this error then include `strict = False` in the PdfFileReader()
* Make sure that the pdf file is in same directory as the project file.
* The PDF should be good so that the code can extract the text from the file
