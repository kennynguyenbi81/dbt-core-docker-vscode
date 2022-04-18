# dbt-core-docker-vscode
This is a repo to create an dbt-core environment with VSCode

Currently, this Dockerfile is used snowflake adapter but you can change to other adapters based on your needs.
At this stage, the initiate project steps are manual as below
- Step 1: create a project folder by using command "mkdir <project_name>"
- Step 2: navigate to new project folder with command "cd <project_name>"
- Step 3: initiate dbt project with command "dbt init" --> then declare all required information, e.g. Snowflake account & development schema
- step 4: Done, now you can start developing your dbt project
