# PDTW150K Dataset
In this repository, we provide the dataset as described in the following paper:

Chan-Ming Hsu, Tse-Hung Lin, Yu-Hsien Chen, and Chih-Yi Chiu.PDTW150K: A Dataset for Patent Drawing Retrieval.

We introduce a new large-scale patent dataset termed PDTW150K for patent drawing retrieval. The dataset contains more than 150,000 patents associated with text metadata and over 850,000 patent drawings. In addition, a set of bounding box positions of individual drawing views is provided to support constructing semantic segmentation and object detection models. We demonstrate the possible ways of using PDTW150K, including image retrieval, cross-modal retrieval, and object detection tasks.


![table 1](figures/PDTW150K-fig2.PNG)



| **#patents**   | Large   | Small    | **#drawings**  | Large   | Small   |
|------------|---------|----------|------------|---------|---------|
| Train      | 79,399  | 14,979   | Train      | 448,316 | 80,330  |
| Validation | 19,958  | 4,998    | Validation | 113,284 | 26,586  |
| Test       | 27,915  | 5,000    | Test       | 157,838 | 26,947  |
| Total      | 127,272 | 24,977   | Total      | 719,438 | 133,863 |

Table 2. The numbers of patents and drawings of the train, validation, and test sets in large and small parts of PDTW105K.

# Example images from the dataset
![fig 1](figures/PDTW150K-fig1.png)

Fig. 1. An example of two patent drawings with auxiliary information, where the left drawing has one view, and the right drawing has two views.


| <span style="font-weight:normal">Patent Number (PN)</span>          | TW127824                                                                                                                                                                                                                                                                                          |
|-----------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Title (TI)                  | 冰塊結構 (Ice Cube Structure)                                                                                                                                                                                                                                                                     |
| Issued Date (ID)            | 19900121                                                                                                                                                                                                                                                                                          |
| Locarno classification (LC) | 01-01                                                                                                                                                                                                                                                                                             |
| Abstract (AB)               | 圖１為本新式樣之「冰塊結構」之形狀；圖２為其正面圖；圖３為其頂面圖；圖４為其側面圖，另一側面相同；圖５為其底面圖。本創作之特徵在於其整體之造型，其中：一較大角錐體中具有四個較小之角錐體，該諸較小角錐體間以形成於其間之錐谷子以分隔。大角錐體之外緣係為圓弧狀。 整體觀之，本創作確為一特異之作。 |


Table 1. An example of metadata of the patent “Ice Cube Structure.”

# Get the Dataset
The dataset has been compressed and split into 2 parts. To decompress the dataset, please download all of the parts into a single folder and combine them into a single

* Small part ([whole](https://drive.google.com/drive/folders/1FmGmE5yeiJB-SpoL1brCyrFUZGDcbQJg))

* Large part ([partition_1](https://drive.google.com/drive/folders/1SqoKJxhSMdZ9yhVltzo_RFBPx0tkwWRH?usp=sharing), [partition_2](https://drive.google.com/drive/folders/1E0jySfdlLrRf4oUT9ntpwq1wbgnn9v_A?usp=sharing), [partition_3](https://drive.google.com/drive/folders/1T02cEnvxAQGZRXLggeaB89PaiaLcP3oA?usp=sharing))


More information and datasets will be available for download later.
