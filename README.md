### Deciphering Machine Learning Decisions to Distinguish between Posterior Fossa Tumor Types Using MRI Features: What Do the Data Tell Us?

The clinical challenges posed by pediatric brain tumors are significant because of their diverse characteristics and overlapping imaging features. In order to address this issue, a growing body of research has shifted towards utilizing machine learning methodologies, and ML models now have the ability to make decisions that carry risk on our behalf, but because these models are complex, interpreting their decisions can be difficult, and it is not always possible for humans to control them. As we proposed in this paper, pre-analysis of data during the development of a machine learning model can improve the interpretability of the results. 

Kernel density estimation method is a useful technique that can reveal important distribution patterns in pediatric posterior fossa tumors, which can help with their identification and classification.

The selection of a data sampling method can have a significant impact on the performance and feature selection of machine learning models. Therefore, it is crucial to carefully consider and optimize this step in the modeling process.

The source codes, EDA outputs and entire ML evaluation results of the presented study can be found as below.

<pre style="font-family:Menlo,'DejaVu Sans Mono',consolas,'Courier New',monospace">🗂 Repository Map                                                                             
<span style="color: #808080; text-decoration-color: #808080">┣━━ </span><span style="font-weight: bold">⭐ src</span>
<span style="color: #808080; text-decoration-color: #808080">┃   ┣━━ </span><span style="font-weight: bold">eda.ipynb</span>
<span style="color: #808080; text-decoration-color: #808080">┃   ┣━━ </span><span style="font-weight: bold">main.ipynb</span>
<span style="color: #808080; text-decoration-color: #808080">┣━━ </span>⭐ eda                                                                 
<span style="color: #808080; text-decoration-color: #808080">┃   ┣━━ </span><span style="font-weight: bold">Analysis 1</span>
<span style="color: #808080; text-decoration-color: #808080">┃   ┣━━ </span><span style="font-weight: bold">Analysis 2</span> 
<span style="color: #808080; text-decoration-color: #808080">┃   ┣━━ </span><span style="font-weight: bold">Analysis 3</span>
<span style="color: #808080; text-decoration-color: #808080">┃   ┣━━ </span><span style="font-weight: bold">Analysis 4</span>
<span style="color: #808080; text-decoration-color: #808080">┃   ┣━━ </span><span style="font-weight: bold">Analysis 5</span>
<span style="color: #808080; text-decoration-color: #808080">┗━━ </span><span style="font-weight: bold">⭐ evaluation</span>
<span style="color: #808080; text-decoration-color: #808080">    ┗━━ </span><span style="font-weight: bold">evaluations.zip</span>
</pre>

### Citation - *BibTeX:*

```
@article{tanyel2023deciphering,
  title={Deciphering Machine Learning Decisions to Distinguish between Posterior Fossa Tumor Types Using MRI Features: What Do the Data Tell Us?},
  author={Tanyel, Toygar and Nadarajan, Chandran and Duc, Nguyen Minh and Keserci, Bilgin},
  journal={Cancers},
  volume={15},
  number={16},
  pages={4015},
  year={2023},
  publisher={MDPI}
}

doi: https://doi.org/10.3390/cancers15164015
```


#### Examples from Analyses:

<pre>

   <img width="370" alt="image" src="https://user-images.githubusercontent.com/44132720/231159201-2d69bc11-f3df-4e3e-b3a8-633ff736c0eb.png">       <img width="480" alt="image" src="https://user-images.githubusercontent.com/44132720/231159301-b5a9b10f-40b5-4800-b18e-eeea20874192.png">
   
       Pairplot with KDE diagonals for ADC                         KDE plot for FLAIR_Tumor feature
</pre>
