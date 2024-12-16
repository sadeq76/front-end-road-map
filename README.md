# **Frontend Roadmap**

**How to Learn Frontend: Zero to Hero**

## License

This project is licensed under the [Creative Commons Attribution-NoDerivatives 4.0 International License](https://creativecommons.org/licenses/by-nd/4.0/).

---

## **Introduction**

Start with understanding the fundamentals of the web and how it works.

### Key Concepts:

- **How to search**: Learn how to find information on the web.
- **Client and Server**: Explore the relationship between the browser and server.
- **Uniform Resource Locators**: A URL is another word for a web address.
- **DNS, IP, Port**: Understand addressing and name resolution.
- **HTTP**: Learn how data is transferred between client and server.
- **TCP/IP**: Discover the protocols governing communication.
- **Hosting**: Learn about deploying websites to the internet.
- **Browsers**: Understand browser engines and rendering processes.
- **Network and Internet**: Grasp how the web connects users globally.

---

## **Learn HTML**

The foundation of web development. Focus on structuring content.

### **Basics**

- **Introduction**: Basics of HTML and its purpose.
- **History**: Evolution of HTML.
- **Syntax**: Learn HTML structure and nesting rules.
- **Tags and Elements**: Core building blocks.
- **Block and inline elements**: The two most common display values
- **Empty Tags**: Tags without closing (e.g., `<img>`).
- **Attributes**: Add metadata and properties to elements.
- **Comments**: Document your code for clarity.

### **Editors & Tools**

- Popular editors: VS Code, Sublime Text.
- Extensions: Emmet, Auto Rename Tag, Live Server, Prettier.

### **Global & Data Attributes**

- **Global Attributes**: Apply universally (e.g., `class`, `id`).
- **Data Attributes**: Custom attributes for storing data (`data-*`).

### **HTML Elements**

- **Document Structure**: `<doctype>`, `<html>`, `<head>`, `<body>`.
- **Content Sectioning**: `<header>`, `<footer>`, `<main>`, `<section>`, `<article>`.
- **Text Content**: Use semantic tags like `<h1>`, `<p>`, `<strong>`, `<code>`.
- **Linking**: Anchor (`<a>`) and navigation elements.
- **Lists**: Ordered, unordered, and description lists.
- **Tables**: Structure tabular data with `<table>`, `<thead>`, `<tbody>`.
- **Multimedia**: Add `<audio>`, `<video>`, `<picture>` tags.
- **Forms and Validations**: Use `<form>`, `<input>`, `<select>`, and built-in validation.
- **Interactive Tags**: `<dialog>`, `<details>`, `<summary>`.
- **Metadata**: `<style>`, `<meta>`, `<link>`.
- **Math**: MathML (Mathematical Markup Language) is a standard for displaying mathematical notations on the web.
- **Deprecated Tags**: elements that are no longer recommended for use because they’ve been replaced by more modern and efficient alternatives.

### **More Concepts**

- **File paths**: Absolute vs. relative paths.
- **HTML Entities, Symbols, and Emojis**: Reserved characters in HTML.
- **Responsive Design**:
  - **Viewport Meta Tag**: Ensure proper scaling.
  - **Responsive Images**: Use `<picture>` and `<source>`.

### **Advanced HTML**

- **Template and slots**: Templates and slots are powerful tools in HTML, especially useful when working with reusable components and custom elements in modern web development.
- **Best Practices**: Follow best practices for HTML structure and semantics.
- **Performance**: Minify HTML, lazy load images, reduce DOM complexity.
- **Security**: Avoid inline styles/scripts, sanitize inputs.

### **Related Topics** (Optional)

- **HTML Preprocessor**: tool that extends the functionality of standard HTML by allowing developers to use advanced features such as variables, loops, conditionals, and templates to simplify and speed up the development process (Not really important just know they exist).
- **Web APIs**: set of interfaces provided by browsers that allow developers to interact with and manipulate various elements of the browser environment, the Document Object Model (DOM), and external data (JavaScript required).
- **Regular Expressions (RegEx)**: powerful tool used for searching, matching, and manipulating strings based on specific patterns.

### **Practice**

- [Check out my HTML Exercises](https://github.com/sadeq76/html-exercises)

### **Test Your Knowledge**

<!-- Add questions and answers -->

---

## **Learn CSS**

Style your HTML effectively with cascading stylesheets.

### **CSS Basics**

- **History**: Learn the evolution of CSS.
- **Syntax**: Rules, declarations, and blocks.
- **Comments**: Use `/* comments */` for clarity.
- **Defining Styles**: Inline, internal, and external styles.
- **Cascade and Inheritance**: Understanding how styles are applied.

### **Editors & Tools**

- **Popular Editors**: VS Code, Sublime Text, Atom.
- **Extensions**: Emmet, Live Sass Compiler, Prettier.

### **Selectors**

- **Simple**: Target elements, classes, IDs, and grouping selectors.
- **Combinator**: Relationships between elements.
- **Pseudo-classes**: Target states (e.g., `:hover`).
- **Pseudo-elements**: Style parts of elements (e.g., `::before`).
- **Attribute Selectors**: Target elements with specific attributes.

### **Units**

- **Absolute**: Fixed sizes (e.g., `px`, `cm`).
- **Relative**: Relative to parent or viewport (e.g., `em`, `rem`, `%`).

### **CSS Properties**

- **Box Model**: Manage dimensions, margins, borders, and padding.
- **Colors**: Use RGB, HEX, HSL, and named colors.
- **Typography**: Font styles, weights, and alignments.
- **Backgrounds**: Images, gradients, and patterns.

### **Positioning & Layout**

- **Positioning**: Static, relative, absolute, fixed, and sticky.
- **Flexbox**: Flexible alignment for layouts.
- **Grid**: Advanced two-dimensional layouts.
- **Z-Index**: Stacking context for overlapping elements.

### **More concepts**

- **At rules**: @import, @media, @keyframes, @font-face, @supports ...
- **Functions**: calc(), var(), url(), attr(), ...
- **CSS Variables**: Reuse values across styles.

### **Image-Related Properties**

- **Background Image Properties**: Control the display of images as backgrounds for elements
- **Object Fit and Object Position**: Control how an image fits inside its container and its alignment within that container.
- **Aspect-Ratio**: Set the width-to-height ratio for elements, ensuring images maintain their natural proportions.
- **Clip Path**: Define a clipping path to restrict the visible area of an element, creating custom shapes.
- **Image Rendering**: Control how images are scaled and rendered, especially useful for pixelated images or maintaining sharpness.
- **Filters**: Apply visual effects like blur, grayscale, or contrast to modify an image's appearance.
- **Masks**: Use masks to control the visibility and transparency of an image, allowing for complex visual effects.

### **Browser Compatibility**

- **Browser Support**: Check compatibility for different browsers.
- **Vendor Prefixes**: Add prefixes for experimental features.
- **Feature Detection**: Check for browser features.
- **Polyfills**: Add support for older browsers.

### **Specificity & Cascade**

- **Cascade & Inheritance**: Understand how styles are applied.
- **Calculating Specificity**: Specificity is calculated with a four-part value: (a, b, c, d).
- **Specificity Order**: When two rules have the same specificity, the rule that appears later in the CSS file is applied. So, order matters.
- **Using !important**: break the natural cascading flow.

### **Responsive Design**

- **Media Queries**: Adapt styles based on device size.
- **Fluid Layouts**: Use percentages or `vw/vh`.

### **Transitions & Animations**

- **Transitions**: Smooth changes on state changes.
- **Animations**: Keyframes for complex animations.
- **Transforms**: Transform elements with 2D and 3D effects.
- **CSS Animations vs JavaScript**: CSS animations are smoother, but JavaScript can be more flexible.
- **Performance and Browser support**: Test and optimize for performance.

### **Preprocessors**

- **What is a preprocessor?**: A tool that enhances CSS by adding features like variables, nesting, and mixins.
- **Benefits**: Helps reduce repetitive code and improves maintainability.
- **Popular preprocessors**: Sass, Less, Stylus.
- **Key features**: Variables, nesting, mixins, and functions.
- **Compilation**: Preprocessor code is converted into regular CSS.
- Learn more about it later.

### **Libraries**

- **Utility-First libraries**: Tailwind CSS-style utilities.
- **Component Libraries**: Pre-built components like Material UI.

### **Architecture**

- **Benefits**: Consistency, maintainability, and scalability.
- **Methodologies**: BEM, SMACSS, OOCSS, ITCSS, RSCSS, Functional CSS, and SUIT CSS.

### **Performance and security**

- Minify CSS.
- Render Tree Construction
- Selector Efficiency
- Animation Performance
- Reduce unused styles.
- Use critical CSS loading.
- CSS Injection
- Clickjacking
- and more.

### **Advanced Topics**

- **Shadow DOM**: Scoped styles for components.
- **CSS Houdini**: Access the browser's rendering engine.

### **Practice**

- **Tools**: Use Lighthouse, DevTools, W3Schools, or SoloLearn.
- **Exams**: Test your skills and earn certifications.
- **Real-World Projects**: Build websites and applications to solidify your knowledge.

## **JavaScript**

## **Accessibility**

- **Benefits**: Enhances website usability for all users, improves SEO, and ensures compliance with accessibility standards.
- **Problems and Disability Types**: Addresses challenges for various disabilities, including visual, auditory, motor, cognitive, and age-related issues, as well as low-end devices and different screen sizes.
- **Semantic HTML**: Use semantic HTML tags for better accessibility.
- **Keyboard Navigation**: Ensure keyboard accessibility.
- **ARIA attributes and roles**: Use ARIA attributes for accessibility.
- **Responsive Design**: Ensure responsive design for all devices.
- **Guidelines and Checklists**: Use accessibility guidelines.
- **Accessibility Testing and Debugging Tools**: Write tests, extensions, and keyboard focus tests with DevTools.
- **Progressive enhancement**: Turn off JavaScript, provide accessible baseline markup, add ARIA with scripting, and prioritize core user flows
- **References**
  - [MDN Accessibility](https://developer.mozilla.org/en-US/docs/Web/Accessibility)
  - [A11YProject](https://www.a11yproject.com/)
  - [The World Wide Web Consortium Accessibility Guidelines](https://www.w3.org/WAI/standards-guidelines/wcag/)

## **Performance**

## **Search Engine Optimization (SEO)**

- **Benefits**: Benefits: Improves website visibility, search engine ranking, and user experience by making it easier for search engines to crawl, index, and rank content.
- **On-Page SEO**: Optimize HTML structure, meta tags, and content.

  - Optimize HTML Structure: Use semantic HTML for better indexing.
  - Meta Tags: Optimize title tags, meta descriptions, and header tags for relevant keywords.
  - Content: Create high-quality, original content that matches user intent and answers their queries.
  - Descriptive URLs: Group similar content in directories and use keyword-rich, short URLs.
  - Non text content and Alternatives: Add descriptive alt text to images to help search engines understand their content.
  - Performance and Security: Ensure fast loading times and secure connections.
  - Accessibility: Ensure your website is accessible to all users and devices.
  - XML Sitemap
  - Robots.txt
  - Canonical Tags
  - Structured Data (Schema Markup)
  - Crawlability and Indexing
  - Fixing Broken Links and Redirects
  - AMP (Accelerated Mobile Pages)
  - International SEO
  - Test tools

- Additional SEO Practices

1. Microdata and RDFa
   Enhance content with microdata and RDFa markup for better visibility in search engines, helping search engines better interpret page content.
1. SEO Best Practices
   Use semantic HTML to improve content structure and search engine understanding.
   Optimize title tags, meta descriptions, and alt tags for better search rankings.
   Keep content relevant and keyword-optimized without keyword stuffing.
   Technical SEO Checklist for Frontend Development
1. HTML Structure
   Heading Hierarchy: Proper use of <h1> to <h6> tags to establish a clear content structure.
   Semantic Elements: Utilize elements like <header>, <nav>, <section>, <article>, and <footer> for improved accessibility and SEO.
1. Meta Tags
Canonical Tags: Prevent duplicate content by defining canonical URLs.
Other Meta Tags:
<meta name="description" content="..."> for search snippets.
Open Graph and Twitter Cards for social sharing.
Robots meta tag (noindex, nofollow when needed).
<meta charset="UTF-8"> and <meta name="viewport" content="width=device-width, initial-scale=1.0">.
1. Accessibility
   Responsive Design: Use media queries and fluid layouts to adapt to different screen sizes.
   Guidelines: Adhere to WCAG (Web Content Accessibility Guidelines) to support all users.
   Key Features:
   ARIA roles and labels.
   Focus states and keyboard navigability.
1. Performance
   Core Web Vitals: Optimize:
   Largest Contentful Paint (LCP).
   First Input Delay (FID).
   Cumulative Layout Shift (CLS).
   Other Optimizations:
   Image formats (WebP/AVIF).
   Lazy loading for non-critical assets.
   Minify CSS, JS, and HTML.
   Prefetch, preload, and critical CSS.
1. URLs
   Clean, descriptive, and human-readable URLs.
   Avoid query string overuse unless necessary.
1. Multi-language Support
   Lang Attribute: Set <html lang="en"> for language identification.
   Dir Attribute: Use dir="rtl" for right-to-left languages like Arabic or Persian.
   Implement hreflang tags for multi-language support.
1. Rendering Methods (JavaScript)
   Ensure crawlability of dynamic content:
   Use Server-Side Rendering (SSR) or Static Site Generation (SSG) for better performance.
   Implement hydration efficiently for client-side rendered apps.
   Lazy load non-critical JavaScript.
1. SEO-related Files
   Robots.txt: Manage crawl directives and allow/disallow specific paths.
   Sitemap.xml: Provide a clear path for crawlers to discover pages.
1. Testing Tools and Extra Tools
   Testing Tools:
   Lighthouse for auditing performance and accessibility.
   Google Search Console for crawl diagnostics.
   Wave or Axe for accessibility testing.
   Extra Tools:
   Schema Markup Generators for structured data.
   WebPageTest.org for granular performance testing.
1. Additional Technical Considerations
   Pagination: Implement proper pagination using rel="next" and rel="prev".
   Content Delivery Network (CDN): Leverage a CDN to reduce latency and serve cached content.
   404 and Redirect Handling:
   Serve custom 404 pages with helpful navigation.
   Use 301 redirects for moved or outdated pages.
   AMP (Optional): Consider Accelerated Mobile Pages for mobile optimization.
   Security:
   Use HTTPS across the site.
   Add security-related headers (Content-Security-Policy, X-Frame-Options).

- **Off-Page SEO**: Build quality backlinks, social media presence.
