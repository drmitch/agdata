## Notes

* Initial configuration to recognise the rules that are to be run on the example.  This involves checking that the SHACL syntax is correct, and then modifying bblock.json to ensure that the path to the rules is valid.  
* setup the examples that will be included in the specification output.  This is done in examples.yaml - either inline or via a reference to a file.  In this case the path is to the examples/example-beef-dataset-and-service.data.ttl
* test the config before committing to the repo
this is done with the Docker command that is in the documentation
* The docker workslow results in a SHACL validation of the data shown in the build/test folder
* Following validation, under the 'tests' folder the example data can be copied/renamed and specified failures can be created to test the SHACL tests, just to be able to confirm that the tests are working.


## The output of this illustration

1.  A dataset is assigned to a DCAT Catalog as a Catalog Item
1.  That dataset is one of a series
1.  The elements of the dataset are described using the Data Structure Definition appropach of the [RDF Data Cube vocabulary](https://www.w3.org/TR/vocab-data-cube) 
1.  SHACL constraints define structure and content profiles specifications
1.  Continuous Integration methods, using software deployed in Docker containers, provides an example of an automation pipeline. 