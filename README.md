# advancedFriendList

> Adds two tabs ("Blocked" and "Ignored") to the Friends page

[![Vencord](https://img.shields.io/badge/Vencord-unofficial%20userplugin-5865F2?style=flat-square&logo=discord&logoColor=white)](https://vencord.dev)
[![License](https://img.shields.io/github/license/Kaerion0/advancedFriendList?style=flat-square&color=8b949e)](./LICENSE)
[![Last commit](https://img.shields.io/github/last-commit/Kaerion0/advancedFriendList?style=flat-square&color=2ea043)](https://github.com/Kaerion0/advancedFriendList/commits)
[![Stars](https://img.shields.io/github/stars/Kaerion0/advancedFriendList?style=flat-square&color=f5c542)](https://github.com/Kaerion0/advancedFriendList/stargazers)

## Screenshots

<p>
<img src="https://github.com/user-attachments/assets/331600dc-2ad7-4779-9fbf-57b86818061e" width="100%" alt="screenshot">
</p>

## Installation

> [!IMPORTANT]
> Userplugins only work in Vencord built from source. Guide: [docs.vencord.dev/installing](https://docs.vencord.dev/installing/)

Run all commands from the folder where Vencord is cloned.

1. Clone the plugin into `src/userplugins`:
   ```sh
   git clone https://github.com/Kaerion0/advancedFriendList src/userplugins/advancedFriendList
   ```
2. Build Vencord:
   ```sh
   pnpm build
   ```
3. Inject Vencord into Discord. Only needed once, if you haven't installed Vencord from source yet:
   ```sh
   pnpm inject
   ```
4. Fully restart Discord.
5. Enable it: **Settings → Vencord → Plugins → advancedFriendList**

### Update

From the Vencord folder, then restart Discord:

```sh
git -C src/userplugins/advancedFriendList pull && pnpm build
```

## Authors

<table>
  <tr>
    <td align="center" width="120">
      <a href="https://github.com/Kaerion0"><img src="https://github.com/Kaerion0.png?size=160" width="80" alt="Kaerion"><br><b>Kaerion</b></a>
    </td>
  </tr>
</table>
