# BroadcastChannel

**Turn your Telegram Channel into a MicroBlog.**

---

English | [简体中文](./README.zh-cn.md)

## ✨ Features

- **Turn your Telegram Channel into a MicroBlog**
- **SEO friendly**
- **0 JS on the browser side**
- **RSS and RSS JSON**

## 🪧 Demo

### Real users

- [面条实验室](https://memo.miantiao.me/)
- [Find Blog👁发现博客](https://broadcastchannel.pages.dev/)
- [Memos 广场 🎪](https://now.memobbs.app/)
- [APPDO 数字生活指南](https://mini.appdo.xyz/)
- [85.60×53.98卡粉订阅/提醒](https://tg.docofcard.com/)
- [新闻在花频道](https://tg.istore.app/)
- [Charles Chin's Whisper](https://memo.eallion.com/)
- [PlayStation 新闻转发](https://playstationnews.pages.dev)
- [Yu's Life](https://daily.pseudoyu.com/)
- [Leslie 和朋友们](https://tg.imlg.co/)
- [OKHK 分享](https://tg.okhk.net/)
- [gledos 的微型博客](https://microblogging.gledos.science)
- [Steve Studio](https://tgc.surgeee.me/)
- [LiFePO4:沙雕吐槽](https://lifepo4.top)
- [Hotspot Hourly](https://hourly.top/)

### Platform

1. [Cloudflare](https://broadcast-channel.pages.dev/)
2. [Netlify](https://broadcast-channel.netlify.app/)
3. [Vercel](https://broadcast-channel.vercel.app/)

BroadcastChannel supports deployment on serverless platforms like Cloudflare, Netlify, Vercel that support Node.js SSR, or on a VPS.
For detailed tutorials, see [Deploy your Astro site](https://docs.astro.build/en/guides/deploy/).

## 🧱 Tech Stack

- Framework: [Astro](https://astro.build/)
- CMS: [Telegram Channels](https://telegram.org/tour/channels)
- Template: [Sepia](https://github.com/Planetable/SiteTemplateSepia)

## 🏗️ Deployment

1. [Fork](https://github.com/ccbikai/BroadcastChannel/fork) this project to your GitHub
2. Create a project on Cloudflare/Netlify/Vercel
3. Select the `BroadcastChannel` project and the `Astro` framework
4. Configure the environment variable `CHANNEL` with your channel name. This is the minimal configuration, for more configurations see the options below
5. Save and deploy
6. Bind a domain (optional).
7. Update code, refer to the official GitHub documentation [Syncing a fork branch from the web UI](https://docs.github.com/pull-requests/collaborating-with-pull-requests/working-with-forks/syncing-a-fork#syncing-a-fork-branch-from-the-web-ui).

## ⚒️ Configuration

```env
## Telegram channel name, required.
CHANNEL=miantiao_me

## Language and timezone settings, language options see [dayjs](https://github.com/iamkun/dayjs/tree/dev/src/locale)
LOCALE=en
TIMEZONE=America/New_York

## Social media usernames
TELEGRAM=ccbikai
TWITTER=ccbikai
GITHUB=ccbikai
MASTODON=mastodon.social/@Mastodon
BLUESKY=bsky.app

## The following two social media need to be URLs
DISCORD=https://DISCORD.com
PODCAST=https://PODCAST.com

## Header and footer code injection, supports HTML
FOOTER_INJECT=FOOTER_INJECT
HEADER_INJECT=HEADER_INJECT

## SEO configuration options, can prevent search engines from indexing content
NO_FOLLOW=false
NO_INDEX=false

## Sentry configuration options, collect server-side errors
SENTRY_AUTH_TOKEN=SENTRY_AUTH_TOKEN
SENTRY_DSN=SENTRY_DSN
SENTRY_PROJECT=SENTRY_PROJECT

## Telegram host name and static resource proxy, not recommended to modify
HOST=telegram.dog
STATIC_PROXY=
```

## ☕ Sponsor

1. [Follow me on Telegram](https://t.me/miantiao_me)
2. [Follow me on 𝕏](https://x.com/0xKaiBi)
3. [Sponsor me on GitHub](https://github.com/sponsors/ccbikai)
