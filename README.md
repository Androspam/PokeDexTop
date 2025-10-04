# THE NATIONAL POKÉDEXTOP  
### Desktop App assistant for Pokémon Players – Updated v1.0.3

> - **Built any Pokémon game — tested on PokéMMO**  
> - Analyze types, teams, matchups & strategies in real time, EV yield, Compare, and many more ... 
> - **Alpha release** – feedback, ideas & bug reports are highly appreciated! 🙌

...

👋 Hey Trainers!
I’m excited to share the **first alpha versions** of a personal side project I’ve been working on
**Note:** This is an early **Alpha release** – bugs and issues are expected .. but I'd love your feedback like: What features should I add? What bugs did you find? What works well for you?

...

**🧠 Why I Built It**
To be honest — I don’t remember every Pokémon’s types…
and sometimes I don't remember what’s super-effective on "Rock Type or Poison Type" … 😅
And I found myself searching online mid-game way too often. So I connected to the **PokéAPI** and built a fast, visual tool to answer all these questions **on the spot**, while playing.
It’s built to help people like me — and hopefully, you too :)

...

**💡 What is PokéDexTop?**
A desktop assistant app for Pokémon fans and players.
Works alongside any pokemon game – gives you ... **fast type analysis, team matchups, and more ...**



## Main Features

### 🎮 Game / Generation Selection  
Choose which generation or Pokémon game you're currently playing — 
data will adapt accordingly

### 🎯 Type Analyzer  
View all **strengths, weaknesses, and resistances** of any Pokémon.  
Includes accurate calculations for **dual-types** and **Pro Mode multipliers** (×4, ×2, ×0.5, ×0.25 …).

### 👥 Team Matchup Checker  
Build your current Pokémon team and analyze it instantly:
- Search any enemy Pokémon  
- See which of your team members are **strong**, **weak**, or **neutral**  
- Plan your strategy in seconds!

### 🎛️ Filter & Sort System  
Sort by stats (Attack, Speed, Total, etc.)  
or filter Pokémon by specific type — perfect for team composition and optimization.

### ✨ Shiny Mode  
Toggle shiny sprites for your entire Pokédex view with one click 

### 📊 Types Tab (Type Chart)  
Access a clean, visual **type chart** — no memorizing required.  
Supports both *Normal Mode* and *Pro Mode* (with multipliers ×2, ×4, ×0.5, ×0.25).

### 🖼️ Game Overlay Mode  
A **draggable, minimal overlay** for live use while gaming.  
Shows:
- Type effectiveness  
- Weaknesses / resistances  
- Quick stats, EV yield, base EXP, catch rate, and battle tips  
Currently optimized for **Windowed Mode** (fullscreen support coming soon).

### ⚙️ Additional Features

- 🧾 **Full Pokédex Info** — Abilities, Egg Groups, EV Yields, Height/Weight, Catch Rate, etc.  
- 🔗 **Evolution Chain Viewer**  
- 🌙 **Dark Mode** (experimental)  
- 🔍 **Smart Search & Quick Access Tabs**

---

## 📸 Screenshots & Guides

### Hompage
**PokeDexTop Homepage** – featuring sorting, type filters, shiny toggle, and the feature to build your own Pokémon team party.
In the example below, you can see that I selected **Charizard**, **Pikachu**, **Kingdra**, **Tyranitar**, and **Hariyama** for my team.

<img width="60%" height="60%" alt="image" src="https://github.com/user-attachments/assets/a462dee3-87b3-4cde-ba22-05438f60ad14" />

### Pokemon Profile (info, stats, battle, moves, evolutions)
**About Tab** -  Get quick access to essential details for any Pokémon you search: species, gen, abilities, gender ratio, egg groups, hatch steps, base XP, EV yield — all in one place.

<img width="60%" height="60%" alt="image" src="https://github.com/user-attachments/assets/30ab6823-84f9-4f8e-8bc6-d26300ee45b2" />

**Stats tab**
<img width="60%" height="60%" alt="image" src="https://github.com/user-attachments/assets/b9704325-b371-4c93-bceb-b19991bf984f" />

**Battle Tab** – In the screenshot below, you can see a full analysis of **your team’s matchup** against a specific Pokémon (e.g., Bulbasaur).
You can also view that Pokémon’s **type weaknesses** even without setting up a team!

**1. Why is there a border on some of the Types badges?**
If a **border** appears around a type badge, it means the **secondary type** of the searched Pokémon is **strong against that type.**
If you see a **mixed (dual-colored) border**, it means **both primary and secondary types** are strong against that type.

<img width="60%" height="60%" alt="image" src="https://github.com/user-attachments/assets/15d1cf8a-5112-42fe-88ba-fd9c6aac0c5e" />

<img width="60%" height="60%" alt="image" src="https://github.com/user-attachments/assets/0dad31b5-95d6-4933-a10a-c1a4acab7e93" />

**2. what is Normal and Pro Mode?**
• **Normal Mode** - A simplified view showing whether a Pokémon is generally **strong** or **weak** — perfect for quick decisions during gameplay.
• **Pro Mode** Designed for advanced players who want to see the exact **type effectiveness values** like: `×2 damage to`, `×0.5 damage from`, `×4`, `×0.25`, etc ..

When enabled with your team, **Pro Mode** shows you exactly **why** each of your Pokémon is considered -> Strong / Weak / Good / Bad / ETC ..

<img width="60%" height="60%" alt="image" src="https://github.com/user-attachments/assets/5d2a9c9d-13cf-4141-8c14-ef3efdfcfc86" />

`ATK` = How much **damage your Pokémon deals.** `DEF` = How much **damage your Pokémon takes**

### Types Tab
The **Types Tab** gives you quick access to a full **type effectiveness chart** – perfect for checking strengths and weaknesses on the fly.
It supports both **Normal Mode** (simple view) and **Pro Mode** (with ×2, ×4, ×0.5, ×0.25, ×0 indicators) for more in-depth analysis.
Whether you're new to type matchups or a veteran trainer looking for exact multipliers — this tab has you covered.


### Settings Tab
Customize your experience in the Settings Tab:

🌙 **Dark Mode** – toggle between light and dark themes (currently experimental)
🎮 **Game/Generation Selector** – choose the Pokémon generation or game you’re currently playing; all data will adapt accordingly

~ **If you're playing PokeMMO** – make sure to select **By Generation -> Generation 5 (Gen 1–5)** in the settings.
This will show only Pokémon from **Gen 1 to Gen 5, excluding Fairy-type**, just like in PokeMMO's current implementation.

### Game Overlay Mode
The **Game Overlay** is a compact, draggable version of the main app — designed to sit **on top of your game window** while you play.
It includes only the essential tools you need for quick decisions ->

**Search any Pokemon** to instantly view its type analysis, weaknesses, and resistances .. with basic about info like EV Yield, Base Exp, Catch Rate .. and Battle Tips

The Battle Tips Section gives you quick insights about any Pokemon you search .. it analyzes key data such as ( Type, Base stats like ATK, HP, SPD, DEF, and more)
And instantly tells you things like ( "Slow Pokemon - consider using Trick Room strategy!", "High HP - great for tanking hits!")

**See how** that Pokemon matches up **against your existing team**
⚠️ To edit or manage your team, use the **main app**

~ Perfect for staying focused in-game while still getting the info you need in real time.
Currently optimized for **Windowed Mode** (fullscreen support planned in the future).

That’s it for now —
This is my personal side project, built from passion as a Pokemon fan, and I truly hope it helps you enjoy the game and other pokemon games even more!
**Keep in mind:** this is an **early Alpha version**, so bugs may appear - and your feedback is super valuable!
Got an idea for a cool feature? Let me know! There's always room to grow XD
