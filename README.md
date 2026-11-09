# readflowsaraiquest

The ReadFlow project page: one static `index.html`, served by GitHub Pages.

## Editing the site without code

PlayLabs photos, team members, testimonials, the two recognition photos, and the
numbers and links all live in `content/*.json`. You edit them in a web editor at
**`/admin/`** on the live site, and every save goes live in about a minute.

### One-time setup: make an access token

1. On GitHub, go to **Settings → Developer settings → Personal access tokens → Fine-grained tokens → Generate new token**.
2. Name it `ReadFlow site editor` and pick an expiry (one year is fine).
3. Under **Repository access**, choose **Only select repositories** and pick `readflowsaraiquest`.
4. Under **Permissions → Repository permissions**, set **Contents** to **Read and write**.
5. Generate the token and copy it. Keep it private, like a password.

### Every time you edit

1. Open **https://saraideshmukh7.github.io/readflowsaraiquest/admin/**
2. Choose **Sign In Using Access Token** (not "Sign In with GitHub", which isn't set up) and paste your token. Your browser remembers it.
3. Open **Website content** and pick what to change:
   - **ReadFlow PlayLabs**: add a session (title, school name, city, date, caption) and as many photos from it as you like. Each session gets its own sideways-scrolling row of photos. The newest goes first; drag to reorder.
   - **Team members**: add a photo, name and position, plus an optional bio and link. With no photo, the card shows initials.
   - **What others say**: add a quote, a name and who they are. The section appears on the page once the first one is added.
   - **Official recognition photos**: the two photos beside the Zilla Parishad recognition.
   - **Logo, numbers & links**: the logo at the top, students impacted, local schools, Instagram, LinkedIn, contact email.
4. Press **Save**. Photos from your phone are shrunk and converted to WebP automatically.

## "Join the team" form

Applications are emailed to the address in **Logo, numbers & links → Email that receives applications**,
using the free [FormSubmit](https://formsubmit.co) service. The very first application sends a
one-time **activation email** to that address: click **Activate** in it once, and every later
application arrives as a normal email. Send yourself a test application right after this goes live.
