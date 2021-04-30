---
title: Install Dotfuscator Community
ms.date: 04/30/2021
ms.devlang: dotnet
ms.topic: how-to
keywords: Dotfuscator, Dotfuscator Community, Dotfuscator CE, PreEmptive, PreEmptive Solutions, PreEmptive Protection, protection, community edition, obfuscation, .NET, free, Visual Studio 2017, Visual Studio 2019, Visual Studio, install
helpviewer_keywords:
- PreEmptive Protection Dotfuscator
- Dotfuscator Community Edition
- Dotfuscator CE
- Dotfuscator Community
- Dotfuscator
- obfuscation
- protection
- Dotfuscator installer
- Dotfuscator setup
- install Dotfuscator
- installing Dotfuscator
- set up Dotfuscator
description: Learn how to install the free copy of Dotfuscator Community included in Visual Studio.
ms.assetid: f2146651-e24a-4e24-ade8-8ddee8ff4e43
author: TerryGLee
ms.author: tglee
manager: jmartens
---
# Install Dotfuscator Community

::: moniker range="vs-2019"

Dotfuscator Community has been included, free of charge, with Visual Studio since Visual Studio .NET 2003.
This page details how to obtain Dotfuscator Community 6, so that you can begin protecting your application.

If you were previously using Dotfuscator Community 5, please see [Upgrading from Community 5][upgrade] instead of these instructions.

> [!NOTE]
> In addition to the versions of Dotfuscator Community shipped with releases of Visual Studio,
> PreEmptive Solutions also periodically provides updated versions on its website.
> If you want to download the **latest version** directly instead of installing from Visual Studio,
> **[click here to go to the Dotfuscator Downloads page][download]**.

## Within Visual Studio

You can install Dotfuscator Community from the Visual Studio IDE:

1. Ensure that Visual Studio is up-to-date.
   For details, see [Update Visual Studio][vs-update].

2. In Visual Studio's **Search Box** (Ctrl+Q), type `dotfuscator`.

   [![](media/install_in_vs19_12.png)](media/install_in_vs19_12.png)

3. In the search results shown, under the *Components* heading, select **Install PreEmptive Protection - Dotfuscator**.

   * If you instead see, under the *Menus* heading, **PreEmptive Protection - Dotfuscator Community**, then Dotfuscator Community is already installed. Select that option to [get started][get-started].

4. A Visual Studio Installer window will launch, pre-configured to install Dotfuscator Community.

   > [!NOTE]
   > You may be required to provide administrator credentials to continue.

   [![](media/install_in_vs19_34.png)](media/install_in_vs19_34.png)

5. In the Visual Studio Installer window, click *Install*.

Once the installation is complete, you can [start using Dotfuscator Community][get-started].

## During Visual Studio Installation

If you have not yet installed Visual Studio, you can obtain the installer from [the Visual Studio website][vs-install].
When run, it will display installation options for the selected Visual Studio edition:

[![](media/install_ui.png)](media/install_ui.png)

You can then install Dotfuscator Community as an individual component of Visual Studio:

1. Select the **Individual components** tab.

2. Under *Code tools*, check the *PreEmptive Protection - Dotfuscator* item.

  [![](media/install_individually_12.png)](media/install_individually_12.png)

3. The *Summary* panel displays *PreEmptive Protection - Dotfuscator* under the *Individual Components* section.

  [![](media/install_individually_3.png)](media/install_individually_3.png)

4. Configure any further installation settings as appropriate for your environment.

5. When ready to install Visual Studio, click the *Install* button.

Once the installation is complete, you can [start using Dotfuscator Community][get-started].

## See also

[This topic in the full Dotfuscator Community User Guide](https://www.preemptive.com/dotfuscator/ce/docs/help/)

::: moniker-end

::: moniker range="vs-2017"

Visual Studio 2017 ships with Dotfuscator Community 5, but it is also compatible with Dotfuscator Community 6.
PreEmptive, the makers of Dotfuscator, strongly recommend using version 6.

To install Dotfuscator Community 6 into Visual Studio 2017, go to the [Dotfuscator Downloads][download] page and select the appropriate link for Visual Studio 2017.
After you have downloaded the `.vsix` file, run it and follow the prompts to install Dotfuscator into Visual Studio.

::: moniker-end

<!-- Copyright © 2021 PreEmptive Solutions, LLC -->

[upgrade]: upgrade_from_5.md

[vs-install]:  https://visualstudio.microsoft.com/downloads/
[vs-update]:    /visualstudio/install/update-visual-studio
[get-started]:  https://www.preemptive.com/dotfuscator/ce/docs/help/gui_getstarted.html

[download]:  https://www.preemptive.com/products/dotfuscator/downloads

[full]:  https://www.preemptive.com/dotfuscator/ce/docs/help/intro_install.html
