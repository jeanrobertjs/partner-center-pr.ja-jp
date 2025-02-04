---
title: 顧客がパートナーに管理特権を委任する | パートナー センター
ms.topic: article
ms.date: 12/18/2018
description: リセラー パートナーの顧客は、リセラー パートナーに管理者を委任できます。また、特権を削除することもできます。
author: LauraBrenner
ms.author: labrenne
keywords: 委任された管理特権, 代理の管理, 特権の削除, DAP, AOBO
ms.localizationpriority: medium
ms.openlocfilehash: 9253bcca2d93d9f0d62d6d7241132f0c0c9bf5ec
ms.sourcegitcommit: b1ab80345b4e4af649fb8cc51d96d798e0791ade
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/23/2019
ms.locfileid: "62135452"
---
# <a name="customers-delegate-administration-privileges-to-partners"></a>顧客がパートナーに管理特権を委任する

**適用対象**

-  パートナー センター

顧客のサービスやをサブスクリプションを顧客に代わって管理するには、顧客からそのサービスについて管理者のアクセス許可を取得する必要があります。 顧客から管理者のアクセス許可を取得するには、再販業者関係の要求を顧客にメール送信します。 顧客が要求を承認すると、パートナーはサービスの管理ポータルにログオンして、顧客の代わりにサービスを管理することができます。 

## <a name="invite-a-customer-to-establish-a-reseller-relationship-with-you"></a>貴社との再販業者関係を確立するために顧客を招待する

1.  **[顧客]** を選択し、**[リセラーの関係を要求する]** を選びます。

2.  次のページで、メール メッセージの下書きを確認します。 既定のメール アプリケーションで下書きメッセージを開くか、メッセージをクリップボードにコピーし、メールに貼り付けます。 

    >[!IMPORTANT]
    >メールのテキストを編集することはできますが、リンクを必ず含めてください。このリンクは、顧客が貴社のアカウントに直接アクセスできるようにカスタマイズされています。 
    
3.  この手順を完了したら、**[完了]** を選びます。

4.  顧客にメールを送信します。

5.  顧客が招待を承諾すると、**[顧客]** ページに顧客が表示され、そこから顧客のサービスのプロビジョニングと管理を実行できるようになります。

6.  顧客のアカウント、サービス、ユーザー、ライセンスを管理するには、顧客の名前の下矢印を選んで、顧客のレコードを展開した後、管理するサービスの管理ポータルを選択します。

>[!IMPORTANT]  
>顧客は、サービスの管理者ポータルで、管理者のアクセス許可の割り当てを変更したり、削除したりすることができます。 ただし顧客が管理者のアクセス許可の割り当てを変更したり、削除したりした後も、パートナーが顧客との契約について再交渉しない限り、また再交渉するまで、パートナーは引き続きカスタマー サポートを提供し、クラウド リセラー契約の条項を遵守する責任を負います。 この状況で顧客にサポートが必要となった場合は、パートナーが顧客に代わって Microsoft サポートにサービス要求を求めることができます。

顧客は、Office 365 管理ポータルを使って、テナントの管理特権を持つパートナーを確認することができます。 これには、次の手順を実行します。

1. 顧客は、グローバル管理者として Office 365 管理ポータルにサインインする必要があります。

2. **[設定]**、**[パートナー関係]** の順に選択します。

3. 顧客は **[Partner relationships]\(パートナー関係\)** ページで、関係しているパートナーと、テナントの代理管理特権を持つパートナーを表示できます。

## <a name="customers-can-manage-a-partners-delegated-admin-privileges"></a>顧客は、パートナーに委任した管理特権を管理することができます。 

顧客は、テナントから委任された管理特権を削除できますが、サブスクリプションとライセンスの更新のため、パートナーとの関係は維持されます。 顧客は、Office 365 管理センターの **[パートナー関係]** ページで、Office 365 アカウントの権利とアクセス許可を管理します。 このページで、顧客は次のことを行えます。

- 関係を持つパートナーを確認し、代理管理特権を持つパートナーを確認できます

- パートナーの代理管理特権をテナントから削除します

パートナーの代理管理特権を削除するには、次の手順を実行します。

1. **[パートナー関係]** ページで、対象のパートナーを選択します。
2. 詳細ウィンドウで、**[代理管理者の削除]** をクリックします。
3. 確認ウィンドウで **[削除]** を選択します。

>[!IMPORTANT]  
>パートナーへの Azure AD ロールの割り当ては暗黙的です。 Azure AD ポータル/PowerShell/Graph を使用して、Azure AD ロールのメンバーを一覧表示した場合、パートナーは表示されません。 パートナーが Azure AD のロールに割り当てられているかどうかを確認するには、Office 365 管理ポータルの [パートナー関係] ページを参照して、代理管理特権がパートナーに付与されているかどうかを確認する必要があります。

## <a name="delegated-admin-privileges-in-azure-ad"></a>Azure AD の代理管理特権 

代理管理に使用されるパートナーの Azure AD テナントには、管理エージェントとヘルプデスク エージェントという、2 つのセキュリティ グループがあります。 顧客が代理管理特権をパートナーに付与する場合:

- 管理エージェント グループは、顧客の Azure AD テナントのグローバル管理者ロールに割り当てられます。

- ヘルプデスク エージェント グループは、顧客の Azure AD テナントのヘルプデスク管理者ロールに割り当てられます。

割り当てられたディレクトリ ロールに基づいて、両方のグループのメンバーは、パートナーの認証情報を使用して、顧客の代理で管理者として、顧客の Azure AD テナントおよび O365 サービスにサインインすることができます。

顧客が代理管理特権を削除すると、Azure AD ロールの割り当てが削除され、顧客の Azure AD テナントを管理することはできなくなります。

### <a name="azure-subscriptions-and-resource-management"></a>Azure サブスクリプションとリソース管理

各 Azure サブスクリプションには、独自のリソース管理ロールのセットがあります。 CSP パートナーが顧客の Azure サブスクリプションを管理するには、そのパートナーには Azure サブスクリプションの 1 つ以上のロールが割り当てられる必要があります。 具体的には、次のとおりです。

- 顧客がリセラーの招待を承諾し、代理管理特権をパートナーに付与した場合、パートナーは自動的には、顧客テナントの既存の Azure サブスクリプションにアクセスすることはできません。

- CSP パートナーが顧客に新しい Azure サブスクリプションをプロビジョニングすると、CSP パートナーのテナントの管理エージェント グループには、サブスクリプションの所有者ロールが自動的に割り当てられます。 このロールの割り当てに基づいて、グループのメンバーは、サブスクリプションのリソースにアクセスして管理することができます。

- 顧客が Office 365 ポータルを使用して、パートナーの代理管理特権を削除しても、パートナーは、サブスクリプションの 1 つ以上のロールに割り当てられている限り、引き続き顧客の Azure サブスクリプションを管理できます。 パートナーによる Azure サブスクリプションの管理を停止するには、顧客はロールの割り当てを削除する必要があります。

## <a name="windows-autopilot"></a>Windows Autopilot

<!--Maggie, 12/5/18 - Removed table showing what different CSP partner types can and can't do because all partner types are now in parity. As per Bhavya Chopra in bug 19841770.-->

CSP パートナーは、パートナー センターから、このような状況で委任された管理者特権がなくても、顧客に対する Autopilot プロファイルを管理できます。 

- 顧客が委任された管理特権を削除しても、パートナーとのリセラー関係を維持している場合は、パートナーは顧客のために引き続き Autopilot プロファイルを管理できます。

- 自分または別のパートナーが追加した顧客デバイスを管理することができます。 

- パートナーは、顧客がビジネス向け Microsoft Store、教育機関向け Microsoft Store、または Microsoft Intune ポータル経由で追加したデバイスを、管理することはできません。

Autopilot について詳しくは、「[Windows Autopilot でデバイスのセットアップを効率化する](https://docs.microsoft.com/partner-center/autopilot)」をご覧ください。

>[!IMPORTANT]  
>パートナー センターでの現在の Autopilot 管理エクスペリエンスは、引き続き変更される可能性があります。 この記事の公開時点では、以下の変更が検討されています。

- パートナーがプロファイルの追加/更新/削除を行ったり、顧客テナントの任意のデバイスのプロファイルの適用/削除を行ったりするには、顧客によってパートナーに代理管理特権が付与される必要があります。

- パートナーが、他のパートナーまたは顧客によって顧客のテナントに追加されたデバイスを削除するには、顧客によってパートナーに代理管理特権が付与される必要があります。 代理管理特権がない場合には、パートナーは自社が追加したデバイスのみを削除することができます。
