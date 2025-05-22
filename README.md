# Comparative Algorithm Analysis for Ml-based Intrusion Detection System (IDS)
This repository contains Jupyter Notebook implementations from our research on evaluating and comparing machine learning algorithms for intrusion detection systems (IDS). The analysis is performed using two prominent datasets: **NSL-KDD** and **UNSW-NB15**. Our study examines the performance of six machine learning algorithms—spanning supervised, semi-supervised, and unsupervised learning paradigms—to identify the most effective approach for modern cyber threat detection.

## 🌱 Motivation
The landscape of cybersecurity threats is continuously evolving, with new intrusion techniques emerging at a rapid pace. Traditional detection systems struggle to keep up, which makes adaptive and intelligent methods, like machine learning, essential for robust protection. This research aims to assess which algorithms are best suited to the changing threat environment and to offer practical insights for deploying IDS solutions in real-world scenarios.

## 🚀 Getting Started
To run the notebooks and reproduce our analysis:

1. **Clone the repository**
   ```bash
   git clone https://github.com/sharukat/benchmark-ml-intrusion-detection.git
   cd ml-intrusion-detection-analysis
   ```
2. **Install Dependencies**
   ```bash
   pip install -r requirements.txt
   ```
3. **Launch Jupyter Notebook**
   ```bash
   jupyter notebook
   ```

## 💻 Technology Stack
<p align="center">
  <a href="https://go-skill-icons.vercel.app/">
    <img
      src="https://go-skill-icons.vercel.app/api/icons?i=python,pandas,numpy,nextjs,matplotlib,tensorflow,jupyter,scikitlearn,"
    />
  </a>
</p>

## 📘 Want to Dive Deeper?
This work was the foundation for a published research paper:
“Comparative Algorithm Analysis for Machine Learning-Based Intrusion Detection Systems” → [Read the full paper here](https://ieeexplore.ieee.org/abstract/document/9605814?casa_token=_VcB5EJepk0AAAAA:E3E-Pt2RzwLDDlzaGyACqr2nnh-H-0L8aPLV_purSv5BCxoT5mnEjH6eHWdOSnAf4P65sF3f)

The paper provides deeper theoretical context, expanded results, and detailed discussions that go beyond the code.

## 📊 Benchmark Results
Below are a few snapshots highlighting key insights from our study:
| Model      | Dataset     | Precision | Recall  | F1-score | ROC  |
|------------|-------------|-----------|---------|----------|------|
| DNN        | NSL-KDD     | 0.9237    | 0.6775  | 0.7817   | 0.80 |
| DNN        | UNSW-NB15   | 0.6635    | 0.9330  | 0.7755   | 0.83 |
| SVM (RBF)  | NSL-KDD     | 0.9276    | 0.7081  | 0.8031   | 0.82 |
| SVM (POLY) | KDD         | 0.9248    | 0.7203  | 0.8098   | 0.82 |
| SVM (RBF)  | UNSW-NB15   | 0.6034    | 0.9804  | 0.7470   | 0.80 |
| SVM (POLY) | NB15        | 0.6054    | 0.9717  | 0.7460   | 0.80 |
| K-NN       | NSL-KDD     | 0.9587    | 0.6566  | 0.7794   | 0.81 |
| K-NN       | UNSW-NB15   | 0.6508    | 0.9382  | 0.7685   | 0.82 |
| One-Class SVM | NSL-KDD  | 0.9739    | 0.6497  | 0.7794   | 0.82 |
| One-Class SVM | UNSW-NB15| 0.9188    | 0.4088  | 0.5658   | 0.67 |
| K-Means    | NSL-KDD     | 0.9847    | 0.5473  | 0.7036   | 0.76 |
| K-Means    | UNSW-NB15   | 0.4865    | 0.9896  | 0.6523   | 0.66 |
| EM         | NSL-KDD     | 0.9837    | 0.5557  | 0.7102   | 0.76 |
| EM         | UNSW-NB15   | 0.5478    | 0.9953  | 0.7067   | 0.73 |


## 🤝 Contributing & Reproducibility
This repository serves as a benchmark research project for evaluating machine learning algorithms in the context of intrusion detection systems using the NSL-KDD and UNSW-NB15 datasets.

Researchers, students, and practitioners are welcome to:

- 🔁 **Replicate** the experiments
- 🔬 **Reproduce** the results
- 🚀 **Extend** the work with new datasets, models, or techniques
- 🧠 **Analyze** and interpret the findings in new ways

### How to Get Involved

1. **Fork the repository**
   Create your own copy by clicking the **"Fork"** button at the top right.

2. **Clone your fork locally**
   ```bash
   git clone https://github.com/sharukat/benchmark-ml-intrusion-detection.git
   cd ml-intrusion-detection-analysis
   ```
3. **Set up the environment**
   ```bash
   pip install -r requirements.txt
   ```
4.	**Explore and modify the notebooks**
The core experiments are implemented in Jupyter notebooks. You can run, edit, or extend them based on your research goals.
5.	**Cite or credit the work**
If you use or adapt this work for a publication or project, a citation or acknowledgment is appreciated. See the “Citation” section below (add this if you include a BibTeX entry).

## Citation
```
@INPROCEEDINGS{9605814,
  author={Thirimanne, Sharuka and Jayawardana, Lasitha and Liyanaarachchi, Pushpika and Yasakethu, Lasith},
  booktitle={2021 10th International Conference on Information and Automation for Sustainability (ICIAfS)}, 
  title={Comparative Algorithm Analysis for Machine Learning Based Intrusion Detection System}, 
  year={2021},
  volume={},
  number={},
  pages={191-196},
  keywords={Support vector machines;Deep learning;Machine learning algorithms;Automation;Supervised learning;Intrusion detection;Classification algorithms;Intrusion Detection;Supervised Learning;Semi-supervised Learning;Unsupervised Learning},
  doi={10.1109/ICIAfS52090.2021.9605814}}
```
   
