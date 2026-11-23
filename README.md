# Unraid templates

Docker templates for Unraid.

| Template | Image |
|---|---|
| [pocket-commander.xml](pocket-commander.xml) | `ghcr.io/jorgentuck/pocket-commander`: root file manager server for the Pocket Commander Android app |

**Install** (Unraid terminal):

```bash
wget -O /boot/config/plugins/dockerMan/templates-user/my-pocket-commander.xml \
  https://raw.githubusercontent.com/jorgentuck/unraid-templates/main/pocket-commander.xml
```

Then Docker → Add Container → Template → **pocket-commander**. (Keep the `my-` prefix.)
