# 🩺 A Collection of Alignments for Large Language Models and Beyond

👋 Hi, there. This is a collection of papers, surveys, etc for the research of language model alignments and beyond. 

Mostly, I will cover learning from human feedback, interactive NLP, and language model alignments.

The collection will be updated continually. 


## :blue_book: Surveys

* Zekun Wang, Ge Zhang, Kexin Yang, Ning Shi, Wangchunshu Zhou, Shaochun Hao, Guangzheng Xiong, Yizhi Li, Mong Yuan Sim, Xiuying Chen, Qingqing Zhu, Zhenzhu Yang, Adam Nik, Qi Liu, Chenghua Lin, Shi Wang, Ruibo Liu, Wenhu Chen, Ke Xu, Dayiheng Liu, Yike Guo, Jie Fu. [**Interactive Natural Language Processing**](https://arxiv.org/pdf/2305.13246.pdf). _arXiv preprint 2023_ <br/>


* Zijie J. Wang and Dongjin Choi and Shenyu Xu and Diyi Yang. [**Putting Humans in the Natural Language Processing Loop: {A} Survey**](https://arxiv.org/abs/2103.04044). _CoRR, abs/2103.04044, 2021_ <br/>

* Settles, Burr. [**Active learning literature survey**](https://minds.wisconsin.edu/bitstream/handle/1793/60660/TR1648.pdf?sequence=1). _arXiv, 0, 2009_ <br/>

## :notebook_with_decorative_cover: Blogs
* [**Illustrating Reinforcement Learning from Human Feedback (RLHF)**](https://huggingface.co/blog/rlhf) <br/>

## :blue_book: Projects
* [**PandaLM: Reproducible and Automated Language Model Assessment**](https://github.com/WeOpenML/PandaLM#data) <br/>
* [**Constrained Value-Aligned LLM via Safe RLHF**](https://github.com/PKU-Alignment/safe-rlhf) <br/>
* [**Chatbot Arena: Benchmarking LLMs in the Wild with Elo Ratings**](https://lmsys.org/blog/2023-05-03-arena/) <br/>
* [**AlpacaFarm: A Simulation Framework for Methods that Learn from Human Feedback**](https://crfm.stanford.edu/2023/05/22/alpaca-farm.html) </br>
* [**An Automatic Evaluator for Instruction-following Language Models**](https://tatsu-lab.github.io/alpaca_eval/) </br>


## :books: Papers

* Arnav Gudibande, Eric Wallace, Charlie Snell, Xinyang Geng, Hao Liu, Pieter Abbeel, Sergey Levine, Dawn Song. [**The False Promise of Imitating Proprietary LLMs**](https://arxiv.org/pdf/2305.15717.pdf). _arXiv preprint 2023_ </br>

* Zeqiu Wu, Yushi Hu, Weijia Shi, Nouha Dziri, Alane Suhr, Prithviraj Ammanabrolu, Noah A Smith, Mari Ostendorf, Hannaneh Hajishirzi. [**Fine-Grained Human Feedback Gives Better Rewards for Language Model Training**](https://arxiv.org/pdf/2306.01693.pdf). _arXiv preprint 2023_ </br>

* Lianmin Zheng, Wei-Lin Chiang, Ying Sheng, Siyuan Zhuang, Zhanghao Wu, Yonghao Zhuang, Zi Lin, Zhuohan Li, Dacheng Li, Eric. P Xing, Hao Zhang, Joseph E. Gonzalez, Ion Stoica. [**Judging LLM-as-a-judge with MT-Bench and Chatbot Arena**](https://arxiv.org/pdf/2306.05685.pdf). _arXiv preprint 2023_ </br>

* Peiyi Wang, Lei Li, Liang Chen, Dawei Zhu, Binghuai Lin, Yunbo Cao, Qi Liu, Tianyu Liu, Zhifang Sui. [**Large Language Models are not Fair Evaluators**](https://arxiv.org/pdf/2305.17926.pdf). _arXiv preprint 2023_ </br>

* Can Xu, Qingfeng Sun, Kai Zheng, Xiubo Geng, Pu Zhao, Jiazhan Feng, Chongyang Tao, Daxin Jian. [**WizardLM: Empowering Large Language Models to Follow Complex Instructions**](https://arxiv.org/pdf/2304.12244.pdf). _arXiv preprint 2023_ </br>

* Yizhong Wang, Hamish Ivison, Pradeep Dasigi, Jack Hessel, Tushar Khot, Khyathi Raghavi Chandu, David Wadden, Kelsey MacMillan, Noah A. Smith, Iz Beltagy, Hannaneh Hajishirzi. [**How Far Can Camels Go? Exploring the State of Instruction Tuning on Open Resources**](https://arxiv.org/pdf/2306.04751.pdf). _arXiv preprint 2023_ </br>

* Yidong Wang, Zhuohao Yu, Zhengran Zeng, Linyi Yang, Cunxiang Wang, Hao Chen, Chaoya Jiang, Rui Xie, Jindong Wang, Xing Xie, Wei Ye, Shikun Zhang, Yue Zhang. [**PandaLM: An Automatic Evaluation Benchmark for LLM Instruction Tuning Optimization**](https://arxiv.org/pdf/2306.05087.pdf).  _arXiv preprint 2023_ </br>

* Yew Ken Chia, Pengfei Hong, Lidong Bing, Soujanya Poria. [**INSTRUCTEVAL: Towards Holistic Evaluation of Instruction-Tuned Large Language Models**](https://arxiv.org/pdf/2306.04757.pdf).  _arXiv preprint 2023_ </br>

* Yuxin Jiang, Chunkit Chan, Mingyang Chen, Wei Wang. [**Lion: Adversarial Distillation of Closed-Source Large Language Model**](https://arxiv.org/pdf/2305.12870.pdf). _arXiv preprint 2023_ </br>

* Rafael Rafailov, Archit Sharma, Eric Mitchell, Stefano Ermon, Christopher D. Manning, Chelsea Fin. [**Direct Preference Optimization: Your Language Model is Secretly a Reward Model**](https://arxiv.org/pdf/2305.18290.pdf). _arXiv preprint 2023_ 

> Comparing to PPO, DPO directly uses the preference data to optimize the model, without learning a reward model.
> Thus, the drawback of DPO is that DPO can not utilize data without human preference. 
> You can understand DPO as a supervised learning method, but PPO is a semi-supervised learning method. 
<br/>

* Ruibo Liu, Ruixin Yang, Chenyan Jia, Ge Zhang, Denny Zhou, Andrew M. Dai, Diyi Yang, Soroush Vosoughi. [**Training Socially Aligned Language Models in Simulated Human Society**](https://arxiv.org/pdf/2305.16960.pdf). _arXiv preprint 2023_ <br/>

* Da Yin, Xiao Liu, Fan Yin, Ming Zhong, Hritik Bansal, Jiawei Han, Kai-Wei Chang. [**Dynosaur: A Dynamic Growth Paradigm for Instruction-Tuning Data Curation**](https://arxiv.org/pdf/2305.14327.pdf). _arXiv preprint 2023_ <br/>

* Sungdong Kim, Sanghwan Bae, Jamin Shin, Soyoung Kang, Donghyun Kwak, Kang Min Yoo, Minjoon Se [**Aligning Large Language Models through Synthetic Feedback**](https://arxiv.org/pdf/2305.13735.pdf). _arXiv preprint 2023_ <br/> 

* Chunting Zhou, Pengfei Liu, Puxin Xu, Srini Iyer, Jiao Sun, Yuning Mao, Xuezhe Ma, Avia Efrat, Ping Yu, Lili Yu, Susan Zhang, Gargi Ghosh, Mike Lewis, Luke Zettlemoyer, Omer Levy. [**LIMA: Less Is More for Alignment**](https://arxiv.org/pdf/2305.11206.pdf). _arXiv preprint 2023_ <br/>

* Yuan Z, Yuan H, Tan C, Wang W, Huang S, Huang F. [**RRHF: Rank Responses to Align Language Models with Human Feedback without tears**](https://arxiv.org/pdf/2304.05302.pdf). _arXiv preprint 2023_ <br/>

* Sun Z, Shen Y, Zhou Q, Zhang H, Chen Z, Cox D, Yang Y, Gan C. [**Principle-Driven Self-Alignment of Language Models from Scratch with Minimal Human Supervision**](https://arxiv.org/pdf/2305.03047.pdf). _arXiv preprint 2023_ <br/>

* Wang Y, Kordi Y, Mishra S, Liu A, Smith NA, Khashabi D, Hajishirzi H. [**Self-Instruct: Aligning Language Model with Self Generated Instructions**](https://arxiv.org/pdf/2212.10560.pdf). _ACL 2023_. <br/>

* Zhao Y, Joshi R, Liu T, Khalman M, Saleh M, Liu PJ. [**SLiC-HF: Sequence Likelihood Calibration with Human Feedback**](https://arxiv.org/pdf/2305.10425.pdf). _arXiv preprint arXiv:2305.10425. 2023_ <br/>



* Yan H, Srivastava S, Tai Y, Wang SI, Yih WT, Yao Z. [**Learning to Simulate Natural Language Feedback for Interactive Semantic Parsing**](https://arxiv.org/pdf/2305.08195.pdf). _ACL 2023_ <br/>

* Akyürek AF, Akyürek E, Madaan A, Kalyan A, Clark P, Wijaya D, Tandon N. [**RL4F: Generating Natural Language Feedback with Reinforcement Learning for Repairing Model Outputs**](https://arxiv.org/pdf/2305.08844.pdf). _ACL 2023_ <br/>


* Jérémy Scheurer, Jon Ander Campos, Tomasz Korbak, Jun Shern Chan, Angelica Chen, Kyunghyun Cho, Ethan Perez. [**Training Language Models with Language Feedback at Scale**](https://arxiv.org/pdf/2303.16755.pdf). _axXiv, 2023_ <br/>


* Sean Welleck and Ximing Lu and Peter West and Faeze Brahman and Tianxiao Shen and Daniel Khashabi and Yejin Choi. [**Generating Sequences by Learning to Self-Correct**](https://openreview.net/forum?id=hH36JeQZDaO). _ICLR, 2023_ <br/>

* Yuntao Bai, Saurav Kadavath, Sandipan Kundu, Amanda Askell, Jackson Kernion, Andy Jones, Anna Chen, Anna Goldie, Azalia Mirhoseini, Cameron McKinnon, etc. [**Constitutional ai: Harmlessness from ai feedback**](https://arxiv.org/pdf/2212.08073.pdf). arXiv preprint arXiv:2212.08073.

* Kurt Shuster and Jing Xu and Mojtaba Komeili and Da Ju and Eric Michael Smith and Stephen Roller and Megan Ung and Moya Chen and Kushal Arora and Joshua Lane and Morteza Behrooz and William Ngan and Spencer Poff and Naman Goyal and Arthur Szlam and YLan Boureau and Melanie Kambadur and Jason Weston. [**BlenderBot 3: a deployed conversational agent that continually learns to responsibly engage**](https://doi.org/10.48550/arXiv.2208.03188). _CoRR, abs/2208.03188, 2022_ <br/>

* Rongzhi Zhang and Yue Yu and Pranav Shetty and Le Song and Chao Zhang. [**PRBoost: Prompt-Based Rule Discovery and Boosting for Interactive Weakly-Supervised Learning**](https://doi.org/10.48550/arXiv.2203.09735). _ACL, 2022_ <br/>


* Mina Lee and Megha Srivastava and Amelia Hardy and John Thickstun and Esin Durmus and Ashwin Paranjape and Ines Gerard-Ursin and Xiang Lisa Li and Faisal Ladhak and Frieda Rong and Rose E. Wang and Minae Kwon and Joon Sung Park and Hancheng Cao and Tony Lee and Rishi Bommasani and Michael S. Bernstein and Percy Liang. [**Evaluating Human-Language Model Interaction**](https://doi.org/10.48550/arXiv.2212.09746). _CoRR, abs/2212.09746, 2022_ <br/>


* Long Ouyang and Jeff Wu and Xu Jiang and Diogo Almeida and Carroll L. Wainwright and Pamela Mishkin and Chong Zhang and Sandhini Agarwal and Katarina Slama and Alex Ray and John Schulman and Jacob Hilton and Fraser Kelton and Luke Miller and Maddie Simens and Amanda Askell and Peter Welinder and Paul F. Christiano and Jan Leike and Ryan Lowe. [**Training language models to follow instructions with human feedback**](https://doi.org/10.48550/arXiv.2203.02155). _CoRR, abs/2203.02155, 2022_ <br/>

* Ge Gao and Eunsol Choi and Yoav Artzi. [**Simulating Bandit Learning from User Feedback for Extractive Question Answering**](https://doi.org/10.18653/v1/2022.acl-long.355). _Proceedings of the 60th Annual Meeting of the Association for Computational Linguistics (Volume 1: Long Papers), {ACL} 2022, Dublin, Ireland, May 22-27, 2022_ <br/>

* William Saunders and Catherine Yeh and Jeff Wu and Steven Bills and Long Ouyang and Jonathan Ward and Jan Leike. [**Self-critiquing models for assisting human evaluators**](https://doi.org/10.48550/arXiv.2206.05802). _CoRR, abs/2206.05802, 2022_ <br/>


* Krishna, Ranjay and Lee, Donsuk and Fei-Fei, Li and Bernstein, Michael S. [**Socially situated artificial intelligence enables learning from human interaction**](https://www.pnas.org/doi/abs/10.1073/pnas.2115730119). _Proceedings of the National Academy of Sciences, 119, 2022_ <br/>

* Jeff Wu and Long Ouyang and Daniel M. Ziegler and Nisan Stiennon and Ryan Lowe and Jan Leike and Paul F. Christiano. [**Recursively Summarizing Books with Human Feedback**](https://arxiv.org/abs/2109.10862). _CoRR, abs/2109.10862, 2021_ <br/>


* Reiichiro Nakano and Jacob Hilton and Suchir Balaji and Jeff Wu and Long Ouyang and Christina Kim and Christopher Hesse and Shantanu Jain and Vineet Kosaraju and William Saunders and Xu Jiang and Karl Cobbe and Tyna Eloundou and Gretchen Krueger and Kevin Button and Matthew Knight and Benjamin Chess and John Schulman. [**WebGPT: Browser-assisted question-answering with human feedback**](https://arxiv.org/abs/2112.09332). _CoRR, abs/2112.09332, 2021_ <br/>


* Vania Mendonca and Ricardo Rei and Luisa Coheur and Alberto Sardinha and Ana Lucia Santos. [**Online Learning Meets Machine Translation Evaluation: Finding the Best Systems with the Least Human Effort**](https://doi.org/10.18653/v1/2021.acl-long.242). _Proceedings of the 59th Annual Meeting of the Association for Computational Linguistics and the 11th International Joint Conference on Natural Language Processing, {ACL/IJCNLP} 2021, (Volume 1: Long Papers), Virtual Event, August 1-6, 2021_ <br/>


* Noriyuki Kojima and Alane Suhr and Yoav Artzi. [**Continual Learning for Grounded Instruction Generation by Observing Human Following Behavior**](https://doi.org/10.1162/tacl\_a\_00428). _Trans. Assoc. Comput. Linguistics, 9, 2021_ <br/>


* Ahmed Elgohary and Christopher Meek and Matthew Richardson and Adam Fourney and Gonzalo A. Ramos and Ahmed Hassan Awadallah. [**{NL-EDIT:} Correcting Semantic Parse Errors through Natural Language Interaction**](https://doi.org/10.18653/v1/2021.naacl-main.444). _Proceedings of the 2021 Conference of the North American Chapter of the Association for Computational Linguistics: Human Language Technologies, {NAACL-HLT} 2021, Online, June 6-11, 2021_ <br/>


* Tobias Falke and Patrick Lehnen. [**Feedback Attribution for Counterfactual Bandit Learning in Multi-Domain Spoken Language Understanding**](https://doi.org/10.18653/v1/2021.emnlp-main.91). _Proceedings of the 2021 Conference on Empirical Methods in Natural Language Processing, {EMNLP} 2021, Virtual Event / Punta Cana, Dominican Republic, 7-11 November, 2021_ <br/>

* Ahmed Elgohary and Saghar Hosseini and Ahmed Hassan Awadallah. [**Speak to your Parser: Interactive Text-to-SQL with Natural Language Feedback**](https://doi.org/10.18653/v1/2020.acl-main.187). _Proceedings of the 58th Annual Meeting of the Association for Computational Linguistics, {ACL} 2020, Online, July 5-10, 2020_ <br/>


* Liat Ein-Dor and Alon Halfon and Ariel Gera and Eyal Shnarch and Lena Dankin and Leshem Choshen and Marina Danilevsky and Ranit Aharonov and Yoav Katz and Noam Slonim. [**Active Learning for {BERT:} An Empirical Study**](https://doi.org/10.18653/v1/2020.emnlp-main.638). _Proceedings of the 2020 Conference on Empirical Methods in Natural Language Processing, {EMNLP} 2020, Online, November 16-20, 2020_ <br/>




* Jon Ander Campos and Kyunghyun Cho and Arantxa Otegi and Aitor Soroa and Eneko Agirre and Gorka Azkune. [**Improving Conversational Question Answering Systems after Deployment using Feedback-Weighted Learning**](https://doi.org/10.18653/v1/2020.coling-main.230). _Proceedings of the 28th International Conference on Computational Linguistics, {COLING} 2020, Barcelona, Spain (Online), December 8-13, 2020_ <br/>



* Natasha Jaques and Judy Hanwen Shen and Asma Ghandeharioun and Craig Ferguson and Agata Lapedriza and Noah Jones and Shixiang Gu and Rosalind W. Picard. [**Human-centric dialog training via offline reinforcement learning**](https://doi.org/10.18653/v1/2020.emnlp-main.327). _Proceedings of the 2020 Conference on Empirical Methods in Natural Language Processing, {EMNLP} 2020, Online, November 16-20, 2020_ <br/>



* Nisan Stiennon and Long Ouyang and Jeff Wu and Daniel M. Ziegler and Ryan Lowe and Chelsea Voss and Alec Radford and Dario Amodei and Paul F. Christiano. [**Learning to summarize from human feedback**](https://arxiv.org/abs/2009.01325). _CoRR, abs/2009.01325, 2020_ <br/>


* Ziyu Yao and Yiqi Tang and Wen-tau Yih and Huan Sun and Yu Su. [**An Imitation Game for Learning Semantic Parsers from User Interaction**](https://doi.org/10.18653/v1/2020.emnlp-main.559). _Proceedings of the 2020 Conference on Empirical Methods in Natural Language Processing, {EMNLP} 2020, Online, November 16-20, 2020_ <br/>



* Bernhard Kratzwald and Stefan Feuerriegel and Huan Sun. [**Learning a Cost-Effective Annotation Policy for Question Answering**](https://doi.org/10.18653/v1/2020.emnlp-main.246). _Proceedings of the 2020 Conference on Empirical Methods in Natural Language Processing, {EMNLP} 2020, Online, November 16-20, 2020_ <br/>

* Julia Kreutzer and Stefan Riezler. [**Self-Regulated Interactive Sequence-to-Sequence Learning**](https://doi.org/10.18653/v1/p19-1029). _Proceedings of the 57th Conference of the Association for Computational Linguistics, {ACL} 2019, Florence, Italy, July 28- August 2, 2019, Volume 1: Long Papers_ <br/>

* Julia Kreutzer and Shahram Khadivi and Evgeny Matusov and Stefan Riezler. [**Can Neural Machine Translation be Improved with User Feedback?**](https://doi.org/10.18653/v1/n18-3012). _Proceedings of the 2018 Conference of the North American Chapter of the Association for Computational Linguistics: Human Language Technologies, {NAACL-HLT} 2018, New Orleans, Louisiana, USA, June 1-6, 2018, Volume 3 (Industry Papers)_ <br/>


* Yang Gao and Christian M. Meyer and Iryna Gurevych. [**{APRIL:} Interactively Learning to Summarise by Combining Active Preference Learning and Reinforcement Learning**](https://doi.org/10.18653/v1/d18-1445). _Proceedings of the 2018 Conference on Empirical Methods in Natural Language Processing, Brussels, Belgium, October 31 - November 4, 2018_ <br/>


* Julia Kreutzer and Joshua Uyheng and Stefan Riezler. [**Reliability and Learnability of Human Bandit Feedback for Sequence-to-Sequence Reinforcement Learning**](https://aclanthology.org/P18-1165/). _Proceedings of the 56th Annual Meeting of the Association for Computational Linguistics, {ACL} 2018, Melbourne, Australia, July 15-20, 2018, Volume 1: Long Papers_ <br/>


* Carolin Lawrence and Stefan Riezler. [**Improving a Neural Semantic Parser by Counterfactual Learning from Human Bandit Feedback**](https://aclanthology.org/P18-1169/). _Proceedings of the 56th Annual Meeting of the Association for Computational Linguistics, {ACL} 2018, Melbourne, Australia, July 15-20, 2018, Volume 1: Long Papers_ <br/>


* Khanh Nguyen and Hal Daume III and Jordan L. Boyd-Graber. [**Reinforcement Learning for Bandit Neural Machine Translation with Simulated Human Feedback**](https://doi.org/10.18653/v1/d17-1153). _Proceedings of the 2017 Conference on Empirical Methods in Natural Language Processing, {EMNLP} 2017, Copenhagen, Denmark, September 9-11, 2017_ <br/>


* Artem Sokolov and Julia Kreutzer and Kellen Sunderland and Pavel Danchenko and Witold Szymaniak and Hagen Furstenau and Stefan Riezler. [**A Shared Task on Bandit Learning for Machine Translation**](https://doi.org/10.18653/v1/w17-4756). _Proceedings of the Second Conference on Machine Translation, {WMT} 2017, Copenhagen, Denmark, September 7-8, 2017_ <br/>



* Carolin Lawrence and Artem Sokolov and Stefan Riezler. [**Counterfactual Learning from Bandit Feedback under Deterministic Logging : {A} Case Study in Statistical Machine Translation**](https://doi.org/10.18653/v1/d17-1272). _Proceedings of the 2017 Conference on Empirical Methods in Natural Language Processing, {EMNLP} 2017, Copenhagen, Denmark, September 9-11, 2017_ <br/>


* Artem Sokolov and Julia Kreutzer and Christopher Lo and Stefan Riezler. [**Learning Structured Predictors from Bandit Feedback for Interactive {NLP}**](https://doi.org/10.18653/v1/p16-1152). _Proceedings of the 54th Annual Meeting of the Association for Computational Linguistics, {ACL} 2016, August 7-12, 2016, Berlin, Germany, Volume 1: Long Papers_ <br/>



* Volodymyr Mnih and Koray Kavukcuoglu and David Silver and Andrei A. Rusu and Joel Veness and Marc G. Bellemare and Alex Graves and Martin A. Riedmiller and Andreas Fidjeland and Georg Ostrovski and Stig Petersen and Charles Beattie and Amir Sadik and Ioannis Antonoglou and Helen King and Dharshan Kumaran and Daan Wierstra and Shane Legg and Demis Hassabis. [**Human-level control through deep reinforcement learning**](https://doi.org/10.1038/nature14236). _Nat., 518, 2015_ <br/>




## To do
- [ ] Cluster the papers by topics.








