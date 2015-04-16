git clone --bare https://github.com/TotalFreedom/TotalFreedomMod.git
# Make a bare clone of the repository

cd old-repository.git
git push --mirror https://github.com/TotalFreedom/TotalFreedomMod.git
# Mirror-push to the new repository

cd ..
rm -rf TotalFreedomMod.git
# Remove our temporary local repository
