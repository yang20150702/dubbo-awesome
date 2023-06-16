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
# Warmup Iteration   1: 2.369 ops/ms
# Warmup Iteration   2: 6.293 ops/ms
# Warmup Iteration   3: 9.239 ops/ms
Iteration   1: 9.871 ops/ms
Iteration   2: 10.256 ops/ms
Iteration   3: 9.676 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.934 ±(99.9%) 5.387 ops/ms [Average]
  (min, avg, max) = (9.676, 9.934, 10.256), stdev = 0.295
  CI (99.9%): [4.547, 15.321] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.515 ops/ms
# Warmup Iteration   2: 9.092 ops/ms
# Warmup Iteration   3: 9.703 ops/ms
Iteration   1: 9.803 ops/ms
Iteration   2: 10.502 ops/ms
Iteration   3: 10.609 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.304 ±(99.9%) 7.988 ops/ms [Average]
  (min, avg, max) = (9.803, 10.304, 10.609), stdev = 0.438
  CI (99.9%): [2.316, 18.293] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.545 ops/ms
# Warmup Iteration   2: 9.310 ops/ms
# Warmup Iteration   3: 9.612 ops/ms
Iteration   1: 10.255 ops/ms
Iteration   2: 10.158 ops/ms
Iteration   3: 10.149 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.187 ±(99.9%) 1.070 ops/ms [Average]
  (min, avg, max) = (10.149, 10.187, 10.255), stdev = 0.059
  CI (99.9%): [9.118, 11.257] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.433 ops/ms
# Warmup Iteration   2: 7.881 ops/ms
# Warmup Iteration   3: 8.450 ops/ms
Iteration   1: 8.575 ops/ms
Iteration   2: 8.355 ops/ms
Iteration   3: 8.677 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.536 ±(99.9%) 2.996 ops/ms [Average]
  (min, avg, max) = (8.355, 8.536, 8.677), stdev = 0.164
  CI (99.9%): [5.539, 11.532] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 9.890 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.791 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.244 ±(99.9%) 0.004 ms/op
Iteration   1: 3.171 ±(99.9%) 0.004 ms/op
Iteration   2: 3.218 ±(99.9%) 0.010 ms/op
Iteration   3: 3.174 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.188 ±(99.9%) 0.476 ms/op [Average]
  (min, avg, max) = (3.171, 3.188, 3.218), stdev = 0.026
  CI (99.9%): [2.711, 3.664] (assumes normal distribution)


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
# Warmup Iteration   1: 6.999 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.238 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.193 ±(99.9%) 0.005 ms/op
Iteration   1: 2.985 ±(99.9%) 0.006 ms/op
Iteration   2: 3.118 ±(99.9%) 0.009 ms/op
Iteration   3: 3.179 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.094 ±(99.9%) 1.804 ms/op [Average]
  (min, avg, max) = (2.985, 3.094, 3.179), stdev = 0.099
  CI (99.9%): [1.290, 4.898] (assumes normal distribution)


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
# Warmup Iteration   1: 8.041 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.369 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.217 ±(99.9%) 0.003 ms/op
Iteration   1: 3.155 ±(99.9%) 0.005 ms/op
Iteration   2: 3.308 ±(99.9%) 0.004 ms/op
Iteration   3: 3.322 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.262 ±(99.9%) 1.697 ms/op [Average]
  (min, avg, max) = (3.155, 3.262, 3.322), stdev = 0.093
  CI (99.9%): [1.565, 4.959] (assumes normal distribution)


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
# Warmup Iteration   1: 9.275 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.124 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.825 ±(99.9%) 0.006 ms/op
Iteration   1: 3.742 ±(99.9%) 0.009 ms/op
Iteration   2: 3.788 ±(99.9%) 0.008 ms/op
Iteration   3: 3.628 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.719 ±(99.9%) 1.495 ms/op [Average]
  (min, avg, max) = (3.628, 3.719, 3.788), stdev = 0.082
  CI (99.9%): [2.225, 5.214] (assumes normal distribution)


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
# Warmup Iteration   1: 7.851 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 3.726 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.333 ±(99.9%) 0.009 ms/op
Iteration   1: 3.224 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.947 ms/op
                 createUser·p0.50:   3.178 ms/op
                 createUser·p0.90:   3.518 ms/op
                 createUser·p0.95:   3.973 ms/op
                 createUser·p0.99:   6.095 ms/op
                 createUser·p0.999:  13.872 ms/op
                 createUser·p0.9999: 20.519 ms/op
                 createUser·p1.00:   20.972 ms/op

Iteration   2: 3.193 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.909 ms/op
                 createUser·p0.50:   3.125 ms/op
                 createUser·p0.90:   3.641 ms/op
                 createUser·p0.95:   4.022 ms/op
                 createUser·p0.99:   5.112 ms/op
                 createUser·p0.999:  9.322 ms/op
                 createUser·p0.9999: 23.134 ms/op
                 createUser·p1.00:   23.593 ms/op

Iteration   3: 3.177 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.434 ms/op
                 createUser·p0.50:   3.138 ms/op
                 createUser·p0.90:   3.514 ms/op
                 createUser·p0.95:   3.732 ms/op
                 createUser·p0.99:   5.399 ms/op
                 createUser·p0.999:  16.089 ms/op
                 createUser·p0.9999: 20.113 ms/op
                 createUser·p1.00:   23.101 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 299997
  mean =      3.198 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19965 
    [ 2.500,  5.000) = 274427 
    [ 5.000,  7.500) = 4580 
    [ 7.500, 10.000) = 561 
    [10.000, 12.500) = 91 
    [12.500, 15.000) = 49 
    [15.000, 17.500) = 111 
    [17.500, 20.000) = 119 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.909 ms/op
     p(50.0000) =      3.146 ms/op
     p(90.0000) =      3.555 ms/op
     p(95.0000) =      3.912 ms/op
     p(99.0000) =      5.481 ms/op
     p(99.9000) =     15.974 ms/op
     p(99.9900) =     22.512 ms/op
     p(99.9990) =     23.495 ms/op
     p(99.9999) =     23.593 ms/op
    p(100.0000) =     23.593 ms/op


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
# Warmup Iteration   1: 7.321 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 3.446 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.105 ±(99.9%) 0.009 ms/op
Iteration   1: 3.068 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.483 ms/op
                 existUser·p0.50:   2.982 ms/op
                 existUser·p0.90:   3.297 ms/op
                 existUser·p0.95:   3.564 ms/op
                 existUser·p0.99:   5.792 ms/op
                 existUser·p0.999:  15.278 ms/op
                 existUser·p0.9999: 19.614 ms/op
                 existUser·p1.00:   21.987 ms/op

Iteration   2: 3.014 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.057 ms/op
                 existUser·p0.50:   2.945 ms/op
                 existUser·p0.90:   3.183 ms/op
                 existUser·p0.95:   3.314 ms/op
                 existUser·p0.99:   5.284 ms/op
                 existUser·p0.999:  13.648 ms/op
                 existUser·p0.9999: 21.430 ms/op
                 existUser·p1.00:   22.249 ms/op

Iteration   3: 3.301 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.442 ms/op
                 existUser·p0.50:   3.224 ms/op
                 existUser·p0.90:   3.797 ms/op
                 existUser·p0.95:   4.096 ms/op
                 existUser·p0.99:   5.546 ms/op
                 existUser·p0.999:  9.339 ms/op
                 existUser·p0.9999: 20.097 ms/op
                 existUser·p1.00:   20.644 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 307283
  mean =      3.123 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17076 
    [ 2.500,  5.000) = 284567 
    [ 5.000,  7.500) = 4946 
    [ 7.500, 10.000) = 314 
    [10.000, 12.500) = 39 
    [12.500, 15.000) = 79 
    [15.000, 17.500) = 52 
    [17.500, 20.000) = 124 
    [20.000, 22.500) = 86 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.483 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      3.502 ms/op
     p(95.0000) =      3.830 ms/op
     p(99.0000) =      5.554 ms/op
     p(99.9000) =     13.648 ms/op
     p(99.9900) =     21.037 ms/op
     p(99.9990) =     21.983 ms/op
     p(99.9999) =     22.249 ms/op
    p(100.0000) =     22.249 ms/op


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
# Warmup Iteration   1: 8.561 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 3.503 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.328 ±(99.9%) 0.011 ms/op
Iteration   1: 3.191 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.614 ms/op
                 getUser·p0.50:   3.056 ms/op
                 getUser·p0.90:   3.547 ms/op
                 getUser·p0.95:   3.760 ms/op
                 getUser·p0.99:   5.890 ms/op
                 getUser·p0.999:  18.547 ms/op
                 getUser·p0.9999: 26.411 ms/op
                 getUser·p1.00:   27.820 ms/op

Iteration   2: 3.164 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.063 ms/op
                 getUser·p0.50:   3.125 ms/op
                 getUser·p0.90:   3.523 ms/op
                 getUser·p0.95:   3.867 ms/op
                 getUser·p0.99:   5.489 ms/op
                 getUser·p0.999:  14.152 ms/op
                 getUser·p0.9999: 21.980 ms/op
                 getUser·p1.00:   23.396 ms/op

Iteration   3: 3.415 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.608 ms/op
                 getUser·p0.50:   3.273 ms/op
                 getUser·p0.90:   3.924 ms/op
                 getUser·p0.95:   4.530 ms/op
                 getUser·p0.99:   6.308 ms/op
                 getUser·p0.999:  13.631 ms/op
                 getUser·p0.9999: 22.402 ms/op
                 getUser·p1.00:   22.970 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 295031
  mean =      3.253 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13563 
    [ 2.500,  5.000) = 274151 
    [ 5.000,  7.500) = 6536 
    [ 7.500, 10.000) = 369 
    [10.000, 12.500) = 42 
    [12.500, 15.000) = 70 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 126 
    [20.000, 22.500) = 110 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      1.063 ms/op
     p(50.0000) =      3.146 ms/op
     p(90.0000) =      3.699 ms/op
     p(95.0000) =      4.030 ms/op
     p(99.0000) =      5.898 ms/op
     p(99.9000) =     15.530 ms/op
     p(99.9900) =     24.969 ms/op
     p(99.9990) =     27.564 ms/op
     p(99.9999) =     27.820 ms/op
    p(100.0000) =     27.820 ms/op


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
# Warmup Iteration   1: 9.144 ±(99.9%) 0.121 ms/op
# Warmup Iteration   2: 4.109 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.843 ±(99.9%) 0.011 ms/op
Iteration   1: 3.799 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.792 ms/op
                 listUser·p0.50:   3.629 ms/op
                 listUser·p0.90:   4.084 ms/op
                 listUser·p0.95:   4.514 ms/op
                 listUser·p0.99:   7.414 ms/op
                 listUser·p0.999:  16.581 ms/op
                 listUser·p0.9999: 22.871 ms/op
                 listUser·p1.00:   23.757 ms/op

Iteration   2: 3.868 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.382 ms/op
                 listUser·p0.50:   3.666 ms/op
                 listUser·p0.90:   4.170 ms/op
                 listUser·p0.95:   5.685 ms/op
                 listUser·p0.99:   7.537 ms/op
                 listUser·p0.999:  13.156 ms/op
                 listUser·p0.9999: 15.446 ms/op
                 listUser·p1.00:   15.925 ms/op

Iteration   3: 3.742 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.708 ms/op
                 listUser·p0.50:   3.645 ms/op
                 listUser·p0.90:   4.014 ms/op
                 listUser·p0.95:   4.186 ms/op
                 listUser·p0.99:   6.453 ms/op
                 listUser·p0.999:  13.164 ms/op
                 listUser·p0.9999: 19.792 ms/op
                 listUser·p1.00:   19.956 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 252561
  mean =      3.802 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 66 
    [ 2.500,  5.000) = 241977 
    [ 5.000,  7.500) = 8495 
    [ 7.500, 10.000) = 1295 
    [10.000, 12.500) = 342 
    [12.500, 15.000) = 216 
    [15.000, 17.500) = 71 
    [17.500, 20.000) = 69 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.382 ms/op
     p(50.0000) =      3.645 ms/op
     p(90.0000) =      4.080 ms/op
     p(95.0000) =      4.522 ms/op
     p(99.0000) =      7.119 ms/op
     p(99.9000) =     13.599 ms/op
     p(99.9900) =     20.487 ms/op
     p(99.9990) =     23.691 ms/op
     p(99.9999) =     23.757 ms/op
    p(100.0000) =     23.757 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.934 ± 5.387  ops/ms
ClientPb.existUser                       thrpt       3  10.304 ± 7.988  ops/ms
ClientPb.getUser                         thrpt       3  10.187 ± 1.070  ops/ms
ClientPb.listUser                        thrpt       3   8.536 ± 2.996  ops/ms
ClientPb.createUser                       avgt       3   3.188 ± 0.476   ms/op
ClientPb.existUser                        avgt       3   3.094 ± 1.804   ms/op
ClientPb.getUser                          avgt       3   3.262 ± 1.697   ms/op
ClientPb.listUser                         avgt       3   3.719 ± 1.495   ms/op
ClientPb.createUser                     sample  299997   3.198 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.909           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.146           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.555           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.912           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.481           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.974           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.512           ms/op
ClientPb.createUser:createUser·p1.00    sample          23.593           ms/op
ClientPb.existUser                      sample  307283   3.123 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.483           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.023           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.502           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.830           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.554           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.648           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.037           ms/op
ClientPb.existUser:existUser·p1.00      sample          22.249           ms/op
ClientPb.getUser                        sample  295031   3.253 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.063           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.146           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.699           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.030           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.898           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.530           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.969           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.820           ms/op
ClientPb.listUser                       sample  252561   3.802 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.382           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.645           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.080           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.522           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.119           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.599           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.487           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.757           ms/op
