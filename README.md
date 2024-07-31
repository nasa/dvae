# Anomaly Detection in Aeronautics Data with Quantum-compatible Discrete Deep Generative Model


Code for [Anomaly Detection in Aeronautics Data with Quantum-compatible Discrete Deep Generative Model] (https://iopscience.iop.org/article/10.1088/2632-2153/ace756; https://arxiv.org/abs/2303.12302).

Please note that the posted data files are shorter and contain fewer instances than the ones used to produce the research results, in order to comply with GitHub's file-size requirements. The full data files are available from the authors/software developers.


## License:
```
NASA_Open_Source_Agreement_ARC-18940-1_DVAE (https://github.com/nasa/dvae/blob/main/NASA_Open_Source_Agreement_ARC-18940-1_DVAE.pdf)
```


## Requirements:
```
python=3.9.13
pytorch=1.13.1
numpy=1.21.5
scipy=1.9.1
scikit-learn=1.0.2
matplotlib=3.5.2
seaborn=0.11.2
kmodes=0.12.2
inflect=6.0.4
```


## Training:
```
discrete_stochastic_training.py (-md validation -m boltzmann -e 400 ...)
```


## Evaluation:
```
discrete_stochastic_evaluation.py (-md validation -m boltzmann -e 400 ...)
```


## Example:
```
The Jupyter notebook file dvae_example.ipynb contains guidance on how to train and evaluate our DVAE model for the purpose of anomaly detection in time-series data.
```


## Citation:
```
@article{Templin_2023,
  title={Anomaly detection in aeronautics data with quantum-compatible discrete deep generative model},
  author={Templin, Thomas and Memarzadeh, Milad and Vinci, Walter and Lott, P. Aaron and Akbari Asanjan, Ata and Alexiades Armenakas, Anthony and Rieffel, Eleanor},
  journal={Machine Learning: Science and Technology},
  volume={4},
  number={3},
  pages={035018},
  year={2023},
  publisher={IOP Publishing}
}
@article{templin2023anomaly,
  title={Anomaly detection in aeronautics data with quantum-compatible discrete deep generative model},
  author={Templin, Thomas and Memarzadeh, Milad and Vinci, Walter and Lott, P. Aaron and Akbari Asanjan, Ata and Alexiades Armenakas, Anthony and Rieffel, Eleanor},
  journal={arXiv preprint arXiv:2303.12302},
  year={2023}
}
```


## Notices:
```
Copyright © 2024 United States Government as represented by the Administrator of the National Aeronautics and Space Administration.  All Rights Reserved.
```


## Disclaimers
```
No warranty: THE SUBJECT SOFTWARE IS PROVIDED "AS IS" WITHOUT ANY WARRANTY OF ANY KIND, EITHER EXPRESSED, IMPLIED, OR STATUTORY, INCLUDING, BUT NOT LIMITED TO, ANY WARRANTY THAT THE SUBJECT SOFTWARE WILL CONFORM TO SPECIFICATIONS, ANY IMPLIED WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE, OR FREEDOM FROM INFRINGEMENT, ANY WARRANTY THAT THE SUBJECT SOFTWARE WILL BE ERROR FREE, OR ANY WARRANTY THAT DOCUMENTATION, IF PROVIDED, WILL CONFORM TO THE SUBJECT SOFTWARE. THIS AGREEMENT DOES NOT, IN ANY MANNER, CONSTITUTE AN ENDORSEMENT BY GOVERNMENT AGENCY OR ANY PRIOR RECIPIENT OF ANY RESULTS, RESULTING DESIGNS, HARDWARE, SOFTWARE PRODUCTS OR ANY OTHER APPLICATIONS RESULTING FROM USE OF THE SUBJECT SOFTWARE.  FURTHER, GOVERNMENT AGENCY DISCLAIMS ALL WARRANTIES AND LIABILITIES REGARDING THIRD-PARTY SOFTWARE, IF PRESENT IN THE ORIGINAL SOFTWARE, AND DISTRIBUTES IT "AS IS."

Waiver and Indemnity:  RECIPIENT AGREES TO WAIVE ANY AND ALL CLAIMS AGAINST THE UNITED STATES GOVERNMENT, ITS CONTRACTORS AND SUBCONTRACTORS, AS WELL AS ANY PRIOR RECIPIENT.  IF RECIPIENT'S USE OF THE SUBJECT SOFTWARE RESULTS IN ANY LIABILITIES, DEMANDS, DAMAGES, EXPENSES OR LOSSES ARISING FROM SUCH USE, INCLUDING ANY DAMAGES FROM PRODUCTS BASED ON, OR RESULTING FROM, RECIPIENT'S USE OF THE SUBJECT SOFTWARE, RECIPIENT SHALL INDEMNIFY AND HOLD HARMLESS THE UNITED STATES GOVERNMENT, ITS CONTRACTORS AND SUBCONTRACTORS, AS WELL AS ANY PRIOR RECIPIENT, TO THE EXTENT PERMITTED BY LAW.  RECIPIENT'S SOLE REMEDY FOR ANY SUCH MATTER SHALL BE THE IMMEDIATE, UNILATERAL TERMINATION OF THIS AGREEMENT. 
```
