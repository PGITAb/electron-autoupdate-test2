Working electron autoupdater app.

1) Upon running the APP, it checks if there's a new version.
2) If yes, download it.
3) On closing the app, it will auto install the new version.
4) When starting the app again, it will be updated to new version.

To publish new release, you MUST increment the version in package.json, then run the command `GH_TOKEN=YOUR_TOKEN_HERE npm run deploy`. This publishes a new release under new version number.

Make your own GH_TOKEN here: https://help.github.com/en/github/authenticating-to-github/creating-a-personal-access-token-for-the-command-line
