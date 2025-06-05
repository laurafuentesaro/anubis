# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This repository contains a single-page web application for a Keto diet meal planning system. The application is implemented as a static HTML file (`calendario-visual-keto.html`) with embedded CSS styling.

## Architecture

The application is built as a monolithic HTML file that includes:
- Complete HTML structure for a 7-day meal plan
- Embedded CSS with modern design system variables
- Responsive grid layouts for meal cards
- No JavaScript functionality (pure HTML/CSS)

## Key Features

- **7-Day Meal Plan**: Each day contains breakfast, lunch, and dinner with calorie counts
- **Substitution Options**: Alternative meal suggestions for flexibility
- **Visual Design System**: Uses CSS custom properties for consistent theming
- **Responsive Layout**: Grid-based design that adapts to different screen sizes
- **Meal Construction Formula**: Guidelines for building custom meals

## Development Notes

Since this is a static HTML file with no build process:
- Changes can be made directly to `calendario-visual-keto.html`
- View changes by opening the file in a web browser
- No dependencies or package management required
- No build, test, or lint commands needed

## Styling Guidelines

The CSS uses a design system with:
- Custom properties for colors (`--black`, `--white`, `--gray-1` through `--gray-12`)
- Consistent spacing and border radius variables
- Inter font family from Google Fonts
- Mobile-first responsive design with media queries at 768px