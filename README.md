# ace-compiler

## ANT-ACE introduction

***

## ANT-ACE paper

- CGO

```

```

- ASPLOS

```
```

## ANT-ACE opensource

- [ANT-ACE compiler infrastructure : **air-infra**](https://github.com/ace-compiler-tmp/air-infra.git)
- [Neural network domain : **nn-addon**](https://github.com/ace-compiler-tmp/nn-addon.git)
- [FHE domain Secret and encryption runtime libraries : **fhe-cmplr**](https://github.com/ace-compiler-tmp/fhe-cmplr.git)
- [Automated testing and performance benchmark data : **cti**](https://github.com/ace-compiler-tmp/fhe-cmplr.git)

```
git clone https://github.com/ace-compiler-tmp/air-infra.git
git clone https://github.com/ace-compiler-tmp/nn-addon.git
git clone https://github.com/ace-compiler-tmp/fhe-cmplr.git
```

## ANT-ACE download, build, test

```
cmake -S fhe-cmplr -B build ****
cmake --build build -- -j
```

```
pytest -m ****
```

## Others