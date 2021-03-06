---
title: Azure からの支払期限を過ぎた未払い額に関する電子メール
description: Azure サブスクリプションに支払期限を過ぎた未払い額がある場合の支払い方法について説明します
author: genlin
manager: dcscontentpm
tags: billing
ms.service: cost-management-billing
ms.workload: na
ms.tgt_pltfrm: na
ms.devlang: na
ms.topic: conceptual
ms.date: 05/20/2019
ms.author: banders
ms.openlocfilehash: c042f5cee3d0a1e874729911a2162e48c1630a72
ms.sourcegitcommit: d6b68b907e5158b451239e4c09bb55eccb5fef89
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 11/20/2019
ms.locfileid: "74226425"
---
# <a name="resolve-past-due-balance-for-your-azure-subscription"></a>支払期限を過ぎた Azure サブスクリプション未払い額の支払い

この記事は、Microsoft オンライン サービス プログラム アカウントを使用するお客様に適用されます。

お客様の支払いが届いていない場合や、お客様の支払いを処理できない場合、メールが届いたり、Azure portal またはアカウント センターにアラートが表示されたりすることがあります。
自分が[アカウント管理者](billing-subscription-transfer.md#whoisaa)である場合は、[Azure portal](https://portal.azure.com) で未払い料金を清算できます。 請求書モードの支払いを利用している場合、請求書の下部に記載されている場所に支払いを送付します。

> [!IMPORTANT]
> * 同じクレジット カードを使用する複数のサブスクリプションがあり、それらがすべて支払期限を過ぎている場合は、未払い残高全体を一度に支払う必要があります。
> * 未払い料金の清算に使用する支払い方法は、失敗した支払い方法を使用していたすべてのサブスクリプションの新しいアクティブな支払い方法になります。

## <a name="resolve-past-due-balance-in-the-azure-portal"></a>Azure portal で期限切れの残高を清算する

1. [Azure portal](https://portal.azure.com) にアカウント管理者としてサインインします。
1. "**コスト管理 + 請求**" を検索します。
1. [概要] ページにサブスクリプションの一覧が表示されます。 サブスクリプションの状態が期限切れの場合は、 **[Settle balance]\(残高の清算\)** リンクをクリックします。
    ![[Settle balance]\(残高の清算\) リンクを示すスクリーン ショット](./media/billing-azure-subscription-past-due-balance/settle-balance-entry-point.png)
1. 合計未払い残高には、失敗した支払い方法を使用するすべての Microsoft サービスの未払い料金が反映されます。
1. 残高を支払うための支払い方法を選択します。 この支払い方法は、現在、失敗した支払い方法を使用しているすべてのサブスクリプションのアクティブな支払い方法になります。
    ![支払い方法の選択のリンクを示すスクリーン ショット](./media/billing-azure-subscription-past-due-balance/settle-balance-screen.png)
1. 選択した支払い方法にも Microsoft サービスの未払い料金がある場合は、これが合計未払い残高に反映されます。 それらの未払い料金も支払う必要があります。
1. **[Pay]\(支払う\)** をクリックします。

## <a name="troubleshoot-declined-credit-card"></a>拒否されたクレジット カードのトラブルシューティング

クレジット カードによる支払いが金融機関によって拒否された場合は、金融機関に問い合わせてこの問題を解決してください。 お使いの銀行で、以下を確認してください。
- カードの国際取引が有効になっている。
- カードに、残高を清算するのに十分な信用限度または資金がある。
- カードの定期的な支払いが有効になっている。

## <a name="not-getting-billing-email-notifications"></a>支払いに関する電子メール通知が届きません。

アカウント管理者である場合は、[通知に使用されている電子メール アドレスを確認](billing-how-to-change-azure-account-profile.md)します。 定期的にチェックする電子メール アドレスを使用することをお勧めします。 電子メールが正しい場合は、迷惑メール フォルダーを確認します。

## <a name="if-i-forget-to-pay-what-happens"></a>支払いを忘れた場合

サービスが取り消され、リソースは使用できなくなります。 サービス停止の 90 日後に、すべての Azure データが削除されます。 詳しくは、[Microsoft Trust Center の Microsoft によるデータの管理方法](https://go.microsoft.com/fwLink/p/?LinkID=822930&clcid=0x409)に関するページをご覧ください。

支払い処理が完了しているのに、サブスクリプションが無効のままになっている場合は、[Azure サポート](https://portal.azure.com/#blade/Microsoft_Azure_Support/HelpAndSupportBlade)までご連絡ください。


## <a name="need-help-contact-us"></a>お困りの際は、 お問い合わせください。

ご質問がある場合やヘルプが必要な場合は、[サポート リクエストを作成](https://go.microsoft.com/fwlink/?linkid=2083458)してください。
