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
# Warmup Iteration   1: 4.817 ops/ms
# Warmup Iteration   2: 12.066 ops/ms
# Warmup Iteration   3: 12.362 ops/ms
Iteration   1: 12.580 ops/ms
Iteration   2: 12.642 ops/ms
Iteration   3: 12.686 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.636 ±(99.9%) 0.977 ops/ms [Average]
  (min, avg, max) = (12.580, 12.636, 12.686), stdev = 0.054
  CI (99.9%): [11.659, 13.613] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.061 ops/ms
# Warmup Iteration   2: 13.187 ops/ms
# Warmup Iteration   3: 13.111 ops/ms
Iteration   1: 13.162 ops/ms
Iteration   2: 13.300 ops/ms
Iteration   3: 13.246 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.236 ±(99.9%) 1.272 ops/ms [Average]
  (min, avg, max) = (13.162, 13.236, 13.300), stdev = 0.070
  CI (99.9%): [11.964, 14.508] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.046 ops/ms
# Warmup Iteration   2: 12.578 ops/ms
# Warmup Iteration   3: 12.617 ops/ms
Iteration   1: 12.875 ops/ms
Iteration   2: 12.706 ops/ms
Iteration   3: 12.698 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.760 ±(99.9%) 1.824 ops/ms [Average]
  (min, avg, max) = (12.698, 12.760, 12.875), stdev = 0.100
  CI (99.9%): [10.936, 14.584] (assumes normal distribution)


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
# Warmup Iteration   1: 6.447 ops/ms
# Warmup Iteration   2: 10.349 ops/ms
# Warmup Iteration   3: 10.442 ops/ms
Iteration   1: 10.565 ops/ms
Iteration   2: 10.568 ops/ms
Iteration   3: 10.606 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.580 ±(99.9%) 0.414 ops/ms [Average]
  (min, avg, max) = (10.565, 10.580, 10.606), stdev = 0.023
  CI (99.9%): [10.165, 10.994] (assumes normal distribution)


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
# Warmup Iteration   1: 4.247 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.632 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.545 ±(99.9%) 0.003 ms/op
Iteration   1: 2.565 ±(99.9%) 0.005 ms/op
Iteration   2: 2.522 ±(99.9%) 0.004 ms/op
Iteration   3: 2.523 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.537 ±(99.9%) 0.444 ms/op [Average]
  (min, avg, max) = (2.522, 2.537, 2.565), stdev = 0.024
  CI (99.9%): [2.092, 2.981] (assumes normal distribution)


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
# Warmup Iteration   1: 3.849 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.448 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.449 ±(99.9%) 0.004 ms/op
Iteration   1: 2.456 ±(99.9%) 0.004 ms/op
Iteration   2: 2.462 ±(99.9%) 0.004 ms/op
Iteration   3: 2.449 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.455 ±(99.9%) 0.119 ms/op [Average]
  (min, avg, max) = (2.449, 2.455, 2.462), stdev = 0.007
  CI (99.9%): [2.336, 2.575] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.958 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.537 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.504 ±(99.9%) 0.003 ms/op
Iteration   1: 2.472 ±(99.9%) 0.003 ms/op
Iteration   2: 2.481 ±(99.9%) 0.004 ms/op
Iteration   3: 2.474 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.476 ±(99.9%) 0.090 ms/op [Average]
  (min, avg, max) = (2.472, 2.476, 2.481), stdev = 0.005
  CI (99.9%): [2.385, 2.566] (assumes normal distribution)


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
# Warmup Iteration   1: 4.820 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.084 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.007 ±(99.9%) 0.005 ms/op
Iteration   1: 3.005 ±(99.9%) 0.005 ms/op
Iteration   2: 3.026 ±(99.9%) 0.006 ms/op
Iteration   3: 3.024 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.018 ±(99.9%) 0.210 ms/op [Average]
  (min, avg, max) = (3.005, 3.018, 3.026), stdev = 0.011
  CI (99.9%): [2.809, 3.228] (assumes normal distribution)


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
# Warmup Iteration   1: 4.229 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.624 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.510 ±(99.9%) 0.006 ms/op
Iteration   1: 2.510 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.963 ms/op
                 createUser·p0.50:   2.548 ms/op
                 createUser·p0.90:   3.064 ms/op
                 createUser·p0.95:   3.215 ms/op
                 createUser·p0.99:   3.899 ms/op
                 createUser·p0.999:  11.547 ms/op
                 createUser·p0.9999: 14.549 ms/op
                 createUser·p1.00:   15.745 ms/op

Iteration   2: 2.499 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.918 ms/op
                 createUser·p0.50:   2.564 ms/op
                 createUser·p0.90:   3.027 ms/op
                 createUser·p0.95:   3.154 ms/op
                 createUser·p0.99:   3.826 ms/op
                 createUser·p0.999:  10.158 ms/op
                 createUser·p0.9999: 18.711 ms/op
                 createUser·p1.00:   19.005 ms/op

Iteration   3: 2.535 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.471 ms/op
                 createUser·p0.50:   2.568 ms/op
                 createUser·p0.90:   3.097 ms/op
                 createUser·p0.95:   3.277 ms/op
                 createUser·p0.99:   4.211 ms/op
                 createUser·p0.999:  8.967 ms/op
                 createUser·p0.9999: 11.377 ms/op
                 createUser·p1.00:   11.747 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 381543
  mean =      2.514 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 89 
    [ 1.250,  2.500) = 183604 
    [ 2.500,  3.750) = 192295 
    [ 3.750,  5.000) = 4316 
    [ 5.000,  6.250) = 749 
    [ 6.250,  7.500) = 25 
    [ 7.500,  8.750) = 51 
    [ 8.750, 10.000) = 76 
    [10.000, 11.250) = 142 
    [11.250, 12.500) = 81 
    [12.500, 13.750) = 58 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.471 ms/op
     p(50.0000) =      2.560 ms/op
     p(90.0000) =      3.060 ms/op
     p(95.0000) =      3.211 ms/op
     p(99.0000) =      4.002 ms/op
     p(99.9000) =      9.437 ms/op
     p(99.9900) =     14.672 ms/op
     p(99.9990) =     18.952 ms/op
     p(99.9999) =     19.005 ms/op
    p(100.0000) =     19.005 ms/op


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
# Warmup Iteration   1: 3.729 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.458 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.404 ±(99.9%) 0.005 ms/op
Iteration   1: 2.400 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.971 ms/op
                 existUser·p0.50:   2.454 ms/op
                 existUser·p0.90:   2.929 ms/op
                 existUser·p0.95:   3.035 ms/op
                 existUser·p0.99:   3.510 ms/op
                 existUser·p0.999:  5.804 ms/op
                 existUser·p0.9999: 16.302 ms/op
                 existUser·p1.00:   17.170 ms/op

Iteration   2: 2.434 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.892 ms/op
                 existUser·p0.50:   2.511 ms/op
                 existUser·p0.90:   2.953 ms/op
                 existUser·p0.95:   3.068 ms/op
                 existUser·p0.99:   3.686 ms/op
                 existUser·p0.999:  6.961 ms/op
                 existUser·p0.9999: 13.777 ms/op
                 existUser·p1.00:   14.090 ms/op

Iteration   3: 2.426 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.021 ms/op
                 existUser·p0.50:   2.454 ms/op
                 existUser·p0.90:   2.961 ms/op
                 existUser·p0.95:   3.080 ms/op
                 existUser·p0.99:   3.660 ms/op
                 existUser·p0.999:  7.727 ms/op
                 existUser·p0.9999: 15.974 ms/op
                 existUser·p1.00:   17.236 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 396319
  mean =      2.420 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 56 
    [ 1.250,  2.500) = 201580 
    [ 2.500,  3.750) = 191465 
    [ 3.750,  5.000) = 2461 
    [ 5.000,  6.250) = 307 
    [ 6.250,  7.500) = 60 
    [ 7.500,  8.750) = 25 
    [ 8.750, 10.000) = 80 
    [10.000, 11.250) = 58 
    [11.250, 12.500) = 59 
    [12.500, 13.750) = 50 
    [13.750, 15.000) = 39 
    [15.000, 16.250) = 50 
    [16.250, 17.500) = 29 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.892 ms/op
     p(50.0000) =      2.470 ms/op
     p(90.0000) =      2.949 ms/op
     p(95.0000) =      3.060 ms/op
     p(99.0000) =      3.621 ms/op
     p(99.9000) =      6.923 ms/op
     p(99.9900) =     16.171 ms/op
     p(99.9990) =     17.139 ms/op
     p(99.9999) =     17.236 ms/op
    p(100.0000) =     17.236 ms/op


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
# Warmup Iteration   1: 3.904 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.550 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.481 ±(99.9%) 0.005 ms/op
Iteration   1: 2.457 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.024 ms/op
                 getUser·p0.50:   2.478 ms/op
                 getUser·p0.90:   2.994 ms/op
                 getUser·p0.95:   3.101 ms/op
                 getUser·p0.99:   3.564 ms/op
                 getUser·p0.999:  6.125 ms/op
                 getUser·p0.9999: 13.107 ms/op
                 getUser·p1.00:   13.795 ms/op

Iteration   2: 2.524 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.934 ms/op
                 getUser·p0.50:   2.527 ms/op
                 getUser·p0.90:   3.088 ms/op
                 getUser·p0.95:   3.273 ms/op
                 getUser·p0.99:   4.334 ms/op
                 getUser·p0.999:  9.672 ms/op
                 getUser·p0.9999: 11.780 ms/op
                 getUser·p1.00:   12.780 ms/op

Iteration   3: 2.476 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.907 ms/op
                 getUser·p0.50:   2.499 ms/op
                 getUser·p0.90:   3.027 ms/op
                 getUser·p0.95:   3.150 ms/op
                 getUser·p0.99:   3.695 ms/op
                 getUser·p0.999:  5.568 ms/op
                 getUser·p0.9999: 11.673 ms/op
                 getUser·p1.00:   12.272 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 385936
  mean =      2.485 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 80 
    [ 1.250,  2.500) = 192622 
    [ 2.500,  3.750) = 188414 
    [ 3.750,  5.000) = 3984 
    [ 5.000,  6.250) = 447 
    [ 6.250,  7.500) = 5 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 82 
    [10.000, 11.250) = 145 
    [11.250, 12.500) = 104 
    [12.500, 13.750) = 49 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.907 ms/op
     p(50.0000) =      2.503 ms/op
     p(90.0000) =      3.035 ms/op
     p(95.0000) =      3.170 ms/op
     p(99.0000) =      3.879 ms/op
     p(99.9000) =      7.153 ms/op
     p(99.9900) =     12.599 ms/op
     p(99.9990) =     13.353 ms/op
     p(99.9999) =     13.795 ms/op
    p(100.0000) =     13.795 ms/op


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
# Warmup Iteration   1: 4.670 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.067 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.034 ±(99.9%) 0.009 ms/op
Iteration   1: 3.042 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.865 ms/op
                 listUser·p0.50:   2.974 ms/op
                 listUser·p0.90:   3.924 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.702 ms/op
                 listUser·p0.999:  9.403 ms/op
                 listUser·p0.9999: 11.346 ms/op
                 listUser·p1.00:   13.713 ms/op

Iteration   2: 3.037 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.850 ms/op
                 listUser·p0.50:   2.974 ms/op
                 listUser·p0.90:   3.899 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.579 ms/op
                 listUser·p0.999:  9.929 ms/op
                 listUser·p0.9999: 12.255 ms/op
                 listUser·p1.00:   13.025 ms/op

Iteration   3: 3.026 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.911 ms/op
                 listUser·p0.50:   2.961 ms/op
                 listUser·p0.90:   3.903 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   5.644 ms/op
                 listUser·p0.999:  9.826 ms/op
                 listUser·p0.9999: 12.067 ms/op
                 listUser·p1.00:   12.845 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 316004
  mean =      3.035 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 139 
    [ 1.250,  2.500) = 85733 
    [ 2.500,  3.750) = 189914 
    [ 3.750,  5.000) = 32905 
    [ 5.000,  6.250) = 5837 
    [ 6.250,  7.500) = 818 
    [ 7.500,  8.750) = 178 
    [ 8.750, 10.000) = 223 
    [10.000, 11.250) = 195 
    [11.250, 12.500) = 37 
    [12.500, 13.750) = 25 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.850 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      3.908 ms/op
     p(95.0000) =      4.391 ms/op
     p(99.0000) =      5.636 ms/op
     p(99.9000) =      9.683 ms/op
     p(99.9900) =     11.970 ms/op
     p(99.9990) =     13.640 ms/op
     p(99.9999) =     13.713 ms/op
    p(100.0000) =     13.713 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.636 ± 0.977  ops/ms
ClientPb.existUser                       thrpt       3  13.236 ± 1.272  ops/ms
ClientPb.getUser                         thrpt       3  12.760 ± 1.824  ops/ms
ClientPb.listUser                        thrpt       3  10.580 ± 0.414  ops/ms
ClientPb.createUser                       avgt       3   2.537 ± 0.444   ms/op
ClientPb.existUser                        avgt       3   2.455 ± 0.119   ms/op
ClientPb.getUser                          avgt       3   2.476 ± 0.090   ms/op
ClientPb.listUser                         avgt       3   3.018 ± 0.210   ms/op
ClientPb.createUser                     sample  381543   2.514 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.471           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.560           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.060           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.211           ms/op
ClientPb.createUser:createUser·p0.99    sample           4.002           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.437           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.672           ms/op
ClientPb.createUser:createUser·p1.00    sample          19.005           ms/op
ClientPb.existUser                      sample  396319   2.420 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.892           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.470           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.949           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.060           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.621           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.923           ms/op
ClientPb.existUser:existUser·p0.9999    sample          16.171           ms/op
ClientPb.existUser:existUser·p1.00      sample          17.236           ms/op
ClientPb.getUser                        sample  385936   2.485 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.907           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.503           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.035           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.170           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.879           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.153           ms/op
ClientPb.getUser:getUser·p0.9999        sample          12.599           ms/op
ClientPb.getUser:getUser·p1.00          sample          13.795           ms/op
ClientPb.listUser                       sample  316004   3.035 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.850           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.970           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.908           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.391           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.636           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.683           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.970           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.713           ms/op
