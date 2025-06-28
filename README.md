# 🐍 GitHub Contribution Snake Animation

This repository is used to automatically generate and host a dynamic contribution graph animation based on my GitHub activity. The animation is generated using GitHub Actions and is displayed in the README of my main profile repository: [Akshat-mittal1](https://github.com/Akshat-mittal1).

> 🎯 **Purpose**: Visualize my GitHub contributions in a fun and interactive way using a snake-like animation.

---

## 📂 Hosted Outputs

The following animation files are automatically generated and committed to the `output` branch:

- `github-contribution-grid-snake.svg`
- `github-contribution-grid-snake-dark.svg?palette=github-dark`
- `github-contribution-grid-snake.gif?color_snake=orange&color_dots=#bfd6f6,#8dbdff,#64a1f4,#4b91f1,#3c7dd9`

These files are then embedded directly into my GitHub profile README via:

```markdown
<img src="https://raw.githubusercontent.com/Akshat-mittal1/snake/output/github-contribution-grid-snake.svg" alt="GitHub Snake Animation" />
⚙️ How It Works
This repository uses Platane's Snake GitHub Action to generate the contribution graph animation daily:

GitHub Actions fetch contribution data using your username

The snake "crawls" over the contribution grid

Output files are committed to the output branch

The SVG/GIF is then used in the main profile's README.md

📈 Live Result
See it in action on my GitHub profile:

🔗 github.com/Akshat-mittal1

<p align="center"> <img src="https://raw.githubusercontent.com/Akshat-mittal1/snake/output/github-contribution-grid-snake.svg" width="100%" /> </p>
🙌 Credits
This setup is based on the amazing open-source project by:

GitHub Action: Platane/snk

Maintained by: @Platane

⭐ If you like the concept, consider starring Platane's repository!
