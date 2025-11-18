# 🔊 Twitch Bot Sounds

Repository dei suoni per il bot Twitch di Stefania_D.

## 📁 Struttura
```
sounds/
├── meme/          # Suoni meme (bruh, airhorn, ecc.)
├── gaming/        # Suoni gaming (level up, victory, ecc.)
├── celebration/   # Suoni celebrativi (applause, tada, ecc.)
└── alert/         # Alert e notifiche
```

## 🎵 Lista Suoni

Vedi `sounds.json` per la lista completa con costi e cooldown.

## ➕ Come Aggiungere Nuovi Suoni

1. Aggiungi il file MP3/WAV nella cartella appropriata
2. Aggiorna `sounds.json` con le info del suono
3. Commit e push
4. Il bot rileverà automaticamente il nuovo suono!

## 📋 Formato Suoni

- **Formato**: MP3 o WAV
- **Durata**: Max 10 secondi
- **Dimensione**: Max 5MB per file
- **Qualità**: 128kbps minimo

## 🔗 Base URL
```
https://raw.githubusercontent.com/Darkmindy/twitch-bot-sounds/main/sounds/CATEGORY/FILENAME
```

## 📝 Licenze

Tutti i suoni devono essere:
- Royalty-free
- No copyright
- Creative Commons

## 🎮 Uso nel Bot
```
!sound bruh      → Costa 30 punti
!sound epic      → Costa 75 punti
!soundlist       → Lista tutti i suoni
!soundcategory meme → Suoni categoria meme
```
```

**Salva** il file.

---

### **2.3 - Crea `.gitignore`**
```
# OS
.DS_Store
Thumbs.db

# Temp
*.tmp
.temp/
```

**Salva** il file.

---

## 📤 STEP 3: Trova e Aggiungi i Suoni

### **Dove Scaricare i Suoni (Gratis e No Copyright):**

1. **Mixkit** - https://mixkit.co/free-sound-effects/
   - Gaming sounds, alerts, celebrations

2. **Freesound** - https://freesound.org/
   - Cerca: "bruh", "airhorn", "fail trombone"

3. **Zapsplat** - https://www.zapsplat.com/
   - Meme sounds, gaming

4. **MyInstants** - https://www.myinstants.com/
   - Pulsanti meme popolari (download con estensione browser)

### **Suoni Specifici da Cercare:**

**Meme:**
- "bruh sound effect"
- "sad trombone"
- "crickets chirping"
- "airhorn sound effect"
- "wow owen wilson"

**Gaming:**
- "level up sound"
- "victory fanfare"
- "game over sound"
- "power up sound"

**Celebration:**
- "applause sound"
- "tada celebration"

**Alert:**
- "notification ping"

---

## 📥 STEP 4: Organizza i File

Dopo aver scaricato i suoni:

1. Rinomina i file secondo `sounds.json`:
   - `bruh.mp3`
   - `airhorn.mp3`
   - `sadtrombone.mp3`
   - ecc.

2. Mettili nelle cartelle giuste:
```
   sounds/meme/bruh.mp3
   sounds/meme/airhorn.mp3
   sounds/gaming/levelup.mp3
   ecc.