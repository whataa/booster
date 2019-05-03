# booster-transform-lint

This module is used for potential performance issues detecting.

## Lint Reports

The [dot](https://www.graphviz.org/doc/info/lang.html) format reports is located at `$buildDir/reports/booster-transform-lint/`,  you can convert the dot files to PNGs using the following command:

```bash
find build -name '*.dot' | xargs -I{} dot -O -Tpng {}
```

Here is an example generated by dot:

![com.didiglobal.booster.demo.MainActivity](../assets/com.didiglobal.booster.demo.MainActivity.dot.png)
