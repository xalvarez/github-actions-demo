# GitHub Actions Demo

## Introduction

This is my first experiment with GitHub Actions. The application contained in
this repository was generated using [Spring Initializr](https://start.spring.io/)
and doesn't do anything special. It includes a basic test which is executed by means
of maven and a GitHub Actions workflow.

## The workflow

The workflow is executed when a pull request is created. Then, a maven wrapper is used to
run the tests.
