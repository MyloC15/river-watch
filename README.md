# Riverwatch

> **Hecho en Osa 2026** · Track: Built by Hand · Social Impact Tool
>
> Write this README yourself, in English or Spanish. AI can help with your code, but this page is in your own words.
> Escribe este README tú mismo, en inglés o español. La IA puede ayudarte con el código, pero esta página va con tus propias palabras.

---

## 1. What it is / Qué es
One sentence. Finish this: **"This project ________."**

✍️ *Mylo, write this sentence in your own words.*

## 2. Who made it / Quién lo hizo
- Makers: Mylo (@MyloC15)
- Mentor: Matthais

## 3. Try it / Pruébalo
- Live link: https://myloc15.github.io/river-watch/ *(once GitHub Pages is switched on and `index.html` is in the repo)*
- Screenshot or short video: ✍️ *add when it's working*
- How to run it on your own computer, step by step:
  1. Web page: download this repo and open `index.html` in a browser.
  2. Hardware: ✍️ *add the steps for uploading the code to the detector and receiver boards once you've chosen them.*

## 4. How it works / Cómo funciona
Explain the main parts in your own words. Which file does what?

✍️ *Mylo, explain the detector → radio → alarm → web page chain in your own words.*

| File or folder | What it does |
|---|---|
| `index.html` | The web page: shows the current conditions at the bathing spot and what each colour means |
| `hardware/detector/` | Code for the detector: reads the HC-SR04 sensor, decides if the water is rising fast, sends the alert by radio |
| `hardware/receiver/` | Code for the receiver: listens for alerts, turns on the siren and lights, sends updates to the web page |
| `sketches/` | Photos of our hand-drawn system and screen designs |
| `PRD.md` · `TRD.md` · `PROMPT.md` | What we're building, how we're building it, and our first prompt for the AI |

The code itself should have comments that explain *why*, written by you.

## 5. Tools we used / Herramientas
Everything that helped: editors, AI tools, websites, hardware, tutorials, people.

| Tool | What we used it for |
|---|---|
| Claude | Helped write the Riverwatch project description, and turned my answers into the first drafts of PRD.md, TRD.md and PROMPT.md |
| Circuit boards and parts (microcontroller, HC-SR04 sensor, radio, siren/buzzer, LEDs, battery, solar panel) | Building the detector and the alarm |
| GitHub | Storing our code and documents, and hosting the web page |

Using AI is allowed and encouraged. Say what you used it for.

## 6. Libraries / Librerías
Any code you didn't write yourself (packages, frameworks, assets, sounds, images).

| Library or asset | Link | Why we needed it |
|---|---|---|
| None yet | | Add any board or radio libraries here when we use them |

## 7. What works, what doesn't / Qué funciona y qué no
✍️ *Mylo, fill these in your own words before code freeze.*
- **Works:**
- **Still broken:**
- **If we had two more weeks:**

## 8. Someone else tried it / Alguien más lo probó
Not yet. ✍️ *After someone tries it: who tried it (a friend, a parent, another team)? What confused them? What did they like?*

## 9. Final presentation / Presentación final
Put your Demo Day slides in the `presentation` folder as a PDF: `presentation/final.pdf`

## 10. How we worked together / Cómo trabajamos juntos *(optional, for teams)*
Did you use issues and pull requests? Who did what? What would you do differently?

---

### ✅ In-hack checklist (all required before the deadline)
- [ ] Sections 1–9 filled in
- [ ] Code comments explain the main parts
- [ ] `presentation/final.pdf` is in the repo
- [ ] No passwords, API keys, phone numbers, emails, or photos of people's faces anywhere in the repo
- [ ] Pushed to [github.com/hechoenosa](https://github.com/hechoenosa) by **Thu 10 Dec, 8 pm**
