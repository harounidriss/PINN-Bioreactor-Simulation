# PINN-Bioreactor-Simulation
#  Simulation d’un bioréacteur avec PINN

Ce projet implémente un **Physics-Informed Neural Network (PINN)** pour résoudre une équation de transport-réaction.

---

##  Objectif

Simuler l’évolution d’une concentration chimique dans un bioréacteur sans données expérimentales, en utilisant uniquement les lois physiques.

---

##  Résultats

###  Solution PINN
![PINN](outputs/reference_pinn.png)

### Convergence du modèle
![Loss](outputs/reference_loss.png)

### Comparaison PINN vs méthode classique
![Comparaison](outputs/reference_comparison.png)

---

## Étude paramétrique

### Diffusion élevée
![Diffusion](outputs/diffusion_high_pinn.png)

### Vitesse élevée
![Vitesse](outputs/velocity_high_pinn.png)

---

## Technologies

- Python
- PyTorch
- NumPy
- Matplotlib

---

## Exécution

```bash
python main.py
