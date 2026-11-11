donoholdings.com website files
==============================

Upload everything in this folder to your site's main folder (on Bluehost: File Manager -> public_html),
keeping the folders as they are. The pages then live at:

  https://donoholdings.com/            home page
  https://donoholdings.com/solitrio/   SoliTrio app page   (App Store "Marketing URL")
  https://donoholdings.com/support/    support page        (App Store "Support URL")
  https://donoholdings.com/privacy/    privacy policy      (App Store "Privacy Policy URL")

If you already have a home page you want to keep, skip index.html.

Before going live:
  - Create the mailbox support@donoholdings.com (Bluehost -> Email), or replace that address in
    privacy/index.html, support/index.html and index.html.
  - The "Download on the App Store" link points to SoliTrio's App Store page and starts working
    once Apple releases the app.

If your site is built with WordPress instead of plain files, create pages with the slugs
"privacy", "support" and "solitrio", add a Custom HTML block to each, and paste the content
between <main ...> and </main> from the matching file. The styling then comes from your theme.
