# Ariel Sadan — Personal Portfolio

A responsive personal portfolio designed for GitHub Pages. The home page centers on Ariel, while the Projects tab can grow over time. GT Movies Store has its own case-study page containing the required assignment material.

## Site structure

- `index.html` — personal home, interests, featured project, and contact
- `projects.html` — expandable collection of projects
- `movies-store.html` — GT Movies Store case study, process, screenshots, and demo
- `style.css` — design and responsive layout
- `script.js` — mobile menu, year, and reveal effects

## Before submitting

1. Open `index.html` and personalize the introduction, interests, contact links, and name if needed.
2. Replace the portrait placeholder with a professional photo. Add `assets/profile.jpg`, then replace the `.portrait-placeholder` block with `<img class="profile-photo" src="assets/profile.jpg" alt="Portrait of Ariel Sadan">`.
3. Open `movies-store.html` and rewrite the overview and process so every statement accurately reflects your work.
4. Replace the four sample user stories with the exact user stories from your assignment/project.
5. Add screenshots to an `assets` folder. Suggested names:
   - `home-page.png`
   - `movie-detail.png`
   - `cart.png`
   - `orders.png`
6. Replace the placeholder gallery blocks in `movies-store.html` with images. Example:

   ```html
   <figure class="screen-placeholder">
     <img src="assets/home-page.png" alt="GT Movies Store catalog page showing movie search results">
     <figcaption>Catalog browsing and search</figcaption>
   </figure>
   ```

7. Upload the demo video to YouTube as **Unlisted**. Replace the `.video-placeholder` block with:

   ```html
   <iframe
     class="video-embed"
     src="https://www.youtube.com/embed/YOUR_VIDEO_ID"
     title="GT Movies Store demonstration"
     allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
     allowfullscreen>
   </iframe>
   ```

   Then add this rule to `style.css`:

   ```css
   .video-embed { width: 100%; aspect-ratio: 16/9; border: 0; border-radius: var(--radius); }
   ```

8. Proofread every page and check the site on both desktop and mobile.

## Add another project later

1. Duplicate `movies-store.html` and rename it for the new project, such as `security-tool.html`.
2. Replace the case-study text and images in the duplicated page.
3. Duplicate the GT Movies Store `<article class="project-row">` block in `projects.html`.
4. Change the card title, description, tags, and links to point to the new page.

## Publish free with GitHub Pages

1. Create a new public GitHub repository, such as `gt-movies-portfolio`.
2. Upload all three HTML files, `style.css`, `script.js`, and your `assets` folder to the repository root.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and `/ (root)`, then click **Save**.
6. GitHub will show the public URL after the deployment completes.

Keep the repository and published site accessible to the instructional team for the full semester.
