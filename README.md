# ai-sirens

Emergency vehicle lights, siren tones, airhorn and ONX lightbars.

Part of [AI Core](https://aicore8.com): a TypeScript FiveM framework where every script is configured in one in-game admin panel, and ESX, QBCore and Qbox scripts run unchanged.

## Install

The [AI Core txAdmin recipe](https://github.com/aicore8/aicore-server) installs it with everything it needs. By hand: unzip `ai-sirens.zip` from the [latest release](https://github.com/aicore8/ai-sirens/releases/latest) into `resources/[ai]/` and add `ensure ai-sirens` to `server.cfg` after `ensure ai-core`. It needs `ai-core`. The zip is built and ready, so no build tools are needed to run it; its source builds with `bun install && bun run build` in the folder. `ai-sirens-runtime.zip` holds only the files the server runs, without the source.

Settings live in the in-game admin panel (`/aiadmin`), not in config files.

## Documentation

[aicore8.com/docs](https://aicore8.com/docs)

## Credits

AI Core learned from and builds on the open-source FiveM community (ESX, QBCore, Qbox, Overextended and many script authors): see [CREDITS.md](https://github.com/aicore8/aicore-server/blob/main/CREDITS.md).

## License

GPL-3.0-only.
