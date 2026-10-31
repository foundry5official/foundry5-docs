# Signs Your Dating App Has a Trust Problem, Not a Matching Problem

A set of questions to help you work out whether people are leaving because the matches are wrong or because they don't trust what they're looking at.

![Signs Your Dating App Has a Trust Problem, Not a Matching Problem](https://images.unsplash.com/photo-1592890288564-76628a30a657?ixid=M3wxMDkwNDQyfDB8MXxzZWFyY2h8MXx8cGVyc29uJTIwdXNpbmclMjBwaG9uZSUyMGFsb25lfGVufDF8MHx8fDE3OTM0MzgzMTJ8MA&ixlib=rb-4.1.0&w=1200&h=630&fit=crop&crop=entropy&q=80&fm=jpg)

A dating app can have a technically solid matching engine and still lose users. The reason is often upstream of matching entirely: people don't trust what they see, so the algorithm has nothing good to work with.

## Signs the problem sits in authenticity, not compatibility

- Profiles feel interchangeable. If you stripped the photos and names, you'd struggle to tell one from another. That's a content problem, and no ranking tweak fixes it.
- Users describe the app as "exhausting" rather than "disappointing." Exhaustion points to volume without signal; disappointment points to bad matches. They call for different work.
- Photos and text don't line up. When someone meets a match and the person is nothing like the profile, the damage isn't just to that pair. It spreads through screenshots and word of mouth.
- The report queue is busy but the ban rate is low. That gap usually means moderation is reacting to volume rather than catching bad actors early.
- People ask for verification features before they ask for better matches. That's a strong hint about what's actually bothering them.

## Questions worth asking about safety and consent

- Can a user be contacted by someone they never accepted? If yes, the first message a new user receives may be from a stranger with an agenda, and that shapes their whole impression.
- Is there a moment where both people have to actively agree before a conversation opens? Mutual acceptance changes the tone of everything that follows, because neither side is reacting to an ambush.
- Does the app give people a way to present themselves that's harder to fake than a few photos and a bio? Video, voice, or structured prompts all raise the cost of misrepresentation, though each brings its own tradeoffs in friction and moderation load.
- When someone reports a profile, what actually happens next, and how quickly? Users forgive a lot if they believe the report goes somewhere.
- Are safety features explained before they're needed, or discovered after something goes wrong?

## Questions about whether your AI is earning its place

- Does the AI help people express who they are, or does it just sort them? A model that turns a short interview into a profile someone is happy to stand behind does real work. A model that silently ranks faces is doing something users can't see and won't thank you for.
- Would users be comfortable if you described exactly what the model does with their data? If not, that discomfort is a design signal, not a communications problem.
- Is match quality being measured by anything other than engagement? Time in app can rise while satisfaction falls, and the two look identical on a dashboard.
- Does the system improve as real users arrive, or is it frozen at launch? Matching quality is not a one-time build; it needs room to be tuned after you see how people actually behave.
- Can you explain a single match to a curious user in plain language? If not, you probably don't understand your own ranking well enough to defend it.

If several of these landed uncomfortably, the good news is that the fixes tend to be product decisions rather than research breakthroughs. The harder part is sequencing them so trust work and matching work reinforce each other instead of competing for the same sprint.

The full write-up on [how Foundry 5 approached the Chance AI dating app](https://foundry-5.com/portfolio/chance-ai) covers the parts this piece deliberately left out: the AI interview and video profile flow, the consent-based match and chat design, the privacy-preserving pipeline behind the matching, and how the build was sequenced from discovery to launch.
