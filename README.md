# github_actions_assignment
---------------------------
Solution of the hands on lab for Github Action Workshop

### 02-Runners
---------------------------------------------------
Solution- Go to repository settings > Action > Runners > New self-hosted runner. 

Now Choose Runner Image According to your OS , Select Architecture. It will provide you the steps to configure self-hosted Runner.

### 03-Github Workflow
----------------------
Creating a first action hello-world.yaml in ```.github/workflows``` directory
- Added jobs my-job which runs on ubuntu-latest 
- Added steps my-step to echo "Hello world Today is Monday"
- Added Event to trigger ```on: push```

### 04-Environment variables
----------------------------
Added env variable and Using the env inside the run.
```
env:
  DAY_OF_WEEK: Monday
```
