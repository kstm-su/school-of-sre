# Linux の基礎

## はじめに
### このコースの前提

- Windows, Linux, Mac など、任意の OS を快適に利用できるスキル
- オペレーティングシステムに関する基本的な知識を持っていることが期待されています

## このコースで期待されること

本コースは3つの部分に別れています。最初の部分では、Linux オペレーションシステムの基礎についてをカバーします。Linux のアーキテクチャ、Linux ディストリビューション、Linux オペレーティングシステムの利用について説明します。また、GUI と CLI の違いについても説明します。



第2部では、Linux で使用される基本的なコマンドについて説明します。

ここでは、ファイルシステムの移動、ファイルの表示と操作、I/O リダイレクトなどに使用されるコマンドについて説明します。



第3部では、Linux におけるシステム管理について説明します。これには、ユーザー/グループの管理、ファイルのアクセス許可の管理、システムパフォーマンスの監視、ログファイルなど、Linux の管理者が実行する日常的なタスクが含まれます。

第2部と第3部では、概念を理解するために例を取り上げます。

## このコースではカバーしない内容

本コースでは、高度な Linux コマンドと bash スクリプトについては説明しません。また、Linux の内部的な話についても取り上げません。

## コースの内容

このコースでは、次のトピックについて説明されています:

-  [Linux 入門](https://kstm.shinshu-u.ac.jp/school-of-sre/level101/linux_basics/intro/)
    -  [Linux オペレーティングシステムって何?](https://kstm.shinshu-u.ac.jp/school-of-sre/level101/linux_basics/intro/#what-are-linux-operating-systems)
    -  [ポピュラーな Linux ディストリビューション](https://kstm.shinshu-u.ac.jp/school-of-sre/level101/linux_basics/intro/#what-are-popular-linux-distributions)
    -  [Linux の使われ方](https://kstm.shinshu-u.ac.jp/school-of-sre/level101/linux_basics/intro/#uses-of-linux-operating-systems)
    -  [Linux のアーキテクチャ](https://kstm.shinshu-u.ac.jp/school-of-sre/level101/linux_basics/intro/#linux-architecture)
    -  [GUI と CLI](https://kstm.shinshu-u.ac.jp/school-of-sre/level101/linux_basics/intro/#graphical-user-interface-gui-vs-command-line-interface-cli)
-  [コマンドラインの基礎](https://kstm.shinshu-u.ac.jp/school-of-sre/level101/linux_basics/command_line_basics/)
    -  [仮想環境の準備](https://kstm.shinshu-u.ac.jp/school-of-sre/level101/linux_basics/command_line_basics/#lab-environment-setup)
    -  [コマンドって何?](https://kstm.shinshu-u.ac.jp/school-of-sre/level101/linux_basics/command_line_basics/#what-is-a-command)
    -  [ファイルシステムの構造](https://kstm.shinshu-u.ac.jp/school-of-sre/level101/linux_basics/command_line_basics/#file-system-organization)
    -  [ファイルシステム内を移動する](https://kstm.shinshu-u.ac.jp/school-of-sre/level101/linux_basics/command_line_basics/#commands-for-navigating-the-file-system)
    -  [ファイルを操作する](https://kstm.shinshu-u.ac.jp/school-of-sre/level101/linux_basics/command_line_basics/#commands-for-manipulating-files)
    -  [ファイルを閲覧する](https://kstm.shinshu-u.ac.jp/school-of-sre/level101/linux_basics/command_line_basics/#commands-for-viewing-files)
    -  [Echo コマンド](https://kstm.shinshu-u.ac.jp/school-of-sre/level101/linux_basics/command_line_basics/#echo-command)
    -  [文字列操作のコマンド](https://kstm.shinshu-u.ac.jp/school-of-sre/level101/linux_basics/command_line_basics/#text-processing-commands)
    -  [I/O リダイレクション (パイプ)](https://kstm.shinshu-u.ac.jp/school-of-sre/level101/linux_basics/command_line_basics/#io-redirection)
-  [Linux システムの管理](https://kstm.shinshu-u.ac.jp/school-of-sre/level101/linux_basics/linux_server_administration/)
    -  [仮想環境の整備](https://kstm.shinshu-u.ac.jp/school-of-sre/level101/linux_basics/linux_server_administration/#lab-environment-setup)
    -  [ユーザー/グループの管理](https://kstm.shinshu-u.ac.jp/school-of-sre/level101/linux_basics/linux_server_administration/#usergroup-management)
    -  [スーパーユーザーになろう](https://kstm.shinshu-u.ac.jp/school-of-sre/level101/linux_basics/linux_server_administration/#becoming-a-superuser)
    -  [ファイルのパーミッション](https://kstm.shinshu-u.ac.jp/school-of-sre/level101/linux_basics/linux_server_administration/#file-permissions)
    -  [SSH コマンド](https://kstm.shinshu-u.ac.jp/school-of-sre/level101/linux_basics/linux_server_administration/#ssh-command)
    -  [パッケージ管理](https://kstm.shinshu-u.ac.jp/school-of-sre/level101/linux_basics/linux_server_administration/#package-management)
    -  [プロセス管理](https://kstm.shinshu-u.ac.jp/school-of-sre/level101/linux_basics/linux_server_administration/#process-management)
    -  [メモリ管理](https://kstm.shinshu-u.ac.jp/school-of-sre/level101/linux_basics/linux_server_administration/#memory-management)
    -  [デーモンと Systemd](https://kstm.shinshu-u.ac.jp/school-of-sre/level101/linux_basics/linux_server_administration/#daemons)
    -  [ログ](https://kstm.shinshu-u.ac.jp/school-of-sre/level101/linux_basics/linux_server_administration/#logs)
-  [おわりに](https://kstm.shinshu-u.ac.jp/school-of-sre/level101/linux_basics/conclusion)
    -  [SRE の役割における適用](https://kstm.shinshu-u.ac.jp/school-of-sre/level101/linux_basics/conclusion/#applications-in-sre-role)
    -  [便利なコースとチュートリアル集](https://kstm.shinshu-u.ac.jp/school-of-sre/level101/linux_basics/conclusion/#useful-courses-and-tutorials)

## Linux オペレーティングシステムって何?

私たちのほとんどは、75% 以上の PC で利用されている Windows OS を知っています。Windows オペレーティングシステムは、Windows NT カーネルに基づいています。カーネルは OS の最も重要な部分であり、プロセス管理、メモリ管理、ファイルシステムの管理などの重要な機能を実行します。

Linux オペレーティングシステムは、Linux カーネルに基づいています。Linux ベースのオペレーティングシステムは、Linux カーネル、GUI / CLI、システムライブラリ、およびシステムユーティリティで構成されます。Linux カーネルは Linus Torvalds 氏によって独自に開発・リリースされました。Linux カーネルは無償でオープンソースです。- [https://github.com/torvalds/linux](https://github.com/torvalds/linux)

Linux はカーネルであって、完全なオペレーティングシステムではありません。Linux カーネルは GNU システムと組み合わせられることにより、完全なオペレーティングシステムを構成します。そのため、Linux ベースのオペレーティングシステムは GNU/Linux システムとも呼ばれます。GNU はコンパイラ、デバッガ、C言語ライブラリなどのフリーソフトウェアの広範なコレクションです。

[LinuxとGNUシステム](https://www.gnu.org/gnu/linux-and-gnu.ja.html)

Linux の歴史 -
[https://ja.wikipedia.org/wiki/Linuxの歴史](https://ja.wikipedia.org/wiki/Linux%E3%81%AE%E6%AD%B4%E5%8F%B2)

## ポピュラーな Linux ディストリビューション

Linux ディストリビューション (ディストロ) は、Linux カーネルとパッケージ管理システムに基づくオペレーティングシステムです。パッケージ管理システムは、OS 上のソフトウェアのインストール、アップグレード、設定、および削除に役立つツールで構成されます。

ソフトウェアは通常、ディストリビューションに採用され、ディストリビューション固有の形式でパッケージ化されます。これらのパッケージは、ディストリビューション固有のリポジトリから入手できます。パッケージは、パッケージマネージャーによって OS にインストールおよび管理されます。

**ポピュラーな Linux ディストリビューションの一例:**

- Fedora

- Ubuntu

- Debian

- Centos

- Red Hat Enterprise Linux

- Suse

- Arch Linux


| パッケージ形式      | ディストリビューション                              | パッケージマネージャー |
| ---------------------- | ------------------------------------------ | -----------------|
| Debian 形式 (.deb)    |   Debian, Ubuntu                          |   APT|
| Red Hat 方式 (.rpm)   |   Fedora, CentOS, Red Hat Enterprise Linux |  YUM|

## Linux のアーキテクチャ

![](images/linux/commands/image25.png)

- Linux カーネルは本質的にモノリシック (一枚岩) なカーネルです。
[https://ja.wikipedia.org/wiki/モノリシックカーネル](https://ja.wikipedia.org/wiki/%E3%83%A2%E3%83%8E%E3%83%AA%E3%82%B7%E3%83%83%E3%82%AF%E3%82%AB%E3%83%BC%E3%83%8D%E3%83%AB)
- システムコールは、Linux カーネル空間とのやりとりに使用されます。
- カーネルコードは、カーネルモードでのみ実行されます。非カーネルコードは、ユーザーモードで実行されます。
- デバイスドライバーは、ハードウェアデバイスとの通信に使用されます。

## Linux の使われ方

Linux カーネルベースの OS は以下のような例で広く利用されています:

- パーソナルコンピュータ

- サーバー

- 携帯電話 - Android は Linux オペレーティングシステムベースです

- 組み込みデバイス - 時計, テレビ, 信号機など

- 人工衛星

- ネットワーク機器 - ルーター, スイッチなど

## GUI と CLI

ユーザーは、ユーザーインターフェイスを使用してコンピューターと対話します。ユーザインターフェイスは、GUI または CLI のいずれかです。

GUI (Graphical User Interface: グラフィカルユーザーインターフェイス) は、ユーザがアイコンや画像などのグラフィックスを使用してコンピュータと対話することを可能にします。ユーザーがアイコンをクリックしてコンピューター上のアプリケーションを開くとき、実際には GUI を使用しています。GUI を使用すると簡単にタスクを実行できます。

CLI (Command Line Interface: コマンドラインインターフェイス) を使用すると、ユーザーはコマンドを使用してコンピューターと対話します。ユーザーがターミナルにコマンドを入力すると、システムはこれらのコマンドの実行を支援します。GUI を使用した経験のある CLI 新入りユーザーは、特定の操作を実行するためのコマンドを知っている必要があるため、CLI との対話が困難になる場合があります。

## シェルとターミナル

シェルは、ユーザーからコマンドを受け取り、それをオペレーティングシステムに渡して処理させるプログラムです。シェルは CLI の一例です。Bash は Linux サーバで利用できる最も人気のあるシェルプログラムの1つです。他の人気のあるシェルプログラムとして、zsh、ksh、tcsh などがあります。

ターミナル (端末) は、ウィンドウを開き、シェルと対話できるようにするプログラムです。よく使われるターミナルの例としては、gnome-terminal、xterm、konsoleなどがあります。

Linux ユーザーは、シェル、ターミナル、プロンプト、コンソールなどの用語を同じ意味で使います。簡単に言うと、これらはすべてユーザーからコマンドを受け取る方法のことを意味しています。

