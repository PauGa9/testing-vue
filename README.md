# testing-vue
With Jest

-  Code coverage (with Istanbul by default). It gives coverage information in two different ways:
    - CLI when running jest (the jest coverage parameter has to be true in package.json).
    - HTML running from /coverage/lcov-report/ (for example with http-server or perform a get request to this folder)
-  Place test files closer to source files because:
    - easy imports (./fileToTest)
    - clear visibility (which files don't have their test?)
    - convenient to open
    - move files and tests together
