# MessageApp

## Project Overview 

This project is a sleek Svelte application designed for user-friendly interaction. Users can input a message, which dynamically displays in real-time, providing immediate feedback and enhancing the user experience.It features a straightforward layout comprising a header, a main content section, and a footer. The main content updates automatically based on user interactions.
 
## Features
- **Responsive** design with an elegant user interface
- **Dynamic state** management using $state
- **Adaptable layout** that supports rendering of child components


# Installation and Development

## Clone

Clone the repository  into a newly created directory.

```bash
git clone git@github.com:eribeq21/sendMessage.git
```

## Install

Install the necessary dependencies  in the package.json file

```bash
npm install
```


# Files Overview

## +layout.svelte

This file provides the overall structure of the application, including a header, footer, and a dynamic content area

## +page.svelte

This page includes an input field bound to a reactive variable, displaying the entered text in real time.

 
# Developing
 
Once you've installed dependencies with `npm install`, start a development server:
 
```bash
npm run dev
```