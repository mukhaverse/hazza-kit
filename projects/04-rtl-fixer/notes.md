# RTL Fixer — notes

you know when you write a sentence in Arabic with an English word in the middle, like a tool name or a number, and the website shows it all mixed up and backwards? that.

it happens in a lot of comment boxes, chats and web apps because they don't set the text direction properly.

**what I built:** a small browser extension. it finds text boxes and messages that contain Arabic, and fixes the direction automatically (it sets `dir="auto"` and some CSS). you install it and forget about it.

**tech:** JavaScript, Chrome Extensions API (Manifest V3). solo. open source (MIT).

**numbers:**
- about **1,200 users** on the extension store
- **85 stars** on GitHub
- **3 people I don't know** sent pull requests (one fixed a bug in Persian text, which I didn't even test)

**links:**
- code: github.com/hazza404/rtl-fixer
- store page: (fake link for the workshop)

**files:** before-after.png
