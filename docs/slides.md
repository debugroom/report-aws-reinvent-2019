<section data-background="images/reinvent.jpg">

<span style="font-size:48px">Las Vegas Report</span>
<br/>
<span style="font-size:24">re:Cap for NTT Data 2019.12.18</span>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
</section>

---

### 自己紹介

<p><img src="images/profile.jpg" style="float:left" width="40%"></p>
<div style="margin: 20px 0px auto">
<ul>
  <div style="font-size:16px; margin:auto">
  <li style="margin: 10px 0px 10px">名前：川畑 光平</li>
  <li style="margin: 10px 0px 10px">所属：デジタル技術部アジャイルプロフェッショナルセンタ</li>
  <li style="margin: 10px 0px 10px">今の仕事：プロジェクト支援(主にクラウド系)とR&amp;D</li>
  <li style="margin: 10px 0px 10px">これまでの仕事
    <ul>
      <li>某金融機関IBアプリケーション開発(投資信託業務)</li>
      <li>某金融社団法人システム基盤開発</li>
      <li>TERASOLUNA/自動化ツール開発</li>
      <li>プロジェクト支援多数(AP基盤/アーキテクト)</li>
    </ul>
  </li>
  <li style="margin: 10px 0px 10px">Technical background
    <ul>
      <li>シニアITスペリャリスト(ソフトウェアアーキテクチャ)</li>
      <li>TERASOLUNA認定アーキテクト</li>
      <li>Pivotal certified Spring Professional</li>
      <li>Redhat certified engineers</li>
      <li>AWS Solution Architect Professional</li>
    </ul>
  </li>
  <li style="margin: 10px 0px 10px"><a href="https://aws.amazon.com/jp/partners/ambassadors/?cards-body.sort-by=item.additionalFields.ambassadorName&cards-body.sort-order=asc&awsm.page-cards-body=1&cards-body.q=Kawabata&cards-body.q_operator=AND" target="_blank">2019 APN AWS Top Engineers &amp; Ambassadors</a></li>
  <li style="margin: 10px 0px 10px">マイナビ「ITSearch+」で記事連載中</li>
  </div>
</ul>
</div>

***

<span style="font-size:48px">re:Invent My Schedule</span><br/>

![image](images/schedule.png)

---

<span style="font-size:48px">Today's Topic</span><br/>

![image](images/schedule-scope.png)

***

<section data-background-video="https://debugroom-sample.s3-ap-northeast-1.amazonaws.com/keynote.mov" data-background-video-loop data-background-video-muted data-background-opacity="1">
  <div style="position: absolute; width: 40%; right: 0; box-shadow: 0 1px 4px rgba(0,0,0,0.5), 0 5px 25px rgba(0,0,0,0.2); background-color: rgba(0, 0, 0, 0.9); color: #fff; padding: 20px; font-size: 20px; text-align: left;">
    <h2>Keynote Hall</h2>
    <a href="https://youtu.be/OdzaTbaQwTg?t=2421" target="_blank">VENETIAN HALL A</a>
  </div>
</section>

***

<span style="font-size:48px">Cell-based Architectures</span><br/>

<p><a href="https://youtu.be/OdzaTbaQwTg?t=2421" target="_blank"><img src="images/keynote.png" width="100%"></a></p>

---

<span style="font-size:24px">Cell-based Architectures - Reducing blast radius(爆発半径：障害影響の範囲) -</span>

![image](images/cell-based-architecture.png)

<span style="text-align:right;font-size:10px">
出典：「Cell-Based Architecture」（Asanka Abeysinghe | Deputy CTO & VP of Architecture | Paul Fremantle | CTO and Co-Founder - CTO Office | WSO2, Inc）： <a href="https://github.com/wso2/reference-architecture/blob/master/reference-architecture-cell-based.md" target="_blank">wso2/reference-architecture</a>
</span>

---

<span style="font-size:24px">Cell-based Architectures - Beyond MicroService -</span>

<p><img src="images/cell-based-architectures.png" width="40%"></p>
<div style="font-size:14px; margin:auto">
<ul>
  <li style="margin: 10px 0px 10px">セルは単一ないしは幾つかのマイクロサービスアプリケーション、サーバレスアプリケーション・データストアなどのコンポーネント(データプレーン)で構成される</li>
  <li style="margin: 10px 0px 10px">セルはメッセージキューやESB、REST APIなどのゲートウェイをもつ(コントロールプレーン)</li>
  <li style="margin: 10px 0px 10px">セルにはレガシーシステムなど巨大なコンポーネントの集まりも指す場合もある</li>
  <li style="margin: 10px 0px 10px">セルはアジャイル開発を行うチームが、CI/CD等によって自動化された開発プロセス、デプロイ、リリースサイクルを最適化される単位である</li>
  <li style="margin: 10px 0px 10px">セルはDomainDrivenDevelopmentで言えば、「境界づけられたコンテキスト」の単位で相互に独立しており、スケーラビリティを有する</li>
</ul>
</div>

---

<span style="font-size:24px">Cell-based Architectures をインターネットバンキングの例で考えてみよう</span>

<p><img src="images/cell-based-architecture-for-ib.png" width="60%"></p>

---

<span style="font-size:24px">Cell-based Architecturesをインターネットバンキングの例で考えてみよう </span>

<p><img src="images/cell-based-architecture-error-for-ib.png" width="60%"></p>

---

<section data-background="images/cell-based-architecture-session-1.jpg">
<span style="font-size:24px">Cell-based Architectures(MicroService)がもたらすもの</span>

<br/>

<p><img src="images/cell-based-architectures.png" width="40%"></p>

<div style="font-size:24px; margin:auto">
  <table>
    <thead>
      <tr>
        <th>Pros</th>
        <th>Cons</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>アベイラビリティ(耐障害性)</td>
        <td>データ一貫性の低下</td>
      </tr>
      <tr>
        <td>柔軟なスケーラビリティ</td>
        <td>複雑性</td>
      </tr>
      <tr>
        <td>開発のアジリティ</td>
        <td></td>
      </tr>
    </tbody>
  </table>

<br/>
</div>
</section>



---

<span style="font-size:24px">Cell-based Architectures Session</span>

<div style="position: absolute; width: 40%; right: 50px; top: 300px; box-shadow: 0 1px 4px rgba(0,0,0,0.5), 0 5px 25px rgba(0,0,0,0.2); background-color: rgba(0, 0, 0, 0.9); color: #fff; padding: 20px; font-size: 24px; text-align: left;">
  <p>障害の影響範囲の極小化に向け、AWSでCell-based Architecturesを如何に実現するか</p>
</div>

---

<span style="font-size:24px">Cell-based Architectures Session</span>

<p><img src="images/cell-based-architecture-session-2.jpg" width="100%"></p>

---

Conclusion

<span style="font-size:24px">Cell-based Architecturesは当社の抱える<br/>ラージスケールなアプリケーションアーキテクチャやレガシーデジタルインテグレーションの課題解決に向けた1つの指針となる</span>

***

<section data-background-video="https://debugroom-sample.s3-ap-northeast-1.amazonaws.com/lambda-for-java.mov" data-background-video-loop data-background-video-muted data-background-opacity="1">
  <div style="position: absolute; width: 40%; right: 0; box-shadow: 0 1px 4px rgba(0,0,0,0.5), 0 5px 25px rgba(0,0,0,0.2); background-color: rgba(0, 0, 0, 0.9); color: #fff; padding: 20px; font-size: 20px; text-align: left;">
    <h2>Session</h2>
    <a href="https://youtu.be/ddg1u5HLwg8?t=0" target="_blank">Best Practice for AWS Lambda and Java</a>
  </div>
</section>

***

<span style="font-size:44px">Session : Best practice AWS Lambda for Java</span><br/>

<p><img src="images/lambda-for-java-session.png" width="100%"></p>

---

<span style="font-size:44px">Conclusion : Best practice AWS Lambda for Java</span><br/>

<p><img src="images/graalvm.png" width="100%"></p>

***

<section data-background-video="https://debugroom-sample.s3-ap-northeast-1.amazonaws.com/ambassadors-meetup.mov" data-background-video-loop data-background-video-muted data-background-opacity="1">
  <div style="position: absolute; width: 40%; right: 0; box-shadow: 0 1px 4px rgba(0,0,0,0.5), 0 5px 25px rgba(0,0,0,0.2); background-color: rgba(0, 0, 0, 0.9); color: #fff; padding: 20px; font-size: 20px; text-align: left;">
    <span style="font-size:32px">Ambassadors Meetup</span><br/><br/>
    <a href="https://aws.amazon.com/jp/partners/ambassadors/?cards-body.sort-by=item.additionalFields.ambassadorName&cards-body.sort-order=asc&awsm.page-cards-body=3&awsf.apn-ambassadors-location=*all" target="_blank">What is Ambassador?</a>
  </div>
</section>

***

<span style="font-size:48px">Impressive New Service</span>

<p><a href="https://youtu.be/7-31KgImGgU?t=7066" target="_blank"><img src="images/codeguru.png" width="100%"></a></p>

---

<span style="font-size:48px">Amazon CodeGuru Reviewer</span>

<p><img src="images/codeguru-reviewer.png" width="100%"></p>

---

<span style="font-size:48px">Amazon CodeGuru Profiler</span>

<a href="https://www.youtube.com/watch?v=WYuo0bIZre0" target="_blank"><img src="images/codeguru-profiler.png" width="80%"></a>

---

Conclusion

当社が好きそう

***
***

<span style="font-size:48px">Next Action : 塾開設</span>
<span style="font-size:20px">CloudNative/MicroService On AWSを中心としたテーマで検証・知見/ノウハウを外部公開</span>

<div style="font-size:24px; margin:auto">
  <table>
    <thead>
      <tr>
        <th>Category</th>
        <th>テーマ</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td rowspan="5">マイクロサービスアーキテクチャ</td>
        <td>Cell-Based Architecture on AWS の検証</td>
      </tr>
      <tr>
        <td>サービス連携処理パターンの検証(オーケストレーション/コレオグラフィ/SAGAパターン等)</td>
      </tr>
      <tr>
        <td>ドメイン駆動設計におけるマイクロサービスモデリング手法の検証</td>
      </tr>
      <tr>
        <td>ログ出力方式ベストプラクティス(CloudWatchLogs/Fluentd/ElasticSearch/Kibana/<br/>AWSGlue/Athena/Prometeus)</td>
      </tr>
      <tr>
        <td style="border-bottom:1px solid;">JakartaEE-MicroProfile検証</td>
      </tr>
    </tbody>
  </table>
</div>

---

<div style="font-size:24px; margin:auto">
  <table>
    <thead>
      <tr>
        <th>Category</th>
        <th>テーマ</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td rowspan="7">クラウドネイティブアプリケーションデザインパターン</td>
        <td>オンライン非同期処理パターン(Spring Cloud Stream/<br/>Amazon Managed Streaming for Kafka)</td>
      </tr>
      <tr>
        <td>クラウドバッチ処理パターン(SpringCloudAWS/AmazonSQS/AWSBatch/SpringBatch/<br/>AWSStepFuntions)</td>
      </tr>
      <tr>
        <td>コンテナ&サーバレス連動処理パターン<br>(AWS Lambda/AmazonElastiCache/WebSockets)</td>
      </tr>
      <tr>
        <td>マネージドサービス連携ベストプラクティス(AmazonS3/AmazonSQS/AmazonMQ/AmazonSNS)</td>
      </tr>
      <tr>
        <td>EKS/AppMesh/SpringCloudKubernetes/サービスメッシュ検証</td>
      </tr>
      <tr>
        <td style="border-bottom:1px solid;">OpenIDConnect/OAuth2/Cognito認証・認可処理パターン検証</td>
      </tr>
      <tr>
        <td style="border-bottom:1px solid;">CloudFormationを用いたアプリケーションDevOps基盤自動化資材の開発</td>
      </tr>
    </tbody>
  </table>
</div>

---

<div style="font-size:24px; margin:auto">
  <table>
    <thead>
      <tr>
        <th>Category</th>
        <th>テーマ</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td rowspan="3">リアクティブプログラミング/サーバレス</td>
        <td>GraalVM/Quarkus/SpringCloudFuntion on AWS Lambda検証</td>
      </tr>
      <tr>
        <td>SpringWebFluxの特徴・実装ノウハウの整理</td>
      </tr>
      <tr>
        <td>サーバレスアーキテクチャパターンonAWSの整理</td>
      </tr>
      <tr>
        <td rowspan="4">NoSQLデータモデリング</td>
        <td>AmazonDynanoDB/ApacheCassandraService等<br/>AP型NoSQLの特徴/運用ノウハウ/データモデリング手法確立</td>
      </tr>
      <tr>
        <td>AmazonElastiCache/SpringSession/SpringDataRedis<br/>を使ったスケラーブルアプリケーションノウハウ整理</td>
      </tr>
      <tr>
        <td>ApacheCassandraService/BigDataOnAWS(ApacheSpark/Hadoop/<br/>ElasticMapReduce)連携検証・ノウハウ整理</td>
      </tr>
      <tr>
        <td style="border-bottom:1px solid;">教育コンテンツ整備(ChatMessageアプリケーション)</td>
      </tr>
    </tbody>
  </table>
</div>

---

<div style="font-size:24px; margin:auto">
  <table>
    <thead>
      <tr>
        <th>Category</th>
        <th>テーマ</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td rowspan="8">ニュージャンル</td>
        <td>AWS IoT検証(AWS IoT Core/Device Management/<br/>Greengrass/Analytics/FreeRTOS/SiteWise等)</td>
      </tr>
      <tr>
        <td>エッジコンピューティングアーキテクチャ on AWS検証</td>
      </tr>
      <tr>
        <td>AWS SystemsManagerエンタープライズ運用<br/>ベストプラクティスの整理</td>
      </tr>
      <tr>
        <td>AmazonCodeGuru(コードレビュー自動化)検証</td>
      </tr>
      <tr>
        <td>AmazonSumerian(VR/AR)検証</td>
      </tr>
      <tr>
        <td>ML/AIサービス検証(Amazon SageMaker等)</td>
      </tr>
      <tr>
        <td>モバイルアプリケーション(AWS MobileHub/<br/>Amplify/iOS/Android)教育コンテンツ整備/<br/>アーキテクチャパターン検証・実装ノウハウの整理</td>
      </tr>
      <tr>
        <td style="border-bottom:1px solid;">Kotlin/Go/Angular/React/Python検証・実装ノウハウの整理</td>
      </tr>
    </tbody>
  </table>
</div>

---

## 塾生募集します！

***

#### ご静聴ありがとうございました :bow:

---
