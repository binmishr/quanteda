# quanteda

The details of the codeset and plots are included in the attached Adobe Acrobat reader (.pdf) file in this repository. 
You need to download the same to view the contents. There are referrals to other contents in BLUE colour also to follow.

Currently available corpus sources:
quanteda has a simple and powerful companion package for loading texts: readtext. The main function in this package, readtext(), takes a file or fileset from disk or a URL, and returns a type of data.frame that can be used directly with the corpus() constructor function, to create a quanteda corpus object.

readtext() works on:

text (.txt) files;
comma-separated-value (.csv) files;
XML formatted data;
data from the Facebook API, in JSON format;
data from the Twitter API, in JSON format; and
generic JSON data.
The corpus constructor command corpus() works directly on:

a vector of character objects, for instance that you have already loaded into the workspace using other tools;
a VCorpus corpus object from the tm package.
a data.frame containing a text column and any other document-level metadata.
