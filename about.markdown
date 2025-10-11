---
theme: jekyll-theme-primer
layout: sub-page
title: About PathCalc
permalink: /about/
---

<section class="bg-gray-light py-5 fade-in-center">
  <div class="container-lg p-responsive">
    <h2 class="alt-h2 mb-4 text-center">About PathCalc</h2>

    <p><strong>PathCalc</strong> was developed in 2024 and is based on the MacKay Carbon Calculator framework. Users select ambition levels for each lever—representing key actions such as behaviour change or technology deployment—to generate and explore scenarios. These are derived from cost-optimised OSeMOSYS model runs, enabling interactive exploration of emissions, energy, and cost trade-offs.</p>

    <h3 class="alt-h3 mt-4">What does it do?</h3>
    <p>PathCalc is an interactive visualisation tool for exploring thousands of potential energy and emissions pathways. It uses pre-run cost-optimised scenarios from a flexible OSeMOSYS base model, allowing users to examine the impact of ambition levels on key metrics such as emissions and system costs.</p>

    <h3 class="alt-h3 mt-4">Scope of the Model</h3>
    <p>PathCalc applies a minimally constrained OSeMOSYS model, adaptable to any country context. Initial implementations are focused on Viet Nam and Laos, with plans to expand its geographical reach.</p>

    <h3 class="alt-h3 mt-4">Target Audience</h3>
    <p>PathCalc is designed for policymakers, technical experts, civil society, and the general public interested in understanding the implications of energy transition pathways. It bridges technical modelling and accessible visual storytelling to foster inclusive, data-driven dialogue.</p>

    <h3 class="alt-h3 mt-4">Outcomes</h3>
    <ul>
      <li>Explore emissions and energy impacts of policy levers.</li>
      <li>Compare alternative low-carbon strategies and ambition levels.</li>
      <li>Support evidence-based policy planning and stakeholder engagement.</li>
    </ul>

    <h3 class="alt-h3 mt-4">Contribute</h3>
    <p>Follow and contribute to PathCalc’s development through the official GitHub repository:</p>
    <ul>
      <li><a href="https://github.com/PathCalc" target="_blank">https://github.com/PathCalc</a></li>
    </ul>

  </div>
</section>

<style>
.fade-in-center {
  opacity: 0;
  transform: translateY(20px);
  animation: fadeInUp 1s ease forwards;
}
@keyframes fadeInUp {
  to {
    opacity: 1;
    transform: translateY(0);
  }
}
.alt-h3 {
  font-size: 1.15rem;
}
@media (min-width: 768px) {
  .row.justify-content-center > .col-md-4 {
    margin-bottom: 2rem;
  }
}
</style>

