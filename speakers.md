## Stefano Soatto: The Emergence Theory of Deep Learning

### Abstract

Theories of Deep Learning are like anatomical parts best not named explicitly in an abstract: Everyone seems to have one. That is why it is important for a theory to be inclusive: It has to be compatible with all known results, and at the very least explain known empirical phenomena. I will describe the basic elements of the Emergence Theory of Deep Learning, that started as a general theory for representations, and is comprised of three parts: (1) Formalization of desirable properties a representation should possess, based on classical principles of statistical decision and information theory: Sufficiency, Invariance, Minimality, Independence. This has nothing to do with Deep Learning, but is closely tied with the notion of Information Bottleneck and Variational Inference. (2) Description of common empirical losses employed in Deep Learning (e.g., empirical cross-entropy), and implicit or explicit regularization practices, including Dropout, Pooling, as well as recently proven additive entropic components of the loss computed by SGD. Finally, (3) theorems and bounds that show that minimizing suitably (implicitly or explicitly) regularized losses with SGD with respect of the weights implies optimization of the loss described in (1) with respect to the activations of a deep network, and therefore achievement of the desirable properties of the resulting representation formalized in (1). The link between the two is specific to the architecture of deep networks. The theory is related to the Information Bottleneck, but not that described in recent theories, but instead a new Information Bottleneck for the weights of a network, rater than the activation. It is also related to PAC-Bayes, and could be derived with that lens, providing independent validation. It is also related to Kolmogorov complexity. It is also related to “flat minima”, in the sense that the crucial regularizing quantity - the information in the weights - bounds the nuclear norm of the Hessian around critical points. It also shows that there is no need to rethink regularization, and that - unlike the Hessian - information is invariant to reparametrization.

### Bio

Stefano Soatto is Professor of Computer Science and Electrical Engineering, and Director of the UCLA Vision Lab, in the Henry Samueli School of Engineering and Applied Sciences at UCLA. He is also Director of Applied Science at Amazon AI - AWS. He received his Ph.D. in Control and Dynamical Systems from the California Institute of Technology in 1996; he joined UCLA in 2000 after being Assistant and then Associate Professor of Electrical and Biomedical Engineering at Washington University, and Research Associate in Applied Sciences at Harvard University. Between 1995 and 1998 he was also Ricercatore in the Department of Mathematics and Computer Science at the University of Udine - Italy. He received his D.Ing. degree (highest honors) from the University of Padova- Italy in 1992. Dr. Soatto is the recipient of the David Marr Prize for work on Euclidean reconstruction and reprojection up to subgroups. He also received the Siemens Prize with the Outstanding Paper Award from the IEEE Computer Society for his work on optimal structure from motion. He received the National Science Foundation Career Award and the Okawa Foundation Grant. He was Associate Editor of the IEEE Transactions on Pattern Analysis and Machine Intelligence (PAMI) and a Member of the Editorial Board of the International Journal of Computer Vision (IJCV) and Foundations and Trends in Computer Graphics and Vision, Journal of Mathematical Imaging and Vision, SIAM Imaging. He is a Fellow of the IEEE.

## Alison Gopnik: What 4 year olds can do and AI cannot yet

### Abstract

The last few years has seen dramatic progress in artificial intelligence, particularly in machine learning, most notably in new work in the connectionist tradition, such as deep learning, but also in work on inferring structured generative models from data. Nevertheless, this new work still is limited to relatively narrow and well-defined spaces of hypotheses. In contrast, human beings and human children, in particular, characteristically generate new, uninstructed and unexpected, yet relevant and plausible hypotheses. I will present several studies showing a surprising pattern. Not only can preschoolers learn abstract higher-order principles from data, but younger learners are actually better at inferring unusual or unlikely principles than older learners and adults. I relate this pattern to computational ideas about search and sampling, to evolutionary ideas about human life history, and to neuroscience findings about the negative effects of frontal control on wide exploration.  My hypothesis is that the evolution of our distinctively long, protected human childhood allows an early period of broad hypothesis search, exploration and creativity, before the demands of goal-directed action set in. This evolutionary solution to the search problem may have implications for AI solutions.

### Bio

Alison Gopnik is a professor of psychology and affiliate professor of philosophy at the
University of California at Berkeley. She received her BA from McGill University and
her PhD. from Oxford University. She is an internationally recognized leader in the study
of children’s learning and development and was one of the founders of the field of
“theory of mind”, an originator of the “theory theory” of children’s development and
more recently introduced the idea that probabilistic models and Bayesian inference could
be applied to children’s learning. She has held a Center for Advanced Studies in the
Behavioral Sciences Fellowship, the Moore Distinguished Scholar fellowship at the
California Institute of Technology, the All Souls College Distinguished Visiting
Fellowship at Oxford, and King’s College Distinguished Visiting Fellowship at
Cambridge. She is an elected member of the Society of Experimental Psychologists, and
the American Academy of Arts and Sciences and a fellow of the Cognitive Science
Society and the American Association for the Advancement of Science. She has been
continuously supported by the NSF and was PI on a 2.5 million dollar interdisciplinary
collaborative grant on causal learning from the McDonnell Foundation.

She is the author or coauthor of over 100 journal articles and several books including
“Words, thoughts and theories” MIT Press, 1997, and the bestselling and critically
acclaimed popular books “The Scientist in the Crib” William Morrow, 1999, “The
Philosophical Baby; What children’s minds tell us about love, truth and the meaning of
life”, and “The Gardener and the Carpenter”, Farrar, Strauss and Giroux, the latter two
won the Cognitive Development Society Best Book Prize in 2009 and 2016. She has also
written widely about cognitive science and psychology for The New York Times, The
Atlantic, The New Yorker, Science, Scientific American, The Times Literary
Supplement, The New York Review of Books, New Scientist and Slate, among others.
Her TED talk on her work has been viewed more than 2.9 million times. And she has
frequently appeared on TV and radio including “The Charlie Rose Show” and “The
Colbert Report”. Since 2013 she has written the Mind and Matter column for the Wall
Street Journal. She lives in Berkeley with her husband Alvy Ray Smith, and has three
children and three grandchildren.

## Mike Lewis: Deal or No Deal? End-to-End Learning for Negotiation Dialogues

### Abstract

Much of human dialogue occurs in semi-cooperative settings, where agents with different goals attempt to agree on common decisions. Negotiations require complex communication and reasoning skills, but success is easy to measure, making this an interesting task for AI. While neural networks have been effective in imitating human language, this task requires them to use language strategically to achieve a goal. We gather a large dataset of human-human negotiations on a multi-issue bargaining task, where agents who cannot observe each other's reward functions must reach an agreement via natural language dialogue. For the first time, we show it is possible to train end-to-end models for negotiation, which must learn both linguistic and reasoning skills with no annotated dialogue states. We also introduce dialogue rollouts, in which the model plans ahead by simulating possible complete continuations of the conversation, and find that this technique dramatically improves performance. Time permitting, I will also discuss recent work on learning discrete latent representations of dialogue messages, which decouples the semantics of a message from its linguistic realization, allowing more effective use of rollouts and reinforcement learning.

### Bio

Mike Lewis is a scientist at Facebook AI Research, working on connecting language and reasoning. Previously he was a postdoc at the University of Washington, developing search algorithms for neural structured prediction, and has a PhD from the University of Edinburgh on combining symbolic and distributed representations of meaning. He has won an Outstanding Submission Award at the 2014 ACL Workshop on Semantic Parsing, Best Paper at EMNLP 2016 and Best Resource Paper at ACL 2017. His work has been extensively covered in the media, with varying levels of accuracy, everywhere from New Scientist to the front page of The Sun.

## Kevin Murphy: Probabilistic models for vision and language

### Abstract

In this talk, I summarize various approaches to mapping images to captions, and our recent work on the reverse process of generating images from text. In particular, I will discuss our work on
- visually grounded referring expressions (CVPR'16, https://arxiv.org/abs/1511.02283)
- discriminative image captioning (CVPR'17, https://arxiv.org/abs/1701.02870)
- optimizing semantic metrics for image captioning using RL (ICCV'17, https://arxiv.org/abs/1612.00370)
- variational autoencoders for images and text (submitted to ICLR'18),  https://arxiv.org/abs/1705.10762


### Bio

Kevin Murphy is a research scientist at Google in Mountain View, California, where he works on AI, machine learning, and computer vision. Before joining Google in 2011, he was an associate professor (with tenure) of computer science and statistics at the University of British Columbia in Vancouver, Canada. Before starting at UBC in 2004, he was a postdoc at MIT.  Kevin got his BA from U. Cambridge, his MEng from U. Pennsylvania, and his PhD from UC Berkeley. He has published over 80 papers in refereed conferences and journals, as well as an 1100-page textbook called "Machine Learning: a Probabilistic Perspective" (MIT Press, 2012), which was awarded the 2013 DeGroot Prize for best book in the field of Statistical Science. Kevin was also the (co) Editor-in-Chief of JMLR (the Journal of Machine Learning Research) 2012-2017.

## Thomas Funkhouser: Data-Driven Methods for Matching, Labeling, and Synthesizing 3D Shapes

### Abstract

A classic problem in computer vision is to train a system to recognize,
label, and synthesize a 3D model from partial camera observations.  In
this talk, I will discuss three projects that address this problem using
3D convolutional neural networks.  The first learns a 3D local shape
descriptor with self-supervision from multiple RGB-D views aligned with
a SLAM reconstruction. The second learns to synthesize novel 3D objects
in an interactive modeling tool using a 3D Generative Adversarial
Network.   The third learns to both complete and label semantics for the
3D space occluded in an RGB-D image.  For each project, I will discuss
the problem formulation, dataset curation, network architecture, and
potential applications.  This is joint work with Angel X. Chang, Angela
Dai, Matthew Fisher, Maciej Halber, Jerry Liu, Matthias Niessner,
Manolis Savva, Shuran Song, Fisher Yu, Yinda Zhang, and Andy Zeng.

### Bio

Thomas Funkhouser is the David M. Siegel Professor of Computer Science
at Princeton University.  He received a B.S. in biological sciences from
Stanford University in 1983, a M.S. in computer science from UCLA in
1989, and a PhD in computer science from UC Berkeley in 1993.  He was a
member of the technical staff at Bell Labs during 1993-1997.  He is
currently a visiting professor at Stanford and a part-time contractor at
Google.  He has published more than 100 research papers and received
several awards, including the ACM SIGGRAPH Computer Graphics Achievement
Award, NSF Career Award, University Council Excellence in Teaching
Awards, Emerson Electric, E. Lawrence Keyes Faculty Advancement Award,
Google Faculty Research Awards, and a Sloan Fellowship.

## Dileep George: Visual Perception, Data Efficiency, and Deep Learning

### Abstract

We'll start by exploring the classic paper on bias-variance dilemma in neural networks and understand the current successes and failures of convolutional neural networks from this context. If adding more biases is among the required modifications, where would these biases come from? Can studies about the visual cortex teach us something about these biases? We'll use the Lee and Mumford paper to understand more about what the visual cortex is really doing. Is it just a feed-forward classifier, or something different? What if classification is just a side effect of "inference to the best explanation", as Lee and Mumford would argue? From the context of these questions, we'll dive deeper into the Recursive Cortical Network (RCN) paper, whose representational choices are heavily inspired by the human brain and does classification as a side effect of inference to best explanation, and compare and contrast it with capsule networks which also has many similar representational choices. We'll end with a discussion on the role of reasoning/inference in visual perception and why that is important for building artificial general intelligence.

### Bio

Dileep is founder of Vicarious AI, where he leads the development of a general AI layer for robotics. Vicarious is a pioneer of brain-inspired and data-efficient AI algorithms, and they gained world-wide attention for breaking CAPTCHAs with very little training data. Dileep has authored several influential papers, published in Science, NIPS, ICML and CVPR and his research has been featured in NYT, WSJ and NPR. Before cofounding Vicarious, Dileep was CTO of Numenta, an AI company he cofounded with Jeff Hawkins and Donna Dubinsky. Before Numenta, Dileep was a Research Fellow at the Redwood Neuroscience Institute. Dileep’s research on hierarchical models of the brain earned him a PhD in Electrical Engineering from Stanford University.  He has an MS in Electrical Engineering from Stanford and a B.Tech in EE from IIT Mumbai.

## Bruno Olshausen: Perception in Brains and Machines

### Abstract

The quest to understand intelligence in brains and to build it in machines is certain to become one of the great intellectual and technological endeavors of the 21st century. Here I shall argue for a multidisciplinary approach that sees both neuroscience and engineering as trying to solve a common set of core problems. I shall draw upon three examples: 1) The theory of sparse coding which play a key role in our understanding of the visual system also forms the basis of modern image analysis and recognition pipelines; 2) Studies of eye movements and foveated imaging inform the use of active vision strategies in robotics; and 3) The end of Moore’s law is steering engineers toward neuroscience in order to learn how reliable computation can be performed with unreliable components.

### Bio

Bruno Olshausen is Professor of Neuroscience and Optometry at the University of California, Berkeley. He also serves as Director of the Redwood Center for Theoretical Neuroscience, an interdisciplinary research group focusing on mathematical and computational models of brain function. He received B.S. and M.S. degrees in electrical engineering from Stanford University, and a Ph.D. in Computation and Neural Systems from the California Institute of Technology. He was Assistant and subsequently Associate Professor in the Departments of Psychology and Neurobiology, Physiology and Behavior at UC Davis from 1996-2005. He has been at UC Berkeley since 2005. Olshausen's research aims to understand the information processing strategies employed by the brain for doing tasks such as object recognition and scene analysis.


## Alex Kurakin: Adversarial Examples

### Abstract

Adversarial examples are small perturbations that cause misclassification in machine learning classifiers. Adversarial examples provide a tool to fool machine learning classifiers thus could be a security problem. In this lecture we study in details what adversarial examples are, how to craft them and how to make classifiers robust to them. Also we will look into some state of the art results and interesting observations such as adversarial examples for humans.

### Bio

Alex Kurakin is a research engineer for Google Brain, where his research focuses on various aspects of adversarial machine learning, including the security and robustness of neural networks. Alex holds a PhD in computer vision and image processing from the Moscow Institute of Physics and Technology. In his work Alex showed that adversarial examples exist even when perceived through physical sensors and also was the first person to scale adversarial training to ImageNet size problems. He also was a main organizer of the adversarial examples competition which was held as a part of NIPS17 competition track.


## Mohammad Norouzi: Expressive Structured Models of Images and Objects

### Abstract

Feedforward neural networks are capable of learning complex functional dependencies between different types of inputs and outputs. However, when learning a mapping from inputs to dependent outputs in problems such as image segmentation, super-resolution, and colorization, one can benefit from learning statistical patterns among the output variables too. Accordingly, we advocate learning feature representation in the joint space of inputs and outputs. I will start by reviewing large margin approaches to structured prediction. Then, I will present deep value networks, a family of energy based models that estimate the task reward given an output configuration and a corresponding input. Once the value network is trained, we perform inference by gradient ascent to find output configurations with large scores according to the value network. I will show results on multi-label classification and image segmentation. Then, I will discuss why this family of models does not directly apply to super-resolution and colorization because such mappings are one to many, and we do not know the task reward metric. I will discuss why autoregressive probabilistic models are suitable for learning one-to-many mappings, and show our super resolution and colorization results based on a pixel recursive architecture. I will conclude by discussing image and object representations that attempt to incorporate 3D geometry via a sparse set of keypoints. I will present our recent work on end-to-end geometric reasoning for discovery of 3D keypoints on object classes like cars, chairs, and airplanes from the shapenet dataset.

### Bio

Mohammad Norouzi is a Senior Research Scientist at Google Brain. He completed the PhD in Computer Science at the University of Toronto working under the supervision of David Fleet supported by a Google Fellowship. His PhD research focused on compact discrete representations for large-scale similarity search. Since joining Google Brain, he has been working at the intersection of deep learning, reinforcement learning, and structured output prediction, co-developing Google's neural machine translation system and the path consistency learning (PCL) algorithm for reinforcement learning.


## Abhinav Gupta: SuperSizing and Empowering Visual Learning

### Abstract

In the last decade, we have made significant advances in field of computer vision thanks to supervised learning. But this passive supervision of our models has now become our biggest bottleneck.  In this talk, I will discuss our efforts towards scaling up and empowering learning. First, I will show how the amount of labeled data is still a crucial factor in representation learning. I will then discuss one possible avenue on how we can scale up learning by using self-supervision. Next, I will discuss how we can scale up semantic learning to 10x and more categories by using visual knowledge and graph-based reasoning. But just scaling on amount of data and categories is not sufficient. We also need to empower our learning algorithms with the ability to control their own supervision. In the third part of the talk, I will discuss how we can move from passive to interactive learning in the context of VQA. Our agents live in the physical world and need the ability to interact in the physical world. Towards this goal, I will finally present our efforts in large-scale learning of embodied agents in robotics.

### Bio

Abhinav Gupta is an Associate Professor at the Robotics Institute, Carnegie Mellon University. Abhinav's research focuses on scaling up learning by building self-supervised, lifelong and interactive learning systems. Specifically, he is interested in how self-supervised systems can effectively use data to learn visual representation, common sense and representation for actions in robots. Abhinav is a recipient of several awards including ONR Young Investigator Award, PAMI Young Research Award, Sloan Research Fellowship, Okawa Foundation Grant, Bosch Young Faculty Fellowship, YPO Fellowship, IJCAI Early Career Spotlight, ICRA Best Student Paper award, and the ECCV Best Paper Runner-up Award. His research has also been featured in Newsweek, BBC, Wall Street Journal, Wired and Slashdot.


## Ryan Adams: Building Probabilistic Structure into Massively Parameterized Models

### Abstract

Scientific applications of machine learning typically involve the identification of interpretable structure from high-dimensional observations. It is often challenging, however, to balance the flexibility required for high dimensional problems against the parsimonious structure that helps us model physical reality. I view this challenge through the lens of semiparametric modeling, in which a massively-parameterized function approximator is coupled to a compact and interpretable probabilistic model. Of particular interest in this vein is the merging of deep neural networks with graphical models containing latent variables, which enables each component to play to its strengths. I will discuss several different classes of such models, and various applications, in areas such as neuroscience.

### Bio

Ryan Adams is a Professor of Computer Science at Princeton University and Research Scientist at Google Brain. Ryan completed his Ph.D. in physics under David MacKay FRS at the University of Cambridge, where he was a Gates Cambridge Scholar. Following his Ph.D. Ryan spent two years as a CIFAR Junior Research Fellow at the University of Toronto. From 2011-2016, he was an Assistant Professor at Harvard University in the School of Engineering and Applied Sciences. Ryan was co-founder and CEO of Whetlab LLC, a machine learning startup that was acquired by Twitter in 2015.  Ryan has won paper awards at ICML, UAI, and AISTATS, received the DARPA Young Faculty Award and the Alfred P. Sloan Fellowship. He also co-hosted the popular Talking Machines podcast.
