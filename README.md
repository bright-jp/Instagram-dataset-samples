# instagram-dataset-samples

<h2>2180人のInstagramコーディングインフルエンサーのサンプルデータセット</h2>

![instagram dataset header](https://github.com/bright-jp/Instagram-dataset-samples/blob/main/instagram-datasets.PNG)

2000人以上の主要なInstagramの[Github](https://www.instagram.com/explore/tags/github/)コーディングインフルエンサーのGitHubデータセットサンプルです。データセットは<b>Bright Data Collector</b>を使用して抽出されました。

<h2>この無料データセットに含まれるデータポイント:</h2>

* フォロワー数
* プロフィールタイプ
* アカウントタイプ
* エンゲージメントスコア
* カテゴリ
* ロケーション
* 外部/バイオリンク
* 使用されたハッシュタグ
* ブランド提携
* バイオ
* ハイライト
* 投稿



これは、「All Instagram account, business & nonbusiness (public data)」データセットから派生したサンプルサブセットです。
このデータセットには<b>614,000,000件のInstagramプロフィール</b>が含まれています。

この例では、Bright Dataのコントロールパネルで利用できるスマートフィルタークエリを使用して、大規模なデータセットをより小さなサブセットに絞り込みました。
<h2>このサブセットのフィルタリングに使用したクエリ:</h2>


*   	$or: [{"post_hashtags":"github"},{"bio_hashtags":"github"}]
*   	followers: {"$gt":100}

追加のフィルタークエリ値には、<b>投稿数、cuntry、認証済みアカウント、複数ハッシュタグの組み合わせなど</b>が含まれます。

利用可能なデータセットファイル形式: <b>JSON, NDJSON, JSON Lines, CSV, or Parquet.</b>。

データセットの配信タイプオプション: <b>API download, Amazon S3, Google cloud, Microsoft Azure, SFTP</b>。

抽出されたデータポイントに追加できるデータエンリッチメント: <b>平均投稿エンゲージメント率、ブランド提携など</b>。

完全版の<b>[Instagram dataset](https://brightdata.jp/products/datasets/instagram)</b>を入手してください。

<h2>利用可能な追加のInstagramデータセット:</h2>

*   635,000,000 「Instagram profiles dataset」 
*   89,000,000 「Instagram posts dataset」
*   12,490,000 「Instagram reels dataset」
*   206,000 「Instagram comments dataset」

<h2>学術研究者およびNGO向けのWebスクレイピングツールとデータセットへの無料アクセス</h2>

Bright Initiativeは、さまざまな環境・社会的課題の推進に取り組む主要な学術機関の学部および研究者、NGO、NPOに対して、Bright Dataの[Web Scraper APIs](https://brightdata.jp/products/web-scraper)へのアクセスを提供しています。申請は[こちら](https://brightinitiative.com)から提出できます。

### Instagramを自分でスクレイピングしたいですか？当社の[Instagram Scraper](https://brightdata.jp/products/web-scraper/instagram)をご利用ください