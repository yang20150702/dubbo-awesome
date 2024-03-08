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
# Warmup Iteration   1: 4.781 ops/ms
# Warmup Iteration   2: 12.129 ops/ms
# Warmup Iteration   3: 12.238 ops/ms
Iteration   1: 12.650 ops/ms
Iteration   2: 12.610 ops/ms
Iteration   3: 12.813 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.691 ±(99.9%) 1.963 ops/ms [Average]
  (min, avg, max) = (12.610, 12.691, 12.813), stdev = 0.108
  CI (99.9%): [10.728, 14.654] (assumes normal distribution)


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
# Warmup Iteration   1: 8.396 ops/ms
# Warmup Iteration   2: 13.241 ops/ms
# Warmup Iteration   3: 13.361 ops/ms
Iteration   1: 13.381 ops/ms
Iteration   2: 13.517 ops/ms
Iteration   3: 13.597 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.498 ±(99.9%) 1.988 ops/ms [Average]
  (min, avg, max) = (13.381, 13.498, 13.597), stdev = 0.109
  CI (99.9%): [11.511, 15.486] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.500 ops/ms
# Warmup Iteration   2: 12.455 ops/ms
# Warmup Iteration   3: 12.953 ops/ms
Iteration   1: 12.990 ops/ms
Iteration   2: 12.822 ops/ms
Iteration   3: 12.963 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.925 ±(99.9%) 1.646 ops/ms [Average]
  (min, avg, max) = (12.822, 12.925, 12.990), stdev = 0.090
  CI (99.9%): [11.279, 14.571] (assumes normal distribution)


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
# Warmup Iteration   1: 6.478 ops/ms
# Warmup Iteration   2: 10.537 ops/ms
# Warmup Iteration   3: 10.653 ops/ms
Iteration   1: 10.626 ops/ms
Iteration   2: 10.634 ops/ms
Iteration   3: 10.664 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.641 ±(99.9%) 0.365 ops/ms [Average]
  (min, avg, max) = (10.626, 10.641, 10.664), stdev = 0.020
  CI (99.9%): [10.276, 11.006] (assumes normal distribution)


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
# Warmup Iteration   1: 3.995 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.580 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.491 ±(99.9%) 0.003 ms/op
Iteration   1: 2.524 ±(99.9%) 0.004 ms/op
Iteration   2: 2.508 ±(99.9%) 0.004 ms/op
Iteration   3: 2.506 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.513 ±(99.9%) 0.177 ms/op [Average]
  (min, avg, max) = (2.506, 2.513, 2.524), stdev = 0.010
  CI (99.9%): [2.335, 2.690] (assumes normal distribution)


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
# Warmup Iteration   1: 3.696 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.416 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.436 ±(99.9%) 0.004 ms/op
Iteration   1: 2.431 ±(99.9%) 0.003 ms/op
Iteration   2: 2.448 ±(99.9%) 0.002 ms/op
Iteration   3: 2.440 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.440 ±(99.9%) 0.148 ms/op [Average]
  (min, avg, max) = (2.431, 2.440, 2.448), stdev = 0.008
  CI (99.9%): [2.291, 2.588] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.971 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.534 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.509 ±(99.9%) 0.003 ms/op
Iteration   1: 2.478 ±(99.9%) 0.005 ms/op
Iteration   2: 2.472 ±(99.9%) 0.005 ms/op
Iteration   3: 2.478 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.476 ±(99.9%) 0.069 ms/op [Average]
  (min, avg, max) = (2.472, 2.476, 2.478), stdev = 0.004
  CI (99.9%): [2.407, 2.545] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.530 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.052 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.019 ±(99.9%) 0.005 ms/op
Iteration   1: 2.986 ±(99.9%) 0.005 ms/op
Iteration   2: 3.017 ±(99.9%) 0.006 ms/op
Iteration   3: 2.983 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.995 ±(99.9%) 0.338 ms/op [Average]
  (min, avg, max) = (2.983, 2.995, 3.017), stdev = 0.019
  CI (99.9%): [2.658, 3.333] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 3.988 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.647 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.462 ±(99.9%) 0.005 ms/op
Iteration   1: 2.472 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.908 ms/op
                 createUser·p0.50:   2.544 ms/op
                 createUser·p0.90:   2.998 ms/op
                 createUser·p0.95:   3.133 ms/op
                 createUser·p0.99:   3.785 ms/op
                 createUser·p0.999:  6.419 ms/op
                 createUser·p0.9999: 13.665 ms/op
                 createUser·p1.00:   14.516 ms/op

Iteration   2: 2.474 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.027 ms/op
                 createUser·p0.50:   2.527 ms/op
                 createUser·p0.90:   3.019 ms/op
                 createUser·p0.95:   3.162 ms/op
                 createUser·p0.99:   3.736 ms/op
                 createUser·p0.999:  6.981 ms/op
                 createUser·p0.9999: 12.583 ms/op
                 createUser·p1.00:   12.845 ms/op

Iteration   3: 2.475 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.746 ms/op
                 createUser·p0.50:   2.531 ms/op
                 createUser·p0.90:   3.019 ms/op
                 createUser·p0.95:   3.166 ms/op
                 createUser·p0.99:   3.842 ms/op
                 createUser·p0.999:  7.608 ms/op
                 createUser·p0.9999: 10.915 ms/op
                 createUser·p1.00:   11.895 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 387675
  mean =      2.474 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 92 
    [ 1.250,  2.500) = 189818 
    [ 2.500,  3.750) = 193586 
    [ 3.750,  5.000) = 3476 
    [ 5.000,  6.250) = 289 
    [ 6.250,  7.500) = 29 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 73 
    [10.000, 11.250) = 132 
    [11.250, 12.500) = 101 
    [12.500, 13.750) = 71 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.746 ms/op
     p(50.0000) =      2.531 ms/op
     p(90.0000) =      3.011 ms/op
     p(95.0000) =      3.154 ms/op
     p(99.0000) =      3.789 ms/op
     p(99.9000) =      7.247 ms/op
     p(99.9900) =     13.045 ms/op
     p(99.9990) =     14.209 ms/op
     p(99.9999) =     14.516 ms/op
    p(100.0000) =     14.516 ms/op


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
# Warmup Iteration   1: 3.718 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.423 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.441 ±(99.9%) 0.005 ms/op
Iteration   1: 2.439 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.887 ms/op
                 existUser·p0.50:   2.499 ms/op
                 existUser·p0.90:   2.974 ms/op
                 existUser·p0.95:   3.097 ms/op
                 existUser·p0.99:   3.686 ms/op
                 existUser·p0.999:  6.804 ms/op
                 existUser·p0.9999: 13.613 ms/op
                 existUser·p1.00:   14.221 ms/op

Iteration   2: 2.419 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.964 ms/op
                 existUser·p0.50:   2.458 ms/op
                 existUser·p0.90:   2.945 ms/op
                 existUser·p0.95:   3.060 ms/op
                 existUser·p0.99:   3.592 ms/op
                 existUser·p0.999:  7.733 ms/op
                 existUser·p0.9999: 13.132 ms/op
                 existUser·p1.00:   14.451 ms/op

Iteration   3: 2.415 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.822 ms/op
                 existUser·p0.50:   2.478 ms/op
                 existUser·p0.90:   2.937 ms/op
                 existUser·p0.95:   3.043 ms/op
                 existUser·p0.99:   3.596 ms/op
                 existUser·p0.999:  8.471 ms/op
                 existUser·p0.9999: 10.273 ms/op
                 existUser·p1.00:   10.945 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 395793
  mean =      2.424 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 86 
    [ 1.250,  2.500) = 200451 
    [ 2.500,  3.750) = 191953 
    [ 3.750,  5.000) = 2429 
    [ 5.000,  6.250) = 397 
    [ 6.250,  7.500) = 29 
    [ 7.500,  8.750) = 73 
    [ 8.750, 10.000) = 104 
    [10.000, 11.250) = 73 
    [11.250, 12.500) = 117 
    [12.500, 13.750) = 71 
    [13.750, 15.000) = 10 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.822 ms/op
     p(50.0000) =      2.478 ms/op
     p(90.0000) =      2.953 ms/op
     p(95.0000) =      3.068 ms/op
     p(99.0000) =      3.625 ms/op
     p(99.9000) =      8.421 ms/op
     p(99.9900) =     13.091 ms/op
     p(99.9990) =     14.228 ms/op
     p(99.9999) =     14.451 ms/op
    p(100.0000) =     14.451 ms/op


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
# Warmup Iteration   1: 3.791 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.519 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.458 ±(99.9%) 0.005 ms/op
Iteration   1: 2.471 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.891 ms/op
                 getUser·p0.50:   2.494 ms/op
                 getUser·p0.90:   3.015 ms/op
                 getUser·p0.95:   3.154 ms/op
                 getUser·p0.99:   3.846 ms/op
                 getUser·p0.999:  6.273 ms/op
                 getUser·p0.9999: 13.390 ms/op
                 getUser·p1.00:   14.483 ms/op

Iteration   2: 2.498 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.643 ms/op
                 getUser·p0.50:   2.519 ms/op
                 getUser·p0.90:   3.047 ms/op
                 getUser·p0.95:   3.244 ms/op
                 getUser·p0.99:   4.456 ms/op
                 getUser·p0.999:  8.815 ms/op
                 getUser·p0.9999: 12.468 ms/op
                 getUser·p1.00:   14.156 ms/op

Iteration   3: 2.483 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.995 ms/op
                 getUser·p0.50:   2.499 ms/op
                 getUser·p0.90:   3.043 ms/op
                 getUser·p0.95:   3.187 ms/op
                 getUser·p0.99:   3.834 ms/op
                 getUser·p0.999:  6.616 ms/op
                 getUser·p0.9999: 11.274 ms/op
                 getUser·p1.00:   11.518 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 386074
  mean =      2.484 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 85 
    [ 1.250,  2.500) = 192384 
    [ 2.500,  3.750) = 187629 
    [ 3.750,  5.000) = 4917 
    [ 5.000,  6.250) = 650 
    [ 6.250,  7.500) = 48 
    [ 7.500,  8.750) = 17 
    [ 8.750, 10.000) = 67 
    [10.000, 11.250) = 105 
    [11.250, 12.500) = 100 
    [12.500, 13.750) = 64 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.643 ms/op
     p(50.0000) =      2.507 ms/op
     p(90.0000) =      3.035 ms/op
     p(95.0000) =      3.187 ms/op
     p(99.0000) =      4.059 ms/op
     p(99.9000) =      6.717 ms/op
     p(99.9900) =     13.042 ms/op
     p(99.9990) =     14.197 ms/op
     p(99.9999) =     14.483 ms/op
    p(100.0000) =     14.483 ms/op


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
# Warmup Iteration   1: 4.981 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.135 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.091 ±(99.9%) 0.009 ms/op
Iteration   1: 3.038 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.836 ms/op
                 listUser·p0.50:   2.970 ms/op
                 listUser·p0.90:   3.944 ms/op
                 listUser·p0.95:   4.440 ms/op
                 listUser·p0.99:   5.562 ms/op
                 listUser·p0.999:  10.019 ms/op
                 listUser·p0.9999: 12.042 ms/op
                 listUser·p1.00:   12.403 ms/op

Iteration   2: 3.020 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.985 ms/op
                 listUser·p0.50:   2.961 ms/op
                 listUser·p0.90:   3.863 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   5.562 ms/op
                 listUser·p0.999:  9.765 ms/op
                 listUser·p0.9999: 10.951 ms/op
                 listUser·p1.00:   11.485 ms/op

Iteration   3: 3.025 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.724 ms/op
                 listUser·p0.50:   2.957 ms/op
                 listUser·p0.90:   3.899 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   5.652 ms/op
                 listUser·p0.999:  9.530 ms/op
                 listUser·p0.9999: 10.994 ms/op
                 listUser·p1.00:   11.518 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 316797
  mean =      3.028 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 139 
    [ 1.250,  2.500) = 89820 
    [ 2.500,  3.750) = 186781 
    [ 3.750,  5.000) = 32795 
    [ 5.000,  6.250) = 5839 
    [ 6.250,  7.500) = 788 
    [ 7.500,  8.750) = 178 
    [ 8.750, 10.000) = 218 
    [10.000, 11.250) = 200 
    [11.250, 12.500) = 39 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.724 ms/op
     p(50.0000) =      2.966 ms/op
     p(90.0000) =      3.903 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      5.587 ms/op
     p(99.9000) =      9.830 ms/op
     p(99.9900) =     11.294 ms/op
     p(99.9990) =     12.236 ms/op
     p(99.9999) =     12.403 ms/op
    p(100.0000) =     12.403 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.691 ± 1.963  ops/ms
ClientPb.existUser                       thrpt       3  13.498 ± 1.988  ops/ms
ClientPb.getUser                         thrpt       3  12.925 ± 1.646  ops/ms
ClientPb.listUser                        thrpt       3  10.641 ± 0.365  ops/ms
ClientPb.createUser                       avgt       3   2.513 ± 0.177   ms/op
ClientPb.existUser                        avgt       3   2.440 ± 0.148   ms/op
ClientPb.getUser                          avgt       3   2.476 ± 0.069   ms/op
ClientPb.listUser                         avgt       3   2.995 ± 0.338   ms/op
ClientPb.createUser                     sample  387675   2.474 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.746           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.531           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.011           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.154           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.789           ms/op
ClientPb.createUser:createUser·p0.999   sample           7.247           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.045           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.516           ms/op
ClientPb.existUser                      sample  395793   2.424 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.822           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.478           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.953           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.068           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.625           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.421           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.091           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.451           ms/op
ClientPb.getUser                        sample  386074   2.484 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.643           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.507           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.035           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.187           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.059           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.717           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.042           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.483           ms/op
ClientPb.listUser                       sample  316797   3.028 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.724           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.966           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.903           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.407           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.587           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.830           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.294           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.403           ms/op
