# JMC Brown Inc Website

Simple, modern, mobile-friendly static website for JMC Brown Inc lawn care & landscaping.

## Pages
- **Home** (`index.html`) - Hero, services, featured work, CTAs
- **About** (`about.html`) - About Jeremy Brown / the company
- **Equipment** (`equipment.html`) - Kubota machines & attachments
- **Request Service** (`contact.html`) - Contact options + form

## Tech
- Pure HTML + Tailwind CSS (CDN) + small custom CSS/JS
- No build step required
- Fully responsive / mobile-friendly
- Easy to edit - just open the HTML files

## Contact Info Used
- Phone: 704-787-5394
- Email: jbrown8601@gmail.com
- Company: JMC Brown Inc (Fully Insured)

## Form Setup (Important)
The contact form is wired for [Formspree](https://formspree.io) (free tier works great).

1. Go to https://formspree.io and create a free account
2. Create a new form
3. Copy the form endpoint (looks like `https://formspree.io/f/xxxxxxxx`)
4. Open `contact.html` and replace `YOUR_FORM_ID` in the form `action` attribute

Until you do that, the form shows a helpful message directing people to call/email.

Alternatively you can change the form to a simple `mailto:` if preferred.

## Deploy to Vercel (recommended)

1. Create a new GitHub repository
2. Upload / push the contents of this folder
3. Go to [vercel.com](https://vercel.com) → New Project → Import the repo
4. Deploy (zero config needed for static sites)

Or drag-and-drop the folder on Vercel’s dashboard.

## Local Preview
Just open `index.html` in a browser, or run a simple static server:

```bash
npx serve .
# or
python3 -m http.server 8000
```

## Customizing
- Colors: Edit the `brand` colors in the Tailwind config script in each HTML head, or the CSS variables in `css/styles.css`
- Content: Edit the HTML files directly - they are clean and well-commented
- Images: Replace files in the `images/` folder (keep the same filenames or update the `src` attributes)

---
Built for easy maintenance and fast loading.
