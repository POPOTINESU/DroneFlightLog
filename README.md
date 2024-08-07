■サービス概要

2022年12月から義務化された飛行記録を記録するためのアプリです。
保有する機体を一元管理でき、機体ごとの飛行データを可視化したり、定期点検時期の通知を受け取ることができます。

■ このサービスへの思い・作りたい理由

現在ドローンメーカーで働いており、飛行日誌に関しては全て手書きで行っています。他のドローンメーカーでも同様に手書きで対応しているため、この作業の非効率さを強く感じ、より効率的な方法がないかと考えた。
さらに、定期点検は一定の飛行時間ごと、または購入からの経過年数に基づいて、あるいはその両方に基づいて行う必要がありますが、これらの定期点検のスケジュール管理が煩雑である点も課題であるため、その両方を解決できるアプリを作成したい。

■ ユーザー層について

個人と企業の18歳から40歳前後のドローンパイロットを対象としています。現在、多くのベテランパイロットは元来ラジコンを操縦しており、その年齢層は40歳前後ですが、ドローンの国家資格が18歳から取得できるようになったため、将来的には若年層のパイロットが増えると考えられます。これにより、幅広い年齢層を対象にしています。また、法律の改正により個人での扱いが難しくなったため、企業向けにフォーカスすることがより大きな需要を生むと考えられます。ただし、企業向けに開発したとしても、個人でも利用可能な設計にしたいと考えています。

■サービスの利用イメージ

・屋外利用時に見やすく操作しやすい。

・簡単に記録できるため、フライトに集中できる。

・定期点検実施時期を見逃さない。

■ ユーザーの獲得について
ドローンの企業に勤めており、知り合いにドローンスクールの関係者が多くいるので、実際にドローンを飛ばしている人に直接紹介しようと考えている。

■ サービスの差別化ポイント・推しポイント

・既存アプリはUIデザインもシンプルではあるが、デザインが古いものがモダンなデザインを取り入れている。]

・定期点検の通知を行っているアプリはなかったため差別化を図れる。


■ 機能候補

MVPリリースまでに作成

・ログイン機能

・飛行記録機能

・グループ毎に使用できる機体を分けれる機能

・プルダウンで地名を入力できる

・ユーザー、グループ作成機能

・機体登録機能

本リリースまでに追加する機能

・定期点検通知機能

・フライト時間計測機能

・現在地を取得して場所を記録できる機能(離陸時にアプリを起動しているデバイスの現在位置を取得)

■ 機能の実装方針予定

・ メールで定期点検通知

・ グループ参加承認機能


### 画面遷移図
https://www.figma.com/file/ztOGy84DLiwyIF4IAc5K7c/%E7%84%A1%E9%A1%8C?type=whiteboard&node-id=0-1&t=5N2dmQcNTTz8GmL6-0

・グループテーブル
・ユーザーテーブル
・機体テーブル
・飛行記録テーブル
・不具合テーブル

- [x] ユーザー作成機能
- [x] グループ作成機能
- [x] ログイン機能
- [x] パスワード変更機能
- [x] グループ毎に使用できる機体を分けれる機能
- [x] 飛行日誌登録機能(このページで、地名の入力、現在位置取得を行う)
- [x] 定期点検通知機能

