# Compiling TypeScript

## Installing and Running the Completed Package

1. OPTIONAL - Install the TypeScript compiler globally (local install is also possible):
`npm install -g typescript`

2. Install this package with Git:
`https://github.com/chackop/typescript-debug-compile`

3. Install local packages with `npm`:
`npm install`

4. Run TypeScript compilation and start the server simultaneously with:
`npm start`

## Exploring the Project

### /public
Contains HTML file which is served to the user - aggregates references to generated .js files.

### /src
Contains the non-compiled TypeScript code. This code becomes JavaScript that the browser can work with.
