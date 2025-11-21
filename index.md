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

    <a href="https://github.com/Vaaruni2797" 
     target="_blank"
     style="text-decoration: none;">
     🐈‍⬛ GitHub
    </a>
  
    <a href="https://www.linkedin.com/in/vaaruni-desai/" 
       target="_blank"
       style="text-decoration: none;">
       🔗 LinkedIn
    </a>
  
    <a href="mailto:vaaruni.desai@gmail.com"
       style="text-decoration: none;">
       📧 Email
    </a>
  
    <a href="https://medium.com/@vaaruni.desai" 
       target="_blank"
       style="text-decoration: none;">
       🖋️ Medium
    </a>
  </div>
</div>
<style>
footer {
  display: none !important;
}
</style>

<!-- Project Cards Section -->
<div style="
  display: flex;
  flex-wrap: wrap;
  gap: 20px;
  margin-top: 30px;
">

  <div class="project-card">
    <img src="imgs/fff.png"
         alt="Finetuning for Flashcards"
         style="width: 100%; border-radius: 6px;" />
    <h3><a href="https://github.com/Vaaruni2797/FinetuningForFlashcards">Finetuning for Flashcards</a></h3>
    <p>AI-powered flashcard generator using fine-tuned transformers.</p>
  </div>

  <div class="project-card">
    <img src="imgs/pcot.png"
         alt="Pick-U-CoT"
         style="width: 100%; border-radius: 6px;" />
    <h3><a href="https://github.com/Vaaruni2797/pickucot">Pick-U-CoT</a></h3>
    <p>Framework for probing causal hint use and explanation faithfulness.</p>
  </div>

  <div class="project-card">
    <img src="imgs/mlp.png"
         alt="Attention-MLPs-in-Transformer-XOR"
         style="width: 100%; border-radius: 6px;" />
    <h3><a href="https://github.com/Vaaruni2797/Attention-MLPs-in-Transformer-XOR">The Role of Attention and MLPs in Transformer XOR Computation</a></h3>
    <p>Experiments analyzing grokking, attention entropy, and representation phase transitions.</p>
  </div>

</div>

<style>
/* Ensure project cards always align 3 per row on desktop */
.project-card {
  border: 1px solid #ddd;
  border-radius: 10px;
  padding: 16px;
  box-sizing: border-box;
  flex: 0 0 calc(33.333% - 20px);
}

/* 2 per row on medium screens */
@media (max-width: 900px) {
  .project-card {
    flex: 0 0 calc(50% - 20px);
  }
}

/* 1 per row on small/mobile */
@media (max-width: 600px) {
  .project-card {
    flex: 0 0 100%;
  }
}
</style>
