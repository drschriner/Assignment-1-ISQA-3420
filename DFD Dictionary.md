
#DFD Dictionary

The definitions of all the entities, processes, databases, and data flows used in the DFD. 

 
##Entities: 

+ **Manager:**  The individual responsbile for software packages. 

+ **Developer:**  The individual responsbile for the creation of software packages through coding. 

##Processes: 

+ **Manage Software Package for License Scanning:**  A process that checks for Open Source Software files in software packages.

+ **Scan for Licenses:**  A process that scans for licenses associated to a software package. 

+ **Request Software Package and License:**  A process that retrieves specified information regarding softare packages and licenses upon request from either Developer or Manager. 

+ **Request Software Policy:**  A process that retrieves policy information pertaining to software packages upon request from  either the Developer or Manager.

+ **Create, Review, Modify Software Policy:**  A process that allows the Manager to update software policies to their most current version.

##Databases:

+ **Known Published Vulnerabilities Database:**  Database that is comprised of known vulnerabilities regarding specific software packages. 

+ **Software Package License and Vulnerability Database:**  Database that is comprised of license and vulernability information corresponding to a software package. 

+ **Software Package License and Vulnerability Policy Database:**  Database that is comprised of license and vulnerability information corresponding to a software policy. 


##Data Flow: 

+ **Software Package:**  Collection of software files. 

+ **Name of Software Package:**  The identifying name of a software package. 

+ **Known Vulnerability Issues:**  The known vulerability issues of a software package. 

+ **Software Package License Results:**  License information pertainting to a specfic software package. 

+ **Software Package License and Vulerability Results:**

+ **Queried Software Project Information:**  Desired software project information requested by an entity. 

+ **Specified Software Project Results:**  The requested software project as queired by the entity. 

+ **Queried Software Policy Information:**  Desired software policy information requestd by an entity. 

+ **Specified Software Policy Results:**  The requested software policy as queired by the entity. 

+ **Updated Software Policy:**  The most current version of a software policy after the manager has edited it. 

+ **Confirmation of Updated Software Policy:**  A message that confirms to the manager the Software Package License and Vulnerability Policy Database received the new version of the software policy. 


  
