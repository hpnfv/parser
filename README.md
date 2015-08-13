(c) Copyright [2015] Hewlett-Packard Development Company, L.P.;

Project Parser will help to provide such tooling mechanism, by parsing Telecom operator's 
descriptors/records into TOSCA/CAMP templates and then further translate TOSCA/CAMP templates
into certain s, common templatewhich could be used in IaaS orchestration projects like OpenStack Heat.

The folder structure and corresponding description is as follows:

opnfv 
	parser
		converter/
		README.md
		LINCESE
		

opnfv : Master repository consisting of all the opnfv related content.
parser : Parser will help to provide tooling mechanism to convert YANG to TOSCA.
converter : This foler consists of the modules/classes for the conversion of "YANG to xml" and "xml to TOSCA"
README.md : Brief description of the parser project.
LINCESE : License agreement for the  parser project.