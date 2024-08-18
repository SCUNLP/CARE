# Procedure Automation

Platform for our ACL 2024 Paper "[CARE: A Clue-guided Assistant for CSRs to Read User Manuals](https://arxiv.org/abs/2408.03633)"

## Why Procedure Automation ?
It is time-saving to build a platform for users when dealing with procedural documents, especially information-rich ones. We propose to develop a time-saving and careful platform for users who need to read, understand and apply procedural documents, which can help them quickly find desired information via explicit clue chains. Specifically, each of the clue chains is formed by inferring over the procedural documents, starting from the node aligned with the user question and ending at a possible response.

## Code
The platform will be released soon ...

If you find our platform useful for your research and applications, please kindly cite using this BibTeX:

```latex
@inproceedings{du-etal-2024-care,
    title = "{CARE}: A Clue-guided Assistant for {CSR}s to Read User Manuals",
    author = "Du, Weihong  and
      Liu, Jia  and
      Wen, Zujie  and
      Jin, Dingnan  and
      Liang, Hongru  and
      Lei, Wenqiang",
    editor = "Ku, Lun-Wei  and
      Martins, Andre  and
      Srikumar, Vivek",
    booktitle = "Proceedings of the 62nd Annual Meeting of the Association for Computational Linguistics (Volume 1: Long Papers)",
    month = aug,
    year = "2024",
    address = "Bangkok, Thailand",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2024.acl-long.581",
    pages = "10795--10811",
    abstract = "It is time-saving to build a reading assistant for customer service representations (CSRs) when reading user manuals, especially information-rich ones. Current solutions don{'}t fit the online custom service scenarios well due to the lack of attention to user questions and possible responses. Hence, we propose to develop a time-saving and careful reading assistant for CSRs, named CARE. It can help the CSRs quickly find proper responses from the user manuals via explicit clue chains. Specifically, each of the clue chains is formed by inferring over the user manuals, starting from the question clue aligned with the user question and ending at a possible response. To overcome the shortage of supervised data, we adopt the self-supervised strategy for model learning. The offline experiment shows that CARE is efficient in automatically inferring accurate responses from the user manual. The online experiment further demonstrates the superiority of CARE to reduce CSRs{'} reading burden and keep high service quality, in particular with {\textgreater}35{\%} decrease in time spent and keeping a {\textgreater}0.75 ICC score.",
}
```
