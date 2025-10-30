### Macatangay and Villados Project Proposal
---
  # Whispers of Ghibli ୭ .ᐟ.ᐟ
### "Where Magic Meets Hand-Drawn Wonder" 

| Logo                                                                                                 | Description                                                                                      |
| ------------- |:-------------:|
| ![logo](https://github.com/aravilalado/WDProjBeMacatangayVillados/blob/main/assets/totoro%20logo.webp)   The favicon displays a small and friendly Totoro waving, which is designed in a soft green-gray color that symbolizes his gentle and earthy nature. The color of the background is light tan, which gives the icon a warm and natural feel; a feel that is in accordance with the cozy and nostalgic aesthetic of the Studio Ghibli films. This minimalistic design reflects the inviting character of Whispers of Ghibli that silently welcomes every visitor through the browser tab with a little bit of magic. |   Whispers of Ghibli is a very emotional and sincere trip to the dream-like realm of the Studio Ghibli—where art, imagination, and feelings come together to create storytelling that will never be forgotten. This site is dedicated to the most famous characters and movies of the studio, the gentle spirit of Totoro to the amazing adventures of Chihiro and Howl. Every part of this website leads you to the repeat of wonders and the warmth that make Ghibli's creations still loved after so long. However, Whispers of Ghibli also goes on to explore the people and passion that were behind the masterpieces, not just through the screen. You will get to know the great artists who drew these fantasy worlds, the creative procedure that changed the hand-drawn magic to life, and lastly, go through an interactive area inspired by the studio's charm that will bring you a little bit of play. Just like that, the whispers lead you through a very special place where each and every frame is full of stories. |

---

## Webpage Breakdown

#### Homepage -- “Welcome to Whispers of Ghibli”
- Content: Short introduction to the site, cards directing to the other pages
- Javascript: Scroll-activated sections, Carousel/scrollable preview menu of website content, title text animations, Subtle floating elements (leaves/soot sprites drifting in the background)
  
#### P1 (Movies – “A Journey Through the Films”): 
- Content: Grid or card-based layout of all Studio Ghibli films (24 total). Each card includes: title, release year, director, and short synopsis. 
- JS Features: Clicking a movie card reveals a brief (but longer) synopsis, Small animated elements themed to each film (e.g., Spirited Away lights, Ponyo waves), and changes the UI color scheme to match the movie’s aesthetic, title text animations

#### P2 (Characters – “Icons of Ghibli”):
- Content: Gallery of iconic characters such as Totoro, Chihiro, Howl, Ponyo, etc. Each character card shows a brief bio, movie appearance, and notable quotes.
- JS Features: Carousel of popular characters (3 rows). Hover or click on the portrait to animate the character slightly (example: Totoro waves, Catbus moves, Kaonashi floats a bit, etc.) while a pop-out appears containing information about the character (example: movie in, likes and dislikes, notable features, etc.). title text animations

#### P3 (About the Studio – “The Art and Heart Behind Ghibli”): 
- Content: History of Studio Ghibli, founder bios (directors Hayao Miyazaki and Isao Takahata and producer Toshio Suzuki), hand-drawn animation techniques, production insights, creative processes, 	and behind-the-scenes images.
- JS Features: Timeline scroll feature for historical milestones,Flipbook-style creative process (A Ghibli character illustration gradually completes as the user scrolls or clicks through steps in the creative pipeline), Expandable bio cards for Miyazaki, Takahata, Suzuki, Interactive behind-the-scenes gallery (Hover to transform sketches → finished art title text animations), title text animations

#### P4 (Interactive) -- "The Ghilbi Realm": 
- Content: Mini interactive experiences inspired by Ghibli films (e.g., drag-and-drop Totoro leaves, click to reveal hidden creatures, links to quizzes and the ghibli museum, character dress-up, or switch UI themes). Includes a secret pop-up of a delivery from Kiki. 
- JS Features: The interactive elements are all javascript, Drag-and-drop Totoro leaf/soot sprites, Click-to-reveal hidden creatures (Kodama rustling, soot sprites popping out), Animated floating elements (leaves drifting, fireflies glowing), Secret popup: “Delivery from Kiki” (Appears randomly or when triggered by user action), Sound toggle for ambience (forest, soft wind, chimes), Title text animation (fade-in, typewriter effect), Canvas particle animation — falling leaves / soot, Hover animations (characters react when hovered)
  
#### P5 (Trivia & Easter Eggs – “Hidden Whispers”):
- Content: Fun facts, hidden references, and Ghibli secrets. Can include quizzes and challenges for users.
- JS Features: Trivia quiz pop-ups, Score reveal & animated transitions, Expandable cards (Click to reveal hidden fun facts, quotes), Timed challenges (e.g., find all soot sprites in 20 sec), Konami Code easter egg   → triggers secret animation / song, Random fact generator, Progress tracking (Shows trivia discovered (localStorage)), Hover reveal → image shows hidden info when hovered, Collect hidden items (Points when finding mini sprites)
  
#### P6 (Sources + Behind the Website): 
- Content: Sources for various images, information, and art around the website. Info and descriptions about the websitemakers
- JS Features: Collapsible source list, Developer cards that flip on hover/click, Tabs for different content categories (credits, bios, sources), Animated scroll reveal, Show more/less toggle for long texts

  
---
## Other Notes:
- Might try to include a little totoro/ponyo/jiji animated sprite (using sprite sheets / Frame-by-Frame Animation ) at the bottom corner

---
## Wireframes
| Page | Base | Expanded |
|---|---|---|
| Home Page: | ![Home page 1](https://github.com/aravilalado/WDProjBeMacatangayVillados/blob/main/assets/Homepage%201.png) ![Home page 2](https://github.com/aravilalado/WDProjBeMacatangayVillados/blob/main/assets/Homepage%202.png) | n/a |
| First Page (A Journey Through the Films): | ![1](https://github.com/aravilalado/WDProjBeMacatangayVillados/blob/main/assets/P1%20(Movies%20%E2%80%93%20%E2%80%9CA%20Journey%20Through%20the%20Films%E2%80%9D).png) | ![1 expanded](https://github.com/aravilalado/WDProjBeMacatangayVillados/blob/main/assets/P1%20-%20expanded%20ver.%20(when%20a%20movie%20card%20is%20clicked%20on).png) |
| Second Page (Icons of Ghibli): | ![2](https://github.com/aravilalado/WDProjBeMacatangayVillados/blob/main/assets/P2%20(Characters%20%E2%80%93%20%E2%80%9CIcons%20of%20Ghibli%E2%80%9D).png) | ![2 expanded](https://github.com/aravilalado/WDProjBeMacatangayVillados/blob/main/assets/P2%20(Characters%20%E2%80%93%20%E2%80%9CIcons%20of%20Ghibli%E2%80%9D)%20(2).png) |
