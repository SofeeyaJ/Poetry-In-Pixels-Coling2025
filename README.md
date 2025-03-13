# Poetry-In-Pixels-Coling2025
 This repository hosts the code and datasets associated with our paper, "Poetry in Pixels: Prompt Tuning for Poem Image Generation via Diffusion Models."


 Abstract:

The task of text-to-image generation has encountered significant challenges when applied to literary works, especially poetry.
Poems are a distinct form of literature, with meanings that frequently transcend beyond the literal words. 
PoemToPixel framework designed to generate images that visually represent the inherent meanings of poems.
Our approach incorporates the concept of prompt tuning in our image generation framework to ensure that the resulting images closely align with the poetic content. 
In addition, we propose the PoeKey algorithm, which extracts three key elements in the form of emotions, visual elements, and themes from poems 
to form instructions which are subsequently provided to a diffusion model for generating corresponding images. 
Furthermore, to expand the diversity of the poetry dataset across different genres and ages, we introduce MiniPo,
a novel multimodal dataset comprising 1001 children's poems and images. Leveraging this dataset alongside PoemSum, 
we conducted both quantitative and qualitative evaluations of image generation using our PoemToPixel framework.
This paper demonstrates the effectiveness of our approach and offers a fresh perspective on generating images from literary sources.



Any resources, ideas, or methodologies derived from our work should be properly cited using the following reference.

@inproceedings{jamil-etal-2025-poetry,
    title = "Poetry in Pixels: Prompt Tuning for Poem Image Generation via Diffusion Models",
    author = "Jamil, Sofia  and
      Reddy, Bollampalli Areen  and
      Kumar, Raghvendra  and
      Saha, Sriparna  and
      J, Joseph K.  and
      Goswami, Koustava",
    editor = "Rambow, Owen  and
      Wanner, Leo  and
      Apidianaki, Marianna  and
      Al-Khalifa, Hend  and
      Eugenio, Barbara Di  and
      Schockaert, Steven",
    booktitle = "Proceedings of the 31st International Conference on Computational Linguistics",
    month = jan,
    year = "2025",
    address = "Abu Dhabi, UAE",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2025.coling-main.620/",
    pages = "9224--9237",
}


