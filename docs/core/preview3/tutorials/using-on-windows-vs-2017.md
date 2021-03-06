---
title: "Introdução ao .NET Core no Windows usando o Visual Studio 2017"
description: "Introdução ao .NET Core no Windows usando o Visual Studio 2017"
keywords: .NET, .NET Core
author: bleroy
ms.author: mairaw
ms.date: 11/16/2016
ms.topic: article
ms.prod: .net-core
ms.devlang: dotnet
ms.assetid: d743134a-08a3-4ff6-aab7-49f71f0568c3
translationtype: Human Translation
ms.sourcegitcommit: 71eab6216e116b99927dfeaa8ce3cf70bcc08a5e
ms.openlocfilehash: 4437f44523bcc4e8517de5b6be42a63439f817d7

---

# <a name="getting-started-with-net-core-on-windows-using-visual-studio-2017"></a>Introdução ao .NET Core no Windows usando o Visual Studio 2017

por [Bertrand Le Roy](https://github.com/bleroy) e [Phillip Carter](https://github.com/cartermp)

O Visual Studio 2017 fornece um ambiente de desenvolvimento completo para desenvolver aplicativos .NET Core. Os procedimentos deste documento descrevem as etapas necessárias para criar um aplicativo de console muito simples, usando o Visual Studio e o .NET Core.

## <a name="prerequisites"></a>Pré-requisitos

Siga as instruções na [nossa página de pré-requisitos](../windows-prerequisites.md) para atualizar seu ambiente.

## <a name="getting-started"></a>Guia de Introdução

As etapas a seguir definirão o Visual Studio 2017 para o desenvolvimento de aplicativos de console no .NET Core:

1. Abra o Visual Studio e, no menu **Arquivo**, escolha **Novo** e **Projeto**.

2. Na caixa de diálogo **Novo Projeto**, na lista **Modelos**, expanda o nó **Visual C#** e escolha **.NET Core**. Você verá quatro novos modelos de projeto para **Aplicativo de Console (.NET Core)**, **Projeto de Teste de Unidade (.NET Core)**, **Biblioteca de Classes (.NET Core)** e **Aplicativo Web do ASP.NET Core (.NET Core)**. Escolha **Aplicativo de Console (.NET Core)**, digite um nome para o projeto, escolha um local e clique em OK.

  ![Novo projeto: aplicativo de console](media/new-project-console-app.png)

3. O projeto resultante terá um único arquivo C# com uma saída "Hello World" no console.

  ![O projeto de aplicativo de console](media/console-app-solution.png)

É possível executar esse aplicativo no modo de depuração usando F5 ou no modo de versão usando CTRL+F5. Você também pode definir pontos de interrupção para interromper a execução, inspecionar variáveis ou começar a escrever códigos mais interessantes.

Boa codificação!

## <a name="what-to-do-next"></a>O que fazer em seguida

Após esta simples introdução, você provavelmente está se perguntando como criar soluções mais avançadas, com bibliotecas reutilizáveis e testes. O tópico [Compilar uma solução completa do .NET Core no Windows usando o Visual Studio 2017](using-on-windows-vs-2017-full-solution.md) lhe mostrará como fazê-lo.



<!--HONumber=Nov16_HO3-->


