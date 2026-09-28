# Statement Counter

A small web app that answers one question: what share of my Uber Eats orders were Order and pay (grocery shopping) versus regular Delivery. You drop in any number of weekly statement PDFs, and it shows the overall split plus a breakdown for each week. Everything runs in the browser: the PDFs are read locally with Mozilla's pdf.js, and nothing is uploaded or sent to any AI model. Instead of trying to redact personal data, the app keeps only what it needs, the transaction type of each row in the Transactions table, and skips headers and footers that repeat on every page. A "Show extracted text" view lets you check how each row was classified, with dollar amounts hidden, and the matching labels can be edited if the statement wording changes. It's a single HTML file with plain HTML, CSS, and JavaScript, so just open `statement-counter.html` in a browser to run it.

Vibe coded by me, for me.
