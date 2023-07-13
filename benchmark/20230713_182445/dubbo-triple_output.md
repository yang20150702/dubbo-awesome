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
# Warmup Iteration   1: 2.094 ops/ms
# Warmup Iteration   2: 5.375 ops/ms
# Warmup Iteration   3: 8.828 ops/ms
Iteration   1: 9.125 ops/ms
Iteration   2: 9.812 ops/ms
Iteration   3: 9.641 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.526 ±(99.9%) 6.519 ops/ms [Average]
  (min, avg, max) = (9.125, 9.526, 9.812), stdev = 0.357
  CI (99.9%): [3.007, 16.045] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.717 ops/ms
# Warmup Iteration   2: 8.733 ops/ms
# Warmup Iteration   3: 9.723 ops/ms
Iteration   1: 10.005 ops/ms
Iteration   2: 9.588 ops/ms
Iteration   3: 9.734 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.776 ±(99.9%) 3.857 ops/ms [Average]
  (min, avg, max) = (9.588, 9.776, 10.005), stdev = 0.211
  CI (99.9%): [5.919, 13.633] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.058 ops/ms
# Warmup Iteration   2: 8.383 ops/ms
# Warmup Iteration   3: 8.767 ops/ms
Iteration   1: 9.421 ops/ms
Iteration   2: 9.377 ops/ms
Iteration   3: 9.375 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.391 ±(99.9%) 0.481 ops/ms [Average]
  (min, avg, max) = (9.375, 9.391, 9.421), stdev = 0.026
  CI (99.9%): [8.910, 9.872] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 2.755 ops/ms
# Warmup Iteration   2: 7.431 ops/ms
# Warmup Iteration   3: 7.838 ops/ms
Iteration   1: 8.008 ops/ms
Iteration   2: 8.204 ops/ms
Iteration   3: 7.982 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.065 ±(99.9%) 2.218 ops/ms [Average]
  (min, avg, max) = (7.982, 8.065, 8.204), stdev = 0.122
  CI (99.9%): [5.847, 10.282] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 8.843 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.895 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.622 ±(99.9%) 0.003 ms/op
Iteration   1: 3.434 ±(99.9%) 0.007 ms/op
Iteration   2: 3.498 ±(99.9%) 0.004 ms/op
Iteration   3: 3.366 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.432 ±(99.9%) 1.204 ms/op [Average]
  (min, avg, max) = (3.366, 3.432, 3.498), stdev = 0.066
  CI (99.9%): [2.228, 4.637] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 9.241 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.706 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.400 ±(99.9%) 0.007 ms/op
Iteration   1: 3.316 ±(99.9%) 0.008 ms/op
Iteration   2: 3.223 ±(99.9%) 0.007 ms/op
Iteration   3: 3.208 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.249 ±(99.9%) 1.067 ms/op [Average]
  (min, avg, max) = (3.208, 3.249, 3.316), stdev = 0.059
  CI (99.9%): [2.181, 4.316] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 8.845 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.666 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.629 ±(99.9%) 0.005 ms/op
Iteration   1: 3.476 ±(99.9%) 0.004 ms/op
Iteration   2: 3.379 ±(99.9%) 0.006 ms/op
Iteration   3: 3.392 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.416 ±(99.9%) 0.962 ms/op [Average]
  (min, avg, max) = (3.379, 3.416, 3.476), stdev = 0.053
  CI (99.9%): [2.454, 4.378] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 10.763 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.348 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.174 ±(99.9%) 0.007 ms/op
Iteration   1: 4.058 ±(99.9%) 0.007 ms/op
Iteration   2: 3.978 ±(99.9%) 0.010 ms/op
Iteration   3: 3.958 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.998 ±(99.9%) 0.966 ms/op [Average]
  (min, avg, max) = (3.958, 3.998, 4.058), stdev = 0.053
  CI (99.9%): [3.033, 4.964] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 9.196 ±(99.9%) 0.137 ms/op
# Warmup Iteration   2: 4.054 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.539 ±(99.9%) 0.010 ms/op
Iteration   1: 3.396 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.307 ms/op
                 createUser·p0.50:   3.310 ms/op
                 createUser·p0.90:   3.785 ms/op
                 createUser·p0.95:   4.047 ms/op
                 createUser·p0.99:   5.612 ms/op
                 createUser·p0.999:  20.475 ms/op
                 createUser·p0.9999: 23.527 ms/op
                 createUser·p1.00:   24.150 ms/op

Iteration   2: 3.463 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.587 ms/op
                 createUser·p0.50:   3.387 ms/op
                 createUser·p0.90:   3.920 ms/op
                 createUser·p0.95:   4.334 ms/op
                 createUser·p0.99:   5.751 ms/op
                 createUser·p0.999:  24.626 ms/op
                 createUser·p0.9999: 29.065 ms/op
                 createUser·p1.00:   30.048 ms/op

Iteration   3: 3.355 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.495 ms/op
                 createUser·p0.50:   3.285 ms/op
                 createUser·p0.90:   3.658 ms/op
                 createUser·p0.95:   3.879 ms/op
                 createUser·p0.99:   4.923 ms/op
                 createUser·p0.999:  18.932 ms/op
                 createUser·p0.9999: 26.509 ms/op
                 createUser·p1.00:   27.066 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 281865
  mean =      3.404 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10346 
    [ 2.500,  5.000) = 266674 
    [ 5.000,  7.500) = 3798 
    [ 7.500, 10.000) = 469 
    [10.000, 12.500) = 150 
    [12.500, 15.000) = 92 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 59 
    [22.500, 25.000) = 77 
    [25.000, 27.500) = 97 
    [27.500, 30.000) = 34 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.307 ms/op
     p(50.0000) =      3.338 ms/op
     p(90.0000) =      3.764 ms/op
     p(95.0000) =      4.088 ms/op
     p(99.0000) =      5.612 ms/op
     p(99.9000) =     19.305 ms/op
     p(99.9900) =     28.076 ms/op
     p(99.9990) =     29.858 ms/op
     p(99.9999) =     30.048 ms/op
    p(100.0000) =     30.048 ms/op


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
# Warmup Iteration   1: 8.046 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 3.719 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.481 ±(99.9%) 0.009 ms/op
Iteration   1: 3.315 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.407 ms/op
                 existUser·p0.50:   3.207 ms/op
                 existUser·p0.90:   3.641 ms/op
                 existUser·p0.95:   3.916 ms/op
                 existUser·p0.99:   5.407 ms/op
                 existUser·p0.999:  15.931 ms/op
                 existUser·p0.9999: 32.486 ms/op
                 existUser·p1.00:   33.391 ms/op

Iteration   2: 3.417 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.015 ms/op
                 existUser·p0.50:   3.289 ms/op
                 existUser·p0.90:   3.871 ms/op
                 existUser·p0.95:   4.260 ms/op
                 existUser·p0.99:   6.275 ms/op
                 existUser·p0.999:  23.935 ms/op
                 existUser·p0.9999: 31.499 ms/op
                 existUser·p1.00:   32.244 ms/op

Iteration   3: 3.400 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.700 ms/op
                 existUser·p0.50:   3.228 ms/op
                 existUser·p0.90:   3.793 ms/op
                 existUser·p0.95:   4.186 ms/op
                 existUser·p0.99:   6.372 ms/op
                 existUser·p0.999:  12.025 ms/op
                 existUser·p0.9999: 32.014 ms/op
                 existUser·p1.00:   32.637 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 284105
  mean =      3.377 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8513 
    [ 2.500,  5.000) = 268406 
    [ 5.000,  7.500) = 6012 
    [ 7.500, 10.000) = 620 
    [10.000, 12.500) = 282 
    [12.500, 15.000) = 16 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 55 
    [25.000, 27.500) = 47 
    [27.500, 30.000) = 26 
    [30.000, 32.500) = 100 
    [32.500, 35.000) = 10 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.015 ms/op
     p(50.0000) =      3.248 ms/op
     p(90.0000) =      3.768 ms/op
     p(95.0000) =      4.141 ms/op
     p(99.0000) =      5.964 ms/op
     p(99.9000) =     12.186 ms/op
     p(99.9900) =     32.113 ms/op
     p(99.9990) =     33.017 ms/op
     p(99.9999) =     33.391 ms/op
    p(100.0000) =     33.391 ms/op


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
# Warmup Iteration   1: 8.447 ±(99.9%) 0.127 ms/op
# Warmup Iteration   2: 3.863 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.587 ±(99.9%) 0.011 ms/op
Iteration   1: 3.562 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.235 ms/op
                 getUser·p0.50:   3.424 ms/op
                 getUser·p0.90:   3.969 ms/op
                 getUser·p0.95:   4.514 ms/op
                 getUser·p0.99:   7.310 ms/op
                 getUser·p0.999:  12.634 ms/op
                 getUser·p0.9999: 23.398 ms/op
                 getUser·p1.00:   24.019 ms/op

Iteration   2: 3.363 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.309 ms/op
                 getUser·p0.50:   3.269 ms/op
                 getUser·p0.90:   3.670 ms/op
                 getUser·p0.95:   3.842 ms/op
                 getUser·p0.99:   5.121 ms/op
                 getUser·p0.999:  23.590 ms/op
                 getUser·p0.9999: 34.242 ms/op
                 getUser·p1.00:   34.734 ms/op

Iteration   3: 3.575 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.925 ms/op
                 getUser·p0.50:   3.457 ms/op
                 getUser·p0.90:   4.149 ms/op
                 getUser·p0.95:   4.530 ms/op
                 getUser·p0.99:   6.441 ms/op
                 getUser·p0.999:  19.464 ms/op
                 getUser·p0.9999: 27.337 ms/op
                 getUser·p1.00:   28.377 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 274229
  mean =      3.497 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7127 
    [ 2.500,  5.000) = 259076 
    [ 5.000,  7.500) = 6607 
    [ 7.500, 10.000) = 948 
    [10.000, 12.500) = 187 
    [12.500, 15.000) = 18 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 57 
    [25.000, 27.500) = 64 
    [27.500, 30.000) = 16 
    [30.000, 32.500) = 28 
    [32.500, 35.000) = 26 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.925 ms/op
     p(50.0000) =      3.391 ms/op
     p(90.0000) =      3.936 ms/op
     p(95.0000) =      4.276 ms/op
     p(99.0000) =      6.652 ms/op
     p(99.9000) =     14.201 ms/op
     p(99.9900) =     32.305 ms/op
     p(99.9990) =     34.554 ms/op
     p(99.9999) =     34.734 ms/op
    p(100.0000) =     34.734 ms/op


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
# Warmup Iteration   1: 10.591 ±(99.9%) 0.142 ms/op
# Warmup Iteration   2: 4.590 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.213 ±(99.9%) 0.014 ms/op
Iteration   1: 4.120 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.452 ms/op
                 listUser·p0.50:   3.932 ms/op
                 listUser·p0.90:   4.489 ms/op
                 listUser·p0.95:   5.046 ms/op
                 listUser·p0.99:   7.750 ms/op
                 listUser·p0.999:  21.365 ms/op
                 listUser·p0.9999: 24.132 ms/op
                 listUser·p1.00:   24.445 ms/op

Iteration   2: 4.049 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.011 ms/op
                 listUser·p0.50:   3.875 ms/op
                 listUser·p0.90:   4.465 ms/op
                 listUser·p0.95:   4.850 ms/op
                 listUser·p0.99:   7.725 ms/op
                 listUser·p0.999:  16.777 ms/op
                 listUser·p0.9999: 18.812 ms/op
                 listUser·p1.00:   19.464 ms/op

Iteration   3: 4.172 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.245 ms/op
                 listUser·p0.50:   4.059 ms/op
                 listUser·p0.90:   4.522 ms/op
                 listUser·p0.95:   4.956 ms/op
                 listUser·p0.99:   7.758 ms/op
                 listUser·p0.999:  14.139 ms/op
                 listUser·p0.9999: 17.411 ms/op
                 listUser·p1.00:   19.595 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 233377
  mean =      4.113 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26 
    [ 2.500,  5.000) = 222167 
    [ 5.000,  7.500) = 8501 
    [ 7.500, 10.000) = 1840 
    [10.000, 12.500) = 334 
    [12.500, 15.000) = 206 
    [15.000, 17.500) = 148 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 50 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.452 ms/op
     p(50.0000) =      3.932 ms/op
     p(90.0000) =      4.489 ms/op
     p(95.0000) =      4.940 ms/op
     p(99.0000) =      7.750 ms/op
     p(99.9000) =     16.116 ms/op
     p(99.9900) =     23.527 ms/op
     p(99.9990) =     24.390 ms/op
     p(99.9999) =     24.445 ms/op
    p(100.0000) =     24.445 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.526 ± 6.519  ops/ms
ClientPb.existUser                       thrpt       3   9.776 ± 3.857  ops/ms
ClientPb.getUser                         thrpt       3   9.391 ± 0.481  ops/ms
ClientPb.listUser                        thrpt       3   8.065 ± 2.218  ops/ms
ClientPb.createUser                       avgt       3   3.432 ± 1.204   ms/op
ClientPb.existUser                        avgt       3   3.249 ± 1.067   ms/op
ClientPb.getUser                          avgt       3   3.416 ± 0.962   ms/op
ClientPb.listUser                         avgt       3   3.998 ± 0.966   ms/op
ClientPb.createUser                     sample  281865   3.404 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.307           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.338           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.764           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.088           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.612           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.305           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.076           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.048           ms/op
ClientPb.existUser                      sample  284105   3.377 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.015           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.248           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.768           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.141           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.964           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.186           ms/op
ClientPb.existUser:existUser·p0.9999    sample          32.113           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.391           ms/op
ClientPb.getUser                        sample  274229   3.497 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.925           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.391           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.936           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.276           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.652           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.201           ms/op
ClientPb.getUser:getUser·p0.9999        sample          32.305           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.734           ms/op
ClientPb.listUser                       sample  233377   4.113 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.452           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.932           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.489           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.940           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.750           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.116           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.527           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.445           ms/op
