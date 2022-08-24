![Overview of the proposed approach](Images/overview_icra.png "Overview of the proposed approach")

<details>
<summary>Abstract</summary>
To certify UAV operations in populated areas, risk mitigation strategies 
-- such as Emergency Landing (EL) -- must be in place to account for 
potential failures. EL aims at reducing ground risk by finding safe 
landing areas using on-board sensors. The first contribution of this 
paper is to present a new EL approach, in line with safety requirements 
introduced in recent research. In particular, the proposed EL pipeline 
includes mechanisms to monitor learning based components during execution. 
This way, another contribution is to study the behavior of Machine Learning 
Runtime Monitoring (MLRM) approaches within the context of a real-world 
critical system. A new evaluation methodology is introduced, and applied to 
assess the practical safety benefits of three MLRM mechanisms. 
The proposed approach is compared to a default mitigation strategy 
(open a parachute when a failure is detected), and demonstrates a much 
safer behavior.
</details>


### Supplementary material
* Details about computing an estimate of the ground size for a given pixel: [here](Supplementary/ICRA2022_supplementary_pixelSize.pdf).
* A notebook to compute the safety coefficient for safety radius: [here](https://github.com/jorisguerin/ANITI_UavEmergencyLanding/blob/main/Supplementary/Beta_coef.ipynb).
* Full results: [here](Supplementary/full_results.csv).

### Code
The code used to generate our results: [here](https://github.com/jorisguerin/ANITI_UavEmergencyLanding/tree/main).

### Contact
[Joris GUERIN](https://jorisguerin.github.io/)  
Laboratoire d'Analyse et d'Architecture des Systèmes (LAAS-CNRS)  
7 avenue du Colonel Roche, 31031 TOULOUSE, FRANCE  
jorisguerin.research@gmail.com

### Citing this work
If you find this research useful, please consider citing 
        
    @inproceedings{guerin2022icra,
    title={Evaluation of Runtime Monitoring for UAV Emergency Landing},
    author={Guerin, Joris and Delmas, Kevin and Guiochet, Jérémie},
    booktitle={2022 IEEE International Conference on Robotics and Automation (ICRA)},
    pages={to appear},
    year={2022},
    organization={IEEE}
    }