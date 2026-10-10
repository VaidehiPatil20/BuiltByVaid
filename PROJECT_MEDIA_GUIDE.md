# Adding project media

Create `assets/projects/` and add approved images or video thumbnails.

For a project image, replace the relevant `<div class="visual">…</div>` block in `index.html` with `<div class="visual"><img src="assets/projects/your-image.jpg" alt="Descriptive project photo" style="width:100%;height:100%;object-fit:cover"></div>`.

For a video, add an accessible link to a public demo or use `<video controls preload="metadata" poster="assets/projects/poster.jpg" style="width:100%"><source src="assets/projects/demo.mp4" type="video/mp4"></video>` inside the case study. Prefer a linked video for large files.

Do not publish confidential company code, internal architecture, customer data, or non-approved photos. Verify rights to public photos.
