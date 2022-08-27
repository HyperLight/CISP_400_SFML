# CISP_400_SFML

git config --global user.email "loganoz6113@gmail.com"
git config --global user.name "HyperLight"

curl -LO https://raw.githubusercontent.com/GitCredentialManager/git-credential-manager/main/src/linux/Packaging.Linux/install-from-source.sh &&
sh ./install-from-source.sh &&
git-credential-manager-core configure
export GCM_CREDENTIAL_STORE="secretservice"

git push -u origin main

