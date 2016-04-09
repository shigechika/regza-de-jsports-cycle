# regza-de-jspocycle
TOSHIBA REGZA DBR-M590 de J Sports/Cycle

TOSHIBA REGZA DBR-M590のおまかせ録画機能は[生]というキーワードを使った設定ができない仕様らしい。DBR-M590を入手してから[生]番組のおまかせ録画すべく試行錯誤しても失敗ばかりだった。解決の糸口を知るべくサポートに問い合わせたら晴れて[生]はおまかせ録画不可能であること知った。（新番組の[新]はおまかせ録画できるのに[生]はおまかせ録画ができない背景から大人の事情で制限していると邪推。）
目的は「Jスポサイクルの[生]放送を自動録画」することだ。自転車番組って放送開始時間がまちまちなので時間指定での連ドラ予約はできない。もちろん番組表からコツコツ手動予約はできる。春のクラッシックレースは週一くらいなので辛うじて対応できるけどグランツールが始まると連日の寝不足に加え約3週間分 x 3セットの予約を完璧にこなす心労はハンパない。そこでDBR-M590のメール予約機能があるのでおまかせ録画機能に頼らず，JSPORTSホームページの番組表から[生]放送を抽出しメール予約すればへっぽこおまかせ録画機能の代替できるかもしれないと調べてみた。調べてみたら[初回]放送も合わせて録画予約出来そうなのでついでに実装。
Google Apps Scriptの勉強兼ねてスクリプト書いてみたので晒してみる。Google Apps Scriptにはタイマー起動（cronのこと）できるのでこのまま運用可能。力技かつエラー処理もなく冗長でオンシーズンしか使えなさげな汚ったねーへっぽこコードだけどひとまず動いたからまぁいいっか！w
