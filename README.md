# 无常

1. Copy files and only include certain folders.
```
$ rsync -rv --inplace \
  --include '/' \
  --include '/*logs*/' \
  --include '/*logs*/*2020-01-10*/' \
  --exclude '*' \
  SRC_FOLDER \
  DEST_FOLDER
```
