# git-completion
## Mac下git自动tab补全

##  

## 正常实现步骤

1. 下载 https://raw.githubusercontent.com/panmin/git-completion/master/git-tab.bash 到本地

2. git-tab重命名为.git-completion.bash到～/目录下

   ```shell
   mv git-tab ~/.git-completion.bash
   ```

3. 配置~/.bash_profile文件

   ```shell
   # git auto completion
   if [ -f ~/.git-completion.bash ]; then
       . ~/.git-completion.bash
   fi
   ```

4. 刷新源

   ```shell
   source ~/.bash_profile
   ```

5. 使用git+tab

   `git stat`+`tab` //自动补全

   `git st`+`tab`+`tab` //两次tab出提示

   