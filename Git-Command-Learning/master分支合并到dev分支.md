1. 分支切换到master

   ```bash
   git checkout master
   ```

2. 代码pull到本地

   ```bash
   git pull
   ```

3. 修改冲突

   有冲突：vs工具

   无冲突：跳转到step: 5

4. 提交到本地

   ```bash
   git add .
   git commit -m "merge"
   ```

5. 切换到dev分支

   ```bash
   git checkout dev
   ```

6. merge

   ```bash
   git merge master
   ```

7. dev分支远程仓库更新

   ```bash
   git push
   ```

   