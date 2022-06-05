# Grasscutter Linux OneClick

![Shell Script](https://img.shields.io/badge/shell_script-%23121011.svg?style=for-the-badge&logo=gnu-bash&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

Tested on:

![Arch Linux](https://img.shields.io/badge/Arch%20Linux-1793D1?logo=arch-linux&logoColor=fff&style=for-the-badge)

如果您在其他发行版上运行成功或出现什么问题，请前往 [Issue](https://github.com/GenKitCN/Grasscutter-Linux-OneClick/issues) 进行反馈

同时，本项目**不考虑**支持 Fedora 系发行版，请勿反馈

## 使用方法

amd64: 
```bash
curl https://linux.mihoyo-is-in.icu/install_amd64 --output install && chmod +x install && ./install
```

aarch64:
```bash
curl https://linux.mihoyo-is-in.icu/install_aarch64 --output install && chmod +x install && ./install
```

## 关于闭源+混淆

看到群里有人问了，就顺带写一下[我个人](https://github.com/chitang233)的想法吧

首先需要说明的是，脚本中不含任何后门，也不会上传到我们自己的服务器(也没那钱)

诚然，闭源的脚本是一个黑盒，特别是需要 root 权限的脚本，多多少少还是放不下心来的

正如 [@timpaik](https://t.me/timpaik) 所说，从用 Linux 的第一天起就被教育不要执行 `curl https://example.com | bash` 这样的的命令

这也确实是个好习惯，我也赞同

毕竟，谁不想大大方方地放出来自己的脚本、接受群众审查、让更多人放心、简单地晚上割草机呢

但是我们也有自己的难处

[某方的 GenshinProxy 模块](https://github.com/577fkj/GenshinProxy) 就是一个活生生的例子

从一开始的开源，到有人拿去倒卖而不得不转向闭源

这是我们不希望看到的，我们不想让自己用爱发电的产品被人拿去卖而赚得盆满钵满

有了前车之鉴，这个脚本也在发布之初就选择了闭源

但这个脚本我们自己也在使用，作为用户，您也大可以放心

如果实在对安全放不下，我也欢迎手动搭建，这并不会对我们造成任何利益上的影响

想要看源码也没问题，在你保证不以任何形式传出该脚本并愿意为项目做贡献的情况下，可以选择[联系我](mailto:chitang@mihoyo-is-in.icu)，我会邀请您进入本 GitHub 组织，而未经混淆的脚本就在 GenKitCN/Grasscutter-OneClick 中，我们愿意接受您的审查

最后，如果可以的话 请考虑[捐赠](https://afdian.net/@chitang)来支持开发及域名费用
