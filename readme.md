## Truncate SCSS Files
```
find ./resources/scss -type f -name “*.scss" -exec sh -c '> {}' \;
```
Source: https://unix.stackexchange.com/questions/260797/find-a-file-and-truncate-it
