# GitHub Contribution Snake 🐍

A simple, easy-to-follow guide to add the animated snake game to your GitHub profile's contribution graph.

This repository provides the necessary GitHub Action workflow file and instructions to get you set up in less than 5 minutes.

![Demo Screenshot](/screenshot.png)

## How to Use This

Follow these three simple steps to get the snake on your profile.

### Step 1: Create the Workflow File

1. Go to your special GitHub profile repository (the one with the same name as your username, e.g., `YourUsername/YourUsername`).

2. Create a new file with the following path: `.github/workflows/snake.yml`.

   * *Tip: When you type `.github/` in the filename box, GitHub will automatically create the folder.*

3. Copy the code from the `snake.yml` file in this repository and paste it into the new file you just created.

### Step 2: Run the Action

1. Go to the **Actions** tab in your repository.

2. On the left sidebar, click on the **"Generate Snake"** workflow.

3. Click the **Run workflow** dropdown button, and then click the green **Run workflow** button inside it.

Wait about a minute for the action to complete. When you see a green checkmark, the animation files have been successfully generated in your repository.

### Step 3: Add the Snake to Your README

You're all set! Now, just copy one of the following lines into your profile's `README.md` file to display the animation.
<br>

**Light Mode Version(Recommended for light  themes):**
```
[![My GitHub contribution graph](https://raw.githubusercontent.com/YOUR_USERNAME/YOUR_USERNAME/main/output/snake.svg)](https://github.com/YOUR_USERNAME)
```
<br>

**Light Mode Version(Recommended for light  themes):**

```
[![My GitHub contribution graph](https://raw.githubusercontent.com/YOUR_USERNAME/YOUR_USERNAME/main/output/snake-dark.svg)](https://github.com/YOUR_USERNAME)
```
<br>

**Important:**
Remember to replace `YOUR_USERNAME` with your actual GitHub username!

## Troubleshooting

* **Action Fails with `exit code 128`:** This means the action didn't have permission to write the new `snake.svg` file to your repository. The included `snake.yml` file already contains the fix (`permissions: write-all`), so you shouldn't encounter this if you copy the file correctly.

* **Image Shows as a Broken Link:** This usually means the URL in your README is incorrect. Double-check that you've replaced `YOUR_USERNAME` in the link and that the path is correct.

Enjoy your new contribution snake!
