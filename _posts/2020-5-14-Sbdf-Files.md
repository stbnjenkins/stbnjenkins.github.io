---
layout: post
title: "SBDF Files"
tags: ["sbdf", "Spotfire", "java", "C#"]
---

SBDF stands for **Spotfire Binary Data File**, and it is a propietrary binary data format owned by TIBCO that is used to store data tables in TIBCO Spotfire®. That's why the fastest way to load data into TIBCO Spotfire® (and other TIBCO products) is using an SBDF file.

This format defines a table metadata section in which it is also defined the metadata of the columns in the table.
According to the [documentation](https://docs.tibco.com/pub/doc_remote/sfire_dev/area/doc/api/TIB_sfire-analyst_api/html/T_Spotfire_Dxp_Data_Formats_Sbdf_SbdfValueType.htm), each column of the data tables can be either a single value or an array of the following data types:

- Binary
- Boolean
- Currency
- Date
- DateTime
- Integer
- LongInteger
- Real 
- SingleReal
- String
- Time
- TimeSpan

TIBCO offers both a Java and C# library that enables your application to read and write data to the SBDF format. Using these libraries you either add in your application support for these kind of files, or you can use them to improve the loading time of data into tools such as TIBCO Spotfire®.

# References
- [SBDF Library Community Post] (https://community.tibco.com/wiki/tibco-spotfire-sbdf-library)
- [C# SBDF Library](https://tap.tibco.com/storefront/sample-evaluations/tibco-spotfire-c-sbdf-library/prod16137.html)
- [Java SBDF Library](https://tap.tibco.com/storefront/sample-evaluations/tibco-spotfire-java-sbdf-library/prod16138.html)
- [SBDF Namespace documentation](https://docs.tibco.com/pub/doc_remote/sfire_dev/area/doc/api/TIB_sfire-analyst_api/html/N_Spotfire_Dxp_Data_Formats_Sbdf.htm)
