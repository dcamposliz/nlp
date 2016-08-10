# nlp

Introduction to Natural Language Processing
University of Michigan (Coursera)
Taught by: Dragomir R. Radev, Ph.D

https://www.coursera.org/learn/natural-language-processing

This course provides an introduction to the field of Natural Language Processing. It includes relevant background material in Linguistics, Mathematics, Probabilities, and Computer Science. Some of the topics covered in the class are Text Similarity, Part of Speech Tagging, Parsing, Semantics, Question Answering, Sentiment Analysis, and Text Summarization. The course includes quizzes, programming assignments in Python, and a final exam.

--

software dependencies

 - Python (== 2.7)

 - z (==3.0)

 - NumPy (>= 1.6.1)

 - SciPy (>= 0.9)

 - sklearn (==0.15.2) - important!

--

natural language processing (NLP) is the study of the computational treatment of natural (human) language -- in other words, teaching computers how to understand (and generate) human language.

--

modern applications:

 - search engines

 - question answering

 - translation systems

 - natural language assistants

--

computers are confused by (human) language

--

goals of this class

 - understand that NLP is hard (and why)

 - understand the key problems in NLP

 - learn about the methods used to address these problems

 - understand the limitations of these methods

--

linguistics

 - speaker

  - intention

  - generation

  - synthesis


 - listener

  - perception

  - interpretation

  - incorporation

--

basic NPL pipeline

 - (U)nderstanding and (G)eneration

 - Languange -(U)-> Computer -(G)-> Language

--

structure of the course

four major parts:

 - linguistic, mathematical, computational background

 - computational models of morphology, syntax, semantics, discourse, pragmatics

 - core NLP technology: parsing, part of speech tagging, text generation, etc

 - applications: text classification, machine translation, information extraction, etc

three major goals:

 - learn the basic principles and theoretical issues underlying natural language processing

 - learn techniques and tools used to develop practical, robust systems that can understand text and communicate with users in one or more languages

 - gain insight into some open research problems in natural language

--

some acronyms

 - NLP: natural language processing

 - CL: computational linguistics

 - IR: informational retrieval

 - SP: speech processing

 - HLT: human language technology

 - NLE: natural language engineering

 - ML: machine learning

--

there are relevant books, courses, reseach, and conferences

--

why is NLP hard?

 - computers are not good at metaphors

 - two sentences may look similar on the surface but they may be different syntactically

--

syntax & semantics

 - syntactically incorrect are typically marked with an asterisk (*)

 - semantically incorrect are typically marked with question mark (?)

example:

 - * Little a has Mary lamb.

 - ? Colorless green ideas sleep furiously.

--

words can have multiple meanings

--

there are various types of ambiguity in language:

 - morphological

 - phonetic

 - part of speech

 - synctactic

 - pp attachment

 - sense

 - modality

 - subjectivity

 - cc attachment

 - negation

 - referential

 - reflexive

 - ellipsis and parallelism

--

linguistic & mathematical background

 - linguistic knowledge
  
  - constituents

   - children eat pizza

   - they eat pizza

  - collocations

   - strong beer but *powerful beer

   - big sister but *large sister

  - knowledge about language

   - phonetics and phonology: study of sounds

   - morphology: the study of word components

   - syntax: the study of sentence and phrase structure

   - lexical semantics: the study of the meanings of words

   - compositional semantics: how to combine words

   - pragmatics: how to accomplish goals

   - discourse conventions: how to deal with units larger than utterances

--

automata

 - deterministic and non-deterministic finite state automata

 - push-down automata

grammars

 - regular grammars

 - context-free grammars

 - context-sensitive grammars

complexity

algorithms

 - dynamic programming

--



 - 
--
