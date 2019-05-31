# Australian Primary Care Practice-to-Practice Record Transfer IG

This project contains all the files necessary to generate the Implementation Guide for the primary care data technical project 
(a.k.a project 2). 

Currently the IG Publisher cannot be configured to change the terminology service. That means you can't configure the web
service or the IG Publisher jar when running locally.

We have a modified version of the IG Publisher jar that allows you to specify an alternative terminology service.

Example usage:

java -jar org.hl7.fhir.igpublisher.ontoserver.jar -ig <directory containging ig.json control file>/ig.json" -tx https://primarycare.ontoserver.csiro.au/fhir


