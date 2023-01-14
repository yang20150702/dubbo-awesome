# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 0.975 ops/ms
# Warmup Iteration   2: 2.206 ops/ms
# Warmup Iteration   3: 4.816 ops/ms
Iteration   1: 4.795 ops/ms
Iteration   2: 4.956 ops/ms
Iteration   3: 5.077 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.943 ±(99.9%) 2.578 ops/ms [Average]
  (min, avg, max) = (4.795, 4.943, 5.077), stdev = 0.141
  CI (99.9%): [2.365, 7.520] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:18
# Fork: 1 of 1
# Warmup Iteration   1: 1.527 ops/ms
# Warmup Iteration   2: 4.601 ops/ms
# Warmup Iteration   3: 5.956 ops/ms
Iteration   1: 5.856 ops/ms
Iteration   2: 5.935 ops/ms
Iteration   3: 5.972 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.921 ±(99.9%) 1.077 ops/ms [Average]
  (min, avg, max) = (5.856, 5.921, 5.972), stdev = 0.059
  CI (99.9%): [4.844, 6.998] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:10
# Fork: 1 of 1
# Warmup Iteration   1: 1.410 ops/ms
# Warmup Iteration   2: 4.306 ops/ms
# Warmup Iteration   3: 5.311 ops/ms
Iteration   1: 5.563 ops/ms
Iteration   2: 5.677 ops/ms
Iteration   3: 5.495 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.578 ±(99.9%) 1.674 ops/ms [Average]
  (min, avg, max) = (5.495, 5.578, 5.677), stdev = 0.092
  CI (99.9%): [3.904, 7.252] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:10:02
# Fork: 1 of 1
# Warmup Iteration   1: 1.549 ops/ms
# Warmup Iteration   2: 3.978 ops/ms
# Warmup Iteration   3: 4.973 ops/ms
Iteration   1: 5.087 ops/ms
Iteration   2: 4.936 ops/ms
Iteration   3: 4.904 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.976 ±(99.9%) 1.784 ops/ms [Average]
  (min, avg, max) = (4.904, 4.976, 5.087), stdev = 0.098
  CI (99.9%): [3.192, 6.760] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:55
# Fork: 1 of 1
# Warmup Iteration   1: 17.162 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 7.500 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 5.875 ±(99.9%) 0.015 ms/op
Iteration   1: 5.662 ±(99.9%) 0.011 ms/op
Iteration   2: 5.612 ±(99.9%) 0.011 ms/op
Iteration   3: 5.475 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.583 ±(99.9%) 1.768 ms/op [Average]
  (min, avg, max) = (5.475, 5.583, 5.662), stdev = 0.097
  CI (99.9%): [3.815, 7.351] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:48
# Fork: 1 of 1
# Warmup Iteration   1: 14.847 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 6.054 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 5.525 ±(99.9%) 0.010 ms/op
Iteration   1: 5.362 ±(99.9%) 0.007 ms/op
Iteration   2: 5.230 ±(99.9%) 0.010 ms/op
Iteration   3: 5.206 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.266 ±(99.9%) 1.531 ms/op [Average]
  (min, avg, max) = (5.206, 5.266, 5.362), stdev = 0.084
  CI (99.9%): [3.735, 6.797] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:41
# Fork: 1 of 1
# Warmup Iteration   1: 18.911 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 6.774 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.731 ±(99.9%) 0.011 ms/op
Iteration   1: 5.538 ±(99.9%) 0.013 ms/op
Iteration   2: 5.732 ±(99.9%) 0.007 ms/op
Iteration   3: 5.483 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.584 ±(99.9%) 2.393 ms/op [Average]
  (min, avg, max) = (5.483, 5.584, 5.732), stdev = 0.131
  CI (99.9%): [3.192, 7.977] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:34
# Fork: 1 of 1
# Warmup Iteration   1: 20.049 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 8.688 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 6.710 ±(99.9%) 0.013 ms/op
Iteration   1: 6.399 ±(99.9%) 0.014 ms/op
Iteration   2: 6.390 ±(99.9%) 0.012 ms/op
Iteration   3: 6.298 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.362 ±(99.9%) 1.021 ms/op [Average]
  (min, avg, max) = (6.298, 6.362, 6.399), stdev = 0.056
  CI (99.9%): [5.341, 7.383] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:26
# Fork: 1 of 1
# Warmup Iteration   1: 18.666 ±(99.9%) 0.267 ms/op
# Warmup Iteration   2: 7.363 ±(99.9%) 0.053 ms/op
# Warmup Iteration   3: 6.176 ±(99.9%) 0.031 ms/op
Iteration   1: 5.378 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.314 ms/op
                 createUser·p0.50:   5.095 ms/op
                 createUser·p0.90:   6.726 ms/op
                 createUser·p0.95:   7.619 ms/op
                 createUser·p0.99:   9.748 ms/op
                 createUser·p0.999:  25.572 ms/op
                 createUser·p0.9999: 32.776 ms/op
                 createUser·p1.00:   33.063 ms/op

Iteration   2: 5.528 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.032 ms/op
                 createUser·p0.50:   5.194 ms/op
                 createUser·p0.90:   7.004 ms/op
                 createUser·p0.95:   8.004 ms/op
                 createUser·p0.99:   10.797 ms/op
                 createUser·p0.999:  17.012 ms/op
                 createUser·p0.9999: 29.571 ms/op
                 createUser·p1.00:   30.835 ms/op

Iteration   3: 5.624 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   2.273 ms/op
                 createUser·p0.50:   5.300 ms/op
                 createUser·p0.90:   7.160 ms/op
                 createUser·p0.95:   8.077 ms/op
                 createUser·p0.99:   10.821 ms/op
                 createUser·p0.999:  26.739 ms/op
                 createUser·p0.9999: 33.830 ms/op
                 createUser·p1.00:   34.734 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 174232
  mean =      5.508 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27 
    [ 2.500,  5.000) = 69037 
    [ 5.000,  7.500) = 93565 
    [ 7.500, 10.000) = 9345 
    [10.000, 12.500) = 1609 
    [12.500, 15.000) = 283 
    [15.000, 17.500) = 145 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 56 
    [27.500, 30.000) = 42 
    [30.000, 32.500) = 43 
    [32.500, 35.000) = 18 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.032 ms/op
     p(50.0000) =      5.186 ms/op
     p(90.0000) =      6.971 ms/op
     p(95.0000) =      7.889 ms/op
     p(99.0000) =     10.469 ms/op
     p(99.9000) =     22.153 ms/op
     p(99.9900) =     32.609 ms/op
     p(99.9990) =     34.734 ms/op
     p(99.9999) =     34.734 ms/op
    p(100.0000) =     34.734 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:20
# Fork: 1 of 1
# Warmup Iteration   1: 18.734 ±(99.9%) 0.306 ms/op
# Warmup Iteration   2: 6.764 ±(99.9%) 0.054 ms/op
# Warmup Iteration   3: 5.571 ±(99.9%) 0.023 ms/op
Iteration   1: 5.189 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   2.298 ms/op
                 existUser·p0.50:   4.760 ms/op
                 existUser·p0.90:   6.808 ms/op
                 existUser·p0.95:   7.709 ms/op
                 existUser·p0.99:   10.387 ms/op
                 existUser·p0.999:  24.445 ms/op
                 existUser·p0.9999: 32.783 ms/op
                 existUser·p1.00:   34.734 ms/op

Iteration   2: 5.242 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.216 ms/op
                 existUser·p0.50:   4.874 ms/op
                 existUser·p0.90:   6.775 ms/op
                 existUser·p0.95:   7.848 ms/op
                 existUser·p0.99:   10.420 ms/op
                 existUser·p0.999:  24.576 ms/op
                 existUser·p0.9999: 30.999 ms/op
                 existUser·p1.00:   31.326 ms/op

Iteration   3: 5.220 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.245 ms/op
                 existUser·p0.50:   4.899 ms/op
                 existUser·p0.90:   6.652 ms/op
                 existUser·p0.95:   7.504 ms/op
                 existUser·p0.99:   10.027 ms/op
                 existUser·p0.999:  26.958 ms/op
                 existUser·p0.9999: 34.617 ms/op
                 existUser·p1.00:   35.324 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 183904
  mean =      5.217 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 53 
    [ 2.500,  5.000) = 106167 
    [ 5.000,  7.500) = 67102 
    [ 7.500, 10.000) = 8441 
    [10.000, 12.500) = 1214 
    [12.500, 15.000) = 533 
    [15.000, 17.500) = 179 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 46 
    [27.500, 30.000) = 45 
    [30.000, 32.500) = 51 
    [32.500, 35.000) = 23 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.216 ms/op
     p(50.0000) =      4.841 ms/op
     p(90.0000) =      6.742 ms/op
     p(95.0000) =      7.692 ms/op
     p(99.0000) =     10.273 ms/op
     p(99.9000) =     24.576 ms/op
     p(99.9900) =     32.775 ms/op
     p(99.9990) =     34.939 ms/op
     p(99.9999) =     35.324 ms/op
    p(100.0000) =     35.324 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 18.223 ±(99.9%) 0.299 ms/op
# Warmup Iteration   2: 7.131 ±(99.9%) 0.049 ms/op
# Warmup Iteration   3: 5.925 ±(99.9%) 0.026 ms/op
Iteration   1: 5.998 ±(99.9%) 0.028 ms/op
                 getUser·p0.00:   0.894 ms/op
                 getUser·p0.50:   5.456 ms/op
                 getUser·p0.90:   8.077 ms/op
                 getUser·p0.95:   9.716 ms/op
                 getUser·p0.99:   14.352 ms/op
                 getUser·p0.999:  20.808 ms/op
                 getUser·p0.9999: 30.704 ms/op
                 getUser·p1.00:   32.309 ms/op

Iteration   2: 5.828 ±(99.9%) 0.026 ms/op
                 getUser·p0.00:   2.695 ms/op
                 getUser·p0.50:   5.349 ms/op
                 getUser·p0.90:   7.602 ms/op
                 getUser·p0.95:   8.815 ms/op
                 getUser·p0.99:   12.405 ms/op
                 getUser·p0.999:  30.970 ms/op
                 getUser·p0.9999: 37.787 ms/op
                 getUser·p1.00:   38.797 ms/op

Iteration   3: 5.898 ±(99.9%) 0.026 ms/op
                 getUser·p0.00:   2.050 ms/op
                 getUser·p0.50:   5.423 ms/op
                 getUser·p0.90:   7.815 ms/op
                 getUser·p0.95:   8.897 ms/op
                 getUser·p0.99:   12.562 ms/op
                 getUser·p0.999:  32.869 ms/op
                 getUser·p0.9999: 37.552 ms/op
                 getUser·p1.00:   37.880 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 162406
  mean =      5.907 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7 
    [ 2.500,  5.000) = 46756 
    [ 5.000,  7.500) = 96748 
    [ 7.500, 10.000) = 13429 
    [10.000, 12.500) = 3321 
    [12.500, 15.000) = 1308 
    [15.000, 17.500) = 462 
    [17.500, 20.000) = 146 
    [20.000, 22.500) = 55 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 16 
    [27.500, 30.000) = 8 
    [30.000, 32.500) = 52 
    [32.500, 35.000) = 44 
    [35.000, 37.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.894 ms/op
     p(50.0000) =      5.407 ms/op
     p(90.0000) =      7.807 ms/op
     p(95.0000) =      9.126 ms/op
     p(99.0000) =     13.401 ms/op
     p(99.9000) =     23.560 ms/op
     p(99.9900) =     37.487 ms/op
     p(99.9990) =     38.552 ms/op
     p(99.9999) =     38.797 ms/op
    p(100.0000) =     38.797 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 21.159 ±(99.9%) 0.362 ms/op
# Warmup Iteration   2: 8.372 ±(99.9%) 0.065 ms/op
# Warmup Iteration   3: 6.534 ±(99.9%) 0.028 ms/op
Iteration   1: 6.388 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   2.142 ms/op
                 listUser·p0.50:   5.865 ms/op
                 listUser·p0.90:   8.331 ms/op
                 listUser·p0.95:   9.585 ms/op
                 listUser·p0.99:   13.058 ms/op
                 listUser·p0.999:  26.670 ms/op
                 listUser·p0.9999: 29.327 ms/op
                 listUser·p1.00:   30.605 ms/op

Iteration   2: 6.592 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   3.125 ms/op
                 listUser·p0.50:   6.070 ms/op
                 listUser·p0.90:   8.585 ms/op
                 listUser·p0.95:   10.076 ms/op
                 listUser·p0.99:   13.337 ms/op
                 listUser·p0.999:  29.934 ms/op
                 listUser·p0.9999: 33.957 ms/op
                 listUser·p1.00:   35.652 ms/op

Iteration   3: 6.588 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   3.113 ms/op
                 listUser·p0.50:   6.160 ms/op
                 listUser·p0.90:   8.372 ms/op
                 listUser·p0.95:   9.559 ms/op
                 listUser·p0.99:   13.001 ms/op
                 listUser·p0.999:  26.368 ms/op
                 listUser·p0.9999: 35.792 ms/op
                 listUser·p1.00:   36.700 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 147091
  mean =      6.522 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5 
    [ 2.500,  5.000) = 8023 
    [ 5.000,  7.500) = 114875 
    [ 7.500, 10.000) = 17923 
    [10.000, 12.500) = 4391 
    [12.500, 15.000) = 1039 
    [15.000, 17.500) = 362 
    [17.500, 20.000) = 101 
    [20.000, 22.500) = 106 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 75 
    [27.500, 30.000) = 78 
    [30.000, 32.500) = 62 
    [32.500, 35.000) = 11 
    [35.000, 37.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      2.142 ms/op
     p(50.0000) =      6.029 ms/op
     p(90.0000) =      8.421 ms/op
     p(95.0000) =      9.732 ms/op
     p(99.0000) =     13.124 ms/op
     p(99.9000) =     27.912 ms/op
     p(99.9900) =     33.093 ms/op
     p(99.9990) =     36.669 ms/op
     p(99.9999) =     36.700 ms/op
    p(100.0000) =     36.700 ms/op


# Run complete. Total time: 00:13:20

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   4.943 ± 2.578  ops/ms
ClientPb.existUser                       thrpt       3   5.921 ± 1.077  ops/ms
ClientPb.getUser                         thrpt       3   5.578 ± 1.674  ops/ms
ClientPb.listUser                        thrpt       3   4.976 ± 1.784  ops/ms
ClientPb.createUser                       avgt       3   5.583 ± 1.768   ms/op
ClientPb.existUser                        avgt       3   5.266 ± 1.531   ms/op
ClientPb.getUser                          avgt       3   5.584 ± 2.393   ms/op
ClientPb.listUser                         avgt       3   6.362 ± 1.021   ms/op
ClientPb.createUser                     sample  174232   5.508 ± 0.012   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.032           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.186           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.971           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.889           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.469           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.153           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.609           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.734           ms/op
ClientPb.existUser                      sample  183904   5.217 ± 0.012   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.216           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.841           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.742           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.692           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.273           ms/op
ClientPb.existUser:existUser·p0.999     sample          24.576           ms/op
ClientPb.existUser:existUser·p0.9999    sample          32.775           ms/op
ClientPb.existUser:existUser·p1.00      sample          35.324           ms/op
ClientPb.getUser                        sample  162406   5.907 ± 0.016   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.894           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.407           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.807           ms/op
ClientPb.getUser:getUser·p0.95          sample           9.126           ms/op
ClientPb.getUser:getUser·p0.99          sample          13.401           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.560           ms/op
ClientPb.getUser:getUser·p0.9999        sample          37.487           ms/op
ClientPb.getUser:getUser·p1.00          sample          38.797           ms/op
ClientPb.listUser                       sample  147091   6.522 ± 0.016   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.142           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.029           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.421           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.732           ms/op
ClientPb.listUser:listUser·p0.99        sample          13.124           ms/op
ClientPb.listUser:listUser·p0.999       sample          27.912           ms/op
ClientPb.listUser:listUser·p0.9999      sample          33.093           ms/op
ClientPb.listUser:listUser·p1.00        sample          36.700           ms/op
