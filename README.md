# Data-to-text-Paper-List
A summary of Data-to-text Generation Papers.

## [Content](#content)

<table>
<tr><td colspan="2"> <a href="#datasets">Datasets</a></td></tr>

<tr>
    <td> <a href="#public-datasets">Public Datasets</a></td>
    <td> <a href="#corpora-generation">Corpora Generation and Manipulation</a></td>
</tr>
<tr>
    <td> <a href="#data-augmentation">Data Augmentation</a></td>
    <td></td>
</tr>

<tr><td colspan="2"> <a href="#analysis">Analysis</a></td></tr>

<tr><td colspan="2"> <a href="#models">Models</a></td></tr>
<tr>
   <td> <a href="#data-representation">Data Representation</a></td>
   <td> <a href="#content-generation">Content Generation</a></td></tr>
<tr>
   <td> <a href="#surface-realization">Surface Realization</a></td>
   <td> <a href="#other-direction">Other Directions</a></td>
</tr>
<tr>
   <td> <a href="#Training Methods">Training Methods</a></td>
   <td></td>
</tr>

<tr><td colspan="2"> <a href="#evaluation">Evaluation</a></td></tr>

<tr><td colspan="2"> <a href="#application">Applications</a></td></tr>

<tr><td colspan="2"> <a href="#thesis">Thesis</a></td></tr>

</table>
## [Datasets](#datasets)

### [Public Datasets](#public-datasets)
1. **Challenges in Data-to-Document Generation** EMNLP, 2017 [paper](http://dx.doi.org/10.18653/v1/d17-1239) 

   *Sam Wiseman; Stuart M. Shieber; Alexander M. Rush*


2. **Creating Training Corpora for NLG Micro-Planners** ACL, 2017 [paper](http://dx.doi.org/10.18653/v1/p17-1017) 

   *Claire Gardent; Anastasia Shimorina; Shashi Narayan; Laura Perez-Beltrachini*


3. **Creating a Corpus for Russian Data-to-Text Generation Using Neural Machine Translation and Post-Editing** BSNLP@ACL, 2019 [paper](http://dx.doi.org/10.18653/v1/w19-3706) 

   *Anastasia Shimorina; Elena Khasanova; Claire Gardent*


4. **Ensuring Readability and Data-fidelity using Head-modifier Templates in Deep Type Description Generation** ACL, 2019 [paper](http://dx.doi.org/10.18653/v1/p19-1196) 

   *Jiangjie Chen; Ao Wang; Haiyun Jiang; Suo Feng; Chenguang Li; Yanghua Xiao*


5. **ViGGO: A Video Game Corpus for Data-To-Text Generation in Open-Domain Conversation.** INLG, 2019 [paper](http://dx.doi.org/10.18653/v1/w19-8623) 

   *Juraj Juraska; Kevin K. Bowden; Marilyn A. Walker*


6. **The CACAPO Dataset : A Multilingual, Multi-Domain Dataset for Neural Pipeline and End-to-End Data-to-Text Generation** INLG, 2020 [paper](https://aclanthology.org/2020.inlg-1.10/) 

   *Chris van der Lee; Chris Emmery; Sander Wubben; Emiel Krahmer*


7. **ToTTo: A Controlled Table-To-Text Generation Dataset** EMNLP, 2020 [paper](http://dx.doi.org/10.18653/v1/2020.emnlp-main.89) 

   *Ankur P. Parikh; Xuezhi Wang; Sebastian Gehrmann; Manaal Faruqui; Bhuwan Dhingra; Diyi Yang; Dipanjan Das*


8. **Plum2Text: a french plumitifs -descriptions data-to-text dataset for natural language generation** ICAIL, 2021 [paper](http://dx.doi.org/10.1145/3462757.3466148) 

   *Nicolas Garneau; Eve Gaumond; Luc Lamontagne; Pierre-Luc Déziel*


9. **Towards Table-to-Text Generation with Numerical Reasoning** ACL/IJCNLP, 2021 [paper](http://dx.doi.org/10.18653/v1/2021.acl-long.115) 

   *Lya Hulliyyatus Suadaa; Hidetaka Kamigaito; Kotaro Funakoshi; Manabu Okumura; Hiroya Takamura*



### [Corpora Generation](#corpora-generation)
1. **Schema-Guided Natural Language Generation.** INLG, 2020 [paper](https://aclanthology.org/2020.inlg-1.35/) 

   *Yuheng Du; Shereen Oraby; Vittorio Perera; Minmin Shen; Anjali Narayan-Chen; Tagyoung Chung; Anu Venkatesh; Dilek Hakkani-Tur*


2. **Knowledge Graph Based Synthetic Corpus Generation for Knowledge-Enhanced Language Model Pre-training** NAACL-HLT, 2021 [paper](http://dx.doi.org/10.18653/v1/2021.naacl-main.278) 

   *Oshin Agarwal; Heming Ge; Siamak Shakeri; Rami Al-Rfou*




### [Data Augmentation](#data-augmentation)

1. **Neural Data-to-Text Generation with LM-based Text Augmentation** EACL, 2021 [paper](http://dx.doi.org/10.18653/v1/2021.eacl-main.64) 

   *Ernie Chang; Xiaoyu Shen; Dawei Zhu; Vera Demberg; Hui Su*


2. **Automatic Construction of Evaluation Suites for Natural Language Generation Datasets** arXiv, 2021 [paper](https://ui.adsabs.harvard.edu/abs/2021arXiv210609069M/abstract) 

   *Simon Mille; Kaustubh Dhole; Saad Mahamood; Laura Perez-Beltrachini; Varun Gangal; Mihir Kale; Emiel van Miltenburg; Sebastian Gehrmann*



## [Analysis](#analysis)
1. **Automated learning of templates for data-to-text generation: comparing rule-based, statistical and neural methods** INLG, 2018 [paper](http://dx.doi.org/10.18653/v1/w18-6504) 

   *Chris van der Lee; Emiel Krahmer; Sander Wubben*


2. **Handling Rare Items in Data-to-Text Generation** INLG, 2018 [paper](http://dx.doi.org/10.18653/v1/w18-6543) 

   *Anastasia Shimorina; Claire Gardent*


3. **Sequence-to-Sequence Models for Data-to-Text Natural Language Generation:Word- vs. Character-based Processing and Output Diversity** INLG, 2018 [paper](http://dx.doi.org/10.18653/v1/w18-6529) 

   *Glorianna Jagfeld; Sabrina Jenne; Ngoc Thang Vu*


4. **A Closer Look at Recent Results of Verb Selection for Data-to-Text NLG.** INLG, 2019 [paper](http://dx.doi.org/10.18653/v1/w19-8622) 

   *Guanyi Chen; Jin-Ge Yao*


5. **Neural data-to-text generation: A comparison between pipeline and end-to-end architectures** EMNLP/IJCNLP, 2019 [paper](http://dx.doi.org/10.18653/v1/d19-1052) 

   *Thiago Castro Ferreira; Chris van der Lee; Emiel van Miltenburg; Emiel Krahmer*


6. **Remodeling Numerical Representation for Text Generation on Small Corpus: A Syntactical Analysis** Proceedings of the 2019 2nd International Conference on Algorithms, Computing and Artificial Intelligence, 2019 [paper](http://dx.doi.org/10.1145/3377713.3377800) 

   *Aristotle Tan; Hui-Ngo Goh; Lai-Kuan Wong*


7. **On Hallucination and Predictive Uncertainty in Conditional Language Generation** EACL, 2021 [paper](http://dx.doi.org/10.18653/v1/2021.eacl-main.236) 

   *Yijun Xiao; William Yang Wang*




## [Models](#models)
### [Data Representation](#data-representation)
1. **Table-to-text Generation by Structure-aware Seq2seq Learning** arXiv, 2017 [paper](https://ui.adsabs.harvard.edu/abs/2017arXiv171109724L/abstract) 

   *Tianyu Liu; Kexiang Wang; Lei Sha; Baobao Chang; Zhifang Sui*


2. **A Hierarchical Model for Data-to-Text Generation** arXiv, 2019 [paper](https://ui.adsabs.harvard.edu/abs/2019arXiv191210011R/abstract) 

   *Clément Rebuffel; Laure Soulier; Geoffrey Scoutheeten; Patrick Gallinari*


3. **Data-to-Text Generation with Attention Recurrent Unit** IJCNN, 2019 [paper](http://dx.doi.org/10.1109/ijcnn.2019.8852343) 

   *Hechong Wang; Wei Zhang; Yuesheng Zhu; Zhiqiang Bai*


4. **Data-to-text Generation with Entity Modeling** ACL, 2019 [paper](http://dx.doi.org/10.18653/v1/p19-1195) 

   *Ratish Puduppully; Li Dong; Mirella Lapata*


5. **Hierarchical Encoder with Auxiliary Supervision for Neural Table-to-Text Generation: Learning Better Representation for Tables** AAAI, 2019 [paper](http://dx.doi.org/10.1609/aaai.v33i01.33016786) 

   *Tianyu Liu; Fuli Luo; Qiaolin Xia; Shuming Ma; Baobao Chang; Zhifang Sui*


6. **Table-to-Text Natural Language Generation with Unseen Schemas.** arXiv, 2019 [paper](https://arxiv.org/abs/1911.03601) 

   *Tianyu Liu; Wei Wei; William Yang Wang*


7. **A Hierarchical Model for Data-to-Text Generation** ECIR, 2020 [paper](http://dx.doi.org/10.1007/978-3-030-45439-5_5) 

   *Clément Rebuffel; Laure Soulier; Geoffrey Scoutheeten; Patrick Gallinari*


8. **Capturing Entity Hierarchy in Data-to-Text Generative Models.** CIRCLE, 2020 [paper](http://ceur-ws.org/Vol-2621/CIRCLE20_38.pdf) 

   *Clément Rebuffel; Laure Soulier; Geoffrey Scoutheeten; Patrick Gallinari*


9. **Data-to-text Generation with Pointer-Generator Networks** AEECA, 2020 [paper](http://dx.doi.org/10.1109/aeeca49918.2020.9213600) 

   *Mengzhu Liu; Zhaonan Mu; Jieping Sun; Cheng Wang*


10. **Learning Better Representation for Tables by Self-Supervised Tasks.** arXiv, 2020 [paper](http://ui.adsabs.harvard.edu/abs/2020arXiv201007606L/abstract) 

    *Liang Li; Can Ma; Yinliang Yue; Linjun Shou; Dayong Hu*


11. **Exploring Structural Encoding for Data-to-Text Generation.** INLG, 2021 [paper](https://aclanthology.org/2021.inlg-1.44) 

    *Joy Mahapatra; Utpal Garain*


12. **TABBIE: Pretrained Representations of Tabular Data** NAACL-HLT, 2021 [paper](http://dx.doi.org/10.18653/v1/2021.naacl-main.270) 

    *Hiroshi Iida; Dung Thai; Varun Manjunatha; Mohit Iyyer*




### [Content Generation](#content-generation)

#### [Semantic-accuracy](#semenatic-accuracy)
1. **Operation-guided Neural Networks for High Fidelity Data-To-Text Generation** EMNLP, 2018 [paper](http://dx.doi.org/10.18653/v1/d18-1422) 

   *Feng Nie; Jinpeng Wang; Jin-Ge Yao; Rong Pan; Chin-Yew Lin*


2. **Beyond Word for Word: Fact Guided Training for Neural Data-to-Document Generation** NLPCC, 2019 [paper](http://dx.doi.org/10.1007/978-3-030-32233-5_41) 

   *Feng Nie; Hailin Chen; Jinpeng Wang; Rong Pan; Chin-Yew Lin*


3. **Enhancing Neural Data-To-Text Generation Models with External Background Knowledge** EMNLP/IJCNLP, 2019 [paper](http://dx.doi.org/10.18653/v1/d19-1299) 

   *Shuang Chen; Jinpeng Wang; Xiaocheng Feng; Feng Jiang; Bing Qin; Chin-Yew Lin*


4. **Step-by-Step: Separating Planning from Realization in Neural Data-to-Text Generation** NAACL-HLT, 2019 [paper](http://dx.doi.org/10.18653/v1/n19-1236) 

   *Amit Moryossef; Yoav Goldberg; Ido Dagan*


5. **Sticking to the Facts: Confident Decoding for Faithful Data-to-Text Generation.** arXiv, 2019 [paper](https://arxiv.org/pdf/1910.08684.pdf) 

   *Ran Tian; Shashi Narayan; Thibault Sellam; Ankur P. Parikh*


6. **Table-to-Text Generation via Row-Aware Hierarchical Encoder** CCL, 2019 [paper](http://dx.doi.org/10.1007/978-3-030-32381-3_43) 

   *Heng Gong; Xiaocheng Feng; Bing Qin; Ting Liu*


7. **Data-to-Text Generation with Iterative Text Editing.** INLG, 2020 [paper](https://arxiv.org/pdf/2011.01694.pdf) 

   *Zdenek Kasner; Ondrej Dusek*


8. **Neural Data-to-Text Generation via Jointly Learning the Segmentation and Correspondence** ACL, 2020 [paper](http://dx.doi.org/10.18653/v1/2020.acl-main.641) 

   *Xiaoyu Shen; Ernie Chang; Hui Su; Cheng Niu; Dietrich Klakow*


9. **A case-based approach to data-to-text generation.** ICCBR, 2021 [paper](http://dx.doi.org/10.1007/978-3-030-86957-1_16) 

   *Ashish Upadhyay; Stewart Massie; Ritwik Kumar Singh; Garima Gupta; Muneendra Ojha*


10. **Attention Is Indeed All You Need: Semantically Attention-Guided Decoding for Data-to-Text NLG.** INLG, 2021 [paper](https://aclanthology.org/2021.inlg-1.45) 

    *Juraj Juraska; Marilyn A. Walker*


11. **Control Prefixes for Text Generation.** arXiv, 2021 [paper](http://export.arxiv.org/abs/2110.08329) 

    *Jordan Clive; Kris Cao; Marek Rei*


12. **Controlling hallucinations at word level in data-to-text generation** Data Mining and Knowledge Discovery, 2021 [paper](http://dx.doi.org/10.1007/s10618-021-00801-4) 

    *Clément Rebuffel; Marco Roberti; Laure Soulier; Geoffrey Scoutheeten; Rossella Cancelliere; Patrick Gallinari*


13. **Generative adversarial network for Table-to-Text generation** Neurocomputing, 2021 [paper](http://dx.doi.org/10.1016/j.neucom.2021.04.036) 

    *Jianyu Zhao; Zhiqiang Zhan; Tong Li; Rang Li; Changjian Hu; Siyun Wang; Yang Zhang*




#### [Reasoning](#reasoning)
1. **Towards Table-to-Text Generation with Numerical Reasoning** ACL/IJCNLP, 2021 [paper](http://dx.doi.org/10.18653/v1/2021.acl-long.115) 

   *Lya Hulliyyatus Suadaa; Hidetaka Kamigaito; Kotaro Funakoshi; Manabu Okumura; Hiroya Takamura*




#### [Content Planning](#content-planning)

1. **Order-Planning Neural Text Generation From Structured Data** AAAI, 2017 [paper](https://ojs.aaai.org/index.php/AAAI/article/view/11947) 

   *Lei Sha; Lili Mou; Tianyu Liu; Pascal Poupart; Sujian Li; Baobao Chang; Zhifang Sui*


2. **Data-to-Text Generation with Content Selection and Planning** AAAI, 2019 [paper](http://dx.doi.org/10.1609/aaai.v33i01.33016908) 

   *Ratish Puduppully; Li Dong; Mirella Lapata*


3. **End-to-End Content and Plan Selection for Data-to-Text Generation** INLG, 2018 [paper](http://dx.doi.org/10.18653/v1/w18-6505) 

   *Sebastian Gehrmann; Falcon Z. Dai; Henry Elder; Alexander M. Rush*


4. **Fine-Grained Control of Sentence Segmentation and Entity Positioning in Neural NLG** Proceedings of the 1st Workshop on Discourse Structure in Neural NLG, 2019 [paper](http://dx.doi.org/10.18653/v1/w19-8103) 

   *Kritika Mehta; Raheel Qader; Cyril Labbé; François Portet*


5. **Improving Quality and Efficiency in Plan-based Neural Data-to-text Generation** INLG, 2019 [paper](http://dx.doi.org/10.18653/v1/w19-8645) 

   *Amit Moryossef; Yoav Goldberg; Ido Dagan*


6. **Sentence generation for entity description with content-plan attention** AAAI, 2020 [paper](https://aaai.org/ojs/index.php/AAAI/article/download/6439/6295) 

   *Bayu Distiawan Trisedya; Jianzhong Qi; Rui Zhang*


7. **AggGen: Ordering and Aggregating while Generating** ACL/IJCNLP, 2021 [paper](http://dx.doi.org/10.18653/v1/2021.acl-long.113) 

   *Xinnuo Xu; Ondřej Dušek; Verena Rieser; Ioannis Konstas*


8. **Data-to-text Generation with Macro Planning** Transactions of the Association for Computational Linguistics, 2021 [paper](http://dx.doi.org/10.1162/tacl_a_00381) 

   *Ratish Puduppully; Mirella Lapata*


9. **Grouped-Attention for Content-Selection and Content-Plan Generation** EMNLP (Findings), 2021 [paper](https://aclanthology.org/2021.findings-emnlp.166/) 

   *Bayu Distiawan Trisedya; Xiaojie Wang; Jianzhong Qi; Rui Zhang; Qingjun Cui*


10. **Plan-then-Generate: Controlled Data-to-Text Generation via Planning** arXiv, 2021 [paper](https://arxiv.org/abs/2108.13740) 

    *Yixuan Su; David Vandyke; Sihui Wang; Yimai Fang; Nigel Collier*



### [Surface Realization](#surface-realization)

#### [Text Quality](#text-quality)

1. **Probabilistic Verb Selection for Data-to-Text Generation** Transactions of the Association for Computational Linguistics, 2018 [paper](http://dx.doi.org/10.1162/tacl_a_00038) 

   *Dell Zhang; Jiahao Yuan; Xiaoling Wang; Adam Foster*


2. **Table-to-Text: Describing Table Region With Natural Language.** AAAI, 2018 [paper](https://www.arxiv-vanity.com/papers/1805.11234/) 

   *Junwei Bao; Duyu Tang; Nan Duan; Zhao Yan; Yuanhua Lv; Ming Zhou; Tiejun Zhao*


3. **Ensuring Readability and Data-fidelity using Head-modifier Templates in Deep Type Description Generation** ACL, 2019 [paper](http://dx.doi.org/10.18653/v1/p19-1196) 

   *Jiangjie Chen; Ao Wang; Haiyun Jiang; Suo Feng; Chenguang Li; Yanghua Xiao*


4. **Long and Diverse Text Generation with Planning-based Hierarchical Variational Model** EMNLP/IJCNLP, 2019 [paper](http://dx.doi.org/10.18653/v1/d19-1321) 

   *Zhihong Shao; Minlie Huang; Jiangtao Wen; Wenfei Xu; Xiaoyan Zhu*


5. **Narrative context-based data-to-text generation for ambient intelligence** Journal of Ambient Intelligence and Humanized Computing, 2019 [paper](http://dx.doi.org/10.1007/s12652-019-01176-7) 

   *Jungsun Jang; Hyungjong Noh; Yeonsoo Lee; Soo Min Pantel; Hae-Chang Rim*


6. **Consistent Data-to-Text Generation with Topic Sequences** JSAI, 2020 [paper](https://confit.atlas.jp/guide/event/jsai2020/subject/1D5-GS-9-05/detail) 

   *Soichiro Murakami*


7. **Latent Template Induction with Gumbel-CRFs** NeurIPS, 2020 [paper](https://papers.nips.cc/paper/2020/hash/ea119a40c1592979f51819b0bd38d39d-Abstract.html) 

   *Yao Fu; Chuanqi Tan; Bin Bi; Mosha Chen; Yansong Feng; Alexander M. Rush*


8. **Learning with Contrastive Examples for Data-to-Text Generation** COLING, 2020 [paper](http://dx.doi.org/10.18653/v1/2020.coling-main.213) 

   *Yui Uehara; Tatsuya Ishigaki; Kasumi Aoki; Hiroshi Noji; Keiichi Goshima; Ichiro Kobayashi; Hiroya Takamura; Yusuke Miyao*


9. **Make Templates Smarter: A Template Based Data2Text System Powered by Text Stitch Model** EMNLP (Findings), 2020 [paper](http://dx.doi.org/10.18653/v1/2020.findings-emnlp.94) 

   *Bingfeng Luo; Bai Zuo; Kunfeng Lai; Jianping Shen*


10. **Template-Based Multi-solution Approach for Data-to-Text Generation** ADBIS, 2020 [paper](http://dx.doi.org/10.1007/978-3-030-54832-2_13) 

    *Abelardo Vieira Mota; Ticiana L. Coelho da Silva; José Antônio Fernandes de Macêdo*


11. **Variational Template Machine for Data-to-Text Generation** ICLR, 2020 [paper](https://openreview.net/pdf?id=HkejNgBtPB) 

    *Rong Ye; Wenxian Shi; Hao Zhou; Zhongyu Wei; Lei Li*


12. **A case-based approach to data-to-text generation.** ICCBR, 2021 [paper](http://dx.doi.org/10.1007/978-3-030-86957-1_16) 

    *Ashish Upadhyay; Stewart Massie; Ritwik Kumar Singh; Garima Gupta; Muneendra Ojha*


13. **De-Confounded Variational Encoder-Decoder for Logical Table-to-Text Generation** ACL/IJCNLP, 2021 [paper](http://dx.doi.org/10.18653/v1/2021.acl-long.430) 

    *Wenqing Chen; Jidong Tian; Yitian Li; Hao He; Yaohui Jin*


14. **Generative adversarial network for Table-to-Text generation** Neurocomputing, 2021 [paper](http://dx.doi.org/10.1016/j.neucom.2021.04.036) 

    *Jianyu Zhao; Zhiqiang Zhan; Tong Li; Rang Li; Changjian Hu; Siyun Wang; Yang Zhang*



#### [Writing Style](#writing-style)
1. **Data-to-Text Generation with Style Imitation** arXiv, 2019 [paper](https://ui.adsabs.harvard.edu/abs/2019arXiv190109501L/abstract) 

   *Shuai Lin; Wentao Wang; Zichao Yang; Xiaodan Liang; Frank F. Xu; Eric P. Xing; Zhiting Hu*


2. **Natural Language Generation for Non-Expert Users** Electronic Proceedings in Theoretical Computer Science, 2019 [paper](http://dx.doi.org/10.4204/eptcs.306.33) 

   *Van Nguyen; Tran Cao Son; Enrico Pontelli*


3. **Text Generation with Exemplar-based Adaptive Decoding** NAACL-HLT, 2019 [paper](http://dx.doi.org/10.18653/v1/n19-1263) 

   *Hao Peng; Ankur P. Parikh; Manaal Faruqui; Bhuwan Dhingra; Dipanjan Das*


4. **Data-to-Text Generation with Style Imitation** EMNLP, 2020 [paper](http://dx.doi.org/10.18653/v1/2020.findings-emnlp.144) 

   *Shuai Lin; Wentao Wang; Zichao Yang; Xiaodan Liang; Frank F. Xu; Eric P. Xing; Zhiting Hu*




### [Other Directions](#other-direction)

#### [Limited Data](#limited-data)
1. **A Novel Task-Oriented Text Corpus in Silent Speech Recognition and its Natural Language Generation Construction Method** NLPIR, 2019 [paper](http://dx.doi.org/10.1145/3342827.3342838) 

   *Dong Cao; Dongdong Zhang; Haibo Chen*


2. **Key Fact as Pivot: A Two-Stage Model for Low Resource Table-to-Text Generation** ACL, 2019 [paper](http://dx.doi.org/10.18653/v1/p19-1197) 

   *Shuming Ma; Pengcheng Yang; Tianyu Liu; Peng Li; Jie Zhou; Xu Sun*


3. **KGPT: Knowledge-Grounded Pre-Training for Data-to-Text Generation** EMNLP, 2020 [paper](http://dx.doi.org/10.18653/v1/2020.emnlp-main.697) 

   *Wenhu Chen; Yu Su; Xifeng Yan; William Yang Wang*


4. **TableGPT: Few-shot Table-to-Text Generation with Table Structure Reconstruction and Content Matching** COLING, 2020 [paper](http://dx.doi.org/10.18653/v1/2020.coling-main.179) 

   *Heng Gong; Yawei Sun; Xiaocheng Feng; Bing Qin; Wei Bi; Xiaojiang Liu; Ting Liu*


5. **Template-Based Multi-solution Approach for Data-to-Text Generation** ADBIS, 2020 [paper](http://dx.doi.org/10.1007/978-3-030-54832-2_13) 

   *Abelardo Vieira Mota; Ticiana L. Coelho da Silva; José Antônio Fernandes de Macêdo*


6. **Text-to-Text Pre-Training for Data-to-Text Tasks** INLG, 2020 [paper](https://arxiv.org/pdf/2005.10433.pdf) 

   *Mihir Kale*




#### [Interpretability and Controlability](#inter-control)
1. **Select and Attend: Towards Controllable Content Selection in Text Generation	EMNLP/IJCNLP** 2019, http://dx.doi.org/10.18653/v1/d19-1054 [paper](Xiaoyu Shen; Jun Suzuki; Kentaro Inui; Hui Su; Dietrich Klakow; Satoshi Sekine) 

   **


2. **Scalable Micro-planned Generation of Discourse from Structured Data	Computational Linguistics** 2019, http://dx.doi.org/10.1162/coli_a_00363 [paper](Anirban Laha; Parag Jain; Abhijit Mishra; Karthik Sankaranarayanan) 

   **


3. **Data-to-text Generation by Splicing Together Nearest Neighbors	EMNLP** 2021, https://aclanthology.org/2021.emnlp-main.352/ [paper](Sam Wiseman; Arturs Backurs; Karl Stratos) 

   **


4. **GenNI: Human-AI Collaboration for Data-Backed Text Generation.** IEEE transactions on visualization and computer graphics, 2021 [paper](http://dx.doi.org/10.1109/tvcg.2021.3114845) 

   *Hendrik Strobelt; Jambay Kinley; Robert Krueger; Johanna Beyer; Hanspeter Pfister; Alexander M. Rush*



#### [Others](#others)
1. **Towards Automatic Generation of Product Reviews from Aspect-Sentiment Scores** INLG, 2017 [paper](http://dx.doi.org/10.18653/v1/w17-3526) 

   *Hongyu Zang; Xiaojun Wan*


2. **Controlling contents in data-to-document generation with human-designed topic labels** INLG, 2019 [paper](http://dx.doi.org/10.18653/v1/w19-8640) 

   *Kasumi Aoki; Akira Miyazawa; Tatsuya Ishigaki; Tatsuya Aoki; Hiroshi Noji; Keiichi Goshima; Ichiro Kobayashi; Hiroya Takamura; Yusuke Miyao*


3. **Copy Mechanism and Tailored Training for Character-Based Data-to-Text Generation** ECML/PKDD, 2020 [paper](http://dx.doi.org/10.1007/978-3-030-46147-8_39) 

   *Marco Roberti; Giovanni Bonetta; Rossella Cancelliere; Patrick Gallinari*


4. **Machine Translation Pre-training for Data-to-Text Generation** INLG, 2020 [paper](https://arxiv.org/pdf/2004.02077.pdf) 

   *Mihir Kale; Scott Roy*


5. **Fuzzy Temporal Protoforms for the Quantitative Description of Processes in Natural Language** FUZZ-IEEE, 2021 [paper](http://dx.doi.org/10.1109/fuzz45933.2021.9494444) 

   *Yago Fontenla-Seco; Alberto Bugarín; Manuel Lama*




### [Training Methods](#training-methods)
1. **Bootstrapping Generators from Noisy Data** NAACL-HLT, 2018 [paper](http://dx.doi.org/10.18653/v1/n18-1137) 

   *Laura Perez-Beltrachini; Mirella Lapata*


2. **DORB: Dynamically Optimizing Multiple Rewards with Bandits.** EMNLP, 2020 [paper](http://dx.doi.org/10.18653/v1/2020.emnlp-main.625) 

   *Ramakanth Pasunuru; Han Guo; Mohit Bansal*


3. **PARENTing via Model-Agnostic Reinforcement Learning to Correct Pathological Behaviors in Data-to-Text Generation.** INLG, 2020 [paper](https://arxiv.org/abs/2010.10866) 

   *Clément Rebuffel; Laure Soulier; Geoffrey Scoutheeten; Patrick Gallinari*


4. **Does the Order of Training Samples Matter? Improving Neural Data-to-Text Generation with Curriculum Learning** EACL, 2021 [paper](http://dx.doi.org/10.18653/v1/2021.eacl-main.61) 

   *Ernie Chang; Hui-Syuan Yeh; Vera Demberg*


5. **On Training Instance Selection for Few-Shot Neural Text Generation** ACL/IJCNLP, 2021 [paper](http://dx.doi.org/10.18653/v1/2021.acl-short.2) 

   *Ernie Chang; Xiaoyu Shen; Hui-Syuan Yeh; Vera Demberg*


6. **Prefix-Tuning: Optimizing Continuous Prompts for Generation** ACL/IJCNLP, 2021 [paper](http://dx.doi.org/10.18653/v1/2021.acl-long.353) 

   *Xiang Lisa Li; Percy Liang*




## [Evaluation](#evaluation)

1. **Evaluating the text quality, human likeness and tailoring component of PASS: A Dutch data-to-text system for soccer** COLING, 2018 [paper](https://aclanthology.org/C18-1082/) 

   *Chris van der Lee; Bart Verduijn; Emiel Krahmer; Sander Wubben*


2. **Specificity Measures and Referential Success** IEEE Transactions on Fuzzy Systems, 2018 [paper](http://dx.doi.org/10.1109/tfuzz.2017.2694803) 

   *Nicolas Marin; Gustavo Rivas-Gervilla; Daniel Sánchez; Ronald R. Yager*


3. **Handling Divergent Reference Texts when Evaluating Table-to-Text Generation** ACL, 2019 [paper](http://dx.doi.org/10.18653/v1/p19-1483) 

   *Bhuwan Dhingra; Manaal Faruqui; Ankur P. Parikh; Ming-Wei Chang; Dipanjan Das; William W. Cohen*


4. **A Gold Standard Methodology for Evaluating Accuracy in Data-To-Text Systems** arXiv, 2020 [paper](https://arxiv.org/abs/2011.03992) 

   *Craig Thomson; Ehud Reiter*


5. **Evaluating Semantic Accuracy of Data-to-Text Generation with Natural Language Inference.** INLG, 2020 [paper](https://arxiv.org/pdf/2011.10819.pdf) 

   *Ondrej Dusek; Zdenek Kasner*


6. **Data-QuestEval: A Referenceless Metric for Data-to-Text Semantic Evaluation** EMNLP, 2021 [paper](https://aclanthology.org/2021.emnlp-main.633.pdf) 

   *Clément Rebuffel; Thomas Scialom; Laure Soulier; Benjamin Piwowarski; Sylvain Lamprier; Jacopo Staiano; Geoffrey Scoutheeten; Patrick Gallinari*


7. **Entity-Based Semantic Adequacy for Data-to-Text Generation** EMNLP (Findings), 2021 [paper](https://aclanthology.org/2021.findings-emnlp.132/) 

   *Juliette Faille; Albert Gatt; Claire Gardent*


8. **Evaluation Guidelines to Deal with Implicit Phenomena to Assess Factuality in Data-to-Text Generation** Proceedings of the 1st Workshop on Understanding Implicit and Underspecified Language, 2021 [paper](http://dx.doi.org/10.18653/v1/2021.unimplicit-1.3) 

   *Roy Eisenstadt; Michael Elhadad*


9. **Text-in-Context: Token-Level Error Detection for Table-to-Text Generation.** INLG, 2021 [paper](https://arxiv.org/pdf/2110.08467.pdf) 

   *Zdenek Kasner; Simon Mille; Ondrej Dusek*




## [Applications](#application)
1. **Generating Syntactic Paraphrases** EMNLP, 2018 [paper](http://dx.doi.org/10.18653/v1/d18-1113)

   *Emilie Colin; Claire Gardent*


2. **ESPRIT: Explaining Solutions to Physical Reasoning Tasks** ACL, 2020 [paper](http://dx.doi.org/10.18653/v1/2020.acl-main.706) 

   *Nazneen Fatema Rajani; Rui Zhang; Yi Chern Tan; Stephan Zheng; Jeremy Weiss; Aadit Vyas; Abhijit Gupta; Caiming Xiong; Richard Socher; Dragomir R. Radev*


3. **Fact-based Text Editing** ACL, 2020 [paper](http://dx.doi.org/10.18653/v1/2020.acl-main.17) 

   *Hayate Iso; Chao Qiao; Hang Li*


4. **Live Commenting of Football Games Using Machine Learning and Natural Language Generation** thesis, 2020 [paper](https://lup.lub.lu.se/student-papers/search/publication/9042563) 

   *Marcus Grönvall*


5. **Towards a Dutch FrameNet lexicon and parser using the data-to-text method** CLIN, 2020 [paper](https://www.narcis.nl/publication/RecordID/oai%3Apure.rug.nl%3Apublications%2F0d61da87-67d2-4563-9f74-fec7f762a947) 

   *Gosse Minnema; Levi Remijnse*


6. **Unsupervised Pidgin Text Generation By Pivoting English Data and Self-Training.** arXiv, 2020 [paper](https://ui.adsabs.harvard.edu/abs/2020arXiv200308272C/abstract) 

   *Ernie Chang; David Ifeoluwa Adelani; Xiaoyu Shen; Vera Demberg*




## [Thesis](#thesis)

1. **Neural generation of textual summaries from knowledge base triples** thesis, 2019 [link](https://ethos.bl.uk/OrderDetails.do?uin=uk.bl.ethos.766858) 

   *Pavlos Vougiouklis*
   
2. **Automatic generation of anomaly reports in a Train Control System: Using Natural Language Generation and Case-Based Reasoning** thesis, 2020 [link](https://repository.tudelft.nl/islandora/object/uuid%3A01b48989-2b5c-4c4a-b3bd-77f64bcad458) 

   *Þórunn Ómarsdóttir*


3. **Live Commenting of Football Games Using Machine Learning and Natural Language Generation** thesis, 2020 [link](https://lup.lub.lu.se/student-papers/search/publication/9042563) 

   *Marcus Grönvall*


4. **Table-to-Text: Generating Descriptive Text for Scientific Tables from Randomized Controlled Trials** thesis, 2020 [link](https://digitalcommons.library.tmc.edu/uthshis_dissertations/48/) 

   *Qiang Wei*


5. **Natural Language Generation : From Data Creation to Evaluation via Modelling** thesis, 2021 [link](http://www.theses.fr/2021LORR0080) 

   *Anastasia Shimorina*



