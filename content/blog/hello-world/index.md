---
title: Unit Tests Vs End To End Tests
date: "2020-12-07T22:12:03.284Z"
description: "Unit Tests Vs End To End Tests"
---

The objective of both testing types is different. The purpose of unit testing is to create a robust codebase. This also allows to identify the defects very early in the software lifecycle (Shift Left). Unit Tests makes up the largest section of the pyramid, therefore creating a sold base.

E2E tests are typically slow because they run against the GUI, interacting with the real server, acting like a real user. They need a working application. That’s why E2E tests are not feasible to be used as the only/main test type. They are pretty important because they are testing everything but they must be used carefully to avoid brittle and time consuming test suites.

Having no or fewer unit tests & more E2E tests is an anti-pattern. Martin Fowler and others within the engineering, QA and DevOps communities call it as ice-cream cone effect.

This [Google Testing Blog](https://testing.googleblog.com/2015/04/just-say-no-to-more-end-to-end-tests.html) also expands on why you shouldn't rely on end-to-end tests.   

