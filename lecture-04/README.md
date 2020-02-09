# Lecture 04 : VM設定(config.vb)

Vagrantfileで行うVMの設定方法を紹介します。

## config.vm.hostname

ホスト名を設定する

## config.vm.network

ネットワークの設定


## config.vm.synced_folder

ローカルディスクとの同期を方法です。  
VMからホストOSのフォルダを利用するための設定方法を紹介します。  

- config.vm.synced_folder "../data", "/vagrant_data"

- config.vm.synced_folder "../data", "/vagrant_data", type: "nfs"

- config.vm.synced_folder "../data", "/vagrant_data", type: "rsync"

- /vagrantフォルダ

- Windows環境でのファイルの同期

Webpackでauto reloadなどが効かない場合があります。

## config.vm.provider "virtualbox" do |vb|

VirtualBoxの設定です。  
よく利用するものを紹介していきます。

- vb.name = "VM_NAME"  
VirtualBoxの登録されるVM名を設定します。

- vb.memory = "1024"  
メモリ量を設定します

- vb.cpus = "2"  
CPUの数を設定します

詳しくは、[こちら](https://www.vagrantup.com/docs/virtualbox/configuration.html)
