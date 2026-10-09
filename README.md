# Sara Zaleta website — version 0.3

Plain HTML/CSS/JS, no build step. Open `index.html` in a browser to preview.

## What's new in 0.3 (vs 0.2)
- Full-width banner photo above the quote on the home page.
- Piano lessons photo (`image1.jpeg`) and piano tuning photo (`piano.jpeg`) now sit to the right of their sections.
- 'Le Band': text and the six audio players on the left; six photos on the right in two columns (natural proportions, no cropping).
- Hero photo points to `sara and preshious baw.jpg`.
- Movies are not on the page yet (planned for a later step).

## Files the page expects (this zip contains NO images or audio)
Copy your existing `images/` and `audio/` folders into this folder, next to `index.html`.

images/
- `IMG_3699_banner.jpeg`   (banner)
- `sara and preshious baw.jpg`   (hero photo, next to "My La La Land")
- `image1.jpeg`   (piano lessons)
- `piano.jpeg`   (piano tuning)
- `IMG_0818.jpg`, `IMG_0785.jpeg`, `IMG_0465.jpeg`, `IMG_1223.jpeg`, `IMG_4286 (2).jpg`, `IMG_3794.JPG`   (Le Band, in this order)

audio/
- `sara_je_ne_regrette_rien_du_tout.mp3`, `deux_amours.mp3`, `super_nana.mp3`, `la_vie_en_rose.mp3`, `carment.mp3`, `la_complainte_du_phoque.mp3`

Names must match exactly, including capitalization and the extension (.jpg vs .jpeg vs .JPG). To use a different filename, edit the `src="..."` in `index.html` (write spaces as %20).

## Contact form
In `contact.html`, replace `YOUR_FORM_ID` in the form's `action` with your Formspree endpoint.
