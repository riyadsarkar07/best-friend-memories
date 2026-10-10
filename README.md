# Best Friend Memories

A static friendship website for Rhian Umali, from Dhaka to the Philippines.

Open `index.html` in a browser, or import this repository into Vercel as a static site. No build step is required.

## What you will see

1. A locked flower-growing intro on a dark background. The "Step Inside" button fades it out and opens the cream main site.
2. Hero with a friendship day counter.
3. Dhaka to Philippines distance map, live clocks, and countdown cards.
4. Timeline, photo gallery, and an opening letter.
5. Paper-plane notes you can write and send across the sky.
6. A stylized friendship recipe card.
7. A lantern wish at the end.

## Local preview

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## Deploy on Vercel

1. Open [vercel.com/new](https://vercel.com/new) and import `riyadsarkar07/best-friend-memories`.
2. Framework Preset: Other.
3. Root Directory: `.`
4. Leave Build Command and Output Directory empty.
5. Deploy. Later pushes to `main` will auto-deploy if GitHub is connected.

## Photos

Place images here if you want the gallery to show real photos:

```
images/1.jpg
images/2.jpg
images/3.jpg
images/4.jpg
```

Missing files fall back to a gold-pink gradient.

## Edit content

Names, dates, letter text, plane notes, and the recipe live in the `CONFIG` object inside `index.html`. Do not change the flower intro block (`#flower-intro`, `#flowerCanvas`, and the flower-growing script).
