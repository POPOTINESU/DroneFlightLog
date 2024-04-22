■サービス概要
2022年12月から義務化された各種飛行日誌（飛行記録、日常点検、点検整備）を記録するためのアプリです。現在位置情報を取得し、記録を迅速に行うことが可能です。さらに、保有する機体を一元管理でき、機体ごとの飛行データを可視化したり、定期点検時期の通知を受け取ることができます。

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
想定したユーザー層に対してそれぞれどのようにサービスを届けるのか現状考えていることがあれば教えてください。

■ サービスの差別化ポイント・推しポイント

・似たようなサービスは、どれもモバイルアプリばかりなので、ユーザーのOSに依存して使用できないことがある。ドローン業界では、機体を自動航行させるアプリ自体がWebアプリを使用していることが多いため、違う端末からでも使用できるWebアプリが最適であり差別化を図れる。
・既存アプリはUIデザインもシンプルではあるが、デザインが古いものがモダンなデザインを取り入れている。
・定期点検の通知を行っているアプリはなかったため差別化を図れる。


■ 機能候補
現状作ろうと思っている機能、案段階の機能をしっかりと固まっていなくても構わないのでMVPリリース時に作っていたいもの、本リリースまでに作っていたいものをそれぞれ分けて教えてください。

・ログイン機能
・飛行記録機能
・現在地を取得して場所を記録できる機能
・グループ毎に使用できる機体を分けれる機能
・ユーザー、グループ作成機能
・機体登録機能
・定期点検通知機能

■ 機能の実装方針予定
一般的なCRUD以外の実装予定の機能についてそれぞれどのようなイメージ(使用するAPIや)で実装する予定なのか現状考えているもので良いので教えて下さい。

・LINE APIで通知　LINE Messaging API
・Geocoderまたは、Google Maps Platform

