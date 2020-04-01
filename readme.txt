typescript

make sure you have node.js installed first

run ths command in terminal 

npm install typescript -g 

https://github.com/TECHCareers-by-Manpower/typescript-tutorials#suggested-extensions-for-visual-studio-code

Suggested Extensions (for Visual Studio Code):

1: ESLint

2: Material Icon Theme

3: Path Intellisense

4: Prettier - Code Formatter

5: TSLint

6: Live Reload
file -> preferences - keyboard shortcuts

formating document
shift alt f

commands 

tsc filename.ts 

- this converts your ts to a js file 

tsc -w -p .

- this automatic complies the ts to a js file 
	the -w & -p are flags
- requires a .json file prior

{
    "compilerOptions": {
        "module": "commonjs",
        "noImplicitAny": true,
        "removeComments": true,
        "preserveConstEnums": true,
        "sourceMap": true
    },
    "files": [
        "main.ts"
    ]
}

$ tsc -w -p .
[11:55:27 AM] Starting compilation in watch mode...

[11:55:34 AM] Found 0 errors. Watching for file changes.

============================================

npm install typescript ts-node -g 

// this command installs ts node

ts-mode filename.ts

	- this provides you with the output directly in the 
	ts-mode main.ts



blah bl;ah