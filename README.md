# Actions CopyRepo

利用GitHub Actions复制公共仓库为私有仓库

:exclamation: **使用前需Fork当前仓库**

:key:  **个人访问令牌**

- 创建：Settings (点击右上角头像) > Developer settings > Personal access tokens > Tokens (classic) > Generate new token > Generate new token (classic)      
  - 只勾选仓库权限
  - <details>
      <summary>查看截图</summary>

      ![18dd8ee0436aa105848631936b51ec7](https://user-images.githubusercontent.com/70625361/236611306-a81552da-e3e0-4712-8f35-df232860d129.png)
    </details>
- 配置：Settings > Secrets and variables > Actions > Secrets > New repository secret
  - 变量名：`TOKEN`
  - 变量值：拥有仓库权限的个人访问令牌
  - <details>
      <summary>查看截图</summary>
      
      ![99887ee23510e96b7c466a569521982](https://user-images.githubusercontent.com/70625361/236611324-e8a4a348-20e3-48fd-8e0c-16e6e07818ce.png)
    </details>

:zap: **使用**：Actions > 复制公共仓库为私有仓库 > Run workflow

- <details>
    <summary>查看截图</summary>
    
    ![b5b7f109d18f45484d898a682f4e03c](https://user-images.githubusercontent.com/70625361/236611354-be0b3144-ef2a-4a23-b242-321e86f641b2.png)
  </details>
