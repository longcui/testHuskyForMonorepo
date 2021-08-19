# testHuskyForMonorepo

Follow [this](https://typicode.github.io/husky/#/).

instead of using 
```
npx husky add .husky/pre-commit "npm test"
```

use
```
npx husky add sub/.husky/pre-commit "npm test"
```


also add `cd sub` in `pre-commit` file.
