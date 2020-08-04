# Identify the technology options

## Common Business Problems

Business processes modeled in software are often called workflows. Azure includes four different technologies that you can use to build and implement workflows that integrate multiple systems:

- Logic Apps
- Microsoft Power Automate
- WebJobs
- Azure Functions

Inputs > Actions > Conditions > Outputs

## Design First Technologies

Similar to starting with a hand-drawn flow chart

- Logic Apps: Drag and drop blocks + JSON code.
- Power Automate: Drag and drop blocks.
  - AutomatedL Trigger on any event
  - Button: Trigger on button press
  - Scheduled: Trigger on certain time
  - Business Process: Intermediate process

### Comparison

|                                  | Power Automate                               | Logic Apps                                                       |
| -------------------------------- | -------------------------------------------- | ---------------------------------------------------------------- |
| Intended Users                   | Office Workers / Business Analysts           | Devlopers and IT Pros                                            |
| Indtended Scenarios              | Self-service workflow creation               | Advanced integration projects                                    |
| Design Tools                     | GUI only. Browser / mobile apps              | Browser and Visual Studio Designer. Code editing is possible     |
| Application Lifecycle management | Includes testing and production environments | Source code can be included in DevOps and Source control systems |

## Code First Technologies

- WebJobs:
  - Azure App service
  - Continuos
  - Triggered
  - Shell Script (Windows, PowerShell, Bash)
  - PHP, Python, Node.js, Java
- WebJobs SDK:
  - C# / Nuget
- Azure Functions:
  - C#, Java, JavaScript, PowerShell, Python
  - HTTP Trigger
  - Timer Trigger
  - Blob Trigger
  - CosmosDB Trigger

### Comparison

|                                   | Azure Webjobs       | Azure Functions |
| --------------------------------- | ------------------- | --------------- |
| Automatic Scaling                 | []                  | [x]             |
| Development / Testing in Browser  | []                  | [x]             |
| Pay-per-use pricing               | []                  | [x]             |
| Integration with Logic Apps       | []                  | [x]             |
| Package Managers                  | Nuget (Webjobs SDK) | Nuget/NPM       |
| Part of App Service application   | [x]                 | []              |
| Provides close control of JobHost | [x]                 | []              |
