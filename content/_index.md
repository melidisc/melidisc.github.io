---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  spacing: "5rem"

sections:
  - block: markdown
    content:
      title: ''
      subtitle: ''
      text: |-
        <div style="text-align: center; margin-bottom: 1.5rem;">
          <span class="hero-logo-wrap">
            <img src="/images/logos/neuralthmics_logo2.png" alt="Neuralithmics Logo" style="max-width: 760px; width: 100%; height: auto; margin: 0 auto;">
          </span>
        </div>
        
        ## I help companies ship AI products faster
        
        From LLM-powered chatbots to voice biometrics, I turn complex AI research into production systems that work at scale.
        
        <div class="cta-container" style="margin-top: 1.5rem;">
          <a href="mailto:christos@neuralithmics.com" class="cta-button">Book a Discovery Call →</a>
        </div>

    design:
      columns: '1'
      css_class: intro-section

  - block: markdown
    content:
      title: ''
      text: |-
        <div class="social-proof-section">
          <p style="font-size: 0.85rem; color: #888; text-transform: uppercase; letter-spacing: 0.1em; margin-bottom: 1rem;">Trusted by teams at</p>

          <div class="logo-grid">
            <a href="https://www.ada.cx/" target="_blank" rel="noopener noreferrer">
              <img src="/images/logos/ada-logo.svg" alt="Ada" onerror="this.style.display='none';this.nextElementSibling.style.display='block';">
              <span class="text-logo" style="display:none;">Ada</span>
            </a>
            <a href="https://omilia.com/" target="_blank" rel="noopener noreferrer">
              <img src="/images/logos/omilia-logo.svg" alt="Omilia" onerror="this.style.display='none';this.nextElementSibling.style.display='block';">
              <span class="text-logo" style="display:none;">Omilia</span>
            </a>
            <a href="https://www.linkedbusiness.eu/" target="_blank" rel="noopener noreferrer">
              <img src="/images/logos/linkedbusiness-logo.svg" alt="LinkedBusiness" onerror="this.style.display='none';this.nextElementSibling.style.display='block';">
              <span class="text-logo" style="display:none;">LinkedBusiness</span>
            </a>
            <a href="https://www.curationzone.com/" target="_blank" rel="noopener noreferrer">
              <img src="/images/logos/curationzone-logo.svg" alt="Curation Zone" onerror="this.style.display='none';this.nextElementSibling.style.display='block';">
              <span class="text-logo" style="display:none;">Curation Zone</span>
            </a>
            <a href="https://www.plymouth.ac.uk/" target="_blank" rel="noopener noreferrer">
              <img src="/images/logos/plymouth-logo.svg" alt="University of Plymouth" onerror="this.style.display='none';this.nextElementSibling.style.display='block';">
              <span class="text-logo" style="display:none;">U. Plymouth</span>
            </a>
            <a href="https://www.unina.it/" target="_blank" rel="noopener noreferrer">
              <img src="/images/logos/naples-logo.svg" alt="University of Naples" onerror="this.style.display='none';this.nextElementSibling.style.display='block';">
              <span class="text-logo" style="display:none;">U. Naples</span>
            </a>
            <a href="https://www.auth.gr/" target="_blank" rel="noopener noreferrer">
              <img src="/images/logos/auth-logo.svg" alt="Aristotle University" onerror="this.style.display='none';this.nextElementSibling.style.display='block';">
              <span class="text-logo" style="display:none;">AUTH</span>
            </a>
          </div>

          <div class="stats-badges">
            <span class="stats-badge"><strong>2</strong> US Patents</span>
            <span class="stats-badge"><strong>7+</strong> Publications</span>
            <span class="stats-badge"><strong>10+</strong> Years in AI/ML</span>
          </div>
        </div>
    design:
      columns: '1'
      css_class: social-proof-section

  - block: markdown
    content:
      title: 'What I Do'
      text: |-
        <div class="services-grid">
          <div class="service-card">
            <h3>
              <span class="service-icon">
                <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor">
                  <path stroke-linecap="round" stroke-linejoin="round" d="M7.5 8.25h9m-9 3H12m-9.75 1.51c0 1.6 1.123 2.994 2.707 3.227 1.129.166 2.27.293 3.423.379.35.026.67.21.865.501L12 21l2.755-4.133a1.14 1.14 0 01.865-.501 48.172 48.172 0 003.423-.379c1.584-.233 2.707-1.626 2.707-3.228V6.741c0-1.602-1.123-2.995-2.707-3.228A48.394 48.394 0 0012 3c-2.392 0-4.744.175-7.043.513C3.373 3.746 2.25 5.14 2.25 6.741v6.018z" />
                </svg>
              </span>
              Conversational AI & LLMs
            </h3>
            <p>Build production-ready chatbots, RAG systems, and LLM-powered applications. From fine-tuning to deployment, I've shipped solutions serving millions of users.</p>
          </div>

          <div class="service-card">
            <h3>
              <span class="service-icon">
                <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor">
                  <path stroke-linecap="round" stroke-linejoin="round" d="M12 18.75a6 6 0 006-6v-1.5m-6 7.5a6 6 0 01-6-6v-1.5m6 7.5v3.75m-3.75 0h7.5M12 15.75a3 3 0 01-3-3V4.5a3 3 0 116 0v8.25a3 3 0 01-3 3z" />
                </svg>
              </span>
              Voice & NLP Systems
            </h3>
            <p>End-to-end voice and text AI: speech recognition, voice biometrics, sentiment analysis, and custom NLP pipelines for your domain.</p>
          </div>

          <div class="service-card">
            <h3>
              <span class="service-icon">
                <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor">
                  <path stroke-linecap="round" stroke-linejoin="round" d="M9.75 3.104v5.714a2.25 2.25 0 01-.659 1.591L5 14.5M9.75 3.104c-.251.023-.501.05-.75.082m.75-.082a24.301 24.301 0 014.5 0m0 0v5.714c0 .597.237 1.17.659 1.591L19.8 15.3M14.25 3.104c.251.023.501.05.75.082M19.8 15.3l-1.57.393A9.065 9.065 0 0112 15a9.065 9.065 0 00-6.23.693L5 14.5m14.8.8l1.402 1.402c1.232 1.232.65 3.318-1.067 3.611A48.309 48.309 0 0112 21c-2.773 0-5.491-.235-8.135-.687-1.718-.293-2.3-2.379-1.067-3.61L5 14.5" />
                </svg>
              </span>
              Research to Production
            </h3>
            <p>Turn academic papers and prototypes into scalable systems. I bridge the gap between cutting-edge research and real-world implementation.</p>
          </div>
        </div>

        <div style="text-align: center; margin-top: 2rem;">
          <a href="/services/" class="cta-button-secondary">View All Services →</a>
        </div>

    design:
      columns: '1'

  - block: markdown
    content:
      title: 'Results I Deliver'
      text: |-
        <div class="results-section">
        
        **At Ada Support**, I spearheaded R&D projects that led to their Generative AI chatbot platform—now serving millions of customer interactions. My work resulted in 2 US patents for conversational AI.
        
        **At Omilia**, I designed voice biometrics and speech recognition systems for enterprise contact centers.
        
        **In academia**, my PhD research on neural network architectures for robotics produced 7+ publications in IEEE and Springer journals.
        
        </div>
        
        <div style="text-align: center; margin-top: 2rem;">
          <a href="/work/" class="cta-button-secondary">See My Work →</a>
          <a href="/publication/" class="cta-button-secondary">View Publications →</a>
        </div>
        
    design:
      columns: '1'

  - block: markdown
    content:
      title: 'How We Work Together'
      text: |-
        <div class="process-section">
        
        **1. Discovery Call** — 30-minute call to understand your challenges (free)
        
        **2. Proposal** — Detailed scope, approach, and timeline within a week
        
        **3. Engagement** — Flexible models: hourly, project-based, or retainer
        
        **4. Delivery** — Implementation with ongoing support options
        
        </div>
        
    design:
      columns: '1'

  - block: markdown
    content:
      title: ''
      text: |-
        <div class="newsletter-section">
          <h3>Stay Updated on AI & ML</h3>
          <p>Insights on conversational AI, LLMs, and building production ML systems.</p>
          <iframe
            src="https://neuralithmics.substack.com/embed"
            width="100%"
            height="120"
            style="border: 1px solid #EEE; background: white; border-radius: 8px;"
            frameborder="0"
            scrolling="no"
            loading="lazy"
          ></iframe>
        </div>

    design:
      columns: '1'

  - block: markdown
    content:
      title: ''
      text: |-
        <div class="cta-final" style="text-align: center; padding: 2rem 0;">

        ## Ready to accelerate your AI project?

        <p style="font-size: 1.1rem; margin-bottom: 1.5rem;">Let's discuss how I can help you ship faster.</p>

        <a href="mailto:christos@neuralithmics.com" class="cta-button">Book a Discovery Call →</a>

        <div class="social-links" style="justify-content: center; margin-top: 2rem;">
          <a href="mailto:christos@neuralithmics.com" title="Email" aria-label="Email">
            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor">
              <path stroke-linecap="round" stroke-linejoin="round" d="M21.75 6.75v10.5a2.25 2.25 0 01-2.25 2.25h-15a2.25 2.25 0 01-2.25-2.25V6.75m19.5 0A2.25 2.25 0 0019.5 4.5h-15a2.25 2.25 0 00-2.25 2.25m19.5 0v.243a2.25 2.25 0 01-1.07 1.916l-7.5 4.615a2.25 2.25 0 01-2.36 0L3.32 8.91a2.25 2.25 0 01-1.07-1.916V6.75" />
            </svg>
          </a>
          <a href="https://linkedin.com/in/christos-melidis" target="_blank" rel="noopener noreferrer" title="LinkedIn" aria-label="LinkedIn">
            <svg xmlns="http://www.w3.org/2000/svg" fill="currentColor" viewBox="0 0 24 24">
              <path d="M20.447 20.452h-3.554v-5.569c0-1.328-.027-3.037-1.852-3.037-1.853 0-2.136 1.445-2.136 2.939v5.667H9.351V9h3.414v1.561h.046c.477-.9 1.637-1.85 3.37-1.85 3.601 0 4.267 2.37 4.267 5.455v6.286zM5.337 7.433c-1.144 0-2.063-.926-2.063-2.065 0-1.138.92-2.063 2.063-2.063 1.14 0 2.064.925 2.064 2.063 0 1.139-.925 2.065-2.064 2.065zm1.782 13.019H3.555V9h3.564v11.452zM22.225 0H1.771C.792 0 0 .774 0 1.729v20.542C0 23.227.792 24 1.771 24h20.451C23.2 24 24 23.227 24 22.271V1.729C24 .774 23.2 0 22.222 0h.003z"/>
            </svg>
          </a>
          <a href="https://twitter.com/ChristosMelidis" target="_blank" rel="noopener noreferrer" title="Twitter/X" aria-label="Twitter">
            <svg xmlns="http://www.w3.org/2000/svg" fill="currentColor" viewBox="0 0 24 24">
              <path d="M18.244 2.25h3.308l-7.227 8.26 8.502 11.24H16.17l-5.214-6.817L4.99 21.75H1.68l7.73-8.835L1.254 2.25H8.08l4.713 6.231zm-1.161 17.52h1.833L7.084 4.126H5.117z"/>
            </svg>
          </a>
          <a href="https://github.com/melidisc" target="_blank" rel="noopener noreferrer" title="GitHub" aria-label="GitHub">
            <svg xmlns="http://www.w3.org/2000/svg" fill="currentColor" viewBox="0 0 24 24">
              <path d="M12 0c-6.626 0-12 5.373-12 12 0 5.302 3.438 9.8 8.207 11.387.599.111.793-.261.793-.577v-2.234c-3.338.726-4.033-1.416-4.033-1.416-.546-1.387-1.333-1.756-1.333-1.756-1.089-.745.083-.729.083-.729 1.205.084 1.839 1.237 1.839 1.237 1.07 1.834 2.807 1.304 3.492.997.107-.775.418-1.305.762-1.604-2.665-.305-5.467-1.334-5.467-5.931 0-1.311.469-2.381 1.236-3.221-.124-.303-.535-1.524.117-3.176 0 0 1.008-.322 3.301 1.23.957-.266 1.983-.399 3.003-.404 1.02.005 2.047.138 3.006.404 2.291-1.552 3.297-1.23 3.297-1.23.653 1.653.242 2.874.118 3.176.77.84 1.235 1.911 1.235 3.221 0 4.609-2.807 5.624-5.479 5.921.43.372.823 1.102.823 2.222v3.293c0 .319.192.694.801.576 4.765-1.589 8.199-6.086 8.199-11.386 0-6.627-5.373-12-12-12z"/>
            </svg>
          </a>
        </div>

        <p style="margin-top: 1rem; font-size: 0.9rem; color: #888;">
          Thessaloniki, Greece · Remote globally
        </p>

        </div>

    design:
      columns: '1'
      css_class: contact-section
---
