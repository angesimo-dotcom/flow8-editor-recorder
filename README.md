# 🎛️ FLOW 8 Editor & 10-Track Recorder (macOS)

An all-in-one desktop control surface and multitrack audio recorder for the **Behringer FLOW 8** digital mixer, built for macOS.

*[Leggi la versione in Italiano più in basso](#-descrizione-del-progetto)*

---

## 🇬🇧 English

### Overview
Behringer never released an official desktop editor for the FLOW 8, leaving computer users without visual control over USB. **FLOW 8 Editor** solves this gap and goes a step further: it combines a full **USB MIDI mixer controller** with a built-in **10-track post-gain audio recorder** in a single, lightweight macOS application.

### Key Features
* **Complete Mixer Control via USB MIDI:** Adjust channel faders, mute/solo states, EQ, monitor sends, onboard FX presets, and mixer snapshots directly from your Mac.
* **Built-in 10-Track Multitrack Recorder:** Capture up to 10 individual audio channels simultaneously straight from the source (post-gain, pre-fader) without needing to launch a heavy DAW during live sessions or rehearsals.
* **DAW-Ready Exports:** Record clean, isolated tracks ready to be imported into Logic Pro, Ableton Live, Reaper, Cubase, or Pro Tools for later mixing.
* **Native macOS App Bundle:** Packaged as a standalone `.app` (`FLOW 8 Editor.app`) combining a Python backend with a responsive HTML/JS interface.

### Requirements & Setup
1. **macOS** (Apple Silicon or Intel).
2. Connect your Behringer FLOW 8 to your Mac via USB.
3. Make sure the FLOW 8 USB mode is set to **Recording Mode (10-in / 2-out)** on the mixer hardware to enable 10-track post-gain capture.
4. Download the latest release from the **Releases** tab, move `FLOW 8 Editor.app` to your Applications folder, and launch it.
   *(Note: Since the app is unsigned, you may need to right-click the app and select **Open** the first time you run it).*

---

## 🇮🇹 Italiano

### Descrizione del Progetto
Behringer non ha mai rilasciato un editor desktop ufficiale per il mixer digitale FLOW 8. **FLOW 8 Editor** colma questa lacuna unendo in un'unica applicazione per macOS sia un **controller MIDI completo via USB** sia un **registratore multitraccia a 10 canali** pronto all'uso.

### Funzionalità Principali
* **Controllo Completo del Mixer via USB MIDI:** Gestisci fader, mute, EQ, mandate monitor, effetti integrati e snapshot direttamente dal schermo del tuo Mac.
* **Registratore Multitraccia a 10 Canali Integrato:** Registra fino a 10 tracce audio separate direttamente dalla sorgente (dopo il gain, pre-fader) nella stessa interfaccia di controllo, senza dover aprire una DAW pesante durante le prove o i live.
* **Pronto per il Remix su DAW:** Ottieni file audio puliti e separati, pronti da importare su Logic Pro, Reaper, Cubase, Ableton Live o qualsiasi altra DAW per il missaggio finale.
* **App Nativa per macOS:** Distribuita come pacchetto autonomo (`FLOW 8 Editor.app`) basato su un backend Python e un'interfaccia grafica moderna.

### Requisiti e Installazione
1. **macOS** (Apple Silicon o Intel).
2. Collega il Behringer FLOW 8 al Mac tramite cavo USB.
3. Imposta il mixer in modalità **Recording (10-in / 2-out)** per abilitare l'invio delle 10 tracce separate post-gain.
4. Scarica l'ultima versione dalla sezione **Releases** di GitHub, sposta `FLOW 8 Editor.app` nella cartella Applicazioni e avviala.
   *(Nota: al primo avvio potrebbe essere necessario fare clic destro sull'icona dell'app e scegliere **Apri** per autorizzare l'esecuzione su macOS).*

---

## 🛠️ Tech Stack
* **Backend:** Python (`flow8_app.py`)
* **Frontend:** HTML / CSS / JavaScript (`flow8-editor.html`)
* **Platform:** macOS App Bundle
