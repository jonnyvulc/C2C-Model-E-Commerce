# C2C-Model-E-Commerce

Hindawi
Mobile Information Systems
Volume 2022, Article ID 4820393, 10 pages https://doi.org/10.1155/2022/4820393
Research Article
C2C Model E-Commerce Credit Evaluation Model Based on Artificial Intelligence
Wei Mu1 and HePing Ding 1,2
1College of Business, Suzhou University, Suzhou 234000, Anhui, China
2Center for International Education, Philippine Christian University, Manila 1004, Philippines
Correspondence should be addressed to HePing Ding; dingheping@ahszu.edu.cn
Received 26 May 2022; Accepted 5 August 2022; Published 19 September 2022
Academic Editor: Imran Shafique Ansari
Copyright © 2022 Wei Mu and HePing Ding. This is an open access article distributed under the Creative Commons Attribution License, which permits unrestricted use, distribution, and reproduction in any medium, provided the original work is properly cited.
The development of network computer technology and artificial intelligence technology promotes the generation of software agents. However, online shopping has inherent information asymmetry due to the anonymity and liquidity of C2C (Customer to Customer) transactions. In the virtual environment, buyers cannot see the physical products, and they do not experience online shopping in person. They can only select products through the seller’s pictures and descriptions. After payment, there may be some problems, such as sending the wrong product, the seller does not deliver the goods after receiving the goods, or the seller does not receive the payment after delivery, etc. Therefore, the credit problem is the bottleneck for the development of online shopping business. Therefore, in order to ensure the transaction security of buyers and sellers, major C2C online trading platforms at home and abroad have established a credit evaluation mechanism. However, due to the reliability of e-commerce technology, the legal environment of e-commerce, the ethical environment of e-commerce, and the problems of existing credit evaluation indicators. The development of e-commerce in China is very slow. Therefore, actively exploring the credit model of Chinese e-commerce is of great significance to promoting the development of Chinese market economy. In this paper, AI technology analyzes the credit evaluation management method of C2C e-commerce website for transaction participants. This paper summarizes some key factors that affect the estab- lishment of C2C credit, and further finds that there are some problems in the credit evaluation model involved in the e-commerce process. These problems stem from the inability to properly deal with the current development of e-commerce in China. There are problems with its evaluation system and honest transaction process. In order to better promote the development of e-commerce, in view of the above problems, this paper proposes a new model of C2C e-commerce credit system based on the game theory model of e-commerce buyers and sellers of AI technology, and further improves the evaluation model and related measures to completely solve the problem. Credit value generally shows a growth trend, but the trend is not obvious.
1. Introduction
Although C2C online shopping is convenient, fast, time- saving and economical, and maintains the momentum of vigorous development, due to the anonymity, high risk, information asymmetry, and other characteristics of C2C e-commerce, many netizens are not satisfied with their shopping safety and merchants’ credit. Doubt arises, the willingness of online shopping is not very strong, which limits the development and popularization of C2C e-com- merce. At present, there are two main modes of online retail market [1]: B2C mode and C2C mode. Different from the
online shopping market in foreign countries [2], in China, both in terms of transaction amount and user scale, C2C shopping websites are ahead of B2C shopping websites [3]. In the first half of 2011, 8% of the Internet users encountered consumer fraud on the Internet [4], and the size of this group reached 38.8 million people. This will greatly affect the health and rapid development of C2C e-commerce in China [5]. This is because in the transaction of C2C e-commerce, its trading platform is based on virtual network media [6], and the participants of both parties are individuals, subject to time and space constraints [7], the buyers and sellers cannot meet, participants can also register and trade anonymously,

2
Mobile Information Systems
which makes C2C e-commerce exist many uncertainties in the transaction process [8], making it face many credit risks, such as counterfeit and inferior commodities, credit speculation, false transactions, and other illegal acts occur frequently. Therefore, in order to reduce and overcome the risks of C2C e-commerce transactions and promote honest transactions, the credit security of online transactions has become one of the important topics of current research [9]. The establishment of a reliable credit evaluation model can effectively restrain the behavior of transaction entities, optimize the e-commerce environment, help improve the overall integrity level of e-commerce, and provide support for the formation and establishment of a social credit system.
Compared with traditional shopping, on the virtual C2C e-commerce trading platform, the most important problem that buyers worry about is the seller’s credit problem [10], because it is difficult for buyers of online shopping to evaluate the quality of goods before purchasing them, and the after-sales service of goods purchased online is extremely inconvenient [11]. If the goods do not meet their own needs again, the situation of returning and exchanging goods will be even more troublesome [12]. Then, this requires the buyer to obtain enough credit information of the seller through the network before the commodity transaction, so as to reduce the uncertainty of the transaction and avoid unnecessary trouble [13]. In the final analysis, the seller’s credit problem is the root of other problems. If the seller’s credit is good, then the quality of the goods, the description of the goods and the problems in the process of returning and exchanging goods can be well guaranteed [14].
The current credit evaluation model of C2C e-commerce trading platform is divided into two situations. One case is smooth shopping [15], if consumers are satisfied with the goods or services they buy, then confirm the receipt, evaluate, and complete the transaction [16]; the other case is non-smooth shopping, that is to say, the buyer is not satisfied with the goods or services he has bought, if he is not satisfied with the goods or services themselves, he needs to return the goods, if the goods are damaged in the logistics link [17], the buyer can exchange the goods. In the course of trading, when the buyer finds that the quality of the goods he purchases does not meet his own requirements, or does not match the information described by the seller on the website, he can negotiate with the seller [18] to return the goods. Credit evaluation model at this stage regards this return as cancellation of the transaction [19]. After the cancellation of the transaction, both sides of the transaction cannot evaluate each other, and the buyer has no way to remind other buyers who want to buy this commodity later. In such transactions, the biggest loss is the buyer, and for the seller, almost no impact [20]. Because the buyer chooses to return the goods and cannot give the seller evaluation [21], then this will not have a negative impact on the seller’s credit evaluation record [22], and if the buyer does not find such a problem, the seller will make considerable profits. Therefore, it is necessary to develop a suitable credit evaluation model [23] to help buyers find such sellers who want to obtain illegal profits [24].
In view of the existing C2C e-commerce credit evalu- ation model, the shortcomings and limitations of Taobao [25], this paper analyzes the current credit evaluation needs in the development of C2C e-commerce [26], builds a new
credit evaluation model, which includes the weight of transaction amount, the evaluation after return, the evalu- ation after exchange, the credit of the evaluator [27], and the timely validity of the difference evaluation. It is hoped that the new credit evaluation model will play a certain role in promoting the improvement of C2C e-commerce seller’s credit and the quality of goods and services [28]. This paper analyses the credit evaluation management method of C2C e-commerce website to transaction participants [29] and summarizes some key factors affecting the establishment of C2C credit, further finds that there are some problems in the credit evaluation model involved in the process of e-com- merce. These problems arise from the inability to correctly deal with the current development of e-commerce in China. There are problems in its evaluation system and integrity trading process [30]. Even if shopping, but did not evaluate the buyer, for the seller’s credit does not have any impact.
2. Literature Review
There are many studies on the integrity of e-commerce abroad, and the same is true for domestic scholars. In the process of writing this article, the author has consulted the school library, NKI, Wanfang, and Longyuan, and has a lot of research materials on the integrity of e-commerce. Domestic scholars mainly focus on credit evaluation models, risks, measures to build trust mechanisms, and the disadvantages of third-party organizations in the development of e-commerce in China. In the literature on e-commerce integrity, there are many studies on e-commerce integrity technology. Song Guangxing pointed out in his research: through the construction of game models in e-commerce to further analyze the choice of buyers and sellers in online transactions and possible problems of integrity. And from the social, self-interest, and even psychological point of view to explore the reasons for the existence of these problems. Based on the analysis of these problems and reasons, it is concluded that only by building a credit management platform in a real sense can we really find measures to solve the lack of integrity. With the continuous popularization of personal computer applications and the continuous progress and ma- turity of Internet technology, e-commerce has a broad space for development, especially C2C e-commerce.
Compared with the research on integrity, there are relatively few studies on the management level of e-com- merce. Zou Xuebo, a research scholar of e-commerce in China, has done a lot of research on this aspect. Starting from the management of e-commerce, he discussed the management methods of credit model, real-name authen- tication of registered users and secure payment tools in the development of e-commerce, and introduced how to ensure the effective development of e-commerce from the man- agement methods. At the same time, many scholars have explored the reasons for the slow development of e-com- merce in China. In addition to technical factors, more scholars have introduced the lack of integrity. Wei Mingxia directly pointed out in his article that one of the direct reasons for the slow development of e-commerce in China is the lack of credit. The risk of credit makes consumers consider whether they really want to spend. Such

Mobile Information Systems
3
 Credit Evaluation Center
     Personal credit supervision
Platform credit rating
  bad records
Personal basic information
Transaction authenticity
 Third party validation
  Improving credit score
      considerations will affect the volume of online shopping transactions to a large extent, and then affect the profit- ability. Many scholars have studied the risks in e-commerce and online shopping. To some extent, there are great risks in e-commerce transactions, which include not only material risks but also personal privacy risks. Dong Dahai and Li Guanghui, famous economists in China, believe that the risks of online shopping affect consumers’ consumption. The existence of these risks will allow consumers to consider whether they really buy in the process of shopping, affecting the cost and sales rate of buyers. At present, there are some problems in the evaluation system of e-commerce and online shopping in China. The evaluation system here refers more to an effective mechanism for integrity supervision. Xiong Yuning pointed out the problem of honesty and credit supervision in the development of e-commerce in China in the study of evaluation systems. Although many e-com- merce transactions in China have this part of evaluation, it is still very difficult to implement it. In view of the existing problems, he explained them from the perspective of rele- vant laws of China and the supervision of the third platform.
There are many reasons for the problem of honesty and credit in the development of e-commerce. Some scholars think that the reason for this problem is the system problem, and some scholars think that it is the information problem. To explore the causes, Peng Liu, a well-known economist in China, pointed out that the root cause of the current problems in the development of e-commerce is the asymmetry of net- work information. In this paper, he specifically analyzed the current situation of online shopping and e-commerce devel- opment in China. On this basis, he explored the reasons from the perspective of asymmetric network information in the development of e-commerce. In order to solve these problems, he made a detailed study and explanation from the
organizational structure, credit policy, and credit management system of enterprise credit management. Through the above description, we can find that the current relevant experts and economists in China have some research on the integrity issues in the development of e-commerce in China. However, in the process of research, the research is limited to surface phe- nomena, and the depth of research is not up to the standard.
3. Research Method
3.1. Implementation Process in C2C Mode. Based on the characteristics of domestic C2C e-commerce and the problems mentioned in Section 2, the objective of this study is mainly to establish a new e-commerce credit rating system independent of various business platforms—two-way credit rating center. Its implementation process in C2C mode is shown in Figure 1 below. The detailed explanation is as follows: the two-way evaluation center mainly serves two major functions in the C2C model:
STEP 1: Collect personal credit information records provided by banking systems and third-party payment platforms.
STEP 2: Credit rating based on the transaction status of each C2C business platform.
STEP 3: Platforms like Taobao, Paipai, eBay, etc. all display their credit scores.
First, collect the personal credit information records provided by the banking system and the third-party payment platform, including identity authentication, personal basic information, personal economic status, personal credit records, and so on, then select and collate the information, and update it every 6 months, and finally form the relative
Refresh every six months
Verification or credit Information system
Figure 1: Implementation flow chart in C2C mode.
Transac -tion amount
User credit degree
Refresh every three months
  Display credit score
Dynamic scoring
  
4
Index Age
Gender
Education level
⎧⎪⎨ 1, work r4�⎪⎩m3/10,
Mobile Information Systems Table 1: Specific scoring criteria and explanatory tables of fuzzy membership functions and indicators for credit scoring.
 Evaluation function
Indicator score description
16–30 years old: 8 points
55–70 years old: 6 points Over 70 years old: 4 points
Female:2 Male:1
Doctor and above have 10 points, masters have 9 points, undergraduates have 8 points, colleges have 7 points, high schools have 6 points, junior high schools and below have 4 points.
State organs have 10 points, enterprises and institutions have 8 points, students and staff have 6 points and others have 4 points.
Consumption level affected by income level
First-tier cities have 10 points, second-tier cities have 8 points, third-tier cities have 6 points and fourth-tier cities have 4 points.
Scoring based on bank credit
credit score for sellers. Finally, Taobao, Paipai, eBay, and other platforms show their credit scores.
3.2. Personal Credit Information Rating. According to the construction of personal credit system in China and the characteristics of C2C e-commerce transaction subjects, and referring to the relatively mature personal credit evaluation index system abroad, seven indicators are selected for its credit evaluation index, including the following seven in- dicators: age, gender, education level, nature of work, monthly income, the city in which it is located, and bank credibility. The information of these credit indicators is mainly provided by websites, third-party payment regis- tration, and banks. The two-way evaluation center uses the fuzzy score matrix to automatically score the credit indi- cators. Fuzzy matrices are matrices used to represent fuzzy relationships. Applying the idea of membership function in fuzzy mathematics, this paper establishes the reliability function of the index, so as to ensure the continuity of the quantitative index score. The fuzzy membership function of each index and the specific scoring criteria and explanations of each index are shown in Table 1:
 ⎧⎪⎨ 1,
r1 � ⎪⎩ m1/10,
0,
31 ≤ m1 ≤ 55 other
m1 < 16
 r2 �􏼨1, ⎧⎪⎨ 1,
m2 �2 m2/2, m1�1
 Nature of
r3 � ⎪⎩ m3/10, 0,
m3 � 10
0 < m3 < 10 m1 � 0
m4 � 10
0 < m4 < 10 m4�0
  Monthly income
City
Bank credibility
0, ⎧⎪⎨ 1,
m5 ≥ 500
500 < m5 < 5000 m5 < 50
r5 � ⎪ (m5 − 500/5000 − 500)1/2 , ⎩ 0,
 ⎧⎪⎨ 1,
r6 � ⎪⎩ m6 /10,
0,
⎧⎪⎨ 1,
r7 � ⎪⎩ m6 /10,
0,
m6 � 10
0 < m6 < 10 m6 � 0
m7 > 70
20 < m7 > 70 m7 < 2
  static personal credit rating of buyers (sellers). For example, for sellers, according to the certification of registered merchants provided by third parties, the credit status and transaction status provided by banks and websites, a strict dynamic assessment is carried out, which is re-evaluated every 6 months, and divided into five grades, which are displayed and published on various platforms. The same is true for buyers, so as to provide a favorable basis and ref- erence for both sides of the transaction.
The second is the credit rating based on transaction for each C2C business platform. Because the traditional credit evaluation model uses the cumulative form of credit evalu- ation and shop evaluation, credit score is usually: 1 point for good reviews, 0 points for middle reviews, and −1 points for poor reviews. This scoring method is more general. Credit rating, also known as credit rating, is a kind of social in- termediary service, which will provide credit information for the society, or provide decision-making reference for the unit itself. There are some unreal ways to evaluate users and users, such as credit hype. Therefore, the two-way credit evaluation center adopts the dynamic store scoring method based on the transaction of each platform, adopts the multi-dimensional and multi-level scoring method, and implements the dynamic

Mobile Information Systems
5
     Determine the credit evaluation index score matrix:
u1 u2 u3
According to the weight analysis, the weight distribution matrix is w (0.1, 0.1, 0.1, 0.15, 0.25, 0.1, 0.2).
 r11 r12 ···r1n 
 
B􏰅wR (0.3, 0.15, 0.304, 0.08, 0). Then, add the credit value on each domain of each indicator to get the buyer’s initial credit score as shown in (3).
 r21 r22 ···r2n  r31 r32 ···r3n
 
N
T 􏰅 􏰆 bi 􏰅 (0.3 + 0.15 + 0.30 + 0.08 + 0) 􏰅 0.384. (3)
(1) Assuming V1􏰅(v ,v ,v ,v , v ,v ,v )􏰅(33,Fe
R􏰅􏰈r􏰇􏰅 u ij 7×n 4
r r ···r  41 42 4n
. 
u5 u6 u7
 r51 r52 · · · r5n  r61r62 · · · r6n
 
I􏰅1
3.3. Business Credit Information Rating. An hierarchy
analysis model is established for the evaluation index system and each rating factor as shown in Figure 2.
The weight is different from the general proportion. It not only reflects the percentage of a certain factor or indicator but also emphasizes the relative importance of the factor or indicator, and tends to contribute or im- portance. In this part, the most commonly used method is the analytic hierarchy process. In the process of deter- mining the weights, it is necessary to set the weights of the indicators at different levels. The concrete steps are as follows: First, according to the judgment scale (as shown in Table 2 below), a comparative index matrix is established.
The criterion judgment matrices are listed in Table 3 below.
r71 r72 ···r7n
11 12 13 14 15 16 17
male, un de rgra du ate, stu de nt3600, Nanchang, goo d), according to the scoring function table of the initial credit index, the evaluation matrix is obtained as shown in (2).
   0 0 1 0 0     1 0 0 0 0     0 0 0 0.8 0 
R􏰅00.6 0 00. (2)  
 0 0 0.816 0 0 
0 0.6 0 0 0 1 0 0 0 0
Figure 2: Hierarchical analysis model diagram.
Is the product genuine?
  Product factors
Is the product intact?
 Satisfaction Degree of Product Packaging
 Seller Description Compatibility
 Information factor
   Shop Dynamic Credit Scoring
Is the seller's description detailed?
 Is the seller delivering the goods correctly?
 Distribution factors
 Seller delivery speed
 Seller service attitude
  Service factor
Timeliness of Return and Exchange of
 Seller after-sales service

6
Mobile Information Systems
wi � (􏽑ni�1 aij)1/n,
w � [0.15, 0.27, 0.09, 0.07]T.
i � 1,2,...,n,
get
rij �⎪0.5, ⎪⎩ 0,
Comparedwithaj,aiismoveimportant, (7) a is more important than a .
2 4
68 46
24 22
ij
The matrix consisting of scoring values is A � (rij)m×n,
⎢⎡⎢
⎢
⎢ 1
⎢ 2 2 ⎢
⎥⎤⎥
where rij � 0.5, rij + rji � 1, the weight coefficient of index ai is shown in (8).
⎢ 1 1 ⎢ 4 2
⎥
⎢
⎢ ⎢ ⎢⎣ 1 1
⎥ ⎥⎦
8 6
⎥ 0.51 ⎥⎢⎡
⎥⎤ ⎢⎡ ⎥ ⎢
2.32 1.09 0.36 0.29
⎥⎤ ⎥
n 􏽐i�1 rij
n n 􏽐i�1 􏽐i�1 rij
⎥⎢ ⎥⎢ ⎥⎢ ⎥⎢ ⎥⎢ ⎥⎢⎣
0.27 ⎥ ⎢ ⎥ ⎢ ⎥ � ⎢ 0.09 ⎥ ⎢ ⎥⎦ ⎢⎣
⎥
wi �
,i�1,2,3,...,n. (8)
Table 2: Judgment scale and Scale meaning.
 Judgment scale
2
4
6
8
10
1, 3, 5, 7, 9
Seller credit evaluation
Product factor Information factor Distribution factor Service factor
Set:
A�
22
According to the product square root method
Scale meaning
It means that the equal importance of two elements in comparison
It means that the former is slightly more important than the latter. It means that the former is obviously more important than the latter. It means that the former is more important than the latter.
It means that the former is more important than the latter. Represents the median value of the above judgment.
  Table 3: Criteria judgment matrix table.
 Product factor
2 1/2 1/4 1/8
Information factor
4
2 1/2 1/6
Distribution factor
Service factor
 6 8 4 6 2 4 2 2
 2 4 ⎢ 1
68 46
24
⎥⎤⎥ ⎥
paper uses a relatively simple relative comparison method to obtain the weight value of each indicator. On this basis, the final evaluation ability is obtained by using fuzzy mathe- matics. Fuzzy mathematics, also known as fuzzy mathe- matics, is a mathematical theory and method for studying and dealing with fuzzy phenomena. The relative comparison method is one of subjective assignment methods, which is graded according to three-level scale and pairwise com- parison. If the score value is set as aij; then, the meaning of three-level scale is shown in (7).
⎪⎧ 1, Compared with a , a is move important, ⎪⎨ ji
⎢⎡⎢
⎢ 2 2 ⎢
⎢
⎥
⎥
⎥. (4) ⎥
 ⎥. (5) ⎥
(6)
Then, the consistency indicator of matrix A is CI � λmax − n/n − 1 � 0.026, when the matrix order is 4, its RI value is 0.9. Calculating the consistency ratio CR � CI/RI � 0.029 < 0.1 considers the consistency of the judgment matrix to be acceptable.
The specific process for the buyer’s dynamic credit evaluation is: Considering the small number of indicators affecting the buyer’s dynamic credit evaluation, in order to reduce the complexity of the comprehensive model, this
Then,
⎢
Aw � ⎢ 1 1
⎥ ⎥⎦
⎢
⎢ 4 2 ⎢
⎢⎣
⎥ 0.07 ⎥⎦
3.4. Credit Evaluation Model Based on Time Factor. The model considers that the validity of the buyer’s evaluation of the seller will change with time. Therefore, the model uses the method of adding time factor to modify the compre- hensive credit value, which is expressed as shown in (9), by a one-variable decreasing function.
C �f(Δt)�(Δt+1)−1. (9) t
Among them, Ct represents the time factor, and Δt is the difference between the time of trust evaluation and the time of evaluation.
On the basis of the model shown in (9), the credit rating of the seller’s evaluation is considered from the recom- mendation experience and direct experience. The compre- hensive evaluation model is shown in (10).
T�􏽘Ei ×Ctj +􏽘Ej ×Ctj ×Crj. (10)
1 1 8 6
1 n 􏽐n a w
λmax � 􏽘 j�1 ij ij �4.04.
 n i�1 wi

Mobile Information Systems
7
where T is the comprehensive evaluation of behavior i; Ctj is the decay factor over time; Ej is the comprehensive eval- uation of behavior j; Crj is the recommendation factor; and Ctj is its attenuation factor with time. After introducing a decreasing function about time, the model objectively transforms the historical credit integral. However, due to the lack of consideration of the amount of transactions, there is still a lack of prevention of credit speculation and other phenomena.
3.5. Given Initial Credit Value Credit Evaluation Model. In this model, the author divides three parts to construct the credit evaluation model of Internet merchants:
First, after considering the credit of the evaluator and the initial credit level, the author determines the weight of the current credit evaluator, as shown in (11).
C
WC 􏰅 . (11) TC
C is the credit level of the current evaluator, TC rep- resents the initial credit level provided by the website, and WC represents the credit weight of the current credit evaluator.
Secondly, the initial value provided by the system is introduced to determine the weight of the transaction volume.
v
WV􏰅 . (12) V
V denotes the original amount given by the system; V denotes the amount of the current transaction; WV is the evaluation level of the current transaction amount; and then takes the average value of the credit weight of the current credit evaluator and the weight of the transaction amount, after considering the weight value of the special transaction, calculates the current credit weight of the user, as shown in (13).
Credit degree
120 100 80 60
40
20
0 20
 W 􏰅 WC + WV, V2
r 􏰅 t(1 + w).
(13)
40 60
80 100 120 140 160 180 Number of buyers
Credit degree
Credit Ratio Considering Evaluation
Figure 3: Relationship between credit and buyer number. 120
 100 80 60 40
20 0
200 400 600 800 1000 1200 1400 1600 1800 Upper limit of transaction amount
Credit degree
Credit Ratio Considering Evaluation
Figure 4: Studies the relationship between maximum trading volume and credit.
transactions; and Ri represents the credit evaluation value at the ith time.
In this model, after introducing the actual credit value, the author synthetically considers the transaction amount and the credit credibility of the evaluator, obtains their weights, respectively, and revises the credit evaluation model according to the different nature of the product. This model provides a more accurate reference method for aggregation of credit values, but it does not consider the impact of transaction time on credit. For the rational recognition of artificial intelligence embodied by electronic agents, this anthropomorphism also provides a good guarantee for its users or design manufacturers and business service providers.
4. Analysis Result Discussion
4.1. The Relationship between Credit Ratio and Number of Buyers. The dotted line are two graphs that consider the overall evaluation rate of the buyer and not the overall
  Credit degree
 W represents the current user credit weight; t is the assessor credit value; and r is the weight value of special transactions. From this, a new credit evaluation model for Internet merchants is proposed, as shown in (14).
−1/i
r′􏰅􏰈1+e 􏰇∗r,
ii
R􏰅R +r′,
i i−1 i
(14) n −1/i
R 􏰅R +􏰆􏰈1+e 􏰇∗r. n0i
i􏰅0
ri represents the ith weighted feedback value of the evaluated person; and r′ represents the credit increment after the ith i
transaction. R0 represents the initial credit value of the evaluated person; Ri−1 represents the credit rating of i − 1

8
Mobile Information Systems
120 100 80 60
40
20 0
Figure 5: The relationship between credit and non-evaluation.
impact of evaluation rate on credit value calculation is still very big.
4.3. Research on the Relationship between Credit and Non- Evaluation Rate. The credit curve changes as shown in Figure 5.
4.4. Study on the Curve Relation between Credit Ratio and the Number of Transactions. In this group of simulation, the number of transactions will be set as a variable, through the changes in the number of transactions, to observe the change trend of credit value. Comparisons between calculated and non-calculated evaluation rates are still made. The credit curve is shown in Figure 6.
The trends of the two curves are still consistent. Credit value generally shows a growth trend, but the trend is not obvious. There will be credit decline in the process, which proves that the credit algorithm in this paper does not increase or increase singly, but changes according to the actual data. First of all, the growth of the two curves shows that with more and more transactions, more and more complex situations, the value of credit in general is cumulative increase. This fully proves that in the real trading platform, credit calculation without considering the evaluation rate is a huge loophole.
5. Conclusion
The main research object of this paper is the credit evalu- ation model of C2C CBEC (CBEC) transaction platform based on AI technology. On the one hand, the advantages and disadvantages of the existing e-commerce credit eval- uation models are systematically analyzed. On the other hand, the simulation environment can be constructed with reference to the transaction behavior of users in the P2P network.
Aiming at the possible fraudulent transaction behavior of sellers, the experiment changed the scoring method based on the existing model, adopted a two-stage scoring, and introduced a price impact factor, a time decay factor and an increased penalty mechanism. It can be seen from the ex- perimental results that the improved model not only en- hances the ability to identify malicious sellers but also enhances the ability to restrain malicious sellers. Experi- ments show that buyer’s behavior interacts with e-commerce market. If the buyer’s behavior does not follow certain reasonable rules, it will affect the healthy development of the entire market. Buyers’ fake reviews, such as malicious negative reviews or colluding with sellers to make positive reviews, will affect the credit rating model used to calculate the seller’s credit score and disrupt the market order.
This paper makes a rational analysis of the advantages and disadvantages of the current C2C e-commerce credit platform as a whole. After analyzing the drawbacks, this paper focuses on the starting point of the AI credit algo- rithm, which can be improved by reading literature and consulting data. Afterward, the paper synthesizes these improvements, conducts a comprehensive analysis, and finds improved algorithms that combine them. In this paper,
 Credit degree
 Credit degree
120 100 80 60
40
20 0
0 0.1 0.15 0.2 0.3 0.35 0.4 0.45 0.5 Buyers do not rate
Credit degree
Credit Ratio Considering Evaluation
0 10 20 30 40 50 60 70 80 Transaction times
Credit degree
Credit Ratio Considering Evaluation
Figure 6: Curve relationship between credit and number of transactions.
evaluation rate of the buyer. Relationship between credit and buyer number is shown in Figure 3.
That is to say, the buyer’s evaluation rate can affect the calculation of credit in the actual situation. In the actual e-commerce website, the default treatment of the buyer’s non-evaluation is the high praise. In this paper, the buyer’s evaluation rate is taken into account in the calculation of credit. That is to say, even if shopping, but did not evaluate the buyer, for the seller’s credit does not have any impact. This is closer to the true credit value. It proves that it is very desirable to calculate the buyer evaluation rate in this paper.
4.2. Study on the Relationship between Maximum Transaction Volume and Credit. Figure 4 shows two curves that vary smoothly but differ widely. From this, we can see that: first, the change of the upper limit of transaction amount has little influence on the credit algorithm of the C2C e-commerce credit evaluation model studied in this paper.
Secondly, the huge credit value gap between the solid line and the dashed line can also show that considering the

Mobile Information Systems
9
the calculation method of credit has been repeatedly scru- tinized by the author. At the same time, the simulation analysis of the new algorithm fully proves the scientificity and feasibility of the proposed algorithm. Finally, several groups of parameters of the new credit algorithm are compared and simulated by MATLAB simulation. MAT- LAB is used in data analysis, wireless communication, deep learning, image processing and computer vision, signal processing, quantitative finance and risk management, ro- botics, control systems, etc. It has been proved by simulation that factors such as the number of buyers, the upper limit of transaction amount, and the evaluation rate play a very important role in credit calculation. Furthermore, this paper recognizes that all of these objective factors are included in the seller’s credit calculation.
Finally, by changing the tolerance value and attenuation coefficient of the gap, several sets of comparison graphs are simulated. The results show that the settings of these two parameters have no effect on the credit algorithm of the C2C credit model studied in this paper. This also proves the objectivity of the algorithm studied in this paper. Through the analysis of multiple sets of simulation comparison charts, the AI credit algorithm in this paper has good performance, and can play a very high reference value for the improve- ment of the future C2C credit evaluation model. Due to the complexity of the research subjects involved, the research in this paper has some limitations.
6. Suggestion
Based on the results of this simulation experiment, the author believes that from the perspective of cross-border e-commerce (CBEC) platform, the methods to solve the credit problems in CBEC can be carried out from the fol- lowing aspects:
(1) Improve the access threshold of sellers. In the tra- ditional C2C e-commerce platform, the entry threshold is low, and the cost of the seller’s regis- tration is very low. As a result, the seller can continue to trade when the credit rating is too low due to continuous fraud. For C2C CBEC, the order amount involved is larger, but the buyer knows less about the information of the goods. Therefore, improving the conditions for the seller to enter the market can reduce the transaction risk of the buyer from the source. CBEC refers to the Global Cross-Border e-commerce Consortium.
(2) Update the credit evaluation model in time with the advanced theoretical research results and technical means. At present, the effectiveness of credit eval- uation models in solving credit problems in virtual environments has been proved by theoretical anal- ysis and simulation experiments, respectively. However, there are many factors affecting credit. Credit evaluation is a very complex process. With the development of C2C CBEC, the form of credit problems may also change. At present, with the improvement of computer performance, machine
learning and other methods have been applied in business activities, and show good business value. In order to improve the accuracy of credit evaluation models and to cope with new credit risks in time, we should use new theory and technology flexibly to update credit evaluation models in time.
(3) Establish a credit assessment mechanism for buyers. The results of the experiment can fully explain the impact of buyer’s behavior on credit evaluation. Because of the strong interaction between buyer and seller in C2C CBEC market, the malicious evaluation of buyer damages not only the interests of honest sellers but also their own interests indirectly, and ultimately has a great negative impact on the overall market order. Therefore, when solving the credit problem of C2C CBEC, we need to consider not only the behavior of malicious sellers but also the behavior of malicious buyers. All e-commerce platforms should establish a set of evaluation mechanisms for buyer’s credit on the basis of existing data.
In order to solve the credit problem of C2C CBEC, we need not only the constraints of credit evaluation model and the management and operation ability of e-commerce platforms but also the support of government and society. For example,
Enhance cooperation between customs and other de- partments. In addition to customs departments, CBEC import and export also involves a number of government departments. If we can strengthen communication and cooperation between government departments, it will be conducive to reducing the cost of supervision and improving the effectiveness of supervision. In addition, if the customs department can cooperate with CBEC platform, it will help the platform to control commodities, achieve information exchange, and ensure the interests of buyers from the source.
Improve the social credit system, including personal credit, enterprise credit, government information disclosure, strengthen credit information database management, and accelerate the construction of third-party credit agencies. At present, each platform is independent of the user’s rating, which cannot describe the user’s credit rating comprehen- sively and reliably. At the same time, it also causes infor- mation waste. The improvement of social credit system can not only support the development of C2C CBEC but also help the development of various industries.
Improve the relevant laws and regulations, smooth consumer complaints channels. Now Taobao and other large CBEC platforms have strengthened the personal review of cross-border business to ensure that sellers’ goods come from overseas. For CBEC, the authenticity of sellers’ identity has a certain reference role in ensuring the authenticity of goods. However, e-commerce platforms cannot check whether the seller’s goods are true one by one. In the current cross-border C2C e-commerce, there are many incidents in which buyers cannot obtain after-sales services or complaints are not available. If relevant laws and regulations can be perfected and consumers have channels for complaints, timely pun- ishment of fraudulent acts of sellers in transactions will be of great benefit to the development of cross-border C2C

10
Mobile Information Systems
e-commerce. The evaluation index system can be further improved. The C2C e-commerce environment and market are changing rapidly, and the index setting still needs to be further improved and perfected in practical application. The improved e-commerce credit evaluation model needs to be further improved and expanded, and more reasonable and feasible solutions should be put forward in practice.
Data Availability
No data were used to support this study.
Conflicts of Interest
The authors declare no potential conflicts of interest in this study.
Acknowledgments
This work was supported by Suzhou University Innovation Team Research on Rural E-Commerce Development, No. 2018kytd02.
References
[1] S. Ba, A. B. Whinston, and H. Zhang, “Building trust in online auction markets through an economic incentive mechanism,” Decision Support, vol. 35, 2003.
[2] K. B. Murray, “A test of services marketing theory: consumer information acquisition activities,” Journal of Marketing, vol. 55, 1991.
[3] S. Grazioli, “Deceived under target online. jarvenpaa,” Com- munications of the ACM, vol. 46, 2003.
[4] D. Gregg, “Reputation systems in reducing on line auction fraud,” International Journal of Electronic Commeree, 2006.
[5] R. Kauffman and A. W. Charles, “Running up the bid: modeling seller opportunism in Internet auctions,” The 2000 Americans Conference on Information Systems, Long Beach, California USA, 2000.
[6] I. Macinnes, “Causes of Disputes in Online Auctions,” Electronic Markets, vol. 15, no. 2, pp. 146–157, 2005.
[7] T. J. Strad and S. N. Ramaswami, “Trust worthinessin C2C online markets,” Communications of the ACM, vol. 45, no. 12, pp. 45–49, 2002.
[8] D. Chrysanthos, “Analyzing the Economic Efficiency of eBay- like Online Reputation Reporting Mechanisms,” Economical Comment, Association for Computing Machinery, Tampa, Florida, USA, 2001.
[9] L. Donna, P. Thomas, and M. P. Novak, “Building Consumer Trust in Online Environments: The Case for Information Privacy,” Communications of the ACM, 1998.
[10] B. Lee and B. Yoo, “Internalization of Electronic “Auction Market” and Information Asymmetry in Electronic Com- merce,” 11th Workshop on Information Systems and Eco- nomics (WISE 1999), Charlotte, NC, 1999.
[11] T. Beth, M. Borcherding, and B. Klein, “Valuation of trust in open networks,” Proceedings of the Third European Sympo- sium on Research in Computer Security, Springer, Berlin, Heidelberg, 1994.
[12] L. U. Glen, S. Fareena, and J. Q. willian, “Placing trust at the center of your Internet strategy,” Sloan Management Review, vol. 42, pp. 39–48, 2000.
[13] Z. Jingan and G. Xiane, “Trust Evaluation Model Based on Fuzzy Logic for C2C E-Commerce,” in Proceedings of the International Symposium on Information Engineering and Electronic Commerce, Ternopil, Ukraine, May 2009.
[14] J. C. Lu and J Liao, “E-Commerce Customer credit evaluation based on AHP,” in Proceedings of the Software Engineering and Service Sciences, Beijing, China, July 2010.
[15] D. H. Mcknight, C. J. Kacmar, and V. Choudhury, “Shifting Factors and the Ineffectiveness of Third Party Assurance Seals: A Two-Stage Model of Initial Trust in a Web Business,” Electronic Markets, vol. 14, no. 3, pp. 252–266, 2004.
[16] A. Josang and S. Hird, “Simulating the effect of reputation system markets,” Proceeding of the First International Con- ference on Trust Management, Springer, Berlin, Heidelberg, 2003.
[17] L. Mui, M. Mohtashemi, and A. Halberstadt, “A computa- tional model for trust and reputation,” in Proceedings of the 35th Hawaii International Conference on System Sciences, Big Island, HI, USA, January 2002.
[18] A. Josang and S. J. Knapskog, A Metric for Trusted Systems. . Global IT Security, Austrian Computer Society, Wien, Austria, 1998.
[19] A. Josang, “Trust-based decision making for electronic transactions,” Proceedings of the 4th Nordic Workshop on Secure Computer System(NORDSEC99), Citeseer, Princeton, New Jersey, USA, 1999.
[20] S. Kang, G. Yuanjing, and L. Chaohua, “The Model of Credit Evaluation in C2C E-Commerce,” in Proceedings of the In- formation Management and Engineering, Chengdu, China, April 2010.
[21] R. N. Bolton and J. H. Drew, “A multistage model of cus- tomers assessments of service quality and value,” Journal of Consumer Research, vol. 17, no. 4, p. 375, 1991.
[22] A. Josang, R. Ismail, and C. Boyd, “A survey of trust and reputation sys-tems for online service provision,” Decision Support, vol. 43, no. 2, pp. 618–44, 2007.
[23] L.CabralandA.Hortacsu,“Thedynamicsofsellerreputation: Theory and evidence from eBay,” NBER Working Paper Series, 2004.
[24] P. Resnick, R. Zeckhauser, E. Friedman, and K. Kuwabara, “Reputation systems,” Communications of the ACM, vol. 43, pp. 45–48, 2000.
[25] S. Ba and P. A. Pavlou, “Evidence of the effect of trust building technology in electronic markets: price premiums and buyer behavior,” MIS Quarterly, vol. 26, no. 3, p. 243, 2002.
[26] C. G. McDonald and V. C. J. Slawson, “Reputation in an Internet Auction Market,” Economic Inquiry, vol. 40, pp. 633–650, 2002.
[27] Y. Bin and P. Munindar, “Mechanism of Reputation Man- agement in Electronic communities,” Proceedings of Fourth International Workshop on Cooperative Information Agents, 2000.
[28] P. Kollock, “The production of trust in online markets,” Advances in Group Processes, vol. 16, pp. 99–123, 1999.
[29] M. K. Lee and E. Turban, “A trust model for consumer In-
ternet shopping,” International Journal of Electronic Com-
merce, vol. 6, pp. 75–91, 2011.
[30] L.MuiandM.Mohtashemi,“Acomputationalmodelfortrust
and rePutation,” in Proceedings of the 35th Annual Hawaii International Conference on System Sciences, Big Island, HI, USA, January 2002.

Copyright 2024 Johnathan Edir Veliz
