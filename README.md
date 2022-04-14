# Boilerplate repo

Following the example from here:
https://itnext.io/step-by-step-building-and-publishing-an-npm-typescript-package-44fe7164964c

Does not include tests and linting, but you should add them

## Usage
`npm install @unegma/template-typescript-npm-utilities`

And then in your code:

```
import { ExampleClass } from "@unegma/template-typescript-npm-utilities";`

let exampleClass = new ExampleClass('Tim');
console.log(exampleClass.sayHello());
```




## ToDo

Check if tsconfig.json needs any other of these:

    "target": "es5",
    "lib": [
      "dom",
      "dom.iterable",
      "esnext"
    ],
    "allowJs": true,
    "skipLibCheck": true,
    "esModuleInterop": true,
    "allowSyntheticDefaultImports": true,
    "strict": true,
    "forceConsistentCasingInFileNames": true,
    "noFallthroughCasesInSwitch": true,
    "module": "esnext",
    "moduleResolution": "node",
    "resolveJsonModule": true,
    "isolatedModules": true,
    "noEmit": true,
    "jsx": "react-jsx"