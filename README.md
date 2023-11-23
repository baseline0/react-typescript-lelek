# orig

npm install

npm start


---

# nov 2023

```
--openssl-legacy-provider error
```

- adding above to package.json start cmd did not work

tried:
```
npm update
```
same error



```
  opensslErrorStack: [ 'error:03000086:digital envelope routines::initialization error' ],
  library: 'digital envelope routines',
  reason: 'unsupported',
  code: 'ERR_OSSL_EVP_UNSUPPORTED'
}

```


tried:
```
export NODE_OPTIONS=--openssl-legacy-provider
npm start
```

gave new errors. ts compilation errors.

made changes to tsconfig and ...

```
npm install --save-dev typescript@^4.0.0
```



http://localhost:8080/ 
