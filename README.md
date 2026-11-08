# Abdellah Bencherif — Portfolio Website

A responsive, single-page portfolio made with plain HTML, CSS and JavaScript. It is designed for GitHub Pages and can be edited freely.

## Preview locally
Open `index.html` in a browser.

## Publish with GitHub Pages
1. Sign in to GitHub and create a new **public** repository named `abdellah-portfolio` (or `<your-username>.github.io`).
2. Upload all files and folders from this package. Keep `index.html` in the repository root.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch **main** and folder **/(root)**, then Save.
6. Wait a minute or two. GitHub will show your live website address in the Pages section.

## Edit your website
- Text and sections: edit `index.html`.
- Colors, spacing and layout: edit `style.css`.
- Menu and small interactions: edit `script.js`.
- Profile photo: create an `assets` folder, add your image as `profile.jpg`, then replace the `.portrait-placeholder` block in `index.html` with:
  `<img class="profile-photo" src="assets/profile.jpg" alt="Abdellah Bencherif">`
  Add this to `style.css`:
  `.profile-photo{width:100%;height:100%;object-fit:cover;border-radius:inherit}`
- CV: create an `assets` folder and upload your PDF as `Abdellah_Bencherif_CV.pdf`. The Download CV button already points there.

## Important
The website currently uses the details available from your CV and our conversation. Before publishing, verify all job dates, titles and certificate names. Add your own photo and CV PDF. Do not publish personal information you do not want public.
