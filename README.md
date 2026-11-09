# 2026-zjsdxs-Qualifier

第九届浙江省大学生网络与信息安全竞赛 预赛

**附件存放在本仓库的 Github Release 中**

## Web - Pickle Me

> 小明写了一个"安全"的 pickle 加载服务, 为了防止反序列化漏洞,
> 他使用了严格白名单的 RestrictedUnpickler —— 任何 find_class 请求
> 只要不在白名单里都会被拒绝, eval/exec/os.system统统拿不到。
> 他说: "我的白名单里只有 builtins.getattr 和 os.walk,
>       这两个人畜无害, 你能拿我怎么办?"
> 请证明他是错的。flag 在 /flag。

## Web - FileDesk

> FileDesk 为企业内各部门与合作单位提供资料归档服务。访客可提交合同扫描件、项目图片和完整资料包，系统会生成统一归档记录并支持在线预览。请从资料接待页完成一次归档，并取得服务端保存的校验标记。

None（环境/靶机题，未提供附件下载）

## Web - rpass

> 爱来自一名天真的rasp开发者
> 知识点：JAVA、RASP绕过、JNI

## Web - short-reflect

> 我给有漏洞的旧服务添加了简单的waf，删掉了一些危险路由，应该可以防住各位黑客的攻击...
> （账密admin/admin123，需要执行/readflag来获得flag）
> 知识点：JAVA、SSTI、waf绕过

## Misc - 奇怪的图片

> 好奇怪像是APNG

## Misc - pyjail

> 你能逃离我的jail吗？

None（环境/靶机题，未提供附件下载）

## Misc - Chaotic_Flight

> This is the last message sent by the undercover Mr.Henon before he was caught. I think there must be something really important hidden in it...

## Misc - boom

> 在流量中找不出完你是得不到结果哦。

## Misc - Bbbbbbird

> where is Bbbbbbird

## Crypto - Digital Signature

> 在某次针对XXX数据签名和加密系统的攻防演习中，我探测到该系统存在两个用户user1、user2，我通过钓鱼手段获取了该系统开发人员user1的主机权限，并且从user1的终端中收集到了关于数字签名和加解密的部分源代码，其中random.c似乎是在签名中用到的一个文件，certificate.csv、message.csv、sign.csv是我从数据库中拿到的信息，分析源代码，他的实现似乎存在漏洞，你能帮我发现漏洞并解密关于user2的数据吗？

## Crypto - Passion!

> be patient!

## Crypto - 1byte

> 事件响应组在取证时发现了一条遗留的恢复通道：它用ElGamal加密保存了一份记录。更糟的是，这把恢复密钥也是在同一次仪式中生成的——它的私钥只有一个字节。

## Reverse - shift

> 加减乘除运算都已经用烂了，来试试移位运算吧

## Reverse - ezAndroid

> 提交时将flag换成DASCTF

## Reverse - easyaosp

> Android的世界也很有趣

## Reverse - PyVM

> from pyvm import justice —— 一个只发布编译产物(.pyc)的校验程序。
> 它内部实现了一台栈式虚拟机,真正的校验逻辑以自定义字节码存储,拿到 Python 3.12 的 pyc 且没有源码,请直接阅读字节码。
> 输入正确的 flag(即 serial)会得到:
>     [+] Correct! The flag is what you entered.

## Pwn - ledger

> 不是哥们，你别告诉我看不懂结构体

## Pwn - echo_rop

> 哦，朋友，我觉得你应该可以reslove这个题目的对吧

## Pwn - basic_pwn

> 最最基本的pwn了，我看看还有谁不签到

## Pwn - baby_heap_3

> 听一万遍反方向的钟，可以回到学heap的第一天吗

## AI - Blind Spot

> 模型藏在服务器后面, 连置信度都看不到:
> - POST /start   : 领取会话 token (每个 IP 限 5 个)
> - POST /oracle  : {token, x} -> {label}  只返回 top-1 标签!
>                   每个会话限 3000 次查询
> - GET  /challenge : 源样本(类别 3) + 一张类别 7 的示例
> - POST /submit  : 提交样本 x
> 判定: L2(x − src) ≤ 1.45 且被预测为类别 7。
> 参考: 线段二分只能把你带到 ~1.9; 想达标, 得在决策边界上"行走"。

None（环境/靶机题，未提供附件下载）

## AI - Gradient Echo

> “原始数据一个字节都没出过设备。我们上报给服务器的只有梯度——那能泄露什么？”工程师说。
> “梯度也是数据。”审计员丢下这句话，只留下一份截获的通信数据。

## AI - 权重手术

> 听说你的分类器很鲁棒噢，让我看看

None（环境/靶机题，未提供附件下载）

## 数据安全 - PaperKite

> 某综合业务网关在日批报送作业中的一次传输留有网关侧采集材料，请依据附件中的展示规范逐作业审计系统生成的报表，形成完整批次复核清单。按规范处理后保存为 CSV 格式文件（文件编码为 utf-8 格式），上传至该题的校验平台（在该校验平台里可以下载该题的示例文件 example.csv，可作为该题的格式参考），校验达标即可拿到 flag。

## 数据安全 - CedarRoom_1

> 某单位资料阅览系统在一次日终逻辑备份后需要生成服务台催还核对表，请依据附件中的《在借阅展示脱敏规范.md》恢复并处理应纳入的借阅事实，按规范完成展示脱敏后保存为 CSV 格式文件（文件编码为 utf-8 格式），上传至该题的校验平台（在该校验平台里可以下载该题的示例文件 example.csv，可作为该题的格式参考），校验达标即可拿到 flag。
