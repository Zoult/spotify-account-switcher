## Spotify Account Switcher ([Download](https://raw.githack.com/Zoult/spotify-account-switcher/main/Spotify%20Account%20Switcher.bat))

A simple tool that helps users switch between multiple Spotify accounts without having to re-enter credentials every time — ideal for strong passwords users

```diff
+ Save multiple Spotify accounts
+ Quickly load a saved account
+ Rename or delete stored profiles
+ Import/export account data (prefs file)
- No server-side Spotify integration
```

```
[t] List     - Show all saved accounts
[s] Save     - Save the currently logged-in account
[r] Rename   - Rename a saved account
[d] Delete   - Delete a saved account
[l] Load     - Load a saved account
[u] Unload   - Remove the active account
[e] Export   - Export current prefs to a chosen folder
[i] Import   - Import a prefs file and set it as active
```

```
%AppData%\Spotify\
├── prefs            < Currently active account
└── Users\
    ├── main         < Saved prefs
    ├── alt          < Saved prefs
    ...
```