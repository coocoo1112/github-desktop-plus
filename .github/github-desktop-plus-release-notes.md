GitHub Desktop Plus v3.5.6-alpha5

## **Changes and improvements:**

- **Windows:** GitHub Desktop Plus is now available for installation using **winget**. Thanks @guplem!  
  To install it, simply run the following command in your terminal:  
  ```powershell
  winget install polrivero.GitHubDesktopPlus
  ```

- Allow displaying the **branch name** next to the repository name in the repository list.   Thanks @guplem!  
  - To enable this feature, go to **File > Options > Appearance > "Show current branch name next to repository name"** and select either *"Always"* or *"When it's not the default branch"*.
  - I personally recommend the *"When it's not the default branch"* option, to quickly identify repositories that may have work in progress.
  - Remember that you can right-click any branch in the branch list and select **"Set as default branch"**.

- The "Worktrees" selector has been moved to the left of the branch selector, so the order is now: **Worktrees | Branches | Pull/Push**. Thanks @devxoul!

- Renamed the context menu item "Make the Default Branch" to "Set as Default Branch".

- Improved the error messages when using the "Pull all" button with unpublished branches.

## **Fixes:**

- The package name in Windows has been changed to `GitHubDesktopPlus`, so it should no longer conflict with the official GitHub Desktop app. Now, both apps can be installed and should work without interfering with each other.

- Improved visibility of **unpushed branches** in the branch list by using a higher-contrast color in light mode and using bold text.
