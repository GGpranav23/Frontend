# 📝 Tmux Copy-Paste Cheatsheet (Your Config)

This cheatsheet is based on **your tmux keybindings** (from `list-keys`).  
Follow these exact steps to copy & paste text inside tmux.

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

   > (In your config, **Enter does not copy**. Use `Alt+w` instead.)

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
