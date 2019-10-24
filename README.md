# Regularization parameters

This repository contains all the lastest regularization parameters. These parameters can be used to compute the regular field at the location of the particle. If you use these parameters, please cite the suitable references as laid out below as well as the phbtoolkit. The most generic cases are listed first, with more specific cases following.

The notation used below follows that introduced by Heffernan et al. in Phys. Rev. D 82, 104023 (2012). This translates to the orignal notation as: <br/>
                                                A<sub>a</sub>: F<sub>a[-1]</sub>,    
                                                B<sub>a</sub>: F<sub>a[0]</sub>,    
                                                D<sub>a</sub>: F<sub>a[2]</sub>,    
                                                F<sub>a</sub>: F<sub>a[4]</sub>,    
                                                H<sub>a</sub>: F<sub>a[6]</sub>



### Schwarzschild parameters

| Expression | Fields			  | Description			  | Parameters		|Authors										| Reference(s)															|
|-------------------|-------------------|-------------------|---------------------|---------------------------------------------|-----------------------------------------------------------------------------------------------|
| Self-force| Scalar			  | Eccentric| F<sub>a[-1]</sub>, F<sub>a[0]</sub> | L. Barack, A. Ori						| Phys. Rev. D66 084022 (2002), [arXiv:gr-qc/0204093](https://arxiv.org/abs/gr-qc/0204093)		|
|  |			  | | F<sub>a[2]</sub> | R. Hass, E. Poisson						| Phys. Rev. D74 044009 (2006), [arXiv:gr-qc/0605077](https://arxiv.org/abs/gr-qc/0605077)		|
| | 			  | | F<sub>a[4]</sub>, F<sub>a[6]</sub>  | A. Heffernan, A. Ottewill, B. Wardell						| Phys. Rev. D82 104023 (2012), [arXiv:1204.0794](https://arxiv.org/abs/1204.0794)		|
| | 			  | Circular| F<sub>a[2]</sub>  | S. Detweiler, E. Messaritaki, B.F. Whiting						| Phys. Rev. D67 104016 (2003), [arXiv:gr-qc/0205079](https://arxiv.org/abs/gr-qc/0205079)		|
| | Electromagnetism		  	| Eccentric| F<sub>a[-1]</sub>, F<sub>a[0]</sub> | L. Barack, A. Ori						| Phys. Rev. D67 024029 (2003), [arXiv:gr-qc/0209072](https://arxiv.org/abs/gr-qc/0209072)     |
| | 		  	| |F<sub>a[2]</sub> | R. Haas					| [arXiv:1112.3707](https://arxiv.org/abs/1112.3707)     |
| | 		  	| |F<sub>a[4]</sub> | A. Heffernan, A. Ottewill, B. Wardell						| Phys. Rev. D82 104023 (2012), [arXiv:1204.0794](https://arxiv.org/abs/1204.0794)		|
| | Gravity		  	| Eccentric| F<sub>a[-1]</sub>, F<sub>a[0]</sub> | L. Barack, A. Ori						| Phys. Rev. D67 024029 (2003), [arXiv:gr-qc/0209072](https://arxiv.org/abs/gr-qc/0209072)     |
| | 		  	| |F<sub>a[2]</sub>, F<sub>a[4]</sub> | A. Heffernan, A. Ottewill, B. Wardell						| Phys. Rev. D82 104023 (2012), [arXiv:1204.0794](https://arxiv.org/abs/1204.0794)		|


### Kerr regularization parameters

| Parameters		| Fields			  |Authors										| Reference(s)																					   |
|-------------------|---------------------|---------------------------------------------|--------------------------------------------------------------------------------------------------|
| A, B, Self-force	| Scalar, EM, Gravity | L. Barack and A. Ori						| Phys. Rev. Lett. 90:111101 (2003), [arXiv:gr-qc/0212103](https://arxiv.org/abs/gr-qc/0212103)    |
