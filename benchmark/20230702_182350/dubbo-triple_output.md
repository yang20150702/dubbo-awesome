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
# Warmup Iteration   1: 1.991 ops/ms
# Warmup Iteration   2: 5.597 ops/ms
# Warmup Iteration   3: 8.182 ops/ms
Iteration   1: 8.872 ops/ms
Iteration   2: 9.083 ops/ms
Iteration   3: 9.027 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.994 ±(99.9%) 1.994 ops/ms [Average]
  (min, avg, max) = (8.872, 8.994, 9.083), stdev = 0.109
  CI (99.9%): [7.000, 10.988] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.776 ops/ms
# Warmup Iteration   2: 7.934 ops/ms
# Warmup Iteration   3: 9.183 ops/ms
Iteration   1: 9.293 ops/ms
Iteration   2: 9.381 ops/ms
Iteration   3: 9.614 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.429 ±(99.9%) 3.022 ops/ms [Average]
  (min, avg, max) = (9.293, 9.429, 9.614), stdev = 0.166
  CI (99.9%): [6.407, 12.452] (assumes normal distribution)


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
# Warmup Iteration   1: 3.069 ops/ms
# Warmup Iteration   2: 8.414 ops/ms
# Warmup Iteration   3: 9.320 ops/ms
Iteration   1: 9.248 ops/ms
Iteration   2: 9.513 ops/ms
Iteration   3: 9.460 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.407 ±(99.9%) 2.556 ops/ms [Average]
  (min, avg, max) = (9.248, 9.407, 9.513), stdev = 0.140
  CI (99.9%): [6.851, 11.963] (assumes normal distribution)


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
# Warmup Iteration   1: 3.022 ops/ms
# Warmup Iteration   2: 7.196 ops/ms
# Warmup Iteration   3: 7.474 ops/ms
Iteration   1: 7.940 ops/ms
Iteration   2: 7.829 ops/ms
Iteration   3: 7.737 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.835 ±(99.9%) 1.852 ops/ms [Average]
  (min, avg, max) = (7.737, 7.835, 7.940), stdev = 0.102
  CI (99.9%): [5.983, 9.687] (assumes normal distribution)


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
# Warmup Iteration   1: 9.770 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.827 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.613 ±(99.9%) 0.008 ms/op
Iteration   1: 3.549 ±(99.9%) 0.007 ms/op
Iteration   2: 3.482 ±(99.9%) 0.005 ms/op
Iteration   3: 3.362 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.464 ±(99.9%) 1.733 ms/op [Average]
  (min, avg, max) = (3.362, 3.464, 3.549), stdev = 0.095
  CI (99.9%): [1.732, 5.197] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 8.336 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.638 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.424 ±(99.9%) 0.006 ms/op
Iteration   1: 3.391 ±(99.9%) 0.004 ms/op
Iteration   2: 3.334 ±(99.9%) 0.005 ms/op
Iteration   3: 3.329 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.351 ±(99.9%) 0.625 ms/op [Average]
  (min, avg, max) = (3.329, 3.351, 3.391), stdev = 0.034
  CI (99.9%): [2.727, 3.976] (assumes normal distribution)


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
# Warmup Iteration   1: 8.710 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.713 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.562 ±(99.9%) 0.005 ms/op
Iteration   1: 3.438 ±(99.9%) 0.004 ms/op
Iteration   2: 3.397 ±(99.9%) 0.006 ms/op
Iteration   3: 3.419 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.418 ±(99.9%) 0.375 ms/op [Average]
  (min, avg, max) = (3.397, 3.418, 3.438), stdev = 0.021
  CI (99.9%): [3.043, 3.792] (assumes normal distribution)


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
# Warmup Iteration   1: 11.145 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 4.575 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.135 ±(99.9%) 0.008 ms/op
Iteration   1: 3.937 ±(99.9%) 0.015 ms/op
Iteration   2: 3.969 ±(99.9%) 0.010 ms/op
Iteration   3: 3.983 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.963 ±(99.9%) 0.423 ms/op [Average]
  (min, avg, max) = (3.937, 3.963, 3.983), stdev = 0.023
  CI (99.9%): [3.540, 4.386] (assumes normal distribution)


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
# Warmup Iteration   1: 9.863 ±(99.9%) 0.129 ms/op
# Warmup Iteration   2: 3.997 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.409 ±(99.9%) 0.009 ms/op
Iteration   1: 3.345 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.534 ms/op
                 createUser·p0.50:   3.228 ms/op
                 createUser·p0.90:   3.719 ms/op
                 createUser·p0.95:   3.928 ms/op
                 createUser·p0.99:   5.718 ms/op
                 createUser·p0.999:  21.476 ms/op
                 createUser·p0.9999: 24.590 ms/op
                 createUser·p1.00:   25.166 ms/op

Iteration   2: 3.451 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.110 ms/op
                 createUser·p0.50:   3.305 ms/op
                 createUser·p0.90:   3.908 ms/op
                 createUser·p0.95:   4.182 ms/op
                 createUser·p0.99:   5.800 ms/op
                 createUser·p0.999:  22.500 ms/op
                 createUser·p0.9999: 27.106 ms/op
                 createUser·p1.00:   28.246 ms/op

Iteration   3: 3.525 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.343 ms/op
                 createUser·p0.50:   3.404 ms/op
                 createUser·p0.90:   4.096 ms/op
                 createUser·p0.95:   4.383 ms/op
                 createUser·p0.99:   5.734 ms/op
                 createUser·p0.999:  21.832 ms/op
                 createUser·p0.9999: 26.542 ms/op
                 createUser·p1.00:   27.066 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 279097
  mean =      3.439 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6589 
    [ 2.500,  5.000) = 267526 
    [ 5.000,  7.500) = 3948 
    [ 7.500, 10.000) = 498 
    [10.000, 12.500) = 119 
    [12.500, 15.000) = 41 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 153 
    [25.000, 27.500) = 97 

  Percentiles, ms/op:
      p(0.0000) =      1.110 ms/op
     p(50.0000) =      3.318 ms/op
     p(90.0000) =      3.908 ms/op
     p(95.0000) =      4.190 ms/op
     p(99.0000) =      5.751 ms/op
     p(99.9000) =     21.915 ms/op
     p(99.9900) =     26.578 ms/op
     p(99.9990) =     28.051 ms/op
     p(99.9999) =     28.246 ms/op
    p(100.0000) =     28.246 ms/op


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
# Warmup Iteration   1: 8.853 ±(99.9%) 0.110 ms/op
# Warmup Iteration   2: 3.666 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.329 ±(99.9%) 0.009 ms/op
Iteration   1: 3.359 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.528 ms/op
                 existUser·p0.50:   3.183 ms/op
                 existUser·p0.90:   3.699 ms/op
                 existUser·p0.95:   4.710 ms/op
                 existUser·p0.99:   6.234 ms/op
                 existUser·p0.999:  11.174 ms/op
                 existUser·p0.9999: 25.345 ms/op
                 existUser·p1.00:   25.625 ms/op

Iteration   2: 3.328 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.655 ms/op
                 existUser·p0.50:   3.228 ms/op
                 existUser·p0.90:   3.727 ms/op
                 existUser·p0.95:   3.969 ms/op
                 existUser·p0.99:   5.497 ms/op
                 existUser·p0.999:  21.035 ms/op
                 existUser·p0.9999: 24.884 ms/op
                 existUser·p1.00:   25.625 ms/op

Iteration   3: 3.376 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.434 ms/op
                 existUser·p0.50:   3.232 ms/op
                 existUser·p0.90:   3.731 ms/op
                 existUser·p0.95:   4.121 ms/op
                 existUser·p0.99:   5.612 ms/op
                 existUser·p0.999:  20.123 ms/op
                 existUser·p0.9999: 36.669 ms/op
                 existUser·p1.00:   37.683 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 286107
  mean =      3.354 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3180 
    [ 2.500,  5.000) = 276021 
    [ 5.000,  7.500) = 5721 
    [ 7.500, 10.000) = 582 
    [10.000, 12.500) = 326 
    [12.500, 15.000) = 21 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 62 
    [22.500, 25.000) = 143 
    [25.000, 27.500) = 18 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      1.434 ms/op
     p(50.0000) =      3.211 ms/op
     p(90.0000) =      3.723 ms/op
     p(95.0000) =      4.129 ms/op
     p(99.0000) =      5.841 ms/op
     p(99.9000) =     12.354 ms/op
     p(99.9900) =     34.931 ms/op
     p(99.9990) =     37.177 ms/op
     p(99.9999) =     37.683 ms/op
    p(100.0000) =     37.683 ms/op


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
# Warmup Iteration   1: 9.779 ±(99.9%) 0.145 ms/op
# Warmup Iteration   2: 3.781 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.618 ±(99.9%) 0.011 ms/op
Iteration   1: 3.467 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.462 ms/op
                 getUser·p0.50:   3.387 ms/op
                 getUser·p0.90:   3.760 ms/op
                 getUser·p0.95:   3.936 ms/op
                 getUser·p0.99:   5.825 ms/op
                 getUser·p0.999:  13.984 ms/op
                 getUser·p0.9999: 25.264 ms/op
                 getUser·p1.00:   26.804 ms/op

Iteration   2: 3.485 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.708 ms/op
                 getUser·p0.50:   3.367 ms/op
                 getUser·p0.90:   3.981 ms/op
                 getUser·p0.95:   4.293 ms/op
                 getUser·p0.99:   5.882 ms/op
                 getUser·p0.999:  23.436 ms/op
                 getUser·p0.9999: 28.567 ms/op
                 getUser·p1.00:   29.262 ms/op

Iteration   3: 3.448 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.092 ms/op
                 getUser·p0.50:   3.355 ms/op
                 getUser·p0.90:   3.764 ms/op
                 getUser·p0.95:   3.953 ms/op
                 getUser·p0.99:   6.201 ms/op
                 getUser·p0.999:  22.936 ms/op
                 getUser·p0.9999: 34.013 ms/op
                 getUser·p1.00:   34.734 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 277211
  mean =      3.467 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5794 
    [ 2.500,  5.000) = 265619 
    [ 5.000,  7.500) = 4760 
    [ 7.500, 10.000) = 674 
    [10.000, 12.500) = 44 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 111 
    [25.000, 27.500) = 60 
    [27.500, 30.000) = 28 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 29 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.092 ms/op
     p(50.0000) =      3.367 ms/op
     p(90.0000) =      3.834 ms/op
     p(95.0000) =      4.088 ms/op
     p(99.0000) =      6.005 ms/op
     p(99.9000) =     14.008 ms/op
     p(99.9900) =     32.885 ms/op
     p(99.9990) =     34.683 ms/op
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
# Warmup Iteration   1: 11.796 ±(99.9%) 0.161 ms/op
# Warmup Iteration   2: 4.558 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.241 ±(99.9%) 0.014 ms/op
Iteration   1: 4.085 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.952 ms/op
                 listUser·p0.50:   3.912 ms/op
                 listUser·p0.90:   4.465 ms/op
                 listUser·p0.95:   4.866 ms/op
                 listUser·p0.99:   7.799 ms/op
                 listUser·p0.999:  23.320 ms/op
                 listUser·p0.9999: 26.105 ms/op
                 listUser·p1.00:   26.575 ms/op

Iteration   2: 4.029 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.640 ms/op
                 listUser·p0.50:   3.871 ms/op
                 listUser·p0.90:   4.448 ms/op
                 listUser·p0.95:   4.661 ms/op
                 listUser·p0.99:   7.119 ms/op
                 listUser·p0.999:  16.138 ms/op
                 listUser·p0.9999: 17.990 ms/op
                 listUser·p1.00:   18.317 ms/op

Iteration   3: 4.121 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.269 ms/op
                 listUser·p0.50:   3.928 ms/op
                 listUser·p0.90:   4.514 ms/op
                 listUser·p0.95:   4.866 ms/op
                 listUser·p0.99:   7.942 ms/op
                 listUser·p0.999:  15.155 ms/op
                 listUser·p0.9999: 20.775 ms/op
                 listUser·p1.00:   21.660 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 235242
  mean =      4.078 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24 
    [ 2.500,  5.000) = 225877 
    [ 5.000,  7.500) = 6635 
    [ 7.500, 10.000) = 1810 
    [10.000, 12.500) = 330 
    [12.500, 15.000) = 192 
    [15.000, 17.500) = 197 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 58 
    [22.500, 25.000) = 75 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      1.640 ms/op
     p(50.0000) =      3.899 ms/op
     p(90.0000) =      4.473 ms/op
     p(95.0000) =      4.784 ms/op
     p(99.0000) =      7.709 ms/op
     p(99.9000) =     16.183 ms/op
     p(99.9900) =     24.952 ms/op
     p(99.9990) =     26.301 ms/op
     p(99.9999) =     26.575 ms/op
    p(100.0000) =     26.575 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.994 ± 1.994  ops/ms
ClientPb.existUser                       thrpt       3   9.429 ± 3.022  ops/ms
ClientPb.getUser                         thrpt       3   9.407 ± 2.556  ops/ms
ClientPb.listUser                        thrpt       3   7.835 ± 1.852  ops/ms
ClientPb.createUser                       avgt       3   3.464 ± 1.733   ms/op
ClientPb.existUser                        avgt       3   3.351 ± 0.625   ms/op
ClientPb.getUser                          avgt       3   3.418 ± 0.375   ms/op
ClientPb.listUser                         avgt       3   3.963 ± 0.423   ms/op
ClientPb.createUser                     sample  279097   3.439 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.110           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.318           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.908           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.190           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.751           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.915           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.578           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.246           ms/op
ClientPb.existUser                      sample  286107   3.354 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.434           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.211           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.723           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.129           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.841           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.354           ms/op
ClientPb.existUser:existUser·p0.9999    sample          34.931           ms/op
ClientPb.existUser:existUser·p1.00      sample          37.683           ms/op
ClientPb.getUser                        sample  277211   3.467 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.092           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.367           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.834           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.088           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.005           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.008           ms/op
ClientPb.getUser:getUser·p0.9999        sample          32.885           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.734           ms/op
ClientPb.listUser                       sample  235242   4.078 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.640           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.899           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.473           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.784           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.709           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.183           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.952           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.575           ms/op
