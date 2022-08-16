# Vaz Singh's 100DaysOfCloud Day [#3/100]

## What I've done today

You might remember that on [day 1](../001/Readme.md) I hit a brick wall and was only able to complete 5/6 modules. Well, today I had another go at the *Deploy Azure infrastructure by using JSON ARM templates* exercise on the [AZ-104: Prerequisites for Azure administrators](https://docs.microsoft.com/en-us/learn/paths/az-104-administrator-prerequisites/?ns-enrollment-type=Collection&ns-enrollment-id=o547a13rg4kwzz) pathway. 

Thankfully, I was able to complete the exercise. I'm still not sure why I was unable to deploy the template on the first attempt. My theory is that Visual Studio Code and my computer needed a restart!

In this module, I was introduced to Azure Resource Manager templates (ARM templates) and used them to deploy a storage account to Azure. I made the template more flexible by adding parameters and got output from the execution of the template.

**Fun fact:**
>You're limited to 256 parameters in a template. 

I can imagine this exercise being incredibly useful for the [Cloud Resume Challenge](https://cloudresumechallenge.dev/) which I plan to do after these 100 days.

## Learning Outcome

- [x] Implemented an ARM template by using Visual Studio Code.
- [x] Declared resources and added flexibility to your template by adding resources, parameters, and outputs.

**More fun facts:**
>Recall that ARM templates are idempotent, which means you can deploy the template to the same environment again and if nothing was changed in the template, nothing will change in the environment. If a change was made to the template, for example, you changed a parameter value, only that change will be deployed.

## Social Proof

[Twitter - Day #3](https://twitter.com/VazDoesTech/status/1559564749528072192)