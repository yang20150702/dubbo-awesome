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
# Warmup Iteration   1: 4.600 ops/ms
# Warmup Iteration   2: 12.119 ops/ms
# Warmup Iteration   3: 12.490 ops/ms
Iteration   1: 12.633 ops/ms
Iteration   2: 12.632 ops/ms
Iteration   3: 12.824 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.696 ±(99.9%) 2.018 ops/ms [Average]
  (min, avg, max) = (12.632, 12.696, 12.824), stdev = 0.111
  CI (99.9%): [10.679, 14.714] (assumes normal distribution)


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
# Warmup Iteration   1: 8.154 ops/ms
# Warmup Iteration   2: 12.919 ops/ms
# Warmup Iteration   3: 13.014 ops/ms
Iteration   1: 12.957 ops/ms
Iteration   2: 12.866 ops/ms
Iteration   3: 12.852 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.892 ±(99.9%) 1.034 ops/ms [Average]
  (min, avg, max) = (12.852, 12.892, 12.957), stdev = 0.057
  CI (99.9%): [11.858, 13.926] (assumes normal distribution)


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
# Warmup Iteration   1: 7.585 ops/ms
# Warmup Iteration   2: 12.544 ops/ms
# Warmup Iteration   3: 12.617 ops/ms
Iteration   1: 12.783 ops/ms
Iteration   2: 12.820 ops/ms
Iteration   3: 12.757 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.787 ±(99.9%) 0.584 ops/ms [Average]
  (min, avg, max) = (12.757, 12.787, 12.820), stdev = 0.032
  CI (99.9%): [12.203, 13.370] (assumes normal distribution)


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
# Warmup Iteration   1: 6.587 ops/ms
# Warmup Iteration   2: 10.611 ops/ms
# Warmup Iteration   3: 10.602 ops/ms
Iteration   1: 10.689 ops/ms
Iteration   2: 10.680 ops/ms
Iteration   3: 10.580 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.650 ±(99.9%) 1.102 ops/ms [Average]
  (min, avg, max) = (10.580, 10.650, 10.689), stdev = 0.060
  CI (99.9%): [9.548, 11.752] (assumes normal distribution)


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
# Warmup Iteration   1: 4.099 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.590 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.563 ±(99.9%) 0.004 ms/op
Iteration   1: 2.586 ±(99.9%) 0.004 ms/op
Iteration   2: 2.509 ±(99.9%) 0.005 ms/op
Iteration   3: 2.521 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.539 ±(99.9%) 0.756 ms/op [Average]
  (min, avg, max) = (2.509, 2.539, 2.586), stdev = 0.041
  CI (99.9%): [1.782, 3.295] (assumes normal distribution)


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
# Warmup Iteration   1: 3.708 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.500 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.472 ±(99.9%) 0.004 ms/op
Iteration   1: 2.477 ±(99.9%) 0.004 ms/op
Iteration   2: 2.476 ±(99.9%) 0.004 ms/op
Iteration   3: 2.454 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.469 ±(99.9%) 0.241 ms/op [Average]
  (min, avg, max) = (2.454, 2.469, 2.477), stdev = 0.013
  CI (99.9%): [2.227, 2.710] (assumes normal distribution)


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
# Warmup Iteration   1: 3.865 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.538 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.518 ±(99.9%) 0.004 ms/op
Iteration   1: 2.521 ±(99.9%) 0.005 ms/op
Iteration   2: 2.497 ±(99.9%) 0.004 ms/op
Iteration   3: 2.515 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.511 ±(99.9%) 0.224 ms/op [Average]
  (min, avg, max) = (2.497, 2.511, 2.521), stdev = 0.012
  CI (99.9%): [2.287, 2.735] (assumes normal distribution)


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
# Warmup Iteration   1: 4.535 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.065 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.057 ±(99.9%) 0.005 ms/op
Iteration   1: 3.019 ±(99.9%) 0.006 ms/op
Iteration   2: 3.002 ±(99.9%) 0.006 ms/op
Iteration   3: 3.034 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.018 ±(99.9%) 0.291 ms/op [Average]
  (min, avg, max) = (3.002, 3.018, 3.034), stdev = 0.016
  CI (99.9%): [2.728, 3.309] (assumes normal distribution)


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
# Warmup Iteration   1: 4.205 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.653 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.554 ±(99.9%) 0.006 ms/op
Iteration   1: 2.548 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.950 ms/op
                 createUser·p0.50:   2.605 ms/op
                 createUser·p0.90:   3.101 ms/op
                 createUser·p0.95:   3.215 ms/op
                 createUser·p0.99:   3.801 ms/op
                 createUser·p0.999:  11.354 ms/op
                 createUser·p0.9999: 13.319 ms/op
                 createUser·p1.00:   14.057 ms/op

Iteration   2: 2.531 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.873 ms/op
                 createUser·p0.50:   2.585 ms/op
                 createUser·p0.90:   3.072 ms/op
                 createUser·p0.95:   3.174 ms/op
                 createUser·p0.99:   3.613 ms/op
                 createUser·p0.999:  10.088 ms/op
                 createUser·p0.9999: 19.914 ms/op
                 createUser·p1.00:   20.251 ms/op

Iteration   3: 2.569 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.973 ms/op
                 createUser·p0.50:   2.597 ms/op
                 createUser·p0.90:   3.133 ms/op
                 createUser·p0.95:   3.260 ms/op
                 createUser·p0.99:   3.968 ms/op
                 createUser·p0.999:  8.424 ms/op
                 createUser·p0.9999: 12.452 ms/op
                 createUser·p1.00:   12.763 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 376195
  mean =      2.549 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 181275 
    [ 2.500,  5.000) = 194046 
    [ 5.000,  7.500) = 476 
    [ 7.500, 10.000) = 89 
    [10.000, 12.500) = 174 
    [12.500, 15.000) = 103 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.873 ms/op
     p(50.0000) =      2.597 ms/op
     p(90.0000) =      3.101 ms/op
     p(95.0000) =      3.219 ms/op
     p(99.0000) =      3.793 ms/op
     p(99.9000) =      8.585 ms/op
     p(99.9900) =     13.742 ms/op
     p(99.9990) =     20.226 ms/op
     p(99.9999) =     20.251 ms/op
    p(100.0000) =     20.251 ms/op


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
# Warmup Iteration   1: 3.730 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.506 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.443 ±(99.9%) 0.005 ms/op
Iteration   1: 2.471 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.824 ms/op
                 existUser·p0.50:   2.560 ms/op
                 existUser·p0.90:   3.011 ms/op
                 existUser·p0.95:   3.117 ms/op
                 existUser·p0.99:   3.613 ms/op
                 existUser·p0.999:  5.412 ms/op
                 existUser·p0.9999: 13.879 ms/op
                 existUser·p1.00:   14.254 ms/op

Iteration   2: 2.458 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.971 ms/op
                 existUser·p0.50:   2.507 ms/op
                 existUser·p0.90:   2.990 ms/op
                 existUser·p0.95:   3.088 ms/op
                 existUser·p0.99:   3.578 ms/op
                 existUser·p0.999:  9.077 ms/op
                 existUser·p0.9999: 13.992 ms/op
                 existUser·p1.00:   14.909 ms/op

Iteration   3: 2.456 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.928 ms/op
                 existUser·p0.50:   2.527 ms/op
                 existUser·p0.90:   2.986 ms/op
                 existUser·p0.95:   3.084 ms/op
                 existUser·p0.99:   3.535 ms/op
                 existUser·p0.999:  7.296 ms/op
                 existUser·p0.9999: 13.140 ms/op
                 existUser·p1.00:   14.090 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 389559
  mean =      2.462 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 57 
    [ 1.250,  2.500) = 192247 
    [ 2.500,  3.750) = 194357 
    [ 3.750,  5.000) = 2251 
    [ 5.000,  6.250) = 201 
    [ 6.250,  7.500) = 82 
    [ 7.500,  8.750) = 33 
    [ 8.750, 10.000) = 74 
    [10.000, 11.250) = 45 
    [11.250, 12.500) = 36 
    [12.500, 13.750) = 134 
    [13.750, 15.000) = 42 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.824 ms/op
     p(50.0000) =      2.531 ms/op
     p(90.0000) =      2.994 ms/op
     p(95.0000) =      3.097 ms/op
     p(99.0000) =      3.576 ms/op
     p(99.9000) =      7.393 ms/op
     p(99.9900) =     13.830 ms/op
     p(99.9990) =     14.282 ms/op
     p(99.9999) =     14.909 ms/op
    p(100.0000) =     14.909 ms/op


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
# Warmup Iteration   1: 3.817 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.593 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.545 ±(99.9%) 0.006 ms/op
Iteration   1: 2.517 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.023 ms/op
                 getUser·p0.50:   2.531 ms/op
                 getUser·p0.90:   3.072 ms/op
                 getUser·p0.95:   3.178 ms/op
                 getUser·p0.99:   3.617 ms/op
                 getUser·p0.999:  11.238 ms/op
                 getUser·p0.9999: 13.423 ms/op
                 getUser·p1.00:   14.090 ms/op

Iteration   2: 2.540 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.796 ms/op
                 getUser·p0.50:   2.548 ms/op
                 getUser·p0.90:   3.088 ms/op
                 getUser·p0.95:   3.232 ms/op
                 getUser·p0.99:   4.325 ms/op
                 getUser·p0.999:  9.512 ms/op
                 getUser·p0.9999: 13.486 ms/op
                 getUser·p1.00:   14.664 ms/op

Iteration   3: 2.510 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.925 ms/op
                 getUser·p0.50:   2.527 ms/op
                 getUser·p0.90:   3.064 ms/op
                 getUser·p0.95:   3.174 ms/op
                 getUser·p0.99:   3.604 ms/op
                 getUser·p0.999:  8.690 ms/op
                 getUser·p0.9999: 12.079 ms/op
                 getUser·p1.00:   12.632 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 380276
  mean =      2.522 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 60 
    [ 1.250,  2.500) = 187577 
    [ 2.500,  3.750) = 188471 
    [ 3.750,  5.000) = 3165 
    [ 5.000,  6.250) = 594 
    [ 6.250,  7.500) = 25 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 83 
    [10.000, 11.250) = 90 
    [11.250, 12.500) = 95 
    [12.500, 13.750) = 99 
    [13.750, 15.000) = 15 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.796 ms/op
     p(50.0000) =      2.540 ms/op
     p(90.0000) =      3.072 ms/op
     p(95.0000) =      3.195 ms/op
     p(99.0000) =      3.809 ms/op
     p(99.9000) =      8.949 ms/op
     p(99.9900) =     13.238 ms/op
     p(99.9990) =     14.177 ms/op
     p(99.9999) =     14.664 ms/op
    p(100.0000) =     14.664 ms/op


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
# Warmup Iteration   1: 4.783 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.021 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.003 ±(99.9%) 0.008 ms/op
Iteration   1: 2.990 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.946 ms/op
                 listUser·p0.50:   2.929 ms/op
                 listUser·p0.90:   3.858 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   5.535 ms/op
                 listUser·p0.999:  9.060 ms/op
                 listUser·p0.9999: 10.240 ms/op
                 listUser·p1.00:   10.928 ms/op

Iteration   2: 2.989 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.878 ms/op
                 listUser·p0.50:   2.920 ms/op
                 listUser·p0.90:   3.879 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.579 ms/op
                 listUser·p0.999:  8.963 ms/op
                 listUser·p0.9999: 10.457 ms/op
                 listUser·p1.00:   10.912 ms/op

Iteration   3: 2.980 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.975 ms/op
                 listUser·p0.50:   2.912 ms/op
                 listUser·p0.90:   3.875 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   5.603 ms/op
                 listUser·p0.999:  9.984 ms/op
                 listUser·p0.9999: 11.817 ms/op
                 listUser·p1.00:   12.255 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 321188
  mean =      2.986 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 138 
    [ 1.250,  2.500) = 96468 
    [ 2.500,  3.750) = 186335 
    [ 3.750,  5.000) = 31098 
    [ 5.000,  6.250) = 5824 
    [ 6.250,  7.500) = 637 
    [ 7.500,  8.750) = 259 
    [ 8.750, 10.000) = 285 
    [10.000, 11.250) = 106 
    [11.250, 12.500) = 38 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.878 ms/op
     p(50.0000) =      2.920 ms/op
     p(90.0000) =      3.871 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      5.571 ms/op
     p(99.9000) =      9.159 ms/op
     p(99.9900) =     11.317 ms/op
     p(99.9990) =     12.061 ms/op
     p(99.9999) =     12.255 ms/op
    p(100.0000) =     12.255 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.696 ± 2.018  ops/ms
ClientPb.existUser                       thrpt       3  12.892 ± 1.034  ops/ms
ClientPb.getUser                         thrpt       3  12.787 ± 0.584  ops/ms
ClientPb.listUser                        thrpt       3  10.650 ± 1.102  ops/ms
ClientPb.createUser                       avgt       3   2.539 ± 0.756   ms/op
ClientPb.existUser                        avgt       3   2.469 ± 0.241   ms/op
ClientPb.getUser                          avgt       3   2.511 ± 0.224   ms/op
ClientPb.listUser                         avgt       3   3.018 ± 0.291   ms/op
ClientPb.createUser                     sample  376195   2.549 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.873           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.597           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.101           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.219           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.793           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.585           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.742           ms/op
ClientPb.createUser:createUser·p1.00    sample          20.251           ms/op
ClientPb.existUser                      sample  389559   2.462 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.824           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.531           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.994           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.097           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.576           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.393           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.830           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.909           ms/op
ClientPb.getUser                        sample  380276   2.522 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.796           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.540           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.072           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.195           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.809           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.949           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.238           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.664           ms/op
ClientPb.listUser                       sample  321188   2.986 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.878           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.920           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.871           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.358           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.571           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.159           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.317           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.255           ms/op
