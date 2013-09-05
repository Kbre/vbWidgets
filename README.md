vbWidgets
=========

Cairo-based Replacements for the CommonControls, based on the vbRichClient-Framework (www.vbRichClient.com). 
There you'll find all the needed information with demos and tutorials.

***
##List of VB6 Controls and the vbWidgets equivalent or replacement
  
###Basic Controls
* PictureBox	
* Label --> cwLabel
* TextBox --> cwTextBox
* Frame --> cwFrame
* CommandButton --> cwButton
* CheckBox --> cwButton - with ButtonStyle property set as CheckBox
* OptionButton --> cwButton - with ButtonStyle property set as OptionBox
* ComboBox --> cwDropDownList
* ListBox --> cwVList - is a generic and flexible widget, the developer has to do some encapsulation code
* HScrollBar --> cwHScrollBar
* VScrollBar --> cwVScrollBar
* Timer --> cTimer - not a widget, included in vbRichClient.dll
* DriveListBox
* DirListBox --> cwDirList - based on cwTree
* FileListBox --> cwFileList - based on cwTree
* Shape
* Line
* Image --> cwImage - also supports SVG format!
* Data
* OLE

###Common Controls
* TabStrip
* ToolBar --> cwToolBar (cwToolBarItem)
* StatusBar --> cwStatusBar
* ProgressBar --> cwProgressBar
* TreeView --> cwTree
* ListView
* ImageList --> cImageList - not a widget, included in vbRichClient.dll
* Slider
* ImageCombo 
* Animation
* UpDown --> cwUpDown
* MonthView
* DTPicker
* FlatScrollBar
* CoolBar

###Other MS Controls
* MSComm
* MSHFlexGrid
* Winsock --> cUDP, cTCPClient, cTCPServer - not widgets, included in vbRichClient.dll
* RichTextBox
* MSFlexGrid --> cwGrid
* CommonDialog --> cFSO.ShowOpenDialog, cFSO.ShowSaveDialog - not widgets, included in vbRichClient.dll

## Other Widgets
* cwAccordeon (cwAccordeonEntry)
* cwBrowser
* cwDropDown - Serves as a generic container to achieve "Combo-like DropDowns" with any Widget you want to drop
* cwFormButtons - Under construction?
* cwGlowButton
* cwMDIMock
* cwMenu (cwMenuItem) - Used to make popup menus
* cwMenuBar (cwMenuBarItem) - Replaces the menu bar of the VB6 Forms, enhanced with icon-images and option-check support
* cwResizer - Allows dragging of the separator between two panels in LayoutView
* cwRibbon (cwRibbonEntry)
* cwScoringLabel
