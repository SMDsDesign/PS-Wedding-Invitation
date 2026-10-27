PRATIKSHA & SANDEEP · WEDDING INVITATION WEBSITE
================================================

WHAT'S IN THIS FOLDER
  index.html            the invitation (English / Marathi, day & night mode, countdowns)
  door.webp, darshan.webp, crest.webp   page images
  og-image.jpg          the portrait link-preview picture (1000 x 1453, 245 KB)
  song.mp3              background music (starts when a guest taps the doors; button top-left to pause)
  favicon.png, apple-touch-icon.png      browser tab / home-screen icon

TO GET THE PORTRAIT PREVIEW ON WHATSAPP
  1. Upload this whole folder (all files together) to any web host that gives an https address:
     Netlify Drop (app.netlify.com/drop - drag the folder in), GitHub Pages, Vercel, or your own domain.
  2. Open index.html in a text editor and replace every
         https://YOUR-DOMAIN.com/
     with your real address, ending in a slash, e.g.  https://pratiksha-sandeep.netlify.app/
     (It appears 5 times: og:url, og:image, og:image:secure_url, twitter:image.)
  3. Upload the edited index.html again.
  4. Check the preview: paste the link into https://developers.facebook.com/tools/debug/ and click "Scrape Again".
  5. Then paste the link in WhatsApp. Wait a second for the preview card before sending.

GOOD TO KNOW
  - WhatsApp remembers a preview the first time a link is shared. If you change the image later,
    share the link with ?v=2 at the end (e.g. .../?v=2) so WhatsApp fetches it fresh.
  - Each app decides how much of a tall image to show: Telegram and iMessage show more of a portrait image;
    WhatsApp and Facebook may crop it towards a landscape or square frame.
  - For the full portrait card every time: send og-image.jpg as a photo with the link in the caption.
  - If you host on Wix using an HTML embed, Wix ignores these tags. Set the picture in that Wix page's
    SEO / Social Share settings instead.
