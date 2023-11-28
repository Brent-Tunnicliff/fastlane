# fastlane
Common Fastlane configurations for my projects.

Fastlane documentation found [here](http://docs.fastlane.tools)

## How to use

In the project wanting to reference this, setup fastlane ([Android](http://docs.fastlane.tools/getting-started/android/setup/) or [iOS](http://docs.fastlane.tools/getting-started/ios/setup/)).
Then define the [Fastfile](http://docs.fastlane.tools/advanced/Fastfile/) and add to it `import_from_git(url: 'https://github.com/Brent-Tunnicliff/fastlane')` to reference this project.

Next add the following files for defining additional configurations:

- [Appfile](http://docs.fastlane.tools/advanced/Appfile/): Define information about the project. 
- [Scanfile](http://docs.fastlane.tools/actions/scan/#scanfile): Define information for the tests.
- (iOS only) [Deliverfile](http://docs.fastlane.tools/actions/deliver/): Define release configurations.
- (iOS only) [Gymfile](http://docs.fastlane.tools/actions/gym/#gymfile): Define build configurations.
- (iOS only) [Matchfile](https://docs.fastlane.tools/actions/match/): Define the location for certificates and profiles.
