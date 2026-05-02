---
layout: post
title: "METASPACE: bringing metabolomics data analysis to the cloud"
date: 2026-05-02
categories: [biomedicine, cloud-computing, metabolomics]
---

<style>
.post-content p {
  text-align: justify;
}
</style>

## METASPACE: Exploring Spatial Metabolomics in the Cloud

Biomedical research is producing increasingly large and complex datasets. This is especially true in omics sciences, where technologies such as genomics, proteomics and metabolomics generate massive amounts of biological information. In metabolomics, researchers study small molecules that reflect the biochemical state of cells, tissues and organisms. These molecules can provide valuable information about health and disease, including cancer, metabolic disorders and inflammatory processes.

However, analysing metabolomics data is not simple. Mass spectrometry and nuclear magnetic resonance technologies can produce large datasets that require specific computational tools, data processing workflows and statistical analysis. As Peters et al. explain in their article about PhenoMeNal, metabolomics data analysis is computationally intensive and often requires open data formats, repositories and interoperable tools (Peters et al., 2019). This is one of the reasons why cloud computing has become increasingly relevant in biomedical research.

### Why cloud computing matters in metabolomics

Cloud computing allows researchers to process data using remote computational resources instead of relying only on their own computers. This is useful because metabolomics datasets can be too large or too complex to analyse locally. Cloud platforms can provide scalable storage, computational power, data sharing and access to specialised bioinformatic tools.

Warth et al. describe several advantages of cloud-based bioinformatic platforms, including easier data sharing, standardised formats, distributed data processing and global access without the need for expensive local hardware. These features are particularly important in omics research, where researchers from different institutions often need to analyse and compare large datasets (Warth et al., 2017).

Cloud-based platforms also support reproducibility. If workflows, parameters and results are stored and shared in the same environment, other researchers can better understand how an analysis was performed and potentially repeat or adapt it. This is a key issue in biomedical research, where reproducibility and transparency are essential.

### What is METASPACE?

METASPACE is a cloud-based platform for spatial metabolomics. More specifically, it is designed for the annotation and interpretation of imaging mass spectrometry data. Imaging mass spectrometry allows researchers to study where metabolites are located within a tissue section. Instead of only knowing that a metabolite is present in a sample, researchers can visualise its spatial distribution.

<img width="1327" height="564" alt="image" src="https://github.com/user-attachments/assets/d40b6f5f-3b7a-4fc1-9281-03785df0748b" />
*Figure 1. METASPACE homepage. The platform is presented as a web-based tool for metabolite annotation of imaging mass spectrometry data, allowing users to upload datasets, explore annotations and access community resources.*


This is especially interesting in biomedicine because tissues are heterogeneous. For example, in cancer research, different regions of a tumour may have different metabolic profiles. Some areas may be more proliferative, hypoxic or necrotic than others. A spatial metabolomics platform such as METASPACE can help researchers explore these molecular differences directly in the tissue context.

METASPACE works as an online environment where users can upload imaging mass spectrometry datasets, perform metabolite annotation and visualise results. It also acts as a community-populated knowledge base, meaning that public datasets can contribute to a larger resource of annotated spatial metabolomes.

<img width="1341" height="589" alt="image" src="https://github.com/user-attachments/assets/a1318cf2-f590-4b44-8429-2409c6741fb3" />
*Figure 2. METASPACE allows users to explore putative metabolite annotations and visualise where a selected molecular ion is distributed within a tissue section. This illustrates how cloud-based tools can make complex spatial metabolomics data easier to inspect and share.*


### Why METASPACE is a good example of a biomedical cloud application

METASPACE illustrates many of the benefits described in the cloud metabolomics literature. First, it makes complex data analysis more accessible. Researchers do not need to build the entire computational infrastructure themselves, because the analysis is performed through a web-based platform.

Second, it supports data sharing and comparison between studies. This is important because metabolomics results can be difficult to compare if each laboratory uses different tools, parameters and annotation strategies.

Third, METASPACE contributes to reproducibility. In metabolomics, annotation is one of the most challenging steps. A cloud platform can help standardise this process and make results more transparent.

Finally, METASPACE is particularly valuable because it focuses on spatial information. Many metabolomics studies analyse homogenised samples, where the original tissue structure is lost. Spatial metabolomics preserves this context and can therefore provide more biologically meaningful information.

### Connection with PhenoMeNal and other cloud metabolomics tools

The PhenoMeNal project is another important example of cloud-based metabolomics infrastructure. PhenoMeNal was designed to integrate open-source tools into reproducible workflows using technologies such as Docker containers, Kubernetes and user-friendly interfaces including Galaxy and Jupyter. The goal was to provide researchers with scalable, interoperable and reproducible metabolomics workflows.

Although PhenoMeNal and METASPACE are not the same type of platform, they respond to similar needs: metabolomics data are complex, computationally demanding and require standardised analysis tools. Both examples show how cloud computing can help transform metabolomics into a more accessible and collaborative field.

Warth et al. also highlight XCMS Online as an example of how cloud computing can make untargeted metabolomics analysis available to a global research community. In the same way, METASPACE extends this idea to imaging mass spectrometry and spatial metabolomics.

### Challenges and limitations

Despite its advantages, cloud computing in biomedicine also has limitations. One important issue is data privacy. Biomedical datasets may contain sensitive information, especially when they are linked to human samples or clinical metadata. Therefore, cloud platforms must use secure infrastructures and comply with ethical and legal requirements.

Another limitation is internet dependency. Uploading large imaging mass spectrometry datasets can be slow, and users need stable internet connections. In addition, although cloud platforms simplify analysis, users still need to understand the biological meaning of the results and the limitations of metabolite annotation.

Finally, cloud tools should avoid becoming “black boxes”. Researchers need transparency about algorithms, parameters and databases used for annotation. This is essential to interpret the results correctly.

### Conclusion

METASPACE is a clear example of how cloud computing can support biomedical research. Enabling online analysis, annotation, visualisation and sharing of imaging mass spectrometry data, it makes spatial metabolomics more accessible and reproducible.

Cloud-based metabolomics platforms such as METASPACE, PhenoMeNal and XCMS Online show that the future of biomedical data analysis will not only depend on generating more data, but also on creating better infrastructures to process, share and interpret that data. In this context, cloud computing is becoming an essential tool for modern biomedicine.

### References

Warth, B., Levin, N., Rinehart, D., Teijaro, J., Benton, H. P., & Siuzdak, G. (2017). Metabolizing Data in the Cloud. Trends in biotechnology, 35(6), 481–483. https://doi.org/10.1016/j.tibtech.2016.12.010

Peters, K., Bradbury, J., Bergmann, S., et al. (2019). PhenoMeNal: processing and analysis of metabolomics data in the cloud. *GigaScience*, 8(2), giy149. https://doi.org/10.1093/gigascience/giy149

METASPACE. Spatial metabolomics platform. https://metaspace2020.org/

METASPACE GitHub repository. Cloud engine and platform for metabolite annotation of imaging mass spectrometry data. https://github.com/metaspace2020/metaspace

