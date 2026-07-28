Comparison table-

| Software           | Audicity (with Claude community built plug in)                                           | Adobe (creative cloud + claude connector)                                        | Descript                                                                                                                      |
| ------------------ | ---------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------- |
| Price              | FREE                                                                                     | $23/month NO FREE                                                                | Available for free, but free version is limited to 1 media hour per month, 100 AI credits, etc (can cost up to $50 per month) |
| Claude Integration | Community built connector, we would self host it                                         | Official Anthropic connector, lots of additional tools (Premiere, Audition, etc) | Official Anthropic connector                                                                                                  |
| Setup              | High, have to enable scripting and run MCP ourselves                                     | Medium, connect Adobe account, learn which app tier Claude could help with       | Lowest, built for this workflow                                                                                               |
| Editing power      | Great (manual multi-track editing), connector can help out as long as script is specific | Pro grade                                                                        | Text based editing (edit audio by editing a transcript), filler word removal, multi track                                     |
| Best for           | Free, DIY, control over every step                                                       | Teams with pro tools and has video capabilities                                  | Least setup friction                                                                                                          |

I'm leaning towards Audacity. The other options are pricey, and just require less effort than 
Audacity (https://www.audacityteam.org)(why the investment is higher)
	- No AI transcription or text-based editing (we can't "delete this sentence" and have it cut the audio- we're working with waveforms directly)
	- No automatic filler-word removal, no AI noise cleanup unlike the newer tools
	- The interface looks a bit dated and can feel less guided for a total beginner at first, though it's not hard once you get the hang of it
I'm willing to learn how to use Audacity, and there is a community plug in for Claude, which I can also learn how to use. Audacity is open source, free forever, no watermarks, which is perfect for us since we are just starting out. We could always switch to Descript (which I like next), once we are more established so that I'm not spending too much time just focusing on editing. 

Claude's opinion- My suggestion: use Audacity to actually learn the craft — trimming, EQ, noise reduction — and optionally layer in the community MCP connector later once you're comfortable with the basics, so you understand what Claude's automating rather than treating it as a black box from day one. 

What we can do with connector for Audacity?
- Noise reduction, high-pass filtering (cutting low rumble/room noise), click/pop removal, compression, loudness normalization
- Pre-built pipelines like "clean up this podcast recording" that chain several of those steps together automatically (e.g., HPF → noise reduction → compression → loudness check)
- Import/export in different formats (WAV, MP3, FLAC, etc.)
- Cutting, trimming, applying effects to specific selections
- Applying things like reverb, EQ adjustments
- Transcribing audio and adding labels at points in the timeline (e.g., marking sentence boundaries), which is handy for figuring out where to cut
-CAVEAT-
- Since this is unofficial/community-built, it requires you to set up Audacity's scripting mode yourself (enabling `mod-script-pipe` in preferences) and it may be less polished or reliable than an official connector
- If your goal is to genuinely learn the craft, I'd actually hold off on using this heavily at first — do your early episodes manually in Audacity so the fundamentals (why noise reduction works the way it does, what compression is actually doing) stick, then bring in the connector later to speed up repetitive cleanup once you already understand it

WILL TAKE TIME TO LEARN. There is Audacity's manual, plenty of YouTube videos, and a forum if I need help. I'll start with interface basics