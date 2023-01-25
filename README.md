# pu093-errorless-attentionless-ibre

CogSci Proceeding for an errorles and attentionless implementation of the inverse base-rate effect

# Some thoughts from Andy

This was a lot better than I had assumed it would be, given your comments about it being an early draft and asking I focus of structure etc :-) It's actually really well written, well done! I've made some phrasing comments, because I thought in terms of readability it was close enough that it made sense for me to do that. There are however a few substnative issues you need to address - things that an alert reviewer is likely to pick up on and cause trouble about, so there's a need to fix before submission. I think probably you should aim to get me to look at another version before submission - not so much for readability, but for ensuring the substnative content is as good as it can be. We can also talk through the substantive issues when we meet on Monday if that's helpful.

Apologies for dumping my comments on the README of the main branch, but I thought initially I was just gonna make a few top-level comments :-)
## DONE

### High-level comments

1. DONE: Some good handling of the Johansen related work! However 

    - DONE: the second para on p.2 seems superfluous - I think you have said all you need to say in para. 1. You could probably drop para. 2 entrirely?
    - LD: I dropped it. It seems wise not to overcomplicate it. I should probably mention other condition from johansen2007paradoxical.
	
	- DONE: On the Appendix B study... not only are there no procedural details, nor analysies, it's n=16 - which is about half what you'd need for a well-powered study given the typical effect size in IBRE, there's no analysis, the C-R difference on BC is only about two-thirds the size of the difference observed in Kruschke's standard design, and they say "qualitatively comparable" which is normally code for "not significant". Although it might not arrive in time for this submission, you should probably ask Mark whether he still has the raw data. I'm pretty confident the BF would not be decisive.
	
	-DONE:  I'm a bit surprised you do not consider the shared-cue, listed, condition of Experiment 3 of Johansen. As far as I can see, this is another demonstration of IBRE without a guess-and-correct methodology? (Table 6, bottom right, phase 1, PC+PR?)

7. INPROGRESS: OK, I just saw the BF for BC in Experiment 2 is just 4. If you still wanted to expand N on this experiment as discussed earlier, I'd be OK with that. 

4. DONE: At some point, also point out that the IBRE can be made to go away by e.g. summary presentation (Johansen). 

5. DONE: Wasn't some of this data collected as part of an UG project? Use an acknowledgement section to thank them (I guess anonymized in the initial submission). I'm guessing the actual authors are: Dome & Wills, right? 

6. DONE: Before submission, check whether US spelling is expected (e.g. memorise -> memorize). 
LD: There was no information provided.

9. DONE: You also go on to discuss Johansen's weird AB -> com, C -> rare design. I would drop this part of the discussion. As you say earlier, this isn't the IBRE, and it's pretty easy to explain with any old associative network.
    LD: Dropped it.


3. DONE: I can see why you might want to cover Inkster 2022 and Wills 2014. The current presentation needs some tweaking. First, the claim that they are the only two sutdies "direclty looking at error driven processes..." is too broad an bold.
Even the narrower claim that they are the only studies using neuroscience methods is too bold because ... O'Bryan, and also Kruschke's eye-tracking of highlighting, which is pretty close. Dealing with O'Bryan probably comes under the heading of Thought 2. But that still leaves 3 studies. And what these show is that, under the standard guess-and-correct procedure, (1) EEG and eyetracking data implies there is attentional reallocation in the manner supposed by models like EXIT (that's Wills 2014 and Kruschke's paper), and (2) brain areas previously implicated in the calculation of prediction error may be responsible for that (Inkster, 2022). So, there's a reasonable case that attentional reallocation happens in the standard procedure and that it is driven by prediction error. This is of course a different question to whether such processes are _necessary_ for a demonstration of IBRE, which is what your work is investigating. So maybe redraft the final para of the introduction more in this way?

8. DONE: In Discussion, p. 5, "- "Compared to Johansen". I don't think we can say anything about asymmetric representation definitively? For example, we talked about running eye-tracking versions of these two studies. If we found asymetric dwell times in those studies, wouldn't that imply asymmetric representation? For now, we don't know. That whole paragraph probably needs some further thought.
    LD: Maybe I shouldn't go into it, but their reasoning is similar to when parts of the explanations are confused with what they are trying to explain. So my reasoning is as follows: asymmetric cogntive representation is hypothesised to underly the inverse base-rate effect. If we were to observe asymmetric dwell time, that would essentially mean that at least as far as visual attention goes, we have evidence for asymmetric representation as it is conceptualised by some theories. If we want to push it further, we might do multivoxel pattern analysis, and so on and so on. If we don't see the inverse base-rate effect with a non-asymmetric dwell times in the traditional design, than we wouldn't see it. So this was kind of my reasoning here, although handled poorly in the text.


2. DONE: There are other theories of the IBRE e.g. DGCM, ELMO, that don't so explicitly involve error-driven learning. Might you need to say something about them somewhere?
    - **Include in discussion section** dgcm no mechanisms for attention but could accommodate results due to its vagueness?

### p.1 

- DONE: In the first section of the introduction, it might be worth having an in-text design summarey e.g. after the Kruschke 96 ref, something like. "The training can be summarised thus: AB -> common, AC -> rare"


- DONE: In col. 2, first para, perhaps say why an error on AC is likely (generalization from AB via A).?

- DONE: "When the ambiguous BC compound is presented..." - perhaps add "this attentional allocation persists, and thus..."?

- DONE: "Any presumption of a causal relation-ship can inadvertently" -- change 'can' to 'might'?

## p. 2

- DONE: Experiment 1 "will present category labels simultaneously with their respective features" perhaps?

- DONE: Footnote 1, perhaps give the github repo?
    LD: It was a hyperlink, which I can see why might not be obvious :smile:

## p.3

- DONE: When participants were given a choice to move to test, did it say something like, "If you are confident you know what causes the diseases?" or somesuch. Would be worth saying what if any prompt participants were given to decide whether or not they were ready to be tested. 

- DONE: Does the patient has -> Does the patient have

- DONE: "Exclusion" - The bit "we arrived at this threshold..." could be shorter and clearer. I'd just say something like, accuracy of 0.75 is that lowest at which evidence the participant is above chance exceeds a Bayes Factor of 3, using the binomal test in Morey & Rouder. 

- DONE: "In a summary" -> "in summary"

- DONE: "People explicitly followed the base rate" . Add "For this cue,..." and then replace "On the contrary" with. "In contrast..."

- DONE: I think you can and probably should dial down the deference to an experiment Johansen only reported incompletely in an appendix. What you wrtie on p.2 is fine, but on this page where you write that you have a "successful conceptual replication..." I would write something like "Thus, the current study strongly confirms that the IBRE can be observed in an observational procedure"

- DONE: I would drop the sentence "This prediction error also drives the development of an asymmetric cog-
nitive representation." entirely

- DONE: "In the absence of this explicit prediction error..." ... I would say "EXIT-like theories cannot predict the presencce of an IBRE"

- DONE: "One shortcoming of the current design is that participants
can still make predictions" -> "One aspect of the current design is that participants might still experience internally-generated prediction errors.

- DONE: "A simple solution" -> "In experiment 2, we address this by removing any design component..." and "We also use stimuli that reduce the the chance people assume any causal relationship between the features"


## p.4

- DONE: _How_ were X and Y selected in the test phase, by the participant. So, is it like, there are two shapes at the top of the screen - B, C, and then two at the bottom, X, Y, which the bottom set labelled "Press X", "Press Y"?

## p.5

- DONE: "this central assumption was prediction error" ->" This central assumption was that the IBRE is caused by the presence of prediction errors" ?

- DONE: "In our first attempt" -> "in our first experiment" (similarly, second experiment)

- DONE: "...,therefore the condition for prediction error. Regardless,..." -> ". Nevertheless,..." (So drop that final clause). 

- DONE: "can predispose" -> "might predispose"

- DONE: "When participants needed to..." -> "When participants were asked to..."

- DONE: "unable to process" -> "unable to accommodate"

- DONE: Open Science: I guess you'll have to be a bit careful here in the sense of these links should presumably not act to deanonymise the submission?

- DONE: Conclusion. "Whether the IBRE requires error-driven components of the experimental procedure" -> "whether demonstration of the IBRE requires the "guess and correct" components of the standard experiment procedure. You may need to revisit anyway given the various points I've made above.


- DONE: "All current theories of the IBRE rely on the assumption that this irrational rare preference arises as a result of optimising accuracy during the training phase." - Do they? What about DGCM? What about ELMO? (Genuine question. But if they don't clearly rely on this then you of course should not say "all theories". Here and elsewhere, what you _can_ do is perhaps focus on EXIT-like theories being the most popular and successful accounts.


# Some thoughts from Andy on second draft

### General thoughts

- A bit too long, right (over 6 pages)? As far as I recall, the page limit includes the references?

- I would drop the paragraph on p.2 about Johansen Exp. 2 entirely, irrespective of how long the paper is. You just don't need it, and it slows and fogs the narrative.

- I've some questions about the exclusion criterion in Experiment 2. First, it seems to be different to Experiment 1, which has no RT exclusion - this difference is not justified in the text and seems hard to justify on the face on it. Second, on what part of the experiment is it applied? Study? Test? Both? Third, it seems to be pretty harsh. By definition, in a normal distribution at least, 1 s.d. below is going to exclude about 17% of participants. And the RT at which it cuts people out - about 800ms - although fast, is not obviously a person blowing off the experiment. And was there no need to exclude any very long mean RTs (e.g. 10s of seconds)? Overall, I think this needs some more thought. Given the time remaining, perhaps see if it still works (i.e. BF > 3) without this additional Experiment 2 exclusion criterion?

### p.1 

twice as much -> twice as often 

"tend to show base rate following" -> add "(i.e. A -> common)" or similar.

"a different variety" -> "a variety"

"an attentional mechanism that drives not only learning but responding as well." -> "an attentional meachanism that drives both learning and responding"

## p.2 

"Unfortunately, there is no statistical anal- ysis confirming that BC → rare is reliably different than BC → common." -> "...confirming that the IBRE is reliably observed".

"a sample size of n = 16" -> "a sample size of 16"

"an α = 0.05" -> "an α of 0.05"

"has power = 0.24" -> "has 24% power, which is substantially underpowered" (and drop next sentence)

"To our knowledge, there is only one attempt to implement the IBRE procedure without explicit feedback." -> "...to implement the standard trial-by-trial IBR`e procedure without explicit feedback" ('cos you list two without this trial-by-trial caveat  - Johansen Appendix & 3)"

I would drop discussion of Johansen exp. 2 - it's not needed and you don't have space.

not "sequential" presentation, perhaps, because you don't know how people dealt with that list. Perhaps "itemized rather than summarised" presentation. And, perhaps earlier in the paragraph say that the summary was in the form of a table? (if I'm right about that?)

"Furthermore, Wills et al. (2014)" -> add "in an EEG study"

"ROI" -> "region of interest (ROI)" (should always define acronyms before use unless 100% all likely readers would know them"

"atten- tional reallocation occurs in a standard supervised learning" -> "prediction-error-driven attentional reallocation" (and drop final clause of course)

End of last intro para, from "...these three studies" - I would drop this and go straight to the "Experiment 1" section 

Also, I not in that bit I'm saying to cut, you cite Kruschke's eye-track study, not previously mentioned in the intro. What I suggest you do here is, when you first introduce the Don study, put "(see also Kruschke, K.. & H..., 2005)" somewhere.

"The rare response bias" -> add "to BC".

"The only information available in their report..." - I would remove this and the rest of the paragraph onwards (so, keep the first sentence, remove the rest). You don't need it, it's unnecessarily negative, you don't have space, and it raises faux questions with likely reviewers about methodological details.

## p. 3

"threshold has passed" -> "threshold was passed"

"label what disease" -> "say which disease"

"test the presence" -> "test for the presence"

"rational responding" -> "base rate following"

## p. 4

"can still experience" -> "might still experience"

"an implicit prediction" -> "a silent prediction" ? "implict" has a number of connotations concerning access to conscious awareness that we probably don't want to get into here...

"asked pariticipants to memorise the arrangement of shapes" - was that the instruction? Because the arrangement, as such, conveys no information, right? Because of spatial counterbalancing. If it was the instruction, no worries. But if not, consider a re-phrase.

"Similarly, the test phase..." -> "The test phase..."

See comments about exclusion criteria.

## p. 5

I think you do not need the decimal places on a six-figure BF :-)

"which will result" -> which could result

"the IBRE is partially caused" -> "the IBRE is caused". Let's go strong on this one!

"Participants learned sentences..." - this sentence begins in the past tense and so should continue in that tense.

"general context model" -> 'generalized context model"

O'Bryan cite should be Author (date), not (Author, date). 

## p.6

Also worth mentioning that ELMO can't do the shared cue effect (i.e. presence of shared cue required for IBRE). Kruschke has a paper on this - I think you cite it elsewhere? Kruschke 2001a.

"because of their inability" -> largely because? (given what you've just said about ELMO?)

"We made available" -> "We have made available"

Add a note to say links will be inserted when document is de-anonymised?

"To Be Added" -> "[to be added on denonymization of paper]"
