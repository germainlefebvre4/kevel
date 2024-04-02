---
hide:
  - navigation
  - toc
---

# Getting Started

Download the latest version of the library.

```bash
curl -o /usr/local/bin/kevel https://raw.githubusercontent.com/germainlefebvre4/kevel/main/kevel
chmod +x /usr/local/bin/kevel
```

Run the kevel command.

```bash
kevel version --output=yaml
```

**You are ready!**

To be able to use Krew commands, it is required to have a file at `/usr/local/bin/kubectl`.
Create a symlink from kevel to kubectl.

```bash
sudo ln -s /usr/local/bin/kevel /usr/local/bin/kubectl
```
