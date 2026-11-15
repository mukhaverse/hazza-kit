# Sandstorm Bot (عاصفة) — notes

hackathon project. 36 hours. team of 3. we got **2nd place out of 28 teams**!!!

**idea:** a Telegram bot. you subscribe with your city. when dust levels get high, it sends you an alert with simple advice (close the windows, wear a mask, if you have asthma keep your inhaler with you).

**my part:** the alert logic: reading air quality data from a public API every 30 minutes, deciding when it's "high" (we used set thresholds), and not spamming people (max 1 alert every 6 hours).
teammates: one did the bot conversation, one did the pitch and slides.

**honest status:** the code is messy (36 hours, no sleep). it works for the demo. we didn't keep running it after the hackathon.

**links:**
- code: github.com/hazza404/sandstorm-bot
- demo video: 40 seconds, on the team's drive (fake link for the workshop)

**files:** screenshot-chat.png
