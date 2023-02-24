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
# Warmup Iteration   1: 2.627 ops/ms
# Warmup Iteration   2: 6.599 ops/ms
# Warmup Iteration   3: 9.610 ops/ms
Iteration   1: 9.865 ops/ms
Iteration   2: 10.351 ops/ms
Iteration   3: 9.941 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  10.052 ±(99.9%) 4.770 ops/ms [Average]
  (min, avg, max) = (9.865, 10.052, 10.351), stdev = 0.261
  CI (99.9%): [5.282, 14.823] (assumes normal distribution)


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
# Warmup Iteration   1: 3.968 ops/ms
# Warmup Iteration   2: 9.864 ops/ms
# Warmup Iteration   3: 10.290 ops/ms
Iteration   1: 10.885 ops/ms
Iteration   2: 10.195 ops/ms
Iteration   3: 10.532 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.537 ±(99.9%) 6.300 ops/ms [Average]
  (min, avg, max) = (10.195, 10.537, 10.885), stdev = 0.345
  CI (99.9%): [4.237, 16.837] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.497 ops/ms
# Warmup Iteration   2: 9.238 ops/ms
# Warmup Iteration   3: 10.362 ops/ms
Iteration   1: 10.164 ops/ms
Iteration   2: 10.343 ops/ms
Iteration   3: 10.284 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.264 ±(99.9%) 1.666 ops/ms [Average]
  (min, avg, max) = (10.164, 10.264, 10.343), stdev = 0.091
  CI (99.9%): [8.597, 11.930] (assumes normal distribution)


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
# Warmup Iteration   1: 3.217 ops/ms
# Warmup Iteration   2: 8.076 ops/ms
# Warmup Iteration   3: 8.418 ops/ms
Iteration   1: 8.768 ops/ms
Iteration   2: 8.612 ops/ms
Iteration   3: 8.699 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.693 ±(99.9%) 1.428 ops/ms [Average]
  (min, avg, max) = (8.612, 8.693, 8.768), stdev = 0.078
  CI (99.9%): [7.265, 10.121] (assumes normal distribution)


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
# Warmup Iteration   1: 8.417 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.509 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.251 ±(99.9%) 0.003 ms/op
Iteration   1: 3.188 ±(99.9%) 0.006 ms/op
Iteration   2: 3.123 ±(99.9%) 0.008 ms/op
Iteration   3: 3.224 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.178 ±(99.9%) 0.929 ms/op [Average]
  (min, avg, max) = (3.123, 3.178, 3.224), stdev = 0.051
  CI (99.9%): [2.249, 4.107] (assumes normal distribution)


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
# Warmup Iteration   1: 7.438 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.246 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.171 ±(99.9%) 0.004 ms/op
Iteration   1: 3.054 ±(99.9%) 0.006 ms/op
Iteration   2: 3.185 ±(99.9%) 0.007 ms/op
Iteration   3: 3.061 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.100 ±(99.9%) 1.346 ms/op [Average]
  (min, avg, max) = (3.054, 3.100, 3.185), stdev = 0.074
  CI (99.9%): [1.754, 4.446] (assumes normal distribution)


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
# Warmup Iteration   1: 7.937 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.357 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.328 ±(99.9%) 0.004 ms/op
Iteration   1: 3.190 ±(99.9%) 0.002 ms/op
Iteration   2: 3.167 ±(99.9%) 0.006 ms/op
Iteration   3: 3.077 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.145 ±(99.9%) 1.085 ms/op [Average]
  (min, avg, max) = (3.077, 3.145, 3.190), stdev = 0.059
  CI (99.9%): [2.060, 4.229] (assumes normal distribution)


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
# Warmup Iteration   1: 9.489 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.095 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.805 ±(99.9%) 0.005 ms/op
Iteration   1: 3.737 ±(99.9%) 0.008 ms/op
Iteration   2: 3.824 ±(99.9%) 0.004 ms/op
Iteration   3: 3.686 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.749 ±(99.9%) 1.274 ms/op [Average]
  (min, avg, max) = (3.686, 3.749, 3.824), stdev = 0.070
  CI (99.9%): [2.475, 5.023] (assumes normal distribution)


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
# Warmup Iteration   1: 7.636 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 3.573 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.313 ±(99.9%) 0.008 ms/op
Iteration   1: 3.160 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.270 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.543 ms/op
                 createUser·p0.95:   3.842 ms/op
                 createUser·p0.99:   5.464 ms/op
                 createUser·p0.999:  14.154 ms/op
                 createUser·p0.9999: 22.276 ms/op
                 createUser·p1.00:   23.495 ms/op

Iteration   2: 3.094 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.135 ms/op
                 createUser·p0.50:   3.109 ms/op
                 createUser·p0.90:   3.277 ms/op
                 createUser·p0.95:   3.338 ms/op
                 createUser·p0.99:   5.087 ms/op
                 createUser·p0.999:  19.813 ms/op
                 createUser·p0.9999: 23.200 ms/op
                 createUser·p1.00:   23.855 ms/op

Iteration   3: 3.225 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.425 ms/op
                 createUser·p0.50:   3.129 ms/op
                 createUser·p0.90:   3.633 ms/op
                 createUser·p0.95:   4.059 ms/op
                 createUser·p0.99:   5.784 ms/op
                 createUser·p0.999:  17.498 ms/op
                 createUser·p0.9999: 23.101 ms/op
                 createUser·p1.00:   24.248 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 303516
  mean =      3.159 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19749 
    [ 2.500,  5.000) = 278213 
    [ 5.000,  7.500) = 4802 
    [ 7.500, 10.000) = 325 
    [10.000, 12.500) = 35 
    [12.500, 15.000) = 39 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 137 
    [20.000, 22.500) = 129 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.135 ms/op
     p(50.0000) =      3.097 ms/op
     p(90.0000) =      3.473 ms/op
     p(95.0000) =      3.789 ms/op
     p(99.0000) =      5.431 ms/op
     p(99.9000) =     17.662 ms/op
     p(99.9900) =     23.090 ms/op
     p(99.9990) =     23.854 ms/op
     p(99.9999) =     24.248 ms/op
    p(100.0000) =     24.248 ms/op


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
# Warmup Iteration   1: 7.431 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 3.232 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.141 ±(99.9%) 0.009 ms/op
Iteration   1: 3.299 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.418 ms/op
                 existUser·p0.50:   3.240 ms/op
                 existUser·p0.90:   3.817 ms/op
                 existUser·p0.95:   4.235 ms/op
                 existUser·p0.99:   5.603 ms/op
                 existUser·p0.999:  9.756 ms/op
                 existUser·p0.9999: 24.094 ms/op
                 existUser·p1.00:   24.609 ms/op

Iteration   2: 3.159 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.290 ms/op
                 existUser·p0.50:   3.068 ms/op
                 existUser·p0.90:   3.564 ms/op
                 existUser·p0.95:   4.284 ms/op
                 existUser·p0.99:   5.341 ms/op
                 existUser·p0.999:  11.808 ms/op
                 existUser·p0.9999: 18.645 ms/op
                 existUser·p1.00:   20.546 ms/op

Iteration   3: 3.137 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.788 ms/op
                 existUser·p0.50:   3.109 ms/op
                 existUser·p0.90:   3.379 ms/op
                 existUser·p0.95:   3.785 ms/op
                 existUser·p0.99:   5.267 ms/op
                 existUser·p0.999:  14.092 ms/op
                 existUser·p0.9999: 26.956 ms/op
                 existUser·p1.00:   27.394 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 300133
  mean =      3.197 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22917 
    [ 2.500,  5.000) = 271653 
    [ 5.000,  7.500) = 4862 
    [ 7.500, 10.000) = 292 
    [10.000, 12.500) = 97 
    [12.500, 15.000) = 58 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 77 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.418 ms/op
     p(50.0000) =      3.133 ms/op
     p(90.0000) =      3.625 ms/op
     p(95.0000) =      4.129 ms/op
     p(99.0000) =      5.415 ms/op
     p(99.9000) =     12.646 ms/op
     p(99.9900) =     25.199 ms/op
     p(99.9990) =     27.230 ms/op
     p(99.9999) =     27.394 ms/op
    p(100.0000) =     27.394 ms/op


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
# Warmup Iteration   1: 8.672 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 3.492 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.213 ±(99.9%) 0.009 ms/op
Iteration   1: 3.198 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.563 ms/op
                 getUser·p0.50:   3.068 ms/op
                 getUser·p0.90:   3.510 ms/op
                 getUser·p0.95:   3.908 ms/op
                 getUser·p0.99:   6.398 ms/op
                 getUser·p0.999:  18.870 ms/op
                 getUser·p0.9999: 26.607 ms/op
                 getUser·p1.00:   27.492 ms/op

Iteration   2: 3.061 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.245 ms/op
                 getUser·p0.50:   2.982 ms/op
                 getUser·p0.90:   3.355 ms/op
                 getUser·p0.95:   3.518 ms/op
                 getUser·p0.99:   4.415 ms/op
                 getUser·p0.999:  8.356 ms/op
                 getUser·p0.9999: 21.987 ms/op
                 getUser·p1.00:   23.036 ms/op

Iteration   3: 3.170 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.276 ms/op
                 getUser·p0.50:   3.080 ms/op
                 getUser·p0.90:   3.469 ms/op
                 getUser·p0.95:   3.838 ms/op
                 getUser·p0.99:   6.554 ms/op
                 getUser·p0.999:  11.164 ms/op
                 getUser·p0.9999: 20.507 ms/op
                 getUser·p1.00:   21.234 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 305424
  mean =      3.142 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11979 
    [ 2.500,  5.000) = 287328 
    [ 5.000,  7.500) = 5096 
    [ 7.500, 10.000) = 675 
    [10.000, 12.500) = 26 
    [12.500, 15.000) = 42 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 75 
    [20.000, 22.500) = 108 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      1.245 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      3.445 ms/op
     p(95.0000) =      3.699 ms/op
     p(99.0000) =      6.054 ms/op
     p(99.9000) =     14.057 ms/op
     p(99.9900) =     25.428 ms/op
     p(99.9990) =     27.197 ms/op
     p(99.9999) =     27.492 ms/op
    p(100.0000) =     27.492 ms/op


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
# Warmup Iteration   1: 9.592 ±(99.9%) 0.133 ms/op
# Warmup Iteration   2: 4.097 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.740 ±(99.9%) 0.011 ms/op
Iteration   1: 3.725 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.339 ms/op
                 listUser·p0.50:   3.633 ms/op
                 listUser·p0.90:   4.030 ms/op
                 listUser·p0.95:   4.284 ms/op
                 listUser·p0.99:   7.148 ms/op
                 listUser·p0.999:  15.159 ms/op
                 listUser·p0.9999: 26.214 ms/op
                 listUser·p1.00:   27.263 ms/op

Iteration   2: 3.772 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.931 ms/op
                 listUser·p0.50:   3.633 ms/op
                 listUser·p0.90:   4.096 ms/op
                 listUser·p0.95:   4.581 ms/op
                 listUser·p0.99:   7.373 ms/op
                 listUser·p0.999:  13.844 ms/op
                 listUser·p0.9999: 17.416 ms/op
                 listUser·p1.00:   17.727 ms/op

Iteration   3: 3.731 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.232 ms/op
                 listUser·p0.50:   3.564 ms/op
                 listUser·p0.90:   3.994 ms/op
                 listUser·p0.95:   4.307 ms/op
                 listUser·p0.99:   7.586 ms/op
                 listUser·p0.999:  14.931 ms/op
                 listUser·p0.9999: 20.279 ms/op
                 listUser·p1.00:   20.709 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 256325
  mean =      3.743 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 87 
    [ 2.500,  5.000) = 246611 
    [ 5.000,  7.500) = 7230 
    [ 7.500, 10.000) = 1536 
    [10.000, 12.500) = 315 
    [12.500, 15.000) = 336 
    [15.000, 17.500) = 111 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      1.339 ms/op
     p(50.0000) =      3.613 ms/op
     p(90.0000) =      4.043 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      7.397 ms/op
     p(99.9000) =     14.347 ms/op
     p(99.9900) =     24.424 ms/op
     p(99.9990) =     26.534 ms/op
     p(99.9999) =     27.263 ms/op
    p(100.0000) =     27.263 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  10.052 ± 4.770  ops/ms
ClientPb.existUser                       thrpt       3  10.537 ± 6.300  ops/ms
ClientPb.getUser                         thrpt       3  10.264 ± 1.666  ops/ms
ClientPb.listUser                        thrpt       3   8.693 ± 1.428  ops/ms
ClientPb.createUser                       avgt       3   3.178 ± 0.929   ms/op
ClientPb.existUser                        avgt       3   3.100 ± 1.346   ms/op
ClientPb.getUser                          avgt       3   3.145 ± 1.085   ms/op
ClientPb.listUser                         avgt       3   3.749 ± 1.274   ms/op
ClientPb.createUser                     sample  303516   3.159 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.135           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.097           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.473           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.789           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.431           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.662           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.090           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.248           ms/op
ClientPb.existUser                      sample  300133   3.197 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.418           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.133           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.625           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.129           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.415           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.646           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.199           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.394           ms/op
ClientPb.getUser                        sample  305424   3.142 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.245           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.031           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.445           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.699           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.054           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.057           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.428           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.492           ms/op
ClientPb.listUser                       sample  256325   3.743 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.339           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.613           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.043           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.383           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.397           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.347           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.424           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.263           ms/op
