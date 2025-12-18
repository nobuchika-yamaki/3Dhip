# 3Dhip
README
Overview

This repository contains the complete analysis code used in the study
“A three-dimensional geometric model reveals posture-dependent effects of femoral anteversion on hip structural alignment.”

The code implements a minimal three-dimensional geometric model to quantify the alignment between the femoral neck axis and the hip joint reaction force across ranges of femoral anteversion, neck–shaft (CCD) angle, and hip flexion.

Model summary

Femoral neck orientation is defined by anteversion (axial rotation) and CCD angle

Hip joint loading direction rotates posteriorly with increasing hip flexion

Structural support is quantified as
S = | n_femur · n_load |

Contents

Full computation of the structural support index S

Generation of Fig. 1 (S heatmap averaged over CCD angles)

Generation of Fig. 2 (ΔS = S(40°) − S(0°) across CCD angles)

Numerical checks reported in the Results section

Detection of posture-dependent restoration onset
