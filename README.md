# CoHS-CQG: Context and History Selection for Conversational Question Generation (COLING 2022)

Code and data for the ACL 2023 paper: https://aclanthology.org/2022.coling-1.48/

*Note: All the data can be found [here](https://drive.google.com/drive/folders/1-1b1wgocLxS-QRkUGIjr3Wr8wWtyu3H6?usp=sharing).*

## 1. About the Notebook
- Notebook ```CoHS_CQG_Context_History_Selection.ipynb``` contains codes to shorten the context and history in the CoQA dataset. 

## 2. Pre-requisites Softwares
Please check the two notebooks for different setups.

## 3. Reference
Any question, please email directly to **Do Xuan Long** via email: *xuanlong.do@u.nus.edu*.

If you have found the codes helpful, please consider to cite the paper:

```
@inproceedings{do-etal-2022-cohs,
    title = "{C}o{HS}-{CQG}: Context and History Selection for Conversational Question Generation",
    author = "Do, Xuan Long  and
      Zou, Bowei  and
      Pan, Liangming  and
      Chen, Nancy F.  and
      Joty, Shafiq  and
      Aw, Ai Ti",
    booktitle = "Proceedings of the 29th International Conference on Computational Linguistics",
    month = oct,
    year = "2022",
    address = "Gyeongju, Republic of Korea",
    publisher = "International Committee on Computational Linguistics",
    url = "https://aclanthology.org/2022.coling-1.48",
    pages = "580--591",
    abstract = "Conversational question generation (CQG) serves as a vital task for machines to assist humans, such as interactive reading comprehension, through conversations. Compared to traditional single-turn question generation (SQG), CQG is more challenging in the sense that the generated question is required not only to be meaningful, but also to align with the provided conversation. Previous studies mainly focus on how to model the flow and alignment of the conversation, but do not thoroughly study which parts of the context and history are necessary for the model. We believe that shortening the context and history is crucial as it can help the model to optimise more on the conversational alignment property. To this end, we propose CoHS-CQG, a two-stage CQG framework, which adopts a novel CoHS module to shorten the context and history of the input. In particular, it selects the top-p sentences and history turns by calculating the relevance scores of them. Our model achieves state-of-the-art performances on CoQA in both the answer-aware and answer-unaware settings.",
}
```

