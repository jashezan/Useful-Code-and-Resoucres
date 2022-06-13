# ⌨️ Commands Used


#### Step 1:
1. Connect with remote git repo: `git remote add origin [YOUR REPO LINK]` ▶️
```bash
git remote add origin .
```

2. Stage all file for `git` ▶️
```bash 
git add -A
```

3. Commit `git` files ▶️
```bash
git commit -m "Initial commit"
```

4. Push all file in remote `git` repository ▶️
```bash
git push -u origin main
```

**if problem arises with `main` then try `master`** .

> Don't forget to add node modules in `.gitignore` file

<br><br>

#### Step 2:
Add this in `package.json`: `"homepage": "https://jashezan.github.io/[YOUR REPO NAME]",`
```bash
"homepage": "https://jashezan.github.io/",
```

<br><br>

#### Step 3:
Run this in terminal ▶️
```bash
npm install gh-pages --save-dev
```

<br><br>

#### Step 4:
Add this in `package.json`:
```bash
"predeploy": "npm run build",
"deploy": "gh-pages -d build",
```

<br><br>

#### Step 5:
Now run this in Terminal ▶️
```bash
npm run deploy
```

<br><br><br><br>


### ⏰ Timestamps


`0:00` Introduction

`0:25` *Step 1* (Get your React app on GitHub)

`2:11` *Step 2* (Add final URL to package.json)

`3:33` *Step 3* (Add gh-pages npm package)

`4:06` *Step 4* (Create deploy scripts and deploy!)

----------------------------------------------------------

video: https://www.youtube.com/watch?v=2hM5viLMJpA
