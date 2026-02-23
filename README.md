mach eine file names idle.html


hir der  code aber der code ist comireit geschützt 





<!DOCTYPE html>
<html lang="de">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>🎮 GameMusic GOD 2.4 👑 – Beste 2026 Vibes pro Spiel</title>
  <style>
    :root {
      --bg: #0d1117;
      --card: #161b22;
      --accent: #ff4d6d;
      --accent-hover: #ff1e4d;
      --text: #e6edf3;
      --gray: #8b949e;
    }
    * { box-sizing: border-box; margin:0; padding:0; }
    body {
      font-family: system-ui, sans-serif;
      background: linear-gradient(135deg, #0f0c29, #302b63, #24243e);
      color: var(--text);
      min-height: 100vh;
      padding: 1.5rem;
    }
    header {
      text-align: center;
      font-size: 2.8rem;
      font-weight: 800;
      margin-bottom: 1.5rem;
      text-shadow: 0 0 20px rgba(255,77,109,0.6);
    }
    .container { max-width: 1100px; margin: 0 auto; }
    .input-group {
      display: flex;
      flex-wrap: wrap;
      gap: 12px;
      justify-content: center;
      margin: 1.5rem 0;
    }
    input, select, button {
      padding: 0.9rem 1.3rem;
      font-size: 1.1rem;
      border: none;
      border-radius: 12px;
      background: var(--card);
      color: var(--text);
    }
    input::placeholder, select { color: var(--gray); }
    button {
      background: var(--accent);
      color: white;
      font-weight: bold;
      cursor: pointer;
      transition: all 0.2s;
    }
    button:hover { background: var(--accent-hover); transform: translateY(-2px); }
    .open-btn { background: #00c853; font-size: 1.2rem; padding: 1rem 2rem; }
    .fav-btn  { background: #ffd600; color: black; }
    h3 { margin: 2rem 0 1rem; font-size: 1.6rem; opacity: 0.9; }
    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(140px, 1fr));
      gap: 12px;
      margin-bottom: 2rem;
    }
    .card {
      background: var(--card);
      padding: 1.2rem;
      border-radius: 12px;
      text-align: center;
      cursor: pointer;
      transition: all 0.2s;
      font-weight: 500;
    }
    .card:hover { background: rgba(255,255,255,0.12); transform: scale(1.04); }
    #result {
      margin-top: 2.5rem;
      font-size: 1.4rem;
      line-height: 1.6;
      text-align: center;
    }
    .song-btn { margin: 0.8rem; min-width: 220px; }
    .spotify-player {
      margin: 2rem auto;
      max-width: 500px;
      width: 100%;
      border-radius: 12px;
      overflow: hidden;
      box-shadow: 0 8px 32px rgba(0,0,0,0.5);
    }
    iframe {
      border: none !important;
      border-radius: 12px;
      width: 100%;
    }
    @media (max-width: 600px) {
      header { font-size: 2.4rem; }
      .input-group { flex-direction: column; }
      input, select, button { width: 100%; }
    }
  </style>
</head>
<body>

<header>🎮 GameMusic GOD 2.4 👑 – Beste Musik pro Spiel 2026</header>

<div class="container">

  <div class="input-group">
    <input id="game" placeholder="Spiel eingeben (z.B. Valorant, Fortnite, Minecraft)" />
    <select id="mood">
      <option value="">🎯 Stimmung (optional – Spotify priorisiert)</option>
      <option value="epic">Episch / Heroisch / EDM</option>
      <option value="aggressive">Aggressiv / Tryhard / Phonk</option>
      <option value="chill">Chill / Relax / LoFi</option>
      <option value="fun">Fun / Viral / TikTok Phonk</option>
    </select>
  </div>

  <div class="input-group">
    <button onclick="findSong()">Beste Musik finden</button>
    <button onclick="randomSong()">🎲 Zufalls-Banger 2026</button>
  </div>

  <h3>Beliebte Vibes & Spiele 2026</h3>
  <div class="grid">
    <div class="card" onclick="pickGame('Fortnite')">Fortnite</div>
    <div class="card" onclick="pickGame('Valorant')">Valorant</div>
    <div class="card" onclick="pickGame('Minecraft')">Minecraft</div>
    <div class="card" onclick="pickGame('GTA')">GTA</div>
    <div class="card" onclick="pickGame('Apex Legends')">Apex</div>
    <div class="card" onclick="pickGame('Elden Ring')">Elden Ring</div>
    <div class="card" onclick="pickGame('Phonk')">Phonk Vibes</div>
    <div class="card" onclick="pickGame('Call of Duty')">CoD</div>
  </div>

  <h3>Eigenen Link hinzufügen (YT oder Spotify) ➕</h3>
  <div class="input-group">
    <input id="customLink" placeholder="YouTube- oder Spotify-Link" />
    <button onclick="addSong()">Hinzufügen</button>
  </div>

  <h3>Favoriten ❤️</h3>
  <div class="input-group">
    <button onclick="showFavs()">Favoriten anzeigen</button>
  </div>

  <div id="result"></div>

</div>

<script>
const gamePlaylists = {
  valorant: [
    "https://open.spotify.com/playlist/5aIYTmOdSUEsldGYgatff2", // Valorant Best Gaming Tracks – Tryhard Vibes
    "https://open.spotify.com/playlist/1l32LAhKq0PYsOVhlEk0S0", // Valorant Playlist / Listen while playing
    "https://open.spotify.com/playlist/0EENPHgbZ67xQyMiQr6Pfp", // GAMING PHONK 2026 – Aggressive/Stream Safe
    "https://open.spotify.com/playlist/5AnmBxdRTUo6PH2UOeNGYq"  // Gaming EDM 2026 Top 100 – Tryhard/Trap/EDM
  ],
  fortnite: [
    "https://open.spotify.com/playlist/0ANSFnK3A8wJ0u9WRloOGV", // Fortnite 2026 – Hype/Viral
    "https://open.spotify.com/playlist/5AnmBxdRTUo6PH2UOeNGYq", // Gaming EDM 2026 – Fortnite/CS/Play
    "https://open.spotify.com/playlist/4M2EwzhQSyLeWIWrXGuRjs", // Gaming Music 2026 – Fortnite/Apex/etc.
    "https://open.spotify.com/playlist/1IpNiRAZuHLRCseQJgHHjJ"  // FORTNITE VIBE PLAYLIST – Hype
  ],
  minecraft: [
    "https://open.spotify.com/playlist/3n6wbQbw4kTtOwhn8yfMKC", // Chill Gaming 2026 – HipHop/EDM/Phonk (gut für entspanntes Bauen)
    "https://open.spotify.com/playlist/15eJCdcsxMvR0KJhYRnYx4", // Gaming Playlist 2026 – Weekly Updated
    "https://open.spotify.com/playlist/4M2EwzhQSyLeWIWrXGuRjs"  // Gaming Music 2026 – Minecraft inkl.
  ],
  "apex legends": [
    "https://open.spotify.com/playlist/0EENPHgbZ67xQyMiQr6Pfp", // Aggressive Phonk – Apex/Valorant Tryhard
    "https://open.spotify.com/playlist/5AnmBxdRTUo6PH2UOeNGYq", // Gaming EDM Top 100 – Apex/Fortnite
    "https://open.spotify.com/playlist/4M2EwzhQSyLeWIWrXGuRjs"  // Gaming Mix 2026 – Apex inkl.
  ],
  "call of duty": [
    "https://open.spotify.com/playlist/0EENPHgbZ67xQyMiQr6Pfp", // Phonk Aggressive – CoD/Tryhard
    "https://open.spotify.com/playlist/5AnmBxdRTUo6PH2UOeNGYq"  // EDM/Trap – CoD/FPS
  ],
  "elden ring": [
    "https://open.spotify.com/playlist/15eJCdcsxMvR0KJhYRnYx4", // Gaming 2026 – Epic/Techno
    "https://open.spotify.com/playlist/4M2EwzhQSyLeWIWrXGuRjs"  // Epic Gaming Mix
  ]
};

// Allgemeine Top-Playlists als Fallback / für keine spezifische Stimmung
const generalPlaylists = {
  epic: [
    "https://open.spotify.com/playlist/15eJCdcsxMvR0KJhYRnYx4", // Gaming Playlist 2026 Weekly
    "https://open.spotify.com/playlist/4M2EwzhQSyLeWIWrXGuRjs", // Gaming Music 2026 Best Mix
    "https://open.spotify.com/playlist/5AnmBxdRTUo6PH2UOeNGYq"  // Gaming EDM Top 100
  ],
  aggressive: [
    "https://open.spotify.com/playlist/0EENPHgbZ67xQyMiQr6Pfp", // GAMING PHONK 2026 Stream Safe
    "https://open.spotify.com/playlist/5AnmBxdRTUo6PH2UOeNGYq", // Tryhard EDM/Trap
    "https://open.spotify.com/playlist/1oL8N6M6nRyIaSgRUgoNe5"  // Gaming & Phonk Edits TikTok
  ],
  chill: [
    "https://open.spotify.com/playlist/3n6wbQbw4kTtOwhn8yfMKC", // Chill Gaming 2026 HipHop/EDM/Phonk
    "https://open.spotify.com/playlist/15eJCdcsxMvR0KJhYRnYx4"  // Gaming Vibes Weekly
  ],
  fun: [
    "https://open.spotify.com/playlist/1oL8N6M6nRyIaSgRUgoNe5", // TikTok Phonk 2026 Viral
    "https://open.spotify.com/playlist/2yf15hiBRKPKPQlJNfENUE"  // Top 50 Phonk 2026
  ]
};

const moodYT = { // YouTube Fallbacks – variiert auch
  epic: "https://www.youtube.com/watch?v=cLxOABXI5Fo",
  aggressive: "https://www.youtube.com/watch?v=qnOyx6lErr4",
  chill: "https://www.youtube.com/watch?v=joOGhQGUcDY",
  fun: "https://www.youtube.com/watch?v=hoPnIxK76h4"
};

let customLinks = JSON.parse(localStorage.getItem("customLinks") || "[]");
let favs = JSON.parse(localStorage.getItem("gameMusicFavs") || "[]");

function pickGame(game) {
  document.getElementById("game").value = game;
}

function rand(arr) {
  if (!arr || arr.length === 0) return null;
  return arr[Math.floor(Math.random() * arr.length)];
}

function getSpotifyEmbed(url) {
  const playlistId = url.split('/playlist/')[1]?.split('?')[0];
  if (!playlistId) return '';
  return `https://open.spotify.com/embed/playlist/${playlistId}?utm_source=generator&theme=0`;
}

function showResult(title, desc, ytLink, spotifyUrl = '') {
  let html = `
    <strong>${title}</strong><br><br>
    ${desc ? `<em>${desc}</em><br><br>` : ''}
    <button class="open-btn song-btn" onclick="window.open('${ytLink}', '_blank')">
      ▶️ YouTube Alternative
    </button>
    <button class="fav-btn song-btn" onclick="saveFav('${ytLink}|${spotifyUrl || ''}')">
      ❤️ Favorit
    </button>
  `;

  if (spotifyUrl) {
    const embedSrc = getSpotifyEmbed(spotifyUrl);
    if (embedSrc) {
      html += `
        <div class="spotify-player">
          <iframe src="${embedSrc}" width="100%" height="480" frameborder="0" allowfullscreen allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture" loading="lazy"></iframe>
        </div>
      `;
    }
  }

  document.getElementById("result").innerHTML = html;
}

function findSong() {
  const gameInput = document.getElementById("game").value.trim().toLowerCase();
  const mood = document.getElementById("mood").value;

  let spotifyUrl = "";
  let ytLink = moodYT[mood] || "https://www.youtube.com/watch?v=cLxOABXI5Fo";
  let desc = "Beste 2026 Gaming-Musik – variiert pro Suche! 🔥";

  // 1. Custom priorisieren (50% Chance)
  if (customLinks.length > 0 && Math.random() > 0.5) {
    const custom = rand(customLinks);
    if (custom.includes("spotify.com")) spotifyUrl = custom;
    else ytLink = custom;
    desc += " (dein Custom-Track!)";
  }

  // 2. Spiel-spezifisch (wenn Spiel eingegeben)
  if (gameInput) {
    for (let key in gamePlaylists) {
      if (gameInput.includes(key)) {
        spotifyUrl = rand(gamePlaylists[key]);
        desc = `Top-Match für **${key.toUpperCase()}** – variiert jeden Mal!`;
        break;
      }
    }
  }

  // 3. Stimmung (wenn keine spiel-spezifische → oder ergänzend)
  if (!spotifyUrl && mood && generalPlaylists[mood]) {
    spotifyUrl = rand(generalPlaylists[mood]);
    desc = `Beste **${mood.toUpperCase()}** Vibes 2026 – nicht immer dieselbe!`;
  }

  // 4. Ultimativer Fallback: allgemein beste Gaming-Playlist
  if (!spotifyUrl) {
    spotifyUrl = rand(generalPlaylists.epic || generalPlaylists.aggressive || []);
    desc = "Allgemein beste Gaming-Hits 2026 – Phonk/EDM Mix!";
  }

  showResult("GOD hat die BESTE für dich gefunden!", desc, ytLink, spotifyUrl);
}

function randomSong() {
  const mood = document.getElementById("mood").value;
  let spotifyUrl = "";
  let ytLink = "https://www.youtube.com/watch?v=cLxOABXI5Fo";

  if (mood && generalPlaylists[mood]) {
    spotifyUrl = rand(generalPlaylists[mood]);
    ytLink = moodYT[mood];
  } else {
    const allGeneral = [...(generalPlaylists.epic || []), ...(generalPlaylists.aggressive || []), ...(generalPlaylists.chill || []), ...(generalPlaylists.fun || [])];
    spotifyUrl = rand(allGeneral);
  }

  showResult("🎲 Zufalls-Top-Track 2026!", mood ? `${mood.toUpperCase()} – frisch variiert` : "Random Banger", ytLink, spotifyUrl);
}

// Restliche Funktionen bleiben gleich (addSong, saveFav, showFavs)
function addSong() {
  const link = document.getElementById("customLink").value.trim();
  if (!link || (!link.includes("youtube.com") && !link.includes("spotify.com"))) {
    alert("Bitte gültigen YouTube- oder Spotify-Link!");
    return;
  }
  if (!customLinks.includes(link)) {
    customLinks.push(link);
    localStorage.setItem("customLinks", JSON.stringify(customLinks));
    alert("Hinzugefügt – wird in Suchen variiert!");
  } else {
    alert("Link schon drin!");
  }
  document.getElementById("customLink").value = "";
}

function saveFav(value) {
  if (!favs.includes(value)) {
    favs.push(value);
    localStorage.setItem("gameMusicFavs", JSON.stringify(favs));
    alert("Favorit gespeichert ❤️");
  } else {
    alert("Schon Favorit!");
  }
}

function showFavs() {
  if (favs.length === 0) {
    document.getElementById("result").innerHTML = "Keine Favoriten.";
    return;
  }
  let html = "<strong>❤️ Favoriten (YT | Spotify):</strong><br><br>";
  favs.forEach(item => {
    const [yt, spot] = item.split('|');
    html += `<button class="open-btn song-btn" onclick="window.open('${yt}','_blank')">▶️ YouTube</button>`;
    if (spot) html += ` <button class="open-btn song-btn" onclick="window.open('${spot}','_blank')">Spotify</button>`;
    html += "<br><br>";
  });
  document.getElementById("result").innerHTML = html;
}
</script>
</body>
</html>
