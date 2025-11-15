# AI Art Detector

**External link:** [Model Deployment](https://huggingface.co/spaces/Dissashaf/ai-or-human)

## Introduction
**Background:**

The rapid advancement of artificial intelligence (AI) has not only transformed various industries but has also found its way into the `realm of art`. AI-generated art, created using algorithms and machine learning techniques, has gained significant attention and popularity in recent years. However, this rise in AI art has also raised concerns within the art community and the design industry about the `authenticity` and originality of these creations. In the art community, as well in the design industry, the soul of art holds crucial matters. Art is not only about its final outcome or visual representation--rather, brings depths and meaning to our creatives efforts. 

Other than originality, AI-generated "art: also holds frustration among artist whose works are used to `train the machine models`. This issue goes beyond questioning the "authenticity of an art" as it delves more to ethical considerations in the use of an artist's work without proper attribute and disregard artists' intelectual property. In a way, the sentiment is more like an `aim towards "art-theft"` rather than denying the "potential of technology" or depicting fears of robot "stealing our jobs". 

To address this challenge, I developed a Convolutional Neural Network (CNN) model to detect AI-generated art. The model is trained on a dataset containing both human-made and AI-generated artworks, learning to identify patterns and features that distinguish between the two types of art. This would be particularly valuable in various domains, including cases of art competitions, concept designs, and the design industry as a whole where originality holds significant importance. Even can help AI artists themselves in evaluating the authenticity of artworks. It provides a meaning to look at the evolving landscape of art. By integrating this technology, the art community and the design industry can adapt to the changing dynamics and explore new opportunities for collaboration and artistic expression.

**Dataset:**

Dataset used is the dataset from [HuggingFace AI or Not Competitions](https://huggingface.co/datasets/competitions/aiornot) which was commited on January 25th. Although it is not very recent, an open source dataset for this topic hasn't yet been widely circulated yet (creating datasets like this comes down to artists' permissions) and is by far the most varied dataset I could find. The dataset consists of 18,557 images for training, labeled '0' for human-made/ real-life photographs and '1' for AI-generated art/ images. 

## Disclamer

As an illustrator who has been painting and creating artwork all my life, I strongly value the integrity and authenticity of artistic expression. While I develop this AI art detection model, please note:  

- I acknowledge that the perception of what is "real" and what is not ultimately lies in the eyes of the beholder. This model is meant as a **support tool**, not a definitive judge of artistic authenticity, and should not be used solely based on stereotypes or whether an artwork “looks AI-generated” or “looks human-made.”
- I am **firmly against art theft** and the unauthorized use of artists’ work.  
- I acknowledge that AI technology exists and can be leveraged ethically, and I believe it can **coexist with human creativity** when used responsibly. 

This project focuses strictly on **detection and protection**, providing insight, supporting decision-making, and safeguarding artists’ rights. It is **not intended to endorse AI-generated art**. The project also aims to engage responsibly with AI technology and appreciate the evolving landscape of art.
