---
title: About Me
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: /uploads/resume.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  - block: markdown
    content:
      title: 'About Me'
      subtitle: 'Machine Learning Scientist | PhD in AI & Robotics'
      text: |-
        I'm a Machine Learning Scientist with over a decade of experience in AI, specializing in **Conversational AI**, including **Speech**, **Natural Language Processing** and **Generation**. With a PhD in Computer Science, focused on innovative Neural Network architectures for Robotics, I excel at transforming cutting-edge research into practical, real-world applications.

        My role often bridges research and production, guiding projects from idea to deployment. This involves everything from initial concept development and requirements gathering with Product teams, to hands-on coding with Engineering teams. Driven by a passion for innovation and a commitment to excellence, I strive to stay at the leading edge of Generative and Conversational AI, delivering solutions that make a difference.

        ### Core Focus Areas

        - 🤖 **Conversational AI & Chatbot Systems**
        - 🔤 **Natural Language Processing & Understanding**
        - ✨ **Generative AI & Large Language Models**
        - 🎤 **Voice Technologies & Biometrics**
        - 🦾 **Robotics & Control Systems**

        ### My Approach

        I have successfully led numerous research projects, seeing them through from ideation to deployment, often guiding cross-functional teams to turn complex machine learning models into scalable products. With a strong foundation in Neural Network architectures—including RNNs, LSTMs, Transformers, and Echo State Networks—I have built and optimized AI systems that power intelligent conversational experiences.

        My work has resulted in **multiple patents** and **publications** in areas ranging from conversational AI to human-robot interaction. I've developed systems across diverse domains including automated chatbot creation, hybrid conversational AI systems, voice biometrics, and intuitive robot control interfaces.
        
        ---
        
        ✉️ **Interested in collaboration or consulting?** [Let's connect!](mailto:christos@neuralithmics.com)
    design:
      columns: '1'
      css_style: |
        .markdown {
          line-height: 1.8;
          font-size: 1.05rem;
        }
        .markdown h2 {
          margin-bottom: 0.5rem;
        }
        .markdown ul {
          list-style-type: none;
          padding-left: 1rem;
        }

  - block: markdown
    content:
      title: Skills & Expertise
      text: |-
        #### AI & Machine Learning
        - **Frameworks**: TensorFlow, PyTorch, Keras, Theano, Caffe
        - **LLMs**: Fine-tuning, Prompt Engineering, RAG Systems
        - **Neural Networks**: RNNs, LSTMs, Transformers, CNNs, Echo State Networks
        
        #### Programming & Development
        - **Languages**: Python, C/C++, JavaScript, Java, Matlab, PHP, Bash
        - **Databases**: SQL, MongoDB, Redis, Cassandra
        - **Systems**: Cloud Platforms (AWS, GCP, Azure), Linux, Git
        
        #### Specialized Areas
        - **NLP & Voice**: Text Classification, NER, Voice Biometrics, Speech Recognition
        - **Robotics**: Control Systems, Kinematics, Adaptive Interfaces, Human-Robot Interaction
    design:
      columns: '2'
      
  - block: markdown
    content:
      title: Patents & Recognition
      subtitle: ''
      text: |-
        #### US Patents
        
        - **Systems and methods for generating a chatbot** (US11676044B1)  
          *US Patent Office, June 2023*  
          Patent granted for innovative chatbot generation technology at Ada Support Inc.
          
        - **Systems and methods for generating automatic training suggestions** (20230297887A1)  
          *US Patent Office, September 2023*  
          Patent for automated training suggestion generation at Ada Support Inc.
    design:
      columns: '2'
      css_style: |
        .markdown h4 {
          margin-top: 0.5rem;
          margin-bottom: 1rem;
          color: var(--primary);
        }
        .markdown p {
          margin-bottom: 1.5rem;
        }
        .markdown ul li {
          margin-bottom: 1rem;
        }
---

