### Creating an RDD
- nums = parallelize([1,2,3,4])
- sc.textFile("path.txt")
- hiveCtx = Hive

### Transforming RDD
- map (1:1 input:output)
- flatmap (not 1:1 based on some filtering)
- filter
- distinct
- sample
- union, intersection, subtract, cartesian

### Example
```
rdd = sc.parallelize([1,2,3,4])
squaredRDD = rdd.map(lambda x: x*x)
Yields 1, 4, 9, 16
```

### RDD Actions
- collect
- count
- countByValue
- take
- top
- reduce

### Lazy evaluation
- Nothing happens till an action is called

#### Running Spark from Local Terminal
- Suffix the command with `spark-submit`
- `spark-submit` also takes runtime parameters (that override cluster defaults)

