# Mawgif (موقف) — notes

Mawgif is basically my project. I basically built Mawgif.

ok fine, it was a team project for a software engineering course, 4 people:
- **me:** backend + API (Node.js, Express, PostgreSQL). designed the database, wrote the endpoints for parking lots, spots, and user reports
- **Reem:** UI/UX design (all the screens in Figma)
- **Faisal:** the mobile app (connected to my API)
- **Joud:** testing and documentation

**problem:** students drive around for up to 20 minutes looking for parking near their building before a lecture.

**idea:** a map of campus parking lots with a live estimate of free spots. we didn't have sensors, so users report "full" / "free" when they park or leave, and the estimate updates.

**status:** prototype only. we demoed it to the department at the end of the semester. got an A. never launched (no sensors, and the semester ended).

**what I learned:** designing an API that another person depends on. Faisal found 6 bugs in my endpoints in one night and I learned to write API docs after that.

**links:** code: github.com/hazza404/mawgif-backend (the app repo is on Faisal's account)

**files:** screenshot-map.png
