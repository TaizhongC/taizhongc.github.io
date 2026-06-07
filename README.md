# Taizhong Chen - Personal Website

This is a minimal, lightweight personal website built using Jekyll. The design is a custom-coded premium dark/light layout that reads all contents directly from `index.md`.

## Local Development Setup

To run this website locally on your computer:

### 1. Install Ruby and MSYS2
Run this command in an administrator PowerShell/Command Prompt:
```powershell
winget install --id RubyInstallerTeam.RubyWithDevKit.3.2 --exact
```

### 2. Install Jekyll and Bundler
Open a **new** PowerShell window (so the updated `PATH` is loaded) and run:
```powershell
gem install jekyll bundler
```

### 3. Install Dependencies
Navigate to this directory (`taizhong.github.io`) and run:
```powershell
bundle install
```

### 4. Run the Local Server
Run the Jekyll development server:
```powershell
bundle exec jekyll serve
```
Once running, open your web browser and navigate to:
```
http://127.0.0.1:4000/
```
The server will automatically reload the website when you make edits to `index.md` or any styling files.
