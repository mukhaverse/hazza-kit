# Jaddati (جدّتي) — notes

ok so this is my favourite project and also the one I can never explain properly lol

**the story:** Teta takes 5 different medicines at different times (morning, after lunch, before sleep, and one every other day which is the most confusing one). she kept forgetting or taking the same pill twice. my aunt was calling her every day to ask "did you take it?" and Teta was getting annoyed.

we tried normal reminder apps. all English, tiny text, too many buttons, and they beep like an alarm clock. Teta deleted 2 of them herself (she knows how to delete apps but not how to use them, interesting).

**what I built:**
- Arabic first, huge buttons (Teta tested every screen, if she squinted I made it bigger)
- reminders play a voice note in MY voice: "يا تيته، حبة الضغط" (she likes this part the most)
- one big button "أخذتها" → sends a message to the family WhatsApp group so nobody needs to call
- if she doesn't press it in 30 minutes, it reminds again, then tells the family
- works offline

**tech:** Flutter, Dart, local notifications, WhatsApp share. built it alone, about 6 weeks of evenings.

**results (real):**
- before: she missed around 3 doses a week (my aunt was keeping count in a notebook)
- after: 0 missed doses in 3 months. ZERO.
- I shared the APK in the neighbourhood WhatsApp group and around 40 families installed it
- my aunt asked for a version for her mother-in-law
- it's not on Google Play / App Store yet (no developer account yet)

**links:**
- code: github.com/hazza404/jaddati
- demo video: I have one on my phone (45 sec), will upload "soon"
- screenshots: in this folder

**files in this folder:** screenshot-home.png, screenshot-reminder.png, feedback.md
