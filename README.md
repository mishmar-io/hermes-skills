# Mishmar skills for Hermes

A tap of [Mishmar](https://mishmar.io)'s agent skill, for Hermes and other self-hosted agents that install skills from a GitHub repository.

Mishmar puts a daily loss limit, a max order size and an approval step on your agent's Hyperliquid or Binance futures trading, and checks every order outside the agent before it is signed.

The skill is [`skills/mishmar/SKILL.md`](skills/mishmar/SKILL.md). It is a copy, byte for byte, of [`skills/mishmar/SKILL.md`](https://github.com/mishmar-io/mishmar/blob/a018cda997ff8307763b5f983ea44a092cb853a0/skills/mishmar/SKILL.md) in the main Mishmar repository at commit `a018cda997ff8307763b5f983ea44a092cb853a0`. Nothing is written here by hand: when the skill changes there, the new copy and its commit are put here.

To check the copy, compare its SHA-256 with the file at that commit: `b67c0f76e08e567851a18e6c6ed0dc147a00048512a6b11e0f4337e1a918a531`.

Install Mishmar only from the [install page](https://docs.mishmar.io/start/install-the-cli/).
