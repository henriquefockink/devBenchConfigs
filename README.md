# Dev Benchwork Config
## git mergetool using visual studio code
  ```
  git config --global merge.tool vscode
  git config --global mergetool.vscode.cmd "code --wait $MERGED"
  git config --global diff.tool vscode
  git config --global difftool.vscode.cmd "code --wait --diff $LOCAL $REMOTE"
  ```
