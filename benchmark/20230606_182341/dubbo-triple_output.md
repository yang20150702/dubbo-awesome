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
# Warmup Iteration   1: 2.663 ops/ms
# Warmup Iteration   2: 6.169 ops/ms
# Warmup Iteration   3: 9.181 ops/ms
Iteration   1: 9.340 ops/ms
Iteration   2: 10.164 ops/ms
Iteration   3: 9.801 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.768 ±(99.9%) 7.532 ops/ms [Average]
  (min, avg, max) = (9.340, 9.768, 10.164), stdev = 0.413
  CI (99.9%): [2.237, 17.300] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.524 ops/ms
# Warmup Iteration   2: 9.184 ops/ms
# Warmup Iteration   3: 9.838 ops/ms
Iteration   1: 10.686 ops/ms
Iteration   2: 10.073 ops/ms
Iteration   3: 9.945 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.234 ±(99.9%) 7.226 ops/ms [Average]
  (min, avg, max) = (9.945, 10.234, 10.686), stdev = 0.396
  CI (99.9%): [3.008, 17.461] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.622 ops/ms
# Warmup Iteration   2: 9.128 ops/ms
# Warmup Iteration   3: 9.685 ops/ms
Iteration   1: 9.717 ops/ms
Iteration   2: 10.204 ops/ms
Iteration   3: 10.193 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.038 ±(99.9%) 5.073 ops/ms [Average]
  (min, avg, max) = (9.717, 10.038, 10.204), stdev = 0.278
  CI (99.9%): [4.965, 15.111] (assumes normal distribution)


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
# Warmup Iteration   1: 3.350 ops/ms
# Warmup Iteration   2: 7.599 ops/ms
# Warmup Iteration   3: 8.350 ops/ms
Iteration   1: 8.646 ops/ms
Iteration   2: 8.541 ops/ms
Iteration   3: 8.268 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.485 ±(99.9%) 3.557 ops/ms [Average]
  (min, avg, max) = (8.268, 8.485, 8.646), stdev = 0.195
  CI (99.9%): [4.929, 12.042] (assumes normal distribution)


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
# Warmup Iteration   1: 8.448 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.451 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.306 ±(99.9%) 0.009 ms/op
Iteration   1: 3.256 ±(99.9%) 0.008 ms/op
Iteration   2: 3.264 ±(99.9%) 0.006 ms/op
Iteration   3: 3.126 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.215 ±(99.9%) 1.406 ms/op [Average]
  (min, avg, max) = (3.126, 3.215, 3.264), stdev = 0.077
  CI (99.9%): [1.810, 4.621] (assumes normal distribution)


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
# Warmup Iteration   1: 7.551 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.215 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.289 ±(99.9%) 0.005 ms/op
Iteration   1: 3.089 ±(99.9%) 0.004 ms/op
Iteration   2: 3.042 ±(99.9%) 0.008 ms/op
Iteration   3: 3.081 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.071 ±(99.9%) 0.452 ms/op [Average]
  (min, avg, max) = (3.042, 3.071, 3.089), stdev = 0.025
  CI (99.9%): [2.619, 3.523] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 7.839 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.496 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.335 ±(99.9%) 0.001 ms/op
Iteration   1: 3.236 ±(99.9%) 0.005 ms/op
Iteration   2: 3.389 ±(99.9%) 0.004 ms/op
Iteration   3: 3.240 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.288 ±(99.9%) 1.598 ms/op [Average]
  (min, avg, max) = (3.236, 3.288, 3.389), stdev = 0.088
  CI (99.9%): [1.690, 4.887] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 8.626 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.116 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.838 ±(99.9%) 0.006 ms/op
Iteration   1: 3.790 ±(99.9%) 0.010 ms/op
Iteration   2: 3.784 ±(99.9%) 0.007 ms/op
Iteration   3: 3.725 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.766 ±(99.9%) 0.649 ms/op [Average]
  (min, avg, max) = (3.725, 3.766, 3.790), stdev = 0.036
  CI (99.9%): [3.117, 4.415] (assumes normal distribution)


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
# Warmup Iteration   1: 8.021 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 3.930 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.291 ±(99.9%) 0.008 ms/op
Iteration   1: 3.269 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.653 ms/op
                 createUser·p0.50:   3.219 ms/op
                 createUser·p0.90:   3.645 ms/op
                 createUser·p0.95:   4.133 ms/op
                 createUser·p0.99:   5.644 ms/op
                 createUser·p0.999:  10.071 ms/op
                 createUser·p0.9999: 20.651 ms/op
                 createUser·p1.00:   21.135 ms/op

Iteration   2: 3.227 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.065 ms/op
                 createUser·p0.50:   3.109 ms/op
                 createUser·p0.90:   3.666 ms/op
                 createUser·p0.95:   3.924 ms/op
                 createUser·p0.99:   4.841 ms/op
                 createUser·p0.999:  19.677 ms/op
                 createUser·p0.9999: 30.114 ms/op
                 createUser·p1.00:   30.802 ms/op

Iteration   3: 3.219 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.255 ms/op
                 createUser·p0.50:   3.109 ms/op
                 createUser·p0.90:   3.592 ms/op
                 createUser·p0.95:   3.957 ms/op
                 createUser·p0.99:   5.661 ms/op
                 createUser·p0.999:  16.252 ms/op
                 createUser·p0.9999: 24.554 ms/op
                 createUser·p1.00:   26.280 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 296290
  mean =      3.238 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17765 
    [ 2.500,  5.000) = 272895 
    [ 5.000,  7.500) = 4762 
    [ 7.500, 10.000) = 492 
    [10.000, 12.500) = 24 
    [12.500, 15.000) = 15 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 150 
    [20.000, 22.500) = 101 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 6 
    [27.500, 30.000) = 19 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.065 ms/op
     p(50.0000) =      3.166 ms/op
     p(90.0000) =      3.637 ms/op
     p(95.0000) =      3.990 ms/op
     p(99.0000) =      5.505 ms/op
     p(99.9000) =     18.219 ms/op
     p(99.9900) =     28.622 ms/op
     p(99.9990) =     30.705 ms/op
     p(99.9999) =     30.802 ms/op
    p(100.0000) =     30.802 ms/op


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
# Warmup Iteration   1: 7.505 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 3.418 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.124 ±(99.9%) 0.007 ms/op
Iteration   1: 3.179 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.956 ms/op
                 existUser·p0.50:   3.150 ms/op
                 existUser·p0.90:   3.469 ms/op
                 existUser·p0.95:   3.830 ms/op
                 existUser·p0.99:   5.554 ms/op
                 existUser·p0.999:  9.847 ms/op
                 existUser·p0.9999: 24.670 ms/op
                 existUser·p1.00:   25.690 ms/op

Iteration   2: 3.359 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.986 ms/op
                 existUser·p0.50:   3.211 ms/op
                 existUser·p0.90:   3.940 ms/op
                 existUser·p0.95:   4.891 ms/op
                 existUser·p0.99:   6.332 ms/op
                 existUser·p0.999:  12.108 ms/op
                 existUser·p0.9999: 22.871 ms/op
                 existUser·p1.00:   23.822 ms/op

Iteration   3: 3.092 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.636 ms/op
                 existUser·p0.50:   3.023 ms/op
                 existUser·p0.90:   3.314 ms/op
                 existUser·p0.95:   3.494 ms/op
                 existUser·p0.99:   5.284 ms/op
                 existUser·p0.999:  17.028 ms/op
                 existUser·p0.9999: 38.579 ms/op
                 existUser·p1.00:   39.518 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 299172
  mean =      3.206 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18757 
    [ 2.500,  5.000) = 272939 
    [ 5.000,  7.500) = 6475 
    [ 7.500, 10.000) = 468 
    [10.000, 12.500) = 177 
    [12.500, 15.000) = 68 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 82 
    [22.500, 25.000) = 51 
    [25.000, 27.500) = 31 
    [27.500, 30.000) = 5 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.956 ms/op
     p(50.0000) =      3.138 ms/op
     p(90.0000) =      3.559 ms/op
     p(95.0000) =      3.990 ms/op
     p(99.0000) =      5.816 ms/op
     p(99.9000) =     13.839 ms/op
     p(99.9900) =     37.945 ms/op
     p(99.9990) =     39.060 ms/op
     p(99.9999) =     39.518 ms/op
    p(100.0000) =     39.518 ms/op


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
# Warmup Iteration   1: 7.632 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 3.488 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.327 ±(99.9%) 0.011 ms/op
Iteration   1: 3.327 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.559 ms/op
                 getUser·p0.50:   3.240 ms/op
                 getUser·p0.90:   3.707 ms/op
                 getUser·p0.95:   4.252 ms/op
                 getUser·p0.99:   5.751 ms/op
                 getUser·p0.999:  16.159 ms/op
                 getUser·p0.9999: 24.884 ms/op
                 getUser·p1.00:   26.149 ms/op

Iteration   2: 3.231 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.709 ms/op
                 getUser·p0.50:   3.146 ms/op
                 getUser·p0.90:   3.719 ms/op
                 getUser·p0.95:   4.035 ms/op
                 getUser·p0.99:   5.743 ms/op
                 getUser·p0.999:  10.158 ms/op
                 getUser·p0.9999: 23.174 ms/op
                 getUser·p1.00:   23.888 ms/op

Iteration   3: 3.265 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.335 ms/op
                 getUser·p0.50:   3.207 ms/op
                 getUser·p0.90:   3.666 ms/op
                 getUser·p0.95:   3.920 ms/op
                 getUser·p0.99:   5.489 ms/op
                 getUser·p0.999:  15.338 ms/op
                 getUser·p0.9999: 23.101 ms/op
                 getUser·p1.00:   23.560 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 292930
  mean =      3.274 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18219 
    [ 2.500,  5.000) = 268176 
    [ 5.000,  7.500) = 5804 
    [ 7.500, 10.000) = 378 
    [10.000, 12.500) = 35 
    [12.500, 15.000) = 14 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 131 
    [22.500, 25.000) = 72 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.709 ms/op
     p(50.0000) =      3.203 ms/op
     p(90.0000) =      3.695 ms/op
     p(95.0000) =      4.043 ms/op
     p(99.0000) =      5.677 ms/op
     p(99.9000) =     15.290 ms/op
     p(99.9900) =     23.583 ms/op
     p(99.9990) =     25.234 ms/op
     p(99.9999) =     26.149 ms/op
    p(100.0000) =     26.149 ms/op


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
# Warmup Iteration   1: 8.505 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 4.149 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.959 ±(99.9%) 0.013 ms/op
Iteration   1: 3.800 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.755 ms/op
                 listUser·p0.50:   3.686 ms/op
                 listUser·p0.90:   4.137 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   6.742 ms/op
                 listUser·p0.999:  16.744 ms/op
                 listUser·p0.9999: 20.447 ms/op
                 listUser·p1.00:   20.742 ms/op

Iteration   2: 3.805 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.269 ms/op
                 listUser·p0.50:   3.752 ms/op
                 listUser·p0.90:   4.129 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   6.939 ms/op
                 listUser·p0.999:  12.909 ms/op
                 listUser·p0.9999: 14.136 ms/op
                 listUser·p1.00:   14.926 ms/op

Iteration   3: 3.744 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.236 ms/op
                 listUser·p0.50:   3.629 ms/op
                 listUser·p0.90:   4.051 ms/op
                 listUser·p0.95:   4.235 ms/op
                 listUser·p0.99:   6.676 ms/op
                 listUser·p0.999:  13.915 ms/op
                 listUser·p0.9999: 17.889 ms/op
                 listUser·p1.00:   18.350 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 253604
  mean =      3.783 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 48 
    [ 2.500,  5.000) = 247230 
    [ 5.000,  7.500) = 4385 
    [ 7.500, 10.000) = 1318 
    [10.000, 12.500) = 213 
    [12.500, 15.000) = 203 
    [15.000, 17.500) = 127 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.755 ms/op
     p(50.0000) =      3.711 ms/op
     p(90.0000) =      4.096 ms/op
     p(95.0000) =      4.350 ms/op
     p(99.0000) =      6.832 ms/op
     p(99.9000) =     14.008 ms/op
     p(99.9900) =     19.530 ms/op
     p(99.9990) =     20.622 ms/op
     p(99.9999) =     20.742 ms/op
    p(100.0000) =     20.742 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.768 ± 7.532  ops/ms
ClientPb.existUser                       thrpt       3  10.234 ± 7.226  ops/ms
ClientPb.getUser                         thrpt       3  10.038 ± 5.073  ops/ms
ClientPb.listUser                        thrpt       3   8.485 ± 3.557  ops/ms
ClientPb.createUser                       avgt       3   3.215 ± 1.406   ms/op
ClientPb.existUser                        avgt       3   3.071 ± 0.452   ms/op
ClientPb.getUser                          avgt       3   3.288 ± 1.598   ms/op
ClientPb.listUser                         avgt       3   3.766 ± 0.649   ms/op
ClientPb.createUser                     sample  296290   3.238 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.065           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.166           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.637           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.990           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.505           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.219           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.622           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.802           ms/op
ClientPb.existUser                      sample  299172   3.206 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.956           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.138           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.559           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.990           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.816           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.839           ms/op
ClientPb.existUser:existUser·p0.9999    sample          37.945           ms/op
ClientPb.existUser:existUser·p1.00      sample          39.518           ms/op
ClientPb.getUser                        sample  292930   3.274 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.709           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.203           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.695           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.043           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.677           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.290           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.583           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.149           ms/op
ClientPb.listUser                       sample  253604   3.783 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.755           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.711           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.096           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.350           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.832           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.008           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.530           ms/op
ClientPb.listUser:listUser·p1.00        sample          20.742           ms/op
