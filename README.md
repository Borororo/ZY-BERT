# TCM-SD dataset and ZY-BERT 

The related paper "TCM-SD: A Benchmark for Probing Syndrome Differentiation via Natural Language Processing" was published in CCL2022.



![](https://s3.bmp.ovh/imgs/2022/10/13/c5b54b7696504507.png)

### Dataset Info.

**TCM_SD_with_knowledge** Contains the full data! 

You can find more details about the dataset at ([here](https://tianchi.aliyun.com/dataset/dataDetail?dataId=139034)).

**TCM Data Sample** Contains the multiple samples from TCM-SD dataset.



We uploaded the corpus used for pretraining ZY-BERT, download via ([here](https://www.dropbox.com/s/jrgngr8afqz41oy/tcm_pretrain_corpus_a.rar?dl=0)).
To be noticed, the current released version does not contains academic papers and journals from CNKI for some reasons(you know why:>). But I would keep updating and enriching the corpus, please keep in mind.


The dataset is licensed by [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/?spm=5176.12282016.0.0.60246d92uOnf7v)。

### Model Info. 

Pre-trained ZY-BERT could be downloaded at [here](https://drive.google.com/file/d/1fC9geqeLk5YK9y_O-UjfIKtLeu0Iie8j/view?usp=sharing)





### Code Info.

**TCM Code**  contains the codes for completing syndrome differentiation task using Bert-like language model.



### Contact Info.

Email: renm@nuist.edu.cn or rdoctmc@gmail.com

Issue is welcome!



### Cite

If you used this in your work, please cite:

```
@inproceedings{mucheng-etal-2022-tcm,
    title = "{TCM}-{SD}: A Benchmark for Probing Syndrome Differentiation via Natural Language Processing",
    author = "Ren, Mucheng  and
      Huang, Heyan  and
      Zhou, Yuxiang  and
      Cao, Qianwen  and
      Bu, Yuan  and
      Gao, Yang",
    booktitle = "Proceedings of the 21st Chinese National Conference on Computational Linguistics",
    month = oct,
    year = "2022",
    address = "Nanchang, China",
    publisher = "Chinese Information Processing Society of China",
    url = "https://aclanthology.org/2022.ccl-1.80",
    pages = "908--920",
    abstract = "{``}Traditional Chinese Medicine (TCM) is a natural, safe, and effective therapy that has spread and been applied worldwide. The unique TCM diagnosis and treatment system requires a comprehensive analysis of a patient{'}s symptoms hidden in the clinical record written in free text. Prior studies have shown that this system can be informationized and intelligentized with the aid of artificial intelligence (AI) technology, such as natural language processing (NLP). However, existing datasets are not of sufficient quality nor quantity to support the further development of data-driven AI technology in TCM. Therefore, in this paper, we focus on the core task of the TCM diagnosis and treatment system{---}syndrome differentiation (SD){---}and we introduce the first public large-scale benchmark for SD, called TCM-SD. Our benchmark contains 54,152 real-world clinical records covering 148 syndromes. Furthermore, we collect a large-scale unlabelled textual corpus in the field of TCM and propose a domain-specific pre-trained language model, called ZYBERT. We conducted experiments using deep neural networks to establish a strong performance baseline, reveal various challenges in SD, and prove the potential of domain-specific pre-trained language model. Our study and analysis reveal opportunities for incorporating computer science and linguistics knowledge to explore the empirical validity of TCM theories.{''}",
    language = "English",
}
```

