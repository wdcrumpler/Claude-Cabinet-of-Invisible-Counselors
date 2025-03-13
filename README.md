# Claude Cabinet of Invisible Counselors

## The Idea
Have Claude (or whichever LLM you prefer) simulate an ongoing cabinet meeting with individuals you admire as a way to provide feedback, inspiration, and accountability. 

The idea for this was sparked when I saw [this QC tweet](https://x.com/QiaochuYuan/status/1854250814841467008) about how helpful people had found it to have conversations with a particular persona he had invented: "[Esmeralda Nightshade, a wise and whip-smart tarot reader](https://x.com/QiaochuYuan/status/1852517808619589776)." After experimenting a bit with QC's Esmeralda persona, I suddenly remembered an article I had read many years back on Art of Manliness about [Napoleon Hill's Cabinet of Invisible Counselors](https://www.artofmanliness.com/character/advice/the-cabinet-of-invisible-counselors/). The short version: OG self-help guru Napoleon Hill used to practice vividly imagining a "cabinet meeting" every night with a group of people he admired in order to receive advice and inspiration. It occurred to me that it would be straightforward to implement this with Claude.

You can use this cabinet framework for many different purposes deepnding on your needs. You may consult with it once a day as a sort of interactive journal. Maybe you only come to it for discussing major problems or decisions you're facing. Or maybe you use it to create an ongoing accountability structure for your daily tasks. Consider this a jumping off point for experimenting with a cabinet of your own.

## This Repository
I've experimented for a few months with this and after a few iterations feel like I have a basic framework that works quite well. At a high level, the cabinet needs three pieces of information to work: 
- Information about the counselors that are being simulated
- Information about you
- Information about what they are supposed to be doing an how they will be interacting with you

This information should be added to a Claude project's knowledge base to serve as the foundation for the cabinet. It can be added as three separate documents or one full document. I've included templates in this repo for the Counselor profiles, Information about the User, and Cabinet Task at the included links. The templates include some general prompts about how to fill in each document, but ultimately the work of writing these background materials will be up to each person. The more detail you give, the better your results. For context, my current prompt doc is 16 pages and about 8,600 words long. But don't get so hung up on writing the perfect backgrounders that you don't start actually using the thing. You can always go back and update the documents, adding more material and tweaking the task parameters. You should see this as an iterative process, so feel free to just boot it up with only a couple of counselors, a page of background about your goals, and a generic framework for how you want to work with it. 

## Who Should My Counselors Be? 

