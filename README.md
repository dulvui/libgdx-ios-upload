# ARCHIVED
This action has been archived and will no longer be maintained.
Please create your own fork.

# libgdx-ios-upload
Github Action to upload an iOS libGDX application to Testflight.  
If you are facing problems with the action or this README feels uncomplete, pull requests are welcome or open an issue.

## Table of contents
- [libgdx-ios-upload](#libgdx-ios-upload)
  - [Table of contents](#table-of-contents)
  - [Requirements](#requirements)
  - [Parameters](#parameters)
  - [Working examples](#working-examples)
  - [License](#license)
## Requirements
 - Apple Developer Account
 - libGDX Project with iOS module
 - Apple Developer Certificate and Provision Profile

Note: Its recommended to create a Apple Developer service account to use a separate user/password to upload.

## Parameters
| key | required | default | description |
| ----|----------|---------|-------------|
| apple-id-username | true |   | Service account username |
| apple-id-password | true |   | Service account password |
| working-directory | false | . | Path to the project |

## Working examples
You an find a working examples here:  
https://github.com/dulvui/sn4ke/blob/main/.github/workflows/upload-ios.yml

## License
This software is licensed under the [MIT license](LICENSE).
