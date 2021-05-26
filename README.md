# FFTweaks
### smol tweaks for firefox proton redesign

My userChrome.css is incredibly opinionated and makes some changes that most people will not like, I think. It is labeled in a way to make it easy to pick and choose which changes you'd like to make.

## Applying userChrome.css to FireFox

Navigate to [about:config](about:config)

Set `toolkit.legacyUserProfileCustomizations.stylesheets` to `true`

Navigate to [about:profiles](about:profiles)

Find the profile labeled "This is the profile in use and it cannot be deleted.", that's your current profile!

Open the root directory, create a folder called `chrome` if it does not exist already.

Inside the `chrome` folder, insert the userChrome.css file from this repository.

Restart FireFox.

If you did everything right, it should look slightly different!!!
