## MMVQA: A Comprehensive Dataset for Investigating Multipage Multimodal Information Retrieval in PDF-based Visual Question Answering
Document Question Answering (QA) presents a challenge in understanding visually rich documents (VRD), particularly those dominated by lengthy textual content such as research journal articles. Existing studies primarily focus on real-world documents with sparse text, while challenges persist in comprehending hierarchical semantic relations among multiple pages to locate multimodal components. To address this gap, we propose MMVQA, which is tailored for research journal articles, encompassing multiple pages and multimodal information retrieval. Unlike traditional machine reading comprehension (MRC) tasks, our approach aims to retrieve entire paragraphs containing answers or visually rich document entities like tables and figures. Our contributions include the introduction of a comprehensive PDF Document VQA dataset, allowing the examination of semantically hierarchical layout structures in text-dominant documents. We also present new VRD-QA frameworks designed to grasp textual contents and relations among document layouts simultaneously, extending page-level understanding to the entire multi-page document. Through this work, our goal is to enhance the capabilities of existing vision and language models in handling challenges posed by text-dominant documents in VRD-QA.

## Dataset Link
We are excited to announce that we will be organizing a competition at an upcoming top-tier conference, utilizing the MMVQA dataset. Participants will have the opportunity to showcase their skills in multimodal visual question answering, using one of the most advanced datasets in the field.

In preparation for the competition, we will be releasing the training and validation sets in advance. Participants are encouraged to start familiarizing themselves with the data and begin their model development. Please note that the competition version of the dataset may differ slightly from the originally released version, reflecting the specific scope and task design of the competition.

A leaderboard will be made available shortly, along with a comprehensive tutorial and detailed instructions to guide participants through the competition process. Stay tuned for more updates and information, which will be released soon.

We look forward to your participation and to seeing the innovative approaches that will emerge from this competition!

### Structured Document Files
The ".pkl" files contain the structural information from the post-processed documents. 

[Training Set](https://drive.google.com/file/d/1AtZaq3M_tCVoTgyp7xxSvXwO0-cs_HFM/view?usp=sharing)

[Validation Set](https://drive.google.com/file/d/1-IkjobifE3khiJxh53AzGCPWTtCHdKyH/view?usp=drive_link)
### Question Answer Pairs
The ".csv" files contain the question-answering pairs with additional information. 

[Training Set](https://drive.google.com/file/d/1-BVyeBf0E_9H9JZVupEgIwoGm_B-8YBR/view?usp=drive_link)

[Validation Set](https://drive.google.com/file/d/1-IkjobifE3khiJxh53AzGCPWTtCHdKyH/view?usp=drive_link)
### Link to the Document Images
The collected document image information. 

[Image_Part1](https://drive.google.com/drive/folders/120dvYlID_D8cZ5-lOYHyu1WuHRKEMac6?usp=drive_link)

[Image_Part2](https://drive.google.com/drive/folders/13JjcYgsH8bjY4W076HJ4apI9tHK5PWfO?usp=drive_link)



## Note 
We are happy to share raw PDF files for your information. However, please note that these are the raw PDF files and are not clean or preprocessed. Just for your reference.
[Raw XML Files](https://drive.google.com/drive/folders/16MN9Q5Va2PE3stNCx42nLzEXvhXtIXMf?usp=drive_link)
[Raw PDF Files](https://drive.google.com/drive/folders/1kZ5oaFXHwuv1mpBOceAb5SThi3LgcSzo?usp=drive_link)

## Citation

If you use our work or dataset in your research, please cite our paper:

```bibtex
@article{dingmmvqa,
  title={MMVQA: A Comprehensive Dataset for Investigating Multipage Multimodal Information Retrieval in PDF-based Visual Question Answering},
  author={Ding, Yihao and Ren, Kaixuan and Huang, Jiabin and Luo, Siwen and Han, Soyeon Caren},
  journal={the 33rd International Joint Conference on Artificial Intelligence},
  year={2024}
}
