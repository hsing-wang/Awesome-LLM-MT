# Machine Translation with LLMs Reading List

**We greatly appreciate any contributions via PRs, issues, emails, or other methods.**

This is a machine translation with large language models (LLMs) reading list maintained by [Xing Wang](http://xingwang4nlp.com/) and [Zhiwei He](https://zwhe99.github.io/).


* [In-context Learning](#in_context_learning)
* [Assessment](#assessment)
* [Chain-of-Thought Prompting](#CoT)
* [Base Model Pre-training](#base)
* [Translation Finetuning](#finetuning)
* [LLMs as Scorer](#llms_as_scorer)
* [Post-Editing](#post-editing)
* [Interpretability](#interpretability)

<!--good luck-->
<h2 id="in_context_learning">In-context Learning</h2> 

* [Language Models are Few-Shot Learners](https://proceedings.neurips.cc/paper/2020/file/1457c0d6bfcb4967418bfb8ac142f64a-Paper.pdf). Tom B. Brown, Benjamin Mann, Nick Ryder, Melanie Subbiah, Jared Kaplan, Prafulla Dhariwal, Arvind Neelakantan, Pranav Shyam, Girish Sastry, Amanda Askell, Sandhini Agarwal, Ariel Herbert-Voss, Gretchen Krueger, Tom Henighan, Rewon Child, Aditya Ramesh, Daniel M. Ziegler, Jeffrey Wu, Clemens Winter, Christopher Hesse, Mark Chen, Eric Sigler, Mateusz Litwin, Scott Gray, Benjamin Chess, Jack Clark, Christopher Berner, Sam McCandlish, Alec Radford, Ilya Sutskever, Dario Amodei. (NeurIPS 2020)
* [Few-shot Learning with Multilingual Generative Language Models](https://aclanthology.org/2022.emnlp-main.616/). Xi Victoria Lin, Todor Mihaylov, Mikel Artetxe, Tianlu Wang, Shuohui Chen, Daniel Simig, Myle Ott, Naman Goyal, Shruti Bhosale, Jingfei Du, Ramakanth Pasunuru, Sam Shleifer, Punit Singh Koura, Vishrav Chaudhary, Brian O’Horo, Jeff Wang, Luke Zettlemoyer, Zornitsa Kozareva, Mona Diab, Veselin Stoyanov, Xian Li. (EMNLP 2022)
* [In-context Examples Selection for Machine Translation](https://aclanthology.org/2023.findings-acl.564.pdf). Sweta Agrawal, Chunting Zhou, Mike Lewis, Luke Zettlemoyer, Marjan Ghazvininejad. (Findings of the ACL 2023)
* [Prompting PaLM for Translation: Assessing Strategies and Performance](https://aclanthology.org/2023.acl-long.859.pdf). David Vilar, Markus Freitag, Colin Cherry, Jiaming Luo, Viresh Ratnakar, George Foster. (ACL 2023)
* [Prompting Large Language Model for Machine Translation: A Case Study](https://openreview.net/pdf?id=yWl0agiI0y). Biao Zhang, Barry Haddow, Alexandra Birch. (ICML 2023)
* [Prompting Neural Machine Translation with Translation Memories](https://arxiv.org/abs/2301.05380). Abudurexiti Reheman, Tao Zhou, Yingfeng Luo, Di Yang, Tong Xiao, Jingbo Zhu. (AAAI 2023)
* [Adaptive Machine Translation with Large Language Models](https://arxiv.org/abs/2301.13294). Yasmin Moslem, Rejwanul Haque, John D. Kelleher, Andy Way. (EAMT 2023) {[code](https://github.com/ymoslem/Adaptive-MT-LLM)}
* [The unreasonable effectiveness of few-shot learning for machine translation](https://openreview.net/pdf?id=zvCSNsoyKW). Xavier Garcia, Yamini Bansal, Colin Cherry, George Foster, Maxim Krikun, Fangxiaoyu Feng, Melvin Johnson, Orhan Firat. (ICML 2023)
* [Dictionary-based Phrase-level Prompting of Large Language Models for Machine Translation](https://arxiv.org/abs/2302.07856). Marjan Ghazvininejad, Hila Gonen, Luke Zettlemoyer. (arxiv 2023)
* [RAMP: Retrieval and Attribute-Marking Enhanced Prompting for Attribute-Controlled Translation](https://aclanthology.org/2023.acl-short.126/). Gabriele Sarti, Phu Mon Htut, Xing Niu, Benjamin Hsu, Anna Currey, Georgiana Dinu, Maria Nadejde. (ACL 2023)
* [Instruction Position Matters in Sequence Generation with Large Language Models](https://arxiv.org/abs/2308.12097). Yijin Liu, Xianfeng Zeng, Fandong Meng, Jie Zhou. (arxiv 2023) {[code](https://github.com/Adaxry/Post-Instruction/tree/main)}
* [Improving Translation Faithfulness of Large Language Models via Augmenting Instructions](https://arxiv.org/abs/2308.12674). Yijie Chen, Yijin Liu, Fandong Meng, Yufeng Chen, Jinan Xu, Jie Zhou. (arxiv 2023) {[code](https://github.com/pppa2019/swie_overmiss_llm4mt)}
* [Neural Machine Translation Models Can Learn to be Few-shot Learners](https://arxiv.org/abs/2309.08590). Raphael Reinauer, Patrick Simianer, Kaden Uhlig, Johannes E. M. Mosig, Joern Wuebker. (arxiv 2023)
* [Towards Effective Disambiguation for Machine Translation with Large Language Models](https://arxiv.org/abs/2309.11668). Vivek Iyer, Pinzhen Chen, Alexandra Birch. (arxiv 2023)
* [SCALE: Synergized Collaboration of Asymmetric Language Translation Engines](https://arxiv.org/abs/2309.17061). Xin Cheng, Xun Wang, Tao Ge, Si-Qing Chen, Furu Wei, Dongyan Zhao, Rui Yan. (arxiv 2023)
* [Steering Large Language Models for Machine Translation with Finetuning and In-Context Learning](https://arxiv.org/abs/2310.13448). Duarte M. Alves, Nuno M. Guerreiro, João Alves, José Pombal, Ricardo Rei, José G. C. de Souza, Pierre Colombo, André F. T. Martins. (Findings of EMNLP 2023) {[code](https://github.com/deep-spin/translation_llm)}
* [Dissecting In-Context Learning of Translations in GPTs](https://arxiv.org/abs/2310.15987). Vikas Raunak, Hany Hassan Awadalla, Arul Menezes. (Findings of EMNLP 2023)
* [Narrowing the Gap between Zero- and Few-shot Machine Translation by Matching Styles](https://arxiv.org/abs/2311.02310). Weiting Tan, Haoran Xu, Lingfeng Shen, Shuyue Stella Li, Kenton Murray, Philipp Koehn, Benjamin Van Durme, Yunmo Chen. (arxiv 2023)




<h2 id="assessment">Assessment</h2> 

* [Is ChatGPT A Good Translator? Yes With GPT-4 As The Engine](https://arxiv.org/abs/2301.08745). Wenxiang Jiao, Wenxuan Wang, Jen-tse Huang, Xing Wang, Zhaopeng Tu. (arxiv 2023) {[code](https://github.com/wxjiao/Is-ChatGPT-A-Good-Translator)}
* [A Multitask, Multilingual, Multimodal Evaluation of ChatGPT on Reasoning, Hallucination, and Interactivity](https://arxiv.org/abs/2302.04023). Yejin Bang, Samuel Cahyawijaya, Nayeon Lee, Wenliang Dai, Dan Su, Bryan Wilie, Holy Lovenia, Ziwei Ji, Tiezheng Yu, Willy Chung, Quyet V. Do, Yan Xu, Pascale Fung. (arxiv 2023) {[code](https://github.com/HLTCHKUST/chatgpt-evaluation)}
* [How Good Are GPT Models at Machine Translation? A Comprehensive Evaluation](https://arxiv.org/abs/2302.09210). Amr Hendy, Mohamed Abdelrehim, Amr Sharaf, Vikas Raunak, Mohamed Gabr, Hitokazu Matsushita, Young Jin Kim, Mohamed Afify, Hany Hassan Awadalla. (arxiv 2023) {[code](https://github.com/microsoft/gpt-MT)}
* [Document-Level Machine Translation with Large Language Models](https://arxiv.org/abs/2304.02210). Longyue Wang, Chenyang Lyu, Tianbo Ji, Zhirui Zhang, Dian Yu, Shuming Shi, Zhaopeng Tu. (arxiv 2023) {[code](https://github.com/longyuewangdcu/Document-MT-LLM)}
* [Multilingual Machine Translation with Large Language Models: Empirical Results and Analysis](https://arxiv.org/abs/2304.04675). Wenhao Zhu, Hongyi Liu, Qingxiu Dong, Jingjing Xu, Shujian Huang, Lingpeng Kong, Jiajun Chen, Lei Li. (arxiv 2023) {[code](https://github.com/OwenNJU/MMT-LLM)}
* [How to Design Translation Prompts for ChatGPT: An Empirical Study](https://arxiv.org/abs/2304.02182). Yuan Gao, Ruili Wang, Feng Hou. (arxiv 2023)
* [Investigating the Translation Performance of a Large Multilingual Language Model: the Case of BLOOM](https://arxiv.org/abs/2303.01911). Rachel Bawden, François Yvon. (EAMT 2023)  {[code](https://github.com/rbawden/mt-bigscience)}
* [Large language models effectively leverage document-level context for literary translation, but critical errors persist](https://arxiv.org/abs/2304.03245). Marzena Karpinska, Mohit Iyyer. (arxiv 2023)  {[code](https://github.com/marzenakrp/LiteraryTranslation)}
* [Do GPTs Produce Less Literal Translations?](https://aclanthology.org/2023.acl-short.90.pdf). Vikas Raunak, Arul Menezes, Matt Post, Hany Hassan Awadalla. (ACL 2023) 
* [Zeno GPT-MT Report](https://github.com/zeno-ml/zeno-build/tree/main/examples/analysis_gpt_mt/report). Graham Neubig. (github 2023) {[code](https://github.com/zeno-ml/zeno-build/tree/main/examples/analysis_gpt_mt/report)}


<h2 id="CoT">Chain-of-Thought Prompting</h2> 

* [Exploring Human-Like Translation Strategy with Large Language Models](https://arxiv.org/abs/2305.04118). Zhiwei He, Tian Liang, Wenxiang Jiao, Zhuosheng Zhang, Yujiu Yang, Rui Wang, Zhaopeng Tu, Shuming Shi, Xing Wang. (arxiv 2023) {[code](https://github.com/zwhe99/MAPS-mt)}
* [Towards Making the Most of ChatGPT for Machine Translation](https://arxiv.org/abs/2303.13780).Keqin Peng, Liang Ding, Qihuang Zhong, Li Shen, Xuebo Liu, Min Zhang, Yuanxin Ouyang, Dacheng Tao. (Findings of EMNLP 2023) {[code](https://github.com/Romainpkq/ChatGPT4MT)}
* [Chain-of-Dictionary Prompting Elicits Translation in Large Language Models](https://arxiv.org/abs/2305.06575). Hongyuan Lu, Haoyang Huang, Dongdong Zhang, Haoran Yang, Wai Lam, Furu Wei. (arxiv 2023)
* [Encouraging Divergent Thinking in Large Language Models through Multi-Agent Debate](https://arxiv.org/abs/2305.19118). Tian Liang, Zhiwei He, Wenxiang Jiao, Xing Wang, Yan Wang, Rui Wang, Yujiu Yang, Zhaopeng Tu, Shuming Shi. (arxiv 2023)  {[code](https://github.com/Skytliang/Multi-Agents-Debate)}


<h2 id="base">Base Model Pre-training</h2> 

* [Cross-Lingual Supervision improves Large Language Models Pre-training](https://arxiv.org/abs/2305.11778). Andrea Schioppa, Xavier Garcia, Orhan Firat. (arxiv 2023)
* [InternLM: A Multilingual Language Model with Progressively Enhanced Capabilitiese](https://github.com/InternLM/InternLM-techreport). InternLM Team. (github 2023) {[code](https://github.com/InternLM/InternLM-techreport)}
* [PolyLM: An Open Source Polyglot Large Language Model](https://arxiv.org/abs/2307.06018). Xiangpeng Wei, Haoran Wei, Huan Lin, Tianhao Li, Pei Zhang, Xingzhang Ren, Mei Li, Yu Wan, Zhiwei Cao, Binbin Xie, Tianxiang Hu, Shangjie Li, Binyuan Hui, Bowen Yu, Dayiheng Liu, Baosong Yang, Fei Huang, Jun Xie. (arxiv 2023) {[code](https://modelscope.cn/models/damo/nlp_polylm_13b_text_generation/summary)}
* [OpenBA: An Open-sourced 15B Bilingual Asymmetric seq2seq Model Pre-trained from Scratch](https://arxiv.org/abs/2309.10706). Juntao Li, Zecheng Tang, Yuyang Ding, Pinzheng Wang, Pei Guo, Wangjie You, Dan Qiao, Wenliang Chen, Guohong Fu, Qiaoming Zhu, Guodong Zhou, Min Zhang. (arxiv 2023) {[code](https://github.com/OpenNLG/openBA)}


<h2 id="finetuning">Translation Finetuning</h2>

* [ParroT: Translating During Chat Using Large Language Models](https://arxiv.org/abs/2304.02426). Wenxiang Jiao, Jen-tse Huang, Wenxuan Wang, Zhiwei He, Tian Liang, Xing Wang, Shuming Shi, Zhaopeng Tu. (Findings of EMNLP 2023) {[code](https://github.com/wxjiao/ParroT)}
* [Eliciting the Translation Ability of Large Language Models via Multilingual Finetuning with Translation Instructions](https://arxiv.org/abs/2305.15083). Jiahuan Li, Hao Zhou, Shujian Huang, Shanbo Chen, Jiajun Chen. (arxiv 2023) 
* [BigTrans: Augmenting Large Language Models with Multilingual Translation Capability over 100 Languages](https://arxiv.org/abs/2305.18098). Wen Yang, Chong Li, Jiajun Zhang, Chengqing Zong. (arxiv 2023) {[code](https://github.com/ZNLP/BigTrans)}
* [BayLing: Bridging Cross-lingual Alignment and Instruction Following through Interactive Translation for Large Language Models](https://arxiv.org/abs/2306.10968). Shaolei Zhang, Qingkai Fang, Zhuocheng Zhang, Zhengrui Ma, Yan Zhou, Langlin Huang, Mengyu Bu, Shangtong Gui, Yunji Chen, Xilin Chen, Yang Feng. (arxiv 2023)  {[code](https://github.com/ictnlp/BayLing)}
* [TIM: Teaching Large Language Models to Translate with Comparison](https://arxiv.org/abs/2307.04408). Jiali Zeng, Fandong Meng, Yongjing Yin, Jie Zhou. (arxiv 2023) {[code](https://github.com/lemon0830/TIM)}
* [Extrapolating Large Language Models to Non-English by Aligning Languages](https://arxiv.org/pdf/2308.04948). Wenhao Zhu, Yunzhe Lv, Qingxiu Dong, Fei Yuan, Jingjing Xu, Shujian Huang, Lingpeng Kong, Jiajun Chen, Lei Li. (arxiv 2023) {[code](https://github.com/OwenNJU/x-LLM)}
* [A Paradigm Shift in Machine Translation: Boosting Translation Performance of Large Language Models](https://arxiv.org/abs/2309.11674). Haoran Xu, Young Jin Kim, Amr Sharaf, Hany Hassan Awadalla. (arxiv 2023) {[code](https://github.com/fe1ixxu/ALMA)}
* [Towards Effective Disambiguation for Machine Translation with Large Language Models](https://arxiv.org/abs/2309.11668). Vivek Iyer, Pinzhen Chen, Alexandra Birch. (arxiv 2023)
* [Steering Large Language Models for Machine Translation with Finetuning and In-Context Learning](https://arxiv.org/abs/2310.13448). Duarte M. Alves, Nuno M. Guerreiro, João Alves, José Pombal, Ricardo Rei, José G. C. de Souza, Pierre Colombo, André F. T. Martins. (Findings of EMNLP 2023) {[code](https://github.com/deep-spin/translation_llm)}





<h2 id="llms_as_scorer">LLMs as Scorer</h2>

* [GPTScore: Evaluate as You Desire](https://arxiv.org/abs/2302.04166). Jinlan Fu, See-Kiong Ng, Zhengbao Jiang, Pengfei Liu. (arxiv 2023) {[code](https://github.com/jinlanfu/GPTScore)}
* [Large Language Models Are State-of-the-Art Evaluators of Translation Quality](https://aclanthology.org/2023.eamt-1.19/). Tom Kocmi, Christian Federmann (EAMT 2023) {[code](https://github.com/MicrosoftTranslator/GEMBA)}
* [Error Analysis Prompting Enables Human-Like Translation Evaluation in Large Language Models: A Case Study on ChatGPT](https://arxiv.org/abs/2303.13809). Qingyu Lu, Baopu Qiu, Liang Ding, Liping Xie, Dacheng Tao. (arxiv 2023) {[code](https://github.com/Coldmist-Lu/ErrorAnalysis_Prompt)}
* [INSTRUCTSCORE: Towards Explainable Text Generation Evaluation with Automatic Feedback](https://arxiv.org/abs/2305.14282). Wenda Xu, Danqing Wang, Liangming Pan, Zhenqiao Song, Markus Freitag, William Yang Wang, Lei Li. (EMNLP 2023) {[code](https://github.com/xu1998hz/SEScore3)}
* [Towards Explainable Evaluation Metrics for Machine Translation](https://arxiv.org/abs/2306.13041). Christoph Leiter, Piyawat Lertvittayakumjorn, Marina Fomicheva, Wei Zhao, Yang Gao, Steffen Eger. (arxiv 2023)
* [The Devil is in the Errors: Leveraging Large Language Models for Fine-grained Machine Translation Evaluation](https://arxiv.org/abs/2308.07286). Patrick Fernandes, Daniel Deutsch, Mara Finkelstein, Parker Riley, André F. T. Martins, Graham Neubig, Ankush Garg, Jonathan H. Clark, Markus Freitag, Orhan Firat. (arxiv 2023)
* [Towards Multiple References Era -- Addressing Data Leakage and Limited Reference Diversity in NLG Evaluation](https://arxiv.org/abs/2308.03131). Xianfeng Zeng, Yijin Liu, Fandong Meng, Jie Zhou. (arxiv 2023) {[code](https://github.com/SefaZeng/LLM-Ref)}
 



<h2 id="post-editing">Post-Editing</h2>

* [Leveraging GPT-4 for Automatic Translation Post-Editing](https://arxiv.org/abs/2305.14878). Vikas Raunak, Amr Sharaf, Hany Hassan Awadallah, Arul Menezes. (arxiv 2023) 
* [Iterative Translation Refinement with Large Language Models](https://arxiv.org/abs/2306.03856). Pinzhen Chen, Zhicheng Guo, Barry Haddow, Kenneth Heafield. (arxiv 2023)
* [Contextual Refinement of Translations: Large Language Models for Sentence and Document-Level Post-Editing](https://arxiv.org/abs/2310.14855). Sai Koneru, Miriam Exel, Matthias Huck, Jan Niehues. (arxiv 2023) 



<h2 id="interpretability">Interpretability</h2>

* [Searching for Needles in a Haystack: On the Role of Incidental Bilingualism in PaLM's Translation Capability](https://arxiv.org/abs/2305.10266). Eleftheria Briakou, Colin Cherry, George Foster. (ACL 2023) 

