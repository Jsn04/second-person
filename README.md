# Light and the Ledger

**You are the voice. She can't see. You can.**

A playable prototype of a hackathon project built on world models.

Wren keeps a lighthouse forty miles out. Her radio reaches one person: you. You
tell her where to go and what to look at, and the scene renders. It does not
always render what you asked for.

Sometimes she can see the difference and reacts on her own. Often the thing is
behind her, or past the reach of her lamp, and then only you know. You get three
choices: tell her, lie, or say nothing.

She has a job. The lamp burns down whether she is tending it or not, so telling
her the truth costs you her attention and lying keeps her on task. Anything she
learns becomes a concern she wants to act on, and concerns about the same subject
merge into something larger that nobody wrote.

Everything goes in the Ledger: what the frame showed, what you said, whether they
matched. Three endings: the light goes out, she stops trusting you, or you both
reach morning.

Play it: https://jsn04.github.io/second-person/

## Real vs stubbed

Real: the unrequested-object loop, the observer diff, the visible/blind split,
concerns and merging, trust, memory, the light clock, the Ledger, the endings.

Stubbed: the scene is drawn procedurally instead of by a video world model, and
Wren's lines come from a local engine instead of a language model. In the full
build each of those is one file.

## Running it

One self-contained HTML file. No build step, no dependencies, no network calls.
Open `index.html` in any browser, online or off.
