# Github Workflow

This repo contains class exercises carried out in the Continuous Integrations and AWS class as part of the Full Stack Web Development Program .

## Task

[![GH workflow](https://github.com/ankita-projects/GITHUB_WORKFLOW/actions/workflows/task.yml/badge.svg)](https://github.com/ankita-projects/GITHUB_WORKFLOW/actions/workflows/task.yml)

## null_or_empty

[![Node CI](https://github.com/ankita-projects/GITHUB_WORKFLOW/actions/workflows/main.yml/badge.svg)](https://github.com/ankita-projects/GITHUB_WORKFLOW/blob/main/.github/workflows/main.yml)

A Node.js package that checks if a given string is null or empty.

### Usage

First, install the package using npm:

    npm install @skalwar/null_or_empty --save

Then, require the package and use it like so:

    var isNullOrEmpty = require('@skalwar/null_or_empty');

    console.log(isNullOrEmpty("")); // true
    console.log(isNullOrEmpty(null)); // true
    console.log(isNullOrEmpty(undefined)); // true

    console.log(isNullOrEmpty("Hello World")); // false

## License

MIT
