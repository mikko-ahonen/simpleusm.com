---
layout: page
title: Contact
permalink: /contact/
---

## Get in Touch

We'd love to hear from you! Whether you have questions about the book, want to share your USM journey, or are interested in speaking engagements and consulting services, please reach out.

<div class="row mt-5">
  <div class="col-lg-8 mx-auto">
    <form class="needs-validation" novalidate action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
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
          <option value="general">General Inquiry</option>
          <option value="book">Book Question</option>
          <option value="speaking">Speaking Engagement</option>
          <option value="consulting">Consulting Services</option>
          <option value="media">Media/Press</option>
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
          Subscribe to newsletter for updates and USM tips
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
            <p class="text-muted">For general inquiries</p>
            <a href="mailto:{{ site.email }}">{{ site.email }}</a>
          </div>
        </div>
      </div>

      <div class="col-md-4 text-center">
        <div class="card h-100 border-0">
          <div class="card-body">
            <i class="bi bi-twitter text-primary" style="font-size: 2.5rem;"></i>
            <h4 class="mt-3">Twitter</h4>
            <p class="text-muted">Follow for updates</p>
            {% if site.twitter_username %}
            <a href="https://twitter.com/{{ site.twitter_username }}" target="_blank">@{{ site.twitter_username }}</a>
            {% else %}
            <span class="text-muted">Coming soon</span>
            {% endif %}
          </div>
        </div>
      </div>

      <div class="col-md-4 text-center">
        <div class="card h-100 border-0">
          <div class="card-body">
            <i class="bi bi-github text-primary" style="font-size: 2.5rem;"></i>
            <h4 class="mt-3">GitHub</h4>
            <p class="text-muted">Resources & tools</p>
            {% if site.github_username %}
            <a href="https://github.com/{{ site.github_username }}" target="_blank">{{ site.github_username }}</a>
            {% else %}
            <span class="text-muted">Coming soon</span>
            {% endif %}
          </div>
        </div>
      </div>
    </div>
  </div>
</div>

<div class="alert alert-info mt-5">
  <h5 class="alert-heading"><i class="bi bi-info-circle me-2"></i>Response Time</h5>
  <p class="mb-0">We typically respond to inquiries within 1-2 business days. For urgent matters, please mention this in your subject line.</p>
</div>

### Frequently Asked Questions

<div class="accordion mt-4" id="faqAccordion">
  <div class="accordion-item">
    <h2 class="accordion-header" id="headingOne">
      <button class="accordion-button" type="button" data-bs-toggle="collapse" data-bs-target="#collapseOne" aria-expanded="true" aria-controls="collapseOne">
        Where can I buy the book?
      </button>
    </h2>
    <div id="collapseOne" class="accordion-collapse collapse show" aria-labelledby="headingOne" data-bs-parent="#faqAccordion">
      <div class="accordion-body">
        SimpleUSM is available on Amazon, major book retailers, and as a digital download. Visit our <a href="/">home page</a> for purchase links.
      </div>
    </div>
  </div>

  <div class="accordion-item">
    <h2 class="accordion-header" id="headingTwo">
      <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapseTwo" aria-expanded="false" aria-controls="collapseTwo">
        Is there a digital version available?
      </button>
    </h2>
    <div id="collapseTwo" class="accordion-collapse collapse" aria-labelledby="headingTwo" data-bs-parent="#faqAccordion">
      <div class="accordion-body">
        Yes! SimpleUSM is available in both paperback and digital formats (PDF, ePub, and Kindle).
      </div>
    </div>
  </div>

  <div class="accordion-item">
    <h2 class="accordion-header" id="headingThree">
      <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapseThree" aria-expanded="false" aria-controls="collapseThree">
        Do you offer bulk discounts for organizations?
      </button>
    </h2>
    <div id="collapseThree" class="accordion-collapse collapse" aria-labelledby="headingThree" data-bs-parent="#faqAccordion">
      <div class="accordion-body">
        Yes, we offer special pricing for bulk orders. Please contact us using the form above with details about your needs.
      </div>
    </div>
  </div>

  <div class="accordion-item">
    <h2 class="accordion-header" id="headingFour">
      <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapseFour" aria-expanded="false" aria-controls="collapseFour">
        Are the downloadable resources included with all versions?
      </button>
    </h2>
    <div id="collapseFour" class="accordion-collapse collapse" aria-labelledby="headingFour" data-bs-parent="#faqAccordion">
      <div class="accordion-body">
        Yes! Every purchase includes access to our online resource library with templates, tools, and additional materials.
      </div>
    </div>
  </div>
</div>
