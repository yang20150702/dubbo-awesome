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
# Warmup Iteration   1: 2.089 ops/ms
# Warmup Iteration   2: 5.502 ops/ms
# Warmup Iteration   3: 8.259 ops/ms
Iteration   1: 9.054 ops/ms
Iteration   2: 9.335 ops/ms
Iteration   3: 9.415 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.268 ±(99.9%) 3.462 ops/ms [Average]
  (min, avg, max) = (9.054, 9.268, 9.415), stdev = 0.190
  CI (99.9%): [5.806, 12.730] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.392 ops/ms
# Warmup Iteration   2: 8.946 ops/ms
# Warmup Iteration   3: 9.338 ops/ms
Iteration   1: 9.583 ops/ms
Iteration   2: 9.575 ops/ms
Iteration   3: 9.650 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.603 ±(99.9%) 0.749 ops/ms [Average]
  (min, avg, max) = (9.575, 9.603, 9.650), stdev = 0.041
  CI (99.9%): [8.853, 10.352] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.934 ops/ms
# Warmup Iteration   2: 8.138 ops/ms
# Warmup Iteration   3: 9.217 ops/ms
Iteration   1: 9.220 ops/ms
Iteration   2: 9.475 ops/ms
Iteration   3: 9.411 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.369 ±(99.9%) 2.422 ops/ms [Average]
  (min, avg, max) = (9.220, 9.369, 9.475), stdev = 0.133
  CI (99.9%): [6.947, 11.791] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 2.852 ops/ms
# Warmup Iteration   2: 7.400 ops/ms
# Warmup Iteration   3: 7.742 ops/ms
Iteration   1: 8.074 ops/ms
Iteration   2: 8.045 ops/ms
Iteration   3: 7.958 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.026 ±(99.9%) 1.106 ops/ms [Average]
  (min, avg, max) = (7.958, 8.026, 8.074), stdev = 0.061
  CI (99.9%): [6.920, 9.132] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 9.620 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 3.894 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.489 ±(99.9%) 0.010 ms/op
Iteration   1: 3.455 ±(99.9%) 0.008 ms/op
Iteration   2: 3.286 ±(99.9%) 0.012 ms/op
Iteration   3: 3.315 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.352 ±(99.9%) 1.657 ms/op [Average]
  (min, avg, max) = (3.286, 3.352, 3.455), stdev = 0.091
  CI (99.9%): [1.695, 5.009] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 8.638 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.602 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.349 ±(99.9%) 0.007 ms/op
Iteration   1: 3.316 ±(99.9%) 0.009 ms/op
Iteration   2: 3.238 ±(99.9%) 0.009 ms/op
Iteration   3: 3.306 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.287 ±(99.9%) 0.778 ms/op [Average]
  (min, avg, max) = (3.238, 3.287, 3.316), stdev = 0.043
  CI (99.9%): [2.509, 4.064] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 8.845 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.822 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.578 ±(99.9%) 0.007 ms/op
Iteration   1: 3.386 ±(99.9%) 0.006 ms/op
Iteration   2: 3.390 ±(99.9%) 0.007 ms/op
Iteration   3: 3.424 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.400 ±(99.9%) 0.385 ms/op [Average]
  (min, avg, max) = (3.386, 3.400, 3.424), stdev = 0.021
  CI (99.9%): [3.015, 3.785] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 10.094 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.350 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.996 ±(99.9%) 0.010 ms/op
Iteration   1: 4.074 ±(99.9%) 0.009 ms/op
Iteration   2: 3.942 ±(99.9%) 0.014 ms/op
Iteration   3: 4.145 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.053 ±(99.9%) 1.878 ms/op [Average]
  (min, avg, max) = (3.942, 4.053, 4.145), stdev = 0.103
  CI (99.9%): [2.176, 5.931] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 10.817 ±(99.9%) 0.145 ms/op
# Warmup Iteration   2: 4.280 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.656 ±(99.9%) 0.012 ms/op
Iteration   1: 3.410 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.556 ms/op
                 createUser·p0.50:   3.404 ms/op
                 createUser·p0.90:   3.588 ms/op
                 createUser·p0.95:   3.949 ms/op
                 createUser·p0.99:   5.792 ms/op
                 createUser·p0.999:  20.283 ms/op
                 createUser·p0.9999: 26.878 ms/op
                 createUser·p1.00:   28.115 ms/op

Iteration   2: 3.436 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.382 ms/op
                 createUser·p0.50:   3.346 ms/op
                 createUser·p0.90:   3.826 ms/op
                 createUser·p0.95:   4.166 ms/op
                 createUser·p0.99:   5.841 ms/op
                 createUser·p0.999:  21.632 ms/op
                 createUser·p0.9999: 26.205 ms/op
                 createUser·p1.00:   26.739 ms/op

Iteration   3: 3.406 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.751 ms/op
                 createUser·p0.50:   3.269 ms/op
                 createUser·p0.90:   3.822 ms/op
                 createUser·p0.95:   4.076 ms/op
                 createUser·p0.99:   5.816 ms/op
                 createUser·p0.999:  16.501 ms/op
                 createUser·p0.9999: 34.370 ms/op
                 createUser·p1.00:   35.324 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 280646
  mean =      3.417 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10138 
    [ 2.500,  5.000) = 265437 
    [ 5.000,  7.500) = 3992 
    [ 7.500, 10.000) = 583 
    [10.000, 12.500) = 157 
    [12.500, 15.000) = 40 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 101 
    [22.500, 25.000) = 57 
    [25.000, 27.500) = 52 
    [27.500, 30.000) = 2 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 31 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.382 ms/op
     p(50.0000) =      3.353 ms/op
     p(90.0000) =      3.768 ms/op
     p(95.0000) =      4.063 ms/op
     p(99.0000) =      5.816 ms/op
     p(99.9000) =     16.728 ms/op
     p(99.9900) =     33.024 ms/op
     p(99.9990) =     34.838 ms/op
     p(99.9999) =     35.324 ms/op
    p(100.0000) =     35.324 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 8.401 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 3.708 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.361 ±(99.9%) 0.008 ms/op
Iteration   1: 3.409 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.757 ms/op
                 existUser·p0.50:   3.375 ms/op
                 existUser·p0.90:   3.875 ms/op
                 existUser·p0.95:   4.268 ms/op
                 existUser·p0.99:   5.308 ms/op
                 existUser·p0.999:  9.706 ms/op
                 existUser·p0.9999: 23.560 ms/op
                 existUser·p1.00:   25.002 ms/op

Iteration   2: 3.491 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.290 ms/op
                 existUser·p0.50:   3.359 ms/op
                 existUser·p0.90:   3.961 ms/op
                 existUser·p0.95:   4.284 ms/op
                 existUser·p0.99:   6.021 ms/op
                 existUser·p0.999:  22.984 ms/op
                 existUser·p0.9999: 27.127 ms/op
                 existUser·p1.00:   28.148 ms/op

Iteration   3: 3.377 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.690 ms/op
                 existUser·p0.50:   3.330 ms/op
                 existUser·p0.90:   3.551 ms/op
                 existUser·p0.95:   4.051 ms/op
                 existUser·p0.99:   5.472 ms/op
                 existUser·p0.999:  20.447 ms/op
                 existUser·p0.9999: 26.592 ms/op
                 existUser·p1.00:   26.968 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 280167
  mean =      3.425 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14678 
    [ 2.500,  5.000) = 260001 
    [ 5.000,  7.500) = 4607 
    [ 7.500, 10.000) = 429 
    [10.000, 12.500) = 74 
    [12.500, 15.000) = 47 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 73 
    [22.500, 25.000) = 123 
    [25.000, 27.500) = 67 

  Percentiles, ms/op:
      p(0.0000) =      1.290 ms/op
     p(50.0000) =      3.355 ms/op
     p(90.0000) =      3.846 ms/op
     p(95.0000) =      4.243 ms/op
     p(99.0000) =      5.751 ms/op
     p(99.9000) =     18.579 ms/op
     p(99.9900) =     26.673 ms/op
     p(99.9990) =     28.121 ms/op
     p(99.9999) =     28.148 ms/op
    p(100.0000) =     28.148 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.836 ±(99.9%) 0.129 ms/op
# Warmup Iteration   2: 3.841 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.391 ±(99.9%) 0.009 ms/op
Iteration   1: 3.484 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.722 ms/op
                 getUser·p0.50:   3.322 ms/op
                 getUser·p0.90:   3.830 ms/op
                 getUser·p0.95:   4.268 ms/op
                 getUser·p0.99:   6.488 ms/op
                 getUser·p0.999:  19.562 ms/op
                 getUser·p0.9999: 21.778 ms/op
                 getUser·p1.00:   22.938 ms/op

Iteration   2: 3.396 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.772 ms/op
                 getUser·p0.50:   3.338 ms/op
                 getUser·p0.90:   3.809 ms/op
                 getUser·p0.95:   4.080 ms/op
                 getUser·p0.99:   5.464 ms/op
                 getUser·p0.999:  20.798 ms/op
                 getUser·p0.9999: 28.360 ms/op
                 getUser·p1.00:   29.393 ms/op

Iteration   3: 3.462 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.753 ms/op
                 getUser·p0.50:   3.301 ms/op
                 getUser·p0.90:   3.801 ms/op
                 getUser·p0.95:   4.108 ms/op
                 getUser·p0.99:   6.369 ms/op
                 getUser·p0.999:  13.140 ms/op
                 getUser·p0.9999: 27.003 ms/op
                 getUser·p1.00:   29.327 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 278320
  mean =      3.447 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5832 
    [ 2.500,  5.000) = 264263 
    [ 5.000,  7.500) = 7374 
    [ 7.500, 10.000) = 466 
    [10.000, 12.500) = 82 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 107 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 71 

  Percentiles, ms/op:
      p(0.0000) =      1.722 ms/op
     p(50.0000) =      3.322 ms/op
     p(90.0000) =      3.809 ms/op
     p(95.0000) =      4.125 ms/op
     p(99.0000) =      6.259 ms/op
     p(99.9000) =     13.287 ms/op
     p(99.9900) =     27.170 ms/op
     p(99.9990) =     29.173 ms/op
     p(99.9999) =     29.393 ms/op
    p(100.0000) =     29.393 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.141 ±(99.9%) 0.123 ms/op
# Warmup Iteration   2: 4.271 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.051 ±(99.9%) 0.011 ms/op
Iteration   1: 4.181 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.829 ms/op
                 listUser·p0.50:   4.030 ms/op
                 listUser·p0.90:   4.506 ms/op
                 listUser·p0.95:   5.087 ms/op
                 listUser·p0.99:   7.905 ms/op
                 listUser·p0.999:  18.439 ms/op
                 listUser·p0.9999: 22.872 ms/op
                 listUser·p1.00:   23.757 ms/op

Iteration   2: 4.049 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.376 ms/op
                 listUser·p0.50:   3.961 ms/op
                 listUser·p0.90:   4.342 ms/op
                 listUser·p0.95:   4.522 ms/op
                 listUser·p0.99:   7.160 ms/op
                 listUser·p0.999:  14.828 ms/op
                 listUser·p0.9999: 16.205 ms/op
                 listUser·p1.00:   16.908 ms/op

Iteration   3: 4.029 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.628 ms/op
                 listUser·p0.50:   3.908 ms/op
                 listUser·p0.90:   4.399 ms/op
                 listUser·p0.95:   4.596 ms/op
                 listUser·p0.99:   7.218 ms/op
                 listUser·p0.999:  13.877 ms/op
                 listUser·p0.9999: 16.597 ms/op
                 listUser·p1.00:   19.071 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 234862
  mean =      4.085 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 33 
    [ 2.500,  5.000) = 226795 
    [ 5.000,  7.500) = 5791 
    [ 7.500, 10.000) = 1367 
    [10.000, 12.500) = 348 
    [12.500, 15.000) = 271 
    [15.000, 17.500) = 173 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.628 ms/op
     p(50.0000) =      3.969 ms/op
     p(90.0000) =      4.407 ms/op
     p(95.0000) =      4.669 ms/op
     p(99.0000) =      7.438 ms/op
     p(99.9000) =     15.401 ms/op
     p(99.9900) =     21.365 ms/op
     p(99.9990) =     23.500 ms/op
     p(99.9999) =     23.757 ms/op
    p(100.0000) =     23.757 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.268 ± 3.462  ops/ms
ClientPb.existUser                       thrpt       3   9.603 ± 0.749  ops/ms
ClientPb.getUser                         thrpt       3   9.369 ± 2.422  ops/ms
ClientPb.listUser                        thrpt       3   8.026 ± 1.106  ops/ms
ClientPb.createUser                       avgt       3   3.352 ± 1.657   ms/op
ClientPb.existUser                        avgt       3   3.287 ± 0.778   ms/op
ClientPb.getUser                          avgt       3   3.400 ± 0.385   ms/op
ClientPb.listUser                         avgt       3   4.053 ± 1.878   ms/op
ClientPb.createUser                     sample  280646   3.417 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.382           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.353           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.768           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.063           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.816           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.728           ms/op
ClientPb.createUser:createUser·p0.9999  sample          33.024           ms/op
ClientPb.createUser:createUser·p1.00    sample          35.324           ms/op
ClientPb.existUser                      sample  280167   3.425 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.290           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.355           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.846           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.243           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.751           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.579           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.673           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.148           ms/op
ClientPb.getUser                        sample  278320   3.447 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.722           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.322           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.809           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.125           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.259           ms/op
ClientPb.getUser:getUser·p0.999         sample          13.287           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.170           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.393           ms/op
ClientPb.listUser                       sample  234862   4.085 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.628           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.969           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.407           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.669           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.438           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.401           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.365           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.757           ms/op
