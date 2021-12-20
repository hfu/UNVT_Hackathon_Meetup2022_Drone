# UNVT_Hackathon_Meetup2022_Drone

# ファイルの説明
- constants.rb: 設定情報を入れたファイルです
- Rakefile: タスクが記載されたファイルです
- reproject.rb: 投影処理のための pipeline を出力するスクリプトです

# 使い方
1. sagamihara20211215aoyamauniv1155mapconcierge00arw01_PointCloud_campus05.las をダウンロードしてこのフォルダに置く 
2. `rake reproject` で a.las ファイルを作成
3. `rake resample` でベクトルタイルを生産
4. `rake style` で docs/style.json を生成
5. `rake host` でサーバを動作させる
