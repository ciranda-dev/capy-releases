# Changelog

What changed in each Capy release. Downloads for every version are on the [Releases](https://github.com/ciranda-dev/capy-releases/releases) page.

## 1.0.15 · 2026-10-26

**Files and video messages**
- Video messages and files go up to 10 MB. A video message shows the time it has left and stops by itself at the limit, for you to check before it goes.
- A bigger file goes straight between computers, with no limit but the disk. A room's Files have no cap either.

**Calls**
- Big calls stay smooth: the stage pages its tiles, and video comes from the people on your page.
- A secure room now holds 2 to 16 people.
- Camera fixes: switching cameras, turning one off while it switches, unplugging one, and a video message whose camera went away.

**Your words and your devices**
- Your 24 words are sealed by your computer's keychain where it has one, and the first run only shows them. Copy and Save as a text file are in Settings → Recovery words, and a copy leaves the clipboard a minute later.
- Lock Capy asks for the current lock (Touch ID or your PIN) before it changes or turns off.
- Linking a device says each step on both computers, and what to try when one waits too long.

**Everything else**
- When one of the team's relays is down, Capy goes to the other one.
- Settings → Network has Copy all, for a bug report.
- The update card no longer shows the word "null".

## 1.0.14 · 2026-10-25

- A second always-on relay and blind peer. When one of them is down, people still reach each other through the other, and messages for someone who is offline still wait for them there.

## 1.0.12 · 2026-10-25

**Your devices**
- Add a device from the one that keeps your 24 words: Settings → Devices → Add a device shows a link and a QR code that work once, for 10 minutes. On the new device, "I already use Capy" → "Link to my account", then Accept on the first one. The words stay on one device.
- Devices show as their type and a short code from their key ("Mac · i1hp55"), never your computer's name, and you can rename them.
- Remove a device from any of yours: every device refuses it from then on, and an up-to-date removed device erases what it kept.
- Recovery takes the 24 words, typed or from the saved file.

**The lock**
- Touch ID first; the PIN only when you pick it. A forgotten PIN is reset only with another device's approval or the 24 words. While locked, nothing outside the lock screen works.

**Rooms and messages**
- A status to stay Invisible, for an hour, until tomorrow or until you change it.
- Muting someone deletes all their messages in that room for everyone. Devices still on 1.0.11 keep showing them.
- Seen shows once everyone has read a message.
- Voice messages are checked before they go, tap or hold to record, five minutes at most.
- Download automatically, in Privacy & security.
- Deleting gives the disk space back.
- Room Files: a same-name file can be a new version, identical files aren't stored twice, drag files and folders.
- Links ask before they open in your browser.
- Every text field has a limit and says so before you reach it.

**Calls**
- A connection test before a call that sends a real burst to the people online and says what it measured.
- Full screen, zoom and side by side for what's shared, with a chip for each share.
- Someone taken out of a call stays out of it on every device.
- Decision and Task have shortcuts (Cmd/Ctrl+Shift+D and T).
- The minutes no longer make tasks by themselves; what the AI finds waits for your click.

**Everything else**
- Switch the language without a reload.
- Linux: the AppImage stays and no longer needs libfuse2; the Snap Store's beta channel has Capy (`sudo snap install capy --beta`).
- macOS: the Macs are notarized by Apple.
- Capy is proprietary from this version, © 2026 Ciranda. Settings → About → Open-source licenses lists what it includes; the source of its LGPL parts is attached here (`capy-1.0.12-lgpl-sources.tar.gz`).

## 1.0.11 · 2026-10-23

- Code in messages: inline code between backticks and blocks between three, each block with a Copy button. In the composer, ⌘E and ⌘⇧E (Ctrl+E and Ctrl+Shift+E) make a selection code
- Invite links: the invite menu has Copy invite link, and a click on a capy:// link opens Capy with the invite in the Join dialog. Show QR code is in the same menu, in a new dialog with the room's picture
- A person's card in the member list shows their role and what you may change there: their role, Mute and Remove from room
- Your status is only the one you pick: Capy never sets you Away by itself
- Lock Capy with Touch ID or a PIN in Settings → Privacy & security. On a computer without Touch ID, a PIN does the job
- Your pinned rooms, muted rooms and what you have read now follow you to your other devices, and a device you add opens your older messages from your other devices
- Your other devices don't ring when you call: they show a quiet notice with a Join button
- Link previews now start off for everyone, since making one shows the website your IP address. Turn them on in Settings → Privacy & security if you want them
- Pick your language on the first screen from a menu, with each language's flag
- On Linux this is the last AppImage: Capy is moving to Flathub and the Snap Store, and the AppImage tells you so once
- Fixes and polish across the app

## 1.0.10 · 2026-10-23

- Calls take up to 16 people at once. When one is full, Join says so, and you can join as soon as someone leaves
- Calls adapt to your connection: video starts lower and climbs while the link is good, backs off when it isn't, and the sound waits a little for voices that arrive late. The connection signal fits long distances, so a far call that sounds fine no longer shows red
- Capy keeps reconnecting to the devices of the people in your rooms, so after a restart or between two calls it doesn't have to find them again
- Nobody has to watch a shared screen or a presented PDF: minimize it to a chip in the call's header and show it again when you like
- A secure room's call can't be started alone, since its end would erase the room
- After a call, your computer writes your own minutes by itself, then the decisions, tasks and open questions for you to add, and the transcript's chapters. A long call is read in parts, and the recap card shows only what the call has
- Links in messages open in your browser when you click them
- Click a room's picture to see it large, and zoom photos with the viewer's new buttons
- Every transfer says how it's going: how much came, how fast, about how long is left, or what it's waiting for
- A file you send over 25 MB is a big file, which goes only straight between two computers, and video and voice messages are held to 25 MB
- Remove from Files no longer deletes anyone else's copy: the file leaves the room's Files and stops being shared from your computer, and people who downloaded it keep theirs
- On macOS and Linux, an update you leave waiting installs itself at a quiet moment, after a one-minute countdown, never during a call
- Capy picks itself up: its background part starts again by itself, the window loads again if it crashes, a message it can't show no longer breaks the room, and what you were typing comes back (outside secure rooms)
- Rooms hold up against a member who tries to flood or break them
- Error reports say which version of Capy each error happened in
- The language cards show each language's name in English too
- Fixes and polish across the app

## 1.0.9 · 2026-10-22

- Files: every room has a Files tab, a tree of folders and files the people in it keep together. Upload a file or a whole folder, make folders, rename and move, and put a new version over the old one. Nothing downloads until you ask, and a file arrives only while you and someone who has it are both online
- Big files: a file in the chat can be up to 10 GB. Above 100 MB it goes only straight between two computers, never through the team's relay or blind peer, and comes only when you press Download; its download can be paused, resumed and cancelled
- Link previews: a link you type gets a card with its page's title and picture. Your computer fetches the page once, the people in the room fetch nothing, and it can be turned off in Settings → Privacy & security
- A room's picture, set by its owner and admins
- Log out is easy to find at the bottom of Settings, and your rooms stay here for when you log in again. To clear this computer, "Log out and erase" is at the bottom of Privacy & security: your rooms stay with the other people in them and on your other devices
- Your status picker says what each status does, and your status shows on your avatar in Settings too
- A join that waits for someone to let you in can be cancelled, and pasting the invite of a room you're already in opens it
- Secure rooms: their file is sealed with your system's keychain, on a Mac they're kept out of Time Machine backups, and they're erased when their call ends, with no other time to pick
- Calls: only real measures are shown, and every audio and video packet is numbered, so lost and late packets are counted for real. The lobby lets go of the camera when you leave it. Holding the record button keeps recording until you let go
- An update shows up within minutes instead of up to an hour, and once you press Restart now the update card's buttons can't be pressed again
- Settings → Devices no longer lists a computer that never really came in, and removes such entries by itself
- A voice message's transcript opens and closes, and Settings → Network shows your address and keys without opening Details first
- Also fixed: a file sent while you were away opens from the blind peer alone, someone blocked from a room who pastes its invite again is refused, and the privacy screen keeps every box the same size
- Fixes and polish across the app

## 1.0.7 · 2026-10-22

- Updates heal themselves: a failed update tries again on its own, a new version that doesn't start puts the previous one back, and on a Mac Capy offers to move itself into Applications so it can update. Nobody has to install it again.
- Four languages: English, Português, Español and العربية, right to left.
- Threads: reply to any message in a thread, with its own replies, mentions and files.
- In a call: quick polls, planning poker and fist of five; breakout rooms that anyone can start, with nobody hosting; present a PDF page by page; a connection card for each person, and a connection test before you join.
- The agenda counts down each item, and the call can vote to move on. A repeating meeting opens with what happened last time, and every call leaves a recap in the room.
- The canvas: a retro where everyone's notes stay hidden until all are ready, and boards from templates (Kanban, Scrum, mind map, SWOT and more) whose cards are the room's tasks.
- With a model downloaded, on your own computer: catch me up when you join late, a live summary, chapters in the transcript, decisions and tasks found for you to confirm, unanswered questions, Prepare me before a meeting, your daily check-in drafted from what you said, and ask the past without leaving the call.
- Better transcription: Whisper large-v3 Turbo and Parakeet TDT 0.6B v3.
- On Windows and Linux, closing the window keeps Capy in the tray.
- Settings → Devices no longer lists ghost copies of the same computer, and can remove them in one click. The room's side panels share one width and the header never runs out of the window.

## 1.0.6 · 2026-10-21

- Meetings now have their own insights: talk share, interruptions and length are worked out per meeting (not for the whole room), the same on everyone's screen. A Meetings panel lists each one and follows a repeating meeting over time.
- Daily check-in: before a standup, everyone writes Yesterday, Today and Blockers; in the call the answers show one person at a time, and a blocker becomes a task with one click. When everyone is in, the call can be skipped.
- A round with a timer per person in the call: random order, the same for everyone, a timer that turns amber then red, and nobody hosts it.
- Shared notes, live: everyone in the call writes the same document from a template (daily, 1:1, planning, interview, retro). A checkbox becomes a task and an @name its owner.
- Decision and Task buttons in the call mark the moment. A Decisions log lists every meeting's decisions, searchable, each opening the call at that moment.
- Changing the language no longer restarts the app. It waits for your call to end.
- Zoom works on every avatar, including letters, and the photo opens as large as the window allows.
- The privacy screen no longer flickers when messages arrive.
- Fixes and polish across the app.

## 1.0.5 · 2026-10-21

- Fixes Capy not opening on Windows.
- A privacy screen: one button blurs what's said on your screen (messages, photos, videos, names) for people passing behind you. Hover a message to peek. Notifications say only "New message".
- Messages show Sent, Delivered and Seen. Delivered says only that the other person's Capy has the message, never when.
- Your status: Active, Away or Busy, automatic or picked.
- A live voice filter in calls, a mic level with "Hear my mic", and warnings when your mic is muted or silent. Your speaking now shows pace and filler words per minute. Clear and Broadcast sound less robotic.
- A connection signal on every tile in a call: green, amber or red.
- Right-click to copy, and one-click copy buttons. Nothing can be copied from a secure room.
- Many more emoji (with a Spicy shelf and Portuguese search), fifty capybara emoji of our own, and more stickers.
- Photos and video messages are sent the way you saw them in the mirror, with a switch to turn that off.
- Click anyone's profile photo to see it big, in the chat, the member list or their card.
- Selects look the same on every system, and boxes no longer move when you reveal a key or press a button.
- AI models: none is picked until you download one, a stalled download can be cancelled and says why, and the status row is tidier.
- A new update card in the sidebar: it never restarts you in the middle of a call.

## 1.0.4 · 2026-10-20

- Leave a room from its menu; the others see you left.
- The owner or an admin can rename a room, remove someone for good, or mute them so they can't post. Someone removed stops getting new messages and seeing who's online.
- See who reacted to a message: rest the mouse on a reaction, or open the message's More menu.
- Video messages: record, watch it back, then send. Or hold the camera button to record and let go to send.
- The camera button takes a photo or a video, and switches cameras.
- A voice filter cleans up your voice messages (Settings → Audio & video), and a call's notes show how you spoke: repeated words, fillers, long pauses. Only you see it.
- Pick one of four AI models on your computer for the minutes (Settings → Notes & AI), and copy or save a call's transcript.
- Pinned rooms first, then the latest activity, with times like "Yesterday".
- A join that waits for someone to let you in moves to the background.
- Pick your language on the first screen, and save your 24 words as a text file.
- Settings → Network shows how your device connects.
- Send feedback and report bugs from Settings → Help & feedback, straight to the Capy team. A report says how your device connects (counts and error codes, never addresses), to help fix connection problems.
- First test builds for Windows and Linux (unstable).
- Fixes: opening the window again after closing it, the "Add to calendar" menu inside a meeting's details, the message toolbar over the room's header, your look's colour around a profile photo, and the installer's disk icon.

## 1.0.2 · 2026-10-19

- Secure rooms stay through a restart, until their call ends or their time runs out.
- Secure rooms connect through the relay when two devices can't reach each other.
- Pin rooms to the top of your list.
- An update shows how far along its download is.

## 1.0.0 · 2026-10-19

- On-device AI (transcripts, minutes, captions) works on any Mac: QVAC 0.22 with no Homebrew libraries.
- Messages reach people who were offline: a blind peer keeps each room encrypted.
- Devices that can't reach each other directly connect through a blind relay.
- Once installed, Capy updates itself over the peer-to-peer network.
