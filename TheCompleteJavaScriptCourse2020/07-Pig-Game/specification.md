# 仕様(画面作成済み)
  
*Pig-Game*
- 合計得点が 100 点以上になったプレイヤーが勝利
  
*画面詳細*
- 「PLAYERS 点数」
- 「CURRENT 点数」
- 「サイコロ目」
- 「PLAYERS 背景」
*ボタン一覧*
- 「NEW GAME」ボタン  
- 「ROLL DICE」ボタン  
- 「HOLD」ボタン    
*状態*
- 「アクティブプレイヤー」  
- 「ノンアクティブプレイヤー」  
- 「プレイ可能」
- 「プレイ不可能」
*ボタン押下処理*
- 「NEW GAME」ボタン
- 初期化
  
- 「ROLL DICE」ボタン
- 「サイコロ目」変更  
- 「サイコロ目」を「CURRENT 点数」に加算  
- ->「サイコロ目」が 1 の場合  
- 「CURRENT 点数」を 0  
- 「PLAYERS 背景」を変更  
- 「アクティブプレイヤー」の変更  
  
- 「HOLD」ボタン  
- 「CURRENT 点数」を「PLAYERS 点数」に加算  
- 「CURRENT 点数」を 0  
- 「PLAYERS 背景」を変更  
- 「アクティブプレイヤー」の変更  
- ->「PLAYERS 点数」が 100 以上の場合
- 「PLAYERS 背景」を変更  
- 「NEW GAME」ボタン以外は無効化  
  
*プラス α*  
- 欄外に勝ち点設定欄とボタン追加
- ゲーム開始時
- PLAYER1 からサイコロを回し
- 大きい目のプレイヤーからゲームスタート
- アニメーション表示
