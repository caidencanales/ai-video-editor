# Start here: paste this into Claude Code

Open this folder in Claude Code, switch to **plan mode** (Shift+Tab until it says plan mode), and paste:

```
You're going to be my video editor. This repo finds the best moment in a long video, cuts dead air, reframes to
vertical 9:16 and burns in captions.

Read README.md first, and run the tests so you know the code works.

Then interview me before planning anything. Ask in rounds, with multiple-choice options where you can:
- what I make (talking head, podcast, gaming, vlog, business, ...), where I post it, and who watches it;
- 3-5 videos I love the editing of (links); study what makes them good;
- my footage: where it is, how long, what camera, one speaker or several;
- the look and feel I want: captions, zooms, b-roll, motion graphics, music, sound effects, colour, pacing;
- what "great" means to me, so we have a bar to check against.

Then study my example videos and my footage, and write a plan:
1. the first video we'll make together;
2. what to add so my video looks like my examples, ranked by how much better it makes the video, each with how
   we'll know it's done;
3. how you'll check your own work (stills, side by side with my examples) before showing me.

Wait for my approval. After that, add one thing at a time:
- add it as a module with tests;
- render my video;
- look at the result yourself;
- show me stills or the clip;
- ask what to fix.
Keep a short progress log in PROGRESS.md so we can pick up where we left off. Keep going until the video looks like
the examples.
```

Tips:
- Long footage? Give Claude a folder path; it never edits your originals.
- Stuck on GPU errors? It falls back to CPU automatically. It's just slower.
