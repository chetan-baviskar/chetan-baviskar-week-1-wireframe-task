# Week 1 Task Report: Transforming Wireframes into a Static Web Page

## 1. Introduction

The objective of this Week 1 task was to transform the supplied visual design into a functional and responsive static web page using HTML and CSS. I analyzed the reference layout first and divided it into two major areas: the task-information section on the left and the work-submission form on the right. This approach helped me maintain the visual hierarchy of the original design while keeping the code structured and reusable.

## 2. Design and Layout Decisions

I used semantic HTML5 elements such as `main`, `section`, `header`, `form`, `label`, `input`, and `textarea` to represent the content hierarchy clearly. The page uses a two-column CSS Grid layout on desktop screens. The left section contains the task title, objective heading, and numbered requirements. The right section contains the submission interface, including file upload, GitHub URL, information notice, report description, and submit button.

The design uses a clean white and light-gray background with dark navy typography. Orange is used as the primary accent for the task number, upload controls, icons, and submission button. Rounded borders, consistent spacing, and subtle shadows were implemented to reproduce the modern appearance of the reference design.

## 3. Responsive Strategy

Responsiveness was implemented with CSS media queries. On smaller screens, the two-column layout changes into a single-column layout so that the content remains readable without horizontal scrolling. Font sizes, padding, form controls, and spacing are reduced progressively for tablets and mobile devices. The file-upload control also changes from a horizontal arrangement to a vertical arrangement on small screens.

## 4. Functionality

Although this is a static webpage, I added lightweight JavaScript to improve the demonstration. The selected report filename is displayed after choosing a file, and the form checks whether the report description contains at least 200 characters before showing a successful validation message. The GitHub field uses URL validation provided by HTML.

## 5. Challenges and Solutions

The main challenge was reproducing the visual proportions of a two-panel interface while keeping it responsive. Fixed widths could cause problems on smaller devices, so I used CSS Grid, flexible widths, relative spacing, and media queries. Another challenge was maintaining consistent alignment between headings, form fields, and notices. I solved this by creating reusable CSS classes and applying consistent margins, padding, border radii, and typography.

## 6. Conclusion

This task provided practical experience in converting a visual reference into a semantic HTML structure and organized CSS implementation. It also strengthened my understanding of CSS Grid, responsive design, form styling, accessibility-friendly labels, and basic client-side validation. The final webpage is designed to closely follow the supplied reference while remaining usable across desktop, tablet, and mobile screen sizes.
