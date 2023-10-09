\*\* Basics

1. [ ] Did you run the tests?
2. [ ] Are the tests passing? Screenshot added to the PR
3. [ ] Did you test the UI flow?
4. [ ] Does the design match Figma? Fonts? Colors? Paddings? Margins?
5. [ ] Is it responsive? Does the mobile web version not break and look good?

\*\*Code Quality

6. [ ] Does the code follow a consistent coding style and conventions (using BEM on the web)?
7. [ ] No use of !important.
8. [ ] No console.log or debug statements left in the code.
9. [ ] No commented-out code left in the files.
10. [ ] Unused variables and imports are removed.
11. [ ] Is the code self-documenting and easy to understand?
12. [ ] Is the code free from code smells and anti-patterns?
13. [ ] Proper error handling and validation are implemented.
14. [ ] Is the code modular and follows the Single Responsibility Principle?
15. [ ] Are meaningful variable and function names used?
16. [ ] No hardcoded values use constant values.
17. [ ] Consistent naming conventions are used (BEM, OOCSS, SMACSS, etc.).
18. [ ] Is the code well-organized and DRY (Don't Repeat Yourself)?
19. [ ] Use destructuring assignment for arrays and objects.
20. [ ] Proper use of ES6 features
21. [ ] Create helper functions (common functions) if a function is repeated elsewhere.
22. [ ] No unused props are being passed to components.
23. [ ] Are there any React warnings reported in the console, like missing a key prop with a unique value for each element in the array?
24. [ ] Components are small if the size exceeds 200-300 lines, create child components.
25. [ ] Using existing variable names for colors across the project.
26. [ ] It's not using inline styling.
27. [ ] Properly encapsulates and scopes CSS styles.
28. [ ] Properly uses React hooks.
29. [ ] Imports hooks from the top along with React, no React.useState
30. [ ] Do not use libraries for what you can do native, like handles dates and use moment js

\*\*Performance

31. [ ] Is the code optimized for performance, avoiding unnecessary re-renders?
32. [ ] No excessive API requests or unnecessary data fetching.
33. [ ] Images and assets are optimized for web use.
34. [ ] Avoid unnecessary server requests.
35. [ ] Properly handles and tests for lazy loading of components.
36. [ ] Properly handles and tests for code splitting.
37. [ ] Properly handles and tests for client-side caching.
38. [ ] Properly handles and tests for virtualization of large lists.
39. [ ] Properly handles and tests for navigation menus.
40. [ ] Properly handles and tests for pagination.

\*\*Accessibility

41. [ ] Proper use of semantic HTML elements.
42. [ ] All images have appropriate alt text.
43. [ ] Focus is managed correctly for keyboard navigation.
44. [ ] ARIA attributes are used where necessary.
45. [ ] Conduct accessibility testing using tools like Axe or Lighthouse.

\*\*Testing

46. [ ] Unit tests cover key functionality.
47. [ ] Integration tests cover the interactions between components.
48. [ ] Code coverage is maintained and improved if necessary.
49. [ ] Proper error messages are displayed to users.
50. [ ] Errors are logged appropriately for debugging.
51. [ ] Review code comments and documentation for clarity and completeness.
52. [ ] Properly handles and tests for form submissions.

\*\*Documentation

54. [ ] Code comments and docstrings are up-to-date.
55. [ ] Readme.md is updated with any new information or changes.
56. [ ] API documentation (if applicable) is updated.

\*\*Security

57. [ ] No security vulnerabilities (e.g., XSS, CSRF) introduced.
58. [ ] Sensitive data is handled securely (e.g., no hardcoded secrets).
59. [ ] Ensure there's a backup and recovery plan in place for data and code.
60. [ ] Ensure there are policies in place for data backups and retention.

\*\*Dependency Management

61. [ ] Dependencies are up-to-date.
62. [ ] No vulnerable dependencies are used.
63. [ ] Set appropriate security headers in the response.
64. [ ] Ensure CORS settings are configured securely.
65. [ ] Codebase is free from SQL injection vulnerabilities.
66. [ ] Codebase is free from CSRF (Cross-Site Request Forgery) vulnerabilities.
67. [ ] Codebase is free from XSS (Cross-Site Scripting) vulnerabilities.
68. [ ] Codebase is free from unused or unnecessary dependencies.
69. [ ] All third-party libraries are properly integrated and configured.

\*\*State Management

70. [ ] No prop drilling, state is as close as the action as needed.
71. [ ] State is managed efficiently using React state or state management libraries.
72. [ ] No unnecessary state duplications.
73. [ ] Props not already in some context.
74. [ ] No unnecessary useeffects

\*\*User Experience (UX)

75. [ ] UI/UX design is consistent with mockups and style guides.
76. [ ] Responsiveness is maintained for different screen sizes.
77. [ ] User interactions are intuitive, and error messages are clear.
78. [ ] Proper loading added.
79. [ ] Ensure proper meta tags and structured data for SEO.
80. [ ] Pages are crawlable and have descriptive titles and URLs.
81. [ ] Implement PWA features like service workers and offline support (if applicable).
82. [ ] Translations are implemented correctly (if applicable).
83. [ ] Text can be easily translated without code changes.

\*\*Development Environment

84. [ ] Properly manages and updates the Redux/Context store (if used).
85. [ ] Codebase is free from memory leaks in event listeners.
86. [ ] Properly handles and tests for error boundaries.

\*\*Third-Party Integrations

87. [ ] Ensure third-party APIs and libraries are properly integrated and configured.
88. [ ] Follow best practices for Redux (if used).
89. [ ] Properly handles and tests for edge cases.
90. [ ] No dead or unreachable code.
91. [ ] Uses strict mode where appropriate.
92. [ ] Properly handles browser events and DOM manipulation.

\*\*Legal and Licensing

93. [ ] Ensure that all third-party libraries and assets have proper licensing and permissions.
94. [ ] Codebase is well-documented for developers.
95. [ ] No global variables or mutable state.
96. [ ] No unnecessary use of external libraries.
97. [ ] Properly handles and tests for edge cases.
98. [ ] Properly manages and updates component state.
99. [ ] No unused functions or variables.
100.  [ ] Properly uses React hooks (if applicable).
