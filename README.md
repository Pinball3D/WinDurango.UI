# WinDurango.UI
[![Join our Discord](https://img.shields.io/discord/1280176159010848790?color=2c9510&label=WinDurango%20Discord&logo=Discord&logoColor=white)](https://discord.gg/mHN2BgH7MR)
[![View stargazers](https://img.shields.io/github/stars/WinDurango-project/WinDurango.UI)](https://github.com/WinDurango-project/WinDurango.UI/stargazers)   
GUI for WinDurango, which is planned to allow for easy installing/patching among other random stuff I decide lmfao

### NOTICE: A large amount of the codebase has to be rewritten as I was not a good C# dev when this was originally made (statics everywhere, messy fields, etc)
#### Additonally, the translation shit does NOT work at this moment, I cannot figure out why.

> [!NOTE]
> This does nothing more than provide a GUI for easily registering and patching packages with WinDurango.   
> 
# Roadmap

## Features
 - [X] Patching
 - [X] Allow for package removal from UI instead of just completely uninstalling.
 - [X] Installation options
 - [X] Scan for already installed EraOS/XUWP stuff
 - [X] Allow for any existing installed package to be added to the applist
 - [ ] Resize content to fit to screen
 - [ ] Allow for search

## Bugs/Improvements
 - [X] Make the applist not go offscreen (lol)
 - [ ] Once we have enough settings in place, make it have pages using a horizontal NavigationView (probably)
 - [ ] Fix UI load speed when loading a lot of packages on startup
 - [X] Applist scrolling
 - [X] Fix icon in the titlebar
 - [ ] Repo contributors on the about screen
 - [ ] Get Fluent Thin working
 - [ ] Add versioning to the InstalledPackages json (as in versioning the JSON file itself)
 - [ ] Make the Package stuff not rely on UI so much, handle that somewhere else.
 - [X] Fix crash when installation errors
 - [ ] Cleanup, lots and lots of it.
