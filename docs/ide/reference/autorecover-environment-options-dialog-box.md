---
title: AutoRecover, Environment, Options Dialog Box
ms.date: 11/04/2016
ms.prod: visual-studio-dev15
ms.technology: vs-ide-general
ms.topic: reference
f1_keywords:
  - "VS.DialogAutoRestore"
  - "VS.ToolsOptionsPages.Environment.AutoRecover"
  - "VS.ToolsOptionsPages.Environment.Auto_Save_and_Restore"
helpviewer_keywords:
  - "files, recovering"
  - "AutoRecover page"
  - "saving files, automatically"
  - "files, saving automatically"
ms.assetid: 397e5e44-4bbe-4289-94d1-642b466c9111
author: gewarren
ms.author: gewarren
manager: douge
ms.workload:
  - "multiple"
---
# AutoRecover, Environment, Options dialog box

Use this page in the **Options** dialog box to specify whether to automatically back up files or not. This page also lets you specify if you want to restore modified files if Visual Studio shuts down unexpectedly.

Access this dialog box by selecting the **Tools** menu, selecting **Options**, and then selecting **Environment** > **AutoRecover**. If this page doesn't appear in the list, select **Show all setting** in the **Options** dialog box.

> [!NOTE]
> The dialog boxes and menu commands you see might differ from those described in Help depending on your active settings or edition. To change your settings, choose **Import and Export Settings** on the **Tools** menu. For more information, see [Personalize the Visual Studio IDE](../../ide/personalizing-the-visual-studio-ide.md).

**Save AutoRecover information every [n] minutes**

Use this option to customize how often a file is automatically saved in the editor. For previously saved files, a copy of the file is saved in *%USERPROFILE%\Documents\Visual Studio \<version>\Backup Files\\<projectname>*. If the file is new and you haven't saved it yet, the file is autosaved using a randomly generated file name.

**Keep AutoRecover information for [n] days**

Use this option to specify how long Visual Studio keeps files created for autorecovery.

## See also

- [Options Dialog Box](../../ide/reference/options-dialog-box-visual-studio.md)