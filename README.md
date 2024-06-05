# learn-optimism

1.  搭建layer2 rollup
    - https://docs.optimism.io/builders/chain-operators/tutorials/create-l2-rollup
2.  构建optimism私链
    - https://learnblockchain.cn/article/5800
3.  使用OP Stack搭建自己的Layer2
    - https://github.com/qingfengzxr/optimism_study_group/blob/main/article/op-stack/%E4%BD%BF%E7%94%A8OP%20Stack%E6%90%AD%E5%BB%BA%E8%87%AA%E5%B7%B1%E7%9A%84Layer2.md
4.  How to run a Custom Gas Token chain
    - https://oplabs.notion.site/EXTERNAL-How-to-run-a-Custom-Gas-Token-chain-d88c68306f934790be051f87213a0b1d
5.  Enable Custom Gas Token on OP Stack
    - https://gov.optimism.io/t/enable-custom-gas-token-on-op-stack/7834
6.  Custom Gas Token Spec
    - https://specs.optimism.io/protocol/granite/custom-gas-token.html
7.  GTON as gas
    - https://github.com/GTON-capital/GTON-Network/commit/89426812c9989bf344def1b8596477b88adb5a21
8.  Swap Sepolia-eth and bridge to sepolia
    - https://app.uniswap.org/explore/tokens/arbitrum/0xe71bdfe1df69284f00ee185cf0d95d0c7680c0d4
    - https://testnetbridge.com/sepolia
9.  Optimism和OP Stack学习
    - https://learnblockchain.cn/article/7545 
10. Understanding Optimism Codebase (CN)
    - https://github.com/joohhnnn/Understanding-Optimism-Codebase-CN/blob/main/README.md
11. Optimistic Rollup 的挑戰機制（一）：Optimism OVM 1.0
    - https://medium.com/taipei-ethereum-meetup/optimistic-rollup-%E7%9A%84%E6%8C%91%E6%88%B0%E6%A9%9F%E5%88%B6-%E4%B8%80-optimism-ovm-1-0-2b6a8e9d64cd
12. 從 Rollups 來聊聊以太坊 Layer2 的演進
    - https://medium.com/taipei-ethereum-meetup/%E5%BE%9E-rollups-%E4%BE%86%E8%81%8A%E8%81%8A%E4%BB%A5%E5%A4%AA%E5%9D%8A-layer2-%E7%9A%84%E6%BC%94%E9%80%B2-c52d6a868411
13. Rollups = Bridges + Blockchains
    - https://ethresear.ch/t/rollups-bridges-blockchains/15739/4
14. How Rollups Actually Work
    - https://dba.mirror.xyz/LYUb_Y2huJhNUw_z8ltqui2d6KY8Fc3t_cnSE9rDL_o
15. op-geth diff geth
    - https://op-geth.optimism.io/
16. ZK Rollup & Optimistic Rollup
    - https://medium.com/coinmonks/zk-rollup-optimistic-rollup-70c01295231b
17. Rollup 的 Force Inclusion 機制介紹
    https://medium.com/taipei-ethereum-meetup/rollup-force-inclusion-mechanism-and-implementations-overview-0853ded0dffa
18. Fault Proofs Changes launch on 2024.06
    - https://docs.optimism.io/builders/notices/fp-changes
19. Optimism 源码浅析
    - https://godorz.info/2022/04/optimism-notes/
20. 6 high-value tutorials
    - https://github.com/ethereum-optimism/docs/issues/73#issuecomment-1828774941
21. production op stack chain operator guide
    - https://github.com/ethereum-optimism/docs/issues/367
22. op-geth故障修复
    - https://github.com/ethereum-optimism/op-geth/issues/130
23. 备份 op-geth
    - https://github.com/ethereum-optimism/developers/discussions/17#discussioncomment-9424817
24. Op链紧急停止
    - https://www.aicoin.com/zh-CN/article/399544
25. Sequencer和Proposer失败，L2如何实施自我排序和紧急出口机制
    - https://www.theblockbeats.info/news/47939?from=telegram
    - https://cloud.tencent.com/developer/news/1125413
26. lock(L1)-deposit(L2)-withdraw(L2)-unlock(L1)
    - arbitrum:
      - (1) 排序器故障(deposit): 基金会集中运营; 出现异常时，用户可以通过L1在L2网络上强制交易
      - (2) 验证器故障(withdraw): 13个白名单实体组成欺诈证明系统; 出现异常6天8小时后，任何人都可以成为验证者并进行提款
      - (3) rollup合约升级(最坏情况下可以提取所有资产)退出窗口(unlock): 2天 (https://l2beat.com/scaling/projects/arbitrum#risk-analysis)
      - (4) Fast Exit / Liquidity Exit: 第三方桥(https://docs.arbitrum.io/intro/glossary#fast-exit--liquidity-exit)
      - (5) 可以绕过sequencer: force-inclusion(https://docs.arbitrum.io/learn-more/faq#can-i-withdraw-my-funds-from-arbitrum-back-to-ethereum-without-going-through-the-sequencer-what-about-funds-that-are-in-a-contract)
      - (6) 可以在L1上操作提取L2上的资产
    - optmism:
      - (1) 排序器故障(deposit):基金会集中运行; 出现异常时，用户可以通过L1在L2网络上强制交易
      - (2) 验证器故障(withdraw): 基金会集中运行; 当验证器离线时，用户将无法从L2提现到L1
      - (3) rollup合约升级(最坏情况下可以提取所有资产)退出窗口(unlock): None(基金会可随时升级合约或暂停bridge) (https://l2beat.com/scaling/projects/optimism#risk-analysis)
      - (4) Fast Exit / Liquidity Exit: 第三方桥?
      - (5) 可以绕过sequencer: https://docs.optimism.io/stack/protocol/outages#bypassing-the-sequencer
      - (6) 在L1上操作提取L2上的资产 
27. 用原生 L2 代幣來支付交易手續費
    https://medium.com/taipei-ethereum-meetup/l2-token-as-gas-fee-pros-and-cons-70c821076313
28. custom-gas-token-bridge
    https://github.com/JoinOrigami/custom-gas-token-bridge/tree/main
29. 

