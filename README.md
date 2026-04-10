# Mind Gateway
Curated resources on Artifical Intelligence (AI), Machine Learning (ML), Philosophy of Mind (PoM), and related topics.

## Contents
+ [Artificial Intelligence](#artificial-intelligence)
   + 📖 [On Intelligence](#on-intelligence) `layperson`
   + 📖 [A Thousand Brains Theory](#a-thousand-brains-theory) `layperson`
   + 📖 [AI: A Guide for Thinking Humans](#ai-a-guide-for-thinking-humans) `layperson`
   + 💯 📺 [MIT Artificial Intelligence](#mit-artificial-intelligence) `beginner`
   + 📺 [The AI Podcast](#the-ai-podcast) `layperson`
+ [General Machine Learning](#general-machine-learning)
   + 💯 📺 📖 [Learning from Data](#learning-from-data) `intermediate`
   + 📖 [Mathematics for Machine Learning](#mathematics-for-machine-learning) `intermediate`
   + 📖 [An Introduction to Statistical Learning](#an-introduction-to-statistical-learning) `intermediate`
   + 💯 📺 [Intuitive Machine Learning](#intuitive-machine-learning) `beginner`
   + 📰 [Papers with Code](#papers-with-code)
   + 📰 [Papers Daily](#papers-daily)
   + 💯 📰 [Distill](#distill) `beginner`/`intermediate`
+ [Deep Learning](#deep-learning)
   + 💯 📺 📖 [Deep Learning for Coders](#deep-learning-for-coders) `beginner`
   + 📺 [Heroes of Deep learning](#heroes-of-deep-learning) `intermediate`
   + 💯 📺 [Introduction to Deep Learning MIT](#introduction-to-deep-learning-mit) `beginner`
+ [Natural Language Processing](#natural-language-processing)
   + 📺 [A Code-First Introduction to NLP](#a-code-first-introduction-to-nlp) `intermediate` 
+ [Philosophy of Mind](#philosophy-of-mind)
   + 💯 📖 [Gödel, Escher, Bach -- an Eternal Golden Braid](#gödel-escher-bach----an-eternal-golden-braid) `layperson`
   + 📖 [The Society of Mind](#the-society-of-mind) `layperson`
   + 📖 [I Am a Strange Loop](#i-am-a-strange-loop) `layperson`
   + 📺 [Closer to Truth](#closer-to-truth) `layperson`
+ [Appendix](#appendix)
   + :electron: 📖 [Free Online Library](#free-online-library) 

## Artificial Intelligence
#### [On Intelligence](https://en.wikipedia.org/wiki/On_Intelligence) 
📖 by [Jeff Hawkins](https://en.wikipedia.org/wiki/Jeff_Hawkins) (2005)

The book explains why previous attempts at understanding intelligence and building intelligent machines have failed. It then introduces and develops the core idea of a proposed theory for how the human neocortex generates intelligent behavior, which the author calls the memory-prediction framework.

#### [A Thousand Brains Theory](https://numenta.com/a-thousand-brains-by-jeff-hawkins) 
📖 by [Jeff Hawkins](https://en.wikipedia.org;/wiki/Jeff_Hawkins) (2021)

Unlike his previous book "On Intelligence" where a lot of detail is given to explain the theory presented, this book spends significantly less space to do that (only about a third of the book deals directly with it, and a good chunk of it is rephrasing of ideas in "On Intelligence"). Instead, it refers interested readers to the scientific papers written by the author and his colleagues at [Numenta](https://numenta.com/). However, here are the three major ideas that the book introduces:

+ The brain learns models of the world to be able to solve problems.
+ The brain learns not one but thousands of such models (e.g., a single object has not one but dozens of complementary models and uses a voting mechanism to unify their predictions into a single one.)
+ The brain uses "reference frames" to build such models. Both tangible and intangible objects are learned using reference frames.

Similarly to "On Intelligence", the book is very well written for a lay audience, and provides enough examples and explanations for the core ideas. If you're looking for more concrete details, you'll definitely need to read the scientific papers and other referenced material in the book.

#### [AI: A Guide for Thinking Humans](https://www.goodreads.com/book/show/43565360-artificial-intelligence) 
📖 by [Melanie Mitchell](https://melaniemitchell.me/) (2019)

The book is a quick but detailed tour for the layperson who's curious and intrigued by Artificial Intelligence. The author takes a critical look at some of the most important developments in the last decade, delving into enough detail to expose the limitations that are often overlooked in popular science publications. The author also reflects on what is missing in state-of-the-art AI technologies that prevents them from potentially achieving human-level intelligence. An important read to dispel myths and see beyond the hype that's been prevalent in many circles around AI.

#### [MIT Artificial Intelligence](https://www.youtube.com/playlist?list=PLUl4u3cNGP63gFHB6xb-kVBiQHYe_4hSi)
💯 📺 by [Patrick Winston](https://en.wikipedia.org/wiki/Patrick_Winston) (2010)

A series of lectures on general AI concepts, including reasoning, problem solving, search in problem spaces, cognitive architectures, probabilistic inference, among others. Even though the topics covered can be found in other similar books and courses, what makes this course special is Patrick's clear exposition, and his particular focus on key ideas and insights in each topic.

#### [The AI Podcast](https://lexfridman.com/podcast/)
📺 by [Lex Fridman](https://lexfridman.com/) (2015)

This podcast started as a series of conversations with some renowned AI/ML researchers (each episode is typically 2 hours long), but over time has expanded to related (and sometimes not so related) topics and themes. Guests include well-known physicists, mathematicians, economists, neuroscientists, etc. The content is not very technical, but from time to time the conversations can be hard to follow unless one has some prerequisite knowledge.

[🔙 to Contents](#contents)

## General Machine Learning
#### [Learning from Data](https://work.caltech.edu/telecourse) 
💯 📺 📖 by [Yaser Abu-Mostafa](https://en.wikipedia.org/wiki/Yaser_Abu-Mostafa) (2012)

An introduction to ML with a strong focus on providing a conceptual and theoretical framework for the subject. It's an excellent complement to other courses which provide practical tools for machine learning but fail to explain in sufficient detail the conceptual underpinnings.

#### [Mathematics for Machine Learning](https://mml-book.github.io/)
📖 by [Marc Peter Deisenroth](https://deisenroth.cc/), [A. Aldo Faisal](https://www.imperial.ac.uk/people/a.faisal), and [Cheng Soon Ong](http://www.ong-home.my/) (2020)

An introduction to the mathematical tools most commonly used in ML/AI. Though it's possible to understand a lot of things in ML/AI without deep knowledge in mathematics, I believe that a solid understanding of these mathematical tools can be very valuable for any practitioner, and indispensable for researchers looking to build their own models or improve the state of the art. 

#### [An Introduction to Statistical Learning](https://www.statlearning.com/)
📖 by [Gareth James](http://faculty.marshall.usc.edu/gareth-james/), [Daniela Witten](https://www.danielawitten.com/), [Travor Hastie](https://web.stanford.edu/~hastie/), and [Rob Tibshirani](http://statweb.stanford.edu/~tibs/) (2021)

The book provides an accessible overview of the field of statistical learning, an essential toolset for making sense of the vast and complex data sets that have emerged in various fields of science. It presents some of the most important modeling and prediction techniques, along with relevant applications. Topics include linear regression, classification, resampling methods, shrinkage approaches, tree-based methods, support vector machines, clustering, and more.

#### [Intuitive Machine Learning](https://www.youtube.com/c/IntuitiveMachineLearning)
📺 by [Intuitive Machine Learning](https://twitter.com/intuitiveml) (2020)

One of the best resources for concise introductions to various topics in ML I've found so far. In just a few minutes, it summarizes topics that other people take half an hour or more to explain. The key to doing this is that the author focuses on key ideas, uses animations to improve visual communication, and omits unnecessary detail for an introduction. Beware you won't necessarily understand a topic deeply after watching a video, but you will have a good conceptual framework so more thorough explanations make absolute sense.

#### [Papers with Code](https://paperswithcode.com/)
📰 by [Facebook AI Research](https://ai.facebook.com/) (2018)

Papers with Code was created with the simple idea of helping the community track newly published machine learning papers with source code and quickly understand the current state of the art. It organizes a lot of the papers published in the field, providing summaries and related resources. Although it's sponsored by Facebook AI Research, it is an open community project.

#### [Papers Daily](https://papers.labml.ai/papers/daily)
📰 by [labml.ai](https://labml.ai/) (2020)

Papers Daily tracks recent and trending research papers in machine learning, aggregating comments from social media platforms (including Twitter, Reddit, and HackerNews) where people are talking about each paper.

#### [Distill](https://distill.pub/)
💯 📰 by [Chris Olah](https://colah.github.io/), [Yoshua Bengio](http://www.iro.umontreal.ca/~bengioy/yoshua_en/index.html), [Ian Goodfellow](http://www.iangoodfellow.com/) and [others](https://distill.pub/about) (2016)

Distill opens a venue for publications in ML that take advantage of all the resources the web has to offer: interactive visualizations, animations, full color, audio and video. As the creators explain: _"Machine learning will fundamentally change how humans and computers interact. It’s important to make those techniques transparent, so we can understand and safely control how they work. Distill will provide a platform for vividly illustrating these ideas."_ With a strong emphasis on very clear communication, it is an excellent preamble to reading more terse, but often obtuse, literature in ML.

[🔙 to Contents](#contents)

## Deep Learning
#### [Deep Learning for Coders](https://course.fast.ai/)
💯 📺 📖 by [FastAI](https://www.fast.ai/) (2020)

This is a course on Deep Learning that follows a non-traditional approach to the subject, deemed more suitable for coders or less mathematically-inclined people. It starts by giving you the tools to build models right away instead of making you go through a lot of theory and concepts before you can see a model in action. Once you've gained a high-level appreciation of Deep Learning, it then gradually unveils more and more details of the underlying machinery building up to a full nuts-and-bolts understanding of the subject.

#### [Heroes of Deep Learning](https://youtube.com/playlist?list=PLkDaE6sCZn6FcbHlDzbVzf3TVgxzxK7lr)
📺 by [Deep Learning AI](https://www.deeplearning.ai/) (2017)

A series of relatively short interviews by [Andrew Ng](https://en.wikipedia.org/wiki/Andrew_Ng) with various leading researchers in the field of machine learning. This is not really a technical resource, but I think it's interesting to hear the stories on how they got started, what ideas they've pursued and are currently pursuing, as well as their thoughts on current AI/ML trends and research.

#### [Introduction to Deep Learning MIT](https://www.youtube.com/playlist?list=PLtBw6njQRU-rwp5__7C0oIVt26ZgjG9NI)
💯 📺 by [MIT 6.S191](http://introtodeeplearning.com/) (2021)

An introductory series of lectures on Deep Learning. Even though it doesn't assume much prior knowledge on ML, it covers a lot of ground but without going into deep detail. Emphasis is put on real-world applications and presentation of high-level ideas, models and techniques (including its limitations), going from the classic all the way to the state of the art. Think of it as a very well-designed, comprehensive tour of modern Deep Learning, which can serve as a map for you to go out and explore in much more detail whatever grabs your attention.

[🔙 to Contents](#contents)

## Natural Language Processing
#### [A Code-First Introduction to NLP](https://www.fast.ai/2019/07/08/fastai-nlp/)
📺 by [Fast AI](https://www.fast.ai/) (2020)

From the creators of [Deep Learning for Coders](https://course.fast.ai/), this course follows the same philosophy of that foundational course. It teaches a blend of traditional NLP topics (including regex, SVD, naive bayes, tokenization) and recent neural network approaches (including RNNs, seq2seq, attention, and the transformer architecture), as well as addressing urgent ethical issues, such as bias and disinformation. Topics can be watched in any order. 

[🔙 to Contents](#contents)

## Philosophy of Mind
#### [Gödel, Escher, Bach -- an Eternal Golden Braid](https://en.wikipedia.org/wiki/G%C3%B6del,_Escher,_Bach) 
💯 📖 by [Douglas Hofstadter](https://en.wikipedia.org/wiki/Douglas_Hofstadter) (1979)

The book discusses how it is that animate beings can come out of inanimate matter; what is a self, and how can a self come out of stuff that is as selfless as a stone or a puddle. It also discusses self-reference and formal rules, isomorphism, what it means to communicate, how knowledge can be represented and stored, the methods and limitations of symbolic representation, and even the fundamental notion of "meaning" itself.

#### [The Society of Mind](https://en.wikipedia.org/wiki/Society_of_Mind)
📖 by [Marvin Minsky](https://en.wikipedia.org/wiki/Marvin_Minsky) (1986)

The book presents a theory of how the mind may work, focusing on the conceptual level and without making reference to the underlying substrate (i.e., neurons). The author develops theories about how processes such as language, memory, and learning work, and also covers concepts such as consciousness, the sense of self, and free will.

#### [I Am a Strange Loop](https://en.wikipedia.org/wiki/I_Am_a_Strange_Loop)
📖 by [Douglas Hofstadter](https://en.wikipedia.org/wiki/Douglas_Hofstadter) (2007)

Although "Gödel, Escher, Bach" (a.k.a. GEB) enjoyed great success--having even won a Pulitzer price--and inspired many future researchers on AI, ML, complex systems, etc., the author lamented in later years that many people seemed to have missed what he considered the central theme in his book. Hofstadter sought to remedy that in this new book by focusing on and expounding on that central theme, which he summarized as _"GEB is a very personal attempt to say how it is that animate beings can come out of inanimate matter. What is a self, and how can a self come out of stuff that is as selfless as a stone or a puddle?"_.

#### [Closer to Truth](https://www.youtube.com/c/CloserToTruthTV/about)
📺 by [Robert Lawrence Kuhn](https://en.wikipedia.org/wiki/Robert_Lawrence_Kuhn) (2020)

A series of interviews on the Cosmos, Consciousness and Meaning. It features leading philosophers and scientists exploring humanity's deepest questions. While its scope is not entirely in the realm of AI/ML or PoM, it does touch upon PoM and neuroscience in many of its episodes (e.g., the interviews with Marvin Minsky on brains and the nature of intelligence are quite interesting.)

[🔙 to Contents](#contents)

## Appendix
#### [Free Online Library](https://archive.org/details/inlibrary)
:electron: 📖 by [Internet Archive](https://archive.org/)

A great resource to access books that are very expensive or difficult to acquire through other channels. It features a vast collection of books from many disciplines. They can be accessed online (and in some cases downloaded) for up to two weeks at a time. It's also a great resource to decide if a book is worth buying.

[🔙 to Contents](#contents)
