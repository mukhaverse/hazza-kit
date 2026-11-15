# Karak Queue (طابور الكرك) — notes

the problem: Abu Fares's karak stand near the engineering building. between lectures (especially 9:50) the line is 20+ people. I was late to lectures because of it. a lot. and I saw people leave the line because they had a lecture, so Abu Fares was losing customers too.

what I did first (this is the part I'm proud of): I stood there for a week with a stopwatch on my phone and timed the line. average wait was **15 minutes**. Abu Fares thought I was from the ministry lol.

then I talked to him: he doesn't want an app, doesn't want to touch money online, and he has one old tablet.

**what I built:**
- QR code on the stand → opens a web page (no app download)
- you order, pay at pickup like normal
- orders appear on Abu Fares's tablet in order, with a big number
- when it's ready, your phone shows "your karak is ready" with your number
- works as an installable web app (PWA) so regulars put it on their home screen

**tech:** React, Firebase (Firestore + Hosting), PWA. built alone in about 3 weeks.

**results:**
- average wait went from 15 minutes to **4 minutes** (I timed it again for a week after launch)
- around **300 orders a week** through the QR
- Abu Fares says his sales went up "about 25%" (his estimate, he says he can feel it in the cash box)
- he printed the QR himself on a bigger sign. that's how I know he likes it

**links:**
- live: karak-queue.web.app (fake link for the workshop)
- code: github.com/hazza404/karak-queue

**files:** screenshot-order.png, screenshot-tablet.png
