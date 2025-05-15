<div align="center"><a href="https://github.com/Safouene1/support-palestine-banner/blob/master/Markdown-pages/Support.md"><img src="https://raw.githubusercontent.com/Safouene1/support-palestine-banner/master/banner-support.svg" alt="Support Palestine" style="width: 100%;"></a></div>

## Hello there 👋 As-salamu Alaikum

Welcome. I'm MSK - a Sunni Muslim Bangali who knows very little about a few things. I've recently completed my undergraduate in Mechanical Engineering from the Bangladesh University of Engineering and Technology (BUET).

- 🔭 I’m currently working on myself.
- 🌱 I’m currently learning about myself (and the world).
- 🤔 I’m looking for help with myself (to learn how to survive in this world).
- 💬 Ask me about nothing. (I know nothing.)
- 📫 How to reach me: Are you sure that you want to reach me? I wonder why.

## Some handy steps for using git-cli locally

### Anonymous git commits

Before making any git commits, you can set it up using the following commands for anonymity:

git config --global user.name "John Doe"  
git config --global user.email "johndoe@email.com"

And if that doesn't work, try replacing "John Doe" with "Your Name" (Just this. DON'T use your actual name.) and "johndoe@email.com" with "you@example.com".

### Creating a local git repo and exporting it to a git repo hosting site

echo "# *repo-name*" >> README.md
git init  
git add .  
git commit -m "first commit"  
git branch -M main <!--Only if you want to change the initial branch name from 'master' to anything else (in this case, 'main')-->  
git remote add origin https://github.com/*username*/*repo-name*.git  
git push -u origin main <!--OR, to push forcibly: git push -uf origin main-->  

Replace *username* and *repo-name* with your required ones.

Just trying to share something relevant that I've benefitted from personally. I hope it helps.

<!--
**msk-nightly/msk-nightly** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
