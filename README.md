### 非商用solver

pulp 線形関数(一次関数)のみ対応  
- pulp公式ドキュメント
https://coin-or.github.io/pulp/

cvxpy 非線形関数(二次関数等)も対応  

- cvxpy公式ドキュメント
https://www.cvxpy.org/api_reference/cvxpy.expressions.html

問題は下記のサイトより  
PuLP による数理最適化超入門  
http://www.nct9.ne.jp/m_hiroi/light/pulp01.html

### 輸送問題
工場 (x, y) から商品を店 (a, b, c) に配送します。供給量、需要量、輸送コストが下表で与えられているとき、総輸送コストが最小となる配送の仕方を求めてください。  

- 表 : 輸送コスト  
||店 a|店 b|店 c|供給量|
|---|---|---|---|---|
|工場 x|10|6|16|8|
|工場 y|8|8|4|16|
|需要量|12|4|8||	