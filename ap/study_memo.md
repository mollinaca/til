# study_memo

## 1-基礎理論

### 誤差

| 名称 | 説明 |
| - | - |
| 桁落ち | 値のほぼ等しい二つの数値の差を求めたとき，有効桁数が減ることによって発生する誤差 |
| 丸め誤差 | 指定された有効桁数で演算結果を表すために，切捨て，切上げ，四捨五入などで下位の桁を削除することによって発生する誤差 |
| 情報落ち | 絶対値が非常に大きな数値と小さな数値の加算や減算を行ったとき，小さい数値が計算結果に反映されないことによって発生する誤差 |
| 打ち切り誤差 | 無限級数で表される数値の計算処理を有限項で打ち切ったことによって発生する誤差 |

### サンプリング周波数の問題とADPCM

サンプリング周波数 10kHz → 秒間 10,000 回  
ADPCM → 1/4 に圧縮  

### TOM(Time Of Flight)方式センサ

光源から射出されたレーザなどの光が，対象物に反射してセンサに届くまでの時間を利用して距離を測定する。

## 2-アルゴリズムとプログラミング
