# Expo Best Practices

Expo and React Native done right. Expo Router, EAS Build, native modules, platform-specific
patterns, and navigation your AI agent should follow.

## Install

### Cursor IDE

```
/add-plugin expo-best-practices
```

### Claude Code

```
/plugin install expo-best-practices
```

### Skills only (any agent)

```bash
npx skills add ofershap/expo-best-practices/expo-best-practices
```

Or copy `skills/` into your `.cursor/skills/` or `.claude/skills/` directory.

## What's Included

### Skills

- **expo-best-practices** - Expo and React Native done right. Expo Router, EAS Build, native
  modules, platform-specific patterns, and navigation your AI agent should follow.

### Rules

- **best-practices** - Always-on rules that enforce current Expo / React Native patterns

### Commands

- `/audit` - Scan your codebase for Expo / React Native anti-patterns

## Why This Plugin?

AI agents are trained on data that includes outdated patterns. This plugin ensures your agent uses
current Expo / React Native best practices:

- Default to manual React Navigation setup instead of Expo Router file-based routing
- Suggest deprecated expo build instead of EAS Build
- Use AsyncStorage for auth tokens instead of expo-secure-store
- Use React Native Image instead of expo-image (missing caching and performance)
- Propose manual native file edits instead of Expo config plugins

## License

MIT
