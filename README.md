website
=======

Web site of the W3C Web and Mobile Interest Group

The homepage is maintained in markdown format, and turned into the actual HTML using pandoc with:
pandoc -o Overview.html -s --template=template.html Overview.md