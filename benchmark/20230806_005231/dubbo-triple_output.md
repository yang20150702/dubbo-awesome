# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.182 ops/ms
# Warmup Iteration   2: 4.166 ops/ms
# Warmup Iteration   3: 8.318 ops/ms
Iteration   1: 8.875 ops/ms
Iteration   2: 8.955 ops/ms
Iteration   3: 9.314 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.048 ±(99.9%) 4.262 ops/ms [Average]
  (min, avg, max) = (8.875, 9.048, 9.314), stdev = 0.234
  CI (99.9%): [4.786, 13.310] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 2.820 ops/ms
# Warmup Iteration   2: 8.421 ops/ms
# Warmup Iteration   3: 9.322 ops/ms
Iteration   1: 9.996 ops/ms
Iteration   2: 9.827 ops/ms
Iteration   3: 9.841 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.888 ±(99.9%) 1.704 ops/ms [Average]
  (min, avg, max) = (9.827, 9.888, 9.996), stdev = 0.093
  CI (99.9%): [8.185, 11.592] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.800 ops/ms
# Warmup Iteration   2: 8.247 ops/ms
# Warmup Iteration   3: 8.767 ops/ms
Iteration   1: 9.091 ops/ms
Iteration   2: 9.244 ops/ms
Iteration   3: 9.518 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.285 ±(99.9%) 3.947 ops/ms [Average]
  (min, avg, max) = (9.091, 9.285, 9.518), stdev = 0.216
  CI (99.9%): [5.337, 13.232] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.805 ops/ms
# Warmup Iteration   2: 7.042 ops/ms
# Warmup Iteration   3: 7.895 ops/ms
Iteration   1: 7.844 ops/ms
Iteration   2: 7.699 ops/ms
Iteration   3: 7.798 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.780 ±(99.9%) 1.351 ops/ms [Average]
  (min, avg, max) = (7.699, 7.780, 7.844), stdev = 0.074
  CI (99.9%): [6.429, 9.132] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 10.845 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.068 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.687 ±(99.9%) 0.005 ms/op
Iteration   1: 3.646 ±(99.9%) 0.006 ms/op
Iteration   2: 3.470 ±(99.9%) 0.007 ms/op
Iteration   3: 3.440 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.519 ±(99.9%) 2.030 ms/op [Average]
  (min, avg, max) = (3.440, 3.519, 3.646), stdev = 0.111
  CI (99.9%): [1.489, 5.548] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 8.714 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.683 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.463 ±(99.9%) 0.008 ms/op
Iteration   1: 3.415 ±(99.9%) 0.004 ms/op
Iteration   2: 3.362 ±(99.9%) 0.005 ms/op
Iteration   3: 3.361 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.379 ±(99.9%) 0.562 ms/op [Average]
  (min, avg, max) = (3.361, 3.379, 3.415), stdev = 0.031
  CI (99.9%): [2.817, 3.941] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 9.733 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.798 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.662 ±(99.9%) 0.005 ms/op
Iteration   1: 3.457 ±(99.9%) 0.005 ms/op
Iteration   2: 3.377 ±(99.9%) 0.003 ms/op
Iteration   3: 3.519 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.451 ±(99.9%) 1.292 ms/op [Average]
  (min, avg, max) = (3.377, 3.451, 3.519), stdev = 0.071
  CI (99.9%): [2.159, 4.743] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 10.563 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.517 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.232 ±(99.9%) 0.006 ms/op
Iteration   1: 4.075 ±(99.9%) 0.008 ms/op
Iteration   2: 4.042 ±(99.9%) 0.008 ms/op
Iteration   3: 4.057 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.058 ±(99.9%) 0.306 ms/op [Average]
  (min, avg, max) = (4.042, 4.058, 4.075), stdev = 0.017
  CI (99.9%): [3.752, 4.364] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 9.858 ±(99.9%) 0.147 ms/op
# Warmup Iteration   2: 4.108 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.659 ±(99.9%) 0.013 ms/op
Iteration   1: 3.547 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.415 ms/op
                 createUser·p0.50:   3.387 ms/op
                 createUser·p0.90:   4.182 ms/op
                 createUser·p0.95:   4.891 ms/op
                 createUser·p0.99:   5.906 ms/op
                 createUser·p0.999:  20.311 ms/op
                 createUser·p0.9999: 25.258 ms/op
                 createUser·p1.00:   26.477 ms/op

Iteration   2: 3.506 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.677 ms/op
                 createUser·p0.50:   3.351 ms/op
                 createUser·p0.90:   3.924 ms/op
                 createUser·p0.95:   4.194 ms/op
                 createUser·p0.99:   6.627 ms/op
                 createUser·p0.999:  22.470 ms/op
                 createUser·p0.9999: 24.989 ms/op
                 createUser·p1.00:   25.919 ms/op

Iteration   3: 3.417 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.599 ms/op
                 createUser·p0.50:   3.371 ms/op
                 createUser·p0.90:   3.666 ms/op
                 createUser·p0.95:   3.936 ms/op
                 createUser·p0.99:   6.054 ms/op
                 createUser·p0.999:  19.806 ms/op
                 createUser·p0.9999: 26.891 ms/op
                 createUser·p1.00:   27.394 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 274938
  mean =      3.489 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6316 
    [ 2.500,  5.000) = 260845 
    [ 5.000,  7.500) = 6244 
    [ 7.500, 10.000) = 974 
    [10.000, 12.500) = 195 
    [12.500, 15.000) = 76 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 74 
    [22.500, 25.000) = 147 
    [25.000, 27.500) = 61 

  Percentiles, ms/op:
      p(0.0000) =      1.415 ms/op
     p(50.0000) =      3.371 ms/op
     p(90.0000) =      3.924 ms/op
     p(95.0000) =      4.284 ms/op
     p(99.0000) =      6.119 ms/op
     p(99.9000) =     20.089 ms/op
     p(99.9900) =     25.903 ms/op
     p(99.9990) =     27.238 ms/op
     p(99.9999) =     27.394 ms/op
    p(100.0000) =     27.394 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 8.980 ±(99.9%) 0.121 ms/op
# Warmup Iteration   2: 3.651 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.482 ±(99.9%) 0.009 ms/op
Iteration   1: 3.396 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.737 ms/op
                 existUser·p0.50:   3.330 ms/op
                 existUser·p0.90:   3.756 ms/op
                 existUser·p0.95:   4.153 ms/op
                 existUser·p0.99:   5.816 ms/op
                 existUser·p0.999:  20.081 ms/op
                 existUser·p0.9999: 29.609 ms/op
                 existUser·p1.00:   31.130 ms/op

Iteration   2: 3.362 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.681 ms/op
                 existUser·p0.50:   3.252 ms/op
                 existUser·p0.90:   3.576 ms/op
                 existUser·p0.95:   3.854 ms/op
                 existUser·p0.99:   6.169 ms/op
                 existUser·p0.999:  21.850 ms/op
                 existUser·p0.9999: 25.312 ms/op
                 existUser·p1.00:   26.083 ms/op

Iteration   3: 3.356 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.608 ms/op
                 existUser·p0.50:   3.301 ms/op
                 existUser·p0.90:   3.654 ms/op
                 existUser·p0.95:   3.928 ms/op
                 existUser·p0.99:   5.980 ms/op
                 existUser·p0.999:  9.863 ms/op
                 existUser·p0.9999: 26.132 ms/op
                 existUser·p1.00:   26.313 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 284391
  mean =      3.371 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12123 
    [ 2.500,  5.000) = 266962 
    [ 5.000,  7.500) = 3939 
    [ 7.500, 10.000) = 877 
    [10.000, 12.500) = 210 
    [12.500, 15.000) = 14 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 72 
    [22.500, 25.000) = 108 
    [25.000, 27.500) = 44 
    [27.500, 30.000) = 24 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.608 ms/op
     p(50.0000) =      3.293 ms/op
     p(90.0000) =      3.654 ms/op
     p(95.0000) =      3.994 ms/op
     p(99.0000) =      5.947 ms/op
     p(99.9000) =     12.430 ms/op
     p(99.9900) =     28.254 ms/op
     p(99.9990) =     30.278 ms/op
     p(99.9999) =     31.130 ms/op
    p(100.0000) =     31.130 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.358 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 3.729 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.682 ±(99.9%) 0.012 ms/op
Iteration   1: 3.547 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.460 ms/op
                 getUser·p0.50:   3.391 ms/op
                 getUser·p0.90:   3.912 ms/op
                 getUser·p0.95:   4.358 ms/op
                 getUser·p0.99:   7.111 ms/op
                 getUser·p0.999:  19.122 ms/op
                 getUser·p0.9999: 26.931 ms/op
                 getUser·p1.00:   29.753 ms/op

Iteration   2: 3.493 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.157 ms/op
                 getUser·p0.50:   3.355 ms/op
                 getUser·p0.90:   3.809 ms/op
                 getUser·p0.95:   4.252 ms/op
                 getUser·p0.99:   6.219 ms/op
                 getUser·p0.999:  22.140 ms/op
                 getUser·p0.9999: 25.128 ms/op
                 getUser·p1.00:   25.657 ms/op

Iteration   3: 3.584 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.993 ms/op
                 getUser·p0.50:   3.453 ms/op
                 getUser·p0.90:   4.022 ms/op
                 getUser·p0.95:   4.571 ms/op
                 getUser·p0.99:   7.037 ms/op
                 getUser·p0.999:  22.708 ms/op
                 getUser·p0.9999: 28.152 ms/op
                 getUser·p1.00:   29.229 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 271028
  mean =      3.541 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4916 
    [ 2.500,  5.000) = 255771 
    [ 5.000,  7.500) = 8634 
    [ 7.500, 10.000) = 1177 
    [10.000, 12.500) = 145 
    [12.500, 15.000) = 72 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 130 
    [25.000, 27.500) = 90 

  Percentiles, ms/op:
      p(0.0000) =      1.157 ms/op
     p(50.0000) =      3.404 ms/op
     p(90.0000) =      3.924 ms/op
     p(95.0000) =      4.424 ms/op
     p(99.0000) =      6.799 ms/op
     p(99.9000) =     21.660 ms/op
     p(99.9900) =     27.122 ms/op
     p(99.9990) =     28.926 ms/op
     p(99.9999) =     29.753 ms/op
    p(100.0000) =     29.753 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 11.124 ±(99.9%) 0.162 ms/op
# Warmup Iteration   2: 4.783 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.158 ±(99.9%) 0.016 ms/op
Iteration   1: 4.155 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.468 ms/op
                 listUser·p0.50:   3.998 ms/op
                 listUser·p0.90:   4.653 ms/op
                 listUser·p0.95:   4.964 ms/op
                 listUser·p0.99:   7.782 ms/op
                 listUser·p0.999:  21.922 ms/op
                 listUser·p0.9999: 25.468 ms/op
                 listUser·p1.00:   27.066 ms/op

Iteration   2: 4.021 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.367 ms/op
                 listUser·p0.50:   3.908 ms/op
                 listUser·p0.90:   4.284 ms/op
                 listUser·p0.95:   4.588 ms/op
                 listUser·p0.99:   8.438 ms/op
                 listUser·p0.999:  15.587 ms/op
                 listUser·p0.9999: 17.008 ms/op
                 listUser·p1.00:   18.317 ms/op

Iteration   3: 4.038 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.023 ms/op
                 listUser·p0.50:   3.875 ms/op
                 listUser·p0.90:   4.391 ms/op
                 listUser·p0.95:   4.620 ms/op
                 listUser·p0.99:   7.864 ms/op
                 listUser·p0.999:  15.037 ms/op
                 listUser·p0.9999: 19.956 ms/op
                 listUser·p1.00:   20.054 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 235856
  mean =      4.070 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27 
    [ 2.500,  5.000) = 226658 
    [ 5.000,  7.500) = 6147 
    [ 7.500, 10.000) = 2034 
    [10.000, 12.500) = 494 
    [12.500, 15.000) = 157 
    [15.000, 17.500) = 158 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 61 
    [22.500, 25.000) = 46 
    [25.000, 27.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      1.468 ms/op
     p(50.0000) =      3.940 ms/op
     p(90.0000) =      4.456 ms/op
     p(95.0000) =      4.792 ms/op
     p(99.0000) =      8.053 ms/op
     p(99.9000) =     16.550 ms/op
     p(99.9900) =     24.557 ms/op
     p(99.9990) =     26.804 ms/op
     p(99.9999) =     27.066 ms/op
    p(100.0000) =     27.066 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.048 ± 4.262  ops/ms
ClientPb.existUser                       thrpt       3   9.888 ± 1.704  ops/ms
ClientPb.getUser                         thrpt       3   9.285 ± 3.947  ops/ms
ClientPb.listUser                        thrpt       3   7.780 ± 1.351  ops/ms
ClientPb.createUser                       avgt       3   3.519 ± 2.030   ms/op
ClientPb.existUser                        avgt       3   3.379 ± 0.562   ms/op
ClientPb.getUser                          avgt       3   3.451 ± 1.292   ms/op
ClientPb.listUser                         avgt       3   4.058 ± 0.306   ms/op
ClientPb.createUser                     sample  274938   3.489 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.415           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.371           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.924           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.284           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.119           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.089           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.903           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.394           ms/op
ClientPb.existUser                      sample  284391   3.371 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.608           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.293           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.654           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.994           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.947           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.430           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.254           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.130           ms/op
ClientPb.getUser                        sample  271028   3.541 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.157           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.404           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.924           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.424           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.799           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.660           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.122           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.753           ms/op
ClientPb.listUser                       sample  235856   4.070 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.468           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.940           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.456           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.792           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.053           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.550           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.557           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.066           ms/op
