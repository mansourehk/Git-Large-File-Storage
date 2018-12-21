Download LFS for windows from "https://git-lfs.github.com/"
Run cmd
cd "the path to the folder contain your data for upload"

Run the following lines:
  >> git init
  >> git lfs install
  >> git lfs track "*.json"
  Repeat the same line for other type of files you want lfs to track, like .psd .txt .mat and so on.
  If you want to add a specific folder use "myfolder/**"
  >> git add .gitattributes
  >> git add yrfile.json
  no need to use double quotation
  >> git commit -m "yr comment"
  >> git remote add origin https://github.com/mansourehk/Git-Large-File-Storage.git
  Add your repository url address instead of the aformentioned url
  >> git push origin master
  Or force push "git push -f origin master" (Mostly this work)
  
If your repository contains some other files, clone or git pull the data, and then git push all.
