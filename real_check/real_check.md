# real_check 

This tool checks if the given libraries contain a pair of symbols of the form `[symbol]` and `real_[symbol]`. 

If the given libraries contain no such pair, the tool returns exit code `0`.
If the given libraries contain such a pair, the tool prints these symbols to stderror and returns exit code `1`.
If the tool is unable to determine if the libraries contain such a pair, it returns exit code `2`.


## Usage

```
PS> real_check.ps1 lib1 lib2 ...
```
