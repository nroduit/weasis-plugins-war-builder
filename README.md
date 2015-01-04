weasis-plugins-war-builder
==========================

This project is an example to show how to build an extension package 'weasis-ext.war' which contains additional Weasis plug-ins.

'weasis-ext' is the default web context when launching Weasis, using another web context requires to modify the porerty **weasis.ext.url** in [weasis-pacs-connector configuration](https://github.com/nroduit/weasis-pacs-connector/blob/master/src/main/resources/weasis-connector-default.properties): weasis.ext.url=${server.base.url}/weasis-newext  
or adding the code base for plugins (cdb-ext) directly in the URL: http://localhost:8080/weasis-pacs-connector/viewer?patientID=9702672&cdb-ext=http://localhost:8080/plugins/weasis-ext