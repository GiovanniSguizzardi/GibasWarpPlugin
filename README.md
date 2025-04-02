![minecraft_warps](https://github.com/user-attachments/assets/bfc85e9f-c586-42c0-bc31-1cb17cf68231)

<h1 align="center">GibasWarps</h1>
<p align="center">
  🧭 Plugin de warps personalizadas com menu, ícones, permissões e muito mais!
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Minecraft-1.21%2B-blue?style=for-the-badge&logo=minecraft" />
  <img src="https://img.shields.io/badge/Java-21+-orange?style=for-the-badge&logo=openjdk" />
  <img src="https://img.shields.io/badge/API-Paper%20%2F%20Spigot-yellow?style=for-the-badge" />
</p>

---

## ✨ Funcionalidades

✅ Criação de warps com `/setwarp <nome>`  
✅ Teleporte com `/warp <nome>`  
✅ Menu GUI com `/warps`  
✅ Ícones com o item da mão via `/setwarpicon <nome>`  
✅ Cabeças personalizadas com textura Base64  
✅ Suporte a `display_name`, `lore` e `slot` no menu  
✅ Permissões por warp  
✅ Reload do config com `/gibaswarps reload`  
✅ 100% configurável via `config.yml`

---

## 🖼️ Exemplo de `config.yml`

```yaml
warps:
  spawn:
    world: world
    x: 0.0
    y: 64.0
    z: 0.0
    yaw: 0.0
    pitch: 0.0
    icon: GRASS_BLOCK
    display_name: "§aSpawn Principal"
    lore:
      - "§7Ponto inicial do servidor"
    slot: 13

  vip:
    world: world
    x: 100.5
    y: 70.0
    z: 200.5
    yaw: 90.0
    pitch: 0.0
    icon: DIAMOND_BLOCK
    display_name: "§bÁrea VIP"
    lore:
      - "§eSomente para jogadores VIPs"
    slot: 22
    permission: gibaswarps.warp.vip
