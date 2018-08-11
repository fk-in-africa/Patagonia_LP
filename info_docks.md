

# そなえLP引き継ぎドキュメント

  written by [hiroki0816](https://github.com/hiroki0816)
＊大杉さんの資料をMarkDownに書き下しました。
[emoji](https://www.webfx.com/tools/emoji-cheat-sheet/)




## 記載の目的

1. そなえLP制作背景を残しておくこと
2. LPの管理/保守の方法を明示すること
3.  LPの管理/保守ができるようになる為の学び方を伝えること
4.   (1) ~(3)を通じてKBメンバーの誰でもLPの保守/編集/新規作成ができる手助けになる、、、かも

  

## 対象
- KBメンバー
- これからLPの制作や管理を担うことになりそうな人

  

## 記載項目

1. 基本的なLP制作のステップ + そなえでの事例
	1. 戦略設計
	2. トーン&マナーの作成
	3. ワイヤーの作成
	4. デザインカンプの作成
	5. コーディング
	6. 公開

2. 保守の仕方
	1. デザインのマスターファイル管理
	2. コードの参照場所(github)
	3. コードの編集の仕方と更新方法

3. おすすめの資料/勉強の仕方
	1. 必要な知識
	2. 資料/学び方

  

## 基本的なLP制作のステップ + そなえでの事例

### ①戦略設計

何のためにLPを制作するのか、目標は何か、目標を達成するためにどのような情報項目/導線設計が必要になるのかを言語化します。  

主旨とはずれるので、このドキュメントでは詳細には書きませんが、要旨だけまとめると、LPでは「**閲覧者の流入数(LPを見る人)**」×「**コンバージョン(契約)率**」という2つの指標が目標(=@ではEP獲得)の達成の為に重要なものとなります。  

「**閲覧者の流入数**」を考える際には「どのようなステータスの人」が「どれくらい見てほしいのか」、あるいは、「どの媒体からの流入」を見込んでいるのか、具体的に「どのような場面でLPを見るのか」等、観点を分解してしっかりと考えておくと良いでしょう。  

また、「**コンバージョン率**」については、今回はLPのゴールを「個別説明会(プレコン)に参加すること」としていて、そのために、抽象化すると①コンセプトに共感する(about)②具体的なプログラムのイメージを掴む(program ~ features)③信頼感を得る(message)④エントリーする という仮説の流れをLPの中に組み込んでいます。今回は、この流れ自体の検証は未完了なので実際にユーザーに見せつつ、ペルソナが話を聞きたいと思える/障壁を超えさせてあげられるようなトリガーは何かを見つけてLPに反映していけばよいかと思います。  
 
(蛇足ですが、海外インターンシップに参加することは心理的/期間的/心理的にも障壁が高い商品なので、いかにこの障壁が下がるような工夫ができるかをよく考えて検証していくことが重要になるかと思います。)  

  

**参考記事**  
[https://olein-design.com/blog/create-lp-1](https://olein-design.com/blog/create-lp-1)
[https://liskul.com/landingpage-strategy-1295](https://liskul.com/landingpage-strategy-1295)

  

**以下の流れの前提となるもの**  
[https://2016.uxdaystokyo.com/article/five-stages-thet-makeup-the-ux.html](https://2016.uxdaystokyo.com/article/five-stages-thet-makeup-the-ux.html)

UIデザインの基礎となる概念ですが、LPを考えていく際にも重要な考え方となるかと思います。  

![ユーザー体験](https://d2mxuefqeaa7sj.cloudfront.net/s_0D1298723F3D0740EFFC2AB0669FF0FAD36BA55A1981B0D6E37845B7AA0776C2_1533712567034_DiiCx9tU8AADsbP.jpg)

  

**工数**  
1. 顧客獲得戦略の整理  (YP書くのと同じくらい)
2. LP目標と理想のユーザーの感情遷移の整理  (2h)
3. LPに載せる情報項目と優先度/順番の整理(1h)

 
### ②トーン&マナーの設定

LPの画面を作っていく際に、どのような色/フォント/余白感であれば伝えたい印象が伝わるかを決めていきます  

具体的には、トーン&マナーの設計を行うことで画面のイメージを付けていきます。  

トーン＆マナーを作る際には、コンセプトの言語化、デザインの要素の抽出、色や余白感の設定というようなプロセスが一般的です。  

そなえではコンセプトを具体化するためのMtgを2時間×3回ほど行いました。（今回はロゴの設計も同時並行に行っていたので重複する工程となりました)[**こちら**](https://docs.google.com/document/d/11fVpcKHSj4kiGcpe2SmLX8R-a5AIIgDYDFbBNfJPRDM/edit)がその際のドキュメントです  

  

コンセプトを具体化したものに対するデザイン要素の抽出という工程は、まとまったものが残っていないので(ごめん)代わりに、[**cocodaというサービスのトンマナを決めた時のもの**](https://www.figma.com/file/0toDeyilPro8OVdEoGEENWpB/Cocoda-PD%E8%A8%AD%E8%A8%88?node-id=0%3A1)と参考記事を貼っておきます。  

  

イメージはこんな感じ。  

![](https://d2mxuefqeaa7sj.cloudfront.net/s_0D1298723F3D0740EFFC2AB0669FF0FAD36BA55A1981B0D6E37845B7AA0776C2_1533654644597_+2018-08-08+0.10.13.png)

  

**参考記事**  

[https://www.concentinc.jp/design_research/2014/04/tone-and-manner/](https://www.concentinc.jp/design_research/2014/04/tone-and-manner/)

  

**工数**  
1. コンセプトの言語化  (4h)
2. デザインパターンの収集  (2h)
3. チームでのすり合わせ  (1h)
4. デザイン要素の具体化  (1h)

  

### ③ワイヤーの作成

①で決めた情報項目と流れを大まかな画面のレイアウトに落とし込んでいきます(この工程をワイヤー作成と言います)。特に①見る観点は目標(=今回はプレコン参加申し込み)という行動を促す上で適切な情報構成であるか、②大まかなレイアウトとしてデザイン観点から破綻していないかという2点です。  
  

画面のイメージはこんな感じです。  

![](https://d2mxuefqeaa7sj.cloudfront.net/s_0D1298723F3D0740EFFC2AB0669FF0FAD36BA55A1981B0D6E37845B7AA0776C2_1533639751232_+2018-08-07+20.01.25.png)

  

制作のために使用したのはAdobe Xdというプロトタイピング制作ツールです。  

パワポやキーノートでも制作可能ですが、パワポが使えれば学習コストがほぼなく直感的に使用できるのでこちらの使用をおすすめします。また、Adobe Xdであれば無料で使用できるプランが有り、そのプランでほぼ十分なパフォーマンスを期待できるので、入れておくと良いかと思います。  

ダウンロードは[**こちら**](https://www.adobe.com/jp/products/xd.html?gclid=EAIaIQobChMIiLPZmeba3AIV2KmWCh1BYAl8EAAYASAAEgKakvD_BwE&sdid=19SCDRPN&mv=search&s_kwcid=AL!3085!3!269354875902!e!!g!!adobe%20xd&ef_id=W0RiygAABcJdN588:20180807110639:s)

  

また、実際に作成したものをKBのドライブ(KBLC>1819term>OGX>ブランド広報物>そなえ)にあげているので参考までに見てみるとよりイメージが掴めるかと思います。  

リンクは[**こちら**](https://drive.google.com/drive/u/1/folders/1ClAUUn9kdMX3TsIFDbpBOMbcdFXAEGVU)

**参考記事**  
[https://ferret-plus.com/5955](https://ferret-plus.com/5955)
[https://liginc.co.jp/367737](https://liginc.co.jp/367737)

**工数**  
1. ワイヤー作成  (3h)

  

### ④デザインカンプの作成

③で作成したワイヤーと②で作成したトーン＆マナーを統合して、実際にweb上で表示される画面と同じものをツール上で作っていきます。  

特に見る観点は①伝えたい印象が適切に伝わるデザインであるか②実装(コーディング)が不可能でないデザインであるかという2点かなと思います。  

  

画面イメージはこんな感じ。  

PC画面だけでなくスマホでも見れるように今回は2パターンのデザインを作ってあります。  

![](https://d2mxuefqeaa7sj.cloudfront.net/s_0D1298723F3D0740EFFC2AB0669FF0FAD36BA55A1981B0D6E37845B7AA0776C2_1533640389969_+2018-08-07+20.12.58.png)

  

ここでもワイヤーと同じくAdobe Xdというツールを使用して作成しており、実際の制作物はドライブにあげてあるので、参考までに見ておくとよいかと思います。  

  

**工数**  
1. デザインカンプ作成  (6h)

  

### ⑤コーディング

デザインできたLPの画面を、ブラウザ上で参照できるようにHTML / CSS / JavaScript等のプログラミング言語を用いて、PCで読み取るようのデータに組み替えていきます。  

  

イメージはこんな感じ。  

![](https://d2mxuefqeaa7sj.cloudfront.net/s_0D1298723F3D0740EFFC2AB0669FF0FAD36BA55A1981B0D6E37845B7AA0776C2_1533641237858_+2018-08-07+20.27.05.png)



若干専門的な知識が必要となる工程なので、インプット的な情報は下の「[勉強の仕方](https://github.com/Yuki-k-lion/sonaeLP/blob/master/info_docks.md#%E5%8B%89%E5%BC%B7%E3%81%AE%E4%BB%95%E6%96%B9)」という欄に記載しておきます。  

  
簡単に技術構成だけ記載しておくと、

使用しているのはHTML / CSS / Javascriptという3つの言語です。

バージョン管理ツールはGithubというwebサービスを使用しています。

実際のファイルはGithub上の[**このページ**](https://github.com/hiroki0816/sonaeLP)(プラーベート設定をしているので招待リンクが必要となります)と、ワイヤーフレームと同じく、ドライブ上にあげているので参考までに見てみると良いかと思います。

  

参照する(あるいはコードを書く)時には、それ用のエディタが必要なのですが今回はatomというツールを使用しました。こちらも無料なので、入れてみると良いかと思います。ダウンロードは[**こちら**](https://atom.io/)。

  

また、最近はそこまでコードが描けなくてもブラウザ上で参照可能なものが作れる便利ツールがたくさん出てきているので、そちらを使用しても良いかもしれません。

  

**その便利ツール**  
Studio([https://studio.design/ja](https://studio.design/ja))

**工数**  
1. コーディング  (10h)

  

### ⑥公開
※このあたりはMCの制度があるようだけど、あまり詳しくないので⑤が終わった段階で引き渡しました。記載が必要であれば、MCの方に聞いてくだせぇ。  

簡単に何をするステップなのかを記載しておくと、HTMLやCSSで書かれたデータだけではブラウザ上で他の人が見ることができないので、ブラウザ上で表示させるためのデータの住所となるドメインと、実際にデータが保存されることになるサーバーというものを取得することになります。

この工程が終わると、Google ChromなどのブラウザでURLを打ち込むとそのサイトが参照できるようになります。

```
20180811_MCIS_komatsu_add
こちらはを[readme](https://github.com/Yuki-k-lion/sonaeLP/tree/master)を見てください。

```  

## 保守の仕方

ここではLP制作を担当した大杉からKBメンバーの皆さんに今後の作業を引き継いだ後に、皆さんが適切に保守運用ができるようにするための簡易マニュアル的に、必要なアクションをまとめていきます。

このドキュメントでは以下の3つの観点から保守の運用方法について書いておきます。

- デザインのマスターファイル管理
- コードの参照場所(github)
- コードの編集の仕方と更新方法

### デザインのマスターファイル管理

LPをローンチした後に、ターゲットの方々の反応を回収/検証してLPの構成やデザインを変えたほうが良い、あるいは具体的な参加の工程/説明会の日程等を載せたほうが良いのではないかというタイミング来ると思います。

その際に、デザインのマスターファイルを用意せずにwebの方のデザインをいじってしまうと、

1. デザインのバージョン管理ができない

　→ 更新したデザインの検証が終わってから、またデザインをもとに戻したい、あるいは、どのデザインで検証したのか蓄積しておきたいという場合に参照ができない

2. デザインのトンマナが統一しにくくなる

　→ 大本となるデザインがなく、複数人がそれぞれにデザインをいじっていくと統一したトンマナが少しずつ崩れて、統一感の無いデザインになっていってしまう。

というような問題が発生してしまいます。

 
基本的には、常に最新版のデザインが格納されているデザインファイルを作っておき、デザインの責任者が管理するようにしておきましょう。

今回使用したXdファイルはドライブにあげてあるので、そちらをダウンロードして、マスターファイルにしてしまうのが良いかと思います。

  
**参考記事**  
[https://ics.media/entry/18004](https://ics.media/entry/18004)
[https://ics.media/entry/18004](https://ics.media/entry/18004)

蛇足ですが、LPも出して終わりにしてしまうのではなく、実際のターゲットの反応を回収し、より目標達成に近づくように更新を重ねることが必要です。その際の組織体制の作り方や、制度設計を以前まとめたので、そちらの記事も貼っておきます。
[https://note.mu/greatest_hiroki/n/n879dc05ab952](https://note.mu/greatest_hiroki/n/n879dc05ab952)

  
### コードの参照場所(github)

コードの管理はgithubというバージョン管理ツールを使用しています。

現在は、github上にLC側でLPのコードを保存しているレポジトリという場所を作って、そこにあるコードを更新し次第、MC担当者に連絡し、実際のwebページへの反映するというフローになっています。

  
**githubとは**  
[https://techacademy.jp/magazine/6235](https://techacademy.jp/magazine/6235)


おそらく引き継ぎをしていく際に保管するレポジトリの所有者をKBメンバーの誰かに移すと思うのですが、一旦は大杉のgithubレポジトリにKB担当者を共同編集者として追加する形で管理をしています。

共同編集者には以下の工程を行うと追加することができます。

**githubにてプライベートレポジトリに共同編集者を追加する方法**  
[https://code-schools.com/github-invite/](https://code-schools.com/github-invite/)

  ```
  20180811_MCIS_komatsu_add
  Current use in https://github.com/Yuki-k-lion/sonaeLP
  ```

### コードの編集の仕方と更新方法

コードを更新する際には、

1. githubからそなえのレポジトリを自分のPCにクローン(ローカルでいじれるようにファイルをダウンロード)してくる
2. ブランチ(作業をするために大本のコードをコピーしたもの)の作成を行う
3. エディタで開いてコードを編集する
4. 変更内容を保存(add / commit)して、github上のファイルにも反映させる(push)

↓(1) git addのイメージ

![git addのイメージ](https://i.gyazo.com/629b24cb7b1dfee14420ffeab26b5167.gif)

↓(2) git commit のイメージ

![](https://i.gyazo.com/f7877738e7719af4dbb63a67ed28202c.gif)

↓ git pushのイメージ

![](https://i.gyazo.com/55d58adf54a669233feabfdbf7dc022a.gif)

  

⑤マスターブランチへの反映依頼(プルリクエスト)をして、変更を反映する(マージ)

  

というようなプロセスを踏むと良いかと思います。

  

これらを一から説明するとすごい文量になってしまうので、参考書籍/記事を載せることで代替します。とても丁寧に書いてある記事なので、おすすめです。

  **参考書籍**  
[https://www.amazon.co.jp/exec/obidos/ASIN/4863542178/gooddays1-22/](https://www.amazon.co.jp/exec/obidos/ASIN/4863542178/gooddays1-22/)

 **参考記事**  
[https://employment.en-japan.com/engineerhub/entry/2017/01/31/110000](https://employment.en-japan.com/engineerhub/entry/2017/01/31/110000)
[http://jsstudy.hatenablog.com/entry/clone-a-repository-from-GitHub](http://jsstudy.hatenablog.com/entry/clone-a-repository-from-GitHub)


## 勉強の仕方

### ①必要かつちょっぴり専門的な知識(前提)

上記の工程を通して、実際に必要となる知識でありかつ、ちょっと勉強しないとわからないなーというものを整理しておきます。

#### デザイン系
- デザインの基礎知識
- デザインツールの使い方
- webデザインをする際の基礎知識

#### プログラミング系
- HTML / CSS / Javascript
- jQuery / Bootstrap等そなえLPで使用しているライブラリについて
- ファビコン / twitterカードの指定
- Git / Githubの使い方
  
### ②デザインのおすすめの資料/勉強の仕方

**デザインの基礎知識**  
「デザインはセンス」などと言われることも多々ありますが、絵画や彫刻等の自己表現をするためのアート/芸術とは異なり、特定の課題解決をするために視覚的(定義によりますが、ここでは所謂ビジュアルデザインを指します)な表現を用いる概念であるデザインは、理論を学び、良いデザインに触れ、練習を重ねれば適切なデザインを作れるようになります。ここでは、その理論の学ぶ上でオススメの書籍/サイトを載せておきます。


**デザインの理論を学びたい方**  
[ノンデザイナーズ・デザインブック ](https://www.amazon.co.jp/%E3%83%8E%E3%83%B3%E3%83%87%E3%82%B6%E3%82%A4%E3%83%8A%E3%83%BC%E3%82%BA%E3%83%BB%E3%83%87%E3%82%B6%E3%82%A4%E3%83%B3%E3%83%96%E3%83%83%E3%82%AF-%E7%AC%AC4%E7%89%88-Robin-Williams/dp/4839955557/ref=sr_1_1?ie=UTF8&qid=1533643401&sr=8-1&keywords=%E3%83%8E%E3%83%B3%E3%83%87%E3%82%B6%E3%82%A4%E3%83%8A%E3%83%BC%E3%82%BA%E3%83%BB%E3%83%87%E3%82%B6%E3%82%A4%E3%83%B3%E3%83%96%E3%83%83%E3%82%AF)

[なるほどデザイン(https://www.amazon.co.jp/%E3%81%AA%E3%82%8B%E3%81%BB%E3%81%A9%E3%83%87%E3%82%B6%E3%82%A4%E3%83%B3%E3%80%88%E7%9B%AE%E3%81%A7%E8%A6%8B%E3%81%A6%E6%A5%BD%E3%81%97%E3%82%80%E6%96%B0%E3%81%97%E3%81%84%E3%83%87%E3%82%B6%E3%82%A4%E3%83%B3%E3%81%AE%E6%9C%AC%E3%80%82%E3%80%89-%E7%AD%92%E4%BA%95-%E7%BE%8E%E5%B8%8C/dp/4844365177/ref=pd_sim_14_1?_encoding=UTF8&pd_rd_i=4844365177&pd_rd_r=e30180d8-9a39-11e8-ad37-27c7ea2ab43d&pd_rd_w=JNlH0&pd_rd_wg=aUZHz&pf_rd_i=desktop-dp-sims&pf_rd_m=AN1VRQENFRJN5&pf_rd_p=053a78c4-e34f-47d4-9426-4d23f47a211d&pf_rd_r=F8JK2ZXFCKQ264SW2XTG&pf_rd_s=desktop-dp-sims&pf_rd_t=40701&psc=1&refRID=F8JK2ZXFCKQ264SW2XTG)

[誰のためのデザイン](https://www.amazon.co.jp/%E8%AA%B0%E3%81%AE%E3%81%9F%E3%82%81%E3%81%AE%E3%83%87%E3%82%B6%E3%82%A4%E3%83%B3%EF%BC%9F-%E5%A2%97%E8%A3%9C%E3%83%BB%E6%94%B9%E8%A8%82%E7%89%88-%E2%80%95%E8%AA%8D%E7%9F%A5%E7%A7%91%E5%AD%A6%E8%80%85%E3%81%AE%E3%83%87%E3%82%B6%E3%82%A4%E3%83%B3%E5%8E%9F%E8%AB%96-D-%E3%83%8E%E3%83%BC%E3%83%9E%E3%83%B3/dp/4788514346/ref=sr_1_1?s=books&ie=UTF8&qid=1533643467&sr=1-1&keywords=%E8%AA%B0%E3%81%AE%E3%81%9F%E3%82%81%E3%81%AE%E3%83%87%E3%82%B6%E3%82%A4%E3%83%B3)

  

**良いデザインに触れたい方**  
[Pinterest ](https://www.pinterest.jp/)
[dribblbe](https://dribbble.com/)


**デザインツールの使い方**  

パワポやキーノートでも代替可能ですが、LPやweb制作をする際にはwebデザインやUIデザインに特化しているデザインツールを使うことをオススメしており、今回のLP制作でも使用しているAdobe Xdは入れておくのが良いかと思います。

  

**参考記事**  

[https://coliss.com/articles/build-websites/operation/design/adobe-xd-starter-kit.html](https://coliss.com/articles/build-websites/operation/design/adobe-xd-starter-kit.html)
[https://note.mu/co_co_d3/n/n4e910ec83b60](https://note.mu/co_co_d3/n/n4e910ec83b60)

  
**webデザインをする際の基礎知識**

スライドや紙面でのデザインとは異なり、webデザインを行う際にはPCやスマホなどのデバイスによってデザインが変える必要がある(画面幅が違うので)ことや、コーディングを通して実現可能であるかどうかという技術的制約があったりと特に注意しておかないといけないポイントがいくつかあるので、その辺りも念頭において勉強しておくと良いかと思います。

  

**参考記事**  

[https://www.internetacademy.jp/it/design.html](https://www.internetacademy.jp/it/design.html)

[https://techacademy.jp/magazine/7802](https://techacademy.jp/magazine/7802)

  

### ③プログラミングのおすすめの勉強の仕方

**HTML / CSS / Javascript**
前述したとおり、ブラウザ上でwebページを表示させるためには、デザインをHTML / CSS / Javascript等のプログラミング言語に変換する必要があります。

ここではオススメの学習サイトと、勉強方法について記載しておきます。

  
[Progate](https://prog-8.com/)
完全なプログラミング初学者向けの学習サービスです。環境構築などが必要なく、ブラウザ上でプログラミングが学べるのと、キャラクターが可愛いのでおすすめです。初級編は全て無料ですが、一定の難易度以降は月額980円程度の課金が必要になります。筆者的には課金する価値は間違いなくあるサービスだと思います。

具体的には、HTML & CSSコース /Javascriputコースを初級編から上級編までの2週ずつくらいしたらある程度書けるようになるかと思います。ちなみに僕は現在261レベルです。

 [ドットインストール](https://dotinstall.com/lessons)
3分動画でプログラミングを学んで行ける学習サービスです。実際にプログラムを書いている画面を見ながら授業的に学ぶことができます。Progateに比べると若干難易度が高いように感じますが、学習できる範囲が多いのでおすすめです。Progateでイメージを掴んだら、ドットインストールでしっかりと作れるようになっていくという流れがいいかと思います。


 **jQuery / Bootstrap**
今回のLP作成では、HTML / CSS / Javascriptをそのまま書くだけでなく、特定の表現方法が簡単な記述で実現できるようになるライブラリというものを使用しています。具体的にはjavascriptライブラリのjQueryとCSSライブラリのBootstrapというものです。

特にBootstrapは簡単に保守もしやすいようにと考えて導入しているのですが、なれるまでは若干難しいかもしれないので、追加で学習しておく必要があるかと思います。

  

jQueryについては前述したProgateのjQueryコースを2週程度すれば理解ができると思います。また、具体的にはページをスクロールした時に、ふわっとパーツが浮かび上がる表現をするためにjQueryを使用しており、その技術についてはこの記事を見れば分かるかと思います。([**こちら**](https://www.webprofessional.jp/js-library-scrollreveal/))

  

Bootstrapについては、前述したドットインストールにBootstrap4入門というコース(無料)があるのでそちらを通して学習すればそなえLPを編集できる程度の力が身につくかと思います。([**こちら**](https://dotinstall.com/lessons/basic_twitter_bootstrap_v5))

具体的には、グリッドシステム([**参考はこちら**](http://websae.net/twitter-bootstrap-grid-system-21060224/))と呼ばれるレイアウト方法の使用、ヘッダーメニューをスマホ画面ではハンバーガーメニューにする、メッセージ部分で顔写真をクリックするとモーダルを表示させる等の場面で使用しています。

  

上記だけでは足りない知識があるかもしれませんが、それぞれGoogleで検索すれば十分すぎるくらい情報が出てくるので探してみるのをおすすめします。

**ファビコン/twitterカードの指定**
細かい部分ですが、変更するかもしれない可能性が高そうなファビコンと、twitterカード設定の変更方法についても記載しておきます


>ファビコンとは

ブラウザのタブに表示されるアイコンの事。

![](https://d2mxuefqeaa7sj.cloudfront.net/s_0D1298723F3D0740EFFC2AB0669FF0FAD36BA55A1981B0D6E37845B7AA0776C2_1533657621360_+2018-08-08+0.59.18.png)

設定してないとこんな感じになる。細かいですがこういうところもきちんと表示させておかないと信頼感にもつながったりするのでちゃんとしておいた方が良いです

![](https://d2mxuefqeaa7sj.cloudfront.net/s_0D1298723F3D0740EFFC2AB0669FF0FAD36BA55A1981B0D6E37845B7AA0776C2_1533657708189_+2018-08-08+1.01.34.png)

  

>ファビコンの設定方法

[https://blog.codecamp.jp/favicon_intro](https://blog.codecamp.jp/favicon_intro)

  

  

>Twitter(SNS)カードとは

Twitterとかラインとかでリンクをシェアした時に表示される画像の事。

![](https://d2mxuefqeaa7sj.cloudfront.net/s_0D1298723F3D0740EFFC2AB0669FF0FAD36BA55A1981B0D6E37845B7AA0776C2_1533657899918_+2018-08-08+1.04.33.png)

設定してないとこんな感じのそっけない感じになる。こちらも細かいですがSNSでシェアした時のクリック率にも大きく関わるので、抜け目なく設定しておくのが良いです。

![](https://d2mxuefqeaa7sj.cloudfront.net/s_0D1298723F3D0740EFFC2AB0669FF0FAD36BA55A1981B0D6E37845B7AA0776C2_1533657927641_+2018-08-08+1.04.41.png)

>Twitterカードの設定方法

[https://saruwakakun.com/html-css/reference/twitter-card](https://saruwakakun.com/html-css/reference/twitter-card)

  

ちなみにそなえではここの記述で設定を行っています。

![](https://d2mxuefqeaa7sj.cloudfront.net/s_0D1298723F3D0740EFFC2AB0669FF0FAD36BA55A1981B0D6E37845B7AA0776C2_1533658156850_+2018-08-08+1.08.07.png)

  
 **Git / Githubの使い方**

今回は記述したコードをGithubというバージョン管理ツールを使用して管理しており、また、それを操作するためにGitという技術を理解する必要があります。

簡単に言うと、「コードを管理するためのGoogleドライブ」みたいなものだと認識したらOKです。

  

Gitについては前述したProgateにコマンドラインコース / Gitコースがあるので、それぞれ学習するとイメージがつくかと思います。

  

イメージがついたら、次は前述のドットインストールにてgit入門というコースがあるので、そちらを学習したらより深い理解ができるかと思います([**こちら**](https://dotinstall.com/lessons/basic_git))

  

  

![cat face](https://paper.dropboxstatic.com/static/img/ace/emoji/1f431.png?version=3.1.2 "cat face" =20x20)おわり![dog face](https://paper.dropboxstatic.com/static/img/ace/emoji/1f436.png?version=3.1.2 "dog face" =20x20)

  

  

>P.S
もし分からないことや、聞きたい事があれば僕(1718termKBOGXD)に聞いていただけたら何でも答えるので気軽に連絡してください。
Twitterは[**こちら**](https://twitter.com/greatest_hiroki)
Facebookは[**こちら**](https://www.facebook.com/profile.php?id=100009226949391)
