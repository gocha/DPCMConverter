DPCMConverter
=============

**[今すぐオンラインで DPCMConverter.swf をお試しください！](http://gocha.s151.xrea.com/onlinetool/DPCMConverter.swf)**

[FlMML](http://flmml.codeplex.com/) 向けの Flash ベースの NES DPCM 変換ツールです。オリジナル版は [arche](http://dic.nicovideo.jp/u/934152) さんによって作られました。

このバージョンはいくつかの重要な不具合修正と、若干の変換オプションの追加を行っています。

- 修正: 誤ったデルタ変換の修正**（重要な不具合修正！）**
- 修正: NES DPCM のサイズ境界（1+16n）に準拠するためのパディングバイトの付加
- 追加: サンプリングレート変換なしでの変換（オーバーサンプリングしたサンプルを FlMML で使用するのに良い）
- 追加: 音量縮小オプション
