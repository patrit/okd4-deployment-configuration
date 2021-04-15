# Argo Workflow Templates Playground

## Example Workflows Templates
- whalesay-template
  - hello world
- loop-from-previous-task-template:
  - generate a given number of random data dicts according to the given number
  - spawn a sleep and echo for each of the value dicts

## Start Workflow Template by CLI
```bash
argo submit -n workflow-examples --from WorkflowTemplate/loop-from-previous-task-template -p number=4
```
