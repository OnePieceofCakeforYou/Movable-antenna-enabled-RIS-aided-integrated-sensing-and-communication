# Movable-antenna-enabled-RIS-aided-integrated-sensing-and-communication
This document contains the simulation codes for my paper titled 'Movable antenna-enabled RIS-aided integrated sensing and communication' published in IEEE Transactions on Cognitive Communications and Networking.

We will initially release the open-source code corresponding to the arXiv version. However, as the remaining code is associated with follow-up work that has not yet been published, it will be progressively made public after the formal publication of the follow-up work. Additionally, We would like to express our heartfelt gratitude to Dr. Jun for his invaluable assistance with my work. The MATLAB code for MA geometric channel model he developed has been critically integrated into my code implementation. We wish to reiterate our sincere appreciation for his contributions.

Friends using this codebase are kindly requested to cite our paper using the following reference format. We sincerely appreciate your acknowledgment of our work and contributions to the research community:

```latex
@article{wu2025movable,
  title={Movable antenna-enabled RIS-aided integrated sensing and communication},
  author={Wu, Haisu and Ren, Hong and Pan, Cunhua and Zhang, Yang},
  journal={IEEE Transactions on Cognitive Communications and Networking},
  year={2025},
  publisher={IEEE}
}
```

Any feedback and suggestions to improve this repo is welcome. If you find this implementation helpful for your research or projects, please kindly consider giving it a star ⭐️. Thank you! Besides, if you have any problem, don't hesitate to start a issue in our Github repository.

> Run the `main.m` function to execute the main program. Please note that the convex optimization part uses the MOSEK and CVX optimization toolboxes, so make sure to install them in advance. Since the number of simulations is relatively large, you may use MATLAB's Parallel Computing Toolbox if needed.
