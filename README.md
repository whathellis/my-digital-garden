https://my-digital-mashrooms-garden.vercel.app/


# Digital Obsidian Garden
This is the template to be used together with the [Digital Garden Obsidian Plugin](https://github.com/oleeskild/Obsidian-Digital-Garden). 
See the README in the plugin repo for information on how to set it up.

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/oleeskild/digitalgarden)

---
## Docs
- Docs are available at [dg-docs.ole.dev](https://dg-docs.ole.dev/)

# Notes
bc I need them to remember wth to do
- **Analytics:** https://github.com/oleeskild/obsidian-digital-garden/discussions/195
- **Comments:** https://giscus.app/
### To make comments better fit the page
- Add `<div class="comments">` before and `</div>` after your code (here `src/site/_includes/components/user/notes/footer/giscus.njk`) from the Giscus

![Screenshot 2025-02-01 18 23 01 my-digital-gardensrcsite_includescomponentsusernot](https://github.com/user-attachments/assets/04840399-2489-4aef-8ca3-2842ff81cd69)
  - Than add this code to the existing custom style file `src/site/styles/custom-style.scss`
      - ***max-width*** depends on your preferences/monitor
    ```css
    .comments {
    display: flex;
    margin: auto;
    max-width: 50%; 
         }
    ```

![Screenshot 2025-02-01 19 46 30 Editing_my-digital-gardensrcsitestylescustom-style](https://github.com/user-attachments/assets/e2235130-5fef-46ce-8a88-f6e0c7ea0ebe)



