# 6章 物流の最適ルートをコンサルティングする１０本ノック

ここでは、「物流」の基礎となる「輸送最適化」を検討するにあたっての基礎的な技術を習得します。  
実際の物流データからネットワーク構造を可視化する方法について学び、最適な物流計画を立案する流れを学んでいきます。
<br>
<br>

《 データ一覧 》<br>
tbl_factory.csv : 生産工場のデータ<br> 
tbl_warehose.csv : 倉庫のデータ<br>
tbl_transaction.csv : 2019年の工場への部品輸送実績<br>
rel_cost.csv : 倉庫と工場間の輸送コスト<br>

trans_route.csv : 輸送ルート<br>
trans_route_pos.csv : 倉庫・工場の位置情報<br>
trans_cost.csv : 倉庫と工場の輸送コスト<br>
trans_route_new.csv : 新しく設計し直した輸送ルート<br> 
demand.csv : 工場の製品生産量に対する需要<br>
supply.csv : 倉庫が供給可能な部品数の上限<br>