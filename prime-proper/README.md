# Prime &amp; Proper Barber Co. — Website

A fast, responsive, single-page marketing site for **Prime &amp; Proper Barber Co.**, a
premium barbershop in Gilbert, AZ.

## Highlights

- **Google reviews as the anchor** — a 5.0 rating badge in the hero, a dedicated
  reviews section with customer quotes, and a "Read all reviews on Google" CTA.
  Includes `BarberShop` + `AggregateRating` structured data (JSON-LD) so the rating
  can surface in search.
- **Booksy booking, properly embedded** — the official Booksy widget for the shop
  (business ID `1703643`) loads on the booking section and renders a live "Book Now"
  button. A direct Booksy link is always present as a guaranteed-working fallback.
- **Sections:** hero, trust strip, reviews, services, barbers, booking, visit (with
  Google Map), footer.
- No build step. Pure HTML/CSS/JS.

## Files

| File | Purpose |
|------|---------|
| `index.html` | Page markup, content, SEO + structured data |
| `styles.css` | Dark, gold-accented premium barbershop theme (responsive) |
| `script.js` | Mobile nav, footer year, Booksy widget loader |

## Run locally

Open `index.html` in a browser, or serve the folder:

```bash
cd prime-proper
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Business details

- **Address:** 3107 S Gilbert Rd #109, Gilbert, AZ 85295
- **Booking:** [Booksy](https://booksy.com/en-us/1703643_prime-proper-barber-co_barber-shop_14704_gilbert)
- **Instagram:** [@primeproperbarberco](https://www.instagram.com/primeproperbarberco/)

> Service names are listed; exact prices are confirmed at checkout on Booksy. Update
> the review quotes, barber roster, and hours as needed before going live.
