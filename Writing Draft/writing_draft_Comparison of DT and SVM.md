In the Data Analysis section, various machine learning techniques were applied to the dataset. Upon analysis of the Decision Tree (DT), Random Forest (RF), and Support Vector Machine (SVM) models, each exhibited distinct performance characteristics.

The DT model achieved an overall accuracy of 0.52. For the 'high' category, the model demonstrated precision, recall, and F1-score of 0.64, 0.68, and 0.66, respectively, with 663 samples. For the 'low' category, both precision and recall were 0.23, the F1-score was 0.23, with 126 samples. For the 'mixed' category, the model showed precision of 0.33, recall of 0.28, and an F1-score of 0.31, with 304 samples.

On the other hand, the RF model obtained a higher overall accuracy of 0.61. For the 'high' category, the RF model exhibited a perfect recall and a substantial precision of 0.61, yielding an F1-score of 0.76. However, the model performed significantly less well for the 'low' and 'mixed' categories, achieving F1-scores of 0.05 and 0.02, respectively, while also showing lower precision and recall for these classes.

Lastly, the SVM model also achieved an overall accuracy of 0.61, similar to RF. However, it outperformed the RF model in precision for the 'mixed' category, scoring 0.83. Nevertheless, the SVM model demonstrated a very low recall for the 'low' and 'mixed' categories, which substantially impacted these categories' F1-scores, reducing them to 0.03.

In summary, the performance of these models varies. While the DT model has a lower overall accuracy, it is more balanced across the categories. In contrast, although the RF and SVM models have higher overall accuracy, their performance is considerably skewed towards the 'high' category. This suggests that these models may not generalize well across various data. For the 'low' and 'mixed' categories, all models performed less well. This could be due to the smaller amount of data available for these categories, resulting in poorer performance during model learning. These findings align with those of a study by Mahmudul Hasan and Md. Milon Islam (reference), in which the authors found that while Decision Tree, Random Forest, and ANN all achieved a test accuracy of 99.4%, other evaluation metrics indicated relatively better performance by Random Forest.


Reference

Hasan, M., Islam, Md. M., Zarif, M. I. I., & Hashem, M. M. A. (2019). Attack and anomaly detection in IoT sensors in IoT sites using machine learning approaches. Internet of Things, 7, 100059. https://doi.org/10.1016/j.iot.2019.100059
