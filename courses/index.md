# SREの学び舎

<img src="img/sos.png" width=200 >

SRE (Site Reliability Engineers: サイト信頼性エンジニア) は、ソフトウェアエンジニアリングとシステムエンジニアリングの交わる部分に位置しています。インフラストラクチャとソフトウェアコンポーネントを組み合わせて目的を達成する方法には、無限の並び替え方や選び方がある可能性がありますが、基本的なスキルに焦点を当て、理解することで、これらのシステムがプロプライエタリであるか、サードパーティ製であるか、オープンソースであるか、クラウド/オンプレミスのインフラストラクチャで実行されているかなどに関係なく、SRE は複雑なシステムやソフトウェアを操作できるようになります。ここで重要なのは、システムとインフラストラクチャの領域が相互にどのように関連し、相互作用するかを深く理解することです。特定のソフトウェアとシステムエンジニアリングスキルの組み合わせはまれであり、一般に、さまざまなインフラストラクチャ、システム、およびソフトウェアにさらされながら時間をかけて構築されます。



SREは、サイトを稼働させ続けるためのエンジニアリング手法を利用します。それぞれの分散システムは、多くのコンポーネントの集合体です。SRE は、ビジネス上の要件の検証、分散システムを構成する各コンポーネントの SLA (Service Level Agreement: サービス品質保証) 設定、SLA の準拠の監視と測定、SLA 違反を軽減または回避するための再設計またはスケールアウト、これらの学びを新しいシステムまたはプロジェクトへフィードバック、それによる運用作業の軽減を行います。したがって、SRE はシステムの設計初期から重要な役割を果たします。

2019年の初め、私たちは最も優秀な人材を採用するため、また、LinkedIn とその複雑なテクノロジースタックを構成するすべてのサービスを誰もがいつでも利用できるようにするため、インド各地のキャンパスを訪問し始めました。LinkedIn の維持するこの重要な機能・サービスは、サイトエンジニアリングチームと、信頼性を専門とするソフトウェアエンジニアであるサイト信頼性エンジニア (SRE) の管轄下にあります。

この旅を続けるうちに、サイト信頼性エンジニアリングの役割には具体的に何が必要なのか? サイト信頼性エンジニアとして成功するために必要なスキルと分野・ルールを学ぶにはどうすればよいか? といった質問が、これらのキャンパスから多く寄せられるようになりました。数ヶ月後、これらのキャンパスの学生の何人かは、インターンとして、またはサイトエンジニアリングチームの一員になるためフルタイムのエンジニアとして LinkedIn に参加していました。また、従来の SRE 出身ではない、組織に参加したいくつかのラテラル採用 (同業他社からの中途採用) もありました。その時、私たちの何人かが集まって、どうすれば新卒エンジニアをサイトエンジニアリングチームに迎え入れることができるかを考え始めました。

SRE 初心者として習得しなければならない基本的なスキルセットについて、指導するリソースはあまり出回っていません。これらのリソースが不足しているため、個人が業界のスタート地点に入るのは難しいと感じました。私たちは、SRE としてのキャリアを築きたいと思っている人のための出発点として、SRE の学び舎を設立しました。
このコースでは、強力な基礎スキルの構築に重点を置いています。このコースは、より多くの実例を提供するよう作られており、これらの各トピックを学習することが、SRE の日常の職責においてどのように重要な役割を果たすことができるかを示しています。現在、私たちは SRE の学び舎の下で以下のトピックをカバーしています。(訳注: タイトルが日本語になっている箇所についてのみ翻訳済)

-   Level 101
    -   基礎シリーズ
        -   [Linux の基礎](https://kstm.shinshu-u.ac.jp/school-of-sre/level101/linux_basics/intro/)
        -   [Git](https://linkedin.github.io/school-of-sre/level101/git/git-basics/)
        -   [Linux Networking](https://linkedin.github.io/school-of-sre/level101/linux_networking/intro/)
    -   [Python and Web](https://linkedin.github.io/school-of-sre/level101/python_web/intro/)
    -   Data
        - [Relational databases(MySQL)](https://linkedin.github.io/school-of-sre/level101/databases_sql/intro/)
        -   [NoSQL concepts](https://linkedin.github.io/school-of-sre/level101/databases_nosql/intro/)
        -   [Big Data](https://linkedin.github.io/school-of-sre/level101/big_data/intro/)
    -   [Systems Design](https://linkedin.github.io/school-of-sre/level101/systems_design/intro/)
    -   [Metrics and Monitoring](https://linkedin.github.io/school-of-sre/level101/metrics_and_monitoring/introduction/)
    -   [Security](https://linkedin.github.io/school-of-sre/level101/security/intro/)

-   Level 102
    -   [Linux Intermediate](https://linkedin.github.io/school-of-sre/level102/linux_intermediate/introduction/)
    -   Linux Advanced
        -   [Containers and orchestration](https://linkedin.github.io/school-of-sre/level102/containerization_and_orchestration/intro/)
        -   [System Calls and Signals](https://linkedin.github.io/school-of-sre/level102/system_calls_and_signals/intro/)
    -   [Networking](https://linkedin.github.io/school-of-sre/level102/networking/introduction/)
    -   [System Design](https://linkedin.github.io/school-of-sre/level102/system_design/intro/)
    -   [System troubleshooting and performance improvements](https://linkedin.github.io/school-of-sre/level102/system_troubleshooting_and_performance/introduction/) 
    -   [Continuous Integration and Continuous Delivery](https://linkedin.github.io/school-of-sre/level102/continuous_integration_and_continuous_delivery/introduction/)

継続的な学習は、スキルセットを拡大するため、より深い知識とスキル・能力を獲得するのに役立つと考えています。すべてのモジュールには、さらに学習するためのガイドとなるリファレンスが追加されています。これらのモジュールを使用することで、Site Reliability Engineer に必要な基本的なスキルを構築できることを望んでいます。

LinkedInではこのカリキュラムを使用し、従来とは異なる採用者や新卒者を SRE として迎え入れています。私たちは、新しい従業員との成功したオンボーディング経験 (新人研修) を何度も経験し、このコースは彼らが非常に短期間で生産的になるのに役立ちました。そこで、他の組織が新しいエンジニアを SRE の役職に追加するのを支援するためのコンテンツをオープンソース化し、これに参加する意欲のある個人へのガイダンスを提供することにしました。私達が作成した最初のコンテンツは出発点に過ぎず、コミュニティがコンテンツの洗練と発展に協力できることを願っています。詳しくは本リポジトリの [コントリビュートに関するガイド](./CONTRIBUTING.md) を参照してください。



### 日本語翻訳について

本リポジトリ([kstm-su/school-of-sre](https://github.com/kstm-su/school-of-sre))  は、オリジナルの School of SRE リポジトリのフォークであり、信州大学の情報系サークルである kstm 所属の学生により翻訳がされています。kstm は信州大学の公認サークルではありますが、本リポジトリの内容については大学とは関係ありませんので、大学へのお問い合わせ等はお控えいただけますよう、お願いいたします。

kstm 所属学生以外からの issue/PR も受け付けています。それ以外の問い合わせについては、twitter@kstm_ までお願いいたします。

日本語翻訳については、原文の内容を損なわない程度に、日本語における意味・技術的内容が伝わりやすくなるような改変を一部行っている箇所があります。

本リポジトリの内容は、オリジナルと同様 Creative Commons「表示」4.0 国際ライセンス下で提供されています。

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.
