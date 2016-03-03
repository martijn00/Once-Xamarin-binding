# Once-Xamarin-binding

Xamarin bindings library for the Once android library

For more information on Once see the [Once] github page
## Setup
Plugin is available on [Nuget].

Add to your Xamarin.Droid project
## Usage
First Once needs to be initialised in the OnCreate method:
```sh
Once.Initialise(this);
```
Now you can start using Once
```sh
string showAppTour = "showAppTour"; //unique tag

if (!Once.beenDone(Once.THIS_APP_INSTALL, showAppTour)) {
    Once.markDone(showAppTour);
}
```
For more options please visit the github page: https://github.com/jonfinerty/Once.
### Thanks to
[Jon Finerty] for the original library.
[Martijn van Dijk] for helping with bindings.

[Martijn van Dijk]:<https://github.com/martijn00>
[Nuget]: <https://www.nuget.org/packages/Xam.Plugins.Android.Once/0.5.0>
[Once]: <https://github.com/jonfinerty/Once>
[Jon Finerty]: <https://github.com/jonfinerty>

