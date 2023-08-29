# SilkyFowl.Avalonia.FuncUI.LiveView.Demo

Demo of SilkyFowl.Avalonia.FuncUI.LiveView by vscode.

## Usage

```sh
gh repo clone SilkyFowl/SilkyFowl.Avalonia.FuncUI.LiveView.Demo
# or
# git clone https://github.com/SilkyFowl/SilkyFowl.Avalonia.FuncUI.LiveView.Demo.git

cd SilkyFowl.Avalonia.FuncUI.LiveView.Demo

dotnet tool restore
dotnet paket install
dotnet tool install SilkyFowl.Avalonia.FuncUI.LiveView.Analyzer --version 0.0.3 --tool-path analyzers

code .
```

set debug setting `.NET Core Launch (Preview)`.

![Alt text](/assets/set-debug-setting.png)

Launch debugger!!
