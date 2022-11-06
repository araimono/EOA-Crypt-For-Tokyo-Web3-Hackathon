# EOA Crypt For Tokyo Web3 Hackathon
## プロダクト概要
現状ほとんどのパブリックBC/分散型ストレージではセンシティブな情報が記録できません。
多くのweb3プロダクトやサービスは、重要なデータ/ロジック部分をweb2領域に保持する必要があります。
この問題が解決できればBCや分散型ストレージ、さらにはweb3領域活用の幅が大きく広がるという仮説のもと、EOAを基盤とした暗号/復号とその利用を考えました。
【いわゆるweb3領域だけでどこまでデータの秘匿化が出来るのか?】【実用的範囲でweb2依存を減らし分散できるのか?】というテーマを検討していくきっかけにしたいという想いで、あえて【E2Eでの暗号/復号】【個人が関連データを保持/管理できる(自己主権)】【データおよびロジックはBC/分散型ストレージとクライアントサイドにのみ配置(リロケータブル)】【デプロイ後は開発者といえども一切関われない(Autonomos)】という要件定義のもとPoC実装を行いました。
【永続化させたいデータを、誰かに「人質」に取られることなく秘匿化し、選択的開示や分散配置を行える仕組み】をみんなで継続して考え、実現していく最初の第一歩が『EOA Crypt』です。

## Tech Stacks
Html、CSS、Javascript、wasm（C＋＋）、Webpack、Solidity、IPFS

## Block Chain
Ethereum Goerli Testnet Network

## repository
https://github.com/ukishima/EOA-Crypt-For-Tokyo-Web3-Hackathon

## contract
https://goerli.etherscan.io/address/0x362bca0228740b2420d9df54b7f5bb53f266afd1

## Demo Page
TBD

## Help Page
https://ukishima.github.io/EOA-Crypt-For-Tokyo-Web3-Hackathon/docs/
