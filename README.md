# A sample repo to show project hieararchy.

This repo is used to define a project template for a cloud/cloud native project.
The definition is `Java` based but this can be extended for any other type of project.
A Jenkins like build job can switch based on the type of source folder provided. 
This can be a more of a convention than a configuration.

## Structure
```
cloud-native --> project name
├───db --> DB artifacts - likely flyway scripts/SQL files
├───deploy --> Helm files
├───java --> Source code along with Dockerfile
├───monitor --> Any monitoring specific files. Ex: Grafana config.
└───test --> automated tests (example test container based)
```
