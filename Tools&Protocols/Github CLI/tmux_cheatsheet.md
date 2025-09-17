# 📝 Tmux Copy-Paste Cheatsheet (Your Config)

This cheatsheet is based on **my tmux keybindings** (from `list-keys`).  
Dont Follow these exact steps to copy & paste text inside tmux. Instead get your key bindings by running:


1. First Enter tmux using "tmux" command
2. Then press ctrl + b then : to enter command prompt of tmux
3. Enter "list-keys" and then press enter

---

## 📋 Copying Text

1. **Enter Copy Mode**  
   ```
   Ctrl + b [
   ```

2. **Move Cursor**  
   Use `↑ ↓ ← →` arrow keys to move around.

3. **Start Selection**  
   ```
   Ctrl + Space
   ```

4. **Highlight Text**  
   Move with arrow keys to extend the selection.

5. **Copy Selection**  
   ```
   Alt + w
   ```

   > (In my config, **Enter did not copy which typically does in most of configs**. So i was Using `Alt+w` instead.)

---

## 📥 Pasting Text

- To paste the last copied selection:  
  ```
  Ctrl + b ]
  ```

---

## 🔑 Quick Reference

| Action              | Keys               |
|---------------------|--------------------|
| Enter copy mode     | `Ctrl+b [`        |
| Start selection     | `Ctrl+Space`      |
| Copy selection      | `Alt+w`           |
| Paste               | `Ctrl+b ]`        |
| Cancel selection    | `Esc`             |
| Page up/down        | `PgUp / PgDn`     |
