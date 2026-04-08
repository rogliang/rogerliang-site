# Roger Liang Personal Site

Simple static one-page site for `rogerliang.com`.

## Files

- `index.html`: page content and contact form
- `styles.css`: layout and visual styling
- `assets/headshot.jpeg`: portrait image

## Local preview

From this folder:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## Contact form

The form currently posts to `formsubmit.co` using `roger@rogerliang.com`.

Before going live, confirm:

- `roger@rogerliang.com` can receive mail
- you want to keep using FormSubmit, or swap to Formspree / Netlify Forms later
- the `_next` URL should stay as `https://rogerliang.com/?message=sent`
