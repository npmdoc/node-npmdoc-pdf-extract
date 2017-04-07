# api documentation for  [pdf-extract (v1.0.11)](https://github.com/nisaacson/pdf-extract#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-pdf-extract.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-pdf-extract) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-pdf-extract.svg)](https://travis-ci.org/npmdoc/node-npmdoc-pdf-extract)
#### Node PDF is a set of tools that takes in PDF files and converts them to usable formats for data processing. The library supports both extracting text from searchable pdf files as well as performing OCR on pdfs which are just scanned images of text

[![NPM](https://nodei.co/npm/pdf-extract.png?downloads=true)](https://www.npmjs.com/package/pdf-extract)

[![apidoc](https://npmdoc.github.io/node-npmdoc-pdf-extract/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-pdf-extract_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-pdf-extract/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-pdf-extract/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-pdf-extract/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/nisaacson/pdf-extract/issues"
    },
    "dependencies": {
        "async": "~0.1.22",
        "eyespect": "~0.1.8",
        "pathhash": "~1.0.0",
        "rimraf": "~2.0.2",
        "temp": "~0.8.3",
        "walk": "~2.2.1"
    },
    "description": "Node PDF is a set of tools that takes in PDF files and converts them to usable formats for data processing. The library supports both extracting text from searchable pdf files as well as performing OCR on pdfs which are just scanned images of text",
    "devDependencies": {
        "mocha": "~1.8.1",
        "should": "~1.2.1"
    },
    "directories": {},
    "dist": {
        "shasum": "a7617a9a40ba87eba56913cee5b8dadfec2d4881",
        "tarball": "https://registry.npmjs.org/pdf-extract/-/pdf-extract-1.0.11.tgz"
    },
    "engines": "node",
    "folders": "lib",
    "gitHead": "1265cbe36203ff2dcb4dddefa8ebc9dd9abb4c07",
    "homepage": "https://github.com/nisaacson/pdf-extract#readme",
    "main": "main.js",
    "maintainers": [
        {
            "name": "clewfirst",
            "email": "noah@nisaacson.com"
        },
        {
            "name": "nisaacson",
            "email": "noah+npmjs@nisaacson.com"
        }
    ],
    "name": "pdf-extract",
    "optionalDependencies": {},
    "private": false,
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/nisaacson/pdf-extract.git"
    },
    "scripts": {
        "test": "mocha --reporter spec"
    },
    "version": "1.0.11"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module pdf-extract](#apidoc.module.pdf-extract)
1.  [function <span class="apidocSignatureSpan">pdf-extract.</span>electronic ()](#apidoc.element.pdf-extract.electronic)
1.  [function <span class="apidocSignatureSpan">pdf-extract.</span>raw ()](#apidoc.element.pdf-extract.raw)
1.  object <span class="apidocSignatureSpan">pdf-extract.</span>electronic.prototype
1.  object <span class="apidocSignatureSpan">pdf-extract.</span>raw.prototype

#### [module pdf-extract.electronic](#apidoc.module.pdf-extract.electronic)
1.  [function <span class="apidocSignatureSpan">pdf-extract.</span>electronic ()](#apidoc.element.pdf-extract.electronic.electronic)
1.  [function <span class="apidocSignatureSpan">pdf-extract.electronic.</span>super_ ()](#apidoc.element.pdf-extract.electronic.super_)

#### [module pdf-extract.electronic.prototype](#apidoc.module.pdf-extract.electronic.prototype)
1.  [function <span class="apidocSignatureSpan">pdf-extract.electronic.prototype.</span>process (pdf_path, options)](#apidoc.element.pdf-extract.electronic.prototype.process)

#### [module pdf-extract.raw](#apidoc.module.pdf-extract.raw)
1.  [function <span class="apidocSignatureSpan">pdf-extract.</span>raw ()](#apidoc.element.pdf-extract.raw.raw)
1.  [function <span class="apidocSignatureSpan">pdf-extract.raw.</span>super_ ()](#apidoc.element.pdf-extract.raw.super_)

#### [module pdf-extract.raw.prototype](#apidoc.module.pdf-extract.raw.prototype)
1.  [function <span class="apidocSignatureSpan">pdf-extract.raw.prototype.</span>process (pdf_path, options)](#apidoc.element.pdf-extract.raw.prototype.process)



# <a name="apidoc.module.pdf-extract"></a>[module pdf-extract](#apidoc.module.pdf-extract)

#### <a name="apidoc.element.pdf-extract.electronic"></a>[function <span class="apidocSignatureSpan">pdf-extract.</span>electronic ()](#apidoc.element.pdf-extract.electronic)
- description and source-code
```javascript
function Electronic(){
  if(false === (this instanceof Electronic)) {
    return new Electronic();
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdf-extract.raw"></a>[function <span class="apidocSignatureSpan">pdf-extract.</span>raw ()](#apidoc.element.pdf-extract.raw)
- description and source-code
```javascript
function Raw(){
  if(false === (this instanceof Raw)) {
    return new Raw();
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.pdf-extract.electronic"></a>[module pdf-extract.electronic](#apidoc.module.pdf-extract.electronic)

#### <a name="apidoc.element.pdf-extract.electronic.electronic"></a>[function <span class="apidocSignatureSpan">pdf-extract.</span>electronic ()](#apidoc.element.pdf-extract.electronic.electronic)
- description and source-code
```javascript
function Electronic(){
  if(false === (this instanceof Electronic)) {
    return new Electronic();
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdf-extract.electronic.super_"></a>[function <span class="apidocSignatureSpan">pdf-extract.electronic.</span>super_ ()](#apidoc.element.pdf-extract.electronic.super_)
- description and source-code
```javascript
function EventEmitter() {
  EventEmitter.init.call(this);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.pdf-extract.electronic.prototype"></a>[module pdf-extract.electronic.prototype](#apidoc.module.pdf-extract.electronic.prototype)

#### <a name="apidoc.element.pdf-extract.electronic.prototype.process"></a>[function <span class="apidocSignatureSpan">pdf-extract.electronic.prototype.</span>process (pdf_path, options)](#apidoc.element.pdf-extract.electronic.prototype.process)
- description and source-code
```javascript
process = function (pdf_path, options) {
  var self = this;
  var text_pages = [];
  var split_output;
  var single_page_pdf_file_paths = [];
  fs.exists(pdf_path, function (exists) {
    var err;
    if (!exists) {
      err = 'no file exists at the path you specified: ' + pdf_path
      self.emit('error', { error: err, pdf_path: pdf_path});
      return
    }
    pathhash(pdf_path, function (err, hash) {
      if (err) {
        err = 'error hashing file at the path you specified: ' + pdf_path + '. ' + err;
        self.emit('error', { error: err, pdf_path: pdf_path});
        return
      }
      // split the pdf into single page pdf files
      split(pdf_path, function (err, output) {
        if (err) {
          self.emit('error', { error: err, pdf_path: pdf_path});
          return
        }


        if (!output) {
          err = 'failed to split pdf file into distinct pages';
          self.emit('error', { error: err, pdf_path: pdf_path});
          return
        }
        split_output = output;
        if (!split_output.hasOwnProperty('files') || split_output.files.length == 0) {
          err = 'no pages where found in your pdf document';
          self.emit('error', { error: err, pdf_path: pdf_path});
          return
        }
        self.emit('log', 'finished splitting pages for file at path ' + pdf_path);
        var files = split_output.files;
        var index = 0;
        async.forEachSeries(
          files,
          // extract the text for each page
          function (file, cb) {
            index++;
            searchable(file.file_path, options, function (err, extract) {
	          if(err){
	            self.emit('error', { error: err, pdf_path: pdf_path});
	            return;
	          }
              text_pages.push(extract);
              var file_path = file.file_path
              single_page_pdf_file_paths.push(file.file_path);
              self.emit('page', { hash: hash, text: extract, index: index, pdf_path: pdf_path});
              cb();
            });
          },
          function (err) {
            if (!err) {
              self.emit('complete', { hash: hash, text_pages: text_pages, pdf_path: pdf_path, single_page_pdf_file_paths: single_page_pdf_file_paths
});
              return;
            }
            self.emit('error', { error: err, pdf_path: pdf_path});
            if (!split_output || ! split_output.folder) { return }
            fs.exists(split_output.folder, function (exists) {
              if (!exists) { return }
              var remove_cb = function() {}
              rimraf(split_output.folder, remove_cb);
            });
          }
        );
      });
    });
  });
}
```
- example usage
```shell
...
    return cb(err);;
  }
  fs.exists(pdf_path, function (exists) {
    if (!exists) {
      err = 'no file exists at the path you specified';
      return cb(err);
    }
    processor.process(pdf_path, options);
    cb();
  });
  return processor;
}
...
```



# <a name="apidoc.module.pdf-extract.raw"></a>[module pdf-extract.raw](#apidoc.module.pdf-extract.raw)

#### <a name="apidoc.element.pdf-extract.raw.raw"></a>[function <span class="apidocSignatureSpan">pdf-extract.</span>raw ()](#apidoc.element.pdf-extract.raw.raw)
- description and source-code
```javascript
function Raw(){
  if(false === (this instanceof Raw)) {
    return new Raw();
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdf-extract.raw.super_"></a>[function <span class="apidocSignatureSpan">pdf-extract.raw.</span>super_ ()](#apidoc.element.pdf-extract.raw.super_)
- description and source-code
```javascript
function EventEmitter() {
  EventEmitter.init.call(this);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.pdf-extract.raw.prototype"></a>[module pdf-extract.raw.prototype](#apidoc.module.pdf-extract.raw.prototype)

#### <a name="apidoc.element.pdf-extract.raw.prototype.process"></a>[function <span class="apidocSignatureSpan">pdf-extract.raw.prototype.</span>process (pdf_path, options)](#apidoc.element.pdf-extract.raw.prototype.process)
- description and source-code
```javascript
process = function (pdf_path, options) {
  var self = this;
  var text_pages = [];
  var split_output;
  if (!options) {
    options = {};
  }
  // default to removing the single page pdfs after ocr completes
  if (!options.hasOwnProperty('clean')) {
    options.clean = true;
  }
  fs.exists(pdf_path, function (exists) {
    if (!exists) {
      var err = 'no file exists at the path you specified: ' + pdf_path
      self.emit('error', { error: err, pdf_path: pdf_path});
      return
    }
    pathHash(pdf_path, function (err, hash) {
      if (err) {
        err = 'error hashing file at the path you specified: ' + pdf_path + '. ' + err;
        self.emit('error', { error: err, pdf_path: pdf_path});
        return;
      }
      split(pdf_path, function (err, output) {
        if (err) {
          self.emit('error', { error: err, pdf_path: pdf_path});
          return
        }
        if (!output) {
          err = 'no files returned from split';
          self.emit('error', { error: err, pdf_path: pdf_path});
          return;
        }
        self.emit('log', 'finished splitting pages for file at path ' + pdf_path);
        split_output = output;
        var pdf_files = output.files;
        if (!pdf_files || pdf_files.length == 0) {
          err = 'error, no pages where found in your pdf document';
          self.emit('error', { error: err, pdf_path: pdf_path});
          return;
        }
        var index = 0;
        var num_pages = pdf_files.length
        var single_page_pdf_file_paths = [];
        async.forEachSeries(
          pdf_files,
          // extract the text for each page via ocr
          function (pdf_file, cb) {
            var quality = 300;
            if (options.hasOwnProperty('quality') && options.quality) {
              quality = options.quality;
            }
            convert(pdf_file.file_path, quality, function (err, tif_path) {
              var zeroBasedNumPages = num_pages-1;
              self.emit('log', 'converted page to intermediate tiff file, page '+ index+ ' (0-based indexing) of '+ zeroBasedNumPages
);
              if (err) { return cb(err); }
              var ocr_flags = [
                '-psm 6'
              ];
              if (options.ocr_flags) {
                ocr_flags = options.ocr_flags;
              }
              ocr(tif_path, ocr_flags, function (err, extract) {
                fs.unlink(tif_path, function (tif_cleanup_err, reply) {
                  if (tif_cleanup_err) {
                    err += ', error removing temporary tif file: "'+tif_cleanup_err+'"';
                  }
                  if (err) { return cb(err); }
                  var page_number = index+1
                  self.emit('log', 'raw ocr: page ' + index + ' (0-based indexing) of ' +zeroBasedNumPages + ' complete');
                  single_page_pdf_file_paths.push(pdf_file.file_path);
                  self.emit('page', { hash: hash, text: extract, index: index, num_pages: num_pages, pdf_path: pdf_path, single_page_pdf_path
: pdf_file.file_path});
                  text_pages.push(extract);
                  index++;
                  cb();
                });
              });
            });
          }, function (err) {
            if (err) {
              self.emit('error', err);
              return;
            }
            self.emit('complete', { hash: hash, text_pages: text_pages, pdf_path: pdf_path, single_page_pdf_file_paths: single_page_pdf_file_paths
});
          });
      });
    });
  });
}
```
- example usage
```shell
...
    return cb(err);;
  }
  fs.exists(pdf_path, function (exists) {
    if (!exists) {
      err = 'no file exists at the path you specified';
      return cb(err);
    }
    processor.process(pdf_path, options);
    cb();
  });
  return processor;
}
...
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
