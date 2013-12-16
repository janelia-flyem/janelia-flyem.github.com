## Media Types for Janelia Service API

This repository holds descriptions of each non-standard Media Type (formerly known as MIME types)
supported by Janelia service APIs.  

### Contents

This repository contains files with a *{schema}.json* in JSON schema format, each describing
a different supported media type.  There are also *{schema}-example.json* that gives an example
implementation of the corresonding schema.

### Defining a custom media type

Please consult examples in this repository and follow instructions on how to create
a JSON schema at [json-schema.org](http://www.json-schema.org).  JSON schema allows
one to specify the validation and format of a JSON file.

The media type for JSONs that follow this schema should be **application/schema+json**

JSON schema is language neutral and there are several tools out there that will validate
a JSON file against the supplied schema.  JSON schema can also transform JSON into
hypertext by supporting URI links.

An example of an online schema validator:
[example](http://json-schema-validator.herokuapp.com/).
