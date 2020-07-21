### Hello world 👋

<!--
**Pixelus/Pixelus** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Hi, I'm Stéphanie Malafosse. I consider myself as a permanent learner, a smart worker and computer programming 💻 is one of my biggest hobbies, with designing 🎨, thinking 🤔, reading 📚, cooking 👩‍🍳 and playing 🏸. I am a 🇫🇷 web developer and designer skilled in HTML, CSS and its frameworks, and I'm currently working on the App Academy's Full-Stack Web Development bootcamp with the goal to become a software developer.

- 🔭 I’m currently working on push my skills with Ruby language.
- 🌱 I’m currently learning Full-Stack Web Development on App Academy Open.
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: She/Her
- ⚡ Fun fact: ...
-->

<!--START_SECTION:activity-->

name: Update README

on:
  schedule:
    - cron: '*/30 * * * *'

jobs:
  build:
    runs-on: ubuntu-latest

    steps:
      - uses: actions/checkout@v2
      - uses: jamesgeorge007/github-activity-readme@master
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
