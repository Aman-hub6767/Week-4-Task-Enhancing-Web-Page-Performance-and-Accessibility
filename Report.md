# PROJECT REPORT
# Week 4: Enhancing Web Page Performance and Accessibility

## 1. Introduction

This project focuses on enhancing the performance and accessibility of the ShopEase e-commerce website. The website is developed using HTML5, CSS3, and JavaScript. The objective of this task is to evaluate website quality, identify potential performance bottlenecks, and follow web accessibility best practices.

Google PageSpeed Insights was used to evaluate the website in Desktop mode.

## 2. Objectives

The main objectives of this project are:

- To evaluate website loading performance.
- To improve the structure of HTML using semantic elements.
- To make website content accessible to users with disabilities.
- To optimize CSS and reduce unnecessary code.
- To evaluate website quality using testing tools.
- To document the test results and learning outcomes.

## 3. Technologies and Tools Used

**HTML5:** Used to structure the webpage and its content.

**CSS3:** Used to style the website and create a responsive layout.

**JavaScript:** Used to provide interactive functionality.

**Google PageSpeed Insights:** Used to evaluate performance, accessibility, best practices, and SEO.

## 4. Existing Website Analysis

The ShopEase website was tested using Google PageSpeed Insights in Desktop mode. The tool provided scores for four categories: Performance, Accessibility, Best Practices, and SEO.

The initial audit results were recorded to understand the current quality of the website and identify areas that may require further improvement.

## 5. Performance Testing Results

The following scores were observed in the provided PageSpeed Insights screenshot:

| Category | Score |
|---|---:|
| Performance | 98/100 |
| Accessibility | 92/100 |
| Best Practices | 100/100 |
| SEO | 100/100 |

The website achieved a Performance score of 98, indicating strong results in the desktop performance audit. The Accessibility score was 92, while Best Practices and SEO both scored 100.

The screenshot also shows a Largest Contentful Paint (LCP) value of approximately 1.1 seconds.

These results represent the recorded Desktop audit. Mobile performance results were not included in the screenshot.

## 6. Performance Optimization

Performance optimization focuses on reducing unnecessary work and improving how efficiently a webpage loads.

The following techniques were identified as relevant optimization areas:

- Reviewing image dimensions and file sizes.
- Using suitable modern image formats where appropriate.
- Removing unnecessary or duplicate CSS rules.
- Reducing unused JavaScript and CSS where possible.
- Keeping external resources and scripts to a minimum.
- Applying appropriate resource-loading techniques.

The recorded PageSpeed Insights scores provide a baseline for evaluating website performance. Any additional optimization should be tested again to verify its effect.

## 7. Accessibility Improvements

Accessibility helps ensure that users with different abilities can understand and navigate a website.

The following accessibility practices are relevant to the ShopEase website:

### 7.1 Semantic HTML

Semantic elements such as `header`, `nav`, `main`, `section`, and `footer` help communicate the webpage structure to browsers and assistive technologies.

### 7.2 Alternative Text for Images

Meaningful `alt` attributes should be provided for informative images. Decorative images can use empty alternative text where appropriate.

### 7.3 Keyboard Navigation

Interactive elements should be usable with a keyboard. A visible focus indicator should help users identify the currently focused element.

### 7.4 Accessible Buttons and Forms

Buttons and form controls should have clear, accessible names. Search inputs should have an associated label or another appropriate accessible name.

### 7.5 Color Contrast

Text and interactive elements should maintain sufficient contrast against their backgrounds to improve readability.

### 7.6 ARIA Attributes

ARIA attributes should be added when necessary to provide accessible names, states, or relationships that native HTML does not already communicate. Native semantic HTML should be preferred whenever possible.

## 8. Testing and Evaluation

Google PageSpeed Insights was used for the recorded Desktop audit.

Additional testing can be conducted using:

- **Lighthouse:** For performance and accessibility audits.
- **WAVE:** For identifying common web accessibility issues.
- **axe DevTools:** For detecting accessibility violations.
- **Keyboard testing:** For checking navigation without a mouse.

The supplied screenshot confirms the PageSpeed Insights scores. Separate WAVE, axe, and keyboard test results were not provided and should be recorded after those tests are performed.

## 9. Challenges and Learning Outcomes

This task demonstrates the importance of evaluating website quality beyond visual appearance.

The main learning outcomes include:

- Understanding website performance scores and metrics.
- Learning the importance of semantic HTML.
- Understanding alternative text and keyboard accessibility.
- Identifying opportunities to reduce unnecessary code.
- Learning how to use website auditing tools.
- Understanding that accessibility requires testing, not only adding HTML attributes.

## 10. Future Improvements

Possible future improvements include:

- Conducting a separate mobile performance audit.
- Investigating the remaining accessibility issues identified by auditing tools.
- Optimizing large images and unnecessary resources.
- Improving keyboard navigation and focus visibility where required.
- Repeating performance and accessibility tests after changes.
- Comparing results before and after verified optimizations.

## 11. Conclusion

The ShopEase website was evaluated using Google PageSpeed Insights in Desktop mode. The recorded results were 98 for Performance, 92 for Accessibility, 100 for Best Practices, and 100 for SEO. The screenshot also reported an LCP value of approximately 1.1 seconds.

These results provide a useful baseline for understanding the website's current quality. Further accessibility testing and verified performance improvements can help make the website more efficient, usable, and inclusive.

