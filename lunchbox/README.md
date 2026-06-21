# The Lunchbox — Menu Website

## Project Structure

```
lunchbox/
├── index.html
├── css/
│   └── style.css
├── images/
│   ├── vegetarian-thali.jpg
│   ├── chicken-thali-mini.jpg
│   ├── chicken-thali.jpg
│   ├── egg-thali.jpg
│   ├── special-thali.jpg
│   ├── aloor-dum.jpg
│   ├── egg-tadka.jpg
│   ├── chicken-tadka.jpg
│   ├── shahi-paneer.jpg
│   ├── egg-bhuna.jpg
│   ├── chicken-kosha.jpg
│   ├── jeera-rice.jpg
│   └── basanti-pulao.jpg
└── README.md
```

## Adding Your Photos

Just take photos and save them into the `images/` folder with these exact filenames:

| Item | Filename |
|---|---|
| Vegetarian Thali | `vegetarian-thali.jpg` |
| Chicken Thali (Mini) | `chicken-thali-mini.jpg` |
| Chicken Thali | `chicken-thali.jpg` |
| Egg Thali | `egg-thali.jpg` |
| Special Thali | `special-thali.jpg` |
| Aloor Dum | `aloor-dum.jpg` |
| Egg Tadka | `egg-tadka.jpg` |
| Chicken Tadka | `chicken-tadka.jpg` |
| Shahi Paneer | `shahi-paneer.jpg` |
| Egg Bhuna | `egg-bhuna.jpg` |
| Chicken Kosha | `chicken-kosha.jpg` |
| Jeera Rice | `jeera-rice.jpg` |
| Basanti Pulao | `basanti-pulao.jpg` |

> Roti, Paratha, and Steamed Rice have no image slots — intentional.
>
> If an image is missing, a colored emoji placeholder shows automatically — no errors.

---

## Deploy to Vercel

### Option 1 — Vercel CLI (fastest)

```bash
npm i -g vercel
cd lunchbox
vercel
```

Follow the prompts. Your site is live in ~30 seconds.

### Option 2 — GitHub + Vercel (recommended for updates)

1. Push this folder to a GitHub repo
2. Go to [vercel.com](https://vercel.com) → New Project
3. Import the repo
4. Leave all settings as default and click **Deploy**

Done. Every time you push to GitHub, Vercel auto-redeploys.

---

## WhatsApp Order Flow

When a customer places an order, they are taken to WhatsApp with a pre-filled message like:

```
🍱 New Order — The Lunchbox

Name: Rahul Sharma
Location: 3rd floor, ABC Office, Salt Lake

Items:
• Chicken Thali × 2 — ₹232
• Aloor Dum × 1 — ₹60
• Roti (1 piece) × 4 — ₹28

Total: ₹320
```

Orders go to: **Number**
