# Emotionally Aware Chatbot for Responding to Indonesian Product Reviews
This research proposes a model to build an emotionally aware chatbot to respond to Indonesian product reviews. 
Six emotion recognition models are examined using two pre-trained models and a multilayer perceptron of a feedforward artificial neural network.
The full report can be seen in [**this link**](http://www.ijicic.org/ijicic-190315.pdf).

Moreover, this research also has evaluated the emotinally aware chatbot and its believability factor.
The experiment's evaluation results show that implementing the emotion recognition model on the chatbot increases its believability. 
* On average, the believability measures in interaction type B (with an emotion model) are enhanced 1.71 times compared to interaction type A (a basic model).
* Integrating a chatbot avatar into the interaction system also heightens the believability factor. Using avatars in chatbots increases the system's believability variables by 1.17 times compared to not using avatars.
The full report can be seen in [**this link**](https://ieeexplore.ieee.org/document/10488202).

## Resources
This work proposes a product review dataset annotated with Shaver's emotion model and several predefined response templates for each emotion to enable answer variations.
The supporting research materials are as follows:
- [**Product Review Dataset with Emotions**](https://github.com/rhiosutoyo/Indonesian-EAC/tree/main/dataset/product-reviews-with-emotions)<br>
It consists of Amazon Review Data that is annotated with emotions.
The reliability of agreement between annotators for the proposed product review dataset is substantial (κ = 0.66).
- [**Knowledge Database**](https://github.com/rhiosutoyo/Indonesian-EAC/blob/main/dataset/response-templates/predefined_respond_semicolon_delimited.csv)<br>
It consists of predefined response templates for answering product reviews.

## BibTeX Citation
If you use the research reports in a scientific publication, we would appreciate using the following citations:

```
@article{rhio2023emotionally,
	title={Emotionally Aware Chatbot for Responding to Indonesian Product Reviews},
	author={Sutoyo, Rhio and Warnars, Harco Leslie Hendric Spits and Isa, Sani Muhamad and Budiharto, Widodo},
	journal={International Journal of Innovative Computing, Information and Control},
	volume={19},
	number={03},
	pages={861},
	year={2023},
	publisher={ICIC International},
	ISSN={1349-4198},
	DOI={10.24507/ijicic.19.03.861},
	URL={https://cir.nii.ac.jp/crid/1390014337396703232}
}
```
```
@INPROCEEDINGS{10488202,
  author={Sutoyo, Rhio and Warnars, Harco Leslie Hendric Spits and Muhamad Isa, Sani and Budiharto, Widodo},
  booktitle={2023 15th International Congress on Advanced Applied Informatics Winter (IIAI-AAI-Winter)}, 
  title={The Impact of Emotion Recognition Models Towards Believability Factor of Chatbots}, 
  year={2023},
  volume={},
  number={},
  pages={64-68},
  keywords={Emotion recognition;Atmospheric measurements;Avatars;Chatbots;Particle measurements;Informatics;emotions recognition;emotionally aware chatbot;believability factor;natural language processing},
  doi={10.1109/IIAI-AAI-Winter61682.2023.00020}}
}
```
