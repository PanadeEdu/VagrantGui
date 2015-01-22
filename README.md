# VagrantGui - A Simple Vagrant Control Tool

## Introduction

VagrantGui is Designed to be a Simple Control for Vagrant Virtual Machines on Windows.
It is written in C# with Visual Studio 2013 and the Code is Licensed under GPLv3.
For further informations about the Licensing, read the LICENSE.md File.

The Sourcecode can be found here: https://github.com/PanadeEdu/VagrantGui_src

## Installation

The VagrantGui is a Standalone Executable, which means you can put and execute it everwhere.
However it is Recommendet to put the VagrantGui.exe in the same Folder as your VagrantFile.
It will now choose the Folder on Default and you can Simply name a Shortcut on your Desktop.

## Usage

VagrantGui requires Administrative Rights, because some VirtualBox Configurations require Administrative Rights.

After start, you will be presented with a Simple Interface:

- Blue Area: Console Output Textbox
- Restart, Start, Suspend and Stop Buttons for your Vagrant VM
- Browse Folders: Required when your VagrantFile is located elsewhere as the Executable of VagrantGui
- Destroy: Will Promt a Confirmation Window and ask if you realy want to Destro your Vagrant VM