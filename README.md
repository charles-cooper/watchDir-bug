This is a simple project to reproduce the bug described at https://github.com/commercialhaskell/stack/issues/1838#issuecomment-188626847

Steps to reproduce

```bash
stack build --file-watch
```
Then in another terminal
```bash
rm -r src/Data
```
