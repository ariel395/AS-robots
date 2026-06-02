# Arcade Strange Landing Page

## How to change images

Open the `assets` folder and replace any image with the same filename:

- `homer.png`
- `mindvault.png`
- `matilda.png`
- `gamified-vending.png`
- `arcade-strange-logo.png`

Keep the filename the same and the website will update automatically.

If you want to use a different filename, open `index.html` and change the `src`, for example:

```html
<img src="assets/my-new-homer-image.png" alt="Homer mind-controlled drinks-pouring robot" />
```

## How to put it online with GitHub Pages

1. Create a new GitHub repository.
2. Upload all files in this folder, including `index.html` and the `assets` folder.
3. Go to Settings → Pages.
4. Under Source, choose Deploy from branch.
5. Choose `main` and `/root`.
6. Click Save.

Your site will be online in a few minutes.

## Contact form note

The form uses FormSubmit:

```html
action="https://formsubmit.co/hello@arcadestrange.com"
```

To change the receiving email, replace `hello@arcadestrange.com` with your email.
