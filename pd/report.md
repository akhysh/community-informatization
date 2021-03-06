---
layout: default
title: パーソナルデータの利活用促進と消費者の信頼性確保の両立に向けて
---

# パーソナルデータ関連

勝手に自治体・地域情報化視点で気になる点をまとめます。
本文章の引用は「[個人情報保護委員会事務局レポート 匿名加工情報 パーソナルデータの利活用促進と消費者の信頼性確保の両立に向けて][8fb1a680]」
  （2017年2月）からのものです。  
引用以外の文章は吉本の個人的見解です。見解の内容について何ら保証するものではありません。


># [パーソナルデータの利活用促進と消費者の信頼性確保の両立に向けて][8fb1a680]
2017年2月

>本レポートは、主に、匿名加工情報を作成するための考え方や手法（法第 36 条第 1 項関連）及び識別行為の禁止（法第 36 条第 5 項及び第 38 条関連）、加工方法等情報や匿名加工情報の安全管理措置（法第 36 条第２項及び第６項並びに第 39 条）に焦点を当てて、認定団体及び事業者団体等が匿名加工情報の作成に関するルールを検討したり、民間事業者が実際に匿名加工情報を作成したりする際に参考となる事項、考え方を示そうとするものである。  

とあるように、個人情報保護法の改正によって導入された「匿名加工情報」の作成を中心に認定個人情報保護団体などが具体的な取り組みを行う際の参考として作られている。  
匿名加工情報については「[個人情報の保護に関する法律についてのガイドライン（匿名加工情報編）][523b2cd4]」（2016年11月 個人情報保護委員会：2017年3月一部改正）(以下、
「ガイドライン」という)に詳しいが、一部さらに突っ込んだ内容が見られる。  
自治体の場合、「][行政機関の保有する個人情報の保護に関する法律についてのガイドライン（行政機関非識別加工情報編)][ce4e9983]」が要参照だが、このあたりについては匿名加工情報変と基本的に変わらない。  


以下内容で特に注目するところ  

>## 2. 個人情報とその取扱いにおける制約
>### 2.1 個人情報の定義
> 「特定の個人を識別することができる」とは、... **一般人の判断力又は理解力をもって** 生存する具体的な人物と情報の間に同一性を認めるに至ることができるかどうかによるものである。
>
>「他の情報と容易に照合することができ」るとは... **通常の業務における一般的な方法で** 、他の情報と容易に照合することができる状態をいうものとされている。

特定個人の識別は「一般人の能力」を基準としている。これはガイドラインと同様の説明である。
全体的に一般人能力基準で判断することになる。  
照合容易性について「通常業務における一般的な方法」基準は匿名加工情報編ガイドラインには述べられていないが、「[個人情報の保護に関する法律についてのガイドライン（通則編）][523b2cd5]」（2016年11月 個人情報保護委員会：2017年3月一部改正）のほうに同様の記述がある。  
  
>同項第 2 号に定める個人識別符号としては、マイナンバー等、公的付番の符号が規定されており、民間付番のサービス ID や携帯電話番号、クレジットカード番号等は規定されていない。しかしながら、これら民間付番の符号は個人識別符号ではなくても、単体あるいはその他の情報と組み合わせられること等により法第２条第１項第１号の個人情報に該当する場合があることに留意する必要がある。  
> 

民間のIDは個人識別符号ではないことを改めて説明しつつ、個人情報に該当する場合はあり得ることを注意している。  

>## 3. 匿名加工情報とは
>### 3.2 匿名加工情報の定義
>匿名加工情報は、... 個人に関する情報である。個人に関する情報であるということは、すなわち情報の単位としては一人ひとりに対応した情報であることが許容されるものである。  
> 

非識別だけでなく、識別非特定も匿名加工情報であることが述べられている。  

>#### 3.2.1 「特定の個人を識別することができない」とは
>... 一般人及び一般的な事業者の能力、手法等を基準として当該情報を個人情報取扱事業者又は匿名加工情報取扱事業者が通常の方法により特定できないような状態にすることを求めるものである。  
>  
>#### 3.2.2 「当該個人情報を復元することができないようにしたもの」とは 
> ... 一般人及び一般的な事業者の能力、手法等を基準として当該情報を個人情報取扱事業者又は匿名加工情報取扱事業者が通常の方法により復元できないような状態にすることを求めるものである。  
> 

ガイドラインにも同様の記述がある。個人情報の定義同様、一般人能力基準である。  

>例えば、スーパーコンピュータのような高度な機能を有する資源を利用したり、高度なハッキング・スキルを利用したりする等のあらゆる手法によって特定や復元を試みたとしてもできないというように、技術的側面から全ての可能性を排除することまでを求めるものではない。  
> 

ガイドラインにはないが、一般人能力基準を超えるものとしてスーパーコンピュータや高度なハッキング・スキルなどが例示されている。


>#### 3.2.3 一部の情報が復元できた場合について
> ... 一部ではあっても元の個人情報の本人を特定し得る情報が復元されることも「復元」に該当する。  
> 一方、特定の個人の識別につながらないような部分の情報の復元については、ここでいう「復元」には当たらない。  
> 

ガイドラインよりも詳細に「一部情報」復元の判断が示されている。  

>#### 3.2.4 「復元することのできる規則性を有しない方法により他の記述等に置き換えること」とは
>... あくまで、置換え後の記述等から元の個人情報の記述等への変換の規則性を有しない方法を意味し、記述等を置き換えるための規則性を有しないことまで求めるものではない。  
> 

ガイドラインより詳しい解説。置き換える規則性まで排除してしまうとハッシュ関数が使えなくなるし。  

>### 3.3 匿名加工情報を取り扱う上での制約
> 匿名加工情報(匿名加工情報データベースを構成するものに限る)を作成し、それを取り扱うときには、個人情報取扱事業者は法第 36 条の規定を順守する必要がある。


「匿名加工情報データベースを構成するものに限る」の説明はガイドラインにも見られる。ただ、「匿名加工情報取扱事業者」の定義から自明なことではある。  
非識別加工情報の場合は、「行政機関非識別加工情報（行政機関非識別加工情報ファイルを構成するものに限る。」になる。  



>### 3.4 匿名加工情報に関する留意点
>#### 3.4.1 統計情報について
>... 適切に加工された統計情報は、個人情報にも匿名加工情報にも該当しないものである。  
>   
>... 個人との対応関係が十分に排斥できるような形で統計化されていることが重要であるといえる。


改めて統計情報は個人情報でも匿名加工情報でもないことを明記している。  
 


>#### 3.4.2 容易照合性との関係
> 匿名加工情報は、... 作成の元となった個人情報を通常の業務における一般的な方法で照合することができる状態にある（すなわち容易照合性がある）とはいえず、個人情報に該当しないとされるものである。  
したがって、匿名加工情報を作成した事業者がこれを当該事業者内部で取り扱うに当たっても、匿名加工情報の取扱いに関する義務（法第 36 条）を守ることにより自由な利活用が認められることとなる。


個人情報取扱事業者内でも匿名加工情報は活用可能であることを明言。  
ただし、非識別加工情報は行政機関内では個人情報。 

>なお、匿名加工情報の作成事業者内部において、匿名加工情報に加工される前の元となる個人情報や加工方法等に関する情報が保存されることは制度的に前提とされており、作成事業者の内部に存在し、かつ識別行為の禁止義務の対象である対応表について、特別に危険視することは適当ではないものの、識別行為の禁止及び加工方法等情報の安全管理措置等の匿名加工情報の取扱いに関する義務を守ることが当然に必要である。

対応表などについてあまりに危険視しすぎないようにとのこと。  

>#### (参考)「容易照合性」
> ... 法第 23 条の第三者提供の制限においても「個人情報」に関する容易照合性の判断は事業者内部における照合性を意味することとなる。  

提供元基準。  

>### 3.5 匿名加工情報の作成とは
> つまり、匿名加工情報を作成する意図がなく、かつ、個人情報として取り扱うことを前提にしたデータの加工については、法律上の「匿名加工情報の作成」に該当するものではないのであり、このようなデータの加工に対して、匿名加工情報に係る義務が発生するものではない。

個人情報として取り扱うつもりならば、たとえ匿名加工のような処理を施したとしても、わざわざ匿名加工情報とする必要はないということ。  

>最終的に匿名加工情報とするための加工作業が完了したことをもって「匿名加工情報を作成」したことになり、匿名加工情報の作成・第三者提供に係る公表義務や安全管理措置等を履行するとともに、匿名加工情報として取り扱うことが可能となる。  

加工途中は個人情報であり、最終的に完了して初めて匿名加工情報になるし、匿名加工情報に関する義務もそこから始まるということ。  


>## 4. 匿名加工情報の作成に当たって求められる加工
>### 4.1 匿名加工情報の加工基準（施行規則第 19 条）について
>#### 4.1.1 第 1 号（特定の個人を識別することができる記述等の削除）
>また、携帯電話番号や電子メールアドレス、SNS 等の ID、クレジットカード番号等は、法人の所有する番号との区別がつかない等の理由により特定の個人を識別し得る符号ではないとして、個人識別符号からは除外されているものではあるが、一般的に本人と密接に関係する情報であり、事業者において単体又は他の情報との組合せによりこれらの情報が特定の個人のものとして認識されている場合については、個人情報として扱われるべきものである。  
> 
>... 基本的には、全部削除することが望ましい.。

前にも述べられているが、民間のIDなどは個人識別符号ではないが、個人情報を構成する可能性が高いので、全部削除を推奨している。  

>**【仮 ID への置き換えについて】**  
>...  1 つは、ハッシュ関数等を用いる際に、その入力情報に提供する事業者ごとに異なる記号列や乱数等を加えることである。  
> ... 、同一事業者への提供であっても、定期的に仮 ID を変更することが望ましい。  
> なお、仮 ID が不要である場合には、再識別リスクを低減する意味からも、仮 ID への置き換えを行わないことが望ましい。


仮IDを使うとき、複数事業者に対して同じIDを使わないようにハッシュ関数を使うならソルトを入れるなりしましょうというのと、同一事業者でも時系列の名寄せを防ぐため仮IDは定期的に変えようという推奨。  

>**【ハッシュ関数による置き換えについて】**  
> ただし、同じデータからは常に同じハッシュ値が得られるということは、名前や電子メールアドレス、携帯電話番号等の多くの事業者が保有するような情報のみでハッシュによる仮 ID を生成すると、提供を受けた事業者において仮 ID の生成に用いられた入力情報を推測することが容易となるおそれがあることを意味する。したがって、ハッシュによる仮 ID 生成に当たっては、（氏名＋秘密の文字列）、（氏名＋電子メールアドレス＋秘密の文字列）といったように、鍵となる秘密の文字列を付加した上でハッシュ化をすること（いわゆる鍵付きハッシュ関数の利用）が望ましい。   

ここでは鍵付きハッシュが推奨されている。ここの説明だけでは鍵付きハッシュでなくてもソルト入れれば十分にも見えるが。  


>#### 4.1.4 第 4 号（特異な記述等の削除）
> なお、同条第 4 号は一般的に特異な記述等が対象となるため、加工対象となる個人情報からなるデータベース内において顕著な値である場合でも、それだけでは本号の「特異」には該当しない。加工対象のデータベース内において顕著な値については、同条第 5 号による措置の対象となり得るものである。  
> 

その個人情報の集合内で珍しい値であっても、一般的に珍しいものでなければ「特異」とは言わないとのこと。  


>#### 4.1.5 第 5 号（個人情報データベース等の性質を踏まえたその他の措置）
> なお、ここで対象となる個人情報データベース等については、... 事業者内にある個人情報データベース全部を対象とするものではなく、匿名加工情報データベース等を構成する匿名加工情報の作成の元となる個人情報で構成される個人情報データベース等の単位で検討することを求めるものである。  
> 

データベースの性質を考えろといっても保有するデータベース全てを勘案する必要はないということ。  


>##### 4.1.5.2 「その他の～適切な措置」が求められる場合
>**【不変性の高い ID、多数の事業者で取得されるサービス ID 等】**  
>スマートフォンのように個人がある程度の期間使用しかつ日常的に携行する機器の ID 等 
>  
>**【時刻に関する情報について】**   
>詳細な時刻情報は、位置や場所を表す情報とセットになることで、異なるデータセット間における共通の識別子として機能し得る。   
>  
>**【位置情報（移動履歴）について】**  
> 移動履歴は長くなるほど他人と重複する可能性が低く一意な情報となる  
> 

具体的な説明がなされている。  


>### 4.2 匿名加工情報を作成する際に検討することが望ましい事項
>#### 4.2.2 他の情報を参照することによる識別の可能性について
>匿名加工情報は「特定の個人を識別することができないように」加工することが求められるが、匿名加工情報の制度は、その流通過程における安全性を確保しつつパーソナルデータの利活用を図る制度であるため、一般的に入手し得る他の様々な情報と参照することによる識別の可能性を検討することが望ましい。  
> 

再識別は禁止なのだが、可能性については検討すべきということ。  
後章に意図せず識別してしまった場合の記述があることに対応している。  


>### 4.3 匿名加工情報の作成のための参考情報
>#### 4.3.1 匿名加工に用いられる代表的な加工手法
>##### 4.3.1.1 ｋ－匿名性について
>匿名加工情報は、上記ケースのように必ずしも一般公開されるものではないから、上記で準識別子とされている情報の項目について、匿名加工情報データベース等との関係でｋ≧２となるように加工することは必ずしも求められない。ただし、匿名加工情報が第三者に提供される態様や利用形態を考慮した上で、必要に応じてこのような考え方を取り入れることが望ましい。  

K-匿名性の対応は必須ではないが、状況に応じて配慮しましょうということ。  
意図しない再識別などもあるので。  


>## 6. 匿名加工情報の利用に当たっての留意点
>### 6.1 識別目的の照合とは
>... 識別を目的とした照合行為自体がこれらの義務違反となる。  
>...例えば、ある集団の傾向やマーケットの動向を分析するために他の情報と照合することについては、識別目的の照合には該当せず、義務違反とはならない。  

意図的に再識別を行うことが違反。照合（ほかの情報とのJOINなど）自体が禁止されているわけではない。  

>### 6.3 匿名加工情報を加工したものの扱い
>元の匿名加工情報から情報を削除する場合については、削除される情報の程度によって変わり得るが、元の匿名加工情報との対応関係が明らかである限りは、同一の匿名加工情報として扱うものと考えることが妥当である。  

多少削っても匿名加工情報であることは変わらない。  


>### 6.4 意図せず特定個人を識別してしまった場合の扱い
>... 偶発的に特定の個人を識別してしまった場合は、これらの義務違反として直ちに罰せられることにはならないが、再度同じような形で個人を識別することがないようにする必要がある。さらに、識別してしまった情報については、個人情報として適切な取扱いを行う必要がある。
> 

わざとじゃなければ再識別しても違反ではない。ただし、再識別してしまった情報は個人情報になる。（本人同意をとるなどの対応が必要。いやなら捨てる）  



  [ce4e9983]: https://www.ppc.go.jp/files/pdf/guidelines05.pdf "行政機関の保有する個人情報の保護に関する法律についてのガイドライン（行政機関非識別加工情報編"
  [4d313918]: http://www.soumu.go.jp/main_content/000539253.pdf "地方公共団体の保有する個人情報の特性に応じた加工について"

  [8fb1a680]: https://www.ppc.go.jp/files/pdf/report_office.pdf "パーソナルデータの利活用促進と消費者の信頼性確保の両立に向けて"
  
  [523b2cd4]: https://www.ppc.go.jp/files/pdf/guidelines04.pdf "個人情報の保護に関する法律についてのガイドライン（匿名加工情報編）"
  [523b2cd5]: https://www.ppc.go.jp/files/pdf/guidelines04.pdf "個人情報の保護に関する法律についてのガイドライン（通則編）"
