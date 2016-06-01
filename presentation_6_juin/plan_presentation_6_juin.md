**Sujet du stage**

**1.Introduction**  
+ Problème entre outils bioinfos et biologistes
+ def rapide wrapper
+ wrapper ont besoins de tests (unitaire fonctionnels)

**2.création ou reprise du test**  
+ Prise en compte de tous les paramètres
+ Paramètres particuliers (ex: output de split_table)
+ Vérification des fichiers d'entrée
+ Génération de fichiers de sortie -> utilisitation des outils

**3.test du wrapper**  
+ planemo  
+ + commandes de contrôle: lint, shed_lint
+ + planemo test  
- test sur galaxy  
- - vérifs fonctionement interface
- - origine erreures pas clair avec planemo
        
**4.Edition d'un wrapper**
+ erreures corrigées
+ utilisation git
+ + branches
+ + commit

**5."publication" wrapper**  
+ utilisation github
+ + PR
+ + travis

**6.Quelques wrappers**  
- tests passed
- - ...
+ tests failed
+ + humann2_download
+ + humann2_rna_dna_norm
+ + group_humann2_uniref_abundances_to_go
