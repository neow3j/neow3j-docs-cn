<div class="oneclicknode-container">
    <a class="oneclicknode-btn" href="https://marketplace.digitalocean.com/apps/1clicknode-for-neo" target="_blank" 
    style="color: #FFFFFF"> 
      ⌛ Don't waste time setting up a Neo Node. 👉 Use 1ClickNode, it's free!
    </a>
</div>
<div style="text-align: center">
    <img src="images/neow3j-neo3.png" alt="Logo" id="logo">
</div>


<h1 id="cover-header">neow3j <small>3.23.0</small></h1>

Neow3j 是一个开发工具包，提供简单且可靠的 Java 平台开发工具（包括 Java、Kotlin 和 Android），以帮助Neo 上的去中心化应用（dApps）和智能合约的开发。该项目是由 Neo 社区开发并由 [AxLabs](https://axlabs.com) 维护的开源项目。

<table>
  <tr>
    <td>
      <a href="https://marketplace.digitalocean.com/apps/1clicknode-for-neo">
        <img src="https://cdn.axlabs.net/1clicknode-logos/1clicknode-logo-for-light.png" width="200" 
        alt="1ClickNode Logo">
      </a>
    </td>
    <td>
      如果需要为 dApp 提供测试网或主网的 Neo 节点，但不想花费太长时间进行设置，请查看 <a href="https://marketplace.digitalocean.com/apps/1clicknode-for-neo">1ClickNode</a>.
    </td>
  </tr>
</table>


## 功能特性 🚀

- 支持 Neo 节点的 JSON-RPC API
- 基于观察者模式监控 Neo 区块链
- 支持 NEP-6 钱包和账户模型
- 多签名地址工具
- 受密码保护的私钥（NEP-2）
- 助记词工具（BIP-39）
- 构建、签名和发送交易
- 代币转账
- 智能合约调用
- 智能合约部署
- 使用 Java 开发和编译智能合约
- 支持 Android API 24，覆盖 [49%](https://developer.android.com/about/dashboards/)（[约10亿台设备](https://www.youtube.com/watch?v=vWLcyFtni6U#t=2m46s)）的活跃 Android 设备 

## 快速入门 

Neow3j 由用于 dApp 开发的 **SDK** 和用于智能合约开发的 **devpack** 组成。以下将介绍如何快速上手这些工具。

### SDK

要使用 neow3j SDK 的所有功能，请将 `io.neow3j:contract` 依赖项添加到您的项目中。

__Gradle__

```groovy
implementation 'io.neow3j:contract:3.23.0'
```

__Maven__

```xml
<dependency>
    <groupId>io.neow3j</groupId>
    <artifactId>contract</artifactId>
    <version>3.23.0</version>
</dependency>
```

### Devpack

neow3j devpack 是一个 Java 库，提供编写 Neo 智能合约所需的 Neo 特定功能。如果想尝试使用 devpack，请将 `io.neow3j:devpack` 依赖项添加到项目中。

__Gradle__

```groovy
implementation 'io.neow3j:devpack:3.23.0'
```

__Maven__

```xml
<dependency>
    <groupId>io.neow3j</groupId>
    <artifactId>devpack</artifactId>
    <version>3.23.0</version>
</dependency>
```

有关如何编译智能合约的信息，请前往 [Setup & Compilation](neo-n3/smart_contract_development/setup_and_compilation.md)。

## 软件需求

Neow3j 要求使用 **Java 8** 或更高版本。对于 Android 应用，需要使用 API 24 或以上级别。

Neow3j **不包含区块链节点**，也就是说，它既不会与其他节点同步，也不会在本地存储或验证区块链信息。Neow3j 依赖于与 Neo 节点的连接来获取区块链信息。如果您想运行自己的节点，请参考 [官方文档](https://docs.neo.org/v3/docs/en-us/node/introduction.html) 配置节点。对于本地开发，推荐使用 [Neo Express](https://github.com/neo-project/neo-express)。

## 为什么叫 "neow3j" ？🤔

该项目基于 [web3j](https://web3j.io)，但专注于 NEO。因此在 "neo" 的名字后面加上了 "w3j" 后缀，即 "neow3j"。

接下来，想象一下 [Bongo Cat](https://knowyourmeme.com/memes/bongo-cat) 在 NEO 节点上演奏，不是 "meow"，而是 "neow"，是不是很自然？:-)

## 版本管理

首先，不要因为名字中的 *3* 而感到困惑，这与 Neo 的版本无关。

Neow3j 的版本控制部分遵循语义化版本控制的变体。为了与 Neo 的主要版本保持一致，neow3j 的第一个数字固定为当前 Neo 版本。例如，neow3j 3.x.x 代表与 Neo N3 兼容的库版本。因此，版本号的语义向右移动一位。第二个数字递增意味着应用了不兼容的变更。第三个数字递增则表示添加了向后兼容的功能和错误修复。

## 捐赠 💰

想支持 neow3j 的开发吗，可以向以下地址进行捐赠:

| Crypto | 地址                                         |
| ------ | -------------------------------------------- |
| NEO N3 | `NfhQyNmMCLCKaaazL6gbvYxtkZNGVb8kRn`         |
| ETH    | `0xe85EbabD96943655e2DcaC44d3F21DC75F403B2f` |
| BTC    | `3L4br7KQ8DCJEZ77nBjJfrukWEdVRXoKiy`         |


## 致谢与鸣谢 🙏

* [NEO Foundation](https://neo.org/team) & [NEO Global Development (NGD)](https://neo.org/team)
* 本项目在很大程度上基于 [web3j](https://web3j.io)，最新版本为此 [commit](https://github.com/web3j/web3j/commit/2a259ece9736c0338fbb66b1be4c04aba0855254)。对此我们深表感谢。😄
