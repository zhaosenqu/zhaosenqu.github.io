# zhaosenqu.github.io

Personal academic website of Zhaosen Qu, served by GitHub Pages at <https://zhaosenqu.github.io/>.

Plain HTML and CSS with no build step and no JavaScript.

| File | Page |
| --- | --- |
| `index.html` | Home |
| `about.html` | Biography, education, experience, teaching |
| `research.html` | Research projects |
| `publications.html` | Articles, manuscripts, presentations |
| `skills.html` | Skills & methods |
| `contact.html` | Contact details and profiles |
| `404.html` | Not-found page |
| `css/site.css` | Shared stylesheet |
| `assets/gradCV_Qu.pdf` | CV |

The header and footer are repeated in every page. When adding a page, copy an existing one, move `aria-current="page"` to the new nav link, and add the URL to `sitemap.xml`.

Preview locally with `python3 -m http.server` and open <http://localhost:8000>.
