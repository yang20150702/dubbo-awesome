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
# Warmup Iteration   1: 5.034 ops/ms
# Warmup Iteration   2: 12.377 ops/ms
# Warmup Iteration   3: 12.540 ops/ms
Iteration   1: 12.807 ops/ms
Iteration   2: 12.884 ops/ms
Iteration   3: 12.865 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.852 ±(99.9%) 0.734 ops/ms [Average]
  (min, avg, max) = (12.807, 12.852, 12.884), stdev = 0.040
  CI (99.9%): [12.118, 13.586] (assumes normal distribution)


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
# Warmup Iteration   1: 8.265 ops/ms
# Warmup Iteration   2: 13.320 ops/ms
# Warmup Iteration   3: 13.231 ops/ms
Iteration   1: 13.324 ops/ms
Iteration   2: 13.381 ops/ms
Iteration   3: 13.300 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.335 ±(99.9%) 0.757 ops/ms [Average]
  (min, avg, max) = (13.300, 13.335, 13.381), stdev = 0.041
  CI (99.9%): [12.578, 14.092] (assumes normal distribution)


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
# Warmup Iteration   1: 7.834 ops/ms
# Warmup Iteration   2: 12.895 ops/ms
# Warmup Iteration   3: 13.023 ops/ms
Iteration   1: 13.131 ops/ms
Iteration   2: 12.839 ops/ms
Iteration   3: 13.080 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.017 ±(99.9%) 2.837 ops/ms [Average]
  (min, avg, max) = (12.839, 13.017, 13.131), stdev = 0.156
  CI (99.9%): [10.179, 15.854] (assumes normal distribution)


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
# Warmup Iteration   1: 6.843 ops/ms
# Warmup Iteration   2: 10.624 ops/ms
# Warmup Iteration   3: 10.662 ops/ms
Iteration   1: 10.757 ops/ms
Iteration   2: 10.775 ops/ms
Iteration   3: 10.808 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.780 ±(99.9%) 0.475 ops/ms [Average]
  (min, avg, max) = (10.757, 10.780, 10.808), stdev = 0.026
  CI (99.9%): [10.305, 11.255] (assumes normal distribution)


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
# Warmup Iteration   1: 3.845 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.542 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.463 ±(99.9%) 0.003 ms/op
Iteration   1: 2.480 ±(99.9%) 0.004 ms/op
Iteration   2: 2.477 ±(99.9%) 0.004 ms/op
Iteration   3: 2.454 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.470 ±(99.9%) 0.257 ms/op [Average]
  (min, avg, max) = (2.454, 2.470, 2.480), stdev = 0.014
  CI (99.9%): [2.213, 2.727] (assumes normal distribution)


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
# Warmup Iteration   1: 3.655 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.429 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.422 ±(99.9%) 0.004 ms/op
Iteration   1: 2.450 ±(99.9%) 0.004 ms/op
Iteration   2: 2.430 ±(99.9%) 0.004 ms/op
Iteration   3: 2.421 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.434 ±(99.9%) 0.273 ms/op [Average]
  (min, avg, max) = (2.421, 2.434, 2.450), stdev = 0.015
  CI (99.9%): [2.161, 2.707] (assumes normal distribution)


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
# Warmup Iteration   1: 3.778 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.553 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.469 ±(99.9%) 0.004 ms/op
Iteration   1: 2.432 ±(99.9%) 0.004 ms/op
Iteration   2: 2.459 ±(99.9%) 0.004 ms/op
Iteration   3: 2.449 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.447 ±(99.9%) 0.246 ms/op [Average]
  (min, avg, max) = (2.432, 2.447, 2.459), stdev = 0.013
  CI (99.9%): [2.201, 2.692] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.590 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.010 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.982 ±(99.9%) 0.005 ms/op
Iteration   1: 2.967 ±(99.9%) 0.007 ms/op
Iteration   2: 2.959 ±(99.9%) 0.006 ms/op
Iteration   3: 2.956 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.961 ±(99.9%) 0.111 ms/op [Average]
  (min, avg, max) = (2.956, 2.961, 2.967), stdev = 0.006
  CI (99.9%): [2.849, 3.072] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:18
# Fork: 1 of 1
# Warmup Iteration   1: 4.158 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.642 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.499 ±(99.9%) 0.005 ms/op
Iteration   1: 2.498 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.020 ms/op
                 createUser·p0.50:   2.572 ms/op
                 createUser·p0.90:   3.035 ms/op
                 createUser·p0.95:   3.146 ms/op
                 createUser·p0.99:   3.654 ms/op
                 createUser·p0.999:  11.092 ms/op
                 createUser·p0.9999: 13.599 ms/op
                 createUser·p1.00:   14.139 ms/op

Iteration   2: 2.471 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.859 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   2.998 ms/op
                 createUser·p0.95:   3.092 ms/op
                 createUser·p0.99:   3.491 ms/op
                 createUser·p0.999:  6.548 ms/op
                 createUser·p0.9999: 12.833 ms/op
                 createUser·p1.00:   13.255 ms/op

Iteration   3: 2.495 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.959 ms/op
                 createUser·p0.50:   2.544 ms/op
                 createUser·p0.90:   3.035 ms/op
                 createUser·p0.95:   3.166 ms/op
                 createUser·p0.99:   3.801 ms/op
                 createUser·p0.999:  8.733 ms/op
                 createUser·p0.9999: 11.085 ms/op
                 createUser·p1.00:   11.862 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 385428
  mean =      2.488 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 46 
    [ 1.250,  2.500) = 187382 
    [ 2.500,  3.750) = 194803 
    [ 3.750,  5.000) = 2560 
    [ 5.000,  6.250) = 224 
    [ 6.250,  7.500) = 19 
    [ 7.500,  8.750) = 18 
    [ 8.750, 10.000) = 111 
    [10.000, 11.250) = 99 
    [11.250, 12.500) = 74 
    [12.500, 13.750) = 87 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.859 ms/op
     p(50.0000) =      2.564 ms/op
     p(90.0000) =      3.023 ms/op
     p(95.0000) =      3.133 ms/op
     p(99.0000) =      3.662 ms/op
     p(99.9000) =      8.489 ms/op
     p(99.9900) =     13.124 ms/op
     p(99.9990) =     13.791 ms/op
     p(99.9999) =     14.139 ms/op
    p(100.0000) =     14.139 ms/op


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
# Warmup Iteration   1: 3.711 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.448 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.413 ±(99.9%) 0.005 ms/op
Iteration   1: 2.415 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.403 ms/op
                 existUser·p0.50:   2.433 ms/op
                 existUser·p0.90:   2.945 ms/op
                 existUser·p0.95:   3.072 ms/op
                 existUser·p0.99:   3.658 ms/op
                 existUser·p0.999:  7.109 ms/op
                 existUser·p0.9999: 23.167 ms/op
                 existUser·p1.00:   23.888 ms/op

Iteration   2: 2.429 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.869 ms/op
                 existUser·p0.50:   2.486 ms/op
                 existUser·p0.90:   2.953 ms/op
                 existUser·p0.95:   3.060 ms/op
                 existUser·p0.99:   3.564 ms/op
                 existUser·p0.999:  7.453 ms/op
                 existUser·p0.9999: 13.795 ms/op
                 existUser·p1.00:   14.795 ms/op

Iteration   3: 2.425 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.092 ms/op
                 existUser·p0.50:   2.486 ms/op
                 existUser·p0.90:   2.953 ms/op
                 existUser·p0.95:   3.064 ms/op
                 existUser·p0.99:   3.572 ms/op
                 existUser·p0.999:  6.035 ms/op
                 existUser·p0.9999: 9.503 ms/op
                 existUser·p1.00:   9.781 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 395782
  mean =      2.423 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 202208 
    [ 2.500,  5.000) = 192733 
    [ 5.000,  7.500) = 484 
    [ 7.500, 10.000) = 117 
    [10.000, 12.500) = 111 
    [12.500, 15.000) = 89 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.403 ms/op
     p(50.0000) =      2.466 ms/op
     p(90.0000) =      2.949 ms/op
     p(95.0000) =      3.064 ms/op
     p(99.0000) =      3.613 ms/op
     p(99.9000) =      6.375 ms/op
     p(99.9900) =     15.031 ms/op
     p(99.9990) =     23.822 ms/op
     p(99.9999) =     23.888 ms/op
    p(100.0000) =     23.888 ms/op


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
# Warmup Iteration   1: 3.844 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.534 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.467 ±(99.9%) 0.005 ms/op
Iteration   1: 2.469 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.956 ms/op
                 getUser·p0.50:   2.482 ms/op
                 getUser·p0.90:   3.011 ms/op
                 getUser·p0.95:   3.133 ms/op
                 getUser·p0.99:   3.777 ms/op
                 getUser·p0.999:  6.728 ms/op
                 getUser·p0.9999: 13.518 ms/op
                 getUser·p1.00:   14.549 ms/op

Iteration   2: 2.483 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.984 ms/op
                 getUser·p0.50:   2.490 ms/op
                 getUser·p0.90:   3.043 ms/op
                 getUser·p0.95:   3.174 ms/op
                 getUser·p0.99:   3.789 ms/op
                 getUser·p0.999:  8.483 ms/op
                 getUser·p0.9999: 11.569 ms/op
                 getUser·p1.00:   13.107 ms/op

Iteration   3: 2.473 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.865 ms/op
                 getUser·p0.50:   2.499 ms/op
                 getUser·p0.90:   3.011 ms/op
                 getUser·p0.95:   3.133 ms/op
                 getUser·p0.99:   3.879 ms/op
                 getUser·p0.999:  6.783 ms/op
                 getUser·p0.9999: 11.392 ms/op
                 getUser·p1.00:   12.501 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 387501
  mean =      2.475 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 64 
    [ 1.250,  2.500) = 194571 
    [ 2.500,  3.750) = 188626 
    [ 3.750,  5.000) = 3439 
    [ 5.000,  6.250) = 406 
    [ 6.250,  7.500) = 10 
    [ 7.500,  8.750) = 15 
    [ 8.750, 10.000) = 122 
    [10.000, 11.250) = 72 
    [11.250, 12.500) = 81 
    [12.500, 13.750) = 89 
    [13.750, 15.000) = 6 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.865 ms/op
     p(50.0000) =      2.490 ms/op
     p(90.0000) =      3.023 ms/op
     p(95.0000) =      3.150 ms/op
     p(99.0000) =      3.809 ms/op
     p(99.9000) =      6.865 ms/op
     p(99.9900) =     13.193 ms/op
     p(99.9990) =     13.982 ms/op
     p(99.9999) =     14.549 ms/op
    p(100.0000) =     14.549 ms/op


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
# Warmup Iteration   1: 4.847 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.036 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.003 ±(99.9%) 0.009 ms/op
Iteration   1: 2.981 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.915 ms/op
                 listUser·p0.50:   2.929 ms/op
                 listUser·p0.90:   3.822 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   5.530 ms/op
                 listUser·p0.999:  9.106 ms/op
                 listUser·p0.9999: 10.867 ms/op
                 listUser·p1.00:   11.059 ms/op

Iteration   2: 2.956 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.858 ms/op
                 listUser·p0.50:   2.900 ms/op
                 listUser·p0.90:   3.813 ms/op
                 listUser·p0.95:   4.284 ms/op
                 listUser·p0.99:   5.571 ms/op
                 listUser·p0.999:  9.418 ms/op
                 listUser·p0.9999: 10.662 ms/op
                 listUser·p1.00:   11.158 ms/op

Iteration   3: 2.985 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.713 ms/op
                 listUser·p0.50:   2.929 ms/op
                 listUser·p0.90:   3.854 ms/op
                 listUser·p0.95:   4.309 ms/op
                 listUser·p0.99:   5.505 ms/op
                 listUser·p0.999:  9.026 ms/op
                 listUser·p0.9999: 10.523 ms/op
                 listUser·p1.00:   11.583 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 322489
  mean =      2.974 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 139 
    [ 1.250,  2.500) = 97749 
    [ 2.500,  3.750) = 188157 
    [ 3.750,  5.000) = 30078 
    [ 5.000,  6.250) = 5161 
    [ 6.250,  7.500) = 618 
    [ 7.500,  8.750) = 181 
    [ 8.750, 10.000) = 229 
    [10.000, 11.250) = 173 
    [11.250, 12.500) = 4 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.713 ms/op
     p(50.0000) =      2.920 ms/op
     p(90.0000) =      3.830 ms/op
     p(95.0000) =      4.301 ms/op
     p(99.0000) =      5.530 ms/op
     p(99.9000) =      9.200 ms/op
     p(99.9900) =     10.748 ms/op
     p(99.9990) =     11.327 ms/op
     p(99.9999) =     11.583 ms/op
    p(100.0000) =     11.583 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.852 ± 0.734  ops/ms
ClientPb.existUser                       thrpt       3  13.335 ± 0.757  ops/ms
ClientPb.getUser                         thrpt       3  13.017 ± 2.837  ops/ms
ClientPb.listUser                        thrpt       3  10.780 ± 0.475  ops/ms
ClientPb.createUser                       avgt       3   2.470 ± 0.257   ms/op
ClientPb.existUser                        avgt       3   2.434 ± 0.273   ms/op
ClientPb.getUser                          avgt       3   2.447 ± 0.246   ms/op
ClientPb.listUser                         avgt       3   2.961 ± 0.111   ms/op
ClientPb.createUser                     sample  385428   2.488 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.859           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.564           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.023           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.133           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.662           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.489           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.124           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.139           ms/op
ClientPb.existUser                      sample  395782   2.423 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.403           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.466           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.949           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.064           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.613           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.375           ms/op
ClientPb.existUser:existUser·p0.9999    sample          15.031           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.888           ms/op
ClientPb.getUser                        sample  387501   2.475 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.865           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.490           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.023           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.150           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.809           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.865           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.193           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.549           ms/op
ClientPb.listUser                       sample  322489   2.974 ± 0.004   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.713           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.920           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.830           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.301           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.530           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.200           ms/op
ClientPb.listUser:listUser·p0.9999      sample          10.748           ms/op
ClientPb.listUser:listUser·p1.00        sample          11.583           ms/op
