# Tmux Shortcuts, Tips & Tricks

![image](https://upload.wikimedia.org/wikipedia/commons/thumb/e/e4/Tmux_logo.svg/2560px-Tmux_logo.svg.png)

## :page_facing_up: What is tmux?

Tmux stands for "Terminal MUltipleXer". In other words, it means that you can run a Tmux session and then open multiple windows inside that session. Each window can be split into rectangular panes.

---

## :wrench: Installation

- Debian based

```
sudo apt install tmux
```

- RedHat based
```
sudo yum install tmux

sudo dnf install tmux
```

- macOS
```
brew install tmux
```

---

## :running: Starting
Run tmux by typing in your terminal:

`tmux`

---


## :smiley: Commands
> :warning: Usually tmux commands start with **Ctrl-b** prefix :blush:

| Key | Action |
| :-  | :-  |
Ctrl-b + %  | Vertical split |
Ctrl-b + "  | Horizontal split |
Ctrl-b + arrow keys | Move between panes |
Ctrl-b, then Ctrl+arrow | Resizing a pane  |
Ctrl-b + q | Display pane numbers for a short while |
Ctrl-b + x | Kill the current pane |
Ctrl-b + t | Show time |
Ctrl-b + z | Toggle pane zoom |
Ctrl-b + c | Creating new window |
Ctrl-b + w | List windows |
Ctrl-b + 2 | Going to window 2 |
Ctrl-b + p | Going previous window |
Ctrl-b + n | Going next window |
Ctrl-b + , | Rename window |
Ctrl-b + { | Move the current pane left |
Ctrl-b + } | Move the current pane right |
Ctrl-b + PageUp or PageDown | Scrolling in a pane |

---

## :sunglasses: Advanced Commands
Create session:
```
tmux new -s amirmohammad
```

Attaching to a session:
```
tmux att -t amirmohammad
```

Detach from session:
```
Ctrl-b + d
```

List session:
```
tmux ls
```

Delete a session:
```
tmux kill-window -t amirmohammad
```

---

## :telephone_receiver: Contact

- Amir mohammad Rezvaninia - [LinkedIn](https://www.linkedin.com/in/amirmohammadrezvaninia/) 

- Email Address: amirmohammadrezvaninia@gmail.com

---

## :man_technologist: Support project	
If you like the content, give it a :star: :wink: