---
title: 紹介の分析情報を取得する | パートナー センター
ms.topic: article
ms.date: 07/12/2019
description: 紹介の分析情報データを定期的に確認し、注意が必要な傾向や分野を特定し、ビジネス目標に向けて取り組むことができます。
author: JnHs
ms.author: jenhayes
keywords: 紹介、分析、解析、メトリック、変換
ms.localizationpriority: high
ms.openlocfilehash: 027fcfb3dbd9b2a8f9c2f53fbfd2e765f15eff53
ms.sourcegitcommit: 0195355f4526362f4d89f59ea643a5e422b6a9b2
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/27/2019
ms.locfileid: "71318750"
---
# <a name="get-referral-insights"></a>紹介の分析情報を取得する

**適用対象**

- パートナー センター

パートナー センターの **[紹介の分析情報]** ページでは、紹介の効果を確認できます。 これらのメトリックを定期的に確認し、注意が必要な傾向や分野を特定し、ビジネス目標に向けて取り組んでください。

紹介の分析情報データを表示するには、パートナー センター メニューから **[紹介] > [紹介の分析情報]** に移動します。

## <a name="apply-filters"></a>フィルターの適用

**[紹介の分析情報]** ページの上部の辺りで、データを表示する期間を選択できます。 既定の選択は **[3M]** (3 か月) ですが、6 か月または 1 年の期間のデータを表示することができます。 また、 **[全期間]** を選択して、すべての紹介データを表示することもできます。

また、[フィルター] を展開し、このページ上のすべてのデータを市場、紹介の方向、紹介ソース、または紹介の種類で絞り込むこともできます。
- **市場**:既定値は **[すべて]** ですが、選択した 1 つまたは複数の市場にデータを絞り込むことができます。
- **紹介の方向**: 既定値は **[すべて]** ですが、データを **[受信]** の紹介 (自分が受信したもの) または **[送信]** の紹介 (自分が送信したもの) のいずれかに絞り込むことができます。
- **紹介ソース**:既定値は **[すべて]** ですが、次のいずれかのソースからの紹介にデータを絞り込むことができます。
  - **直接**:顧客によって直接作成されました。
  - **マーケティング クオリファイド**:Microsoft のマーケティング システムによって作成されました。
  - **セールス クオリファイド**:Microsoft 販売代理店によって作成されました。
  - **見込み度低い**:品質尺度が関連付けられていない紹介。
- **紹介の種類**: 既定値は **[すべて]** ですが、データを **[個別]** の紹介 (顧客と直接やり取りしてクローズする予定のもの) または **[共同販売]** の紹介 (連携してクローズする予定の追加のパーティを含むもの) に絞り込むことができます。

ここで説明するすべてのグラフの情報には、以下の注意する場合を除き、選択した日付範囲とフィルターが反映されます。 一部のセクションでは、特定のソリューションにフィルターを適用するなど、追加のフィルターを適用することもできます。

## <a name="referrals-summary"></a>紹介の概要

このグラフには、紹介の効果の概要が表示されます。 このグラフに適用されるのは、日付範囲フィルターのみであることに注意してください。その他のフィルターは適用されません。 

このグラフには、選択した期間の紹介の合計数、成約件数、合計取引額 (米国ドル) が表示されます。 グラフを展開すると、紹介ソースや紹介の方向の内訳などの追加データが表示されます。 

変化率メトリック (赤または緑で表示、矢印インジケーター付き) は、選択した日付範囲の最後の 1 か月間とその範囲の最初の 1 か月間の差を示します。 たとえば、現在の日付が 6 月 15 日で、過去 3 か月間のデータを表示する **[3M]** フィルターを選択したとします。 この場合、これらのメトリックでは、5 月 (選択した期間の最後の 1 か月間) と 3 月 (選択した期間の最初の 1 か月間) の差が示されます。選択した日付範囲は過去 **[3M]** であり、5 月のデータと 3 月のデータの比較になります。

## <a name="performance-by-solution"></a>ソリューション別の業績

このグラフでは、紹介件数が最も多いソリューションと、最も高い取引額を確認できます。

円グラフには、成約した紹介について、上位のソリューションの合計ビューが取引額別に表示されます。 選択した期間内に達成された業績について上位 4 つ のソリューションの詳細が表示されます。 これらの各ソリューションについて、成約した取引件数の合計、平均取引規模 (米国ドル)、合計取引額 (米国ドル)、およびコンバージョン率 (成約した取引の割合を示します) を確認できます。

## <a name="solution-performance-breakdown"></a>ソリューションのパフォーマンスの内訳

このグラフでは、より詳細な業績データを表示するために、1 つまたは複数のソリューションを選択できます。

選択したソリューションについて、次のようなグラフが表示されます。
- グラフの上部には、成約した取引件数の合計、平均取引規模 (米国ドル)、および合計取引額 (米国ドル) が表示されます。
- **[Referrals location]\(紹介先の場所\)** セクションには、紹介先の国/地域と、各国/地域の詳細が表示されます。
- **[紹介の傾向]** セクションには、選択した期間全体の紹介の業績のスナップショットが表示されます。
- **[紹介先の状態]** セクションには、さまざまな段階の紹介の総数を視覚的に示すインジケーターが表示されます。
- **[コンバージョン ファネル]** セクションには、 **[新規]** から **[承認済み]** 、 **[成立]** へと移行した紹介の数を視覚的に示すインジケーターが表示されます。
- **[平均進行時間]** セクションには、紹介がステージ間の移行にかかった平均日数が示されます (たとえば、 **[新規]** から **[承認済み]** )。
- **[保留中の紹介]** セクションには、まだ承認されていない、または拒否されている紹介に関する情報と、 **[アクションの実行]** へのリンクと承認または拒否が保留中の紹介が表示されます。 保留中の紹介がない場合は、ここにデータは表示されません。

## <a name="solution-performance-comparison"></a>ソリューションの業績の比較

このグラフでは、最大 3 つのソリューションを選択して紹介の業績 (紹介の数と成約した取引の数) を比較することができます。 3 つ以上のソリューションがある場合は、そのうち 3 つが既定で選択され、表示されます。 比較するソリューションは選択できます。

> [!NOTE]
> **[紹介の分析情報]** ページには、パートナー センターで生成された紹介のデータのみが表示されます。 [Partner Sales Connect](https://support.microsoft.com/help/3170447/learn-to-use-partner-center-sales-connect) または他のメカニズムを使用して生成された紹介のデータは表示されません。

> [!TIP]
> [[Find a solution provider]\(ソリューション プロバイダーを見つける\)](https://www.microsoft.com/solution-providers/home) エクスペリエンスでビジネス プロファイルの効果を表示するには、[[ビジネス プロファイルの分析情報]](analyze-your-marketing-profile.md) ページを確認します。
