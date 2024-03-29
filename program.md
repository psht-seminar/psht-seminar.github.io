## 2022--2023

- [Jun 2023: Nina Otter, and Kelly Maggs and Samuel Lavenir](#talk-2-9)
- [May 2023: Michael Usher and Ryan Grady](#talk-2-8)
- [Apr 2023: Steve Oudot and Daniel Perez](#talk-2-7)
- [Mar 2023: Sylvain Douteau and René Corbet](#talk-2-6)
- [Feb 2023: Ulrich Bauer and Vadim Lebovici](#talk-2-5)
- [Jan 2023: Justin Curry and Abigail Hickok ](#talk-2-4)
- [Dec 2022: Claudia Landi and Benedikt Fluhr](#talk-2-3)
- [Nov 2022: Ezra Miller and Benjamin Blanchette](#talk-2-2)
- [Oct 2022: Martina Scolamiero and Lukas Waas](#talk-2-1)

## 2021--2022
- [Jun 2022: Paul Biran and Darrick Lee](#talk-1-8)
- [May 2022: Stéphane Guillermou and Alexander Rolle](#talk-1-7)
- [Apr 2022: Andrew Blumberg and Luis Scoccola](#talk-1-6)
- [Mar 2022: Pierre Schapira and Barbara Giunti](#talk-1-5)
- [Feb 2022: Wojciech Chachólski and Adam Brown](#talk-1-4)
- [Jan 2022: Michael Lesnick and Yuichi Ike](#talk-1-3)
- [Dec 2021: Rick Jardine and Jun Zhang](#talk-1-2)
- [Nov 2021: Léonid Polterovich and Magnus Botnan](#talk-1-1)

---

&nbsp;
&nbsp;


## June 13th, 2023 <a name="talk-2-9"></a>

### Nina Otter (Queen Mary University of London, UK)

*The (persistent) magnitude of a metric space*

>Magnitude is an isometric invariant for metric spaces that was introduced by Leinster around 2010, and is currently the object of intense research, since it has been shown to encode many known invariants of metric spaces. Magnitude is related to persistent homology, and this relationship has opened a new area of investigation in both magnitude and persistence theory. In this talk I will give an overview of the two fields, and discuss invariants of persistence modules arising from this connection. This talk is partly based on joint work with Sara Kalisnik, Miguel O’Malley, Barbara Giunti, Lukas Waas and John Nolan.


### Kelly Maggs and Samuel Lavenir (EPFL, Lausanne, Switzerland)

*Persistent Minimal Models in Rational Homotopy Theory*

>Rational homotopy theory aims at studying homotopy types by disregarding the torsion phenomena that inevitably occur in homotopy theory. Its power comes from the ability to model homotopy types using algebraic invariants such as (differential graded) commutative algebras. The use of minimal models - as developed by Sullivan - benefits the theory by allowing explicit computations to be performed. 
>
>In this talk, we outline how the ideas of persistence can be applied to the context of rational homotopy theory. After describing how obstruction theory can be used to compute explicit minimal models for persistent (differential graded) commutative algebras, we will describe how this construction hints at the idea of a model structure on the category of persistent chain complexes. This structure is described by explicit sets of generating cofibrations with respect to which persistent minimal models become cell complexes. By transfer along free-forgetful adjunctions, we obtain cofibrantly generated model structures on various categories of persistent differential graded algebras.

## May 9th, 2023 <a name="talk-2-8"></a>

### Michael Usher (University of Georgia, USA)

*Abstract interlevel persistence for Morse-Novikov and Floer theory*

>The persistence module given by the sublevel sets of a Morse function on a smooth manifold can be computed from the filtered Morse chain complex associated to the function. This adapts straightforwardly to certain contexts in symplectic geometry, with the filtered Morse complex replaced by the filtered Hamiltonian Floer complex; this viewpoint (in various guises) has a long and successful history.  In this talk we will describe the (two-parameter) persistence module given by the interlevel sets (preimages of general intervals) of a Morse function in terms of data related to Morse complexes, giving a flexible abstract formulation that again can be applied, inter alia, to Hamiltonian Floer theory. This includes situations in which the function becomes single-valued only after lifting to a covering space. 
>The basic structure that we introduce, a "filtered matched pair," encodes data modeling the interaction of the homologies of sub- and superlevel sets of the function in a way reminiscent of the extended persistence of Cohen-Steiner, Edelsbrunner, and Harer.  Filtered matched pairs have associated barcodes that satisfy an abstract stability theorem.  In the presence of additional structure that abstracts Poincaré duality, the barcodes satisfy symmetry properties familiar from extended and interlevel persistence.

### Ryan Grady (Montana State University, USA)

*K-theory for persistence modules*

>We compute the K-theory spectrum and resulting K-groups for multiparameter persistence modules valued in vector spaces or pointed sets. Our point of view is to write persistence modules as constructible cosheaves on a stratified parameter space and use exodromy to perform computations in terms of representations of the associated (combinatorial) entrance path categories.  We will discuss how many classical (additive) invariants define classes in the Grothendieck group $K_0$; which is a result known in many circles for at least 30 years.  We will then pivot and discuss the group $K_1$ and its relationship to automorphisms. We will finish by describing work in progress on explicit constructions of classes in $K_1$. Our talk is based on joint work with Anna Schenfisch.


## April 11th, 2023 <a name="talk-2-7"></a>

### Steve Oudot (Inria Saclay - Ile-de-France, France)

*Signed rank decompositions for multi-parameter persistence: from Moebius inversion to relative homological algebra*

>A question that comes up repeatedly in recent developments on multi-parameter persistence is to define mathematically sound and computationally tractable notions of approximation for multi-parameter persistence modules. As $\mathbb{R}^n$ is of wild representation type, one seeks to approximate arbitrary (say, finitely presentable) modules by modules coming from some subcategory that is easier to work with in practice. An obvious candidate subcategory is the one of interval-decomposable modules, whose summands are indicator modules of intervals (i.e. convex, connected subsets of $\mathbb{R}^n$, equipped with the product order). Indeed, interval-decomposable modules are convenient to work with, since they are easy to encode and manipulate on a computer, and to interpret visually. Several notions of module approximation using this subcategory have been proposed, among which the most common one seeks to preserve the rank invariant when switching from the original module to its interval-decomposable approximation. The motivation is that, the rank invariant being one of the weakest invariants available to us, preserving it is considered to be a minimum. As it turns out, this is not always possible, however one can always decompose the rank invariant of the module as a $\mathbb{Z}$-linear combination of rank invariants of interval modules. Thus, a weaker form of preservation of the rank invariant is possible, in which the interval summands are signed (hence the name "signed rank decomposition"). This fact can be viewed as a consequence of the Moebius inversion formula, but more fundamentally, it can be obtained by working in  the Grothendieck group relative to an appropriate exact structure, where the rank invariant of the module becomes equal to the alternating sum of the rank invariants of the various terms in the module's minimal relative projective resolution. This alternative proof strategy offers some significant benefits: (1) it links the coefficients in the decomposition to the structure of the module, as in the 1-parameter setting; (2) it provides a roadmap to study their bottleneck stability; (3) it connects multi-parameter persistence to relative homological algebra, thereby paving the way towards the definition of more refined invariants for multi-parameter persistence modules using larger classes of projectives. The purpose of my talk will be to tell this story.

### Daniel Perez (Département de mathématiques et applications - ENS Paris, France)
 
*Some topological properties of subgaussian fields on Riemannian manifolds*

>We discuss some topological properties of the persistent homology of subgaussian fields on compact Riemannian manifolds. This class of processes have many desirable properties regarding the distribution of its the persistence diagrams. In particular, a stochastic stability theorem of persistence diagrams can be shown to hold for these processes. We will discuss an application of the results presented to Euler and Betti curves, and give some perspectives and outlook regarding these topics.

## March 14th, 2023 <a name="talk-2-6"></a>

### Sylvain Douteau (Institut de recherche en informatique fondamentale, Paris Cité University, France)

*Stratified homotopy theory*

> Stratifications and stratified spaces first arised from the study of singular objects. In that context, a space is decomposed into strata corresponding to various degrees of singularity. Nowadays, stratifications - and stratified spaces - are defined much more broadly, as a sort of generalized filtration on spaces, which is used to encode some structure, that may or may not be related to singularities.
>
>Based on that general point of view, stratified homotopy theory tries to offer a homotopy theoretic description of the spaces carrying a stratification, while retaining homotopy theoretic information about the stratifications themselves. In my talk, I will explain how to construct several Quillen-equivalent model categories for the homotopy theory of stratified spaces, and present a particularly nice model for the homotopy category of stratified spaces : the category of labelled CW-complexes.


### René Corbet (KTH, Stockholm, Sweden)
 
*A computational perspective on noise systems and stable rank*

>Noise systems, as introduced by Scolamerio et al., give a rich framework for the construction of distances in one- and multiparameter persistence. When used together with hierarchical stabilization, as introduced by Gäfvert and Chachólski, we get stable invariants. A main example of hierarchical stabilization is stable rank: given a distance, for every ball around a persistence module, we extract the minimum over the number of generators of those persistence modules that one can find in this neighborhood. In particular, stable rank is a non-increasing function suitable for machine learning algorithms.
>
>I will first give an incomplete survey on the successes of noise systems and stable rank in one-parameter persistence under the lens of computation and applications. This includes work by Agerberg, Chachólski, Guidolin, Riihimäki, Scolamiero, and Wehlin.
>
>Then we discuss challenges, partial success, and open questions in the case of multiparameter persistence. As shown by Gäfvert and Chachólski, the intricacy of the algebraic theory of multiparameter persistence yields that the problem of computing of stable rank for a standard noise system is algorithmic but NP-hard. In fact, even computing the shift-dimension is NP-hard.
>We search for overcoming the computational challenges with approximation techniques relying on the computation of stable rank on interval modules. Given a simple noise system and an interval decomposable module, summing up stable rank summand-wise is guaranteed to be an upper bound of stable rank, but is neither guaranteed to be equal to stable rank, nor to be stable. Many questions can be asked: How well can we expect this additive version of stable rank to approximate original stable rank, in theory, and in practice? Does it make sense to consider a signed additive version for resolutions of persistence modules consisting of interval modules? How does the approximation of stable rank perform in applications? Do these techniques make sense for stable invariants other than stable rank?
>This is based on joint work with Chachólski and Sattelberger, and on ongoing joint work with Scolamiero.

## February 14th, 2023 <a name="talk-2-5"></a>

### Ulrich Bauer (Technical University of Munich, Germany)

*Indecomposables in multiparameter persistence*

>I will discuss various aspects of multi-parameter persistence related to representation theory and decompositions into indecomposable summands, based on joint work with Magnus Botnan, Steffen Oppermann, Johan Steen, Benedikt Fluhr, and Luis Scoccola.
>
>A classification of indecomposables is infeasible; the category of two-parameter persistence modules has wild representation type. We show [1] that this is still the case if the structure maps in one parameter direction are epimorphisms, a property that is commonly satisfied by degree 0 persistent homology and related to filtered hierarchical clustering.
>
>Furthermore, we show [2] that indecomposable persistence modules are dense in the interleaving distance, and that being nearly-indecomposable is a generic property of persistence modules.
>
>On the other hand, the two-parameter persistence modules arising from interleaved sets (relative interleaved set cohomology) have a very well-behaved structure [3] that is encoded as a complete invariant in the extended persistence diagram. This perspective reveals some important but largely overlooked insights about persistent homology; in particular, it highlights a strong reason for working at the level of chain complexes, in a derived category [4].
>
>[1] Bauer, U., Botnan, M. B., Oppermann, S., & Steen, J. (2020). Cotorsion torsion triples and the representation theory of filtered hierarchical clustering. Advances in Mathematics, 369, 107171.
>
>[2] Bauer, U., & Scoccola, L. (2022). Generic Two-Parameter Persistence Modules are Nearly Indecomposable. arXiv preprint arXiv:2211.15306.
>
>[3] Bauer, U., Botnan, M. B., & Fluhr, B. (2021). Structure and Interleavings of Relative Interlevel Set Cohomology. arXiv preprint arXiv:2108.09298.
>
>[4] Bauer, U., & Fluhr, B. (2022). Categorification of Extended Persistence Diagrams. arXiv preprint arXiv:2205.15275.

### Vadim Lebovici (Université Paris-Sud, France)

*Hybrid transforms of constructible functions*

>Euler calculus techniques — integration of constructible functions with respect to the Euler characteristic — have led to important advances in topological data analysis. One reason is that constructible functions naturally associated to multi-parameter persistent modules stand as simple, informative and well-behaved invariants of these objects. In this talk, I will introduce integral transforms combining Lebesgue integration and Euler calculus for constructible functions. I will focus on two examples. First, the Euler-Laplace transform, which is a satisfactory generalisation of Govc and Hepworth’s persistent magnitude to multi-parameter persistent modules. Second, the Euler-Fourier transform, which is injective on a subset of constructible functions and paves the way for a hybrid Fourier theory.


## January 10th, 2023 <a name="talk-2-4"></a>

### Justin Curry (University at Albany SUNY, USA)

*Algebraic and Geometric Models for Space Networking*

>In this talk I will describe recent and ongoing work dedicated to developing scalable autonomous routing protocols for a future solar system wide internet. At the heart of the talk will be a description of a new coordinate system (based on cosheaves and persistence) for time-varying graphs. In this new coordinate system, we can describe distances between various space networking scenarios, as well as model routing (with propagation delay) using matrix multiplication in a modified coefficient system valued in semi-rings.  To demonstrate these models in practice, we use simulations of Earth-Moon-Mars systems generated in SOAP (Satellite Orbital Analysis Program) ranging from 10s to 100s of nodes in size. These simulations are part of a growing codebase being developed by SUNY Albany and NASA Glenn Research Center under the TIMAEUS project.

### Abigail Hickok (University of California, Los Angeles, USA)

*Persistence Diagram Bundles: A multidimensional generalization of vineyards*

>It is an active area of research to develop new methods for analyzing how the topology of a data set changes as multiple parameters vary. For example, if a point cloud evolves over time, then one might be interested in using time as a second parameter. When there are only two parameters (e.g., a scale parameter and time), one can compute a "vineyard," which encodes how persistent homology (PH) changes over time. However, vineyards cannot be used when there are more than two parameters. For example, in many time-evolving point clouds, there are additional system parameters controlling the coordinates of the points, and distinct topological features may arise for different system parameters. Generally, one cannot use multiparameter PH, either, because the filtered complexes constructed from the point clouds at different times and different system parameters do not form a multifiltration. In recent work, I generalized the concept of a vineyard to a "persistence diagram (PD) bundle," in which a set of filtered complexes is parameterized by an arbitrary topological space. In this talk, I'll discuss what a PD bundle is, talk about an algorithm for efficiently computing piecewise-linear PD bundles, and show that PD bundles can exhibit "monodromy," unlike vineyards. I'll also talk about a connection to cellular sheaves.


## December 13th, 2022 <a name="talk-2-3"></a>

### Claudia Landi (Università di Modena e Reggio Emilia, Italy)

*Morse inequalities for the Koszul complex of multi-persistence*

>In this talk, I will show how to derive inequalities involving, on the one hand, the homological Morse numbers of a filtered cell complex, and, on the other hand, the multi-graded Betti numbers of the multi-parameter persistence modules of such filtrations. Here, the homological Morse numbers of a filtration are defined in terms of the relative homology of nested filtration pieces and capture the minimal possible number of critical cells in any gradient vector field consistent with the filtration. We will first obtain strong and weak Morse inequalities involving the above quantities. Then we will improve the weak inequalities achieving a sharp lower bound for the homological Morse numbers. The main tool is the Mayer-Vietoris spectral sequence. Finally, we will see a tight upper bound for the minimal number of critical cells, expressed again in terms of multi-graded Betti numbers.

### Benedikt Fluhr (Technical University of Munich, Germany)

*Categorification of (Extended) Persistence Diagrams*

>We demonstrate how the lack of additivity of the rank invariant
restrains us from adopting tried-and-true approaches from algebraic
topology to persistence theory at the example of a pointwise
Mayer–Vietoris sequence in persistent homology. Then we explain how
persistence diagrams can be obtained as a universal additive invariant
of relative sublevel set cohomology. Finally, we return to our
motivating example from the beginning and we compute a persistence
diagram by using a Mayer–Vietoris sequence in relative sublevel set
cohomology. This is joint work with Ulrich Bauer (arXiv:2205.15275).




## November 8th, 2022 <a name="talk-2-2"></a>

### Ezra Miller (Duke University, USA)

*Concrete representatives for multiparameter derived sheaves*

>Persistent homology with multiple real parameters can be phrased
in more or less equivalent ways in terms of multigraded modules,
or sheaves, or functors, or derived categories.  All of these
descriptions have in common an underlying partially ordered set
indexing a family of vector spaces, and this family is
interpreted under increasing layers of abstraction.  The simplest
objects at any level of abstraction are the "indicator" objects,
which place a single copy of the ground field at every point of
an interval (an intersection of an upset with a downset) in the
underlying poset.  Taking the cue from ordinary persistence,
where there is just one real parameter, the theory of real
multipersistence has in large part revolved around relating
arbitrary persistent homology as closely as possible to indicator
objects, particularly where algorithmic computation is concerned.
To that end, effective methods demand concrete representatives of
derived sheaves and stratifications of their supports.  Kashiwara
and Schapira conjectured that derived sheaves in principle
possess such concrete representatives and stratifications.  The
goal here is to prove their conjectures, in a manner designed to
extract indicator resolutions algorithmically and produce data
structures, by way of a syzygy theorem for poset modules.


### Benjamin Blanchette (Université de Sherbrooke, Canada)

*Bounding lengths of relative resolutions of persistence modules*

>We start by going over a homological approach to approximating persistence modules over wild posets by a controlled set of indecomposable modules, then present results as well as work in progress related to bounding resolution length for various such families including intervals, hooks, single sourced, upsets and all spreads.



## October 11th, 2022 <a name="talk-2-1"></a>

### Martina Scolamiero (KTH, Stockholm, Sweden)

*p-Wasserstein- stable topological features*


>In the hierarchical stabilisation framework, topological invariants for persistence (e.g the stable rank) are constructed starting from metrics to compare persistence modules. Such metrics can be defined axiomatically at the algebraic level and include parametrised families such as p-Wasserstein distances and distances induced by so called contours. After highlighting the different nature of these types of distances, we will discuss a way to combine them. The focus of the talk will then be on the computation and the properties of the stable ranks built from these new combined distances. 

### Lukas Waas (Heidelberg University, Germany)

*From samples to persistent stratified homotopy types*

>For many applications, both of theoretical as well as of applied nature, homotopy type can be too coarse of a discriminating invariant. For example, while closed one-manifolds and (smooth) surfaces are entirely classified by their homology and thus by their homotopy type, even in dimension one this is not the case for singular spaces. I will begin this talk with a short introduction to stratified homotopy theory, a version of homotopy theory tailored to deal with spaces with singularities. I will then explain how stratified homotopy theory can be used in topological data analysis to obtain finer invariants than persistent homology which are specifically adapted to detect and investigate singular data sets.


## June 14th, 2022 <a name="talk-1-8"></a>

### Paul Biran (ETH Zürich, Switzerland)

*Persistence K-theory*

>  K-theory, in its classical form, associates to a triangulated category an abelian group called the K-group (or the Grothendieck group). Important invariants of various triangulated categories are known to factor through their K-groups. In this talk we will explain the foundations of persistence K-theory, which is an analogous theory for triangulated persistence categories. In particular we will introduce new persistence measurements coming from these K-groups, and new invariants coming from the combination of the persistence and triangulated structures. In the last part of the talk we will exemplify this new theory on the case of the persistence Fukaya category of Lagrangian submanifolds. In particular we will show how our invariants can distinguish between modules that can represent embedded Lagrangians and those who can represent only immersed ones. Based on joint work with Octav Cornea and Jun Zhang.

### Darrick Lee (EPFL, Lausanne, Switzerland)

*A Topological Approach to Signatures*

>  The path signature is a characterization of paths initially developed by K. T. Chen to study the topology of loop spaces. This has recently been used to develop the foundations of rough paths in stochastic analysis, and provides a powerful feature map for sequential data in machine learning. We introduce a generalization of the path signature to mapping spaces, motivated by Chen's iterated integral cochain models, and show that it preserves many analytic and algebraic properties which makes it suitable for applications.

## May 10th, 2022 <a name="talk-1-7"></a>

### Stéphane Guillermou (Institut Fourier, Grenoble, France)

*The microsupport of sheaves is $\gamma$-coisotropic*

> An important result of Kashiwara and Schapira in microlocal sheaf theory says that the microsupport of sheaves is coisotropic. Since a microsupport is a priori not smooth the meaning of coisotropic has to be precised. The definition of Kashiwara and Schapira asks that the "small" tangent cone at any point contains the symplectic orthogonal of the "big" tangent cone. Other definitions of coisotropic have been proposed recently by Usher and Viterbo ("$\gamma$-coisotropic") which are invariant by symplectic homeomorphism. We will review these notions and see that the microsupport is $\gamma$-coisotropic. This is Joint work with Claude Viterbo.

### Alexander Rolle (TUM, Munich, Germany)

*Functorial nerve theorems for persistence*

>  The nerve theorem is a basic result of algebraic topology that plays a central role in computational and applied aspects of the subject. In applied topology, one is often interested in diagrams of covered spaces and corresponding diagrams of nerves; a functorial nerve theorem relates these diagrams. We describe a framework for proving functorial nerve theorems and show how one can use techniques from homotopy theory to prove a variety of these theorems. This is joint work with Ulrich Bauer, Michael Kerber, and Fabian Roll.

## April 12th, 2022 <a name="talk-1-6"></a>

### Andrew Blumberg (Columbia University, New-York, USA)

*Probabilistic stability theorems for topological data analysis*

> The foundations of topological data analysis rest on stability theorems, which roughly speaking say that small perturbations of point clouds (finite metric spaces) lead to small perturbations of associated persistent topological invariants. In this talk, I will describe various extensions of these results to metric measure spaces, describing joint work with Mike Mandell and Mike Lesnick.

### Luis Scoccola (Northeastern University, USA)

*Bottleneck stability for multigraded Betti numbers and Hilbert functions*

> Unlike one-parameter persistence modules, for which we have the barcode, persistence modules with two or more parameters do not admit a complete discrete invariant, and thus incomplete invariants must be used to study the structure of such modules in practice. The Hilbert function and the multigraded Betti numbers are among the simplest such incomplete invariants, and, although these invariants are already being used in applications, it is a priori unclear whether they satisfy a stability result analogous to the stability of the one-parameter barcode. Stability results are essential for the interpretability and consistency of practical methods. I will present joint work with Steve Oudot in which we prove bottleneck stability results for multigraded Betti numbers and for the Hilbert function. I will put this work into the broad context of additive invariants of persistence modules, and I will discuss connections to recent work of Blanchette, Brüstle, and Hanson on invariants coming from relative homological algebra, to the signed barcodes of Botnan, Oppermann, and Oudot, and to the generalized persistence diagrams of Patel.

## March 8th, 2022 <a name="talk-1-5"></a>

### Pierre Schapira (Sorbonne Université, Paris)

*Thickening of the diagonal and interleaving distance*

> On a topological space X, a thickening kernel is a presheaf on R with values in the monoidal category of kernels on X. To such a thickening kernel, one naturally associates an interleaving distance on the derived category of sheaves and study its properties (stability, Lipschitz). We prove that a thickening kernel exists in two different situations. First, when X is a manifold and one is given a non-positive Hamiltonian isotopy on the cotangent bundle. Second, when X is a metric space satisfying suitable properties, in particular when X is a Riemannian manifold with strictly positive positive convexity radius. We prove that in this case, the two thickening kernels, one associated with the distance, the other with the geodesic flow, coincide. This is joint work with François Petit.

### Barbara Giunti (TU Graz)

*Amplitudes in persistence theory*

> In persistence theory, one starts with data and then build a parameterized object from them, which is then analysed via some invariants, typically retrieved using homology. This pipeline is stable in 1-parameter persistence, where the invariants are all given by the barcode. Since there is no proper generalization of barcode in the multiparamenter case, the choice of the invariants - which is strictly related to the choice of the distances used to ensure the stability of the persistence pipeline - depends on the specific information one wants to extract from the data. Different invariants may greatly vary their behaviour and be stable only under very different distances. With the goal of addressing this problem, we introduce amplitudes, which are invariants that arise from assigning a non-negative real number to each persistence module, and are monotone and subadditive in an appropriate sense. There are different ways to associate a distance to an amplitude, which is useful in practical applications. Indeed, this gives us the possibility to define metrics based on the wanted invariants and fine-tune the stability results. Our framework is very comprehensive, as many different invariants that have been introduced in the Topological Data Analysis literature are examples of amplitudes. Furthermore, many known distances for multiparameter persistence can be shown to be distances from amplitudes. In addition, this framework allows us to compare different distances and can be used to prove new stability results.

## February 8th, 2022 <a name="talk-1-4"></a>

### Wojciech Chachólski (KTH, Stockholm)

*Realisations of Posets and tameness*

> My presentation is based on an article with the same title coauthored with A. Jin and F. Tombari (arXiv:2112.12209). I will present a construction called realisation, transforming posets into posets which are particularly suitable for persistence methods. Intuitively the realisation associates a continuous structure to a locally discrete poset by filling in empty spaces. For example the realisation of $\mathbf{N}^r$ is $[0,\infty)^r$. Our key results can be summarised as: realisations share key features with upper semilattices, which explains why they fit well with persistence. This is unexpected as for example the realisation of an upper semilattice may fail to be an upper semilattice. I will illustrate for example that realisations and upper semilattics share key homological properties. For instance the homological dimension (the length of the minimal free resolution) and Betti numbers of tame vector space valued functors indexed by both realisations and upper semilattices can be calculated using Koszul complexes. Consequently, calculating these invariants for functors indexed by both types of posets can be done directly, avoiding constructing explicit resolutions.

### Adam Brown (IST Austria)

*Computing Minimal Injective Resolutions*

>  Efficient algorithms for computing classical operations on sheaves are necessary to further develop applications of derived sheaf theory in topological data analysis. Injective resolutions, a fundamental `first-step’ in this pipeline, are used to study sheaves from the derived perspective, i.e. as objects in a derived category. In this talk we will discuss methods for computing injective resolutions of sheaves on simplicial complexes. We will outline the existence and uniqueness of minimal injective resolutions, an algorithm for their construction, and (time permitting) give an asymptotically tight bound on the computational complexity of this algorithm. This talk is based on joint work with Ondrej Draganov.

## January 11th, 2022 <a name="talk-1-3"></a>

### Michael Lesnick (SUNY Albany)

*$\ell^p$-Metrics on Multiparameter Persistence Modules*

> Motivated both by theoretical and practical considerations in topological data analysis, we generalize the $p$-Wasserstein distance on barcodes to multiparameter persistence modules. For each $p \in [1,\infty]$, we in fact introduce two such generalizations $d_I^p$ and $d_M^p$, such that $d_I^\infty$ equals the interleaving distance and $d_M^\infty$ equals the matching distance. Finally, we show that on 1- or 2-parameter persistence modules over prime fields, $d_I^p$ is the universal (i.e., largest) metric satisfying a natural stability property; this result extends a stability theorem of Skraba and Turner for the $p$-Wasserstein distance on barcodes in the 1-parameter case, and is also a close analogue of a universality property for the interleaving distance given by the second author. We also show that $d_M^p \leq d_I^p$ for all $p \in [1,\infty]$, extending an observation of Landi in the $p = \infty$ case. We observe that the distances $d_M^p$ can be efficiently approximated. In a forthcoming paper, we apply some of these results to study the stability of (2-parameter) multicover.

### Yuichi Ike (University of Tokyo)

*Interleaving distance for sheaves and displacement energy in symplectic geometry*

> I will talk about some interactions among the microlocal theory of sheaves, persistence modules, and symplectic geometry. The microlocal theory of sheaves has been applied to symplectic geometry after the pioneering work of Tamarkin. Motivated by the work of Kashiwara and Schapira, we introduce a persistence-like distance on the Tamarkin sheaf category and prove a stability result for a Hamiltonian deformation of sheaves. Using this result, we give a sheaf-theoretic method to give a lower bound of the displacement energy of compact subsets of a cotangent bundle, which is a quantitative generalization of Tamarkin's non-displaceability theorem. Joint work with Tomohiro Asano.


## December 14th, 2021 <a name="talk-1-2"></a>

### Rick Jardine (Western University, Canada)

*UMAP for the working mathematician*

> The Healy-McInnes UMAP algorithm is a highly successful clustering tool that involves interesting ideas from mathematics and data science:
> 1. Spivak's theory of extended pseudo metric spaces (ep-metric spaces)
> 2. TDA constructions in ep-metric spaces
> 3. weighted graphs
> 4. classical dimension reduction
> 5. graph optimization: fuzzy sets, cross entropy
>
>I will explain this algorithm from a mathematical point of view.

### Jun Zhang (Université de Montréal)

*Triangulated persistence category*

> In this talk, we will introduce a new algebraic structure called triangulated persistence category (TPC). A TPC combines the persistence module and the classical triangulation structure so that a meaningful measurement, via cone decomposition, can be defined on the set of objects. We will also elaborate on various examples of TPC that come from algebra, topology, and symplectic geometry. Finally, we will investigate the Grothendieck group of a TPC and explain several unexpected properties. This talk is based on joint work with Paul Biran and Octav Cornea.

## November 9th, 2021 <a name="talk-1-1"></a>

### Léonid Polterovich (Tel Aviv University)

*Persistence barcodes in symplectic topology*

> I shall review some applications of the theory of persistence modules in symplectic topology.

### Magnus Botnan (VU, Netherlands)

*Signed barcodes for multiparameter persistence*

> Moving from persistent homology in one parameter to multiparameter persistence comes at a significant increase in complexity. In particular, the notion of a barcode does not generalize straightforwardly. However, in this talk, I will show how it is possible to assign a unique barcode to a multiparameter persistence module if one is willing to take Z-linear combinations of intervals. The theoretical discussion will be complemented by numerical experiments. This is joint work with Steffen Oppermann and Steve Oudot.
