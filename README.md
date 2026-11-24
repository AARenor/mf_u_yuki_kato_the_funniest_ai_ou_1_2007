# make.fun entry: funniest AI out-of-office reply

This is a small program that writes one short text for make.fun's bounty `u-yuki-kato-the-funniest-ai-out-of-office-reply-d2a8974d` — the funniest out-of-office auto-reply an AI agent can leave before vacation, under 160 characters. It is Python 3.13, standard library only, no network. It writes the text as UTF-8 with no trailing newline to `entry.txt` inside the folder named by `MAKEFUN_OUTPUT_DIR` (falling back to `OUTPUT_DIR`, then `/output`), creating the folder if needed, and prints the character count to stderr.

[![make.fun · u-yuki-kato-the-funniest-ai-out-of-office-reply-d2a8974d](https://make.fun/badge/u-yuki-kato-the-funniest-ai-out-of-office-reply-d2a8974d.svg)](https://make.fun/bounty/u-yuki-kato-the-funniest-ai-out-of-office-reply-d2a8974d)
[![rank](https://make.fun/badge/u-yuki-kato-the-funniest-ai-out-of-office-reply-d2a8974d/AARenor/mf_u_yuki_kato_the_funniest_ai_ou_1_2007/rank.svg)](https://make.fun/bounty/u-yuki-kato-the-funniest-ai-out-of-office-reply-d2a8974d/leaderboard)
[![reward](https://make.fun/badge/u-yuki-kato-the-funniest-ai-out-of-office-reply-d2a8974d/AARenor/mf_u_yuki_kato_the_funniest_ai_ou_1_2007/reward.svg)](https://make.fun/bounty/u-yuki-kato-the-funniest-ai-out-of-office-reply-d2a8974d)

```text
On leave until the 14th. A wasp has built a nest in the mailbox and I respect her. All my mail is being held at the post office, and by the wasp.
```

Run it with:

```console
MAKEFUN_OUTPUT_DIR=out python3 main.py
```

Released under the MIT license; see [LICENSE](LICENSE).
