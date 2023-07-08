# Start-OpenSource

Welcome to "Start-OpenSource," a repository designed to help beginners to learn the art of contributing to open source projects. Let's dive in together! 🚀

## 🎯 Choosing Your First Contribution 

Getting started can be daunting, but we've curated a list of beginner-friendly issues and tasks. Look for labels like "good first issue" or "beginner-friendly" to find well-defined tasks that provide a gentle introduction to the project.

## ⚡️ The Power of Simple Contributions 

Every small action counts! Correct typographical errors, fix small bugs, or suggest simple improvements. These seemingly modest contributions create a ripple effect of positivity, paving the way for further advancements. 

## 🚀 Get Started
### ⭐ HOW TO MAKE A PULL REQUEST:

**1.** Start by making a Fork of the [**start-opensource**](https://github.com/thecyberworld/start-opensource) repository. Click on the <a href="https://github.com/thecyberworld/start-opensource/fork"><img src="https://i.imgur.com/G4z1kEe.png" height="21" width="21"></a>Fork symbol at the top right corner.

**2.** Clone your new fork of the repository in the terminal/CLI on your computer with the following command:
```bash
git clone https://github.com/<your-github-username>/start-opensource
```

**3.** Navigate to the newly created start-opensource project directory:
```bash
cd start-opensource
```

**4.** Set upstream command:

```bash
git remote add upstream https://github.com/thecyberworld/start-opensource.git
```

**5.** Create a new branch:
```bash
git checkout -b YourBranchName
```

**6.** Sync your fork or your local repository with the origin repository:
- In your forked repository, click on "Fetch upstream"
- Click "Fetch and merge"
### Alternatively, Git CLI way to Sync forked repository with origin repository:

```bash
git fetch upstream
```

```bash
git merge upstream/main
```

### [GitHub Docs](https://docs.github.com/en/github/collaborating-with-pull-requests/addressing-merge-conflicts/resolving-a-merge-conflict-on-github) for Syncing

**7.** Make your changes to the source code.
  - Add you name in [Contributors.md](Contributors.md)
  - Example:
    ```markdown
    - [Kabir](https://github.com/kabir0x23)
    ```

**8.** Stage your changes and commit:

⚠️ **Make sure** not to commit `package.json` or `package-lock.json` file, until and unless you have installed the new packages.

⚠️ **Make sure** not to run the commands `git add .` or `git add *`. Instead, stage your changes for each file/folder

```bash
git add Contributors.md
```

```bash
git commit -m "<your_commit_message>"
```

**9.** Push your local commits to the remote repository:

```bash
git push origin YourBranchName
```

**10.** Create a [Pull Request](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request)!

**11.** **Congratulations!** You've made your first contribution to [**start-opensource**](https://github.com/thecyberworld/start-opensource/graphs/contributors)! 🙌🏼

**_:trophy: After this, the maintainers will review the PR and will merge it if it helps move the start-opensource project forward. Otherwise, it will be given constructive feedback and suggestions for the changes needed to add the PR to the codebase._**

---

- We help and encourage each other to contribute to open source little and often 😄.
- Feel free to check out other cool open-source repositories:
    - [Thecyberworld](https://github.com/thecyberworld)
    
---
## 🔗 Connect with Us:
<p align="left">
<a href="https://github.com/thecyberworld/support/issues/new?assignees=&labels=invite+me+to+the+organisation&template=invitation.yml&title=Please+invite+me+to+the+GitHub+Community+Organization" target="blank"><img align="center" src="https://raw.githubusercontent.com/gauravghongde/social-icons/9d939e1c5b7ea4a24ac39c3e4631970c0aa1b920/SVG/Color/Github.svg" height="40" width="50" /></a>
<a href="https://discord.gg/QHBPq6xP5p" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/discord.svg" height="40" width="50" /></a>
<a href="https://www.linkedin.com/company/thecyberw0rld/" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" height="30" width="40" /></a>
<a href="https://twitter.com/thecyberw0rld" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/twitter.svg" height="30" width="40" /></a>
<a href="https://www.youtube.com/c/thecyberworld?sub_confirmation=1" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/youtube.svg" height="40" width="50" /></a>
<a href="https://t.me/thecyberw0rld" target="blank"><img align="center" src="https://raw.githubusercontent.com/gauravghongde/social-icons/9d939e1c5b7ea4a24ac39c3e4631970c0aa1b920/SVG/Color/Telegram.svg" height="30" width="40" /></a>
<a href="https://instagram.com/thecyberw0rld" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/instagram.svg" height="30" width="40" /></a>
</p>