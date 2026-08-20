# Second Person

A playable prototype of a hackathon project built on world models.

You are a voice on a radio. Wren keeps a lighthouse and cannot see you. Tell her
where to go and what to look at. A scene generator draws the room, and it
sometimes puts things in it that were never requested. An observer step compares
what was asked for against what was rendered, and hands anything unaccounted for
to Wren as something she has just seen. She trusts her own eyes over you.

Play it: https://jsn04.github.io/second-person/

## What is real and what is stubbed

Real: the anomaly injection, the observer diff, the buffering and pacing, Wren's
memory of what she has seen, the escalation, and the persist/vanish behaviour
when you leave a room and return.

Stubbed: the scene is drawn procedurally instead of by a video world model, and
Wren's lines come from a local engine instead of a language model. In the full
build each of those is a single file.

## Running it

One self-contained HTML file, no build step and no dependencies. Open
`index.html` in any browser, online or off.
