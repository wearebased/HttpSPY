# HttpSPY

A lightweight and open-source **HTTPS Spy** tool for Roblox, built in Lua. This script lets you intercept and log outgoing HTTPS requests made by Roblox games — ideal for debugging, reverse engineering, or educational use.

---

## ⚙️ Features

-  Intercepts all `HttpService` requests
-  Logs:
  - Request URLs
  - Methods (GET, POST, etc.)
  - Body content (POST data)
-  Clean and readable output
-  Fully open-source and customizable

---

## 📁 How to Use

1. **Download or copy** the Lua script from this repository.
2. **Inject** it into your Roblox game session using a Lua executor.
3. **View captured requests** in your executor's console.

> Use this script only for **educational or debugging** purposes. Abusing it may violate [Roblox's Terms of Service](https://en.help.roblox.com/hc/en-us/articles/203313410-Roblox-Terms-of-Use).

---

## Disclaimer

> This tool is provided **as-is**, with no warranties.  
> Misuse can result in **account bans** or **legal consequences**.  
> **You are responsible** for how you use this code.



# Loadstring 
```lua
loadstring(game:HttpGet("https://raw.githubusercontent.com/wearebased/HttpSPY/refs/heads/main/main.lua"))()
```

```lua
[HTTPS SPY] URL: https://game.roblox.com/some/api
[HTTPS SPY] Method: POST
[HTTPS SPY] Body: { "userId": 12345678 }
