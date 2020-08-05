# Analyze the decision criteria

## Chosing a service

![Choice](images\03-service-choice-flow-diagram.png)

### Reasons to choose Design-First

- Non-coders and coders can both use the design tools
- Templates provided for common worflows
- Easier to understand workflow as it is visually defined

### Reasons to choose Code-First

- You have an existing App Service Application that you want to convert to a workflow
- You need to make customizations to `JobHost`
- Developers might prefer working directly in code
- Workflow details need to be hidden from users

## Mixing Technologies

Technologies can be mixed and matched e.g. A custom Azure Fuction can be called from a Power Automate workflow and a Power Automate workflow can be started from a WebJob.
