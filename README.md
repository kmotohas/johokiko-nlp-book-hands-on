# johokiko-nlp-book-hands-on

Explosion AIが開発する汎用的な自然言語処理ツールである **spaCy** と、Hugging Faceが開発するtransformerベースの現在最先端のモデルを簡単に利用するためのツールである **transformers** を扱ってニュース記事の分類モデルを作成します。

Jupyter Notebook等でhands-on.ipynbの各セルを順々に実行していってください。

動作確認は以下の環境で行いました。

- Machine (AWS EC2 p2.xlargeインスタンス)
    - OS: Ubuntu 16.04
    - CPU: Intel(R) Xeon(R) CPU E5-2686 v4 @ 2.30GHz
    - RAM: 64GB 
    - GPU: NVIDIA Tesla K80
- Python
    - python: 3.7.5
    - mecab-python3: 0.996.2
    - torch (PyTorch): 1.3.1
    - torchtext: 0.4.0
    - transformers 2.3.0
    - spaCy 2.2.3
    - cupy 7.0.0
