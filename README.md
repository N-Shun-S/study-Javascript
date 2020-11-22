# study-JavaScript
JavaScript学習用　　
2020/09/22~

# コーディング規約
*1.変数宣言*
- 変数宣言 : let
- 定数 : const
- 非推奨 : var  
※ 現在の職場環境での動作確認等の場合、var可

*2.関数宣言*
- アロー関数 const funcArrow = () => {}
- function宣言 function func(){}
- 関数式 const func = function(){}  
※ 上から順に採用　　
※　V + N

*3.命名規則*
- 基本 : キャメルケース
- クラス名 : アッパーキャメルケース
- 定数 : スネークケース　　
　　
- Element取得 : 末尾El
- button : btnXxx

*4.インデント*
- スペース4つ  
※ タブでのインデントは非推奨

*5.行末セミコロン*
- 全て入れる  
  
# コミットメッセージのフォーマット
[Prefix] チケット番号 要約  
空行  
変更した理由の詳細  

-例
[Fix] refs #01 ○○の不具合の修正

- [Fix]　修正（ミス・バグ）
- [Add]　追加（ファイル・機能）
- [Remove]　削除（コード・ファイル）
- [Change]　仕様変更（コード・ファイル）
- [Update]　修正・改善（Fixではない場合）
- [Upgrade]　更新（パッケージ・ドキュメント）
- [Revert]　変更取り消し  
  
- [Study]  
※ 個人学習用 教材名番号記載  