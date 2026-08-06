# Hi there, I'm Rimal 👋

Welcome to my GitHub profile!

## 🚀 About Me

- 💻 Passionate about software development
- 🌱 Always learning and growing
- 🤝 Open to collaborating on interesting projects
- 🔭 Exploring new technologies and building cool things

## 🛠️ Technologies & Tools

![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Git](https://img.shields.io/badge/-Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/-GitHub-181717?style=flat-square&logo=github&logoColor=white)
![VS Code](https://img.shields.io/badge/-VS%20Code-007ACC?style=flat-square&logo=visual-studio-code&logoColor=white)

## 📊 GitHub Stats

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=mo74m3ed&show_icons=true&theme=default&hide_border=true)

## 🐛 Debugging & Problem Solving

- 🔍 Enjoy diving deep into complex problems
- 🛠️ Experienced with debugging tools and techniques
- 📝 Writing clean, maintainable code

## Quickstart for GitHub REST API

Learn how to get started with the GitHub REST API.

### Introduction

This quickstart shows how to make a simple GitHub REST API request with GitHub CLI, `curl`, or JavaScript. For a more detailed guide, see [Getting started with the REST API](https://docs.github.com/en/rest/using-the-rest-api/getting-started-with-the-rest-api).

### Using GitHub CLI

```bash
gh auth login
gh api /octocat --method GET
```

### Using curl

```bash
curl -L \
  -H "Accept: application/vnd.github+json" \
  -H "X-GitHub-Api-Version: 2022-11-28" \
  https://api.github.com/octocat
```

### Using JavaScript

```js
const response = await fetch("https://api.github.com/octocat", {
  headers: {
    Accept: "application/vnd.github+json",
    "X-GitHub-Api-Version": "2022-11-28",
  },
});

const data = await response.text();
console.log(data);
```

### Next steps

For a more detailed guide, see [Getting started with the REST API](https://docs.github.com/en/rest/using-the-rest-api/getting-started-with-the-rest-api).

## 📫 Get in Touch

Feel free to reach out or explore my repositories!

[![GitHub followers](https://img.shields.io/github/followers/mo74m3ed?label=Follow&style=social)](https://github.com/mo74m3ed)
