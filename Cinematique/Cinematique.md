Cinématique
===========

Introduction
------------

La *cinématique* est l'étude du mouvement des corps. Nous ne
considérerons que des corps de faibles dimensions de sorte qu'ils seront
toujours assimilés à des points appelés *mobiles*. Les grandeurs
physiques de la cinématique sont le temps, la position, la vitesse et
l'accélération.

Étudier le mouvement d'un mobile veut dire:

-   trouver la relation mathématique entre position et temps;

-   trouver la relation mathématique entre vitesse et temps;

-   trouver la relation mathématique entre vitesse et position;

-   trouver l'équation de la trajectoire du mobile.

Référentiel et repère
---------------------

### Référentiel

La description d'un mouvement se fait par rapport à un objet, choisi
comme référence, appelé *référentiel*. La description du mouvement n'est
pas la même dans tous les référentiels!

*Exemple*:

\retraitparagraphe{0.6cm}
Deux voyageurs $A$ et $B$ sont assis dans un wagon en mouvement. Le
voyageur $A$ observe $B$ et conclut: $B$ est immobile. Le chef de gare
$C$ observe $B$ et conclut: $B$ est en mouvement. Ces deux observations
sont-elles contradictoires? Non, car elles sont faites dans deux
référentiels différents: $A$ fait ses observations dans le référentiel
du wagon, $C$ fait ses observations dans le référentiel lié à la Terre.

Le référentiel est un objet de référence par rapport auquel on étudie un
mouvement. Il peut être matérialisé par un seul corps ou par un ensemble
de corps qui restent à distance constante les uns des autres.

*Exemples de référentiels*:

-   le laboratoire, la salle de classe, un wagon, un carrousel, ...

-   le référentiel *terrestre*: son centre est le centre de la Terre,
    ses axes sont liés à des points fixes sur la Terre. On l'utilise
    pour décrire tous les mouvements sur la Terre. Les référentiels
    laboratoire et salle de classe sont équivalents au référentiel
    terrestre.

-   le référentiel *géocentrique*: son centre est le centre de la Terre,
    ses axes sont dirigés vers des étoiles lointaines considérées comme
    fixes. On l'utilise p.ex. pour décrire le mouvement des satellites;

-   le référentiel *héliocentrique*: son centre est le soleil, ses axes
    sont dirigés vers des étoiles lointaines considérées comme fixes. On
    l'utilise p.ex. pour décrire le mouvement des planètes;

### Repère

Pour décrire le mouvement d'un mobile, un observateur dans un
référentiel doit se munir:

-   d'un *repère* pour déterminer la position du mobile;

-   d'une horloge.

Un repère est déterminé par une origine $O$ et par une base, le plus
souvent orthonormée.

*Exemple*: repère $(O,\;\vec{\imath},\;\vec{\jmath},\;\vec{k})$
orthonormé à 3 dimensions
(figure [\[fig:repere\]](#fig:repere){reference-type="ref"
reference="fig:repere"}).

![Repère orthonormé à 3
dimensions[]{label="fig:repere"}](./Figures/Repere){#fig:repere}

Les axes $Oy$ et $Oz$ sont perpendiculaires entre eux et sont dans le
plan de la feuille de papier. L'axe $Ox$ sort de ce plan et est
perpendiculaire à ce plan.

Dans le domaine des sciences comme dans la vie courante, une horloge
permet de déterminer:

-   la *durée* ou l'intervalle de temps qui s'écoule entre deux
    événements;

-   la *date* ou l'instant auquel un événement a lieu.

L'unité S.I. (Système International d'Unités) du temps est la *seconde*
().

### Trajectoire

La trajectoire est l'ensemble des positions successives occupées par le
mobile $M$ lors de son mouvement. Elle est représentée par une courbe
dans l'espace (figure
[\[fig:trajectoire\]](#fig:trajectoire){reference-type="ref"
reference="fig:trajectoire"}). Comme toute courbe, la trajectoire est
déterminée, dans un repère donné, par son équation mathématique. La
trajectoire dépend du choix du référentiel et du repère.

![Trajectoire dans un repère à 3
dimensions[]{label="fig:trajectoire"}](./Figures/Trajectoire){#fig:trajectoire}

*Exemples*:

-   Trajectoire d'un point de la roue d'une bicyclette, dans les
    référentiels suivants: observateur au repos au bord de la route,
    cycliste, roue?

-   Trajectoire d'un enfant sur un manège: immobile ou en rotation?

Position
--------

### Coordonnées cartésiennes

Soit $M$ le mobile et $(O,\;\vec{\imath},\;\vec{\jmath},\;\vec{k})$ le
repère choisi. La position du mobile est repérée à chaque instant par
les *coordonnées* $x$, $y$, $z$ du *vecteur position*
$\overrightarrow{OM}$ (figure
[\[fig:position\]](#fig:position){reference-type="ref"
reference="fig:position"}).

![Vecteur
position[]{label="fig:position"}](./Figures/Position){#fig:position}

Dans la base du repère:
$\overrightarrow{OM}=x\,\vec{\imath}+y\,\vec{\jmath}+z\,\vec{k}$.

Si le repère est orthonormé, $x$, $y$, $z$ sont appelés coordonnées
*cartésiennes* du point $M$. Dans la suite nous n'utiliserons que des
repères orthonormés.

S'il y a mouvement, les coordonnées $x$, $y$ et $z$ varient au cours du
temps. Les fonctions $x = f(t)$, $y = g(t)$ et $z = h(t)$ sont appelées
*équations horaires* ou *équations paramétriques* du mouvement.

Dans le repère $(O,\;\vec{\imath},\;\vec{\jmath},\;\vec{k})$ la position
d'un point $M$ est définie à chaque instant par:
$$x=2\,t\text{; }y=4\,t^2+1\text{; }z=0.$$ Donner les positions
respectives du point $M$ aux instants , 1 s, 2 s, 3 s et 4 s. En déduire
l'équation de la trajectoire suivie par $M$.

### Abscisse curviligne

Si la trajectoire d'un mobile $M$ est connue, on peut l'orienter et
choisir un point origine $A$. La valeur algébrique de l'arc
$\wideparen{AM}$ est l'*abscisse curviligne* $s$ du point $M$ (figure
[\[fig:abscurv\]](#fig:abscurv){reference-type="ref"
reference="fig:abscurv"}).

![Abscisse
curviligne[]{label="fig:abscurv"}](./Figures/Abscurv){#fig:abscurv}

*Signe* de l'abscisse curviligne:

-   $s>0$ si en allant de $A$ à $M$ on se déplace dans le sens de
    l'orientation.

-   $s<0$ si en allant de $A$ à $M$ on se déplace dans le sens inverse
    de l'orientation.

On oriente, dans la mesure du possible, la trajectoire dans le sens du
mouvement. L'abscisse curviligne est liée au temps par la relation
$s = f(t)$, appelée *équation horaire* du mouvement.

Vecteur vitesse d'un point
--------------------------

La rapidité avec laquelle un mobile change de position est indiquée par
sa *vitesse* (vecteur vitesse). On distingue vitesse *moyenne* et
vitesse *instantanée*.

### Vitesse moyenne

La vitesse moyenne $v_\mathrm{m}$ est la distance $d$ parcourue divisée
pas la durée $t$: $$v_\mathrm{m}=\frac{d}{t}.$$

Si un point mobile se trouve en $M_1$ à l'instant $t_1$ et en $M_2$ à
l'instant $t_2$, la vitesse moyenne au cours du déplacement de $M_1$
vers $M_2$ s'écrit:
$$\boxed{v_\mathrm{m}=\frac{s_2-s_1}{t_2-t_1}=\frac{\Delta s}{\Delta t}}$$

*Remarque*: on note usuellement par $\Delta x$ la différence de la
valeur finale de la grandeur $x$ et de sa valeur initiale:
$\Delta x=x_\mathrm{final}-x_\mathrm{initial}$.

Unité S.I. de la vitesse: 1 m/s.

Autre unité: 1 km/h.

Transformations:
$\SI{1}{\kilo\meter\per\hour}=\SI[parse-numbers=false]{\dfrac{1000}{3600}}{\meter\per\second}=\SI[parse-numbers=false]{\dfrac{1}{3,6}}{\meter\per\second}\Leftrightarrow \SI{1}{\meter\per\second}=\SI{3,6}{\kilo\meter\per\hour}.$

### Vitesse instantanée algébrique

La vitesse instantanée donne des renseignements plus précis que la
vitesse moyenne: elle définit la vitesse du mobile à chaque instant!

Si au cours d'un intervalle de temps $\Delta t$ la vitesse ne varie pas
d'un instant à l'autre, c'est-à-dire qu'elle est constante, il est
évident que pour cet intervalle de temps, la vitesse instantanée à
chaque instant est égale à la vitesse moyenne.

Si par contre la vitesse varie d'un instant à l'autre, la vitesse
instantanée s'obtient en réduisant la distance sur laquelle la vitesse
est mesurée de sorte qu'on puisse admettre que la vitesse ne varie plus
sur cette distance tellement petite. La durée mesurée devient plus
petite aussi et la vitesse instantanée en un point $M$ est:
$$v_M=\frac{\text{distance très petite}}{\text{durée très petite}}$$
$$v_M=\frac{\delta s}{\delta t}=\lim_{\Delta t\to 0}\frac{\Delta s}{\Delta t}.$$

Signe de la vitesse instantanée:

-   Si le mouvement s'effectue dans le sens positif, $\delta s > 0$ et
    $v_M > 0$.

-   Si le mouvement s'effectue dans le sens négatif, $\delta s < 0$ et
    $v_M < 0$.

### Vecteur vitesse

On définit un vecteur vitesse moyenne entre $M_1$ et $M_2$ par:
$$\vec{v}_\mathrm{m}=\frac{\overrightarrow{M_1M_2}}{\Delta t}.$$

Introduisons l'origine $O$ du repère (figure
[\[fig:vectvitmoy\]](#fig:vectvitmoy){reference-type="ref"
reference="fig:vectvitmoy"}) et utilisons la relation de Chasles:

![Vecteur
déplacement[]{label="fig:vectvitmoy"}](./Figures/Vectvitmoy){#fig:vectvitmoy}

$$\overrightarrow{M_1M_2}=\overrightarrow{M_1O}+\overrightarrow{OM_2}=\overrightarrow{OM_2}-\overrightarrow{OM_1}=\Delta \overrightarrow{OM}$$
alors:
$$\vec{v}_\mathrm{m}=\frac{\Delta \overrightarrow{OM}}{\Delta t}.$$

Quand $\Delta t\to 0$, les points $M_1$ et $M_2$ se rapprochent pour
donner un point $M$ et la direction de $\vec{v}_m$ devient la direction
de la tangente à la trajectoire en $M$. Le vecteur vitesse moyenne
devient le vecteur vitesse instantanée en $M$
(figure [\[fig:vectvitinst\]](#fig:vectvitinst){reference-type="ref"
reference="fig:vectvitinst"}):
$$\boxed{\vec{v}_M=\lim_{\Delta t\to 0}\frac{\Delta \overrightarrow{OM}}{\Delta t}=\frac{\delta \overrightarrow{OM}}{\delta t}}
\label{equ:defvitinst}$$

![Vecteur vitesse
instantanée[]{label="fig:vectvitinst"}](./Figures/Vectvitinst){#fig:vectvitinst}

Propriétés du vecteur vitesse instantanée:

-   direction: la tangente à la trajectoire en $M$;

-   sens: celui du mouvement;

-   intensité (norme):
    $v_M=\|\vec{v}_M\|=\left| \dfrac{\delta s}{\delta t}\right|$.

### Coordonnées du vecteur vitesse instantanée

Dans le repère $(O,\;\vec{\imath},\;\vec{\jmath},\;\vec{k})$ le vecteur
$\vec{v}$ s'exprime par:
$$\vec{v}=v_x\,\vec{\imath}+v_y\,\vec{\jmath}+v_z\,\vec{k}.$$

L'intensité $v$ est reliée aux coordonnées $v_x$, $v_y$, $v_z$ par la
relation de Pythagore: $$v=\sqrt{{v_x}^2+{v_y}^2+{v_z}^2}.$$

Dans le cas d'un mouvement plan (figure
[\[fig:vitplan\]](#fig:vitplan){reference-type="ref"
reference="fig:vitplan"}), les expressions se simplifient:
$\vec{v}=v_x\,\vec{\imath}+v_y\,\vec{\jmath}$ et
$v=\sqrt{{v_x}^2+{v_y}^2}$.

![Vecteur vitesse dans un
plan[]{label="fig:vitplan"}](./Figures/Vitplan){#fig:vitplan}

### Exercices

Lors d'une course cycliste contre la montre, un coureur parcourt dans
une première partie 22 km en 30 min. Puis la seconde partie de 48 km est
faite en 1 h30 min.

1.  Quelle est la vitesse moyenne du coureur sur la première partie?

2.  Quelle est la vitesse moyenne du coureur sur la deuxième partie?

3.  Quelle est la vitesse moyenne du coureur sur l'ensemble de
    l'épreuve?

Afin de contrôler le bon fonctionnement de l'indicateur de vitesse de
son automobile, un conducteur chronomètre une durée de 28 s pour
parcourir 1 km sur l'autoroute.

1.  Quelle est la vitesse moyenne correspondant à cette observation?

2.  L'automobiliste lit 130 km/h sur son indicateur de vitesse. La
    précision de cette indication est de 5 %.\
    Que peut-en conclure l'automobiliste?

Accélération
------------

Lorsque la vitesse $\vec{v}$ d'un mobile change au cours du temps, on
aimerait connaître la rapidité avec laquelle elle change. C'est
l'*accélération* $\vec{a}$ du mobile qui nous donne cette information.

L'accélération indique de combien la vitesse $\vec{v}$ varie en 1
seconde. La vitesse peut varier en intensité et en direction. Une forte
accélération $a$ (intensité de $\vec{a}$) signifie donc que la vitesse
varie vite, une faible accélération signifie qu'elle varie lentement.
L'accélération indique la *rapidité de variation de la vitesse*.

On distingue l'accélération *moyenne* $\vec{a}_\mathrm{m}$ au cours d'un
intervalle de temps $\Delta t$, et l'accélération *instantanée*
$\vec{a}$ à un instant donné.

### Accélération moyenne

Quand la vitesse d'un mobile varie entre $\vec{v}_1$ à la date $t_1$ et
$\vec{v}_2$ à la date $t_2$, le vecteur accélération moyenne est:
$$\boxed{\vec{a}_\mathrm{m}=\frac{\vec{v}_2-\vec{v}_1}{t_2-t_1}=\frac{\Delta\vec{v}}{\Delta t}}
\label{equ:defaccmoy}$$

Unité S.I. de l'accélération: 1 m/s².

L'accélération d'un mobile dont la vitesse varie de 1 m/s en 1 s est
1 m/s².

### Accélération instantanée

De la même façon que la vitesse instantanée, on définit le vecteur
accélération instantanée:
$$\boxed{\vec{a}=\lim_{\Delta t\to 0}\frac{\Delta\vec{v}}{\Delta t}=\frac{\delta\vec{v}}{\delta t}}
\label{equ:defaccinst}$$

En général, le vecteur accélération n'est pas tangent à la trajectoire.

Calcule l'accélération dans les cas suivants:

1.  Une voiture accélère sur une route rectiligne de 30 km/h à 90 km/h
    en 8 s.

2.  Un navire animé d'un mouvement rectiligne de vitesse 20 km/h met
    1 min pour arriver au repos.

Mouvements rectilignes
----------------------

Un mouvement est rectiligne si sa trajectoire est une droite. Dans ce
cas, nous pouvons choisir un repère à une dimension $(O,\;\vec{\imath})$
de même direction que la trajectoire.

La position du mobile devient: $\overrightarrow{OM}=x\,\vec{\imath}$.

![Mouvement
rectiligne[]{label="fig:vecmouvrect"}](./Figures/Vecmouvrect){#fig:vecmouvrect}

Le vecteur vitesse est tangent à la trajectoire :
$\vec{v}=v_x\,\vec{\imath}$. La variation du vecteur vitesse et, par
conséquent, l'accélération sont sur l'axe du repère (figure
[\[fig:vecmouvrect\]](#fig:vecmouvrect){reference-type="ref"
reference="fig:vecmouvrect"}): $\vec{a}=a_x\,\vec{\imath}$.

### Mouvement rectiligne uniforme

Un mouvement est rectiligne uniforme (MRU) si la trajectoire est une
droite et si la vitesse est une constante.

La relation ([\[equ:defaccmoy\]](#equ:defaccmoy){reference-type="ref"
reference="equ:defaccmoy"}) permet de calculer l'accélération moyenne:
$${a_\mathrm{m}}_x=\frac{{v_2}_x-{v_1}_x}{t_2-t_1}=\frac{0}{\Delta t}=0$$
car ${v_2}_x={v_1}_x=\text{constante}$.

Ce résultat est vrai aussi dans la limite $\Delta t\to 0$; il en suit
que $a_x=0$ à tout instant. La vitesse est constante:
$v_x={v_\mathrm{m}}_x={v_0}_x=\text{constante}$.

Nous allons déterminer l'équation horaire par la méthode de l'airefg. La
représentation $v_x=f(t)$ est une droite horizontale (figure
[\[fig:vituniftemps\]](#fig:vituniftemps){reference-type="ref"
reference="fig:vituniftemps"}).

![Mouvement rectiligne
uniforme[]{label="fig:vituniftemps"}](./Figures/Vituniftemps){#fig:vituniftemps}

L'expression ([\[equ:defvitinst\]](#equ:defvitinst){reference-type="ref"
reference="equ:defvitinst"}) de la vitesse instantanée donne:
$$v_x=\frac{\delta x}{\delta t}\Longrightarrow \delta x=v_x\,\delta t.$$

L'aire du petit rectangle (on dit rectangle *élémentaire*) de largeur
$\delta t$ et de longueur $v_x$ est $v_x\,\delta t$. Cette *aire
élémentaire* est égale à la distance $\delta x$ parcourue pendant le
temps $\delta t$ avec la vitesse $v_x$. La distance totale parcourue
entre $t=0$ et $t$ est donnée par l'aire totale du rectangle pour cet
intervalle de temps: $v_x\,t$.

Soit $x_0$ la position du mobile à la date $t=0$. Pour obtenir sa
position à la date $t$ il suffit d'ajouter la distance parcourue:
$$x=v_x\, t+x_0.$$ Cette relation est l'équation horaire du MRU.

Les équations horaires qui régissent le mouvement rectiligne uniforme
sont: $$\boxed{
\begin{array}{l}
x=v_x\, t+x_0\vspace{6pt}\\
v_x={v_0}_x=\mathrm{constante}\vspace{6pt}\\
a_x=0
\label{}
\end{array}}$$

Connaissant la position initiale et la vitesse du mobile, on peut
déterminer sa position à toute date. La figure
[\[fig:mrupositiontemps\]](#fig:mrupositiontemps){reference-type="ref"
reference="fig:mrupositiontemps"} montre les représentations $x=f(t)$ de
quelques cas particuliers.

\subfloat[$v_x>0$]
{\includegraphics{./Figures/Mruvitpos}}
\hfill
\subfloat[$v_x<0$]
{\includegraphics{./Figures/Mruvitneg}}
\hfill
\subfloat[$v_x>0$]
{\includegraphics{./Figures/Mruinitneg}}
### Mouvement rectiligne uniformément varié

Un mouvement est rectiligne uniformément varié (MRUV) si la trajectoire
est une droite et si le vecteur accélération est constant, porté par la
trajectoire.

L'accélération est constante:
$a_x={a_\mathrm{m}}_x={a_0}_x=\mathrm{constante}$

Nous allons déterminer la loi des vitesses par la méthode de l'airefg.
La représentation $a_x=f(t)$ est une droite horizontale (figure
[\[fig:accuniftemps\]](#fig:accuniftemps){reference-type="ref"
reference="fig:accuniftemps"}).

![Accélération
constante[]{label="fig:accuniftemps"}](./Figures/Accuniftemps){#fig:accuniftemps}

L'expression ([\[equ:defaccinst\]](#equ:defaccinst){reference-type="ref"
reference="equ:defaccinst"}) de l'accélération donne:
$$a_x=\frac{\delta v_x}{\delta t}\Longrightarrow \delta v_x=a_x\, \delta t.$$

L'aire du rectangle élémentaire de largeur $\delta t$ et de longueur
$a_x$ est $a_x\, \delta t$. Cette aire élémentaire est égale à
l'augmentation de la vitesse $\delta v_x$ pendant le temps $\delta t$
due à l'accélération. L'augmentation totale de la vitesse entre $t=0$ et
$t$ est donnée par l'aire totale du rectangle pour cet intervalle de
temps: $a_x\, t$.

Soit ${v_0}_x$ la vitesse du mobile à la date $t=0$. Pour obtenir la
vitesse du mobile à la date $t$ il suffit d'ajouter l'augmentation de la
vitesse: $$v_x=a_x\, t+{v_0}_x.
\label{equ:mruvvit}$$

Par la même méthode de l'airefg nous pouvons déterminer l'équation
horaire. La représentation $v_x=f(t)$ est une droite (figure
[\[fig:vitvartemps\]](#fig:vitvartemps){reference-type="ref"
reference="fig:vitvartemps"}).

\hspace{4.5cm}
![Mouvement rectiligne uniformément
varié[]{label="fig:vitvartemps"}](./Figures/Vitvartemps){#fig:vitvartemps}

L'expression ([\[equ:defvitinst\]](#equ:defvitinst){reference-type="ref"
reference="equ:defvitinst"}) de la vitesse instantanée donne:
$$v_x=\frac{\delta x}{\delta t}\Longrightarrow \delta x=v_x\, \delta t.$$

L'aire du petit rectangle élémentaire de largeur $\delta t$ et de
longueur $v_x$ est $v_x\, \delta t$. Cette aire élémentaire est égale à
la distance $\delta x$ parcourue pendant le temps $\delta t$ avec la
vitesse $v_x$. La distance totale parcourue entre $t=0$ et $t$ est
donnée par l'aire totale du trapèze pour cet intervalle de temps. Cette
aire se décompose $$\left|
\begin{array}{ll}
\text{en un rectangle d'aire:} & {v_0}_x\, t \vspace{6pt}\\
\text{et en un triangle d'aire:}  & \tfrac{1}{2}\,(v_x-{v_0}_x)\, t.     
\end{array}\right.$$ L'aire totale est:
${v_0}_x\, t+\frac{1}{2}\,(v_x-{v_0}_x)\,t$. En utilisant la relation
([\[equ:mruvvit\]](#equ:mruvvit){reference-type="ref"
reference="equ:mruvvit"}):
$$v_x=a_x\, t+{v_0}_x\Longrightarrow v_x-{v_0}_x=a_x\, t$$ nous obtenons
pour l'aire totale:
${v_0}_x\, t+\frac{1}{2}\,a_x\, t\, t={v_0}_x\, t+\frac{1}{2}\,a_x\, t^2$.

Soit $x_0$ la position du mobile à la date $t=0$. Pour obtenir sa
position à la date $t$ il suffit d'ajouter la distance parcourue:
$$x=\tfrac{1}{2}\,a_x\, t^2+{v_0}_x\, t+x_0.$$ Cette relation est
l'équation horaire du MRUV.

Les équations horaires qui régissent le mouvement rectiligne
uniformément varié sont: $$\boxed{
\begin{array}{l}
x=\frac{1}{2}\,a_x\, t^2+{v_0}_x\, t+x_0\vspace{6pt}\\
v_x=a_x\, t+{v_0}_x\vspace{6pt}\\
a_x={a_0}_x=\mathrm{constante}
\label{}
\end{array}}$$

Connaissant la position initiale, la vitesse initiale et l'accélération
du mobile, on peut déterminer sa position et sa vitesse à toute date. La
figure
[\[fig:mruvvitessetemps\]](#fig:mruvvitessetemps){reference-type="ref"
reference="fig:mruvvitessetemps"} montre les représentations $v_x=f(t)$
de quelques cas particuliers.

\subfloat[$a_x>0$]
{\includegraphics{./Figures/Mruvaccpos}}
\hfill
\subfloat[$a_x<0$]
{\includegraphics{./Figures/Mruvaccneg}}
\hfill
\subfloat[$a_x>0$]
{\includegraphics{./Figures/Mruvinitneg}}
En éliminant le temps dans les équations du mouvement, on obtient une
relation entre vitesse et position:
$$v_x=a_x\, t+{v_0}_x\Longrightarrow t=\frac{v_x-{v_0}_x}{a_x}$$ d'où:
$$\begin{aligned}
x &=\tfrac{1}{2}\,a_x\left(\frac{v_x-{v_0}_x}{a_x}\right)^2+{v_0}_x\left(\frac{v_x-{v_0}_x}{a_x}\right)+x_0\\
&= \tfrac{1}{2}\,\frac{{v_x}^2-2\,v_x\,{v_0}_x+{{v_0}_x}^2}{a_x}+\frac{{v_0}_x\,v_x-{{v_0}_x}^2}{a_x}+x_0\\
&= \frac{{v_x}^2-2\,v_x\,{v_0}_x+{{v_0}_x}^2+2\,{v_0}_x\,v_x-2\,{{v_0}_x}^2}{2\,a_x}+x_0\\
&= \frac{{v_x}^2-{{v_0}_x}^2}{2\,a_x}+x_0\end{aligned}$$ donc:
$$x-x_0=\frac{{v_x}^2-{{v_0}_x}^2}{2\,a_x}$$ et finalement:
$$\boxed{{v_x}^2-{{v_0}_x}^2=2\,a_x\, (x-x_0)}$$

### Exercices

Une voiture part du repos et atteint 100 km/h en 12 s avec une
accélération constante. Ensuite elle roule à vitesse constante pendant
30 s. Quelle est la distance totale parcourue? Calcule la décélération
nécessaire pour qu'elle s'arrête en 5 s.

Un cycliste grimpe un col de longueur $d$ à la vitesse moyenne
$v=\SI{18}{\kilo\meter\per\hour}$, puis sans s'arrêter, redescend le
même col à la vitesse moyenne $v'=\SI{42}{\kilo\meter\per\hour}$.

1.  Calcule la vitesse moyenne du cycliste pour cet aller-retour.

2.  Sachant que le temps total du parcours est de
    $\SI{1}{\hour}\:\SI{40}{\minute}$, calcule la longueur $d$ du col et
    les temps mis pour effectuer l'ascension, la descente.

Deux piétons $A$ et $B$ se déplacent dans le même sens sur une route
rectiligne. La vitesse de $A$ est 5,4 km/h, celle de $B$ est 3,6 km/h.
La distance qui les sépare à $t=0$ est 80 m, $B$ étant en avance sur
$A$.

1.  À quelle date $t$ $A$ dépassera-t-il $B$?

2.  Quelle sera alors la distance parcourue par chaque piéton depuis
    l'instant $t=0$?

3.  Représenter sur un graphique la distance séparant les piétons en
    fonction du temps.

Deux mobiles $M$ et $M'$ se déplacent sur un axe $x'x$. Leurs abscisses
respectives sont $x=2t-2$, $x'=-3t+4$ ($x$ et $x'$ en , $t$ en ).

1.  Que peut-on dire des mouvements de $M$ et $M'$?

2.  Quelles sont les valeurs de leurs vitesses?

3.  À quelle date les deux mobiles se rencontrent-ils?

4.  À quelles dates sont-ils distants de 2 m?

Un voyageur arrive sur le quai de la gare à l'instant où son train
démarre. Le voyageur, qui se trouve à une distance $d=\SI{25}{\meter}$
de la portière, court à la vitesse constante
$v_1=\SI{24}{\kilo\meter\per\hour}$. Le train est animé d'un mouvement
rectiligne d'accélération constante
$a=\SI{1,2}{\meter\per\square\second}$.

1.  Le voyageur pourra-t-il rattraper le train?

2.  Dans le cas contraire, à quelle distance minimale de la portière
    parviendra-t-il ?

Une automobile se trouvant à 5 m devant un feu rouge démarre avec une
accélération $a=\SI{2,5}{\meter\per\square\second}$ lorsque le feu passe
au vert. À cet instant, un camion roulant à la vitesse
$v=\SI{45}{\kilo\meter\per\hour}$ se trouve à une distance
$d=\SI{25}{\meter}$ du feu devant celui-ci. Il maintient sa vitesse
constante. Dans un premier temps, le camion va doubler l'automobile,
puis celle-ci va dépasser le camion. On choisit comme origine des dates
l'instant où le feu passe au vert, et comme origine des espaces, la
position du feu tricolore. Déterminer:

1.  les dates des dépassements;

2.  les abscisses des dépassements;

3.  les vitesses de l'automobile à ces instants.

Robin des Bois aperçoit Marianne qui a faussé compagnie au vilain shérif
de Nottingham et qui s'éloigne en courant dans la forêt à une vitesse
constante de 9 km/h. Au moment où il l'aperçoit, la belle a 50 m
d'avance sur lui. On suppose que Robin des Bois avance à vitesse
constante de 18 km/h sur son cheval au moment où il aperçoit Marianne.

Vous choisirez comme origine des temps le départ de Robin des Bois et
comme origine des espaces sa position à $t= 0$.

*1 cas*:

On suppose que Robin continue à la même vitesse. Au bout de combien de
temps rejoindra-t-il Marianne?

*2 cas*:

On suppose qu'au moment où il aperçoit Marianne, Robin accélère et
décrit un MRUV tel que sa vitesse passe de 18 à 36 km/h en 5 s. Au bout
de combien de temps rejoindra-t-il Marianne?

Nestor Boyau arrive en retard en courant à vitesse constante de 5 m/s
sur le quai de la gare; alors que le train s'apprête à partir, Nestor se
trouve 50 m derrière lui. Le train accélère de telle manière qu'il passe
de 0 à 36 km/h en 10 s.

1.  Montrez que Nestor ne peut pas rattraper le train.

2.  Calculez la vitesse minimale que Nestor devrait avoir pour rattraper
    le train. Qu'en pensez-vous? (Le record du monde sur 200 m est de
    l'ordre de 20 s.)

3.  Déterminez la date et le lieu de la rencontre.

Juliette fait du jogging dans la forêt. Elle passe à vitesse constante
de 12,6 km/h devant Roméo assis sur son cheval. Lorsque Juliette a 20 m
d'avance, Roméo fait partir son cheval d'un mouvement accéléré qui le
fait passer en 5 s à une vitesse de 10 m/s.

Vous choisirez comme origine des temps le départ de Roméo et comme
origine des espaces sa position à $t=0$.

1.  Au bout de combien de temps rejoindra-t-il Juliette?

2.  Quelle distance aura-t-il parcourue?

3.  Quelle sera alors sa vitesse (on suppose que le cheval continue son
    mouvement rectiligne uniformément accéléré)?

Lors de sa première traversée, en juillet 1952, le paquebot United
States a gagné le ruban bleu pour avoir effectué la traversée la plus
rapide de l'Atlantique entre New York et Cornwall au Royaume-Uni. Le
voyage avait duré 3 jours $\SI{10}{\hour}\:\SI{40}{\minute}$ avec une
vitesse moyenne de $\SI{65,5}{\kilo\meter\per\hour}$, c'est-à-dire
$\SI{10}{\hour}\:\SI{2}{\minute}$ de moins que le record que détenait
depuis 14 ans le Queen Mary. Quelle était la vitesse moyenne du Queen
Mary?

Un oiseau vole vers le nord à $\SI{20}{\meter\per\second}$ pendant
$\SI{15}{\second}$. Il se repose pendant $\SI{5}{\second}$ puis vole
vers le sud à $\SI{25}{\meter\per\second}$ pendant $\SI{10}{\second}$.
Déterminez, la vitesse moyenne pour la totalité de son voyage.

Une automobile et un camion se déplacent initialement dans la même
direction à $\SI{20}{\meter\per\second}$, le camion ayant
$\SI{38}{\meter}$ d'avance. L'automobile accélère à un taux constant de
$\SI{2}{\meter\per\second\squared}$, dépasse le camion, et se rabat dans
la voie de droite lorsqu'elle se trouve à 11 m devant le camion. Quelle
distance a parcourue le camion durant ce temps?

Le train $A$ a une longueur de 1 km et roule à
$\SI{50}{\meter\per\second}$. Le train $B$ a une longueur de
$\SI{0,5}{\kilo\meter}$ et démarre juste à l'instant où l'arrière du
train $A$ passe au niveau de l'avant du train $B$. Le train $B$ a une
accélération de $\SI{3}{\meter\per\second\squared}$ et une vitesse
maximale de $\SI{60}{\meter\per\second}$.

1.  À quel instant $B$ dépasse-t-il $A$, c'est-à-dire à quel instant
    l'arrière de $B$ dépasse-t-il l'avant de $A$?

2.  Quelle distance le train $A$ a-t-il parcourue pendant ce temps?

Un T.G.V. roule sur une voie rectiligne à la vitesse de
$\SI{260}{\kilo\meter\per\hour}$. La longueur du convoi vaut
$\SI{400}{\meter}$. Un hélicoptère, de longueur négligeable, vole à
$\SI{300}{\kilo\meter\per\hour}$ au-dessus de la voie ferrée dans le
sens inverse du TGV. Le TGV et l'hélicoptère se croisent sur la voie
rectiligne. Calculer le temps pendant lequel l'hélicoptère va rester à
au-dessus du TGV.

Un automobiliste roule sur un tronçon d'autoroute rectiligne à la
vitesse de $\SI{130}{\kilo\meter\per\hour}$. Soudain, un obstacle fixe
apparaît sur la voie à une distance de 120 m. Le conducteur freine
immédiatement et réduit sa vitesse à $\SI{105}{\kilo\meter\per\hour}$ au
bout d'une durée de $\SI{1}{\second}$. On suppose la décélération de
l'automobile constante.

1.  Calculer la valeur de la décélération.

2.  À quelle distance de l'obstacle la voiture va-t-elle s'arrêter?

La plus grande vitesse atteinte par un être humain est de
$\SI{12,5}{\meter\per\second}$. C'est Robert Hayes qui a réalisé cet
exploit pendant une course. Une Porsche 911 Turbo peut atteindre
$\SI{96}{\kilo\meter\per\hour}$ en $\SI{4,6}{\second}$. Supposons que
Hayes puisse maintenir sa vitesse maximale et que l'automobile démarre
juste au moment où il arrive à sa hauteur.

1.  Où et quand va-t-elle le rattraper?

2.  Quelles sont leurs vitesses à ce point?
