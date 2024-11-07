# github
my own version of user guide


**branches**
 - git branch
 - git branch --all

**删除github的文件 git clone**[[https://github.com/username/repository-name.git](https://github.com/username/repository-name.git)](https://github.com/lukalee/introduction-to-data-science.git)

 - cd repository-name git rm “file name” 
 - git commit -m "Delete file from repository"  
 - git push origin main


**改名字** 

 - git branch git branch -m 原名字 newName新名字  
 - git push -u origin newName新名字  
 - git push origin --delete 原名字



**把文件夹push上来**
[https://blog.csdn.net/qq_41574522/article/details/134680674]


## **git hub desktop的folder里已经删了的文件出现在了git hub webpage里**

**检查文件变更**：
-   打开 GitHub Desktop，确认左侧的 "Changes" 选项卡里是否显示了被删除的文件。
-   如果你看到删除的文件在 "Changes" 中列出，表示 GitHub Desktop 侦测到了该文件被删除的更改。

- **提交更改**：
-   在 "Summary" 输入框中输入提交信息（比如 "Delete file"）。
-   点击 "Commit to main" 或者你的分支名称，将更改提交到本地仓库。
-   右键 amend commit：修改提交
-   ![image](https://github.com/user-attachments/assets/97f6cfa7-b6d8-4c38-9da4-509b720c0309) 把文件直接拖到固定文件夹上传。
