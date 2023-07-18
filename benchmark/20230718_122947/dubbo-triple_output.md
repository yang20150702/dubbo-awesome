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
# Warmup Iteration   1: 2.052 ops/ms
# Warmup Iteration   2: 5.235 ops/ms
# Warmup Iteration   3: 8.282 ops/ms
Iteration   1: 8.879 ops/ms
Iteration   2: 9.005 ops/ms
Iteration   3: 8.942 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.942 ±(99.9%) 1.148 ops/ms [Average]
  (min, avg, max) = (8.879, 8.942, 9.005), stdev = 0.063
  CI (99.9%): [7.794, 10.090] (assumes normal distribution)


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
# Warmup Iteration   1: 3.002 ops/ms
# Warmup Iteration   2: 8.541 ops/ms
# Warmup Iteration   3: 8.892 ops/ms
Iteration   1: 9.338 ops/ms
Iteration   2: 9.744 ops/ms
Iteration   3: 9.742 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.608 ±(99.9%) 4.264 ops/ms [Average]
  (min, avg, max) = (9.338, 9.608, 9.744), stdev = 0.234
  CI (99.9%): [5.344, 13.873] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.663 ops/ms
# Warmup Iteration   2: 8.049 ops/ms
# Warmup Iteration   3: 8.710 ops/ms
Iteration   1: 9.184 ops/ms
Iteration   2: 9.174 ops/ms
Iteration   3: 9.206 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.188 ±(99.9%) 0.295 ops/ms [Average]
  (min, avg, max) = (9.174, 9.188, 9.206), stdev = 0.016
  CI (99.9%): [8.893, 9.483] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 2.762 ops/ms
# Warmup Iteration   2: 6.979 ops/ms
# Warmup Iteration   3: 7.687 ops/ms
Iteration   1: 7.936 ops/ms
Iteration   2: 7.767 ops/ms
Iteration   3: 7.959 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.887 ±(99.9%) 1.918 ops/ms [Average]
  (min, avg, max) = (7.767, 7.887, 7.959), stdev = 0.105
  CI (99.9%): [5.969, 9.805] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 10.807 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 4.117 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.693 ±(99.9%) 0.006 ms/op
Iteration   1: 3.520 ±(99.9%) 0.005 ms/op
Iteration   2: 3.498 ±(99.9%) 0.009 ms/op
Iteration   3: 3.504 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.507 ±(99.9%) 0.200 ms/op [Average]
  (min, avg, max) = (3.498, 3.507, 3.520), stdev = 0.011
  CI (99.9%): [3.307, 3.707] (assumes normal distribution)


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
# Warmup Iteration   1: 8.834 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.701 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.423 ±(99.9%) 0.004 ms/op
Iteration   1: 3.260 ±(99.9%) 0.009 ms/op
Iteration   2: 3.366 ±(99.9%) 0.003 ms/op
Iteration   3: 3.300 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.309 ±(99.9%) 0.978 ms/op [Average]
  (min, avg, max) = (3.260, 3.309, 3.366), stdev = 0.054
  CI (99.9%): [2.331, 4.287] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 9.532 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.702 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.602 ±(99.9%) 0.005 ms/op
Iteration   1: 3.440 ±(99.9%) 0.007 ms/op
Iteration   2: 3.476 ±(99.9%) 0.005 ms/op
Iteration   3: 3.366 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.427 ±(99.9%) 1.018 ms/op [Average]
  (min, avg, max) = (3.366, 3.427, 3.476), stdev = 0.056
  CI (99.9%): [2.409, 4.445] (assumes normal distribution)


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
# Warmup Iteration   1: 11.368 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.387 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.162 ±(99.9%) 0.009 ms/op
Iteration   1: 4.084 ±(99.9%) 0.009 ms/op
Iteration   2: 3.997 ±(99.9%) 0.011 ms/op
Iteration   3: 4.151 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.077 ±(99.9%) 1.406 ms/op [Average]
  (min, avg, max) = (3.997, 4.077, 4.151), stdev = 0.077
  CI (99.9%): [2.671, 5.484] (assumes normal distribution)


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
# Warmup Iteration   1: 10.401 ±(99.9%) 0.136 ms/op
# Warmup Iteration   2: 4.092 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.783 ±(99.9%) 0.014 ms/op
Iteration   1: 3.537 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.192 ms/op
                 createUser·p0.50:   3.383 ms/op
                 createUser·p0.90:   3.961 ms/op
                 createUser·p0.95:   4.268 ms/op
                 createUser·p0.99:   6.472 ms/op
                 createUser·p0.999:  18.878 ms/op
                 createUser·p0.9999: 22.379 ms/op
                 createUser·p1.00:   23.527 ms/op

Iteration   2: 3.499 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.880 ms/op
                 createUser·p0.50:   3.355 ms/op
                 createUser·p0.90:   3.858 ms/op
                 createUser·p0.95:   4.219 ms/op
                 createUser·p0.99:   6.955 ms/op
                 createUser·p0.999:  21.692 ms/op
                 createUser·p0.9999: 23.855 ms/op
                 createUser·p1.00:   24.936 ms/op

Iteration   3: 3.520 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.718 ms/op
                 createUser·p0.50:   3.453 ms/op
                 createUser·p0.90:   3.891 ms/op
                 createUser·p0.95:   4.243 ms/op
                 createUser·p0.99:   5.988 ms/op
                 createUser·p0.999:  19.169 ms/op
                 createUser·p0.9999: 26.834 ms/op
                 createUser·p1.00:   27.394 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 272742
  mean =      3.519 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4509 
    [ 2.500,  5.000) = 261064 
    [ 5.000,  7.500) = 5754 
    [ 7.500, 10.000) = 889 
    [10.000, 12.500) = 169 
    [12.500, 15.000) = 54 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 112 
    [22.500, 25.000) = 69 
    [25.000, 27.500) = 63 

  Percentiles, ms/op:
      p(0.0000) =      1.192 ms/op
     p(50.0000) =      3.404 ms/op
     p(90.0000) =      3.912 ms/op
     p(95.0000) =      4.243 ms/op
     p(99.0000) =      6.431 ms/op
     p(99.9000) =     19.145 ms/op
     p(99.9900) =     26.500 ms/op
     p(99.9990) =     27.203 ms/op
     p(99.9999) =     27.394 ms/op
    p(100.0000) =     27.394 ms/op


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
# Warmup Iteration   1: 9.396 ±(99.9%) 0.128 ms/op
# Warmup Iteration   2: 3.726 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.509 ±(99.9%) 0.009 ms/op
Iteration   1: 3.273 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.268 ms/op
                 existUser·p0.50:   3.162 ms/op
                 existUser·p0.90:   3.584 ms/op
                 existUser·p0.95:   3.809 ms/op
                 existUser·p0.99:   5.562 ms/op
                 existUser·p0.999:  11.607 ms/op
                 existUser·p0.9999: 23.844 ms/op
                 existUser·p1.00:   24.543 ms/op

Iteration   2: 3.402 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.771 ms/op
                 existUser·p0.50:   3.346 ms/op
                 existUser·p0.90:   3.789 ms/op
                 existUser·p0.95:   4.219 ms/op
                 existUser·p0.99:   6.275 ms/op
                 existUser·p0.999:  10.093 ms/op
                 existUser·p0.9999: 24.124 ms/op
                 existUser·p1.00:   26.771 ms/op

Iteration   3: 3.365 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.251 ms/op
                 existUser·p0.50:   3.363 ms/op
                 existUser·p0.90:   3.510 ms/op
                 existUser·p0.95:   3.809 ms/op
                 existUser·p0.99:   5.746 ms/op
                 existUser·p0.999:  23.067 ms/op
                 existUser·p0.9999: 35.193 ms/op
                 existUser·p1.00:   35.783 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 286852
  mean =      3.346 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16609 
    [ 2.500,  5.000) = 264736 
    [ 5.000,  7.500) = 4700 
    [ 7.500, 10.000) = 490 
    [10.000, 12.500) = 61 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 62 
    [22.500, 25.000) = 123 
    [25.000, 27.500) = 7 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 30 
    [35.000, 37.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.771 ms/op
     p(50.0000) =      3.330 ms/op
     p(90.0000) =      3.580 ms/op
     p(95.0000) =      3.981 ms/op
     p(99.0000) =      5.784 ms/op
     p(99.9000) =     11.357 ms/op
     p(99.9900) =     33.401 ms/op
     p(99.9990) =     35.481 ms/op
     p(99.9999) =     35.783 ms/op
    p(100.0000) =     35.783 ms/op


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
# Warmup Iteration   1: 8.252 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 3.728 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.541 ±(99.9%) 0.012 ms/op
Iteration   1: 3.505 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.606 ms/op
                 getUser·p0.50:   3.305 ms/op
                 getUser·p0.90:   3.895 ms/op
                 getUser·p0.95:   4.260 ms/op
                 getUser·p0.99:   6.871 ms/op
                 getUser·p0.999:  22.759 ms/op
                 getUser·p0.9999: 42.787 ms/op
                 getUser·p1.00:   43.188 ms/op

Iteration   2: 3.498 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.184 ms/op
                 getUser·p0.50:   3.412 ms/op
                 getUser·p0.90:   3.895 ms/op
                 getUser·p0.95:   4.276 ms/op
                 getUser·p0.99:   6.000 ms/op
                 getUser·p0.999:  9.519 ms/op
                 getUser·p0.9999: 29.983 ms/op
                 getUser·p1.00:   30.933 ms/op

Iteration   3: 3.448 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.901 ms/op
                 getUser·p0.50:   3.301 ms/op
                 getUser·p0.90:   3.834 ms/op
                 getUser·p0.95:   4.194 ms/op
                 getUser·p0.99:   6.250 ms/op
                 getUser·p0.999:  22.602 ms/op
                 getUser·p0.9999: 28.017 ms/op
                 getUser·p1.00:   29.622 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 275408
  mean =      3.484 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 267289 
    [ 5.000, 10.000) = 7628 
    [10.000, 15.000) = 139 
    [15.000, 20.000) = 96 
    [20.000, 25.000) = 95 
    [25.000, 30.000) = 116 
    [30.000, 35.000) = 13 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 32 

  Percentiles, ms/op:
      p(0.0000) =      1.184 ms/op
     p(50.0000) =      3.342 ms/op
     p(90.0000) =      3.875 ms/op
     p(95.0000) =      4.243 ms/op
     p(99.0000) =      6.365 ms/op
     p(99.9000) =     18.186 ms/op
     p(99.9900) =     42.074 ms/op
     p(99.9990) =     43.123 ms/op
     p(99.9999) =     43.188 ms/op
    p(100.0000) =     43.188 ms/op


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
# Warmup Iteration   1: 10.805 ±(99.9%) 0.160 ms/op
# Warmup Iteration   2: 4.432 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.316 ±(99.9%) 0.015 ms/op
Iteration   1: 4.271 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.935 ms/op
                 listUser·p0.50:   4.088 ms/op
                 listUser·p0.90:   4.620 ms/op
                 listUser·p0.95:   5.112 ms/op
                 listUser·p0.99:   8.569 ms/op
                 listUser·p0.999:  23.734 ms/op
                 listUser·p0.9999: 29.868 ms/op
                 listUser·p1.00:   30.802 ms/op

Iteration   2: 4.040 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.404 ms/op
                 listUser·p0.50:   3.965 ms/op
                 listUser·p0.90:   4.358 ms/op
                 listUser·p0.95:   4.547 ms/op
                 listUser·p0.99:   6.054 ms/op
                 listUser·p0.999:  16.531 ms/op
                 listUser·p0.9999: 20.709 ms/op
                 listUser·p1.00:   21.103 ms/op

Iteration   3: 4.059 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.224 ms/op
                 listUser·p0.50:   3.920 ms/op
                 listUser·p0.90:   4.375 ms/op
                 listUser·p0.95:   4.702 ms/op
                 listUser·p0.99:   7.274 ms/op
                 listUser·p0.999:  14.549 ms/op
                 listUser·p0.9999: 15.374 ms/op
                 listUser·p1.00:   15.827 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 232997
  mean =      4.121 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 46 
    [ 2.500,  5.000) = 224207 
    [ 5.000,  7.500) = 6018 
    [ 7.500, 10.000) = 1874 
    [10.000, 12.500) = 357 
    [12.500, 15.000) = 157 
    [15.000, 17.500) = 129 
    [17.500, 20.000) = 92 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 39 
    [27.500, 30.000) = 17 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.935 ms/op
     p(50.0000) =      3.973 ms/op
     p(90.0000) =      4.465 ms/op
     p(95.0000) =      4.751 ms/op
     p(99.0000) =      7.742 ms/op
     p(99.9000) =     16.515 ms/op
     p(99.9900) =     27.722 ms/op
     p(99.9990) =     30.289 ms/op
     p(99.9999) =     30.802 ms/op
    p(100.0000) =     30.802 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.942 ± 1.148  ops/ms
ClientPb.existUser                       thrpt       3   9.608 ± 4.264  ops/ms
ClientPb.getUser                         thrpt       3   9.188 ± 0.295  ops/ms
ClientPb.listUser                        thrpt       3   7.887 ± 1.918  ops/ms
ClientPb.createUser                       avgt       3   3.507 ± 0.200   ms/op
ClientPb.existUser                        avgt       3   3.309 ± 0.978   ms/op
ClientPb.getUser                          avgt       3   3.427 ± 1.018   ms/op
ClientPb.listUser                         avgt       3   4.077 ± 1.406   ms/op
ClientPb.createUser                     sample  272742   3.519 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.192           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.404           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.912           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.243           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.431           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.145           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.500           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.394           ms/op
ClientPb.existUser                      sample  286852   3.346 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.771           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.330           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.580           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.981           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.784           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.357           ms/op
ClientPb.existUser:existUser·p0.9999    sample          33.401           ms/op
ClientPb.existUser:existUser·p1.00      sample          35.783           ms/op
ClientPb.getUser                        sample  275408   3.484 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.184           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.342           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.875           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.243           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.365           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.186           ms/op
ClientPb.getUser:getUser·p0.9999        sample          42.074           ms/op
ClientPb.getUser:getUser·p1.00          sample          43.188           ms/op
ClientPb.listUser                       sample  232997   4.121 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.935           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.973           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.465           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.751           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.742           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.515           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.722           ms/op
ClientPb.listUser:listUser·p1.00        sample          30.802           ms/op
