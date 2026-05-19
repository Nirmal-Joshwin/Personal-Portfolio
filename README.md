# 🌐 Personal Portfolio — Nirmal Joshwin
 
A multi-page personal portfolio website built with **Bootstrap 5** and custom CSS, showcasing projects, interests, and a photo gallery.
 
---
 
## Pages
 
| Page | File | Description |
|------|------|-------------|
| Home | `index.html` | Hero carousel, bio, and capstone project highlight |
| Projects | `projects.html` | Showcase of technical projects |
| Interests | `interests.html` | Favourite song, place, video, and hobbies |
| Gallery | `gallery.html` | Photo grid layout |
 
---
 
## Tech Stack
 
- **Bootstrap 5.3.8** — navbar, carousel, responsive layout
- **Google Fonts** — `Google Sans` (body), `Oleo Script Swash Caps` (display headings)
- **Vanilla CSS** (`style.css`) — custom layout, typography, and component overrides
- **Spotify & YouTube embeds** — on the Interests page
---
 
## Project Structure
 
```
portfolio/
├── index.html        # Home page with hero carousel and bio
├── projects.html     # Projects listing
├── interests.html    # Personal interests with embeds
├── gallery.html      # Photo gallery grid
├── style.css         # All custom styles
├── Resume.pdf        # Downloadable resume
├── 1.jpg, 2.jpg, 3.jpg            # Hero carousel images
├── event1.jpg                     # Project/capstone image
├── proj2.png                      # Voice Assistant project image
├── place1.jpg, place2.jpg, place3.jpg  # Interests carousel images
└── gal (1).jpg … gal (6).jpg     # Gallery images
```
 
---
 
## Running Locally
 
No build step or server required — just open the HTML files directly in a browser:
 
```bash
# Clone or download the repo, then open:
open index.html
```
 
Or use a simple local server for cleaner asset loading:
 
```bash
# Python 3
python -m http.server 8000
# Then visit http://localhost:8000
```
 
---
 
## External Links
 
- [LinkedIn](https://www.linkedin.com/in/nirmaljoshwin/)
- [GitHub](https://github.com/Nirmal-Joshwin)
- [LeetCode](https://leetcode.com/u/Nirmal_Joshwin/)
- [HackerRank](https://www.hackerrank.com/profile/Joshwin)
---
 
## Projects Featured
 
**Resilience-as-a-Service** — Offline-first, local observability and alert dissemination system running on Kubernetes. Operates entirely without internet; any browser on the LAN can receive alerts.
 
**Voice Assistant** — Python desktop voice assistant with dark-themed GUI, supporting voice and text input. Handles system controls, file management, Wikipedia lookups, and LLM-powered Q&A.
 
---
 
## License
 
MIT License — free to use and adapt.
