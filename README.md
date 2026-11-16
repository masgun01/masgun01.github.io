# Portfolio — Gunawan Wibisono

Personal portfolio site. Web developer working in PHP, Python, MySQL and PostgreSQL.

**Live:** https://masgun01.github.io

## What is here

A single self-contained `index.html`. No build step, no dependencies to install. Fonts load from Google Fonts; everything else — styles, scripts, the photo, and all four project illustrations — lives inside the file.

## Contents

| Section | What it covers |
| --- | --- |
| Services | The four kinds of system I build |
| Work | Four case studies: the problem, what I built, the features, the stack |
| Process | How a project runs, from first discussion to handover |
| Skills | Languages, databases, deployment |
| Contact | WhatsApp and email |

## Projects featured

- **Online Enrolment System** — school enrolment for SLB Sana Dharma. PHP, MySQL, PHPMailer, PhpSpreadsheet, TCPDF, Ratchet WebSocket.
- **Coffee Stock Planning System** — sales forecasting with Random Forest, converted into raw material requirements. Python, Flask, scikit-learn, pandas, PostgreSQL.
- **Mabar Dimsum** — online ordering with QRIS/COD checkout and automatic WhatsApp order summaries. PHP, MySQL, JavaScript.
- **Masjid Al-Barokah** — community information system with prayer times, events, and financial reporting. PHP, MySQL, Chart.js.

## Editing

Contact details and project links sit in one `SETTINGS` block near the bottom of `index.html`:

```js
var SETTINGS = {
  whatsapp: "6281477120376",
  email: "pakgunz01@gmail.com",
  github: "masgun01",
  projects: {
    ppdb: { demo: "", code: "" },
    ...
  }
};
```

Anything left as `""` is hidden rather than shown empty. Add a `demo` or `code` URL and the link appears on that project automatically.

## Accessibility

Motion is disabled automatically when the visitor's device has "reduce motion" turned on, and all content stays readable with JavaScript off.

## Contact

WhatsApp +62 814-7712-0376 · pakgunz01@gmail.com
