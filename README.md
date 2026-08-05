# 結婚祝いメッセージサイト（由里子さん・正二さん）

ご祝儀袋に印刷したQRコードから開く、家族からのお祝いメッセージページ。

- 公開URL: https://siraha0611.github.io/wedding-message-2026/
- 渡す日: 2026-08-16（お盆）
- 依頼元: 母（sawako.k）／LINE「カツマタ家」2026-08-05

## 現状

仮組み版。メッセージ6枚は**仮テキスト**（勝俣父母・河西家・モモナ・ヒロ・ホナミ・コトミ・邦広家・佐和子家）。
実メッセージが集まったら `index.html` 内の `.message-card` の本文を差し替える。

## 動画の入れ方

YouTubeに**限定公開**でアップロード → `index.html` の「ビデオメッセージ」セクションにあるコメントアウト済み iframe の `VIDEO_ID` を差し替え、`.video-placeholder` を削除する。

## 検索対策

`<meta name="robots" content="noindex">` 済み。URLを知っている人だけが実質見られる。
