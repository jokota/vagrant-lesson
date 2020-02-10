# Section 02 : インストール

OS・環境別にVagrantのインストール手順を説明します。

## 1. Windows + VirtualBox

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

## 2. Mac + VirtualBox

### (1). VirtualBoxをインストールする

https://www.virtualbox.org/


### (2). Vagrantをインストールする

https://www.vagrantup.com/


### (3). Pluginをインストールする

```
$ vagrant plugin install vagrant-vbguest
```
