ディープラーニングの勉強というか研究用あぷろだみたいなの（2018/4～2019/3）
keras_test ( https://github.com/tamakiHaru/keras_test ) の続きみたいな感じ

tensorflowやpytorch使ってRNNの勉強というか練習する過程のいろいろ
名前に入ってないけど結局kerasも使ってる
研究用あぷろだ代わりのリポジトリ
実際にPC上で動かして時とはフォルダ分け違うところあるのでダウンロードして実行する際はファイルパス等に注意
commitとかpushだけでなくブラウザ上の操作でもファイル更新や追加してるので履歴は雑



-----各ディレクトリ等の説明-------------------------------------------

Data
実験に使うコーパスやテストデータおよびその正解データ
学習データはサイズの都合上おいてないこともある
「Dataの説明.txt」にcorpusディレクトリ内の各ファイルの説明を記載してある


Programs
各プログラム
基本的にpython
作成時期や用途でさらにディレクトリ分けてある
プログラムの実行結果の一部もここにおいたり
「Programsの説明.txt」にprogramsディレクトリ内の各ファイルの説明を記載してある


tmp.txt
単なるメモ代わり用
実行コマンドや実行結果メモしたりだけ
特に残す意味もないからほぼ毎回上書きしてる
大事なことは引継ぎメモに転記してる




-----今後の予定リスト-------------------------------------------
改善する保証は無い漠然としたアイデア
・seq2seqのbeam search デコード実装(tensorflowのチュートリアル風に)
・最近はやりのBERTモデルを適用してみるとか
・MPNetなどへの半教師あり学習の適用とか


-----その他雑記-------------------------------------------
