<img src="./sshot.png" width="260" />

# Usage

1. Copy `start_session.py` to `~/.config/kitty/`

   ```
   curl https://raw.githubusercontent.com/muchzill4/kitty-session/master/start_session.py > ~/.config/kitty/start_session.py
   ```

1. Create [kitty session](https://sw.kovidgoyal.net/kitty/index.html#startup-sessions) files in a directory of your choice

1. In `kitty.conf`

   ```
   map key kitten start_session.py "path/to/directory/with/sessions"
   ```
