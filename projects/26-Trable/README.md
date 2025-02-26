## 基本资料	

### 项目名称

Trable

### 项目立项日期

2023年12月

## 项目整体简介

### Project background

随着Web3生态的不断壮大，拥有数字货币的地址数量逐年增加，自然有越来越多的人使用加密货币进行产品和服务的支付，但如今想要走完购买的全流程非常繁琐（尤其涉及到境外产品时），中间需经历数次的资产置换。这个过程不仅耗时，还会对用户原先的资产产生多次消耗，成本高昂。

对此我们的项目提出解决方案，优化资产转换流程，提升用户在Web3的体验。并且后疫情时代，旅游业蓬勃发展，Trable进入这个庞大的市场，旨在提供独特的价值主张。


<h3 align="center">
  链上-DEX-CEX-法币-非本国法币支付
  
    ❌DEX转换磨损
    ❌CEX交易手续费  
    ❌出金汇率磨损
    ❌非本国发币支付货币转换费
    
    ✅一步签名即到位 仅收取较少费用
    
</h3>

### Project Introduction

Trable是一款针对加密货币支付的境外旅游产品Dapp应用。此应用通过集成Uniswap V4等技术，有效地简化了用户使用加密货币订购境外旅游产品的流程，缩减所需时间及降低DEX/CEX货币转换的成本。

用户仅需选择所需的支付加密货币并完成签名，即可轻松在本Dapp预订境外旅游产品。我们解决了个人外汇额度限制和支付工具不足的问题，提供了必要的法币支付支持。同时，我们在链上实时监控资金流向，确保资金安全。在整个过程中，只会收取一次手续费，为用户的订购体验提供全面保障。

Trable is a DApp application designed for overseas travel products with a focus on cryptocurrency payments. By integrating technologies such as Uniswap V4, this application effectively streamlines the process for users to order overseas travel products using cryptocurrency, reducing the time required and lowering the cost of DEX-CEX currency conversions.

Users simply need to select the desired cryptocurrency for payment and complete the signature, making it easy to book overseas travel products through this DApp. We address issues such as individual foreign exchange limits and insufficient payment tools by providing necessary fiat currency payment support. Additionally, we monitor the flow of funds in real-time on the blockchain to ensure the security of funds. Throughout the entire process, a single transaction fee is charged, offering comprehensive protection for the user's booking experience.



  <img src="https://github.com/Web3-Club/Trable/assets/76860915/7e5a55f1-1486-4de6-a28e-7080e046f19d" alt="25461702219436_ pic">

### 在黑客马拉松期间完成的代码功能

#### Solidity

#### Acala
我们团队一直在研究如何简化不同链上虚拟资产的交易流程，发现uniswap v4中讲所有的资金池部署在一个合约的方案具有优势，因此主要的思想还是基于uniswap v4。

但由于uniswap V4 现阶段使用的Bussiness license的4年商用限制问题，现阶段采用unswap v3的改进版进行代币质押兑换。

由于acala multi chain routing的特质很好的满足了团队的这一需求

因此团队技术正在逐步学习研究acala router，并且后续会在acala evm上开展更多的测试，并在本次黑客松期间尝试跑通整套流程

现阶段的痛点可以用acala multichain router解决

由于 uniswap v4现在的技术方案经过测试还有些不成熟，并且商业license也没有到达按期开放的时间节点，

所以团队前期采用自研的uniswap v3 trable，目前正在将合约部分迁移到acala multichain router。

我们由此希望去在本次黑客松 

主要使用 Asset Router的 LST 集成协议，允许用户通过类似于 一笔交易将 DOT等多链token 从 Polkadot 发送到 Acala 并交换到LST 跨链桥与其他链上的加密货币进行互操作，使用 XCM 交换到另一个平行链的方式，来尝试对比我们的uniswap trable方案 来完成构建在polkadot生态上的trable的跨链及swap交互实验。

### Project logo




### Key Dapp Features

- Support for fiat currency payments（法币支付支持）

确保旅游产品跨境crypto直接支付的便利性

- Fast transactions anytime, anywhere（随时随地、快速交易）

简化虚拟货币转移过程（多链资产转换）

- Save time and effort, lower loss（省时省力、更低损耗）

结合Uniswap V4 降低多种token的swap成本，减少不必要的原始资产的转换和支付磨损

- No need to consider personal foreign exchange restrictions（无需考虑个人外汇限制）

不受传统银行外汇限额的影响，更流畅的旅行体验

### Project demo 



## 黑客松期间计划完成的事项


### 区块链端



### 客户端

front-end



### 后端


## 黑客松期间所完成的事项



### 最终完成的功能点

### 完成的开发工作及代码结构

### PPT等大文件链接地址

https://docs.google.com/presentation/d/1YajFYiBXxBr2Q0o1F3PbKhmQ7hMsGFVRvAOra6DJ3pg/edit?usp=sharing

## 使用方法



## 测试

项目包含了针对合约功能的测试用例，确保了各项功能的正确性和安全性。

## 队员信息
Name: Yanbo
Introduction:

Yanbo is an experienced blockchain product manager with a deep understanding of technical challenges and project management in various areas of Web3.
Role: He possesses valuable expertise in public goods and leads the team's vision and overall strategy at Trable as an accomplished product manager.

GitHub:yanboishere
WeChat ID: YanboAtWeb3

Name：nuttt
Introduction：SEU EEer, building hacking with me!
GitHub: RbRe145
WeChat ID：zhj314816759

Name：Zijing
Introduction：BD Head of Go2Mars
Role：I am in charge of Trable business model 
GitHub: zijin79
WeChat ID：ZZJZZJ9248


Name: HH Tsang
Introduction:
Role:
GitHub: N/A
WeChat ID: N/A


