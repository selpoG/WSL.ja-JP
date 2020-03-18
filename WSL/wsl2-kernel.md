---
title: WSL 2 Linux カーネルの更新
description: WSL 2 Linux カーネルを手動で更新するための手順
keywords: BashOnWindows, bash, wsl, windows, windows subsystem for linux, windowssubsystem, ubuntu, wsl.conf, wslconfig
ms.date: 03/12/2020
ms.topic: article
ms.assetid: 7afaeacf-435a-4e58-bff0-a9f0d75b8a51
ms.localizationpriority: high
ms.custom: seodec18
ms.openlocfilehash: f7fce13c2acc65e3afa2cc56873e40bc55a460bc
ms.sourcegitcommit: 506272bd7fc1cbda7e32146d54a8bdd02af3e0c4
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/13/2020
ms.locfileid: "79319712"
---
# <a name="updating-the-wsl-2-linux-kernel"></a><span data-ttu-id="6de1a-104">WSL 2 Linux カーネルの更新</span><span class="sxs-lookup"><span data-stu-id="6de1a-104">Updating the WSL 2 Linux kernel</span></span>

<span data-ttu-id="6de1a-105">WSL 2 内の Linux カーネルを手動で更新するには、次の手順に従ってください。</span><span class="sxs-lookup"><span data-stu-id="6de1a-105">To manually update the Linux kernel inside of WSL 2 please follow these steps.</span></span> 

## <a name="download-the-linux-kernel-update-package"></a><span data-ttu-id="6de1a-106">Linux カーネル更新プログラム パッケージをダウンロードする</span><span class="sxs-lookup"><span data-stu-id="6de1a-106">Download the Linux kernel update package</span></span>

<span data-ttu-id="6de1a-107">[このリンク](https://wslstorestorage.blob.core.windows.net/wslblob/wsl_update_x64.msi)をクリックして、AMD64 マシン用の最新の WSL2 Linux カーネル更新プログラム パッケージをダウンロードしてください。</span><span class="sxs-lookup"><span data-stu-id="6de1a-107">Please click on [this link](https://wslstorestorage.blob.core.windows.net/wslblob/wsl_update_x64.msi) to download the latest WSL2 Linux kernel update package for AMD64 machines.</span></span>

> [!NOTE] 
> <span data-ttu-id="6de1a-108">ARM64 マシンを使用している場合は、代わりに[このパッケージ](https://wslstorestorage.blob.core.windows.net/wslblob/wsl_update_arm64.msi)をダウンロードしてください。</span><span class="sxs-lookup"><span data-stu-id="6de1a-108">If you're using an ARM64 machine, please download [this package](https://wslstorestorage.blob.core.windows.net/wslblob/wsl_update_arm64.msi) instead.</span></span>

## <a name="install-the-linux-kernel-update-package"></a><span data-ttu-id="6de1a-109">Linux カーネル更新プログラム パッケージをインストールする</span><span class="sxs-lookup"><span data-stu-id="6de1a-109">Install the Linux kernel update package</span></span>

<span data-ttu-id="6de1a-110">Linux カーネル更新パッケージをインストールするには、次の手順に従ってください。</span><span class="sxs-lookup"><span data-stu-id="6de1a-110">To install the Linux kernel update package:</span></span>

    1. <span data-ttu-id="6de1a-111">前の手順でダウンロードした更新プログラム パッケージを実行します。</span><span class="sxs-lookup"><span data-stu-id="6de1a-111">Run the update package downloaded in the previous step.</span></span>
    2. <span data-ttu-id="6de1a-112">管理者特権のアクセス許可の入力が求められます。このインストールを承認するには、[はい] を選択します。</span><span class="sxs-lookup"><span data-stu-id="6de1a-112">You will be prompted for elevated permissions, select ‘yes’ to approve this installation.</span></span>
    3. <span data-ttu-id="6de1a-113">インストールが完了したら、WSL2 の使用を開始できます。</span><span class="sxs-lookup"><span data-stu-id="6de1a-113">Once the installation is complete, you are ready to begin using WSL2!</span></span>

## <a name="future-plans-for-updating-the-wsl2-linux-kernel"></a><span data-ttu-id="6de1a-114">WSL2 Linux カーネルの更新に関する今後の計画</span><span class="sxs-lookup"><span data-stu-id="6de1a-114">Future plans for updating the WSL2 Linux kernel</span></span>

<span data-ttu-id="6de1a-115">これらの変更の詳細については、[Windows コマンド ライン ブログ](https://aka.ms/cliblog)の[このブログ記事](https://devblogs.microsoft.com/commandline/wsl2-will-be-generally-available-in-windows-10-version-2004)をお読みください。</span><span class="sxs-lookup"><span data-stu-id="6de1a-115">For more info on these changes, please read [this blog post](https://devblogs.microsoft.com/commandline/wsl2-will-be-generally-available-in-windows-10-version-2004) on the [Windows Command Line Blog](https://aka.ms/cliblog).</span></span>