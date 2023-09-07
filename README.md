# IEEE RAS Summer School on Multi Robot Systems 2023 参加記録<!-- omit in toc -->

IEEE RAS Summer School on Multi Robot Systems 2023 という国際サマースクールに参加してきました。
- ここ得られた経験が分野を超えて有用だと思ったこと
- マルチロボットシステムに興味を持つ人が増えてほしいこと

の2点の理由から、参加記録を残します。

- [記事の要旨](#記事の要旨)
- [スクール基本情報](#スクール基本情報)
- [参加記録](#参加記録)
  - [1日ごとの記録](#1日ごとの記録)
  - [かかった費用について](#かかった費用について)
  - [外部資金の活用](#外部資金の活用)
- [所感](#所感)
  - [参加には何が必要か（資金と時間以外で）](#参加には何が必要か資金と時間以外で)
  - [参加を通じて何が得られるか](#参加を通じて何が得られるか)
- [旅のコツなど](#旅のコツなど)

## 記事の要旨
- IEEEの[マルチロボットシステム技術委員会](https://www.multirobotsystems.org/)が提供するサマースクールに参加してきた（[スクールのwebサイト](http://mrs.felk.cvut.cz/summer-school-2023/)）
  - 実務面は[チェコ工科大学のマルチロボットシステムグループ](http://mrs.felk.cvut.cz/)が提供している
  - 使ったコードなどは全て公開されていて自習も可能→[サマースクール向けのリポジトリ](https://github.com/ctu-mrs/summer-school-2023)
- 講義のほか、3人1組のグループワークがある
  - 2機のドローンを用いた電力設備点検の性能を競うコンペ形式
  - 検査点割当や経路生成のコードを運営側に提出し、シミュレーションおよび実機それぞれで最終日に性能を競う
- **国際協調・交渉力（≠英語力）の基礎を体験する機会**としてオススメ
  - 旨味が大きい仕事を自分の担当にするとか、自分らの存在感・主導権を確立するとか
  - 英語力や技術力も鍛えられる（それならサマースクールでなくてよいが・・・）

## スクール基本情報
### 提供<!-- omit in toc -->
- IEEEの[マルチロボットシステム技術委員会](https://www.multirobotsystems.org/)
- [チェコ工科大学のマルチロボットシステムグループ](http://mrs.felk.cvut.cz/)

### 期間・場所<!-- omit in toc -->
- 2023年7月3日（月）～7日（金）
- チェコ工科大学（チェコ共和国・プラハ）
 
<img src="..\230703083653787.jpg" width="500" alt="会場となった電気工学部E棟" title="会場となった電気工学部E棟">

### 参加者<!-- omit in toc -->
- 2022年では31ヵ国から163名が現地参加、13名が遠隔参加[^1]
- 自分が参加した2023年も同じくらいの規模に見えた
- 講義初日に大まかな学年構成を知る機会があったが、**博士課程学生が概ね8割程度**、修士学生が1～2割、社会人と学部生がごく少数という印象で、かなり年齢層が高いと感じた。
  - 日本人学生は確認できた範囲では自分含めて2名（もう1人は海外在住で、日本から来た日本人は自分のみ）

### 時程<!-- omit in toc -->
- 9時から18時、休憩や食事を除き実働7時間。
- 18時から21時くらいまで、食事会やガイドツアーを運営側が企画してくれるため、これにも参加するとより楽しい。
- 5日間ミッチリ予定が詰まっている。時差ボケもあるし、ずっと英語で話し続けるので、体力的にはそれなりにきつい。自分はスクール終了後に延泊して観光したが、疲れきっていて30分～1時間ごとに喫茶店で休憩が必要になった。

## 参加記録
### 1日ごとの記録
- ここからは本当に毎日の活動記録を詳しく書いていく。この手のサマースクールに参加すると具体的にどのような出来事が起こるのか、イメージをつけてもらうことを狙いとしている。

#### 0日目（7月2日（日））<!-- omit in toc -->
- 参加者向けSlackで前日に夕飯でもどうかと参加者の1人が声掛けがあり、それに手を挙げた。洋食のレストランで夕食を食べ、そのあと街をぶらついた。

#### 1日目<!-- omit in toc -->
- 08:30ごろに大学で受付。参加賞（？）としてビールジョッキを渡されて驚く。ビールが好きな国らしい。
  - 裏庭にビールサーバが用意されていて、期間中は自由にビールが飲める環境（自分はお酒に弱いのでパスせざるを得なかった
- 講義が5コマ。
  - チェコ工科大学のマルチロボットシステムグループの研究紹介など。
- 19時ごろから裏庭で歓迎会としてBBQパーティ。
  - この間に3人1組で実施するグループワークのメンバーも見つけなければならない。
  - 異国の地で中々辛いものがあるが、運よくスペイン人学生（スペインの大学の博士学生）と台湾人学生（アメリカの大学の博士学生）とチームを組むことができた。
  - 後で知ったが、チームを組めず1人で参加した人も居たそう。
- 21時ごろ学生寮にチェックイン。

#### 2日目<!-- omit in toc -->
- 講義が4コマ。
  - マルチエージェントシステムの経路計画、人との相互作用など。
- グループワークのオリエンテーション。
  - 課題の説明とシステムのインストール。
  - 課題は2機のドローンを用いた電力設備点検。
    - 点検箇所の割当、経路計画などがポイントになる。
    - ソースコードを提出して、運営側が提供するシミュレータと実機それぞれでの点検性能を競う
  - [課題の内容やシステムのインストール方法等は全てgithubで公開されている](https://github.com/ctu-mrs/summer-school-2023)ので、自習もできる。
    - 最低限の点検行動はデフォルトでも実行できる状態になっている。
    - 更に効率的な点検を行うためにどうすれば良いか、ドキュメントやソースコード中にヒントが書いてあるので、それを1つ1つ潰していく形のため、熟練者でなくても何かしらできることはある。
- 自分以外の2名はROSの取り扱いや経路計画、クラスタリングなどに詳しい様子。
  - オリエンテーション中に最初の課題（ドローンの方向転換のスムージング）を実装してみせてくれた。
  - 心強い一方で、自分はどうやってチームに貢献できるかと不安になる。
- 18時30分ごろから旧市街ツアー。あまりの疲労に途中離脱しようかと思ったが勿体ないので最後までついていった。
- 20時30分ごろ解散→グループワークのチームメイトが夕飯に誘ってくれたのでついていく。同じ国から来た人がたくさんいたようで、そのグループに混じってローストポークを食べた。
- 22時30分ごろ帰寮。
  - グループワークに不安があったので、少し課題のガイドやソースコードを読み解く。自分にもできそうな部分にアタリを付けた。

<img src="https://github.com/kazuho-koba/MRS-SummerSchool2023/blob/main/pictures/230704201204248.jpg" width="500" alt="ツアーで訪れたカレル橋" title="ツアーで訪れたカレル橋">

<img src="https://github.com/kazuho-koba/MRS-SummerSchool2023/blob/main/pictures/230704214834232.jpg" width="500" alt="夕飯に食べたローストポーク" title="夕飯に食べたローストポーク。この旅で一番おいしかった。">

#### 3日目<!-- omit in toc -->
- 講義が2コマ
- 午後はグループワークがメイン
  - チームメイトが経路計画にも詳しいようで、実装・改良して見せてくれた。
  - もう1名はドローンが各点検箇所で一時停止せず通過しながら点検を行う（点検地点で点検箇所の方向を向けば点検完了と見なされるため、一時停止やカメラの操作などは省略できる）方式を実装してくれた。
  - 自分は昨晩予習した成果として、比較的簡単そうなに見えた以下2点に取り組んだ。
    - 経路のショートカット（RRTアルゴリズムなどで出力した経路はジグザグになるため、それをスムージングする処理）の実装
    - 計画済みの経路を実行前にチェックして、ドローン同士がぶつからないように離陸タイミングをズラす処理の実装
- 夕方は参加者（自分含む）有志で、5分間自分の研究紹介などを行う。
  - 大幅に時間オーバーする人が多く、少しでも短縮しようと自分のターンは1、2分で終わらせたが、事前に練習もしていないため殆ど何も言えずに終わった。
- 19時から大学付近のレストランで食事会（運営主催）
  - この費用（ドリンク2杯と食事のコース）もスクール参加費に含まれている。
- 21時30分ごろ帰寮。本業（博士課程）で学会予稿の投稿〆切が近かったのでそれを仕上げる。

#### 4日目<!-- omit in toc -->
- 講義が2コマ。
  - ロボット群による環境認識、集団意思決定など。
  - 自業自得だが講義とグループワークが交互にあるのは具合が悪い。講義中もグループワークの方が気になってしまい、講義が頭に入ってこない。
- グループワークの続き。
  - 点検地点の割当てや経路計画の高速化などでチームメイトが苦戦していた。
    - 自分はその議論に着いていけず（言っていることはなんとなくわかるが、自分でコードが弄れるレベルではない）
  - 議論に参加するフリをしながら、ドローンの衝突回避や急峻な挙動の制限に関する安全マージンの調整など、自分にもできそうなことを進めた。
- ラボツアーでチェコ工科大マルチロボットシステムグループが開発するドローンや開発現場を見せてもらった。
  - 下に図示した実験用のドローンだけでなく、プロペラ軸間距離1m程度の大型ドローン（ビル火災の消火実験に使うらしい）などもあった。
  - 他の研究機関などからの開発請負もしているらしい。


<img src="https://github.com/kazuho-koba/MRS-SummerSchool2023/blob/main/pictures/230706145333110.jpg" width="500" alt="グループワーク課題の実機実験で使うクアッドロータ型ドローン。他にも様々な機体がある。" title="グループワーク課題の実機実験で使うクアッドロータ型ドローン。他にも様々な機体がある。">
<br><br>

- 18時ごろスクールとしては解散。
  - 何チームかで連れ立ってカフェに移動して課題の追い込み。
  - もはや技術的に自分にできることが殆どなく、（チームメイトの許可を得て）初学者しか居なかった他チームのメンバーに自分たちのやり方を教えたりしていた。
- 22時にカフェが閉まってしまい、以降は自分の部屋にチームメイトを招いて最後の調整を行った。〆切ギリギリの23時55分ごろに課題のソースコードを提出し、お互いの粘りを称えあって解散した。

#### 5日目（最終日）<!-- omit in toc -->
- この日は各チームが提出したソースコードを実際に走らせるフィールドテスト。
  - 9時に川の中州に集合する。普段から実機実験はここでやっているらしい。
  - 電柱とソーラーパネルの模型が設置された環境を2機のドローンが飛び回る。
  - RTK-GPSを用いて位置が計測され、操作者の手元のノートPCからドローンを遠隔操作している様子。
  
  <img src="https://github.com/kazuho-koba/MRS-SummerSchool2023/blob/main/pictures/230707092904452.jpg" width="500" alt="実験フィールド。電柱、電線やソーラーパネルの模型が置かれている。RTK-GPSの基地局は画面外左に設置されていた。" title="実験フィールド。電柱、電線やソーラーパネルの模型が置かれている。RTK-GPSの基地局は画面外左に設置されていた。">
  <img src="https://github.com/kazuho-koba/MRS-SummerSchool2023/blob/main/pictures/230707093626620.jpg" width="500" alt="実験セットはこのキャンピングカーで運ぶらしい。出張デモなどもあるだろうから便利なのかもしれない。" title="実験セットはこのキャンピングカーで運ぶらしい。出張デモなどもあるだろうから便利なのかもしれない。">
  <br><br>

- 各チームで順に提出したコードを走らせる。
  - まずはシミュレーション競技で、GAZEBO上で提出したコードを走らせて、観測に成功した点検箇所の数、点検に要した時間、高度や速度などの制限に対する違反の有無をチェックする。
  - その後実機実験を行う。こちらも評価項目は同じだと思う。
  - リモート参加していた参加者の課題提出も受け付けていた様子。

- 30チームくらいあるのでみなすぐに飽きる。
  - 昼食を取りながら各々の本業（主に博士の研究）を紹介したりしていた。
  - ここで初めて日本人が自分以外にもう一人居たことに気付いた。海外留学中で日本から来たわけではなかったが、思いもよらない共通点があったので話は弾んだ。
  - 参加者の一人に声をかけられて、経路計画や経路のスムージングなどの質問を受ける。
    - 自分が実装した部分じゃなかったけどコード自体は手元にあるし最低限理屈はわかっているので説明した。
    - この人がそうだったのでここで初めて気づいたが、チームを組まず（組めず？）課題を提出できなかった人も居た様子。
- 14時には全チームのテストが終わって性能が良かったチームの表彰式
  - **自分たちのチームはシミュレーション部門で優勝することができた**
    - 全部の点検箇所を回ること、高度や速度などの制限に抵触しないことは多くのチームがクリアしていたので、所要時間（経路計画に要した計算時間＋実際の飛行に要した時間）が最も早かったものと思われる。
    - 点検箇所の割り当て、スムーズな経路の生成、それらの演算効率化がポイントだったらしい。
    <img src="https://github.com/kazuho-koba/MRS-SummerSchool2023/blob/main/pictures/IMG_2772.jpg" width="500" alt="表彰式の様子（右が自分）" title="表彰式の様子（右が自分）">
  <br><br>
  - 実機部門は入賞できず、順位不明。
    - フィールドの諸元（障害物や点検箇所の配置）がシミュレーションと異なったようで、自分たちのチームは点検箇所の割り当てが上手く行かなかった様子だった。1機のドローンに殆どの点検箇所が集中して割り当てられていた。
- 15時ごろスクール終了・解散。
  - スクールで仲良くなったほかの参加者とプラハの街を観光し、その後食事に行った。24時ごろ解散。

#### 後日談<!-- omit in toc -->
- 自分が作った部分、どれくらい意味があったんだろう？と気になった。
  - ジグザグで出力される経路をスムージングする処理を作ったけど、その後経路計画アルゴリズム自体を変更したので、もう不要なのではと内心思っていた。
  - そこだけコメントアウトしたら、思った以上にジグザグな経路が出力され、性能が2割くらい落ちた。意外と役に立っていたらしい。


### かかった費用について
- **合計（\426,419-）**
  - スクール参加費（\76,693-）
    - 昼食×5日分、常時飲み放題のビール、夕食×2（1日目と3日目）が含まれる。たくさん飲み食いすれば半額分くらい元が取れるかもしれない（？）
  - 航空券（\253,560-）
    - 4月末に購入。もっと早く購入すれば安く上がったかも？
  - 宿代（\30,966-）
    - 前泊と後泊を含む。
    - 学生寮が4泊で1000コルナ（9000円強）＋前・後泊のシティホテル分
    - 早めに予約すれば学生寮で前・後泊も可能だったらしい。
  - その他（\65,200-）
    - うち2万5千円くらいは日本で借りたポケットwifi代
    - 食費、交通費、お土産など
- 節約するとしたら？
  - 航空券をもっと早く予約する
  - 学生寮にもっと早く申し込んで前・後泊も使わせてもらう
  - ポケットwifiは諦める
    - スクール会場にも、大抵のホテルにもWiFiはある。
    - スクール以外の仕事をしたり、スクール外でグループワーク課題に取り組むなら必要かも
    - Amazonで買ったプリペイド海外SIMも安かった（通信はすごく遅かった）
  - 街歩き中にダラダラと飲み食いしない
  
### 外部資金の活用
- サマースクールに40万円はかなりの出費。
  - 自分は一度就職していることもあり懐事情に余裕があった。
- 大学に一部だけでも補助してもらえるのが理想か
  - 所属研究室によっては補助してもらえるかも。周りの（日本以外の国からの）参加者はそうしていた。
  - 大学によっては海外活動を補助する制度がある（自分の所は[国際学術交流奨励事業](https://global.ynu.ac.jp/studyabroad/encourage/)という制度で最大20万円の補助が受けられる様子）

## 所感
- 40万円払う価値は自分にはあった
- 純粋に技術を学びたいなら自分でアレコレやった方が早い
  - リモート参加も可能だが後述のように現地で他の参加者とやり取りするところに旨味があると感じた。
  - リモート参加するくらいなら国内のハッカソンに参加するとか、[スクールが提供するコード](https://github.com/ctu-mrs/summer-school-2023)で自習した方が良い。

### 参加には何が必要か（資金と時間以外で）
- 技術力、英語力、積極性（根性？）のうち2つ以上あればかなり楽しめそう。
  - 技術力
    - グループワークではPython（ROS利用）で書かれたコードを見て、ドキュメントのガイドに従って改変していく
    - 今回はクラスタリング（k-means法、最短距離法など）や経路計画（RRT、A*など）などの基礎的手法を理解し実装できれば十分そうだった
    - 講義は研究紹介に近いので、マルチロボットシステムに興味があれば問題無さそう
  - 英語力
    - 講義は最低限の英語力があればぼんやりと意味を取るくらいはできる
    - グループワークは少人数とは言え、担当タスクの割り振りやわからない所の相談などでかなり濃密な対話が必要。
  - 積極性（根性？）
    - 慣れない海外で、技術力なり英語力なり、何かしら自分が自信を持てない技能を求められるのは大変
    - 拗ねたり塞ぎ込んだりせずに、周りと話すこと、自分にできそうなことを探すことが重要
- 自分の場合は英語力と積極性が功を奏した。
  - 技術についても（群ロボットが自分の博士研究テーマなので）専門ではあるが、Python（ROS）は趣味で触った程度、経路計画やクラスタリングは名前以外忘れてしまっている状況。
  - 英語は割と得意
  - 積極性は知らない土地にいるという高揚感で押し切った
    - 一度就職したことで（？）昔より会話スキルなどが上がっていたかも

### 参加を通じて何が得られるか
- **国際協調・競争力**
  - グループワークでは比較的長期間・高強度で対話を続け、互いにタスクを割り振ったり、技術力に差があれば教えたり教わったりしなければならず、一般的に言う「英語力」の範疇を超えたパワーが必要
  - 将来的に、国際共同開発や国際標準化などに関わる場合、いかに自分らに有利な体制を作るか、いかに実入りの良いタスクを担当するかなど、色々と調整が必要になると思われる。国際グループワークはその練習第1歩として有用と感じた。
  - 自分の仕事を国際共同案件にしない場合も、しない理由を求められたり、外国からの参画への誘いをいかに断るかなど、やはり調整が必要になるのではないか。
- 海外に行ったという経験
  - 初めての海外は色々と緊張するので、プレッシャーがかかる学会発表や仕事だと大変。旅行やサマースクールで慣れておくと多少楽かもしれない。


## 旅のコツなど
- ガイドブックを見るのが一番、現地のネット環境がわからないので自分は紙の本のタイプのガイドブックを持っていく（他の参加者には随分と珍しがられた）
  - 観光地の情報だけでなく現地で気を付けるべきことなども載っている
- 現金は現地に着いてから両替した方が良い
  - 当時の額面レートは1コルナ＝6.5円程度（インターネット調べ）だったが、日本の空港の両替所では1コルナ＝10円弱だった。
  - プラハ市内の至る所に両替所があり、1コルナ＝7円くらいで両替ができた。手続きも日本よりシンプル。空港から市内へのバスや電車はクレカでOK。
  - 街中にATMがたくさんあるので、クレカの海外キャッシングでもよい。1コルナ＝8円強。
    - 海外キャッシング対応のハズの自分の楽天カード（VISA、MC）は2枚とも使えず、緊急時用の3枚目のカードで辛うじて使えた。
    - 出発前に確認する術があれば良いが不明。
- タッチ決済のクレジットカードが便利
  - プラハ市内はかなり小さく古い店舗でもクレカタッチ決済に対応している
  - 今新しく発行するカードはほぼ対応しているかもしれないが、更新間際の自分の古いカードは対応しておらず、支払いのテンポが悪かった。

[^1]: [Příhodová2023](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10084390)