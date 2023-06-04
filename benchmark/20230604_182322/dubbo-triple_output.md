# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.021 ops/ms
# Warmup Iteration   2: 5.370 ops/ms
# Warmup Iteration   3: 8.753 ops/ms
Iteration   1: 9.057 ops/ms
Iteration   2: 8.996 ops/ms
Iteration   3: 9.172 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.075 ±(99.9%) 1.635 ops/ms [Average]
  (min, avg, max) = (8.996, 9.075, 9.172), stdev = 0.090
  CI (99.9%): [7.439, 10.710] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 2.693 ops/ms
# Warmup Iteration   2: 7.935 ops/ms
# Warmup Iteration   3: 9.314 ops/ms
Iteration   1: 9.346 ops/ms
Iteration   2: 9.620 ops/ms
Iteration   3: 9.532 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.499 ±(99.9%) 2.556 ops/ms [Average]
  (min, avg, max) = (9.346, 9.499, 9.620), stdev = 0.140
  CI (99.9%): [6.943, 12.056] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.830 ops/ms
# Warmup Iteration   2: 7.753 ops/ms
# Warmup Iteration   3: 8.851 ops/ms
Iteration   1: 9.400 ops/ms
Iteration   2: 9.365 ops/ms
Iteration   3: 9.469 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.411 ±(99.9%) 0.970 ops/ms [Average]
  (min, avg, max) = (9.365, 9.411, 9.469), stdev = 0.053
  CI (99.9%): [8.442, 10.381] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.005 ops/ms
# Warmup Iteration   2: 7.276 ops/ms
# Warmup Iteration   3: 8.102 ops/ms
Iteration   1: 7.909 ops/ms
Iteration   2: 8.086 ops/ms
Iteration   3: 8.182 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.059 ±(99.9%) 2.525 ops/ms [Average]
  (min, avg, max) = (7.909, 8.059, 8.182), stdev = 0.138
  CI (99.9%): [5.534, 10.583] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 10.633 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.758 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.599 ±(99.9%) 0.007 ms/op
Iteration   1: 3.462 ±(99.9%) 0.002 ms/op
Iteration   2: 3.372 ±(99.9%) 0.009 ms/op
Iteration   3: 3.372 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.402 ±(99.9%) 0.951 ms/op [Average]
  (min, avg, max) = (3.372, 3.402, 3.462), stdev = 0.052
  CI (99.9%): [2.451, 4.353] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 8.346 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.511 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.282 ±(99.9%) 0.008 ms/op
Iteration   1: 3.150 ±(99.9%) 0.006 ms/op
Iteration   2: 3.230 ±(99.9%) 0.006 ms/op
Iteration   3: 3.199 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.193 ±(99.9%) 0.730 ms/op [Average]
  (min, avg, max) = (3.150, 3.193, 3.230), stdev = 0.040
  CI (99.9%): [2.463, 3.923] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 8.560 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.016 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.564 ±(99.9%) 0.004 ms/op
Iteration   1: 3.450 ±(99.9%) 0.008 ms/op
Iteration   2: 3.407 ±(99.9%) 0.004 ms/op
Iteration   3: 3.333 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.397 ±(99.9%) 1.085 ms/op [Average]
  (min, avg, max) = (3.333, 3.397, 3.450), stdev = 0.059
  CI (99.9%): [2.312, 4.482] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 10.845 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.468 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.096 ±(99.9%) 0.008 ms/op
Iteration   1: 3.975 ±(99.9%) 0.009 ms/op
Iteration   2: 3.953 ±(99.9%) 0.009 ms/op
Iteration   3: 4.006 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.978 ±(99.9%) 0.486 ms/op [Average]
  (min, avg, max) = (3.953, 3.978, 4.006), stdev = 0.027
  CI (99.9%): [3.492, 4.464] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 9.058 ±(99.9%) 0.124 ms/op
# Warmup Iteration   2: 3.906 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.615 ±(99.9%) 0.011 ms/op
Iteration   1: 3.427 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.532 ms/op
                 createUser·p0.50:   3.355 ms/op
                 createUser·p0.90:   3.850 ms/op
                 createUser·p0.95:   4.088 ms/op
                 createUser·p0.99:   5.643 ms/op
                 createUser·p0.999:  19.368 ms/op
                 createUser·p0.9999: 22.501 ms/op
                 createUser·p1.00:   25.919 ms/op

Iteration   2: 3.410 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.550 ms/op
                 createUser·p0.50:   3.265 ms/op
                 createUser·p0.90:   3.854 ms/op
                 createUser·p0.95:   4.170 ms/op
                 createUser·p0.99:   5.743 ms/op
                 createUser·p0.999:  22.130 ms/op
                 createUser·p0.9999: 25.928 ms/op
                 createUser·p1.00:   27.296 ms/op

Iteration   3: 3.393 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.330 ms/op
                 createUser·p0.50:   3.260 ms/op
                 createUser·p0.90:   3.863 ms/op
                 createUser·p0.95:   4.108 ms/op
                 createUser·p0.99:   5.587 ms/op
                 createUser·p0.999:  18.491 ms/op
                 createUser·p0.9999: 27.314 ms/op
                 createUser·p1.00:   28.213 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 281295
  mean =      3.410 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3962 
    [ 2.500,  5.000) = 272058 
    [ 5.000,  7.500) = 4426 
    [ 7.500, 10.000) = 426 
    [10.000, 12.500) = 59 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 63 
    [20.000, 22.500) = 104 
    [22.500, 25.000) = 83 
    [25.000, 27.500) = 69 

  Percentiles, ms/op:
      p(0.0000) =      0.330 ms/op
     p(50.0000) =      3.285 ms/op
     p(90.0000) =      3.854 ms/op
     p(95.0000) =      4.116 ms/op
     p(99.0000) =      5.693 ms/op
     p(99.9000) =     19.370 ms/op
     p(99.9900) =     26.767 ms/op
     p(99.9990) =     27.433 ms/op
     p(99.9999) =     28.213 ms/op
    p(100.0000) =     28.213 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 9.497 ±(99.9%) 0.129 ms/op
# Warmup Iteration   2: 3.759 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.261 ±(99.9%) 0.007 ms/op
Iteration   1: 3.284 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.298 ms/op
                 existUser·p0.50:   3.203 ms/op
                 existUser·p0.90:   3.576 ms/op
                 existUser·p0.95:   3.899 ms/op
                 existUser·p0.99:   5.923 ms/op
                 existUser·p0.999:  9.726 ms/op
                 existUser·p0.9999: 28.869 ms/op
                 existUser·p1.00:   29.360 ms/op

Iteration   2: 3.307 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.630 ms/op
                 existUser·p0.50:   3.277 ms/op
                 existUser·p0.90:   3.662 ms/op
                 existUser·p0.95:   4.014 ms/op
                 existUser·p0.99:   5.431 ms/op
                 existUser·p0.999:  14.414 ms/op
                 existUser·p0.9999: 24.543 ms/op
                 existUser·p1.00:   25.264 ms/op

Iteration   3: 3.259 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.618 ms/op
                 existUser·p0.50:   3.207 ms/op
                 existUser·p0.90:   3.498 ms/op
                 existUser·p0.95:   3.789 ms/op
                 existUser·p0.99:   5.874 ms/op
                 existUser·p0.999:  11.000 ms/op
                 existUser·p0.9999: 24.456 ms/op
                 existUser·p1.00:   25.002 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 292363
  mean =      3.283 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18274 
    [ 2.500,  5.000) = 268204 
    [ 5.000,  7.500) = 4999 
    [ 7.500, 10.000) = 555 
    [10.000, 12.500) = 43 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 86 
    [22.500, 25.000) = 124 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      1.298 ms/op
     p(50.0000) =      3.236 ms/op
     p(90.0000) =      3.564 ms/op
     p(95.0000) =      3.924 ms/op
     p(99.0000) =      5.759 ms/op
     p(99.9000) =     10.971 ms/op
     p(99.9900) =     27.149 ms/op
     p(99.9990) =     29.269 ms/op
     p(99.9999) =     29.360 ms/op
    p(100.0000) =     29.360 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 10.158 ±(99.9%) 0.126 ms/op
# Warmup Iteration   2: 3.716 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.481 ±(99.9%) 0.010 ms/op
Iteration   1: 3.523 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.417 ms/op
                 getUser·p0.50:   3.396 ms/op
                 getUser·p0.90:   4.022 ms/op
                 getUser·p0.95:   4.628 ms/op
                 getUser·p0.99:   6.398 ms/op
                 getUser·p0.999:  20.514 ms/op
                 getUser·p0.9999: 22.738 ms/op
                 getUser·p1.00:   23.429 ms/op

Iteration   2: 3.457 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.382 ms/op
                 getUser·p0.50:   3.355 ms/op
                 getUser·p0.90:   3.789 ms/op
                 getUser·p0.95:   3.981 ms/op
                 getUser·p0.99:   6.070 ms/op
                 getUser·p0.999:  22.380 ms/op
                 getUser·p0.9999: 29.123 ms/op
                 getUser·p1.00:   30.441 ms/op

Iteration   3: 3.534 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.386 ms/op
                 getUser·p0.50:   3.367 ms/op
                 getUser·p0.90:   4.055 ms/op
                 getUser·p0.95:   4.489 ms/op
                 getUser·p0.99:   6.840 ms/op
                 getUser·p0.999:  19.513 ms/op
                 getUser·p0.9999: 26.344 ms/op
                 getUser·p1.00:   26.935 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 273979
  mean =      3.505 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6317 
    [ 2.500,  5.000) = 259492 
    [ 5.000,  7.500) = 6933 
    [ 7.500, 10.000) = 707 
    [10.000, 12.500) = 86 
    [12.500, 15.000) = 120 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 107 
    [22.500, 25.000) = 98 
    [25.000, 27.500) = 37 
    [27.500, 30.000) = 28 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.386 ms/op
     p(50.0000) =      3.375 ms/op
     p(90.0000) =      3.949 ms/op
     p(95.0000) =      4.342 ms/op
     p(99.0000) =      6.488 ms/op
     p(99.9000) =     20.022 ms/op
     p(99.9900) =     28.528 ms/op
     p(99.9990) =     30.286 ms/op
     p(99.9999) =     30.441 ms/op
    p(100.0000) =     30.441 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.978 ±(99.9%) 0.144 ms/op
# Warmup Iteration   2: 4.290 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.972 ±(99.9%) 0.012 ms/op
Iteration   1: 3.903 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.468 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   4.182 ms/op
                 listUser·p0.95:   4.506 ms/op
                 listUser·p0.99:   6.963 ms/op
                 listUser·p0.999:  18.186 ms/op
                 listUser·p0.9999: 22.308 ms/op
                 listUser·p1.00:   23.134 ms/op

Iteration   2: 3.945 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.913 ms/op
                 listUser·p0.50:   3.875 ms/op
                 listUser·p0.90:   4.137 ms/op
                 listUser·p0.95:   4.530 ms/op
                 listUser·p0.99:   7.172 ms/op
                 listUser·p0.999:  15.237 ms/op
                 listUser·p0.9999: 17.203 ms/op
                 listUser·p1.00:   17.236 ms/op

Iteration   3: 3.926 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.290 ms/op
                 listUser·p0.50:   3.871 ms/op
                 listUser·p0.90:   4.284 ms/op
                 listUser·p0.95:   4.571 ms/op
                 listUser·p0.99:   6.537 ms/op
                 listUser·p0.999:  15.712 ms/op
                 listUser·p0.9999: 23.953 ms/op
                 listUser·p1.00:   24.052 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 244470
  mean =      3.925 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31 
    [ 2.500,  5.000) = 237879 
    [ 5.000,  7.500) = 4814 
    [ 7.500, 10.000) = 977 
    [10.000, 12.500) = 258 
    [12.500, 15.000) = 157 
    [15.000, 17.500) = 232 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.913 ms/op
     p(50.0000) =      3.854 ms/op
     p(90.0000) =      4.194 ms/op
     p(95.0000) =      4.538 ms/op
     p(99.0000) =      6.947 ms/op
     p(99.9000) =     15.721 ms/op
     p(99.9900) =     22.610 ms/op
     p(99.9990) =     24.037 ms/op
     p(99.9999) =     24.052 ms/op
    p(100.0000) =     24.052 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.075 ± 1.635  ops/ms
ClientPb.existUser                       thrpt       3   9.499 ± 2.556  ops/ms
ClientPb.getUser                         thrpt       3   9.411 ± 0.970  ops/ms
ClientPb.listUser                        thrpt       3   8.059 ± 2.525  ops/ms
ClientPb.createUser                       avgt       3   3.402 ± 0.951   ms/op
ClientPb.existUser                        avgt       3   3.193 ± 0.730   ms/op
ClientPb.getUser                          avgt       3   3.397 ± 1.085   ms/op
ClientPb.listUser                         avgt       3   3.978 ± 0.486   ms/op
ClientPb.createUser                     sample  281295   3.410 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.330           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.285           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.854           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.116           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.693           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.370           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.767           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.213           ms/op
ClientPb.existUser                      sample  292363   3.283 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.298           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.236           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.564           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.924           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.759           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.971           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.149           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.360           ms/op
ClientPb.getUser                        sample  273979   3.505 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.386           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.375           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.949           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.342           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.488           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.022           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.528           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.441           ms/op
ClientPb.listUser                       sample  244470   3.925 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.913           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.854           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.194           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.538           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.947           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.721           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.610           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.052           ms/op
