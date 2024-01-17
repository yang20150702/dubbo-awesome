# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 5.105 ops/ms
# Warmup Iteration   2: 12.397 ops/ms
# Warmup Iteration   3: 12.557 ops/ms
Iteration   1: 12.744 ops/ms
Iteration   2: 12.687 ops/ms
Iteration   3: 12.853 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.761 ±(99.9%) 1.545 ops/ms [Average]
  (min, avg, max) = (12.687, 12.761, 12.853), stdev = 0.085
  CI (99.9%): [11.217, 14.306] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.278 ops/ms
# Warmup Iteration   2: 13.338 ops/ms
# Warmup Iteration   3: 13.242 ops/ms
Iteration   1: 13.320 ops/ms
Iteration   2: 13.237 ops/ms
Iteration   3: 13.309 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.289 ±(99.9%) 0.821 ops/ms [Average]
  (min, avg, max) = (13.237, 13.289, 13.320), stdev = 0.045
  CI (99.9%): [12.468, 14.109] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.074 ops/ms
# Warmup Iteration   2: 12.991 ops/ms
# Warmup Iteration   3: 13.003 ops/ms
Iteration   1: 13.062 ops/ms
Iteration   2: 12.973 ops/ms
Iteration   3: 13.099 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.045 ±(99.9%) 1.179 ops/ms [Average]
  (min, avg, max) = (12.973, 13.045, 13.099), stdev = 0.065
  CI (99.9%): [11.866, 14.224] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:44
# Fork: 1 of 1
# Warmup Iteration   1: 6.598 ops/ms
# Warmup Iteration   2: 10.548 ops/ms
# Warmup Iteration   3: 10.632 ops/ms
Iteration   1: 10.730 ops/ms
Iteration   2: 10.783 ops/ms
Iteration   3: 10.764 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.759 ±(99.9%) 0.496 ops/ms [Average]
  (min, avg, max) = (10.730, 10.759, 10.783), stdev = 0.027
  CI (99.9%): [10.263, 11.255] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 3.769 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.522 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.492 ±(99.9%) 0.004 ms/op
Iteration   1: 2.508 ±(99.9%) 0.004 ms/op
Iteration   2: 2.484 ±(99.9%) 0.004 ms/op
Iteration   3: 2.472 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.488 ±(99.9%) 0.331 ms/op [Average]
  (min, avg, max) = (2.472, 2.488, 2.508), stdev = 0.018
  CI (99.9%): [2.157, 2.819] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:33
# Fork: 1 of 1
# Warmup Iteration   1: 3.569 ±(99.9%) 0.008 ms/op
# Warmup Iteration   2: 2.412 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.404 ±(99.9%) 0.003 ms/op
Iteration   1: 2.392 ±(99.9%) 0.004 ms/op
Iteration   2: 2.403 ±(99.9%) 0.004 ms/op
Iteration   3: 2.379 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.391 ±(99.9%) 0.216 ms/op [Average]
  (min, avg, max) = (2.379, 2.391, 2.403), stdev = 0.012
  CI (99.9%): [2.175, 2.607] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.737 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.504 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.478 ±(99.9%) 0.004 ms/op
Iteration   1: 2.464 ±(99.9%) 0.005 ms/op
Iteration   2: 2.456 ±(99.9%) 0.004 ms/op
Iteration   3: 2.452 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.457 ±(99.9%) 0.113 ms/op [Average]
  (min, avg, max) = (2.452, 2.457, 2.464), stdev = 0.006
  CI (99.9%): [2.344, 2.570] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.543 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.099 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.051 ±(99.9%) 0.006 ms/op
Iteration   1: 3.060 ±(99.9%) 0.005 ms/op
Iteration   2: 3.039 ±(99.9%) 0.006 ms/op
Iteration   3: 3.018 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.039 ±(99.9%) 0.383 ms/op [Average]
  (min, avg, max) = (3.018, 3.039, 3.060), stdev = 0.021
  CI (99.9%): [2.656, 3.422] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 3.893 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.597 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.494 ±(99.9%) 0.005 ms/op
Iteration   1: 2.479 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.848 ms/op
                 createUser·p0.50:   2.486 ms/op
                 createUser·p0.90:   3.027 ms/op
                 createUser·p0.95:   3.158 ms/op
                 createUser·p0.99:   3.727 ms/op
                 createUser·p0.999:  7.363 ms/op
                 createUser·p0.9999: 15.827 ms/op
                 createUser·p1.00:   16.253 ms/op

Iteration   2: 2.467 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.021 ms/op
                 createUser·p0.50:   2.527 ms/op
                 createUser·p0.90:   2.990 ms/op
                 createUser·p0.95:   3.092 ms/op
                 createUser·p0.99:   3.690 ms/op
                 createUser·p0.999:  9.265 ms/op
                 createUser·p0.9999: 12.242 ms/op
                 createUser·p1.00:   13.631 ms/op

Iteration   3: 2.477 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.687 ms/op
                 createUser·p0.50:   2.523 ms/op
                 createUser·p0.90:   3.011 ms/op
                 createUser·p0.95:   3.121 ms/op
                 createUser·p0.99:   3.674 ms/op
                 createUser·p0.999:  9.241 ms/op
                 createUser·p0.9999: 10.868 ms/op
                 createUser·p1.00:   14.385 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 387598
  mean =      2.474 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 68 
    [ 1.250,  2.500) = 192918 
    [ 2.500,  3.750) = 191053 
    [ 3.750,  5.000) = 2626 
    [ 5.000,  6.250) = 419 
    [ 6.250,  7.500) = 47 
    [ 7.500,  8.750) = 64 
    [ 8.750, 10.000) = 117 
    [10.000, 11.250) = 117 
    [11.250, 12.500) = 69 
    [12.500, 13.750) = 51 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 29 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.687 ms/op
     p(50.0000) =      2.507 ms/op
     p(90.0000) =      3.011 ms/op
     p(95.0000) =      3.125 ms/op
     p(99.0000) =      3.703 ms/op
     p(99.9000) =      9.231 ms/op
     p(99.9900) =     13.983 ms/op
     p(99.9990) =     16.028 ms/op
     p(99.9999) =     16.253 ms/op
    p(100.0000) =     16.253 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.630 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 2.454 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.410 ±(99.9%) 0.005 ms/op
Iteration   1: 2.405 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.984 ms/op
                 existUser·p0.50:   2.486 ms/op
                 existUser·p0.90:   2.916 ms/op
                 existUser·p0.95:   3.002 ms/op
                 existUser·p0.99:   3.305 ms/op
                 existUser·p0.999:  4.956 ms/op
                 existUser·p0.9999: 13.320 ms/op
                 existUser·p1.00:   13.943 ms/op

Iteration   2: 2.427 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.079 ms/op
                 existUser·p0.50:   2.540 ms/op
                 existUser·p0.90:   2.937 ms/op
                 existUser·p0.95:   3.027 ms/op
                 existUser·p0.99:   3.383 ms/op
                 existUser·p0.999:  5.579 ms/op
                 existUser·p0.9999: 10.715 ms/op
                 existUser·p1.00:   11.796 ms/op

Iteration   3: 2.439 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.014 ms/op
                 existUser·p0.50:   2.531 ms/op
                 existUser·p0.90:   2.961 ms/op
                 existUser·p0.95:   3.064 ms/op
                 existUser·p0.99:   3.521 ms/op
                 existUser·p0.999:  7.618 ms/op
                 existUser·p0.9999: 12.103 ms/op
                 existUser·p1.00:   12.517 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 395737
  mean =      2.423 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 30 
    [ 1.250,  2.500) = 196354 
    [ 2.500,  3.750) = 197146 
    [ 3.750,  5.000) = 1625 
    [ 5.000,  6.250) = 216 
    [ 6.250,  7.500) = 39 
    [ 7.500,  8.750) = 29 
    [ 8.750, 10.000) = 127 
    [10.000, 11.250) = 38 
    [11.250, 12.500) = 79 
    [12.500, 13.750) = 48 
    [13.750, 15.000) = 6 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.984 ms/op
     p(50.0000) =      2.519 ms/op
     p(90.0000) =      2.937 ms/op
     p(95.0000) =      3.031 ms/op
     p(99.0000) =      3.391 ms/op
     p(99.9000) =      5.579 ms/op
     p(99.9900) =     12.721 ms/op
     p(99.9990) =     13.829 ms/op
     p(99.9999) =     13.943 ms/op
    p(100.0000) =     13.943 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.830 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.553 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.483 ±(99.9%) 0.006 ms/op
Iteration   1: 2.487 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.982 ms/op
                 getUser·p0.50:   2.511 ms/op
                 getUser·p0.90:   3.031 ms/op
                 getUser·p0.95:   3.162 ms/op
                 getUser·p0.99:   3.854 ms/op
                 getUser·p0.999:  9.943 ms/op
                 getUser·p0.9999: 13.718 ms/op
                 getUser·p1.00:   14.320 ms/op

Iteration   2: 2.478 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.995 ms/op
                 getUser·p0.50:   2.486 ms/op
                 getUser·p0.90:   3.031 ms/op
                 getUser·p0.95:   3.170 ms/op
                 getUser·p0.99:   3.933 ms/op
                 getUser·p0.999:  6.149 ms/op
                 getUser·p0.9999: 11.667 ms/op
                 getUser·p1.00:   12.059 ms/op

Iteration   3: 2.503 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.916 ms/op
                 getUser·p0.50:   2.519 ms/op
                 getUser·p0.90:   3.052 ms/op
                 getUser·p0.95:   3.215 ms/op
                 getUser·p0.99:   4.243 ms/op
                 getUser·p0.999:  8.067 ms/op
                 getUser·p0.9999: 11.394 ms/op
                 getUser·p1.00:   12.714 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 385263
  mean =      2.489 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 100 
    [ 1.250,  2.500) = 192053 
    [ 2.500,  3.750) = 187526 
    [ 3.750,  5.000) = 4459 
    [ 5.000,  6.250) = 623 
    [ 6.250,  7.500) = 86 
    [ 7.500,  8.750) = 50 
    [ 8.750, 10.000) = 97 
    [10.000, 11.250) = 101 
    [11.250, 12.500) = 75 
    [12.500, 13.750) = 83 
    [13.750, 15.000) = 10 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.916 ms/op
     p(50.0000) =      2.507 ms/op
     p(90.0000) =      3.035 ms/op
     p(95.0000) =      3.183 ms/op
     p(99.0000) =      3.998 ms/op
     p(99.9000) =      8.536 ms/op
     p(99.9900) =     13.140 ms/op
     p(99.9990) =     14.053 ms/op
     p(99.9999) =     14.320 ms/op
    p(100.0000) =     14.320 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.848 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.103 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.025 ±(99.9%) 0.009 ms/op
Iteration   1: 3.016 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.665 ms/op
                 listUser·p0.50:   2.949 ms/op
                 listUser·p0.90:   3.879 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   5.584 ms/op
                 listUser·p0.999:  9.518 ms/op
                 listUser·p0.9999: 14.889 ms/op
                 listUser·p1.00:   15.204 ms/op

Iteration   2: 3.031 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.884 ms/op
                 listUser·p0.50:   2.970 ms/op
                 listUser·p0.90:   3.944 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   5.603 ms/op
                 listUser·p0.999:  10.347 ms/op
                 listUser·p0.9999: 15.188 ms/op
                 listUser·p1.00:   15.663 ms/op

Iteration   3: 3.042 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.846 ms/op
                 listUser·p0.50:   2.970 ms/op
                 listUser·p0.90:   3.969 ms/op
                 listUser·p0.95:   4.530 ms/op
                 listUser·p0.99:   5.702 ms/op
                 listUser·p0.999:  9.290 ms/op
                 listUser·p0.9999: 11.408 ms/op
                 listUser·p1.00:   12.059 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 316600
  mean =      3.029 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 127 
    [ 1.250,  2.500) = 89851 
    [ 2.500,  3.750) = 185538 
    [ 3.750,  5.000) = 33111 
    [ 5.000,  6.250) = 6573 
    [ 6.250,  7.500) = 715 
    [ 7.500,  8.750) = 170 
    [ 8.750, 10.000) = 267 
    [10.000, 11.250) = 163 
    [11.250, 12.500) = 21 
    [12.500, 13.750) = 7 
    [13.750, 15.000) = 37 
    [15.000, 16.250) = 20 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.665 ms/op
     p(50.0000) =      2.961 ms/op
     p(90.0000) =      3.928 ms/op
     p(95.0000) =      4.448 ms/op
     p(99.0000) =      5.636 ms/op
     p(99.9000) =      9.585 ms/op
     p(99.9900) =     14.729 ms/op
     p(99.9990) =     15.611 ms/op
     p(99.9999) =     15.663 ms/op
    p(100.0000) =     15.663 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.761 ± 1.545  ops/ms
ClientPb.existUser                       thrpt       3  13.289 ± 0.821  ops/ms
ClientPb.getUser                         thrpt       3  13.045 ± 1.179  ops/ms
ClientPb.listUser                        thrpt       3  10.759 ± 0.496  ops/ms
ClientPb.createUser                       avgt       3   2.488 ± 0.331   ms/op
ClientPb.existUser                        avgt       3   2.391 ± 0.216   ms/op
ClientPb.getUser                          avgt       3   2.457 ± 0.113   ms/op
ClientPb.listUser                         avgt       3   3.039 ± 0.383   ms/op
ClientPb.createUser                     sample  387598   2.474 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.687           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.507           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.011           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.125           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.703           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.231           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.983           ms/op
ClientPb.createUser:createUser·p1.00    sample          16.253           ms/op
ClientPb.existUser                      sample  395737   2.423 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.984           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.519           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.937           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.031           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.391           ms/op
ClientPb.existUser:existUser·p0.999     sample           5.579           ms/op
ClientPb.existUser:existUser·p0.9999    sample          12.721           ms/op
ClientPb.existUser:existUser·p1.00      sample          13.943           ms/op
ClientPb.getUser                        sample  385263   2.489 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.916           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.507           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.035           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.183           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.998           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.536           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.140           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.320           ms/op
ClientPb.listUser                       sample  316600   3.029 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.665           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.961           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.928           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.448           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.636           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.585           ms/op
ClientPb.listUser:listUser·p0.9999      sample          14.729           ms/op
ClientPb.listUser:listUser·p1.00        sample          15.663           ms/op
