# Maniar Eye Clinic — Website

A simple, one-page website for Maniar Eye Clinic (Dr. Nittal Maniar). No coding
knowledge is required to edit or publish it.

## Files in this folder

```
index.html      -> the page content (text, layout)
style.css       -> the page design (colors, fonts, spacing)
script.js       -> small interactive behaviors (menu, flip cards) — no need to touch this
images/         -> put your logo and photos here
README.md       -> this file
```

## 1. Editing the content

Open `index.html` in any text editor (Notepad, TextEdit, or Notepad++/VS Code
if you have them). Every place you should personalize is marked with a
comment that looks like:

```
<!-- EDIT: hero headline -->
```

Just replace the text right below/near that comment. Look for these sections:

- **Hero headline & intro** — near the top
- **About / bio** — short paragraph about Dr. Maniar
- **Qualifications** — a bullet list, one line each (add or remove `<li>...</li>` lines freely)
- **Services** — 3 flip cards; each has a short front summary and a longer back description
- **Location / Address** — the clinic address, plus an optional Google Maps embed
- **Contact** — phone, email, and clinic hours

Save the file after editing, then double-click `index.html` (or refresh your
browser tab) to see your changes.

## 2. Adding your photos and logo

Put two image files inside the `images` folder, named exactly:

- `images/logo.png` — your clinic logo
- `images/doctor.jpg` — a photo of Dr. Nittal Maniar

The logo appears in the header, the footer, and as the browser tab icon. The
doctor photo appears in the hero banner and the About section. If a file
isn't there yet, the page shows a tidy placeholder box instead of breaking —
so you can add photos whenever they're ready.

(If your files have different extensions, e.g. `.jpeg` or `.jpg` for the
logo, either rename them to match exactly, or open `index.html`, search for
`images/`, and update the file names there.)

## 3. Adding a Google Map (optional)

In the **Location** section of `index.html`, there's a comment explaining
how: go to Google Maps, search for your clinic (or its address), click
**Share → Embed a map**, copy the code it gives you, and paste it in where
the comment says.

## 4. Publishing the site with GitHub Pages

GitHub Pages hosts static websites like this one for free. Here's the
easiest way to do it, entirely through the GitHub website (no command line
needed).

### Step 1 — Create a GitHub account
Go to https://github.com and sign up if you don't already have an account.

### Step 2 — Create a new repository
1. Click the **+** icon (top right) → **New repository**.
2. Name it something like `maniar-eye-clinic`.
3. Set it to **Public** (GitHub Pages requires a public repo on free plans).
4. Leave "Add a README" unchecked (you already have one).
5. Click **Create repository**.

### Step 3 — Upload your files
1. On your new repository's page, click **Add file → Upload files**.
2. Drag in all the files and folders from this project:
   `index.html`, `style.css`, `script.js`, `README.md`, and the `images`
   folder (with your logo and photo inside it).
3. Scroll down and click **Commit changes**.

### Step 4 — Turn on GitHub Pages
1. In your repository, click **Settings** (top menu).
2. In the left sidebar, click **Pages**.
3. Under "Build and deployment" → **Source**, choose **Deploy from a branch**.
4. Under **Branch**, choose `main` and folder `/ (root)`, then click **Save**.
5. Wait about a minute, then refresh the page. GitHub will show you a live
   URL, something like:
   `https://your-username.github.io/maniar-eye-clinic/`

That's your live website — share that link with anyone.

### Making future updates
Whenever you want to change text or swap a photo:
1. Go to your repository on GitHub.
2. Click the file you want to change (e.g. `index.html`), then click the
   pencil (✏️) icon to edit it directly in the browser — or delete/re-upload
   an image in the `images` folder.
3. Click **Commit changes**.
4. Your live site updates automatically within a minute or two.

## 5. Previewing changes before publishing (optional)

You can always just double-click `index.html` on your computer to preview it
in your browser before uploading anything to GitHub — no server needed.
