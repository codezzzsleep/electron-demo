# electron 初始化流程

1. 创建文件夹

   ```bash
   mkdir project && cd project
   ```

   

2. yarn/npm 初始化文件夹

   ```bash
   yarn init
   ```

   

3. 引入electron 的依赖

   ```bash
    yarn add --dev electron
   ```

   

4. 增加一段脚本

   ```json
   {
     "scripts": {
       "start": "electron ."
     }
   }
   ```

   

5. 