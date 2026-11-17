# 🧩 Easy Piece

A practical tool to organize, adjust, and validate Power BI report layouts, making design standardization easier.

Easy Piece helps report developers review visual placement, adjust layouts, and identify inconsistencies through a visual interface.

## Why Easy Piece?

Adjusting report layouts can involve repetitive work: moving visuals, checking spacing, and reviewing alignment across pages.

Easy Piece brings these tasks into one interface to make layout review and standardization easier.

## Features

- Import an existing Power BI report
- Navigate between report pages
- Inspect and adjust visual positions and dimensions
- Review alignment, spacing, and page boundaries
- Apply layout adjustments to the current page or all pages
- Review validation results
- Export an adjusted PBIX report

## How to Use

### 1. Open Easy Piece

Open `EasyPiece.html` in your browser.

### 2. Choose your starting point

You can start in three ways:

#### Create a layout from scratch

Start with a blank canvas, add pages and visual placeholders, and organize your report layout before building it in Power BI.

#### Import a Figma file

Use a layout designed in Figma as your starting point, then review and adjust it in Easy Piece before continuing your report development workflow.

#### Import an existing Power BI report

Use an existing report as your starting point:

- **Import PBIX:** select your Power BI report file.
- **Import PBIP folder (PBIR):** select the report folder from a Power BI Project.

The interface marks the PBIR import option as beta.

### 3. Explore the layout

Select a page from the **Report Pages** panel.

The canvas displays the report’s visual containers so you can inspect their placement and size. It is a layout preview, not a rendering of the report’s data or interactive visuals.

Use zoom to review the full page or focus on specific areas.

### 4. Adjust visuals

Select a visual to inspect its layout properties.

Move or resize elements on the canvas, or use the inspector to adjust their position and dimensions.

You can also use:

- **Adjust current page** to apply layout adjustments to the selected page.
- **Adjust all pages** to apply adjustments across the report.
- **Undo adjust** to reverse the adjustment.

Review the result after applying changes, especially on pages with complex layouts.

### 5. Review validation results

Use the **Validation** and **Results** panels to review the issues and feedback reported by the tool.

Check the final arrangement before exporting.

### 6. Export and check in Power BI

Click **Download PBIX report** to export the adjusted report.

Open the exported file in Power BI Desktop and review:

- Visual placement and dimensions
- Titles, labels, and content readability
- Groups and overlapping elements
- Navigation, bookmarks, and interactions

Keep a copy of your original report so you can compare the results.

## Scope

Easy Piece focuses on report layout and visual organization.

It does not replace Power BI Desktop for data modeling, DAX development, or functional report testing. Layout validation also does not confirm the accuracy of business metrics or underlying data.

## Project Background

I started developing Easy Piece during my first weeks at Bose.

What began as an idea for a spreadsheet to simplify layout work evolved into a working prototype. With valuable contributions from my colleagues, it grew into a practical tool that now supports our daily work.

## Feedback

Have you tried Easy Piece? [Share your feedback in our satisfaction survey](https://forms.cloud.microsoft/Pages/ResponsePage.aspx?id=fuCKXdB_TUCFwUU_89yMHkp0kOZY2hVErhqODuqTZIBUOVVSRVBJR0JOVE5UTlE5QVNGWkdJQlBQTS4u).

Found a bug or have a suggestion? Open an issue with:

- A description of the problem or idea
- Steps to reproduce it
- Expected and actual behavior
- Screenshots, when useful
- The import format used, if applicable

Use sample reports and remove sensitive information before sharing files or screenshots.

## Author

**Andreza Umbelino**

[LinkedIn](https://www.linkedin.com/in/andrezaumbelino)
