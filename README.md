# Experiments Website

## Overview

Here we present additional experiments that further confirm the performance of our proposed method, CMAB-SAMBA. 
Here we have experimetns with larger scale, as well as additional ablation studies. 

# Experiment 1: Regret Progression Over Rounds (K = 20, 50, 100)

We run our experiments for larger scale settings to confirm the scalability of our method.

## $K = 20, d = 5, C = 100k, \Delta = 10^{-2}$

<table>
  <tr>
    <td align="center">
      <img src="no_mucbv_K20.png" width="300"><br>
      <sub><b>(a)</b> No Corruption.</sub>
    </td>
     <td align="center">
      <img src="random_mucbv_K20.png" width="300"><br>
      <sub><b>(b)</b> Corruption in C random Rounds.</sub>
    </td>
    </tr>
  <tr>
    <td align="center">
      <img src="prefix_mucbv_K20.png" width="300"><br>
      <sub><b>(c)</b> First C Rounds Corrupted
    </td>
    <td align="center">
      <img src="paper_mucbv_K20.png" width="300"><br>
      <sub><b>(d)</b> Targeted Attack.</sub>
    </td>
  </tr>
</table>
 
<p align="center">
  <b>Figure 1.</b> $K = 20, d = 5, C = 100k, \Delta = 10^{-2}$
</p>

## $K = 50, d = 5, C = 100k, \Delta = 10^{-2}$

<table>
  <tr>
    <td align="center">
      <img src="no_K50.png" width="300"><br>
      <sub><b>(a)</b> No Corruption.</sub>
    </td>
     <td align="center">
      <img src="random_K50.png" width="300"><br>
      <sub><b>(b)</b> Corruption in C random Rounds.</sub>
    </td>
    </tr>
  <tr>
    <td align="center">
      <img src="prefix_K50.png" width="300"><br>
      <sub><b>(c)</b> First C Rounds Corrupted
    </td>
    <td align="center">
      <img src="paper_K50.png" width="300"><br>
      <sub><b>(d)</b> Targeted Attack.</sub>
    </td>
  </tr>
</table>
 
<p align="center">
  <b>Figure 1.</b> $K = 50, d = 5, C = 100k, \Delta = 10^{-2}$
</p>


## $K = 100, d = 5, C = 100k, \Delta = 10^{-2}$

<table>
  <tr>
    <td align="center">
      <img src="no_K100.png" width="300"><br>
      <sub><b>(a)</b> No Corruption.</sub>
    </td>
     <td align="center">
      <img src="random_K100.png" width="300"><br>
      <sub><b>(b)</b> Corruption in C random Rounds.</sub>
    </td>
    </tr>
  <tr>
    <td align="center">
      <img src="prefix_K100.png" width="300"><br>
      <sub><b>(c)</b> First C Rounds Corrupted
    </td>
    <td align="center">
      <img src="paper_K100.png" width="300"><br>
      <sub><b>(d)</b> Targeted Attack.</sub>
    </td>
  </tr>
</table>
 
<p align="center">
  <b>Figure 1.</b> $K = 100, d = 5, C = 100k, \Delta = 10^{-2}$
</p>
## Notes

- All figures are stored in the `figures/` folder.
- Replace the sample captions with your experiment-specific descriptions.
- You can add more sections here for methods, data, or conclusions.
