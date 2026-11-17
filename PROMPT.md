# Our first prompt

Built from our PRD (Week 3) and TRD (Week 4) in Week 5. Sent for the first time at the **Vibe Jam**.

1. **Context:** I'm 11 and new to coding. Help me build a river flood alarm called Riverwatch: a detector, a radio link and an alarm, plus a small web page.
2. **Who it's for:** Families and locals in Uvita, Costa Rica, who bathe, swim and play in the river.
3. **The problem:** Flash floods come down the river with almost no warning. The rivers around Uvita have flooded suddenly many times, and people have died in recent floods. One person told me: "I was lucky to survive the flash flood."
4. **The ONE thing:** When the water rises fast at the detector, the alarm downstream goes off.
5. **Step by step:**
   1. The detector (upstream) measures the distance down to the water with an HC-SR04 ultrasonic sensor, over and over.
   2. If the water is rising fast for several readings in a row, it sends an alert by radio. One splash must not set it off.
   3. The receiver at the bathing spot turns on the alarm: green light = safe, amber = watch, red light + siren = danger.
   4. The receiver sends regular updates to a web page (`index.html`).
   5. On a phone, the web page shows the bathing spot's colour, the water level, when it was last updated, and what each colour means.
6. **Done when:**
   1. When I quickly move water (or a board) closer to the sensor and keep it there, the siren sounds and the red light comes on within a few seconds.
   2. When the water level stays the same, the light stays green and there is no siren.
   3. When I splash or wave my hand under the sensor just once, the alarm stays green.
   4. When the detector is switched off, the web page shows it's offline or the update is old, never "safe".
   5. When I open the web page on my phone, I can see the colour, level and last-updated time without zooming.
7. **Rules:** The web page is one `index.html` with HTML, CSS and JavaScript (Stack level 1, Live). The hardware is a microcontroller board, an HC-SR04 sensor, a radio module, a siren/buzzer and LEDs, running on a battery and solar panel. We haven't chosen the board and radio yet: ESP32 + LoRa, ESP32 + ESP-NOW, or Arduino Uno + LoRa. Files: `index.html`, `hardware/detector/`, `hardware/receiver/`. Colours: river blue, plus green, amber and red for the alert levels. Works on a phone. Add a short comment above each part.
8. **Not yet:** No phone or text alerts, no rain gauge, only one detector.
9. **How to answer:** Ask me up to 5 questions first. Then build only #4. Then explain how it works in 5 sentences, like I'm 12.

Checked by mentor: ______
