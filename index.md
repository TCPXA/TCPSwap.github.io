# TCP钱包教程
## 1.安装与设置Polkadot.js
Polkadot.js可以通过Chrome浏览器下载。在本教程中，我们将使用Chrome版本进行演示，不同平台的流程大致相同。 首先，请跳转至[Polkadot.js](https://chrome.google.com/webstore/detail/polkadot{js}-extension/mopnmbcafieddcagagdcbnhejhlodfdd)下载页面或[火狐Polkadot.js](http://www.quarkswap.network/wallet/)下载。选择您使用的平台，然后按以下步骤在设备中安装Polkadot.js。快捷安装，超级简单！ 接下来，按照App指定的设置进行操作。点击"创建钱包”（ Create a Account）。在私密性较强的设备（最好是与网络断连的设备）中输入备份的助记词（seed phrase）。如果没有妥善存储助记词，在设备损坏或丢失时，很可能无法找回资金。因此，请在下一页确认已将助记词写下并妥善保管。 设置即将完成！现在画面中显示钱包，您可以发送和接收资金。
谷歌浏览器插件地址

### 这里为您提供了谷歌与火狐的插件地址
谷歌浏览器插件地址
- On Chrome, install via [Chrome web store](https://chrome.google.com/webstore/detail/polkadot{js}-extension/mopnmbcafieddcagagdcbnhejhlodfdd)


火狐浏览器插件地址
- On Firefox, install via [Firefox add-ons](https://addons.mozilla.org/en-US/firefox/addon/polkadot-js-extension/)

接下来以Chrome为案例，下载完后点击右上角小图标（如下图）

![image](https://user-images.githubusercontent.com/89764116/131432573-28babec1-51e5-429a-bafb-af2976a8ee69.png)

会弹出扩展程序窗口，点击polkadot{.js}extension出现Accounts窗口，点击窗口右上角的＋号，选择Import account from pre-existing seed，输入你的助记词并保存，最后刷新此页面会弹出授权页面（如下图）点Yes即可在右上角看到您的账户（如果没有显示就多次刷新）

![6ca708580181451d910a1811765414a](https://user-images.githubusercontent.com/89764116/131433079-61673333-0a99-4237-9e64-04bb405b6f56.png)


## 币安链测试币领取教程
安装与设置MetaMask MetaMask可以通过Chrome和Firefox浏览器下载，移动端支持iOS和Android平台。在本教程中，我们将使用Firefox版本进行演示，不同平台的流程大致相同。 首先，请跳转至[MetaMask](https://chrome.google.com/webstore/detail/metamask/nkbihfbeogaeaoehlefnkodbefgpgknn?utm_source=chrome-ntp-icon)下载页面。选择您使用的平台，然后按以下步骤在设备中安装MetaMask。快捷安装，超级简单！ 接下来，按照App指定的设置进行操作。点击"创建钱包”（ Create a Wallet）。在私密性较强的设备（最好是与网络断连的设备）中输入备份的助记词（seed phrase）。如果没有妥善存储助记词，在设备损坏或丢失时，很可能无法找回资金。因此，请在下一页确认已将助记词写下并妥善保管。 设置即将完成！现在画面中显示钱包，您可以发送和接收资金。

![image](https://user-images.githubusercontent.com/89764116/131434412-dcac8637-c458-4de5-93c3-91024b6f43c5.png)

初始化的MetaMask钱包。

### 配置钱包
在安装与设置過後，您可能会立即意识到，我们仍在使用[以太坊](https://academy.binance.com/zh/articles/what-is-ethereum)钱包。最幸运的情况是，该钱包无法与币安智能链dApps结合使用；最糟糕的狀况是，您可能将资金发送至无效地址，造成资金损失。

因此，我们需要对设置进行调整。访问“设置”（Settings）页面，将钱包指向币安智能链节点（Binance Smart Chain nodes）

![image](https://user-images.githubusercontent.com/89764116/131434603-288fd655-d75c-4b94-b74c-64cee84abc89.png)
在设置页面中，找到“网络”（Networks）菜单。
![image](https://user-images.githubusercontent.com/89764116/131434662-61171dad-9cef-48ce-99d9-a7e3150b5e1d.png)
“网络”（Networks）菜单。

点击右上角的“添加网络”（Add Networks），我们需要在这里手动添加币安智能链，因为它原本未与MetaMask绑定。请注意，在此处可以使用两个网络：测试网（ Testnet ）或主网络（Mainnet）。以下是每种网络对应填写的参数。

测试网

网络名称（ Network Name）：Smart Chain - Testnet

新的RPC URL（ New RPC URL）：https://data-seed-prebsc-1-s1.binance.org:8545/

智能链ID（ChainID）：97

符号（Symbol）：BNB

区块浏览器URL（Block Explorer URL）：https://testnet.bscscan.com

在本教程中，我们将使用测试网作示范，但如果您希望使用MetaMask中的主网络转移币安币或币安智能链的其他代币，建议同时添加两个网络。

在保存（Save）网络并返回主页面后，您需要注意两点：1.网络已自动设置为刚输入的网络；2.计价单位由以太坊（ETH）转换为币安币（BNB）。

![image](https://user-images.githubusercontent.com/89764116/131434874-520a06ec-1f2e-4eb4-9cff-88754d3ac430.png)

测试网连接成功

### 领取测试币
首先，不要被以太坊的标志所迷惑，我们已经切换到币安智能链（BSC）的测试网。接下来，我们需要获取一些资金，以便演示相关操作。将光标悬停于帐户1之上，点击您的地址并复制到剪贴板。然后，访问币安智能链“[水龙头”(Faucet)](https://testnet.binance.org/faucet-smart)，将其粘贴到表单

![image](https://user-images.githubusercontent.com/89764116/131436501-10c834f4-b1d1-4e9b-ba30-9a54423c9456.png)
如需测试支持[BEP-20](https://academy.binance.com/en/glossary/bep-20)代币的应用程序，可能需要使用锚定代币（Peggy coins）。它们是币安智能链发行的简单代币，与其他链上的资产（例如比特币、瑞波币、泰达币等）挂钩，因此可以在不同链上以相同价格进行交易。

我们会使用币安币作相关演示。点击“接收币安币”（Give me BNB）下拉菜单，选择希望接收的金额。请耐心等待几分钟，资金到账后将在您的测试网钱包中显示。
![image](https://user-images.githubusercontent.com/89764116/131436636-e8c9809f-0ca5-493d-9a50-1f0a05b137f1.png)

接下来点添加代币，在代币合约地址输入：0x8559e7DCe5cfe45306eBc1118cFeb52A6dD6A1F6
![image](https://user-images.githubusercontent.com/89764116/131436846-48c0c6ad-c792-492d-a119-cca8b31eb82e.png)

下一步，并添加

![image](https://user-images.githubusercontent.com/89764116/131437085-9a353544-edb8-4c5a-b6c5-eb58854374b0.png)

## 以上即本次全部教程
