---
title: CPOR モデルを使用して顧客の関連付けを作成する |パートナーセンター
ms.topic: article
ms.date: 10/29/2019
description: CPOR モデルを使用して顧客の関連付けを作成する
author: LauraBrenner
ms.author: labrenne
keywords: インセンティブ要求、共同操作要求、共同操作ファンド、OSU、OSA、ISV、収益関連
ms.localizationpriority: medium
ms.openlocfilehash: 9acac203d44e3942f9a07bc5af90528e558bce39
ms.sourcegitcommit: 014669c26592a3ab35c2aa7f3ff615f5f1091752
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/30/2019
ms.locfileid: "73083867"
---
**適用対象**

-  パートナー センター

# <a name="create-a-customer-association-using-the-cpor-model"></a>CPOR モデルを使用して顧客の関連付けを作成する

2019年10月1日に、Microsoft は、パートナーの取引先レコード (CPOR) モデルを使用して、オンラインサービスアドバイザリ (OSA) の販売、オンラインサービス使用状況 (OSU) に関して、Microsoft 365 と Dynamics 365 のお客様との関連付けを管理しました。Microsoft 365 と OSU-ビジネスアプリケーションインセンティブ。

要求を送信すると、Microsoft によって検証されます。 詳細については、こちらからお問い合わせください。 また、お客様にアソシエーション要求を通知します。 お客様は、5営業日以内にオプトアウトできます。オプトアウトされていない場合は、この特定のテナントとワークロードとの関連付けが公式になります。 この時点で、顧客の使用状況データにアクセスできます。 

要求を完了するには、次の情報が必要です。

- 要求を行うエンティティの**MPN ID**

- 顧客の**ドメイン名**[検索](https://docs.microsoft.com/partner-center/find-customer-domain-name)

- 顧客の**ディレクトリ id**または**テナント id**を[検索](https://docs.microsoft.com/partner-center/find-customer-domain-name)します

- Business Applications や Microsoft 365 などの**ソリューション領域**

- 実行した**アクティビティ**と、販売前、使用状況、収益の関連付けなど、作成する要求の種類

- お客様の**連絡先の名前**、役職、および電子メールアドレス

- Dynamics 365 では、顧客の**技術担当者**名、役職、および電子メールアドレスも入力する必要があります。

- 自分の会社の**連絡先名**と電子メールアドレス

- この要求の**名前**を作成します

- 要求している**製品**またはワークロード

- 顧客によって署名された作業ステートメントなど、**実行の証拠 (POE)** 。 また、使用する POE テンプレートをダウンロードすることもできます。

- 収益の関連付けのみを要求しているパートナーの場合: **Dynamics ソリューション販売者名**、**顧客名**、および**ISV 製品/ソリューションの名前**。 

また、次の点についても理解しておく必要があります。
- 既存の Microsoft 365 のお客様の場合は、このプロセスを使用して引き続き OSU インセンティブを獲得する必要があります。
- Dynamics 365 または Power BI の顧客との既存の関連付けがある場合、これらの関連付けは、サブスクリプションの有効期限が切れるまで有効のままになります。
- 顧客は複数のパートナーを持つことができますが、各ワークロード (OSU-Microsoft 365) またはサブスクリプション (OSA 販売と OSU-Business Applications) は、1つのパートナーにのみ関連付けることができます。

## <a name="create-a-customer-association"></a>顧客の関連付けを作成する
1.  パートナーセンターのダッシュボードで、 **[インセンティブ]** の下にある **[概要]** を選択し、 **[顧客の関連付け]** を選択します。 

2.  顧客の関連付け ページの上部で、 **+ 顧客の関連付け** を選択します。

3.  顧客に関連付けるパートナーの場所の**MPN ID**を選択し、顧客のドメイン名とディレクトリ ID を追加します。 [これらはどこにありますか。](https://docs.microsoft.com/partner-center/find-customer-domain-name)

**[続行]** を選びます。

4.  ソリューションの**区分**と**アクティビティ**を選択します。 

>[!Note]

>[Business Applications] を選択した場合は、[**使用状況] または [事前売上**] または **[収益の関連付け]** を選択し、 **[続行]** を選択します。 

>[収益の関連付け] を選択した場合は、以下の情報とは少し異なる情報を入力するように求められます。 

5.  **[顧客の関連付け]** ページで適切な情報を入力し、 **[要求の作成]** を選択します。

6.  この顧客の関連付けに関連付けられている製品を選択し、 **[続行]** を選択します。

7.  お客様の連絡先情報と会社の連絡先情報を入力します。 すべてのフィールドは必須です。 

>[!Note]

製品が Dynamics 365 で、選択した製品がこの特定の顧客に対して複数のサブスクリプションを持っている場合は、サブスクリプション ID も入力する必要があります。

8.  実行の証拠 (POE) を提供します。 このボタンをボックスにドラッグするか、独自のサポートドキュメントを参照するか、[テンプレートの**ダウンロード**] を選択してテンプレートを使用することができます。 

9.  必要に応じてコメントを追加して保存し、 **[要求の送信]** を選択します。 顧客の関連付けの承認を要求する電子メールをお客様に送信します。 

>[!NOTE]

>顧客の関連付けを送信した後は、それを編集することはできません。 

顧客の関連付けの状態が **[状態]** フィールドに表示されます。 

**[履歴]** を選択して、顧客の関連付けの履歴を表示します。
