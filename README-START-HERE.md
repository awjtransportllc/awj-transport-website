# A W J TRANSPORT LLC — Website Setup Guide
Everything below is free. Total time: about 30–40 minutes the first time.

Your login email for editing the site later: **awjtpt@gmail.com**

---

## PART 1 — Put the website online (one-time setup)

### Step 1: Create a GitHub account (free)
1. Go to **github.com** → click **Sign up**
2. Use your email: `awjtpt@gmail.com`
3. Verify your email when GitHub sends the confirmation

### Step 2: Create a new repository
1. Once logged in, click the **+** icon (top right) → **New repository**
2. Name it: `awj-transport-website`
3. Keep it **Public**
4. Click **Create repository**

### Step 3: Upload your website files
1. On the new repository page, click **uploading an existing file**
2. Drag in ALL the files and folders I gave you (`index.html`, `netlify.toml`, the `admin` folder, the `content` folder, and the `images` folder) — keep the folder structure exactly as-is
3. Scroll down, click **Commit changes**

### Step 4: Connect to Netlify (free hosting)
1. Go to **netlify.com** → **Sign up** → choose **Sign up with GitHub**
2. Click **Add new site** → **Import an existing project**
3. Choose **GitHub** → select your `awj-transport-website` repository
4. Leave all settings as default → click **Deploy site**
5. In 1–2 minutes, Netlify gives you a live web address like `https://random-name-123.netlify.app` — **your website is now live.**

### Step 5: Give it a proper free web address (optional)
1. In Netlify: **Site settings** → **Change site name**
2. Change it to something like `awjtransport` → your site becomes `awjtransport.netlify.app`
3. Later, if you want your own domain (e.g. `awjtransportllc.ae`), buy it from GoDaddy/Namecheap (~$10–20/year) and connect it under **Domain settings**. Hosting stays free either way.

---

## PART 2 — Set up your login access to edit the website

### Step 6: Turn on Identity
1. In Netlify: **Site configuration** → **Identity** → **Enable Identity**
2. Under **Registration preferences**, set to **Invite only**
3. Scroll to **Services** → **Git Gateway** → **Enable Git Gateway**

### Step 7: Invite yourself as the site editor
1. Still in **Identity**, click **Invite users**
2. Type: `awjtpt@gmail.com` → send invite
3. Check that Gmail inbox → accept the invite → set a password (save it somewhere safe)

### Step 8: Log in and edit your site
1. Go to `yoursite.netlify.app/admin`
2. Log in with `awjtpt@gmail.com` and your password
3. You can edit: hero headline/text, all 6 services, about section, phone numbers, emails, address, and swap the logo image
4. Click **Publish** — changes go live in ~30–60 seconds

**Bookmark `yoursite.netlify.app/admin`** — that's your permanent editing login.

---

## PART 3 — Where your quote requests go
The **"Request a Quote"** form is automatically connected to Netlify.
- Netlify dashboard → **Forms** tab shows every submission
- Turn on email notifications (Forms → Settings) so submissions land in `awjtpt@gmail.com`

---

## What's already done
✅ Your real logo is integrated in the header, footer, and about section
✅ Colors matched to your brand's gold and navy
✅ Your tagline "Trust · Transparency · Tranquility" is on the homepage

## What's next
- If you have real phone photos of your trucks, trailers, or office, send them — they build more trust than illustrations and I can swap them in
- Once the site is live, we can build the **truck & trailer maintenance tracker** as a separate tool (logging services, due dates, breakdowns per vehicle)
- I can help you set up **Google Business Profile** so you show up on Google Maps for logistics searches near Ras Al Khor

If you get stuck on any step, tell me the step number and what you're seeing — I'll walk you through it.
