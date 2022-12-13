# resumebuilder-ui
Creating a resume builder ui with React. 

Main Concept:  
- Previously, I built a resume builder that can create resumes from the terminal. It didn't have a user interface. This project is meant to rectify that. 

Project Layout: 
  - First iteration and features : 
    - Uses my previous original yaml file
    - Able to download the resume
    - Create forms: 
       - Search Tags
       - Name File
  - Architecture 
    - Front-end : React /Javascript
    - Serverless API
         - Routes : 
          - getPDF 
            - Method : POST
            - Keys :
              - Tags
              - Input
              - Output
              - Max Experience
              - Display Project Skills
              - Header Font Size
              - Body Font Size
              - Title Font Size
    - Things to fix: 
      - Convert the yaml file into dynamodb
      - Create a method in resume builder to pull the data from dynamodb