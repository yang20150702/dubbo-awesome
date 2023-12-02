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
# Warmup Iteration   1: 5.019 ops/ms
# Warmup Iteration   2: 12.022 ops/ms
# Warmup Iteration   3: 12.207 ops/ms
Iteration   1: 12.493 ops/ms
Iteration   2: 12.366 ops/ms
Iteration   3: 12.581 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.480 ±(99.9%) 1.972 ops/ms [Average]
  (min, avg, max) = (12.366, 12.480, 12.581), stdev = 0.108
  CI (99.9%): [10.509, 14.452] (assumes normal distribution)


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
# Warmup Iteration   1: 8.181 ops/ms
# Warmup Iteration   2: 13.015 ops/ms
# Warmup Iteration   3: 13.092 ops/ms
Iteration   1: 13.084 ops/ms
Iteration   2: 13.001 ops/ms
Iteration   3: 13.075 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.053 ±(99.9%) 0.829 ops/ms [Average]
  (min, avg, max) = (13.001, 13.053, 13.084), stdev = 0.045
  CI (99.9%): [12.224, 13.883] (assumes normal distribution)


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
# Warmup Iteration   1: 7.593 ops/ms
# Warmup Iteration   2: 12.465 ops/ms
# Warmup Iteration   3: 12.825 ops/ms
Iteration   1: 12.901 ops/ms
Iteration   2: 12.770 ops/ms
Iteration   3: 12.843 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.838 ±(99.9%) 1.201 ops/ms [Average]
  (min, avg, max) = (12.770, 12.838, 12.901), stdev = 0.066
  CI (99.9%): [11.637, 14.039] (assumes normal distribution)


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
# Warmup Iteration   1: 6.269 ops/ms
# Warmup Iteration   2: 10.352 ops/ms
# Warmup Iteration   3: 10.498 ops/ms
Iteration   1: 10.524 ops/ms
Iteration   2: 10.537 ops/ms
Iteration   3: 10.575 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.546 ±(99.9%) 0.484 ops/ms [Average]
  (min, avg, max) = (10.524, 10.546, 10.575), stdev = 0.027
  CI (99.9%): [10.062, 11.029] (assumes normal distribution)


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
# Warmup Iteration   1: 4.036 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.603 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.522 ±(99.9%) 0.005 ms/op
Iteration   1: 2.543 ±(99.9%) 0.004 ms/op
Iteration   2: 2.571 ±(99.9%) 0.003 ms/op
Iteration   3: 2.532 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.549 ±(99.9%) 0.372 ms/op [Average]
  (min, avg, max) = (2.532, 2.549, 2.571), stdev = 0.020
  CI (99.9%): [2.176, 2.921] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:32
# Fork: 1 of 1
# Warmup Iteration   1: 3.575 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.465 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.465 ±(99.9%) 0.005 ms/op
Iteration   1: 2.433 ±(99.9%) 0.003 ms/op
Iteration   2: 2.467 ±(99.9%) 0.004 ms/op
Iteration   3: 2.471 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.457 ±(99.9%) 0.380 ms/op [Average]
  (min, avg, max) = (2.433, 2.457, 2.471), stdev = 0.021
  CI (99.9%): [2.077, 2.837] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.736 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.565 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.514 ±(99.9%) 0.004 ms/op
Iteration   1: 2.504 ±(99.9%) 0.004 ms/op
Iteration   2: 2.488 ±(99.9%) 0.004 ms/op
Iteration   3: 2.537 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.510 ±(99.9%) 0.458 ms/op [Average]
  (min, avg, max) = (2.488, 2.510, 2.537), stdev = 0.025
  CI (99.9%): [2.052, 2.968] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.712 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.065 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.008 ±(99.9%) 0.004 ms/op
Iteration   1: 3.006 ±(99.9%) 0.005 ms/op
Iteration   2: 3.010 ±(99.9%) 0.005 ms/op
Iteration   3: 3.007 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.007 ±(99.9%) 0.036 ms/op [Average]
  (min, avg, max) = (3.006, 3.007, 3.010), stdev = 0.002
  CI (99.9%): [2.972, 3.043] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:18
# Fork: 1 of 1
# Warmup Iteration   1: 4.193 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.641 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.537 ±(99.9%) 0.006 ms/op
Iteration   1: 2.520 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.951 ms/op
                 createUser·p0.50:   2.593 ms/op
                 createUser·p0.90:   3.056 ms/op
                 createUser·p0.95:   3.187 ms/op
                 createUser·p0.99:   3.797 ms/op
                 createUser·p0.999:  12.349 ms/op
                 createUser·p0.9999: 16.045 ms/op
                 createUser·p1.00:   16.941 ms/op

Iteration   2: 2.513 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.816 ms/op
                 createUser·p0.50:   2.568 ms/op
                 createUser·p0.90:   3.056 ms/op
                 createUser·p0.95:   3.199 ms/op
                 createUser·p0.99:   3.908 ms/op
                 createUser·p0.999:  8.779 ms/op
                 createUser·p0.9999: 12.386 ms/op
                 createUser·p1.00:   13.369 ms/op

Iteration   3: 2.517 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.480 ms/op
                 createUser·p0.50:   2.572 ms/op
                 createUser·p0.90:   3.060 ms/op
                 createUser·p0.95:   3.191 ms/op
                 createUser·p0.99:   3.830 ms/op
                 createUser·p0.999:  8.995 ms/op
                 createUser·p0.9999: 17.138 ms/op
                 createUser·p1.00:   17.433 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 381030
  mean =      2.517 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 52 
    [ 1.250,  2.500) = 182962 
    [ 2.500,  3.750) = 193479 
    [ 3.750,  5.000) = 3749 
    [ 5.000,  6.250) = 322 
    [ 6.250,  7.500) = 41 
    [ 7.500,  8.750) = 39 
    [ 8.750, 10.000) = 78 
    [10.000, 11.250) = 113 
    [11.250, 12.500) = 28 
    [12.500, 13.750) = 62 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 46 
    [16.250, 17.500) = 36 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.480 ms/op
     p(50.0000) =      2.576 ms/op
     p(90.0000) =      3.060 ms/op
     p(95.0000) =      3.191 ms/op
     p(99.0000) =      3.850 ms/op
     p(99.9000) =      8.995 ms/op
     p(99.9900) =     16.235 ms/op
     p(99.9990) =     17.320 ms/op
     p(99.9999) =     17.433 ms/op
    p(100.0000) =     17.433 ms/op


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
# Warmup Iteration   1: 3.765 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.474 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.460 ±(99.9%) 0.005 ms/op
Iteration   1: 2.461 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.828 ms/op
                 existUser·p0.50:   2.544 ms/op
                 existUser·p0.90:   2.994 ms/op
                 existUser·p0.95:   3.109 ms/op
                 existUser·p0.99:   3.707 ms/op
                 existUser·p0.999:  5.998 ms/op
                 existUser·p0.9999: 14.107 ms/op
                 existUser·p1.00:   15.319 ms/op

Iteration   2: 2.458 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.894 ms/op
                 existUser·p0.50:   2.568 ms/op
                 existUser·p0.90:   2.970 ms/op
                 existUser·p0.95:   3.080 ms/op
                 existUser·p0.99:   3.635 ms/op
                 existUser·p0.999:  8.408 ms/op
                 existUser·p0.9999: 14.402 ms/op
                 existUser·p1.00:   14.713 ms/op

Iteration   3: 2.468 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.948 ms/op
                 existUser·p0.50:   2.511 ms/op
                 existUser·p0.90:   3.002 ms/op
                 existUser·p0.95:   3.133 ms/op
                 existUser·p0.99:   3.912 ms/op
                 existUser·p0.999:  9.224 ms/op
                 existUser·p0.9999: 12.322 ms/op
                 existUser·p1.00:   12.648 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 389477
  mean =      2.462 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 40 
    [ 1.250,  2.500) = 190813 
    [ 2.500,  3.750) = 194680 
    [ 3.750,  5.000) = 2675 
    [ 5.000,  6.250) = 777 
    [ 6.250,  7.500) = 114 
    [ 7.500,  8.750) = 11 
    [ 8.750, 10.000) = 44 
    [10.000, 11.250) = 75 
    [11.250, 12.500) = 83 
    [12.500, 13.750) = 116 
    [13.750, 15.000) = 47 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.828 ms/op
     p(50.0000) =      2.540 ms/op
     p(90.0000) =      2.990 ms/op
     p(95.0000) =      3.105 ms/op
     p(99.0000) =      3.760 ms/op
     p(99.9000) =      7.095 ms/op
     p(99.9900) =     14.009 ms/op
     p(99.9990) =     14.739 ms/op
     p(99.9999) =     15.319 ms/op
    p(100.0000) =     15.319 ms/op


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
# Warmup Iteration   1: 3.927 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.594 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.546 ±(99.9%) 0.006 ms/op
Iteration   1: 2.508 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.046 ms/op
                 getUser·p0.50:   2.568 ms/op
                 getUser·p0.90:   3.043 ms/op
                 getUser·p0.95:   3.166 ms/op
                 getUser·p0.99:   3.957 ms/op
                 getUser·p0.999:  5.861 ms/op
                 getUser·p0.9999: 14.406 ms/op
                 getUser·p1.00:   14.664 ms/op

Iteration   2: 2.503 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.029 ms/op
                 getUser·p0.50:   2.560 ms/op
                 getUser·p0.90:   3.035 ms/op
                 getUser·p0.95:   3.166 ms/op
                 getUser·p0.99:   3.908 ms/op
                 getUser·p0.999:  8.280 ms/op
                 getUser·p0.9999: 14.828 ms/op
                 getUser·p1.00:   17.236 ms/op

Iteration   3: 2.505 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.855 ms/op
                 getUser·p0.50:   2.552 ms/op
                 getUser·p0.90:   3.043 ms/op
                 getUser·p0.95:   3.178 ms/op
                 getUser·p0.99:   3.912 ms/op
                 getUser·p0.999:  9.504 ms/op
                 getUser·p0.9999: 12.009 ms/op
                 getUser·p1.00:   12.435 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 382830
  mean =      2.506 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 43 
    [ 1.250,  2.500) = 187195 
    [ 2.500,  3.750) = 190506 
    [ 3.750,  5.000) = 4132 
    [ 5.000,  6.250) = 551 
    [ 6.250,  7.500) = 45 
    [ 7.500,  8.750) = 7 
    [ 8.750, 10.000) = 25 
    [10.000, 11.250) = 120 
    [11.250, 12.500) = 58 
    [12.500, 13.750) = 81 
    [13.750, 15.000) = 56 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.855 ms/op
     p(50.0000) =      2.560 ms/op
     p(90.0000) =      3.043 ms/op
     p(95.0000) =      3.170 ms/op
     p(99.0000) =      3.920 ms/op
     p(99.9000) =      6.498 ms/op
     p(99.9900) =     14.364 ms/op
     p(99.9990) =     16.085 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.705 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.115 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.066 ±(99.9%) 0.009 ms/op
Iteration   1: 3.034 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.930 ms/op
                 listUser·p0.50:   2.966 ms/op
                 listUser·p0.90:   3.916 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   5.693 ms/op
                 listUser·p0.999:  9.219 ms/op
                 listUser·p0.9999: 13.475 ms/op
                 listUser·p1.00:   14.303 ms/op

Iteration   2: 3.015 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.865 ms/op
                 listUser·p0.50:   2.953 ms/op
                 listUser·p0.90:   3.871 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   5.702 ms/op
                 listUser·p0.999:  10.666 ms/op
                 listUser·p0.9999: 12.655 ms/op
                 listUser·p1.00:   13.238 ms/op

Iteration   3: 3.017 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.888 ms/op
                 listUser·p0.50:   2.961 ms/op
                 listUser·p0.90:   3.899 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.538 ms/op
                 listUser·p0.999:  9.224 ms/op
                 listUser·p0.9999: 10.748 ms/op
                 listUser·p1.00:   11.829 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 317369
  mean =      3.022 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 119 
    [ 1.250,  2.500) = 89715 
    [ 2.500,  3.750) = 188101 
    [ 3.750,  5.000) = 31867 
    [ 5.000,  6.250) = 6178 
    [ 6.250,  7.500) = 748 
    [ 7.500,  8.750) = 182 
    [ 8.750, 10.000) = 206 
    [10.000, 11.250) = 175 
    [11.250, 12.500) = 44 
    [12.500, 13.750) = 29 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.865 ms/op
     p(50.0000) =      2.961 ms/op
     p(90.0000) =      3.895 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      5.636 ms/op
     p(99.9000) =      9.568 ms/op
     p(99.9900) =     12.554 ms/op
     p(99.9990) =     13.790 ms/op
     p(99.9999) =     14.303 ms/op
    p(100.0000) =     14.303 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.480 ± 1.972  ops/ms
ClientPb.existUser                       thrpt       3  13.053 ± 0.829  ops/ms
ClientPb.getUser                         thrpt       3  12.838 ± 1.201  ops/ms
ClientPb.listUser                        thrpt       3  10.546 ± 0.484  ops/ms
ClientPb.createUser                       avgt       3   2.549 ± 0.372   ms/op
ClientPb.existUser                        avgt       3   2.457 ± 0.380   ms/op
ClientPb.getUser                          avgt       3   2.510 ± 0.458   ms/op
ClientPb.listUser                         avgt       3   3.007 ± 0.036   ms/op
ClientPb.createUser                     sample  381030   2.517 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.480           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.576           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.060           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.191           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.850           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.995           ms/op
ClientPb.createUser:createUser·p0.9999  sample          16.235           ms/op
ClientPb.createUser:createUser·p1.00    sample          17.433           ms/op
ClientPb.existUser                      sample  389477   2.462 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.828           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.540           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.990           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.105           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.760           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.095           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.009           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.319           ms/op
ClientPb.getUser                        sample  382830   2.506 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.855           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.560           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.043           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.170           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.920           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.498           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.364           ms/op
ClientPb.getUser:getUser·p1.00          sample          17.236           ms/op
ClientPb.listUser                       sample  317369   3.022 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.865           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.961           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.895           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.383           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.636           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.568           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.554           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.303           ms/op
