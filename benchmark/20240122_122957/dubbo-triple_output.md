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
# Warmup Iteration   1: 4.559 ops/ms
# Warmup Iteration   2: 12.051 ops/ms
# Warmup Iteration   3: 12.431 ops/ms
Iteration   1: 12.645 ops/ms
Iteration   2: 12.605 ops/ms
Iteration   3: 12.785 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.678 ±(99.9%) 1.726 ops/ms [Average]
  (min, avg, max) = (12.605, 12.678, 12.785), stdev = 0.095
  CI (99.9%): [10.952, 14.405] (assumes normal distribution)


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
# Warmup Iteration   1: 7.680 ops/ms
# Warmup Iteration   2: 12.990 ops/ms
# Warmup Iteration   3: 12.953 ops/ms
Iteration   1: 13.044 ops/ms
Iteration   2: 13.081 ops/ms
Iteration   3: 13.012 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.046 ±(99.9%) 0.629 ops/ms [Average]
  (min, avg, max) = (13.012, 13.046, 13.081), stdev = 0.034
  CI (99.9%): [12.417, 13.674] (assumes normal distribution)


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
# Warmup Iteration   1: 7.279 ops/ms
# Warmup Iteration   2: 12.587 ops/ms
# Warmup Iteration   3: 12.935 ops/ms
Iteration   1: 12.949 ops/ms
Iteration   2: 12.945 ops/ms
Iteration   3: 12.825 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.907 ±(99.9%) 1.283 ops/ms [Average]
  (min, avg, max) = (12.825, 12.907, 12.949), stdev = 0.070
  CI (99.9%): [11.624, 14.190] (assumes normal distribution)


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
# Warmup Iteration   1: 6.652 ops/ms
# Warmup Iteration   2: 10.608 ops/ms
# Warmup Iteration   3: 10.745 ops/ms
Iteration   1: 10.785 ops/ms
Iteration   2: 10.723 ops/ms
Iteration   3: 10.762 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.756 ±(99.9%) 0.577 ops/ms [Average]
  (min, avg, max) = (10.723, 10.756, 10.785), stdev = 0.032
  CI (99.9%): [10.180, 11.333] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:38
# Fork: 1 of 1
# Warmup Iteration   1: 3.820 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.563 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.491 ±(99.9%) 0.003 ms/op
Iteration   1: 2.497 ±(99.9%) 0.004 ms/op
Iteration   2: 2.468 ±(99.9%) 0.004 ms/op
Iteration   3: 2.468 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.478 ±(99.9%) 0.308 ms/op [Average]
  (min, avg, max) = (2.468, 2.478, 2.497), stdev = 0.017
  CI (99.9%): [2.170, 2.786] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:33
# Fork: 1 of 1
# Warmup Iteration   1: 3.724 ±(99.9%) 0.007 ms/op
# Warmup Iteration   2: 2.430 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.419 ±(99.9%) 0.004 ms/op
Iteration   1: 2.400 ±(99.9%) 0.004 ms/op
Iteration   2: 2.416 ±(99.9%) 0.003 ms/op
Iteration   3: 2.439 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.418 ±(99.9%) 0.362 ms/op [Average]
  (min, avg, max) = (2.400, 2.418, 2.439), stdev = 0.020
  CI (99.9%): [2.056, 2.781] (assumes normal distribution)


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
# Warmup Iteration   1: 3.602 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.448 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.416 ±(99.9%) 0.003 ms/op
Iteration   1: 2.438 ±(99.9%) 0.004 ms/op
Iteration   2: 2.424 ±(99.9%) 0.003 ms/op
Iteration   3: 2.415 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.426 ±(99.9%) 0.213 ms/op [Average]
  (min, avg, max) = (2.415, 2.426, 2.438), stdev = 0.012
  CI (99.9%): [2.213, 2.639] (assumes normal distribution)


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
# Warmup Iteration   1: 4.528 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.000 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.980 ±(99.9%) 0.005 ms/op
Iteration   1: 2.963 ±(99.9%) 0.006 ms/op
Iteration   2: 2.987 ±(99.9%) 0.005 ms/op
Iteration   3: 2.958 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.969 ±(99.9%) 0.277 ms/op [Average]
  (min, avg, max) = (2.958, 2.969, 2.987), stdev = 0.015
  CI (99.9%): [2.692, 3.246] (assumes normal distribution)


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
# Warmup Iteration   1: 4.048 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.564 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.487 ±(99.9%) 0.005 ms/op
Iteration   1: 2.475 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.031 ms/op
                 createUser·p0.50:   2.560 ms/op
                 createUser·p0.90:   2.998 ms/op
                 createUser·p0.95:   3.109 ms/op
                 createUser·p0.99:   3.641 ms/op
                 createUser·p0.999:  6.528 ms/op
                 createUser·p0.9999: 13.076 ms/op
                 createUser·p1.00:   13.730 ms/op

Iteration   2: 2.469 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.945 ms/op
                 createUser·p0.50:   2.560 ms/op
                 createUser·p0.90:   2.986 ms/op
                 createUser·p0.95:   3.084 ms/op
                 createUser·p0.99:   3.604 ms/op
                 createUser·p0.999:  9.511 ms/op
                 createUser·p0.9999: 12.403 ms/op
                 createUser·p1.00:   13.812 ms/op

Iteration   3: 2.490 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.666 ms/op
                 createUser·p0.50:   2.552 ms/op
                 createUser·p0.90:   3.035 ms/op
                 createUser·p0.95:   3.154 ms/op
                 createUser·p0.99:   3.830 ms/op
                 createUser·p0.999:  8.232 ms/op
                 createUser·p0.9999: 9.863 ms/op
                 createUser·p1.00:   15.270 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 387058
  mean =      2.478 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 48 
    [ 1.250,  2.500) = 188818 
    [ 2.500,  3.750) = 194693 
    [ 3.750,  5.000) = 2735 
    [ 5.000,  6.250) = 314 
    [ 6.250,  7.500) = 28 
    [ 7.500,  8.750) = 26 
    [ 8.750, 10.000) = 155 
    [10.000, 11.250) = 51 
    [11.250, 12.500) = 119 
    [12.500, 13.750) = 68 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.666 ms/op
     p(50.0000) =      2.556 ms/op
     p(90.0000) =      3.006 ms/op
     p(95.0000) =      3.117 ms/op
     p(99.0000) =      3.686 ms/op
     p(99.9000) =      8.946 ms/op
     p(99.9900) =     12.878 ms/op
     p(99.9990) =     13.740 ms/op
     p(99.9999) =     15.270 ms/op
    p(100.0000) =     15.270 ms/op


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
# Warmup Iteration   1: 3.613 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.406 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.371 ±(99.9%) 0.005 ms/op
Iteration   1: 2.411 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.976 ms/op
                 existUser·p0.50:   2.507 ms/op
                 existUser·p0.90:   2.937 ms/op
                 existUser·p0.95:   3.043 ms/op
                 existUser·p0.99:   3.506 ms/op
                 existUser·p0.999:  4.809 ms/op
                 existUser·p0.9999: 13.545 ms/op
                 existUser·p1.00:   14.025 ms/op

Iteration   2: 2.390 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.092 ms/op
                 existUser·p0.50:   2.511 ms/op
                 existUser·p0.90:   2.900 ms/op
                 existUser·p0.95:   2.990 ms/op
                 existUser·p0.99:   3.326 ms/op
                 existUser·p0.999:  7.635 ms/op
                 existUser·p0.9999: 12.585 ms/op
                 existUser·p1.00:   13.156 ms/op

Iteration   3: 2.394 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.022 ms/op
                 existUser·p0.50:   2.441 ms/op
                 existUser·p0.90:   2.908 ms/op
                 existUser·p0.95:   3.015 ms/op
                 existUser·p0.99:   3.588 ms/op
                 existUser·p0.999:  6.642 ms/op
                 existUser·p0.9999: 11.762 ms/op
                 existUser·p1.00:   12.321 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 399914
  mean =      2.398 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 51 
    [ 1.250,  2.500) = 201393 
    [ 2.500,  3.750) = 195985 
    [ 3.750,  5.000) = 1830 
    [ 5.000,  6.250) = 247 
    [ 6.250,  7.500) = 21 
    [ 7.500,  8.750) = 86 
    [ 8.750, 10.000) = 81 
    [10.000, 11.250) = 69 
    [11.250, 12.500) = 83 
    [12.500, 13.750) = 58 
    [13.750, 15.000) = 10 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.976 ms/op
     p(50.0000) =      2.486 ms/op
     p(90.0000) =      2.912 ms/op
     p(95.0000) =      3.015 ms/op
     p(99.0000) =      3.482 ms/op
     p(99.9000) =      7.016 ms/op
     p(99.9900) =     13.075 ms/op
     p(99.9990) =     13.926 ms/op
     p(99.9999) =     14.025 ms/op
    p(100.0000) =     14.025 ms/op


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
# Warmup Iteration   1: 3.640 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.540 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.455 ±(99.9%) 0.005 ms/op
Iteration   1: 2.442 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.569 ms/op
                 getUser·p0.50:   2.478 ms/op
                 getUser·p0.90:   2.961 ms/op
                 getUser·p0.95:   3.056 ms/op
                 getUser·p0.99:   3.547 ms/op
                 getUser·p0.999:  6.393 ms/op
                 getUser·p0.9999: 13.268 ms/op
                 getUser·p1.00:   13.877 ms/op

Iteration   2: 2.522 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.000 ms/op
                 getUser·p0.50:   2.552 ms/op
                 getUser·p0.90:   3.047 ms/op
                 getUser·p0.95:   3.248 ms/op
                 getUser·p0.99:   4.948 ms/op
                 getUser·p0.999:  10.229 ms/op
                 getUser·p0.9999: 16.226 ms/op
                 getUser·p1.00:   17.007 ms/op

Iteration   3: 2.441 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.718 ms/op
                 getUser·p0.50:   2.482 ms/op
                 getUser·p0.90:   2.970 ms/op
                 getUser·p0.95:   3.064 ms/op
                 getUser·p0.99:   3.584 ms/op
                 getUser·p0.999:  5.407 ms/op
                 getUser·p0.9999: 11.140 ms/op
                 getUser·p1.00:   11.551 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 388582
  mean =      2.468 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 72 
    [ 1.250,  2.500) = 193508 
    [ 2.500,  3.750) = 189753 
    [ 3.750,  5.000) = 3674 
    [ 5.000,  6.250) = 1138 
    [ 6.250,  7.500) = 82 
    [ 7.500,  8.750) = 59 
    [ 8.750, 10.000) = 13 
    [10.000, 11.250) = 85 
    [11.250, 12.500) = 104 
    [12.500, 13.750) = 61 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 22 
    [16.250, 17.500) = 10 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.569 ms/op
     p(50.0000) =      2.511 ms/op
     p(90.0000) =      2.990 ms/op
     p(95.0000) =      3.109 ms/op
     p(99.0000) =      4.055 ms/op
     p(99.9000) =      6.496 ms/op
     p(99.9900) =     13.477 ms/op
     p(99.9990) =     16.719 ms/op
     p(99.9999) =     17.007 ms/op
    p(100.0000) =     17.007 ms/op


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
# Warmup Iteration   1: 4.577 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.011 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.981 ±(99.9%) 0.008 ms/op
Iteration   1: 2.955 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.807 ms/op
                 listUser·p0.50:   2.892 ms/op
                 listUser·p0.90:   3.809 ms/op
                 listUser·p0.95:   4.276 ms/op
                 listUser·p0.99:   5.513 ms/op
                 listUser·p0.999:  9.123 ms/op
                 listUser·p0.9999: 10.705 ms/op
                 listUser·p1.00:   11.649 ms/op

Iteration   2: 2.953 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.891 ms/op
                 listUser·p0.50:   2.896 ms/op
                 listUser·p0.90:   3.797 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   5.472 ms/op
                 listUser·p0.999:  9.634 ms/op
                 listUser·p0.9999: 10.833 ms/op
                 listUser·p1.00:   11.174 ms/op

Iteration   3: 2.960 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.878 ms/op
                 listUser·p0.50:   2.904 ms/op
                 listUser·p0.90:   3.822 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   5.431 ms/op
                 listUser·p0.999:  8.913 ms/op
                 listUser·p0.9999: 10.322 ms/op
                 listUser·p1.00:   11.469 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 324484
  mean =      2.956 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 161 
    [ 1.250,  2.500) = 101550 
    [ 2.500,  3.750) = 187356 
    [ 3.750,  5.000) = 28895 
    [ 5.000,  6.250) = 5260 
    [ 6.250,  7.500) = 570 
    [ 7.500,  8.750) = 249 
    [ 8.750, 10.000) = 328 
    [10.000, 11.250) = 105 
    [11.250, 12.500) = 10 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.807 ms/op
     p(50.0000) =      2.896 ms/op
     p(90.0000) =      3.809 ms/op
     p(95.0000) =      4.301 ms/op
     p(99.0000) =      5.472 ms/op
     p(99.9000) =      9.159 ms/op
     p(99.9900) =     10.764 ms/op
     p(99.9990) =     11.485 ms/op
     p(99.9999) =     11.649 ms/op
    p(100.0000) =     11.649 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.678 ± 1.726  ops/ms
ClientPb.existUser                       thrpt       3  13.046 ± 0.629  ops/ms
ClientPb.getUser                         thrpt       3  12.907 ± 1.283  ops/ms
ClientPb.listUser                        thrpt       3  10.756 ± 0.577  ops/ms
ClientPb.createUser                       avgt       3   2.478 ± 0.308   ms/op
ClientPb.existUser                        avgt       3   2.418 ± 0.362   ms/op
ClientPb.getUser                          avgt       3   2.426 ± 0.213   ms/op
ClientPb.listUser                         avgt       3   2.969 ± 0.277   ms/op
ClientPb.createUser                     sample  387058   2.478 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.666           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.556           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.006           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.117           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.686           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.946           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.878           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.270           ms/op
ClientPb.existUser                      sample  399914   2.398 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.976           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.486           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.912           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.015           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.482           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.016           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.075           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.025           ms/op
ClientPb.getUser                        sample  388582   2.468 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.569           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.511           ms/op
ClientPb.getUser:getUser·p0.90          sample           2.990           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.109           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.055           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.496           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.477           ms/op
ClientPb.getUser:getUser·p1.00          sample          17.007           ms/op
ClientPb.listUser                       sample  324484   2.956 ± 0.004   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.807           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.896           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.809           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.301           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.472           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.159           ms/op
ClientPb.listUser:listUser·p0.9999      sample          10.764           ms/op
ClientPb.listUser:listUser·p1.00        sample          11.649           ms/op
