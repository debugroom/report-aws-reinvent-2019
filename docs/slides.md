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
  <div style="font-size:18px; margin:auto">
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
      <li>AWS Solution Architect Processional</li>
    </ul>
  </li>
  <li style="margin: 10px 0px 10px"><a href="https://aws.amazon.com/jp/partners/ambassadors/?cards-body.sort-by=item.additionalFields.ambassadorName&cards-body.sort-order=asc&awsm.page-cards-body=1&cards-body.q=Kawabata&cards-body.q_operator=AND" target="_blank">2019 APN AWS Top Engineers &amp; Ambassadors</a></li>
  <li style="margin: 10px 0px 10px">マイナビ「ITSearch+」で記事連載中</li>
  </div>
</ul>
</div>

***

### re:Invent My Schedule

![image](images/schedule.png)

---

### Today's Topic

![image](images/schedule-scope.png)

***
***

### Cell-based Architecture

![image](images/keynote.png)

---

<span style="font-size:24px">Cell-based Architecture - Reducing blast radius(爆発半径：障害影響の範囲) -</span>

![image](images/cell-based-architecture.png)

<span style="text-align:right;font-size:10px">
出典：「Cell-Based Architecture」（Asanka Abeysinghe | Deputy CTO & VP of Architecture | Paul Fremantle | CTO and Co-Founder - CTO Office | WSO2, Inc）： <a href="https://github.com/wso2/reference-architecture/blob/master/reference-architecture-cell-based.md" target="_blank">wso2/reference-architecture</a>
</span>

---

<span style="font-size:24px">Cell-based Architecture - Beyond MicroService -</span>

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

<span style="font-size:24px">Cell-based Architecture をインターネットバンキングの例で考えてみよう</span>

<p><img src="images/cell-based-architecture-for-ib.png" width="60%"></p>

---

<span style="font-size:24px">Cell-based Architectureをインターネットバンキングの例で考えてみよう </span>

<p><img src="images/cell-based-architecture-error-for-ib.png" width="60%"></p>

---

<section data-background="images/cell-based-architecture-session-1.jpg">
<span style="font-size:24px">Cell-based Architecture(MicroService)がもたらすもの</span>

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

<span style="font-size:24px">Cell-based Architecture Session</span>

<div style="position: absolute; width: 40%; right: 50px; top: 300px; box-shadow: 0 1px 4px rgba(0,0,0,0.5), 0 5px 25px rgba(0,0,0,0.2); background-color: rgba(0, 0, 0, 0.9); color: #fff; padding: 20px; font-size: 24px; text-align: left;">
  <p>障害の影響範囲の極小化に向け、AWSでCell-based Architectureを如何に実現するか</p>
</div>

---

<span style="font-size:24px">Cell-based Architecture Session</span>

<p><img src="images/cell-based-architecture-session-2.jpg" width="100%"></p>

---

Conclusion

Cell-based Architectureは当社の抱える、ラージスケールなアプリケーションアーキテクチャやレガシーデジタルインテグレーションの課題解決に向けた1つの指針となる

***

<section data-background-video="https://debugroom-sample.s3-ap-northeast-1.amazonaws.com/lambda-for-java.mov" data-background-video-loop data-background-video-muted data-background-opacity="1">
  <div style="position: absolute; width: 40%; right: 0; box-shadow: 0 1px 4px rgba(0,0,0,0.5), 0 5px 25px rgba(0,0,0,0.2); background-color: rgba(0, 0, 0, 0.9); color: #fff; padding: 20px; font-size: 20px; text-align: left;">
    <h2>Session</h2>
    <a href="https://youtu.be/ddg1u5HLwg8?t=0" target="_blank">Best Practice for AWS Lambda and Java</a>
  </div>
</section>

***

#### Session : Best practice Lambda for Java

<p><img src="images/lambda-for-java-session.png" width="100%"></p>

---

#### Conclusion : Best practice Lambda for Java

<p><img src="images/graalvm.png" width="100%"></p>

***

<section data-background-video="https://debugroom-sample.s3-ap-northeast-1.amazonaws.com/ambassadors-meetup.mov" data-background-video-loop data-background-video-muted data-background-opacity="1">
  <div style="position: absolute; width: 40%; right: 0; box-shadow: 0 1px 4px rgba(0,0,0,0.5), 0 5px 25px rgba(0,0,0,0.2); background-color: rgba(0, 0, 0, 0.9); color: #fff; padding: 20px; font-size: 20px; text-align: left;">
    <h2>Ambassadors Meetup</h2>
    <a href="https://aws.amazon.com/jp/partners/ambassadors/?cards-body.sort-by=item.additionalFields.ambassadorName&cards-body.sort-order=asc&awsm.page-cards-body=3&awsf.apn-ambassadors-location=*all" target="_blank">What is Ambassador?</a>
  </div>
</section>

***

### Impressive New Service

<p><img src="images/codeguru.png" width="100%"></p>

---

<span style="font-size:24px">Amazon CodeGuru Reviewer</span>

<p><img src="images/codeguru-reviewer.png" width="100%"></p>

---

<span style="font-size:24px">Amazon CodeGuru Profiler</span>

<p><img src="images/codeguru-profiler.png" width="80%"></p>

<span style="text-align:right;font-size:16px">
<a href="https://www.youtube.com/watch?v=WYuo0bIZre0" target="_blank">「Session Amazon CodeGuru」</a>
</span>

---

Conclusion

当社が好きそう

***

#### ご静聴ありがとうございました :bow:

---