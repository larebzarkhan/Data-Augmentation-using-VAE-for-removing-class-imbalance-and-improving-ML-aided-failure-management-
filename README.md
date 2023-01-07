# Data-Augmentation-using-VAE-for-removing-class-imbalance-and-improving-ML-aided-failure-management-

Augmentation of tabular data was performed using Variational Autoencoder (VAE) and then the "good" synthetic samples were selected using Synthetic Samples Selector. The synthetic samples were combined with original experimental training data to address the issue of class imbalance and then performance was evaluated in terms of accuracy and training time of neural networks.

We considered dataset related to failure management in optical networks but you can use this approach to balance any tabular dataset. Feel free to use this code and we'll appreciate if you'll cite our work.

L. Z. Khan, J. Pedro, N. Costa, L. De Marinis, A. Napoli and N. Sambo, "Data augmentation to improve performance of neural networks for failure management in optical networks," in Journal of Optical Communications and Networking, vol. 15, no. 1, pp. 57-67, January 2023, doi: 10.1364/JOCN.472605.

To reproduce these results, run files in the following sequence:


1) Data to be augmented generator
2) Data Augmentation using VAE
3) ONFM (Failure Classification Comparison)
4) ONFM (Failure Detection Comparison)


In case of any queries, comments or feedback, please feel free to write me at larebzarkhan@gmail.com .

Cheers.
