# Adversarial Attacks

An adversarial attack is an attempt to minimally perturb an input to a (trained) classifier -- leading to misclassification. This repository presents several adversarial attacks along with their implementation. In a nutshell, the attacks can be described as follows:

- **FGSM**: the attack perturbs an input in the direction that increases the loss by the greatest amount, causing misclassification if the distance is great enough.
- **DeepFool**: the attack perturbs an input outside of its decision boundary and into another class.
- **Carlini Wagner**: the attack uses regularization to minimize the size of change while maximizing change in prediction.
