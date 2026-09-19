<!--
  Technified: GitHub organization profile.
  Lives at:  .github/profile/README.md   (images at .github/profile/assets/)

  Images use absolute raw.githubusercontent.com URLs pointing at Technified-xyz/.github.
  Relative image paths do not resolve on the org profile page, but absolute raw URLs do.

  The buttons are images rendered from the design system (8px radius, 40px tall, brand
  blue #275df5, white label). Their width attributes are half-size on purpose: the files
  are 3x, so they stay sharp on retina screens. To change a label, re-render the button.
-->

<div align="center">

<img src="https://raw.githubusercontent.com/Technified-xyz/.github/main/profile/assets/technified-mark.png" width="84" alt="Technified">

# Technified

**Tools for Roblox communities and the people who build them.**

Two products: a platform that keeps a Discord server and a Roblox experience in sync,
and a desktop IDE that gives Roblox development a real editor.

<sub>
<a href="https://technified.xyz">Website</a> ·
<a href="https://docs.technified.xyz">Documentation</a> ·
<a href="https://discord.gg/rPCrq5TwMr">Discord</a> ·
<a href="https://technified.xyz/updates">Updates</a>
</sub>

</div>

---

## Technified: Discord and Roblox, in sync

Running a Discord server and a Roblox experience means running two communities. A member
verified in one is a stranger in the other, a ban on one is an open door on the other, and
the staff team keeps two sets of records.

Technified closes that gap. Members verify once with official Roblox OAuth, roles follow
group ranks, and a moderation action applies on both platforms at the same time, with a
full audit trail. Setup takes about two minutes: invite the bot, connect your group, and
let members verify.

<p>
<a href="https://technified.xyz"><img src="https://raw.githubusercontent.com/Technified-xyz/.github/main/profile/assets/btn-add-to-discord.png" width="139" alt="Add to Discord"></a>
&nbsp;
<a href="https://technified.xyz/features"><picture><source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Technified-xyz/.github/main/profile/assets/btn-features-dark.png"><img src="https://raw.githubusercontent.com/Technified-xyz/.github/main/profile/assets/btn-features-light.png" width="170" alt="Explore all features"></picture></a>
</p>

| Area | What it covers |
| --- | --- |
| **Verification and roles** | Roblox OAuth, role bindings by rank, gamepass, badge or asset, verified and unverified roles, Bloxlink compatibility |
| **Moderation and security** | Unified bans and mutes across both platforms, moderation dashboard with audit logs, AutoMod with custom actions, bulk actions |
| **Staff management** | Activity tracking, quotas with auto-strikes, leave of absence workflow, performance analytics, live sessions, notes and duty status |
| **Forms, tickets and appeals** | Drag-and-drop form builder with conditional logic, up to 15 application forms, per-type appeal forms, ticket panels and transcripts |
| **Roblox Studio** | Drop-in plugin for Adonis and Guardsman, server manager with live players, bidirectional sync of bans, mutes and permissions |
| **Developer surface** | Scoped API keys, webhooks for verification and moderation events, Cloudflare Workers with sub-150ms responses worldwide |

The Studio side is a drop-in module: copy the snippet from the dashboard, paste it into the
Studio command bar, and the plugin handles bans, mutes, permissions and the shield state in
both directions. The full setup is in the
[documentation](https://docs.technified.xyz).

## Technified Code: a real IDE for Roblox, on your desktop

Studio is where the place lives; it is not where a codebase wants to be edited. Technified
Code mirrors your Studio place to disk as it changes, scripts and GUIs included, and gives
it back to you in a real editor. Your edits go straight back into the place.

That mirror is what makes the rest possible: a place becomes a repository, so Git works on
it, and coding agents can read and change it like any other project.

<p>
<a href="https://technified.xyz/code"><img src="https://raw.githubusercontent.com/Technified-xyz/.github/main/profile/assets/btn-download-windows.png" width="195" alt="Download for Windows"></a>
&nbsp;
<a href="https://docs.technified.xyz"><picture><source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Technified-xyz/.github/main/profile/assets/btn-docs-dark.png"><img src="https://raw.githubusercontent.com/Technified-xyz/.github/main/profile/assets/btn-docs-light.png" width="137" alt="Read the docs"></picture></a>
</p>

<sub>Windows 10 and 11, Beta 3. macOS next. Free while it is in the works.</sub>

| Area | What it covers |
| --- | --- |
| **Live mirror** | Your place on disk and in sync both ways, editable with Studio closed |
| **Luau editor** | Tokenization, bracket pairing, symbol outlines and type hints. An editor, not a text box |
| **GUI canvas** | ScreenGuis laid out visually, drag and drop, written back as real instances |
| **Version control** | Git on the place itself, with per-file diffs |
| **Agents** | Claude Code and Codex working on the place, with the Studio output console in the editor |

## Technified Shield: suspended

Shield was a child-safety service: a shared, centrally maintained block list that any
Shield-enabled game could opt into, to keep condo users out.

It has been suspended indefinitely following Roblox's Third-Party App Policy clarification
of 2 June 2026. The flag list is preserved, lookups and protection are offline, and games
that ran the integration should remove it from their Adonis configuration. The appeal
centre stays open for anyone who was flagged: [technified.xyz/appeals](https://technified.xyz/appeals).

## Repositories

Public work lives in this organization: the Roblox plugin, the API clients, and the
examples referenced in the documentation. Issues and pull requests are welcome on any of
them. Start with the repository's own `CONTRIBUTING.md`.

## Security

Found a vulnerability? Do not open a public issue. Report it through
[the support channel](https://discord.gg/rPCrq5TwMr) or the contact address in the
documentation, and give us a way to reach you. The stack runs HttpOnly cookies, AES-256
encryption at rest, CSRF protection and Cloudflare DDoS mitigation; reports that hold up
get credited unless you would rather stay anonymous.

## Links

[Website](https://technified.xyz) · [Technified Code](https://technified.xyz/code) ·
[Documentation](https://docs.technified.xyz) · [Articles](https://technified.xyz/articles) ·
[Updates](https://technified.xyz/updates) · [Appeals](https://technified.xyz/appeals) ·
[Discord](https://discord.gg/rPCrq5TwMr) · [Terms](https://technified.xyz/terms) ·
[Privacy](https://technified.xyz/privacy)

<div align="center">
<sub>© 2026 Technified. Not affiliated with Discord Inc. or Roblox Corporation.</sub>
</div>