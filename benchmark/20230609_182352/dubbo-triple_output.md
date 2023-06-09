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
# Warmup Iteration   1: 2.335 ops/ms
# Warmup Iteration   2: 5.630 ops/ms
# Warmup Iteration   3: 9.150 ops/ms
Iteration   1: 9.387 ops/ms
Iteration   2: 9.898 ops/ms
Iteration   3: 9.909 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.731 ±(99.9%) 5.443 ops/ms [Average]
  (min, avg, max) = (9.387, 9.731, 9.909), stdev = 0.298
  CI (99.9%): [4.288, 15.175] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.473 ops/ms
# Warmup Iteration   2: 9.372 ops/ms
# Warmup Iteration   3: 10.099 ops/ms
Iteration   1: 10.641 ops/ms
Iteration   2: 10.340 ops/ms
Iteration   3: 10.702 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.561 ±(99.9%) 3.534 ops/ms [Average]
  (min, avg, max) = (10.340, 10.561, 10.702), stdev = 0.194
  CI (99.9%): [7.027, 14.095] (assumes normal distribution)


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
# Warmup Iteration   1: 3.388 ops/ms
# Warmup Iteration   2: 8.536 ops/ms
# Warmup Iteration   3: 9.616 ops/ms
Iteration   1: 9.745 ops/ms
Iteration   2: 10.150 ops/ms
Iteration   3: 10.167 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.021 ±(99.9%) 4.351 ops/ms [Average]
  (min, avg, max) = (9.745, 10.021, 10.167), stdev = 0.239
  CI (99.9%): [5.669, 14.372] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.124 ops/ms
# Warmup Iteration   2: 7.523 ops/ms
# Warmup Iteration   3: 8.144 ops/ms
Iteration   1: 8.398 ops/ms
Iteration   2: 8.297 ops/ms
Iteration   3: 8.414 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.369 ±(99.9%) 1.152 ops/ms [Average]
  (min, avg, max) = (8.297, 8.369, 8.414), stdev = 0.063
  CI (99.9%): [7.218, 9.521] (assumes normal distribution)


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
# Warmup Iteration   1: 9.012 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.450 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.335 ±(99.9%) 0.005 ms/op
Iteration   1: 3.096 ±(99.9%) 0.003 ms/op
Iteration   2: 3.125 ±(99.9%) 0.006 ms/op
Iteration   3: 3.116 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.112 ±(99.9%) 0.270 ms/op [Average]
  (min, avg, max) = (3.096, 3.112, 3.125), stdev = 0.015
  CI (99.9%): [2.842, 3.383] (assumes normal distribution)


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
# Warmup Iteration   1: 7.536 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.351 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.330 ±(99.9%) 0.005 ms/op
Iteration   1: 3.263 ±(99.9%) 0.002 ms/op
Iteration   2: 3.027 ±(99.9%) 0.004 ms/op
Iteration   3: 3.279 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.189 ±(99.9%) 2.575 ms/op [Average]
  (min, avg, max) = (3.027, 3.189, 3.279), stdev = 0.141
  CI (99.9%): [0.614, 5.764] (assumes normal distribution)


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
# Warmup Iteration   1: 7.897 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.570 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.404 ±(99.9%) 0.004 ms/op
Iteration   1: 3.131 ±(99.9%) 0.005 ms/op
Iteration   2: 3.310 ±(99.9%) 0.004 ms/op
Iteration   3: 3.261 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.234 ±(99.9%) 1.680 ms/op [Average]
  (min, avg, max) = (3.131, 3.234, 3.310), stdev = 0.092
  CI (99.9%): [1.554, 4.914] (assumes normal distribution)


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
# Warmup Iteration   1: 9.406 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.127 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.942 ±(99.9%) 0.006 ms/op
Iteration   1: 3.729 ±(99.9%) 0.012 ms/op
Iteration   2: 3.819 ±(99.9%) 0.006 ms/op
Iteration   3: 3.919 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.822 ±(99.9%) 1.733 ms/op [Average]
  (min, avg, max) = (3.729, 3.822, 3.919), stdev = 0.095
  CI (99.9%): [2.089, 5.555] (assumes normal distribution)


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
# Warmup Iteration   1: 9.144 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 3.854 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.152 ±(99.9%) 0.008 ms/op
Iteration   1: 3.159 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.967 ms/op
                 createUser·p0.50:   3.064 ms/op
                 createUser·p0.90:   3.334 ms/op
                 createUser·p0.95:   3.600 ms/op
                 createUser·p0.99:   5.456 ms/op
                 createUser·p0.999:  17.203 ms/op
                 createUser·p0.9999: 20.869 ms/op
                 createUser·p1.00:   22.348 ms/op

Iteration   2: 3.296 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.801 ms/op
                 createUser·p0.50:   3.248 ms/op
                 createUser·p0.90:   3.752 ms/op
                 createUser·p0.95:   3.969 ms/op
                 createUser·p0.99:   5.464 ms/op
                 createUser·p0.999:  15.543 ms/op
                 createUser·p0.9999: 25.414 ms/op
                 createUser·p1.00:   25.821 ms/op

Iteration   3: 3.321 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.962 ms/op
                 createUser·p0.50:   3.310 ms/op
                 createUser·p0.90:   3.670 ms/op
                 createUser·p0.95:   4.030 ms/op
                 createUser·p0.99:   5.538 ms/op
                 createUser·p0.999:  14.494 ms/op
                 createUser·p0.9999: 21.365 ms/op
                 createUser·p1.00:   21.660 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 294750
  mean =      3.257 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20992 
    [ 2.500,  5.000) = 267703 
    [ 5.000,  7.500) = 5165 
    [ 7.500, 10.000) = 438 
    [10.000, 12.500) = 84 
    [12.500, 15.000) = 87 
    [15.000, 17.500) = 70 
    [17.500, 20.000) = 105 
    [20.000, 22.500) = 74 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.801 ms/op
     p(50.0000) =      3.228 ms/op
     p(90.0000) =      3.609 ms/op
     p(95.0000) =      3.903 ms/op
     p(99.0000) =      5.505 ms/op
     p(99.9000) =     14.569 ms/op
     p(99.9900) =     23.495 ms/op
     p(99.9990) =     25.790 ms/op
     p(99.9999) =     25.821 ms/op
    p(100.0000) =     25.821 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 7.925 ±(99.9%) 0.100 ms/op
# Warmup Iteration   2: 3.597 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.159 ±(99.9%) 0.007 ms/op
Iteration   1: 3.201 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.227 ms/op
                 existUser·p0.50:   3.183 ms/op
                 existUser·p0.90:   3.424 ms/op
                 existUser·p0.95:   3.797 ms/op
                 existUser·p0.99:   5.521 ms/op
                 existUser·p0.999:  13.812 ms/op
                 existUser·p0.9999: 26.018 ms/op
                 existUser·p1.00:   26.640 ms/op

Iteration   2: 3.247 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.327 ms/op
                 existUser·p0.50:   3.174 ms/op
                 existUser·p0.90:   3.662 ms/op
                 existUser·p0.95:   4.055 ms/op
                 existUser·p0.99:   5.917 ms/op
                 existUser·p0.999:  13.495 ms/op
                 existUser·p0.9999: 28.188 ms/op
                 existUser·p1.00:   29.753 ms/op

Iteration   3: 3.211 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.120 ms/op
                 existUser·p0.50:   3.117 ms/op
                 existUser·p0.90:   3.760 ms/op
                 existUser·p0.95:   4.094 ms/op
                 existUser·p0.99:   5.726 ms/op
                 existUser·p0.999:  9.532 ms/op
                 existUser·p0.9999: 22.152 ms/op
                 existUser·p1.00:   23.331 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 298069
  mean =      3.220 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26147 
    [ 2.500,  5.000) = 264903 
    [ 5.000,  7.500) = 6140 
    [ 7.500, 10.000) = 411 
    [10.000, 12.500) = 118 
    [12.500, 15.000) = 60 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 102 
    [20.000, 22.500) = 76 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 39 

  Percentiles, ms/op:
      p(0.0000) =      1.120 ms/op
     p(50.0000) =      3.162 ms/op
     p(90.0000) =      3.584 ms/op
     p(95.0000) =      4.043 ms/op
     p(99.0000) =      5.685 ms/op
     p(99.9000) =     13.548 ms/op
     p(99.9900) =     26.640 ms/op
     p(99.9990) =     29.267 ms/op
     p(99.9999) =     29.753 ms/op
    p(100.0000) =     29.753 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 7.570 ±(99.9%) 0.102 ms/op
# Warmup Iteration   2: 3.367 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.374 ±(99.9%) 0.011 ms/op
Iteration   1: 3.162 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.229 ms/op
                 getUser·p0.50:   3.023 ms/op
                 getUser·p0.90:   3.424 ms/op
                 getUser·p0.95:   3.645 ms/op
                 getUser·p0.99:   5.915 ms/op
                 getUser·p0.999:  18.940 ms/op
                 getUser·p0.9999: 20.599 ms/op
                 getUser·p1.00:   20.873 ms/op

Iteration   2: 3.174 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.642 ms/op
                 getUser·p0.50:   3.076 ms/op
                 getUser·p0.90:   3.588 ms/op
                 getUser·p0.95:   3.985 ms/op
                 getUser·p0.99:   4.809 ms/op
                 getUser·p0.999:  9.423 ms/op
                 getUser·p0.9999: 24.311 ms/op
                 getUser·p1.00:   25.133 ms/op

Iteration   3: 3.247 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.530 ms/op
                 getUser·p0.50:   3.097 ms/op
                 getUser·p0.90:   3.572 ms/op
                 getUser·p0.95:   4.530 ms/op
                 getUser·p0.99:   5.947 ms/op
                 getUser·p0.999:  10.053 ms/op
                 getUser·p0.9999: 25.330 ms/op
                 getUser·p1.00:   25.887 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 300586
  mean =      3.194 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7272 
    [ 2.500,  5.000) = 286877 
    [ 5.000,  7.500) = 5623 
    [ 7.500, 10.000) = 467 
    [10.000, 12.500) = 12 
    [12.500, 15.000) = 15 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 95 
    [20.000, 22.500) = 126 
    [22.500, 25.000) = 61 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      1.229 ms/op
     p(50.0000) =      3.060 ms/op
     p(90.0000) =      3.527 ms/op
     p(95.0000) =      4.002 ms/op
     p(99.0000) =      5.677 ms/op
     p(99.9000) =     17.315 ms/op
     p(99.9900) =     24.541 ms/op
     p(99.9990) =     25.722 ms/op
     p(99.9999) =     25.887 ms/op
    p(100.0000) =     25.887 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 9.135 ±(99.9%) 0.119 ms/op
# Warmup Iteration   2: 3.966 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.887 ±(99.9%) 0.013 ms/op
Iteration   1: 3.768 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.704 ms/op
                 listUser·p0.50:   3.641 ms/op
                 listUser·p0.90:   4.026 ms/op
                 listUser·p0.95:   4.235 ms/op
                 listUser·p0.99:   6.996 ms/op
                 listUser·p0.999:  14.133 ms/op
                 listUser·p0.9999: 24.134 ms/op
                 listUser·p1.00:   24.936 ms/op

Iteration   2: 3.801 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.208 ms/op
                 listUser·p0.50:   3.674 ms/op
                 listUser·p0.90:   4.137 ms/op
                 listUser·p0.95:   4.309 ms/op
                 listUser·p0.99:   6.900 ms/op
                 listUser·p0.999:  14.347 ms/op
                 listUser·p0.9999: 17.288 ms/op
                 listUser·p1.00:   17.400 ms/op

Iteration   3: 3.729 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.812 ms/op
                 listUser·p0.50:   3.592 ms/op
                 listUser·p0.90:   4.121 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   6.667 ms/op
                 listUser·p0.999:  13.754 ms/op
                 listUser·p0.9999: 15.211 ms/op
                 listUser·p1.00:   15.794 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 254948
  mean =      3.766 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 60 
    [ 2.500,  5.000) = 248616 
    [ 5.000,  7.500) = 4543 
    [ 7.500, 10.000) = 1079 
    [10.000, 12.500) = 245 
    [12.500, 15.000) = 253 
    [15.000, 17.500) = 120 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.704 ms/op
     p(50.0000) =      3.625 ms/op
     p(90.0000) =      4.104 ms/op
     p(95.0000) =      4.301 ms/op
     p(99.0000) =      6.840 ms/op
     p(99.9000) =     14.075 ms/op
     p(99.9900) =     23.037 ms/op
     p(99.9990) =     24.460 ms/op
     p(99.9999) =     24.936 ms/op
    p(100.0000) =     24.936 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.731 ± 5.443  ops/ms
ClientPb.existUser                       thrpt       3  10.561 ± 3.534  ops/ms
ClientPb.getUser                         thrpt       3  10.021 ± 4.351  ops/ms
ClientPb.listUser                        thrpt       3   8.369 ± 1.152  ops/ms
ClientPb.createUser                       avgt       3   3.112 ± 0.270   ms/op
ClientPb.existUser                        avgt       3   3.189 ± 2.575   ms/op
ClientPb.getUser                          avgt       3   3.234 ± 1.680   ms/op
ClientPb.listUser                         avgt       3   3.822 ± 1.733   ms/op
ClientPb.createUser                     sample  294750   3.257 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.801           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.228           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.609           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.903           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.505           ms/op
ClientPb.createUser:createUser·p0.999   sample          14.569           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.495           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.821           ms/op
ClientPb.existUser                      sample  298069   3.220 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.120           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.162           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.584           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.043           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.685           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.548           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.640           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.753           ms/op
ClientPb.getUser                        sample  300586   3.194 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.229           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.060           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.527           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.002           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.677           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.315           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.541           ms/op
ClientPb.getUser:getUser·p1.00          sample          25.887           ms/op
ClientPb.listUser                       sample  254948   3.766 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.704           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.625           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.104           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.301           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.840           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.075           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.037           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.936           ms/op
