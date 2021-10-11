# Networld X 2021 ハンズオン Docker / Kubernetes を触ってみよう  

DockerやKubernetesを実際に触ってみるためのハンズオンです。
ハンズオン内容はネットワールド社内で体験してみるために公開している内容をそのまま利用しています。  

ハンズオンはコマンドラインでの操作に慣れている方であれば、2~3時間で完了します。


## 稼働環境
環境はAzure Lab Serviceを利用しており、下記のコンポーネントで構成されています。
- Windows + Vagrant + Hyper-V  

参加者の方それぞれに専用の環境が割り当てられます。

> Vagrantとは
> HashiCorp社製の違う環境に移行可能な開発環境を簡単に構築・管理し、配布することができる開発環境作成ツールです。
> 今回はVagrantを使ってHyper-V上にVMをデプロイしていますが特段操作を覚える必要はありません。  

### ホスト
LabService上の1台のHyper-Vホストを利用しています。  

|||
|:--|:--|
|OS|Windows Server 2019|
|CPU|8Core|
|mem|32GB|
|Disk|100GB|
|Hyper-V| |
|Vagrant| version 2.2.16|

### Docker ハンズオン環境
Hyper-VのゲストOSとして下記を稼働させてDockerのハンズオンを実施していただきます。

|||
|:--|:--|
|台数|1|
|OS|AlmaLinux release 8.4 (Electric Cheetah)|
|CPU|4Core|
|mem|4GB|
|Disk|20GB|

#### Kubernetes ハンズオン環境
Hyper-VのゲストOSとして下記を稼働させてKubernetesのハンズオンを実施していただきます。

|||
|:--|:--|
|役割|Master Node|
|台数|1|
|OS|AlmaLinux release 8.4 (Electric Cheetah)|
|CPU|4Core|
|mem|4GB|
|Disk|20GB|

|||
|:--|:--|
|役割|Worker Node|
|台数|3|
|OS|AlmaLinux release 8.4 (Electric Cheetah)|
|CPU|4Core|
|mem|4GB|
|Disk|20GB|


## ハンズオン内容について  
ハンズオン内容はまだ触ったことのない人向けです。  
座学はありませんのでWeb上にある基礎的な資料をご確認ください。
Web上に様々な資料がございますが、[こちらの資料](https://www.slideshare.net/KoheiTokunaga/ss-122754942)がわかりやすいと思います。

### ハンズオンの進め方  
DockerのハンズオンとKubernetesのハンズオンは別々に構成されています。  
どちらから始めていただいても問題ないですし、どちらかだけ実施でも問題ありません。

環境は専用の環境となりますので、ご自身で試したい内容などもぜひ試してみてください。  

[Dockerのハンズオンを始める方はこちら](hyper-v/docker_almalinux/README.md)  
[Kubernetesのハンズオンを始める方はこちら](hyper-v/k8s/README.md)  



