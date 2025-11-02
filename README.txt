PSPPORT V2 - Static site package (Premium)
------------------------------------------
Files:
- index.html, about.html, products.html, contact.html
- assets/styles.css
- assets/images/* (your images + logo SVG)
- assets/videos/* (your uploaded videos)

How to use:
1. Open the folder in Visual Studio Code to preview.
2. To publish on GitHub Pages:
   - Create a GitHub repo.
   - Upload all files to repository root (or use GitHub Desktop to publish).
   - In repo Settings → Pages, select branch 'main' and folder '/' (root).
   - Add a CNAME file or set custom domain to pspport.com in Pages settings.
3. To connect domain, update DNS (CNAME for www, A records for apex) at your registrar.
<!-- Logo Section -->
<div style="text-align:center; margin-top:20px;">
  <img src="images/logo.png" alt="PSP Imports & Exports Logo" style="width:180px; height:auto;">
</div>

<!-- About Us Video Section -->
<div style="text-align:center; margin-top:30px;">
  <h2>Watch Our Story</h2>
  <video width="600" controls autoplay loop muted style="border-radius:10px;">
    <source src="videos/about.mp4" type="video/mp4">
    Your browser does not support the video tag.
  </video>
</div>
