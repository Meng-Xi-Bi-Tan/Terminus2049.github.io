---

layout: post

title: 为众人抱薪者，必将铭刻于区块链上

date: 2018-04-25

categories: Archive

tags: 区块链

description: 昨天，公共区块链平台以太坊(Ethereum)上发生了一笔可能永载史册的交易。通过这笔交易，敢言者的声音被宣扬，正义在某种程度上得到伸张。

---

作者：邢逸帆 宋图样

文章来自微信 ~~[硅星人](https://mp.weixin.qq.com/s/b-ahM8RLi4-pJBDTKd0QTg%23%23)~~

---

![](https://archive.is/Salxo/9eb6f4ccb95cc28ef1cd080bb8da7272f0c0036f)
*在割韭菜和云养猫之外，区块链技术终于发挥了应有的作用。文：宋图样邢逸帆\|编辑：光谱*

**昨天，公共区块链平台以太坊(Ethereum)上发生了一笔可能永载史册的交易。**

**通过这笔交易，敢言者的声音被宣扬，正义在某种程度上得到伸张。**

区块 5490403，一位用户用自己的钱包给自己转账了0以太币（点击阅读原文查看）。以太坊每笔交易都需要一笔手续费，也即所谓的“燃料”。为了这笔交易，该用户支付了 0.0007787 个以太币，这笔手续费在交易发生之时大约价值53美分，或者三块三毛人民币。

![](https://archive.is/Salxo/2dc7c4a795b2020a9281926e522eff9d0562782a)

花了手续费，最后却没有完成任何价值的转移，听起来这位用户脑子抽了。实际上并非如此。这笔交易的关键在于，其正当性和信息的准确性，已经得到遍布全球超过 1.6 万个以太坊节点的认证。没人可以删除，没人可以篡改。这正是以太坊以及大部分公链的特性。

**通过这笔交易，一段文字永久地存在了遍布全球的超过1.6万个以太坊节点中。而这一切仅耗费了一套煎饼的钱。**

**为众人抱薪者，必将铭刻于区块链上。**

### 区块链新应用：写文章

人们都听说过区块链，但大部分人都不知道这玩意到底能干嘛用。而通过这笔交易，区块链终于证明了自己：它有能力，让一段信息“恒久远，永流传”。

当你在支付宝上转账，可以附上一句话。在支付宝上，这句话只有你和转账对象（或者加上支付宝）知道。

和支付宝一样，在以太坊上转账同样可以留下一句话。然而不同之处在于，这段话并非双方之间的“悄悄话”，而将成为区块链上，甚至整个互联网上一段的“永不消失的电波”。

在炒泡沫、割韭菜和云养猫之外，区块链技术终于发挥了应有的作用。

事实上，在区块链上放置永久的信息，并不是什么新鲜技术，反而是以太坊这类公链平台的基础能力操作起来都简单的不可思议。

今天，我们就来教你怎样在区块链上写文章。

### 准备

你至少需要四样东西：

1. 钱包——相当于银行卡号，唯一，生成起来很方便。
2. 以太币 (Ether)——在以太坊上交易使用的 token，也即所谓“数字货币”，兑换起来也很方便
3. 内容——你需要发布的内容。
4. 编码转换器——后面告诉你为什么需要，以及怎样使用。英文内容可以直接转成 16 进制码，中文内容则需要先转 Unicode 码然后再转 16 进制码。
 
首先我们需要一个以太坊钱包。你可以用 MetaMask 这样的浏览器插件，或者 MyEtherWallet 网站来生成并管理自己的钱包。今天的教程就围绕 MetaMask 进行。

（如果你是硅星人/PingWest品玩的忠实读者，你可能会记得 MetaMask 就是上次那个[在区块链上养猫](https://archive.is/o/Salxo/https://mp.weixin.qq.com/s?__biz=MzI3ODg4ODEwMA==&mid=2247484642&idx=1&sn=c3a210b2546aedc77cecabe014e7d516&chksm=eb516f29dc26e63fdd4d838ffcfe823c3b3a06decc747e29f5185fef5e688709d7a12210d845&scene=21%23wechat_redirect)所用的工具。）

![](https://archive.is/Salxo/d90c0f2d1278f95a10adfa853be50f60b5c8c0c9)

### 交易

本质上，在区块链上做大部分事情，包括发文章，都是交易。

很简单，点击 MetaMask，按照流程完成注册，然后点击 Send 按钮发起一个交易。

什么，没有以太币？你也可以点击 Buy 按钮，购买以太币。因为我们在美国，此处就用美国兑换方式 Coinbase 演示。

输入你想花多少钱，输入你的电子邮件地址，买完之后会邮件告知，以太币会打入你的钱包。

![](https://archive.is/Salxo/375a4b6b393d90ed1097c6f03f37dd9895bbf7dd)]

你的银行可能会阻止你以太币这样的数字货币，请你通过和银行联系解决问题，或者找会玩数字货币的朋友给你转一点以太币。

接下来，你有以太币了，可以给自己转账了。

你需要在下面的 Transaction Data (Optional) 里面填写你想发布的内容。

![](https://archive.is/Salxo/59e50a847126eae22a95b91ca870ea5ea7b18bcb)

内容需要转换为 16 进制码，还要在代码之前加上固定头部“0x”以表示 16 进制。这里建议你把文字翻译成英文，因为英文 (UTF-8) 转换到 16 进制是最方便的。区块 5490403 就是这样做的。

![](https://archive.is/Salxo/187c31e4562c6f16332922cb2ea56a53c73ab9cf)

其实这个功能本来是用来做备注用的，因为区块链交易没有什么名目，最后要靠备注来标记这笔钱用来投资还是买酒了。

接下来，MetaMask 会提醒你设置这笔交易的手续费 (Gas)。

![](https://archive.is/Salxo/129f666162c90763eb2dc5ab9e70213af9b625d8)

“手续费”是个值得说的东西。理论上，在以太坊或者任何公链上交易，是可以不支付手续费的，但实际不给手续费不可能交易成功。因为每笔交易的背后都是所谓的矿工在执行，当交易量过大的时候（其实一直很多）就会出现交易阻塞，这时矿工先执行谁就要看手续费的多少了。

设置好手续费，点接受，就好了！

![](https://archive.is/Salxo/300b1910951205beee726a29793b5db97041ec91)


### 永不消逝的电波

前面提到，以太坊是一个公链，交易完成后就登录在一个账本上，而这个账本也是公开的。

全球有 16646 个以太坊节点，也就是 16646 本完全同步的账本。一旦写入，除非这 16646 个节点都下线并被摧毁，你的文章总有一份保存在世界的某个地方，就像永不消逝的电波一样……

查看这段信息，以及整个交易，也有很多方式。比如 Etherscan 网站，你可以理解为区块链是一个硬盘，而像 Etherscan 这样的网站或者软件，就是文件浏览器。

![](https://archive.is/Salxo/1fca697412963206c627713487c2429a9382a3a9)

不必多说，给自己设个小目标吧：在这星期内完成一次交易，把你喜欢的文章保存到以太坊或者任何其他的公链上。

**只需要一套煎饼的钱，你也可以让那些站在阴影里的人明白：正义永不缺席，正义的声音也不会消失。**

---

**记者** | **活动策划执行** | **BD** | **微信运营**
以上职位接受全职/实习硅星人是 PingWest品玩旗下立足中美的中文泛科技新媒体深度精辟，前沿有趣还不赶快上车？（点击下方阅读原文查看 JD 及联系方式）

![](https://archive.is/Salxo/cb0c1362ee5a32d4847b70304ac0db6922ff4c28)

![](https://archive.is/Salxo/1c45882237028e5792b7add3307ef18631119645.png) 

受苹果公司新规定影响，微信 iOS 版的赞赏功能被关闭，可通过二维码转账支持公众号。 