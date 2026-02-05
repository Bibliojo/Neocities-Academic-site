## About This Tutorial

This tutorial walks you through creating a **small, handmade academic website** using **Neocities**, basic **HTML**, and a **single CSS stylesheet**.

The goal is *not* to build a “perfect” website, nor to rely on platforms or templates that hide how the web works. Instead, this exercise focuses on **learning by doing**: writing simple code, seeing immediate results, and understanding how structure and style come together to form a site. Also this is *FUN* at least I think so :)

---

## What You’ll Build

You will create a straightforward academic web presence with pages for:

- a homepage  
- a CV  
- publications  
- teaching  
- projects  
- contact information  

All pages will share the same layout and design, controlled by **one CSS file**.

You will copy and paste code directly into Neocities, edit it in the browser, and watch your site take shape in real time.

---

## Why Neocities?

This approach is deliberately **small-scale and transparent**.

Neocities gives you full control over your files, avoids advertising and supports long-term preservation of web content. It also makes the underlying structure of the web visible:

- files  
- links  
- folders  
- stylesheets  

—not dashboards or hidden settings.

---

## What You’ll Learn

You do **not** need prior experience with HTML or CSS to complete this tutorial. You will be introduced to:

- basic HTML tags  
  *(headings, paragraphs, lists, links)*

- semantic page structure  
  *(header, navigation, main content, footer)*

- external CSS for styling  
  *(text, layout, spacing, colour)*

While we will review concepts together during the session, this page is designed as a **quick reference** you can return to later. You can work through it at your own pace, copy sections as needed, and adapt the site structure for your own academic or creative work.

---

## By the End of This Tutorial

You will have:

- a live website hosted on Neocities  
- a basic understanding of how HTML and CSS interact  
- a foundation you can extend, personalize, and preserve over time  

Think of this site as a **starting point**, not a finished product —  
a *handmade academic home on the small web*.

# Setting Up a Neocities Website (Beginner Walkthrough)

This guide walks you step by step through creating a simple website on **Neocities** using basic HTML and CSS.  
No prior web experience is required.

You will work directly in the browser, copying and pasting code, saving files, and seeing results immediately.

---

## What You Need

Before you begin, make sure you have:

- a computer with a web browser  
- an internet connection  
- a free Neocities account  

No software installs. No command line. No templates.

---

## Step 1: Create a Neocities Account

1. Go to https://neocities.org  
2. Click **Sign Up**  
3. Choose:
   - a username  
     - your site will live at  
       `https://yourusername.neocities.org`
   - an email address  
   - a password  
4. Click **Create Account**

You now have a website, even if it’s empty.

---

## Step 2: Understand the File Manager

After logging in, you will see the **File Manager**.

This is where your website lives.

You are working directly with:
- files  
- filenames  
- folders  

Think of this as a folder on your computer — but online.

---

## Step 3: Create or Open `index.html`

Every website needs a file called `index.html`.

1. In the File Manager:
   - if `index.html` exists, click it  
   - if it does not exist:
     - click **New File**
     - name it exactly:
       ```
       index.html
       ```

Spelling and capitalization matter.

---

## Step 4: Paste in Starter HTML

1. Open `index.html`
2. Delete any existing content
3. Paste in the starter HTML code from the tutorial
4. Click **Save**

Now open a new browser tab and visit:

https://yourusername.neocities.org


You should see your page live on the web.

---

## Step 5: Edit → Save → Refresh

This is the basic workflow:

1. Edit text in `index.html`
2. Click **Save**
3. Refresh your site in the browser

If changes do not appear, do a hard refresh:
- Mac: `Cmd + Shift + R`
- Windows: `Ctrl + Shift + R`

---

## Step 6: Add a CSS File

CSS controls how your site looks.

### Create `style.css`

1. In the File Manager, click **New File**
2. Name it:
style.css
3. Open the file
4. Paste in the starter CSS
5. Click **Save**

---

## Step 7: Link CSS to HTML

3. Paste in the starter CSS
4. Click **Save**

---

## Step 7: Link CSS to HTML

Inside `<head>` in `index.html`, add:

<link rel="stylesheet" href="style.css">

## Step 8: Create More Pages

Duplicate `index.html` to create additional pages:

- `cv.html`
- `publications.html`
- `teaching.html`
- `projects.html`
- `contact.html`

On each page:
- update the page title
- replace the main content with page-specific text

All pages share the same design through `style.css`.
## Step 9: Link Pages Together

Links between pages look like this:

<a href="cv.html">CV</a>
<a href="publications.html">Publications</a>
<a href="teaching.html">Teaching</a>

## Final Thought

Voilà! You now have an **academic profile** that is:

- unique to you  
- easy to manage and update  
- built from simple, transparent files  

Make changes. Experiment. Revise as your work evolves.

---

## Preserving Your Site (Internet Archive)

You can ask the **Internet Archive’s Wayback Machine** to save a copy of your site for long-term preservation.

1. Go to: https://web.archive.org  
2. In the **“Save Page Now”** box, enter your site URL:  https://yourusername.neocities.org
3. Click **Save Page**

To archive additional pages (for example `cv.html` or `publications.html`), repeat the process using their full URLs.

Archiving your site ensures that a snapshot of your work is preserved, even if you later make changes or move platforms.

---

## Moving or Re-Using Your Site

Your Neocities site is made of ordinary files, which means it is **portable**.

You can:

- download your HTML and CSS files from Neocities  
- save them to your computer or cloud storage  
- reuse them on another hosting service  
- adapt them for a different project or platform  

Because your site is built with standard HTML and CSS, it is not locked to any single service. You can take it with you.

---

A handmade academic website is never finished — it grows alongside your work.

