---
theme: jekyll-theme-primer
layout: sub-page
title: Get Involved
permalink: /contact/
---

<section class="bg-gray-light py-5 fade-in-center">
  <div class="container-lg p-responsive text-center">
    <h2 class="alt-h2 mb-4">Get Involved</h2>
    <p>Follow the development and updates of PathCalc through our GitHub repository.</p>

    <a href="https://github.com/PathCalc" target="_blank" class="btn btn-primary btn-lg mb-3">Visit PathCalc on GitHub →</a>

    <div class="social-links mt-4">
      <p class="text-gray">Additional channels will be added soon.</p>
    </div>
  </div>
</section>


<style>
/* Enhanced Get Involved Page Styling */
.involvement-section {
  background: white;
  padding: 2rem;
  border-radius: 12px;
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
  transition: all 0.3s ease;
}

.involvement-section:hover {
  transform: translateY(-2px);
  box-shadow: 0 8px 25px rgba(0, 0, 0, 0.15);
}

.section-title {
  color: #0366d6;
  font-size: 1.5rem;
  font-weight: 600;
  margin-bottom: 1.5rem;
  padding-bottom: 0.5rem;
  border-bottom: 2px solid #e1e4e8;
}

.platform-benefits-title {
  color: #24292e;
  font-size: 1.2rem;
  font-weight: 500;
  margin-bottom: 2rem;
}

.benefits-container {
  display: flex;
  justify-content: center;
  align-items: stretch;
  gap: 2rem;
  flex-wrap: wrap;
  margin: 0 auto;
  max-width: 900px;
}

.benefit-card {
  background: #f8f9fa;
  padding: 2rem 1rem;
  border-radius: 8px;
  transition: all 0.3s ease;
  border: 1px solid #e1e4e8;
  flex: 1;
  min-width: 250px;
  max-width: 280px;
}

.benefit-card:hover {
  background: white;
  transform: translateY(-4px);
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
}

.benefit-card h5 {
  color: #24292e;
  font-weight: 600;
  margin-bottom: 1rem;
}

.github-container {
  display: flex;
  justify-content: center;
  margin: 0 auto;
  max-width: 600px;
}

.unified-github-card {
  background: #f8f9fa;
  padding: 2rem;
  border-radius: 8px;
  transition: all 0.3s ease;
  border: 1px solid #e1e4e8;
  border-left: 4px solid #0366d6;
  width: 100%;
}

.unified-github-card:hover {
  background: white;
  transform: translateY(-4px);
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
}

.contribution-section {
  margin-top: 2rem;
  padding-top: 2rem;
  border-top: 1px solid #e1e4e8;
}

.github-link {
  text-decoration: none;
  transition: all 0.3s ease;
  display: inline-block;
}

.github-link:hover {
  transform: scale(1.05);
  text-decoration: none;
}

.github-link svg {
  transition: all 0.3s ease;
}

.github-link:hover svg {
  transform: scale(1.1);
}

.unified-github-card h5 {
  color: #24292e;
  font-weight: 600;
  margin-bottom: 1rem;
}

.unified-github-card h6 {
  color: #0366d6;
  font-weight: 600;
  margin-top: 1rem;
  margin-bottom: 0.5rem;
}

.contribution-steps {
  list-style: none;
  padding-left: 0;
}

.contribution-steps li {
  padding: 0.5rem 0;
  padding-left: 1.5rem;
  position: relative;
}

.contribution-steps li::before {
  content: "→";
  position: absolute;
  left: 0;
  color: #0366d6;
  font-weight: bold;
}

.contribution-steps a {
  color: #0366d6;
  text-decoration: none;
}

.contribution-steps a:hover {
  text-decoration: underline;
}

.btn-primary {
  background-color: #0366d6;
  border-color: #0366d6;
  padding: 0.75rem 1.5rem;
  font-weight: 500;
  transition: all 0.3s ease;
}

.btn-primary:hover {
  background-color: #0256c7;
  border-color: #0256c7;
  transform: translateY(-2px);
  box-shadow: 0 4px 12px rgba(3, 102, 214, 0.3);
}

/* Enhanced fade-in animations */
.fade-in-center {
  opacity: 0;
  transform: translateY(30px);
  animation: fadeInUp 1.2s ease-out forwards;
}

@keyframes fadeInUp {
  to {
    opacity: 1;
    transform: translateY(0);
  }
}

/* Responsive design */
@media (max-width: 768px) {
  .involvement-section {
    padding: 1.5rem;
  }
  
  .benefits-container, .github-container {
    flex-direction: column;
    gap: 1rem;
    max-width: 100%;
  }
  
  .benefit-card, .unified-github-card {
    padding: 1.5rem 1rem;
    min-width: auto;
    max-width: 100%;
    flex: none;
  }
  
  .contribution-section {
    margin-top: 1.5rem;
    padding-top: 1.5rem;
  }
  
  .section-title {
    font-size: 1.25rem;
  }
}
</style>