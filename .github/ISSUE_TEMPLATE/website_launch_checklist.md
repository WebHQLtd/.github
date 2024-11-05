# Website Development Pre-Flight Checklist

## 1. Project Setup
- [ ] **Folder Structure**: Place the Next.js app inside a `frontend` folder.
- [ ] **Clean Slate**: Remove all default Next.js content.
- [ ] **Install Dependencies**: Install `bootstrap` and `sass`.

## 2. Code & Component Standards
- [ ] **CSS Conventions**: Use **dash format** for CSS classes (e.g., `bright-text`) and **camelCase** for IDs (e.g., `videoSection`).
- [ ] **Column Widths**: Set column widths using `md={}` instead of classnames.
- [ ] **Reusable Components**: Modularize any elements used more than once as components.
- [ ] **Layout Components**: Create a `components` folder with **Header** and **Footer** components.
- [ ] **Layout Integration**: Import Header and Footer into `layout` and place them above and below `{children}`.
- [ ] **Bootstrap-First Approach**: Use Bootstrap for styling; apply custom CSS only if necessary.

## 3. Styling & Assets
- [ ] **Global Styles**: Move `globals.css` to a `styles` folder, rename it `globals.scss`.
  - Add `@import "~bootstrap/scss/bootstrap";` at the top of `globals.scss`.
  - Update `styles` import path in layout to match the new location and name.
- [ ] **Avoid Inline Styling**: Keep styling in CSS/SCSS files, avoid inline styling.
- [ ] **Padding & Margin**: Expand Bootstrap padding and margin capacities if required.
- [ ] **Images**: Use the `<Image />` component instead of `<img>` for all images.

## 4. Metadata & SEO
- [ ] **Meta Titles & Descriptions**: Ensure each page has a unique and descriptive meta title and description.
- [ ] **Favicon**: Add a favicon for brand recognition in browser tabs.
- [ ] **Meta Image**: Include a meta image (e.g., Open Graph image) for sharing on social media, if required.

## 5. Branding & Accessibility
- [ ] **Brand Color Palette**: Set up the brand color palette for consistent styling.
- [ ] **Fonts**: Install and license brand fonts as needed.
- [ ] **Image Alt Tags**: Check all image alt tags for accessibility and SEO.
- [ ] **Accessibility Checker**: Run an accessibility check to ensure compliance.

## 6. Sitemap & Monitoring
- [ ] **XML Sitemap**: Add an XML sitemap for search engine indexing.
- [ ] **StatusCake Monitoring**: Add the site to StatusCake monitoring.
- [ ] **UseFathom Analytics**: Set up UseFathom analytics.

## 7. Contact Form
- [ ] **Contact Form ID**: Verify that the contact form ID is correct.
- [ ] **Email Testing**: Set up emails on FormSpree and test functionality.

## 8. Dependency Management
- [ ] **Update npm Packages**: Update all npm packages to the latest stable versions.
- [ ] **Remove Unused Packages**: Remove any packages that are no longer in use to optimize project size and load times.

## 9. Development & Build
- [ ] **Component Reusability**: Ensure any frequently-used elements are made into reusable components.
- [ ] **Build Check**: Run `npm run build` to confirm there are no build errors.

## 10. Testing & Quality Assurance
- **Device & Browser Testing**
  - [ ] Test on multiple devices for responsiveness.
  - [ ] Test on Google Chrome and Safari.

- **Functional Testing**
  - [ ] Ensure all links are working and navigate correctly.
  - [ ] Verify that contact forms and booking systems can receive submissions.

---

### Final Launch Checklist
- [ ] Confirm all previous steps have been completed.
- [ ] Perform a final review of layout, styles, and components for consistency.
- [ ] Launch the website and monitor for any immediate issues post-launch.
