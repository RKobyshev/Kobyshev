1) ssh
ssh-keygen -t ed25519 -C ""
eval "$(ssh-agent -s)"
ssh-add ~/.ssh/id_ed25519
cat ~/.ssh/id_ed25519.pub
copy and paste it on github in user->settings->ssh
2)  clone
git clone ssh-url from github
