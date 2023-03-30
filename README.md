# juce_audio_devices
This is a `git subtree split` of the `juce_audio_devices` module from the JUCE project. This split was made in order to make it easier to maintain a custom version of this module in a separate repository while being able to pull updates from upstream project. Other than the addition of this README.md file, no changes have been made to contents of the module.

## How was this subtree split created?
This subtree was created by running the command `git subtree split --prefix modules/juce_audio_devices --annotate='(split) ' --rejoin --squash --branch juce_audio_devices` on the `master` branch.