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
# Warmup Iteration   1: 0.917 ops/ms
# Warmup Iteration   2: 2.169 ops/ms
# Warmup Iteration   3: 4.889 ops/ms
Iteration   1: 5.565 ops/ms
Iteration   2: 5.525 ops/ms
Iteration   3: 5.855 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.649 ±(99.9%) 3.289 ops/ms [Average]
  (min, avg, max) = (5.525, 5.649, 5.855), stdev = 0.180
  CI (99.9%): [2.359, 8.938] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:17
# Fork: 1 of 1
# Warmup Iteration   1: 1.499 ops/ms
# Warmup Iteration   2: 4.068 ops/ms
# Warmup Iteration   3: 5.481 ops/ms
Iteration   1: 5.682 ops/ms
Iteration   2: 6.001 ops/ms
Iteration   3: 6.213 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.965 ±(99.9%) 4.881 ops/ms [Average]
  (min, avg, max) = (5.682, 5.965, 6.213), stdev = 0.268
  CI (99.9%): [1.084, 10.846] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:04
# Fork: 1 of 1
# Warmup Iteration   1: 1.593 ops/ms
# Warmup Iteration   2: 4.667 ops/ms
# Warmup Iteration   3: 5.742 ops/ms
Iteration   1: 5.983 ops/ms
Iteration   2: 5.860 ops/ms
Iteration   3: 5.897 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.914 ±(99.9%) 1.157 ops/ms [Average]
  (min, avg, max) = (5.860, 5.914, 5.983), stdev = 0.063
  CI (99.9%): [4.757, 7.070] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 1.690 ops/ms
# Warmup Iteration   2: 4.008 ops/ms
# Warmup Iteration   3: 4.802 ops/ms
Iteration   1: 4.803 ops/ms
Iteration   2: 4.857 ops/ms
Iteration   3: 5.238 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.966 ±(99.9%) 4.331 ops/ms [Average]
  (min, avg, max) = (4.803, 4.966, 5.238), stdev = 0.237
  CI (99.9%): [0.636, 9.297] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 18.171 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 6.673 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.910 ±(99.9%) 0.008 ms/op
Iteration   1: 5.368 ±(99.9%) 0.018 ms/op
Iteration   2: 5.475 ±(99.9%) 0.013 ms/op
Iteration   3: 5.545 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.463 ±(99.9%) 1.629 ms/op [Average]
  (min, avg, max) = (5.368, 5.463, 5.545), stdev = 0.089
  CI (99.9%): [3.834, 7.092] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 18.352 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 6.333 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 5.651 ±(99.9%) 0.004 ms/op
Iteration   1: 5.482 ±(99.9%) 0.008 ms/op
Iteration   2: 5.307 ±(99.9%) 0.015 ms/op
Iteration   3: 5.309 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.366 ±(99.9%) 1.837 ms/op [Average]
  (min, avg, max) = (5.307, 5.366, 5.482), stdev = 0.101
  CI (99.9%): [3.529, 7.203] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 20.255 ±(99.9%) 0.098 ms/op
# Warmup Iteration   2: 6.925 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 5.656 ±(99.9%) 0.014 ms/op
Iteration   1: 5.644 ±(99.9%) 0.011 ms/op
Iteration   2: 5.516 ±(99.9%) 0.011 ms/op
Iteration   3: 5.379 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.513 ±(99.9%) 2.413 ms/op [Average]
  (min, avg, max) = (5.379, 5.513, 5.644), stdev = 0.132
  CI (99.9%): [3.100, 7.926] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 20.281 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 8.341 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 6.628 ±(99.9%) 0.014 ms/op
Iteration   1: 6.726 ±(99.9%) 0.014 ms/op
Iteration   2: 6.691 ±(99.9%) 0.009 ms/op
Iteration   3: 6.668 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.695 ±(99.9%) 0.532 ms/op [Average]
  (min, avg, max) = (6.668, 6.695, 6.726), stdev = 0.029
  CI (99.9%): [6.163, 7.228] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 18.096 ±(99.9%) 0.363 ms/op
# Warmup Iteration   2: 7.763 ±(99.9%) 0.057 ms/op
# Warmup Iteration   3: 6.028 ±(99.9%) 0.029 ms/op
Iteration   1: 5.348 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   2.388 ms/op
                 createUser·p0.50:   5.071 ms/op
                 createUser·p0.90:   6.455 ms/op
                 createUser·p0.95:   7.447 ms/op
                 createUser·p0.99:   10.076 ms/op
                 createUser·p0.999:  26.421 ms/op
                 createUser·p0.9999: 29.656 ms/op
                 createUser·p1.00:   31.261 ms/op

Iteration   2: 5.633 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   2.355 ms/op
                 createUser·p0.50:   5.300 ms/op
                 createUser·p0.90:   7.135 ms/op
                 createUser·p0.95:   8.118 ms/op
                 createUser·p0.99:   10.060 ms/op
                 createUser·p0.999:  27.869 ms/op
                 createUser·p0.9999: 34.297 ms/op
                 createUser·p1.00:   37.356 ms/op

Iteration   3: 5.687 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   2.499 ms/op
                 createUser·p0.50:   5.349 ms/op
                 createUser·p0.90:   6.988 ms/op
                 createUser·p0.95:   8.086 ms/op
                 createUser·p0.99:   11.518 ms/op
                 createUser·p0.999:  21.188 ms/op
                 createUser·p0.9999: 33.826 ms/op
                 createUser·p1.00:   34.537 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 172803
  mean =      5.552 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6 
    [ 2.500,  5.000) = 62226 
    [ 5.000,  7.500) = 99207 
    [ 7.500, 10.000) = 9171 
    [10.000, 12.500) = 1456 
    [12.500, 15.000) = 369 
    [15.000, 17.500) = 101 
    [17.500, 20.000) = 55 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 34 
    [27.500, 30.000) = 61 
    [30.000, 32.500) = 38 
    [32.500, 35.000) = 32 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      2.355 ms/op
     p(50.0000) =      5.210 ms/op
     p(90.0000) =      6.889 ms/op
     p(95.0000) =      7.963 ms/op
     p(99.0000) =     10.453 ms/op
     p(99.9000) =     22.518 ms/op
     p(99.9900) =     33.545 ms/op
     p(99.9990) =     36.544 ms/op
     p(99.9999) =     37.356 ms/op
    p(100.0000) =     37.356 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 17.031 ±(99.9%) 0.287 ms/op
# Warmup Iteration   2: 6.099 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 5.502 ±(99.9%) 0.021 ms/op
Iteration   1: 5.291 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   2.343 ms/op
                 existUser·p0.50:   4.948 ms/op
                 existUser·p0.90:   6.783 ms/op
                 existUser·p0.95:   7.815 ms/op
                 existUser·p0.99:   9.634 ms/op
                 existUser·p0.999:  14.942 ms/op
                 existUser·p0.9999: 27.524 ms/op
                 existUser·p1.00:   28.213 ms/op

Iteration   2: 5.478 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   2.372 ms/op
                 existUser·p0.50:   5.169 ms/op
                 existUser·p0.90:   6.652 ms/op
                 existUser·p0.95:   7.766 ms/op
                 existUser·p0.99:   11.354 ms/op
                 existUser·p0.999:  28.646 ms/op
                 existUser·p0.9999: 35.127 ms/op
                 existUser·p1.00:   36.831 ms/op

Iteration   3: 5.225 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   2.474 ms/op
                 existUser·p0.50:   4.948 ms/op
                 existUser·p0.90:   6.259 ms/op
                 existUser·p0.95:   7.021 ms/op
                 existUser·p0.99:   9.339 ms/op
                 existUser·p0.999:  27.996 ms/op
                 existUser·p0.9999: 31.835 ms/op
                 existUser·p1.00:   34.406 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 180006
  mean =      5.329 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13 
    [ 2.500,  5.000) = 88361 
    [ 5.000,  7.500) = 82418 
    [ 7.500, 10.000) = 7253 
    [10.000, 12.500) = 1216 
    [12.500, 15.000) = 432 
    [15.000, 17.500) = 128 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 16 
    [27.500, 30.000) = 62 
    [30.000, 32.500) = 54 
    [32.500, 35.000) = 10 
    [35.000, 37.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      2.343 ms/op
     p(50.0000) =      5.014 ms/op
     p(90.0000) =      6.545 ms/op
     p(95.0000) =      7.537 ms/op
     p(99.0000) =     10.256 ms/op
     p(99.9000) =     17.989 ms/op
     p(99.9900) =     32.375 ms/op
     p(99.9990) =     35.678 ms/op
     p(99.9999) =     36.831 ms/op
    p(100.0000) =     36.831 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 20.637 ±(99.9%) 0.350 ms/op
# Warmup Iteration   2: 7.141 ±(99.9%) 0.053 ms/op
# Warmup Iteration   3: 5.699 ±(99.9%) 0.022 ms/op
Iteration   1: 5.565 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   2.413 ms/op
                 getUser·p0.50:   5.243 ms/op
                 getUser·p0.90:   6.767 ms/op
                 getUser·p0.95:   8.290 ms/op
                 getUser·p0.99:   10.902 ms/op
                 getUser·p0.999:  24.117 ms/op
                 getUser·p0.9999: 39.142 ms/op
                 getUser·p1.00:   39.780 ms/op

Iteration   2: 5.494 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   2.306 ms/op
                 getUser·p0.50:   5.202 ms/op
                 getUser·p0.90:   6.611 ms/op
                 getUser·p0.95:   7.741 ms/op
                 getUser·p0.99:   10.486 ms/op
                 getUser·p0.999:  26.744 ms/op
                 getUser·p0.9999: 30.776 ms/op
                 getUser·p1.00:   31.162 ms/op

Iteration   3: 5.314 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   2.793 ms/op
                 getUser·p0.50:   5.046 ms/op
                 getUser·p0.90:   6.398 ms/op
                 getUser·p0.95:   7.291 ms/op
                 getUser·p0.99:   9.814 ms/op
                 getUser·p0.999:  30.171 ms/op
                 getUser·p0.9999: 36.635 ms/op
                 getUser·p1.00:   37.487 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 175862
  mean =      5.455 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4 
    [ 2.500,  5.000) = 69062 
    [ 5.000,  7.500) = 96753 
    [ 7.500, 10.000) = 7894 
    [10.000, 12.500) = 1395 
    [12.500, 15.000) = 353 
    [15.000, 17.500) = 91 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 56 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 25 
    [27.500, 30.000) = 37 
    [30.000, 32.500) = 47 
    [32.500, 35.000) = 16 
    [35.000, 37.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      2.306 ms/op
     p(50.0000) =      5.153 ms/op
     p(90.0000) =      6.570 ms/op
     p(95.0000) =      7.774 ms/op
     p(99.0000) =     10.486 ms/op
     p(99.9000) =     24.576 ms/op
     p(99.9900) =     37.541 ms/op
     p(99.9990) =     39.731 ms/op
     p(99.9999) =     39.780 ms/op
    p(100.0000) =     39.780 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 22.165 ±(99.9%) 0.373 ms/op
# Warmup Iteration   2: 8.404 ±(99.9%) 0.063 ms/op
# Warmup Iteration   3: 6.763 ±(99.9%) 0.028 ms/op
Iteration   1: 6.618 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   2.212 ms/op
                 listUser·p0.50:   6.136 ms/op
                 listUser·p0.90:   8.151 ms/op
                 listUser·p0.95:   9.634 ms/op
                 listUser·p0.99:   13.396 ms/op
                 listUser·p0.999:  27.383 ms/op
                 listUser·p0.9999: 30.534 ms/op
                 listUser·p1.00:   31.850 ms/op

Iteration   2: 6.431 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   3.281 ms/op
                 listUser·p0.50:   6.078 ms/op
                 listUser·p0.90:   7.676 ms/op
                 listUser·p0.95:   8.684 ms/op
                 listUser·p0.99:   12.059 ms/op
                 listUser·p0.999:  32.619 ms/op
                 listUser·p0.9999: 34.998 ms/op
                 listUser·p1.00:   36.307 ms/op

Iteration   3: 6.618 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   3.654 ms/op
                 listUser·p0.50:   6.316 ms/op
                 listUser·p0.90:   7.823 ms/op
                 listUser·p0.95:   9.126 ms/op
                 listUser·p0.99:   11.780 ms/op
                 listUser·p0.999:  25.861 ms/op
                 listUser·p0.9999: 31.960 ms/op
                 listUser·p1.00:   32.539 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 146457
  mean =      6.555 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 3606 
    [ 5.000,  7.500) = 123192 
    [ 7.500, 10.000) = 15139 
    [10.000, 12.500) = 3046 
    [12.500, 15.000) = 868 
    [15.000, 17.500) = 182 
    [17.500, 20.000) = 65 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 76 
    [25.000, 27.500) = 60 
    [27.500, 30.000) = 61 
    [30.000, 32.500) = 62 
    [32.500, 35.000) = 50 
    [35.000, 37.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      2.212 ms/op
     p(50.0000) =      6.185 ms/op
     p(90.0000) =      7.897 ms/op
     p(95.0000) =      9.110 ms/op
     p(99.0000) =     12.501 ms/op
     p(99.9000) =     28.574 ms/op
     p(99.9900) =     34.692 ms/op
     p(99.9990) =     36.094 ms/op
     p(99.9999) =     36.307 ms/op
    p(100.0000) =     36.307 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.649 ± 3.289  ops/ms
ClientPb.existUser                       thrpt       3   5.965 ± 4.881  ops/ms
ClientPb.getUser                         thrpt       3   5.914 ± 1.157  ops/ms
ClientPb.listUser                        thrpt       3   4.966 ± 4.331  ops/ms
ClientPb.createUser                       avgt       3   5.463 ± 1.629   ms/op
ClientPb.existUser                        avgt       3   5.366 ± 1.837   ms/op
ClientPb.getUser                          avgt       3   5.513 ± 2.413   ms/op
ClientPb.listUser                         avgt       3   6.695 ± 0.532   ms/op
ClientPb.createUser                     sample  172803   5.552 ± 0.012   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.355           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.210           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.889           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.963           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.453           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.518           ms/op
ClientPb.createUser:createUser·p0.9999  sample          33.545           ms/op
ClientPb.createUser:createUser·p1.00    sample          37.356           ms/op
ClientPb.existUser                      sample  180006   5.329 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.343           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.014           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.545           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.537           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.256           ms/op
ClientPb.existUser:existUser·p0.999     sample          17.989           ms/op
ClientPb.existUser:existUser·p0.9999    sample          32.375           ms/op
ClientPb.existUser:existUser·p1.00      sample          36.831           ms/op
ClientPb.getUser                        sample  175862   5.455 ± 0.012   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.306           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.153           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.570           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.774           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.486           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.576           ms/op
ClientPb.getUser:getUser·p0.9999        sample          37.541           ms/op
ClientPb.getUser:getUser·p1.00          sample          39.780           ms/op
ClientPb.listUser                       sample  146457   6.555 ± 0.015   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.212           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.185           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.897           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.110           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.501           ms/op
ClientPb.listUser:listUser·p0.999       sample          28.574           ms/op
ClientPb.listUser:listUser·p0.9999      sample          34.692           ms/op
ClientPb.listUser:listUser·p1.00        sample          36.307           ms/op
