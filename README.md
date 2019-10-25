# Regularization parameters

This repository contains all the lastest regularization parameters. These parameters can be used to compute the regular field at the location of the particle. If you use these parameters, please cite the suitable references as laid out below as well as the BHPToolkit as outlined on the [homepage](http://bhptoolkit.org/). The most generic cases are listed first, with more specific cases following.

The notation used below follows that introduced by Heffernan et al. in Phys. Rev. D 82, 104023 (2012). This translates to the orignal notation as: <br/>
                                                A<sub>a</sub>: F<sub>a[-1]</sub>,    
                                                B<sub>a</sub>: F<sub>a[0]</sub>,    
                                                D<sub>a</sub>: F<sub>a[2]</sub>,    
                                                F<sub>a</sub>: F<sub>a[4]</sub>,    
                                                H<sub>a</sub>: F<sub>a[6]</sub>.

We have made an effort to make this list and the digitally available parameters as extensive as possible, however if we have misrepresented any work or omitted any suitable research, please contact us via niels [dot] warburton [at] ucd [dot] ie.

## Schwarzschild Spacetime

### Geodesic self-force parameters

| Field			  | Description			  | Parameters		|Authors										| Reference(s)															|
|-------------------|-------------------|---------------------|---------------------------------------------|-----------------------------------------------------------------------------------------------|
| Scalar			  | Eccentric| F<sub>a[-1]</sub>, F<sub>a[0]</sub> | L. Barack, A. Ori						| Phys. Rev. D66 084022 (2002), [arXiv:gr-qc/0204093](https://arxiv.org/abs/gr-qc/0204093)		|
|			  | | F<sub>a[2]</sub> | R. Hass, E. Poisson						| Phys. Rev. D74 044009 (2006), [arXiv:gr-qc/0605077](https://arxiv.org/abs/gr-qc/0605077)		|
| 			  | | F<sub>a[4]</sub>, F<sub>a[6]</sub>  | A. Heffernan, A. Ottewill, B. Wardell						| Phys. Rev. D82 104023 (2012), [arXiv:1204.0794](https://arxiv.org/abs/1204.0794)		|
| 			  | Circular| F<sub>a[2]</sub>  | S. Detweiler, E. Messaritaki, B.F. Whiting						| Phys. Rev. D67 104016 (2003), [arXiv:gr-qc/0205079](https://arxiv.org/abs/gr-qc/0205079)		|
| Electromagnetism		  	| Eccentric| F<sub>a[-1]</sub>, F<sub>a[0]</sub> | L. Barack, A. Ori						| Phys. Rev. D67 024029 (2003), [arXiv:gr-qc/0209072](https://arxiv.org/abs/gr-qc/0209072)     |
| 		  	| |F<sub>a[2]</sub> | R. Haas					| [arXiv:1112.3707](https://arxiv.org/abs/1112.3707)     |
| 		  	| |F<sub>a[4]</sub> | A. Heffernan, A. Ottewill, B. Wardell						| Phys. Rev. D82 104023 (2012), [arXiv:1204.0794](https://arxiv.org/abs/1204.0794)		|
| Gravity		  	| Eccentric| F<sub>a[-1]</sub>, F<sub>a[0]</sub> | L. Barack, A. Ori						| Phys. Rev. D67 024029 (2003), [arXiv:gr-qc/0209072](https://arxiv.org/abs/gr-qc/0209072)     |
| 		  	| |F<sub>a[2]</sub>, F<sub>a[4]</sub> | A. Heffernan, A. Ottewill, B. Wardell						| Phys. Rev. D82 104023 (2012), [arXiv:1204.0794](https://arxiv.org/abs/1204.0794)		|

### Useful scalar quantities for geodesic motion

| Expression | Field			  | Description			  | Parameters		|Authors										| Reference(s)															|
|------------|--------------|-------------------|---------------|---------------------------|--------------------------------------------|
| Singular Field | Scalar | Eccentric | &Phi;<sub>[0]</sub>, &Phi;<sub>[2]</sub>, &Phi;<sub>[4]</sub>, &Phi;<sub>[6]</sub>  | A. Heffernan, A. Ottewill, B. Wardell						| Phys. Rev. D82 104023 (2012), [arXiv:1204.0794](https://arxiv.org/abs/1204.0794)		|
|||Circular | &Phi;<sub>[0]</sub>, &Phi;<sub>[2]</sub>  | L.M. Diaz-Rivera, E. Messaritaki, B.F. Whiting, S. Detweiler						| Phys. Rev. D70 124018 (2004), [arXiv:gr-qc/0410011](https://arxiv.org/abs/gr-qc/0410011)		|
|Detweiler redshift| Gravity | Eccentric | H<sub>[0]</sub>, H<sub>[2]</sub>, H<sub>[4]</sub>  | A. Heffernan, A. Ottewill, B. Wardell						| Phys. Rev. D82 104023 (2012), [arXiv:1204.0794](https://arxiv.org/abs/1204.0794)		|


### Non-geodesic parameters

| Expression | Field			  | Description			  | Parameters		|Authors										| Reference(s)															|
|------------|--------------|-------------------|---------------|---------------------------|--------------------------------------------|
| Self-force| Scalar | Eccentric | F<sub>a[-1]</sub>, F<sub>a[0]</sub>, F<sub>a[2]</sub> | A. Heffernan <br/> A.Heffernan, A.C. Ottewill, N. Warburton, B. Wardell, P. Diener						| [arXiv:1403.6177](https://arxiv.org/abs/1403.6177) (2014) <br/>Class. Quant. Grav. 35 (2018) 19, 194001, [arXiv:1712.01098](https://arxiv.org/abs/1712.01098)		|
| |  | Static | F<sub>a[-1]</sub>, F<sub>a[0]</sub>, F<sub>a[2]</sub> | M. Casals, E. Poisson, I. Vega| Phys. Rev. D86 064033 (2012), [arXiv:1206.3772](https://arxiv.org/abs/1206.3772)		|
| Singular Field | Scalar | Eccentric | &Phi;<sub>[0]</sub>, &Phi;<sub>[2]</sub> | A.Heffernan, A.C. Ottewill, N. Warburton, B. Wardell, P. Diener						| Class. Quant. Grav. 35 (2018) 19, 194001, [arXiv:1712.01098](https://arxiv.org/abs/1712.01098)		|

## Kerr Spacetime

### Geodesic self-force parameters

| Field			  | Description			  | Parameters		|Authors										| Reference(s)															|
|-------------------|-------------------|---------------------|---------------------------------------------|-----------------------------------------------------------------------------------------------|
| Scalar| Eccentric, inclined| F<sub>a[-1]</sub>, F<sub>a[0]</sub>	 | L. Barack, A. Ori						| Phys. Rev. Lett. 90:111101 (2003), [arXiv:gr-qc/0212103](https://arxiv.org/abs/gr-qc/0212103)    |
| | Eccentric, equatorial| F<sub>a[2]</sub>, F<sub>a[4]</sub>	 |  A. Heffernan, A. Ottewill, B. Wardell							| Phys. Rev. D89 024030 (2014), [arXiv:1211.6446](https://arxiv.org/abs/1211.6446)    |
| Electromagnetism & gravity| Eccentric, inclined| F<sub>a[-1]</sub>, F<sub>a[0]</sub>	 | L. Barack, A. Ori						| Phys. Rev. Lett. 90:111101 (2003), [arXiv:gr-qc/0212103](https://arxiv.org/abs/gr-qc/0212103)    |
| | Eccentric, equatorial| F<sub>a[2]</sub> |  A. Heffernan, A. Ottewill, B. Wardell							| Phys. Rev. D89 024030 (2014), [arXiv:1211.6446](https://arxiv.org/abs/1211.6446)    |

### Useful scalar quantities for geodesic motion

| Expression | Field			  | Description			  | Parameters		|Authors										| Reference(s)															|
|------------|--------------|-------------------|---------------|---------------------------|--------------------------------------------|
| Singular Field | Scalar | Eccentric, equatorial | &Phi;<sub>[0]</sub>, &Phi;<sub>[2]</sub>, &Phi;<sub>[4]</sub>  | A. Heffernan, A. Ottewill, B. Wardell						| Phys. Rev. D89 024030 (2014), [arXiv:1211.6446](https://arxiv.org/abs/1211.6446)    |
|Detweiler redshift| Gravity | Eccentric, equatorial | H<sub>[0]</sub>, H<sub>[2]</sub>  | A. Heffernan, A. Ottewill, B. Wardell						| Phys. Rev. D89 024030 (2014), [arXiv:1211.6446](https://arxiv.org/abs/1211.6446)    |
