Hier kommen deine eigenen MP3s rein.

Danach in index.html im Abschnitt "PLAYLIST CONFIG" (const playlist = [];) Eintraege ergaenzen, z.B.:

const playlist = [
    { title: "Intro", src: "mp3/01. Intro.mp3", cover: "Bilder/foto-01.jpeg" },
    { title: "Naechster Track", src: "mp3/02. Titel.mp3", cover: "Bilder/foto-01.jpeg" },
];

Der Player, die Playlist-Liste und der Download-Bereich fuellen sich dann automatisch.
