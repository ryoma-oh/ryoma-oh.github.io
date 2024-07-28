---
layout: page
title: "UML"
permalink: /docs/software-eng4
---

# ソフトウェア工学 2024

[ホーム](/docs/index)

## UML

　UML(Unified Modeling Language)とは、文章によるドキュメントに加えて開発・設計を図示化する万国共通の記法である。開発フェーズに応じて様々なUML図を使い分ける。

**ユースケース図**

　外部からアクションを起こす人やモノをアクター、システム内部での振る舞いをユースケースとしてこれらの相互関係を図示化する。

**アクティビティ図**

　タスクに相当するアクションノードや制御フローの方向を示す矢印などを使って、システム内部で各ユースケースをどのようなプロセスで実現するかを記載する。

**クラス図**

　オブジェクト指向モデルでクラスやオブジェクト、インスタンスなどで表現される。クラスはオブジェクトの型を定義したもので、オブジェクトは具体化されたもの、インスタンスはクラスにデータが入り実体化したものである。

**シークエンス図**

　時間の前後関係やタイミングを表現できる。

**コミュニケーション図**

　シークエンス図を書き換えたもので、通信リンクを使って接続形態やネットワーク構成が表現できる。

**タイミング図**

　オブジェクト間の相互作用のタイミングと状態遷移を表現したもの。

**相互作用概要図(iod)**

　システムの鳥瞰図で、シークエンス図、コミュニケーション図、タイミング図の相互作用をアクションとするアクティビティ図。

**コンポーネント図**

　カプセル化されたソフトウェアパーツの管理を目的とした図で、複数のクラスで構成される処理に対して１つ以上のインターフェースを用意し、あたかも１つのクラスのように取り扱ったものであるコンポーネントを使って表現する。

**パッケージ図**

　クラス図の内、"package"であるクラスを抽出し、パッケージの依存関係を表現し管理する。

**状態マシン図**

　トリガーによるオブジェクトの状態遷移を表現する。

**配置図**

　サーバーやデスクトップPCといったハードウェアの構成を表現する。