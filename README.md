# Automated essay scoring tool for the Russian Unified State Exam preparation and assessment

*Can automated essay scoring be used to improve teaching and assessment practices in teaching writing in English as a foreign language to Russian-speaking students?*

*My aspiration is to design an automated essay scoring tool for students and teachers of English as a foreign language, which can potentially be developed into a nationwide exam assessment platform, bringing together computational linguistics and empirical educational science to improve teaching and assessment practices and promote equality in education.*

For the past 8 years I have been working as an English language instructor at a university (teaching English language majors) and a private language school (providing tutoring for secondary and high school students) in a remote region of Russia. Alongside teaching, I worked as a Secondary Education Unified State Exam (USE) Assessor within the Regional Examining Board for 5 years. 

Both as a teacher and an assessor I observed difficulties in teaching written speech in English as a foreign language and grading it at final exams. 

Here are some of my observations:

### A teacher’s perspective

Written speech is often overlooked in secondary education language training because it is challenging, time-consuming and does not appear as practically important as other language skills for the majority of students. However, in the national exam (USE) in the English language, writing (a personal letter and an argumentative essay) contributes a considerable part of the grade and is a decisive factor in the access to higher education.

Although writing a personal letter is manageable for language learners with little or no special preparation, the skill of essay writing is a lot more challenging since it requites extended outlook, critical thinking and good command of the language. 

Despite the extensive research and materials on teaching writing to Russian students, few secondary school teachers are able to use them because of poor training or heavy workload, and there are no computer-based or Internet-based writing feedback tools for Russian-speaking learners. 

Thus, school-leavers hoping for high scores in their final exams have to rely on tutoring outside school, while less privileged students are left out. 

### An assessor’s perspective

The Unified State Exam (USE) in foreign languages was introduced in 2009. It is a nation-wide exam which serves both as a school-leaving and an entrance examination to universities.

Its positive effect on higher education opportunities equality is hard to overestimate, since it sets a national standard and gives an opportunity to school-leavers from remote regions to compete for places in top Russian universities.

Since its establishment, the USE has undergone substantial changes and improvements. However, it still arouses criticism, and open-ended, human-graded writing tasks are a particular point of controversy.  

Each exam paper is graded by two assessors anonymously and independently, and in case the difference in their grade is greater than 2 points, then the paper is assessed by the third rater who gives the final grade. 

In spite of all the effort put into developing assessment guidelines (which are holistic in character and can still be interpreted ambiguously) and training experts (the training system is very formal in character), there is still a lack of assessment uniformity. The situation is made worse by imperfections of the assessors themselves: their qualification (which varies greatly across the country), personal traits (e.g. empathy level), rater fatigue and others. As a result, the discrepancy percentage in my region (according to annual reports by the Regional Examining Board) is up to 30%. 

A possible solution to the problem would be to create a tool to facilitate assessment which could ensure uniformity on certain criteria.

### Possible solution - Automated essay scoring tool

My idea is to create an automated essay scoring tool which could (1) ease the workload and make up for teachers' lack of training, (2) provide a self-learning tool for less privileged students, (3) provide training opportunities for exam raters, (4) prospectively be used as a part of the national examination assessment system. 

The tool should have the following functions:

1. Score essays on the criteria including vocabulary use, grammar, spelling and punctuation mistakes.

2. Generate feedback on what types of mistakes were made by the student in the listed criteria and provide guidelines for revision.

3. Score the level of language complexity according to the Common European Framework of Reference.

4. Check the appropriacy of the use of cohesive ties and generate feedback on mistakes and misuses.

5. Give preliminary feedback on cohesion and topical relevance based on pre-computed prompts and word embeddings.

### A programmer’s perspective

When I got the idea of addressing computational linguistics and natural language processing to tackle the described problem, I was overwhelmed at the heated debate going on around AES. 

I do not believe that an automated scoring tool can completely replace a human rater, but I really hope that such a tool could benefit all the parties involved.
However, being new to CL and NLP, I find it difficult to see to which extent my idea is feasible. 

Here is a list of articles I have studied and some comments on them, would be grateful if you could recommend more. 

1. Zixuan Ke, Vincent Ng. 2019. Automated Essay Scoring: A Survey of the State of the Art. Proceedings of the Twenty-Eighth International Joint Conference on Artificial Intelligence (IJCAI-19), pages 6300-6308.

2. Zarah Weiss, Anja Riemenschneider, Pauline Schroter, Detmar Meurers. 2019. Computationally Modeling the Impact of Task-Appropriate Language Complexity and Accuracy on Human Grading of German Essays. Association for Computational Linguistics: Proceedings of the Fourteenth Workshop on Innovative Use of NLP for Building Educational Applications, pages 30–45.

*Apparently, exam essay grading problems in Russia are partly shared by its German counterpart. Like in Germany, assessors in Russia are often biased towards content affected by non-construct essay features.* 

3. Bjorn Rudzewitz, Ramon Ziai, Kordula De Kuthy, Verena Moller, Florian Nuxoll, Detmar Meurers. 2018. Generating Feedback for English Foreign Language Exercises. Association for Computational Linguistics: Proceedings of the Thirteenth Workshop on Innovative Use of NLP for Building Educational Applications, pages 127–136.

*In my view, the described FeedBook project providing automated formative feedback as a breakthrough in terms of automated feedback quality.* 

4. Stig Johan Berggren, Taraka Rama, Lilja Øvrelid. 2019. Regression or classification? Automated Essay Scoring for Norwegian. Association for Computational Linguistics: Proceedings of the Thirteenth Workshop on Innovative Use of NLP for Building Educational Applications, pages 92-102.

5. Farah Nadeem, Huy Nguyen, Yang Liu, and Mari Ostendorf. 2019. Automated Essay Scoring with Discourse-Aware Neural Models. Association for Computational Linguistics: Proceedings of the Thirteenth Workshop on Innovative Use of NLP for Building Educational Applications, pages 484-493.
