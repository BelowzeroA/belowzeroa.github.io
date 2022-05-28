### How to build AGI?

Take an architecture that predicts the next element of the sequence, add multimodality, train on hundreds diverse tasks and get what some journalists claim as "proto-AGI that just needs to be scaled".

Nando de Freitas wrote on Twitter

It’s all about scale now! The Game is Over! It’s about making these models bigger, safer, compute efficient, faster at sampling, smarter memory, more modalities, INNOVATIVE DATA, on/offline, … 1/N.

It collected over 200 retweets.

Is it fair to say “It’s all about scale now?” The article Nando was replying to has made it clear:

The very first problem on the way to solving AGI: building an AI that can learn new things without training.

What does it mean to “learn new things without training”? Even we, humans, the only samples of general intelligence, learn new things.. with training, be it a new game or a new language. I guess the author made a mistake by missing “by engineers”. It’s when we need engineers to infill a new skill into a machine learning model, in contrast to the fact that biological intelligence does the same by itself.

Why is it so crucial for AGI to be autonomous? Imagine we have achieved AGI, implemented as a super-duper program, now tasked to do something useful. In the real-world usage scenario, new tasks are constantly popping up, giving no chance for a team that would hypothetically support that program to catch up with the new requirements.

Take translation, the work, almost automated by deep learning models. Why not replace human translators completely? The thing is, the job of a translator is not only about translation.

While I was learning to fly, I had a chance to translate an operating handbook on Cessna 172, a lightweight plane. From English to Russian. I did a well-known trick — I put the source text into the Google translate and then got it honed to be readable. What was most annoying about automated translation is special aviation terms that the model behind Google translate probably didn’t see much and thus didn’t know how to translate properly.

With a fair portion of imagination, the ideal translation service scenario would look like:

Me: here is the text to translate [some text]

Service: done! [translated text]

Me: well, this is almost fine, but. Elevator is not “лифт”, but “руль высоты” in this context. Rotation speed is not the speed of something rotating, but the speed of takeoff.

Service: sure thing! [translated text 2nd edition]

Me: Wow! Wait, emm, could you convert every mention of pressure in inches of mercury into hPa? The conversion rate is [conversion rate]

Service: the translation is on its way!

Why does a service like this seem impossible while based on deep learning models? Because the things I want the service to be capable of are brand new tasks that the engineers have been unable to foresee. No matter how many tasks the model is trained on, there will always be the millionth + 1 task not provided by the system design. Even worse, the majority of new tasks that happen in real life cannot be defined from a machine learning perspective.

That’s why I’m pessimistic on attempts to reach AGI using good old deep learning approaches.
