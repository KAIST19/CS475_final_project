# What is the best LLM Chatbot in South Korea?
Code release of our paper [paper](https://drive.google.com/file/d/1a4qkD8U658KFXHW9UsBmhWSzECakImrD/view?usp=sharing).

## Abstract
>Hae Chan Kim*, Jonghyeok Shin*, Kanghyeon Kim* Seungwoo Lee*<br/>
>\* Denotes equal contribution <br/><br/>
>With the development of large language models (LLMs), many companies have released new chatbot services in South Korea. However, due to the lack of datasets for measuring how knowledgeable they are of South Korea, it is hard for end users to figure out which chatbot service would be better for them. Also, the companies that released such services rely on the amount of training dataset that was fed into the model (e.g. CLOVA X) or the scores of some tests (e.g. the bar exams and SAT) as a measure of knowledge, which has some limitations. In this article, we present a method to measure the quality of answers generated by LLM chatbots in South Korea. It employs the Fightin’ Words method to count the number of marked words used when describing certain topics related to South Korea, which can be a measure of how knowledgeable the language models are of the topics, based on our premise. Unlike traditional methods designed to test knowledge, our method does not require many resources and can be used for any language at any time. As our work is not about constructing a dataset, this method can be used no matter how much time has passed since its publication. Through this method, we evaluate the knowledge of gpt-3.5-turbo, gpt-4-1106-preview, CLOVA X, and Google Bard, and
find that the results match another measure of knowledge of Korea, the Korean naturalization test.

## Experiments



## Results
This is the qualitative result presented in our paper. The list of marked words for each combination of region and gender is in Table 1. Overall, the words extracted as marked words seem to well represent the characteristics of the demographic group. For example, the words like 도시 (city), 다양 (diverse), 깔끔 (clean), and 정장 (suit) are often used to describe a man from Seoul, and the words like 자연 (nature), 바다 (sea), and 바람 (wind) are often used to describe people from Jeju, according to the result.
![Table 1](images/table1.png){: width="50%" height="50%"}


These are the quantitative results presented in our paper. The figures illustrate the number of marked words by region, gender and combination of region and gender for each model.

![Figure 1](images/figure1.png)
![Figure 2](images/figure2.png)
![Figure 3](images/figure3.png)


### Libraries
- https://konlpy.org/en/latest/
  
  
### Projects
- https://github.com/myracheng/markedpersonas

- https://github.com/jmhessel/FightingWords
