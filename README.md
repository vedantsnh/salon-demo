# salon-demo
Responsive one-page salon website template with WhatsApp booking. Built with HTML, CSS and JavaScript.


# Glow Studio: Salon Website Demo

A fast, mobile-friendly one-page website template for salons and beauty parlours. This is a **demo project** with a fictional salon, built to show local businesses what their own website could look like.

**Live demo:** https://vedantsnh.github.io/salon-demo/

## Features

- Responsive design that works on phones, tablets and desktops
- Sections: hero, services, price list, "why choose us", gallery, contact
- **WhatsApp booking**: the form sends the customer's name, service and preferred time as a ready-made WhatsApp message
- Floating WhatsApp button on every screen
- Google Maps link for directions
- No frameworks, no build step, no backend. Just one HTML file
- Loads quickly and is free to host

## Tech

HTML, CSS and vanilla JavaScript. Hosted on GitHub Pages.

## Customise for a business

Open `index.html` and edit the `SITE` block near the top:

```js
const SITE = {
  name: "Glow Studio",
  tagline: "Salon & Beauty",
  phone: "919999999999",       // WhatsApp number with country code, no + or spaces
  displayPhone: "+91 99999 99999",
  address: "123 Sample Road, Kakkanad, Kochi, Kerala",
  hours: "Mon-Sat 10:00 AM - 8:00 PM | Sun 11:00 AM - 5:00 PM",
  mapsLink: "https://www.google.com/maps/search/?api=1&query=Kakkanad+Kochi",
  instagram: "https://instagram.com/",
  creditName: "Your Name",
  creditLink: "https://instagram.com/yourhandle"
};
```

Then:

1. Change the brand colour with `--accent` in the CSS at the top.
2. Update the services and prices.
3. Replace the gallery placeholders with real photos.

## Run locally

Download `index.html` and open it in any browser.


## Want a website like this for your business?

I build simple, affordable websites for local businesses.

- Instagram: @vedantsinha.snh(https://instagram.com/vedantsinha.snh)
- WhatsApp: +91 7782887734
- LinkedIn: Vedant Sinha(https://linkedin.com/in/vedantsnh)

*Built by Your VEDANT SINHA.*
