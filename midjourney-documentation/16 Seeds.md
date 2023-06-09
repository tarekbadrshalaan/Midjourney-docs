﻿**Seeds**

**The Midjourney bot uses a seed number to create a field of visual noise, like television static, as a starting point to generate the initial image grids. Seed numbers are generated randomly for each image but can be specified with the --seed or --sameseed parameter. Using the same seed number and prompt will produce similar ending images.**

- --seed accepts whole numbers 0–4294967295.
- --seed values only influence the initial image grid.
- Identical --seed values using [Model Versions](https://docs.midjourney.com/models) 1, 2, 3, test, and testp will produce images with similar composition, color, and details.
- Identical --seed values using [Model Versions](https://docs.midjourney.com/models) 4, 5, and niji will produce nearly identical images.
- Seed numbers are not static and should not be relied upon between sessions.

**Seed Parameter**

If no Seed is specified, Midjourney will use a randomly generated seed number, producing a wide variety of options each time a prompt is used.

**Jobs run three times with random seeds:**

prompt example: /imagine prompt celadon owl pitcher

MJ\_SeedRandom13.png ¬

MJ\_SeedRandom1.png ¬

MJ\_SeedRandom2.png ¬

**Jobs run two times with --seed 123:**

prompt example: /imagine prompt celadon owl pitcher --seed 123

MJ\_Seed-123\_V4\_.png ¬

MJ\_Seed-123\_V4\_.png ¬


**Sameseed Parameter**

--seed values create a single large random noise field applied across all images in the initial grid. When --sameseed is specified, all images in the initial grid use the same starting noise and will produce very similar generated images.

--sameseed accepts whole numbers 0–4294967295.--sameseed is only compatible with [Model Versions](https://docs.midjourney.com/models) 1, 2, 3, test, and testp.

**Early visual noise from --sameseed**

MJ\_Sameseed\_Stop10.png ¬

--sameseed 12345

**Finished Job made with --sameseed**

MJ\_Sameseed.png ¬

--sameseed 12345

**Early visual noise without --sameseed**

MJ\_seed\_Stop10.png ¬

--seed 12345

**Finished Job made without --sameseed**

MJ\_seed.png ¬

--seed 12345

**How to Find a Job's Seed Number**

**Use a Discord Emoji Reaction**

Find the seed number of a Job in discord by reacting with an ✉️ envelope emoji to a Job.

MJ\_JobID\_EmojiReact.gif ¬

**Use The Show Command to Bring Back Old Jobs**

To get the seed number for a past image, [copy the job ID ](https://docs.midjourney.com/docs/show-job)and use the /show <Job ID #> command with that ID to revive the Job. You can then react to the newly regenerated Job with an ✉️ envelope emoji.

**How To Change Seed Numbers**

**Use the --seed or --sameseed Parameter**

Add --seed <value> or --sameseed <value> to the end of your prompt.
