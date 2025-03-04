


![pickled logo](/img/pickled-banner.png)

## Description

A simple gherkin editor for the work item form with Gherkin code snippets. This is based on a fork of [Heymega's Pickles](https://marketplace.visualstudio.com/items?itemName=Heymega.Pickles)

## Installation

1. [Add a custom field to inherited process](https://docs.microsoft.com/en-us/azure/devops/organizations/settings/work/add-custom-field?view=azure-devops#add-a-field).

The Field needs to be named **PicklesField** with the type **Text (multiple lines)**.

2. [Add Pickles as a custom control to inherited process](https://docs.microsoft.com/en-us/azure/devops/organizations/settings/work/custom-controls-process?view=azure-devops#add-a-field-level-contribution-or-custom-control)

Then in the options choose the custom field created in previous step.

3. Open the work item page, and the Gherkin editor will be displayed.


## Release notes

### 0.2.3
* First Version from Fork of heymega.pickles - Cope with New Boards Hub
