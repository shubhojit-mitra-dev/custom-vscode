# Instructions

**NOTE:** Please take time to read the short documentation of **"Custom CSS and JS Loader"** for some useful tips for various operating systems to avoid issues regarding the changes not taking effect.

1. Install "Custom CSS and JS Loader" VS Code Extension.
2. Copy the contents of settings.json to your VS Code's settings.json (warning: it will overwrite your settings).
3. Add `vscode_custom_css.imports` array to your settings.json file:
```
"vscode_custom_css.imports": [
    // Absolute file paths for your css/js files
    // For Mac or Linux
    // "file:///Users/your-user-name/custom-vscode.css",
    // "file:///Users/your-user-name/custom-vscode-script.js"

    // For Windows
    // "file:///C:/path-of-custom-css/custom-vscode.css",
    // "file:///C:/path-of-custom-css/custom-vscode-script.js"
],
```
4. You might need to take ownership of the CSS/JS files you made or run VS Code with admin privileges on certain operating system:
```
Mac and Linux users
The extension would NOT work if Visual Studio Code cannot modify itself. The cases include:

Code files being read-only, like on a read-only file system or,
Code is not started with the permissions to modify itself.
You need to claim ownership on Visual Studio Code's installation directory, by running this command:

Note: Replace /usr/share/code where your VS Code is installed.
sudo chown -R your-user-name /usr/share/code
```
5. Enable "Custom CSS and JS Loader" from VS Code's command dialog.
6. Customize the css or js from this repo to make it look the way you want to, or even better, explore areas of VS Code that you want to customize.
7. After making some changes, reload the extension (Reload Custom CSS and JS) from VS Code's command dialog.

## PREVIEW

![Screenshot from 2024-12-16 14-53-55](https://github.com/user-attachments/assets/2cb91f85-6043-47d1-8b45-a434c8cbd197)
![Screenshot from 2024-12-16 14-55-47](https://github.com/user-attachments/assets/4502c16f-2a59-489e-a344-e7be9660c407)
![Screenshot from 2024-12-16 15-01-10](https://github.com/user-attachments/assets/de63e90f-5af5-4283-ad2d-8ef0d487d97e)
![Screenshot from 2024-12-16 15-01-49](https://github.com/user-attachments/assets/346d4028-60d7-43a5-b94e-11bea75b5820)




