## Termlex - SNOMED CT API
Termlex is a modular, service oriented API for SNOMED CT

#### Authors
  * Jay Kola, Noesis Informatica

#### Build Status

[![Build Status](http://ci.noesisinformatica.com/buildStatus/icon?job=Termlex)](http://ci.noesisinformatica.com/job/Termlex/)

#### How to use
1. Extract the `Termlex.zip` to a folder where you have read and write permissions.
2. Verify the entries in `snomed-db.properties` to match your MySQL database that contains SNOMED CT data.
3. Set database connection properties in `termlogic-server.properties` for Termlex to store data. You can also edit this file to change the port that Termlex runs on.
4. Start Termlex using the `run.sh` or `run.bat` files in the folder.

### Configuration Folder
Termlex services can be configured using property files. Default values for the services are included in the jar files. However, it is possible to override the default values by providing property files for each of the services. Termlex has a default configuration folder called `config` located in the folder it is extracted.
The following is a list of property files that can be used to configure services:

|File name | Description | Termlex deployment location |
|:------------- |:-------------:|:-----|
snomed-db.properties | Settings to configure the database that contains SNOMED CT data | /opt/termlex/config |
termlogic-server.properties | Settings to configure the port number and database details used by Termlex | /opt/termlex/config |
obj-snomed-db.properties | Settings to configure database that stores Termlex managed local extensions |  /opt/termlex/config |
refset-db.properties | Settings to configure the database that contains refset data |  /opt/termlex/config |

### Looking for source code?
If you are using Termlex, you can access the source code at: [https://gitlab.com/noesisinformatica/termlex] (https://gitlab.com/noesisinformatica/termlex)

### Want to learn how it can be used?
If you'd like to see what Termlex can do, then you can check out [Snolex](https://snolex.com) the SNOMED CT browser and refset manager powered by Termlex.

### Support or Contact
Interested in using Termlex or having trouble with Termlex? You can [contact support](https://noesisinformatica.com/contact/) and we’ll help you sort it out.

Happy Hacking!
