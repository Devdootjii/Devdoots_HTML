# 📚 Data Structures — Team Devdoots

Unit-wise study pages for **Data Structures (BCS301)** — class me padhane ke liye, revision ke liye, aur exam se pehle.

Sab kuch **single HTML files** hai: internet ki zaroorat nahi, bas file kholo aur chal jayega.

---

## 🚀 Kaise kholna hai

### Option 1 — Direct (sabse aasan)
1. `ds/` folder kholo
2. **`index.html`** pe double-click karo
3. Wahan se koi bhi page khol lo

### Option 2 — GitHub Pages (kahin se bhi, phone se bhi)

Ek baar enable karna hai:

1. Repo → **Settings** → **Pages**
2. **Source**: `Deploy from a branch`
3. **Branch**: `main` · **Folder**: `/ (root)`
4. Save — 1-2 minute baad link ready:

```
https://devdootjii.github.io/Devdoots_HTML/ds/
```

Uske baad phone, laptop, kisi bhi device se — sirf link kholo. Kuch download karne ki zaroorat nahi.

### Option 3 — Offline copy
Kisi bhi page ko download karke phone me rakh lo — bina internet chalega (fonts ke liye internet chahiye, par content sab inline hai).

---

## 🗂️ Structure

```
Devdoots_HTML/
├── ds/                          ← Data Structures (yeh folder)
│   ├── index.html               ← HUB: saare pages ek jagah + search
│   ├── README.md                ← yeh file
│   ├── unit1/
│   │   └── DS_Unit1.html
│   ├── unit3/
│   │   ├── DS_Unit3_Session1.html   ← Linear + Binary + Bubble
│   │   ├── DS_Unit3_Session2.html   ← Hashing + Selection + Insertion
│   │   ├── DS_Unit3_Session3.html   ← Merge + Quick
│   │   ├── DS_Unit3_Session4.html   ← Revision + Heap + Radix
│   │   ├── DS_Unit3_MasterSheet.html← Cheat sheet
│   │   ├── DS_Unit3_PYQ_Copy.html   ← PYQ + handwritten answers
│   │   ├── DS_Unit3_AnswerCopy.html ← Poori answer copy
│   │   └── DS_Unit3.html            ← Full unit notes
│   └── unit4/
│       ├── DS_Unit4_Session1.html   ← Trees basics + traversals
│       ├── DS_Unit4_Session2.html   ← BST + AVL
│       ├── DS_Unit4_Session3.html   ← AVL poora + B-Tree
│       └── DS_Unit4_Session4.html   ← B-Tree · B+ · Huffman · Heap
│
├── python/        ← (doosre subjects aise hi apna folder banayenge)
├── os/
└── ...
```

**Rule:** har subject ka apna folder — `ds/`, `python/`, `os/`, `dbms/` … koi bhi ek doosre ke folder me change nahi karega.

---

## ✨ Har page me kya milta hai

| Feature | Kaise | Kya karta hai |
|---|---|---|
| **📖 Page navigation** | neeche-daaye `←` `⌂` `→` | Agla / pichla page, aur hub pe wapas. Keyboard: `←` `→` `Home` |
| **✏️ Pen** | dock me ✏ | Screen pe likho — 5 colour, 3 motai, eraser, undo, clear, ✕ se band. Likha hua scroll ke saath chalta hai |
| **⏱️ Timer** | dock me ▶ | Block-wise timer; time up pe banner + beep + agla block khud |
| **🎯 Spin** | dock me 🎯 | Random student + sawaal. Dropdown se **section chuno** (ya Auto). ✓/✕ mark karo → **scoreboard** |
| **🌙 Theme** | dock me ☾ | Dark / light |
| **🎧 Audio** | dock me 🎧 | Page ko bolega (browser voice) — default me chhupa hua hai |
| **🖨️ Print** | Ctrl/Cmd + P | Answer copy pages A4 pe theek print hote hain |

**Keyboard shortcuts:** `←` `→` page change · `Home` hub · `Esc` card band

---

## ➕ Naya page kaise add karein (team ke liye)

### 1. Apna subject folder banao
```
python/
  index.html
  unit1/
    Python_Unit1.html
```

### 2. Page banao
- Ek hi `.html` file, CSS aur JS andar (koi external file nahi — sirf Google Fonts chalega)
- Dark theme default + light mode
- Diagrams HTML/CSS se (SVG nahi)

### 3. Navigation buttons lagao
Har page ke `</body>` se pehle yeh block paste karo aur `PREV` / `NEXT` ki jagah apni file ka naam daalo:

```html
<div class="dsnav">
  <a class="dsnav-b" href="PREV_FILE.html" title="Pichla page">←</a>
  <a class="dsnav-b" href="../index.html" title="Sab pages">⌂</a>
  <a class="dsnav-b" href="NEXT_FILE.html" title="Agla page">→</a>
</div>
<style>
.dsnav{position:fixed;right:14px;bottom:78px;z-index:650;display:flex;gap:6px;align-items:center;
  background:rgba(10,14,22,.86);backdrop-filter:blur(10px);border:1px solid rgba(255,255,255,.18);
  border-radius:30px;padding:6px 8px;box-shadow:0 10px 28px rgba(0,0,0,.45);opacity:.6;
  transition:opacity .2s,transform .2s;font-family:system-ui,sans-serif}
.dsnav:hover{opacity:1;transform:translateY(-2px)}
.dsnav-b{width:32px;height:32px;display:flex;align-items:center;justify-content:center;border-radius:50%;
  background:rgba(255,255,255,.09);color:#fff;text-decoration:none;font-size:15px}
.dsnav-b:hover{background:#ff9f45;color:#101820}
@media print{.dsnav{display:none}}
</style>
```

### 4. Hub me card add karo
Apne subject ke `index.html` me ek card copy karo:

```html
<a class="card" href="unit1/Python_Unit1.html" data-k="python unit1 basics variables">
  <div class="num">Unit 1</div>
  <h3>Python basics</h3>
  <p>Variables, loops, functions.</p>
  <div class="tags"><span class="tag g">New</span></div>
</a>
```
`data-k` me keywords likho — search usi se chalta hai.

### 5. Push karo
```bash
git checkout -b user/yourname-topic
git add .
git commit -m "ds: add session 5 (graphs)"
git push origin user/yourname-topic
```
Phir GitHub pe **Pull Request** banao.

---

## 🎨 Design system (consistency ke liye)

| Cheez | Value |
|---|---|
| Background (dark) | `#0f1420` – `#14100c` (har page ka apna, par dark) |
| Accent | ek primary + ek secondary (orange/cyan, terracotta/sage, plum/apricot…) |
| Fonts | headings: Chivo / Epilogue / Outfit · body: Figtree / Manrope · code: Azeret Mono / JetBrains Mono |
| Card radius | 12–16px |
| Animation | background me halki (blobs / aurora / diagonal lines) — text ke peeche, opacity kam |

**Har page ka apna rang** rakho — students ko lagta hai "aaj kuch naya hai".

---

## 📝 Content banane ka tarika (jo chal raha hai)

1. **Pehle problem, phir solution** — "yeh kyun banaya" se shuru karo
2. **Har cheez ka example** — 3 nodes ka chhota tree, 5 numbers ka array
3. **Tree/diagram har jagah** — text me "left child" likhne se samajh nahi aata
4. **Table har hisaab ke saath** — BF, height, passes, probes
5. **"Kahan use hota hai"** — har concept ke baad real use
6. **Code ki har line pe comment**
7. **Practice me jawab chhupe hue** — pehle khud socho

---

## 👥 Team

| Kaam | Kaun |
|---|---|
| DS pages | Divyansh |
| (doosre subjects) | apna naam yahan add karo |

---

## ⚠️ Note

- PYQ section online papers se compile kiya gaya hai (2020–2026) — apne college ke papers se ek baar cross-check kar lena
- 2027 prediction **pattern-based guess** hai, guarantee nahi
- Har page single file hai — 100–140 KB, phone pe bhi aaram se khulta hai
