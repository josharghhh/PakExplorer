
# Pak Explorer

A simple GUI application for opening/viewing/extracting Arma Reforger's PAC1 file format.

## Quick download
Grab the latest portable build from the GitHub Releases page:
https://github.com/josharghhh/enfusion_tools_EXTARGH/releases/latest

## Web version
This project is a Windows desktop (WPF) application and does not run inside a browser. If you'd like a browser-based version, we'd need to build a separate web client (for example, a WebAssembly or server-backed extractor) with different packaging and security constraints.

## Build from GitHub
1. Install the .NET SDK (8.0 or newer).
2. Clone the repo:
   ```
   git clone https://github.com/josharghhh/enfusion_tools_EXTARGH.git
   cd enfusion_tools_EXTARGH
   ```
3. Restore and build:
   ```
   dotnet restore PakExplorer.sln
   dotnet build PakExplorer.sln -c Release
   ```
4. Run from Visual Studio or launch the built EXE from `PakExplorer/bin/Release`.
