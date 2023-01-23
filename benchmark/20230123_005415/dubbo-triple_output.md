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
# Warmup Iteration   1: 2.387 ops/ms
# Warmup Iteration   2: 5.372 ops/ms
# Warmup Iteration   3: 9.177 ops/ms
Iteration   1: 9.764 ops/ms
Iteration   2: 9.424 ops/ms
Iteration   3: 10.285 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.825 ±(99.9%) 7.914 ops/ms [Average]
  (min, avg, max) = (9.424, 9.825, 10.285), stdev = 0.434
  CI (99.9%): [1.911, 17.738] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.335 ops/ms
# Warmup Iteration   2: 9.083 ops/ms
# Warmup Iteration   3: 10.555 ops/ms
Iteration   1: 10.379 ops/ms
Iteration   2: 10.554 ops/ms
Iteration   3: 9.992 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.309 ±(99.9%) 5.246 ops/ms [Average]
  (min, avg, max) = (9.992, 10.309, 10.554), stdev = 0.288
  CI (99.9%): [5.063, 15.555] (assumes normal distribution)


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
# Warmup Iteration   1: 3.250 ops/ms
# Warmup Iteration   2: 9.269 ops/ms
# Warmup Iteration   3: 9.673 ops/ms
Iteration   1: 10.031 ops/ms
Iteration   2: 10.489 ops/ms
Iteration   3: 9.831 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.117 ±(99.9%) 6.156 ops/ms [Average]
  (min, avg, max) = (9.831, 10.117, 10.489), stdev = 0.337
  CI (99.9%): [3.961, 16.273] (assumes normal distribution)


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
# Warmup Iteration   1: 3.324 ops/ms
# Warmup Iteration   2: 7.840 ops/ms
# Warmup Iteration   3: 7.992 ops/ms
Iteration   1: 8.598 ops/ms
Iteration   2: 8.037 ops/ms
Iteration   3: 8.715 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.450 ±(99.9%) 6.612 ops/ms [Average]
  (min, avg, max) = (8.037, 8.450, 8.715), stdev = 0.362
  CI (99.9%): [1.838, 15.062] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.690 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.637 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.246 ±(99.9%) 0.004 ms/op
Iteration   1: 3.293 ±(99.9%) 0.005 ms/op
Iteration   2: 3.245 ±(99.9%) 0.006 ms/op
Iteration   3: 3.155 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.231 ±(99.9%) 1.285 ms/op [Average]
  (min, avg, max) = (3.155, 3.231, 3.293), stdev = 0.070
  CI (99.9%): [1.947, 4.516] (assumes normal distribution)


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
# Warmup Iteration   1: 7.067 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.428 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.086 ±(99.9%) 0.002 ms/op
Iteration   1: 3.048 ±(99.9%) 0.005 ms/op
Iteration   2: 3.221 ±(99.9%) 0.006 ms/op
Iteration   3: 3.006 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.092 ±(99.9%) 2.080 ms/op [Average]
  (min, avg, max) = (3.006, 3.092, 3.221), stdev = 0.114
  CI (99.9%): [1.011, 5.172] (assumes normal distribution)


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
# Warmup Iteration   1: 8.391 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.400 ±(99.9%) 0.001 ms/op
# Warmup Iteration   3: 3.295 ±(99.9%) 0.004 ms/op
Iteration   1: 3.169 ±(99.9%) 0.002 ms/op
Iteration   2: 3.150 ±(99.9%) 0.005 ms/op
Iteration   3: 3.217 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.179 ±(99.9%) 0.633 ms/op [Average]
  (min, avg, max) = (3.150, 3.179, 3.217), stdev = 0.035
  CI (99.9%): [2.546, 3.812] (assumes normal distribution)


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
# Warmup Iteration   1: 8.579 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.157 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.956 ±(99.9%) 0.004 ms/op
Iteration   1: 3.711 ±(99.9%) 0.010 ms/op
Iteration   2: 3.769 ±(99.9%) 0.005 ms/op
Iteration   3: 3.687 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.722 ±(99.9%) 0.762 ms/op [Average]
  (min, avg, max) = (3.687, 3.722, 3.769), stdev = 0.042
  CI (99.9%): [2.961, 4.484] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 8.193 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 3.627 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.209 ±(99.9%) 0.008 ms/op
Iteration   1: 3.365 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.823 ms/op
                 createUser·p0.50:   3.277 ms/op
                 createUser·p0.90:   3.912 ms/op
                 createUser·p0.95:   4.137 ms/op
                 createUser·p0.99:   5.520 ms/op
                 createUser·p0.999:  15.692 ms/op
                 createUser·p0.9999: 18.236 ms/op
                 createUser·p1.00:   19.268 ms/op

Iteration   2: 3.211 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.309 ms/op
                 createUser·p0.50:   3.158 ms/op
                 createUser·p0.90:   3.424 ms/op
                 createUser·p0.95:   4.026 ms/op
                 createUser·p0.99:   5.587 ms/op
                 createUser·p0.999:  14.647 ms/op
                 createUser·p0.9999: 21.374 ms/op
                 createUser·p1.00:   22.053 ms/op

Iteration   3: 3.215 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.781 ms/op
                 createUser·p0.50:   3.166 ms/op
                 createUser·p0.90:   3.609 ms/op
                 createUser·p0.95:   3.916 ms/op
                 createUser·p0.99:   5.480 ms/op
                 createUser·p0.999:  14.394 ms/op
                 createUser·p0.9999: 21.009 ms/op
                 createUser·p1.00:   22.020 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 293978
  mean =      3.262 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21661 
    [ 2.500,  5.000) = 266379 
    [ 5.000,  7.500) = 5019 
    [ 7.500, 10.000) = 463 
    [10.000, 12.500) = 65 
    [12.500, 15.000) = 117 
    [15.000, 17.500) = 80 
    [17.500, 20.000) = 86 
    [20.000, 22.500) = 108 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.781 ms/op
     p(50.0000) =      3.199 ms/op
     p(90.0000) =      3.756 ms/op
     p(95.0000) =      4.051 ms/op
     p(99.0000) =      5.546 ms/op
     p(99.9000) =     14.615 ms/op
     p(99.9900) =     21.004 ms/op
     p(99.9990) =     21.989 ms/op
     p(99.9999) =     22.053 ms/op
    p(100.0000) =     22.053 ms/op


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
# Warmup Iteration   1: 7.605 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 3.333 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.215 ±(99.9%) 0.008 ms/op
Iteration   1: 3.091 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.910 ms/op
                 existUser·p0.50:   3.060 ms/op
                 existUser·p0.90:   3.326 ms/op
                 existUser·p0.95:   3.658 ms/op
                 existUser·p0.99:   5.251 ms/op
                 existUser·p0.999:  9.728 ms/op
                 existUser·p0.9999: 21.842 ms/op
                 existUser·p1.00:   22.479 ms/op

Iteration   2: 3.182 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.102 ms/op
                 existUser·p0.50:   3.162 ms/op
                 existUser·p0.90:   3.342 ms/op
                 existUser·p0.95:   3.711 ms/op
                 existUser·p0.99:   5.538 ms/op
                 existUser·p0.999:  14.926 ms/op
                 existUser·p0.9999: 21.986 ms/op
                 existUser·p1.00:   25.919 ms/op

Iteration   3: 3.201 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.298 ms/op
                 existUser·p0.50:   3.133 ms/op
                 existUser·p0.90:   3.658 ms/op
                 existUser·p0.95:   3.957 ms/op
                 existUser·p0.99:   5.833 ms/op
                 existUser·p0.999:  8.914 ms/op
                 existUser·p0.9999: 23.364 ms/op
                 existUser·p1.00:   24.347 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 304041
  mean =      3.157 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25684 
    [ 2.500,  5.000) = 271392 
    [ 5.000,  7.500) = 6073 
    [ 7.500, 10.000) = 532 
    [10.000, 12.500) = 18 
    [12.500, 15.000) = 58 
    [15.000, 17.500) = 62 
    [17.500, 20.000) = 69 
    [20.000, 22.500) = 129 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.298 ms/op
     p(50.0000) =      3.125 ms/op
     p(90.0000) =      3.478 ms/op
     p(95.0000) =      3.826 ms/op
     p(99.0000) =      5.530 ms/op
     p(99.9000) =     14.248 ms/op
     p(99.9900) =     22.217 ms/op
     p(99.9990) =     25.623 ms/op
     p(99.9999) =     25.919 ms/op
    p(100.0000) =     25.919 ms/op


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
# Warmup Iteration   1: 7.385 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 3.548 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.326 ±(99.9%) 0.009 ms/op
Iteration   1: 3.215 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.653 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.465 ms/op
                 getUser·p0.95:   4.088 ms/op
                 getUser·p0.99:   6.668 ms/op
                 getUser·p0.999:  10.084 ms/op
                 getUser·p0.9999: 20.514 ms/op
                 getUser·p1.00:   21.594 ms/op

Iteration   2: 3.204 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.229 ms/op
                 getUser·p0.50:   3.080 ms/op
                 getUser·p0.90:   3.498 ms/op
                 getUser·p0.95:   3.682 ms/op
                 getUser·p0.99:   5.792 ms/op
                 getUser·p0.999:  15.383 ms/op
                 getUser·p0.9999: 24.577 ms/op
                 getUser·p1.00:   26.182 ms/op

Iteration   3: 3.206 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.606 ms/op
                 getUser·p0.50:   3.129 ms/op
                 getUser·p0.90:   3.531 ms/op
                 getUser·p0.95:   3.797 ms/op
                 getUser·p0.99:   6.220 ms/op
                 getUser·p0.999:  11.895 ms/op
                 getUser·p0.9999: 21.627 ms/op
                 getUser·p1.00:   22.544 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 299190
  mean =      3.208 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7916 
    [ 2.500,  5.000) = 284553 
    [ 5.000,  7.500) = 5807 
    [ 7.500, 10.000) = 493 
    [10.000, 12.500) = 46 
    [12.500, 15.000) = 88 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 105 
    [20.000, 22.500) = 90 
    [22.500, 25.000) = 57 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.229 ms/op
     p(50.0000) =      3.092 ms/op
     p(90.0000) =      3.502 ms/op
     p(95.0000) =      3.785 ms/op
     p(99.0000) =      6.382 ms/op
     p(99.9000) =     14.474 ms/op
     p(99.9900) =     23.560 ms/op
     p(99.9990) =     25.002 ms/op
     p(99.9999) =     26.182 ms/op
    p(100.0000) =     26.182 ms/op


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
# Warmup Iteration   1: 9.197 ±(99.9%) 0.127 ms/op
# Warmup Iteration   2: 4.164 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.991 ±(99.9%) 0.013 ms/op
Iteration   1: 3.803 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.569 ms/op
                 listUser·p0.50:   3.699 ms/op
                 listUser·p0.90:   4.227 ms/op
                 listUser·p0.95:   4.596 ms/op
                 listUser·p0.99:   7.037 ms/op
                 listUser·p0.999:  17.496 ms/op
                 listUser·p0.9999: 19.942 ms/op
                 listUser·p1.00:   21.398 ms/op

Iteration   2: 3.761 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.228 ms/op
                 listUser·p0.50:   3.645 ms/op
                 listUser·p0.90:   4.026 ms/op
                 listUser·p0.95:   4.202 ms/op
                 listUser·p0.99:   6.504 ms/op
                 listUser·p0.999:  13.369 ms/op
                 listUser·p0.9999: 16.089 ms/op
                 listUser·p1.00:   16.368 ms/op

Iteration   3: 3.843 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.167 ms/op
                 listUser·p0.50:   3.658 ms/op
                 listUser·p0.90:   4.194 ms/op
                 listUser·p0.95:   4.596 ms/op
                 listUser·p0.99:   7.506 ms/op
                 listUser·p0.999:  12.419 ms/op
                 listUser·p0.9999: 19.104 ms/op
                 listUser·p1.00:   21.791 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 252261
  mean =      3.802 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 68 
    [ 2.500,  5.000) = 244044 
    [ 5.000,  7.500) = 6221 
    [ 7.500, 10.000) = 1304 
    [10.000, 12.500) = 241 
    [12.500, 15.000) = 184 
    [15.000, 17.500) = 85 
    [17.500, 20.000) = 103 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.569 ms/op
     p(50.0000) =      3.670 ms/op
     p(90.0000) =      4.129 ms/op
     p(95.0000) =      4.481 ms/op
     p(99.0000) =      7.037 ms/op
     p(99.9000) =     13.697 ms/op
     p(99.9900) =     19.653 ms/op
     p(99.9990) =     21.774 ms/op
     p(99.9999) =     21.791 ms/op
    p(100.0000) =     21.791 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.825 ± 7.914  ops/ms
ClientPb.existUser                       thrpt       3  10.309 ± 5.246  ops/ms
ClientPb.getUser                         thrpt       3  10.117 ± 6.156  ops/ms
ClientPb.listUser                        thrpt       3   8.450 ± 6.612  ops/ms
ClientPb.createUser                       avgt       3   3.231 ± 1.285   ms/op
ClientPb.existUser                        avgt       3   3.092 ± 2.080   ms/op
ClientPb.getUser                          avgt       3   3.179 ± 0.633   ms/op
ClientPb.listUser                         avgt       3   3.722 ± 0.762   ms/op
ClientPb.createUser                     sample  293978   3.262 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.781           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.199           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.756           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.051           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.546           ms/op
ClientPb.createUser:createUser·p0.999   sample          14.615           ms/op
ClientPb.createUser:createUser·p0.9999  sample          21.004           ms/op
ClientPb.createUser:createUser·p1.00    sample          22.053           ms/op
ClientPb.existUser                      sample  304041   3.157 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.298           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.125           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.478           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.826           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.530           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.248           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.217           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.919           ms/op
ClientPb.getUser                        sample  299190   3.208 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.229           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.092           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.502           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.785           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.382           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.474           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.560           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.182           ms/op
ClientPb.listUser                       sample  252261   3.802 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.569           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.670           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.129           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.481           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.037           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.697           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.653           ms/op
ClientPb.listUser:listUser·p1.00        sample          21.791           ms/op
