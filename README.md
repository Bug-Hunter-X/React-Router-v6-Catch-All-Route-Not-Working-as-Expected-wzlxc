# React Router v6 Catch-All Route Issue

This repository demonstrates an unexpected behavior with the catch-all route ('*') in React Router v6.  Navigation to a route that doesn't explicitly exist does not always trigger the NotFound component.

## Bug Description

The `App.js` file contains a simple React Router setup with Home, About, and NotFound components.  The expected behavior is that navigating to any URL other than '/' or '/about' would show the NotFound component. However, this is not consistent across all scenarios. 

## Solution

The solution is provided in `AppSolution.js` demonstrating a potential fix or workaround. It addresses the issue by ensuring that the catch-all route is placed correctly within the route hierarchy to correctly handle all other navigation attempts.