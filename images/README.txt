DROP YOUR IMAGES IN THIS FOLDER USING THESE EXACT FILENAMES
============================================================

YOUR PHOTO (hero section):
  profile.jpg        <- a good photo of you (square-ish works best, e.g. 800x800).
                        .jpg or .png both fine, but keep the name "profile.jpg"
                        (if you use .png, tell me and I'll switch the extension)

CERTIFICATE IMAGES (the moving carousel in the Education section):
  cert-1.png  <- Foundations: Data, Data, Everywhere
  cert-2.png  <- Ask Questions to Make Data-Driven Decisions
  cert-3.png  <- Prepare Data for Exploration
  cert-4.png  <- Process Data from Dirty to Clean
  cert-5.png  <- Analyze Data to Answer Questions
  cert-6.png  <- Share Data Through the Art of Visualization

HOW TO ADD MORE CERTIFICATES (super easy):
  1. Drop the new image here as   cert-7.png   (then cert-8.png, etc.)
  2. In index.html, find the ALL_CERTS array (search "ALL_CERTS")
     and add ONE line:
       {img:'images/cert-7.png', name:'Your Cert Name', desc:'Issuer · Year'},
  3. That's it — it appears in the moving carousel automatically.

To add a big/important credential to the FLAGSHIP row instead, find
FLAGSHIP_CERTS in index.html and add a line there.

Notes:
- If an image is missing, that carousel card shows a small "Add cert-N.png"
  placeholder, so nothing ever looks broken.
- Shown in a 4:3 frame, top-aligned — a normal certificate screenshot fits great.
- Keep each file under ~1MB so the page stays fast.
