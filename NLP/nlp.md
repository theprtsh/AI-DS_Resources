1. **What is the study of morphology in NLP?**
**Correct Answer:** Study of word structure
**Reasoning:** Morphology is a subfield of linguistics (and by extension, NLP) that deals with the internal structure of words and how they are formed from smaller meaningful units called morphemes. It is not about sentence structure (syntax) or meaning (semantics).

2. **What is a morpheme?**
**Correct Answer:** The smallest grammatical unit of meaning
**Reasoning:** A morpheme is the most basic unit of meaning in a language. It cannot be divided into smaller meaningful parts. For example, the word "unhappiness" has three morphemes: "un-", "happy", and "-ness".

3. **Which of these is a derivational morpheme?**
**Correct Answer:** un-
**Reasoning:** Derivational morphemes are affixes (prefixes or suffixes) that are added to a word to create a new word with a new meaning or a different lexical category (part of speech). The prefix "un-" changes the meaning of a word to its opposite (e.g., "happy" -> "unhappy"). "-ing", "-s", and "-ed" are inflectional morphemes, which modify a word's tense, number, etc., without changing its core meaning or category.

4. **Which of these is a free morpheme?**
**Correct Answer:** dog
**Reasoning:** A free morpheme is a morpheme that can stand alone as its own word (e.g., "dog", "run", "happy"). A bound morpheme, like "-ly", "-ed", and "-s", must be attached to a free morpheme.

5. **What is stemming used for?**
**Correct Answer:** To group inflected forms of words
**Reasoning:** Stemming is a crude heuristic process that chops off the endings of words (affixes) to reduce them to a common base form, or stem. The goal is to conflate different inflected forms of a word (e.g., "running", "runs", "ran" -> "run") so they can be analyzed as the same item, which is useful in tasks like information retrieval.

6. **Which NLP task often relies on morphological parsing?**
**Correct Answer:** Part-of-speech tagging
**Reasoning:** Morphological parsing, which identifies the morphemes within a word, provides crucial information about a word's likely part of speech. For example, a word ending in "-ly" is often an adverb, and a word ending in "-ed" is often a past tense verb. This information is a key feature for accurate POS tagging.

7. **What does a parse tree represent?**
**Correct Answer:** The grammatical structure of a sentence
**Reasoning:** A parse tree is a tree diagram that visually represents the syntactic structure of a sentence according to a formal grammar (like CFG). It shows how the sentence breaks down into phrases (e.g., Noun Phrase, Verb Phrase) and how those phrases relate to each other hierarchically.

8. **What is a context-free grammar (CFG)?**
**Correct Answer:** A set of rules generating syntactically valid sentences
**Reasoning:** A CFG is a formal grammar used to model the syntax of a language. It consists of a set of production rules that describe how symbols (non-terminals like 'S' for sentence) can be rewritten into other symbols (other non-terminals or terminals/words). It defines all the possible valid sentence structures in a language.

9. **What is syntactic ambiguity?**
**Correct Answer:** A sentence having multiple grammatical interpretations
**Reasoning:** Syntactic ambiguity occurs when a sentence's word sequence can be parsed in more than one way, leading to different meanings. A classic example is "I saw the man with the telescope," which could mean I used a telescope to see the man, or I saw a man who was holding a telescope.

10. **What is a probabilistic context-free grammar (PCFG)?**
**Correct Answer:** A CFG with probabilities assigned to production rules
**Reasoning:** A PCFG is an extension of a CFG. Each production rule has an associated probability. These probabilities are learned from a treebank (a corpus of parsed sentences). This allows a parser to not only find all possible parses but also to rank them by their likelihood, choosing the most probable one.

11. **"I saw bats" contains which type of ambiguity?**
**Correct Answer:** Lexical
**Reasoning:** The ambiguity here comes from the word "bats," which has multiple meanings (flying mammals or sports equipment). This is lexical ambiguity, where a single word form has multiple senses. The sentence structure itself is not ambiguous.

12. **The words "bank/data bank/blood bank" is an example of ----------**
**Correct Answer:** Polysemy
**Reasoning:** Polysemy occurs when a single word has multiple related meanings. The core concept of "bank" involves a "storage place" or "repository," which is extended to financial institutions ("bank"), data storage ("data bank"), and medical storage ("blood bank"). The meanings are connected, unlike homonymy where they are coincidentally identical.

13. **HMM are designed to model the joint distribution P(H , O) , where H is the _____state and O is the ________ state**
**Correct Answer:** Hidden, Observed
**Reasoning:** In a Hidden Markov Model (HMM), the system being modeled is assumed to be a Markov process with hidden (unobserved) states `H`. We can only observe the outputs `O` that these hidden states produce. In POS tagging, the hidden states are the POS tags, and the observed outputs are the words.

14. **Elements of Semantic analysis**
**Correct Answer:** Hyponymy, Homonymy, Polysemy
**Reasoning:** Semantic analysis involves understanding meaning. This includes studying the relationships between words (lexical semantics). Hyponymy (is-a relationships, e.g., dog is an animal), homonymy (same form, unrelated meanings, e.g., "bank"), and polysemy (same form, related meanings) are all fundamental lexical relations analyzed in semantics.

15. **Which of the following is a example of irregular noun form?**
**Correct Answer:** Mouse
**Reasoning:** An irregular noun does not form its plural by adding "-s" or "-es". The plural of "mouse" is "mice". "Fox", "dog", and "cat" are regular nouns that form their plurals by adding "-es" or "-s" ("foxes", "dogs", "cats").

16. **What is the role of syntactic analysis in NLP?**
**Correct Answer:** Understanding sentence structure
**Reasoning:** The primary role of syntactic analysis (or parsing) is to analyze the grammatical structure of a sentence. It identifies the constituent parts of a sentence (nouns, verbs, phrases, clauses) and reveals the relationships between them, such as subject-verb-object.

17. **.______ morphology is a type of word formation that creates new lexemes**
**Correct Answer:** Derivational morphology
**Reasoning:** Derivational morphology creates new words (new lexemes), often with a change in the part of speech or core meaning (e.g., "happy" [adj] -> "unhappiness" [noun]). Inflectional morphology only modifies a word to express grammatical features like tense or number without creating a new dictionary entry.

18. **Which approach to WSD uses dictionaries or thesauri?**
**Correct Answer:** Dictionary-based approach
**Reasoning:** Dictionary-based (or knowledge-based) approaches to Word Sense Disambiguation (WSD) rely on external lexical resources like machine-readable dictionaries (e.g., WordNet) and thesauri. The Lesk algorithm is a famous example, which compares the dictionary definitions of an ambiguous word's senses to the words in its surrounding context.

19. **What is syntactic structure used for in NLP?**
**Correct Answer:** To determine grammatical relationships in a sentence
**Reasoning:** The output of syntactic analysis is a syntactic structure (like a parse tree). This structure is crucial for determining "who did what to whom" – the grammatical relationships between words. This is a foundational step for more complex tasks like semantic role labeling and machine translation.

20. **What is the primary challenge of syntactic analysis?**
**Correct Answer:** Resolving syntactic ambiguity
**Reasoning:** Natural language is full of sentences that can be parsed in multiple ways (syntactic ambiguity). The primary challenge for a parser is to use contextual clues, world knowledge, and probabilistic information to select the correct parse from among the many possible ones.

21. **What is a context-free grammar (CFG)?**
**Correct Answer:** A set of rules generating syntactically valid sentences
**Reasoning:** (Repeated question, same reasoning as Q.8) A CFG is a formal grammar consisting of production rules that define the hierarchical structure of sentences in a language, specifying how to generate all syntactically valid strings.

22. **Which algorithm is used for parsing sentences in CFG?**
**Correct Answer:** CYK algorithm
**Reasoning:** The Cocke-Younger-Kasami (CYK) algorithm is a classic parsing algorithm for Context-Free Grammars. It uses dynamic programming to efficiently parse sentences, even ambiguous ones, by building a table of possible constituents. It requires the grammar to be in Chomsky Normal Form.

23. **What does statistical parsing rely on?**
**Correct Answer:** Probabilistic context-free grammars
**Reasoning:** Statistical parsing uses data-driven methods. It primarily relies on Probabilistic Context-Free Grammars (PCFGs), where rules have probabilities derived from a treebank. The parser searches for the parse tree with the highest probability given the sentence, which helps resolve ambiguity.

24. **What is syntactic ambiguity?**
**Correct Answer:** A sentence having multiple grammatical interpretations
**Reasoning:** (Repeated question, same reasoning as Q.9) This is when a sentence's word order allows for more than one valid parse tree, each corresponding to a different interpretation of the sentence's structure and meaning.

25. **Which parsing technique uses probabilities to select the most likely parse tree?**
**Correct Answer:** Statistical parsing
**Reasoning:** Statistical parsing is defined by its use of probabilities. By training on a treebank (a large collection of manually parsed sentences), a statistical parser learns the probabilities of different grammatical constructions. When faced with an ambiguous sentence, it calculates the probability of each possible parse and selects the most likely one.

26. **What is a probabilistic context-free grammar (PCFG)?**
**Correct Answer:** A CFG with probabilities assigned to production rules
**Reasoning:** (Repeated question, same reasoning as Q.10) A PCFG augments a standard CFG by adding a probability to each production rule, enabling the calculation of the likelihood of any given parse tree.

27. **What type of grammar is used in syntactic analysis?**
**Correct Answer:** Context-free grammar
**Reasoning:** Context-Free Grammar is the most widely used formal grammar for syntactic analysis in NLP. Its balance of expressive power and computational tractability makes it suitable for modeling the phrase structure of natural languages.

28. **What is a top-down parsing algorithm?**
**Correct Answer:** Begins parsing from the root of the parse tree
**Reasoning:** A top-down parser starts with the start symbol of the grammar (e.g., 'S' for sentence) and applies production rules in a forward direction to try to expand it until it matches the input sentence. It works from the root of the parse tree down to the leaves (the words).

29. **What are the two components of FST?**
**Correct Answer:** Input states and output symbols
**Reasoning:** A Finite-State Transducer (FST) is a finite-state automaton that maps an input string to an output string. Its core components are a set of states and a set of transitions between them. Each transition reads a symbol from the input string and writes a symbol to the output string. They are widely used in morphology for tasks like stemming and generating word forms.

30. **Which of the following is NOT a main role of a parser?**
**Correct Answer:** To translate text into binary code
**Reasoning:** The main roles of a parser in compilation (and by analogy in NLP) are to analyze syntax, report errors, and build a structural representation (e.g., a parse tree or symbol table). Translating to binary code is the role of the code generation phase, which comes after parsing.

31. **What is the role of syntactic analysis in NLP?**
**Correct Answer:** Understanding sentence structure
**Reasoning:** (Repeated question, same reasoning as Q.16) Its core role is to uncover the grammatical structure of sentences, which is essential for extracting meaning.

32. **What is bottom-up parsing?**
**Correct Answer:** Starts with the input symbols and builds up the parse tree
**Reasoning:** A bottom-up parser starts with the individual words of the input sentence (the leaves of the future parse tree) and applies production rules in reverse, combining smaller constituents into larger ones until it reaches the start symbol. It builds the tree from the bottom up.

33. **What is the difference between statistical parsing and rule-based parsing?**
**Correct Answer:** Statistical parsing uses probabilities, while rule-based parsing uses fixed rules
**Reasoning:** This is the fundamental difference. Rule-based parsing relies on a hand-crafted set of grammatical rules. Statistical parsing uses a probabilistic model trained on data to guide the parsing process and choose between ambiguities. Statistical parsers generally perform better with robust, real-world text.

34. **In top-down parsing, the parse tree is constructed starting from:**
**Correct Answer:** The start symbol
**Reasoning:** (Consistent with Q.28) Top-down parsing is goal-driven. It begins with the highest-level goal (the start symbol, e.g., 'S') and recursively expands it using the grammar's production rules until it matches the terminal symbols (words) in the input string.

35. **What is syntactic structure used for in NLP?**
**Correct Answer:** To determine grammatical relationships in a sentence
**Reasoning:** (Repeated question, same reasoning as Q.19) The syntactic structure is the representation that explicitly shows grammatical relationships like subject, object, and modifier, which are necessary for understanding sentence meaning.

36. **What is a dependency tree?**
**Correct Answer:** A tree showing grammatical relationships between words in a sentence
**Reasoning:** A dependency tree is an alternative to a constituency-based parse tree. It represents syntax as a set of binary relations (dependencies) between words. Each relation connects a head (a governing word) and a dependent. The tree shows direct relationships like subject-verb or verb-object.

37. **What is head-dependent structure in syntactic analysis?**
**Correct Answer:** A grammatical relationship where one word governs another
**Reasoning:** This is the core concept of dependency grammar. The head is the word that determines the syntactic properties of a phrase, and the dependents are words that modify or complete the head. For example, in "big dog", "dog" is the head noun and "big" is its dependent adjective.

38. **What is the difference between lemmatization and stemming?**
**Correct Answer:** Lemmatization provides root words, while stemming cuts endings
**Reasoning:** Stemming crudely chops off affixes to reach a common stem, which may not be a real word (e.g., "running" -> "run", but "are" -> "ar"). Lemmatization uses a vocabulary and morphological analysis to return the base or dictionary form of a word, known as the lemma (e.g., "are" -> "be", "running" -> "run"). Lemmatization is more accurate but computationally more expensive.

39. **What is the primary challenge of syntactic analysis?**
**Correct Answer:** Resolving syntactic ambiguity
**Reasoning:** (Repeated question, same reasoning as Q.20) The main challenge is choosing the correct parse from multiple grammatically valid options, which requires context and world knowledge.

40. **What is lexical semantics?**
**Correct Answer:** Study of word meanings and relationships
**Reasoning:** Lexical semantics is the subfield of linguistics and NLP concerned with the meaning of individual words (lexemes) and the systematic relationships between them, such as synonymy, antonymy, hyponymy, and meronymy.

41. **What is Word Sense Disambiguation (WSD)?**
**Correct Answer:** Determining the correct meaning of a word in context
**Reasoning:** WSD is the task of identifying which sense (meaning) of a word is being used in a given sentence or context. For example, determining if "bank" refers to a financial institution or the side of a river.

42. **Which approach to WSD uses dictionaries or thesauri?**
**Correct Answer:** Dictionary-based approach
**Reasoning:** (Repeated question, same reasoning as Q.18) Knowledge-based or dictionary-based methods use pre-existing lexical knowledge resources like WordNet to perform disambiguation by comparing word context to sense definitions.

43. **What is syntactic analysis?**
**Correct Answer:** Parsing the grammatical structure of sentences
**Reasoning:** (Repeated concept) Syntactic analysis is the process of analyzing a string of symbols (words) to conform to the rules of a formal grammar, resulting in a parse tree that reveals the sentence's grammatical structure.

44. **The main goal of syntactic analysis in NLP is to:**
**Correct Answer:** Check if the text conforms to formal grammar rules
**Reasoning:** While understanding structure is key, a fundamental goal is to determine if a sentence is well-formed according to the grammatical rules of the language. This validation is a prerequisite for deeper semantic analysis. Other options are applications or results of this analysis, not its core goal.

45. **Which type of parsing starts from the input symbols and works towards the start symbol?**
**Correct Answer:** Bottom-up parsing
**Reasoning:** (Consistent with Q.32) Bottom-up parsing is data-driven. It begins with the terminal symbols (the words) and uses the grammar's rules to combine them into larger and larger constituents until it forms the start symbol.

46. **Which type of representation is used in syntactic analysis?**
**Correct Answer:** Parse tree
**Reasoning:** The parse tree is the most common graphical representation of the output of syntactic analysis. It explicitly shows the hierarchical constituency structure of a sentence. Dependency graphs are another common representation.

47. **What does a parse tree represent?**
**Correct Answer:** The grammatical structure of a sentence
**Reasoning:** (Repeated question, same reasoning as Q.7) It is a tree diagram that depicts the syntactic structure derived from the grammar, showing how the sentence is composed of nested phrases.

48. **What is Latent Semantic Analysis (LSA)?**
**Correct Answer:** A method for extracting hidden relationships between words
**Reasoning:** LSA is a technique in natural language processing and information retrieval. It uses a mathematical technique called Singular Value Decomposition (SVD) to identify underlying (latent) conceptual relationships between words and documents by analyzing large text corpora. It does not rely on pre-defined syntactic or semantic rules.

49. **What does semantic analysis in NLP focus on?**
**Correct Answer:** Meaning of words, phrases, and sentences
**Reasoning:** While syntax deals with structure, semantics deals with meaning. Semantic analysis is concerned with interpreting the meaning of linguistic units, from individual words to entire sentences and texts.

50. **Which of these represents relations among lexemes?**
**Correct Answer:** Synonyms and antonyms
**Reasoning:** Synonyms (words with similar meanings) and antonyms (words with opposite meanings) are classic examples of lexical semantic relations that exist between lexemes (word entries in the mental lexicon).

51. **What is semantic role labeling?**
**Correct Answer:** Identifying the role of words in a sentence
**Reasoning:** Semantic Role Labeling (SRL) is the task of identifying the semantic roles played by constituents in a sentence. It answers "who did what to whom, when, where, and why" by labeling arguments with roles like Agent, Patient, Instrument, or Location. It typically operates on the output of syntactic parsing.

52. **What is hypernymy?**
**Correct Answer:** A hierarchical relationship where one term is more general than another
**Reasoning:** Hypernymy is the "is-a-kind-of" relationship. A hypernym is a broad, superordinate term that encompasses more specific terms (hyponyms). For example, "fruit" is a hypernym of "apple" and "banana".

53. **In a left-most derivation, which part of the sentential form is replaced first?**
**Correct Answer:** Left-most non-terminal
**Reasoning:** A derivation is the process of applying grammar rules to generate a string. In a left-most derivation, the leftmost non-terminal symbol in the current sentential form is always the one that is expanded next. This defines a specific order for building the parse tree.

54. **What does hyponymy represent?**
**Correct Answer:** A hierarchical relationship where one term is more specific than another
**Reasoning:** Hyponymy is the inverse of hypernymy. A hyponym is a word with a more specific meaning than its hypernym. "Apple" and "banana" are hyponyms of "fruit". This relationship creates a semantic hierarchy.

55. **In a parse tree, the leaf nodes represent:**
**Correct Answer:** Terminal symbols
**Reasoning:** The leaf nodes of a parse tree are the terminal symbols of the grammar, which are the actual words (or tokens) of the sentence. The internal nodes represent non-terminal symbols (phrasal categories like NP, VP).

56. **What is polysemy?**
**Correct Answer:** A word having multiple meanings
**Reasoning:** Polysemy is the phenomenon where a single word has several different, but closely related, meanings. For example, the word "head" can mean the top of your body, the leader of a company, or the froth on a beer. The meanings are connected by extension.

57. **What is synonymy?**
**Correct Answer:** Words with similar meanings
**Reasoning:** Synonymy is a semantic relation where different words have the same or very similar meanings in some or all contexts (e.g., "big" and "large", "quick" and "fast").

58. **Which semantic relation is the opposite of synonymy?**
**Correct Answer:** Antonymy
**Reasoning:** Antonymy is the relationship between words with opposite meanings (e.g., "hot" and "cold", "up" and "down"). It is the direct counterpart to synonymy.

59. **What is the primary purpose of WSD?**
**Correct Answer:** To resolve ambiguity in word meanings
**Reasoning:** (Repeated concept) The core purpose of Word Sense Disambiguation is to resolve the ambiguity that arises from words having multiple possible meanings (polysemy/homonymy) by selecting the correct sense based on context.

60. **What is semantic ambiguity?**
**Correct Answer:** A word or sentence having multiple possible meanings
**Reasoning:** Semantic ambiguity occurs when a word, phrase, or sentence can be interpreted to have more than one meaning. This can be due to lexical ambiguity (a single word) or structural ambiguity (the whole phrase).

61. **Which model is commonly used for semantic representation?**
**Correct Answer:** Word embeddings
**Reasoning:** Modern NLP heavily relies on word embeddings (e.g., Word2Vec, GloVe) for semantic representation. These are dense vector representations of words in a continuous space, where semantic similarity is reflected by geometric proximity (words with similar meanings have vectors that are close together).

62. **What is the key focus of lexical semantics?**
**Correct Answer:** Word meanings and relationships
**Reasoning:** (Repeated concept) Lexical semantics is specifically focused on the meaning of words and the semantic relationships (like synonymy, antonymy, hyponymy) that exist between them.

63. **Which of these is NOT a semantic relation?**
**Correct Answer:** Morpheme segmentation
**Reasoning:** Morpheme segmentation is a task in morphology, not semantics. It involves breaking a word down into its constituent morphemes (e.g., "un-happy-ness"). Hypernymy, synonymy, and antonymy are all semantic relations.

64. **Which mathematical model of grammar was introduced by Noam Chomsky in 1956?**
**Correct Answer:** Context Free Grammar (CFG)
**Reasoning:** Noam Chomsky's hierarchy of formal grammars, introduced in the 1950s, is a foundational concept in computer science and linguistics. The Context-Free Grammar is a central model in this hierarchy and has been immensely influential in computational linguistics for modeling syntax.

65. **What is a homonym?**
**Correct Answer:** Words that sound alike but have different meanings
**Reasoning:** Homonyms are words that share the same spelling *and* pronunciation (homographs *and* homophones) but have completely unrelated, distinct meanings. A classic example is "bank" (financial institution) and "bank" (side of a river).

66. **What is semantic similarity?**
**Correct Answer:** A measure of how similar two words or sentences are in meaning
**Reasoning:** Semantic similarity is a metric that quantifies the degree to which the meanings of two words, phrases, or sentences are alike. It is a core concept in tasks like information retrieval, text summarization, and question answering.

67. **Dependency grammar is different from constituency grammar because:**
**Correct Answer:** It is based on dependency relations between words
**Reasoning:** This is the fundamental distinction. Constituency grammar (like CFG) groups words into nested phrases (constituents). Dependency grammar ignores constituents and instead represents syntax purely as a set of binary asymmetric relations (dependencies) between individual words.

68. **What is part-of-speech tagging?**
**Correct Answer:** Assigning grammatical categories to words
**Reasoning:** Part-of-speech (POS) tagging is the process of marking each word in a text corpus with its corresponding part of speech (e.g., noun, verb, adjective, adverb), based on both its definition and its context.

69. **In Context Free Grammar (CFG), the set of basic symbols used to form strings is called:**
**Correct Answer:** Terminals
**Reasoning:** The formal definition of a CFG is a 4-tuple (N, T, S, P). `T` is the set of Terminal symbols. These are the basic symbols that form the strings of the language (e.g., words). `N` is the set of Non-terminals (syntactic variables), `S` is the Start symbol, and `P` is the set of Production rules.

70. **What is the study of morphology in NLP?**
**Correct Answer:** Study of word structure
**Reasoning:** (Repeated question, same reasoning as Q.1)

71. **What does HMM stand for in POS tagging?**
**Correct Answer:** Hidden Markov Model
**Reasoning:** Hidden Markov Models are a very common statistical model used for sequence labeling tasks like POS tagging. The hidden states are the POS tags, and the observed emissions are the words.

72. **What is the purpose of lemmatization?**
**Correct Answer:** Convert words to their base forms
**Reasoning:** (Repeated concept, consistent with Q.38) The purpose is to reduce inflected words to their base dictionary form, or lemma, for normalization and analysis.

73. **What type of morpheme cannot stand alone?**
**Correct Answer:** Bound morpheme
**Reasoning:** A bound morpheme is a morpheme that must be attached to a free morpheme to have meaning and cannot stand alone as a word. All affixes (prefixes, suffixes, infixes) are bound morphemes (e.g., "-ed", "un-", "-s").

74. **What are the two components of FST?**
**Correct Answer:** Input states and output symbols
**Reasoning:** (Repeated question, same reasoning as Q.29) An FST is defined by its states and the transitions between them, where each transition reads an input symbol and writes an output symbol.

75. **Which of these is a free morpheme?**
**Correct Answer:** dog
**Reasoning:** (Repeated question, same reasoning as Q.4) "dog" can stand alone as a complete word.

76. **What is the primary challenge in POS tagging?**
**Correct Answer:** Ambiguity in word roles
**Reasoning:** Many words can function as more than one part of speech depending on the context (e.g., "book" can be a noun or a verb, "like" can be a verb, preposition, or conjunction). The main challenge is to correctly resolve this ambiguity for each token in context.

77. **What is the role of emission probabilities in HMM?**
**Correct Answer:** Probability of a word given a tag
**Reasoning:** In an HMM for POS tagging, there are two types of probabilities. Transition probabilities model P(tag_i | tag_i-1). Emission probabilities model P(word | tag), which is the likelihood of observing a specific word given that the current hidden state is a specific POS tag.

78. **What does a parse tree represent?**
**Correct Answer:** The grammatical structure of a sentence
**Reasoning:** (Repeated question, same reasoning as Q.7)

79. **What is syntactic ambiguity?**
**Correct Answer:** A sentence having multiple grammatical interpretations
**Reasoning:** (Repeated question, same reasoning as Q.9)

80. **What is the role of syntactic analysis in NLP?**
**Correct Answer:** Understanding sentence structure
**Reasoning:** (Repeated question, same reasoning as Q.16)

81. **The tuple notation (N, T, S, P) for grammar represents:**
**Correct Answer:** Non-terminals, Terminals, Start symbol, Production rules
**Reasoning:** This is the standard formal definition of a Context-Free Grammar. `N` is the set of Non-terminal symbols, `T` is the set of Terminal symbols, `S` is the Start symbol (a member of N), and `P` is the set of Production rules.

82. **What is bottom-up parsing?**
**Correct Answer:** Starts with the input symbols and builds up the parse tree
**Reasoning:** (Repeated question, same reasoning as Q.32)

83. **What is lexical semantics?**
**Correct Answer:** Study of word meanings and relationships
**Reasoning:** (Repeated question, same reasoning as previous "lexical semantics" question)

84. **What is the main limitation of rule-based POS tagging?**
**Correct Answer:** Inability to handle unknown words effectively
**Reasoning:** Rule-based taggers use a pre-defined set of contextual rules. Their major weakness is encountering words not in their lexicon (unknown words). They have no way to guess the tag for such words, whereas statistical or neural models can generalize from patterns in the training data.

85. **Which approach to WSD uses dictionaries or thesauri?**
**Correct Answer:** Dictionary-based approach
**Reasoning:** (Repeated question, same reasoning as Q.18)

86. **Which of the following best defines Word Sense Disambiguation (WSD)?**
**Correct Answer:** Determining the correct meaning of a word based on its context
**Reasoning:** (Repeated concept) This is the concise and accurate definition of the WSD task.

87. **What is semantic role labeling?**
**Correct Answer:** Identifying the role of words in a sentence
**Reasoning:** (Repeated question, same reasoning as previous "semantic role labeling" question)

88. **In homonymy, the senses of a word are:**
**Correct Answer:** Completely unrelated
**Reasoning:** This is what distinguishes homonymy from polysemy. In homonymy, the different meanings of the identical word form are historically and semantically unrelated; it's often a coincidence (e.g., "bat" (animal) and "bat" (sports equipment)).

89. **What is the study of morphology in NLP?**
**Correct Answer:** Study of word structure
**Reasoning:** (Repeated question, same reasoning as Q.1)

90. **What is a morpheme?**
**Correct Answer:** The smallest grammatical unit of meaning
**Reasoning:** (Repeated question, same reasoning as Q.2)

91. **The relationship between rose (flower type) and flower is an example of:**
**Correct Answer:** Hyponymy
**Reasoning:** A "rose" *is a type of* "flower". Therefore, "rose" is a hyponym of its hypernym "flower". This is a classic hierarchical "is-a" relationship.

92. **Which of these is a derivational morpheme?**
**Correct Answer:** un-
**Reasoning:** (Repeated question, same reasoning as Q.3)

93. **Which approach does LSA primarily rely on?**
**Correct Answer:** Statistical patterns in large corpora
**Reasoning:** Latent Semantic Analysis (LSA) is a purely statistical corpus-based method. It does not use handcrafted rules, dictionaries, or linguistic annotation. It derives semantic relationships by performing linear algebra (SVD) on a term-document matrix built from a large corpus.

94. **In NLP, a lexeme refers to:**
**Correct Answer:** The smallest unit of meaning, including all its inflected forms
**Reasoning:** A lexeme is an abstract unit of meaning. It represents a set of inflected forms. For example, the lexeme RUN encompasses the word forms "run", "runs", "ran", and "running". It is the headword or entry you would find in a dictionary.

95. **What is a corpus in POS tagging?**
**Correct Answer:** A large annotated collection of text used for training
**Reasoning:** In the context of POS tagging and NLP generally, a corpus is a large and structured set of texts. For supervised learning (like training an HMM tagger), this corpus must be annotated (tagged) with the correct POS labels.

96. **What is semantic similarity?**
**Correct Answer:** A measure of how similar two words or sentences are in meaning
**Reasoning:** (Repeated question, same reasoning as previous "semantic similarity" question)

97. **Which of these is a free morpheme?**
**Correct Answer:** dog
**Reasoning:** (Repeated question, same reasoning as Q.4)

98. **What is stemming used for?**
**Correct Answer:** To group inflected forms of words
**Reasoning:** (Repeated question, same reasoning as Q.5)

99. **What is syntactic analysis?**
**Correct Answer:** Parsing the grammatical structure of sentences
**Reasoning:** (Repeated question, same reasoning as previous "syntactic analysis" question)

100. **Which type of representation is used in syntactic analysis?**
**Correct Answer:** Parse tree
**Reasoning:** (Repeated question, same reasoning as previous "representation" question)

101. **What does a parse tree represent?**
**Correct Answer:** The grammatical structure of a sentence
**Reasoning:** (Repeated question, same reasoning as Q.7)

102. **What is a context-free grammar (CFG)?**
**Correct Answer:** A set of rules generating syntactically valid sentences
**Reasoning:** (Repeated question, same reasoning as Q.8)

103. **Which algorithm is used for parsing sentences in CFG?**
**Correct Answer:** CYK algorithm
**Reasoning:** (Repeated question, same reasoning as Q.22)

104. **"I saw bats" contains which type of ambiguity?**
**Correct Answer:** Lexical
**Reasoning:** (Repeated question, same reasoning as Q.11)

105. **The phrase “The White House issued a statement” is an example of:**
**Correct Answer:** Metonymy
**Reasoning:** Metonymy is a figure of speech where a thing or concept is referred to by the name of something closely associated with it. Here, "The White House" is not referring to the physical building but to the people within it (the executive branch of the U.S. government).

106. **The words "bank/data bank/blood bank" is an example of ----------**
**Correct Answer:** Polysemy
**Reasoning:** (Repeated question, same reasoning as Q.12) The meanings are related through the core idea of a "repository" or "storage place".

107. **Which of the following relations involves words with opposite meanings?**
**Correct Answer:** Antonymy
**Reasoning:** (Repeated concept) Antonymy is the semantic relation of opposition.

108. **HMM are designed to model the joint distribution P(H , O) , where H is the _____state and O is the ________ state**
**Correct Answer:** Hidden, Observed
**Reasoning:** (Repeated question, same reasoning as Q.13)

109. **Which of the following is NOT a linguistic relation between lexemes?**
**Correct Answer:** Lemmatization
**Reasoning:** Lemmatization is a computational process, not a inherent linguistic relation between words. Hyponymy, antonymy, and synonymy are all semantic relations that exist between lexemes.

110. **The Lesk algorithm for WSD works by:**
**Correct Answer:** Comparing context words with dictionary definitions to find maximum overlap
**Reasoning:** The core idea of the (simplified) Lesk algorithm is to disambiguate a word by comparing the words in its immediate context to the words in the dictionary definitions (glosses) of each of its possible senses. The sense whose definition has the highest word overlap with the context is chosen.

111. **Elements of Semantic analysis**
**Correct Answer:** Hyponymy, Homonymy, Polysemy
**Reasoning:** (Repeated question, same reasoning as Q.14)

112. **Which of the following is a example of irregular noun form?**
**Correct Answer:** Mouse
**Reasoning:** (Repeated question, same reasoning as Q.15)

113. **What does statistical parsing rely on?**
**Correct Answer:** Probabilistic context-free grammars
**Reasoning:** (Repeated question, same reasoning as Q.23)

114. **What is syntactic ambiguity?**
**Correct Answer:** A sentence having multiple grammatical interpretations
**Reasoning:** (Repeated question, same reasoning as Q.9)

115. **Which WSD approach does not require annotated training data?**
**Correct Answer:** Knowledge-based methods
**Reasoning:** Knowledge-based (or dictionary-based) methods, like the Lesk algorithm, rely on existing lexical resources (e.g., WordNet) and do not require a corpus that has been manually annotated with word senses for training. Supervised and semi-supervised methods do require such annotated data.

116. **Latent Semantic Analysis (LSA) primarily aims to:**
**Correct Answer:** Find hidden patterns and relationships between words and documents
**Reasoning:** (Repeated concept) LSA's goal is to uncover the latent semantic structure in a collection of text by analyzing the statistical co-occurrence patterns of words within documents.

117. **Which parsing technique uses probabilities to select the most likely parse tree?**
**Correct Answer:** Statistical parsing
**Reasoning:** (Repeated question, same reasoning as Q.25)

118. **What is a probabilistic context-free grammar (PCFG)?**
**Correct Answer:** A CFG with probabilities assigned to production rules
**Reasoning:** (Repeated question, same reasoning as Q.10)

119. **What type of grammar is used in syntactic analysis?**
**Correct Answer:** Context-free grammar
**Reasoning:** (Repeated question, same reasoning as Q.27)

