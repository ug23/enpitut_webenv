enPiT筑波大Webアプリ開発環境セット
====

概要
---
Webアプリ（Ruby on Rails）の開発環境構築セットです。
開発メンバーの開発環境(OS等）が異なっている場合でも、仮想マシンを
使って簡単に同じ環境を用意することができます。

また、同じ環境をクラウド上に構築することもできます。
（なお、協力企業のIDCフロンティアのクラウドサービスを利用することを想定しています）

![Overview](figures/overview.png "利用イメージ")

開発環境の構成
---
* OS: Cent OS 7.0
* インストールされているもの
  * Ruby(2.2), Java(1.8), gcc(4.8.3)
  * Ruby on Rails(4.2.3)
  * Postgresql(9.2), MySQL(5.5), SQLite(3.7)
  * GitHubと連携するための各種コマンド(git, hub, github-connect.sh)
  * 各種設定ファイル（.bash_profile, .gemrc, .gitconfig)

設定手順
---
* [準備](preparation.md)
* [enPiT筑波大が提供する仮想マシンを利用する](generateVM.md)
* [開発環境の構成を変更する](modifyVagrantfile.md)
* [クラウド上に環境を設定する](deployVM.md)