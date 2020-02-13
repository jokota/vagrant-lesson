# Section 02 : インストール

OS・環境別にVagrantのインストール手順を説明します。

## 1. Mac + VirtualBox

### (1). VirtualBoxをインストールする

https://www.virtualbox.org/


### (2). Vagrantをインストールする

https://www.vagrantup.com/


### (3). Pluginをインストールする

```
$ vagrant plugin install vagrant-vbguest
```


## 2. Windows + VirtualBox

### (1). BIOSのVitrualizaionをONにする

ほとんどのPCは出荷状態ではBIOSのVirtualizationの機能が無効になっています。  
PCメーカーのマニュアル・ホームページなどを確認しながら、BIOSの設定変更を行ってください。


### (2). VirtualBoxをインストールする

https://www.virtualbox.org/



### (3). Vagrantをインストールする

https://www.vagrantup.com/


### (4). Pluginをインストールする

```
$ vagrant plugin install vagrant-vbguest
```

---



## 3. Windows + Hyper-V

Docker Desktopなどと共存したい場合、仮想化基盤にHyper-Vを利用する必要があります。  
本プロジェクトでは、「VirtualBox」をメインに説明をしていきますが、Hyper-Vの利用方法も簡単に紹介しておきます。

### (1). Hyper-Vを有効にします。

Windowsのサイトを見ながら行ってください。

### (2). Vagrantをインストールする

https://www.vagrantup.com/


VagrantからHyper-Vを操作するには、Windowsの管理者権限が必要です。  
Visual Studio CodeのターミナルからVagrantを実行する場合は、Visual Studio Codeを管理者権限で実行してしまうのが簡単です。（自己責任でお願いします。)


