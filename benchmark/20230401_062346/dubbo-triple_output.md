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
# Warmup Iteration   1: 2.032 ops/ms
# Warmup Iteration   2: 5.447 ops/ms
# Warmup Iteration   3: 8.582 ops/ms
Iteration   1: 9.220 ops/ms
Iteration   2: 9.209 ops/ms
Iteration   3: 9.612 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.347 ±(99.9%) 4.191 ops/ms [Average]
  (min, avg, max) = (9.209, 9.347, 9.612), stdev = 0.230
  CI (99.9%): [5.156, 13.538] (assumes normal distribution)


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
# Warmup Iteration   1: 3.109 ops/ms
# Warmup Iteration   2: 9.099 ops/ms
# Warmup Iteration   3: 9.661 ops/ms
Iteration   1: 9.957 ops/ms
Iteration   2: 9.869 ops/ms
Iteration   3: 9.927 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.918 ±(99.9%) 0.820 ops/ms [Average]
  (min, avg, max) = (9.869, 9.918, 9.957), stdev = 0.045
  CI (99.9%): [9.097, 10.738] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.525 ops/ms
# Warmup Iteration   2: 8.844 ops/ms
# Warmup Iteration   3: 9.024 ops/ms
Iteration   1: 9.227 ops/ms
Iteration   2: 9.701 ops/ms
Iteration   3: 9.579 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.502 ±(99.9%) 4.489 ops/ms [Average]
  (min, avg, max) = (9.227, 9.502, 9.701), stdev = 0.246
  CI (99.9%): [5.013, 13.991] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.012 ops/ms
# Warmup Iteration   2: 7.664 ops/ms
# Warmup Iteration   3: 7.926 ops/ms
Iteration   1: 7.998 ops/ms
Iteration   2: 8.413 ops/ms
Iteration   3: 8.202 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.204 ±(99.9%) 3.782 ops/ms [Average]
  (min, avg, max) = (7.998, 8.204, 8.413), stdev = 0.207
  CI (99.9%): [4.423, 11.986] (assumes normal distribution)


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
# Warmup Iteration   1: 8.431 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 3.778 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.467 ±(99.9%) 0.007 ms/op
Iteration   1: 3.432 ±(99.9%) 0.006 ms/op
Iteration   2: 3.308 ±(99.9%) 0.007 ms/op
Iteration   3: 3.370 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.370 ±(99.9%) 1.135 ms/op [Average]
  (min, avg, max) = (3.308, 3.370, 3.432), stdev = 0.062
  CI (99.9%): [2.235, 4.504] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 7.744 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.487 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.205 ±(99.9%) 0.005 ms/op
Iteration   1: 3.217 ±(99.9%) 0.006 ms/op
Iteration   2: 3.163 ±(99.9%) 0.007 ms/op
Iteration   3: 3.195 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.192 ±(99.9%) 0.503 ms/op [Average]
  (min, avg, max) = (3.163, 3.192, 3.217), stdev = 0.028
  CI (99.9%): [2.689, 3.695] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 8.869 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.629 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.498 ±(99.9%) 0.004 ms/op
Iteration   1: 3.395 ±(99.9%) 0.006 ms/op
Iteration   2: 3.294 ±(99.9%) 0.009 ms/op
Iteration   3: 3.265 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.318 ±(99.9%) 1.248 ms/op [Average]
  (min, avg, max) = (3.265, 3.318, 3.395), stdev = 0.068
  CI (99.9%): [2.071, 4.566] (assumes normal distribution)


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
# Warmup Iteration   1: 9.900 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.287 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.849 ±(99.9%) 0.009 ms/op
Iteration   1: 3.794 ±(99.9%) 0.011 ms/op
Iteration   2: 3.838 ±(99.9%) 0.009 ms/op
Iteration   3: 3.819 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.817 ±(99.9%) 0.398 ms/op [Average]
  (min, avg, max) = (3.794, 3.817, 3.838), stdev = 0.022
  CI (99.9%): [3.419, 4.214] (assumes normal distribution)


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
# Warmup Iteration   1: 9.377 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 3.908 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.491 ±(99.9%) 0.011 ms/op
Iteration   1: 3.375 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.096 ms/op
                 createUser·p0.50:   3.211 ms/op
                 createUser·p0.90:   3.842 ms/op
                 createUser·p0.95:   4.407 ms/op
                 createUser·p0.99:   6.025 ms/op
                 createUser·p0.999:  19.886 ms/op
                 createUser·p0.9999: 22.381 ms/op
                 createUser·p1.00:   23.364 ms/op

Iteration   2: 3.282 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.137 ms/op
                 createUser·p0.50:   3.236 ms/op
                 createUser·p0.90:   3.441 ms/op
                 createUser·p0.95:   3.949 ms/op
                 createUser·p0.99:   5.128 ms/op
                 createUser·p0.999:  14.057 ms/op
                 createUser·p0.9999: 27.665 ms/op
                 createUser·p1.00:   28.934 ms/op

Iteration   3: 3.318 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.534 ms/op
                 createUser·p0.50:   3.244 ms/op
                 createUser·p0.90:   3.469 ms/op
                 createUser·p0.95:   3.838 ms/op
                 createUser·p0.99:   6.735 ms/op
                 createUser·p0.999:  16.555 ms/op
                 createUser·p0.9999: 24.665 ms/op
                 createUser·p1.00:   26.345 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 288733
  mean =      3.325 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15319 
    [ 2.500,  5.000) = 268331 
    [ 5.000,  7.500) = 3671 
    [ 7.500, 10.000) = 835 
    [10.000, 12.500) = 189 
    [12.500, 15.000) = 87 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 164 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      1.096 ms/op
     p(50.0000) =      3.232 ms/op
     p(90.0000) =      3.604 ms/op
     p(95.0000) =      4.084 ms/op
     p(99.0000) =      5.865 ms/op
     p(99.9000) =     16.533 ms/op
     p(99.9900) =     26.288 ms/op
     p(99.9990) =     28.057 ms/op
     p(99.9999) =     28.934 ms/op
    p(100.0000) =     28.934 ms/op


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
# Warmup Iteration   1: 8.697 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 3.600 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.358 ±(99.9%) 0.009 ms/op
Iteration   1: 3.191 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.384 ms/op
                 existUser·p0.50:   3.072 ms/op
                 existUser·p0.90:   3.531 ms/op
                 existUser·p0.95:   3.756 ms/op
                 existUser·p0.99:   5.628 ms/op
                 existUser·p0.999:  8.929 ms/op
                 existUser·p0.9999: 28.571 ms/op
                 existUser·p1.00:   29.655 ms/op

Iteration   2: 3.229 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.366 ms/op
                 existUser·p0.50:   3.211 ms/op
                 existUser·p0.90:   3.391 ms/op
                 existUser·p0.95:   3.727 ms/op
                 existUser·p0.99:   5.562 ms/op
                 existUser·p0.999:  11.675 ms/op
                 existUser·p0.9999: 24.972 ms/op
                 existUser·p1.00:   26.575 ms/op

Iteration   3: 3.329 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.188 ms/op
                 existUser·p0.50:   3.269 ms/op
                 existUser·p0.90:   3.621 ms/op
                 existUser·p0.95:   4.243 ms/op
                 existUser·p0.99:   5.622 ms/op
                 existUser·p0.999:  17.239 ms/op
                 existUser·p0.9999: 24.543 ms/op
                 existUser·p1.00:   24.936 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 295308
  mean =      3.248 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16055 
    [ 2.500,  5.000) = 274339 
    [ 5.000,  7.500) = 3994 
    [ 7.500, 10.000) = 491 
    [10.000, 12.500) = 116 
    [12.500, 15.000) = 57 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 51 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 99 
    [25.000, 27.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      1.188 ms/op
     p(50.0000) =      3.199 ms/op
     p(90.0000) =      3.518 ms/op
     p(95.0000) =      3.850 ms/op
     p(99.0000) =      5.620 ms/op
     p(99.9000) =     13.533 ms/op
     p(99.9900) =     27.191 ms/op
     p(99.9990) =     29.279 ms/op
     p(99.9999) =     29.655 ms/op
    p(100.0000) =     29.655 ms/op


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
# Warmup Iteration   1: 8.780 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 3.568 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.336 ±(99.9%) 0.008 ms/op
Iteration   1: 3.410 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.468 ms/op
                 getUser·p0.50:   3.215 ms/op
                 getUser·p0.90:   3.826 ms/op
                 getUser·p0.95:   4.743 ms/op
                 getUser·p0.99:   6.103 ms/op
                 getUser·p0.999:  19.316 ms/op
                 getUser·p0.9999: 24.146 ms/op
                 getUser·p1.00:   25.068 ms/op

Iteration   2: 3.515 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.133 ms/op
                 getUser·p0.50:   3.363 ms/op
                 getUser·p0.90:   4.076 ms/op
                 getUser·p0.95:   4.694 ms/op
                 getUser·p0.99:   6.242 ms/op
                 getUser·p0.999:  21.035 ms/op
                 getUser·p0.9999: 23.593 ms/op
                 getUser·p1.00:   24.117 ms/op

Iteration   3: 3.492 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.567 ms/op
                 getUser·p0.50:   3.367 ms/op
                 getUser·p0.90:   4.026 ms/op
                 getUser·p0.95:   4.456 ms/op
                 getUser·p0.99:   6.152 ms/op
                 getUser·p0.999:  20.735 ms/op
                 getUser·p0.9999: 23.588 ms/op
                 getUser·p1.00:   24.379 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 276382
  mean =      3.472 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10025 
    [ 2.500,  5.000) = 256980 
    [ 5.000,  7.500) = 8242 
    [ 7.500, 10.000) = 682 
    [10.000, 12.500) = 112 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 170 
    [22.500, 25.000) = 104 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.133 ms/op
     p(50.0000) =      3.334 ms/op
     p(90.0000) =      3.973 ms/op
     p(95.0000) =      4.604 ms/op
     p(99.0000) =      6.169 ms/op
     p(99.9000) =     19.956 ms/op
     p(99.9900) =     23.736 ms/op
     p(99.9990) =     24.672 ms/op
     p(99.9999) =     25.068 ms/op
    p(100.0000) =     25.068 ms/op


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
# Warmup Iteration   1: 9.657 ±(99.9%) 0.129 ms/op
# Warmup Iteration   2: 4.239 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.987 ±(99.9%) 0.012 ms/op
Iteration   1: 3.977 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.403 ms/op
                 listUser·p0.50:   3.834 ms/op
                 listUser·p0.90:   4.325 ms/op
                 listUser·p0.95:   4.604 ms/op
                 listUser·p0.99:   7.055 ms/op
                 listUser·p0.999:  19.464 ms/op
                 listUser·p0.9999: 24.674 ms/op
                 listUser·p1.00:   25.100 ms/op

Iteration   2: 3.927 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.576 ms/op
                 listUser·p0.50:   3.777 ms/op
                 listUser·p0.90:   4.375 ms/op
                 listUser·p0.95:   4.620 ms/op
                 listUser·p0.99:   7.283 ms/op
                 listUser·p0.999:  14.740 ms/op
                 listUser·p0.9999: 17.007 ms/op
                 listUser·p1.00:   18.350 ms/op

Iteration   3: 3.984 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.281 ms/op
                 listUser·p0.50:   3.863 ms/op
                 listUser·p0.90:   4.538 ms/op
                 listUser·p0.95:   4.922 ms/op
                 listUser·p0.99:   6.893 ms/op
                 listUser·p0.999:  12.427 ms/op
                 listUser·p0.9999: 13.713 ms/op
                 listUser·p1.00:   13.746 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 242205
  mean =      3.962 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 37 
    [ 2.500,  5.000) = 233765 
    [ 5.000,  7.500) = 6567 
    [ 7.500, 10.000) = 1145 
    [10.000, 12.500) = 280 
    [12.500, 15.000) = 226 
    [15.000, 17.500) = 85 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.403 ms/op
     p(50.0000) =      3.838 ms/op
     p(90.0000) =      4.391 ms/op
     p(95.0000) =      4.735 ms/op
     p(99.0000) =      7.037 ms/op
     p(99.9000) =     14.595 ms/op
     p(99.9900) =     21.933 ms/op
     p(99.9990) =     24.988 ms/op
     p(99.9999) =     25.100 ms/op
    p(100.0000) =     25.100 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.347 ± 4.191  ops/ms
ClientPb.existUser                       thrpt       3   9.918 ± 0.820  ops/ms
ClientPb.getUser                         thrpt       3   9.502 ± 4.489  ops/ms
ClientPb.listUser                        thrpt       3   8.204 ± 3.782  ops/ms
ClientPb.createUser                       avgt       3   3.370 ± 1.135   ms/op
ClientPb.existUser                        avgt       3   3.192 ± 0.503   ms/op
ClientPb.getUser                          avgt       3   3.318 ± 1.248   ms/op
ClientPb.listUser                         avgt       3   3.817 ± 0.398   ms/op
ClientPb.createUser                     sample  288733   3.325 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.096           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.232           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.604           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.084           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.865           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.533           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.288           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.934           ms/op
ClientPb.existUser                      sample  295308   3.248 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.188           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.199           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.518           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.850           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.620           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.533           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.191           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.655           ms/op
ClientPb.getUser                        sample  276382   3.472 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.133           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.334           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.973           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.604           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.169           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.956           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.736           ms/op
ClientPb.getUser:getUser·p1.00          sample          25.068           ms/op
ClientPb.listUser                       sample  242205   3.962 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.403           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.838           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.391           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.735           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.037           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.595           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.933           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.100           ms/op
