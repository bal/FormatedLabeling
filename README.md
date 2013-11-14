FormatedLabeling
================

An ArcGIS labelling script that uses VB to label concatenated numbers.

This script is designed to label Baltimore County's SimConFirstDivision layer, which represents plats in GIS. The purpose of the label is to format the `FirstDivisionID` in a stylized way. The `FirstDivisionID` is a concatenation of the three digit book and page of the recorded plat, padding any one or two digit numbers with zeroes. So *Book 19 Page 312* would become `019312`. This script is really just a label expression to expand those identifiers into something that makes sense on a map.
