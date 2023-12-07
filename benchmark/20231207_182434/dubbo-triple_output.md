# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.922 ops/ms
# Warmup Iteration   2: 11.893 ops/ms
# Warmup Iteration   3: 12.025 ops/ms
Iteration   1: 12.416 ops/ms
Iteration   2: 12.416 ops/ms
Iteration   3: 12.379 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.404 ±(99.9%) 0.394 ops/ms [Average]
  (min, avg, max) = (12.379, 12.404, 12.416), stdev = 0.022
  CI (99.9%): [12.009, 12.798] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 8.225 ops/ms
# Warmup Iteration   2: 12.987 ops/ms
# Warmup Iteration   3: 13.033 ops/ms
Iteration   1: 12.957 ops/ms
Iteration   2: 12.928 ops/ms
Iteration   3: 12.862 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.916 ±(99.9%) 0.888 ops/ms [Average]
  (min, avg, max) = (12.862, 12.916, 12.957), stdev = 0.049
  CI (99.9%): [12.028, 13.803] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.541 ops/ms
# Warmup Iteration   2: 11.876 ops/ms
# Warmup Iteration   3: 12.474 ops/ms
Iteration   1: 12.553 ops/ms
Iteration   2: 12.587 ops/ms
Iteration   3: 12.540 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.560 ±(99.9%) 0.443 ops/ms [Average]
  (min, avg, max) = (12.540, 12.560, 12.587), stdev = 0.024
  CI (99.9%): [12.117, 13.003] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.745 ops/ms
# Warmup Iteration   2: 10.241 ops/ms
# Warmup Iteration   3: 10.417 ops/ms
Iteration   1: 10.464 ops/ms
Iteration   2: 10.600 ops/ms
Iteration   3: 10.515 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.526 ±(99.9%) 1.255 ops/ms [Average]
  (min, avg, max) = (10.464, 10.526, 10.600), stdev = 0.069
  CI (99.9%): [9.271, 11.781] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.163 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 2.615 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.568 ±(99.9%) 0.004 ms/op
Iteration   1: 2.592 ±(99.9%) 0.003 ms/op
Iteration   2: 2.557 ±(99.9%) 0.004 ms/op
Iteration   3: 2.573 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.574 ±(99.9%) 0.324 ms/op [Average]
  (min, avg, max) = (2.557, 2.574, 2.592), stdev = 0.018
  CI (99.9%): [2.249, 2.898] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.767 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.474 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.500 ±(99.9%) 0.005 ms/op
Iteration   1: 2.469 ±(99.9%) 0.004 ms/op
Iteration   2: 2.434 ±(99.9%) 0.004 ms/op
Iteration   3: 2.414 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.439 ±(99.9%) 0.502 ms/op [Average]
  (min, avg, max) = (2.414, 2.439, 2.469), stdev = 0.027
  CI (99.9%): [1.937, 2.940] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 3.984 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.576 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.570 ±(99.9%) 0.004 ms/op
Iteration   1: 2.522 ±(99.9%) 0.005 ms/op
Iteration   2: 2.517 ±(99.9%) 0.003 ms/op
Iteration   3: 2.521 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.520 ±(99.9%) 0.044 ms/op [Average]
  (min, avg, max) = (2.517, 2.520, 2.522), stdev = 0.002
  CI (99.9%): [2.476, 2.565] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.722 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.069 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.051 ±(99.9%) 0.005 ms/op
Iteration   1: 3.016 ±(99.9%) 0.005 ms/op
Iteration   2: 3.026 ±(99.9%) 0.006 ms/op
Iteration   3: 3.020 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.021 ±(99.9%) 0.096 ms/op [Average]
  (min, avg, max) = (3.016, 3.021, 3.026), stdev = 0.005
  CI (99.9%): [2.925, 3.116] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.353 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 2.732 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.546 ±(99.9%) 0.006 ms/op
Iteration   1: 2.511 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.762 ms/op
                 createUser·p0.50:   2.601 ms/op
                 createUser·p0.90:   3.035 ms/op
                 createUser·p0.95:   3.162 ms/op
                 createUser·p0.99:   3.834 ms/op
                 createUser·p0.999:  10.780 ms/op
                 createUser·p0.9999: 17.441 ms/op
                 createUser·p1.00:   17.727 ms/op

Iteration   2: 2.551 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.098 ms/op
                 createUser·p0.50:   2.613 ms/op
                 createUser·p0.90:   3.101 ms/op
                 createUser·p0.95:   3.236 ms/op
                 createUser·p0.99:   3.944 ms/op
                 createUser·p0.999:  8.989 ms/op
                 createUser·p0.9999: 16.342 ms/op
                 createUser·p1.00:   16.646 ms/op

Iteration   3: 2.564 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.921 ms/op
                 createUser·p0.50:   2.626 ms/op
                 createUser·p0.90:   3.121 ms/op
                 createUser·p0.95:   3.269 ms/op
                 createUser·p0.99:   4.116 ms/op
                 createUser·p0.999:  8.178 ms/op
                 createUser·p0.9999: 10.174 ms/op
                 createUser·p1.00:   11.076 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 377363
  mean =      2.542 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 51 
    [ 1.250,  2.500) = 178612 
    [ 2.500,  3.750) = 193279 
    [ 3.750,  5.000) = 4263 
    [ 5.000,  6.250) = 583 
    [ 6.250,  7.500) = 126 
    [ 7.500,  8.750) = 91 
    [ 8.750, 10.000) = 124 
    [10.000, 11.250) = 86 
    [11.250, 12.500) = 20 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 15 
    [15.000, 16.250) = 40 
    [16.250, 17.500) = 65 
    [17.500, 18.750) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.762 ms/op
     p(50.0000) =      2.613 ms/op
     p(90.0000) =      3.088 ms/op
     p(95.0000) =      3.224 ms/op
     p(99.0000) =      3.977 ms/op
     p(99.9000) =      8.612 ms/op
     p(99.9900) =     16.676 ms/op
     p(99.9990) =     17.571 ms/op
     p(99.9999) =     17.727 ms/op
    p(100.0000) =     17.727 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.711 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 2.485 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.462 ±(99.9%) 0.006 ms/op
Iteration   1: 2.428 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.435 ms/op
                 existUser·p0.50:   2.449 ms/op
                 existUser·p0.90:   2.957 ms/op
                 existUser·p0.95:   3.080 ms/op
                 existUser·p0.99:   3.625 ms/op
                 existUser·p0.999:  6.365 ms/op
                 existUser·p0.9999: 14.658 ms/op
                 existUser·p1.00:   14.811 ms/op

Iteration   2: 2.480 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.722 ms/op
                 existUser·p0.50:   2.515 ms/op
                 existUser·p0.90:   3.023 ms/op
                 existUser·p0.95:   3.146 ms/op
                 existUser·p0.99:   3.838 ms/op
                 existUser·p0.999:  8.601 ms/op
                 existUser·p0.9999: 14.238 ms/op
                 existUser·p1.00:   15.024 ms/op

Iteration   3: 2.449 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.440 ms/op
                 existUser·p0.50:   2.400 ms/op
                 existUser·p0.90:   3.088 ms/op
                 existUser·p0.95:   3.449 ms/op
                 existUser·p0.99:   4.612 ms/op
                 existUser·p0.999:  8.471 ms/op
                 existUser·p0.9999: 14.875 ms/op
                 existUser·p1.00:   15.679 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 391097
  mean =      2.452 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 217 
    [ 1.250,  2.500) = 205202 
    [ 2.500,  3.750) = 179045 
    [ 3.750,  5.000) = 5364 
    [ 5.000,  6.250) = 700 
    [ 6.250,  7.500) = 134 
    [ 7.500,  8.750) = 68 
    [ 8.750, 10.000) = 89 
    [10.000, 11.250) = 56 
    [11.250, 12.500) = 64 
    [12.500, 13.750) = 62 
    [13.750, 15.000) = 87 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.435 ms/op
     p(50.0000) =      2.437 ms/op
     p(90.0000) =      3.011 ms/op
     p(95.0000) =      3.191 ms/op
     p(99.0000) =      4.137 ms/op
     p(99.9000) =      8.471 ms/op
     p(99.9900) =     14.711 ms/op
     p(99.9990) =     15.172 ms/op
     p(99.9999) =     15.679 ms/op
    p(100.0000) =     15.679 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.065 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.570 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.514 ±(99.9%) 0.006 ms/op
Iteration   1: 2.490 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.708 ms/op
                 getUser·p0.50:   2.421 ms/op
                 getUser·p0.90:   3.138 ms/op
                 getUser·p0.95:   3.428 ms/op
                 getUser·p0.99:   4.448 ms/op
                 getUser·p0.999:  10.297 ms/op
                 getUser·p0.9999: 15.387 ms/op
                 getUser·p1.00:   15.909 ms/op

Iteration   2: 2.480 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.637 ms/op
                 getUser·p0.50:   2.421 ms/op
                 getUser·p0.90:   3.138 ms/op
                 getUser·p0.95:   3.408 ms/op
                 getUser·p0.99:   4.257 ms/op
                 getUser·p0.999:  6.448 ms/op
                 getUser·p0.9999: 12.685 ms/op
                 getUser·p1.00:   13.599 ms/op

Iteration   3: 2.530 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.553 ms/op
                 getUser·p0.50:   2.466 ms/op
                 getUser·p0.90:   3.207 ms/op
                 getUser·p0.95:   3.543 ms/op
                 getUser·p0.99:   4.481 ms/op
                 getUser·p0.999:  6.900 ms/op
                 getUser·p0.9999: 22.720 ms/op
                 getUser·p1.00:   24.347 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 383612
  mean =      2.500 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 203548 
    [ 2.500,  5.000) = 178369 
    [ 5.000,  7.500) = 1358 
    [ 7.500, 10.000) = 17 
    [10.000, 12.500) = 184 
    [12.500, 15.000) = 72 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.553 ms/op
     p(50.0000) =      2.437 ms/op
     p(90.0000) =      3.158 ms/op
     p(95.0000) =      3.457 ms/op
     p(99.0000) =      4.391 ms/op
     p(99.9000) =      7.046 ms/op
     p(99.9900) =     15.520 ms/op
     p(99.9990) =     23.849 ms/op
     p(99.9999) =     24.347 ms/op
    p(100.0000) =     24.347 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.869 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 2.981 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 2.982 ±(99.9%) 0.009 ms/op
Iteration   1: 2.934 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.958 ms/op
                 listUser·p0.50:   2.863 ms/op
                 listUser·p0.90:   3.903 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   5.415 ms/op
                 listUser·p0.999:  9.421 ms/op
                 listUser·p0.9999: 11.456 ms/op
                 listUser·p1.00:   16.941 ms/op

Iteration   2: 2.980 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.865 ms/op
                 listUser·p0.50:   2.920 ms/op
                 listUser·p0.90:   3.883 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   5.505 ms/op
                 listUser·p0.999:  11.200 ms/op
                 listUser·p0.9999: 14.002 ms/op
                 listUser·p1.00:   15.155 ms/op

Iteration   3: 3.004 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.894 ms/op
                 listUser·p0.50:   2.937 ms/op
                 listUser·p0.90:   3.912 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   5.669 ms/op
                 listUser·p0.999:  9.863 ms/op
                 listUser·p0.9999: 13.539 ms/op
                 listUser·p1.00:   14.991 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 322591
  mean =      2.973 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 247 
    [ 1.250,  2.500) = 103978 
    [ 2.500,  3.750) = 178284 
    [ 3.750,  5.000) = 33320 
    [ 5.000,  6.250) = 5274 
    [ 6.250,  7.500) = 649 
    [ 7.500,  8.750) = 249 
    [ 8.750, 10.000) = 242 
    [10.000, 11.250) = 172 
    [11.250, 12.500) = 98 
    [12.500, 13.750) = 54 
    [13.750, 15.000) = 22 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.865 ms/op
     p(50.0000) =      2.904 ms/op
     p(90.0000) =      3.899 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      5.530 ms/op
     p(99.9000) =     10.240 ms/op
     p(99.9900) =     13.660 ms/op
     p(99.9990) =     14.969 ms/op
     p(99.9999) =     16.941 ms/op
    p(100.0000) =     16.941 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.404 ± 0.394  ops/ms
ClientPb.existUser                       thrpt       3  12.916 ± 0.888  ops/ms
ClientPb.getUser                         thrpt       3  12.560 ± 0.443  ops/ms
ClientPb.listUser                        thrpt       3  10.526 ± 1.255  ops/ms
ClientPb.createUser                       avgt       3   2.574 ± 0.324   ms/op
ClientPb.existUser                        avgt       3   2.439 ± 0.502   ms/op
ClientPb.getUser                          avgt       3   2.520 ± 0.044   ms/op
ClientPb.listUser                         avgt       3   3.021 ± 0.096   ms/op
ClientPb.createUser                     sample  377363   2.542 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.762           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.613           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.088           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.224           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.977           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.612           ms/op
ClientPb.createUser:createUser·p0.9999  sample          16.676           ms/op
ClientPb.createUser:createUser·p1.00    sample          17.727           ms/op
ClientPb.existUser                      sample  391097   2.452 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.435           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.437           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.011           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.191           ms/op
ClientPb.existUser:existUser·p0.99      sample           4.137           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.471           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.711           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.679           ms/op
ClientPb.getUser                        sample  383612   2.500 ± 0.004   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.553           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.437           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.158           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.457           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.391           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.046           ms/op
ClientPb.getUser:getUser·p0.9999        sample          15.520           ms/op
ClientPb.getUser:getUser·p1.00          sample          24.347           ms/op
ClientPb.listUser                       sample  322591   2.973 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.865           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.904           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.899           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.383           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.530           ms/op
ClientPb.listUser:listUser·p0.999       sample          10.240           ms/op
ClientPb.listUser:listUser·p0.9999      sample          13.660           ms/op
ClientPb.listUser:listUser·p1.00        sample          16.941           ms/op
