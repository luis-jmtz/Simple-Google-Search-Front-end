# Google Search Frontend - Project 0

## Description
This project is a frontend implementation of Google Search, Google Image Search, and Google Advanced Search, created as part of Harvard's CS50 Web Programming with Python and JavaScript course. The project demonstrates how HTML forms can interact with existing web servers (in this case, Google's search functionality) by using GET parameters in URLs.

## Features
- **Three distinct search pages**:
  - `index.html`: Main Google Search page
  - `google_image_search.html`: Google Image Search page
  - `google_advanced_search.html`: Google Advanced Search page
- **Navigation links** between all search pages in the upper-right corner
- **Responsive design** that works on different screen sizes
- **Styled components** to resemble Google's aesthetic:
  - Centered search bar with rounded corners
  - Properly aligned advanced search fields
  - Blue "Advanced Search" button with white text
- **"I'm Feeling Lucky"** functionality that takes users directly to the first search result

## Technical Implementation
- Uses HTML forms with appropriate `action` attributes pointing to Google's search endpoints
- Implements correct GET parameters for each search type:
  - `q` for basic searches
  - `as_epq`, `as_oq`, `as_eq` for advanced search fields
- CSS styling that mimics Google's interface:
  - Media queries for responsive design
  - Proper spacing and alignment of form elements
  - Focus states for input fields

## Files
- `index.html`: Main Google search page
- `google_image_search.html`: Image search page
- `google_advanced_search.html`: Advanced search page
- `styles.css`: Shared stylesheet for all pages
- `google-logo.png`: Google logo image
- `google-images-logo.png`: Google Images logo image

## How to Use
1. Open `index.html` in a web browser
2. Use the navigation links in the upper-right to switch between search types
3. Enter search queries and submit the forms to see Google's results

## Project Requirements
This project meets all requirements specified in the CS50 assignment:
- Three distinct search pages with proper navigation
- Correct form implementations for each search type
- Proper styling to match Google's interface
- All specified functionality including "I'm Feeling Lucky"
- Responsive design that works on different screen sizes

## Acknowledgments
Project created as part of Harvard's CS50 Web Programming course by Brian Yu and David J. Malan.