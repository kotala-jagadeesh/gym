# College Gym Website

A one-page website for a college gym, built with plain HTML and CSS in a neon green and dark theme. There is no build step and no framework.

## Files

| File | Purpose |
|------|---------|
| `index.html` | The whole website (HTML, CSS and a small script in one file) |
| `README.md` | This guide |

## How to run

1. Download `index.html`.
2. Double-click it to open in any modern browser.
3. Stay connected to the internet so the images and fonts can load.

## What's on the page

- **Hero:** headline and two buttons (join and see the gym)
- **Facilities:** free weights, cardio zone, trainers, group classes
- **Opening hours:** a weekly timetable
- **Student plans:** monthly, semester and annual
- **Join form:** name, roll number, phone and plan
- **Footer:** address and contact email

## Customize it

Open the file in any text editor (VS Code, Notepad) and change the following.

**College name:** search for `Your College` and replace it. It appears in the page title, the logo and the footer.

**Prices and hours:** search for `₹` for the plans, and for `Opening hours` for the timetable.

**Colors:** edit the variables at the top of the `<style>` block.

```css
:root{
  --bg:#070a08;     /* page background */
  --panel:#0f1511;  /* cards and sections */
  --neon:#39ff6a;   /* neon green accent */
  --text:#e9f2ec;   /* main text */
}
```

**Images:** every image is an `<img src="https://images.unsplash.com/...">` tag, plus one background image in the `.hero` rule. Replace the URL with another online link, or with your own photo such as `images/gym1.jpg` placed next to the HTML file.

**Fonts:** Barlow Condensed (headings) and DM Sans (body), loaded from Google Fonts at the top of the file.

## Join form

The form currently only shows a thank-you message on the page. It does not save or send the details anywhere. To collect real sign-ups, connect it to a form service (such as Google Forms or Formspree) or to your own backend, by editing the `<form>` tag and the script at the bottom of the file.

## Notes

- The layout adapts to phones, tablets and desktops.
- Images and fonts need an internet connection. Offline, the page still works with fallback fonts and dark image boxes.
- The prices, hours and email are example values. Replace them before publishing.
- The photos come from Unsplash. Check their license terms before using the site commercially.
