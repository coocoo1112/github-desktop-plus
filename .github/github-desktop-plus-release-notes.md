GitHub Desktop Plus v3.5.7-beta3

Upstream: [GitHub Desktop 3.5.7-beta3 release notes](https://github.com/desktop/desktop/releases/tag/release-3.5.7-beta3)

## **Changes and improvements:**

- We now support **multiple app windows**! To use them, either select **File > Open new window**, use the keyboard shortcut `Ctrl+Alt+N` (`Cmd+Option+N` on macOS), or right-click on a repository in the repo list and select **Open repository in new window**. Thank you @hewigovens!

- Allow users to hide the "Compare" tab in the commit list.  
  While I wouldn't recommend hiding it, if all your repositories have a single branch or you just never use this feature, you can now remove it in **File > Options > Appearance**.


## **Fixes:**

- Fixed a crash when attempting to add a repository with an SSH remote URL that doesn't start with `git@`. Thank you @coocoo1112!

- Fixed a problem in the welcome flow where the text in the Enterprise URL textbox appeared reversed. Thank you @coocoo1112!

- Fixed the infamous *"cannot read property 'path' of undefined"* error when launching the terminal (Ctrl+`) without configuring a terminal first.
