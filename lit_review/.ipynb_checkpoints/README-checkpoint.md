# Syscoin 4.0 Literature Review

* [Sidhu, Syscoin and its vision for the future](https://docs.google.com/document/d/1SC69GVFKhjeHu-Q6jam1VeooeW4z8WZeMOhbKrchDaI/edit?ts=6026d598#heading=h.ynvi12mdhgqf)
	* Working document for future blog post

## KNP Introductory Surveys

* [Clark et. al., Zero-knowledge proofs (ZKP): Privacy Preserving
Authentication, KPMG](https://published-prd.lanyonevents.com/published/rsaus19/sessionsFiles/13672/IDY-W02-Zero-Knowledge-ZK-Proofs_Privacy_Preserving-Authentication.pdf)
	* KPMP Conference Talk
	* Schematics for a digital identity model using ZKP

* [Nelson, Zero Knowledge Proofs (ZKP): Privacy Preserving Digital Identity, Amazon](https://www.youtube.com/watch?v=D4iUeVbib_k)
	* VP from Amazon

* [Boneh, Discrete Log based Zero-Knowledge Proofs](https://www.youtube.com/watch?v=wB3DlND7KEw)
	* Academic survey talk

## Non-interactive Zero Knowledge Proofs

* [Yun, Implementing a Zero Knowledge Proof](https://www.youtube.com/watch?v=sOKh7WQgwpw)
	* Technical nuts and bolts outline of Bulletproof implementation

* [Groth, Non-interactive Zero Knowledge](https://www.youtube.com/watch?v=BLqvqTjDZok)
	* Academic Introduction to NIZP

* [Coladangelo et. al., Non-Interactive Zero-Knowledge Arguments for QMA, with preprocessing](https://www.youtube.com/watch?v=24mN-_d5LVo)
	* Caltech conference paper on NIZK arguments

## ZK-STARKS

* [Ben-Sasson et. al, Scalable, transparent, and post-quantum secure computational integrity](https://eprint.iacr.org/2018/046.pdf)
	* Inaugural academic paper on zk-STARKS

* [Ben-Sasson, SNARKs and STARKs](https://www.youtube.com/watch?v=7BQqb8S1FA8&feature=youtu.be)
	* Lecture contrasting PCP, IOP, STIK, and STARKS and how they work together

* [Zero-knowledge Scalable Transparent Arguments of Knowledge](http://cryptowiki.net/index.php?title=Zero-knowledge_Scalable_Transparent_Arguments_of_Knowledge_(zk-STARKs))
	* Introduction to ZK-STARKS (academic)

* [Ben-Sasson, From PCP to ZK-STARK](https://cyber.biu.ac.il/wp-content/uploads/2019/02/2-BarIlan_Feb_2019.pdf)
	* Contrasts PCP, IOP, STIK, and STARKS and how they work together

* [Starkware, The Great Reddit Scaling Bake-off](https://medium.com/starkware/the-great-reddit-bake-off-2020-c93196bad9ce)
	* Reddit bake-off

## ZK-SNARKS

* [Drakes, Polynomial Commitments with Justin Drakes](https://www.youtube.com/watch?v=bz16BURH_u8&feature=emb_logo)
	* Another study on polynomial committments

## ZK-rollups

* [Scaling Ethereum on L2: Optimistic Rollups and ZK-Rollups](https://medium.com/interdax/ethereum-l2-optimistic-and-zk-rollups-dffa58870c93)
	* Good Optimistic Rollups and ZK-Rollups

## ZK-Sync

* [Matter Labs ,L2 scalability and zkSync](https://www.youtube.com/watch?v=el-9YYGN1nw)
	* Slides [here](https://docs.google.com/presentation/d/1DTLcEJVHWEx8XkoD6RVLhQBMgkpuUW8rSv4e5H7xbdc/edit#slide=id.p)

## Verifiable Delay Functions

* [Boheh, Verifiable Delay Functions](https://www.youtube.com/watch?v=dN-1q8c50q0&feature=youtu.be)
	* Introductory talk on VDF

## Ethereum and the EVM

* [Vitalik, Understanding the Ethereum Blockchain Protocol](https://www.youtube.com/watch?v=gjwr-7PgpN8)
	* Nice intro to the EVM

* [Robinson et. al., EVM: From Solidity to byte code, memory and storage](https://www.youtube.com/watch?v=RxL_1AfV7N4)
	* Overview of how Solidity is deployed and EVM opersting system

* [Hotchkiss, The 1.x Files: The State of Stateless Ethereum](https://blog.ethereum.org/2019/12/30/eth1x-files-state-of-stateless-ethereum/)
	* Good explaination of stateless Ethereum

* [Ramesh, Polynomial Commitments for Witness Compression for Ethereum 1.x](https://www.youtube.com/watch?v=1Iaxr6FP3VU)
	* Break down of Vitalik's post (Summer, 2020) on desired approach for witness compression

* [Mackay, Ethereum Virtual Machine](https://www.youtube.com/watch?v=ihHdvulWW40)
	* Discusses fundamentals behind the EVM

* [Wood, Ethereum Yellow Paper](https://ethereum.github.io/yellowpaper/paper.pdf)
	* Formal definition of the Ethereum protocol

* [Saldanha, Ethereum Yellow Paper Walkthrough](https://www.lucassaldanha.com/ethereum-yellow-paper-walkthrough-1/)
	* Step-by-step walkthrough of ETH yellow paper

* [Wood, Ethereum: So now we've built it, WTF is it!](https://www.youtube.com/watch?v=U_LK0t_qaPo)
	* Good refresher on Ethereuem's vision

* [Saini, Getting Deep Into Ethereum: How Data Is Stored In Ethereum?](https://hackernoon.com/getting-deep-into-ethereum-how-data-is-stored-in-ethereum-e3f669d96033)
	* Explores storage in Ethereum via various Tries in Ethereum (state, transactions, and storage)

* [Akhunov, Turbo Geth: What is it all about?](https://www.youtube.com/watch?v=oEpY4NkkeYQ&t=2663s)
	* Useful for understanding Ethereum storage Tries

* [Ethereum Data Strcuture](https://i.stack.imgur.com/afWDt.jpg)
	* Detailed breakdown of the ETH blockchain mechanisim


## ZKP Applications

* [Bloemen, Scalling DEXes](https://www.youtube.com/watch?v=qwtOJvFo6vs)
	* 0X technical fellow
	* How ZK is used at 0x to scale decentralized exchanges

* [Nascimento et. al., Zero Knowledge Proofs applied to Auctions](https://courses.csail.mit.edu/6.857/2019/project/18-doNascimento-Kumari-Ganesan.pdf)
	* MIT survey paper
	* Appliying zero knowledge proof systems to online auctions
	* Distinguishes between Interactive vs Non-interactive
	* Compares STARKS, SNARKS and Bulletproofs

## ZKP Implementation

* [Gluchowski, zkPorter: Composable Scalability in L2 Beyond zkRollup](https://medium.com/matter-labs/zkporter-composable-scalability-in-l2-beyond-zkrollup-2a30c4d69a75)
	* Presents a L2 scaling technique via zkRollup and sharding

* [CARIO, cairo-lang.org](https://www.cairo-lang.org/)
	* Turing-complete language for creating provable programs


## Misc

* [Buchanan, How To Create a General Election With a Single Signature for All Votes: Meet Boneh–Lynn–Shacham (BLS) signatures](https://medium.com/asecuritysite-when-bob-met-alice/boneh-lynn-shacham-bls-signatures-d053cf049aa8)

