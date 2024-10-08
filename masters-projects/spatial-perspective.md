Perspective and Spatial Language
When people hold conversations we are constantly speaking about things which has an implicit or explicit point of view. E.g. if I say “there’s a cup to the left of the plate” this might be from my point of view, your point of view, an intrinsic point of view, etc. In dialogue the point of view being used is constantly shifting, as noted e.g. by the CUPS dataset. There they found that point of view information can shift without any explicit linguistic markers, but that sometimes it is not clear which point of view is being used and thus interlocutors ask clarifying questions or mark it explicitly.

The current state of the arg in grounded language understanding does not handle this problem explicitly.  Mostly we ask models to speak about images taken from a single perspective and we do not think much about the problems that arise when we act in the real world with a human or other agent in the same space.

The purpose of this project is to develop an understanding of how well current state of the art does at communicating when interlocutors are seeing a scene from different points of view. The main questions we are asking are: "How well do current state of the art models model perspective? Can we train models to take into account different perspectives?"

[The CUPS dataset](https://www.semanticscholar.org/paper/Local-Alignment-of-Frame-of-Reference-Assignment-in-Dobnik-Kelleher/496e5eb5f302e20d2bcd84b5aad988912bc9d9fb) consists of longer human dialogues (1h) about cups on a table where the participants see the situation from different points of view. Within these dialogues many different language games arise. A project could look at modeling one of these game types.

To Your Left dataset, this dataset consists currently of images of geometric objects that are taken from various different points of view. We are currently studying the emergent languages which arise when the two agents attempt to learn to communicate about these images. You could extend this data by adding natural language labels and training models in a supervised way to produce or recognize objects inside of this set-up. You could also gather human data, to see how people communicate about this task. Or you could study emergent languages yourself, there are many interesting modeling and analysis challenges that could be tackled. 

You could investigate the ability of current state of the art LLMs such as ChatGPT 4o or models like CLIP to see how well they are able to take different perspectives. In this case there is scope to not just look at spatial language but also perspective taking as a whole, e.g. from the perspective of a student, is this a good project? What about from the perspective of a post-doc who is trying to get a student to do his work? These are the type of questions you could ask ChatGPT. The challenge here will be on the side of analysis rather than modeling but could also include prompt engineering. 

We are also interested in projects which have to do with studying emergent languages in language games (e.g. in the EGG framework, see readings below). 

Example reading: 

https://www.semanticscholar.org/reader/354b48677e314ef2f47512c5a81723cfd17dd05d 

https://www.semanticscholar.org/paper/Perspective-alignment-in-spatial-language-Steels-Loetzsch/d568217f0e3f43b2c1a40b96da7bd4d8b8f9d6dc 

https://www.semanticscholar.org/paper/EGG%3A-a-toolkit-for-research-on-Emergence-of-in-Kharitonov-Chaabouni/d6c799129b8eb54db932cf03fae89000897fda2d 

https://www.semanticscholar.org/paper/Learning-to-Compose-Spatial-Relations-with-Grounded-Ghanimifard-Dobnik/d56fda7043eb683ecfcdd62277e82480e75b9f14 

https://www.semanticscholar.org/paper/A-computational-analysis-of-the-apprehension-of-Logan-Sadler/52d48cf7ccbe0b95808be7de1157e27f9a4e9d88 
