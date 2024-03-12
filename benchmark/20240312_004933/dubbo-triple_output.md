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
# Warmup Iteration   1: 5.220 ops/ms
# Warmup Iteration   2: 12.410 ops/ms
# Warmup Iteration   3: 12.486 ops/ms
Iteration   1: 12.876 ops/ms
Iteration   2: 12.785 ops/ms
Iteration   3: 12.675 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.778 ±(99.9%) 1.837 ops/ms [Average]
  (min, avg, max) = (12.675, 12.778, 12.876), stdev = 0.101
  CI (99.9%): [10.941, 14.616] (assumes normal distribution)


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
# Warmup Iteration   1: 8.467 ops/ms
# Warmup Iteration   2: 13.366 ops/ms
# Warmup Iteration   3: 13.330 ops/ms
Iteration   1: 13.344 ops/ms
Iteration   2: 13.447 ops/ms
Iteration   3: 13.363 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.385 ±(99.9%) 0.996 ops/ms [Average]
  (min, avg, max) = (13.344, 13.385, 13.447), stdev = 0.055
  CI (99.9%): [12.388, 14.381] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.306 ops/ms
# Warmup Iteration   2: 12.695 ops/ms
# Warmup Iteration   3: 13.197 ops/ms
Iteration   1: 13.164 ops/ms
Iteration   2: 13.205 ops/ms
Iteration   3: 13.130 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.166 ±(99.9%) 0.683 ops/ms [Average]
  (min, avg, max) = (13.130, 13.166, 13.205), stdev = 0.037
  CI (99.9%): [12.483, 13.849] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.991 ops/ms
# Warmup Iteration   2: 10.653 ops/ms
# Warmup Iteration   3: 10.844 ops/ms
Iteration   1: 10.908 ops/ms
Iteration   2: 10.830 ops/ms
Iteration   3: 10.878 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.872 ±(99.9%) 0.720 ops/ms [Average]
  (min, avg, max) = (10.830, 10.872, 10.908), stdev = 0.039
  CI (99.9%): [10.152, 11.592] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 3.886 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.555 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.456 ±(99.9%) 0.004 ms/op
Iteration   1: 2.454 ±(99.9%) 0.004 ms/op
Iteration   2: 2.438 ±(99.9%) 0.003 ms/op
Iteration   3: 2.447 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.446 ±(99.9%) 0.144 ms/op [Average]
  (min, avg, max) = (2.438, 2.446, 2.454), stdev = 0.008
  CI (99.9%): [2.302, 2.590] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:32
# Fork: 1 of 1
# Warmup Iteration   1: 3.620 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.398 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.363 ±(99.9%) 0.004 ms/op
Iteration   1: 2.409 ±(99.9%) 0.004 ms/op
Iteration   2: 2.384 ±(99.9%) 0.004 ms/op
Iteration   3: 2.391 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.394 ±(99.9%) 0.238 ms/op [Average]
  (min, avg, max) = (2.384, 2.394, 2.409), stdev = 0.013
  CI (99.9%): [2.157, 2.632] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.798 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.475 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.449 ±(99.9%) 0.004 ms/op
Iteration   1: 2.426 ±(99.9%) 0.005 ms/op
Iteration   2: 2.428 ±(99.9%) 0.003 ms/op
Iteration   3: 2.438 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.431 ±(99.9%) 0.112 ms/op [Average]
  (min, avg, max) = (2.426, 2.431, 2.438), stdev = 0.006
  CI (99.9%): [2.318, 2.543] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.435 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.016 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.947 ±(99.9%) 0.005 ms/op
Iteration   1: 2.926 ±(99.9%) 0.004 ms/op
Iteration   2: 2.928 ±(99.9%) 0.003 ms/op
Iteration   3: 2.931 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.929 ±(99.9%) 0.043 ms/op [Average]
  (min, avg, max) = (2.926, 2.929, 2.931), stdev = 0.002
  CI (99.9%): [2.885, 2.972] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:18
# Fork: 1 of 1
# Warmup Iteration   1: 4.144 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.603 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.448 ±(99.9%) 0.005 ms/op
Iteration   1: 2.447 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.798 ms/op
                 createUser·p0.50:   2.523 ms/op
                 createUser·p0.90:   2.961 ms/op
                 createUser·p0.95:   3.068 ms/op
                 createUser·p0.99:   3.580 ms/op
                 createUser·p0.999:  7.924 ms/op
                 createUser·p0.9999: 14.269 ms/op
                 createUser·p1.00:   15.319 ms/op

Iteration   2: 2.461 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.357 ms/op
                 createUser·p0.50:   2.535 ms/op
                 createUser·p0.90:   2.986 ms/op
                 createUser·p0.95:   3.105 ms/op
                 createUser·p0.99:   3.674 ms/op
                 createUser·p0.999:  5.931 ms/op
                 createUser·p0.9999: 13.025 ms/op
                 createUser·p1.00:   13.386 ms/op

Iteration   3: 2.476 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.494 ms/op
                 createUser·p0.50:   2.556 ms/op
                 createUser·p0.90:   3.006 ms/op
                 createUser·p0.95:   3.129 ms/op
                 createUser·p0.99:   3.793 ms/op
                 createUser·p0.999:  7.604 ms/op
                 createUser·p0.9999: 11.321 ms/op
                 createUser·p1.00:   11.829 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 389723
  mean =      2.461 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 66 
    [ 1.250,  2.500) = 191394 
    [ 2.500,  3.750) = 194810 
    [ 3.750,  5.000) = 2777 
    [ 5.000,  6.250) = 242 
    [ 6.250,  7.500) = 42 
    [ 7.500,  8.750) = 41 
    [ 8.750, 10.000) = 72 
    [10.000, 11.250) = 80 
    [11.250, 12.500) = 89 
    [12.500, 13.750) = 79 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.357 ms/op
     p(50.0000) =      2.535 ms/op
     p(90.0000) =      2.986 ms/op
     p(95.0000) =      3.101 ms/op
     p(99.0000) =      3.682 ms/op
     p(99.9000) =      7.617 ms/op
     p(99.9900) =     13.664 ms/op
     p(99.9990) =     14.960 ms/op
     p(99.9999) =     15.319 ms/op
    p(100.0000) =     15.319 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.643 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.465 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.439 ±(99.9%) 0.005 ms/op
Iteration   1: 2.421 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.128 ms/op
                 existUser·p0.50:   2.540 ms/op
                 existUser·p0.90:   2.925 ms/op
                 existUser·p0.95:   3.011 ms/op
                 existUser·p0.99:   3.346 ms/op
                 existUser·p0.999:  7.335 ms/op
                 existUser·p0.9999: 14.434 ms/op
                 existUser·p1.00:   16.908 ms/op

Iteration   2: 2.423 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.038 ms/op
                 existUser·p0.50:   2.494 ms/op
                 existUser·p0.90:   2.929 ms/op
                 existUser·p0.95:   3.023 ms/op
                 existUser·p0.99:   3.568 ms/op
                 existUser·p0.999:  7.801 ms/op
                 existUser·p0.9999: 12.321 ms/op
                 existUser·p1.00:   12.714 ms/op

Iteration   3: 2.431 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.824 ms/op
                 existUser·p0.50:   2.515 ms/op
                 existUser·p0.90:   2.957 ms/op
                 existUser·p0.95:   3.076 ms/op
                 existUser·p0.99:   3.633 ms/op
                 existUser·p0.999:  6.994 ms/op
                 existUser·p0.9999: 11.480 ms/op
                 existUser·p1.00:   12.124 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 395406
  mean =      2.425 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 46 
    [ 1.250,  2.500) = 196471 
    [ 2.500,  3.750) = 196253 
    [ 3.750,  5.000) = 1944 
    [ 5.000,  6.250) = 251 
    [ 6.250,  7.500) = 45 
    [ 7.500,  8.750) = 40 
    [ 8.750, 10.000) = 94 
    [10.000, 11.250) = 88 
    [11.250, 12.500) = 58 
    [12.500, 13.750) = 88 
    [13.750, 15.000) = 22 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 5 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.824 ms/op
     p(50.0000) =      2.515 ms/op
     p(90.0000) =      2.937 ms/op
     p(95.0000) =      3.035 ms/op
     p(99.0000) =      3.510 ms/op
     p(99.9000) =      7.749 ms/op
     p(99.9900) =     13.648 ms/op
     p(99.9990) =     16.598 ms/op
     p(99.9999) =     16.908 ms/op
    p(100.0000) =     16.908 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.695 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.580 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.496 ±(99.9%) 0.006 ms/op
Iteration   1: 2.486 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.867 ms/op
                 getUser·p0.50:   2.519 ms/op
                 getUser·p0.90:   3.019 ms/op
                 getUser·p0.95:   3.158 ms/op
                 getUser·p0.99:   3.850 ms/op
                 getUser·p0.999:  8.261 ms/op
                 getUser·p0.9999: 13.224 ms/op
                 getUser·p1.00:   13.812 ms/op

Iteration   2: 2.495 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.964 ms/op
                 getUser·p0.50:   2.494 ms/op
                 getUser·p0.90:   3.052 ms/op
                 getUser·p0.95:   3.183 ms/op
                 getUser·p0.99:   3.805 ms/op
                 getUser·p0.999:  8.729 ms/op
                 getUser·p0.9999: 13.159 ms/op
                 getUser·p1.00:   13.451 ms/op

Iteration   3: 2.477 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.829 ms/op
                 getUser·p0.50:   2.478 ms/op
                 getUser·p0.90:   3.031 ms/op
                 getUser·p0.95:   3.166 ms/op
                 getUser·p0.99:   3.752 ms/op
                 getUser·p0.999:  6.902 ms/op
                 getUser·p0.9999: 10.886 ms/op
                 getUser·p1.00:   11.190 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 385801
  mean =      2.486 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 92 
    [ 1.250,  2.500) = 193166 
    [ 2.500,  3.750) = 188259 
    [ 3.750,  5.000) = 3523 
    [ 5.000,  6.250) = 361 
    [ 6.250,  7.500) = 16 
    [ 7.500,  8.750) = 25 
    [ 8.750, 10.000) = 99 
    [10.000, 11.250) = 95 
    [11.250, 12.500) = 73 
    [12.500, 13.750) = 90 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.829 ms/op
     p(50.0000) =      2.499 ms/op
     p(90.0000) =      3.035 ms/op
     p(95.0000) =      3.170 ms/op
     p(99.0000) =      3.805 ms/op
     p(99.9000) =      6.804 ms/op
     p(99.9900) =     13.173 ms/op
     p(99.9990) =     13.477 ms/op
     p(99.9999) =     13.812 ms/op
    p(100.0000) =     13.812 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.557 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 2.996 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.948 ±(99.9%) 0.008 ms/op
Iteration   1: 2.964 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.886 ms/op
                 listUser·p0.50:   2.892 ms/op
                 listUser·p0.90:   3.834 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   5.612 ms/op
                 listUser·p0.999:  8.361 ms/op
                 listUser·p0.9999: 10.768 ms/op
                 listUser·p1.00:   11.403 ms/op

Iteration   2: 2.940 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.890 ms/op
                 listUser·p0.50:   2.879 ms/op
                 listUser·p0.90:   3.785 ms/op
                 listUser·p0.95:   4.276 ms/op
                 listUser·p0.99:   5.530 ms/op
                 listUser·p0.999:  9.556 ms/op
                 listUser·p0.9999: 11.119 ms/op
                 listUser·p1.00:   11.796 ms/op

Iteration   3: 2.962 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.712 ms/op
                 listUser·p0.50:   2.900 ms/op
                 listUser·p0.90:   3.822 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   5.456 ms/op
                 listUser·p0.999:  10.339 ms/op
                 listUser·p0.9999: 12.291 ms/op
                 listUser·p1.00:   12.616 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 324530
  mean =      2.955 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 178 
    [ 1.250,  2.500) = 103125 
    [ 2.500,  3.750) = 185547 
    [ 3.750,  5.000) = 28624 
    [ 5.000,  6.250) = 5797 
    [ 6.250,  7.500) = 598 
    [ 7.500,  8.750) = 256 
    [ 8.750, 10.000) = 203 
    [10.000, 11.250) = 147 
    [11.250, 12.500) = 51 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.712 ms/op
     p(50.0000) =      2.892 ms/op
     p(90.0000) =      3.813 ms/op
     p(95.0000) =      4.325 ms/op
     p(99.0000) =      5.530 ms/op
     p(99.9000) =      9.297 ms/op
     p(99.9900) =     11.511 ms/op
     p(99.9990) =     12.546 ms/op
     p(99.9999) =     12.616 ms/op
    p(100.0000) =     12.616 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.778 ± 1.837  ops/ms
ClientPb.existUser                       thrpt       3  13.385 ± 0.996  ops/ms
ClientPb.getUser                         thrpt       3  13.166 ± 0.683  ops/ms
ClientPb.listUser                        thrpt       3  10.872 ± 0.720  ops/ms
ClientPb.createUser                       avgt       3   2.446 ± 0.144   ms/op
ClientPb.existUser                        avgt       3   2.394 ± 0.238   ms/op
ClientPb.getUser                          avgt       3   2.431 ± 0.112   ms/op
ClientPb.listUser                         avgt       3   2.929 ± 0.043   ms/op
ClientPb.createUser                     sample  389723   2.461 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.357           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.535           ms/op
ClientPb.createUser:createUser·p0.90    sample           2.986           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.101           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.682           ms/op
ClientPb.createUser:createUser·p0.999   sample           7.617           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.664           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.319           ms/op
ClientPb.existUser                      sample  395406   2.425 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.824           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.515           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.937           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.035           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.510           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.749           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.648           ms/op
ClientPb.existUser:existUser·p1.00      sample          16.908           ms/op
ClientPb.getUser                        sample  385801   2.486 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.829           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.499           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.035           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.170           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.805           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.804           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.173           ms/op
ClientPb.getUser:getUser·p1.00          sample          13.812           ms/op
ClientPb.listUser                       sample  324530   2.955 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.712           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.892           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.813           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.325           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.530           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.297           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.511           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.616           ms/op
