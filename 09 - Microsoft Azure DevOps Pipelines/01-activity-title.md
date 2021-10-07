# Azure DevOps Pieplines
# Azure DevOps Introduction

### Instructions
- Create a New Azure DevOps Organization
- Create a New Azure DevOps Project and name it whatever you like and mark it as public
- Fork, Import or Push a sample App inside the Repos Section of the newly created Project
- Setup a simple build pipeline with both classic and Yaml pipelines that publishes an artifact called "drop"
- each time a new push to the main branch takes place, both pipelines should automatically run
- give access to the trainer and reviewers to the repos


### Expected deliverables
- Two build pipelines (Classic and Yaml) should be available on the new projects pointing to the imported Projects
- Both pipelines should be succesfully publishing artifacts once new code in the main branch is pushed



### Evaluation

| Metric name | Description | % Value |
| ----------- |-------------| -------:|
| Project Created | Repo should be created sucessfully and should be public  | %20 |
| Repo with sample app imported   | The ADO project should have a demo app available on the Repos Section  | %20 |
| Classic build   | a classic pipeline should be publishing a build artifact from the repo | %20 |
| Yaml Build   | a yaml pipeline should be publishing a build artifact from the repo  | %20 |
| Automatic triggers   | both pipelines should be triggered once new code is available on the main branch  | %20 |
