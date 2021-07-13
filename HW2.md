# 作业

## Git

请把作业发送到邮箱 [me@panda2134.site](mailto:me@panda2134.site)，截止时间为7.14晚23:59.

1. 在你的计算机安装Git。你安装的Git版本是多少？（提示：使用命令 `git --version`）

	2.28.0.windows.1

2. 生成一个密钥对，可以不设置密钥的密码。采用你昨天学习的shell命令列出.ssh文件夹的内容。用文本编辑器打开.ssh/id_rsa.pub文件，用通俗的语言描述该文件包含哪几个以空格分开的部分。上传这个密钥对到GitHub和[清华内部Git服务器](https://git.tsinghua.edu.cn).

	包含了三部分：'ssh-rsa'、公钥、 用户邮箱

3. Eve 是一个中间人，能在公网监听你和GitHub服务器之间的流量。请问，当你使用SSH协议推送提交到GitHub私有仓库时，他能知晓你的提交内容吗？如果他获得了你的SSH公钥，他能看到你的私有仓库内容吗？如果他获得了私钥呢？

	不能；不能；能

4. 直接运行`ls`能看到`.git`目录吗，为什么？

	不能，因为`.git`是隐藏目录

5. 查找资料，试着简述Git和早期SVN等源代码管理工具等区别。为了帮助你理解这一区别，尝试一下下面的题目。
   - 2021年3月10日，一场大火摧毁了OVH这一服务器提供商在法国的一座数据中心。[News](https://datacenterfrontier.com/ovh-data-center-in-france-destroyed-by-fire-all-staff-safe/)

   - 如果你在这个数据中心内托管了一个SVN服务器，而且没有任何备份。平时开发者使用 `svn checkout` 获得当前版本的项目代码。那么大火后，你还能获得所有历史版本的代码吗？

   	不能。

   - 如果你托管的是Git服务器，并且开发者使用 `git clone` 获得项目代码，又如何呢？

   	能，因为git是分布式的。

6. 下图是前几年很火的一个meme.

![useful git aliases | git-knowledge-base](https://idiv-biodiversity.github.io/git-knowledge-base/img/git-fire.png)

假设Git服务器不受到火灾影响，在你遇到火灾时，执行上述命令一定能成功push代码吗？如果能，试着解释原因；如果不能，试着给出修改后的命令，它能保证：只要网络未受损，Git服务器正常运行，你提交的代码就一定不会被Git服务端程序拒绝。（参考: [Git Fire](https://github.com/qw3rtman/git-fire)）

--------

## GitHub Actions

## 

- 什么是CI/CD? 什么是单元测试？什么是代码覆盖率？
- TypeScript语言常用的linter是什么？
- GitHub托管CI/CD运行在谁的服务器上？自托管的呢？
- 列举2个常见的第三方CI服务（除了GitHub Actions）
- GitHub Actions的文档地址是（）。简单描述在GitHub Actions配置ESLint对JS项目进行语法检查的过程，或者把配置好了的仓库链接贴上来。