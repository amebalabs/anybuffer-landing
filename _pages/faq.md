---
layout: page
title: FAQ
include_in_header: true
---

# Frequently Asked Questions

## **Managing Items**

### Q: How can I add stuff to Anybuffer?
**A:** There are quite a few ways to add things to Anybuffer, covering the wide variety of use cases:

* Main app
  * Paste from clipboard
    * Press the Paste button
    * Keyboard shortcut CMD+V
    * Automatically (enable in settings)
  * From Add Menu
    * Add from Photos
    * Add from Files
    * Scan Documents
    * Create a Sketch
  * iPad only: Drag&Drop from other apps
* Share Extension
* Today Widget
* Shortcuts app

### Q: I've enabled Auto Add from Clipboard in Settings, but it's not working?
**A:** Anybuffer can't autosave your clipboard if it is in the background, this is a limitation of iOS. This means that on iPhone you have to switch to Anybuffer to trigger auto add, on iPad the easiest way is to keep Anybuffer in Slide Over.

### Q: I can't add images to rich text document form custom keyboard, is it broken?
**A:** When you tap on a text or URL item in custom keyboard it directly added to the text document, when you tap on any other kind of item (image, pdf, etc.) it is copied to the clipboard, you should paste it manually. This is iOS limitation.

### Q: Can I see shelf's name in the sidebar?
**A:** Yes, but only on iPad. Got to Settings -> Nitpicky Details and enable Wide Sidebar.

### Q: What does the selector with Name, Date, Size, and Kind do?
**A:** This is item sorting option. Tapping on selected option repeatedly alternates between ascending and descending modes. Sorting is saved for each shelf independently.

### Q: Most of the times I use the filter and rarely sorting, can I switch the default?
**A:** Yes. Got to Settings -> Nitpicky Details and choose default control.


### Q: I've emptied the trash, now my items are gone, can I restore it?
**A:** No. Item deleted from trash are gone forever, there is no undo.

## **Search and Smart Shelf**

### Q: How can I invoke Search?
**A:** There are a couple of ways to invoke Search:

* Pull down the item list (like pull to refresh)
* Tap on magnifying glass icon in the sidebar
* Long press on magnifying glass icon in the sidebar to access Search Presets
* CMD+F keyboard shortcut
* Long press on a shelf to invoke search in the shelf's scope
* ALT+CMD+F keyboard shortcut to invoke search in the current shelf's scope

### Q: What is a Smart Shelf?
**A:** Smart Shelf is a Shelf based on the saved search query. Items can't be added to the smart shelf directly. If you delete an item from the smart shelf - it will be moved to trash, deleting Smart Shelf itself doesn't affect items.

### Q: Can I create Smart Shelf from Search?
**A:** Yes. Tap + button on the panel on top of the keyboard or use CMD+N keyboard shortcut.

### Q: I can't find items in Trash, is this by design?
**A:** Yes. Items in the trash are excluded from search results and Smart Shelves.

### Q: Can I limit the search for items of certain types?
**A:** Yes. Either choose item kind in a panel on top of keyboard or type in an operator. Currently supported operators:

* kind:pdf
* kind:image
* kind:url
* kind:archive
* kind:text
* kind:audio
* kind:video

## **Sync**

### Q: How does syncing work? Is there a third-party server involved?
**A:** Syncing work using Apple iCloud, your data is saved on Apple's servers in addition to a local copy

### Q: Can I disable syncing?
**A:** Yes. in iOS, Settings go to iCloud settings and disable it for Anybuffer.

### Q: My items are not showing up on the second/third/etc. device, can I force the sync?
**A:** No. Pretty much like apple apps (Notes, for example) syncing just works (until it doesn't). Anybuffer relies on iOS technologies for background sync, in ideal case your devices should be in sync all the time. Initial sync can be long, give it some time.

### Q: Can I see the sync status?
**A:** No, not yet.

### Q: Why items in Trash are syncing?
**A:** Why not? :) Maybe the item was deleted by mistake and you want to restore it from another device. Delete the item from trash to remove it completely.


## **URL Scheme**

* **Invoke Search** anybuffer://search?query=[hour,day,week,image,gif,pdf,text,archive,url,audio,video]
* **Create Shelf** anybuffer://create?[smart=true]
* **Launch Scanner** anybuffer://scan
* **Launch Sketch** anybuffer://sketch
* **Add File** anybuffer://addfile
* **Add Photo** anybuffer://addphoto
