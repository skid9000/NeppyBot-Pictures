# NeppyBot Picture Repo

## What is NeppyBot?

NeppyBot is a closed source (for now) python 3 bot posting cute Neptunia pics every 20 minutes on Twitter, the Fediverse and Telegram.

- Twitter : [@NeppyBot](https://twitter.com/NeppyBot)

- Fediverse : [@NeppyBot@pl.smuglo.li](https://pl.smuglo.li/users/NeppyBot)

- Telegram : [t.me/neppygram](https://t.me/neppygram)

## What is the purpose of this repo?

I will resume that in 3 points:

- Let people add pictures by letting a PR in this repo.

- Sorting properly all pictures (cauz' you know, 1k+ pictures can be kind of a mess to deal with)

- Have the original source of all pics with CREDITS.md

## Why are you using git for this?

It's more simple for me to just merge PR than adding manually pictures to the bot.

If i have some time, there will be a dedicated website to be more user friendly (but still use git).

## That's cool! How can i submit a picture?

For now, you just have to do a PR, BUT :

Before doing a pull request, check if your picture is already in the repo.
Since i sorted out all pics, it should take 1-2 minutes to check that.

If your picture is not in the repo, you can start making a pull request.
You have to sort your picture in the correct folder and rename it to match the pattern.

If your PR is merged, the picture will be in the bot when it will renew the local pics folder on the server. (so every 4-5 days, depend of how many pictures are in the repo)

## Do you plan to mention original artists at some point?

Yes! A CREDITS.md will be in each folder of this repo, so we can put the artist name/pseudo and the sauce.

## What the Nep? Some files are not renamed correctly!

Normally, it shouldn't happen but if i missed some files, feel free to open a issue or a PR.

## WHY NEPPYBOT ISN'T OPEN SOURCE?

Short Answer:

Because i'm lazy af.

Long Answer:

Actually my code works only on my Python environement, if i wanted to make it public so everyone can re-use it, i need to provide crappy patchs for some pip packages and actually, i don't have time for that.
Also my code is pure torture to read, i don't want anybody to suffer by reading it lmao.