# Software Test Plan: SauceDemo E-Commerce Platform

## 1. Project Overview
This document defines the manual testing strategy for validating the end-to-end user journeys on the SauceDemo e-commerce web application.

## 2. Scope of Testing
- **In-Scope:** User Authentication, Product Catalog Sorting/Filtering, Shopping Cart Operations, and Checkout Workflow.
- **Out-of-Scope:** software Configuration, Payment gateway integration (sandbox site), load/stress testing, cross-browser support for legacy browsers (IE11).

## 3. Test Strategy & Types
- **Manual Functional Testing:** Verification of user stories against expected system behaviors.
- **UI & Responsiveness Testing:** Executed on Google Chrome (1920x1080) and Mobile Viewport emulation.
- **Access Control Testing:** Verification of page restrictions when unauthenticated.

## 4. Entry & Exit Criteria
- **Entry Criteria:** Target application (https://www.saucedemo.com/) accessible via browser.
- **Exit Criteria:** 100% of planned test cases executed; 0 unresolved Critical or High severity bugs.
