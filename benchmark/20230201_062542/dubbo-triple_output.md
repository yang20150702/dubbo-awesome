# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.069 ops/ms
# Warmup Iteration   2: 2.136 ops/ms
# Warmup Iteration   3: 4.416 ops/ms
Iteration   1: 5.388 ops/ms
Iteration   2: 5.311 ops/ms
Iteration   3: 5.557 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.419 ±(99.9%) 2.288 ops/ms [Average]
  (min, avg, max) = (5.311, 5.419, 5.557), stdev = 0.125
  CI (99.9%): [3.131, 7.707] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:15
# Fork: 1 of 1
# Warmup Iteration   1: 1.438 ops/ms
# Warmup Iteration   2: 3.952 ops/ms
# Warmup Iteration   3: 5.665 ops/ms
Iteration   1: 5.692 ops/ms
Iteration   2: 5.862 ops/ms
Iteration   3: 6.045 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.866 ±(99.9%) 3.218 ops/ms [Average]
  (min, avg, max) = (5.692, 5.866, 6.045), stdev = 0.176
  CI (99.9%): [2.648, 9.084] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:03
# Fork: 1 of 1
# Warmup Iteration   1: 1.539 ops/ms
# Warmup Iteration   2: 4.037 ops/ms
# Warmup Iteration   3: 5.401 ops/ms
Iteration   1: 5.707 ops/ms
Iteration   2: 5.497 ops/ms
Iteration   3: 5.697 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.634 ±(99.9%) 2.162 ops/ms [Average]
  (min, avg, max) = (5.497, 5.634, 5.707), stdev = 0.119
  CI (99.9%): [3.472, 7.796] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 1.417 ops/ms
# Warmup Iteration   2: 3.867 ops/ms
# Warmup Iteration   3: 4.697 ops/ms
Iteration   1: 4.834 ops/ms
Iteration   2: 4.819 ops/ms
Iteration   3: 4.813 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.822 ±(99.9%) 0.191 ops/ms [Average]
  (min, avg, max) = (4.813, 4.822, 4.834), stdev = 0.010
  CI (99.9%): [4.632, 5.013] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:51
# Fork: 1 of 1
# Warmup Iteration   1: 17.754 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 7.166 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 5.889 ±(99.9%) 0.010 ms/op
Iteration   1: 5.625 ±(99.9%) 0.018 ms/op
Iteration   2: 5.518 ±(99.9%) 0.019 ms/op
Iteration   3: 5.664 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.603 ±(99.9%) 1.382 ms/op [Average]
  (min, avg, max) = (5.518, 5.603, 5.664), stdev = 0.076
  CI (99.9%): [4.221, 6.984] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 18.649 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 8.054 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 5.687 ±(99.9%) 0.012 ms/op
Iteration   1: 5.592 ±(99.9%) 0.014 ms/op
Iteration   2: 5.370 ±(99.9%) 0.009 ms/op
Iteration   3: 5.231 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.398 ±(99.9%) 3.319 ms/op [Average]
  (min, avg, max) = (5.231, 5.398, 5.592), stdev = 0.182
  CI (99.9%): [2.079, 8.716] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 14.739 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 7.423 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 5.930 ±(99.9%) 0.005 ms/op
Iteration   1: 5.723 ±(99.9%) 0.012 ms/op
Iteration   2: 5.562 ±(99.9%) 0.011 ms/op
Iteration   3: 5.536 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.607 ±(99.9%) 1.848 ms/op [Average]
  (min, avg, max) = (5.536, 5.607, 5.723), stdev = 0.101
  CI (99.9%): [3.759, 7.455] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 21.339 ±(99.9%) 0.136 ms/op
# Warmup Iteration   2: 7.997 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 6.693 ±(99.9%) 0.012 ms/op
Iteration   1: 6.660 ±(99.9%) 0.012 ms/op
Iteration   2: 6.537 ±(99.9%) 0.013 ms/op
Iteration   3: 6.460 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.552 ±(99.9%) 1.837 ms/op [Average]
  (min, avg, max) = (6.460, 6.552, 6.660), stdev = 0.101
  CI (99.9%): [4.715, 8.389] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 18.118 ±(99.9%) 0.314 ms/op
# Warmup Iteration   2: 7.354 ±(99.9%) 0.049 ms/op
# Warmup Iteration   3: 6.094 ±(99.9%) 0.025 ms/op
Iteration   1: 5.703 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   1.694 ms/op
                 createUser·p0.50:   5.358 ms/op
                 createUser·p0.90:   7.094 ms/op
                 createUser·p0.95:   8.176 ms/op
                 createUser·p0.99:   10.836 ms/op
                 createUser·p0.999:  23.910 ms/op
                 createUser·p0.9999: 26.986 ms/op
                 createUser·p1.00:   29.262 ms/op

Iteration   2: 5.689 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.441 ms/op
                 createUser·p0.50:   5.464 ms/op
                 createUser·p0.90:   6.930 ms/op
                 createUser·p0.95:   7.700 ms/op
                 createUser·p0.99:   10.355 ms/op
                 createUser·p0.999:  18.370 ms/op
                 createUser·p0.9999: 31.404 ms/op
                 createUser·p1.00:   31.752 ms/op

Iteration   3: 5.366 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   2.503 ms/op
                 createUser·p0.50:   5.145 ms/op
                 createUser·p0.90:   6.455 ms/op
                 createUser·p0.95:   7.209 ms/op
                 createUser·p0.99:   9.437 ms/op
                 createUser·p0.999:  27.471 ms/op
                 createUser·p0.9999: 32.507 ms/op
                 createUser·p1.00:   33.063 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 171941
  mean =      5.582 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10 
    [ 2.500,  5.000) = 56135 
    [ 5.000,  7.500) = 105757 
    [ 7.500, 10.000) = 8177 
    [10.000, 12.500) = 1322 
    [12.500, 15.000) = 256 
    [15.000, 17.500) = 75 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 58 
    [27.500, 30.000) = 47 
    [30.000, 32.500) = 41 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.694 ms/op
     p(50.0000) =      5.292 ms/op
     p(90.0000) =      6.857 ms/op
     p(95.0000) =      7.733 ms/op
     p(99.0000) =     10.174 ms/op
     p(99.9000) =     21.662 ms/op
     p(99.9900) =     32.022 ms/op
     p(99.9990) =     32.969 ms/op
     p(99.9999) =     33.063 ms/op
    p(100.0000) =     33.063 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 17.463 ±(99.9%) 0.285 ms/op
# Warmup Iteration   2: 6.172 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 5.833 ±(99.9%) 0.023 ms/op
Iteration   1: 5.631 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.437 ms/op
                 existUser·p0.50:   5.349 ms/op
                 existUser·p0.90:   6.816 ms/op
                 existUser·p0.95:   7.684 ms/op
                 existUser·p0.99:   10.617 ms/op
                 existUser·p0.999:  26.230 ms/op
                 existUser·p0.9999: 28.650 ms/op
                 existUser·p1.00:   30.638 ms/op

Iteration   2: 5.572 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   2.658 ms/op
                 existUser·p0.50:   5.366 ms/op
                 existUser·p0.90:   6.644 ms/op
                 existUser·p0.95:   7.307 ms/op
                 existUser·p0.99:   10.125 ms/op
                 existUser·p0.999:  13.597 ms/op
                 existUser·p0.9999: 31.219 ms/op
                 existUser·p1.00:   32.637 ms/op

Iteration   3: 5.646 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   2.306 ms/op
                 existUser·p0.50:   5.407 ms/op
                 existUser·p0.90:   6.799 ms/op
                 existUser·p0.95:   7.569 ms/op
                 existUser·p0.99:   10.437 ms/op
                 existUser·p0.999:  28.357 ms/op
                 existUser·p0.9999: 49.197 ms/op
                 existUser·p1.00:   50.004 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 170942
  mean =      5.616 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 47399 
    [ 5.000, 10.000) = 121503 
    [10.000, 15.000) = 1729 
    [15.000, 20.000) = 125 
    [20.000, 25.000) = 18 
    [25.000, 30.000) = 114 
    [30.000, 35.000) = 22 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 31 
    [50.000, 55.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.306 ms/op
     p(50.0000) =      5.374 ms/op
     p(90.0000) =      6.750 ms/op
     p(95.0000) =      7.519 ms/op
     p(99.0000) =     10.315 ms/op
     p(99.9000) =     23.136 ms/op
     p(99.9900) =     47.901 ms/op
     p(99.9990) =     49.957 ms/op
     p(99.9999) =     50.004 ms/op
    p(100.0000) =     50.004 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 19.070 ±(99.9%) 0.279 ms/op
# Warmup Iteration   2: 7.428 ±(99.9%) 0.056 ms/op
# Warmup Iteration   3: 6.036 ±(99.9%) 0.025 ms/op
Iteration   1: 5.804 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   1.909 ms/op
                 getUser·p0.50:   5.513 ms/op
                 getUser·p0.90:   6.947 ms/op
                 getUser·p0.95:   8.274 ms/op
                 getUser·p0.99:   11.403 ms/op
                 getUser·p0.999:  16.450 ms/op
                 getUser·p0.9999: 28.341 ms/op
                 getUser·p1.00:   29.393 ms/op

Iteration   2: 5.851 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   2.351 ms/op
                 getUser·p0.50:   5.464 ms/op
                 getUser·p0.90:   7.193 ms/op
                 getUser·p0.95:   8.651 ms/op
                 getUser·p0.99:   10.846 ms/op
                 getUser·p0.999:  30.588 ms/op
                 getUser·p0.9999: 34.643 ms/op
                 getUser·p1.00:   35.455 ms/op

Iteration   3: 5.514 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   3.305 ms/op
                 getUser·p0.50:   5.243 ms/op
                 getUser·p0.90:   6.504 ms/op
                 getUser·p0.95:   7.266 ms/op
                 getUser·p0.99:   10.240 ms/op
                 getUser·p0.999:  28.148 ms/op
                 getUser·p0.9999: 30.802 ms/op
                 getUser·p1.00:   31.293 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 167843
  mean =      5.719 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4 
    [ 2.500,  5.000) = 37728 
    [ 5.000,  7.500) = 119059 
    [ 7.500, 10.000) = 8258 
    [10.000, 12.500) = 1971 
    [12.500, 15.000) = 390 
    [15.000, 17.500) = 208 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 39 
    [27.500, 30.000) = 63 
    [30.000, 32.500) = 69 
    [32.500, 35.000) = 15 
    [35.000, 37.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.909 ms/op
     p(50.0000) =      5.390 ms/op
     p(90.0000) =      6.865 ms/op
     p(95.0000) =      8.069 ms/op
     p(99.0000) =     10.863 ms/op
     p(99.9000) =     25.960 ms/op
     p(99.9900) =     32.712 ms/op
     p(99.9990) =     35.411 ms/op
     p(99.9999) =     35.455 ms/op
    p(100.0000) =     35.455 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 21.659 ±(99.9%) 0.384 ms/op
# Warmup Iteration   2: 8.311 ±(99.9%) 0.057 ms/op
# Warmup Iteration   3: 6.897 ±(99.9%) 0.030 ms/op
Iteration   1: 6.674 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   2.380 ms/op
                 listUser·p0.50:   6.250 ms/op
                 listUser·p0.90:   8.217 ms/op
                 listUser·p0.95:   9.454 ms/op
                 listUser·p0.99:   12.694 ms/op
                 listUser·p0.999:  28.445 ms/op
                 listUser·p0.9999: 31.785 ms/op
                 listUser·p1.00:   32.178 ms/op

Iteration   2: 6.820 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   3.236 ms/op
                 listUser·p0.50:   6.480 ms/op
                 listUser·p0.90:   8.118 ms/op
                 listUser·p0.95:   9.308 ms/op
                 listUser·p0.99:   12.386 ms/op
                 listUser·p0.999:  33.561 ms/op
                 listUser·p0.9999: 35.934 ms/op
                 listUser·p1.00:   36.700 ms/op

Iteration   3: 6.688 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   2.593 ms/op
                 listUser·p0.50:   6.291 ms/op
                 listUser·p0.90:   8.110 ms/op
                 listUser·p0.95:   9.519 ms/op
                 listUser·p0.99:   12.829 ms/op
                 listUser·p0.999:  29.245 ms/op
                 listUser·p0.9999: 33.444 ms/op
                 listUser·p1.00:   33.948 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 142627
  mean =      6.726 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 2932 
    [ 5.000,  7.500) = 116353 
    [ 7.500, 10.000) = 17846 
    [10.000, 12.500) = 3968 
    [12.500, 15.000) = 872 
    [15.000, 17.500) = 333 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 44 
    [27.500, 30.000) = 80 
    [30.000, 32.500) = 71 
    [32.500, 35.000) = 51 
    [35.000, 37.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      2.380 ms/op
     p(50.0000) =      6.349 ms/op
     p(90.0000) =      8.151 ms/op
     p(95.0000) =      9.437 ms/op
     p(99.0000) =     12.698 ms/op
     p(99.9000) =     30.015 ms/op
     p(99.9900) =     35.389 ms/op
     p(99.9990) =     36.505 ms/op
     p(99.9999) =     36.700 ms/op
    p(100.0000) =     36.700 ms/op


# Run complete. Total time: 00:13:18

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.419 ± 2.288  ops/ms
ClientPb.existUser                       thrpt       3   5.866 ± 3.218  ops/ms
ClientPb.getUser                         thrpt       3   5.634 ± 2.162  ops/ms
ClientPb.listUser                        thrpt       3   4.822 ± 0.191  ops/ms
ClientPb.createUser                       avgt       3   5.603 ± 1.382   ms/op
ClientPb.existUser                        avgt       3   5.398 ± 3.319   ms/op
ClientPb.getUser                          avgt       3   5.607 ± 1.848   ms/op
ClientPb.listUser                         avgt       3   6.552 ± 1.837   ms/op
ClientPb.createUser                     sample  171941   5.582 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.694           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.292           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.857           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.733           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.174           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.662           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.022           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.063           ms/op
ClientPb.existUser                      sample  170942   5.616 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.306           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.374           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.750           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.519           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.315           ms/op
ClientPb.existUser:existUser·p0.999     sample          23.136           ms/op
ClientPb.existUser:existUser·p0.9999    sample          47.901           ms/op
ClientPb.existUser:existUser·p1.00      sample          50.004           ms/op
ClientPb.getUser                        sample  167843   5.719 ± 0.012   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.909           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.390           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.865           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.069           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.863           ms/op
ClientPb.getUser:getUser·p0.999         sample          25.960           ms/op
ClientPb.getUser:getUser·p0.9999        sample          32.712           ms/op
ClientPb.getUser:getUser·p1.00          sample          35.455           ms/op
ClientPb.listUser                       sample  142627   6.726 ± 0.015   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.380           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.349           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.151           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.437           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.698           ms/op
ClientPb.listUser:listUser·p0.999       sample          30.015           ms/op
ClientPb.listUser:listUser·p0.9999      sample          35.389           ms/op
ClientPb.listUser:listUser·p1.00        sample          36.700           ms/op
