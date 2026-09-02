
# Système 
- Fermé : pas d'échange de **matière**
- Isolé : **pas d'échange**

# Transformations
- Quasi statique : suite continue d'**état d'équilibre interne** 
- Reversible : quasi statique + renversable. $P=P_{ext}, \space T=T_{ext}$ 
- Iso... : **système** constant
- ==Mono... : **milieu exterieur** constant, $P_A = P_B =  P=_{ext}$==
- Adiabatique : Aucun **transfert** de chaleur

# Travail #W
$$\delta W = -P_{ext} dV $$
Si la transformation est méchaniqument **reversible** ($P=P_{ext}$) : 
$$ W = -\int_{V_A}^{V_B}{P\space dV} $$ 

# Cycles

Sur un diagramme de Clayperon, si cycle moteur est dans le sens : 
- Trigo : $W_{cycle} \gt 0$, donc le travail est reçu
- Anti-trigo : $W_{cycle} \lt 0$, donc le travail est fourni

$$ \left| W\right|=Aire\space sous\space la \space courbe$$

# Transfert thermique #Q

C'est l'énergie échangé sans le travail macroscopique

Q est en Joules (J)

# Premier principe #U

$$ \Delta U = W + Q $$
U : énergie interne 

$$ dU = \delta W + \delta Q $$

Sur un cycle, $\Delta U = 0$
Sur un système isolé, U est constante

# Enthalpie #H

$$H = U + PV$$

Pour un système monobare, $\Delta H= Q_P$

# Capacité thermiques #C

Capacité thermique Isochore : 
$$ C_V = \left( \frac{\partial U}{\partial T} \right)_V $$
Capacité thermique Isobare :
$$ C_P = \left( \frac{\partial H}{\partial T} \right)_P $$

Capacité molaire & capacité massique :
$$ C_{V,m} = \frac{C_V}{n}\space \& \space c_{V} = \frac{C_V}{m}$$

Unité : $J\cdot K^{-1}$

==Eau liquide : c = 4185== $J\cdot kg^{-1} \cdot K^{-1}$

$$ \Delta H \approx \Delta U \approx m c \Delta T  $$

# Calorimétrie

==C'est une enceinte **Adiabatique**, avec une évolution **Monobare** : ==
$$Q=\Delta H_{tot} =0$$

Valeur en eau µ du calorimètre : $C_{cal} = \micro \cdot c_{eau}$
Tout se passe comme si la masse d'eau était $m_e + \micro$

$$ H_{tot} = \sum_i{m_i\space c_i (T_f - T_i)} = 0 $$

---

# Lois de Joule

Pour un Gaz Parfait :
$$ U = U(T) \Rightarrow dU = C_VdT $$
(experience de Joule-Gay-Lussac)

$$ H = H(T) \Rightarrow dH = C_PdT $$
(expérience de Joule-Thomson)

# Relation de Mayer

Dans un Gaz Parfait
$$ H = U + PV = U(T) +nRT $$
Où : 
$$ C_P - C_V = nR $$
$$ \gamma = \frac{C_P}{C_V} \gt 1 \space ;C_V = \frac{nR}{\gamma - 1} $$
# Loi de Laplace

Condition 1 :
Gaz parfait -> $\gamma = cst$

Condition 2 : 
Adiabatique -> $\delta Q = 0$

Condition 3 : 
Réversible -> $P_{ext} = P$ à chaque instant

$$ W = \Delta U = C_V \Delta T = \frac{P_BV_B-P_AV_A}{\gamma -1}$$

Ainsi : 
$$ PV^\gamma = cte $$
diagramme de Clapeyron
$$TV^{\gamma -1} = cte$$
taux de compression (moteurs)
$$T^\gamma P^{1-\gamma} = cte$$
détentes, compresseurs

# Détente de Joule-Gay-Lussac

$$W = 0, Q = 0 \Rightarrow \Delta U = 0$$
- La détente est isoénergétique 
- Par l'expérience : $T_{finale} = T_{initiale}$ pour un gaz dilué
- U et T constante, V variable ->  U ne dépend pas de V : 1ère loi de Joule
- Gaz réel : léger refroidissement 
- La transformation est spontanée, brutale : IRRÉVERSIBLE 

# Détente de Joule-Thomson

On a un écoulement lent, permanetn, calorifugé -> la transformation est isenthalpique

- Chute de pression a travers l'obstacle : $P_2 \lt P_1$

Démonstration de $\Delta H = 0$

- Système fermé : une tranche de gaz qui traverse le bouchon
- Le gaz amont la pousse ($W_{amont}=+p_1V_1$) ; elle repousse l'aval ($W_{aval}=-P_2V_2$)
- Conduite calorifugée : Q = 0

$$ \Delta U = \Delta PV \Leftrightarrow H_2 = H_1$$

Interpretations : 
- Gaz parfait : H = H(T) et $\Delta H = 0$ -> $T_2 = T_1$ : vérifie la 2ème loi de Joule
- Gaz réel : la température varie ! Sous la température d'inversion : refroidissement
- Comme Joule-Gay-Lussac : transformation irréversible













