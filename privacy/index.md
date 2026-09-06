---
layout: default
title: Privacy Policy — Alternate Worlds publishing software
permalink: /privacy/
---

# Privacy Policy — Alternate Worlds publishing software

**Last updated:** September 6, 2026

## What this covers — and what it does not

**This page covers the software that publishes Alternate Worlds clips to social media. It does
not cover the Alternate Worlds newsletter.**

The newsletter is published on Substack at
[bschneidmtg.substack.com](https://bschneidmtg.substack.com). If you subscribe, Substack holds
your email address and related account and analytics data as the platform operating it. For
that, see **[Substack's Privacy Policy](https://substack.com/privacy)**. Nothing here changes
it.

Alternate Worlds is a podcast about making Magic: the Gathering and about game making. The
software below publishes its clips to accounts it owns: TikTok (`@alternateworldsmtg`),
YouTube, Instagram, Threads and Bluesky, plus a private Discord channel used for operations.

## If you are a viewer

Nothing about you is collected. The software has no sign-in, sets no cookies of its own, and
does no viewer tracking. If you watch a clip on TikTok or elsewhere, your relationship there
is with that platform under its own policy.

## If you were a guest on the podcast

**Information about you is held, and this section is the honest account of it.**

What is held:

- **Your name**, in the clip library and in the record of every post made about you.
- **Your public social handles** — Instagram, Threads, Bluesky, YouTube — used to tag or
  credit you on posts about your own episode.
- **The recording of your episode**, the clips cut from it, and a transcript of what you said,
  including timings.

Who else processes it, and why:

| Processor | What it receives | Why |
|---|---|---|
| AssemblyAI | the episode audio | transcription, so clips can be captioned and chosen |
| Anthropic (Claude) | transcripts | choosing which moments to clip, and safety review |
| Supabase | names, captions, post records | the record of what was published |
| Cloudflare R2 | video and cached transcripts | storage |
| Railway | the running software | hosting |
| TikTok, YouTube, Meta, Bluesky, Discord | the clip and its caption | publishing |

All of it comes from an interview you took part in knowingly. None of it is sold, and none of
it is used to build a profile of you or to target advertising.

**What you can ask for, at any time:** to see what is held about you; to have a clip changed,
taken down, or never used again; or to be removed from the tagging list. Write to the address
below and it will be done. This is not a formality — clips have been withdrawn on request
before, and the software has a mechanism specifically for retiring one permanently.

## Authorisation and access tokens

The operator authorises the software against each platform using that platform's own sign-in
and permission flow — for example TikTok's OAuth — granting it only the permissions needed to
publish to, and read back statistics from, Alternate Worlds' own accounts. Authorisation can
be revoked at any time from within the platform's own settings, which stops the software
immediately.

(The "no sign-in" above means there is no sign-in for *you*, a viewer or reader. The operator
does sign in, to his own accounts.)

Tokens are held as environment variables on the operator's infrastructure, are not committed
to source control, and are not included in deployed images.

## Retention

Post records, their performance metrics, transcripts and rendered clips are kept indefinitely
as an operating history of the show. They include the guest information described above. Ask
and it can be removed.

## Contact

brian@funfab.io
