---
layout: page
feature_image: "https://picsum.photos/1300/400?image=879"
title: Selected Publications
permalink: /publications/
---
[Google Scholar](https://scholar.google.com/citations?user=JB1uRvQAAAAJ&hl=en) [DBLP](https://dblp.org/pid/68/6577-3.html) [ORCID](https://orcid.org/0000-0003-2063-1769)

* **Security-Performance Tradeoff in DAG-based Proof-of-Work Blockchain Protocols.** Shichen Wu, Puwen Wei\*, Ren Zhang\*, and Bowen Jiang. NDSS 2024. [[eprint](https://eprint.iacr.org/2023/1089)]  
\* corresponding authors

Contrary to popular belief, DAG-based protocols, like their chain-based predecessors, are not immune to the security-performance tradeoff.

* **Polynomial IOPs for Memory Consistency Checks in Zero-Knowledge Virtual Machines.** Yuncong Zhang, Shi-Feng Sun, Ren Zhang, and Dawu Gu. ASIACRYPT 2023. [[eprint](https://eprint.iacr.org/2023/1555)] [[youtube](https://youtu.be/ufInKsFa7k4?si=4tytv_kJ-cDsMpyg&t=5231)] [[bilibili](https://www.bilibili.com/video/BV1eg4y1o7Jp/?spm_id_from=333.337.search-card.all.click&vd_source=b4d10a772adba7121193377a41d4caaf)]

Zero-knowledge virtual machines (ZKVMs) rely heavily on random-access memory, a component that has been understudied despite its influence on performance.

* **When is Slower Block Propagation More Profitable for Large Miners?** Zhichun Lu and Ren Zhang*. ESORICS 2023. [[eprint](https://eprint.iacr.org/2023/891)]  
\* corresponding author

For years, Bitcoin miners put little efforts into adopting several widely-acclaimed block acceleration techniques, which, as some argued, would secure their revenues. Why?

* **VOProof: Efficient zkSNARKs from Vector Oracle Compilers.** Yuncong Zhang, Alan Szepieniec, Ren Zhang\*, Shi-feng Sun\*, Geng Wang, and Dawu Gu*. ACM CCS 2022. [[eprint](https://eprint.iacr.org/2021/710)] [[youtube](https://www.youtube.com/watch?v=uzOW0D7nvpo)] [[bilibili](https://www.bilibili.com/video/BV1vx1NY8EZK/?vd_source=584ee066ee4a8e89fcbd3788bbd817a4)]  
\* corresponding authors

We propose a novel workflow for designing and implementing zkSNARKs that conceals most algebraic and cryptographic operations inside the compiler, eliminating the need for designers to grasp these complex and error-prone procedures.

* **Crystal: Enhancing Blockchain Mining Transparency With Quorum Certificate.** Jianyu Niu, Fangyu Gai, Runchao Han, Ren Zhang, Yinqian Zhang, and Chen Feng. IEEE TDSC 2022. [[arXiv](https://arxiv.org/abs/2312.00741)]

Many Proof-of-Stake protocols utilize a committee to sign each block, enhancing its security. Could a similar approach be applied to Proof-of-Work protocols?

* **Analysing and Improving Shard Allocation Protocols for Sharded Blockchains.** Runchao Han, Jiangshan Yu, and Ren Zhang. ACM AFT 2022. [[eprint](https://eprint.iacr.org/2020/943)]  
Selected as ["Paper of the Week"](https://zkcapital.substack.com/) (Issue #68) by ZK Capital.

Maintaining a balanced distribution of nodes across shards is a challenging task. We explore the underlying reasons and present a viable solution.

* **NC-Max: Breaking the Security-Performance Tradeoff in Nakamoto Consensus.** Ren Zhang, Dingwei Zhang, Quake Wang, Shichen Wu, Jan Xie, and Bart Preneel. NDSS 2022. [[eprint](https://eprint.iacr.org/2020/1101)] [[youtube](https://www.youtube.com/watch?v=CyT3mPOROes), 23 min] [[bilibili](https://www.bilibili.com/video/BV1XP411n7qV/?spm_id_from=333.337.search-card.all.click&vd_source=b4d10a772adba7121193377a41d4caaf), 23 min]  
NC-Max is implemented in Nervos CKB. [[Nervos RFC](https://github.com/nervosnetwork/rfcs/blob/master/rfcs/0020-ckb-consensus-protocol/0020-ckb-consensus-protocol.md)]  
Invited to present at IJTCS 2020. [[bilibili](https://www.bilibili.com/video/BV1NT4y1A7Wk/?spm_id_from=333.337.search-card.all.click&vd_source=b4d10a772adba7121193377a41d4caaf), 55 min]

By decoupling transaction synchronization from confirmation, we can fully exhaust the network's throughput and substantially reduce the transaction confirmation latency.

* **Ghost in the Binder: Binder Transaction Redirection Attacks in Android System Services.** Xiaobo Xiang, Ren Zhang, Hanxiang Wen, Xiaorui Gong, and Baoxu Liu. ACM CCS 2021. [[Open Access](https://dl.acm.org/doi/pdf/10.1145/3460120.3484801)]

Binder, Android's primary mechanism for inter-process communication (IPC), employs a client-server model where applications act as clients and system services serve as servers. While most security measures focus on protecting against client-side attacks, the system remains vulnerable when an attacker assumes the role of a Binder server.

* **Authenticated and Auditable Data Sharing via Smart Contract.** Vincent Reniers, Yuan Gao, Ren Zhang, Paolo Viviani, Akash Madhusudan, Bert Lagaisse, Svetla Nikova, Dimitri Van Landuyt, Riccardo Lombardi, Bart Preneel, and Wouter Joosen. ACM SAC 2020. [[pdf](https://lirias.kuleuven.be/retrieve/596647/)]

This task is extracted from a real-world application. One party needs to distribute an encryption key to multiple parties using a blockchain, knowing only their public keys. How can we ensure (1) that all parties receive the same key, and (2) that any discrepancies can be publicly proven without compromising the key's secrecy?

* **Lay Down the Common Metrics: Evaluating Proof-of-Work Consensus Protocols' Security.** Ren Zhang and Bart Preneel. IEEE S&P 2019. [[pdf](https://www.esat.kuleuven.be/cosic/publications/article-3005.pdf)] [[code](https://github.com/nirenzang/PoWSecurity)] [[slides](https://www.ieee-security.org/TC/SP2019/SP19-Slides-pdfs/Ren_Zhang_02_-CommonMetrics.pdf)] [[One-minute introduction](https://www.youtube.com/watch?v=Q50bDTMzBKs)] [[2019 S&P talk](https://www.youtube.com/watch?v=Gs9TSpFSK_E), 18 min]  
Invited to present at "Master Workshop: Layer I solutions" organized by Binary District in 2018. [[youtube](https://www.youtube.com/watch?v=UV5E-DjCHn4), 31 min]  
Invited to present at Stanford Blockchain Conference 2019. [[youtube](https://www.youtube.com/watch?v=HiIQcdnKZBQ&list=PLxiUDysqkJ9xTGggKpeHwdANjPnM4Fxv3&index=28), 24 min]  
Invited to present at AFT 2019 as "outstanding paper of the year".

Many PoW protocols claim superior security to Nakamoto Consensus. Do they deliver?

* **On the Necessity of a Prescribed Block Validity Consensus: Analyzing Bitcoin Unlimited Mining Protocol.** Ren Zhang and Bart Preneel. CoNEXT 2017. [[eprint](https://eprint.iacr.org/2017/686)] [[code](https://github.com/nirenzang/Analyzing-Bitcoin-Unlimited)] [[reddit discussion](https://www.reddit.com/r/btc/comments/6o7l2t/on_the_necessity_of_a_prescribed_block_validity/)]  
Invited to present at Breaking Bitcoin 2017. [[youtube](https://www.youtube.com/live/0WCaoGiAOHE?si=To1zjz8CLXw2cEgW&t=4163)]  
Invited to present at CESC 2017. [[youtube](https://www.youtube.com/watch?v=P35M74KcLmA)]

BU was once the most popular Bitcoin scaling proposal among the miners. Is it as secure as its supporters claimed?

* **Publish or Perish: A Backward-Compatible Defense against Selfish Mining in Bitcoin.** Ren Zhang and Bart Preneel. CT-RSA 2017. [[pdf](https://www.esat.kuleuven.be/cosic/publications/article-2746.pdf)] [[code](https://github.com/nirenzang/Publish-or-Perish)]  
Presented by Max Fang at BPASE 2018. [[youtube](https://www.youtube.com/watch?v=ujz3sXpNgtc)]

My first attempt to defend against selfish mining by encouraging miners to ignore late blocks.  
*Post-publication note:* I would not recommend a faithful implementation of this design. Now that we understand PoW better, the design and analysis presented in this paper could benefit from further refinement.

* **Censorship-Resistant and Privacy-Preserving Distributed Web Search.** Michael Herrmann, Ren Zhang, Kai-Chun Ning, Claudia Diaz, and Bart Preneel. P2P 2014. [[pdf](https://git.gnunet.org/bibliography.git/plain/docs/DistributedSearch2014Hermann.pdf)]

Existing distributed web search engines (Faroo, Seeks, and Yacy) do not offer adequate protection against censorship and de-anonymization attacks. We identify the security properties and design new protocols to achieve them.

* **Making Eclipse Attacks Computationally Infeasible in Large-Scale DHTs.** Ren Zhang, Jianyu Zhang, Yu Chen, Nanhao Qin, Bingshuang Liu, and Yuan Zhang. IPCCC 2011. [[pdf]({{site.baseurl}}/assets/Making-Eclipse-Attacks-Computationally-Infeasible-in-Large-Scale-DHTs.pdf)]

By requiring every user to complete a proof-of-work puzzle, the DHT network discourages attackers from monopolizing particular ID ranges, as this would necessitate significant computational resources.  
*Post-publication note:* This mechanism no longer works. The widespread availability of ASIC mining equipment has rendered PoW an ineffective defense against Sybil attacks. An attacker can easily overwhelm honest nodes by deploying specialized hardware.