# yo. i'm YoDoes.

```js
const dev = {
  age:      15,
  device:   "Android (Termux)",
  editor:   "Spck Code Editor",
  stack:    ["Node.js", "discord.js", "SQLite", "Express"],
  workflow: "Spck → GitHub → Termux → prod",
};
```

---

## what i'm building

### 🤖 [Amaze](https://github.com/YoDoesDev/Amaze) `v1.2.0`
A high-performance Discord bot with a full economy, stock market, and reputation system.

- Custom **Matrix-Database Architecture** over SQLite — atomic transactions, no race conditions
- Surgical **cache limits** tuned for 256MB RAM on mobile hardware
- Modular event system — `guildCreate`, `messageCreate`, `interactionCreate` each in their own module
- Dynamic command loaders for both prefix (`!`) and slash (`/`) commands
- Graceful shutdown with clean DB close on `SIGINT`

> Built entirely from a phone. No laptop. No desktop.

---

## how i work

Most devs have a MacBook. I have Termux and a phone.

Every commit gets pushed from **Spck** → pulled in **Termux** → running in prod.  
No CI/CD pipeline — I am the pipeline.

---

## stack

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![Discord.js](https://img.shields.io/badge/discord.js-5865F2?style=flat-square&logo=discord&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![REST APIs](https://img.shields.io/badge/REST_APIs-FF6C37?style=flat-square&logo=postman&logoColor=white)
![Webhooks](https://img.shields.io/badge/Webhooks-5865F2?style=flat-square&logo=discord&logoColor=white)

**patterns & architecture**
`Map-based caching` `sweep intervals` `modular event system` `atomic transactions` `composite-key DB abstraction` `dynamic command loaders` `dotenv config` `graceful shutdown`

---

## stats

![YoDoesDev's GitHub stats](https://github-readme-stats.vercel.app/api?username=YoDoesDev&show_icons=true&theme=dark&hide_border=true&bg_color=0d1117&title_color=ffffff&icon_color=ffffff&text_color=888888)

---

*building from a phone. shipping anyway.*
