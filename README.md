# Physics-Inspired Graph Neural Networks

["Combinatorial Optimization with Physics-Inspired Graph Neural Networks"] を元に進めている研究.

method name.ipynb や utils.py は [co-with-gnns-example] リポジトリの実装をベースにしていますが,
Mean Field Approximation や 最大カット問題を追加で実装しています.

実験結果は [analysis.ipynb] の図を参照してください.

<pre>
pi-gnn/  
  └─ sotsuron/: 卒業論文用のディレクトリ
      ├─ method name/: 各手法用 (1_layer_gnn, 2_layer_gnn, mfa (Mean Field Approximation)) のディレクトリ
      │   ├─ method name.ipynb: 実験用の notebook
      │   ├─ utils.py: method name.ipynb で使用するクラス・関数
      │   ├─ data/: 生データ
      │   └─ processed_data/: 加工済みデータ
      └─ analysis/: データ解析用のディレクトリ
          └─ analysis.ipynb: データ解析用の notebook
</pre>

# ライセンス

このプロジェクトのライセンスは MIT ライセンスです. 詳細は [LICENSE] をご覧ください.

["Combinatorial Optimization with Physics-Inspired Graph Neural Networks"]: https://arxiv.org/abs/2107.01188
[co-with-gnns-example]: https://github.com/amazon-science/co-with-gnns-example
[analysis.ipynb]: https://github.com/tatsumasaogawa/pi-gnn/blob/main/sotsuron/analysis/analysis.ipynb
[LICENSE]: https://github.com/tatsumasaogawa/pi-gnn/blob/main/LICENSE
