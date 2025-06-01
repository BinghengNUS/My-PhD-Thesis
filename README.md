# My-PhD-Thesis
My PhD thesis, entitled "***Learning Robot Control Via Bilevel Optimization***", is available at https://scholarbank.nus.edu.sg/entities/publication/55fafb31-8609-412d-9173-bbc59dffce69

|     The proposed learning methods for bilevel optimization problems with neural network policies     |
:----------------------------------------------------------------------------------------------------------------------------------:
![proposed_bilevel_optimization_2](https://github.com/user-attachments/assets/5ee64985-09e1-4141-abbc-48786356b389)


Dynamic optimization techniques like model predictive control (MPC) and moving horizon estimation (MHE) are crucial in robot control but heavily depend on finely tuned hyperparameters, traditionally set through substantial human effort and expert knowledge, thus limiting system autonomy. This thesis leverages recent trends in bilevel optimization to automate this process, employing a hierarchical framework
where machine learning techniques optimize hyperparameters based on the results of lower-level dynamic optimization. It explores new methods that integrate the dynamic optimization into neural networks via the bilevel optimization, significantly enhancing the training process.

This repository contains all the projects from my PhD thesis, which are open-sourced through the following repositories.
   * Chapter 3: https://github.com/RCL-NUS/NeuroMHE
   * Chpater 4: https://github.com/BinghengNUS/TR-NeuroMHE
   * Chapter 5: https://github.com/RCL-NUS/Auto-Multilift

Minor corrections (e.g., typos and citation fixes) are documented in a note located in the '**Discussion**' folder.

## Citation
If you find these projects helpful in your publications, I would appreciate citing my thesis
```
@phdthesis{Wang_2024,
  author       = {Bingheng Wang},
  title        = {Learning Robot Control Via Bilevel Optimization},
  school       = {National Univeristy of Singapore},
  year         = {2024},
  address      = {Singapore, Singapore},
  type         = {Ph.D. thesis},
  url          = {https://scholarbank.nus.edu.sg/entities/publication/55fafb31-8609-412d-9173-bbc59dffce69}, % optional
}
 ```
## Contact
I welcome any suggestions or feedback you may have — please feel free to reach out.
   * Name: Dr. Bingheng Wang
   * Email: wangbingheng@u.nus.edu
