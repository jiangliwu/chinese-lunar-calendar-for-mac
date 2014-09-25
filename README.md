# Chinese Lunar Calendar for Mac
This is a MenuExtra app which shows a simple chinese lunar calendar.

You can use CMD+Drag to move the location of this item.

## Code Structure
there are three projects in this application.

### 1. CLCLauncher
this application is a agent application, which launch "MenuCracker.menu" & "CLCMenuExtra.menu"

It dependens on MenuCracker.menu and CLCMenuExtra.menu (these two bundles will be packed into CLCLauncher.app as resources)

### 2. CLCMenuExtra
This bundle finishs the actual functionality.
this bundle is using un-official NSMenuExtra API.

### 3. CLCStatusItem
This application has the same functionality with CLCMenuExtra, but it's using official NSStatusItem API. This means its location can't be changed with CMD+Drag.

## Simple Demo for MenuExtra
You can use branch "MenuExtraDemo" to learn how to develop menuExtra app.
It's a early stage of CLC.
Branch Link: [MenuExtraDemo](https://github.com/zfdang/chinese-lunar-calendar-for-mac/tree/menuextrademo)

## Referrences
http://duhanebel.wordpress.com/2010/04/02/nsmenuextra-how-to-work-with-undocumented-apis/
https://github.com/aschuch/AXStatusItemPopup
http://sourceforge.net/projects/menucracker/

