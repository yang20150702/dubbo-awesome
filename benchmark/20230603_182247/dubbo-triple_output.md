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
# Warmup Iteration   1: 1.948 ops/ms
# Warmup Iteration   2: 4.819 ops/ms
# Warmup Iteration   3: 8.614 ops/ms
Iteration   1: 9.145 ops/ms
Iteration   2: 9.385 ops/ms
Iteration   3: 9.736 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.422 ±(99.9%) 5.417 ops/ms [Average]
  (min, avg, max) = (9.145, 9.422, 9.736), stdev = 0.297
  CI (99.9%): [4.006, 14.839] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.162 ops/ms
# Warmup Iteration   2: 8.594 ops/ms
# Warmup Iteration   3: 9.589 ops/ms
Iteration   1: 10.028 ops/ms
Iteration   2: 9.861 ops/ms
Iteration   3: 10.061 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.983 ±(99.9%) 1.952 ops/ms [Average]
  (min, avg, max) = (9.861, 9.983, 10.061), stdev = 0.107
  CI (99.9%): [8.032, 11.935] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.925 ops/ms
# Warmup Iteration   2: 8.211 ops/ms
# Warmup Iteration   3: 8.772 ops/ms
Iteration   1: 9.617 ops/ms
Iteration   2: 9.684 ops/ms
Iteration   3: 9.249 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.517 ±(99.9%) 4.280 ops/ms [Average]
  (min, avg, max) = (9.249, 9.517, 9.684), stdev = 0.235
  CI (99.9%): [5.236, 13.797] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 2.702 ops/ms
# Warmup Iteration   2: 6.777 ops/ms
# Warmup Iteration   3: 7.848 ops/ms
Iteration   1: 7.850 ops/ms
Iteration   2: 8.144 ops/ms
Iteration   3: 7.927 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.974 ±(99.9%) 2.781 ops/ms [Average]
  (min, avg, max) = (7.850, 7.974, 8.144), stdev = 0.152
  CI (99.9%): [5.193, 10.755] (assumes normal distribution)


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
# Warmup Iteration   1: 11.595 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 4.134 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.588 ±(99.9%) 0.009 ms/op
Iteration   1: 3.457 ±(99.9%) 0.005 ms/op
Iteration   2: 3.497 ±(99.9%) 0.005 ms/op
Iteration   3: 3.396 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.450 ±(99.9%) 0.929 ms/op [Average]
  (min, avg, max) = (3.396, 3.450, 3.497), stdev = 0.051
  CI (99.9%): [2.521, 4.379] (assumes normal distribution)


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
# Warmup Iteration   1: 8.363 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.452 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.268 ±(99.9%) 0.004 ms/op
Iteration   1: 3.362 ±(99.9%) 0.005 ms/op
Iteration   2: 3.305 ±(99.9%) 0.013 ms/op
Iteration   3: 3.434 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.367 ±(99.9%) 1.186 ms/op [Average]
  (min, avg, max) = (3.305, 3.367, 3.434), stdev = 0.065
  CI (99.9%): [2.181, 4.553] (assumes normal distribution)


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
# Warmup Iteration   1: 8.441 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.714 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.443 ±(99.9%) 0.005 ms/op
Iteration   1: 3.436 ±(99.9%) 0.006 ms/op
Iteration   2: 3.313 ±(99.9%) 0.008 ms/op
Iteration   3: 3.419 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.389 ±(99.9%) 1.224 ms/op [Average]
  (min, avg, max) = (3.313, 3.389, 3.436), stdev = 0.067
  CI (99.9%): [2.165, 4.614] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 9.247 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.317 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.073 ±(99.9%) 0.011 ms/op
Iteration   1: 4.040 ±(99.9%) 0.008 ms/op
Iteration   2: 3.980 ±(99.9%) 0.010 ms/op
Iteration   3: 3.963 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.994 ±(99.9%) 0.737 ms/op [Average]
  (min, avg, max) = (3.963, 3.994, 4.040), stdev = 0.040
  CI (99.9%): [3.257, 4.731] (assumes normal distribution)


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
# Warmup Iteration   1: 9.111 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 4.012 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.410 ±(99.9%) 0.009 ms/op
Iteration   1: 3.364 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.464 ms/op
                 createUser·p0.50:   3.326 ms/op
                 createUser·p0.90:   3.670 ms/op
                 createUser·p0.95:   4.112 ms/op
                 createUser·p0.99:   5.636 ms/op
                 createUser·p0.999:  19.986 ms/op
                 createUser·p0.9999: 25.116 ms/op
                 createUser·p1.00:   27.132 ms/op

Iteration   2: 3.469 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.624 ms/op
                 createUser·p0.50:   3.346 ms/op
                 createUser·p0.90:   4.030 ms/op
                 createUser·p0.95:   4.317 ms/op
                 createUser·p0.99:   5.956 ms/op
                 createUser·p0.999:  24.071 ms/op
                 createUser·p0.9999: 26.040 ms/op
                 createUser·p1.00:   26.706 ms/op

Iteration   3: 3.412 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.323 ms/op
                 createUser·p0.50:   3.375 ms/op
                 createUser·p0.90:   3.609 ms/op
                 createUser·p0.95:   4.133 ms/op
                 createUser·p0.99:   5.521 ms/op
                 createUser·p0.999:  19.012 ms/op
                 createUser·p0.9999: 25.284 ms/op
                 createUser·p1.00:   25.592 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 281077
  mean =      3.414 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16321 
    [ 2.500,  5.000) = 258250 
    [ 5.000,  7.500) = 5574 
    [ 7.500, 10.000) = 471 
    [10.000, 12.500) = 109 
    [12.500, 15.000) = 54 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 107 
    [22.500, 25.000) = 87 
    [25.000, 27.500) = 77 

  Percentiles, ms/op:
      p(0.0000) =      1.323 ms/op
     p(50.0000) =      3.351 ms/op
     p(90.0000) =      3.834 ms/op
     p(95.0000) =      4.211 ms/op
     p(99.0000) =      5.661 ms/op
     p(99.9000) =     19.331 ms/op
     p(99.9900) =     25.556 ms/op
     p(99.9990) =     27.105 ms/op
     p(99.9999) =     27.132 ms/op
    p(100.0000) =     27.132 ms/op


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
# Warmup Iteration   1: 8.458 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 3.691 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.345 ±(99.9%) 0.008 ms/op
Iteration   1: 3.310 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.102 ms/op
                 existUser·p0.50:   3.195 ms/op
                 existUser·p0.90:   3.678 ms/op
                 existUser·p0.95:   3.998 ms/op
                 existUser·p0.99:   5.562 ms/op
                 existUser·p0.999:  13.660 ms/op
                 existUser·p0.9999: 22.020 ms/op
                 existUser·p1.00:   24.773 ms/op

Iteration   2: 3.445 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.413 ms/op
                 existUser·p0.50:   3.244 ms/op
                 existUser·p0.90:   3.957 ms/op
                 existUser·p0.95:   4.579 ms/op
                 existUser·p0.99:   7.094 ms/op
                 existUser·p0.999:  19.927 ms/op
                 existUser·p0.9999: 24.445 ms/op
                 existUser·p1.00:   26.509 ms/op

Iteration   3: 3.279 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.276 ms/op
                 existUser·p0.50:   3.178 ms/op
                 existUser·p0.90:   3.584 ms/op
                 existUser·p0.95:   3.838 ms/op
                 existUser·p0.99:   5.751 ms/op
                 existUser·p0.999:  10.224 ms/op
                 existUser·p0.9999: 27.811 ms/op
                 existUser·p1.00:   28.738 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 287164
  mean =      3.343 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6553 
    [ 2.500,  5.000) = 274558 
    [ 5.000,  7.500) = 4694 
    [ 7.500, 10.000) = 892 
    [10.000, 12.500) = 150 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 164 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 54 

  Percentiles, ms/op:
      p(0.0000) =      1.102 ms/op
     p(50.0000) =      3.203 ms/op
     p(90.0000) =      3.727 ms/op
     p(95.0000) =      4.125 ms/op
     p(99.0000) =      6.013 ms/op
     p(99.9000) =     19.197 ms/op
     p(99.9900) =     26.921 ms/op
     p(99.9990) =     28.180 ms/op
     p(99.9999) =     28.738 ms/op
    p(100.0000) =     28.738 ms/op


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
# Warmup Iteration   1: 9.578 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 3.755 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.580 ±(99.9%) 0.013 ms/op
Iteration   1: 3.468 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.524 ms/op
                 getUser·p0.50:   3.322 ms/op
                 getUser·p0.90:   3.903 ms/op
                 getUser·p0.95:   4.383 ms/op
                 getUser·p0.99:   6.576 ms/op
                 getUser·p0.999:  13.879 ms/op
                 getUser·p0.9999: 27.969 ms/op
                 getUser·p1.00:   28.770 ms/op

Iteration   2: 3.416 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.995 ms/op
                 getUser·p0.50:   3.318 ms/op
                 getUser·p0.90:   3.928 ms/op
                 getUser·p0.95:   4.170 ms/op
                 getUser·p0.99:   5.456 ms/op
                 getUser·p0.999:  22.042 ms/op
                 getUser·p0.9999: 29.426 ms/op
                 getUser·p1.00:   29.753 ms/op

Iteration   3: 3.535 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.661 ms/op
                 getUser·p0.50:   3.404 ms/op
                 getUser·p0.90:   4.153 ms/op
                 getUser·p0.95:   4.440 ms/op
                 getUser·p0.99:   6.224 ms/op
                 getUser·p0.999:  19.895 ms/op
                 getUser·p0.9999: 25.853 ms/op
                 getUser·p1.00:   29.131 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 276385
  mean =      3.472 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10573 
    [ 2.500,  5.000) = 258746 
    [ 5.000,  7.500) = 5982 
    [ 7.500, 10.000) = 676 
    [10.000, 12.500) = 102 
    [12.500, 15.000) = 38 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 57 
    [22.500, 25.000) = 75 
    [25.000, 27.500) = 64 

  Percentiles, ms/op:
      p(0.0000) =      0.995 ms/op
     p(50.0000) =      3.355 ms/op
     p(90.0000) =      4.014 ms/op
     p(95.0000) =      4.325 ms/op
     p(99.0000) =      6.046 ms/op
     p(99.9000) =     14.504 ms/op
     p(99.9900) =     28.803 ms/op
     p(99.9990) =     29.620 ms/op
     p(99.9999) =     29.753 ms/op
    p(100.0000) =     29.753 ms/op


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
# Warmup Iteration   1: 10.780 ±(99.9%) 0.147 ms/op
# Warmup Iteration   2: 4.425 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.159 ±(99.9%) 0.015 ms/op
Iteration   1: 3.831 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.405 ms/op
                 listUser·p0.50:   3.752 ms/op
                 listUser·p0.90:   3.952 ms/op
                 listUser·p0.95:   4.211 ms/op
                 listUser·p0.99:   6.076 ms/op
                 listUser·p0.999:  18.624 ms/op
                 listUser·p0.9999: 22.936 ms/op
                 listUser·p1.00:   23.986 ms/op

Iteration   2: 4.003 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.091 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   4.432 ms/op
                 listUser·p0.95:   4.784 ms/op
                 listUser·p0.99:   7.258 ms/op
                 listUser·p0.999:  15.532 ms/op
                 listUser·p0.9999: 18.842 ms/op
                 listUser·p1.00:   18.940 ms/op

Iteration   3: 3.904 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.486 ms/op
                 listUser·p0.50:   3.781 ms/op
                 listUser·p0.90:   4.284 ms/op
                 listUser·p0.95:   4.473 ms/op
                 listUser·p0.99:   6.831 ms/op
                 listUser·p0.999:  14.303 ms/op
                 listUser·p0.9999: 16.941 ms/op
                 listUser·p1.00:   17.007 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 245395
  mean =      3.911 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 42 
    [ 2.500,  5.000) = 239064 
    [ 5.000,  7.500) = 4586 
    [ 7.500, 10.000) = 1033 
    [10.000, 12.500) = 224 
    [12.500, 15.000) = 139 
    [15.000, 17.500) = 204 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.405 ms/op
     p(50.0000) =      3.777 ms/op
     p(90.0000) =      4.276 ms/op
     p(95.0000) =      4.522 ms/op
     p(99.0000) =      6.808 ms/op
     p(99.9000) =     15.247 ms/op
     p(99.9900) =     22.086 ms/op
     p(99.9990) =     23.548 ms/op
     p(99.9999) =     23.986 ms/op
    p(100.0000) =     23.986 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.422 ± 5.417  ops/ms
ClientPb.existUser                       thrpt       3   9.983 ± 1.952  ops/ms
ClientPb.getUser                         thrpt       3   9.517 ± 4.280  ops/ms
ClientPb.listUser                        thrpt       3   7.974 ± 2.781  ops/ms
ClientPb.createUser                       avgt       3   3.450 ± 0.929   ms/op
ClientPb.existUser                        avgt       3   3.367 ± 1.186   ms/op
ClientPb.getUser                          avgt       3   3.389 ± 1.224   ms/op
ClientPb.listUser                         avgt       3   3.994 ± 0.737   ms/op
ClientPb.createUser                     sample  281077   3.414 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.323           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.351           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.834           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.211           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.661           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.331           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.556           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.132           ms/op
ClientPb.existUser                      sample  287164   3.343 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.102           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.203           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.727           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.125           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.013           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.197           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.921           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.738           ms/op
ClientPb.getUser                        sample  276385   3.472 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.995           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.355           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.014           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.325           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.046           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.504           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.803           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.753           ms/op
ClientPb.listUser                       sample  245395   3.911 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.405           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.777           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.276           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.522           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.808           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.247           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.086           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.986           ms/op
