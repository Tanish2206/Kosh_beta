# kosh (glass) — test mode

A native SwiftUI kosh for iOS 26: Apple's light look (SF Pro, white pages, grey cards), the
Liquid Glass tab bar with the running month above it, glass month chips over the ledger, and
the month cards opening into their page with a zoom.

Test mode reads `Kosh/kosh.json`, a snapshot of the ledger. Nothing here talks to the network,
and changes made in the app (naming payments, adding a spend) last until it is closed.

Open `Kosh.xcodeproj` in Xcode 26, pick an iPhone simulator, and press Run.

Run starts the app without the debugger, because attaching it stalls the launch on this Mac.
To debug, tick Product › Scheme › Edit Scheme › Run › Debug executable.
