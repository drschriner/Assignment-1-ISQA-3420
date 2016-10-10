*Three Use Cases:*

##1)  Title:  Determine License and Vulnerability Information 

**Primary Actor:**  Manager

**Goal in Context:**  The manager is able to determine license and vulernability information from provided project information. 

**Stakeholders:** 

+ *Manager:* To receive clear and relevant Open Source Software license and vulnerability package information. 

+ *Developer:* To provide the relevant file/package level information.

**Preconditions:** 

+ Relevant file/package information is in the Known Vulnerability Issue Database

+ Software package license and vulnerability information is up to date 

+ Scanner provides accurate Open Source Software license information

**Main Success Scenario:**  Manager receives accurate and valid license and vulnerability information for the requested project packages.

**Failed End Conditions:**  Manager receives inaccurate or invalid license and vulnerability information for the requested project packages.

**Trigger:**  Manager uploads or identifies project information to which license and vulnerability information is provided. 

  ------------------------------------------------------------------------------------------------------------------

##2)  Title:  Determine Software Policies for Respective Software Package

**Primary Actor:**  Manager

**Goal in Context:**  The manager is able to obtain Open Source Software policies for a given software project. 

**Stakeholders:** 

+ *Corporate Manager:* To receive clear and relevant Open Source Software policy information corresponding to a software project.

+ *Corporate Developer:* To provide the relevant file/package level information.

**Preconditions:** 

+ Relevant file/package information is in the Software Package License and Vulnerability Policy Database

+ Scanner provides accurate Open Source Software license information

+ Known Published Vulnerabilites Database and Software Package License and Vulnerability Database are up to date

**Main Success Scenario:**  Manager obtains accurate and valid software policy for requested software package.

**Failed End Conditions:**  Manager receives inaccurate or invalid software policies upon requested software package.

**Trigger:**  Manager has access to modify software policies for any requested software package.

  ------------------------------------------------------------------------------------------------------------------

##3)  Title:  Review / Modify Software Policies for Software Package

**Primary Actor:**  Manager

**Goal in Context:**  The manager is able to create or update Open Source Software policies for a given software package.

**Stakeholders:** 

+ *Corporate Manager:* To receive, modify, or change Open Source Software policy information corresponding to a software project.

**Preconditions:** 

+ Relevant file/package information is in the Software Package License and Vulnerability Policy Database

+ Manager is able to retreive most current version of software policy upon request 

**Main Success Scenario:**  Corporate manager is able to create or update Open Source Software policy to their most current version. 

**Failed End Conditions:**  The corporate manger's created or updated Open Source Software policy does not make it to the Software Package License and Vulnerability Policy database.

**Trigger:**  Corporate manager has ability to modify or create software policies to push a software pacakge through.
