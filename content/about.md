---
title: About
type: landing

design:
  spacing: "0"

sections:
  - block: resume-biography-3
    content:
      username: admin
      text: ""
      button:
        text: Download CV
        url: /uploads/resume.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false

  - block: markdown
    content:
      title: ''
      text: |-
        <div style="display: flex; justify-content: center; gap: 0.75rem; flex-wrap: wrap; margin: 2.5rem 0;">
          <a href="#work" class="cta-button-secondary">Work Experience</a>
          <a href="#publications" class="cta-button-secondary">Publications</a>
          <a href="#education" class="cta-button-secondary">Education</a>
        </div>
    design:
      columns: '1'

  - block: markdown
    id: work
    content:
      title: ''
      text: |-
        <div class="section-header" style="margin-top: 2rem;">
          <span class="section-tag">Career</span>
          <h2>Work Experience</h2>
          <p>10+ years building AI systems deployed at scale — from academic research to industry innovation.</p>
        </div>
    design:
      columns: '1'

  - block: markdown
    content:
      title: ''
      text: |-
        <div style="margin-bottom: 0.5rem;">
          <span style="display: inline-block; font-size: 0.8rem; font-weight: 600; text-transform: uppercase; letter-spacing: 0.1em; color: #6366f1; background: rgba(99, 102, 241, 0.08); padding: 0.35rem 0.85rem; border-radius: 50px;">Consulting</span>
        </div>
    design:
      columns: '1'

  - block: markdown
    content:
      text: |
        ### Machine Learning Consultant

        **[Linked Business](https://www.linkedbusiness.eu/)** | Apr 2020 - Apr 2022 | Athens [Remote]

        FinTech company that aggregates official business data from government registries to deliver B2B intelligence, sales leads, and KYC services. Served as a trusted advisor on AI, ML, and text-mining strategies, translating academic research and emerging technologies into production-ready solutions.

        - Designed and prototyped algorithms for **entity recognition**, **lead scoring**, and **automated data enrichment**
        - Created and led collaborations of cross-functional teams to embed models into production pipelines, ensuring accuracy and scalability
        - Led rapid **proof-of-concept initiatives** to validate technical feasibility and business value, shaping the company's data-driven roadmap

        **Technologies:** Python, scikit-learn, spaCy, FastAPI, MongoDB, SQL, REST APIs

    design:
      columns: '1'
      css_class: experience-card

  - block: markdown
    content:
      title: ''
      text: |-
        <div style="margin-top: 2rem; margin-bottom: 0.5rem;">
          <span style="display: inline-block; font-size: 0.8rem; font-weight: 600; text-transform: uppercase; letter-spacing: 0.1em; color: #6366f1; background: rgba(99, 102, 241, 0.08); padding: 0.35rem 0.85rem; border-radius: 50px;">Industry</span>
        </div>
    design:
      columns: '1'

  - block: markdown
    content:
      title: ''
      text: |
        ### Staff Machine Learning Scientist - R&D

        **[Ada Support LTD](https://www.ada.cx/)** | Feb 2024 - Present | Toronto [Remote]

        Leading Generative AI efforts through Applied Research. Work resulted in **2 US patents** related to Conversational AI technologies. Worked end-to-end on conception, design, and implementation of ML-based product improvements.

        - Architected a modular, LLM-based **AI Agent Platform** optimizing model allocation for cost and performance
        - Drove **context management pipeline redesign**, improving top-5 retrieval accuracy from **80% to 90%+** and increasing "Resolved Inquiries" by **3%**
        - Led ML efforts for the **Playbooks Framework**, achieving **<1% adherence error** and enhancing resolution rates
        - Spearheading research on testing methodologies, performance evaluation, and AI explainability

        **Technologies:** LLMs, NLP, Generative AI, Python, PyTorch

    design:
      columns: '1'
      css_class: current-role

  - block: markdown
    content:
      text: |
        ### Senior Machine Learning Scientist - R&D

        **[Ada Support LTD](https://www.ada.cx/)** | Aug 2021 - Feb 2024 | Toronto [Remote]

        Leading Generative AI efforts through Applied Research. Worked end-to-end on conception, design, and implementation.

        - Designed and implemented **Generative Reply** and **Generative Action** systems integrating retrieval, moderation, and query rewriting
        - Developed **Autolaunch**, a declarative chatbot creation framework, and **ATS** (Automatic Training Suggestions) — both patented
        - Co-inventor on **2 U.S. patents** in Conversational AI and automated training systems
        - Drove Ada's transition to hybrid and generative chatbot solutions leveraging fine-tuned LLMs

        **Technologies:** LLMs, NLP, Generative AI, Python, PyTorch

    design:
      columns: '1'
      css_class: experience-card

  - block: markdown
    content:
      text: |
        ### Senior Machine Learning Specialist - R&D

        **[Omilia LTD](https://omilia.com/)** | Feb 2020 - Aug 2021 | Athens [Remote]

        Designed and implemented machine learning models for Voice Biometrics, Automated Speech Recognition, and Natural Language Processing. Also involved in serving and maintaining the models.

        - Designed and deployed neural models for **Voice Biometrics**, **Speech Recognition**, and **Emotion Recognition**
        - Led applied research on **Anti-Spoofing**, **Diarization**, and **Transformer-based architectures**

        **Technologies:** Python, C++, PyTorch, TensorFlow, Deep Neural Networks, Probabilistic Neural Models

    design:
      columns: '1'
      css_class: experience-card

  - block: markdown
    content:
      text: |
        ### Data Scientist

        **[Curation Zone LTD](https://www.curationzone.com/)** | Apr 2019 - Feb 2020 | London [Remote]

        Working on AI technologies to identify the World's best filmmakers.

        - Built deep learning models to identify top global filmmakers using **BERT**, **ELMo**, and **LSTMs**
        - Deployed ML pipelines for **scoring**, **recommendation**, and **data management**

        **Technologies:** Python, BERT, ELMo, LSTMs, TensorFlow, RESTful API, MongoDB

    design:
      columns: '1'
      css_class: experience-card

  - block: markdown
    content:
      text: |
        ### Lead AI Developer

        **[Stellanovus LTD](https://www.stellanovus.com/)** | Oct 2018 - Apr 2019 | Republic of Ireland [Remote]

        Working on [AINU.ai](http://www.ainu.ai/), a digital marketing platform powered by NLP and deep learning.

        - Led AI development for the platform
        - Focused on building and scaling neural architectures for **text understanding** and **automation**

        **Technologies:** Python, LSTMs, TensorFlow, RESTful API

    design:
      columns: '1'
      css_class: experience-card

  - block: markdown
    content:
      text: |
        ### AI & Machine Learning Scientist

        **[i-DAT](http://i-dat.org/)** | Sep 2017 - Sep 2018 | UK [Remote]

        Working on a chatbot engine with text comprehension.

        - Developed a chatbot engine for **text comprehension** and **dialogue management**
        - Implemented LSTM-based **NLU/NLG modules** using Keras, Rasa, and DialogFlow

        **Technologies:** Python, LSTMs, Keras, DialogFlow, Rasa

    design:
      columns: '1'
      css_class: experience-card

  - block: markdown
    content:
      title: ''
      text: |-
        <div style="margin-top: 2rem; margin-bottom: 0.5rem;">
          <span style="display: inline-block; font-size: 0.8rem; font-weight: 600; text-transform: uppercase; letter-spacing: 0.1em; color: #06b6d4; background: rgba(6, 182, 212, 0.08); padding: 0.35rem 0.85rem; border-radius: 50px;">Academic & Research</span>
        </div>
    design:
      columns: '1'

  - block: markdown
    content:
      text: |
        ### Research Scientist

        **[University of Naples, Federico II](http://www.nac.unina.it/nac/)** | Jun 2017 - Sep 2017 | Italy

        Researcher Position under the supervision of Prof. Davide Marocco. Working on a **Generative Adversarial Architecture** based on Echo State Networks, with applications to **music generation**.

        **Technologies:** Python, LSTMs, Echo State Networks, Theano

    design:
      columns: '1'
      css_class: academic-card

  - block: markdown
    content:
      text: |
        ### Research Assistant & Laboratory Assistant

        **Plymouth University** | 2015 - 2017 | UK

        **2 Research Projects:** Research and Development of Neural Architectures for:
        - Sentiment Analysis in Tweets and Natural Language Processing
        - Explanation of Functional Disorders

        **3 Laboratories:** Teaching:
        - MSc level: Robotics and Control
        - BSc level: Cross-platform application development in C++
        - BSc level: Parallel and Distributed Programming

        **Technologies:** CUDA, C/C++, Python, TensorFlow, RNNs, Industrial Robotics

    design:
      columns: '1'
      css_class: academic-card

  - block: markdown
    id: publications
    content:
      title: ''
      text: |-
        <div class="section-header" style="margin-top: 3rem;">
          <span class="section-tag">Research</span>
          <h2>Publications & Patents</h2>
          <p><strong>2 US Patents</strong> in Conversational AI | <strong>7+ Publications</strong> in IEEE, Springer, Applied Sciences</p>
        </div>

        ### US Patents

        - **Systems and methods for generating a chatbot** — US11676044B1 (2023)
        - **Systems and methods for generating automatic training suggestions** — US20230297887A1 (2023)

        ---

        ### Selected Publications

        - **Effective Behavioural Dynamic Coupling through Echo State Networks** — Applied Sciences (2019)
        - **A test of the adaptive network explanation of functional disorders** — Biosystems (2017)
        - **Intuitive control of mobile robots** — Cognitive Processing, Springer (2017)
        - **KURE: Kinematic universal remote interface** — IEEE SMC (2016)
        - **A Human Centric Approach to Robotic Control** — IEEE SMC (2015)

        <div style="margin-top: 1.5rem;">
          <a href="/publication/" class="cta-button-secondary">View All Publications &rarr;</a>
        </div>

    design:
      columns: '1'

  - block: markdown
    id: education
    content:
      title: ''
      text: |-
        <div class="section-header" style="margin-top: 3rem;">
          <span class="section-tag">Education</span>
          <h2>Education</h2>
        </div>

        ### PhD in Computer Science, AI & Robotics

        **University of Plymouth** | 2014 - 2017

        Thesis: *"Adaptive Neural Architectures For Intuitive Robot Control"*
        Part of the CogNovo Doctoral Programme
        [View Thesis &rarr;](https://pearl.plymouth.ac.uk/handle/10026.1/9998)

        ---

        ### BSc in Informatics

        **Aristotle University of Thessaloniki** | 2008 - 2013

        Specialty in Information Systems, Expert Systems, and Database Management
        Thesis: *"Reinforcement Learning in Robotics"*

    design:
      columns: '1'

  - block: markdown
    content:
      title: ''
      text: |-
        <div class="cta-section" style="margin-top: 3rem;">
          <h2>Ready to work together?</h2>
          <p>Let's discuss how I can help with your AI project.</p>

          <div class="cta-container">
            <a href="mailto:christos@neuralithmics.com" class="cta-button-white">Book a Discovery Call</a>
          </div>
        </div>
    design:
      columns: '1'
      css_class: contact-section
---
