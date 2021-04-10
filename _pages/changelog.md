---
layout: page
title: What's New
include_in_header: true
---

# Changelog
<br>

### `Latest`
# **2021.1**
`April 10, 2021`

- 🎈Tags - a new way to organize things in Anybuffer, available for Pro users.
- 🎈Tagging in Import Actions
- 🎈Face ID - Secure access to Anybuffer.
- 🎈Set Default Shelf to open on Anybuffer launch
- 🎈Opt-In to Reader Mode for Links opened in Anybuffer
- 🎈New Shelf Icons
- 🎈Show Item Count for each Shelf in the sidebar
- 🎈Edit URL for links saved in Anybuffer
- 🎈Copy as Text action for text items saved in Anybuffer
- 🎈Enter Selection Mode from Shelf context menu
- 🎈Copy Shelf URL from Shelf context menu
- ⚙️ Significant VoiceOver Improvements
- ⚙️ Stable sorting by name, size, and kind
- ⚙️ Anybuffer logo for empty shelf is now dimmed
- ⚙️ Family Sharing for in-app purchases
- 🐛 Items added through the share sheet may not appear in the search
- 🐛 Icons in Smart Shelf filters are correctly tinted

Besides new features and small bug fixes in this release of Anybuffer we've fixed a syncing bug that affected a small number of users. These users shall see items that were not syncing before in the Inbox. There was no data loss, but a UI problem - Anybuffer wasn't showing some of the items synced from another device.


# **2020.15**
`November 16, 2020`

🥳🎉🎈**Anybuffer for macOS release**🎈🎉🥳

- 🎈Info pane now can be pinned to the right side on iPadOS, which is handy when combined with keyboard navigation.
- 🎈Compact layout for Anybuffer keyboard
- 🎈Choose shelves to show in Anybuffer keyboard
- 🎈New parameters in “Get Items Info” Shortcut: Fetch limit and item Kind filter.
- 🎈Rich menus support for Shortcuts. Anybuffer items will appear in Shortcuts dialogs with image, title and subtitle.
- 🎈 URL Scheme. Refer to https://anybuffer.ameba.co/faq/ for more info.
- ⚙️ Search and Smart Shelf filter for Kind:Video now includes more video formats.
- ⚙️ Keyboard arrows navigation on iPadOS
- 🐛 Low-quality Inbox and Trash icons. Existing Anybuffer users should update the icon manually from Edit menu.
- 🐛 The sorting state would not change or save.
- 🐛 A couple of crashes in the app's internals
- 🐛 Scanning from Widget improvements

# **2020.11-13**
`September 26, 2020`
- 🎈Improved GIF Support, GIF is available as a separate type you can use in Search and Smart Shelves.
- 🎈If “Auto Add from Clipboard” is enabled and Anybuffer opened on a Smart Shelf the item will be pasted to the Inbox
- 🎈Compressed URLs appear as text files
- 🐛 Keyboard showing preview only for text items. Don’t forget to “Allow Full Access” for Anybuffer’ keyboard.
- 🐛 Paste from Widget doesn’t work in some cases
- 🐛 Compressing all items in a shelf may create an empty archive
- 🐛 Shelves stay collapsed on iPhone and in compact mode on iPad
- 🐛 Smart Shelf can be created from Search without Anybuffer Pro
- 🐛 Seamingly random crash when opening Anybuffer after adding items with Share Sheet

# **2020.10**
`September 19, 2020`

- 🎈iOS 14 look and feel, including updated sidebar and dropdown menus
- 🎈Items can be marked as “Favorite” for later use in search and Smart Shelves
- 🎈Custom app icons, Pride icon
- 🎈Set custom font for text items thumbnails
- 🎈Opt-In one tap Share extension
- 🎈Open Shelf Widget. Opens Anybuffer on selected shelf.
- 🎈Recent Items Widget.  Opens Anybuffer and highlights selected item.
- 🎈Quick Actions. Opens Anybuffer with selected action.
- 🎈Experimental Files app integration
- 🎈 Improved scroll performance in shelves with many(>50) items 
- 🐛 When “Auto-add from Clipboard” enabled Anybuffer will read the clipboard while alive in background. New behavior - Anybuffer reads clipboard only when on screen.
- 🐛 Smart shelf settings screen follws app’s accent color

# **2020.9**
`July 9, 2020`

- 🎈Smart shelf can filter by multiple text terms, i.e. show items with text “AAA” or text “BBB”. Terms should be separated by comma - AAA,BBB
- 🎈Full URL preview in item’s details
- 🎈Add file to Shelf shortcut
- 🎈App icon clipping

# **2020.8**
`June 14, 2020`
 
- 🎈Shelf icons can be colored, tint color available on shelf create/edit view. Shelf icon tint color can be set from an external app, like Pastel
- 🎈External PNG image can be used as a shelf icon. In shelf create/edit view use folder icon to open Files or just drop an image on the view
- 🎈Icon and name for Inbox and trash can be edited
- 🎈Drag and drop to reorder shelves
- 🎈Items organized according to its Kind and showed categorically, when sort by “Kind” is selected
- 🎈Select All from shelf’s contextual menu
- 🎈Select All keyboard shortcut CMD+A
- 🎈Multi-select with pointer - click and drag around to select items
- 🎈CMD+Pointer click to start multi-select 
- 🎈Shift+Pointer click to multi-select range of items
- 🎈6 colors app icon
- 🎈Filter by “Date Added” in search. Long press on search icon or type in key tokens( last:hour, last:day, last:week and last:month)
- 🎈One-Tap on Item to Copy. Tap on an item in Anybuffer copies it to Clipboard instead of opening it. 
- 🎈Open Links in Safari. Tap on a link opens it in Safari, instead of the in-app browser.
- 🎈"Open in Safari" contextual menu option
- ⚙️ Reworked dark theme
- ⚙️ Search token for a shelf includes shelf icon
- ⚙️ Removed headers in settings
- ⚙️ Settings layout
- ⚙️ Item counts in filter view fit more than 2 digits
- ⚙️ Added additional padding for sidebar buttons for devices without FaceID
- ⚙️ Keyboard shortcuts now correctly handle multi-selection (i.e. select multiple items and press CMD+C)
- ⚙️ “Action on Tap” setting changed from toggle to explicit selector between “Preview” and “Copy”
- ⚙️ Apple's universal links (Books, App Store, TestFlight, Music) forced to open in Anybuffer 
- ⚙️ Smoother animation for Search
- ⚙️  Better fallback for URL thumbnails for websites without proper metadata
- 🐛 Search details label clips on shelf icon in some cases
- 🐛 Auto-paste from clipboard can add duplicate items in rare cases
- 🐛 Keyboard may not show up in Anybuffer share extension on iPhone

# **2020.7**
`May 11, 2020`

- ⚙️ Improved Today Widget clipboard preview
- ⚙️ Improved text indexing and search performance
- 🐛 Fixed: Filter button clips on iPhone SE in some cases

# **2020.6**
`May 3, 2020`

- 🎈Today Widget. Preview clipboard contents, add it to Anybuffer in one tap.
- 🎈Better Text Search. Text items content and URLs are searchable now. Before this version only item name was considered.
- 🎈Search only in selected shelves, available trough shelf's contextual menu or using operator in:<shelf name>.
- 🎈Create Smart Shelf from Search. Press plus in accessory view, or use CMD+N keyboard shortcut.
- 🎈Spotlight. Search for Anybuffer items from iOS Spotlight.
- ⚙️ Keyboard shortcuts to cycle through shelves: CTRL+TAB and CTRL+SHIFT+TAB. Old CMD+] and CMD+[ will continue to work.
- ⚙️ Improved layout for iPad 9.7, and Slide Over in vertical orientation.
- ⚙️ Deleting Smart shelf should not delete it contents. 
- ⚙️ Items in Trash should not appear in search results.
- ⚙️ New item kind icons in Filter view.
- 🐛 Setting custom name for an item through share sheet may corrupt the item.
- 🐛 Narrow sidebar shows and clips shelf name in some cases.

# **2020.5**
`Apr 24, 2020`

- 🎈Wide Sidebar. See shelves names in a wider sidebar on iPad, enable in Settings -> Nitpicky Details.
- 🎈Custom Keyboard. Access Anybuffer items where you need it: Messages, Twitter, Safari, anywhere.
- 🎈New Gestures. Swipe left or right with one finger on the screen or with two fingers on the trackpad to switch between shelves. Swipe from the left edge to reveal sidebar.
- 🎈Search Improvements. Long press on the search icon to access search presets.
- ⚙️ Added context menu to Add Shelf button
- ⚙️ Replaced smart shelf indicator in the sidebar
- ⚙️ Added FAQ link to settings
- ⚙️ Added shelves icons and item kind icons in Smart Shelf view
- ⚙️ Reduced memory consumption
- ⚙️ Moved custom icon selection to theme screen
- ⚙️ Changed sidebar toggle button image
- ⚙️ Changed search image icon
- ⚙️ iPad pointer will snap to buttons on the item details screen
- ⚙️ More consistent items size between different window sizes and devices 
- 🐛 A couple of nasty crashes
- 🐛 Shelves order in Smart Shelf view
- 🐛 Sharing from Youtube app to Anybuffer
- 🐛 Pull down to search show search on all active windows on iPad
- 🐛 Quicklook from search results dismisses search view
- 🐛 Auto-add from clipboard can add duplicate items in some cases
- 🐛 Typos, caused by app localization

# **2020.4**
`Apr 13, 2020`

- 🎈Revamped Search. New Search allows you quickly find items by kind and name. Now you can use contextual menu in search results. Pull down or use the shortcut to invoke Search.
- 🎈Pointer support on iPadOS. First class support of the newest iPadOS feature.
- ⚙️ Improved Share Extension. Clean design, improved data handling.
- ⚙️ Optional Tip Jar. Toss a coin to your app developer! 
- 🐛Fixed: Shared iOS screenshot doesn't appear in Anybuffer

# **2020.3**
`Apr 7, 2020`

- 🎈Added Simplified Chinese language support
- 🎈Added Russian language support

# **2020.2**
`Mar 7, 2020`

- 🐛Fixed wrong item thumbnail
- 🐛Fixed occasional wrong state for clipboard button

# **2020.1**
`Feb 15, 2020`

**New Features in Anybuffer 2020.1**:

- 🎈Smart Shelves .Browse items based on configured search criteria - item shelf, type, name or date added.
- 🎈Sketching Mode. Quickly sketch an idea and save image to Anybuffer, available in Add Menu "+"
- 🎈Edit Text. Modify text items without leaving the app, tap edit from item contextual menu

**Improvements**:
- ⚙️ Tap on sorting control second time to switch between ascending and descending
- ⚙️ New icons in the Settings screen
- ⚙️ Contextual menu now smarter about available options, i.e. "Compress All" only available if shelf contains items
- ⚙️ Share Extension better handles shares from Files app
- ⚙️ Share Extension activates in more cases and support more apps
- ⚙️ Anybuffer will occasionally ask for review
- ⚙️ Improved name detection for items added with drag & drop

**Bug fixes**:
- 🐛Item borders don't update with theme switches
- 🐛In dark theme, white line appears on the left side, when sidebar collapsed
- 🐛 Show\Hide sidebar chevron has wrong orientation in some cases
- 🐛 Navigation bar mismatch current theme in some cases

# **2.1.1**
`Dec 29, 2019`
- 🐛Fixed crash when select Inbox on the first launch in some cases

# **2.1**
`Nov 25, 2019`

**New Features in Anybuffer 2.1:**
- 🎈Contextual Menus for Filter. Long press Filter item to show contextual menu.
- 🎈Compress. Compress one or more items. Available in Item's, Shelf's and Filter's contextual menu.
- ⚙️ Nitpicky Settings:
  - Items View Header. Set default control in the header - Sorting or Filter.
  - Small Thumbnails. Optionally show more items on iPhone and in compact layout on iPad.
  - Text Size. Choose font size you like for text item's thumbnail.
  
# **2.0**
`Nov 6, 2019`

**New Features in Anybuffer 2.0:**
- Completely new design, feels at home on iOS and works better on iPhone
- Multiple Windows on iPad OS
- Dark Mode
- Powerful Siri Shortcuts
- Context Menus (tap and hold on items or shelves)
- New multitasking select gesture, swipe with two fingers to select multiple items
- New Cards UI, looks and works great om iPad
- New Quick Look feature adds edit function for images and PDFs
- Scan documents with your camera
- Better Thumbnails
- In-app Search 
- Sort items by name, date, size or kind
- Great keyboard shortcuts support

**Improvements:**
- iCloud sync reliability improvements
- Better default item name when adding from clipboard and share extension
- Lot's of under the hood changes make this release much more stable and reliable


**What's next:**
- Integration with iOS Files  to be release in 2019
- Biometric


# **1.1.1**
`Dec 8, 2018`

A couple of nasty bugs were introduced in the previous release... :(

Fixing it as soon as I can:
- 🐛Item removal may cause a crash
- 🐛Dark theme glitches

# **1.1**
`Nov 27, 2018`

- 🎈Support for new iPad Pro: new screen sizes and Face ID
- 🎈Clipboard history mode: add items from clipboard automatically
- 🎈Shortcuts app integration
- ⚙️Item representations view respects applied filter

# **1.0.8**
`Sep 8, 2018`

- ⚙️More reliable filter counts
- ⚙️Improved Sharing with other apps

# **1.0.7** 
`Aug 28, 2018`

🐛Share sheet bug fixes

# **1.0.6**
`Aug 23, 2018`

⚙️Improved sharing compatibility with Evernote and AirDrop

# **1.0.5**
`Jul 16, 2018`

New features:
- ⚙️Greatly enhanced keyboard support, now you can navigate items and perform quick actions without touching the screen!
- 🎈New Copy and Share actions in Action Drawer, quickly copy or share one or several items with Drag&Drop
- 🎈Restrict access to Anybuffer with Touch\Face ID

Fixes:
- 🐛Copy\Paste preserves item name
- 🐛Performance improvements for large number of items
- 🐛Fixed a few typos

# **1.0.4**
`Mar 28, 2018`

New & Improved:
- 🎈Item re-order using drag & drop
- 🎈Custom Keyboard for quicker access to your items, right where you need them
- 🎈Extract files from Zip archives: drop archive on Action Drawer(can be enabled in settings) to unarchive

Fixes:
- 🐛UI may stagger during iCloud synchronization

# **1.0.3**
`Mar 20, 2018`

New & Improved:
- ⚙️iOS system search now can find items in Anybuffer
- ⚙️Improved preview for some data types
- ⚙️Improved reliability of the Share Extension
- ⚙️Optimized storage and traffic usage

Fixes:
- 🐛Adding EPUB, Pages and Numbers from Files fails
- 🐛Some alert dialogs are not readable using black theme

# **1.0.2**
`Mar 6, 2018`
🐛Fixed a crash introduced in last release.

# **1.0.1**
`Mar 5, 2018`

New:
- 🎈Dark Theme
- 🎈Smart web-url handling for App Store and Instagram, custom preview and image extraction
- ⚙️Option to disable Action Drawer(drop area which replace filters during drag)
- ⚙️Better drag animation and item preview
- ⚙️Better support for different data types
- 🎈New shelf icons

Fixes:
- 🐛iCloud settings switch false-positive state
- 🐛App Icon not changing on iPad

# **1.0**
`Feb 27, 2018`

Initial release.
