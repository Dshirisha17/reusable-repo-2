# reusable-repo-2
This repo are used for working on example on the concept of reusable workflows

# Workflow B Overview
Workflow B is a GitHub Actions workflow that is designed to be triggered by another workflow using the workflow_call event. This workflow processes an input message passed from a calling workflow and outputs the message for further use or logging. It runs on a Windows environment and demonstrates the basic functionality of receiving inputs from another workflow.

#### Trigger
Workflow B is triggered by another workflow via the workflow_call event. It accepts an input parameter, input_message, which is passed from the calling workflow.

#### Inputs
input_message: A string input that must be provided by the calling workflow. It is required to execute the workflow
