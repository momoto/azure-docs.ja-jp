---
title: Linux VM 向け Azure Disk Storage マネージド ディスクの概要
description: Linux VM を使用するときにストレージ アカウントを管理する Azure マネージド ディスクの概要
author: roygara
ms.service: virtual-machines-linux
ms.topic: overview
ms.date: 11/06/2019
ms.author: rogarana
ms.subservice: disks
ms.openlocfilehash: 7e9a5e1b1e1b0c879a1264573e7073e70a1e95fc
ms.sourcegitcommit: 49cf9786d3134517727ff1e656c4d8531bbbd332
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 11/13/2019
ms.locfileid: "74035863"
---
# <a name="introduction-to-azure-managed-disks"></a>Azure マネージド ディスクの概要

Azure マネージド ディスクは仮想ハード ディスク (VHD) です。 オンプレミス サーバーの物理ディスクと似ていますが、仮想化されたディスクと考えることができます。 Azure マネージド ディスクは、Azure のランダム IO ストレージ オブジェクトであるページ BLOB として格納されます。 マネージド ディスクを "マネージド" と呼ぶ理由は、ページ BLOB、BLOB コンテナー、および Azure ストレージ アカウントを抽象化したものであるためです。 マネージド ディスクでは、ディスクをプロビジョニングするだけで、後の管理は Azure が実行します。

ワークロードに Azure マネージド ディスクを使用することを選択した場合、Azure で自動的にディスクが作成され、管理されます。 使用できるディスクの種類は、Ultra ディスク、Premium ソリッド ステート ドライブ (SSD)、Standard SSD、Standard ハード ディスク ドライブ (HDD) です。 各ディスクの種類の詳細については、「[IaaS VM 用のディスクの種類の選択](disks-types.md)」を参照してください。

[!INCLUDE [virtual-machines-managed-disks-overview.md](../../../includes/virtual-machines-managed-disks-overview.md)]

> [!div class="nextstepaction"]
> [IaaS VM 用のディスクの種類の選択](disks-types.md)
