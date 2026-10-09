# Adrián Pereyra

Web software developer | Python + AI | E-commerce and custom platforms | Digital and content marketing

I build **websites and tools with Python and artificial intelligence**, from the idea to a site running online. I also create and manage **digital and content marketing**: Facebook and Instagram pages, images, copy and videos for advertising.

Mendoza, Argentina

---

## Featured project: MenduEbook

[![MenduEbook](imagenes/menduebook.jpg)](https://mendumarket.com.ar)

**A platform that uses AI to create a complete PDF ebook and its sales page, ready to sell.** The customer enters a topic and within minutes receives the designed book (guide, recipe book or coloring book), the sales landing page and instructions to publish it. It takes payments through Mercado Pago, has an admin panel, translates into other languages and runs on its own server. It has already generated more than 60 books.

**Python · Flask · Claude API · OpenAI API · SQLite · Mercado Pago · Google login · Ubuntu server**

[Visit the site](https://mendumarket.com.ar) · [Screenshots, examples and code](https://github.com/adrian884hub/mendu-market-portfolio)

---

## Other projects

### GastoRegistrado: automatic expense log
![GastoRegistrado](imagenes/gastoregistrado.jpg)

A web app that automatically records purchases and payments from every digital wallet by reading the phone's notifications, and shows them in a single list with date, amount, merchant and wallet. It installs on the phone as an app.

**Next.js · TypeScript · Supabase (PostgreSQL) · Tailwind CSS · Vitest · Vercel** · *Private code (it handles personal data). A real excerpt: the part that reads the amount from any notification.*

```ts
// "$ 1.000", "$400", "$ 300,00", "US$ 20", "U$S 20"
const IMPORTE = /(US\$|U\$S|USD|\$)\s?(\d{1,3}(?:\.\d{3})+(?:,\d{1,2})?|\d+(?:[.,]\d{1,2})?)/i;

export type TipoLectura =
  | "gasto"        // money going out to another person or merchant
  | "propia"       // transfer between my own wallets: not an expense
  | "entrada"      // money coming in
  | "dudosa"       // has an amount but direction is unclear
  | "sin_importe"; // promotions and notices: ignored
```

### Restaurante Los Olivos: website for a restaurant
[![Restaurante Los Olivos](imagenes/restaurante-los-olivos.jpg)](https://adrian884hub.github.io/restaurante-los-olivos/)

Sample site for a restaurant in Mendoza: photo carousel, tabbed menu, reservations sent through WhatsApp and mobile-first design. Includes test cases and bug reports (QA).

**HTML · CSS · JavaScript** · [View the page](https://adrian884hub.github.io/restaurante-los-olivos/) · [Code](https://github.com/adrian884hub/restaurante-los-olivos)

### 30 Keto Recipes: ebook sales landing page
[![30 Keto Recipes](imagenes/recetas-keto.jpg)](https://adrian884hub.github.io/recetas-keto/)

Sales page for a recipe ebook, designed to turn visits into purchases.

**HTML · CSS · JavaScript** · [View the page](https://adrian884hub.github.io/recetas-keto/) · [Code](https://github.com/adrian884hub/recetas-keto)

### Mendu Market help center
[![Help center](imagenes/faq-mendu-market.jpg)](https://adrian884hub.github.io/faq-mendumarket./)

Frequently asked questions about payments, shipping and returns for the Mendu Market online store, with WhatsApp contact.

**HTML · CSS · JavaScript** · [View the page](https://adrian884hub.github.io/faq-mendumarket./) · [Code](https://github.com/adrian884hub/faq-mendumarket.)

### TradingView indicators
![Zonas Rebote + Volumen indicator running on TradingView](imagenes/indicador-tradingview.jpg)

Two technical analysis indicators in Pine Script: automatic support and resistance detection with scoring, volume profile, buy and sell signals by confluence, automatic Stop Loss and Take Profit, and a price heat map.

**Pine Script v5** · [Bounce Zones + Volume](https://github.com/adrian884hub/indicador-zonas-rebote-volumen) · [SR Confluence + Heat Map](https://github.com/adrian884hub/indicadores-tradingview-1-)

### Game Booster: PC cleaner and optimizer
<img src="imagenes/game-booster.png" alt="Game Booster icon" width="160">

Desktop program that prepares the PC for gaming: cleans temporary files, closes background processes and frees memory with a single button.

**Python · Tkinter · PyInstaller** · [Code](https://github.com/adrian884hub/game-booster)

---

## What I do

- Websites and sales pages
- Platforms with online payments (Mercado Pago)
- Python tools and automation
- Artificial intelligence integrations (Claude, OpenAI)
- Digital and content marketing for social media
- TradingView indicators (Pine Script)

## Contact

**Available for projects and work.** Get in touch and let's talk.

- Email: [adrianpereyra884@gmail.com](mailto:adrianpereyra884@gmail.com)
- WhatsApp: [+54 261 637-3263](https://wa.me/542616373263)
