# Birthday Wisher 🎂

Students ke birthday se kuch din pehle parents ko WhatsApp par wish + celebration options bhejne wala simple web app.

## Features
- Students ka data paste karo ya CSV upload karo (`Naam, DD-MM-YYYY, Phone`)
- Agle N din (default 7) ke birthdays apne aap list ho jate hain
- Ek click me WhatsApp khulta hai, message pehle se likha hua
- Message aur celebration options (cake, chocolates, decoration, photo card) editable
- "Sent" mark hota hai, data browser (localStorage) me save rehta hai
- Koi server ya backend nahi, sirf ek `index.html`

## CSV format
```
Aman Kumar, 15-10-2014, 9876543210
Riya Sharma, 17-10-2013, 9812345678
```
10 digit number par `+91` apne aap lag jata hai.

## GitHub Pages par chalane ke liye
1. GitHub par naya repository banao (e.g. `birthday-wisher`)
2. `index.html` aur `README.md` upload karo
3. Settings → Pages → Source: `Deploy from a branch` → Branch: `main` / `(root)` → Save
4. Kuch minute baad link milega: `https://<username>.github.io/birthday-wisher/`

## Privacy
Students aur parents ka data sirf aapke browser me rehta hai, kisi server par nahi jata. Is repo me asli student data commit mat karna.

## Limitation
Yeh app click par WhatsApp kholta hai. Bina click ke automatic bhejne ke liye WhatsApp Business API (Meta Cloud API) chahiye.
