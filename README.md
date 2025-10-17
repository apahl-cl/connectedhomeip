# Devcontainer edits for [Coder](https://coder.com/)

Tweaks to the connectedhomeip devcontainer to be runnable in Coder
[until Coder supports initializeCommand](https://github.com/coder/envbuilder/issues/395).

If you need to update the environment, merge in the latest changes from the
upstream master branch. Then, run `bash .devcontainer/build.sh` and it will
print the Docker build args that would be used to do the build. Then, update the
Dockerfile with these args and commit these changes.
