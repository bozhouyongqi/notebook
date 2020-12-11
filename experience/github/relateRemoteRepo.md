本地仓库与github远程仓库关联

#### …or create a new repository on the command line
```
echo "# debugReact" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:bozhouyongqi/debugReact.git
git push -u origin main       
```

#### …or push an existing repository from the command line
```
git remote add origin git@github.com:bozhouyongqi/debugReact.git
git branch -M main
git push -u origin main
```
