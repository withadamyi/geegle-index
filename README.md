# Geegle Index

Indexed dataset of 10% of StackOverflow questions

Used by https://github.com/adamyi/Geegle3/blob/master/chals/web/search/app/main.py

This is a backup Git LFS repo.

## Combining Files
GitHub limits LFS file size to 2 GB so we have to split files.

```
$ cp index.tar.part0 index.tar
$ cat index.tar.part1 >> index.tar
$ cat index.tar.part2 >> index.tar
```

## Download from S3 (Preferred Way)

https://geegle-index.s3-ap-southeast-2.amazonaws.com/index.tar

This is not guranteed to be still up though, since SECedu is paying for it.
