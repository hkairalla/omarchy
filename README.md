# Codex limits visual verification for Omarchy PR #14630

These screenshots use synthetic RPC data, not personal account usage. Both were rendered with the actual upstream Agents panel in an isolated nested Hyprland desktop, using a fake app-server and separate HOME/XDG directories.

Before: collector at 50d687a1. After: collector at f19badb0. Both receive a legacy general quota plus a two-bucket map (25% general usage and 80% Other model usage). The corresponding JSON records are included.

The candidate renders two distinct rows without overlap. Long names are intentionally elided by the existing panel control; its tooltip carries the full title, percentage, and reset time. No QML layout or styling changed.
