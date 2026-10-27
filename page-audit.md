# Portfolio page audit

Checked on 28 October 2026 against the local files in this folder and a live preview at `http://127.0.0.1:8765/`.

| Requirement | Status | Notes |
| --- | --- | --- |
| Name accuracy | Verified | Displayed as Vishwas Saini in the brand, hero, about, footer, and page title. |
| Professional headline accuracy | Verified | Hero and footer use “Video Editor \| Cinematographer \| Visual Storyteller”. |
| Education accuracy | Verified | Class 12: SVP Shikshan Avam Anusandhan Sansthan. Class 10: Ajeet Public School. No invented years, grades, or college. Earlier unverified JECRC / Matrix content was removed. |
| Contact information | Verified | Email is a placeholder. Instagram, GitHub, and X use URLs from the previous site. Phone is not shown. |
| About section accuracy | Verified | Describes working video editor and cinematographer roles without employers, clients, or years of experience. |
| Video editing skills accuracy | Verified | Matches the supplied skill list. No proficiency percentages. |
| Cinematography skills accuracy | Verified | Matches the supplied skill list. No proficiency percentages. |
| Software and equipment accuracy | Pending | Premiere Pro, DaVinci Resolve, After Effects, Photoshop, and Lightroom are listed from the supplied skill set, with a note that they can be edited. Existing files did not independently confirm each tool. |
| Project descriptions | Verified | Cards are labeled placeholders. No fabricated clients, credits, or completed work. |
| Project video URLs and playback | No | No genuine project video files or URLs were found in this folder. |
| Showreel URL verification | No | Showreel is a placeholder. No player is embedded. |
| Instagram and YouTube URLs | Verified | Instagram `https://www.instagram.com/vishwas_213` was taken from the previous site. YouTube remains a placeholder. Live profile reachability was not checked. |
| LinkedIn URL verification | No | Previous site used `href="#"`. LinkedIn is a placeholder with no fake link. |
| Achievement and certification accuracy | Verified | Placeholder only. No invented certificates or awards. |
| Services section accuracy | Verified | Presented as service categories. No prices, packages, clients, or results. |
| Responsive design | Verified | Desktop, tablet-width CSS, and a 390px mobile emulation were reviewed. Mobile uses a hamburger menu. |
| Mobile navigation | Verified | Menu opens, lists all sections, and closes after choosing About. Escape handling is in `script.js`. |
| Accessibility and keyboard navigation | Verified | Skip link, semantic landmarks, labels on form fields, `aria-expanded` on the menu, and `:focus-visible` styles are present. Full keyboard-only pass was not completed. |
| HTML validation | Pending | Not submitted to https://validator.w3.org/nu/ because the site is local only. |
| CSS and JavaScript file links | Verified | `index.html` links to `style.css` and `script.js`. Preview confirmed both load; copyright year rendered as 2026. |
| Navigation section IDs | Verified | Home, About, Skills, Projects, Services, Education, Showreel, and Contact all match section IDs. |
| Missing assets | Verified | No broken local image/video references in the new markup. `main.jpg` remains in the folder and is unused, by request (CSS hero instead of a photo). |
| Video thumbnail and media availability | No | No verified thumbnails or media files are used. |
| Remaining PLACEHOLDER values | Verified | Email, YouTube, LinkedIn, portfolio/showreel URL, project videos, showreel, and achievements remain clearly marked placeholders. |

## Additional notes

- The previous contact form was kept. Discord webhook and Express/MongoDB code were removed from `script.js` so the static site does not depend on unavailable services or expose a webhook.
- Form submit was tested: it reports that sending is paused until a real email is added.
- Location is not displayed because it was not confirmed in the supplied details.
- Google Fonts are loaded from Google; the rest of the site uses plain HTML, CSS, and JavaScript.
