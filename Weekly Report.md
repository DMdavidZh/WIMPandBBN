# Weekly Report

### Summary

* **Period: **Dec 3 to Dec 7, 2020

* **Task Finished:** Reading two papers (1312.5725 and 1908.00007) carefully, learn the formulism in this paper and try to understand how light WIMP particle with mass in $0.1 - 10^{2}\text{ MeV}$ affects the BBN progress.
* **Questions Meet: ** What is the physics details during BBN: what does "WIMP couples with photon and $e^{\pm}$"  means, what is the freeze-out and what is the decouple (especially "neutrino decouple"). What is the four type of light WIMP? Is the temperature $T$ for different component is the Also, not clearly know what should do next. 
* **Plans for next 7 days: **
  * Reading *Modern Cosmology* and other textbooks or review paper *Big Bang Nucleosynthesis: Present status*, understand the basic physics of BBN
  * Reading 3 theoretical papers discussing 3 ways WIMP affects the BBN
  * Summarize reading result and do a presentation on Thursday's group meeting (need to finish two steps above)
  * Try to learn Kawano BBN code and do the Figure 1 in 1312.5725

### Progress in details

In this part, I will write a bit more about the progress for the past 5 days (Dec 3 to Dec 7). I have done literature reading these days so I will write a short reading report below.

#### Reading Report

This week I read two papers concerning the study of light WIMP particles with BBN. In this paper they consider the case with (1) photon, (2) $e^{\pm}$, (3) standard model neutrino, (4) equivalent neutrino and (5) light WIMP. The basic physics I learn from the paper 1312.5725 is listed below

* There are four kinds of light WIMP we are interested in: (1) real scalar, (2) complex scalar, (3) Majorana fermion, (4) Dirac WIMP

* WIMP particles can annihilate into $\gamma, e^{\pm}$ and SM $\nu$. They can also couple with these three particles

* The exist of equivalent neutrino and light WIMP particle can affect the $N_{\rm eff}$. We have from the textbook that
  $$
  \rho_{\nu} = 3 \times \frac{7}{8} \times \left(\frac{T_{\nu}}{T_{\gamma}}\right)^{4}\rho_{\gamma}
  $$
  where $(T_{\nu}/T_{\gamma})^{3} = 4/11$ in standard BBN. If we define $\rho_{R} = \rho_{\gamma}+\rho_{\nu} +\rho_{\xi}$ where $\xi$ denotes equivalent neutrino (e.g., sterile neutrino), we have
  $$
  \left(\frac{\rho_{R}}{\rho_{\gamma}}\right)_{0} = 1 +  \frac{7}{8}\left[ 3 \left(\frac{T_{\nu}}{T_{\gamma}}\right)_{0}^{4} + N_{\xi}\left(\frac{T_{\xi}}{T_{\gamma}}\right)_{0}^{4}\right] = 1 + \frac{7}{8}\left(\frac{4}{11}\right)^{4/3}N_{\rm eff}
  $$
  so we have
  $$
  N_{\rm eff} = \left[ \frac{11}{4}\left(\frac{T_{\nu}}{T_{\gamma}}\right)^{3}_{0} \right]^{4/3} \left[3+N_{\xi}\left(\frac{T_{\xi}}{T_{\nu}}\right)^{4}\right] = 3\left[ \frac{11}{4}\left(\frac{T_{\nu}}{T_{\gamma}}\right)^{3}_{0} \right]^{4/3} \left[1+\frac{\Delta N_{\nu}^{*}}{3}\right] = N_{\rm eff, 0}\left[1+\frac{\Delta N_{\nu}^{*}}{3}\right]
  $$
  where $\Delta N_{\nu}^{*} = N_{\xi}(T_{\xi}/T_{\nu})^{4} $. 

* $N_{\rm eff}$ depends on (1) WIMP properties, (2) coupling and (3) mass of particle

* The combination of different couple scenario (couple with $\gamma/e^{\pm}$ or SM $\nu$) and the presence of $\xi$ will bring different effect on $N_{\rm eff,0}$. CMB can measure $N_{\rm eff,0}$ directly, but it can hard to solve the degenercy of different scenarios as well as constrain the mass of particle (Figure 1 in 1312.5725).  

* There are three ways light WIMP affect the BBN:

  * WIMP contributes to $\rho_{\rm tot}$ and modify the expansion rate, and it tends to cause late freeze-out
  * Colder neutrinos suppress the rate of $n\rightleftharpoons p$, and it suppress $p\rightarrow n$ more, which will cause early freeze-out
  * When $m_{\chi}\leq m_{e}$, the baryon-to-photon ratio $\eta$ changes also when WIMP annihilates. $\eta$ will be improved more significantly when WIMP annihilates after $e^{\pm}$ annihilation

* We need to add the density 
  $$
  \rho_{\chi} = \frac{g_{\chi}}{\pi^{2}}\int_{m_{\chi}}^{\infty}\frac{(E^{2}-m^{2}_{\chi})^{1/2}}{\exp(E/T)\pm 1}E^{2}\mathrm{d}E
  $$
  and the change of $\eta$ by entropy of light WIMP particle 
  $$
  \eta = \eta_{0}\left(1+\frac{S_{e}+S_{\chi}}{S_{\gamma}}\right)
  $$
  to Kawano code.

