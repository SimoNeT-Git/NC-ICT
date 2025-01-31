# NC-ICS

Exercises for the class **Neuromorphic Computing and Integrative Cognitive Systems** (a.y. 2020-2023) held by prof. Silvio P. Sabatini @ DIBRIS (University of Genoa, Italy).

---

To play with these notebooks open [Colab](http://colab.research.google.com/github) and type "simo-net", then navigate to the "NC-ICS" repository and finally choose the notebook you want to open.

To autonomously and easily navigate through this repository, read the following brief explanation of the main notebooks available:

 - "GaborFiltering.ipynb" is just a basic hands-on demonstration on how to design and use Gabor filters for standard computer-vision applications.
 - "Start.ipynb" is an introduction to the LIF neuron model and the neural simulator Brian2, a useful tool for computational neuroscientists. The following 3 exercises (task1, task2, task3) are intended as hands-on coding exercises with growing complexity for working with basic spiking neural networks (SNNs) on _Brian2_ and starting to deal with event-based output of a neuromorphic vision sensor (to this purpose, give a look mainly at task 3 for applying Reichardt detectors on actual recordings from an event-based camera). Solutions are provided for all such tasks.
 - "tutorial1-spikingML_SurrogateGradient.ipynb" and "tutorial2-spikingML_FashionMNIST.ipynb" are guided tutorials aiming to give an insight on applying deep learning techniques in supervised tasks for training SNNs using a surrogate gradient.
 - the folders "utils" and "data" contain functions and event-based recordings, respectively. All of them are used in task 3.
