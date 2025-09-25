---
title: "Improving Zero-Shot Reasoning Using Dynamic Non-Verbal Tokens"
category: project
featured: true
metadata_only: false
author: Tanya Marwah*, Zhili Feng*, Lester Mackey, Nicolo Fusi, David Alvarez-Melis
actual_url: https://drive.google.com/file/d/1y4hQ03PmEr2AW5VTsts7JJQoSPZywLaW/view
url: https://drive.google.com/file/d/1y4hQ03PmEr2AW5VTsts7JJQoSPZywLaW/view
abstract:
|
    We explore an approach to improve the reasoning capabilities of large 
    language models without explicit verbalization of their reasoning process by introducing continuous thought embeddings derived from the model’s hidden state.
---

<p class="abstract">
Large language models can reason more effectively without spelling out their steps. This work introduces input-dependent thought embeddings, constructed as sparse combinations of existing token embeddings using an additional fine-tuned layer. Appending just a handful of these continuous embeddings to the prompt doubles the zero-shot accuracy of Llama3-8B on GSM8K (16% → 35%) and lifts MATH from 11% to 26%, all while keeping inference-time token budgets low. The results highlight the promise of continuous, non-verbal reasoning aids—especially for domains where explicit chain-of-thought supervision is scarce.
</p>

[PDF](https://drive.google.com/file/d/1y4hQ03PmEr2AW5VTsts7JJQoSPZywLaW/view)
