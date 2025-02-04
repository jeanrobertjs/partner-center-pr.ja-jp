---
title: Azure プランに移行する - はじめに | パートナー センター
ms.topic: article
ms.date: 10/15/2019
description: ''
author: LauraBrenner
ms.author: labrenne
Keywords: ''
robots: ''
ms.localizationpriority: High
ms.openlocfilehash: eb46255403297539c17145b82ecf096699abe390
ms.sourcegitcommit: cd90a59ff0ea81197b603abcb7bf462c4fb1edbe
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/09/2019
ms.locfileid: "72171275"
---
# <a name="move-to-azure-plan---get-started"></a>Azure プランに移行する - はじめに

Microsoft では、Microsoft パートナー契約に署名している Azure パートナー向けの CSP に新しいコマース エクスペリエンスを導入しています。 この新しいコマース エクスペリエンスでは、パートナーは、Microsoft 顧客契約に基づいて、従量課金制の料金で提供される顧客向けの Azure サービスにアクセスできるようになります。 

このプランによって、購入エクスペリエンスが簡略化され、複数の Azure サブスクリプションを 1 つのAzure プランに含めることができます。 Azure サブスクリプションごとに個別の注文を送信する必要がなくなりました。 また、Azure 向けのこの新しいコマース エクスペリエンスでは、単一のグローバルな価格体系に合わせているため、CSP パートナーが公開価格で Azure を提供できるようにしています。 

顧客が求めているデジタル変革のニーズでは、パートナーから新しいスキルを提供することが求められています。 多くの顧客は、クラウドへの移行を円滑に進めるための処理や Azure サービスを効率的に使用するためのサポートを上回るサービスの提供をパートナーに求めています。 Microsoft パートナーは、顧客のライフサイクルのすべての段階で重要な役割を果たします。 この種のパートナー サービスは本質的に継続的なものであり、Azure 資産の監視、ポリシーとガバナンスの管理、設定と構成の微調整、テクニカル サポート、およびその他のさまざまなサービスが含まれています。 顧客は、パートナーが顧客の Azure 環境を熟知し、管理対象のリソースを継続的かつ適切に管理して制御することを求めています。 この 24 時間 365 日体制でクラウド運用管理を提供する請求パートナーには、その仕事を行うために**管理しているサービスに対するパートナー獲得クレジット**を得る資格があります。

## <a name="make-sure-your-customers-have-signed-the-microsoft-customer-agreement"></a>顧客が Microsoft 顧客契約に署名していることを確認する

2019 年 10 月 1 日以降、顧客は、Microsoft 顧客契約 (完全にデジタル化されたプロセスを使用して顧客の購入エクスペリエンスの簡素化と合理化を行う永続的な契約) にデジタル署名することができます。 Azure 向けの CSP の新しいコマース エクスペリエンスを利用することを希望するすべての顧客は、Microsoft 顧客契約に署名する必要があります。

詳細については、「[Microsoft 顧客契約に対する顧客の同意を確認する](confirm-customer-agreement.md)」を参照してください。

## <a name="security-and-access-control-practices"></a>セキュリティとアクセス制御のプラクティス

パートナーと顧客を保護するために、マイクロソフトは、アドバイザー、コントロール パネル ベンダー、およびクラウド ソリューション プロバイダー プログラムに参加しているパートナーを対象とした一連の必須セキュリティ要件を導入しています。 

これらの要件が適用されると、必須のセキュリティ要件を実装していないパートナーは、クラウド ソリューション プロバイダー プログラムで取引したり、代理管理者権限を利用して顧客テナントを管理したりできなくなります。 現在、要件の技術的な適用開始日を設定しています。日付と詳細情報については、追ってパートナーに通知します。 

## <a name="actions-to-take-to-implement-mfa"></a>MFA を実装するために実行するアクション 

パートナーには高い特権が付与されている、という点を考えると、すべての単一認証について、MFA チャレンジが各ユーザーに確実に適用されるようにする必要があります。 これは、次のいずれかの方法で実現できます。

- Azure AD Premium を実装し、多要素認証 (MFA) が各ユーザーに確実に適用されるようにする 
- ベースライン保護ポリシーを実装する 
- サードパーティ ソリューションを実装し、MFA が各ユーザーに確実に適用されるようにする 

2019 年 8 月 1 日以降、すべてのパートナーは、パートナー テナントのすべてのユーザー (サービス アカウントを含む) に対して多要素認証を適用する必要があります。 これらのセキュリティ要件の詳細については、「[パートナーのセキュリティ要件](https://docs.microsoft.com/partner-center/partner-security-requirements)」を参照してください。 

Microsoft では、[Azure Active Directory Privileged Identity Management リソース](https://docs.microsoft.com/azure/active-directory/privileged-identity-management/pim-configure )を通して有効になるベスト プラクティスに従って、RBAC を十分に活用することをパートナーに推奨しています。 

## <a name="read-more-about-the-azure-plan"></a>Azure プランの詳細を確認する

- [Azure プランを購入する](purchase-azure-plan.md)

- [Azure オファーを比較する](compare-azure-offers.md)

- [パートナー獲得クレジット - 概要](partner-earned-credit.md)

- パートナー獲得クレジット (PEC) の計算、パートナー獲得クレジットを得る資格があるロールとアクセス許可については、パートナー センター ダッシュボードの価格表で確認できます (サインインする必要があります)。

- [パートナー獲得クレジットの計算方法 - 詳細](partner-earned-credit-explanation.md)

- [Azure プランの価格表の説明](azure-plan-price-list.md)

- [顧客を Azure プランに移行する](azure-plan-transition.md)

- [Azure プランのサブスクリプションとリソースを管理する](azure-plan-manage.md)

- [Azure プランを利用できる国/地域の完全な一覧](https://query.prod.cms.rt.microsoft.com/cms/api/am/binary/RE3QN0x)

 



