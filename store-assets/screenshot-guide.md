# Sendo App Store Screenshot Capture Guide

## Required size

- **iPhone 6.5" display**: 1284 × 2778 pixels (or 1242 × 2688)
- Apple accepts 1290 × 2796 (iPhone 14 Pro Max, 15 Pro Max) as the unified 6.5"–6.7" size.

## How many

- **Minimum**: 3 screenshots
- **Maximum**: 10
- I recommend submitting **5–6** for maximum App Store impact. Apple shows the first 3 directly on the search results page.

## What to capture, in order

Apple shows screenshots left-to-right. Put your strongest 3 first.

### Screenshot 1 — "Send SMS without internet" (the hero shot)
- **Screen**: Home with 3–4 contacts visible (NOT empty state)
- **Setup**: Add 4 contacts manually before screenshotting:
  - "Aamiina Hassan" — +252 61 234 5678
  - "Cabdi Yusuf" — +252 65 432 1098
  - "Faadumo Ali" — +252 63 876 5432
  - "Mum" — +252 61 999 8888
- **What it sells**: A clean, full, ready-to-use messenger

### Screenshot 2 — "Real chat experience" (the chat screen)
- **Screen**: Open chat with messages (send 4–5 test messages first to populate)
- **Setup**: Before screenshot, send a few texts in the chat so it has content
- **What it sells**: WhatsApp-style bubbles, voice messages, blue ticks

### Screenshot 3 — "Voice messages over SMS" (the differentiator)
- **Screen**: Chat screen with the mic button being held down (recording state visible)
- **Setup**: Press and hold the mic button mid-recording, take screenshot before releasing
- **What it sells**: Voice notes that work without internet, sent as MMS

### Screenshot 4 — "Add anyone from your contacts"
- **Screen**: The "Add Contact" screen showing "Pick from my contacts" and manual entry
- **What it sells**: Easy to add anyone, no internet needed

### Screenshot 5 — "Works with any phone" (a marketing slide, not an app screenshot)
- **Optional**: A graphic showing "Sendo → carrier → iPhone/Android/feature phone"
- You can make this in Canva or Figma using the app's screen as background
- **What it sells**: Cross-platform with no internet for the recipient

### Screenshot 6 (optional) — Contact info or settings
- **Screen**: Contact info screen, or settings screen
- **What it sells**: Polished detail

## How to capture on your iPhone

1. Open Sendo on your iPhone (the one connected to Xcode)
2. Navigate to the screen you want to capture
3. Press **Power + Volume Up** simultaneously to take a screenshot
4. Screenshot saves to Photos → Albums → Screenshots
5. AirDrop / iCloud to your Mac
6. The screenshot is already the correct resolution for your device (the App Store accepts native device resolution)

## How to upload to App Store Connect

1. App Store Connect → My Apps → Sendo
2. Left sidebar → iOS 1.0 Prepare for Submission
3. Scroll to "iPhone Screenshots"
4. Click "+" and upload each PNG/JPG
5. Drag to reorder so screenshot 1 is the leftmost
6. Apple auto-generates the smaller required sizes from your 6.5" submission

## Marketing text overlays (optional but recommended)

The App Store allows you to add text overlays to screenshots. Most successful apps do this. Examples:

- Screenshot 1: "Send messages anywhere. No internet needed."
- Screenshot 2: "WhatsApp-style chat, powered by SMS."
- Screenshot 3: "Voice notes that work without Wi-Fi."

Use a tool like:
- **AppLaunchpad** (free) — applaunchpad.com
- **Figma** (free) — design from scratch
- **Canva** — has App Store screenshot templates

Apple does NOT require text overlays, but apps that have them convert much better.

## Quick capture checklist

- [ ] Capture from your iPhone (not the iOS Simulator — real device only for App Store)
- [ ] Use full-resolution PNGs (don't resize manually)
- [ ] No status bar Wi-Fi or carrier name in screenshots (turn on airplane mode first, then re-enable cellular if needed, OR use Demo Mode in Settings → Developer)
- [ ] Battery shows 100% (charge phone first or use Demo Mode)
- [ ] Time shows 9:41 AM (the classic Apple marketing time — use Demo Mode in Developer settings)
- [ ] No personal data visible (use fake names for contacts when capturing)

## Demo Mode for clean status bars

In iOS Settings:
- Go to Settings → Developer (only appears if you've connected to Xcode)
- Toggle "Status Bar Demo" → "Override System Status Bar"
- Set time to 9:41, battery to 100, signal to full bars, hide carrier name

This is what Apple uses for its own screenshots. Your screenshots will look professional.
