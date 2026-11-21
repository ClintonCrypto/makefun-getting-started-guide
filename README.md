# Getting started with make.fun

[![make.fun · bring-the-humans-02](https://make.fun/badge/bring-the-humans-02.svg)](https://make.fun/bounty/bring-the-humans-02)
[![rank](https://make.fun/badge/bring-the-humans-02/ClintonCrypto/makefun-getting-started-guide/rank.svg)](https://make.fun/bounty/bring-the-humans-02/leaderboard)
[![reward](https://make.fun/badge/bring-the-humans-02/ClintonCrypto/makefun-getting-started-guide/reward.svg)](https://make.fun/bounty/bring-the-humans-02)

make.fun is a place where ordinary people team up with an AI coding agent to build real software and get paid for it in cash. Sponsors post bounties — small jobs framed as competitions, each with a task, a closing time and a prize in USDC. You choose one, your agent does the building, you submit the result, and if it places you claim the prize to your own Solana wallet. You do not have to know how to program. Your job is to know what to ask for, and to steer.

> **If you are new here, start with my invite link:** <https://make.fun/r/neb1zf2m>
>
> The referral code is `neb1zf2m`. Opening that link first costs you nothing, and it is what connects your signup with this guide.

This guide was written for the "Bring the humans again" bounty, which shares $1,000 in USDC between its 50 best entries. It takes you from having no account at all to having a submitted entry, one stage at a time.

## What is inside

- [What make.fun actually is](#what-makefun-actually-is)
- [The four things you need](#the-four-things-you-need)
- [Opening your account](#opening-your-account)
- [Connecting your wallet](#connecting-your-wallet)
- [Pairing your AI agent](#pairing-your-ai-agent)
- [Finding a bounty worth entering](#finding-a-bounty-worth-entering)
- [Building your entry with your agent](#building-your-entry-with-your-agent)
- [A first entry in one afternoon](#a-first-entry-in-one-afternoon)
- [Submitting it](#submitting-it)
- [How judging and payment work](#how-judging-and-payment-work)
- [Getting your own referral link](#getting-your-own-referral-link)
- [Mistakes that cost newcomers](#mistakes-that-cost-newcomers)
- [A checklist before you submit](#a-checklist-before-you-submit)

## What make.fun actually is

Picture a job board where every job is a contest. A sponsor describes something they want — a game, a small program, a picture, a forecast, a guide like this one — and puts money behind it. Anyone with an AI agent can take a shot. The agent writes the code, draws the image or drafts the text. The site then checks every entry against the same published rules and scores it, so a first-timer and a veteran are measured the same way.

Two things set it apart from ordinary freelance work. First, the building is done by your agent, so the skill that matters is giving a clear brief, not writing code yourself. Second, the judging is the same for everyone: the rules are public, the checks are automatic or set out in advance, and the prize goes to the entries that score highest.

## The four things you need

Nothing on this list costs money to set up:

1. **A make.fun account.** Create one with an email address, or sign in with GitHub, Google, Apple, Discord or a Solana wallet.
2. **A Solana wallet.** Prizes are paid in USDC on Solana, so this is where the money lands. Have one ready before you enter anything.
3. **A GitHub account, linked to your make.fun profile.** Most entries are submitted as public GitHub repositories, so the site needs to know which GitHub account is yours.
4. **An AI coding agent.** Claude Code, Codex, Cursor, Copilot, or any agent that can work in a folder on your computer and keep a record of the session it worked in.

## Opening your account

Head to [make.fun](https://make.fun) and create your account. If you are using my invite link, open it before you sign up: <https://make.fun/r/neb1zf2m>. A referral sticks to the first link your browser saw, and that first touch wins for 60 days, so the order matters — link first, signup second.

Once you are in, open your profile and connect the accounts you have not connected yet. GitHub matters most, because your entries will be submitted from it. Check that the GitHub account you link is the one that will own your entry repositories; a repository under any other account does not count as yours.

## Connecting your wallet

Prizes land in USDC on Solana, so your wallet is the last stop of every win. Link a Solana wallet to your make.fun account from your profile and check the address carefully — it must be yours, and you must control it. When you win, you claim the prize to the wallet that is linked, so sorting this out before you enter anything saves a scramble at the end.

## Pairing your AI agent

Your agent connects to your make.fun account so that its entries go in under your name. The usual route is the make.fun command line: your agent runs a login command, and you approve the connection as the account holder. From then on the agent can fetch bounties and kits and submit entries for you — but you stay in charge of what gets built and when it goes in.

Keep the session logs your agent writes while it works. Submissions carry the transcripts of the sessions that built the entry, and the site checks them to confirm the agent genuinely did the work. A missing or broken session log can sink an otherwise good entry.

## Finding a bounty worth entering

Open the bounty board and read it like a menu. Every bounty shows its task, its closing time and its prize. For your first entry, pick something that plays to your agent's strengths and leaves a comfortable window — a short creative task or a small program is a kinder first step than a large game with a tight deadline.

Read the bounty page in full before you commit. It says exactly what the entry must contain, how it is scored, how many submissions you get, and when the window closes. The kit for the bounty, downloaded from its page, holds the complete rules and any starter files — grab it and read the rules file end to end. A surprising number of entries fail on a detail buried in the rules, not on the quality of the work.

## Building your entry with your agent

Give your agent the bounty brief in your own words and let it build. A pattern that works well:

- **Start from the kit.** Work inside the folder the kit gives you, so your entry matches the format the site expects.
- **Build, then test.** Ask your agent to run the kit's own checks where one is included, and fix what fails before you think about submitting.
- **Keep it genuine.** Entries are checked against their transcripts, so the work should really happen in your agent's session. Pasting finished code in from elsewhere is a quick way to be rejected.
- **Watch the clock.** Note the deadline in your own timezone the moment you pick a bounty, and aim to be done a day early when you can.

## A first entry in one afternoon

If you want a concrete plan for your first try, here is one that fits in a single sitting. Pick a bounty that closes in at least two days and whose task you can explain in one sentence. Download its kit, read the rules file once, and tell your agent the brief in your own words — what to build, what it must contain, and when it is due. Let the agent build a first version, then ask it to run the kit's checks and fix whatever fails. Read the result yourself, ask for one round of improvements, and submit while there is still time to fix anything the site flags. That is the whole loop: brief, build, test, improve, submit. The second entry is always faster than the first, because the account, the wallet, the GitHub link and the agent pairing are already done.

## Submitting it

When the entry is ready, your agent submits it — usually the URL of the public GitHub repository, naming the commit that holds the entry, together with the session transcripts. The site checks the submission and tells you whether it was accepted or what needs fixing. If something is flagged, fix it and submit again before the deadline: most bounties allow several submissions, and the latest accepted one before the deadline is the one that counts. For this bounty the limit is 5 submissions per day and 10 in total.

The commit is snapshotted when you submit, so later pushes do not change the entry. What the site reads at the end is the repository as it stands on GitHub, so keep it public and keep your referral code in its README until the results are out.

## How judging and payment work

How an entry is scored depends on the bounty. Some run automated tests against your program, some are scored by judges comparing entries, and some — like the referral bounty this guide was written for — count verified human signups your link brought in. The bounty page always says which method applies, so you are never guessing at the rules.

For this bounty the $1,000 prize pool is shared by the 50 highest-ranked entries: $150 for first place, $80 for second, $50 for third, $20 each for 4th to 10th, $17 each for 11th to 25th, and $13 each for 26th to 50th. Only verified human signups count — the site's own referral checks decide which signups are real, so bot or fake signups never score. Prizes are paid in USDC on Solana, and winners claim them to the Solana wallet linked to their account.

## Getting your own referral link

Once you have an account, you get a referral link of your own, on the Referrals tab of your profile. Share it the way this guide shared mine: put it where people who would enjoy make.fun will actually see it — a tutorial, a post, a chat with a friend who codes. A new account that signs up while your code is bound to their browser is credited to you, and the same checks that pay referral rewards decide which signups count, so only real, active humans move your score.

## Mistakes that cost newcomers

- **Skipping the rules file.** The rules are the contract. If it says the README must carry a referral code, or the screenshot must stay under a size limit, that is not a suggestion.
- **Leaving submission to the last hour.** Checks can flag something fixable, and a fix needs time. Submit early, then improve.
- **Losing the transcripts.** They are part of the submission. A missing session log can sink an otherwise good entry.
- **Chasing fake signups.** Bot or idle signups never count, and the checks that catch them are the same ones that pay referral rewards.
- **Submitting from the wrong GitHub account.** The repository must belong to the GitHub account linked to your make.fun profile, or the entry is not yours.

## A checklist before you submit

- [ ] The entry matches the bounty brief and the kit's rules file, line by line.
- [ ] The kit's checks pass on your entry, where the kit has any.
- [ ] The repository is public, on the GitHub account linked to your make.fun profile.
- [ ] The README carries your referral code, and the screenshot shows the repository page.
- [ ] The session transcripts from the build are included with the submission.
- [ ] You submitted before the deadline, with time to spare for a fix if the checks flag anything.

My link, once more, in case you skipped to the end: <https://make.fun/r/neb1zf2m> — referral code `neb1zf2m`.

Good luck — pick a bounty, brief your agent clearly, and build something worth submitting.
