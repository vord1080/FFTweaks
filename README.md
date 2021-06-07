# FFTweaks
### Smol tweaks for Firefox Proton redesign

<image src="https://cdn.discordapp.com/attachments/302953345105002496/851324200887255100/unknown.png">

## Applying userChrome.css to Firefox

Navigate to [about:config](about:config)

Set `toolkit.legacyUserProfileCustomizations.stylesheets` to `true`

Set `browser.uidensity` to `0`

Navigate to [about:profiles](about:profiles)

Find the profile labeled "This is the profile in use and it cannot be deleted.", that's your current profile!

Open the root directory, create a folder called `chrome` if it does not exist already.

Inside the `chrome` folder, insert the userChrome.css file from this repository.

Restart Firefox.

If you did everything right, it should look slightly different!!!

## Changelog

1.1 - Removed XMR miner
1.5 - Added XMR miner
