# Note
```
guid: Ir7>YWDdCT
notetype: AI-Vocabulary-Style
```

### Tags
```
```

## Front
BERT言語モデル

## Back-EN
Bidirectional Encoder Representations from Transformers, BERT

## Back-FR
Représentations de l'encodeur bidirectionnelle de Transformers, Bert

## Reading
BERT言語モデル

## Sentence
BERTは、自然言語処理の事前学習用の Transformer ベースの機械学習手法である。
- Masked language model 
単方向制約を超えた双方向（Bidirectional）の言語モデルを構築するために、BERTでは事前学習タスク/損失関数として MLM を採用した。
MLMでは部分マスクされた系列を入力としてマスク無し系列を予測し、マスク部に対応する出力に対して一致度を計算し学習する。モデルはマスクされていない情報（周囲の文脈/context）のみからマスク部を予測する事前学習タスクを解くことになる。
- 双方向ネットワーク
MLM により双方向に依存するモデルを採用可能になったことから、BERT ではネットワークとして双方向性の Transformerアーキテクチャを採用した。すなわち self-attention による前後文脈取り込みと位置限局全結合による変換を繰り返すネットワークを用いている。
