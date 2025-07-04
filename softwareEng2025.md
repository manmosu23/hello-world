# 第11回github課題

## 第１回講義まとめ
　第１回では、ソフトウェア工学の講義の概要についてだった。ここで、これからの授業のスケジュールや何をしていくかを確認した。

## 第２回講義まとめ
　第２回では、ソフトウェア工学概論１ということで、ソフトウェア工学とは何か、今なぜソフトウェア工学が必要なのかについてだった。
　ソフトウェア工学とは、「品質」、「コスト」、「納期」の最適なバランスを実現するための手法・方法論のことだ。現在の社会はソフトウェアなしでは回らないものになっているため、そのソフトウェアを効率よく開発し、メンテナンスできる人材が今後さらに必要になっている。また、利用者のニーズが変化し続けているので、そのニーズに対応するためにもソフトウェア工学は必要だ。

## 第3回講義まとめ
　第3回ではソフトウェアライフサイクルということで、ソフトウェアの誕生から開発・運用、廃止までの流れについてだった。
　まず、ソフトウェアの誕生はニーズの発生から始まり、そのニーズに合うシステムを作る計画をする。そして、その計画を具現化するうえで、ソフトウェアを作る前に要件定義をする。要件定義とはどういうものを作るのか定義することで、実現する機能・実現しない機能を明確にすることが重要になる。
　ソフトウェア開発では、まず要件定義書をもとに設計書を書き、それに従って制作する。制作方法は主に自社開発と外部委託の２つがある。自社開発はそのままの意味だが、一部機能をパッケージとして外部から購入する場合もある。外部委託では納品物にソースコードを含めるかどうかで対応が変わり、含める場合はメンテナンスを自社で行えるが、含めない場合はそれが不可能となる。複数人でのソフトウェア開発の場合はドキュメンテーションを使うので、非同期コミュニケーションが重要になってくる。ソフトウェアの保守ではテストとデバッグが行われる。バグのないソフトウェアは存在しないので、あらかじめテストしバグを早期発見・対処するのが理想だ。

## 第４回講義まとめ
　第４回ではプロジェクト・ソフトウェア分析・開発プロセスについてだった。
　プロジェクトを計画するうえで、フォアキャスティングとバックキャスティングという考え方がある。フォアキャスティングは現状から順に目標に進んでいく考え方で、目標に到達できない可能性がある。バックキャスティングは定めた目標から逆算して計画することで、目標を明確に設定する必要がある。プロジェクト業務はバックキャスティングで行われる。
　ソフトウェアを分析するにあたって、物量、実行性能、開発工数、品質の４つの観点から分析する。まず、物量の観点ではステップ数（ソースコード行数など）・オブジェクト容量の大きさから評価する。実行性能では画面の視認性・操作性・入力補助・互換性・ガイダンスなどで評価する。開発工数はファンクションポイント法を使って評価する。この方法を使うことで、必要な機能が見えてきた段階でシステム規模を概算することが可能になる。品質はバグ発生率を基準に評価する。
　開発プロセスには様々な種類があるが、今回は４つ紹介する。１つ目は、ウォーターフォール型だ。この方法は要件定義から開発、テストまでを一気に行う手法で、進捗管理が容易になり、成果物が明確になるが、その分後工程にしわ寄せが集中するリスクがある。
　２つ目はスパイラルモデルで、プログラム開発を小さなフェーズに分割し、そのフェーズごとにプロトタイプによるデモンストレーションを行い、フィードバックする。この方法ではプロトタイプ作成時に想定外の作業量が発生するリスクがある。
　３つ目は反復型開発プロセスで、ソフトウェアを機能分割し、これを反復という単位で管理する。メリットとしては部分的に完成させていくことによる顧客の要求の取り入れやすさや部分的な納品が可能なことがあるが、デメリットとして分割による業務の増加や全体像が見えづらいことが挙げられる。
　４つ目はアジャイルプロセスだ。アジャイルプロセスでは、計画から実装、テストまでの工程を小さなサイクルで繰り返す。この方法を使うと、変化に柔軟に対応することができる。この方法のフレームワークの一つにスクラムがあるが、これは少人数でチームを結成して「スプリント」と呼ばれる短期間の開発サイクルを繰り返す方法だ。

## 第5回講義まとめ
　第５回ではWBSについての話だった。WBSとは、プロジェクト目標を達成し、必要な要素成果物を生成するためにプロジェクトチームが実行する作業を、要素成果物を主体に階層的に要素分解したものだ。これを作るメリットとしては、やることとやらないことや全体管理、作業計画などが明確になったり、プロジェクト実施時はWBSに則り実行するのみになったりすることだ。
　作り方としては、まずスコープを明確にし、大きな作業をグルーピングする。そうしてグルーピングした作業の相互関連を考え、各グループの作業を洗い出す。

## 第６回講義まとめ
　第６回では第５回で出たWBS演習の続きが行われた。