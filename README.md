### Macatangay and Villados Project Proposal
---
  # Whispers of Ghibli ୭ .ᐟ.ᐟ
### "Where Magic Meets Hand-Drawn Wonder" 
https://aravilalado.github.io/WDProjBeMacatangayVillados/public/homepage.html

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

#### P4 (Interactive) -- "The Ghilbi Realm Entry": 
- Content: Mini interactive experiences inspired by Ghibli films (e.g., drag-and-drop Totoro leaves, click to reveal hidden creatures, links to quizzes and the ghibli museum, character dress-up, or switch UI themes). Includes a secret pop-up of a delivery from Kiki. Will also be used as a preferences/log-in page
- JS Features: The interactive elements are all javascript, Drag-and-drop Totoro leaf/soot sprites, Click-to-reveal hidden creatures (Kodama rustling, soot sprites popping out), Animated floating elements (leaves drifting, fireflies glowing), Secret popup: “Delivery from Kiki” (Appears randomly or when triggered by user action), Sound toggle for ambience (forest, soft wind, chimes), Title text animation (fade-in, typewriter effect), Canvas particle animation — falling leaves / soot, Hover animations (characters react when hovered)
  
#### P5 (Trivia & Easter Eggs – “Hidden Whispers”):
- Content: Fun facts, hidden references, and Ghibli secrets. Can include quizzes and challenges for users.
- JS Features: Trivia quiz pop-ups, Score reveal & animated transitions, Expandable cards (Click to reveal hidden fun facts, quotes), Timed challenges (e.g., find all soot sprites in 20 sec), Konami Code easter egg   → triggers secret animation / song, Random fact generator, Progress tracking (Shows trivia discovered (localStorage)), Hover reveal → image shows hidden info when hovered, Collect hidden items (Points when finding mini sprites)
  
#### P6 (Sources + Behind the Website): 
- Content: Sources for various images, information, and art around the website. Info and descriptions about the websitemakers
- JS Features: Collapsible source list, Developer cards that flip on hover/click, Tabs for different content categories (credits, bios, sources), Animated scroll reveal, Show more/less toggle for long texts

  
---
## Updated Project Proposal: HTML Forms Integration
###### pages 4-6 will be the 3 updated websites for this integration but all 6 webpages would be affected. Some aspects of page 4 was changed to better fit the integration

### Overview of the Update
To enhance interactivity, inclusivity, and personalization of the site, the website will incorporate an HTML form that collects user input and saves it on the user’s computer using JavaScript and localStorage. The collected data will then be used dynamically across at least two other webpages, making the website feel more immersive and responsive to each user.
The form will align with the magical, cozy, and whimsical Studio Ghibli theme of the site.

The HTML form will serve as a Visitor Passport / Realm Entry Form, allowing users to:
- Enter a display name
- Choose their favorite Ghibli film or realm
- Select preferred interactive features (trivia, ambience sounds, mini-games)
- Opt in to easter eggs and hidden/exclusive content
Provided nformation will be used to personalize interactions, unlock special effects, and track progress across the website/s.

#### P4 – The Ghilbi Realm Entry

##### Content & Form Design
- A themed HTML form styled like a magical passport or letter from Studio Ghibli
- Input elements:
Text input: Visitor Name
Dropdown: Ghibli Realm (which is essentially theme options would be some of the popular movies/characters)
Checkboxes: Preferred activities (Trivia, Interactive Animations, Sounds)
Toggle: Enable secret deliveries & easter eggs
- A “Enter the Realm” button that saves the data to localStorage
##### Function
- On submission:
User data is validated
Data is saved to the user’s computer
User is redirected to P1 and allowed access to hidden interactions on P5
##### Visual feedback:
- Animated confirmation based on the chosen realm/theme


#### P5 – Trivia & Easter Eggs (“Hidden Whispers”)
#####Use of Stored Data
- Displays a personalized greeting (e.g., “Welcome back, Ara!”)
- Trivia questions adapt based on:
- User’s chosen favorite film
- Previous trivia progress

##### Progress tracking:
- Score and discovered secrets saved and retrieved from localStorage. may add a button that shows how many have been discovered over how many are left 
- Special easter eggs:
- Certain features unlock only if the user opted in via the form
- Konami Code triggers extra effects only for registered users


#### P6 – Sources + Behind the Website + mini ghibli-themed Photobooth for fun 
##### Use of Stored Data
- Personalized message thanking the visitor by name
- Registered users may add comments

##### Displays:
- How many trivia items or secrets the user has discovered (same as the button)
- A “journey summary” of their interaction with the site

##### Optional feature:
- Button to clear saved data (reset progress and preferences)

---
## Wireframes
| Page | Base | Expanded |
|---|---|---|
| Home Page: | ![Home page 1](https://github.com/aravilalado/WDProjBeMacatangayVillados/blob/main/assets/Homepage%201.png) ![Home page 2](https://github.com/aravilalado/WDProjBeMacatangayVillados/blob/main/assets/Homepage%202.png) | n/a |
| First Page (A Journey Through the Films): | ![1](https://github.com/aravilalado/WDProjBeMacatangayVillados/blob/main/assets/P1%20(Movies%20%E2%80%93%20%E2%80%9CA%20Journey%20Through%20the%20Films%E2%80%9D).png) | ![1 expanded](https://github.com/aravilalado/WDProjBeMacatangayVillados/blob/main/assets/P1%20-%20expanded%20ver.%20(when%20a%20movie%20card%20is%20clicked%20on).png) |
| Second Page (Icons of Ghibli): | ![2](https://github.com/aravilalado/WDProjBeMacatangayVillados/blob/main/assets/P2%20(Characters%20%E2%80%93%20%E2%80%9CIcons%20of%20Ghibli%E2%80%9D).png) | ![2 expanded](https://github.com/aravilalado/WDProjBeMacatangayVillados/blob/main/assets/P2%20(Characters%20%E2%80%93%20%E2%80%9CIcons%20of%20Ghibli%E2%80%9D)%20(2).png) |
|  enter realm page  |  ![4](https://github.com/aravilalado/WDProjBeMacatangayVillados/blob/main/public/P1%20(Movies%20%E2%80%93%20%E2%80%9CA%20Journey%20Through%20the%20Films%E2%80%9D).png?raw=true))  |  |
|  hidden whispers  |  ![5]((https://github.com/aravilalado/WDProjBeMacatangayVillados/blob/main/public/Homepage%201.png?raw=true)  |  |
|  sources + info  |  ![6](https://github.com/aravilalado/WDProjBeMacatangayVillados/blob/main/public/Homepage%201%20(1).png?raw=true))![7](https://github.com/aravilalado/WDProjBeMacatangayVillados/blob/main/public/Homepage%201%20(2).png?raw=true)  |  |

---
## FINAL MODIFICATION Proposal
##### This section documents the updated design and implementation plan for localStorage data management (CRUD), updated wireframes, and all new feature additions introduced in the final modification phase.
### Overview of modifications
The final modification expands on the previous HTML Forms integration plan along with 3 major aditions to include CRUD
#### 1.   Photobooth section included in P6 - Behind the Website
- CRUD: Users may take a picture using the available camera (website asks permission before accessing) and it is saved to local storage. Users would then select a few of those pictures to either download individually or create a photo strip with ghibli-themed stickers and frames. Users may save the aforementioned photostrips to edit later, edits are saved as well and photos can be deleted with a click of a button.
#### 2. An Account Preferences Update system that is accessible in every webpage allowing users to modify their saved visitor profile at any time.
- users may update their account preferences such as preferred name, theme, and favorite movie at anytime
#### 3. Users may have the option to delete all saved local storage data on the site

### localStorage CRUD Design & Narrative
#### Purpose
The site uses localStorage as a lightweight, browser-based persistence layer — no accounts, no servers, no logins required. This keeps the experience magical and low-friction, fitting the whimsical Ghibli spirit. Users build a personal "realm profile" as they explore the site, and that profile persists across visits until they choose to change or remove it. All stored data is local to the user's browser and device. Nothing is transmitted to any server.

### CRUD Operations by feature
#### 1. Create and Update of User visitor profile and preferences
- CREATE (First Visit):
When a user fills out the Realm Entry Form for the first time and clicks "Enter the Realm," all form values are validated and written to localStorage. A success animation plays (themed to the chosen realm), and the user is redirected to P1.
- UPDATE (Return Visit / Edit Preferences):
On P4, returning users (those with existing localStorage data) will see their form pre-populated with their saved preferences. A clearly labeled "Update My Realm" button (distinct from the initial "Enter the Realm" button) allows them to overwrite saved values. On save, a brief confirmation animation plays — "Your realm has shifted!" — and updated values propagate immediately to P5 and P6 on next load.
#### 2. Trivia & Easter Eggs (P5) Read and Update
- READ:
On page load, P5 reads wog_name, wog_realm, wog_activities, wog_easter_eggs, and wog_trivia_progress from localStorage. This data drives the personalized greeting, adaptive trivia questions, and locked/unlocked easter egg content.
- UPDATE:
Every time a user answers a trivia question, discovers a hidden creature, or triggers an easter egg, their wog_trivia_progress entry is updated silently in the background. A progress indicator (e.g., "12 of 30 secrets found") reflects the live state of this data.
#### 3. Photobooth (P6) Full CRUD
The Ghibli Realm Photobooth is a fun, low-stakes creative feature tucked into the "Behind the Website" page. Users can snap photos using their device camera (with explicit permission requested), decorate them with Ghibli-themed stickers and frames, and save personal photo strips as keepsakes of their visit to the realm.
- READ AND UPDATE
On P6 load, all saved photos are retrieved from wog_photos and displayed in a scrollable gallery beneath the camera. Saved photo strips are retrieved from wog_photostrips and shown in a separate "My Strips" section. The user may select 2–4 photos from their gallery to compose a photo strip. A strip editor opens with options to: apply a Ghibli-themed frame (e.g., Totoro forest, Spirited Away bathhouse, Howl's castle), add sticker overlays (soot sprites, Kodama, No-Face mask, catbus), and rearrange photo order via drag-and-drop. Clicking "Save Strip" serializes the strip configuration (selected photo indices, frame ID, sticker placements) and saves it to wog_photostrips in localStorage. Clicking "Edit" on a previously saved strip reopens the editor with the saved configuration loaded — allowing the user to revise and re-save.
- DELETE
Individual photos can be deleted from the gallery by clicking a small ✕ button on each photo tile. A soft confirmation prompt appears: "Send this memory to the spirit world?" with Yes/No options. Individual photo strips can be deleted from the "My Strips" section similarly. Deletion updates the relevant localStorage key immediately and re-renders the gallery.
- Download (non-storage)
Individual photos can be downloaded directly via a download button (no localStorage interaction — the base64 data is fed directly to an <a> download link). Completed photo strips can be rendered to a Canvas element and downloaded as a single PNG.
#### 4. Data Reset Option
A "Leave the Realm" button is available at the bottom of P6. When clicked, a styled confirmation modal appears:
``` "Are you sure you want to leave? All your progress, photos, and realm preferences will be forgotten. Even Totoro won't remember you." ```
Two buttons: "Stay in the Realm" (cancel) and "Clear Everything" (confirm). On confirmation, localStorage.clear() is called, wiping all wog_* keys. The page refreshes, and the user is gently redirected to P4 to start fresh.

### Updates Wireframes
| Page | Base | Other Versions | Notes for coder (Ara)|
|---|---|---| --- |
| P4: Realm Entry & Preferences (Create + Update) | . | n/a |  If localStorage has saved data → pre-fill all fields; show "Update Realm" button.If no saved data → show empty form; show "Enter the Realm" button. Validation: Name must not be empty; realm must be selected. On success: brief overlay animation either redirect to P1 (first visit) or stay on P4 (update)|
| P6: Photobooth in Behind the Website (Create, Read, Update, Delete) | . | . | Camera section: renders only after user clicks "Open Photobooth" (lazy load; permission requested at that point), Photos stored as base64 in wog_photos[] array (max 12), Strip config stored in wog_photostrips[] (frame id, sticker data, photo indices), Edit button re-opens photo strip Editor with pre-loaded saved config, Delete triggers soft confirm modal ("Send to the spirit world?") |
| P5: Trivia Progress & Personalization (Read + Update) | . | . | Page reads localStorage on load; gracefully degrades if no data, All progress updates (trivia score, creature finds) immediately write back to wog_trivia_progress in localStorage, Easter egg section conditionally rendered based on opt-in flag, Konami Code easter egg checks for wog_name before triggering |
|  P6: Data Reset Panel (Delete All)  | . | . | n/a |


