# deep-learning

### Chapter 1 - Introduction

###### deep learning

This book is about a solution to these more intuitive problems. This solution is to allow computers to learn from experience and understand the world in terms of a hierarchy of concepts, with each concept defined through its relation to simpler concepts. By gathering knowledge from experience, this approach avoids the need for human operators to formally specify all the knowledge that the computer needs. The hierarchy of concepts enables the computer to learn complicated concepts by building them out of simpler ones. If we draw a graph showing how these concepts are built on top of each other, the graph is deep, with many layers. For this reason, we call this approach to AI **deep learning**.

###### Knowledge Base approach 

hard-code knowledge about the world in formal languages **+** logical inference

**Conclusion**: Not a good approach because "People struggle to devise formal rules with enough complexity to accurately describe the world."

###### Machine learning approach

Ability to acquire their own(AI system) knowledge, by extracting patterns from raw data.

###### logistic regression

Determin cesarean delivery

###### naive Bayes

Separate legitimate e-mail from spam e-mail

###### **representation** of the data

Cartesian coordinates vs. Polar coordinates

Logistic regression is used to recommend cesarean delivery; doctor tells the system several pieces of relevant information, such as the presence or absence of a uterine scar. Each piece of information included in the representation of the patient is known as a **feature**.

###### What if it's difficult to know what features should be extracted?

Eg. Detect cars in photographs: only pixels and pixel seems not make sense in terms of feature.

Solution: **representation learning**

###### representation learning

input -> encoder -> eg. feature vector -> decoder -> back into the original format

###### factors of variation

When designing features or algorithms for learning features, our goal is usually to separate the **factors of variation** that explain the observed data.

**factors of variation** is the core thing that makes date points different from each other.

They may also exist as **constructs** in the human mind that provide useful simplifying explanations or inferred causes of the observed data.

When analyzing a speech recording, the **factors of variation** include the speaker’s age, their sex, their accent and the words they are speaking. When analyzing an image of a car, the **factors of variation** include the position of the car, its color, and the angle and brightness of the sun.

**Deep learning** solves this central problem in **representation learning** by introducing representations that are expressed in terms of other, simpler representations. (Multi-layer neuron network, eg. MNIST hand-written number)

###### 3 Part of this book

1> basic **mathematical** tools and machine learning **concepts**

2> most established deep learning **algorithms**, which are essentially solved technologies

3> more speculative ideas that are widely believed to be important for **future** research in deep learning

(Skip from 1.2)