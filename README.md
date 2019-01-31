# S1000D Framework for oXygenXML

Provides support in oXygen for working with S100OD files (XML only).

## What is S1000D

According to https://www.asd-europe.org/s1000d:

> S1000D is an international specification for the procurement and production of technical publications. It is an XML specification for preparing, managing, and using equipment maintenance and operations information. It was initially developed by ASD for use with military aircraft. The specification has since been modified for use with land, sea, and commercial equipment. S1000D is part of the S-Series of ILS specifications.


## How to start

- [ ] Install oXygenXML **Author** (evaluation version can be downloaded on https://www.oxygenxml.com/xml_author.html)
- [ ] Clone the current Github project
- [ ] download the package with specifications, schemas at [S1000D Downloads](http://s1000d.org/Downloads/Pages/S1000DDownloads.aspx). Select the issue number you need among 4.0 / 4.1 /4.2.
- [ ] Copy the schemas (xsd files) in the schemas/S1000D\_4-1/xml\_schema_flat folder
- [ ] Open the asd-s1000d.xpr project. You should now able to author S1000D documents.
- [ ] To display the CGM images, you may install the CGM add-on, see https://www.oxygenxml.com/doc/versions/20.1/ug-editor/topics/cgm-addon.html


This framework is provided to you by [AMPLEXOR](https://www.amplexor.com) 


# Limitations

## Supported versions 

This framework currently supports S1000D 4.0 through 4.2 schemas sets.

## Warranty

No warranty of any kind is provided. You can however open issues in the GitHub project to suggest fixes, evolutions, ask questions, report errors.

# Copyright and licence

Copyright (C) 2018-2019 AMPLEXOR

This project is licensed under [Apache License 2.0](LICENSE.txt)

