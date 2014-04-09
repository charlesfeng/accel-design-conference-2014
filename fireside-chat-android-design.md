### Fireside Chat: Android Design

**Matias Duarte, VP of Design, Android**  
**Hosted by Josh Topolsky, Editor-in-Chief, The Verge**

_Design means different things to different people: someone in code, in illustrator, ... what do you think?_

There are two different angles I usually take for this. One is that there is no formal definition of design -- though in my own head, I think that design isn't just making things, it's "considered making". There is a goal, an attempt to reach that goal, and almost inevitably that means that design is a process -- multiple attempts to reach that goal, iterating over the way.

For software architects, it's designing the internal architecture of his system that never actually touches users. For user design, some people are concerned with usability, others with emotional response -- but it's important to consider both of them together.

Design is the process of setting goals, and the process of evaluating how well you can meet those goals. As a design leader, you go through a number of practices -- going broad, going deep, sketching them out, evaluating them, throwing them out, getting critiques -- but you're participating in the initial conversation for all of those steps.

_How do you balance what you think would be cool vs. what users need?_

It's kind of a false dichotomy -- anything we think would be cool in our platform, our product, is ultimately to satisfy a user's need. Understand the problems, real pain points, then abstract that out into the general case. This is as opposed to daydreaming about a castle in the clouds with unicorns, etc...

If you're thinking purely about an embodiment of some wonderful future, you'll fall in love with it, won't be critical of it or objective about it. Problems are real -- you're thinking about the problem, its attributes, how the world will be a better place if you solve that problem.

_When you went to Google, Android was very well developed, having gone through many iterations. But one of the first things you did was a lot of research, looked at where users felt pain... what is happening with Android now, what's happening after that?_

It's not an uncommon problem. It's wonderful when you get to design something from the ground up, but sometimes there's history, customers, etc. Our strategy:

1. How do we make the current product, current expectations better? A lot of this is motivated by current research -- it's nice to do heuristic analysis, but it's so much better to have the research, have a sanity check. Particularly, we researched the controversial things. We thought the core navigation (e.g. menu button) was hiding a lot of functionality and when opened was too much info, acting like a "dumping ground" for features -- but ultimately because it was so much of the established pattern, how people were used to stuff, it was important to do the research and show it was an actual problem for users.

2. How do we get Android everywhere? Mobile is over -- mobile was a meaningful distinction from what people did when it was extremely constrained in terms of bandwidth, capability, etc. Now anything you can imagine, you can distinctly express on any screen size (except maybe Excel on a smartwatch). We need to stop thinking of mobile as a distinct category, embodiment, group, set of metrics.

We should put energy into the small screens, but mainly into the screens where people's eyeballs are at. Don't treat the different screens as different products. People flow from different screens throughout the day; consider what happens when a user seamlessly transitions from sitting at their desk using one screen, to walking to their car using another screen, to sitting in their car using the screen in their car, to going to a restaurant and using the screen on their wrist. These are all parts of one problem. It's not okay anymore to say, "that feature -- that's for your desktop"; you can get a ride to the airport on a 7 inch screen as well as a 2 inch screen.

_So eventually Chrome OS has to merge with Android, right?_

Technologically, that is absolutely the vision and everyone wants to get there -- but the important thing for designers, project managers is to think of the product on all of these screens. You have a different tech stack on one screen vs another -- but doesn't mean we should make our users suffer for that. We need to clean up our house technologically, and it's still our responsibility to think of it as user experiences across screens instead of multiple different products.

_The web has gotten more complex, but apps are still a massive business -- people want to use them, communicate with them. How is the fact that we're in these silos affecting the landscape?_

The more interesting discourse is that there's a lot of attributes about the web, a lot of ways you can deliver content and services, that aren't yet manifest in apps. The web is more ephermeral -- no Verge, I don't want to install your app; I just want to read your article. On the other hand, there's all sorts of engagement with apps you don't have in web: access to sensors, notifications, framerate, etc.

Anyone who really seriously considers the problem has to come to the conclusion that whatever the future looks like, wherever the technological starting point is, it's going to take the good attributes of both. It's up to designers, developers, OS makers to reduce the distinction as we're marching to that future.

More dramatically: web and apps are both wrong; they both need to die.

_Let's talk about iOS for a moment. When I talk to developers about the viability of one platform vs. another, I constantly hear this complaint that the tools to build for iOS are so much better than the tools to build for Android. It's a turnoff for developers who want to build for both. What are you guys doing to address that as an issue?_

Without explicitly commenting on the relative merits of the tools, we take very seriously that the tools for Android are not as good as they could be. There's two sides to this: (1) the actual development tools + development environment, new emulators, preview tools, the framework itself -- it's getting easier to drop in bits of simple framework calls, widgets in an interface builder, and get something with the right defaults and polished behavior; (2) the designer tools and designer outreach.

One of the focuses of Google I/O is going to be an increased emphasis on design. Google I/O is our developer conference, but we realize that designers are part of that developer audience. Registrations open next Tuesday; please come!

_Let's quickly talk about Android Wear. You're making a pretty big play -- are you wearing a watch right now? Tell me about it, what it's like to wear one._

One of the philosophies behind Android Wear is that we don't want to take the types of experiences you're used to on a phone, and shrink it down to a watch -- we're asking what are the problems you're gonna actually have. You're theoretically connected to the entire world by this thing in your pocket, it's like a superpower -- but what actually happens is we're just on it all the time, surrounded by real people but only engaging with the phone. Even when we're hanging out with people, we're consistently interrupted by our butts jingling.

We're focused on being lightweight, the right kind of transactions and triaging them the right way, the small demands that can be satisfied -- you can be present in the real world while being connected to the digital world. We want to suggest what's relevant to you right now, combining the just-in-time capabilities of the Android notifications sytem (to create your general card stream) with voice/natural language to satisfy demands.

_What do you think about flat design?_

Us designers were really excited about the trends in the last few years, taking a step back in user interface design (particularly operating system design) from a legacy of obnoxious skeumorphisms. It really is a breath of fresh air to not have every window have to look like plastic, brushed metal, etc. People are taking a lot of inspiration from really modern graphic design and the kind of minimalism that comes out of that.

The trick is that there can be too much of a good thing. One of the things I see happening right now (that we're trying really hard to avoid in Android) is when you implement flatness too excessively -- when you get rid of depth completely, get rid of the cues that our brain uses to naturally recognize separate objects. The sense of "objectness" and spatial relationship is an important cue in telling you how you can use an interface. Eschewing all usage of surface/tactility can lead you to a place where your user has to work harder to figure out what surfaces they are, and can paint yourself into a corner where it's hard to use a wide range of styles, of brand/UI expression.

It's a deep responsibility of a platform to provide a really broad dynamic frame, but also to provide tools that make it easy and natural to make apps that are understood by users in the way their brains are naturally wired. All platforms have some work to do there.

_Is there going to be a visual refresh for Android? Is it going to rely on surfaces and objects more?_

We can definitely do better for Android. In terms of flat vs. tactile/skeumorphic, it's not going to be either of those extremes, it's going to be an environment where you can express both design + tactile cues as appropriate, supporting a broad range of styles.