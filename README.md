## Offline only modified for self-use

1. store online wiki data for offline.
2. add right click map marker to complete it.
3. prevent map right click to support No.2.
4. (TODO) add export/import completed markers.

please global search `MODIFIED` for every change.

# Zelda Dungeon Interactive Maps

Interactive maps for Zelda games, hosted on https://www.zeldadungeon.net

Published maps:

- https://www.zeldadungeon.net/breath-of-the-wild-interactive-map
- https://www.zeldadungeon.net/links-awakening-interactive-map
- https://www.zeldadungeon.net/tears-of-the-kingdom-interactive-map

## Contributing

- `npm install` to install dependencies
- `npm run prepare` to set up git commit hooks
- `npm run dev` to launch the dev server for local testing
- `npm run format` to format code (enforced on commit) (or install Prettier VS Code extension and enable format-on-save)
- `npm run lint` to lint code (enforced on commit) (or install ESLint VS Code extension)

For now, certain ZD staff have push permission for the develop branch, and pushing to develop will trigger deployment to the staging environment `https://www.zeldadungeon.net/maps-beta`. To publish to prod `https://www.zeldadungeon.net/maps`, coordinate with Locke.

For non-staff, feel free to create PRs or Issues, and join our [discord](https://www.discord.io/zelda) to discuss ideas (use the #wiki channel).
