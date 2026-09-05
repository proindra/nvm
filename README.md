<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=220&color=0:44A833,100:76B900&text=⬢%20NVM%20Handbook&fontSize=45&fontColor=ffffff&animation=fadeIn"/>

</div>

<p align="center">
<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&height=60&text=%3E_%20Easy%20Memory%20Trick&fontSize=28&color=0:44A833,100:76B900&fontColor=4C1D95"/>
</p>

| Tool         | Role                    | Comes with Node.js?                            |
| ------------ | ----------------------- | ---------------------------------------------- |
| **Node.js**  | JavaScript runtime      | ✅ Yes                                          |
| **npm**      | Package manager         | ✅ Yes                                          |
| **npx**      | Run package commands    | ✅ Yes                                          |
| **Corepack** | Manage Yarn / pnpm      | ✅ Included with Node.js 18, but needs enabling |
| **NVM**      | Manage Node.js versions | ❌ No — install separately                      |
| **Yarn**     | Package manager         | ❌ No — managed through Corepack                |
| **pnpm**     | Package manager         | ❌ No — managed through Corepack                |


> 💡 **Memory Trick:** NVM = Install + Switch + Manage Node.js versions.

<p align="center">
<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&height=60&text=%3E_%20Multiple%20Projects&fontSize=28&color=0:44A833,100:76B900&fontColor=4C1D95"/>
</p>

Different projects can use different Node.js versions.

```powershell
# Backend
nvm use 18.20.8

# Frontend
nvm use 20.19.0
```

> 💡 **NVM lets you switch Node.js versions without reinstalling Node.js.**

---

<p align="center">
<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&height=60&text=%3E_%20Quick%20Cheat%20Sheet&fontSize=28&color=0:44A833,100:76B900&fontColor=4C1D95"/>
</p>

| Task               | Command                   |
| ------------------ | ------------------------- |
| Check NVM          | `nvm version`             |
| List versions      | `nvm list`                |
| Available versions | `nvm list available`      |
| Install Node       | `nvm install <version>`   |
| Switch Node        | `nvm use <version>`       |
| Check Node         | `node -v`                 |
| Check npm          | `npm -v`                  |
| Check npx          | `npx -v`                  |
| Remove Node        | `nvm uninstall <version>` |
| Enable Corepack    | `corepack enable`         |
| Check Yarn         | `yarn -v`                 |

---

This is the version I'd recommend keeping in your notes: **short enough to remember, but covers the commands you'll actually use.**
