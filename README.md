# Hanzo-EasyUse

[![Open in Hanzo](https://hanzo.app/badges/open-in-hanzo.svg)](https://hanzo.app/dev/open?repo=github.com/hanzoai/Hanzo-EasyUse&ref=main&action=open) [![Edit with Hanzo](https://hanzo.app/badges/edit-with-hanzo.svg)](https://hanzo.app/dev/open?repo=github.com/hanzoai/Hanzo-EasyUse&ref=main&action=edit) [![Deploy with Hanzo](https://hanzo.app/badges/deploy-with-hanzo.svg)](https://hanzo.app/dev/open?repo=github.com/hanzoai/Hanzo-EasyUse&ref=main&action=deploy)

ComfyUI nodes that collapse common multi-node patterns into single nodes, so ordinary workflows stay small.

This is a Hanzo-maintained fork of [yolain/ComfyUI-Easy-Use](https://github.com/yolain/ComfyUI-Easy-Use), pinned so the ComfyUI node packs we
run together stay on versions we have tested together.

## Install

```bash
cd ComfyUI/custom_nodes
git clone https://github.com/hanzoai/Hanzo-EasyUse
cd Hanzo-EasyUse
[ -f requirements.txt ] && pip install -r requirements.txt
```

Restart ComfyUI. The nodes appear in the node menu under the categories upstream defines.

## Docs

Node reference and usage are upstream's — see [yolain/ComfyUI-Easy-Use](https://github.com/yolain/ComfyUI-Easy-Use). Nothing about the nodes
themselves is changed here.

## Contributing

Improvements to the nodes belong upstream: open them against
[yolain/ComfyUI-Easy-Use](https://github.com/yolain/ComfyUI-Easy-Use), and this fork picks them up on the next sync. Open an issue here only
for something specific to the fork.

## License

Upstream's; see the licence file in this repository.
