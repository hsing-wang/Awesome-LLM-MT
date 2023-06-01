# Machine Translation with Large Language Models Reading List

* [In-context Learning](#in_context_learning)
* [Evaluation](#evaluation)
* [Chain-of-Thought Prompting](#CoT)
* [LLMs as Scorer](#llms_as_scorer)
* [In-context Learning](#in_context_learning)

<h2 id="in_context_learning">In-context Learning</h2> 

* [Language Models are Few-Shot Learners](https://arxiv.org/abs/2005.14165). Tom B. Brown, Benjamin Mann, Nick Ryder, Melanie Subbiah, Jared Kaplan, Prafulla Dhariwal, Arvind Neelakantan, Pranav Shyam, Girish Sastry, Amanda Askell, Sandhini Agarwal, Ariel Herbert-Voss, Gretchen Krueger, Tom Henighan, Rewon Child, Aditya Ramesh, Daniel M. Ziegler, Jeffrey Wu, Clemens Winter, Christopher Hesse, Mark Chen, Eric Sigler, Mateusz Litwin, Scott Gray, Benjamin Chess, Jack Clark, Christopher Berner, Sam McCandlish, Alec Radford, Ilya Sutskever, Dario Amodei. (arxiv 2020)
* [Few-shot Learning with Multilingual Generative Language Models](https://aclanthology.org/2022.emnlp-main.616/).Xi Victoria Lin, Todor Mihaylov, Mikel Artetxe, Tianlu Wang, Shuohui Chen, Daniel Simig, Myle Ott, Naman Goyal, Shruti Bhosale, Jingfei Du, Ramakanth Pasunuru, Sam Shleifer, Punit Singh Koura, Vishrav Chaudhary, Brian O’Horo, Jeff Wang, Luke Zettlemoyer, Zornitsa Kozareva, Mona Diab, Veselin Stoyanov, Xian Li. (EMNLP 2022)
* [In-context Examples Selection for Machine Translation](https://arxiv.org/abs/2212.02437). Sweta Agrawal, Chunting Zhou, Mike Lewis, Luke Zettlemoyer, Marjan Ghazvininejad. (arxiv 2022)
* [Prompting PaLM for Translation: Assessing Strategies and Performance](https://arxiv.org/abs/2211.09102). Sweta Agrawal, Chunting Zhou, Mike Lewis, Luke Zettlemoyer, Marjan Ghazvininejad. (arxiv 2022)
* [Prompting Large Language Model for Machine Translation: A Case Study](https://arxiv.org/abs/2301.07069). Biao Zhang, Barry Haddow, Alexandra Birch. (arxiv 2023)
* [Adaptive Machine Translation with Large Language Models](https://arxiv.org/abs/2301.13294). Yasmin Moslem, Rejwanul Haque, John D. Kelleher, Andy Way. (EAMT 2023)
* [The unreasonable effectiveness of few-shot learning for machine translation](https://arxiv.org/abs/2302.01398). Xavier Garcia, Yamini Bansal, Colin Cherry, George Foster, Maxim Krikun, Fangxiaoyu Feng, Melvin Johnson, Orhan Firat. (arxiv 2023)
* [Dictionary-based Phrase-level Prompting of Large Language Models for Machine Translation](https://arxiv.org/abs/2302.07856). Marjan Ghazvininejad, Hila Gonen, Luke Zettlemoyer. (arxiv 2023)


<h2 id="evaluation">Evaluation</h2> 

* [Is ChatGPT A Good Translator? Yes With GPT-4 As The Engine](https://arxiv.org/abs/2301.08745). Wenxiang Jiao, Wenxuan Wang, Jen-tse Huang, Xing Wang, Zhaopeng Tu. (arxiv 2023) {[code](https://github.com/wxjiao/Is-ChatGPT-A-Good-Translator)}
* [How Good Are GPT Models at Machine Translation? A Comprehensive Evaluation](https://arxiv.org/abs/2302.09210). Amr Hendy, Mohamed Abdelrehim, Amr Sharaf, Vikas Raunak, Mohamed Gabr, Hitokazu Matsushita, Young Jin Kim, Mohamed Afify, Hany Hassan Awadalla. (arxiv 2023) {[code](https://github.com/microsoft/gpt-MT)}
* [Document-Level Machine Translation with Large Language Models](https://arxiv.org/abs/2304.02210). Longyue Wang, Chenyang Lyu, Tianbo Ji, Zhirui Zhang, Dian Yu, Shuming Shi, Zhaopeng Tu. (arxiv 2023) {[code](https://github.com/longyuewangdcu/Document-MT-LLM)}
* [Multilingual Machine Translation with Large Language Models: Empirical Results and Analysis](https://arxiv.org/abs/2301.13294). Wenhao Zhu, Hongyi Liu, Qingxiu Dong, Jingjing Xu, Shujian Huang, Lingpeng Kong, Jiajun Chen, Lei Li. (arxiv 2023) {[code](https://github.com/OwenNJU/MMT-LLM)}
* [How to Design Translation Prompts for ChatGPT: An Empirical Study](https://arxiv.org/abs/2304.02182). Yuan Gao, Ruili Wang, Feng Hou. (arxiv 2023)
* [Investigating the Translation Performance of a Large Multilingual Language Model: the Case of BLOOM](https://arxiv.org/abs/2304.02182). Rachel Bawden, François Yvon. (EAMT 2023)  {[code](https://github.com/rbawden/mt-bigscience)}


<h2 id="CoT">Chain-of-Thought Prompting</h2> 

* [Exploring Human-Like Translation Strategy with Large Language Models](https://arxiv.org/abs/2305.04118). Zhiwei He, Tian Liang, Wenxiang Jiao, Zhuosheng Zhang, Yujiu Yang, Rui Wang, Zhaopeng Tu, Shuming Shi, Xing Wang. (arxiv 2023) {[code](https://github.com/zwhe99/MAPS-mt)}
* [Towards Making the Most of ChatGPT for Machine Translation](https://arxiv.org/abs/2303.13780).Keqin Peng, Liang Ding, Qihuang Zhong, Li Shen, Xuebo Liu, Min Zhang, Yuanxin Ouyang, Dacheng Tao. (arxiv 2023) {[code](https://github.com/Romainpkq/ChatGPT4MT)}
* [Chain-of-Dictionary Prompting Elicits Translation in Large Language Models](https://arxiv.org/abs/2305.06575). Hongyuan Lu, Haoyang Huang, Dongdong Zhang, Haoran Yang, Wai Lam, Furu Wei. (arxiv 2023)



<h2 id="llms_as_scorer">LLMs as Scorer</h2>

* [GPTScore: Evaluate as You Desire](https://arxiv.org/abs/2302.04166). Jinlan Fu, See-Kiong Ng, Zhengbao Jiang, Pengfei Liu. (arxiv 2023)  {[code](https://github.com/jinlanfu/GPTScore)}
* [Large Language Models Are State-of-the-Art Evaluators of Translation Quality](https://arxiv.org/abs/2302.14520). Tom Kocmi, Christian Federmann (arxiv 2023) {[code](https://github.com/MicrosoftTranslator/GEMBA)}
* [Error Analysis Prompting Enables Human-Like Translation Evaluation in Large Language Models: A Case Study on ChatGPT](https://arxiv.org/abs/2303.13809). Qingyu Lu, Baopu Qiu, Liang Ding, Liping Xie, Dacheng Tao. (arxiv 2023)  {[code](https://github.com/Coldmist-Lu/ErrorAnalysis_Prompt)}
