
Run below commands:
```
cd functions
npm install
cd ../scripts2
npm install
deno myscript.ts
```

Result:
```
error: Relative import path "firebase-admin/firestore" not prefixed with / or ./ or ../
    at file:///Users/laurent/Documents/GitHub/test-deno-import/functions/shared_code.ts:1:27
```
