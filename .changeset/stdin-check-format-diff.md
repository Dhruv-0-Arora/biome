---
"@biomejs/biome": patch
---

Fixed `biome check --stdin-file-path` without `--write` not showing formatting differences.
Biome now prints the same "Formatter would have printed the following content:" diagnostic that it prints in file mode, instead of only reporting that the contents aren't fixed.
