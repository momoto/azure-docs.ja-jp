---
title: MailChimp に接続する
description: MailChimp REST API と Azure Logic Apps を使用して、マーケティング電子メールを作成および管理します
services: logic-apps
ms.suite: integration
ms.reviewer: klam, logicappspm
ms.topic: article
ms.date: 08/18/2016
tags: connectors
ms.openlocfilehash: a440f702058abc25bb360111418c451d59c3ab1b
ms.sourcegitcommit: 76b48a22257a2244024f05eb9fe8aa6182daf7e2
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 12/03/2019
ms.locfileid: "74789639"
---
# <a name="get-started-with-the-mailchimp-connector"></a>MailChimp コネクタの使用

MailChimp は、電子メール マーケティング活動を管理および自動化するための企業向け SaaS サービスです。このサービスにより、マーケティング電子メールの送信、自動メッセージ、対象を絞ったキャンペーンなどを行うことができます。

まず、ロジック アプリを作成します。[ロジック アプリの作成](../logic-apps/quickstart-create-first-logic-app-workflow.md)に関する記事を参照してください。

## <a name="create-a-connection-to-mailchimp"></a>MailChimp への接続の作成

MailChimp を使用してロジック アプリを作成するには、まず**接続**を作成してから、次のプロパティの詳細を指定する必要があります。

| プロパティ | 必須 | 説明 |
| --- | --- | --- |
| トークン |はい |MailChimp の資格情報を提供します |

> [!INCLUDE [Steps to create a connection to MailChimp](../../includes/connectors-create-api-mailchimp.md)]

## <a name="connector-specific-details"></a>コネクタ固有の詳細

[コネクタの詳細](/connectors/mailchimp/)に関するページに、Swagger で定義されているトリガーとアクション、さらに制限が記載されています。

## <a name="more-connectors"></a>その他のコネクタ

[API リスト](apis-list.md)に戻ります。