#Installation

##Requirements
* A web server
  - A document root (served by the web server) that you own
  - CGIExec permission within that directory
* Perl 5

##Installation
Copy the cruiser script to your web document root:
'''
   cp <cruiser_git_image>/cruiser <document_root>
'''
Make sure that it has world execute permission.
'''
   chmod 755 <document_root>/cruiser
'''
You may also wish to copy the example auxilliary (.@) file as a template for your own.

Open cruiser from a web browser:
'''
   http://myserver/myroot/cruiser
'''

##Troubleshooting

* Check that you can access pages at your document root.
* Ensure that the cruiser script has world execute permission.
* Check that your web server can execute scripts in your document root directory.

##Going Forward
Unless hidden, cruiser will show the subdirectories of each page it formats, so it should be obvious how to add information to your document root.  cruiser consults the .@ file in each directory to format the information there.  

##Documentation
Complete documentation of the auxilliary file commands can be found in the comments at the head of the script itself.

