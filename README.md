# SeceditDSC
A wrapper around secedit.exe to allow you to confiugre local security policies.  This resouce requires a Windows OS with secedit.exe.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

## How to Contribute
If you would like to contribute to this repository, please read the DSC Resource Kit [contributing guidelines](https://github.com/PowerShell/DscResource.Kit/blob/master/CONTRIBUTING.md).

## Resources
*  **xUserRightsAssignment** configures user rights assignments in local security policies.

## xUserRightsAssignment
* **Policy**: The policy name of the user right assignment to be configured.
* **Identity**: The identity of the user or group to be added or removed from the user right assignment.

## Unreleased

## Versions
1.0.0.0
* Initial release with the following resource:
 * xUserRightsAssignment
