<img width="1760" height="493" alt="torq_banner_01" src="https://github.com/user-attachments/assets/1eb2be37-9b20-4738-bb2b-674e3dd0d2b0" />

# TORQ Lite 🚧

**Find every link on your Windows computer. Free.**

TORQ Lite finds the links on your disks — symbolic links, junctions, mounted volumes and subst drives, plus hardlinks with a deep scan — shows where each one points, and tells you whether its target is still there. Scanning only reads your disks: it never changes, moves or deletes anything.

## Features

- Scan the whole computer, or only the folders you choose
- Symbolic links, junctions, mounted volumes and subst drives; hardlinks with a deep scan
- Each link's location, what it points to, and the volume it is on
- Whether each target still exists, checked again whenever you click **Check now**
- Search by path, target or volume
- Save or download the results as a plain-text report
- **Restart as administrator** to reach folders that need higher access
- Works offline, keeps everything in its own folder, and sends nothing anywhere

## Download

1. Go to **[Releases](../../releases)** and download **TORQ-Lite.zip**.
2. Before you extract it, right-click the zip, choose **Properties**, tick **Unblock** and press **OK**. This avoids most Windows warnings.
3. Extract it into a folder your user account can write to, such as `C:\TORQ`. Avoid Program Files and folders that OneDrive syncs.
4. Double-click **TORQ-Lite.exe**.

The first time, Windows may say **"Windows protected your PC"**. Click **More info**, then **Run anyway**. This happens because TORQ is not code-signed yet. We have not seen it in our own testing, but every Windows setup is different and yours might show it.

This repository holds the app only.

## Using it

1. Double-click **TORQ-Lite.exe**. A TORQ console window opens and your browser shows TORQ. Keep the console open while you work: closing it stops TORQ.
2. Click **New Link Scan**. Tick the disks or folders you want (expand a disk to pick a folder inside it), then click **Scan selected**. Leave everything unticked to scan the whole computer; on large disks that can take a while.
3. When the scan finishes, the **Links** page lists every link. Click one to see its details.
4. Click **Save results** to keep a report as a text file.

If the top bar says **Limited access**, some folders were skipped. Click **Restart as administrator** and choose **Yes** on the Windows prompt.

TORQ Lite does not keep a history of scans. Save the report if you want to keep a result.

## Requirements

- Windows 10 or Windows 11 (not Windows in S mode)
- No installation, no internet connection, no extra software
- TORQ is not code-signed yet, so security software may flag it the first time, and Windows 11's Smart App Control may block it. If your antivirus quarantines it, restore it and allow it. We have rarely seen this in our testing at different security levels, but every setup is different.

## License

TORQ Lite v1.0 · by CrateTools

TORQ Lite is free to use, at home or at work. It may not be sold, redistributed, changed or reverse engineered. No support is provided. See [LICENSE](LICENSE.md) for the full terms.

Copyright (c) 2026 CrateTools. All rights reserved.

---
<img width="1760" height="493" alt="torq_technician_banner_01" src="https://github.com/user-attachments/assets/0a140f33-7033-4606-8c80-47469afd9fb5" />

# Also available: TORQ Technician 🚧

**Links, Folder Disks and Network Disks: made in a few clicks, tracked on every machine, run from one screen.**

TORQ Lite shows you the links. **TORQ Technician puts you in control of them.** Create junctions and symbolic links, turn folders into disks with the letter you want, and map network shares as disks for one user or for every user of the PC. Do it on this PC, or on any PC you have paired on your network. TORQ keeps track of everything it made, on every machine, so you always know what is set up where.

When something breaks, TORQ tells you, and you can fix it on the spot.

## Lite vs Technician

| Feature | Lite (free) | Technician |
|---|:---:|:---:|
| **🔍 Scan and report** | | |
| Scan the whole computer or chosen folders | ✔ | ✔ |
| Symbolic links, junctions, mounted volumes, subst drives, hardlinks (deep scan) | ✔ | ✔ |
| Clone and snapshot-copy hints | ✔ | ✔ |
| Link list, details and search | ✔ | ✔ |
| Check now | ✔ | ✔ |
| Save / download report | ✔ | ✔ |
| Restart as administrator | ✔ | ✔ |
| Offline, nothing sent anywhere | ✔ | ✔ |
| **💿 Storage** | | |
| Storage at a glance: drive letters, mount folders, volumes, disks, used and free | ✔ | ✔ |
| Storage by letter, volume, partition and disk, with disk health (S.M.A.R.T.) | ✔ | ✔ |
| Replace or Check on each disk, with the reason: temperature, reallocated sectors, NVMe spare and wear | ✔ | ✔ |
| Pools, RAID, dynamic disks and BitLocker shown as they really are, missing members and locked drives included | ✔ | ✔ |
| What each disk holds: its letters and folders, EFI and recovery partitions, unallocated space | ✔ | ✔ |
| Disk tags: sticker code, label photo (QR read for you, offline) and a note: where it sits, who to call | ✗ | ✔ |
| Tags follow each disk by its serial number, kept on your PC, never written to the disk | ✗ | ✔ |
| Warranty tracking for every tagged disk, on every machine: end date, maker, vendor and receipt | ✗ | ✔ |
| Warranty countdown: soonest first, alerts as the end gets close, acknowledged once handled | ✗ | ✔ |
| Storage of every paired PC through Site Manager, also while it is offline | ✗ | ✔ |
| **🔗 Create and manage links** | | |
| Create junctions and symbolic links with two side-by-side folder panes (Pick and Drop) | ✗ | ✔ |
| Preview of the exact command before anything is created | ✗ | ✔ |
| Symbolic links to network shares, with mapped drive letters turned into the full share path so they work for every user | ✗ | ✔ |
| Mirror Navigation: both panes follow each other through matching folders | ✗ | ✔ |
| Link List: every link you made, kept after a restart, with its state (OK, target missing, link missing) | ✗ | ✔ |
| Each new link is scanned at once and added to your results | ✗ | ✔ |
| Remove links, or open any link from your results straight in Link Tools | ✗ | ✔ |
| **📁 Folder Disk: folders as drive letters** | | |
| Give any folder its own drive letter in Explorer | ✗ | ✔ |
| For you, for one named person, or for every user of the PC | ✗ | ✔ |
| Kept at sign-in: the letter comes back by itself | ✗ | ✔ |
| Letters waiting for sign-in, with who they are for and why they are not mounted now | ✗ | ✔ |
| **🌐 Network Disk: shares as drive letters** | | |
| Map network shares for you, for one named person, or for every user of the PC | ✗ | ✔ |
| Browse Share: find computers, shares and folders on your network | ✗ | ✔ |
| Plain reasons when a drive does not connect: the server, the share or the sign-in | ✗ | ✔ |
| No passwords stored by TORQ | ✗ | ✔ |
| **🖥️ Site Manager: every PC from one screen** | | |
| Pair other Windows PCs through the TORQ Agent | ✗ | ✔ |
| Create links, Folder Disks and Network Disks on remote PCs, as if you were sitting there | ✗ | ✔ |
| Scan remote PCs and browse their folders | ✗ | ✔ |
| See who is signed in on each machine | ✗ | ✔ |
| Every request signed with the pairing key; no password ever sent over the network | ✗ | ✔ |
| Windows 10 and 11 on the same network, physical PCs and virtual machines | ✗ | ✔ |
| **🗂️ History and tracking** | | |
| Every scan saved, for every machine, with search | ✗ | ✔ |
| One card per machine: its links, Folder Disks and Network Disks | ✗ | ✔ |
| Snapshots of what TORQ set up on each machine, kept even while it is offline | ✗ | ✔ |
| Safe two-step delete: shows which links still exist on disk first | ✗ | ✔ |
| Report of what TORQ set up on a machine, with the link scan | ✗ | ✔ |
| **🩺 Diagnostics** | | |
| Status panel: clear "things to check" vs "waiting, nothing to fix" | ✗ | ✔ |
| "Not TORQ" tag on links and letters TORQ did not create | ✗ | ✔ |
| Open a link's location or target folder with one click | ✗ | ✔ |
| **⚙️ Settings and clean-up** | | |
| See and manage TORQ's background tasks | ✗ | ✔ |
| Uninstall: check for leftovers, and clean up only what TORQ made | ✗ | ✔ |
| Full user manual included | ✗ | ✔ |

**[Get TORQ Technician on Gumroad](https://cratetools.gumroad.com/l/TORQ)**

**[Watch TORQ in action 🟥⃢▸](https://www.youtube.com/watch?v=LmgwvyVcqpw)**

### What TORQ Technician does

TORQ Technician started with links, folder disks and network disks. It now covers the whole picture of a Windows machine's storage, on every PC you look after, and it keeps growing.

**Links, made and tracked.** Two side-by-side folder panes: pick the folder, drop it where the link should go, see exactly what will run, and confirm. Junctions and symbolic links, including links to network shares that work for every user. Every link you make goes into your **Link List**, kept after a restart, so you can check it, open it or remove it later.

**Folders as drive letters.** **Folder Disk** makes any folder show up in Explorer as its own disk, for you, for one named person, or for every user of the PC, and brings it back at every sign-in.

**Network shares as drive letters.** **Network Disk** maps shares for you, for one named person, or for every user of the PC, restored at sign-in. **Browse Share** finds the computers, shares and folders on your network. When a drive does not connect, TORQ says whether the server, the share or the sign-in is the reason. TORQ stores no passwords.

**Storage, as it really is.** Every drive letter, mount folder, volume, partition and disk, with what each disk holds and how much is used and free. Pools, RAID, dynamic disks and BitLocker are shown as they really are, missing members and locked drives included. Disk health (S.M.A.R.T.) puts **Replace** or **Check** on a disk with the reason: temperature, reallocated sectors, NVMe spare and wear.

**Disks you can identify.** Tag each disk with a sticker code, a photo of its label (the QR code is read for you, offline) and a note: where it sits, who to call. Tags follow the disk by its serial number and stay on your PC; nothing is ever written to the disk.

**Warranties you won't miss.** Record each disk's warranty end date, maker, vendor and receipt. The **Warranty** page lists every disk of every machine, soonest end first, warns you as the end gets close, and lets you acknowledge one once it's handled.

**Every machine, from one screen.** **Site Manager** pairs your other Windows PCs through a small agent. Then create links, set up Folder Disks, map Network Disks, scan, browse folders and see storage and warranties on them as if you were sitting there. Every machine's links, history and storage stay in one place, and you can still look at them while that machine is offline. A server, a client's PC, a virtual machine in the next room: one screen for all of them. Every request is signed with the pairing key, and no password ever crosses the network.

**Real problems, not false alarms.** The status panel tells **things to check** apart from things that are only **waiting**, such as a drive that connects when someone signs in, or a disk that is unplugged. Spot a link whose target is gone, open its folder or target with one click, then remove the link or make it again. The **Not TORQ** tag marks links and drive letters TORQ did not create, so the unexpected ones stand out.

**A history you can trust.** Every scan is saved, for every machine, and you can reopen and search any of them. One card per machine shows its links, Folder Disks and Network Disks, kept even while it is offline, with a report of what TORQ set up there. Deleting a saved scan is safe: TORQ first shows which of its links still exist on disk, and asks twice.

**Clean to keep, clean to leave.** See and manage TORQ's background tasks in Settings. When you're done, **Uninstall** checks for leftovers and cleans up only what TORQ made.

**Private and offline.** TORQ Technician keeps everything in its own folder, works without an internet connection, and sends nothing anywhere. Nothing phones home.

More is on the way.

Built for homelab enthusiasts and technicians who set up and maintain PCs, inherit messy disks, clean up after migrations, and need to prove what is and is not linked.

**[Get TORQ Technician on Gumroad](https://cratetools.gumroad.com/l/TORQ)**

### Technician requirements

- Windows 10 or Windows 11 (not Windows in S mode); mixed networks of both are supported
- No installation, no internet connection
- Some actions need administrator rights, such as symbolic links and drives for every user
- Site Manager needs the TORQ Agent running on the other PC and Windows file sharing working between your PCs. Setting up your own network, accounts and permissions is your responsibility; the included manual covers the common setups.
- In Task Scheduler and ProgramData, the parts TORQ sets up carry its technical name, **SymScan** (for example the "SymScan Agent" task and `C:\ProgramData\SymScan`). Each task's description says TORQ.
