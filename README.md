# Plots and tables for the RW functionalities paper

Structure:

* ```results/```: results of weight analysis. The `medians.pdf` and `selected_medians.pdf` files show summary statistics over a selection of models. The subdirectories correspond to models, including fine-tuned and non-GLU models that we did not include in the paper.
* `plots/` contains all the plots except the weight-based ones:
  * ```plots/ablations/``` for the neuron ablations
    * all the ```attributes.pdf``` files: attributes rate experiment
    * files named ```entropy.pdf``` etc.: entropy experiment
  * `plots/freq` etc: activation frequencies, frequencies of activation quadrants (sign combinations), mean activations (over activation quadrants).

Git-ignored directories (available upon request):

* `eap/`: attribution patching experiments, not included in the paper.
* ```intervention_results/```: machine-readable results of the main ablation experiments.
* `generations/`: model generations when ablating a given class of neurons (not described in the paper).
* ```knowns/```: prompts for the attributes rate experiment.
* ```se/logitlens.pickle```: machine-readable results (`pandas.read_pickle()`) of the attributes rate experiment.

You can also ask us for the Wikipedia data used for subject-attribute mappings.
