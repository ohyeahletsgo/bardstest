---
layout: default
---

{{% include navigation.html %}}

<h1>{{ page.name }}</h1>

<p>{{ page.race }} {{ page.class }} / {{ page.secondary-class }} level: {{ page.level }}

Class info: {{ page.class-link }}

## Character Stats

**BASIC STATS**

| Stat         | Value | Buff |
| ------------ | ----- | ---- |
| Strength     | {{ page.strength-basic }}   | {{ page.strength-basic-buff }}   |
| Dexterity    | {{ page.dexterity-basic }}    | {{ page.dexterity-basic-buff }}   |
| Constitution | {{ page.constitution-basic }}    | {{ page.constitution-basic-buff }}   |
| Intelligence | {{ page.intelligence-basic }}    | {{ page.intelligence-basic-buff }}   |
| Wisdom       |{{ page.wisdom-basic }}     | {{ page.wisdom-basic-buff }}   |
| Charisma     | {{ page.charisma-basic }}    | {{ page.charisma-basic-buff }}   |

**CORE STATS***

| Stat         | Value |
| ------------ | ----- |
| Health Points | {{ page.damage }} / {{ page.health-points }} |
| Inspiration  | {{ page.inspiration }}     | 
| Proficiency  | {{ page.proficiency }}    | 
| Armor Class  | {{ page.armor-class }}    | 
| Initiative   | {{ page.initiative }}    | 
| Speed        | {{ page.speed }} | 

**SAVING THROWS**

| Stat         | Value |
| ------------ | ----- |
| Strength     | {{ page.strength-saving-throw }}     |
| Dexterity    | {{ page.dexterity-saving-throw }}    |
| Constitution | {{ page.constitution-saving-throw }}     |
| Intelligence | {{ page.intelligence-saving-throw }}     |
| Wisdom       | {{ page.wisdom-saving-throw }}     |
| Charisma     | {{ page.charisma-saving-throw }}    |

**SKILLS**

| Stat                  | Value |
| --------------------- | --------------- |
| Acrobatics (Dex)      | {{ page.acrobatics }}      |
| Animal Handling (Wis) | {{ page.animal-handling }} |
| Arcana (Int)          | {{ page.arcana }}          |
| Athletics (Str)       | {{ page.athletics }}       |
| Deception (Cha)       | {{ page.deception }}       |
| History (Int)         | {{ page.history }}         |
| Insight (Wis)         | {{ page.insight }}         |
| Intimidation (Cha)    | {{ page.intimidation }}    |
| Investigation (Int)   | {{ page.investigation }}   |
| Medicine (Wis)        | {{ page.medicine }}        |
| Nature (Int)          | {{ page.nature }}     |
| Perception (Wis)      | {{ page.perception }}     |
| Performance (Cha)     | {{ page.performance }}    |
| Persuasion (Cha)      | {{ page.persuasion }}     |
| Religion (Int)        | {{ page.religion }}     |
| Sleight of Hand (Dex) | {{ page.sleight-of-hand }}     |
| Stealth (Dex)         | {{ page.stealth }}     |
| Survival (Wis)        | {{ page.survival }}     |

{{ content }}
  
