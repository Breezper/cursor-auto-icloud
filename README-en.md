# Cursor Pro (iCloud) Automation Tool

⭐️ Star us on GitHub — it motivates us a lot!

[中文 README](README.md)

## Table of Contents

- [Prepare](#prepare)
- [Download](#download)
- [Setting up](#setting-up)
- [Running the tool](#running-the-tool)
- [Disclaimer](#disclaimer)
- [Credits](#credits)
- [Contributing](#contributing)
- [License](#license)

## Prepare

You should have following items before using this tool:

- An apple account with **iCloud Plus**

## Download

1. Download the latest version from GitHub Releases
2. Choose the version according to your system:

> Windows: Download CursorKeepAlive.exe directly
> Mac (Intel): Choose x64 version
> Mac (M series): Choose ARM64(aarch64) version

### Additional Steps for Mac Users

> Open Terminal, navigate to the application directory
> Execute the following command to make the file executable:
> ```chmod +x ./CursorKeepAlive```

Follow the setup instructions below, then run the tool.

## Setting up

### Setting up environment variables

> Mac User: If you are not able to rename the file, you can use `touch .env` to create the file in the same directory as executable file.

1. Download `.env.example` file and rename it to `.env`
2. Fill in the `.env` file

```env
ICLOUD_USER=your_apple_id (!!! without @icloud.com)
ICLOUD_APP_PASSWORD=your_apple_id_app_specific_password (explained below)
ICLOUD_COOKIES=your_icloud_cookies (explained below)
```

### Getting iCloud cookie string

1. Download [Cookie-Editor](https://chromewebstore.google.com/detail/cookie-editor/hlkenndednhfkekhgcdicdfddnkalmdm) Chrome extension
2. Navigate to [iCloud settings](https://www.icloud.com/settings/) in your browser and log in
3. Click on the Cookie-Editor extension and export cookies with `Header String` format
4. Paste the exported cookies into a file named `.env` as `ICLOUD_COOKIES`

### Getting Apple ID App Specific Password

1. Sign in to your Apple Account on [account.apple.com](https://account.apple.com)
2. In the Sign-In and Security section, select App-Specific Passwords.
3. Select Generate an app-specific password, then follow the steps on your screen.
4. Copy the generated password and paste it into a file named `.env` as `ICLOUD_APP_PASSWORD`

## Running the tool

### Windows User

Double-click the executable file to run the tool.

### Mac User

1. Open Terminal
2. Navigate to the directory where the executable file is located
3. `./CursorKeepAlive`

### Please press `4` to start the automation 

## Disclaimer

This project is created solely for educational purposes. The author(s) do not assume any responsibility or liability for:

- Any misuse of the code or related materials.
- Any damages or legal implications arising from the use of this project.
- The accuracy, completeness, or usefulness of the provided content.

By using this project, you agree that you are doing so at your own risk. This project is not intended for use in production environments, and no warranties or guarantees are provided.
If you have any legal or ethical concerns, please refrain from using this repository.

## Credits

This project can't be done without the help of these amazing projects:

- [cursor-auto-free](https://github.com/chengazhen/cursor-auto-free)
- [go-cursor-help](https://github.com/yuaotian/go-cursor-help)

## Contributing

If you want to contribute to this project, please feel free to open a pull request.

## License

This product is distributed under a proprietary license. You can review the full license agreement at the following link: [CC BY-NC-ND 4.0](https://creativecommons.org/licenses/by-nc-nd/4.0/).
