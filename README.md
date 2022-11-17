- 👋 Hi, I’m @km674542532
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
km674542532/km674542532 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
Error 1
after update the MacOS, when open the ITerm the error pop out.

[oh-my-zsh] Can't update: not a git repositosotion

Solution:
1. try following code
`cd ~/.oh-my-zsh
git init`
2.if following error pop out.

`xcrun: error: invalid active developer path (/Library/Developer/CommandLineTools), missing xcrun at: /Library/Developer/CommandLineTools/usr/bin/xcrun`

indicate the xcode tools is missing.

3.
`xcode-select --install`
