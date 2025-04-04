# Claude Cabinet of Invisible Counselors

## The Idea
Have Claude (or whichever LLM you prefer) simulate an ongoing cabinet meeting with individuals you admire as a way to provide feedback, inspiration, and accountability. 

The idea for this was sparked when I saw [this QC tweet](https://x.com/QiaochuYuan/status/1854250814841467008) about how helpful people had found it to have conversations with a particular persona he had invented: "[Esmeralda Nightshade, a wise and whip-smart tarot reader](https://x.com/QiaochuYuan/status/1852517808619589776)." After experimenting a bit with QC's Esmeralda persona, I suddenly remembered an article I had read many years back about [Napoleon Hill's Cabinet of Invisible Counselors](https://www.artofmanliness.com/character/advice/the-cabinet-of-invisible-counselors/). The short version: OG self-help guru Napoleon Hill used to practice vividly imagining a "cabinet meeting" every night with a group of people he admired in order to receive advice and inspiration. It occurred to me that it would be straightforward to implement this with Claude.

You can use this cabinet framework for many different purposes deepnding on your needs. You could use it like Hill did, and just talk with your cabinet every evening as a kind of daily debrief. Or you could only come to it when discussing major problems or decisions. Or you could talk with it as you go through your day reflecting on everything you're doing. I've personally been experimenting with using mine as an accountability tool, informing my cabinet of what I plan to do for the next hour (or half hour, or two hours, or whatever), then getting to work knowing that I have someone I will have to account to. But just consider this a jumping off point for experimenting with a cabinet of your own.

## This Repository
I've experimented for a few months with this and after a handful of iterations feel like I have a basic framework that works quite well. At a high level, the cabinet needs three pieces of information to work: 
- [Information about the counselors that are being simulated
](https://github.com/wdcrumpler/Claude-Cabinet-of-Invisible-Counselors/blob/main/Counselor%20Profiles)
- [Information about you](https://github.com/wdcrumpler/Claude-Cabinet-of-Invisible-Counselors/blob/main/Information_About_the_User.md)
- [Information about what they are supposed to be doing an how they will be interacting with you](https://github.com/wdcrumpler/Claude-Cabinet-of-Invisible-Counselors/blob/main/Cabinet_Task.md)

This information should be added to a Claude project's knowledge base to serve as the foundation for the cabinet. It can be added as three separate documents or one full document. You should also add the prompt in the [Claude Project Instructions](https://github.com/wdcrumpler/Claude-Cabinet-of-Invisible-Counselors/blob/main/Claude_Project_Instructions) file as instructions in the project you spin up for your cabinet. The templates linked above include some general prompts about how to fill in each document, but ultimately the work of writing these background materials will be up to each person. The more detail you give, the better your results. For context, my current prompt doc is 16 pages and about 8,600 words long. But don't get so hung up on writing the perfect backgrounders that you don't start actually using the thing. You can always go back and update the documents, adding more material and tweaking the task parameters. You should see this as an iterative process, so feel free to just boot it up with only a couple of counselors, a page of background about your goals, and a generic framework for how you want to work with it. 

## Say Hi
If you have any feedback or just want to say hi, I lurk on Twitter at [@AboutRadishes](https://x.com/AboutRadishes).
