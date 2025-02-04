---
title: Power BI 用パートナー センター分析アプリ | パートナー センター
ms.topic: article
ms.date: 03/15/2019
description: Power BI 用パートナー センター分析アプリ (CSP の直接パートナー向け) の使用方法を説明します。
fwlink: https://go.microsoft.com/fwlink/?linkid=852581
author: LauraBrenner
ms.author: labrenne
ms.localizationpriority: medium
ms.openlocfilehash: 085fcb059a11b487c69ba64d9c411b173ed48c6b
ms.sourcegitcommit: f916aa2884239b205398c24d04d1f1dc41b63c2b
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/28/2019
ms.locfileid: "64668746"
---
# <a name="view-your-business-data-with-the-partner-center-analytics-app-for-microsoft-power-bi"></a>Microsoft Power BI 用パートナー センター分析アプリでビジネス データを表示する

**適用対象**

-   パートナー センター

## <a name="view-your-business-data"></a>ビジネス データを表示する

Power BI 用パートナー センター分析アプリでは、ビジネス データの視覚表現を利用できます。以下に例を示します。

- 顧客数、サブスクリプション数、ライセンス数の増加

- Office 365、Microsoft Dynamics、Microsoft Azure の製品の使用量

- 過去 60 日間の各 Azure サブスクリプションにおける従量制課金リソースごとの 1 日当たりの消費単位

- (最新の価格カードに基づく) 推定コスト

- データセットのエクスポートおよびカスタム レポート作成 (顧客別など) の機能 

### <a name="about-the-partner-center-analytics-app-preview-release"></a>パートナー センターの分析のアプリのプレビュー リリースについて

 - このアプリは、クラウド ソリューション プロバイダー プログラムの直接パートナーのみを対象としています。 CSP の他のパートナー (間接リセラーなど) はログインできません。

- 見積もりコストはすべて税抜きの請求データであり、法的拘束力を持ちません。 推定コストは、データ インサイトの目的のみで使用することを想定しています。

- 顧客情報は、サブスクリプションに基づきます。 最近、アカウントを作成し、まだサブスクリプションがない顧客はカウントされません。 

- 推定コストは、最新の価格カード (CSP 価格に基づく) を使って算出されます。 

- 日数は暦日です。 


### <a name="business-insights-report"></a>ビジネス インサイト レポート

-  **Customer tenants** (顧客テナント数): サブスクリプションを購入した顧客の個別の Azure AD テナント数

-  **New (last 30 days)** (新規 (過去 30 日)): 過去 30 日以内に 1 つ以上のサブスクリプションを購入した新規顧客数

-  **Churn (last 30 days)** (チャーン (過去 30 日)): "アクティブ"、"猶予期間中"、"無効" のいずれのサブスクリプションも持たない顧客数

- **New (last 24 hours)** (新規 (過去 24 時間)): 過去 24 時間以内に 1 つ以上のサブスクリプションを購入した新規顧客数

- **Estimated monthly cost over last 12 months** (過去 12 か月間の月間推定コスト): 過去 12 か月間にわたって月単位で集計された税抜き推定請求金額 (単位: ドル) の月別推移

- **Estimated cost by product over last 12 months** (過去 12 か月間の製品別推定コスト): 過去 12 か月間にわたって集計された税抜き推定請求金額 (単位: ドル) の順に示された販売済み製品。 これにより、収益性の高い主力製品が明確になります。

- **Customers over last 12 months** (過去 12 か月間の顧客数): 過去 12 か月間にわたって月単位で集計された新規顧客数とチャーン顧客数の月別推移

- **Estimated cost by customer over last 12 months** (過去 12 か月間の顧客別推定コスト): 過去 12 か月間にわたって集計された税抜き推定請求金額 (単位: ドル) の順に示された顧客数。 これにより、収益性の高い主要顧客が明確になります。

- **Customer count by product** (製品別顧客数): 関連付けられている顧客数の順に示された販売済み製品。 これにより、多くの顧客が購入した主力製品が明らかになります。 


### <a name="subscription-insights-report"></a>サブスクリプション インサイト レポート 

- **Subscription status** (サブスクリプションの状態): 

    - [アクティブ]:"アクティブ" 状態または "猶予期間中" 状態のサブスクリプション数

    - Suspended (中断): "無効" 状態のサブスクリプション数

    - De-provisioned (プロビジョニング解除): "プロビジョニング解除" 状態または "期限切れ" 状態のサブスクリプション数

- **Expiry status** (有効期限の状態): 

    - ［有効期限切れ］:既に有効期限切れのサブスクリプション数 (サブスクリプションの終了日が過去の日付)

    - Expiring after 30 days (30 日後に期限切れ): 30 日後に期限切れとなるサブスクリプション数 (サブスクリプションの終了日が 30 日後)

    - Expiring in 30 days (30 日以内に期限切れ): 今後 30 日以内に期限切れとなるサブスクリプション数 (サブスクリプションの終了日が今日から 30 日後までの間)

-  **Total subscriptions** (サブスクリプション合計): "アクティブ"、"猶予期間中"、"無効" のいずれかの状態のサブスクリプション数

- **New (last 30 days)** (新規 (過去 30 日)): 過去 30 日以内に顧客によって購入された新しいサブスクリプション数

- **New (last 24 hours)** (新規 (過去 24 時間)): 過去 24 時間以内に顧客によって購入された新しいサブスクリプション数

- **Expiring in 30 days** (30 日以内に期限切れ): 今後 30 日以内に期限切れとなるサブスクリプション数

- **Churn (last 30 days)** (チャーン (過去 30 日)): 過去 30 日以内にプロビジョニング解除または中断 (無効) となったサブスクリプション数

- **Distribution by subscription types** (サブスクリプションの種類別分布率): 全サブスクリプションのライセンス ベースと利用量ベースのサブスクリプションの種類別分布率

- **Active subscription count by product** (製品別アクティブなサブスクリプション数): アクティブなサブスクリプション数の順に示された販売済み製品

- **Subscriptions over last 12 months** (過去 12 か月間のサブスクリプション数): 過去 12 か月間にわたって月単位で集計された新規サブスクリプション数とチャーン サブスクリプション数の月別推移

- **Customer subscription details** (顧客のサブスクリプションの詳細): 顧客、サブスクリプション、オファーの詳細ビュー 


### <a name="license-insights-report"></a>ライセンス インサイト レポート:

- **Total licenses** (総ライセンス数): すべてのライセンス ベースのサブスクリプションを合わせたライセンスの合計数

- **New (last 30 days)** (新規 (過去 30 日)): 過去 30 日以内のライセンス増加数

- **Churn (last 30 days)** (チャーン (過去 30 日)): 過去 30 日以内のライセンス減少数

- **New (last 24 hours)** (新規 (過去 24 時間)): 過去 24 時間以内のライセンス増加数

- **Licenses over last 90 days** (過去 90 日間のライセンス): 過去 90 日間にわたって月単位で集計されたライセンス数増減の月別推移

- **Active license count by product** (製品別アクティブなライセンス数): アクティブなライセンス数の順に示された販売済み製品

- **Active license count by customer** (顧客別アクティブなライセンス数): アクティブなライセンス数の順に示された顧客数

- **Customer license event details over last 90 days** (過去 90 日間の顧客ライセンス イベントの詳細): 顧客、サブスクリプション、サブスクリプション イベント (イベント発生日、イベント名、数量、数量の変化など) の詳細ビュー


### <a name="licenses-usage-report"></a>ライセンス使用状況レポート:

- **Licenses assigned by product** (製品別割り当て済みライセンス数): ライセンス割り当て数の順に示された販売済み製品

- **Licenses in use by product** (製品別使用中ライセンス数): ライセンス使用数の順に示された販売済み製品

- **Customer distribution of licenses assigned** (割り当て済みライセンスの顧客分布): 全顧客を 20% 刻みのライセンス割り当て率の範囲ごとに分割した分布率

- **Customer distribution of licenses in use** (使用中ライセンスの顧客分布): すべての顧客を 20% 刻みの使用中ライセンス率の範囲ごとに分割した分布率

- **Licenses assigned by customer** (顧客別割り当て済みライセンス数): 販売済みライセンスと割り当てられたライセンスを顧客別および製品別に表示した詳細ビュー

- **Licenses in use by customer** (顧客別使用中ライセンス数): 販売済みライセンスと使用中ライセンスを顧客別および製品別に表示した詳細ビュー


### <a name="azure-insights-report"></a>Azure インサイト レポート:

- **Usage based customers over last 12 months** (過去 12 か月間の使用量ベースの顧客数): 過去 12 か月間にわたって月単位で集計された使用量ベースの新規顧客数と使用量ベースのチャーン顧客数の月別推移

- **Usage based subscriptions over last 12 months** (過去 12 か月間の使用量ベースのサブスクリプション数): 過去 12 か月間にわたって月単位で集計された使用量ベースの新規サブスクリプション数と使用量ベースのチャーン サブスクリプション数の月別推移

- **Estimated cost of usage by customer over last 60 days** (過去 60 か日間の顧客別推定使用コスト): 過去 60 日間にわたって集計された税抜き推定請求金額 (単位: ドル) の順に示された使用量ベースの顧客数。 これにより、収益性の高い使用量ベースの主要顧客が明確になります。

- **Estimated cost of usage by category over last 60 days** (過去 60 か日間のカテゴリ別推定使用コスト): 過去 60 日間にわたって集計された税抜き推定請求金額 (単位: ドル) の順に示された使用量ベースのサブスクリプションの従量制課金カテゴリ。

- **Estimated cost of usage by subscription over last 60 days** (過去 60 か日間のサブスクリプション別推定使用コスト): 過去 60 日間にわたって集計された税抜き推定請求金額 (単位: ドル) の順に示された使用量ベースのサブスクリプション数。

- **Customer estimated usage cost by spending budget** (予算支出別顧客推定使用コスト): 現在の使用量予算支出のしきい値 (100%) を超えた部分のパーセント率の順に示された顧客数。


### <a name="azure-resource-usage-report"></a>Azure リソース使用状況レポート:

- **Usage of Azure resources by day for selected period** (選択した期間の 1 日当たりの Azure リソース使用量): 過去 60 日間のうち選択した期間の使用量ベースのサブスクリプション別および従量制課金リソース別の 1 日当たりの消費単位。

- **Estimated usage cost of Azure resources for selected period** (選択した期間の Azure リソース推定使用コスト): 過去 60 日間のうち選択した期間の使用量ベースのサブスクリプション別および従量制課金リソース別の最新の価格カードに基づく推定使用コスト。 

## <a name="see-also"></a>関連項目

[Power BI 用パートナー センター分析アプリの概要](power-bi-app-for-direct-partners.md)


[Power BI 用パートナー センター分析アプリをインストールしてプレビューする](power-bi-app-for-direct-partners-install.md)
