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