iPhone, iPad and mac Clipboard store...can keep in sync across all devices

Privacy Policy  
This Privacy Policy explains what information AICopyPaste collects, why it collects it, and how it is handled. We have written this in plain English because we believe you deserve a clear and honest explanation, not legal boilerplate.  

1. Who we are  
AICopyPaste is developed and operated by Darren B Wilson  ("we", "us", "our"). If you have any questions about this policy, contact us at:  

darrenwilson23@icloud.com  

2. What we collect  
We collect only what is necessary to operate the clipboard strip feature. Nothing more.  

2.1  Clipboard content you explicitly save  
When you copy something and it appears in the AICopyPaste keyboard strip, that item is stored locally on your device. This includes text snippets, file references,   image thumbnails, and screen prints you have chosen to save. We do not automatically capture everything you copy — only items you deliberately save through the app or keyboard strip are retained.  

2.2  Comments and tags you add  
If you add a comment, label, or tag to a clipboard entry, that annotation is stored alongside the entry. It is used solely to support search and organisation features within the app.  

2.3  Sync data (optional)  
If you choose to enable iCloud sync, clipboard entries and their comments are synced across your devices via Apple's iCloud infrastructure. This is entirely opt-in and can be disabled at any time in Settings. When sync is off, no data leaves your device.

2.4  Crash reports (optional)  
If you have enabled diagnostic sharing in your iOS Settings, Apple may share anonymised crash logs with us. These contain no clipboard content, no keystrokes, and no personal identifiers.  

What we do NOT collect:    
  •  Keystrokes, passwords, or anything you type    
  •  Data from other apps on your device    
  •  Location, contacts, camera, or microphone data  
  •  Device identifiers used for advertising  
  •  Browsing history or app usage outside AICopyPaste  

3. Why we need Full Access  
iOS requires keyboard extensions to be granted "Full Access" by the user in order to:  
•	Read clipboard contents reliably across all apps  
•	Connect to the internet to sync your clipboard across devices (if enabled)  
•	Share data between the keyboard extension and the main AICopyPaste app  

Apple's standard Full Access warning states that the developer could transmit anything you type. This warning applies to all keyboards requesting this permission. We want to be unambiguous: we do not log, store, or transmit keystrokes. The Full Access permission is used solely for the three purposes listed above.  

4. How we store your data  
 - Storage type	        - Details  
 - On-device (default)	- All clipboard entries are stored in the app's private local storage on your iPhone or iPad. No data leaves your device unless you enable
                          iCloud sync.  
 - iCloud sync (opt-in)	- When enabled, entries sync via Apple's encrypted iCloud infrastructure. We do not operate our own sync servers.  
 - Retention	          - Clipboard entries remain until you delete them manually, clear all entries from the strip, or uninstall the app. We do not apply automatic
                          expiry by default.  
 - Encryption           - Data stored on-device is protected by iOS's standard data protection. iCloud data is encrypted in transit and at rest by Apple.  

6. Sharing your data  
We do not sell, rent, or share your clipboard data with any third party. The only circumstances in which data may be disclosed are:  
•	If required by Australian law or a valid legal order  
•	To Apple, as part of iCloud sync (governed by Apple's own Privacy Policy)  
•	To an anonymised crash reporting service, which receives no clipboard content  

7. Your rights  
You have the right to:  
•	Access all clipboard data stored by the app (it is visible to you in the app at all times)  
•	Delete individual entries or all entries at any time  
•	Disable iCloud sync at any time in the app's Settings  
•	Revoke Full Access at any time via iOS Settings > General > Keyboard > Keyboards  
•	Request deletion of any account or associated data by contacting us at darrenwilson23@icloud.com  

8. Children  
AICopyPaste is not directed at children under the age of 13. We do not knowingly collect data from children. If you believe a child has provided data through our app, please contact us and we will delete it promptly.  

9. Changes to this policy  
If we make material changes to this Privacy Policy, we will notify you via an in-app notice and update the effective date at the top of this document. Continued use of the app after the notice period constitutes acceptance of the updated policy.  


Feature List

Clipboard History  
• Automatic clipboard monitoring on macOS and iOS — copies are saved instantly  
• Manual save from the toolbar ("Save from Clipboard" button)  
• Supports all content types: plain text, URLs, images, files, and binary data  
• Automatic type detection and classification  
• Duplicate detection — the same content is never saved twice  
• Search across all items (text, URLs, filenames, comments, type identifiers)  
• Pin items to keep them permanently at the top of the list  
• Add and edit comments/annotations on any item  
• Swipe actions for quick pin and comment operations  
• Auto-delete old items (configurable: 7 / 14 / 30 / 90 / 180 / 365 days)  
• Configurable maximum item size (1 MB → 1 GB, or unlimited)  

Storage & Sync  
• Device storage — kept locally in an App Group container shared with the helper and extensions  
• iCloud storage — CloudKit sync across all your Apple devices  
• Promote individual device items to iCloud on demand  
• Switch storage location from Settings (requires restart)  
• Automatic migration from legacy storage location  

Link Previews  
• Automatic rich link preview fetching for URLs and text containing links  
• Persistent disk-based image cache with in-memory metadata cache (100 items)  
• Compact preview in list rows (title + thumbnail)  
• Full rich preview in context menu long-press  

Copy & Paste  
• One-tap copy any item back to clipboard  
• Context menu with Copy, Open URL, Save to Downloads, Pin, Add Comment, Send to iCloud, Delete  
• On macOS, file copies are delegated to the native helper for full file attachment support  
• Visual checkmark feedback on copy  

Mac Menu Bar Helper  
• Separate native macOS helper app that runs silently in the background  
• Menu bar icon with live badge count (caps at 99+)  
• Floating Clip Panel — resizable panel showing your most recent clips, accessible from the menu bar  
• Configurable number of recent clips shown (5–100)  
• Global keyboard shortcut ⌘⇧V to show/hide the Clip Panel from anywhere  
• Launch at Login support  

App Lock & Security  
• PIN lock (4–6 digits) stored securely in Keychain  
• Face ID / Touch ID biometric unlock with PIN fallback  
• Auto-locks when the app is backgrounded or inactive  
• PIN change and removal from Settings  

Data Import / Export  
• Export all clipboard items as a JSON file  
• Import from a previously exported JSON file (duplicates skipped automatically)  
• On macOS: saves directly to Downloads folder  
• On iOS: standard share sheet  

iOS Keyboard Extension  
• Custom keyboard giving direct access to your clipboard history from any app  
• Horizontally scrolling clip cards with thumbnails, URL previews, and comments  
• Type icons and domain extraction for URLs  
• "Next Keyboard" button for switching  
• Syncs with the main app via App Group  

iOS Share Extension  
• Share any URL, image, file, video, or text directly into the clipboard history from any app's share sheet  
• Compose field text becomes the item's comment when sharing an attachment  

Platform Support  
• iOS (iPhone and iPad)  
• macOS via Mac Catalyst  
• iCloud sync between iOS and macOS  

Context Menu Actions (long press / right click)  
| Action | Available for |  
|---|---|  
| Copy | All items |  
| Open URL | URL items and text containing a valid URL |  
| Save to Downloads | Files, images, binary data (macOS) |  
| Pin / Unpin | All items |  
| Add / Edit Comment | All items |  
| Send to iCloud | Device-stored items |  
| Delete | All items |  


