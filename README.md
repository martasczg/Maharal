# Golem Game / Hra Golem

A simple interactive web-based puzzle game in Czech language.

## Description / Popis

This is a browser-based puzzle game where players need to:
1. Play the Golem game to decipher a secret code
2. Enter the code on the protected webpage
3. Unlock the surprise - an image of Golem with a celebratory sound

**Correct code:** `1609`

## Files / Soubory

- `index.html` - The main HTML page with login form and protected content
- `golem.jpg` - The Golem image revealed after entering the correct code
- `golem-sound.mp3` - Audio file played when the code is successfully entered
- `golem_final_sound_synced.mp4` - Video file with synchronized sound

## How to Use / Jak používat

1. Open `index.html` in a web browser
2. Enter the code you deciphered from playing the Golem game
3. Click "Potvrdit" (Confirm) button
4. If correct, you'll see the Golem image and hear the success sound

## Features / Funkce

- Simple password protection mechanism
- Responsive design
- Audio playback on successful code entry
- Error messages for incorrect codes
- Czech language interface

## Technical Details / Technické detaily

- Pure HTML, CSS, and JavaScript (no frameworks required)
- Client-side code validation
- Audio element for sound playback
- Responsive layout using flexbox

## Note / Poznámka

The audio may not play automatically in some browsers due to autoplay policies. Users may need to interact with the page first.
