---
theme: jekyll-theme-primer
layout: sub-page
title: Learning & Capacity Building
permalink: /learning_capacity/
---

<section class="bg-gray-light py-5 fade-in-center">
  <div class="container-lg p-responsive text-center">
    <h2 class="alt-h2 mb-4">Learning & Capacity Building</h2>
    <p class="lead">This section is under development. E-learning and training resources for PathCalc will be available soon.</p>
    <a href="{{ site.baseurl }}/coming_soon.html" class="btn btn-outline-primary sky-blue-accent mt-3">Coming Soon →</a>
  </div>
</section>

<style>
/* Fade-in animation for main title */
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

/* Animate-in effects for all elements */
.animate-in {
  opacity: 0;
  transform: translateY(30px);
  animation: animateIn 0.8s ease-out forwards;
  animation-delay: var(--animation-delay, 0s);
}

/* Staggered animation delays */
.animate-in:nth-child(1) { --animation-delay: 0.1s; }
.animate-in:nth-child(2) { --animation-delay: 0.2s; }
.animate-in:nth-child(3) { --animation-delay: 0.3s; }
.animate-in:nth-child(4) { --animation-delay: 0.4s; }
.animate-in:nth-child(5) { --animation-delay: 0.5s; }
.animate-in:nth-child(6) { --animation-delay: 0.6s; }
.animate-in:nth-child(7) { --animation-delay: 0.7s; }
.animate-in:nth-child(8) { --animation-delay: 0.8s; }
.animate-in:nth-child(9) { --animation-delay: 0.9s; }
.animate-in:nth-child(10) { --animation-delay: 1.0s; }

/* Column animations with staggered delays for 3-column layout */
.col-md-4.float-left.animate-in:nth-child(1) { animation-delay: 0.1s; }
.col-md-4.float-left.animate-in:nth-child(2) { animation-delay: 0.2s; }
.col-md-4.float-left.animate-in:nth-child(3) { animation-delay: 0.3s; }

/* Column hover effects */
.col-md-4.float-left {
  transition: all 0.3s ease;
  display: flex;
  flex-direction: column;
  height: 100%;
}

.col-md-4.float-left:hover {
  transform: translateY(-4px);
}

/* Standardize column height and content distribution */
.col-md-4.float-left > h3 {
  flex-shrink: 0;
  min-height: 5rem;
  display: flex;
  align-items: center;
  justify-content: center;
  text-align: center;
  margin-bottom: 1rem;
  line-height: 1.3;
}

.col-md-4.float-left > p:first-of-type {
  flex-shrink: 0;
  text-align: center;
  margin-bottom: 1rem;
}

/* Standardized image container */
.col-md-4 img {
  width: 100%;
  height: 220px;
  object-fit: cover;
  object-position: center;
  border-radius: 8px;
  transition: transform 0.3s ease;
}

.col-md-4 img:hover {
  transform: scale(1.02);
}

/* Text content area - flexible height */
.col-md-4.float-left > p.text-gray {
  flex: 1;
  margin-bottom: 1.5rem;
  line-height: 1.5;
}

/* Details section at bottom - aligned */
.col-md-4.float-left > details {
  margin-top: auto;
  align-self: flex-start;
}

/* Button alignment */
.col-md-4.float-left > details > summary {
  margin: 0;
}

/* List item animations */
li.animate-in:nth-child(1) { animation-delay: 0.1s; }
li.animate-in:nth-child(2) { animation-delay: 0.2s; }
li.animate-in:nth-child(3) { animation-delay: 0.3s; }
li.animate-in:nth-child(4) { animation-delay: 0.4s; }
li.animate-in:nth-child(5) { animation-delay: 0.5s; }
li.animate-in:nth-child(6) { animation-delay: 0.6s; }
li.animate-in:nth-child(7) { animation-delay: 0.7s; }
li.animate-in:nth-child(8) { animation-delay: 0.8s; }
li.animate-in:nth-child(9) { animation-delay: 0.9s; }

@keyframes animateIn {
  from {
    opacity: 0;
    transform: translateY(30px);
  }
  to {
    opacity: 1;
    transform: translateY(0);
  }
}

/* Hover effects for interactive elements */
.animate-in:hover {
  transform: translateY(-2px);
  transition: transform 0.3s ease;
}

/* Enhanced container animations */
.container .animate-in {
  animation-delay: 0.3s;
}

/* Button hover animations */
.btn.animate-in:hover {
  transform: translateY(-2px);
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.15);
  transition: all 0.3s ease;
}

/* Image animations */
img.animate-in:hover {
  transform: scale(1.05);
  transition: transform 0.3s ease;
}

.toggle-arrow::after {
  content: '↓';
  display: inline-block;
  margin-left: 6px;
  transition: transform 0.3s ease;
}
details[open] .toggle-arrow::after {
  transform: rotate(180deg);
}
</style>