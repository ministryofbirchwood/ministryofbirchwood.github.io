MINISTRY OF BIRCHWOOD WEBSITE

Files included:
- index.html
- styles.css
- assets/birchwood-seal.png
- assets/reverend-birch.png

WHAT IS ALREADY DONE
- The footer year updates automatically.
- The contact form is designed and built.
- Your personal email address is NOT written anywhere in the website source.

ONE-TIME CONTACT FORM SETUP
The form uses Formspree because GitHub Pages itself cannot send email.
Formspree currently has a free tier with up to 50 submissions per month and uses an opaque form ID, so visitors and spam bots do not see your personal email address in the website HTML.

1. Go to https://formspree.io and create a free account.
2. Create a new form.
3. Set the notification/destination email to: nickbirch@outlook.com
4. Formspree will give you an endpoint that looks like:
   https://formspree.io/f/abcdefgh
5. Open index.html in a text editor and find:
   https://formspree.io/f/REPLACE_WITH_FORM_ID
6. Replace that whole URL with your actual Formspree endpoint.
7. Save the file.

FREE GITHUB PAGES SETUP
1. Create a free GitHub account at github.com if you do not already have one.
2. Create a new public repository.
   - If you want the site at https://YOURNAME.github.io, name the repository YOURNAME.github.io
   - Otherwise name it ministryofbirchwood and the site will usually be at https://YOURNAME.github.io/ministryofbirchwood
3. Upload all files and folders from this package into the repository.
4. In GitHub, go to Settings > Pages.
5. Under Build and deployment choose:
   - Source: Deploy from a branch
   - Branch: main
   - Folder: / (root)
6. Save.
7. Wait a minute or two and refresh the Pages settings screen.
8. GitHub will show your live website URL.

LATER
- If you buy a custom domain, connect it in GitHub Pages settings.
- You can update wording any time by editing index.html.
- Styling lives in styles.css.
