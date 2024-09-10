This repository stores the official documentation of the 1Panel project , which is built using the Material for MkDocs theme under the MkDocs documentation framework.

Local Development
Clone this repository
git clone https://github.com/1Panel-dev/docs.git
Install Dependencies
cd docs
pip install -r requirements/requirements.txt
Modify document content
The document structure of this document is defined in mkdocs.ymlthe file, and the specific contents of the document are in docsthe directory.

The document content is written in markdown syntax. If you want to add a new document, you need to first add the corresponding chapter navigation in the part mkdocs.ymlof the file .nav

Local debugging documentation
mkdocs serve
After executing the above command, you can http://127.0.0.1:8000view the generated document content through the address. When the document is modified, the page content will be automatically updated.

Building Documentation
mkdocs build
After executing the above command, sitestatic files of the document site will be generated in the directory. Copy the contents in the directory to any HTTP server to complete the deployment of the document.

Question Feedback
If you find errors in the documentation or have questions about the content, please submit a GitHub Issue to the main repository of the 1Panel project.
