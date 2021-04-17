# API Testing Using Postman
This Project Demonstrates API Testing . API tested in this project includes different HTTP request create , update, delete , get , post . test can be executed using postman collection runner and newman

# Prerequisite

1. Node.js installed
2. Newman Package installed

# Command to execute testcase using cmd

```
newman run CONTACTAPI.postman_collection.json -e CONTACTAPI.postman_environment.json
```

# Installing Reporter Package for generating simple and advance HTML reports

install -g newman-reporter-html      ( simple reports without formatting )

install -g newman-reporter-htmlextra ( advance html reports with formatting )

# Execution of testcase for report generation

newman run CONTACTAPI.postman_collection.json -e CONTACTAPI.postman_environment.json -r html    ( simple html report is generated with folder name newman )

newman run CONTACTAPI.postman_collection.json -e CONTACTAPI.postman_environment.json -r htmlextra  ( advance html report is generated with folder name newman )


