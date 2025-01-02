# Notion Desktop

Notion Desktop is a cross-platform desktop application that allows you to use Notion directly on your computer, making it easier to chat with friends and family while working.

![Image](https://github.com/levicm/notion-desktop/blob/main/screenshots/notion-desktop.jpeg)

## 🛠 **Features**

- **Full Notion Functionality**: Access all Notion features in a dedicated desktop app.
- **Single Instance**: Ensures only one instance of the app runs at a time.
- **Custom User-Agent**: Enhanced compatibility with Notion Web.
- **Window Management**: Automatically maximizes on startup for better visibility.
- **Google Sign-In Support**: Login via Google is supported with external browser fallback for security.
- **Popup Handling**: Popups are allowed to ensure smooth navigation and interactions.

---

![Image](https://github.com/levicm/notion-desktop/blob/main/screenshots/image1.png)

## 📦 **Installation**

### Build From Source

1. **Clone the repository**:

```bash
git clone https://github.com/levicm/notion-desktop.git
cd Notion-desktop
```

2. **Install dependencies**: Ensure that you have all the necessary dependencies installed.

```bash
   npm instal
```

3. Start the application:

```bash
npm start
```

4. **Build the application**: Run the following command to create a AppImage package of the application.

```bash
npm run dist
```

5. **Change to the dist directory**: Navigate to the dist directory where the AppImage package is located.

```bash
cd dist
```

6. **Make it executable**: Use the following command to make it executable.

```bash
chmod +x ./Notion-desktop_1.0.3_amd64.AppImage 
```

## ↩️ **Uninstallation Steps**

Since the software is never installed, there is no need to ‘uninstall’ it. Just delete the associated AppImage file and your software is removed from the system.

If you integrated the AppImage through AppImage Launcher (as [Gear Lever](https://github.com/mijorus/gearlever)), you can right-click on the application and select Remove AppImage from the system option.

## 📖 **Usage Instructions**

### **Launching the App**:

   Once you have made the AppImage file executable, just double-click on it to run it, or execute :

```bash
   ./Notion-desktop_1.0.3_amd64.AppImage
```

## 🤝 **Contributing**

Contributions are welcome! If you'd like to contribute to this project, please fork the repository and submit a pull request.

## 📜 **License**

This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for details.

## Acknowledgments

- **Electron** - Framework used to build the application.
- **Notion** - A new tool that blends your everyday work apps into one. It's the all-in-one workspace for you and your team.
