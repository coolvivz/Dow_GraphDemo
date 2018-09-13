# Dow_GraphDemo
Demo Code for consuming Graph workspaces in Calculation Views
The code provided can be cloned directly into your XSA WebIDE. 
Once cloned , you can assign a SPACE for the project and then build it . 
All the tables are built as a part of the project and do no need User provided Services to access Schemas.
Folder Strcuture of the project

Dow_Demo  - MTA Project 
 
    db     - HANA DB module
     
      src   - Folder with source code 
        
        --> graph folder   -- folder holding graph workspace
        --> models folder  -- folder containing calculation views whihc conusmes graph workspace 
             --.cv_graph_pattern.hdbcalculationview   -- Calculation View manipulating pattern matching graphically 
             -- cv_match .hdbcalculationview          -- Calculation View manipulating pattern matching using openCypher
   
     
