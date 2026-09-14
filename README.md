# Gagarin Parma — concept demo

High-end unsolicited concept demo for **Gagarin ГАГАРИН**, a cocktail bar in Parma's Oltretorrente. The project demonstrates the **Punto Due Studio — Crescita (€700)** tier.

> Concept dimostrativo non commissionato. This repository does not imply approval, endorsement, or affiliation by Gagarin.

## Project approach

The site intentionally stays within Crescita scope: one focused, conversion-oriented page rather than unnecessary routes or advanced application features. The visual direction is built around the real venue's established space/Soviet/cyrillic identity instead of applying a generic bar template.

## Stack

- Semantic HTML5
- Modular CSS
- Small vanilla JavaScript layer
- Static Netlify-ready deployment
- No framework, database, backend, authentication, CRM, customer accounts, custom booking engine, loyalty system, payments, or admin dashboard

## Structure

- `index.html` — positioning, venue story, cocktails, events, social proof, contact/location
- `styles.css` — CSS entry point
- `assets/base.css` — global design system, header and hero
- `assets/story.css` — story and differentiators
- `assets/cocktails.css` — cocktail section
- `assets/events.css` — events/social-proof section
- `assets/visit-footer.css` — contact, map illustration and footer
- `assets/tablet.css`, `assets/mobile.css` — responsive behavior
- `script.js` — mobile navigation, sticky-header state and reveal interactions
- `404.html` — branded 404 page
- `_headers` — basic Netlify security/privacy headers
- `assets/favicon.svg` — custom favicon

## Verified public information used

- Business: **Gagarin ГАГАРИН**
- Category: cocktail bar
- Address: **Strada Giovanni Inzani 3/A, 43125 Parma PR**
- Phone: **+39 0521 196 7803**
- Instagram: **@gagarinparma**
- Opening reported in **2021**
- Local coverage identifies **Michele and Alessio** as the people managing the venue
- Public reporting describes the venue's Cyrillic/Soviet-space interior identity and suspended rocket/missile decor
- Publicly reported cocktail references include **Sputnik**, **Gagarino** (recipe described as secret), and a drink using a **popcorn infusion**
- Public reporting documents live music, DJ sets, karaoke, open mic, reggae and themed/cultural evenings

### Public research sources

1. Restaurant Guru — current business listing, address, phone, category, hours, Instagram reference and public reviews: https://restaurantguru.it/Gagarin-Parma
2. Made in Parma — venue background, 2021 opening, management, identity, named cocktails and event formats: https://www.madeinparma.com/it/news/gagarin-oltretorrente-cirillico
3. Parma Parallela — more recent reporting on management, audience and event activity: https://parmaparallela.it/la-linea-sottilissima-di-piazzale-inzani/
4. Parma Partecipa — 2026 evidence of Gagarin representation in Oltretorrente neighbourhood activity: https://parmapartecipa.comune.parma.it/assemblies/quartiere-Oltretorrente/f/25/meetings/203

## Accuracy decisions

Public directories do **not** fully agree on exact opening/closing times. For that reason the customer-facing demo states only the consistent high-level pattern — evening opening Tuesday through Sunday, Monday closed — and asks visitors to verify current hours on official channels.

The demo deliberately does not invent:

- a complete menu;
- cocktail ingredients not made public;
- current prices;
- WhatsApp availability;
- a booking provider;
- legal/VAT information;
- future event dates;
- a contact-form backend;
- official venue photography rights.

## Crescita features demonstrated

- Custom business-specific visual system
- Mobile-first responsive composition
- Accessible navigation and keyboard focus states
- `prefers-reduced-motion` support
- Verified click-to-call
- Google Maps directions CTA
- Official Instagram CTA
- Strong conversion hierarchy
- Basic SEO title/meta/social metadata
- Factual `BarOrPub` JSON-LD
- Favicon
- Custom 404
- Netlify security headers
- Unsolicited-concept disclosure

## Evoluzione opportunities intentionally excluded

A future higher-tier project could add a lightweight event/menu CMS, structured event publishing, richer analytics, CRM/automation or reservation integrations after requirements and permissions are confirmed with the business. None of these are implemented in this Crescita demo.

## Local development

No dependencies are required. From the repository root:

```bash
python -m http.server 8080
```

Then open `http://localhost:8080`.

## Netlify deployment

This is a zero-build static project.

Recommended Netlify settings:

- **Base directory:** leave empty
- **Build command:** leave empty
- **Publish directory:** repository root (`.`)
- **Functions directory:** leave empty

After Netlify assigns the final public domain, production SEO can be completed by adding the exact canonical URL, `og:url`, and a sitemap containing that domain.

## Production checks still requiring the business

Before an official launch, confirm directly with Gagarin:

- exact current opening hours;
- current drinks/food offer and prices;
- preferred reservation/contact flow;
- whether the public phone number also supports WhatsApp;
- legal/privacy information required by any future tracking/forms;
- permission/licensing for official photography;
- final approved copy and branding.
