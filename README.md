# DDLSim-Lab Project Website

<p align="center">
  <strong>Official Website & Public Research Interface</strong>
</p>

<p align="center">
  <a href="https://ktruby-oss.github.io/DDLSIM/">
    Live Website
  </a>
  ·
  <a href="https://github.com/ktruby-oss/DDLSIM">
    Website Repository
  </a>
  ·
  <a href="https://github.com/ktruby-oss/DDLSim-Lab">
    Main Research Repository
  </a>
</p>

---

## About

This repository contains the official public-facing website for **DDLSim-Lab**.

The website is designed to present the project, research directions, documentation, experiments, technical information, project updates, and public resources through a responsive web interface.

This repository is specifically dedicated to the **website and its public-facing content**.

It is separate from the main DDLSim-Lab research and simulation repository.

---

## Live Website

**DDLSim-Lab Website**

https://ktruby-oss.github.io/DDLSIM/

The website provides access to:

- Project information
- Research and experiments
- Documentation
- Quick-start information
- Research updates
- Technical articles
- Public project resources
- Contact information
- Collaboration information

---

## Repository Separation

DDLSim-Lab is organized into two separate repositories.

### Website Repository

This repository:

```text
https://github.com/ktruby-oss/DDLSIM

contains the public website.

Main Research Repository

The core DDLSim-Lab research and simulation project is maintained separately:

https://github.com/ktruby-oss/DDLSim-Lab

The separation keeps the public website and the research implementation independently maintainable.


---

What This Repository Contains

This repository may contain website-related files such as:

DDLSIM/
│
├── index.html
├── about.html
├── research.html
├── documentation.html
├── blog.html
├── contact.html
│
├── static/
│   ├── css/
│   │   ├── bulma.min.css
│   │   └── fontawesome.all.min.css
│   │
│   └── js/
│       └── fontawesome.all.min.js
│
├── images/
│
├── assets/
│
├── README.md
│
└── LICENSE

The exact structure may evolve as the website develops.


---

Website Sections

Home

The main landing page for the project.

It provides an overview of DDLSim-Lab and links to the project's public resources.

About

Provides project background, research context and information about the project.

Research

Presents research directions, experimental capabilities and areas related to distributed deep learning systems.

Documentation

Provides documentation, quick-start instructions, configuration examples and citation information.

Blog

Contains public project updates, technical articles, research notes and other website publications.

Contact

Provides public contact information and channels for project-related communication.


---

Website Technology

The website is built using lightweight web technologies.

HTML5

HTML5 provides the structure and semantic content of the website.

The project uses separate HTML pages for the major public sections of the website.

Examples include:

index.html
about.html
research.html
documentation.html
blog.html
contact.html


---

CSS3

Custom CSS is used to provide the visual identity of the website.

The styles include:

Responsive layouts

Dark navigation

Research-oriented hero sections

Cards

Buttons

Mobile navigation

Responsive typography

Hover states

Focus states

Code blocks

Research sections

Footer layouts

Mobile interfaces

Accessibility improvements

Reduced-motion support



---

Bulma

The website uses the Bulma CSS framework.

Bulma provides responsive layout utilities and reusable interface components.

The local Bulma stylesheet is located under:

static/css/bulma.min.css


---

Icons & Visual Identity

Icons are an important part of the DDLSim-Lab website interface.

The website uses Font Awesome rather than decorative emoji characters for its interface icons.

This provides a consistent visual language across the website.

Font Awesome

The local Font Awesome resources are stored under:

static/css/fontawesome.all.min.css
static/js/fontawesome.all.min.js

The website uses both:

Font Awesome solid icons

Font Awesome brand icons


Examples include:

<i class="fas fa-microchip"></i>
<i class="fas fa-flask"></i>
<i class="fas fa-book"></i>
<i class="fas fa-envelope"></i>
<i class="fas fa-code"></i>
<i class="fas fa-network-wired"></i>
<i class="fas fa-shield-alt"></i>
<i class="fab fa-github"></i>
<i class="fab fa-osi"></i>

These icons are used for navigation, research sections, documentation, GitHub links, contact information and other interface elements.


---

Website Logo / Brand Mark

The website currently uses a lightweight web-based brand mark built from the DDLSim-Lab visual identity.

The primary symbol represents computing and distributed systems and is used throughout:

Navigation

Footer

Website branding

Mobile navigation

Project presentation sections


The current interface uses:

<i class="fas fa-microchip"></i>

as the primary brand symbol.

This avoids requiring a large image file for the basic website logo while keeping the interface fast and scalable.

If a dedicated official SVG logo is introduced in the future, it can be placed in the website assets directory and reused throughout the site.


---

Website Assets

Website assets may include:

images/
assets/
static/

These directories can contain public-facing resources used by the website.

Examples include:

Logos

SVG graphics

Research illustrations

Website images

Icons

Decorative graphics

UI assets


Assets should be optimized for web delivery whenever possible.

Large unnecessary files should be avoided.


---

Images

The website may use images for:

Hero sections

Research presentation

Technical illustrations

Project pages

Blog articles

Public documentation


Images should be appropriate for public distribution and should respect their respective licenses.

When using external imagery, contributors should verify that the image can legally be used and should preserve appropriate attribution or licensing information where required.


---

Typography

The website uses modern web typography for readability and a technical research-oriented appearance.

The primary interface font is:

Inter

The technical/code-oriented font is:

JetBrains Mono

These fonts are used for:

Navigation

Headings

Research descriptions

Code blocks

Technical labels

Project metadata



---

Responsive Design

The website is designed to work across different screen sizes.

Supported layouts include:

Desktop

Laptop

Tablet

Mobile

Small mobile screens


The mobile interface includes a dedicated navigation drawer rather than relying solely on a desktop navigation layout.


---

Mobile Navigation

The website includes a responsive mobile navigation system.

On smaller screens, the navigation becomes a side drawer.

The mobile navigation includes:

Slide-in navigation

Background overlay

Active page indicator

Navigation icons

GitHub link

Escape-key support

Automatic closing after navigation

Scroll locking while the menu is open


This behavior is implemented with HTML, CSS and JavaScript.


---

Accessibility

Accessibility is considered throughout the website.

The interface includes:

Semantic HTML

Navigation labels

ARIA attributes

Keyboard navigation

Visible focus states

Accessible buttons

Reduced-motion support

Readable color contrast

Responsive text

Alternative text where appropriate


New components should maintain these practices.


---

Website Content

The website can be updated with public-facing project material.

Examples include:

Research summaries

Technical explanations

Tutorials

Documentation updates

Project announcements

Research notes

Blog posts

Release information

Website improvements

Navigation updates

Public project information


Content should be accurate and appropriate for a public research website.

Do not add unsupported claims about:

Universities

Research laboratories

Institutional partnerships

Researchers

Publications

Experimental results

Funding

Affiliations

Project contributors


unless the relevant information can be verified from an appropriate project source.


---

Contributing to the Website

Contributions to this website repository are welcome.

The scope of contributions is the website and its public-facing content.

You may contribute improvements such as:

HTML fixes

CSS improvements

JavaScript improvements

Responsive design improvements

Mobile navigation improvements

Accessibility improvements

UI/UX improvements

Website icons

Logo improvements

Website images

Documentation presentation

Research page presentation

Blog updates

Tutorials

Website articles

Broken-link fixes

Navigation improvements

Performance improvements

Website content corrections



---

Website-Only Contributions

Examples of acceptable contributions include:

Improve the navigation
Fix a mobile layout
Improve the footer
Add a new research webpage
Improve an existing HTML page
Add a website article
Update documentation presentation
Add a website icon
Improve the project logo
Optimize an image
Fix accessibility issues
Improve responsive behavior
Correct website text
Add a new public-facing section

These changes belong in this repository.


---

Contributions to the Main Research Project

This website repository is not the place for contributions to the DDLSim-Lab research implementation.

Do not use this repository to submit changes to:

DDLSim-Lab simulation engine
Core research software
Distributed training implementation
Fault-injection implementation
AI control systems
Machine-learning implementation
Research algorithms
Simulation infrastructure
Research experiments
Core project dependencies

For those contributions, use the main DDLSim-Lab research repository:

https://github.com/ktruby-oss/DDLSim-Lab


---

Repository Scope

Area	Website Repository	Main Research Repository

HTML	Yes	No
CSS	Yes	No
Website JavaScript	Yes	No
Website navigation	Yes	No
Website UI/UX	Yes	No
Website icons	Yes	No
Website logo	Yes	No
Website images	Yes	No
Website articles	Yes	No
Public documentation presentation	Yes	No
Research page presentation	Yes	No
Website announcements	Yes	No
Simulation engine	No	Yes
Core research implementation	No	Yes
Research algorithms	No	Yes
Simulation infrastructure	No	Yes
Research experiments	No	Yes
Core AI implementation	No	Yes
Fault-injection implementation	No	Yes



---

Pull Request Guidelines

Before opening a Pull Request, verify the following:

HTML

Pages load correctly

Navigation works

Internal links work

External links work

No duplicated attributes

No obvious HTML errors


CSS

Desktop layout works

Mobile layout works

No unnecessary overflow

Existing visual identity is preserved

New components remain consistent


JavaScript

No console errors

Mobile navigation works

Buttons work

Interactive elements remain accessible


Assets

Images load correctly

Icons load correctly

Assets are appropriately optimized

External assets have appropriate usage rights


Content

Information is accurate

No unsupported institutional claims are added

Research claims are not exaggerated

Public information is clearly written



---

Development Workflow

Clone the website repository:

git clone https://github.com/ktruby-oss/DDLSIM.git

Enter the repository:

cd DDLSIM

Create a branch:

git checkout -b improve-website

Make the required website changes.

Then review the website locally before submitting a Pull Request.


---

Local Website Preview

Because the website is primarily composed of static files, it can be previewed using a simple local HTTP server.

For example, with Python:

python -m http.server 8000

Then open:

http://localhost:8000

This is useful for checking:

Navigation

Relative links

CSS

JavaScript

Images

Mobile layouts

Documentation pages



---

Project Structure

A typical website structure is:

DDLSIM/
│
├── index.html
├── about.html
├── research.html
├── documentation.html
├── blog.html
├── contact.html
│
├── static/
│   │
│   ├── css/
│   │   ├── bulma.min.css
│   │   └── fontawesome.all.min.css
│   │
│   └── js/
│       └── fontawesome.all.min.js
│
├── images/
│
├── assets/
│
├── README.md
│
└── LICENSE

The structure may change as the website evolves.


---

Design Principles

The website follows several design principles.

Clarity

Information should be easy to understand and navigate.

Consistency

Navigation, colors, typography, icons and interaction patterns should remain consistent between pages.

Accessibility

The website should remain usable across different devices and input methods.

Performance

Images, scripts and styles should be kept reasonably lightweight.

Maintainability

Website components should remain understandable and easy to modify.

Research-Oriented Presentation

The interface should communicate the technical and research nature of DDLSim-Lab without unnecessary visual clutter.


---

Collaboration

The project welcomes people interested in improving the public website.

This includes:

Researchers

Research groups

Laboratories

Developers

Engineers

Students

Technical writers

Designers

Open-source contributors


Contributions can involve either technical website work or improvements to the public presentation of the project.


---

Project Lead

Kaitlyn Brishae Truby

Project-related contact information is available through the website:

https://ktruby-oss.github.io/DDLSIM/


---

Important Distinction

This repository is the DDLSim-Lab website repository.

It exists to maintain and improve:

Website
HTML
CSS
JavaScript
Icons
Logo
Images
Navigation
Documentation presentation
Research presentation
Blog
Public updates
Public-facing content

It should not be interpreted as permission to copy, redistribute, rehost, repackage, or independently publish the DDLSim-Lab research software.

For the research software, simulation environment and core implementation, refer to the main repository:

https://github.com/ktruby-oss/DDLSim-Lab

The applicable terms for the research software are determined by that repository and its accompanying license and documentation.


---

Links

Resource	Link

Website	https://ktruby-oss.github.io/DDLSIM/
Website Repository	https://github.com/ktruby-oss/DDLSIM
Main Research Repository	https://github.com/ktruby-oss/DDLSim-Lab



---

License

The website source and content are licensed according to the terms provided in:

LICENSE

Review the repository license before reusing or redistributing website source code, content, images or other assets.


---

<p align="center">
  <strong>DDLSim-Lab</strong><br>
  Distributed Deep Learning Systems Research
</p>
