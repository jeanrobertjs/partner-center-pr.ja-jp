---
title: Azure プランのサブスクリプションとリソースを管理する | パートナー センター
ms.topic: article
ms.date: 10/04/2019
description: 複数の Azure サブスクリプションを、サブスクリプションごとに注文を送信することなく購入します
ms.assetid: ''
author: LauraBrenner
ms.author: labrenne
ms.localizationpriority: High
ms.openlocfilehash: 5aa39cbecc7f468329c9a5234dd975c776a63ea6
ms.sourcegitcommit: dcc2a2077ef17255ecf7a2fa5fae6bbeefaa9eb0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/07/2019
ms.locfileid: "71997864"
---
# <a name="manage-subscriptions-and-resources-under-the-azure-plan"></a>Azure プランのサブスクリプションとリソースを管理する

パートナーは、顧客を Azure プランに移行すると、既定では Azure の特権管理者権限 (代理管理者によるサブスクリプション所有者権限) が割り当てられます。

 > [!NOTE]
 > Azure サブスクリプションに対する管理者権限は、サブスクリプション、リソース グループ、またはワークロード レベルで顧客が削除できます。 

 パートナーは、CSP で、ロールベースのアクセス制御機能 (RBAC) によって提供されるさまざまなオプションを使用して、顧客の Azure リソースを 24 時間体制で制御し、管理することができます。 

- **代理管理者 (AOBO)** - AOBO では、パートナー テナントの管理者エージェント ロールを持つすべてのユーザーに、CSP プログラムを使用して作成した Azure サブスクリプションに対する RBAC 所有者のアクセス権が付与されます。

- **Azure Lighthouse**:AOBO では、複数の顧客と連携する個別のグループを柔軟に作成したり、グループやユーザーに対して複数のロールを有効にしたりすることはできません。 Azure Lighthouse を使用すると、複数のグループを複数の顧客またはロールに割り当てることができます。 Azure の委任されたリソース管理によって、ユーザーには適切なレベルのアクセス権が付与されるため、管理者エージェント ロールを持つ (つまり、AOBO のフル アクセス権を持つ) ユーザーの数を減らすことができます。 これにより、顧客のリソースへの不要なアクセスが制限され、セキュリティを向上させることができます。 また、大規模な複数の顧客をより柔軟に管理できます。 詳細については、「[Azure Lighthouse と Cloud Solution Provider プログラム](https://docs.microsoft.com/azure/lighthouse/concepts/cloud-solution-provider)」を参照してください。

-  **ディレクトリまたはゲスト ユーザーまたは[サービス プリンシパル](https://docs.microsoft.com/azure/active-directory/develop/app-objects-and-service-principals)** :CSP サブスクリプションへの詳細なアクセス権を委任するには、顧客のディレクトリにユーザーを追加するか、ゲスト ユーザーを追加して特定の RBAC ロールを割り当てます。 

セキュリティ対策として、作業を実行するために必要な最小限のアクセス許可をユーザーに付与することをお勧めします。 [Azure Active Directory Privileged Identity Management リソース](https://docs.microsoft.com/azure/active-directory/privileged-identity-management/pim-configure)に関する記事を参照してください。 

## <a name="link-your-partner-id-mpn-idto-your-credentials-for-managing-customers-azure-resources"></a>顧客の Azure リソースを管理するためにパートナー ID (MPN ID) を自分の資格情報にリンクする

次の表は、パートナー ID をさまざまな RBAC アクセス オプションに関連付けるために使用する方法をまとめたものです。

|**カテゴリ**   |**シナリオ**   |**MPN ID の関連付け**|
|-----------------|:------------------------|:------------------|
|AOBO   |CSP ダイレクト パートナーまたはインダイレクト プロバイダーは、AOBO を使用して、CSP ダイレクト パートナーまたはインダイレクト プロバイダーをサブスクリプションの既定の所有者にする顧客のサブスクリプションを作成します。CSP のダイレクト パートナーまたはインダイレクト プロバイダーは、AOBO を使用して、サブスクリプションへのアクセス権をインダイレクト リセラーに付与します。|自動 (パートナーの作業は不要)|
|Azure Lighthouse|パートナーは、新しい[マネージド サービス オファーをマーケットプレースに](https://docs.microsoft.com/azure/lighthouse/concepts/managed-services-offers)作成します。 このオファーが CSP サブスクリプションで承認されると、パートナーは CSP サブスクリプションにアクセスできるようになります。|自動 (パートナーの作業は不要)|
|Azure Lighthouse|パートナーは、Azure サブスクリプションで [ARM テンプレート](https://docs.microsoft.com/azure/lighthouse/how-to/onboard-customer)をデプロイします|パートナーは、パートナー テナントのユーザーまたはサービス プリンシパルに MPN ID を関連付ける必要があります。 詳細については、[パートナー ID のリンク](https://docs.microsoft.com/en-us/azure/billing/billing-partner-admin-link-started)に関する記事を参照してください。|
|ディレクトリまたはゲスト ユーザー|パートナーは、顧客のディレクトリに新しいユーザーまたはサービス プリンシパルを作成し、ユーザーに CSP サブスクリプションへのアクセス権を付与します。 パートナーは、顧客のディレクトリに新しいユーザーまたはサービス プリンシパルを作成します。 パートナーは、グループにユーザーを追加し、グループへの CSP サブスクリプションへのアクセス権を付与します。|パートナーは、顧客テナントのユーザーまたはサービス プリンシパルに MPN ID を関連付ける必要があります。 詳細については、[パートナー ID のリンク](https://docs.microsoft.com/en-us/azure/billing/billing-partner-admin-link-started)に関する記事を参照してください。|

## <a name="confirm-that-you-have-admin-access"></a>管理者アクセス権を持っていることを確認する

顧客のサービスを管理し、獲得したクレジットを受け取るには、管理者アクセス権が必要です。 獲得したクレジットの詳細については、[パートナー獲得クレジット](partner-earned-credit.md)に関する記事を参照してください。 管理者アクセス権を持っていることを確認するには、2 つの方法があります。

- 毎日の利用状況ファイルを確認する - これを判断するには、毎日の使用量ファイル内の単価と実効単価を見て、割引が適用されているかどうかを確認します。 割引が適用されている場合は管理者です。

- Azure Monitor のアラートを作成する - RBAC のアクセスが CSP サブスクリプションから削除されたことが通知する Azure Monitor のアクティビティ ログ [アラート](https://docs.microsoft.com/azure/azure-monitor/platform/alerts-activity-log)を作成します。

### <a name="create-an-azure-monitor-alert"></a>Azure Monitor のアラートを作成する

1. アラートを作成します。

![Azure アラート](images/azure/azurealert1.png)

2. アラートを受け取るアクションの種類を選択します。たとえば、メールを送信するように指定すると、ロールの割り当ての削除が発生した場合に通知するメールが送信されます。

![アラートを構成する](images/azure/azureconfigurealert2.png)

### <a name="aobo-removal"></a>AOBO の削除

顧客は、Azure portal で **[アクセス制御]** に移動してサブスクリプションへのアクセスを管理できます。 **[ロールの割り当て]** タブで、 **[アクセス許可の削除]** を選択します。 この操作が行われた場合は、以下のように対処します。

- 顧客と話し、管理者アクセス権を回復できるかどうかを確認します。
- [ロールベースのアクセス制御 (RBAC)](https://docs.microsoft.com/azure/role-based-access-control/overview) を介して付与されたアクセス権を使用します。
- [Azure Lighthouse](https://azure.microsoft.com/services/azure-lighthouse/) を介して付与されたアクセス権を使用します。

ロールベースのアクセス権は、管理者アクセス権とは異なります。 ロールでは、できることと実行できないことが明確に分かれています。 管理者アクセス権の方が広範囲です。

PEC を獲得できるロールを確認するには、[パートナー獲得クレジットのロールとアクセス許可](https://query.prod.cms.rt.microsoft.com/cms/api/am/binary/RE3QuW2)に関する記事を参照してください。

**詳細情報**

- [パートナー獲得クレジット - 概要](partner-earned-credit.md)

- [マネージド サービスのパートナー獲得クレジット](partner-earned-credit-explanation.md)