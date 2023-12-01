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
# Warmup Iteration   1: 4.932 ops/ms
# Warmup Iteration   2: 11.709 ops/ms
# Warmup Iteration   3: 11.877 ops/ms
Iteration   1: 12.157 ops/ms
Iteration   2: 12.123 ops/ms
Iteration   3: 12.319 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.200 ±(99.9%) 1.909 ops/ms [Average]
  (min, avg, max) = (12.123, 12.200, 12.319), stdev = 0.105
  CI (99.9%): [10.291, 14.108] (assumes normal distribution)


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
# Warmup Iteration   1: 7.408 ops/ms
# Warmup Iteration   2: 12.882 ops/ms
# Warmup Iteration   3: 12.789 ops/ms
Iteration   1: 12.726 ops/ms
Iteration   2: 12.793 ops/ms
Iteration   3: 12.833 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.784 ±(99.9%) 0.992 ops/ms [Average]
  (min, avg, max) = (12.726, 12.784, 12.833), stdev = 0.054
  CI (99.9%): [11.792, 13.776] (assumes normal distribution)


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
# Warmup Iteration   1: 7.850 ops/ms
# Warmup Iteration   2: 12.394 ops/ms
# Warmup Iteration   3: 12.515 ops/ms
Iteration   1: 12.642 ops/ms
Iteration   2: 12.696 ops/ms
Iteration   3: 12.557 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.632 ±(99.9%) 1.279 ops/ms [Average]
  (min, avg, max) = (12.557, 12.632, 12.696), stdev = 0.070
  CI (99.9%): [11.353, 13.910] (assumes normal distribution)


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
# Warmup Iteration   1: 6.621 ops/ms
# Warmup Iteration   2: 10.309 ops/ms
# Warmup Iteration   3: 10.484 ops/ms
Iteration   1: 10.427 ops/ms
Iteration   2: 10.490 ops/ms
Iteration   3: 10.540 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.485 ±(99.9%) 1.033 ops/ms [Average]
  (min, avg, max) = (10.427, 10.485, 10.540), stdev = 0.057
  CI (99.9%): [9.452, 11.519] (assumes normal distribution)


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
# Warmup Iteration   1: 3.973 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.638 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.544 ±(99.9%) 0.005 ms/op
Iteration   1: 2.551 ±(99.9%) 0.004 ms/op
Iteration   2: 2.598 ±(99.9%) 0.005 ms/op
Iteration   3: 2.562 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.570 ±(99.9%) 0.450 ms/op [Average]
  (min, avg, max) = (2.551, 2.570, 2.598), stdev = 0.025
  CI (99.9%): [2.120, 3.020] (assumes normal distribution)


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
# Warmup Iteration   1: 3.843 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.493 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.521 ±(99.9%) 0.005 ms/op
Iteration   1: 2.526 ±(99.9%) 0.005 ms/op
Iteration   2: 2.511 ±(99.9%) 0.003 ms/op
Iteration   3: 2.520 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.519 ±(99.9%) 0.137 ms/op [Average]
  (min, avg, max) = (2.511, 2.519, 2.526), stdev = 0.008
  CI (99.9%): [2.382, 2.656] (assumes normal distribution)


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
# Warmup Iteration   1: 3.896 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.559 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.506 ±(99.9%) 0.004 ms/op
Iteration   1: 2.530 ±(99.9%) 0.004 ms/op
Iteration   2: 2.513 ±(99.9%) 0.004 ms/op
Iteration   3: 2.520 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.521 ±(99.9%) 0.151 ms/op [Average]
  (min, avg, max) = (2.513, 2.521, 2.530), stdev = 0.008
  CI (99.9%): [2.370, 2.672] (assumes normal distribution)


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
# Warmup Iteration   1: 4.836 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.072 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.074 ±(99.9%) 0.004 ms/op
Iteration   1: 3.033 ±(99.9%) 0.005 ms/op
Iteration   2: 3.044 ±(99.9%) 0.005 ms/op
Iteration   3: 3.037 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.038 ±(99.9%) 0.099 ms/op [Average]
  (min, avg, max) = (3.033, 3.038, 3.044), stdev = 0.005
  CI (99.9%): [2.939, 3.137] (assumes normal distribution)


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
# Warmup Iteration   1: 4.068 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.668 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.530 ±(99.9%) 0.006 ms/op
Iteration   1: 2.544 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.069 ms/op
                 createUser·p0.50:   2.613 ms/op
                 createUser·p0.90:   3.092 ms/op
                 createUser·p0.95:   3.228 ms/op
                 createUser·p0.99:   3.940 ms/op
                 createUser·p0.999:  11.802 ms/op
                 createUser·p0.9999: 13.737 ms/op
                 createUser·p1.00:   14.615 ms/op

Iteration   2: 2.534 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.217 ms/op
                 createUser·p0.50:   2.634 ms/op
                 createUser·p0.90:   3.072 ms/op
                 createUser·p0.95:   3.174 ms/op
                 createUser·p0.99:   3.650 ms/op
                 createUser·p0.999:  9.626 ms/op
                 createUser·p0.9999: 17.138 ms/op
                 createUser·p1.00:   18.285 ms/op

Iteration   3: 2.544 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.798 ms/op
                 createUser·p0.50:   2.634 ms/op
                 createUser·p0.90:   3.088 ms/op
                 createUser·p0.95:   3.224 ms/op
                 createUser·p0.99:   4.002 ms/op
                 createUser·p0.999:  9.001 ms/op
                 createUser·p0.9999: 12.091 ms/op
                 createUser·p1.00:   12.763 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 377455
  mean =      2.541 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 27 
    [ 1.250,  2.500) = 179884 
    [ 2.500,  3.750) = 192870 
    [ 3.750,  5.000) = 3723 
    [ 5.000,  6.250) = 502 
    [ 6.250,  7.500) = 35 
    [ 7.500,  8.750) = 27 
    [ 8.750, 10.000) = 79 
    [10.000, 11.250) = 91 
    [11.250, 12.500) = 80 
    [12.500, 13.750) = 95 
    [13.750, 15.000) = 10 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 28 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.798 ms/op
     p(50.0000) =      2.626 ms/op
     p(90.0000) =      3.084 ms/op
     p(95.0000) =      3.207 ms/op
     p(99.0000) =      3.883 ms/op
     p(99.9000) =      9.176 ms/op
     p(99.9900) =     14.324 ms/op
     p(99.9990) =     17.488 ms/op
     p(99.9999) =     18.285 ms/op
    p(100.0000) =     18.285 ms/op


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
# Warmup Iteration   1: 3.932 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.536 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.502 ±(99.9%) 0.005 ms/op
Iteration   1: 2.519 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.766 ms/op
                 existUser·p0.50:   2.593 ms/op
                 existUser·p0.90:   3.056 ms/op
                 existUser·p0.95:   3.178 ms/op
                 existUser·p0.99:   3.912 ms/op
                 existUser·p0.999:  10.684 ms/op
                 existUser·p0.9999: 13.489 ms/op
                 existUser·p1.00:   14.270 ms/op

Iteration   2: 2.491 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.012 ms/op
                 existUser·p0.50:   2.589 ms/op
                 existUser·p0.90:   3.019 ms/op
                 existUser·p0.95:   3.121 ms/op
                 existUser·p0.99:   3.674 ms/op
                 existUser·p0.999:  5.707 ms/op
                 existUser·p0.9999: 12.667 ms/op
                 existUser·p1.00:   13.500 ms/op

Iteration   3: 2.494 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.735 ms/op
                 existUser·p0.50:   2.568 ms/op
                 existUser·p0.90:   3.023 ms/op
                 existUser·p0.95:   3.133 ms/op
                 existUser·p0.99:   3.699 ms/op
                 existUser·p0.999:  9.257 ms/op
                 existUser·p0.9999: 12.042 ms/op
                 existUser·p1.00:   12.337 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 383389
  mean =      2.501 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 60 
    [ 1.250,  2.500) = 184932 
    [ 2.500,  3.750) = 194520 
    [ 3.750,  5.000) = 3028 
    [ 5.000,  6.250) = 421 
    [ 6.250,  7.500) = 48 
    [ 7.500,  8.750) = 17 
    [ 8.750, 10.000) = 50 
    [10.000, 11.250) = 107 
    [11.250, 12.500) = 100 
    [12.500, 13.750) = 99 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.735 ms/op
     p(50.0000) =      2.585 ms/op
     p(90.0000) =      3.035 ms/op
     p(95.0000) =      3.146 ms/op
     p(99.0000) =      3.756 ms/op
     p(99.9000) =      7.243 ms/op
     p(99.9900) =     13.173 ms/op
     p(99.9990) =     13.937 ms/op
     p(99.9999) =     14.270 ms/op
    p(100.0000) =     14.270 ms/op


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
# Warmup Iteration   1: 3.978 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.567 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.558 ±(99.9%) 0.006 ms/op
Iteration   1: 2.493 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.970 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   3.035 ms/op
                 getUser·p0.95:   3.142 ms/op
                 getUser·p0.99:   3.706 ms/op
                 getUser·p0.999:  10.572 ms/op
                 getUser·p0.9999: 14.194 ms/op
                 getUser·p1.00:   14.877 ms/op

Iteration   2: 2.506 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.876 ms/op
                 getUser·p0.50:   2.535 ms/op
                 getUser·p0.90:   3.052 ms/op
                 getUser·p0.95:   3.187 ms/op
                 getUser·p0.99:   4.010 ms/op
                 getUser·p0.999:  9.944 ms/op
                 getUser·p0.9999: 13.025 ms/op
                 getUser·p1.00:   13.959 ms/op

Iteration   3: 2.538 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.971 ms/op
                 getUser·p0.50:   2.572 ms/op
                 getUser·p0.90:   3.092 ms/op
                 getUser·p0.95:   3.244 ms/op
                 getUser·p0.99:   4.166 ms/op
                 getUser·p0.999:  9.193 ms/op
                 getUser·p0.9999: 11.911 ms/op
                 getUser·p1.00:   12.190 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 381713
  mean =      2.512 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 83 
    [ 1.250,  2.500) = 187586 
    [ 2.500,  3.750) = 188731 
    [ 3.750,  5.000) = 4083 
    [ 5.000,  6.250) = 770 
    [ 6.250,  7.500) = 36 
    [ 7.500,  8.750) = 31 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 138 
    [11.250, 12.500) = 105 
    [12.500, 13.750) = 87 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.876 ms/op
     p(50.0000) =      2.548 ms/op
     p(90.0000) =      3.060 ms/op
     p(95.0000) =      3.191 ms/op
     p(99.0000) =      3.965 ms/op
     p(99.9000) =      9.409 ms/op
     p(99.9900) =     13.664 ms/op
     p(99.9990) =     14.844 ms/op
     p(99.9999) =     14.877 ms/op
    p(100.0000) =     14.877 ms/op


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
# Warmup Iteration   1: 4.630 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.058 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.024 ±(99.9%) 0.009 ms/op
Iteration   1: 2.999 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.077 ms/op
                 listUser·p0.50:   2.937 ms/op
                 listUser·p0.90:   3.858 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   5.554 ms/op
                 listUser·p0.999:  9.789 ms/op
                 listUser·p0.9999: 12.321 ms/op
                 listUser·p1.00:   13.566 ms/op

Iteration   2: 2.998 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.779 ms/op
                 listUser·p0.50:   2.945 ms/op
                 listUser·p0.90:   3.875 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   5.505 ms/op
                 listUser·p0.999:  9.896 ms/op
                 listUser·p0.9999: 11.960 ms/op
                 listUser·p1.00:   12.190 ms/op

Iteration   3: 3.025 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.854 ms/op
                 listUser·p0.50:   2.957 ms/op
                 listUser·p0.90:   3.912 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   5.571 ms/op
                 listUser·p0.999:  9.901 ms/op
                 listUser·p0.9999: 12.489 ms/op
                 listUser·p1.00:   13.418 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 318875
  mean =      3.008 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 131 
    [ 1.250,  2.500) = 93523 
    [ 2.500,  3.750) = 186265 
    [ 3.750,  5.000) = 31775 
    [ 5.000,  6.250) = 5867 
    [ 6.250,  7.500) = 576 
    [ 7.500,  8.750) = 133 
    [ 8.750, 10.000) = 332 
    [10.000, 11.250) = 200 
    [11.250, 12.500) = 59 
    [12.500, 13.750) = 14 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.779 ms/op
     p(50.0000) =      2.945 ms/op
     p(90.0000) =      3.883 ms/op
     p(95.0000) =      4.391 ms/op
     p(99.0000) =      5.546 ms/op
     p(99.9000) =      9.847 ms/op
     p(99.9900) =     12.111 ms/op
     p(99.9990) =     13.397 ms/op
     p(99.9999) =     13.566 ms/op
    p(100.0000) =     13.566 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.200 ± 1.909  ops/ms
ClientPb.existUser                       thrpt       3  12.784 ± 0.992  ops/ms
ClientPb.getUser                         thrpt       3  12.632 ± 1.279  ops/ms
ClientPb.listUser                        thrpt       3  10.485 ± 1.033  ops/ms
ClientPb.createUser                       avgt       3   2.570 ± 0.450   ms/op
ClientPb.existUser                        avgt       3   2.519 ± 0.137   ms/op
ClientPb.getUser                          avgt       3   2.521 ± 0.151   ms/op
ClientPb.listUser                         avgt       3   3.038 ± 0.099   ms/op
ClientPb.createUser                     sample  377455   2.541 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.798           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.626           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.084           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.207           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.883           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.176           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.324           ms/op
ClientPb.createUser:createUser·p1.00    sample          18.285           ms/op
ClientPb.existUser                      sample  383389   2.501 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.735           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.585           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.035           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.146           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.756           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.243           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.173           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.270           ms/op
ClientPb.getUser                        sample  381713   2.512 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.876           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.548           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.060           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.191           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.965           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.409           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.664           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.877           ms/op
ClientPb.listUser                       sample  318875   3.008 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.779           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.945           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.883           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.391           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.546           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.847           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.111           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.566           ms/op
