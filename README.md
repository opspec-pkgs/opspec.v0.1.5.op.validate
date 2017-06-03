# problem statement
validates an opspec 0.1.3 package

# example usage

> note: in examples, VERSION represents a version of the opspec0.1.3.pkg.validate pkg

## install

```shell
opctl pkg install github.com/opspec-pkgs/opspec0.1.3.pkg.validate#VERSION
```

## run

```
opctl run github.com/opspec-pkgs/opspec0.1.3.pkg.validate#VERSION
```

## compose

```yaml
run:
  op:
    pkg: { ref: github.com/opspec-pkgs/opspec0.1.3.pkg.validate#VERSION }
    inputs: { pkg }
```

