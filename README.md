# ATLUS

This is a project done as a part of the course CS769 : Optimization in Machine Learning. We improvised upon the ICLR Paper that discuss an efficient way to train LLMs with lesser data (as compared to DPO), SPIN (Self Play Fine Tuning). Our contributions are the following : 


• Proposal of a hardness definition for curriculum learning to be used along with random
sampling for better self-play fine tuning(SPIN) of LLMs.


• Proposal of a facility coverage maximization-based coreset selection method for optimizing
SPIN fine-tuning of LLMs, built upon the foundation of CORDS IITB.


• Proposal of incorporating adversarial training with the aforementioned techniques to enhance
the robustness of large language models (LLMs) trained under constraints of limited
data and computational resources.


Thus, we improved SPIN performance by incorporating curriculum learning and subset selection and showcased model's robustness to FGSM based adverserial attacks.
