Example for [https://github.com/power-assert-js/espower-typescript/issues/14]

1. run **npm install** (it is include run test) - the test will crash
2. remove from **tsconfig.json** **outDir** prop
3. run **npm install** again - the test will be started and performed as expected
