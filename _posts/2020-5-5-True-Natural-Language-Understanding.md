
Natural language understanding is one of the most difficult topics to achieve by AI. Another difficulty is that there is no widely adopted agreement of what it means to understand a language. While some scholars from neuroscience claim that true understanding is exclusively human prerogative, drawing Searle’s Chinese room as an argument, guys from computer science community tend to say that computers understand language too, in it’s own way.

People from the machine learning industry offer a variety of tests in a data science fashion that measure the computer’s “understanding” on tasks like question answering, textual entailment, relation extraction etc. We all know that models solving these tasks explore statistical patterns pertinent to language that allow them to perform well without any real understanding or reasoning.

Here I propose a test that requires real, human-kind understanding. The task for an NLP system is to participate in a simple dialogue between the tester (T) and the NLP system (N). Each dialogue of the kind is pretty simple for humans and impossible for current NLP approaches, unless being explicitly programmed for the task. The test can be easily automated as it does not require open-ended answers from the tested system.

The following are 10 sample dialogue scenarios for the test:

Only-playing-with-words tasks

#1

T. Hey, let’s play a game. I will write two arbitrary words and you will send them back in reverse order. Like that: “hero depending” and you write “depending hero”. You get the rules?

N. Yes

T. Fashion industry

N. Industry fashion

T. Replay derghy

N. Derghy replay

#2

T. I will write three arbitrary words and you are to switch the two last words. Like this “George forgot to” — “George to forgot”. You get the rules?

N. Yes

T. Неre we go

N. Here go we

#3

T. I will write a sentence consisting of several words. Your task is to tell me the first letters of each word. Like this “five dollars in my pocket” — “f, d, I, m, p”. Did you understand the rules?

N. Yes

T. To be or not to be

N. T, b, o, n, t, b

#4

T. I will write a sentence consisting of several words. You should enumerate letters, one letter from each word: if a word has more than three letters, take the last letter, otherwise take the first one. Like this: “birds can fly really high” — “s, c, f, y, h”. You get the rules?

N. Yes

T. The pen is mightier than the sword

N. T, p, I, r, n, t, d

#5

T. I will write several words. Your task is to move the longest word from its place to the end of the sentence. Like this: “the tree has no leaves on it” — “the tree has no on it leaves”. Do you understand what is required?

N. What if there are two or more longest words?

T. Then take and move any of them.

N. Got it

T. Tell me the truth, dear

N. Tell me the, dear truth

Tasks requiring some world knowledge

#6

T. I will write a sentence which contains a word denoting a color. Your task is to replace this word with any other word that starts with the same letter. Like this “it’s a black suit” — “it’s a bad suit”. You understand the task?

N. Yes

T. I usually drink red coffee

N. I usually drink renovated coffee

#7

T. I will write a sentence containing a verb in the present simple. Convert it to a past simple form. Like this: “I go to school” — “I went to school”. You get the idea?

N. Yes

T. I eat apples

N. I ate apples

T. Mahara bloody dangerous

N. There is no verb here

#8

T. I will write a sentence containing a word denoting an animal. You should add an arbitrary adjective before that word. Like this: “I like pigs” — “ I like fantastic pigs”. You understand the task?

N. Yes

T. Who teaches the bird to fly?

N. Who teaches the wet bird to fly?

#9

T. I will enumerate objects and their characteristics. Your task is to find an inappropriate combination of an object and its characteristic. Like this: “Wet asphalt, fragile glass, oblique air” — “oblique air”. You understand the task?

N. Yes

T. Screeching tea, hot water, narrow passage

N. Screeching tea

#10

T. I will enumerate objects and their characteristics. I will take two of them and switch their characteristics so that their respective combinations become inappropriate. You are to find these two and restore the appropriate characteristics. Like this: “surprised policeman, unfinished lion, bewildered spectators, hungry story” — “hungry lion, unfinished story”. You understand the task?

N. Yes

T. Delicious sweater, dangerous walk, furious anger, cosy apple

N. Delicious apple, cosy sweater
