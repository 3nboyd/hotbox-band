# Hotbox band links

Hotbox's event link page, adapted from [bookingspage](https://github.com/3nboyd/bookingspage). It preserves the original layout, purple styling, payment destinations, and booking contact, with the band's photo and Instagram.

- Website: https://3nboyd.github.io/hotbox-band/
- Instagram: https://www.instagram.com/hotboxtheband/

## Local preview

```sh
python3 -m http.server 8000
```

Open http://localhost:8000. The site uses plain HTML, CSS, and JavaScript with no build step. GitHub Pages serves `main` from the repository root.

## Updates

- Edit `index.html` to change links, text, or the booking email.
- Edit `styles.css` to change styling and background blur.
- Replace `background.jpg` to change the band photo.
- `script.js` handles revealing and copying the booking email.
