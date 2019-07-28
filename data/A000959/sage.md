```
echo "A000959 = [$(cat b000959.txt | awk '{ print $2 }'   | tr '\n' ',' | sed 's/,$/]\n/' )" > A000959.sage
```
