# DTC 477 Game Project Overview
**Game Title:** *The Adventures of Lewis and Clark – An Educational Game*  

**Concept & Goals:**  
This game is an educational experience designed for younger audiences, teaching them about the historical journey of Lewis and Clark. The gameplay is structured around **7 mini-games**, each representing a different stage of the expedition.  

The goal is to combine **interactive gameplay with historical storytelling**, allowing players to learn through engagement, exploration, and decision-making.

---

# Team & Roles
- **Marilyn:**  
  Intro sequence, Chapter 1 game, Chapter 2 game, journal system, dialogue box design & functionality  

- **Sophia:**  
  Chapter 3 game, Chapter 4 game, Chapter 5 game  

- **Dalila:**  
  Chapter 6 game, Chapter 7 (outro), ending sequence  

---

# Game Structure
The game consists of an **intro cutscene, 7 chapters (mini-games), and an outro sequence**.

---

## Intro Cutscene — St. Louis / Camp Dubois (1804)
- Lewis and Clark sprites are introduced through dialogue  
- President Jefferson assigns the mission:
  - Explore the Louisiana Purchase  
  - Map rivers  
  - Meet Indigenous tribes  
  - Find a water route to the Pacific  
- Players are introduced to **The Corps of Discovery**

---

## Chapter 1: What Are You Packing?
**Setting:** St. Louis (by the boat)  

**Gameplay:**  
- Drag-and-drop inventory system  
- Players choose which items to bring  
- Feedback provided via modal:
  - Correct items → explanation  
  - Incorrect items → reasoning  

- Items appear laid out on a table  

---

## Chapter 2: Up the Missouri River
**Setting:** Missouri River (keelboats/canoes)  

**Gameplay:**  
- Side-scrolling river navigation  
- Avoid obstacles:
  - Logs  
  - Rocks  
  - Strong currents  

---

## Chapter 3: Into Unknown Land (Spring 1805)
**Setting:** Leaving Fort Mandan → Rocky Mountains  

**Gameplay:**  
- Journal collection mini-game  
- Click plants and animals to collect entries  

**Journal Modal: Sioux Territory**
- Dialogue explaining historical context  
- Map showing location  

---

## Chapter 4: Grizzly Country
**Setting:** Montana plains / foothills  

**Gameplay:**  
- Bear encounter  
- Player rapidly presses spacebar to escape  

**Journal Modal: The Three Forks Decision**
- Missouri River splits into:
  - Jefferson River  
  - Madison River  
  - Gallatin River  
- Decision point:
  - Expedition follows **Jefferson River** toward Shoshone territory  

---

## Chapter 5: Crossing the Rockies (Bitterroot Mountains)
**Setting:** Rocky Mountains  

**Gameplay:**  
- Path decision mechanic  
- Choice:
  - Shortcut → leads to cliffs and snowstorm (failure)  
  - Follow guide → correct path  

---

## Chapter 6: Nez Perce Help — Dialogue Game
**Setting:** Idaho region  

**Gameplay:**  
- Dialogue-based interaction with Nez Perce tribe  
- Player selects correct dialogue options  
- Focus on narrative and cultural interaction  

**Journal Entry: Down the Columbia River**
- Plant and animal identification mini-game  

---

## Chapter 7 (Outro): “Ocean in View!”
**Setting:** Fort Clatsop / Pacific Ocean  

**Gameplay & Ending Sequence:**  
- Final map shows completed journey across America  
- Journal summary screen includes:
  - Rivers traveled  
  - Hardships faced  
  - Alliances formed  

**Final Dialogue:**  
- Lewis: “We have crossed a continent.”  
- Clark: “And now we must find our way home.”  

---

# Core Systems
- Consistent visual styling across all chapters  
- Shared systems:
  - Journal modal  
  - Dialogue boxes  
  - Map progression tracker  
- Reusable mechanics:
  - Click-and-drag  
  - Selection-based interactions  

---

# Folder Structure
- Individual **HTML file per chapter**  
- One **global CSS file**  
- Additional **chapter-specific CSS files**  
- Inline JavaScript within each HTML file  
- **Image folder** with organized subfolders  

---

# Setup Instructions
- All team members work in the same GitHub repository and branch  
- Each member works on **separate chapter files** to avoid overlap  
- Team communication is required:
  - Notify when starting work  
  - Notify when finished and pushing changes  

This workflow helps prevent merge conflicts.

---

# Git Workflow
- Same process as setup instructions:
  - Work within assigned files  
  - Communicate before and after changes  
  - Push updates regularly  

---

# Naming Conventions
- **CSS classes & IDs:** kebab-case  
- **JavaScript variables & functions:** camelCase  
- **File names (including images):** kebab-case  

---

# Style Guide
- Visual style: **pixelated, retro aesthetic**  
- Typography: Pixelify Sans (Google Fonts)  
- Consistent UI and sprite design across all chapters  