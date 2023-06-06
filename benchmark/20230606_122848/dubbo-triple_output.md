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
# Warmup Iteration   1: 1.838 ops/ms
# Warmup Iteration   2: 4.858 ops/ms
# Warmup Iteration   3: 8.612 ops/ms
Iteration   1: 8.868 ops/ms
Iteration   2: 9.114 ops/ms
Iteration   3: 9.139 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.040 ±(99.9%) 2.737 ops/ms [Average]
  (min, avg, max) = (8.868, 9.040, 9.139), stdev = 0.150
  CI (99.9%): [6.303, 11.777] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.210 ops/ms
# Warmup Iteration   2: 9.138 ops/ms
# Warmup Iteration   3: 9.349 ops/ms
Iteration   1: 9.602 ops/ms
Iteration   2: 9.792 ops/ms
Iteration   3: 9.329 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.575 ±(99.9%) 4.242 ops/ms [Average]
  (min, avg, max) = (9.329, 9.575, 9.792), stdev = 0.232
  CI (99.9%): [5.333, 13.816] (assumes normal distribution)


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
# Warmup Iteration   1: 3.228 ops/ms
# Warmup Iteration   2: 8.428 ops/ms
# Warmup Iteration   3: 9.034 ops/ms
Iteration   1: 9.310 ops/ms
Iteration   2: 8.970 ops/ms
Iteration   3: 9.478 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.253 ±(99.9%) 4.727 ops/ms [Average]
  (min, avg, max) = (8.970, 9.253, 9.478), stdev = 0.259
  CI (99.9%): [4.525, 13.980] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.649 ops/ms
# Warmup Iteration   2: 6.932 ops/ms
# Warmup Iteration   3: 7.795 ops/ms
Iteration   1: 7.701 ops/ms
Iteration   2: 8.239 ops/ms
Iteration   3: 7.951 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.963 ±(99.9%) 4.913 ops/ms [Average]
  (min, avg, max) = (7.701, 7.963, 8.239), stdev = 0.269
  CI (99.9%): [3.050, 12.877] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 9.190 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 3.632 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.681 ±(99.9%) 0.005 ms/op
Iteration   1: 3.514 ±(99.9%) 0.003 ms/op
Iteration   2: 3.362 ±(99.9%) 0.007 ms/op
Iteration   3: 3.275 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.384 ±(99.9%) 2.208 ms/op [Average]
  (min, avg, max) = (3.275, 3.384, 3.514), stdev = 0.121
  CI (99.9%): [1.176, 5.592] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 7.781 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.537 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.384 ±(99.9%) 0.009 ms/op
Iteration   1: 3.332 ±(99.9%) 0.004 ms/op
Iteration   2: 3.375 ±(99.9%) 0.007 ms/op
Iteration   3: 3.345 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.350 ±(99.9%) 0.401 ms/op [Average]
  (min, avg, max) = (3.332, 3.350, 3.375), stdev = 0.022
  CI (99.9%): [2.949, 3.752] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 8.296 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.721 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.395 ±(99.9%) 0.004 ms/op
Iteration   1: 3.403 ±(99.9%) 0.009 ms/op
Iteration   2: 3.412 ±(99.9%) 0.011 ms/op
Iteration   3: 3.505 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.440 ±(99.9%) 1.028 ms/op [Average]
  (min, avg, max) = (3.403, 3.440, 3.505), stdev = 0.056
  CI (99.9%): [2.412, 4.468] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 10.121 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.408 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.083 ±(99.9%) 0.009 ms/op
Iteration   1: 4.008 ±(99.9%) 0.013 ms/op
Iteration   2: 4.063 ±(99.9%) 0.012 ms/op
Iteration   3: 3.983 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.018 ±(99.9%) 0.753 ms/op [Average]
  (min, avg, max) = (3.983, 4.018, 4.063), stdev = 0.041
  CI (99.9%): [3.265, 4.771] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 10.383 ±(99.9%) 0.146 ms/op
# Warmup Iteration   2: 3.935 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.685 ±(99.9%) 0.014 ms/op
Iteration   1: 3.591 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.702 ms/op
                 createUser·p0.50:   3.428 ms/op
                 createUser·p0.90:   4.174 ms/op
                 createUser·p0.95:   4.579 ms/op
                 createUser·p0.99:   6.685 ms/op
                 createUser·p0.999:  20.172 ms/op
                 createUser·p0.9999: 25.526 ms/op
                 createUser·p1.00:   25.854 ms/op

Iteration   2: 3.641 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.458 ms/op
                 createUser·p0.50:   3.445 ms/op
                 createUser·p0.90:   4.407 ms/op
                 createUser·p0.95:   4.940 ms/op
                 createUser·p0.99:   6.504 ms/op
                 createUser·p0.999:  22.943 ms/op
                 createUser·p0.9999: 27.987 ms/op
                 createUser·p1.00:   28.246 ms/op

Iteration   3: 3.517 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.548 ms/op
                 createUser·p0.50:   3.432 ms/op
                 createUser·p0.90:   3.953 ms/op
                 createUser·p0.95:   4.391 ms/op
                 createUser·p0.99:   5.825 ms/op
                 createUser·p0.999:  24.153 ms/op
                 createUser·p0.9999: 38.705 ms/op
                 createUser·p1.00:   40.567 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 267874
  mean =      3.582 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 258552 
    [ 5.000, 10.000) = 8823 
    [10.000, 15.000) = 156 
    [15.000, 20.000) = 22 
    [20.000, 25.000) = 199 
    [25.000, 30.000) = 113 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 6 
    [40.000, 45.000) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.458 ms/op
     p(50.0000) =      3.437 ms/op
     p(90.0000) =      4.182 ms/op
     p(95.0000) =      4.710 ms/op
     p(99.0000) =      6.398 ms/op
     p(99.9000) =     21.758 ms/op
     p(99.9900) =     27.096 ms/op
     p(99.9990) =     40.436 ms/op
     p(99.9999) =     40.567 ms/op
    p(100.0000) =     40.567 ms/op


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
# Warmup Iteration   1: 9.220 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 3.734 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.410 ±(99.9%) 0.008 ms/op
Iteration   1: 3.232 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.735 ms/op
                 existUser·p0.50:   3.121 ms/op
                 existUser·p0.90:   3.527 ms/op
                 existUser·p0.95:   3.785 ms/op
                 existUser·p0.99:   5.554 ms/op
                 existUser·p0.999:  9.733 ms/op
                 existUser·p0.9999: 25.107 ms/op
                 existUser·p1.00:   26.378 ms/op

Iteration   2: 3.397 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.704 ms/op
                 existUser·p0.50:   3.252 ms/op
                 existUser·p0.90:   3.711 ms/op
                 existUser·p0.95:   4.334 ms/op
                 existUser·p0.99:   6.717 ms/op
                 existUser·p0.999:  22.606 ms/op
                 existUser·p0.9999: 31.155 ms/op
                 existUser·p1.00:   31.490 ms/op

Iteration   3: 3.272 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.298 ms/op
                 existUser·p0.50:   3.150 ms/op
                 existUser·p0.90:   3.596 ms/op
                 existUser·p0.95:   3.850 ms/op
                 existUser·p0.99:   5.530 ms/op
                 existUser·p0.999:  11.247 ms/op
                 existUser·p0.9999: 31.442 ms/op
                 existUser·p1.00:   32.375 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 290772
  mean =      3.299 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4596 
    [ 2.500,  5.000) = 279805 
    [ 5.000,  7.500) = 5414 
    [ 7.500, 10.000) = 584 
    [10.000, 12.500) = 70 
    [12.500, 15.000) = 15 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 57 
    [22.500, 25.000) = 126 
    [25.000, 27.500) = 42 
    [27.500, 30.000) = 16 
    [30.000, 32.500) = 47 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.298 ms/op
     p(50.0000) =      3.166 ms/op
     p(90.0000) =      3.617 ms/op
     p(95.0000) =      3.944 ms/op
     p(99.0000) =      5.816 ms/op
     p(99.9000) =     13.176 ms/op
     p(99.9900) =     30.376 ms/op
     p(99.9990) =     32.158 ms/op
     p(99.9999) =     32.375 ms/op
    p(100.0000) =     32.375 ms/op


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
# Warmup Iteration   1: 8.564 ±(99.9%) 0.119 ms/op
# Warmup Iteration   2: 3.789 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.588 ±(99.9%) 0.013 ms/op
Iteration   1: 3.420 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.444 ms/op
                 getUser·p0.50:   3.293 ms/op
                 getUser·p0.90:   3.695 ms/op
                 getUser·p0.95:   3.879 ms/op
                 getUser·p0.99:   6.531 ms/op
                 getUser·p0.999:  19.431 ms/op
                 getUser·p0.9999: 27.371 ms/op
                 getUser·p1.00:   28.344 ms/op

Iteration   2: 3.624 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.724 ms/op
                 getUser·p0.50:   3.428 ms/op
                 getUser·p0.90:   4.391 ms/op
                 getUser·p0.95:   4.923 ms/op
                 getUser·p0.99:   6.504 ms/op
                 getUser·p0.999:  10.617 ms/op
                 getUser·p0.9999: 26.230 ms/op
                 getUser·p1.00:   27.197 ms/op

Iteration   3: 3.491 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.665 ms/op
                 getUser·p0.50:   3.404 ms/op
                 getUser·p0.90:   4.002 ms/op
                 getUser·p0.95:   4.342 ms/op
                 getUser·p0.99:   6.005 ms/op
                 getUser·p0.999:  19.772 ms/op
                 getUser·p0.9999: 37.093 ms/op
                 getUser·p1.00:   38.404 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 273458
  mean =      3.510 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7256 
    [ 2.500,  5.000) = 257346 
    [ 5.000,  7.500) = 7756 
    [ 7.500, 10.000) = 691 
    [10.000, 12.500) = 150 
    [12.500, 15.000) = 3 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 72 
    [22.500, 25.000) = 66 
    [25.000, 27.500) = 60 
    [27.500, 30.000) = 5 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      1.444 ms/op
     p(50.0000) =      3.379 ms/op
     p(90.0000) =      4.047 ms/op
     p(95.0000) =      4.481 ms/op
     p(99.0000) =      6.365 ms/op
     p(99.9000) =     11.633 ms/op
     p(99.9900) =     36.504 ms/op
     p(99.9990) =     37.504 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 10.610 ±(99.9%) 0.141 ms/op
# Warmup Iteration   2: 4.401 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.027 ±(99.9%) 0.012 ms/op
Iteration   1: 4.020 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.817 ms/op
                 listUser·p0.50:   3.838 ms/op
                 listUser·p0.90:   4.383 ms/op
                 listUser·p0.95:   4.727 ms/op
                 listUser·p0.99:   7.193 ms/op
                 listUser·p0.999:  20.087 ms/op
                 listUser·p0.9999: 22.482 ms/op
                 listUser·p1.00:   23.233 ms/op

Iteration   2: 3.995 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.441 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   4.506 ms/op
                 listUser·p0.95:   4.760 ms/op
                 listUser·p0.99:   7.438 ms/op
                 listUser·p0.999:  16.073 ms/op
                 listUser·p0.9999: 18.842 ms/op
                 listUser·p1.00:   18.907 ms/op

Iteration   3: 4.070 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.097 ms/op
                 listUser·p0.50:   3.846 ms/op
                 listUser·p0.90:   4.588 ms/op
                 listUser·p0.95:   5.120 ms/op
                 listUser·p0.99:   7.602 ms/op
                 listUser·p0.999:  14.949 ms/op
                 listUser·p0.9999: 18.612 ms/op
                 listUser·p1.00:   18.678 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 238001
  mean =      4.028 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 39 
    [ 2.500,  5.000) = 227671 
    [ 5.000,  7.500) = 7947 
    [ 7.500, 10.000) = 1531 
    [10.000, 12.500) = 246 
    [12.500, 15.000) = 151 
    [15.000, 17.500) = 219 
    [17.500, 20.000) = 114 
    [20.000, 22.500) = 76 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.817 ms/op
     p(50.0000) =      3.830 ms/op
     p(90.0000) =      4.497 ms/op
     p(95.0000) =      4.850 ms/op
     p(99.0000) =      7.487 ms/op
     p(99.9000) =     16.581 ms/op
     p(99.9900) =     21.823 ms/op
     p(99.9990) =     23.018 ms/op
     p(99.9999) =     23.233 ms/op
    p(100.0000) =     23.233 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.040 ± 2.737  ops/ms
ClientPb.existUser                       thrpt       3   9.575 ± 4.242  ops/ms
ClientPb.getUser                         thrpt       3   9.253 ± 4.727  ops/ms
ClientPb.listUser                        thrpt       3   7.963 ± 4.913  ops/ms
ClientPb.createUser                       avgt       3   3.384 ± 2.208   ms/op
ClientPb.existUser                        avgt       3   3.350 ± 0.401   ms/op
ClientPb.getUser                          avgt       3   3.440 ± 1.028   ms/op
ClientPb.listUser                         avgt       3   4.018 ± 0.753   ms/op
ClientPb.createUser                     sample  267874   3.582 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.458           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.437           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.182           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.710           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.398           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.758           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.096           ms/op
ClientPb.createUser:createUser·p1.00    sample          40.567           ms/op
ClientPb.existUser                      sample  290772   3.299 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.298           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.166           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.617           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.944           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.816           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.176           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.376           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.375           ms/op
ClientPb.getUser                        sample  273458   3.510 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.444           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.379           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.047           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.481           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.365           ms/op
ClientPb.getUser:getUser·p0.999         sample          11.633           ms/op
ClientPb.getUser:getUser·p0.9999        sample          36.504           ms/op
ClientPb.getUser:getUser·p1.00          sample          38.404           ms/op
ClientPb.listUser                       sample  238001   4.028 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.817           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.830           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.497           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.850           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.487           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.581           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.823           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.233           ms/op
