# My Office Add-in

![Screenshot](docs/screenshot.png?raw=true "Screenshot")

## Running

```bash
$ npm run dev-server
> office-addin-taskpane-angular@0.0.1 dev-server
> webpack-dev-server --mode development

You already have trusted access to https://localhost.
Certificate: /Users/user/.office-addin-dev-certs/localhost.crt
Key: /Users/user/.office-addin-dev-certs/localhost.key
ℹ ｢wds｣: Project is running at https://localhost:3000/
ℹ ｢wds｣: webpack output is served from /
ℹ ｢wds｣: Content not from webpack is served from /Users/user/Projects/GLML/My Office Add-in
⚠ ｢wdm｣: Hash: c94ae67b46879649c8b3
Version: webpack 4.46.0

$ npm start
> office-addin-taskpane-angular@0.0.1 start
> office-addin-debugging start manifest.xml

Debugging is being started...
App type: desktop
The dev server is already running on port 3000.
Sideloading the Office Add-in...
Debugging started.
```

Debug office add-ins in Mac
```bash
$ defaults write com.microsoft.Word OfficeWebAddinDeveloperExtras -bool true

```
