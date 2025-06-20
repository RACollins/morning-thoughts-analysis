Okay, here is one thought—number five, second week.

I wanted to talk about the day with a little bit of structure. So what I'm actually trying to do here is a little bit like OpenAugI. It's an open-source project by Bits of Cress. It's a building—I haven't learned much new from the YouTube channel lately—but basically, what he's trying to do is add an AI agent, a layer, to his Obsidian vault. 

I've seen some demonstrations. Some of the core functionality he's proposing is the ability for an LLM to consolidate notes, to be able to merge similar notes together into one, create clusters of similar notes, get topics, and do some topic modeling. It's kind of what I've been thinking about as well. It's an interesting framework, but its only purpose is to use Obsidian.

I like Obsidian. I like its visual style. I think it looks very nice. I also like the graph view of notes. The problem I have with Obsidian is that it's not very user-friendly, particularly for beginners. It has a very steep learning curve. I get the idea that it's meant to be very basic when you first open the app. You can really just make a note, and that's it. You're supposed to build complexity on top of that using plugins, or by creating your own plugin if you can.

However, I find the time spent constructing a perfect note-taking system takes away from the supposed benefits of Obsidian, which is that it should be self-organising. But yeah, I spend more time organising the house than taking the notes. So I guess I'd like to address that by purely allowing users to take notes—through text or through voice. I think voice is a bit easier—and then just letting the system organise itself. 

Have a very limited set of organisational tools, maybe folders, but ultimately allow the AI to organise the notes for you. I'm not sure if this will be a winner, but it's certainly something I would like to see. I guess I could do it with Obsidian, and I could find the plugins necessary, I could find all of these extra features, but I'm almost sure that it won't be exactly what I want. 

Furthermore, I'd have to change settings and play around with different menus and things like that. You know, it's just a bit of a pain. I just want to take notes and allow the system to self-organise.

Now, the really key feature of my system—the one that I'm proposing—is that after you've taken notes, after they have been organised manually or through AI, there should be some sort of generation tool based on the notes. 

Let me give you an example. Let's say I have written or dictated notes about my career—just very scrappy notes, unorganised, unstructured, a stream of thoughts. Something along the lines of:

"I worked at such-and-such company for six years. I enjoyed my time there. I enjoyed the freedom. I worked well with my colleagues. I worked on some interesting projects, one involving clustering of weather data. That was really fun. I'd like to do that again, if possible. My colleagues were good. We had a good relationship. We understood each other well. I didn't go to the office very much. I'd like to go to the office a bit more, to be honest."

Okay, something like that. Let's say that is one note. You see it's very unstructured, very unorganised, just a stream of thoughts. Now, let's say we have not just those notes, but among those notes and among all the other notes I have taken on very separate topics, what my system should do is: if you were to ask the AI model, "Okay, I want you to write a CV for me," it will identify those notes that I've taken about my career and then use them to produce a CV for me.

I shouldn't need to tell the system which notes to use as context. It should be able to understand which notes are relevant to the task at hand. This, I think, is very powerful because, as we know, large language models need context in order to perform certain tasks.

If you have a naked LLM and you ask it something personal like "When's my birthday?"—the LLM doesn't have a clue who you are. Even if you give it your name, unless you're famous, it's not going to know anything about you. There's no information about you in its training data. So how on earth is it going to answer that question?

The way we get around this is by providing context to the LLM, typically through a RAG-type system—retrieval-augmented generation. There are some very sophisticated RAG techniques like GraphRAG, all sorts of different databases. And this is how I propose generated content might be made—to use a type of access method to then inject the query with the relevant context.

It doesn't need to be a CV. It could be, I don't know, for example: let's say I want to learn Thai—the language—and I have some musings in the form of audio notes. I've transcribed them, or I've written notes about my strengths and weaknesses, my motivations, things like that. They're all embedded in the huge database of notes that I have taken over the years.

Let's say I asked the AI, "Please create me a syllabus to learn Thai in six months." It should be able to pick up all of those notes and then generate a syllabus based on my strengths and weaknesses and motivations. That's the idea anyway.

So this is the value-added part of my personal system. I don't think it's unique. I think there are rivals—other similar systems or applications out there. Notably, note-taking apps that then book your next meeting for you. You've just had a meeting, you take a note, and now you want to book the next meeting based on the context of the meeting you just had.

So there are integrated systems like that. I like the idea of having a meeting and then generating some sort of business document from that meeting. It could be just basic minutes. I like the idea of writing up a full personalised proposal based on that meeting and then having it emailed directly to the client or the person that you've just spoken to.

I'm sure these systems exist already, but it's just something that I thought would be quite interesting.

Anyway, I'll, of course, continue recording my thoughts on this topic and many other topics and then do some analysis on it. I'm still creating a solution and, at the moment, looking for a problem—working at things completely the opposite way. But within creating a solution, there are many sub-problems that force you to look backwards and force you to look at the underlying technology and learn something about that before you can apply it.

So anywhere along the product development pipeline, I'll need to look backwards. Who knows? Maybe I'll find that problem.

I think the system that I'm proposing is quite broad in the sense that humans generate content, organise it, and generate from it. That workflow is quite broad and universal. So I don't think I'll have a difficult time finding a problem—just whether it's a big enough problem that people are willing to pay for a solution. That's the question.

Anyway, one last thing I'd like to talk about is just how spooky and scary the pace of technological change is. Touching a little bit on what I spoke about in my last note, that's the idea that you could download someone's personality as a set of weights and biases of a large language model. 

It sounds very science fiction—having an AI model that speaks exactly like you. You can clone someone's voice, add that as an extra layer. Even someone's likeness—you can have an avatar speak in your likeness.

Just reflecting on how strange that sounds and how creepy it is. But also, I'm reminded that when painting became lifelike, when photorealistic painting started to become popular, people must have been freaked out by the fact that you could see an almost perfect replica of someone on paper. I'm sure some people must have thought this is science fiction—this person is real—but yet it's just a representation.

I'm sure when voice recordings started to become popular, people were freaked out by the fact that someone's voice was coming from the machine, perfectly replicated. Some people probably thought that they were inside the machine. Photographs must have had a similar effect—to be able to see someone's perfect replication as an image must have been very scary. But people became used to it very quickly.

Now we look at photos and we think, "Well, it's just a photo. It's not real." It's not a real person. It's just a voice recording. It's just a video. And soon, we will start thinking, "Well, it's just an AI model. It's not a real person."

Yes, it has all of the idiosyncrasies and slight voice inflections, small habits of this person, but ultimately, it is not that person. And in a deeper philosophical sense, are we not just a bunch of atoms knocking around—just as an LLM, an AI model, is just a bunch of ones and zeros?

What really separates us from the machines, anyway?

I think I'll finish there today.
