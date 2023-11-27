# fastlane
Common Fastlane configurations for my projects.

Fastlane documentation found [here](http://docs.fastlane.tools)

## How to use

In the project wanting to reference this, setup fastlane ([Android](http://docs.fastlane.tools/getting-started/android/setup/) or [iOS](http://docs.fastlane.tools/getting-started/ios/setup/)) and the following files:
- [Appfile](http://docs.fastlane.tools/advanced/Appfile/): Define information about the project. 
- [Fastfile](http://docs.fastlane.tools/advanced/Fastfile/): Define `import_from_git(url: 'https://github.com/Brent-Tunnicliff/fastlane')` to reference this project.
- [Scanfile](http://docs.fastlane.tools/actions/scan/#scanfile): Define information for the tests.
- (iOS only) [Gymfile](): Define build configurations.
