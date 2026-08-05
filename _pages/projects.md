---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

<section class="project-showcase">
  <article class="project-feature">
    <h2>Establishing a Systematic Relationship Between MEA Geometry and Mechanical Strain</h2>
    <div class="project-feature__body">
      <div class="project-feature__image">
        <img src="/images/project-mea-strain.png" alt="Microelectrode array entering a tissue block with finite-element strain contours">
      </div>
      <div class="project-feature__story">
        <p>What makes a neural implant gentle enough for the brain? This project begins with that question, using finite element modeling to understand how microelectrode array geometry shapes the mechanical strain inside surrounding tissue.</p>
        <p>I built COMSOL models of geometry-based MEAs interacting with a rodent brain tissue block, then studied how changes in length, width, and thickness altered the strain field. The goal was to move implant design from intuition toward a systematic design space.</p>
        <p class="project-feature__note">Focus: COMSOL Multiphysics, finite element modeling, design of experiment, neural interface mechanics.</p>
      </div>
    </div>
  </article>

  <article class="project-feature">
    <h2>Thin Film Microelectrode Array Fabrication and In-Vivo Immune Response Analysis</h2>
    <div class="project-feature__body">
      <div class="project-feature__image">
        <img src="/images/project-mea-fabrication.png" alt="Wafer-scale thin film microelectrode arrays with microscopy-inspired immune response imagery">
      </div>
      <div class="project-feature__story">
        <p>After modeling the design, the next step was to build it. I fabricated 32 geometry-based thin-film MEAs through wafer preparation, thin-film deposition, photolithography, plasma and wet etching, PECVD passivation, and thermal curing.</p>
        <p>The work connected cleanroom process development with biological validation. Devices reached 90% yield across wafers, then moved into a chronic 16-week rat implantation study where GFAP, Iba1, and NeuN histology helped quantify geometry-dependent immune response.</p>
        <p class="project-feature__note">Focus: thin-film fabrication, a-SiC, polyimide, metal deposition, histology, chronic neural implants.</p>
      </div>
    </div>
  </article>

  <article class="project-feature">
    <h2>Multi-Output Neural Network for Predicting Neuroinflammation</h2>
    <div class="project-feature__body">
      <div class="project-feature__image">
        <img src="/images/project-neural-network.png" alt="Neural network connecting implant geometry and strain fields to multiple biomarker outputs">
      </div>
      <div class="project-feature__story">
        <p>Instead of fabricating and implanting every possible design, this project asks whether computation can narrow the search. I trained a feedforward neural network to connect MEA geometry and FEM-derived strain features with biological outcomes.</p>
        <p>The model predicts GFAP, CD68, Iba1, and NeuN loss as multiple outputs, creating a faster path for screening neural interface designs in silico. I validated the workflow using 5-fold cross-validation and evaluated performance with R-squared and RMSE metrics.</p>
        <p class="project-feature__note">Focus: neural networks, FEM-derived features, neuroinflammation prediction, model validation.</p>
      </div>
    </div>
  </article>

  <article class="project-feature">
    <h2>Investigating Artificial Nanocomposite Fibers to Mimic Human Hair Nanotribology</h2>
    <div class="project-feature__body">
      <div class="project-feature__image">
        <img src="/images/project-nanotribology.png" alt="Atomic force microscope probe scanning natural and synthetic nanocomposite fibers">
      </div>
      <div class="project-feature__story">
        <p>Human hair has a complex surface story: roughness, friction, adhesion, and nanoscale texture all shape how it behaves. In this project, I used AFM-based surface characterization to compare natural hair with synthetic and PVC-coated composite fibers.</p>
        <p>I optimized AFM scanning parameters such as set-point force and scan velocity, then analyzed force-distance curves in MATLAB. The work identified PVC composites with tribological behavior comparable to natural curly hair, helping bridge synthetic material design and biological surface mechanics.</p>
        <p class="project-feature__note">Focus: AFM, adhesion force, friction, roughness, MATLAB, nanocomposite fibers.</p>
      </div>
    </div>
  </article>
</section>
