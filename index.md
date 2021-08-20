# FRIB-TA Summer School

## A practical walk through formal scattering theory: Connecting bound states, resonances, and scattering states in exotic nuclei and beyond

- Online, August 4-6, 2021.
- [Indico Event Page](https://indico.frib.msu.edu/event/43/)

![FRIB](images/FRIB_southeast_view_cropped.jpg)

## Brief description

Scattering theory is a framework connecting seemingly different phenomena of the quantum world such as stable bound states, resonances, elastic scattering, and reactions. It has applications in many areas of physics, ranging from hadrons and nuclear physics to the description of ultracold atomic systems. In particular, scattering theory provides the foundation for few- and many-body approaches that solve quantum problems from first principles, and it is an essential ingredient for the description of low-energy nuclear reactions that will be studied at the Facility for Rare Isotope Beams (FRIB).

This summer school will offer an introduction to nonrelativistic quantum scattering theory, discussing its fundamental assumptions and techniques guided by concrete applications. Formal aspects, centered around the important concept of the S-matrix, will be covered in detail, complemented at each step by numerical illustrations and hands-on programming exercises.

At the end of this three-day course, participants will have a firm understanding of the basic concepts of scattering theory, how they relate to a variety of few- and many-body quantum systems, and how they can be implemented numerically for simple examples.


## Teachers and local organization

### Lecturers/Organizers:
- [Sebastian K&ouml;nig](https://skoenig.wordpress.ncsu.edu/), North Carolina State University, USA
- [Kevin Fossez](https://www.phy.anl.gov/theory/staff/kfossez/kfossez.html), FRIB, Michigan State University, and Argonne National Laboratory, USA
- [Heiko Hergert](https://pa.msu.edu/profile/hergert/), FRIB, Michigan State University, USA

## Schedule and material

- [Python helper library](code/lib.zip) (required by several notebooks linked below)

### Day 1

- **D1, M1 (9:00am-10:30am EDT): lecture**
  - Introduction ([slides](slides/intro.pdf))
  - Math and physics review ([slides](slides/lecture_FRIBTA_scatt_th_reminder.pdf), [notebook](code/solve_2nd_inho_ODE.ipynb))
- Break (10:30am-11:00am EDT)
- **D1, M2 (11:00am-12:30pm EDT): lecture**
  - Lippmann-Schwinger equation ([slides](slides/lseq.pdf), [notebook](code/lseq.ipynb))
  - Quadrature for integral equations ([notebook](code/quad.ipynb))
- Break (12:30pm-1:30pm EDT)
- **D1, A1 (1:30pm-3:00pm EDT): lecture**
  - Radial Schrödinger equation ([slides](slides/radseq.pdf), [notebook](code/radseq.ipynb))
- Break (3:00pm-3:30pm EDT)
- **D1, A2 (3:30pm-5:00pm EDT): lab**
  - Scattering wavefunctions

### Day 2

- **D2, M1 (9:00am-10:30am EDT): lecture**
  - Lippmann-Schwinger equation (continued)
  - Scattering wavefunctions ([notebook](code/scattwf.ipynb))
  - Scattering eigenstates ([notebook](code/eigen.ipynb))
  - Analytic continuation ([slides](slides/contour.pdf))
- Break (10:30am-11:00am EDT)
- **D2, M2 (11:00am-12:30pm EDT): lab**
  - Bound states and virtual states
- Break (12:30pm-1:30pm EDT)
- **D2, A1 (1:30pm-3:00pm EDT): lecture**
  - Quasi-stationary formalism I ([slides](slides/lecture_FRIBTA_scatt_th_QSF_I.pdf))
- Break (3:00pm-3:30pm EDT)
- **D2, A2 (3:30pm-5:00pm EDT): lab** ([notebook solution](code/qsf_lab_1_sol.ipynb))

### Day 3

- **D3, M1 (9:00am-10:30am EDT): lecture**
  - Quasi-stationary formalism II ([slides](slides/lecture_FRIBTA_scatt_th_QSF_II.pdf), [Jost function paper](https://doi.org/10.1093/ptep/ptt101))
  - Virtual-state search in momentum space ([notebook](code/virtual.ipynb))
- Break (10:30am-11:00am EDT)
- **D3, M2 (11:00am-12:30pm EDT): lab** ([notebook solution](code/qsf_lab_2_sol.ipynb))
- Break (12:30pm-1:30pm EDT)
- **D3, A1 (1:30pm-3:00pm EDT): lecture**
  - Few- and many-body calculations ([slides](slides/lecture_FRIBTA_scatt_th_MB.pdf))
- Break (3:00pm-3:30pm EDT)
- **D3, A2 (3:30pm-5:00pm EDT): lab**

---

This summer school and associated materials were supported by the U.S.
Department of Energy, Office of Science, Office of Nuclear Physics, under the
[FRIB Theory Alliance](https://fribtheoryalliance.org/) award DE-SC0013617.
