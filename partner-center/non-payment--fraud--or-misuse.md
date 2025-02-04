---
title: 未払い、詐欺、または誤用 | パートナー センター
ms.topic: article
ms.date: 10/25/2019
description: 商品やサービスに対する顧客の未払い、不正行為、不正使用などのオンライン トランザクション リスクを管理するための戦略。
ms.assetid: 2F4B9A27-37FF-41E4-8A26-5EAE88DD8A49
keywords: 詐欺, 不正使用, 使用条件, 利用規約, 未払い, 顧客が料金を支払わない, オンライン リスク, サービスの盗用, サービスの不正使用, サブスクリプションの一時停止,
author: MaggiePucciEvans
ms.author: evansma
ms.localizationpriority: medium
ms.custom: seodec18
ms.openlocfilehash: 2e8ab123b4b735f685c7caf1ba740c04c93fd134
ms.sourcegitcommit: 07e459a906c384eab114246d0ac550605abc4a45
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/28/2019
ms.locfileid: "72978734"
---
# <a name="non-payment-fraud-or-misuse"></a>未払い、詐欺、または誤用

**適用対象**

-  パートナー センター
-  米国政府機関向け Microsoft Cloud のパートナー センター



パートナーは、顧客による不正購入や、購入サービスの料金未払いについて、金銭的な責任を負います。 このため、詐欺の防止と発見およびリスク軽減に向けた対策を講じることをお勧めします。

## <a name="types-of-online-risk"></a>オンライン リスクの種類

不正行為や不正使用を回避したり、これらに対処するには、潜在的なリスクを理解して、リスクへの露出を軽減するためのポリシーとプラクティスを作成することが重要です。

#### <a name="risk-exposure-to-be-mitigated"></a>露出の軽減が必要なリスクの種類

- **サービスの盗用**: 使用したサービスに対して顧客が料金を支払う意図がないこと。支払い方法の盗用、不正な請求情報の提供、未払い額の支払い不履行などの方法が使用されます。

- **サービスの不正使用**: 顧客が Microsoft の利用規約に従わずにクラウド サービスを使用すること。

#### <a name="examples-of-possible-fraud-or-service-abuse"></a>詐欺やサービス不正使用の例
- スパム
- ハッキング
- DDOS 攻撃
- ビットコイン マイニング
- マルウェアの配布
- 偽造されたサブスクリプションの再販 

#### <a name="examples-of-online-transaction-risk"></a>オンライン トランザクション リスクの例
- "クレジット カードが存在しない" トランザクション (対面で行わないトランザクションなど)
- ID の不正使用
- サービスのプロビジョニングおよび使用が最初の支払い受領前に発生すること
- 新興市場/オンライン詐欺のリスクが高い地域
- 不正目的でのアカウントの作成と購入の自動化

## <a name="strategies-for-managing-online-risk"></a>オンライン リスクの管理戦略

これらの推奨事項は、顧客との関係のライフサイクル全体を通じて、オンライン トランザクション リスクにさらされる度合いを軽減するためのポリシーとプラクティスの作成に役立ちます。  

#### <a name="when-onboarding-new-customers"></a>新規顧客のオンボード時
- 可能であれば直接的に顧客との関係を確立します (電話で連絡するなど)。
- 顧客の信用状態や経歴を確認するための良い方法 (信用調査所/企業調査会社など) を探します。 
- ロボットによるアカウントの作成と購入のリスクを最小限に抑えるため、サインアップ中に SMS 検証を使用します。
- デジタル ID サービスなどのサービスを使用して ID 管理と追跡を行います。
- クレジット カード詐欺を厳密に検出するシステムを使用して、顧客の財務体質を確認します。
- プロセスのコレクションを詳細に記述し、どのようなときにサブスクリプションへのアクセスに影響するかを示した明確なポリシーを作成します (未払いに対して、アクセスを無効にするか[顧客のサブスクリプションを一時停止する](suspend-a-subscription.md)ことができます)。

#### <a name="post-purchase-customer-account-management"></a>購入後の顧客アカウント管理
- 顧客と連携して、クラウド利用のビジネス ニーズを理解し、適切な監視しきい値を設定します。
    > [!NOTE]  
    >  パートナー センターで [Azure の月額支出予算を設定](set-an-azure-spending-budget-for-your-customers.md)すると、顧客による月間使用量を監視し、顧客の支出が予算の上限に近づいた場合にメールで通知を受け取ることができます。
- [顧客のアクティビティ ログ](activity-logs.md)を定期的に監視することにより、詐欺を早い段階で検出します。
- 疑わしい活動が検出されたら、迅速にアクションを実行します。
- リスク軽減コントロールを実装する前に、サブスクリプションへの完全な管理アクセス権を顧客に設定しないでください。
- Microsoft の通知を迅速に受信、確認、対応、応答するプロセスを実装します。

#### <a name="post-purchase-customer-billing-management"></a>購入後の顧客請求管理
- 最初のトランザクションおよび請求の前に、前払いを要求します。 
- プリペイド カードやストアド バリュー カードなど、高リスクの支払い方法は受け入れないでください。
- 顧客の支払い状況と未払い金を監視し、遅延や未払いについては、標準化された督促手順を積極的に適用します。

オンライン リスクを軽減するための詳しい方法については、[オンライン トランザクション リスクの管理ガイド](https://assets.windowsphone.com/7d885238-e13b-4f10-a682-3d5adacd2859/CSP-PartnerRiskGuide-APSFinal_InvariantCulture_Default.zip)をご覧ください。

> [!IMPORTANT]  
> パートナーまたは顧客の活動が利用規約に違反していると Microsoft によって確認された場合または違反の疑いが検出された場合は、強制手順が実施されます。 お客様はすぐに中断され、Microsoft から貴社に強制措置について通知するか、要求が更新されます。

 セキュリティと multi-factor authentication の詳細については、「[パートナーのセキュリティ要件](partner-security-requirements.md)」を参照してください。

 



