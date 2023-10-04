## Notes

* Initial configuration to recognise the rules that are to be run on the example.  This involves checking that the SHACL syntax is correct, and then modifying bblock.json to ensure that the path to the rules is valid.  
* setup the examples that will be included in the specification output.  This is done in examples.yaml - either inline or via a reference to a file.  In this case the path is to the examples/example-beef-dataset-and-service.data.ttl
* test the config before committing to the repo
this is done with the Docker command that is in the documentation
* The docker workslow results in a SHACL validation of the data shown in the build/test folder
 