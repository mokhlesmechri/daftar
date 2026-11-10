# Daftar (دفتر)

**The shopkeeper's credit notebook, digitized with one photo.** Built for the OpenRouter x Meta Build Day, $1 Challenge.

## The problem
Millions of small shops across North Africa, the Middle East, Africa and South Asia let regular customers buy on credit. Every debt is written by hand in a notebook ("daftar" / "kerrasa"). Pages get lost, totals are wrong, and shopkeepers feel uncomfortable asking for their money. That lost money is often the difference between a good and a bad month for the family.

## The solution
1. The shopkeeper takes a photo of a notebook page with any phone.
2. **Muse Ember** reads the handwriting (Arabic, French, English, mixed, local abbreviations) and builds a clean ledger.
3. It computes what each customer still owes and the total owed to the shop.
4. It writes a short, warm, respectful WhatsApp reminder for each customer in the shopkeeper's language, ready to send in one tap.

## Why Muse Ember
Muse Ember understands images and is extremely cheap ($0.10/M input, $0.50/M output tokens). A full notebook page costs a fraction of a cent, so **$1 digitizes thousands of pages**: a whole neighborhood's notebooks. The live cost counter in the app shows it on every run.

## How to run
1. Open `index.html` in a browser. No install, no backend.
2. Paste your OpenRouter API key.
3. Upload a photo of a notebook page, choose the reminder language, click "Digitize page".

Model: `meta/muse-ember` via the OpenRouter API (`https://openrouter.ai/api/v1/chat/completions`).

## Author
Mokhles Mechri (مخلص المشري)
