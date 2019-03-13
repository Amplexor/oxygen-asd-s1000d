# oXygen framework for ASD S1000D

Provides support in SyncroSoft oXygenXML for working with S1000D files (XML only).

## What is S1000D?

According to https://www.asd-europe.org/s1000d:

> S1000D is an international specification for the procurement and production of technical publications. It is an XML specification for preparing, managing, and using equipment maintenance and operations information. It was initially developed by ASD for use with military aircraft. The specification has since been modified for use with land, sea, and commercial equipment. S1000D is part of the S-Series of ILS specifications.


## How to start

- [ ] Install oXygenXML **Author** (evaluation version can be downloaded on [www.oxygenxml.com](https://www.oxygenxml.com/xml_author.html))
- [ ] Install the oXygen S1000D framework by downloading the ZIP content https://github.com/Amplexor/oxygen-asd-s1000d/archive/master.zip or by cloning the current Github project `git clone https://github.com/Amplexor/oxygen-asd-s1000d.git` 
- [ ] Download the S1000D specifications package, containing schemas at [S1000D Downloads](http://s1000d.org/Downloads/Pages/S1000DDownloads.aspx). Select the issue number you need among 4.0 / 4.1 /4.2.

  Please note the schemas are not embedded in the distribution of the framework; you need to download them (freely) from the above S1000D website. 
- [ ] Copy the schemas (*.xsd files) to the _schemas/S1000D\_4-1/xml\_schema\_flat_ folder. In the specification package, the schemas can be found in the "_XML Schema package\Schemas_" subfolder.  
- [ ] Open (double-click) the asd-s1000d.xpr oXygenXML project. You should now able to author S1000D documents. Sample files are provided in the specification package, in the "_Bike data set_" subfolder.
- [ ] To display the CGM images, you may install the [CGM add-on from oXygenXML](https://www.oxygenxml.com/doc/versions/20.1/ug-editor/topics/cgm-addon.html).

This framework is provided to you by [AMPLEXOR](https://www.amplexor.com).


# Limitations

## Supported versions 

This framework currently supports **authoring** for S1000D 4.0 through 4.2 schemas sets. Publishing is currently not supported.

Authoring of the:

* Data Modules (DM)
* Publication Modules (PM)
* Data Dispatch Notes (DDN)
* Data Modules List (DML)

are currently supported. 

## Warranty

No warranty of any kind is provided. You can however open issues in the [GitHub project]() to report errors, suggest enhancements or evolutions, ask questions.

# Copyright and licence

Copyright (C) 2018-2019 AMPLEXOR

This project is licensed under [Apache License 2.0](LICENSE.txt)

