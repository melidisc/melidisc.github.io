---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  spacing: "0"

sections:
  # ===== HERO SECTION =====
  - block: markdown
    content:
      title: ''
      subtitle: ''
      text: |-
        <div class="hero-section">
          <div style="max-width: 800px; margin: 0 auto;">
            <div style="margin-bottom: 1.5rem;">
              <span style="display: inline-block; font-size: 0.8rem; font-weight: 600; text-transform: uppercase; letter-spacing: 0.12em; color: rgba(255,255,255,0.5); background: rgba(255,255,255,0.08); padding: 0.4rem 1rem; border-radius: 50px;">AI & Machine Learning Consultant</span>
            </div>

            <h2>I help companies <span class="gradient-text">ship AI products</span> faster</h2>

            <p class="hero-subtitle">From Agentic AI systems to voice biometrics, I turn complex research into production systems that work at scale. 10+ years, 2 US patents, systems serving millions.</p>

            <div class="cta-container" style="margin-top: 2.5rem;">
              <a href="mailto:christos@neuralithmics.com" class="cta-button-white">Book a Discovery Call</a>
              <a href="/services/" class="cta-button-outline-white">View Services</a>
            </div>
          </div>
        </div>

    design:
      columns: '1'
      css_class: intro-section
      spacing:
        padding: ["0", "0", "0", "0"]

  # ===== SOCIAL PROOF =====
  - block: markdown
    content:
      title: ''
      text: |-
        <div style="text-align: center; padding: 3rem 0;">
          <p style="font-size: 0.8rem; font-weight: 600; text-transform: uppercase; letter-spacing: 0.15em; color: #94a3b8; margin-bottom: 1.25rem;">Trusted by teams at</p>

          <div class="company-logos">
            <a href="https://www.ada.cx/" target="_blank">Ada</a>
            <span class="logo-separator">&middot;</span>
            <a href="https://omilia.com/" target="_blank">Omilia</a>
            <span class="logo-separator">&middot;</span>
            <a href="https://www.linkedbusiness.eu/" target="_blank">LinkedBusiness</a>
            <span class="logo-separator">&middot;</span>
            <a href="https://www.curationzone.com/" target="_blank">Curation Zone</a>
            <span class="logo-separator">&middot;</span>
            <a href="https://www.plymouth.ac.uk/" target="_blank">University of Plymouth</a>
            <span class="logo-separator">&middot;</span>
            <a href="https://www.unina.it/" target="_blank">University of Naples</a>
          </div>
        </div>
    design:
      columns: '1'
      spacing:
        padding: ["0", "0", "0", "0"]

  # ===== STATS BAR =====
  - block: markdown
    content:
      title: ''
      text: |-
        <div class="stats-bar">
          <div class="stat-item">
            <div class="stat-number">2</div>
            <div class="stat-label">US Patents</div>
          </div>
          <div class="stat-item">
            <div class="stat-number">7+</div>
            <div class="stat-label">Publications</div>
          </div>
          <div class="stat-item">
            <div class="stat-number">10+</div>
            <div class="stat-label">Years in AI/ML</div>
          </div>
          <div class="stat-item">
            <div class="stat-number">9+</div>
            <div class="stat-label">Companies Served</div>
          </div>
        </div>
    design:
      columns: '1'
      spacing:
        padding: ["0", "0", "0", "0"]

  # ===== WHAT I DO - SERVICES GRID =====
  - block: markdown
    content:
      title: ''
      text: |-
        <div style="padding: 5rem 0;">
          <div class="section-header">
            <span class="section-tag">Services</span>
            <h2>What I do</h2>
            <p>End-to-end AI consulting from research through production deployment</p>
          </div>

          <div class="services-grid-modern">
            <div class="service-card">
              <span class="card-icon">&#x1F916;</span>
              <h3>Agentic AI & LLM Apps</h3>
              <p>Production-ready AI agents, RAG systems, and LLM-powered applications. I've shipped chatbots serving millions of users and hold 2 US patents in conversational AI.</p>
              <a href="/services/" class="card-link">Learn more &rarr;</a>
            </div>

            <div class="service-card">
              <span class="card-icon">&#x1F3A4;</span>
              <h3>Voice & NLP Systems</h3>
              <p>End-to-end voice and text AI: speech recognition, voice biometrics, sentiment analysis, and custom NLP pipelines optimized for your domain.</p>
              <a href="/services/" class="card-link">Learn more &rarr;</a>
            </div>

            <div class="service-card">
              <span class="card-icon">&#x1F52C;</span>
              <h3>Research to Production</h3>
              <p>Turn academic papers and prototypes into scalable systems. I bridge the gap between cutting-edge research and real-world implementation.</p>
              <a href="/services/" class="card-link">Learn more &rarr;</a>
            </div>

            <div class="service-card">
              <span class="card-icon">&#x1F4C8;</span>
              <h3>B2B Intelligence & Data</h3>
              <p>AI-powered lead scoring, entity recognition, and data enrichment. Proven results in FinTech and enterprise contexts.</p>
              <a href="/services/" class="card-link">Learn more &rarr;</a>
            </div>

            <div class="service-card">
              <span class="card-icon">&#x1F9ED;</span>
              <h3>AI Strategy & Leadership</h3>
              <p>Roadmap planning, technology evaluation, and hands-on technical leadership for AI initiatives at any scale.</p>
              <a href="/services/" class="card-link">Learn more &rarr;</a>
            </div>

            <div class="service-card">
              <span class="card-icon">&#x1F527;</span>
              <h3>MCP & Agent Tooling</h3>
              <p>Model Context Protocol implementations, multi-agent architectures, and tool-use systems for complex conversational workflows.</p>
              <a href="/services/" class="card-link">Learn more &rarr;</a>
            </div>
          </div>

          <div style="text-align: center; margin-top: 3rem;">
            <a href="/services/" class="cta-button-secondary">View All Services &rarr;</a>
          </div>
        </div>
    design:
      columns: '1'

  # ===== RESULTS / PROOF =====
  - block: markdown
    content:
      title: ''
      text: |-
        <div style="background: #f8fafc; padding: 5rem 0; margin: 0 -5vw; padding-left: 5vw; padding-right: 5vw;">
          <div class="section-header">
            <span class="section-tag">Results</span>
            <h2>Proven impact at scale</h2>
            <p>Real outcomes from real engagements</p>
          </div>

          <div class="results-grid">
            <div class="result-card">
              <div class="result-company">Ada Support</div>
              <div class="result-metric">80% &rarr; 90%+</div>
              <h3>Retrieval accuracy improvement</h3>
              <p>Redesigned context management pipeline, increasing top-5 retrieval accuracy and boosting resolved inquiries by 3%.</p>
            </div>

            <div class="result-card">
              <div class="result-company">Ada Support</div>
              <div class="result-metric">&lt;1% error</div>
              <h3>Playbooks adherence rate</h3>
              <p>Led ML efforts for the Playbooks Framework, achieving near-perfect adherence and enhanced resolution rates.</p>
            </div>

            <div class="result-card">
              <div class="result-company">Ada Support</div>
              <div class="result-metric">2 US Patents</div>
              <h3>Conversational AI inventions</h3>
              <p>Co-invented patented systems for chatbot generation and automated training suggestions.</p>
            </div>

            <div class="result-card">
              <div class="result-company">Omilia</div>
              <div class="result-metric">Enterprise-scale</div>
              <h3>Voice biometrics deployment</h3>
              <p>Designed and deployed neural models for voice biometrics, speech recognition, and emotion detection for enterprise contact centers.</p>
            </div>

            <div class="result-card">
              <div class="result-company">LinkedBusiness</div>
              <div class="result-metric">Production ML</div>
              <h3>B2B intelligence pipeline</h3>
              <p>Designed algorithms for entity recognition, lead scoring, and automated data enrichment for a FinTech B2B platform.</p>
            </div>

            <div class="result-card">
              <div class="result-company">Academic Research</div>
              <div class="result-metric">7+ Papers</div>
              <h3>Published research</h3>
              <p>Publications in IEEE, Springer, and Applied Sciences on neural architectures, robotics, and adaptive systems.</p>
            </div>
          </div>
        </div>
    design:
      columns: '1'

  # ===== HOW IT WORKS =====
  - block: markdown
    content:
      title: ''
      text: |-
        <div style="padding: 5rem 0;">
          <div class="section-header">
            <span class="section-tag">Process</span>
            <h2>How we work together</h2>
            <p>Simple, transparent engagement from first call to delivery</p>
          </div>

          <div class="process-steps">
            <div class="process-step">
              <h3>Discovery Call</h3>
              <p>Free 30-minute call to understand your challenges, goals, and technical requirements.</p>
            </div>

            <div class="process-step">
              <h3>Proposal</h3>
              <p>Detailed scope, approach, and timeline delivered within a week. No surprises.</p>
            </div>

            <div class="process-step">
              <h3>Engagement</h3>
              <p>Flexible models: project-based, hourly consulting, or retainer. Pick what works for you.</p>
            </div>

            <div class="process-step">
              <h3>Delivery</h3>
              <p>Implementation with clear milestones, documentation, and ongoing support options.</p>
            </div>
          </div>
        </div>
    design:
      columns: '1'

  # ===== FINAL CTA =====
  - block: markdown
    content:
      title: ''
      text: |-
        <div class="cta-section">
          <h2>Ready to accelerate your AI project?</h2>
          <p>Let's discuss how I can help you ship faster, reduce risk, and build systems that scale.</p>

          <div class="cta-container">
            <a href="mailto:christos@neuralithmics.com" class="cta-button-white">Book a Discovery Call</a>
            <a href="/about/" class="cta-button-outline-white">Learn About Me</a>
          </div>

          <div class="cta-links" style="margin-top: 2.5rem;">
            <a href="mailto:christos@neuralithmics.com">christos@neuralithmics.com</a> &middot;
            <a href="https://linkedin.com/in/christos-melidis" target="_blank">LinkedIn</a> &middot;
            <a href="https://github.com/melidisc" target="_blank">GitHub</a> &middot;
            Thessaloniki, Greece (Remote globally)
          </div>
        </div>
    design:
      columns: '1'
      css_class: contact-section
---
