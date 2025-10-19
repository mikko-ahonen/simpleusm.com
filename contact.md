---
layout: page
title: Contact
permalink: /contact/
---

## Get in Touch

Whether you have questions about Simple USM, want to discuss USM coaching for your organization, or are interested in consulting services, please reach out. Mikko is here to help you understand and deploy Unified Service Management.

<div class="row mt-5">
  <div class="col-lg-8 mx-auto">
    <form class="needs-validation" novalidate action="mailto:{{ site.email }}" method="POST">
      <div class="mb-3">
        <label for="name" class="form-label">Name *</label>
        <input type="text" class="form-control" id="name" name="name" required>
        <div class="invalid-feedback">
          Please provide your name.
        </div>
      </div>

      <div class="mb-3">
        <label for="email" class="form-label">Email Address *</label>
        <input type="email" class="form-control" id="email" name="email" required>
        <div class="invalid-feedback">
          Please provide a valid email address.
        </div>
      </div>

      <div class="mb-3">
        <label for="subject" class="form-label">Subject *</label>
        <select class="form-select" id="subject" name="subject" required>
          <option value="">Choose...</option>
          <option value="usm-coaching">USM Coaching</option>
          <option value="book-question">Question About Simple USM</option>
          <option value="usm-deployment">USM Deployment Support</option>
          <option value="consulting">Consulting Services (Jauzo Oy)</option>
          <option value="training">USM Training</option>
          <option value="general">General Inquiry</option>
          <option value="other">Other</option>
        </select>
        <div class="invalid-feedback">
          Please select a subject.
        </div>
      </div>

      <div class="mb-3">
        <label for="message" class="form-label">Message *</label>
        <textarea class="form-control" id="message" name="message" rows="6" required></textarea>
        <div class="invalid-feedback">
          Please provide a message.
        </div>
      </div>

      <div class="mb-3 form-check">
        <input type="checkbox" class="form-check-input" id="newsletter" name="newsletter">
        <label class="form-check-label" for="newsletter">
          Keep me informed about USM resources and updates
        </label>
      </div>

      <button type="submit" class="btn btn-primary btn-lg">
        <i class="bi bi-send me-2"></i>Send Message
      </button>
    </form>
  </div>
</div>

<div class="row mt-5">
  <div class="col-lg-10 mx-auto">
    <hr class="my-5">

    <div class="row g-4">
      <div class="col-md-4 text-center">
        <div class="card h-100 border-0">
          <div class="card-body">
            <i class="bi bi-envelope-fill text-primary" style="font-size: 2.5rem;"></i>
            <h4 class="mt-3">Email</h4>
            <p class="text-muted">Direct contact</p>
            <a href="mailto:{{ site.email }}">{{ site.email }}</a>
          </div>
        </div>
      </div>

      <div class="col-md-4 text-center">
        <div class="card h-100 border-0">
          <div class="card-body">
            <i class="bi bi-globe text-primary" style="font-size: 2.5rem;"></i>
            <h4 class="mt-3">USM Coach</h4>
            <p class="text-muted">Main website</p>
            <a href="http://usm.coach" target="_blank">usm.coach</a>
          </div>
        </div>
      </div>

      <div class="col-md-4 text-center">
        <div class="card h-100 border-0">
          <div class="card-body">
            <i class="bi bi-linkedin text-primary" style="font-size: 2.5rem;"></i>
            <h4 class="mt-3">LinkedIn</h4>
            <p class="text-muted">Connect professionally</p>
            <a href="https://www.linkedin.com/in/mikko-ahonen-8893b/" target="_blank">Mikko Ahonen</a>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>

<div class="alert alert-info mt-5">
  <h5 class="alert-heading"><i class="bi bi-info-circle me-2"></i>Response Time</h5>
  <p class="mb-0">Mikko typically responds to inquiries within 1-2 business days. For urgent USM coaching needs, please mention this in your message.</p>
</div>

### Frequently Asked Questions

<div class="accordion mt-4" id="faqAccordion">
  <div class="accordion-item">
    <h2 class="accordion-header" id="headingOne">
      <button class="accordion-button" type="button" data-bs-toggle="collapse" data-bs-target="#collapseOne" aria-expanded="true" aria-controls="collapseOne">
        How do I get the Simple USM e-book?
      </button>
    </h2>
    <div id="collapseOne" class="accordion-collapse collapse show" aria-labelledby="headingOne" data-bs-parent="#faqAccordion">
      <div class="accordion-body">
        The Simple USM e-book is available as a free PDF download. Visit the <a href="/">home page</a> and click "Download E-Book" or download it directly <a href="/assets/pdf/Simple_USM_v6.pdf" target="_blank">here</a>.
      </div>
    </div>
  </div>

  <div class="accordion-item">
    <h2 class="accordion-header" id="headingTwo">
      <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapseTwo" aria-expanded="false" aria-controls="collapseTwo">
        What is USM coaching?
      </button>
    </h2>
    <div id="collapseTwo" class="accordion-collapse collapse" aria-labelledby="headingTwo" data-bs-parent="#faqAccordion">
      <div class="accordion-body">
        USM coaching guides your organization in learning how to deploy USM. Unlike consulting where work is done for you, coaching focuses on making your organization self-sufficient. Coaches provide project support tools, templates, and expert guidance throughout deployment.
      </div>
    </div>
  </div>

  <div class="accordion-item">
    <h2 class="accordion-header" id="headingThree">
      <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapseThree" aria-expanded="false" aria-controls="collapseThree">
        How long does USM deployment take?
      </button>
    </h2>
    <div id="collapseThree" class="accordion-collapse collapse" aria-labelledby="headingThree" data-bs-parent="#faqAccordion">
      <div class="accordion-body">
        Deployment time varies based on your organization's size, complexity, and goals. A typical engagement starts with understanding your current state and defining workflows, which can take a few weeks to several months. Contact us to discuss your specific situation.
      </div>
    </div>
  </div>

  <div class="accordion-item">
    <h2 class="accordion-header" id="headingFour">
      <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapseFour" aria-expanded="false" aria-controls="collapseFour">
        Can USM work with our existing frameworks?
      </button>
    </h2>
    <div id="collapseFour" class="accordion-collapse collapse" aria-labelledby="headingFour" data-bs-parent="#faqAccordion">
      <div class="accordion-body">
        Yes! USM is complementary to frameworks like ITIL, ISO 20000-1, and COBIT. It's principle-based rather than prescriptive, making it ideal for achieving compliance and certifications. Auditors can cross-reference framework requirements to USM workflows and activities.
      </div>
    </div>
  </div>

  <div class="accordion-item">
    <h2 class="accordion-header" id="headingFive">
      <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapseFive" aria-expanded="false" aria-controls="collapseFive">
        What consulting services does Jauzo Oy provide?
      </button>
    </h2>
    <div id="collapseFive" class="accordion-collapse collapse" aria-labelledby="headingFive" data-bs-parent="#faqAccordion">
      <div class="accordion-body">
        Jauzo Oy provides technical development and coordination consulting, including architecture, product ownership, and technology leadership. Visit <a href="http://jauzo.com" target="_blank">jauzo.com</a> or contact us using the form above for more information.
      </div>
    </div>
  </div>
</div>
