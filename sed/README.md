# sed

## Remove lines that contain a specific text in a file

#### With GNU sed

```
sed '/example\.com/d;/test\.com/d' -i file.txt
```

will remove the lines with example.com and test.com.
