# Renku templates 

this repo includes custom made renku templates.

- python-cuda

## Notes

__folder key vs. id key__

The file ```manifest.yaml``` has the deprecated key ```folder```. The command ```renku template validate``` also generates the warning. But if you create a project with the key ```id```, the key will cause an error, and the project will not be created. So for the time being the deprecated key is used in the file. 


