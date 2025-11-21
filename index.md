---
layout: home
---

<!-- Avatar + Intro Section -->
<div style="display: flex; align-items: center; flex-wrap: wrap; gap: 20px; margin-bottom: 30px;">

  <img src="imgs/profile.png"
    alt="avatar"
    style="
      width: 120px;
      height: 120px;
      border-radius: 50%;
      object-fit: cover;
      flex-shrink: 0;
    " />

  <div style="flex: 1; min-width: 250px;">
    <p><strong>Welcome! I am Vaaruni Desai.</strong></p>

    <p>
      I am an AI researcher obsessed with how transformers think.
      I specialize in building probing tools to align AI to human goals.
    </p>
  </div>
  <!-- EXPERIENCE SECTION -->
<h2 style="margin-top: 50px;">Experience</h2>

<div style="display: flex; flex-direction: column; gap: 20px; margin-top: 20px;">


  <!-- Independent Research -->
  <div style="
      border: 1px solid #ddd;
      border-radius: 10px;
      padding: 20px;
  ">
    <h3>AI Researcher — Independent Research</h3>
    <p style="margin: 0; color: #555;"><em>Remote · Oct 2025 – Present</em></p>
    <ul>
      <li>Developed end-to-end training + probing pipelines using Universal Dependencies (English-EWT) to study syntactic feature emergence.</li>
      <li>Designed longitudinal interpretability experiments analyzing circuit formation across training checkpoints (linear probes, attention entropy, PCA dynamics).</li>
      <li>Extending work toward POS-conditioned attention and cross-lingual transfer to explore universality of learned circuits.</li>
    </ul>
  </div>


  <!-- AI Safety Global Society -->
  <div style="
      border: 1px solid #ddd;
      border-radius: 10px;
      padding: 20px;
  ">
    <h3>AI Alignment Research Fellow — AI Safety Global Society</h3>
    <p style="margin: 0; color: #555;"><em>Remote · Mar 2025 – Oct 2025</em></p>
    <ul>
      <li>Ran interpretability experiments on XOR, parity, and structured tasks to study transformer reasoning and generalization.</li>
      <li>Managed large-scale GPU training runs (100k+ epochs) and built automated compute pipelines with robust evaluation metrics.</li>
      <li>Developed <strong>pickucot</strong>, a framework to probe causal hint-use and explanation faithfulness for small language models.</li>
    </ul>
  </div>


  <!-- Refinitiv -->
  <div style="
      border: 1px solid #ddd;
      border-radius: 10px;
      padding: 20px;
  ">
    <h3>Associate Software Engineer — Refinitiv (an LSEG Business)</h3>
    <p style="margin: 0; color: #555;"><em>Bangalore, India · Jul 2019 – Nov 2021</em></p>
    <ul>
      <li>Designed and delivered 70+ high-performance REST APIs with caching, RBAC, and encryption for enterprise clients (e.g., Vanguard, Wells Fargo).</li>
      <li>Improved data retrieval speed by <strong>66%</strong> and reduced response times by <strong>50%</strong>.</li>
      <li>Worked cross-functionally to ensure scalable, secure integration of financial data services.</li>
    </ul>
  </div>


  <!-- Thomson Reuters -->
  <div style="
      border: 1px solid #ddd;
      border-radius: 10px;
      padding: 20px;
  ">
    <h3>Trainee Software Engineer — Thomson Reuters</h3>
    <p style="margin: 0; color: #555;"><em>Bangalore, India · Jan 2019 – Jun 2019</em></p>
    <ul>
      <li>Enhanced financial data inquiry/maintenance systems by developing secure and efficient APIs.</li>
      <li>Optimized backend data flows for performance and reliability.</li>
    </ul>
  </div>


  <!-- Research Experience -->
  <div style="
      border: 1px solid #ddd;
      border-radius: 10px;
      padding: 20px;
  ">
    <h3>Volunteer Research Assistant — UC San Diego</h3>
    <p style="margin: 0; color: #555;"><em>Remote · Dec 2023 – Jun 2024</em></p>
    <ul>
      <li>Built domain-specific knowledge graphs using LLM-driven extraction and transformation pipelines in Python.</li>
      <li>Applied transformer architectures to improve semantic representation of tabular and relational datasets.</li>
    </ul>
  </div>

</div>

</div>


<!-- Project Cards Section -->
<div style="
  display: flex;
  flex-wrap: wrap;
  gap: 20px;
  margin-top: 30px;
">

  <!-- Card 1 -->
  <div style="
    flex: 1 1 280px;
    border: 1px solid #ddd;
    border-radius: 10px;
    padding: 16px;
  ">
    <img src="imgs/fff.png"
         alt="Finetuning for Flashcards"
         style="width: 100%; border-radius: 6px;" />
    <h3><a href="https://github.com/Vaaruni2797/FinetuningForFlashcards">Finetuning for Flashcards</a></h3>
    <p>AI-powered flashcard generator using fine-tuned transformers.</p>
  </div>

  <!-- Card 2 -->
  <div style="
    flex: 1 1 280px;
    border: 1px solid #ddd;
    border-radius: 10px;
    padding: 16px;
  ">
    <img src="imgs/pcot.png"
         alt="Pick-U-CoT"
         style="width: 100%; border-radius: 6px;" />
    <h3><a href="https://github.com/Vaaruni2797/pickucot">Pick-U-CoT</a></h3>
    <p>Framework for probing causal hint use and explanation faithfulness.</p>
  </div>

  <!-- Card 3 -->
  <div style="
    flex: 1 1 280px;
    border: 1px solid #ddd;
    border-radius: 10px;
    padding: 16px;
  ">
    <img src="imgs/mlp.png"
         alt="Attention-MLPs-in-Transformer-XOR"
         style="width: 100%; border-radius: 6px;" />
    <h3><a href="https://github.com/Vaaruni2797/Attention-MLPs-in-Transformer-XOR">Attention-MLPs-in-Transformer-XOR</a></h3>
    <p>Experiments analyzing grokking, attention entropy, and representation phase transitions.</p>
  </div>

</div>
