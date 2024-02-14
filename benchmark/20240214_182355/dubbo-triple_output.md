# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.565 ops/ms
# Warmup Iteration   2: 11.935 ops/ms
# Warmup Iteration   3: 12.117 ops/ms
Iteration   1: 12.459 ops/ms
Iteration   2: 12.349 ops/ms
Iteration   3: 12.421 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.410 ±(99.9%) 1.020 ops/ms [Average]
  (min, avg, max) = (12.349, 12.410, 12.459), stdev = 0.056
  CI (99.9%): [11.389, 13.430] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.891 ops/ms
# Warmup Iteration   2: 12.888 ops/ms
# Warmup Iteration   3: 13.122 ops/ms
Iteration   1: 13.333 ops/ms
Iteration   2: 13.127 ops/ms
Iteration   3: 13.509 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.323 ±(99.9%) 3.487 ops/ms [Average]
  (min, avg, max) = (13.127, 13.323, 13.509), stdev = 0.191
  CI (99.9%): [9.836, 16.810] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.443 ops/ms
# Warmup Iteration   2: 12.730 ops/ms
# Warmup Iteration   3: 12.712 ops/ms
Iteration   1: 12.870 ops/ms
Iteration   2: 12.776 ops/ms
Iteration   3: 12.810 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.819 ±(99.9%) 0.864 ops/ms [Average]
  (min, avg, max) = (12.776, 12.819, 12.870), stdev = 0.047
  CI (99.9%): [11.955, 13.683] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.307 ops/ms
# Warmup Iteration   2: 10.474 ops/ms
# Warmup Iteration   3: 10.693 ops/ms
Iteration   1: 10.575 ops/ms
Iteration   2: 10.580 ops/ms
Iteration   3: 10.723 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.626 ±(99.9%) 1.534 ops/ms [Average]
  (min, avg, max) = (10.575, 10.626, 10.723), stdev = 0.084
  CI (99.9%): [9.092, 12.160] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.231 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 2.619 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.604 ±(99.9%) 0.006 ms/op
Iteration   1: 2.625 ±(99.9%) 0.009 ms/op
Iteration   2: 2.585 ±(99.9%) 0.009 ms/op
Iteration   3: 2.557 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.589 ±(99.9%) 0.621 ms/op [Average]
  (min, avg, max) = (2.557, 2.589, 2.625), stdev = 0.034
  CI (99.9%): [1.968, 3.210] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.712 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.478 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.409 ±(99.9%) 0.007 ms/op
Iteration   1: 2.399 ±(99.9%) 0.009 ms/op
Iteration   2: 2.337 ±(99.9%) 0.007 ms/op
Iteration   3: 2.373 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.370 ±(99.9%) 0.571 ms/op [Average]
  (min, avg, max) = (2.337, 2.370, 2.399), stdev = 0.031
  CI (99.9%): [1.799, 2.940] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 4.160 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 2.601 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.505 ±(99.9%) 0.012 ms/op
Iteration   1: 2.536 ±(99.9%) 0.010 ms/op
Iteration   2: 2.533 ±(99.9%) 0.008 ms/op
Iteration   3: 2.489 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.519 ±(99.9%) 0.481 ms/op [Average]
  (min, avg, max) = (2.489, 2.519, 2.536), stdev = 0.026
  CI (99.9%): [2.038, 3.000] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.921 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 2.965 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.909 ±(99.9%) 0.009 ms/op
Iteration   1: 2.965 ±(99.9%) 0.009 ms/op
Iteration   2: 3.001 ±(99.9%) 0.010 ms/op
Iteration   3: 2.933 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.967 ±(99.9%) 0.623 ms/op [Average]
  (min, avg, max) = (2.933, 2.967, 3.001), stdev = 0.034
  CI (99.9%): [2.343, 3.590] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.532 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 2.635 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.509 ±(99.9%) 0.006 ms/op
Iteration   1: 2.500 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.689 ms/op
                 createUser·p0.50:   2.466 ms/op
                 createUser·p0.90:   3.191 ms/op
                 createUser·p0.95:   3.514 ms/op
                 createUser·p0.99:   4.366 ms/op
                 createUser·p0.999:  12.257 ms/op
                 createUser·p0.9999: 14.969 ms/op
                 createUser·p1.00:   16.777 ms/op

Iteration   2: 2.531 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.356 ms/op
                 createUser·p0.50:   2.486 ms/op
                 createUser·p0.90:   3.211 ms/op
                 createUser·p0.95:   3.572 ms/op
                 createUser·p0.99:   4.719 ms/op
                 createUser·p0.999:  10.542 ms/op
                 createUser·p0.9999: 15.333 ms/op
                 createUser·p1.00:   18.842 ms/op

Iteration   3: 2.496 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.764 ms/op
                 createUser·p0.50:   2.462 ms/op
                 createUser·p0.90:   3.158 ms/op
                 createUser·p0.95:   3.441 ms/op
                 createUser·p0.99:   4.243 ms/op
                 createUser·p0.999:  9.444 ms/op
                 createUser·p0.9999: 12.901 ms/op
                 createUser·p1.00:   13.238 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 382264
  mean =      2.509 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 383 
    [ 1.250,  2.500) = 196882 
    [ 2.500,  3.750) = 173017 
    [ 3.750,  5.000) = 10061 
    [ 5.000,  6.250) = 889 
    [ 6.250,  7.500) = 400 
    [ 7.500,  8.750) = 147 
    [ 8.750, 10.000) = 49 
    [10.000, 11.250) = 104 
    [11.250, 12.500) = 165 
    [12.500, 13.750) = 98 
    [13.750, 15.000) = 38 
    [15.000, 16.250) = 27 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.356 ms/op
     p(50.0000) =      2.470 ms/op
     p(90.0000) =      3.187 ms/op
     p(95.0000) =      3.506 ms/op
     p(99.0000) =      4.424 ms/op
     p(99.9000) =     10.580 ms/op
     p(99.9900) =     14.824 ms/op
     p(99.9990) =     16.459 ms/op
     p(99.9999) =     18.842 ms/op
    p(100.0000) =     18.842 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.896 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.485 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.451 ±(99.9%) 0.006 ms/op
Iteration   1: 2.465 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.779 ms/op
                 existUser·p0.50:   2.417 ms/op
                 existUser·p0.90:   3.178 ms/op
                 existUser·p0.95:   3.527 ms/op
                 existUser·p0.99:   4.342 ms/op
                 existUser·p0.999:  12.570 ms/op
                 existUser·p0.9999: 15.140 ms/op
                 existUser·p1.00:   15.909 ms/op

Iteration   2: 2.510 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.420 ms/op
                 existUser·p0.50:   2.437 ms/op
                 existUser·p0.90:   3.281 ms/op
                 existUser·p0.95:   3.670 ms/op
                 existUser·p0.99:   4.678 ms/op
                 existUser·p0.999:  10.791 ms/op
                 existUser·p0.9999: 16.934 ms/op
                 existUser·p1.00:   18.448 ms/op

Iteration   3: 2.470 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.754 ms/op
                 existUser·p0.50:   2.404 ms/op
                 existUser·p0.90:   3.260 ms/op
                 existUser·p0.95:   3.604 ms/op
                 existUser·p0.99:   4.489 ms/op
                 existUser·p0.999:  9.470 ms/op
                 existUser·p0.9999: 14.215 ms/op
                 existUser·p1.00:   16.466 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 386593
  mean =      2.481 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 407 
    [ 1.250,  2.500) = 212097 
    [ 2.500,  3.750) = 159473 
    [ 3.750,  5.000) = 12671 
    [ 5.000,  6.250) = 1145 
    [ 6.250,  7.500) = 292 
    [ 7.500,  8.750) = 98 
    [ 8.750, 10.000) = 25 
    [10.000, 11.250) = 58 
    [11.250, 12.500) = 76 
    [12.500, 13.750) = 81 
    [13.750, 15.000) = 115 
    [15.000, 16.250) = 35 
    [16.250, 17.500) = 14 
    [17.500, 18.750) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.420 ms/op
     p(50.0000) =      2.421 ms/op
     p(90.0000) =      3.244 ms/op
     p(95.0000) =      3.600 ms/op
     p(99.0000) =      4.497 ms/op
     p(99.9000) =      9.828 ms/op
     p(99.9900) =     15.308 ms/op
     p(99.9990) =     17.887 ms/op
     p(99.9999) =     18.448 ms/op
    p(100.0000) =     18.448 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.216 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 2.694 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.616 ±(99.9%) 0.008 ms/op
Iteration   1: 2.580 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.727 ms/op
                 getUser·p0.50:   2.527 ms/op
                 getUser·p0.90:   3.379 ms/op
                 getUser·p0.95:   3.793 ms/op
                 getUser·p0.99:   4.858 ms/op
                 getUser·p0.999:  12.632 ms/op
                 getUser·p0.9999: 16.214 ms/op
                 getUser·p1.00:   16.974 ms/op

Iteration   2: 2.621 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.833 ms/op
                 getUser·p0.50:   2.593 ms/op
                 getUser·p0.90:   3.367 ms/op
                 getUser·p0.95:   3.756 ms/op
                 getUser·p0.99:   4.669 ms/op
                 getUser·p0.999:  11.780 ms/op
                 getUser·p0.9999: 18.763 ms/op
                 getUser·p1.00:   20.644 ms/op

Iteration   3: 2.586 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.696 ms/op
                 getUser·p0.50:   2.560 ms/op
                 getUser·p0.90:   3.314 ms/op
                 getUser·p0.95:   3.711 ms/op
                 getUser·p0.99:   4.571 ms/op
                 getUser·p0.999:  9.378 ms/op
                 getUser·p0.9999: 13.529 ms/op
                 getUser·p1.00:   13.959 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 369527
  mean =      2.595 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 175970 
    [ 2.500,  5.000) = 191007 
    [ 5.000,  7.500) = 1882 
    [ 7.500, 10.000) = 257 
    [10.000, 12.500) = 125 
    [12.500, 15.000) = 161 
    [15.000, 17.500) = 101 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.696 ms/op
     p(50.0000) =      2.560 ms/op
     p(90.0000) =      3.355 ms/op
     p(95.0000) =      3.756 ms/op
     p(99.0000) =      4.702 ms/op
     p(99.9000) =     11.419 ms/op
     p(99.9900) =     16.910 ms/op
     p(99.9990) =     20.003 ms/op
     p(99.9999) =     20.644 ms/op
    p(100.0000) =     20.644 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.182 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 2.985 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 2.998 ±(99.9%) 0.010 ms/op
Iteration   1: 3.041 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.706 ms/op
                 listUser·p0.50:   2.912 ms/op
                 listUser·p0.90:   4.227 ms/op
                 listUser·p0.95:   4.735 ms/op
                 listUser·p0.99:   6.128 ms/op
                 listUser·p0.999:  11.642 ms/op
                 listUser·p0.9999: 19.071 ms/op
                 listUser·p1.00:   19.431 ms/op

Iteration   2: 3.009 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.757 ms/op
                 listUser·p0.50:   2.900 ms/op
                 listUser·p0.90:   4.166 ms/op
                 listUser·p0.95:   4.661 ms/op
                 listUser·p0.99:   5.857 ms/op
                 listUser·p0.999:  11.333 ms/op
                 listUser·p0.9999: 13.414 ms/op
                 listUser·p1.00:   14.975 ms/op

Iteration   3: 3.037 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.830 ms/op
                 listUser·p0.50:   2.929 ms/op
                 listUser·p0.90:   4.170 ms/op
                 listUser·p0.95:   4.653 ms/op
                 listUser·p0.99:   5.882 ms/op
                 listUser·p0.999:  11.013 ms/op
                 listUser·p0.9999: 13.131 ms/op
                 listUser·p1.00:   14.238 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 316678
  mean =      3.029 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 491 
    [ 1.250,  2.500) = 107271 
    [ 2.500,  3.750) = 153726 
    [ 3.750,  5.000) = 45279 
    [ 5.000,  6.250) = 7505 
    [ 6.250,  7.500) = 1123 
    [ 7.500,  8.750) = 457 
    [ 8.750, 10.000) = 271 
    [10.000, 11.250) = 233 
    [11.250, 12.500) = 213 
    [12.500, 13.750) = 56 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 15 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.706 ms/op
     p(50.0000) =      2.912 ms/op
     p(90.0000) =      4.190 ms/op
     p(95.0000) =      4.678 ms/op
     p(99.0000) =      5.964 ms/op
     p(99.9000) =     11.277 ms/op
     p(99.9900) =     15.150 ms/op
     p(99.9990) =     19.229 ms/op
     p(99.9999) =     19.431 ms/op
    p(100.0000) =     19.431 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.410 ± 1.020  ops/ms
ClientPb.existUser                       thrpt       3  13.323 ± 3.487  ops/ms
ClientPb.getUser                         thrpt       3  12.819 ± 0.864  ops/ms
ClientPb.listUser                        thrpt       3  10.626 ± 1.534  ops/ms
ClientPb.createUser                       avgt       3   2.589 ± 0.621   ms/op
ClientPb.existUser                        avgt       3   2.370 ± 0.571   ms/op
ClientPb.getUser                          avgt       3   2.519 ± 0.481   ms/op
ClientPb.listUser                         avgt       3   2.967 ± 0.623   ms/op
ClientPb.createUser                     sample  382264   2.509 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.356           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.470           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.187           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.506           ms/op
ClientPb.createUser:createUser·p0.99    sample           4.424           ms/op
ClientPb.createUser:createUser·p0.999   sample          10.580           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.824           ms/op
ClientPb.createUser:createUser·p1.00    sample          18.842           ms/op
ClientPb.existUser                      sample  386593   2.481 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.420           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.421           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.244           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.600           ms/op
ClientPb.existUser:existUser·p0.99      sample           4.497           ms/op
ClientPb.existUser:existUser·p0.999     sample           9.828           ms/op
ClientPb.existUser:existUser·p0.9999    sample          15.308           ms/op
ClientPb.existUser:existUser·p1.00      sample          18.448           ms/op
ClientPb.getUser                        sample  369527   2.595 ± 0.004   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.696           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.560           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.355           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.756           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.702           ms/op
ClientPb.getUser:getUser·p0.999         sample          11.419           ms/op
ClientPb.getUser:getUser·p0.9999        sample          16.910           ms/op
ClientPb.getUser:getUser·p1.00          sample          20.644           ms/op
ClientPb.listUser                       sample  316678   3.029 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.706           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.912           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.190           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.678           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.964           ms/op
ClientPb.listUser:listUser·p0.999       sample          11.277           ms/op
ClientPb.listUser:listUser·p0.9999      sample          15.150           ms/op
ClientPb.listUser:listUser·p1.00        sample          19.431           ms/op
