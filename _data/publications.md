---
title: Publications
layout: single
---

# Publications

This page lists peer-reviewed publications. For citation export and complete records, visit my [Google Scholar](https://scholar.google.com/citations?user=VZdE1t8AAAAJ&hl=en).

{% for p in site.data.publications.journals %}
## {{ p.section_title }}
{% break %}
{% endfor %}

{% assign journals = site.data.publications.journals %}
{% if journals %}
### Refereed Journal Publications
{% for item in journals %}
- **{{ item.authors }}**, *{{ item.title }}*, _{{ item.journal }}_, {{ item.year }}. {% if item.doi %}[DOI]({{ item.doi }}){% endif %} {% if item.note %} — {{ item.note }}{% endif %}
{% endfor %}
{% endif %}

{% if site.data.publications.conferences %}
### Refereed Conference Publications
{% for item in site.data.publications.conferences %}
- **{{ item.authors }}**, *{{ item.title }}*, _{{ item.venue }}_, {{ item.year }}. {% if item.doi %}[Link]({{ item.doi }}){% endif %}
{% endfor %}
{% endif %}

{% if site.data.publications.book_chapters %}
### Book Chapters
{% for item in site.data.publications.book_chapters %}
- **{{ item.authors }}**, *{{ item.title }}*, in {{ item.book }}, {{ item.year }}. {% if item.doi %}[DOI]({{ item.doi }}){% endif %}
{% endfor %}
{% endif %}

{% if site.data.publications.book_editor %}
### Book Editor
{% for item in site.data.publications.book_editor %}
- **{{ item.authors }}**, _{{ item.title }}_, {{ item.year }}.
{% endfor %}
{% endif %}
journals:
  - authors: "G. Sambasivam, G. Prabu Kanna, Munesh Singh Chauhan, Prem Raja, Yogesh Kumar"
    title: "A Hybrid Deep Learning Model Approach for Automated Detection and Classification of Cassava Leaf Diseases"
    journal: "Scientific Reports (Sci Rep)"
    year: 2025
    doi: "https://doi.org/10.1038/s41598-025-90646-4"
    note: "Indexed in SCIE & Scopus. Q1. Impact Factor: 3.8"

  - authors: "G. Sambasivam, J. Amudhavel and G. Sathya"
    title: "A Predictive Performance Analysis of Vitamin D Deficiency Severity using Machine Learning Methods"
    journal: "IEEE Access"
    year: 2020
    doi: "https://doi.org/10.1109/ACCESS.2020.3002191"
    note: "Indexed in SCIE & Scopus. Q1. Impact Factor: 3.9"

  - authors: "G. Sambasivam and Geoffrey Duncan Opiyo"
    title: "A Predictive Machine Learning Application in Agriculture : Cassava Disease Detection and Classification with Imbalanced Dataset using Convolutional Neural Networks"
    journal: "Egyptian Informatics Journal"
    year: 2021
    doi: "https://doi.org/10.1016/j.eij.2020.02.007"
    note: "Indexed in SCIE & Scopus. Q1. Impact Factor: 5.2"

  - authors: "Chandramohan Dhasarathan, Sambasivam Gnanasekaran, et al."
    title: "Tensor RT optimized driver drowsiness detection system using edge device"
    journal: "Ain Shams Engineering Journal"
    year: 2025
    doi: "https://doi.org/10.1016/j.asej.2025.103620"
    note: "Indexed in SCIE & Scopus. Q1. Impact Factor: 5.9"

  - authors: "R.G. Babukarthik, V. Ananth Krishna Adiga, G. Sambasivam, D. Chandramohan and J. Amudhavel"
    title: "Prediction of COVID-19 using Genetic Deep Learning Convolutional Neural Network (GDCNN)"
    journal: "IEEE Access"
    year: 2020
    note: "Indexed in SCIE & Scopus. Q1. Impact Factor: 3.9"

  - authors: "M. Rajeswari, G. Sambasivam, T. Vengattaraman"
    title: "Appraisal and Analysis on Various Web Service Composition Approaches Based On Qos Factors"
    journal: "Journal of King Saud University–Computer and Information Sciences"
    year: 2014
    doi: "https://doi.org/10.1016/j.jksuci.2013.08.003"
    note: "Indexed in SCIE & Scopus. Impact Factor: 6.9"

  - authors: "L. Manjunath, N. Prabakaran, Aswin Kumer S V, E. Mohan, Balaji Natarajan, G. Sambasivam, Vaibhav Bhushan Tyagi"
    title: "QoS Aware Integrated Management Technique for 5G mmWaveBased Hetnets"
    journal: "IEEE Access"
    year: 2023
    doi: "https://ieeexplore.ieee.org/document/10261172"

  - authors: "R. G. Babukarthik, D. Chandramohan, G. Sambasivam"
    title: "COVID-19 Identification in Chest X-Ray Images using Intelligent Multi-Level Classification Scenario"
    journal: "Computers and Electrical Engineering"
    year: 2022
    doi: "https://doi.org/10.1016/j.compeleceng.2022.108405"

  - authors: "E. Mohan, P. Saravanan, Balaji Natarajan, Aswin Kumer S V, G. Sambasivam, G. Prabu Kanna and Vaibhav Bhushan Tyagi"
    title: "Thyroid Detection and Classification Using DNN Based on Hybrid Meta-Heuristic and LSTM Technique"
    journal: "IEEE Access"
    year: 2023
    doi: "https://doi.org/10.1109/ACCESS.2023.3289511"

  - authors: "Aswin Kumer S V, N Prabhakaran, E.Mohan, Balaji Natarajan, G. Sambasivam, Vaibhav Bhushan Tyagi"
    title: "Enhancing Cloud Task Scheduling with a Robust Security Approach and Optimized hybrid POA"
    journal: "IEEE Access"
    year: 2023
    doi: "https://doi.org/10.1109/ACCESS.2023.3329052"

  - authors: "A. Moshika.M, Thirumaran, N. Balaji, Andal, G. Sambasivam & M. Rajesh"
    title: "Vulnerability Assessment In Heterogeneous Web Environment Using Probabilistic Arithmetic Automata"
    journal: "IEEE Access"
    year: 2021
    doi: "https://doi.org/10.1109/ACCESS.2021.3081567"

  - authors: "S. Ezhil Pradha, A. Moshika, N. Balaji, K.Andal, G. Sambasivam, M. Shanmugam"
    title: "Scheduled Access Strategy For Improving Sensor Node Battery Life Time And Delay Analysis Of Wireless Body Area Network"
    journal: "IEEE Access"
    year: 2022
    doi: "https://doi.org/10.1109/ACCESS.2021.3139663"

  - authors: "R Sivaraj Chinnasamy, Naveen J, P.J.A. Alphonse, Chandramohan Dhasarathan, G. Sambasivam"
    title: "Energy-Aware Multi-Level Clustering Scheme for Underwater Wireless Sensor Networks"
    journal: "IEEE Access"
    year: 2022
    doi: "https://doi.org/10.1109/ACCESS.2022.3177722"

  - authors: "Aswin Kumer S V, Lakshmi Bharath Gogu, E.Mohan, Suman Maloji, Balaji Natarajan, G. Sambasivam, Vaibhav Bhushan Tyagi"
    title: "Track and Noise Separation based on the Universal Codebook and enhanced speech recognition using Hybrid Deep Learning Method"
    journal: "IEEE Access"
    year: 2023
    doi: "https://doi.org/10.1109/ACCESS.2023.3328208"

  - authors: "G. Sambasivam, Vengattaraman, T and P. Dhavachelvan"
    title: "An QoS Based Multifaceted Matchmaking Framework for Web Services Discovery"
    journal: "Future Computing and Informatics Journal"
    year: 2018
    doi: "https://doi.org/10.1016/j.fcij.2018.10.007"

  - authors: "S., H., Jayavel, A., Gnanasekaran, Sambasivam., Sohail, S. S., & Madsen, D."
    title: "Interpretable and ethical learning assessment transformer (IELAT): an explainable transformer model for personalized student assessments"
    journal: "Cogent Education"
    year: 2025
    doi: "https://doi.org/10.1080/2331186X.2025.2485508"

conferences:
  - authors: "G. Sambasivam, V. Ravisankar, T. Vengattaraman, R. Baskaran and P. Dhavachelvan"
    title: "A Normalized Approach For Service Discovery"
    venue: "ICICT 2014 (Procedia Computer Science)"
    year: 2015
    doi: "https://doi.org/10.1016/j.procs.2015.02.157"

  - authors: "Yogesh Kumar, G Prabhu Kanna, SJK Jagadeesh Kumar, G Sambasivam"
    title: "Influenza Flu Diagnostics and Detection using Artificial Intelligence-based Learning Approaches: Challenges and Recent Study"
    venue: "IC3I 2023"
    year: 2023

  - authors: "N. Balaji, G. Sambasivam, M.S.SaleemBasha, T. Vengattaraman, and P. Dhavachelvan"
    title: "SLA Based Architecture For Web Service Selection And Ranking With QoS"
    venue: "ICHCI 2013"
    year: 2013

  - authors: "D.Chandramohan, D.Veeraiah, M.Shanmugam, N.Balaji and G.Sambasivam, and ShaileshKhapre"
    title: "SVIP-Enhanced Security Mechanism for SIP Based VoIP Systems and Its Issues"
    venue: "Springer AISC"
    year: 2012

  - authors: "ShaileshPanchamKhapre, Dr. M.S. SaleemBasha, G. Sambasivam and B. SaravanaBalaji"
    title: "Uncertainty Issues in Automated Web Service Selection"
    venue: "ACIT 2013"
    year: 2013

  - authors: "B. Anantharaj, N. Balaji, G. Sambasivam, M. S. S. Basha and T. Vengattaraman"
    title: "EQVS: Enhanced Quality Video Streaming Distribution over Wired/Wireless Networks"
    venue: "ICTACC 2017"
    year: 2017

  - authors: "N. M. Yasin, N. Balaji, G. Sambasivam, M. S. S. Basha and P. Sujatha"
    title: "ADSMS: Anomaly Detection Scheme for Mitigating Sink Hole Attack in Wireless Sensor Network"
    venue: "ICTACC 2017"
    year: 2017

  - authors: "Prabu U., Malarvizhi N., Amudhavel J., Sambasivam G."
    title: "A Distributed Spanning Tree-Based Scalable Fault-Tolerant Algorithm for Load Balancing in Web Server Farms"
    venue: "Smart Energy and Communication (Springer), 2021"
    year: 2021

book_chapters:
  - authors: "S. Lakshmi, D. Helen, and G. Sambasivam"
    title: "Redefining and transforming software development with generative AI"
    book: "Generative AI for Software Development, Walter de Gruyter"
    year: 2025

  - authors: "Chandramohan Dhasarathan, Ramachandra Reddy. B., Ashok Kumar. S., Sambasivam Gnanasekaran"
    title: "Digital Twin for Sustainable Farming: Developing User-Friendly Interfaces..."
    book: "The Future of Agriculture: IoT, AI and Blockchain Technology for Sustainable Farming"
    year: 2024
    doi: "https://doi.org/10.2174/9789815274349124010004"

  - authors: "MJ Abinash, G Prabu Kanna, S Aanjankumar, G Sambasivam, P Karthikeyan"
    title: "An Challenges Introduction and Issues to the Identified in Digital Health and Wellness"
    book: "Cybersecurity in Healthcare Applications"
    year: 2025
    note: "CRC Press"

book_editor:
  - authors: "Kumar, T. A., Rajmohan, R., Niranjanamurthy, M., & Sambasivam, G. (Eds.)"
    title: "Deep learning models towards health informatics management: Foundations, challenges and opportunities"
    year: 2025
    note: "Cognitive approaches in cloud and edge computing"
