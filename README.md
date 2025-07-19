# 🧙 JavaScript Quest: The Forest of Choices

## 📖 Story Introduction

> **Dear Adventurer,**
>
> You wake up on a bed of moss, the sun peeking through tall trees. The air smells like wet bark and mystery. You have no idea how you got here—but you’re *not alone*.
>
> Next to you lies a stone tablet. Etched on it are these words:
>
> > _"The Forest of Choices tests only the bravest minds. Every decision shapes your fate. Choose wisely, for there are many paths, but only few ways out."_
>
> As you stand up and dust yourself off, you see **three paths** before you:
>
> ### 🔹 Path 1: The Spooky Cave 🕸️
> Dark and echoing, the cave murmurs secrets. Do you dare enter?
>
> ### 🔹 Path 2: The Deep Woods 🌲
> The trees here are twisted and ancient. Something watches from the shadows...
>
> ### 🔹 Path 3: The Glowing Road 🍄
> Mushrooms light the way, but the air is unusually sweet and strange.
>
> You realize one thing: the only way out is forward.
>
> **Every decision you make matters**. One step could lead you to freedom, fortune—or total failure. 😵

---

## 🎯 Your Mission

Create a **text-based adventure game** using **JavaScript**. Your goal is to code a story that reacts to the user’s choices using **control flow**.

### 🧪 Requirements

1. Use at least:
   - One `if...else if...else` block
   - One `switch` statement
2. Use `prompt()` to get input from the player
3. Use `alert()` or `console.log()` to show what happens in the story
4. Create **at least 6 different endings**
5. Make the game creative, funny, or mysterious — your choice!

---

## 💡 Bonus Ideas (Optional)

- Use emojis to make it more fun 🎉
- Add unexpected endings or plot twists
- Give each path 2–3 steps of decisions

---

## 🧵 Sample Starter Code

```javascript
let choice1 = prompt("You wake up in a forest. Choose a path:\n1. Spooky Cave 🕸️\n2. Deep Woods 🌲\n3. Glowing Road 🍄");

if (choice1 === "1") {
  let caveChoice = prompt("The cave is dark. Do you:\nA. Light a torch 🔥\nB. Walk in blindly 😱");
  if (caveChoice === "A") {
    alert("You scare off the bats and find treasure! 💰");
  } else {
    alert("You fall into a pit. Oops! 💀");
  }
} else if (choice1 === "2") {
  // Add your forest logic
} else if (choice1 === "3") {
  // Add your glowing mushroom logic
} else {
  alert("You stand still... forever. Game over! 😂");
}
