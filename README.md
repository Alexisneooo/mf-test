# mf-test · 练习一用的仓库

《金融 AI 智能体设计与应用》第 7 次课练习一用这个仓库。每人 Fork 一份到自己账号下，在自己的分支上改 `demo1/index.html`，再发 Pull Request 回来。老师当场合几个，大家一起看合并和冲突是怎么发生的。

仓库是公开的，谁都能看到。页面上只写昵称，不写学号、手机号、全名。

| 文件 | 这次怎么处理 |
|:--|:--|
| `demo1/index.html` | 名片页，只改它。源码里标了五处「改这里 ①–⑤」 |
| `index.html` | 练习二用的第一页，不动 |
| `README.md` | 这份说明，不动 |

## 七步

1. **Fork**。登录 GitHub，在本页右上角点 Fork，再点 Create fork。你的账号下会多出一个 `<你的用户名>/mf-test`。
2. **克隆自己的 fork**。让 Claude Code 克隆 `https://github.com/<你的用户名>/mf-test`。克隆的是你自己那份，不是 zhangyf29 的。
3. **开分支**。分支名用 `stu/<你的用户名>`，比如 `stu/xiaohong`。
4. **只改五处**。`demo1/index.html` 里标了「改这里」的地方是昵称与组号、一句话、三张卡片、主题色那一行、更新日期。别处一个字不动。
5. **提交**。备注写清改了什么，比如「demo1：填昵称、一句话、三张卡片和主题色」。
6. **推到自己的 fork**。第一次推送会弹出 GitHub 登录窗口，在浏览器里自己点授权。
7. **发 Pull Request**。回到自己 fork 的网页，点黄条上的 Compare & pull request，没有黄条就点 Contribute 再点 Open pull request。核对上面一行，左边是 `zhangyf29/mf-test` 的 `main`，右边是你的 `stu/<你的用户名>`。标题写「第 N 组 · 昵称」，点 Create pull request。

第 1 步和第 7 步在网页上自己点。账号、密码、令牌都不交给 Claude Code。

老师合了别人的 Pull Request 以后，你的那个可能显示有冲突。这正是练习要看的现象，不用自己处理。

## 发给 Claude Code 的一段话

把尖括号连同里面的字换成你自己的，整段复制给 Claude Code。

```text
帮我做 Git 练习一。每做完一步告诉我结果。出错就停下，把报错原文给我看，不要自己换办法绕过去。

1. 把 https://github.com/<我的GitHub用户名>/mf-test 克隆到当前文件夹，进到 mf-test 文件夹里。
2. 新开一条分支 stu/<我的GitHub用户名>，切过去。
3. 打开 demo1/index.html，只改标了「改这里」的五处，其他地方一个字不动。
   ① 组号写「第 <N> 组」，昵称写「<我的昵称>」
   ② 一句话写「<我最想让智能体替我做的一件事>」
   ③ 三张卡片写 <第一件>、<第二件>、<第三件>，每张一个四到八字的名字，加一句话说清交给它什么、要它交回什么
   ④ 主题色换成 <色号，比如 #1F6F5C>
   ⑤ 更新日期写今天
4. 用 git diff 给我看改了哪几行，等我说可以再提交。
5. 提交，备注写「demo1：填昵称、一句话、三张卡片和主题色」。
6. 推到 origin 的 stu/<我的GitHub用户名> 分支。弹出登录窗口时告诉我，我自己登录。
7. 跑 git log --oneline -3，把结果给我看。
```

## GitHub 打不开时

老师会在群里给一个 Gitee 上的地址，内容和这里一样。步骤照旧，网址里的 github.com 换成 gitee.com，用户名换成你的 Gitee 用户名。Gitee 的仓库页同样有 Fork 按钮，第 7 步在仓库页的 Pull Requests 里新建。推送时弹出的是 Gitee 登录窗口，同样自己登录。
