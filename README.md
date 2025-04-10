# CA School Board Policy Natural Language Processing 

<img width="429" alt="Screenshot 2025-02-18 at 5 49 11 PM" src="https://github.com/user-attachments/assets/04a36a3b-9d92-4d75-9c98-579b9f140983" />

In preliminary analysis, I examined the relationship between California school district policies (BP & AR 3514.1) and their sustainability scores using natural language processing methods. Despite extensive text analysis, including word count, frequency comparisons, and semantic similarity using sentence embeddings, I found no significant correlation between word count or cosine similarity and sustainability outcomes. Notably, even the most semantically similar policies varied widely in their scores, suggesting that surface-level or structural similarities in language may not reliably predict sustainability strength. 

In a follow-up analysis, I explored the relationship between specific environmental indicators, policy language intensity (“Scoville Scale”), and sustainability scores. Using keyword-based embeddings and dimensionality reduction, I analyzed the presence of key environmental strategies—such as hazardous materials management and zero waste initiatives—across BP 3514.1 and BP 3511.1. While most findings revealed no statistically significant link between language similarity and sustainability outcomes, one notable result suggested that “mild” language related to conservation education may positively influence scores, whereas “spicy” language tied to external collaboration may have a negative impact. However, these results came with caveats due to low model reliability and multicollinearity. Overall, the analysis reinforced that textual features alone may not reliably predict environmental implementation. Although these findings are limited, my recommendation was to spend less time customizing school board policies, and further investigate aspects that do have an effect on implementation. 

*Data*
- contains downloaded pdfs from Board Policiy and Authoritative Regulation 3514.1 (Hazardous Substances), and Board Policy 3511.1 (Integrated Waste Management)
- contains excel file with school district level data and path to pdf file for text extraction

*utils*
- contains .py file with fuctions for text extraction

*cleaned_data*
- contains excel files with cleaned and extracted textual data for each school district

*notebooks*
- contains .ipynb files with detailed code for extracting and cleaning textual data, as well as full analysis notebooks
