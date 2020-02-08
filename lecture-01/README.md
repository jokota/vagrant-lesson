# Lecture 01： はじめに

## 1. Vagrantを使ったデモ

Vagrantが、どのようなものか理解するために、初期化からVirtual Machine(以下、VM)にsshログインするまでの流れをデモしていきます。

### (1). フォルダを初期化する

```
$ vagrant init
```

「Vagrantfile」が生成されます。

### (2). boxイメージを変更する

「Vagrantfile」のboxの行を書き換えます。

```
-  config.vm.box = "base"
+  config.vm.box = "ubuntu/bionic64"
```

### (3). VMを起動する

編集したVagrantfileを使ってVMを起動します。

```
$ vagrant up
```

VMの起動が完了するまで、しばらく待ちます。

### (4). VMにログインする

VMにログインします。

```
$ vagrant ssh
```
