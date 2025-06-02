## 2025 Machine Agency Book Review

### Author: Clayton Lewis

### Publisher: Springer

### e‑ISBN: 978‑3‑031‑76646‑6

## Key Conclusions

**Preface**  
The author situates the book within the tradition of predictive psychology and explains why large language models—trained to anticipate the next token—provide an unexpectedly rich window for reflecting on the human mind. He recounts his personal journey, from his skepticism in the 1960s toward natural‑language processing to his surprise at GPT‑4’s capabilities. He states that, although the work mentions applications and possible risks, its goal is strictly cognitive: to extract insights about how we think based on what these systems can already do, not to improve the models themselves. He closes the preface by announcing that he will employ hypothetical extensions—the **“Prediction Room,”** capable of perceiving images or acting—only to explore parallels with human cognition.

**General Content and Plan of the Work**  
After listing thirty chapters grouped into seven parts, the author outlines his strategy: each chapter revisits landmark psychological experiments and asks whether a purely predictive system could reproduce the phenomenon. When the answer is affirmative, the theoretical consequences are discussed; when negative, the gaps are pinpointed. The journey begins with a detailed presentation of the **Prediction Room**, continues through six major blocks (Problem Solving, Memory, Language, Action, The Human Condition, Mechanisms, and Interpretation), and concludes with reflections and open challenges.

**Chapter 1 — Introduction**  
The fundamentals of LLMs are explained: neural networks trained on millions of token sequences to predict the next symbol. The author emphasizes that these models do not store a linear record of the corpus but instead build a statistical abstraction that allows them to respond to sequences never seen before. Surprising demonstrations—from Raven‑style analogies to safety advice—reveal reasoning, tacit memory, and linguistic flexibility. Classic objections are then raised: lack of sensory grounding, costly knowledge updates, and the ambiguous role of fine‑tuning. The chapter ends with a roadmap: using predictive success as a lens to reinterpret human reasoning, memory, emotion, and language.

**Chapter 2 — The Prediction Room**  
A conceptual model is introduced that extends LLMs with a continuous flow of multimodal perception, motor actions, and *inner speech*. This system updates its predictive model in real time—unlike current LLMs, which are frozen after training—and generates behaviors when its own model anticipates them. The idea is justified by linking it to Active Inference theory: acting is, in a sense, confirming our predictions. Finally, the author details why imagining a Prediction Room helps compare diverse tasks—such as solving analogies or imitating gestures—without pre‑built symbolic structures.

---

### Part I — Problem Solving and Reasoning

*Overview*  
Chapters 3 to 8 will analyze classic problems to investigate whether mere prediction suffices. Highlighted is the Luchins Einstellung effect: after solving several tasks with the same pattern, people get stuck using that approach even when a shorter one emerges. The author prompts GPT‑4 with examples and finds that the model reproduces strategic rigidity, suggesting that *fixation* can emerge without symbolic rules, merely from sensitivity to recent context. Kahneman’s “fast and slow” distinction is introduced, anticipating that LLMs possess analogues of both systems: fast pattern matching and slower sequential reasoning.

**Chapter 3 — Einstellung**  
After summarizing the original water‑jar experiment, the GPT‑4 protocol is described: graded instructions, induction problems, and a final test. The model finds long solutions after the training phase and returns to the short shortcut when induction is omitted, reproducing human fixation. The author contrasts this behavior with earlier explanations based on production systems; he now observes that GPT produces the solution as discourse, interpreted contextually without internal logical structures. He concludes that *natural* semantics derived from text is enough to model the phenomenon.

**Chapter 4 — Analogical Reasoning**  
The surprising performance of GPT‑3 on digit, letter, and word analogies is analyzed. First, a rudimentary model (LoAn) is shown to solve patterns by copying subsequences, without abstract concepts. Verbal analogy is then examined; by manipulating delimiters and list length, the author observes that the network identifies relations (antonyms, synonyms, category‑member) through contextual frequency. He proposes *virtual abduction*: each pair implicitly evokes a rule, and the rules compete like votes to predict the next token. This mechanism, although different from classical structure mapping, explains why analogy emerges from pure predictive pressure.

---

### Section 5 — More Reasoning: Inference and Prediction  
The chapter starts from Brandom’s and Harman’s critique that human reasoning is not pure logical calculation. Brandom shows that real inferences rely on indefinite networks of premises—such as the thousand conditions that might qualify “if I strike the match, it lights”—and Harman notes that logic, being monotonic, does not tell us which conclusion to pick or when to retract. The author translates “A, B, C → I think D” into predictive logic: different cues vote for possible thoughts, and the winner is the one with the most contextual weight. Counter‑examples (wet matches, no oxygen) simply add votes against, and belief revision occurs when new data flip the majority. Logic thus becomes ex‑post commentary on useful patterns, not the engine of thought.

### Section 6 — Transfer of Skills, Production Rules, and Prediction  
Drawing on Polson’s 1980s studies of text editing, the chapter describes how ACT‑R measures *transfer* by counting how many existing production rules apply to a new task; fewer new rules, less learning time. Lewis shows that a purely predictive model reproduces that pattern without storing declarative rules: if the system has already experienced contexts that anticipate certain actions, it need not relearn them. This explains ACT‑R’s empirical success but highlights a crucial difference: robustness. In a symbolic system a single‑bit error breaks the rule; in a voting predictive model, errors are diluted and the overall answer still works. Hence GPT understands “prsident” as “president” without an explicit orthographic correction module.

### Section 7 — Qualitative Physics  
The tour through qualitative physics—Forbus, Charniak, and the dream of robots that *think* without equations—shows that GPT‑4 already answers many practical questions (why a can explodes in fire, how to pour coffee, how a doorbell solenoid vibrates) without the structured representations that the symbolic school deemed indispensable. The key is the semantic breadth arising from massive training: the same model that describes solenoid torque also offers safety warnings, jokes, and pedagogical uses. For Lewis this confirms that predictive pressure suffices to generate plausible physical inferences, while also noting limits: the description is less rigorous than classical mathematical simulation but far more flexible and contextual.

### Section 8 — Situated Cognition  
Carraher’s study of street‑vendor children in Recife shows that they solve perfect multiplications while collecting payment but fail with the same numbers in a pencil‑and‑paper test. From a rule‑based viewpoint, two distinct rule‑sets (market vs. classroom) must be duplicated. From the predictive perspective it is more natural: the Prediction Room’s experiential flow associates different patterns to each environment without explicit separate memories. The cues that arise in the street—money, fruit, haggling—do not appear at the desk, and vice versa; performance differences emerge from contextual disparity, not from an intrinsic arithmetic deficit.

### Section 9 — Recall from Long‑Term Memory  
Williams’s thesis on remembering classmates decades later reveals an iterative search, cue generation, consistency checks, and near‑false memories. Lewis reproduces the phenomenon with GPT: the model suggests correct titles and invented authors, and only removes errors if instructed to check against alternative contexts. Both S1 and GPT generate candidates, test them with new information, and refine the output; the difference is that GPT does not self‑initiate verification because its corpus lacks introspective examples, whereas a continuously trained PR could learn that loop. “Storing and retrieving” is thus a poor metaphor: predictive memory weaves contexts that maximize plausible votes, always open to extension, contradiction, or replacement.

---

### Transition to Part II — Memory  
The chapter announces the shift from reasoning to memory and introduces the issue of *continuous updating*, impossible today in LLMs due to catastrophic forgetting. Lewis proposes that in a fully operational PR, the same mechanism that explains episodic recall—and that GPT already sketches with external aids like Bing—would allow new experiences to be integrated without destabilizing previous learning.

---

## TODO

- **Chapter 10 – Interference with World Knowledge**  
- **Chapter 11 – Speed‑Accuracy Trade‑offs**  
- **Chapter 12 – Is Knowledge Propositionally Represented?**  
- **Chapter 13 – Associationism**  
- **Chapter 14 – Procedural vs. Declarative Knowledge**  
- **Chapter 15 – Language Learning**  
- **Chapter 16 – Inner Language**  
- **Section 16 – Inner Speech**  
- **Section 17 – Babies and Other Primates**  
- **Section 18 – Gestures**  
- **Section 19 – Action and Identity**  
- **Section 20 – Predictive Modeling and Active Inference**  
- **Section 21 – Embodiment and Grounding**  
- **Section 22 – Concepts?**  
- **Section 23 – Emotions**  
- **Section 24 – Intuition**  
- **Section 25 – Belief–Desire Psychology**  


