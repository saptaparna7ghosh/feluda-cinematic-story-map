# 🕵️ The Feluda Cinematic Story Map

### *Where literature meets geospatial technology*

**What if your favourite story could live on a map?**

Not just words on a page, and not just a film on a screen. Imagine every scene pinned to the real place where it happens, so you can watch it, hear it and read it in your own language. Then you move on to the next scene as if you were travelling beside the characters.

That is what this project is. It takes five of Satyajit Ray's Feluda adventures and turns them into an interactive, cinematic journey across India and Nepal.

**Five stories. Thirty-two locations. One experience.**

---

## 👋 Who Is Feluda?

Satyajit Ray created Feluda in 1965. Pradosh Chandra Mitter, known to everyone as Feluda, is a private investigator from Kolkata. He is sharp in mind, disciplined in body and deeply rooted in Indian culture.

He never travels alone:

- **Topshe** (Tapesh) is his young cousin and our narrator. We see every mystery through his eyes.
- **Jatayu** (Lalmohan Ganguly) is a comic thriller writer whose warmth and enthusiasm bring both laughter and heart to every case.

Wherever Bengali culture has travelled, from Kolkata to London and from Mumbai to New York, Feluda has travelled with it. Yet for decades his world has lived only on the printed page and the cinema screen. This map is an attempt to let you walk through it.

---

## 🗺️ What You Can Do Here

**Pick a story.** Choose from the list at the bottom-left of the screen. The map narrows down to that story's own colour-coded markers.

**Click a marker.** Every numbered pin is a scene. It opens a full-screen moment with the movie clip playing behind the text, so the video feels like the world around you and not a thumbnail.

**Read it your way.** Every scene is written in **English, বাংলা and हिंदी**. Switch languages whenever you like.

**Keep going.** Use the previous and next buttons to follow the mystery from scene to scene without going back to the map each time.

**Meet the cast.** Profiles of **Satyajit Ray, Feluda, Topshe and Jatayu** sit outside any single story, so you can get to know them first. Each profile is also available in all three languages.

**Let the music play.** The Feluda theme plays softly in the background. It fades out when a scene video begins and returns when you close it, much like a film score.

---

## 📚 The Five Adventures

| Story | Scenes |
| --- | :---: |
| Golapi Mukta Rahasya | 8 |
| Joy Baba Felunath | 7 |
| Sonar Kella | 4 |
| Joto Kando Kathmandu-te | 6 |
| Tintorettor Jishu | 7 |

---

## 🎬 Why It Feels Different

This is meant to feel like stepping into a film, not like using a utility map.

- **A cinematic look.** The map tiles are dark and sepia-toned, and the two serif typefaces give it the feel of a vintage detective novel.
- **Story first, geography second.** You follow a curated path of story, marker, scene and next scene, instead of panning around aimlessly.
- **Multilingual from the start.** The three languages were built in from the beginning, not added later.
- **Built for phones too.** On a small screen the character buttons and story list become scrollable strips, and the scene panel becomes a bottom sheet so the video stays visible above it. Markers are bigger for easy tapping.

---

## 🛠️ Under the Hood

The location data was prepared in GIS software. Coordinates were taken from Google My Maps and exported as shapefiles, and each point carries its scene identity, narrative text and multimedia details in three languages.

The front end uses [Leaflet.js](https://leafletjs.com/), an open-source mapping library, with OpenStreetMap data. Everything else is plain HTML, CSS and JavaScript in **one self-contained `index.html` file**. It is lightweight and portable, needs no build step, and can be hosted anywhere.

---

## 🌱 Where This Could Go

Feluda is only the beginning. The same framework could map:

- **All of Feluda's adventures**, growing beyond these five stories
- **Animated scenes with voiceover narration** in every language
- **Tagore's journeys, the Partition narratives of 1947, Mughal trade routes**, or the folk traditions of any Indian state
- **Any author's world.** A novelist could show readers the cities, forests and coastlines that shaped their story, and readers could explore them.

Some of the practical uses:

- **Cultural tourism:** helping fans find the real places behind the stories
- **Education:** teaching literature, geography and film heritage in an engaging way
- **Heritage preservation:** keeping Ray's legacy alive in a new form
- **Regional language promotion:** bringing Bengali literature to Hindi and English readers

Great stories have always been about place. Here, the geography is the story.

---

## 👩‍💻 Credits

**Prepared by Saptaparna Ghosh**
📧 saptaparna7ghosh@gmail.com

If you have ideas, feedback or want to collaborate, please get in touch.

---

## ⚠️ A Note on Rights

This is a fan-made, non-commercial educational project made out of love for Satyajit Ray's work. Feluda, the stories, the characters and the films belong to their respective creators and rights holders. Images and videos are used for illustration only.

