# Expo Best Practices

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Skills](https://img.shields.io/badge/skills.sh-expo--best--practices-blue)](https://skills.sh/ofershap/expo-best-practices)

Expo and React Native done right. Expo Router file-based navigation, EAS Build, `expo-image`,
`expo-secure-store`, config plugins, platform-specific code, and TypeScript navigation params.

> AI coding assistants set up React Navigation manually, suggest deprecated `expo build`, store
> tokens in AsyncStorage, and use the built-in Image component. This plugin keeps your agent on the
> current Expo SDK patterns.

## Install

### Cursor / Claude Code / Windsurf

```bash
npx skills add ofershap/expo-best-practices
```

Or copy `skills/` into your `.cursor/skills/` or `.claude/skills/` directory.

## What's Included

| Type    | Name                  | Description                                                               |
| ------- | --------------------- | ------------------------------------------------------------------------- |
| Skill   | `expo-best-practices` | 12 rules for Expo Router, EAS Build, expo-image, config plugins, and more |
| Rule    | `best-practices`      | Always-on behavioral rule that enforces current Expo patterns             |
| Command | `/audit`              | Scan your codebase for Expo / React Native anti-patterns                  |

## What Agents Get Wrong

| What the agent writes                  | What Expo best practice is             |
| -------------------------------------- | -------------------------------------- |
| Manual React Navigation setup          | Expo Router file-based routing         |
| `expo build:ios`                       | EAS Build (`eas build`)                |
| `AsyncStorage` for tokens              | `expo-secure-store` for sensitive data |
| React Native `<Image>`                 | `expo-image` with caching and blurhash |
| Editing `ios/` and `android/` directly | Expo config plugins                    |
| `expo-av` for video/audio              | `expo-video` and `expo-audio`          |
| Hardcoded `app.json`                   | `app.config.ts` with dynamic config    |

## Related Plugins

- [tailwind-best-practices](https://github.com/ofershap/tailwind-best-practices) - Tailwind CSS v4
  patterns (works with NativeWind)
- [typescript-best-practices](https://github.com/ofershap/typescript-best-practices) - TypeScript
  5.x strict patterns

## Author

[![Made by ofershap](https://gitshow.dev/api/card/ofershap)](https://gitshow.dev/ofershap)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/ofershap)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-181717?style=flat&logo=github&logoColor=white)](https://github.com/ofershap)

## License

MIT
