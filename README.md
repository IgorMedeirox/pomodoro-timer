```markdown
# ✅ Task Manager Mini-App

Welcome to my simple, stylish JavaScript task manager! 📋✨  
This project lets users **create**, **complete**, and **delete** tasks with a click of a button — perfect for anyone who loves staying organized with clean code and cool buttons.

---

## 🚀 Features

- ✨ **Add tasks** dynamically to your to-do list  
- ✅ **Mark tasks as done** with a stylish toggle effect  
- ❌ **Delete tasks** when you're done with them  
- 📦 Component-based logic with `BotaoConclui` and `BotaoDeleta` for clean separation of functionalities

---

## 🔧 Technologies Used

- Vanilla **JavaScript**
- DOM manipulation
- Modular design using `export/import`

---

## 🧠 How It Works

When a task is added:
- A new `<li>` element is created with a description
- The **"Conclude"** button toggles the `.done` class
- The **"Delete"** button removes the task completely from the list

```js
// Adding a task
novaTarefa.addEventListener('click', criarTarefa);

// Marking as done
tarefaCompleta.classList.toggle('done');

// Removing task
tarefaDeletada.remove();
```

---

## ✍️ Author's Note

This is just the beginning! I'm working on evolving my career as a developer 🚀  
Feel free to check out more of my work or suggest improvements!

---

## 📎 License

This project is free to use and modify. Just give credit where it's due 💙

```

Want me to add emojis, badges, or a demo GIF section too? Let's make this README pop like a task list on Monday morning! 😄📅✅
