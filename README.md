# AI Art Detector

**Background:**

The rapid advancement of artificial intelligence (AI) has not only transformed various industries but has also found its way into the `realm of art`. AI-generated art, created using algorithms and machine learning techniques, has gained significant attention and popularity in recent years. However, this rise in AI art has also raised concerns within the art community and the design industry about the `authenticity` and originality of these creations. In the art community, as well in the design industry, the soul of art holds crucial matters. Art is not only about its final outcome or visual representation--rather, brings depths and meaning to our creatives efforts. 

Other than originality, AI-generated "art: also holds frustration among artist whose works are used to `train the machine models`. This issue goes beyond questioning the "authenticity of an art" as it delves more to ethical considerations in the use of an artist's work without proper attribute and disregard artists' intelectual property. In a way, the sentiment is more like an `aim towards "art-theft"` rather than denying the "potential of technology" or depicting fears of robot "stealing our jobs". 

To address this challenge, we aim to develop a Convolutional Neural Network (CNN) model to detect AI-generated art. This would be particularly valuable in various domains, including cases of art competitions, concept designs, and the design industry as a whole where originality holds significant importance. Even can help AI artists themselves in evaluating the authenticity of artworks. It provides a meaning to look at the evolving landscape of art. By integrating this technology, the art community and the design industry can adapt to the changing dynamics and explore new opportunities for collaboration and artistic expression.

**Problem Statement:**

The emergence of AI-generated art presents a unique challenge for the art community and the design industry. We aim to develop a Convolutional Neural Network (CNN) model to detect AI-generated art. By training the model on a dataset consisting of both AI-generated and human-made artworks, we can leverage the power of deep learning algorithms to identify patterns and features that distinguish between the two types of art. The model would be useful for art curators, design industry, as well as other domains that may value these aspects for any cause. 


**Dataset:**

Dataset used is the dataset from [HuggingFace AI or Not Competitions](https://huggingface.co/datasets/competitions/aiornot) which was commited on January 25th. Although it is not very recent, an open source dataset for this topic hasn't yet been widely circulated yet (creating datasets like this comes down to artists' permissions) and is by far the most varied dataset we could find. The dataset consists of 18557 images for training, labeled '0' for human-made/ real-life photographs and '1' for AI-generated art/ images. 

**Disclamer:**

We acknowledge that the perception of what is "real" and what is not ultimately lies in the eyes of the beholder. Please note that while our AI art detection model can be a valuable assist, it is should not be the sole determinant of artistic authenticity. It is meant to be used as a tool to gain a richer understanding and appreciation of art in its various forms. Lastly, while we do fight towards artists' rights, we also believe in a world where different forms of creativity can `coexist`.