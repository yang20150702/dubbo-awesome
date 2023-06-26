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
# Warmup Iteration   1: 1.001 ops/ms
# Warmup Iteration   2: 2.121 ops/ms
# Warmup Iteration   3: 4.705 ops/ms
Iteration   1: 5.169 ops/ms
Iteration   2: 5.190 ops/ms
Iteration   3: 5.443 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.267 ±(99.9%) 2.783 ops/ms [Average]
  (min, avg, max) = (5.169, 5.267, 5.443), stdev = 0.153
  CI (99.9%): [2.484, 8.051] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 1.342 ops/ms
# Warmup Iteration   2: 3.713 ops/ms
# Warmup Iteration   3: 4.783 ops/ms
Iteration   1: 5.121 ops/ms
Iteration   2: 5.065 ops/ms
Iteration   3: 5.224 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.137 ±(99.9%) 1.473 ops/ms [Average]
  (min, avg, max) = (5.065, 5.137, 5.224), stdev = 0.081
  CI (99.9%): [3.664, 6.610] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:05
# Fork: 1 of 1
# Warmup Iteration   1: 1.225 ops/ms
# Warmup Iteration   2: 3.539 ops/ms
# Warmup Iteration   3: 4.858 ops/ms
Iteration   1: 4.485 ops/ms
Iteration   2: 4.901 ops/ms
Iteration   3: 5.279 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.888 ±(99.9%) 7.243 ops/ms [Average]
  (min, avg, max) = (4.485, 4.888, 5.279), stdev = 0.397
  CI (99.9%): [≈ 0, 12.131] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:57
# Fork: 1 of 1
# Warmup Iteration   1: 1.282 ops/ms
# Warmup Iteration   2: 3.355 ops/ms
# Warmup Iteration   3: 4.058 ops/ms
Iteration   1: 3.991 ops/ms
Iteration   2: 4.470 ops/ms
Iteration   3: 4.721 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.394 ±(99.9%) 6.765 ops/ms [Average]
  (min, avg, max) = (3.991, 4.394, 4.721), stdev = 0.371
  CI (99.9%): [≈ 0, 11.159] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:52
# Fork: 1 of 1
# Warmup Iteration   1: 20.573 ±(99.9%) 0.125 ms/op
# Warmup Iteration   2: 8.157 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 6.343 ±(99.9%) 0.013 ms/op
Iteration   1: 6.594 ±(99.9%) 0.010 ms/op
Iteration   2: 6.819 ±(99.9%) 0.008 ms/op
Iteration   3: 6.100 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.504 ±(99.9%) 6.707 ms/op [Average]
  (min, avg, max) = (6.100, 6.504, 6.819), stdev = 0.368
  CI (99.9%): [≈ 0, 13.211] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:45
# Fork: 1 of 1
# Warmup Iteration   1: 20.516 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 7.418 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.869 ±(99.9%) 0.013 ms/op
Iteration   1: 5.641 ±(99.9%) 0.009 ms/op
Iteration   2: 5.460 ±(99.9%) 0.019 ms/op
Iteration   3: 5.499 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.533 ±(99.9%) 1.742 ms/op [Average]
  (min, avg, max) = (5.460, 5.533, 5.641), stdev = 0.095
  CI (99.9%): [3.791, 7.275] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:39
# Fork: 1 of 1
# Warmup Iteration   1: 20.096 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 8.157 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 6.117 ±(99.9%) 0.010 ms/op
Iteration   1: 6.049 ±(99.9%) 0.016 ms/op
Iteration   2: 6.285 ±(99.9%) 0.016 ms/op
Iteration   3: 6.666 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.333 ±(99.9%) 5.680 ms/op [Average]
  (min, avg, max) = (6.049, 6.333, 6.666), stdev = 0.311
  CI (99.9%): [0.653, 12.013] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 22.813 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 9.760 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 6.929 ±(99.9%) 0.022 ms/op
Iteration   1: 6.880 ±(99.9%) 0.015 ms/op
Iteration   2: 6.879 ±(99.9%) 0.015 ms/op
Iteration   3: 6.591 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.783 ±(99.9%) 3.036 ms/op [Average]
  (min, avg, max) = (6.591, 6.783, 6.880), stdev = 0.166
  CI (99.9%): [3.747, 9.819] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:26
# Fork: 1 of 1
# Warmup Iteration   1: 20.129 ±(99.9%) 0.364 ms/op
# Warmup Iteration   2: 8.929 ±(99.9%) 0.074 ms/op
# Warmup Iteration   3: 6.574 ±(99.9%) 0.032 ms/op
Iteration   1: 5.963 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   2.507 ms/op
                 createUser·p0.50:   5.554 ms/op
                 createUser·p0.90:   7.512 ms/op
                 createUser·p0.95:   8.765 ms/op
                 createUser·p0.99:   11.682 ms/op
                 createUser·p0.999:  25.995 ms/op
                 createUser·p0.9999: 30.296 ms/op
                 createUser·p1.00:   31.588 ms/op

Iteration   2: 6.065 ±(99.9%) 0.024 ms/op
                 createUser·p0.00:   2.404 ms/op
                 createUser·p0.50:   5.751 ms/op
                 createUser·p0.90:   7.537 ms/op
                 createUser·p0.95:   8.684 ms/op
                 createUser·p0.99:   11.370 ms/op
                 createUser·p0.999:  29.251 ms/op
                 createUser·p0.9999: 38.535 ms/op
                 createUser·p1.00:   38.666 ms/op

Iteration   3: 6.264 ±(99.9%) 0.030 ms/op
                 createUser·p0.00:   2.634 ms/op
                 createUser·p0.50:   5.677 ms/op
                 createUser·p0.90:   8.487 ms/op
                 createUser·p0.95:   9.748 ms/op
                 createUser·p0.99:   13.500 ms/op
                 createUser·p0.999:  30.636 ms/op
                 createUser·p0.9999: 35.311 ms/op
                 createUser·p1.00:   35.783 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 157409
  mean =      6.095 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 25996 
    [ 5.000,  7.500) = 112456 
    [ 7.500, 10.000) = 14156 
    [10.000, 12.500) = 3410 
    [12.500, 15.000) = 854 
    [15.000, 17.500) = 272 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 39 
    [27.500, 30.000) = 72 
    [30.000, 32.500) = 49 
    [32.500, 35.000) = 20 
    [35.000, 37.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      2.404 ms/op
     p(50.0000) =      5.652 ms/op
     p(90.0000) =      7.823 ms/op
     p(95.0000) =      9.126 ms/op
     p(99.0000) =     12.124 ms/op
     p(99.9000) =     28.553 ms/op
     p(99.9900) =     38.224 ms/op
     p(99.9990) =     38.666 ms/op
     p(99.9999) =     38.666 ms/op
    p(100.0000) =     38.666 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 19.056 ±(99.9%) 0.349 ms/op
# Warmup Iteration   2: 6.679 ±(99.9%) 0.036 ms/op
# Warmup Iteration   3: 5.581 ±(99.9%) 0.022 ms/op
Iteration   1: 5.639 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   2.429 ms/op
                 existUser·p0.50:   5.284 ms/op
                 existUser·p0.90:   7.102 ms/op
                 existUser·p0.95:   8.339 ms/op
                 existUser·p0.99:   10.666 ms/op
                 existUser·p0.999:  13.587 ms/op
                 existUser·p0.9999: 28.386 ms/op
                 existUser·p1.00:   32.408 ms/op

Iteration   2: 5.715 ±(99.9%) 0.024 ms/op
                 existUser·p0.00:   1.964 ms/op
                 existUser·p0.50:   5.276 ms/op
                 existUser·p0.90:   7.365 ms/op
                 existUser·p0.95:   8.700 ms/op
                 existUser·p0.99:   11.239 ms/op
                 existUser·p0.999:  29.297 ms/op
                 existUser·p0.9999: 37.501 ms/op
                 existUser·p1.00:   38.404 ms/op

Iteration   3: 6.145 ±(99.9%) 0.031 ms/op
                 existUser·p0.00:   2.408 ms/op
                 existUser·p0.50:   5.521 ms/op
                 existUser·p0.90:   8.438 ms/op
                 existUser·p0.95:   9.814 ms/op
                 existUser·p0.99:   14.025 ms/op
                 existUser·p0.999:  30.015 ms/op
                 existUser·p0.9999: 32.866 ms/op
                 existUser·p1.00:   33.686 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 164664
  mean =      5.825 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9 
    [ 2.500,  5.000) = 46651 
    [ 5.000,  7.500) = 100490 
    [ 7.500, 10.000) = 12821 
    [10.000, 12.500) = 3349 
    [12.500, 15.000) = 874 
    [15.000, 17.500) = 202 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 34 
    [27.500, 30.000) = 54 
    [30.000, 32.500) = 53 
    [32.500, 35.000) = 34 
    [35.000, 37.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      1.964 ms/op
     p(50.0000) =      5.341 ms/op
     p(90.0000) =      7.627 ms/op
     p(95.0000) =      8.991 ms/op
     p(99.0000) =     12.059 ms/op
     p(99.9000) =     27.230 ms/op
     p(99.9900) =     35.110 ms/op
     p(99.9990) =     38.277 ms/op
     p(99.9999) =     38.404 ms/op
    p(100.0000) =     38.404 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 20.613 ±(99.9%) 0.350 ms/op
# Warmup Iteration   2: 7.947 ±(99.9%) 0.064 ms/op
# Warmup Iteration   3: 6.074 ±(99.9%) 0.026 ms/op
Iteration   1: 5.895 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   1.157 ms/op
                 getUser·p0.50:   5.554 ms/op
                 getUser·p0.90:   7.193 ms/op
                 getUser·p0.95:   8.405 ms/op
                 getUser·p0.99:   11.511 ms/op
                 getUser·p0.999:  24.303 ms/op
                 getUser·p0.9999: 33.751 ms/op
                 getUser·p1.00:   34.406 ms/op

Iteration   2: 5.989 ±(99.9%) 0.028 ms/op
                 getUser·p0.00:   1.937 ms/op
                 getUser·p0.50:   5.530 ms/op
                 getUser·p0.90:   7.447 ms/op
                 getUser·p0.95:   8.798 ms/op
                 getUser·p0.99:   13.369 ms/op
                 getUser·p0.999:  28.156 ms/op
                 getUser·p0.9999: 45.459 ms/op
                 getUser·p1.00:   45.744 ms/op

Iteration   3: 6.197 ±(99.9%) 0.028 ms/op
                 getUser·p0.00:   2.920 ms/op
                 getUser·p0.50:   5.710 ms/op
                 getUser·p0.90:   8.167 ms/op
                 getUser·p0.95:   9.863 ms/op
                 getUser·p0.99:   12.894 ms/op
                 getUser·p0.999:  30.553 ms/op
                 getUser·p0.9999: 39.459 ms/op
                 getUser·p1.00:   40.567 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 159338
  mean =      6.024 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 26868 
    [ 5.000, 10.000) = 127297 
    [10.000, 15.000) = 4463 
    [15.000, 20.000) = 468 
    [20.000, 25.000) = 51 
    [25.000, 30.000) = 71 
    [30.000, 35.000) = 56 
    [35.000, 40.000) = 29 
    [40.000, 45.000) = 22 

  Percentiles, ms/op:
      p(0.0000) =      1.157 ms/op
     p(50.0000) =      5.595 ms/op
     p(90.0000) =      7.520 ms/op
     p(95.0000) =      9.126 ms/op
     p(99.0000) =     12.780 ms/op
     p(99.9000) =     28.355 ms/op
     p(99.9900) =     44.569 ms/op
     p(99.9990) =     45.666 ms/op
     p(99.9999) =     45.744 ms/op
    p(100.0000) =     45.744 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 22.795 ±(99.9%) 0.425 ms/op
# Warmup Iteration   2: 8.290 ±(99.9%) 0.057 ms/op
# Warmup Iteration   3: 6.912 ±(99.9%) 0.027 ms/op
Iteration   1: 6.535 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   3.244 ms/op
                 listUser·p0.50:   6.119 ms/op
                 listUser·p0.90:   7.758 ms/op
                 listUser·p0.95:   9.093 ms/op
                 listUser·p0.99:   12.648 ms/op
                 listUser·p0.999:  29.949 ms/op
                 listUser·p0.9999: 36.045 ms/op
                 listUser·p1.00:   39.780 ms/op

Iteration   2: 6.965 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   2.806 ms/op
                 listUser·p0.50:   6.562 ms/op
                 listUser·p0.90:   8.536 ms/op
                 listUser·p0.95:   9.945 ms/op
                 listUser·p0.99:   13.544 ms/op
                 listUser·p0.999:  29.064 ms/op
                 listUser·p0.9999: 33.102 ms/op
                 listUser·p1.00:   34.931 ms/op

Iteration   3: 7.067 ±(99.9%) 0.033 ms/op
                 listUser·p0.00:   2.839 ms/op
                 listUser·p0.50:   6.537 ms/op
                 listUser·p0.90:   9.110 ms/op
                 listUser·p0.95:   10.600 ms/op
                 listUser·p0.99:   14.991 ms/op
                 listUser·p0.999:  30.656 ms/op
                 listUser·p0.9999: 37.125 ms/op
                 listUser·p1.00:   40.894 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 140266
  mean =      6.848 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 2758 
    [ 5.000, 10.000) = 130647 
    [10.000, 15.000) = 5919 
    [15.000, 20.000) = 540 
    [20.000, 25.000) = 95 
    [25.000, 30.000) = 170 
    [30.000, 35.000) = 122 
    [35.000, 40.000) = 14 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.806 ms/op
     p(50.0000) =      6.382 ms/op
     p(90.0000) =      8.454 ms/op
     p(95.0000) =      9.945 ms/op
     p(99.0000) =     13.697 ms/op
     p(99.9000) =     29.983 ms/op
     p(99.9900) =     35.384 ms/op
     p(99.9990) =     40.446 ms/op
     p(99.9999) =     40.894 ms/op
    p(100.0000) =     40.894 ms/op


# Run complete. Total time: 00:13:19

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.267 ± 2.783  ops/ms
ClientPb.existUser                       thrpt       3   5.137 ± 1.473  ops/ms
ClientPb.getUser                         thrpt       3   4.888 ± 7.243  ops/ms
ClientPb.listUser                        thrpt       3   4.394 ± 6.765  ops/ms
ClientPb.createUser                       avgt       3   6.504 ± 6.707   ms/op
ClientPb.existUser                        avgt       3   5.533 ± 1.742   ms/op
ClientPb.getUser                          avgt       3   6.333 ± 5.680   ms/op
ClientPb.listUser                         avgt       3   6.783 ± 3.036   ms/op
ClientPb.createUser                     sample  157409   6.095 ± 0.015   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.404           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.652           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.823           ms/op
ClientPb.createUser:createUser·p0.95    sample           9.126           ms/op
ClientPb.createUser:createUser·p0.99    sample          12.124           ms/op
ClientPb.createUser:createUser·p0.999   sample          28.553           ms/op
ClientPb.createUser:createUser·p0.9999  sample          38.224           ms/op
ClientPb.createUser:createUser·p1.00    sample          38.666           ms/op
ClientPb.existUser                      sample  164664   5.825 ± 0.014   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.964           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.341           ms/op
ClientPb.existUser:existUser·p0.90      sample           7.627           ms/op
ClientPb.existUser:existUser·p0.95      sample           8.991           ms/op
ClientPb.existUser:existUser·p0.99      sample          12.059           ms/op
ClientPb.existUser:existUser·p0.999     sample          27.230           ms/op
ClientPb.existUser:existUser·p0.9999    sample          35.110           ms/op
ClientPb.existUser:existUser·p1.00      sample          38.404           ms/op
ClientPb.getUser                        sample  159338   6.024 ± 0.015   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.157           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.595           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.520           ms/op
ClientPb.getUser:getUser·p0.95          sample           9.126           ms/op
ClientPb.getUser:getUser·p0.99          sample          12.780           ms/op
ClientPb.getUser:getUser·p0.999         sample          28.355           ms/op
ClientPb.getUser:getUser·p0.9999        sample          44.569           ms/op
ClientPb.getUser:getUser·p1.00          sample          45.744           ms/op
ClientPb.listUser                       sample  140266   6.848 ± 0.017   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.806           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.382           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.454           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.945           ms/op
ClientPb.listUser:listUser·p0.99        sample          13.697           ms/op
ClientPb.listUser:listUser·p0.999       sample          29.983           ms/op
ClientPb.listUser:listUser·p0.9999      sample          35.384           ms/op
ClientPb.listUser:listUser·p1.00        sample          40.894           ms/op
