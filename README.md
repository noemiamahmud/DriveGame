
# IMPORTANT!!!!!!!


# clone in your terminal using these steps:

git lfs install 

git clone https://github.com/noemiamahmud/DriveGame.git

cd DriveGame

git lfs install

git lfs pull



if there's issues with lfs install -> 

do

brew install git-lfs       <- make sure homebrew is installed first

then

git lfs install


# Saving changes in unreal !!!!

fully close unreal engine when doen making changes!!

then, check git status

DO NOT add or commit anything from the Saved/ folder

git add the config and content changes


if you see these for whatever reason, To remove all local changes in Saved/ (they’re safe to delete — Unreal will rebuild them):

git restore Drive/Saved/

next, do git restore Drive/Content/__ExternalActors__/

lastly:

git pull origin main --rebase

git push origin main


