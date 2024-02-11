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
# Warmup Iteration   1: 4.752 ops/ms
# Warmup Iteration   2: 12.150 ops/ms
# Warmup Iteration   3: 12.406 ops/ms
Iteration   1: 12.671 ops/ms
Iteration   2: 12.672 ops/ms
Iteration   3: 12.737 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.693 ±(99.9%) 0.692 ops/ms [Average]
  (min, avg, max) = (12.671, 12.693, 12.737), stdev = 0.038
  CI (99.9%): [12.001, 13.386] (assumes normal distribution)


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
# Warmup Iteration   1: 7.819 ops/ms
# Warmup Iteration   2: 12.957 ops/ms
# Warmup Iteration   3: 12.924 ops/ms
Iteration   1: 13.048 ops/ms
Iteration   2: 13.084 ops/ms
Iteration   3: 13.091 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.074 ±(99.9%) 0.423 ops/ms [Average]
  (min, avg, max) = (13.048, 13.074, 13.091), stdev = 0.023
  CI (99.9%): [12.652, 13.497] (assumes normal distribution)


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
# Warmup Iteration   1: 7.491 ops/ms
# Warmup Iteration   2: 12.667 ops/ms
# Warmup Iteration   3: 12.837 ops/ms
Iteration   1: 12.980 ops/ms
Iteration   2: 12.982 ops/ms
Iteration   3: 12.649 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.870 ±(99.9%) 3.504 ops/ms [Average]
  (min, avg, max) = (12.649, 12.870, 12.982), stdev = 0.192
  CI (99.9%): [9.366, 16.375] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.401 ops/ms
# Warmup Iteration   2: 10.459 ops/ms
# Warmup Iteration   3: 10.707 ops/ms
Iteration   1: 10.888 ops/ms
Iteration   2: 10.813 ops/ms
Iteration   3: 10.865 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.855 ±(99.9%) 0.699 ops/ms [Average]
  (min, avg, max) = (10.813, 10.855, 10.888), stdev = 0.038
  CI (99.9%): [10.156, 11.555] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 3.951 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 2.520 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.466 ±(99.9%) 0.003 ms/op
Iteration   1: 2.482 ±(99.9%) 0.005 ms/op
Iteration   2: 2.458 ±(99.9%) 0.004 ms/op
Iteration   3: 2.451 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.464 ±(99.9%) 0.298 ms/op [Average]
  (min, avg, max) = (2.451, 2.464, 2.482), stdev = 0.016
  CI (99.9%): [2.166, 2.761] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.940 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.494 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.481 ±(99.9%) 0.003 ms/op
Iteration   1: 2.435 ±(99.9%) 0.004 ms/op
Iteration   2: 2.430 ±(99.9%) 0.004 ms/op
Iteration   3: 2.434 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.433 ±(99.9%) 0.053 ms/op [Average]
  (min, avg, max) = (2.430, 2.433, 2.435), stdev = 0.003
  CI (99.9%): [2.380, 2.486] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 3.908 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.506 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.479 ±(99.9%) 0.004 ms/op
Iteration   1: 2.467 ±(99.9%) 0.005 ms/op
Iteration   2: 2.468 ±(99.9%) 0.004 ms/op
Iteration   3: 2.506 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.480 ±(99.9%) 0.404 ms/op [Average]
  (min, avg, max) = (2.467, 2.480, 2.506), stdev = 0.022
  CI (99.9%): [2.076, 2.884] (assumes normal distribution)


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
# Warmup Iteration   1: 4.753 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.015 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.948 ±(99.9%) 0.005 ms/op
Iteration   1: 2.972 ±(99.9%) 0.005 ms/op
Iteration   2: 2.963 ±(99.9%) 0.006 ms/op
Iteration   3: 3.014 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.983 ±(99.9%) 0.493 ms/op [Average]
  (min, avg, max) = (2.963, 2.983, 3.014), stdev = 0.027
  CI (99.9%): [2.490, 3.476] (assumes normal distribution)


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
# Warmup Iteration   1: 4.270 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 2.599 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.500 ±(99.9%) 0.005 ms/op
Iteration   1: 2.486 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.569 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.015 ms/op
                 createUser·p0.95:   3.125 ms/op
                 createUser·p0.99:   3.617 ms/op
                 createUser·p0.999:  8.051 ms/op
                 createUser·p0.9999: 13.599 ms/op
                 createUser·p1.00:   14.352 ms/op

Iteration   2: 2.498 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.935 ms/op
                 createUser·p0.50:   2.572 ms/op
                 createUser·p0.90:   3.035 ms/op
                 createUser·p0.95:   3.150 ms/op
                 createUser·p0.99:   3.793 ms/op
                 createUser·p0.999:  9.683 ms/op
                 createUser·p0.9999: 12.655 ms/op
                 createUser·p1.00:   13.156 ms/op

Iteration   3: 2.509 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.002 ms/op
                 createUser·p0.50:   2.552 ms/op
                 createUser·p0.90:   3.060 ms/op
                 createUser·p0.95:   3.215 ms/op
                 createUser·p0.99:   3.973 ms/op
                 createUser·p0.999:  8.062 ms/op
                 createUser·p0.9999: 10.699 ms/op
                 createUser·p1.00:   11.600 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 384021
  mean =      2.498 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 49 
    [ 1.250,  2.500) = 185666 
    [ 2.500,  3.750) = 194229 
    [ 3.750,  5.000) = 3091 
    [ 5.000,  6.250) = 516 
    [ 6.250,  7.500) = 40 
    [ 7.500,  8.750) = 68 
    [ 8.750, 10.000) = 98 
    [10.000, 11.250) = 67 
    [11.250, 12.500) = 94 
    [12.500, 13.750) = 98 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.569 ms/op
     p(50.0000) =      2.568 ms/op
     p(90.0000) =      3.035 ms/op
     p(95.0000) =      3.162 ms/op
     p(99.0000) =      3.789 ms/op
     p(99.9000) =      8.552 ms/op
     p(99.9900) =     13.238 ms/op
     p(99.9990) =     13.937 ms/op
     p(99.9999) =     14.352 ms/op
    p(100.0000) =     14.352 ms/op


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
# Warmup Iteration   1: 3.656 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.486 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.453 ±(99.9%) 0.005 ms/op
Iteration   1: 2.423 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.828 ms/op
                 existUser·p0.50:   2.535 ms/op
                 existUser·p0.90:   2.931 ms/op
                 existUser·p0.95:   3.027 ms/op
                 existUser·p0.99:   3.473 ms/op
                 existUser·p0.999:  5.703 ms/op
                 existUser·p0.9999: 14.660 ms/op
                 existUser·p1.00:   15.778 ms/op

Iteration   2: 2.426 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.919 ms/op
                 existUser·p0.50:   2.552 ms/op
                 existUser·p0.90:   2.937 ms/op
                 existUser·p0.95:   3.031 ms/op
                 existUser·p0.99:   3.494 ms/op
                 existUser·p0.999:  5.448 ms/op
                 existUser·p0.9999: 12.984 ms/op
                 existUser·p1.00:   13.877 ms/op

Iteration   3: 2.422 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.894 ms/op
                 existUser·p0.50:   2.466 ms/op
                 existUser·p0.90:   2.941 ms/op
                 existUser·p0.95:   3.047 ms/op
                 existUser·p0.99:   3.539 ms/op
                 existUser·p0.999:  9.257 ms/op
                 existUser·p0.9999: 11.826 ms/op
                 existUser·p1.00:   12.157 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 395624
  mean =      2.424 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 26 
    [ 1.250,  2.500) = 196497 
    [ 2.500,  3.750) = 196608 
    [ 3.750,  5.000) = 1817 
    [ 5.000,  6.250) = 192 
    [ 6.250,  7.500) = 61 
    [ 7.500,  8.750) = 51 
    [ 8.750, 10.000) = 83 
    [10.000, 11.250) = 93 
    [11.250, 12.500) = 81 
    [12.500, 13.750) = 77 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 7 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.828 ms/op
     p(50.0000) =      2.515 ms/op
     p(90.0000) =      2.937 ms/op
     p(95.0000) =      3.035 ms/op
     p(99.0000) =      3.502 ms/op
     p(99.9000) =      7.862 ms/op
     p(99.9900) =     13.728 ms/op
     p(99.9990) =     15.582 ms/op
     p(99.9999) =     15.778 ms/op
    p(100.0000) =     15.778 ms/op


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
# Warmup Iteration   1: 3.965 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.537 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.500 ±(99.9%) 0.006 ms/op
Iteration   1: 2.488 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.849 ms/op
                 getUser·p0.50:   2.515 ms/op
                 getUser·p0.90:   3.035 ms/op
                 getUser·p0.95:   3.183 ms/op
                 getUser·p0.99:   3.891 ms/op
                 getUser·p0.999:  9.362 ms/op
                 getUser·p0.9999: 15.167 ms/op
                 getUser·p1.00:   16.040 ms/op

Iteration   2: 2.507 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.803 ms/op
                 getUser·p0.50:   2.531 ms/op
                 getUser·p0.90:   3.060 ms/op
                 getUser·p0.95:   3.219 ms/op
                 getUser·p0.99:   4.227 ms/op
                 getUser·p0.999:  7.037 ms/op
                 getUser·p0.9999: 12.886 ms/op
                 getUser·p1.00:   13.353 ms/op

Iteration   3: 2.494 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.961 ms/op
                 getUser·p0.50:   2.515 ms/op
                 getUser·p0.90:   3.056 ms/op
                 getUser·p0.95:   3.178 ms/op
                 getUser·p0.99:   3.752 ms/op
                 getUser·p0.999:  5.396 ms/op
                 getUser·p0.9999: 11.239 ms/op
                 getUser·p1.00:   11.469 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 384298
  mean =      2.496 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 81 
    [ 1.250,  2.500) = 190323 
    [ 2.500,  3.750) = 188737 
    [ 3.750,  5.000) = 4081 
    [ 5.000,  6.250) = 658 
    [ 6.250,  7.500) = 82 
    [ 7.500,  8.750) = 14 
    [ 8.750, 10.000) = 55 
    [10.000, 11.250) = 64 
    [11.250, 12.500) = 59 
    [12.500, 13.750) = 92 
    [13.750, 15.000) = 37 
    [15.000, 16.250) = 15 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.803 ms/op
     p(50.0000) =      2.519 ms/op
     p(90.0000) =      3.052 ms/op
     p(95.0000) =      3.191 ms/op
     p(99.0000) =      3.928 ms/op
     p(99.9000) =      6.644 ms/op
     p(99.9900) =     14.320 ms/op
     p(99.9990) =     15.728 ms/op
     p(99.9999) =     16.040 ms/op
    p(100.0000) =     16.040 ms/op


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
# Warmup Iteration   1: 4.821 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.091 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.008 ±(99.9%) 0.008 ms/op
Iteration   1: 3.018 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.765 ms/op
                 listUser·p0.50:   2.953 ms/op
                 listUser·p0.90:   3.908 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.620 ms/op
                 listUser·p0.999:  8.914 ms/op
                 listUser·p0.9999: 11.549 ms/op
                 listUser·p1.00:   12.190 ms/op

Iteration   2: 3.006 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.894 ms/op
                 listUser·p0.50:   2.933 ms/op
                 listUser·p0.90:   3.895 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   5.576 ms/op
                 listUser·p0.999:  8.804 ms/op
                 listUser·p0.9999: 12.222 ms/op
                 listUser·p1.00:   13.550 ms/op

Iteration   3: 3.015 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.950 ms/op
                 listUser·p0.50:   2.953 ms/op
                 listUser·p0.90:   3.875 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   5.579 ms/op
                 listUser·p0.999:  9.535 ms/op
                 listUser·p0.9999: 11.518 ms/op
                 listUser·p1.00:   12.173 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 318275
  mean =      3.013 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 139 
    [ 1.250,  2.500) = 91293 
    [ 2.500,  3.750) = 187281 
    [ 3.750,  5.000) = 32393 
    [ 5.000,  6.250) = 5906 
    [ 6.250,  7.500) = 639 
    [ 7.500,  8.750) = 252 
    [ 8.750, 10.000) = 187 
    [10.000, 11.250) = 122 
    [11.250, 12.500) = 57 
    [12.500, 13.750) = 6 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.765 ms/op
     p(50.0000) =      2.945 ms/op
     p(90.0000) =      3.891 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      5.587 ms/op
     p(99.9000) =      9.093 ms/op
     p(99.9900) =     11.734 ms/op
     p(99.9990) =     13.080 ms/op
     p(99.9999) =     13.550 ms/op
    p(100.0000) =     13.550 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.693 ± 0.692  ops/ms
ClientPb.existUser                       thrpt       3  13.074 ± 0.423  ops/ms
ClientPb.getUser                         thrpt       3  12.870 ± 3.504  ops/ms
ClientPb.listUser                        thrpt       3  10.855 ± 0.699  ops/ms
ClientPb.createUser                       avgt       3   2.464 ± 0.298   ms/op
ClientPb.existUser                        avgt       3   2.433 ± 0.053   ms/op
ClientPb.getUser                          avgt       3   2.480 ± 0.404   ms/op
ClientPb.listUser                         avgt       3   2.983 ± 0.493   ms/op
ClientPb.createUser                     sample  384021   2.498 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.569           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.568           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.035           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.162           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.789           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.552           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.238           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.352           ms/op
ClientPb.existUser                      sample  395624   2.424 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.828           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.515           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.937           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.035           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.502           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.862           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.728           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.778           ms/op
ClientPb.getUser                        sample  384298   2.496 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.803           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.519           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.052           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.191           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.928           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.644           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.320           ms/op
ClientPb.getUser:getUser·p1.00          sample          16.040           ms/op
ClientPb.listUser                       sample  318275   3.013 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.765           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.945           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.891           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.383           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.587           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.093           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.734           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.550           ms/op
