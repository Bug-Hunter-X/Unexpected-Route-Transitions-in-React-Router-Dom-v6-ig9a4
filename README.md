# Unexpected Route Transitions in React Router Dom v6

This repository demonstrates an unexpected behavior in React Router Dom v6 when navigating between routes with nested components. The navigation using Links does not work as expected, leading to unexpected route transitions. 

## Bug Description

The issue is observed in a simple application with two routes, Home and About.  Navigating between these routes using Links does not always transition to the correct route or may not transition at all.  This behavior may appear intermittently. 

## Solution

The bug was likely caused by a misconfiguration in the React Router routes or a conflict between nested components or other libraries. The solution involves using the `useLocation` hook to correctly manage route transitions. 
