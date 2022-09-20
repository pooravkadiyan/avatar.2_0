# Idea

> **There are only about 250 certified sign language interpreters in India, translating for a deaf population of between 1.8 million and 7 million.**

> **Most of the sign-language users face difficulty in even reading the normal languages we use, so just making information or instructions in available in text doesn't solve the problem**

> **It is estimated that by 2050 over 700 million people – or one in every ten people – will have disabling hearing loss.***

## Background

- Mutism is typically understood as a person's inability to speak. It is estimated that one in every 1,000 school-age children are affected by mutism. And in most cases, only sign language comes to resort for them.

- Deafness is hearing loss that precludes a person from understanding spoken language. Over 5% of the world’s population – or 430 million people – require rehabilitation to address their ‘disabling’ hearing loss (432 million adults and 34 million children). It is estimated that by 2050 over 700 million people – or one in every ten people – will have disabling hearing loss.

- Deaf-Mute are those who could neither understand spoken language nor express them.

- Through things have changed a lot now, YouTube’s auto-subtitle feature and Courser’s transcript feature, lip reading, neurochips have made life much more easier for the mute and deaf. But despite of these technological advancements and alternatives, the use of sign language is prominent among these specially abled people. 

- There are around 300 sign languages with different dialects and versions and around 70 million people use sign language today. So, translation of sign language holds an important role if we want to provide equal opportunity for these people.



## Our Proposal

The deaf community has long been underserved by businesses due to the difficulty of communication. In particular, questions or concerns about products and services can often go unheard. Our project seeks to change that by proposing **a virtual avatar that can communicate with deaf customers and provide them with the assistance they need.** The avatar would be able to sign, as well as listen and respond to questions using a knowledge base of common questions and information that could be accessed and utilised by the process of information extraction and text generation. By providing deaf customers with a means of communication, businesses would be able to better **serve this huge underserved population**.

**In simple words, a virtual avatar who is fluent in sign language as well our normal languages like English, Hindi and Gujarati; and could communicate with deaf customers and resolve their quesies.**

![Avatar Image](https://github.com/pooravkadiyan/avatar.2_0/blob/main/idea/avatar_image.png)

## Implementation 
The communication model would have two parts:
- Understanding the input : Involves taking input in sign language and translate it into written representation of a language humans understand, preferably English. And finding relevant text around it or previous similar answers to the questions using a knowledge extraction algorithm. 

- Providing relevant output : This would be done through a set of models like a "Knowledge discovery Model", "Response generation" based on transfer learning from language models like GPT-3 and followed by translation of the text to sign language using an "T2SL Model".

![Avatar Image](https://github.com/pooravkadiyan/avatar.2_0/blob/main/idea/diagram.png)


## Potential Problems and Solutions

- It could easily answer generic questions around the financial services and products like "How much time does it take to get a credit card?" but resolving personal queries and processing a loan application would be difficult to accomplish with higher accuracy. : In order to solve this, we could create our own dataset annotated by humans.

- Multiple ML models and processes would be part of this communication system, hence an error from a single part/model will compound in later stages and processes causing trouble : We could try training a single model in end-to-end fashion.

## Why we

We already have a dataset of Indian Sign Language collected from institutions that teach sign language. 

## Fact References

[1]Muteness - Wikipedia. (2022). Retrieved 27 July 2022, from https://en.wikipedia.org/wiki/Muteness
What percentage of world population is mute? – AnswersToAll. (2019). Retrieved 27 July 2022, from https://answer-to-all.com/technology/what-percentage-of-world-population-is-mute/

[2]Deafness and hearing loss. (2021). Retrieved 27 July 2022, from https://www.who.int/news-room/fact-sheets/detail/deafness-and-hearing-loss#:~:text=Over%205%25%20of%20the%20world's,will%20have%20disabling%20hearing%20loss

[3]Deaf-mute - Wikipedia. (2022). Retrieved 27 July 2022, from https://en.wikipedia.org/wiki/Deaf-mute

[4]With a deaf community of millions, hearing India is only just beginning to sign(2017). Retrieved 27 July 2022, from https://. theworld.org/stories/2017-01-04/deaf-community-millions-hearing-india-only-just-beginning-sign



