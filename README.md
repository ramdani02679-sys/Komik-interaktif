komik-interaktif/
│
├─ index.html
├─ style.css
├─ script.js
├─ story.json
└─ images/
   ├─ panel1.jpg
   ├─ panel2a.jpg
   └─ panel2b.jpg

{
  "start": "panel1",
  "panels": {
    "panel1": {
      "image": "images/panel1.jpg",
      "text": "Kamu menemukan pintu misterius di sekolah.",
      "choices": [
        { "label": "Buka pintu", "next": "panel2a" },
        { "label": "Pergi menjauh", "next": "panel2b" }
      ]
    },

 "panel2a": {
      "image": "images/panel2a.jpg",
      "text": "Di balik pintu ada cahaya terang.",
      "choices": [
        { "label": "Tamat", "next": null }
      ]
    },

  "panel2b": {
      "image": "images/panel2b.jpg",
      "text": "Kamu memilih pergi. Cerita berakhir.",
      "choices": [
        { "label": "Tamat", "next": null }
      ]
    }
  }
}
