# History #

Like most pieces of computer software, odslib-python has a history.  Back in 2003 I was teaching English at a private school in Nagoya, Japan.  While teaching there, I became interested in the idea of writing an online gradebook that I could use to keep track of student progress.
I wrote all of the pieces to the gradebook using the Perl programming language.  I decided that the program needed to have a way to export the data into a spreadsheet that I could use with OpenOffice.org.  My only office suite at the time was OpenOffice.org, so naturally, this was the best format to use.

After searching all over the Internet, I decided that the library module I needed did not exist.  I had read that the .sxc file format in use was nothing more than a zipped file containing XML code.  This, I figured, would be easy to create, so I started writing the module and created the ooolib project on Source Forge.

The goal of the project was to have a simple to use library module that would easily create OpenOffice.org documents.

Later, while working on a large massive Perl project, I became frustrated that I could not remember parts of the code I had written.  I had about 10 thousand lines of code and I was getting lost.  I figured there must be a better language out there for large projects.  This is when I discovered the Python programming language.

In 2006, I decided to convert the whole ooolib project from Perl to Python.  Because the code was different, I decided I would call the Python piece ooolib-python.  Also, because of the OASIS standardization of the Open Document Format, OpenOffice.org had changed their file format.  I decided the new Python module would be written to create documents in the new .ods file format.

I continued to make edits to the versions of ooolib-python until about 2008.  I was in graduate school then and did not have the time to work on ooolib-python much.  An additional problem I was running into was that the way I had approached the creation of the documents made it difficult for me to make modifications.  Basically, I just let the project become stale.

In 2010 and 2011, I started really looking at the object oriented side of Python.  This gave me new ideas on how to rewrite the ooolib-python engine.  I tried a few different things, but ran into time constraints, method naming conventions, and backwards compatibility issues that prevented me from making a complete solution.

In 2012, I decided that I would just abandon the old ooolib-python modules and start everything from scratch again.  This turned out to be a good idea since I was then able to use the object oriented nature of Python to my advantage.

As I wrote the new module odslib-python, I took care to make sure it worked with both Python 2 and Python 3.  There are a few places when I had to carefully code pieces so that both interpreters would accept the syntax and work correctly.  I also decided that I was not concerned about the ability to read documents produced, I only wanted to export data.  This allowed me to limit the scope of the project to something I cared about doing.

The odslib-python goal is to have an easy to use module that creates ODS documents and does not require a full installation of OpenOffice.org or LibreOffice to operate.  Anything beyond this is also beyond the scope of this project.  Fortunately, for people wanting that, there is the Python-UNO bridge.