---
title: Dotfuscator Community
ms.date: 04/30/2021
ms.devlang: dotnet
ms.topic: overview
keywords: Dotfuscator, Dotfuscator CE, Dotfuscator Community, PreEmptive, PreEmptive Solutions, PreEmptive Protection, protection, community edition, obfuscation, .NET, free, Visual Studio 2019, Visual Studio 2017, Visual Studio
helpviewer_keywords:
- PreEmptive Protection Dotfuscator
- Dotfuscator Community Edition
- Dotfuscator CE
- Dotfuscator Community
- Dotfuscator
- obfuscation
- protection
description: Learn how you can protect your .NET applications with the free copy of Dotfuscator Community included in Visual Studio.
ms.assetid: d9550502-0a82-49a6-b005-2caa791fbe02
author: TerryGLee
ms.author: tglee
manager: jmartens
---
# Dotfuscator Community

***PreEmptive Protection - Dotfuscator Community*** (formerly *Dotfuscator CE*) provides comprehensive .NET application protection that easily fits into your secure software development lifecycle. 
Use it to harden, protect, and prune desktop, mobile, server, and embedded applications to help secure trade secrets and other intellectual property (IP), reduce piracy and counterfeiting, and protect against tampering and unauthorized debugging.
Dotfuscator works on compiled assemblies without the need for additional programming or even access to source code.

![PreEmptive Protection - Dotfuscator](media/header.svg)

## Why protection matters

It's important to **protect your intellectual property** (IP).
Your application's code contains design and implementation details which can be considered IP.
However, applications built on .NET [contain significant metadata and high-level intermediate code][assemblies], making them easy to reverse engineer, just by using one of many free, automated tools.
By disrupting and stopping reverse-engineering, you can prevent unauthorized IP disclosure, as well as demonstrate that your code contains trade secrets.
Dotfuscator can [obfuscate][obfuscation] your .NET assemblies to hinder reverse-engineering, while maintaining original application behavior.

It's also important to **protect the integrity of your application**.
In addition to reverse-engineering, bad actors may attempt to pirate your application, alter the application's behavior at run time, or manipulate data.
Dotfuscator can inject your application with the capability to [detect and respond to unauthorized uses][checks], including tampering, third-party debugging, and rooted devices.

For more information on how Dotfuscator fits into a secure software development lifecycle, see our [SDL App Protection page][sdl-protection].

## About Dotfuscator Community

Your copy of Microsoft Visual Studio includes a free license for ***PreEmptive Protection - Dotfuscator Community***.
For instructions on how to install the version of Dotfuscator Community included with Visual Studio, see the [Installation page][install].
Please note that these instructions apply only to Visual Studio versions 2017 and later, as previous versions were installed with Dotfuscator Community by default.

Dotfuscator Community offers a range of [software protection and hardening][software-protection] services for developers, architects and testers. 
Examples of [.NET Obfuscation][obfuscation] and other [Application Protection][app-protection] features included in Dotfuscator Community are:

* *[Renaming][renaming]* of identifiers to make reverse-engineering of the compiled assemblies more difficult.
* *[Anti-tamper][tamper]* to detect and respond with pre-defined behaviors or with custom logic to the execution of tampered applications.
* *[Anti-debug][debug]* to detect and respond with pre-defined behaviors or with custom logic to the attachment of a debugger to a running application.
* *[Anti-rooted device][root]* to detect and respond with pre-defined behaviors or with custom logic if the application is running on a rooted Android device.
* *[Application expiration behaviors][shelflife]* that encode an "end-of-life" date, and then detect and respond with pre-defined behaviors or with custom logic when applications are executed after their expiration date.

For details on these features, including how they fit into your application protection strategy, see the [Capabilities page][capabilities].

Dotfuscator Community offers basic protection out-of-the-box, and you can unlock additional features once [registered][register].
Even more application protection measures are available to users of *PreEmptive Protection - Dotfuscator* Professional, the world's leading [.NET Obfuscator][net-obfuscator].
For information, see [Upgrading to Professional][upgrades].

## Getting started

::: moniker range="vs-2019"

To begin using Dotfuscator Community from Visual Studio, type `dotfuscator` into the search box (**Ctrl**+**Q**).

::: moniker-end

::: moniker range="vs-2017"

To begin using Dotfuscator Community from Visual Studio, type `dotfuscator` into the *Quick Launch* (**Ctrl**+**Q**) search box.

::: moniker-end

* If Dotfuscator Community is already installed, this will bring up the *Menu* option to start the Dotfuscator Community user interface. See [Getting Started][getstarted] in the Dotfuscator Community user guide.

* If Dotfuscator Community is not yet installed, this will bring up the relevant *Install* option. See [Installation][install].

  > [!TIP]
  > In addition to the versions of Dotfuscator available in Visual Studio, you can always get the latest version of Dotfuscator Community from **[Dotfuscator Downloads][download]**.

## Full documentation

This page and its subpages provide a high-level overview of Dotfuscator Community's features, as well as [instructions for installing the tool][install].

See [the full Dotfuscator Community User Guide at preemptive.com][full] for detailed usage instructions, including [how to start using the Dotfuscator Community user interface][getstarted].

<!-- Copyright © 2021 PreEmptive Solutions, LLC -->

[assemblies]:  /dotnet/standard/assembly-format
[software-protection]:  https://www.preemptive.com/software-protection
[obfuscation]:  https://www.preemptive.com/obfuscation
[app-protection]:  https://www.preemptive.com/application-protection
[sdl-protection]:  https://www.preemptive.com/solutions/SDL-App-Protection
[net-obfuscator]:  https://www.preemptive.com/products/dotfuscator/overview
[download]:  https://www.preemptive.com/products/dotfuscator/downloads

[install]:  install.md
[capabilities]:  capabilities.md
[register]: register.md
[upgrades]:  upgrades.md

[getstarted]:  https://www.preemptive.com/dotfuscator/ce/docs/help/gui_getstarted.html

[renaming]:  https://www.preemptive.com/dotfuscator/ce/docs/help/obfuscation_renaming.html

[checks]:  https://www.preemptive.com/dotfuscator/ce/docs/help/checks_overview.html
[tamper]:  https://www.preemptive.com/dotfuscator/ce/docs/help/checks_tamper.html
[debug]:  https://www.preemptive.com/dotfuscator/ce/docs/help/checks_debug.html
[root]: https://www.preemptive.com/dotfuscator/ce/docs/help/checks_root.html
[shelflife]:  https://www.preemptive.com/dotfuscator/ce/docs/help/checks_shelflife.html

[full]:  https://www.preemptive.com/dotfuscator/ce/docs/help/index.html
