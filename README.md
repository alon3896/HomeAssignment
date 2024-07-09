# Take-Home Assignment
## Objective:
Your task is to create a GitHub workflow that will build the code from the home assignment repository https://github.com/AfimilkRnD/HomeAssignment, create a NuGet package, and publish it in the repository as a Release. 
1. The trigger for the workflow action should be a change event in https://github.com/AfimilkRnD/HomeAssignmentTrigger
2. The compiled DLL should have the same version as the nuget package
3. The nuget package should contain the compiled DLL without source code or other build artifact
4. Each time the workflow is triggered, the version of the release the NuGet package and the DLL should be incremented by 1

## Premise:
1. Your team owns the code for HomeAssignment and you can change your clone to fit your needs as long as you don't make changes to the code itself
2. You can not change HomeAssignmentTrigger - it simulates an external repository

## Instructions:
1.	Clone https://github.com/AfimilkRnD/HomeAssignment
2.	Define the workflow in the cloned repository
3.	Push the workflow file to your own repository, using conventional commits for the commit message
## Deliverables:
A link to your cloned repository
