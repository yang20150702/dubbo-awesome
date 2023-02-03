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
# Warmup Iteration   1: 2.275 ops/ms
# Warmup Iteration   2: 5.533 ops/ms
# Warmup Iteration   3: 8.925 ops/ms
Iteration   1: 9.456 ops/ms
Iteration   2: 9.467 ops/ms
Iteration   3: 9.563 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.495 ±(99.9%) 1.070 ops/ms [Average]
  (min, avg, max) = (9.456, 9.495, 9.563), stdev = 0.059
  CI (99.9%): [8.425, 10.566] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.497 ops/ms
# Warmup Iteration   2: 8.711 ops/ms
# Warmup Iteration   3: 9.799 ops/ms
Iteration   1: 9.901 ops/ms
Iteration   2: 10.046 ops/ms
Iteration   3: 9.627 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.858 ±(99.9%) 3.888 ops/ms [Average]
  (min, avg, max) = (9.627, 9.858, 10.046), stdev = 0.213
  CI (99.9%): [5.970, 13.746] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.891 ops/ms
# Warmup Iteration   2: 8.488 ops/ms
# Warmup Iteration   3: 9.242 ops/ms
Iteration   1: 9.501 ops/ms
Iteration   2: 9.326 ops/ms
Iteration   3: 9.385 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.404 ±(99.9%) 1.630 ops/ms [Average]
  (min, avg, max) = (9.326, 9.404, 9.501), stdev = 0.089
  CI (99.9%): [7.775, 11.034] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 2.687 ops/ms
# Warmup Iteration   2: 7.420 ops/ms
# Warmup Iteration   3: 8.143 ops/ms
Iteration   1: 8.094 ops/ms
Iteration   2: 8.306 ops/ms
Iteration   3: 8.366 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.255 ±(99.9%) 2.603 ops/ms [Average]
  (min, avg, max) = (8.094, 8.255, 8.366), stdev = 0.143
  CI (99.9%): [5.652, 10.858] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 9.741 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.715 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.579 ±(99.9%) 0.008 ms/op
Iteration   1: 3.356 ±(99.9%) 0.008 ms/op
Iteration   2: 3.285 ±(99.9%) 0.007 ms/op
Iteration   3: 3.307 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.316 ±(99.9%) 0.664 ms/op [Average]
  (min, avg, max) = (3.285, 3.316, 3.356), stdev = 0.036
  CI (99.9%): [2.652, 3.980] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 7.803 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.470 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.305 ±(99.9%) 0.003 ms/op
Iteration   1: 3.189 ±(99.9%) 0.008 ms/op
Iteration   2: 3.286 ±(99.9%) 0.004 ms/op
Iteration   3: 3.379 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.284 ±(99.9%) 1.736 ms/op [Average]
  (min, avg, max) = (3.189, 3.284, 3.379), stdev = 0.095
  CI (99.9%): [1.548, 5.021] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 8.821 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.633 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.655 ±(99.9%) 0.005 ms/op
Iteration   1: 3.368 ±(99.9%) 0.006 ms/op
Iteration   2: 3.402 ±(99.9%) 0.008 ms/op
Iteration   3: 3.381 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.384 ±(99.9%) 0.307 ms/op [Average]
  (min, avg, max) = (3.368, 3.384, 3.402), stdev = 0.017
  CI (99.9%): [3.077, 3.690] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 10.545 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.333 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.232 ±(99.9%) 0.003 ms/op
Iteration   1: 3.992 ±(99.9%) 0.008 ms/op
Iteration   2: 3.950 ±(99.9%) 0.006 ms/op
Iteration   3: 3.872 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.938 ±(99.9%) 1.117 ms/op [Average]
  (min, avg, max) = (3.872, 3.938, 3.992), stdev = 0.061
  CI (99.9%): [2.821, 5.055] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 8.486 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 3.756 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.497 ±(99.9%) 0.010 ms/op
Iteration   1: 3.362 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.043 ms/op
                 createUser·p0.50:   3.301 ms/op
                 createUser·p0.90:   3.777 ms/op
                 createUser·p0.95:   4.022 ms/op
                 createUser·p0.99:   5.644 ms/op
                 createUser·p0.999:  17.815 ms/op
                 createUser·p0.9999: 20.561 ms/op
                 createUser·p1.00:   20.906 ms/op

Iteration   2: 3.340 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.999 ms/op
                 createUser·p0.50:   3.232 ms/op
                 createUser·p0.90:   3.772 ms/op
                 createUser·p0.95:   4.162 ms/op
                 createUser·p0.99:   5.251 ms/op
                 createUser·p0.999:  18.011 ms/op
                 createUser·p0.9999: 23.197 ms/op
                 createUser·p1.00:   25.428 ms/op

Iteration   3: 3.389 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.980 ms/op
                 createUser·p0.50:   3.219 ms/op
                 createUser·p0.90:   3.854 ms/op
                 createUser·p0.95:   4.284 ms/op
                 createUser·p0.99:   5.890 ms/op
                 createUser·p0.999:  19.406 ms/op
                 createUser·p0.9999: 25.159 ms/op
                 createUser·p1.00:   26.214 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 285378
  mean =      3.364 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7127 
    [ 2.500,  5.000) = 272954 
    [ 5.000,  7.500) = 4364 
    [ 7.500, 10.000) = 530 
    [10.000, 12.500) = 51 
    [12.500, 15.000) = 13 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 134 
    [20.000, 22.500) = 131 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.980 ms/op
     p(50.0000) =      3.248 ms/op
     p(90.0000) =      3.805 ms/op
     p(95.0000) =      4.133 ms/op
     p(99.0000) =      5.644 ms/op
     p(99.9000) =     18.796 ms/op
     p(99.9900) =     24.213 ms/op
     p(99.9990) =     25.869 ms/op
     p(99.9999) =     26.214 ms/op
    p(100.0000) =     26.214 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 8.267 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 3.477 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.285 ±(99.9%) 0.009 ms/op
Iteration   1: 3.233 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.751 ms/op
                 existUser·p0.50:   3.203 ms/op
                 existUser·p0.90:   3.457 ms/op
                 existUser·p0.95:   3.850 ms/op
                 existUser·p0.99:   5.358 ms/op
                 existUser·p0.999:  10.320 ms/op
                 existUser·p0.9999: 27.492 ms/op
                 existUser·p1.00:   28.672 ms/op

Iteration   2: 3.355 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.653 ms/op
                 existUser·p0.50:   3.248 ms/op
                 existUser·p0.90:   3.863 ms/op
                 existUser·p0.95:   4.325 ms/op
                 existUser·p0.99:   5.767 ms/op
                 existUser·p0.999:  8.749 ms/op
                 existUser·p0.9999: 27.638 ms/op
                 existUser·p1.00:   28.705 ms/op

Iteration   3: 3.264 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.323 ms/op
                 existUser·p0.50:   3.248 ms/op
                 existUser·p0.90:   3.437 ms/op
                 existUser·p0.95:   3.785 ms/op
                 existUser·p0.99:   5.292 ms/op
                 existUser·p0.999:  13.393 ms/op
                 existUser·p0.9999: 34.734 ms/op
                 existUser·p1.00:   35.258 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 292455
  mean =      3.283 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26085 
    [ 2.500,  5.000) = 260123 
    [ 5.000,  7.500) = 5559 
    [ 7.500, 10.000) = 375 
    [10.000, 12.500) = 50 
    [12.500, 15.000) = 7 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 72 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 65 
    [27.500, 30.000) = 31 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 29 
    [35.000, 37.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.751 ms/op
     p(50.0000) =      3.236 ms/op
     p(90.0000) =      3.633 ms/op
     p(95.0000) =      4.030 ms/op
     p(99.0000) =      5.530 ms/op
     p(99.9000) =     10.207 ms/op
     p(99.9900) =     34.144 ms/op
     p(99.9990) =     35.127 ms/op
     p(99.9999) =     35.258 ms/op
    p(100.0000) =     35.258 ms/op


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
# Warmup Iteration   1: 8.903 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 3.554 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.436 ±(99.9%) 0.010 ms/op
Iteration   1: 3.435 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.233 ms/op
                 getUser·p0.50:   3.330 ms/op
                 getUser·p0.90:   3.899 ms/op
                 getUser·p0.95:   4.276 ms/op
                 getUser·p0.99:   6.319 ms/op
                 getUser·p0.999:  10.544 ms/op
                 getUser·p0.9999: 21.594 ms/op
                 getUser·p1.00:   24.707 ms/op

Iteration   2: 3.343 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.683 ms/op
                 getUser·p0.50:   3.195 ms/op
                 getUser·p0.90:   3.637 ms/op
                 getUser·p0.95:   3.924 ms/op
                 getUser·p0.99:   6.922 ms/op
                 getUser·p0.999:  18.649 ms/op
                 getUser·p0.9999: 23.509 ms/op
                 getUser·p1.00:   24.084 ms/op

Iteration   3: 3.467 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.389 ms/op
                 getUser·p0.50:   3.334 ms/op
                 getUser·p0.90:   3.940 ms/op
                 getUser·p0.95:   4.284 ms/op
                 getUser·p0.99:   6.218 ms/op
                 getUser·p0.999:  18.645 ms/op
                 getUser·p0.9999: 27.157 ms/op
                 getUser·p1.00:   28.475 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 281137
  mean =      3.414 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6169 
    [ 2.500,  5.000) = 266840 
    [ 5.000,  7.500) = 7143 
    [ 7.500, 10.000) = 649 
    [10.000, 12.500) = 65 
    [12.500, 15.000) = 9 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 86 
    [20.000, 22.500) = 106 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      1.233 ms/op
     p(50.0000) =      3.277 ms/op
     p(90.0000) =      3.854 ms/op
     p(95.0000) =      4.219 ms/op
     p(99.0000) =      6.693 ms/op
     p(99.9000) =     10.751 ms/op
     p(99.9900) =     25.531 ms/op
     p(99.9990) =     27.911 ms/op
     p(99.9999) =     28.475 ms/op
    p(100.0000) =     28.475 ms/op


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
# Warmup Iteration   1: 10.256 ±(99.9%) 0.139 ms/op
# Warmup Iteration   2: 4.205 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.998 ±(99.9%) 0.013 ms/op
Iteration   1: 4.110 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.892 ms/op
                 listUser·p0.50:   3.908 ms/op
                 listUser·p0.90:   4.489 ms/op
                 listUser·p0.95:   5.546 ms/op
                 listUser·p0.99:   8.520 ms/op
                 listUser·p0.999:  20.257 ms/op
                 listUser·p0.9999: 23.443 ms/op
                 listUser·p1.00:   24.543 ms/op

Iteration   2: 3.952 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.454 ms/op
                 listUser·p0.50:   3.777 ms/op
                 listUser·p0.90:   4.383 ms/op
                 listUser·p0.95:   4.956 ms/op
                 listUser·p0.99:   7.881 ms/op
                 listUser·p0.999:  15.516 ms/op
                 listUser·p0.9999: 23.348 ms/op
                 listUser·p1.00:   24.314 ms/op

Iteration   3: 3.917 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.154 ms/op
                 listUser·p0.50:   3.830 ms/op
                 listUser·p0.90:   4.211 ms/op
                 listUser·p0.95:   4.384 ms/op
                 listUser·p0.99:   7.045 ms/op
                 listUser·p0.999:  14.998 ms/op
                 listUser·p0.9999: 21.170 ms/op
                 listUser·p1.00:   22.446 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 240344
  mean =      3.991 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 54 
    [ 2.500,  5.000) = 229787 
    [ 5.000,  7.500) = 7510 
    [ 7.500, 10.000) = 2056 
    [10.000, 12.500) = 379 
    [12.500, 15.000) = 158 
    [15.000, 17.500) = 217 
    [17.500, 20.000) = 63 
    [20.000, 22.500) = 76 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.454 ms/op
     p(50.0000) =      3.822 ms/op
     p(90.0000) =      4.342 ms/op
     p(95.0000) =      4.792 ms/op
     p(99.0000) =      7.889 ms/op
     p(99.9000) =     15.991 ms/op
     p(99.9900) =     23.134 ms/op
     p(99.9990) =     24.301 ms/op
     p(99.9999) =     24.543 ms/op
    p(100.0000) =     24.543 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.495 ± 1.070  ops/ms
ClientPb.existUser                       thrpt       3   9.858 ± 3.888  ops/ms
ClientPb.getUser                         thrpt       3   9.404 ± 1.630  ops/ms
ClientPb.listUser                        thrpt       3   8.255 ± 2.603  ops/ms
ClientPb.createUser                       avgt       3   3.316 ± 0.664   ms/op
ClientPb.existUser                        avgt       3   3.284 ± 1.736   ms/op
ClientPb.getUser                          avgt       3   3.384 ± 0.307   ms/op
ClientPb.listUser                         avgt       3   3.938 ± 1.117   ms/op
ClientPb.createUser                     sample  285378   3.364 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.980           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.248           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.805           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.133           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.644           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.796           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.213           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.214           ms/op
ClientPb.existUser                      sample  292455   3.283 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.751           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.236           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.633           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.030           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.530           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.207           ms/op
ClientPb.existUser:existUser·p0.9999    sample          34.144           ms/op
ClientPb.existUser:existUser·p1.00      sample          35.258           ms/op
ClientPb.getUser                        sample  281137   3.414 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.233           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.277           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.854           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.219           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.693           ms/op
ClientPb.getUser:getUser·p0.999         sample          10.751           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.531           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.475           ms/op
ClientPb.listUser                       sample  240344   3.991 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.454           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.822           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.342           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.792           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.889           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.991           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.134           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.543           ms/op
