---
title: インセンティブ支払い情報を表示する |パートナーセンター
ms.topic: article
ms.date: 06/03/2019
description: インセンティブ プログラムの収益と支払いを表示することができます。
author: LauraBrenner
ms.author: labrenne
ms.localizationpriority: medium
ms.openlocfilehash: 2a4d69fbe4f4618ebad1f8641f8d07e6563f28fd
ms.sourcegitcommit: e73d8a1d74ed4ea87a5330b00fe119222bc2c3da
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/18/2019
ms.locfileid: "71093062"
---
# <a name="view-your-incentives-payments-information"></a>インセンティブの支払い情報を表示する

**適用対象**

-  パートナー センター

これらのページを使用して、過去、保留中、および今後の支払いの詳細と、トランザクションの完全な履歴を表示します。 また、すべてのトランザクションの詳細情報をダウンロードまたはエクスポートすることもできます。 すべてのインセンティブページには、米ドルの金額が表示されます。 

>[!Note]
>MPN Id と関連付けられているプログラムのデータのみが表示されます。 追加のデータにアクセスする場合は、インセンティブ管理者にお問い合わせください。 


## <a name="access-the-incentives-pages"></a>インセンティブページにアクセスする
いずれかのインセンティブページを開くには、次のようにします。
1. 右上隅にある**Money**アイコンを選択します。
2. **支払い**、**トランザクション履歴**、または**データのエクスポート**を選択します。

## <a name="payments-page"></a>支払いページ
このページの合計は、使用するすべての MPN Id を表します。 参加者 ID、プログラム、支払い ID、および製品の種類でフィルター処理できます。 金額は米ドルで示されます。 有料の値は、支払先通貨にも表示されます。 

|**領域**   |**説明**    |
|------------------|:-------------------------------------|
|今年の支払い合計        |すべての MPN Id について、この年の合計が米国ドルで合計されています。                                      |
|次の推定支払い      |1回の次回の支払い (他のユーザーが近日公開されている場合でも) は、米ドルです。                                     |
|前回の支払い           |最新の支払いの金額 (米ドル単位)、プログラム名、および MPN ID。                                      |
|ソース別の支払い       |過去12か月間のプログラムによって表される支払いの量 (米ドル単位)。                                      |
|支払い                       |**[有料]** または **[保留中]** を選択し、必要に応じて並べ替えます。 特定の支払いの詳細については、「ビュー」を**参照**してください。 支払い送金明細書のコピーをダウンロードするには、 **[ダウンロード]** を選択します。 トランザクション履歴データが表示されるまでに最大24時間かかる場合があるため、関連する収益がすぐに表示されない場合があります。  |

このページのデータをエクスポートするには、**エクスポート** を選択し、データのエクスポート ページの指示に従います。 

## <a name="transaction-history-page"></a>[トランザクション履歴] ページ
このページには、それぞれの日付、種類、および収入を含む、個々の利益がすべて表示されます。 表示する期間を選択できます。また、登録 ID、プログラム、支払い ID、製品の種類、レバー、状態でフィルター処理することもできます。 データは、現在の会計年度 (7 月1日から6月30日) と前の2つの会計年度で利用できます。 

詳細を表示するには、ページの右側にある下矢印を選択します。 これにより、レバー、収益量、製品、顧客が表示されます。 何らかの理由で、このデータのいずれかが使用できないが、アクセスする必要がある場合は、サポートにお問い合わせください。 収益がトランザクションではなく調整の結果である場合、Product フィールドと Customer フィールドは表示されません。 

このページのトランザクションデータをエクスポートするには、**エクスポート** を選択し、データのエクスポート ページの指示に従います。 [トランザクション履歴] ページからエクスポートされたファイルには、トランザクション通貨でのデータ、トランザクション通貨と米ドルの収益、および支払額の支払い額が表示されます。 

## <a name="payment-status"></a>入金状況

|**獲得ステータス** |**理由** |**パートナーのアクションが必要ですか?**       |
|------------------|:-------------------------------------|:-------------------------------------|
|未処理        | 前払いは支払いの対象となります。 インセンティブプログラムの番組ガイドで定義されているように、冷却期間中はこの状態のままになります。       |必須ではない        |
|将来      |支払いが処理される前に、保留中の内部レビューが生成されました。       |必須ではない       |
|保留中の税金請求書      |税金請求書が不完全または無効です。          |支払いを行うには、税金請求書を更新する必要があります         |
|レビュー中に拒否        |確認中に支払いが拒否されました。          |詳細については、Microsoft サポートにお問い合わせください         |
|Failed        |Microsoft システムエラーが発生したため、支払いに失敗しました。         |詳細については、Microsoft サポートにお問い合わせください         |
|進行中     |支払いが進行中です。         |必須ではない         |
|支払いが間違っています        |支払い recouping が進行中です。          |必須ではない        |
|送信        |お支払いが銀行に送信されました。          |必須ではない       |
|再       |Microsoft システムエラーが発生したため、支払いを再処理しています。           |必須ではない         |
|反転        |お支払いは銀行によって取り消され、次回の支払いサイクルで再度送信されます。          |必須ではない        |
|税金請求書が拒否されました       |税金請求書は、レビュー中に拒否されました。 すべての保留中の支払いは、税金請求書のレビューが完了するまで保留されます。          |詳細については、Microsoft サポートにお問い合わせください         |
|レビュー中の税金請求書        |税金請求書を確認しています。 税金請求書が承認されると、支払いがリリースされます。           |必須ではない        |
|元        |お支払いは銀行によって拒否されました。           |詳細については、銀行にお問い合わせください。  |

## <a name="export-data-page"></a>[データのエクスポート] ページ
このページの指示に従って、必要なデータをエクスポートします。 

**注:**
-   MPN Id と関連付けられているプログラムのデータのみが表示されます。 追加のデータにアクセスする場合は、インセンティブ管理者にお問い合わせください。 
-   [データのエクスポート] ページは、それ自体では更新されません。 最新のデータを表示するには、手動でページを更新することが必要になる場合があります。 
-   フィルターを使用すると、**データを使用できない**というエラーが発生する可能性があります。 これは、既定の期間を3か月で選択したままにしてから、その期間外の前払いの支払い ID を選択したことを意味します。 期間を拡大して、もう一度やり直してください。 

## <a name="payment-download-export"></a>支払いダウンロードのエクスポート
このオプションを使用すると、特定のプログラム、関連付けられた税金、および集計された使用量について、銀行で受け取った支払いをダウンロードできます。

|**列の名前**   |**説明**   |
|------------------|:-------------------------------------|
|participantID   |プログラムの下でパートナーが獲得するプライマリ id      |
|participantIDType   |一般に、ストアプログラムのインセンティブプログラムと販売者 ID の MPN      |
|participantName   |取引先の名前      |
|programName   |インセンティブ/店舗プログラム名      |
|獲得   |そのプログラム/participantID の支払先通貨で獲得された金額      |
|earnedUSD   |プログラム/参加者 ID の獲得金額 (USD)      |
|Withtax   |プログラム/participantID の支払先通貨で源泉徴収される税額      |
|salesTax   |プログラム/participantID の支払先通貨における売上税の合計金額      |
|totalPayment   |源泉徴収税を除く現地通貨での支払い額と、プログラム/participantID の売上税 (該当する場合) を含む合計支払額      |
|currencyCode   |通貨コードに支払う      |
|paymentMethod   |パートナーの支払いに使用する方法 (電子銀行の譲渡、クレジットメモ)      |
|paymentID   |支払いの一意の識別子。 通常、この数値は銀行の明細書に表示されます。      |
|paymentStatus   |入金状況      |
|paymentStatusDescription   |支払い状態のわかりやすい説明      |
|paymentDate   |Microsoft から支払いが送信された日付      |

## <a name="transaction-history-download-export"></a>トランザクション履歴のダウンロードエクスポート
このオプションを選択すると、[トランザクションの履歴] ページに表示される各明細項目、[処理の種類]、[日付]、[関連付けられたトランザクションの金額]、[顧客]、[製品]、および [インセンティブプログラムに適用されるその他のトランザクションの詳細] がダウンロードされます。

|**列の名前**   |**説明**   |
|------------------|:-------------------------------------|
|earningId   |各収益の一意識別子   |
|participantID   |プログラムの下でパートナーが獲得するプライマリ id   |
|participantIDType   |一般に、ストアプログラムのインセンティブプログラムと販売者 ID の MPN   |
|participantName   |取引先の名前   |
|partnerCountryCode   |取引先の国/地域   |
|programName   |インセンティブ/店舗プログラム名   |
|transactionCurrency   |元の顧客トランザクションが発生した通貨   |
|transactionDate   |トランザクションの日付。 多くのトランザクションが1つの収益に寄与するプログラムに役立ちます。   |
|transactionExchangeRate  |対応する USD の金額を表示するために使用する換算レートの日付 |
|transactionAmount   |収益が生成された元のトランザクション通貨のトランザクション金額   |
|transactionAmountUSD   |トランザクションの金額 (米国ドル)   |
|transactionCountryCode   |トランザクションの購入/国コードへの販売   |
|レバー   |収益のビジネスルールを示します。   |
|earningRate   |獲得を生成するためにトランザクション量に適用されたインセンティブ率   |
|quantity |このフィールドはプログラムによって異なります。 トランザクションプログラムの場合は、請求数量が示されます。 |
|earningType   |手数料、リベート、co-op、販売などであるかどうかを示します。   |
|earningAmount   |元のトランザクション通貨での金額   |
|earningAmountUSD   |USD の数量   |
|earningDate   |収益の日付   |
|earningExchangeRate   |対応する USD の金額を示すために使用される換算レート   |
|exchangeRateDate   |EarningAmount USD の計算に使用される為替レートの日付   |
|paymentId   |支払いの一意の識別子。 通常、この数値は銀行の明細書に表示されます。   |
|paymentStatus   |入金状況   |
|paymentStatusDescription   |支払い状態のわかりやすい説明   |
|顧客   |顧客識別子   |
|おける   |トランザクションの顧客名   |


上記の表に加えて、これらのトランザクション履歴フィールドは、プログラムに適用できるようになります。

|**列の名前**   |**説明**   |
|------------------|:-------------------------------------|
|partNumber   |トランザクションにリンクされたパーツ番号。 Microsoft の用語。   |
|productName   |トランザクションに罫線を持つ製品ファミリ名   |
|invoiceNumber   |請求書番号   |
|サブスクリプション   |顧客に関連付けられているサブスクリプション識別子   |
|And subscription.subscriptionstartdate   |サブスクリプション開始日   |
|Subscription.subscriptionenddate   |サブスクリプション終了日   |
|offerId   |TBD   |
|resellerId   |再販業者識別子   |
|resellerName   |販売店名   |
|distributorId   |ディストリビューター識別子   |
|distributorName   |ディストリビューター名   |
|agreementNumber   |契約番号   |
|agreementStartDate   |契約開始日   |
|agreementEndDate   |契約終了日   |
|ワークロード   |ワークロード   |
  

