# Izzy's notes

In this webiste, I will keep my notes in PVHS. 

## Setup 

### 1. Create a GitHub Account

Go to https://github.com, sign up for a free account, follow steps to register and verify my email address.
> My account name: izzy1309

### 2. Create a New Repository

On the GitHub homepage, click “+” → “New repository.”
  1. Name it izzy1309.github.io, which follows the format <my account name>.github.io
  2. Set the repo to Public.
  3. Check “Add a README file”.
  4. Add MIT license
  5. Click “Create repository.”

### 3. Install git and visual studio code

We use 2 tools for web page editing:
* git is the tool to talk to github to pull and push changes.
* visual studio code is the IDE helping to edit the pages.

1. Install xcode
```shell
# xcode-select will install git
sudo xcode-select --install

# verify git version
git --version
```

2. Install visual studio code

* Go to the official website: https://code.visualstudio.com/
* Click the “Download for macOS” button.
* Click downloaded dmg to install

### 4. Add the Website Files

* Pull the repository from github
* Open vs code to open the folder
* Add index.html

```html
<html>
<head>
<title>Izzy's notes</title>
</head>
<body>
<h1>Hello, world!</h1>
</body>
</html>
```

### 5. Enable GitHub Pages

Go to the repository → Settings → Pages (on the sidebar).
1. Under “Source”, choose “Deploy from a branch.”
2. Choose the main branch, and / (root) folder.
3. Click “Save.”
4. Wait a few minutes — the website will appear at https://izzy1309.github.io