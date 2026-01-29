---
title: About
type: landing

design:
  spacing: "4rem"

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
        <div style="display: flex; justify-content: center; gap: 1rem; flex-wrap: wrap; margin: 2rem 0;">
          <a href="#work" class="cta-button-secondary" style="display: inline-flex; align-items: center; gap: 0.5rem;">
            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" style="width: 18px; height: 18px;">
              <path stroke-linecap="round" stroke-linejoin="round" d="M20.25 14.15v4.25c0 1.094-.787 2.036-1.872 2.18-2.087.277-4.216.42-6.378.42s-4.291-.143-6.378-.42c-1.085-.144-1.872-1.086-1.872-2.18v-4.25m16.5 0a2.18 2.18 0 00.75-1.661V8.706c0-1.081-.768-2.015-1.837-2.175a48.114 48.114 0 00-3.413-.387m4.5 8.006c-.194.165-.42.295-.673.38A23.978 23.978 0 0112 15.75c-2.648 0-5.195-.429-7.577-1.22a2.016 2.016 0 01-.673-.38m0 0A2.18 2.18 0 013 12.489V8.706c0-1.081.768-2.015 1.837-2.175a48.111 48.111 0 013.413-.387m7.5 0V5.25A2.25 2.25 0 0013.5 3h-3a2.25 2.25 0 00-2.25 2.25v.894m7.5 0a48.667 48.667 0 00-7.5 0M12 12.75h.008v.008H12v-.008z" />
            </svg>
            Work Experience
          </a>
          <a href="#publications" class="cta-button-secondary" style="display: inline-flex; align-items: center; gap: 0.5rem;">
            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" style="width: 18px; height: 18px;">
              <path stroke-linecap="round" stroke-linejoin="round" d="M12 6.042A8.967 8.967 0 006 3.75c-1.052 0-2.062.18-3 .512v14.25A8.987 8.987 0 016 18c2.305 0 4.408.867 6 2.292m0-14.25a8.966 8.966 0 016-2.292c1.052 0 2.062.18 3 .512v14.25A8.987 8.987 0 0018 18a8.967 8.967 0 00-6 2.292m0-14.25v14.25" />
            </svg>
            Publications
          </a>
          <a href="#education" class="cta-button-secondary" style="display: inline-flex; align-items: center; gap: 0.5rem;">
            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" style="width: 18px; height: 18px;">
              <path stroke-linecap="round" stroke-linejoin="round" d="M4.26 10.147a60.436 60.436 0 00-.491 6.347A48.627 48.627 0 0112 20.904a48.627 48.627 0 018.232-4.41 60.46 60.46 0 00-.491-6.347m-15.482 0a50.57 50.57 0 00-2.658-.813A59.905 59.905 0 0112 3.493a59.902 59.902 0 0110.399 5.84c-.896.248-1.783.52-2.658.814m-15.482 0A50.697 50.697 0 0112 13.489a50.702 50.702 0 017.74-3.342M6.75 15a.75.75 0 100-1.5.75.75 0 000 1.5zm0 0v-3.675A55.378 55.378 0 0112 8.443m-7.007 11.55A5.981 5.981 0 006.75 15.75v-1.5" />
            </svg>
            Education
          </a>
        </div>
    design:
      columns: '1'

  - block: markdown
    id: work
    content:
      title: ''
      text: |-
        <h2 style="display: flex; align-items: center; justify-content: center; gap: 0.75rem;">
          <span class="section-icon">
            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor">
              <path stroke-linecap="round" stroke-linejoin="round" d="M20.25 14.15v4.25c0 1.094-.787 2.036-1.872 2.18-2.087.277-4.216.42-6.378.42s-4.291-.143-6.378-.42c-1.085-.144-1.872-1.086-1.872-2.18v-4.25m16.5 0a2.18 2.18 0 00.75-1.661V8.706c0-1.081-.768-2.015-1.837-2.175a48.114 48.114 0 00-3.413-.387m4.5 8.006c-.194.165-.42.295-.673.38A23.978 23.978 0 0112 15.75c-2.648 0-5.195-.429-7.577-1.22a2.016 2.016 0 01-.673-.38m0 0A2.18 2.18 0 013 12.489V8.706c0-1.081.768-2.015 1.837-2.175a48.111 48.111 0 013.413-.387m7.5 0V5.25A2.25 2.25 0 0013.5 3h-3a2.25 2.25 0 00-2.25 2.25v.894m7.5 0a48.667 48.667 0 00-7.5 0M12 12.75h.008v.008H12v-.008z" />
            </svg>
          </span>
          Work Experience
        </h2>
        <p style="text-align: center;">10+ years building AI systems deployed at scale—from academic research to industry innovation.</p>
    design:
      columns: '1'
      css_class: header-section

  - block: markdown
    content:
      title: ''
      text: |-
        <h3 style="display: flex; align-items: center; gap: 0.5rem; color: var(--tc-text);">
          <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" style="width: 24px; height: 24px; color: var(--tc-primary);">
            <path stroke-linecap="round" stroke-linejoin="round" d="M15 19.128a9.38 9.38 0 002.625.372 9.337 9.337 0 004.121-.952 4.125 4.125 0 00-7.533-2.493M15 19.128v-.003c0-1.113-.285-2.16-.786-3.07M15 19.128v.106A12.318 12.318 0 018.624 21c-2.331 0-4.512-.645-6.374-1.766l-.001-.109a6.375 6.375 0 0111.964-3.07M12 6.375a3.375 3.375 0 11-6.75 0 3.375 3.375 0 016.75 0zm8.25 2.25a2.625 2.625 0 11-5.25 0 2.625 2.625 0 015.25 0z" />
          </svg>
          Consulting
        </h3>
    design:
      columns: '1'

  - block: markdown
    content:
      text: |
        ### Machine Learning Consultant
        
        **[Linked Business](https://www.linkedbusiness.eu/)** | Apr 2020 - Apr 2022 | 📍 Athens [Remote]
        
        FinTech company that aggregates official business data from government registries to deliver B2B intelligence, sales leads, and KYC services. Served as a trusted advisor on AI, ML, and text-mining strategies, translating academic research and emerging technologies into production-ready solutions.
        
        - 🔍 Designed and prototyped algorithms for **entity recognition**, **lead scoring**, and **automated data enrichment**
        - 👥 Created and led collaborations of cross-functional teams to embed models into production pipelines, ensuring accuracy and scalability
        - 🚀 Led rapid **proof-of-concept initiatives** to validate technical feasibility and business value, shaping the company's data-driven roadmap
        
        **Technologies:** Python • scikit-learn • spaCy • FastAPI • MongoDB • SQL • REST APIs
        
    design:
      columns: '1'
      css_class: experience-card

  - block: markdown
    content:
      title: ''
      text: |-
        <h3 style="display: flex; align-items: center; gap: 0.5rem; color: var(--tc-text);">
          <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" style="width: 24px; height: 24px; color: var(--tc-primary);">
            <path stroke-linecap="round" stroke-linejoin="round" d="M2.25 21h19.5m-18-18v18m10.5-18v18m6-13.5V21M6.75 6.75h.75m-.75 3h.75m-.75 3h.75m3-6h.75m-.75 3h.75m-.75 3h.75M6.75 21v-3.375c0-.621.504-1.125 1.125-1.125h2.25c.621 0 1.125.504 1.125 1.125V21M3 3h12m-.75 4.5H21m-3.75 3.75h.008v.008h-.008v-.008zm0 3h.008v.008h-.008v-.008zm0 3h.008v.008h-.008v-.008z" />
          </svg>
          Industry Experience
        </h3>
    design:
      columns: '1'

  - block: markdown
    content:
      title: ''
      text: |
        ### Staff Machine Learning Scientist - R&D
        
        **[Ada Support LTD](https://www.ada.cx/)** | Feb 2024 - Present | 📍 Toronto [Remote]
        
        Leading Generative AI efforts through Applied Research. Work resulted in **2 US patents** related to Conversational AI technologies. Worked end-to-end on conception, design, and implementation of ML-based product improvements.
        
        - 🤖 Architected a modular, LLM-based **AI Agent Platform** optimizing model allocation for cost and performance
        - 📚 Drove **context management pipeline redesign**, improving top-5 retrieval accuracy from **80%→90%+** and increasing "Resolved Inquiries" by **3%**
        - 📋 Led ML efforts for the **Playbooks Framework**, achieving **<1% adherence error** and enhancing resolution rates
        - 🧪 Spearheading research on testing methodologies, performance evaluation, and AI explainability
        
        **Technologies:** LLMs • NLP • Generative AI • Python • PyTorch
        
    design:
      columns: '1'
      css_class: current-role

  - block: markdown
    content:
      text: |
        ### Senior Machine Learning Scientist - R&D
        
        **[Ada Support LTD](https://www.ada.cx/)** | Aug 2021 - Feb 2024 | 📍 Toronto [Remote]
        
        Leading Generative AI efforts through Applied Research. Worked end-to-end on conception, design, and implementation.
        
        - 🔄 Designed and implemented **Generative Reply** and **Generative Action** systems integrating retrieval, moderation, and query rewriting
        - 🚀 Developed **Autolaunch**, a declarative chatbot creation framework, and **ATS** (Automatic Training Suggestions) — both patented
        - 📜 Co-inventor on **2 U.S. patents** in Conversational AI and automated training systems
        - ⚙️ Drove Ada's transition to hybrid and generative chatbot solutions leveraging fine-tuned LLMs
        
        **Technologies:** LLMs • NLP • Generative AI • Python • PyTorch
        
    design:
      columns: '1'
      css_class: experience-card

  - block: markdown
    content:
      text: |
        ### Senior Machine Learning Specialist - R&D
        
        **[Omilia LTD](https://omilia.com/)** | Feb 2020 - Aug 2021 | 📍 Athens [Remote]
        
        Designed and implemented machine learning models for Voice Biometrics, Automated Speech Recognition, and Natural Language Processing. Also involved in serving and maintaining the models.
        
        - 🎤 Designed and deployed neural models for **Voice Biometrics**, **Speech Recognition**, and **Emotion Recognition**
        - 🧠 Led applied research on **Anti-Spoofing**, **Diarization**, and **Transformer-based architectures**
        
        **Technologies:** Python • C++ • PyTorch • TensorFlow • Deep Neural Networks • Probabilistic Neural Models
        
    design:
      columns: '1'
      css_class: experience-card

  - block: markdown
    content:
      text: |
        ### Data Scientist
        
        **[Curation Zone LTD](https://www.curationzone.com/)** | Apr 2019 - Feb 2020 | 📍 London [Remote]
        
        Working on AI technologies to identify the World's best filmmakers.
        
        - 🎬 Built deep learning models to identify top global filmmakers using **BERT**, **ELMo**, and **LSTMs**
        - 📊 Deployed ML pipelines for **scoring**, **recommendation**, and **data management**
        
        **Technologies:** Python • BERT • ELMo • LSTMs • TensorFlow • RESTful API • MongoDB
        
    design:
      columns: '1'
      css_class: experience-card

  - block: markdown
    content:
      text: |
        ### Lead AI Developer
        
        **[Stellanovus LTD](https://www.stellanovus.com/)** | Oct 2018 - Apr 2019 | 📍 Republic of Ireland [Remote]
        
        Working on [AINU.ai](http://www.ainu.ai/), a digital marketing platform powered by NLP and deep learning.
        
        - 🚀 Led AI development for the platform
        - 🧠 Focused on building and scaling neural architectures for **text understanding** and **automation**
        
        **Technologies:** Python • LSTMs • TensorFlow • RESTful API
        
    design:
      columns: '1'
      css_class: experience-card

  - block: markdown
    content:
      text: |
        ### AI & Machine Learning Scientist
        
        **[i-DAT](http://i-dat.org/)** | Sep 2017 - Sep 2018 | 📍 UK [Remote]
        
        Working on a chatbot engine with text comprehension.
        
        - 💬 Developed a chatbot engine for **text comprehension** and **dialogue management**
        - 🧠 Implemented LSTM-based **NLU/NLG modules** using Keras, Rasa, and DialogFlow
        
        **Technologies:** Python • LSTMs • Keras • DialogFlow • Rasa
        
    design:
      columns: '1'
      css_class: experience-card

  - block: markdown
    content:
      title: ''
      text: |-
        <h3 style="display: flex; align-items: center; gap: 0.5rem; color: var(--tc-text);">
          <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" style="width: 24px; height: 24px; color: var(--tc-primary);">
            <path stroke-linecap="round" stroke-linejoin="round" d="M4.26 10.147a60.436 60.436 0 00-.491 6.347A48.627 48.627 0 0112 20.904a48.627 48.627 0 018.232-4.41 60.46 60.46 0 00-.491-6.347m-15.482 0a50.57 50.57 0 00-2.658-.813A59.905 59.905 0 0112 3.493a59.902 59.902 0 0110.399 5.84c-.896.248-1.783.52-2.658.814m-15.482 0A50.697 50.697 0 0112 13.489a50.702 50.702 0 017.74-3.342M6.75 15a.75.75 0 100-1.5.75.75 0 000 1.5zm0 0v-3.675A55.378 55.378 0 0112 8.443m-7.007 11.55A5.981 5.981 0 006.75 15.75v-1.5" />
          </svg>
          Academic & Research
        </h3>
    design:
      columns: '1'

  - block: markdown
    content:
      text: |
        ### Research Scientist
        
        **[University of Naples, Federico II](http://www.nac.unina.it/nac/)** | Jun 2017 - Sep 2017 | 📍 Italy
        
        Researcher Position under the supervision of Prof. Davide Marocco. Working on a **Generative Adversarial Architecture** based on Echo State Networks, with applications to **music generation**.
        
        **Technologies:** Python • LSTMs • Echo State Networks • Theano
        
    design:
      columns: '1'
      css_class: academic-card

  - block: markdown
    content:
      text: |
        ### Research Assistant & Laboratory Assistant
        
        **Plymouth University** | 2015 - 2017 | 📍 UK
        
        **2 Research Projects:** Research and Development of Neural Architectures for:
        - 📱 Sentiment Analysis in Tweets and Natural Language Processing
        - 🏥 Explanation of Functional Disorders
        
        **3 Laboratories:** Teaching:
        - 🎓 MSc level: Robotics and Control
        - 👨‍💻 BSc level: Cross-platform application development in C++
        - ⚡ BSc level: Parallel and Distributed Programming
        
        **Technologies:** CUDA • C/C++ • Python • TensorFlow • RNNs • Industrial Robotics
        
    design:
      columns: '1'
      css_class: academic-card

  - block: markdown
    id: publications
    content:
      title: ''
      text: |-
        <h2 style="display: flex; align-items: center; gap: 0.75rem;">
          <span class="section-icon">
            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor">
              <path stroke-linecap="round" stroke-linejoin="round" d="M12 6.042A8.967 8.967 0 006 3.75c-1.052 0-2.062.18-3 .512v14.25A8.987 8.987 0 016 18c2.305 0 4.408.867 6 2.292m0-14.25a8.966 8.966 0 016-2.292c1.052 0 2.062.18 3 .512v14.25A8.987 8.987 0 0018 18a8.967 8.967 0 00-6 2.292m0-14.25v14.25" />
            </svg>
          </span>
          Publications & Patents
        </h2>
        **2 US Patents** in Conversational AI | **7+ Publications** in IEEE, Springer, Applied Sciences
        
        ---
        
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
          <a href="/publication/" class="cta-button-secondary">View All Publications →</a>
        </div>
        
    design:
      columns: '1'

  - block: markdown
    id: education
    content:
      title: ''
      text: |-
        <h2 style="display: flex; align-items: center; gap: 0.75rem;">
          <span class="section-icon">
            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor">
              <path stroke-linecap="round" stroke-linejoin="round" d="M4.26 10.147a60.436 60.436 0 00-.491 6.347A48.627 48.627 0 0112 20.904a48.627 48.627 0 018.232-4.41 60.46 60.46 0 00-.491-6.347m-15.482 0a50.57 50.57 0 00-2.658-.813A59.905 59.905 0 0112 3.493a59.902 59.902 0 0110.399 5.84c-.896.248-1.783.52-2.658.814m-15.482 0A50.697 50.697 0 0112 13.489a50.702 50.702 0 017.74-3.342M6.75 15a.75.75 0 100-1.5.75.75 0 000 1.5zm0 0v-3.675A55.378 55.378 0 0112 8.443m-7.007 11.55A5.981 5.981 0 006.75 15.75v-1.5" />
            </svg>
          </span>
          Education
        </h2>
        ### PhD in Computer Science, AI & Robotics
        
        **University of Plymouth** · 2014–2017
        
        Thesis: *"Adaptive Neural Architectures For Intuitive Robot Control"*  
        Part of the CogNovo Doctoral Programme  
        [View Thesis →](https://pearl.plymouth.ac.uk/handle/10026.1/9998)
        
        ---
        
        ### BSc in Informatics
        
        **Aristotle University of Thessaloniki** · 2008–2013
        
        Specialty in Information Systems, Expert Systems, and Database Management  
        Thesis: *"Reinforcement Learning in Robotics"*
        
    design:
      columns: '1'

  - block: markdown
    content:
      title: ''
      text: |-
        <div class="cta-final" style="text-align: center; padding: 2rem 0;">
        
        ## Ready to work together?
        
        <p style="font-size: 1.1rem; margin-bottom: 1.5rem;">Let's discuss how I can help with your AI project.</p>
        
        <a href="mailto:christos@neuralithmics.com" class="cta-button">Book a Discovery Call →</a>
        
        </div>
        
    design:
      columns: '1'
      css_class: contact-section
---
