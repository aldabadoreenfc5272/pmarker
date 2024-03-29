# pmarker
Python package for marking PDF files

## Introduction
pmarker is a Python package for marking PDF files. It allows users to add notes and annotations to PDF documents, making it a useful tool for reviewing, commenting, and collaborating on PDF files. 

pmarker is built on top of the pymupdf package, which provides a range of PDF manipulation capabilities. pmarker is designed to be easy to use and integrate with existing workflows. It can be installed via pip and is compatible with Python 3. 

pmarker support both text and image marking based on the content of the notes, it provide a convenient way to mark up and annotate images in conjunction with notes and other textual content. The package provides four basic marker types: PAR, CTH, Claim, and Example, which can be used to mark different sections of a document. 

One of the major advantages of pmarker is its ability to automatically convert note content into the corresponding positions in a PDF file, without requiring the user to manually specify the exact location of the notes. To use pmarker, you simply need to provide the PDF file you want to mark and a file containing the note content in the required format. The package will then automatically generate a new PDF file with the notes and annotations added. This saves time and effort and makes the process of marking up a PDF file much more efficient and convenient.

Overall, pmarker is a powerful and versatile tool for anyone who needs to mark up and annotate PDF documents, from researchers and academics to business professionals and students.

## Requirements
* pymupdf
* beautifulsoup4
