# VisionScan

**VisionScan by [Vision Technologies and Robotics](https://www.visiontech.com.in)** — a simple Windows app to scan your papers and save them as a **PDF** (or image), in one click.

➡️ **[Download VisionScan](https://github.com/visiontech-com-ai/VisionScan-releases/releases/latest)** — from the latest release, download **`VisionScan-Setup.exe`** and run it. It installs VisionScan and adds a Start-menu shortcut — no admin needed.

*Prefer no install?* Download **`VisionScan-win-x64.zip`** from the same release, unzip it anywhere, and run `VisionScan.exe` (portable).

The app also updates itself from this page.

---

## What the screen looks like

![VisionScan main window](docs/overview.png)

Three parts to know:

1. **Left side** — your scan settings and the **Scan** / **Save PDF** buttons.
2. **Middle** — the **preview** of the page you scanned or opened.
3. **Right side** — the list of **files you have saved**.

---

## 1. Scan to a size limit (size-driven scan)

<img src="docs/size-scan.png" width="280" align="right" alt="Size settings" />

Some websites only accept small files (like "under 500 KB"). VisionScan can do this for you.

**How:**

1. In the **File Name** box, type a name (example: `aadhaar`).
2. In **File type**, choose **PDF**.
3. In **Max file size (KB)**, type a number. `500` means about 500 KB.
4. Click **Scan**, then **Save PDF**.

VisionScan makes the file fit under the size you asked for. It first lowers the quality a little; if it is still too big, it makes the picture smaller. **Leave the box empty if you do not want any limit.**

<br clear="all" />

---

## 2. The saved files list (file grid)

![Saved files list](docs/file-grid.png)

Every file you save shows up on the **right side**, newest on top. For each file you see:

- **Date / Time** — when you saved it
- **File name**
- **Location** — the folder it is in
- **Size**

Type in the **Search saved files…** box to find one quickly. This list stays even after you close and open the app again.

> 💡 If a file with the same name already exists, VisionScan adds the time to the new name. **Your old files are never deleted or replaced.**

---

## 3. The preview panel

<img src="docs/preview-panel.png" width="220" align="right" alt="Preview panel" />

The **middle** of the window shows what you scanned or opened, so you can check it **before** you save.

- Click **Scan** to bring a page from your scanner into the preview.
- Or click **Import** to open a picture or PDF you already have.
- After you save, the preview keeps showing your last file. The next time you scan, it starts fresh.
- Tick **Combine pages into one file** to put many pages into **one** PDF.

<br clear="all" />

---

## 4. Two sides on one page (ID cards)

<img src="docs/combine-a4.png" width="230" align="right" alt="Two card sides combined onto one page" />

Scan both sides of a card — Aadhaar, PAN, voter ID (EPIC), driving licence — and put them **on one page**, like a photocopy.

**How:**

1. **Scan** (or **Import**) side 1, then side 2 — now you have two pages.
2. Type a **File Name** and pick the **File type** and, if you want, a **Max file size (KB)**.
3. Click **Combine to page**. A small window shows both sides on one sheet — you can flip the layout or swap top/bottom, then click **OK**.
4. VisionScan saves one file with both sides.

The combined page uses the **Page size** you picked on the left (A4, Letter, …) and is squeezed under your **Max file size** too. Tick **Keep original pages** in the window if you also want to keep the two single scans.

<br clear="all" />

---

## 5. Skip blank pages

<img src="docs/blank-pages.png" width="220" align="right" alt="Ask about blank pages checkbox" />

Two-sided papers often have empty backs. VisionScan can find blank pages for you and let you drop them.

**How:**

1. Tick **Ask about blank pages** on the left.
2. Scan your stack — flatbed or feeder (ADF).
3. When the scan finishes, any blank pages are **highlighted** and VisionScan asks *"2 blank page(s) were detected — delete them?"* Click **Yes** to remove them, or **No** to keep them.

> ℹ️ **Note:** If you save each scan straight to a file (a **File Name** is set *and* **Combine pages into one file** is **off**), each page is saved the moment it's scanned — so deleting a blank afterwards clears it from the preview but **not** from the already-saved file. To review blanks **before** saving, tick **Combine pages into one file** (or leave the File Name empty), then click **Save PDF** once you're happy.

<br clear="all" />

---

## 6. Resize a picture (size & DPI)

Need a picture at an exact size — so many pixels, a set width in cm, a certain DPI, or just a smaller file? Open (or scan) a picture, click it in the preview, then open the **Image** menu and choose **Resize**.

**How:**

1. Select the page in the preview, open the **Image** menu, and click **Resize**.
2. Choose how you want to measure — **px** (pixels), **%**, **in**, **mm**, or **cm** — and type the **Width** and **Height**. Keep **Maintain aspect ratio** ticked so the picture does not stretch.
3. *(Optional)* Set the **Resolution (DPI)** — handy for printing or passport/ID photos (for example `300`).
4. *(Optional)* To aim for a file size, type a number in **Target file size (KB)** and click **Calculate** — VisionScan works out the new size for you.
5. Click **OK**. The line at the bottom always shows the result, like `→ 827 × 1063 px (~180 KB JPEG)`.

> 💡 The KB figure is an estimate for JPEG — the real size depends on the **File type** you save as. For a strict limit, also use **Max file size (KB)** on the left.

<br clear="all" />

---

## Quick start (the whole thing)

1. Type a **File Name** (example: `birth-certificate`).
2. Choose **File type** = **PDF**.
3. *(Optional)* Set **Max file size (KB)**, example `500`.
4. Put your paper in the scanner and click **Scan**. *(Or click **Import** to open a file you already have.)*
5. Click **Save PDF**.

Your file is saved to the **Output folder** and appears in the **Saved files** list on the right.

> ⌨️ **Tip:** Press **Enter** in the File Name box to start scanning right away.

---

## Keeping VisionScan up to date

VisionScan can update itself from this page — you do not need to reinstall.

1. Click **About** (top-right corner).
2. Tick **Check for updates**.
3. If a newer version is out, an **Install …** link appears. Click it — the new version downloads and installs by itself, then VisionScan restarts.

You can also download the newest `.zip` from the **[Releases page](https://github.com/visiontech-com-ai/VisionScan-releases/releases/latest)** at any time.

---
---

# ভিশনস্ক্যান (VisionScan)

**ভিশনস্ক্যান — [Vision Technologies and Robotics](https://www.visiontech.com.in) থেকে।** এটি একটি সহজ Windows অ্যাপ, যা দিয়ে আপনি আপনার কাগজ স্ক্যান করে **PDF** (বা ছবি) হিসেবে সেভ করতে পারেন — মাত্র এক ক্লিকে।

➡️ **[ভিশনস্ক্যান ডাউনলোড করুন](https://github.com/visiontech-com-ai/VisionScan-releases/releases/latest)** — সর্বশেষ রিলিজ থেকে **`VisionScan-Setup.exe`** নামিয়ে চালান। এটি ভিশনস্ক্যান ইনস্টল করে এবং স্টার্ট-মেনুতে শর্টকাট যোগ করে — অ্যাডমিন লাগে না।

*ইনস্টল করতে চান না?* একই রিলিজ থেকে **`VisionScan-win-x64.zip`** নামিয়ে যেকোনো জায়গায় আনজিপ করুন এবং `VisionScan.exe` চালান (পোর্টেবল)।

অ্যাপটি নিজে থেকেই এই পেজ থেকে আপডেট নিয়ে নেয়।

---

## স্ক্রিনটি দেখতে কেমন

![ভিশনস্ক্যান মূল উইন্ডো](docs/overview.png)

তিনটি অংশ চিনে রাখুন:

1. **বাঁ দিক** — স্ক্যানের সেটিং এবং **Scan** / **Save PDF** বোতাম।
2. **মাঝখান** — আপনি যে পেজ স্ক্যান বা ওপেন করেছেন তার **প্রিভিউ**।
3. **ডান দিক** — আপনি যেসব ফাইল **সেভ করেছেন** তার তালিকা।

---

## ১. নির্দিষ্ট সাইজে স্ক্যান (size-driven scan)

<img src="docs/size-scan.png" width="280" align="right" alt="সাইজ সেটিং" />

অনেক ওয়েবসাইট শুধু ছোট ফাইল নেয় (যেমন "৫০০ KB-এর কম")। ভিশনস্ক্যান এটি আপনার হয়ে করে দিতে পারে।

**যেভাবে করবেন:**

1. **File Name** ঘরে একটি নাম লিখুন (যেমন: `aadhaar`)।
2. **File type**-এ **PDF** বেছে নিন।
3. **Max file size (KB)** ঘরে একটি সংখ্যা লিখুন। `500` মানে প্রায় ৫০০ KB।
4. **Scan** চাপুন, তারপর **Save PDF** চাপুন।

ভিশনস্ক্যান ফাইলটিকে আপনার বলা সাইজের নিচে নামিয়ে আনে। প্রথমে সামান্য কোয়ালিটি কমায়; তাতেও বড় থাকলে ছবিটিকে ছোট করে। **কোনো সীমা না চাইলে ঘরটি খালি রাখুন।**

<br clear="all" />

---

## ২. সেভ করা ফাইলের তালিকা (file grid)

![সেভ করা ফাইলের তালিকা](docs/file-grid.png)

আপনি যে ফাইলই সেভ করেন সেটি **ডান দিকে** দেখা যায়, নতুনটি সবার উপরে। প্রতিটি ফাইলের জন্য দেখবেন:

- **Date / Time** — কখন সেভ করেছেন
- **File name** — ফাইলের নাম
- **Location** — কোন ফোল্ডারে আছে
- **Size** — ফাইলের সাইজ

**Search saved files…** ঘরে লিখে দ্রুত খুঁজে নিতে পারেন। অ্যাপ বন্ধ করে আবার খুললেও এই তালিকা থেকে যায়।

> 💡 একই নামের ফাইল আগে থেকে থাকলে ভিশনস্ক্যান নতুন নামের সাথে সময় জুড়ে দেয়। **আপনার পুরনো ফাইল কখনো মুছে যায় না বা বদলে যায় না।**

---

## ৩. প্রিভিউ প্যানেল

<img src="docs/preview-panel.png" width="220" align="right" alt="প্রিভিউ প্যানেল" />

উইন্ডোর **মাঝখানে** আপনি যা স্ক্যান বা ওপেন করেছেন তা দেখা যায়, যাতে সেভ করার **আগেই** যাচাই করে নিতে পারেন।

- স্ক্যানার থেকে পেজ আনতে **Scan** চাপুন।
- অথবা আগে থেকে থাকা ছবি বা PDF খুলতে **Import** চাপুন।
- সেভ করার পর প্রিভিউতে আপনার শেষ ফাইলটি দেখাতে থাকে। পরেরবার স্ক্যান করলে নতুন করে শুরু হয়।
- অনেক পেজ **এক** PDF-এ রাখতে **Combine pages into one file** টিক দিন।

<br clear="all" />

---

## ৪. এক পেজে দুই দিক (আইডি কার্ড)

<img src="docs/combine-a4.png" width="230" align="right" alt="দুই দিক এক পেজে" />

কার্ডের দুই দিক — আধার, প্যান, ভোটার আইডি (EPIC), ড্রাইভিং লাইসেন্স — স্ক্যান করে **এক পেজে** বসান, ফটোকপির মতো।

**যেভাবে করবেন:**

1. আগে **Scan** (বা **Import**) দিয়ে ১ম দিক, তারপর ২য় দিক আনুন — এখন দুটি পেজ হলো।
2. একটি **File Name** লিখুন, **File type** বেছে নিন, চাইলে **Max file size (KB)** দিন।
3. **Combine to page** চাপুন। একটি ছোট উইন্ডোতে দুই দিক এক পেজে দেখাবে — চাইলে সাজানো বদলান বা উপর-নিচ অদল-বদল করুন, তারপর **OK** চাপুন।
4. ভিশনস্ক্যান দুই দিক সহ একটি ফাইল সেভ করে।

কম্বাইন করা পেজটি বাঁ দিকে বেছে নেওয়া **Page size** (A4, Letter …) অনুযায়ী হয় এবং আপনার **Max file size**-এর নিচেও নামিয়ে আনা হয়। দুটি আলাদা স্ক্যানও রাখতে চাইলে উইন্ডোতে **Keep original pages** টিক দিন।

<br clear="all" />

---

## ৫. ফাঁকা পেজ বাদ দিন

<img src="docs/blank-pages.png" width="220" align="right" alt="ফাঁকা পেজ সম্পর্কে জিজ্ঞাসা" />

দুই দিকের কাগজের পেছনটা প্রায়ই ফাঁকা থাকে। ভিশনস্ক্যান ফাঁকা পেজ খুঁজে দিয়ে সেগুলো বাদ দিতে সাহায্য করে।

**যেভাবে করবেন:**

1. বাঁ দিকে **Ask about blank pages** টিক দিন।
2. আপনার কাগজ স্ক্যান করুন — ফ্ল্যাটবেড বা ফিডার (ADF)।
3. স্ক্যান শেষ হলে ফাঁকা পেজগুলো **হাইলাইট** হয় এবং ভিশনস্ক্যান জিজ্ঞাসা করে *"2 blank page(s) were detected — delete them?"* মুছতে **Yes**, রাখতে **No** চাপুন।

> ℹ️ **মনে রাখুন:** যদি প্রতিটি স্ক্যান সরাসরি ফাইলে সেভ হয় (**File Name** দেওয়া আছে *এবং* **Combine pages into one file** বন্ধ), তাহলে প্রতিটি পেজ স্ক্যানের সাথে সাথেই সেভ হয়ে যায় — তাই পরে ফাঁকা পেজ মুছলে সেটি প্রিভিউ থেকে যায়, কিন্তু আগে সেভ হওয়া ফাইল থেকে **যায় না**। সেভ করার **আগে** ফাঁকা পেজ যাচাই করতে চাইলে **Combine pages into one file** টিক দিন (বা File Name খালি রাখুন), তারপর ঠিক থাকলে **Save PDF** চাপুন।

<br clear="all" />

---

## ৬. ছবির সাইজ ও DPI বদলান

কোনো ছবি নির্দিষ্ট সাইজে দরকার — এত পিক্সেল, নির্দিষ্ট সেন্টিমিটার চওড়া, নির্দিষ্ট DPI, বা শুধু ছোট ফাইল? ছবিটি ওপেন (বা স্ক্যান) করে প্রিভিউতে ক্লিক করুন, তারপর **Image** মেনু খুলে **Resize** বেছে নিন।

**যেভাবে করবেন:**

1. প্রিভিউতে পেজটি সিলেক্ট করে **Image** মেনু খুলুন এবং **Resize** চাপুন।
2. কীভাবে মাপবেন বেছে নিন — **px** (পিক্সেল), **%**, **in**, **mm**, বা **cm** — এবং **Width** ও **Height** লিখুন। ছবি যেন টেনে বিকৃত না হয় সেজন্য **Maintain aspect ratio** টিক রাখুন।
3. *(ইচ্ছা করলে)* **Resolution (DPI)** দিন — প্রিন্ট বা পাসপোর্ট/আইডি ছবির জন্য কাজে লাগে (যেমন `300`)।
4. *(ইচ্ছা করলে)* নির্দিষ্ট ফাইল সাইজ পেতে **Target file size (KB)** ঘরে সংখ্যা লিখে **Calculate** চাপুন — ভিশনস্ক্যান নতুন সাইজ হিসাব করে দেয়।
5. **OK** চাপুন। নিচের লাইনে সবসময় ফলাফল দেখায়, যেমন `→ 827 × 1063 px (~180 KB JPEG)`।

> 💡 KB সংখ্যাটি JPEG-এর জন্য আনুমানিক — আসল সাইজ নির্ভর করে আপনি কোন **File type**-এ সেভ করছেন তার উপর। কড়া সীমা রাখতে বাঁ দিকের **Max file size (KB)**-ও ব্যবহার করুন।

<br clear="all" />

---

## দ্রুত শুরু (পুরো কাজটি)

1. একটি **File Name** লিখুন (যেমন: `birth-certificate`)।
2. **File type** = **PDF** বেছে নিন।
3. *(ইচ্ছা করলে)* **Max file size (KB)** দিন, যেমন `500`।
4. স্ক্যানারে কাগজ রেখে **Scan** চাপুন। *(অথবা আগে থেকে থাকা ফাইল খুলতে **Import** চাপুন।)*
5. **Save PDF** চাপুন।

আপনার ফাইল **Output folder**-এ সেভ হয় এবং ডান দিকের **Saved files** তালিকায় দেখা যায়।

> ⌨️ **টিপ:** File Name ঘরে **Enter** চাপলেই সাথে সাথে স্ক্যান শুরু হয়।

---

## ভিশনস্ক্যান আপডেট রাখা

ভিশনস্ক্যান এই পেজ থেকে নিজে আপডেট নিতে পারে — আবার নতুন করে ইনস্টল করতে হয় না।

1. উপরে ডান দিকে **About** ক্লিক করুন।
2. **Check for updates** টিক দিন।
3. নতুন ভার্সন থাকলে একটি **Install …** লিঙ্ক আসে। ক্লিক করলেই নতুন ভার্সন নিজে নেমে ইনস্টল হয়ে যায়, তারপর ভিশনস্ক্যান আবার চালু হয়।

চাইলে যেকোনো সময় **[Releases পেজ](https://github.com/visiontech-com-ai/VisionScan-releases/releases/latest)** থেকে নতুন `.zip` ডাউনলোড করতে পারেন।

---

<sub>Public download host for VisionScan Windows builds. Used by the app auto-updater. Source: private repo `visiontech-com-ai/VisionScan`.</sub>
