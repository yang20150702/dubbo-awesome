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
# Warmup Iteration   1: 5.168 ops/ms
# Warmup Iteration   2: 11.982 ops/ms
# Warmup Iteration   3: 12.301 ops/ms
Iteration   1: 12.431 ops/ms
Iteration   2: 12.570 ops/ms
Iteration   3: 12.600 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.534 ±(99.9%) 1.644 ops/ms [Average]
  (min, avg, max) = (12.431, 12.534, 12.600), stdev = 0.090
  CI (99.9%): [10.890, 14.178] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:53
# Fork: 1 of 1
# Warmup Iteration   1: 8.396 ops/ms
# Warmup Iteration   2: 12.804 ops/ms
# Warmup Iteration   3: 12.920 ops/ms
Iteration   1: 12.895 ops/ms
Iteration   2: 12.938 ops/ms
Iteration   3: 12.903 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.912 ±(99.9%) 0.421 ops/ms [Average]
  (min, avg, max) = (12.895, 12.912, 12.938), stdev = 0.023
  CI (99.9%): [12.491, 13.334] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.741 ops/ms
# Warmup Iteration   2: 12.552 ops/ms
# Warmup Iteration   3: 12.791 ops/ms
Iteration   1: 12.843 ops/ms
Iteration   2: 12.582 ops/ms
Iteration   3: 12.774 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.733 ±(99.9%) 2.459 ops/ms [Average]
  (min, avg, max) = (12.582, 12.733, 12.843), stdev = 0.135
  CI (99.9%): [10.274, 15.192] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.818 ops/ms
# Warmup Iteration   2: 10.357 ops/ms
# Warmup Iteration   3: 10.443 ops/ms
Iteration   1: 10.591 ops/ms
Iteration   2: 10.518 ops/ms
Iteration   3: 10.529 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.546 ±(99.9%) 0.717 ops/ms [Average]
  (min, avg, max) = (10.518, 10.546, 10.591), stdev = 0.039
  CI (99.9%): [9.829, 11.263] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.091 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.625 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.526 ±(99.9%) 0.005 ms/op
Iteration   1: 2.567 ±(99.9%) 0.004 ms/op
Iteration   2: 2.543 ±(99.9%) 0.004 ms/op
Iteration   3: 2.551 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.554 ±(99.9%) 0.219 ms/op [Average]
  (min, avg, max) = (2.543, 2.554, 2.567), stdev = 0.012
  CI (99.9%): [2.334, 2.773] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:33
# Fork: 1 of 1
# Warmup Iteration   1: 3.965 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.490 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.473 ±(99.9%) 0.005 ms/op
Iteration   1: 2.462 ±(99.9%) 0.004 ms/op
Iteration   2: 2.450 ±(99.9%) 0.004 ms/op
Iteration   3: 2.440 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.451 ±(99.9%) 0.201 ms/op [Average]
  (min, avg, max) = (2.440, 2.451, 2.462), stdev = 0.011
  CI (99.9%): [2.250, 2.652] (assumes normal distribution)


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
# Warmup Iteration   1: 3.920 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.525 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.464 ±(99.9%) 0.004 ms/op
Iteration   1: 2.463 ±(99.9%) 0.004 ms/op
Iteration   2: 2.435 ±(99.9%) 0.004 ms/op
Iteration   3: 2.465 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.454 ±(99.9%) 0.305 ms/op [Average]
  (min, avg, max) = (2.435, 2.454, 2.465), stdev = 0.017
  CI (99.9%): [2.150, 2.759] (assumes normal distribution)


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
# Warmup Iteration   1: 4.618 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.029 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.010 ±(99.9%) 0.005 ms/op
Iteration   1: 3.018 ±(99.9%) 0.006 ms/op
Iteration   2: 3.027 ±(99.9%) 0.005 ms/op
Iteration   3: 2.995 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.013 ±(99.9%) 0.299 ms/op [Average]
  (min, avg, max) = (2.995, 3.013, 3.027), stdev = 0.016
  CI (99.9%): [2.714, 3.312] (assumes normal distribution)


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
# Warmup Iteration   1: 4.127 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.655 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.499 ±(99.9%) 0.005 ms/op
Iteration   1: 2.494 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.004 ms/op
                 createUser·p0.50:   2.585 ms/op
                 createUser·p0.90:   3.019 ms/op
                 createUser·p0.95:   3.121 ms/op
                 createUser·p0.99:   3.715 ms/op
                 createUser·p0.999:  9.876 ms/op
                 createUser·p0.9999: 21.540 ms/op
                 createUser·p1.00:   23.560 ms/op

Iteration   2: 2.496 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.118 ms/op
                 createUser·p0.50:   2.560 ms/op
                 createUser·p0.90:   3.035 ms/op
                 createUser·p0.95:   3.150 ms/op
                 createUser·p0.99:   3.822 ms/op
                 createUser·p0.999:  8.897 ms/op
                 createUser·p0.9999: 11.420 ms/op
                 createUser·p1.00:   12.681 ms/op

Iteration   3: 2.541 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.965 ms/op
                 createUser·p0.50:   2.585 ms/op
                 createUser·p0.90:   3.088 ms/op
                 createUser·p0.95:   3.277 ms/op
                 createUser·p0.99:   4.407 ms/op
                 createUser·p0.999:  8.913 ms/op
                 createUser·p0.9999: 11.108 ms/op
                 createUser·p1.00:   15.106 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 381991
  mean =      2.510 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 184391 
    [ 2.500,  5.000) = 196598 
    [ 5.000,  7.500) = 558 
    [ 7.500, 10.000) = 198 
    [10.000, 12.500) = 181 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.965 ms/op
     p(50.0000) =      2.576 ms/op
     p(90.0000) =      3.043 ms/op
     p(95.0000) =      3.174 ms/op
     p(99.0000) =      3.965 ms/op
     p(99.9000) =      8.897 ms/op
     p(99.9900) =     13.091 ms/op
     p(99.9990) =     23.235 ms/op
     p(99.9999) =     23.560 ms/op
    p(100.0000) =     23.560 ms/op


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
# Warmup Iteration   1: 3.648 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.451 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.427 ±(99.9%) 0.005 ms/op
Iteration   1: 2.436 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.861 ms/op
                 existUser·p0.50:   2.441 ms/op
                 existUser·p0.90:   2.982 ms/op
                 existUser·p0.95:   3.101 ms/op
                 existUser·p0.99:   3.523 ms/op
                 existUser·p0.999:  5.345 ms/op
                 existUser·p0.9999: 13.695 ms/op
                 existUser·p1.00:   14.270 ms/op

Iteration   2: 2.445 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.859 ms/op
                 existUser·p0.50:   2.486 ms/op
                 existUser·p0.90:   2.990 ms/op
                 existUser·p0.95:   3.113 ms/op
                 existUser·p0.99:   3.645 ms/op
                 existUser·p0.999:  7.957 ms/op
                 existUser·p0.9999: 13.974 ms/op
                 existUser·p1.00:   14.516 ms/op

Iteration   3: 2.496 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.968 ms/op
                 existUser·p0.50:   2.531 ms/op
                 existUser·p0.90:   3.047 ms/op
                 existUser·p0.95:   3.215 ms/op
                 existUser·p0.99:   4.432 ms/op
                 existUser·p0.999:  7.476 ms/op
                 existUser·p0.9999: 12.098 ms/op
                 existUser·p1.00:   12.452 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 390116
  mean =      2.458 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 73 
    [ 1.250,  2.500) = 196517 
    [ 2.500,  3.750) = 189113 
    [ 3.750,  5.000) = 3376 
    [ 5.000,  6.250) = 663 
    [ 6.250,  7.500) = 18 
    [ 7.500,  8.750) = 27 
    [ 8.750, 10.000) = 44 
    [10.000, 11.250) = 88 
    [11.250, 12.500) = 99 
    [12.500, 13.750) = 69 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.859 ms/op
     p(50.0000) =      2.486 ms/op
     p(90.0000) =      3.002 ms/op
     p(95.0000) =      3.138 ms/op
     p(99.0000) =      3.834 ms/op
     p(99.9000) =      6.094 ms/op
     p(99.9900) =     13.516 ms/op
     p(99.9990) =     14.423 ms/op
     p(99.9999) =     14.516 ms/op
    p(100.0000) =     14.516 ms/op


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
# Warmup Iteration   1: 3.848 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.558 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.524 ±(99.9%) 0.005 ms/op
Iteration   1: 2.514 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.007 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   3.064 ms/op
                 getUser·p0.95:   3.211 ms/op
                 getUser·p0.99:   3.949 ms/op
                 getUser·p0.999:  11.249 ms/op
                 getUser·p0.9999: 14.161 ms/op
                 getUser·p1.00:   15.499 ms/op

Iteration   2: 2.541 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.021 ms/op
                 getUser·p0.50:   2.576 ms/op
                 getUser·p0.90:   3.088 ms/op
                 getUser·p0.95:   3.248 ms/op
                 getUser·p0.99:   4.547 ms/op
                 getUser·p0.999:  7.874 ms/op
                 getUser·p0.9999: 12.819 ms/op
                 getUser·p1.00:   12.960 ms/op

Iteration   3: 2.521 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.905 ms/op
                 getUser·p0.50:   2.531 ms/op
                 getUser·p0.90:   3.076 ms/op
                 getUser·p0.95:   3.199 ms/op
                 getUser·p0.99:   3.797 ms/op
                 getUser·p0.999:  9.496 ms/op
                 getUser·p0.9999: 11.204 ms/op
                 getUser·p1.00:   12.042 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 379848
  mean =      2.525 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 61 
    [ 1.250,  2.500) = 186451 
    [ 2.500,  3.750) = 187505 
    [ 3.750,  5.000) = 4542 
    [ 5.000,  6.250) = 823 
    [ 6.250,  7.500) = 68 
    [ 7.500,  8.750) = 39 
    [ 8.750, 10.000) = 41 
    [10.000, 11.250) = 131 
    [11.250, 12.500) = 87 
    [12.500, 13.750) = 74 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.905 ms/op
     p(50.0000) =      2.540 ms/op
     p(90.0000) =      3.076 ms/op
     p(95.0000) =      3.219 ms/op
     p(99.0000) =      4.076 ms/op
     p(99.9000) =      7.943 ms/op
     p(99.9900) =     13.599 ms/op
     p(99.9990) =     15.018 ms/op
     p(99.9999) =     15.499 ms/op
    p(100.0000) =     15.499 ms/op


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
# Warmup Iteration   1: 4.674 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.106 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.026 ±(99.9%) 0.009 ms/op
Iteration   1: 2.974 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.858 ms/op
                 listUser·p0.50:   2.920 ms/op
                 listUser·p0.90:   3.842 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   5.456 ms/op
                 listUser·p0.999:  9.117 ms/op
                 listUser·p0.9999: 10.994 ms/op
                 listUser·p1.00:   11.731 ms/op

Iteration   2: 3.013 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.811 ms/op
                 listUser·p0.50:   2.953 ms/op
                 listUser·p0.90:   3.903 ms/op
                 listUser·p0.95:   4.440 ms/op
                 listUser·p0.99:   5.620 ms/op
                 listUser·p0.999:  9.224 ms/op
                 listUser·p0.9999: 11.190 ms/op
                 listUser·p1.00:   11.616 ms/op

Iteration   3: 2.997 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.919 ms/op
                 listUser·p0.50:   2.937 ms/op
                 listUser·p0.90:   3.879 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.439 ms/op
                 listUser·p0.999:  9.650 ms/op
                 listUser·p0.9999: 11.343 ms/op
                 listUser·p1.00:   11.682 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 320323
  mean =      2.994 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 110 
    [ 1.250,  2.500) = 95472 
    [ 2.500,  3.750) = 186175 
    [ 3.750,  5.000) = 31677 
    [ 5.000,  6.250) = 5798 
    [ 6.250,  7.500) = 452 
    [ 7.500,  8.750) = 205 
    [ 8.750, 10.000) = 253 
    [10.000, 11.250) = 155 
    [11.250, 12.500) = 26 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.811 ms/op
     p(50.0000) =      2.937 ms/op
     p(90.0000) =      3.871 ms/op
     p(95.0000) =      4.366 ms/op
     p(99.0000) =      5.505 ms/op
     p(99.9000) =      9.257 ms/op
     p(99.9900) =     11.190 ms/op
     p(99.9990) =     11.678 ms/op
     p(99.9999) =     11.731 ms/op
    p(100.0000) =     11.731 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.534 ± 1.644  ops/ms
ClientPb.existUser                       thrpt       3  12.912 ± 0.421  ops/ms
ClientPb.getUser                         thrpt       3  12.733 ± 2.459  ops/ms
ClientPb.listUser                        thrpt       3  10.546 ± 0.717  ops/ms
ClientPb.createUser                       avgt       3   2.554 ± 0.219   ms/op
ClientPb.existUser                        avgt       3   2.451 ± 0.201   ms/op
ClientPb.getUser                          avgt       3   2.454 ± 0.305   ms/op
ClientPb.listUser                         avgt       3   3.013 ± 0.299   ms/op
ClientPb.createUser                     sample  381991   2.510 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.965           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.576           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.043           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.174           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.965           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.897           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.091           ms/op
ClientPb.createUser:createUser·p1.00    sample          23.560           ms/op
ClientPb.existUser                      sample  390116   2.458 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.859           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.486           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.002           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.138           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.834           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.094           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.516           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.516           ms/op
ClientPb.getUser                        sample  379848   2.525 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.905           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.540           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.076           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.219           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.076           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.943           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.599           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.499           ms/op
ClientPb.listUser                       sample  320323   2.994 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.811           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.937           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.871           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.366           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.505           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.257           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.190           ms/op
ClientPb.listUser:listUser·p1.00        sample          11.731           ms/op
