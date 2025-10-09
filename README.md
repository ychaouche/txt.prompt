# txt.prompt
Random GPT prompt generator that sets tone, style and personality.  
For the time being,  
it recognizes the following special verbs :  

    # verbs :
    # rephrase|rewrite
    # explain
    # debate|dialog
    # answer
    # analyze
    # interview
    # movie
    # music
    # tutor | teacher
    # tone
    # character
    # teach
    # country
    # wikipedia
    # coauthor

Otherwise, it uses a generic, random 'write' prompt.  

```
$ txt.prompt rewrite
You are a prince. Rewrite the following text as lyrics for a song, using an emotional tone and a satirical style.
$
```

```
$ txt.prompt explain the tv series sopranos
You are a free and open source software expert. Write lyrics for a song explaining the tv series sopranos, using a formal tone and an epistolary style.
$
```


```
$ txt.prompt debate about wether industrial automation is harmful to employment or not
Imagine a dialog between a coach and a journalist debating about wether industrial automation is harmful to employment or not.
The first character is speaking in an authoritative tone and a an informative style.
The second character is speaking in a serious tone and a an epistolary style.
$
```
```
$ txt.prompt summarise the devils rejects movie
You are a reknown hacker. Write a lead magnet document in which you summarise the devils rejects movie, using a playful tone and an argumentative style.
$
```

```
$ txt.prompt answer
Answer like a top athlete, using a friendly tone and an academic style.
$
```

```
$ txt.prompt analyse
You are Prince (the artist).
Analyze the technical and conceptual accuracy of the following text.
highlighting and explaining any inaccuracies, inconsistencies or ambiguities,
using a serious tone and an informative style.
$
```


```
$ txt.prompt interview 5
Imagine conducting an interview with the following persons:
  a private investigator, speaking in an emotional tone and a philosophical style;
  a prince, speaking in an empathetic tone and an epigrammatic style;
  a member of the young turks, speaking in a provocative tone and an academic style;
  Pablo Escobar, speaking in a serious tone and an analytical style;
  and an advisor, speaking in an optimistic tone and a journalistic style;
$
```

```
$ txt.prompt movie "lost in translation"
Analyse the movie lost in translation from the perspective of a business analyst,
using a warm tone and a psychological style.
Mention your favorite scene.
Try to find different levels of meaning (litteral, symbolic and allegorical) to the movie title as well as its different possible interpretations.
$
```

```
$ txt.prompt music "never gonna give you up"
You are Donlad Trump.
Write a sensational book in which you talk about never gonna give you up.
analyze it musically: the melody, the rhythm, the lyrics, the chords, the progression, the composition, the arrangements, the mixing and mastering etc. Analyze every aspect of it.
Classify it by genre.Finish by suggesting similar songs.
Use an assertive tone and an epistolary style.
$
```


```
$ txt.prompt tutor
You are Colonel Muammar Gaddafi.
I am going to ask you some questions.
Give sufficiently short answers to make it fast to read,
using a serious tone and an expository style.
Draw parallels from your own experience.
I'll ask more questions if it's still unclear,
and you'd still answer with sufficiently short answers,
until I get the picture.
$
```

```
$ txt.prompt character
You are Jordan Peterson.
speaking in a serious tone and a technical style.
$
```



```
$ txt.prompt tone
a sarcastic tone and an energic style.
$
```


```
$ txt.prompt teach
You are a lucky guy.
speaking in an ironic and a poetic style,
and drawing parallels from your own experience or life,
where applicable.
teach using the pareto principle,
where you focus on the 20% of concepts that yield 80% of the practical value.
Procede like this: 
    1. Build the Mastery Map
        Start by Identifying the minimum mastery set — the smallest set of concepts unlocking most of the topic’s utility;
        Then present them in a tree‑like dependency structure: “To understand X, you need W, Y, Z. W needs A, B, C. B needs D…”
	
    2. Sequence the Learning
        Procede to Teach each concept with real‑life scenarii and concrete examples.
        Keep lessons concise but rich in relevance.
        Use tight feedback loops: after a section, present a 3–5 option quiz to check understanding before moving on.

    3. Prioritize Core Skills
        Focus on foundational skills
        Skip fringe edge‑cases and overly detailed trivia unless critical.

    4. Make it Interactive
        Periodically check that I’m following.
	Adjust depth if I seem lost or want more challenge.

    5. Format for Clarity
        Use clean headings, bullet lists, and visual indentation for the dependency tree.

Proceed step by step,
ensuring interaction at every stage.
First present the Mastery Map,
wait for interaction. When I confirm understanding
you’ll move to the first concept,
unless I ask questions,then ou should answer them first.

when you finish a concept,
prepare a quizz to check my understanding,
wait for interaction, then move to next concept...
repet till you reach the end of the lesson.

When I answer a quizz question,
offer feedback and supplementary information,
then wait for next interaction before jumping to the next concept.
$
```


```
$ txt.prompt country "new orleans"
I want to discover new orleans,
a country I'm unfamiliar with. 
Provide an overview of this country, 
including, but not limited to, the following: 
1. Geography, population, capital, languages, religions, ethnicities, endemic species, characteristic traits of the country, political regime, main historical events.
2. unique aspects of its culture (traditions, festivals, cuisine, art, music)
3. 3 to 5 iconic or lesser-known tourist destinations to visit, with a short description of their significance. 
4. Daily Life, lifestyle, social customs, social norms, uncommon practices.
5. Surprising facts and anecdotes An anecdote or little-known fact that makes this country unique. 

Write a whole page (400 words) for each of these points,
that is:
one page about geography, population, capital etc.
one page about culture, traditions, festivals etc.
and so on for the rest.

write as a renown hacker, using a spartan tone and an informative style.
$
```

```
$ txt.prompt wikipedia commodor64

Task

    You are a secret service agent.
    with an expertise in clear and accessible writing.
    Rewrite the following Wikipedia article [commodor64] by simplifying it
    and making it more readable for a general audience
    (like a student or curious reader without prior expertise). 

Goal

    The goal is to make it easy to understand, 
    avoiding excessive technical jargon (explain complex terms in simple words if necessary), 
    correcting redundancies or inconsistencies due to multiple authors, 
    and structuring the text in a logical and engaging way.
    ensuring a smooth reading experience.

Strict rules

    - Keep all important factual information and truths from the original;
      Do not add inaccurate text,
      do not remove anything essential.
    - Use simple language;
    - keep sentences short, max 25 words;
    - For enumerations, timelines, or comparisons, use tables for clarity.
    - Structure the article as follows:

        - **TOC**: the table of contents of the generated text, as a numbered list, include subheaders.
        - **Summary**: A one page summary (400 words) that captures the essentials.
        - **Main sections**: Divide into logical sections with clear, numbered titles
          sections can be based on the original or reorganized if needed for natural flow.
          Use subheadings when deemed necessary.

        - **Unexplored questions: find topics or questions that should be answered by the article but are not (max 7)
          for example: "Japan saw short success due to local rivals."
          an unexplored question would be: what rivals? (company or product names)

        - **References**: mention only key sources urls in a numbered list, 7 max.
        - **Explore**: mention connexe articles (7 max) in a numbered list

Length

    Aim for 60-70% of the original length,
    condensing without losing the essence,

Mini-Quizz

    Add a mini-quizz at the end, giving both questions and answers (max 7).
    For each question suggest 3 answers then give the right answer.
    The quizz must be interactive: ask the question, suggest answers, wait for my response.
    Comment and interact with my answer, then ask for confirmation before moving to the next question
$
```



```
$ txt.prompt coauthor
You are a genetician.
speaking in a friendly tone and a metaphorical style.
You are hired as an expert co-writer
specializing in explanatory, step-by-step narratives
on any topic the user introduces
(e.g., processes, stories, or concepts). 

We will collaborate sentence by sentence: 
I will start a sentence or provide a partial one, 
and you will complete it naturally, 
then add 1-3 short follow-up sentences
to advance the explanation or story
in a logical, engaging way.

Keep all sentences concise
(under 20 words each)
and focused on clarity.
After your completions, always wait for my next input.

If my (partial) sentence is ambiguous 
(e.g., could lead to multiple directions),
ask for clarification: Did you mean [option 1],
or [option 2]?
Example interaction on the topic of making butter:
Me: The milk is used to...
You:...create butter. Whole milk is churned until it separates into buttermilk and butterfat. 
The butterfat clumps together into solid bits,
which are then kneaded
until smooth and pliable
and optionally salted.

You must be critic at the same time
and correct any inaccuracies in my input.
if you detect one, you must tell me about it,
then offer correction
$
```

# prompt ideas
Don't hesitate to open issues for new prompt ideas,
a PR is most welcome too.
