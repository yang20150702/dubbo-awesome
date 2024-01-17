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
# Warmup Iteration   1: 4.716 ops/ms
# Warmup Iteration   2: 11.983 ops/ms
# Warmup Iteration   3: 11.995 ops/ms
Iteration   1: 12.405 ops/ms
Iteration   2: 12.452 ops/ms
Iteration   3: 12.437 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.431 ±(99.9%) 0.435 ops/ms [Average]
  (min, avg, max) = (12.405, 12.431, 12.452), stdev = 0.024
  CI (99.9%): [11.996, 12.867] (assumes normal distribution)


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
# Warmup Iteration   1: 8.148 ops/ms
# Warmup Iteration   2: 12.984 ops/ms
# Warmup Iteration   3: 13.031 ops/ms
Iteration   1: 13.044 ops/ms
Iteration   2: 13.110 ops/ms
Iteration   3: 12.801 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.985 ±(99.9%) 2.968 ops/ms [Average]
  (min, avg, max) = (12.801, 12.985, 13.110), stdev = 0.163
  CI (99.9%): [10.017, 15.953] (assumes normal distribution)


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
# Warmup Iteration   1: 7.504 ops/ms
# Warmup Iteration   2: 12.428 ops/ms
# Warmup Iteration   3: 12.790 ops/ms
Iteration   1: 12.831 ops/ms
Iteration   2: 12.858 ops/ms
Iteration   3: 12.860 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.850 ±(99.9%) 0.294 ops/ms [Average]
  (min, avg, max) = (12.831, 12.850, 12.860), stdev = 0.016
  CI (99.9%): [12.556, 13.144] (assumes normal distribution)


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
# Warmup Iteration   1: 6.624 ops/ms
# Warmup Iteration   2: 10.385 ops/ms
# Warmup Iteration   3: 10.708 ops/ms
Iteration   1: 10.722 ops/ms
Iteration   2: 10.606 ops/ms
Iteration   3: 10.643 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.657 ±(99.9%) 1.084 ops/ms [Average]
  (min, avg, max) = (10.606, 10.657, 10.722), stdev = 0.059
  CI (99.9%): [9.573, 11.742] (assumes normal distribution)


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
# Warmup Iteration   1: 4.254 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.606 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.556 ±(99.9%) 0.003 ms/op
Iteration   1: 2.568 ±(99.9%) 0.004 ms/op
Iteration   2: 2.555 ±(99.9%) 0.005 ms/op
Iteration   3: 2.572 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.565 ±(99.9%) 0.164 ms/op [Average]
  (min, avg, max) = (2.555, 2.565, 2.572), stdev = 0.009
  CI (99.9%): [2.401, 2.729] (assumes normal distribution)


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
# Warmup Iteration   1: 3.766 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.497 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.427 ±(99.9%) 0.003 ms/op
Iteration   1: 2.433 ±(99.9%) 0.003 ms/op
Iteration   2: 2.460 ±(99.9%) 0.004 ms/op
Iteration   3: 2.470 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.454 ±(99.9%) 0.353 ms/op [Average]
  (min, avg, max) = (2.433, 2.454, 2.470), stdev = 0.019
  CI (99.9%): [2.101, 2.808] (assumes normal distribution)


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
# Warmup Iteration   1: 3.916 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.596 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.536 ±(99.9%) 0.004 ms/op
Iteration   1: 2.542 ±(99.9%) 0.004 ms/op
Iteration   2: 2.520 ±(99.9%) 0.004 ms/op
Iteration   3: 2.541 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.534 ±(99.9%) 0.221 ms/op [Average]
  (min, avg, max) = (2.520, 2.534, 2.542), stdev = 0.012
  CI (99.9%): [2.313, 2.755] (assumes normal distribution)


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
# Warmup Iteration   1: 4.604 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.055 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.062 ±(99.9%) 0.006 ms/op
Iteration   1: 3.019 ±(99.9%) 0.004 ms/op
Iteration   2: 3.035 ±(99.9%) 0.004 ms/op
Iteration   3: 3.056 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.037 ±(99.9%) 0.338 ms/op [Average]
  (min, avg, max) = (3.019, 3.037, 3.056), stdev = 0.019
  CI (99.9%): [2.699, 3.374] (assumes normal distribution)


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
# Warmup Iteration   1: 4.111 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.679 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.553 ±(99.9%) 0.006 ms/op
Iteration   1: 2.568 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.043 ms/op
                 createUser·p0.50:   2.634 ms/op
                 createUser·p0.90:   3.121 ms/op
                 createUser·p0.95:   3.240 ms/op
                 createUser·p0.99:   3.793 ms/op
                 createUser·p0.999:  11.576 ms/op
                 createUser·p0.9999: 13.755 ms/op
                 createUser·p1.00:   13.992 ms/op

Iteration   2: 2.551 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.979 ms/op
                 createUser·p0.50:   2.597 ms/op
                 createUser·p0.90:   3.097 ms/op
                 createUser·p0.95:   3.215 ms/op
                 createUser·p0.99:   3.830 ms/op
                 createUser·p0.999:  9.716 ms/op
                 createUser·p0.9999: 13.745 ms/op
                 createUser·p1.00:   14.254 ms/op

Iteration   3: 2.592 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.863 ms/op
                 createUser·p0.50:   2.626 ms/op
                 createUser·p0.90:   3.154 ms/op
                 createUser·p0.95:   3.310 ms/op
                 createUser·p0.99:   4.243 ms/op
                 createUser·p0.999:  8.684 ms/op
                 createUser·p0.9999: 11.534 ms/op
                 createUser·p1.00:   14.598 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 373038
  mean =      2.570 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 52 
    [ 1.250,  2.500) = 177860 
    [ 2.500,  3.750) = 189823 
    [ 3.750,  5.000) = 4205 
    [ 5.000,  6.250) = 603 
    [ 6.250,  7.500) = 69 
    [ 7.500,  8.750) = 54 
    [ 8.750, 10.000) = 74 
    [10.000, 11.250) = 87 
    [11.250, 12.500) = 96 
    [12.500, 13.750) = 90 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.863 ms/op
     p(50.0000) =      2.617 ms/op
     p(90.0000) =      3.125 ms/op
     p(95.0000) =      3.252 ms/op
     p(99.0000) =      3.973 ms/op
     p(99.9000) =      8.748 ms/op
     p(99.9900) =     13.622 ms/op
     p(99.9990) =     14.206 ms/op
     p(99.9999) =     14.598 ms/op
    p(100.0000) =     14.598 ms/op


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
# Warmup Iteration   1: 3.697 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.468 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.445 ±(99.9%) 0.005 ms/op
Iteration   1: 2.466 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.919 ms/op
                 existUser·p0.50:   2.523 ms/op
                 existUser·p0.90:   2.998 ms/op
                 existUser·p0.95:   3.097 ms/op
                 existUser·p0.99:   3.506 ms/op
                 existUser·p0.999:  6.374 ms/op
                 existUser·p0.9999: 14.092 ms/op
                 existUser·p1.00:   14.713 ms/op

Iteration   2: 2.468 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.864 ms/op
                 existUser·p0.50:   2.523 ms/op
                 existUser·p0.90:   3.002 ms/op
                 existUser·p0.95:   3.113 ms/op
                 existUser·p0.99:   3.695 ms/op
                 existUser·p0.999:  8.707 ms/op
                 existUser·p0.9999: 12.815 ms/op
                 existUser·p1.00:   13.435 ms/op

Iteration   3: 2.475 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.941 ms/op
                 existUser·p0.50:   2.486 ms/op
                 existUser·p0.90:   3.027 ms/op
                 existUser·p0.95:   3.158 ms/op
                 existUser·p0.99:   3.879 ms/op
                 existUser·p0.999:  5.784 ms/op
                 existUser·p0.9999: 12.868 ms/op
                 existUser·p1.00:   13.713 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 388288
  mean =      2.470 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 61 
    [ 1.250,  2.500) = 193451 
    [ 2.500,  3.750) = 191193 
    [ 3.750,  5.000) = 2887 
    [ 5.000,  6.250) = 307 
    [ 6.250,  7.500) = 14 
    [ 7.500,  8.750) = 26 
    [ 8.750, 10.000) = 74 
    [10.000, 11.250) = 56 
    [11.250, 12.500) = 84 
    [12.500, 13.750) = 113 
    [13.750, 15.000) = 22 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.864 ms/op
     p(50.0000) =      2.507 ms/op
     p(90.0000) =      3.006 ms/op
     p(95.0000) =      3.121 ms/op
     p(99.0000) =      3.703 ms/op
     p(99.9000) =      6.298 ms/op
     p(99.9900) =     13.520 ms/op
     p(99.9990) =     14.394 ms/op
     p(99.9999) =     14.713 ms/op
    p(100.0000) =     14.713 ms/op


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
# Warmup Iteration   1: 3.904 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.521 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.472 ±(99.9%) 0.005 ms/op
Iteration   1: 2.474 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.873 ms/op
                 getUser·p0.50:   2.494 ms/op
                 getUser·p0.90:   3.015 ms/op
                 getUser·p0.95:   3.129 ms/op
                 getUser·p0.99:   3.547 ms/op
                 getUser·p0.999:  6.394 ms/op
                 getUser·p0.9999: 13.603 ms/op
                 getUser·p1.00:   14.402 ms/op

Iteration   2: 2.545 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.887 ms/op
                 getUser·p0.50:   2.580 ms/op
                 getUser·p0.90:   3.088 ms/op
                 getUser·p0.95:   3.351 ms/op
                 getUser·p0.99:   5.005 ms/op
                 getUser·p0.999:  6.715 ms/op
                 getUser·p0.9999: 18.481 ms/op
                 getUser·p1.00:   18.711 ms/op

Iteration   3: 2.474 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.876 ms/op
                 getUser·p0.50:   2.515 ms/op
                 getUser·p0.90:   3.015 ms/op
                 getUser·p0.95:   3.146 ms/op
                 getUser·p0.99:   3.760 ms/op
                 getUser·p0.999:  5.968 ms/op
                 getUser·p0.9999: 11.633 ms/op
                 getUser·p1.00:   11.960 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 384104
  mean =      2.497 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 54 
    [ 1.250,  2.500) = 189219 
    [ 2.500,  3.750) = 188740 
    [ 3.750,  5.000) = 4435 
    [ 5.000,  6.250) = 1236 
    [ 6.250,  7.500) = 75 
    [ 7.500,  8.750) = 25 
    [ 8.750, 10.000) = 48 
    [10.000, 11.250) = 64 
    [11.250, 12.500) = 112 
    [12.500, 13.750) = 56 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 9 
    [17.500, 18.750) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.873 ms/op
     p(50.0000) =      2.535 ms/op
     p(90.0000) =      3.035 ms/op
     p(95.0000) =      3.187 ms/op
     p(99.0000) =      4.125 ms/op
     p(99.9000) =      6.536 ms/op
     p(99.9900) =     13.887 ms/op
     p(99.9990) =     18.547 ms/op
     p(99.9999) =     18.711 ms/op
    p(100.0000) =     18.711 ms/op


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
# Warmup Iteration   1: 4.827 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.114 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.074 ±(99.9%) 0.009 ms/op
Iteration   1: 3.077 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.887 ms/op
                 listUser·p0.50:   3.006 ms/op
                 listUser·p0.90:   3.990 ms/op
                 listUser·p0.95:   4.522 ms/op
                 listUser·p0.99:   5.734 ms/op
                 listUser·p0.999:  9.519 ms/op
                 listUser·p0.9999: 12.445 ms/op
                 listUser·p1.00:   13.861 ms/op

Iteration   2: 3.053 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.963 ms/op
                 listUser·p0.50:   2.990 ms/op
                 listUser·p0.90:   3.932 ms/op
                 listUser·p0.95:   4.440 ms/op
                 listUser·p0.99:   5.603 ms/op
                 listUser·p0.999:  10.147 ms/op
                 listUser·p0.9999: 11.797 ms/op
                 listUser·p1.00:   12.485 ms/op

Iteration   3: 3.055 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.899 ms/op
                 listUser·p0.50:   2.986 ms/op
                 listUser·p0.90:   3.940 ms/op
                 listUser·p0.95:   4.473 ms/op
                 listUser·p0.99:   5.685 ms/op
                 listUser·p0.999:  9.574 ms/op
                 listUser·p0.9999: 11.462 ms/op
                 listUser·p1.00:   12.222 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 313231
  mean =      3.062 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 95 
    [ 1.250,  2.500) = 81849 
    [ 2.500,  3.750) = 188898 
    [ 3.750,  5.000) = 34326 
    [ 5.000,  6.250) = 6618 
    [ 6.250,  7.500) = 778 
    [ 7.500,  8.750) = 193 
    [ 8.750, 10.000) = 222 
    [10.000, 11.250) = 168 
    [11.250, 12.500) = 75 
    [12.500, 13.750) = 8 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.887 ms/op
     p(50.0000) =      2.994 ms/op
     p(90.0000) =      3.957 ms/op
     p(95.0000) =      4.481 ms/op
     p(99.0000) =      5.677 ms/op
     p(99.9000) =      9.699 ms/op
     p(99.9900) =     12.173 ms/op
     p(99.9990) =     13.035 ms/op
     p(99.9999) =     13.861 ms/op
    p(100.0000) =     13.861 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.431 ± 0.435  ops/ms
ClientPb.existUser                       thrpt       3  12.985 ± 2.968  ops/ms
ClientPb.getUser                         thrpt       3  12.850 ± 0.294  ops/ms
ClientPb.listUser                        thrpt       3  10.657 ± 1.084  ops/ms
ClientPb.createUser                       avgt       3   2.565 ± 0.164   ms/op
ClientPb.existUser                        avgt       3   2.454 ± 0.353   ms/op
ClientPb.getUser                          avgt       3   2.534 ± 0.221   ms/op
ClientPb.listUser                         avgt       3   3.037 ± 0.338   ms/op
ClientPb.createUser                     sample  373038   2.570 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.863           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.617           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.125           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.252           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.973           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.748           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.622           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.598           ms/op
ClientPb.existUser                      sample  388288   2.470 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.864           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.507           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.006           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.121           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.703           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.298           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.520           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.713           ms/op
ClientPb.getUser                        sample  384104   2.497 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.873           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.535           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.035           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.187           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.125           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.536           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.887           ms/op
ClientPb.getUser:getUser·p1.00          sample          18.711           ms/op
ClientPb.listUser                       sample  313231   3.062 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.887           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.994           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.957           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.481           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.677           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.699           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.173           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.861           ms/op
