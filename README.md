

## Local development

### clone warehouse
```bash
git clone https://github.com/KaySar12/1panel-docs.git
```

### Installation dependencies
```bash
CD DOCS
pip install -R Requirements/requirement.txt
```

### Modify the document content

The document structure of this document is defined in the `mkdocs.yml` file, and the specific content of the document is in the` docs` directory.

The content of the document is written in Markdown syntax. If you want to add a new document, you need to add the corresponding chapter navigation in the `nav` in the` mkdocs.yml` file.

### Local debug document
```bash
mkdocs server
```
After executing the above commands, you can view the generated document content through the address of `http://127.0.0.0.0.1: 8000`. When the document is modified, the page content will be updated automatically.

### Construction document
```bash
mkdocs build
```

After executing the above commands, the static file of the document site will be generated in the `site` directory, and the content of the document can be completed on any HTTP server to complete the deployment of the document.

### feedback

If you find an error in the document, or have any questions about the content of the document, submit github issues to the [1panel project's main warehouse] (https://github.com/1panel-dev/1panel/issues))
