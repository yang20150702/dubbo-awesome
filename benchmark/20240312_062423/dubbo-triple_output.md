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
# Warmup Iteration   1: 4.854 ops/ms
# Warmup Iteration   2: 12.410 ops/ms
# Warmup Iteration   3: 12.621 ops/ms
Iteration   1: 12.779 ops/ms
Iteration   2: 12.820 ops/ms
Iteration   3: 12.810 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.803 ±(99.9%) 0.391 ops/ms [Average]
  (min, avg, max) = (12.779, 12.803, 12.820), stdev = 0.021
  CI (99.9%): [12.412, 13.194] (assumes normal distribution)


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
# Warmup Iteration   1: 8.008 ops/ms
# Warmup Iteration   2: 12.984 ops/ms
# Warmup Iteration   3: 13.144 ops/ms
Iteration   1: 12.960 ops/ms
Iteration   2: 13.029 ops/ms
Iteration   3: 13.067 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.019 ±(99.9%) 0.989 ops/ms [Average]
  (min, avg, max) = (12.960, 13.019, 13.067), stdev = 0.054
  CI (99.9%): [12.030, 14.008] (assumes normal distribution)


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
# Warmup Iteration   1: 7.940 ops/ms
# Warmup Iteration   2: 12.414 ops/ms
# Warmup Iteration   3: 12.693 ops/ms
Iteration   1: 12.729 ops/ms
Iteration   2: 12.622 ops/ms
Iteration   3: 12.716 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.689 ±(99.9%) 1.066 ops/ms [Average]
  (min, avg, max) = (12.622, 12.689, 12.729), stdev = 0.058
  CI (99.9%): [11.623, 13.756] (assumes normal distribution)


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
# Warmup Iteration   1: 6.942 ops/ms
# Warmup Iteration   2: 10.596 ops/ms
# Warmup Iteration   3: 10.621 ops/ms
Iteration   1: 10.745 ops/ms
Iteration   2: 10.640 ops/ms
Iteration   3: 10.696 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.694 ±(99.9%) 0.956 ops/ms [Average]
  (min, avg, max) = (10.640, 10.694, 10.745), stdev = 0.052
  CI (99.9%): [9.737, 11.650] (assumes normal distribution)


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
# Warmup Iteration   1: 4.085 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.579 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.450 ±(99.9%) 0.003 ms/op
Iteration   1: 2.502 ±(99.9%) 0.004 ms/op
Iteration   2: 2.486 ±(99.9%) 0.004 ms/op
Iteration   3: 2.482 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.490 ±(99.9%) 0.191 ms/op [Average]
  (min, avg, max) = (2.482, 2.490, 2.502), stdev = 0.010
  CI (99.9%): [2.299, 2.682] (assumes normal distribution)


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
# Warmup Iteration   1: 3.674 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.432 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.443 ±(99.9%) 0.004 ms/op
Iteration   1: 2.423 ±(99.9%) 0.005 ms/op
Iteration   2: 2.425 ±(99.9%) 0.004 ms/op
Iteration   3: 2.445 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.431 ±(99.9%) 0.223 ms/op [Average]
  (min, avg, max) = (2.423, 2.431, 2.445), stdev = 0.012
  CI (99.9%): [2.209, 2.654] (assumes normal distribution)


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
# Warmup Iteration   1: 4.070 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.582 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.494 ±(99.9%) 0.004 ms/op
Iteration   1: 2.481 ±(99.9%) 0.005 ms/op
Iteration   2: 2.490 ±(99.9%) 0.004 ms/op
Iteration   3: 2.477 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.483 ±(99.9%) 0.122 ms/op [Average]
  (min, avg, max) = (2.477, 2.483, 2.490), stdev = 0.007
  CI (99.9%): [2.361, 2.604] (assumes normal distribution)


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
# Warmup Iteration   1: 4.621 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.056 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.984 ±(99.9%) 0.005 ms/op
Iteration   1: 2.984 ±(99.9%) 0.005 ms/op
Iteration   2: 2.966 ±(99.9%) 0.004 ms/op
Iteration   3: 2.986 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.979 ±(99.9%) 0.198 ms/op [Average]
  (min, avg, max) = (2.966, 2.979, 2.986), stdev = 0.011
  CI (99.9%): [2.781, 3.177] (assumes normal distribution)


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
# Warmup Iteration   1: 4.187 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.641 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.478 ±(99.9%) 0.006 ms/op
Iteration   1: 2.503 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.009 ms/op
                 createUser·p0.50:   2.556 ms/op
                 createUser·p0.90:   3.043 ms/op
                 createUser·p0.95:   3.166 ms/op
                 createUser·p0.99:   3.703 ms/op
                 createUser·p0.999:  10.413 ms/op
                 createUser·p0.9999: 14.647 ms/op
                 createUser·p1.00:   15.434 ms/op

Iteration   2: 2.478 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.952 ms/op
                 createUser·p0.50:   2.531 ms/op
                 createUser·p0.90:   3.019 ms/op
                 createUser·p0.95:   3.142 ms/op
                 createUser·p0.99:   3.711 ms/op
                 createUser·p0.999:  9.421 ms/op
                 createUser·p0.9999: 13.396 ms/op
                 createUser·p1.00:   14.418 ms/op

Iteration   3: 2.497 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.940 ms/op
                 createUser·p0.50:   2.556 ms/op
                 createUser·p0.90:   3.031 ms/op
                 createUser·p0.95:   3.146 ms/op
                 createUser·p0.99:   3.731 ms/op
                 createUser·p0.999:  8.606 ms/op
                 createUser·p0.9999: 10.686 ms/op
                 createUser·p1.00:   12.534 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 384665
  mean =      2.493 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 63 
    [ 1.250,  2.500) = 187878 
    [ 2.500,  3.750) = 193115 
    [ 3.750,  5.000) = 2845 
    [ 5.000,  6.250) = 312 
    [ 6.250,  7.500) = 26 
    [ 7.500,  8.750) = 43 
    [ 8.750, 10.000) = 110 
    [10.000, 11.250) = 89 
    [11.250, 12.500) = 69 
    [12.500, 13.750) = 79 
    [13.750, 15.000) = 34 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.940 ms/op
     p(50.0000) =      2.548 ms/op
     p(90.0000) =      3.031 ms/op
     p(95.0000) =      3.150 ms/op
     p(99.0000) =      3.711 ms/op
     p(99.9000) =      8.629 ms/op
     p(99.9900) =     13.681 ms/op
     p(99.9990) =     14.845 ms/op
     p(99.9999) =     15.434 ms/op
    p(100.0000) =     15.434 ms/op


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
# Warmup Iteration   1: 3.778 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.450 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.448 ±(99.9%) 0.005 ms/op
Iteration   1: 2.435 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.889 ms/op
                 existUser·p0.50:   2.503 ms/op
                 existUser·p0.90:   2.961 ms/op
                 existUser·p0.95:   3.072 ms/op
                 existUser·p0.99:   3.510 ms/op
                 existUser·p0.999:  9.492 ms/op
                 existUser·p0.9999: 13.361 ms/op
                 existUser·p1.00:   14.549 ms/op

Iteration   2: 2.419 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.014 ms/op
                 existUser·p0.50:   2.494 ms/op
                 existUser·p0.90:   2.937 ms/op
                 existUser·p0.95:   3.031 ms/op
                 existUser·p0.99:   3.569 ms/op
                 existUser·p0.999:  5.615 ms/op
                 existUser·p0.9999: 13.468 ms/op
                 existUser·p1.00:   13.959 ms/op

Iteration   3: 2.452 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.896 ms/op
                 existUser·p0.50:   2.458 ms/op
                 existUser·p0.90:   2.994 ms/op
                 existUser·p0.95:   3.125 ms/op
                 existUser·p0.99:   3.976 ms/op
                 existUser·p0.999:  8.765 ms/op
                 existUser·p0.9999: 11.796 ms/op
                 existUser·p1.00:   11.960 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 393811
  mean =      2.435 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 64 
    [ 1.250,  2.500) = 198542 
    [ 2.500,  3.750) = 191738 
    [ 3.750,  5.000) = 2622 
    [ 5.000,  6.250) = 387 
    [ 6.250,  7.500) = 62 
    [ 7.500,  8.750) = 34 
    [ 8.750, 10.000) = 83 
    [10.000, 11.250) = 96 
    [11.250, 12.500) = 88 
    [12.500, 13.750) = 83 
    [13.750, 15.000) = 12 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.889 ms/op
     p(50.0000) =      2.482 ms/op
     p(90.0000) =      2.961 ms/op
     p(95.0000) =      3.076 ms/op
     p(99.0000) =      3.662 ms/op
     p(99.9000) =      7.590 ms/op
     p(99.9900) =     13.199 ms/op
     p(99.9990) =     14.467 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.915 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.569 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.518 ±(99.9%) 0.006 ms/op
Iteration   1: 2.458 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.819 ms/op
                 getUser·p0.50:   2.486 ms/op
                 getUser·p0.90:   2.982 ms/op
                 getUser·p0.95:   3.088 ms/op
                 getUser·p0.99:   3.600 ms/op
                 getUser·p0.999:  6.878 ms/op
                 getUser·p0.9999: 14.516 ms/op
                 getUser·p1.00:   15.466 ms/op

Iteration   2: 2.536 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.926 ms/op
                 getUser·p0.50:   2.552 ms/op
                 getUser·p0.90:   3.092 ms/op
                 getUser·p0.95:   3.326 ms/op
                 getUser·p0.99:   4.768 ms/op
                 getUser·p0.999:  9.432 ms/op
                 getUser·p0.9999: 13.626 ms/op
                 getUser·p1.00:   15.057 ms/op

Iteration   3: 2.487 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.994 ms/op
                 getUser·p0.50:   2.503 ms/op
                 getUser·p0.90:   3.035 ms/op
                 getUser·p0.95:   3.191 ms/op
                 getUser·p0.99:   3.944 ms/op
                 getUser·p0.999:  5.745 ms/op
                 getUser·p0.9999: 10.568 ms/op
                 getUser·p1.00:   11.370 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 384767
  mean =      2.493 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 67 
    [ 1.250,  2.500) = 190771 
    [ 2.500,  3.750) = 187789 
    [ 3.750,  5.000) = 4865 
    [ 5.000,  6.250) = 851 
    [ 6.250,  7.500) = 66 
    [ 7.500,  8.750) = 20 
    [ 8.750, 10.000) = 61 
    [10.000, 11.250) = 73 
    [11.250, 12.500) = 108 
    [12.500, 13.750) = 58 
    [13.750, 15.000) = 33 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.819 ms/op
     p(50.0000) =      2.515 ms/op
     p(90.0000) =      3.031 ms/op
     p(95.0000) =      3.191 ms/op
     p(99.0000) =      4.104 ms/op
     p(99.9000) =      6.762 ms/op
     p(99.9900) =     13.755 ms/op
     p(99.9990) =     15.043 ms/op
     p(99.9999) =     15.466 ms/op
    p(100.0000) =     15.466 ms/op


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
# Warmup Iteration   1: 4.645 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.121 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.032 ±(99.9%) 0.008 ms/op
Iteration   1: 3.020 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.792 ms/op
                 listUser·p0.50:   2.949 ms/op
                 listUser·p0.90:   3.908 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   5.669 ms/op
                 listUser·p0.999:  8.421 ms/op
                 listUser·p0.9999: 10.788 ms/op
                 listUser·p1.00:   11.502 ms/op

Iteration   2: 3.045 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.841 ms/op
                 listUser·p0.50:   2.970 ms/op
                 listUser·p0.90:   3.940 ms/op
                 listUser·p0.95:   4.473 ms/op
                 listUser·p0.99:   5.848 ms/op
                 listUser·p0.999:  9.994 ms/op
                 listUser·p0.9999: 12.698 ms/op
                 listUser·p1.00:   12.993 ms/op

Iteration   3: 3.033 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.946 ms/op
                 listUser·p0.50:   2.957 ms/op
                 listUser·p0.90:   3.940 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   5.628 ms/op
                 listUser·p0.999:  9.758 ms/op
                 listUser·p0.9999: 21.246 ms/op
                 listUser·p1.00:   22.446 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 316302
  mean =      3.032 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 89304 
    [ 2.500,  5.000) = 218679 
    [ 5.000,  7.500) = 7597 
    [ 7.500, 10.000) = 482 
    [10.000, 12.500) = 176 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.792 ms/op
     p(50.0000) =      2.957 ms/op
     p(90.0000) =      3.932 ms/op
     p(95.0000) =      4.456 ms/op
     p(99.0000) =      5.718 ms/op
     p(99.9000) =      9.662 ms/op
     p(99.9900) =     18.628 ms/op
     p(99.9990) =     21.895 ms/op
     p(99.9999) =     22.446 ms/op
    p(100.0000) =     22.446 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.803 ± 0.391  ops/ms
ClientPb.existUser                       thrpt       3  13.019 ± 0.989  ops/ms
ClientPb.getUser                         thrpt       3  12.689 ± 1.066  ops/ms
ClientPb.listUser                        thrpt       3  10.694 ± 0.956  ops/ms
ClientPb.createUser                       avgt       3   2.490 ± 0.191   ms/op
ClientPb.existUser                        avgt       3   2.431 ± 0.223   ms/op
ClientPb.getUser                          avgt       3   2.483 ± 0.122   ms/op
ClientPb.listUser                         avgt       3   2.979 ± 0.198   ms/op
ClientPb.createUser                     sample  384665   2.493 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.940           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.548           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.031           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.150           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.711           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.629           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.681           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.434           ms/op
ClientPb.existUser                      sample  393811   2.435 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.889           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.482           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.961           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.076           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.662           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.590           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.199           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.549           ms/op
ClientPb.getUser                        sample  384767   2.493 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.819           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.515           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.031           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.191           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.104           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.762           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.755           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.466           ms/op
ClientPb.listUser                       sample  316302   3.032 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.792           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.957           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.932           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.456           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.718           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.662           ms/op
ClientPb.listUser:listUser·p0.9999      sample          18.628           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.446           ms/op
