# gromov-wasserstein-statistics
Statistics on the space of asymmetric networks via Gromov-Wasserstein distance.

Based on our paper 'Gromov-Wasserstein Averaging in a Riemannian Framework', in CVPR Workshop Proceedings for the DIFF-CVML Workshop [here](http://openaccess.thecvf.com/content_CVPRW_2020/papers/w50/Chowdhury_Gromov-Wasserstein_Averaging_in_a_Riemannian_Framework_CVPRW_2020_paper.pdf).

Requires the Python Optimal Transport Library: https://pot.readthedocs.io/en/stable/

We extend the Gromov-Wasserstein distance algorithm of POT to treat asymmetric networks. We also provide tools to compute Frechet means and perform other statistical tasks on the space of networks. Our methods are based on Riemannian geometry of Gromov-Wasserstein space, inspired by work of K.T. Sturm https://arxiv.org/abs/1208.0434. Our work was also inspired by work of Peyre, Cuturi and Solomon https://github.com/gpeyre/2016-ICML-gromov-wasserstein.

Basic examples for using the code are included in Jupyter notebooks.
