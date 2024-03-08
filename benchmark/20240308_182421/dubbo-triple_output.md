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
# Warmup Iteration   1: 4.922 ops/ms
# Warmup Iteration   2: 12.255 ops/ms
# Warmup Iteration   3: 12.525 ops/ms
Iteration   1: 12.711 ops/ms
Iteration   2: 12.738 ops/ms
Iteration   3: 12.782 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.744 ±(99.9%) 0.648 ops/ms [Average]
  (min, avg, max) = (12.711, 12.744, 12.782), stdev = 0.036
  CI (99.9%): [12.096, 13.391] (assumes normal distribution)


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
# Warmup Iteration   1: 8.566 ops/ms
# Warmup Iteration   2: 13.180 ops/ms
# Warmup Iteration   3: 13.282 ops/ms
Iteration   1: 13.118 ops/ms
Iteration   2: 13.182 ops/ms
Iteration   3: 13.307 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.203 ±(99.9%) 1.749 ops/ms [Average]
  (min, avg, max) = (13.118, 13.203, 13.307), stdev = 0.096
  CI (99.9%): [11.454, 14.951] (assumes normal distribution)


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
# Warmup Iteration   1: 7.564 ops/ms
# Warmup Iteration   2: 12.803 ops/ms
# Warmup Iteration   3: 13.021 ops/ms
Iteration   1: 13.209 ops/ms
Iteration   2: 13.196 ops/ms
Iteration   3: 13.212 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.206 ±(99.9%) 0.158 ops/ms [Average]
  (min, avg, max) = (13.196, 13.206, 13.212), stdev = 0.009
  CI (99.9%): [13.048, 13.364] (assumes normal distribution)


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
# Warmup Iteration   1: 6.726 ops/ms
# Warmup Iteration   2: 10.612 ops/ms
# Warmup Iteration   3: 10.613 ops/ms
Iteration   1: 10.728 ops/ms
Iteration   2: 10.791 ops/ms
Iteration   3: 10.690 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.736 ±(99.9%) 0.934 ops/ms [Average]
  (min, avg, max) = (10.690, 10.736, 10.791), stdev = 0.051
  CI (99.9%): [9.802, 11.670] (assumes normal distribution)


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
# Warmup Iteration   1: 4.170 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.546 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.506 ±(99.9%) 0.003 ms/op
Iteration   1: 2.492 ±(99.9%) 0.004 ms/op
Iteration   2: 2.478 ±(99.9%) 0.003 ms/op
Iteration   3: 2.493 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.488 ±(99.9%) 0.148 ms/op [Average]
  (min, avg, max) = (2.478, 2.488, 2.493), stdev = 0.008
  CI (99.9%): [2.340, 2.636] (assumes normal distribution)


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
# Warmup Iteration   1: 3.430 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.405 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.406 ±(99.9%) 0.004 ms/op
Iteration   1: 2.404 ±(99.9%) 0.004 ms/op
Iteration   2: 2.418 ±(99.9%) 0.004 ms/op
Iteration   3: 2.412 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.411 ±(99.9%) 0.126 ms/op [Average]
  (min, avg, max) = (2.404, 2.411, 2.418), stdev = 0.007
  CI (99.9%): [2.285, 2.538] (assumes normal distribution)


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
# Warmup Iteration   1: 3.793 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.533 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.453 ±(99.9%) 0.003 ms/op
Iteration   1: 2.473 ±(99.9%) 0.004 ms/op
Iteration   2: 2.473 ±(99.9%) 0.004 ms/op
Iteration   3: 2.455 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.467 ±(99.9%) 0.187 ms/op [Average]
  (min, avg, max) = (2.455, 2.467, 2.473), stdev = 0.010
  CI (99.9%): [2.279, 2.654] (assumes normal distribution)


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
# Warmup Iteration   1: 4.524 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.003 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.002 ±(99.9%) 0.005 ms/op
Iteration   1: 2.995 ±(99.9%) 0.006 ms/op
Iteration   2: 3.013 ±(99.9%) 0.005 ms/op
Iteration   3: 2.969 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.992 ±(99.9%) 0.397 ms/op [Average]
  (min, avg, max) = (2.969, 2.992, 3.013), stdev = 0.022
  CI (99.9%): [2.596, 3.389] (assumes normal distribution)


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
# Warmup Iteration   1: 3.987 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.623 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.509 ±(99.9%) 0.005 ms/op
Iteration   1: 2.515 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.022 ms/op
                 createUser·p0.50:   2.585 ms/op
                 createUser·p0.90:   3.043 ms/op
                 createUser·p0.95:   3.166 ms/op
                 createUser·p0.99:   3.842 ms/op
                 createUser·p0.999:  11.629 ms/op
                 createUser·p0.9999: 13.887 ms/op
                 createUser·p1.00:   15.155 ms/op

Iteration   2: 2.499 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.929 ms/op
                 createUser·p0.50:   2.568 ms/op
                 createUser·p0.90:   3.031 ms/op
                 createUser·p0.95:   3.138 ms/op
                 createUser·p0.99:   3.551 ms/op
                 createUser·p0.999:  10.536 ms/op
                 createUser·p0.9999: 13.029 ms/op
                 createUser·p1.00:   13.287 ms/op

Iteration   3: 2.503 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.954 ms/op
                 createUser·p0.50:   2.523 ms/op
                 createUser·p0.90:   3.052 ms/op
                 createUser·p0.95:   3.199 ms/op
                 createUser·p0.99:   3.912 ms/op
                 createUser·p0.999:  8.425 ms/op
                 createUser·p0.9999: 10.125 ms/op
                 createUser·p1.00:   15.401 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 382611
  mean =      2.506 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 66 
    [ 1.250,  2.500) = 187136 
    [ 2.500,  3.750) = 191364 
    [ 3.750,  5.000) = 3156 
    [ 5.000,  6.250) = 355 
    [ 6.250,  7.500) = 88 
    [ 7.500,  8.750) = 48 
    [ 8.750, 10.000) = 100 
    [10.000, 11.250) = 72 
    [11.250, 12.500) = 91 
    [12.500, 13.750) = 119 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.929 ms/op
     p(50.0000) =      2.556 ms/op
     p(90.0000) =      3.043 ms/op
     p(95.0000) =      3.162 ms/op
     p(99.0000) =      3.781 ms/op
     p(99.9000) =      9.028 ms/op
     p(99.9900) =     13.496 ms/op
     p(99.9990) =     14.473 ms/op
     p(99.9999) =     15.401 ms/op
    p(100.0000) =     15.401 ms/op


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
# Warmup Iteration   1: 3.591 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 2.422 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.446 ±(99.9%) 0.005 ms/op
Iteration   1: 2.426 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.918 ms/op
                 existUser·p0.50:   2.490 ms/op
                 existUser·p0.90:   2.945 ms/op
                 existUser·p0.95:   3.064 ms/op
                 existUser·p0.99:   3.609 ms/op
                 existUser·p0.999:  6.109 ms/op
                 existUser·p0.9999: 15.513 ms/op
                 existUser·p1.00:   15.778 ms/op

Iteration   2: 2.417 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.953 ms/op
                 existUser·p0.50:   2.474 ms/op
                 existUser·p0.90:   2.937 ms/op
                 existUser·p0.95:   3.031 ms/op
                 existUser·p0.99:   3.375 ms/op
                 existUser·p0.999:  7.995 ms/op
                 existUser·p0.9999: 13.493 ms/op
                 existUser·p1.00:   14.172 ms/op

Iteration   3: 2.415 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.821 ms/op
                 existUser·p0.50:   2.478 ms/op
                 existUser·p0.90:   2.933 ms/op
                 existUser·p0.95:   3.035 ms/op
                 existUser·p0.99:   3.535 ms/op
                 existUser·p0.999:  6.809 ms/op
                 existUser·p0.9999: 11.084 ms/op
                 existUser·p1.00:   11.698 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 396403
  mean =      2.419 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 64 
    [ 1.250,  2.500) = 199884 
    [ 2.500,  3.750) = 193787 
    [ 3.750,  5.000) = 1984 
    [ 5.000,  6.250) = 250 
    [ 6.250,  7.500) = 34 
    [ 7.500,  8.750) = 19 
    [ 8.750, 10.000) = 102 
    [10.000, 11.250) = 110 
    [11.250, 12.500) = 60 
    [12.500, 13.750) = 75 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 21 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.821 ms/op
     p(50.0000) =      2.482 ms/op
     p(90.0000) =      2.937 ms/op
     p(95.0000) =      3.043 ms/op
     p(99.0000) =      3.514 ms/op
     p(99.9000) =      7.637 ms/op
     p(99.9900) =     13.479 ms/op
     p(99.9990) =     15.715 ms/op
     p(99.9999) =     15.778 ms/op
    p(100.0000) =     15.778 ms/op


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
# Warmup Iteration   1: 4.300 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.584 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.529 ±(99.9%) 0.006 ms/op
Iteration   1: 2.496 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.868 ms/op
                 getUser·p0.50:   2.507 ms/op
                 getUser·p0.90:   3.035 ms/op
                 getUser·p0.95:   3.150 ms/op
                 getUser·p0.99:   3.817 ms/op
                 getUser·p0.999:  10.893 ms/op
                 getUser·p0.9999: 13.566 ms/op
                 getUser·p1.00:   13.910 ms/op

Iteration   2: 2.524 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.933 ms/op
                 getUser·p0.50:   2.560 ms/op
                 getUser·p0.90:   3.064 ms/op
                 getUser·p0.95:   3.174 ms/op
                 getUser·p0.99:   4.002 ms/op
                 getUser·p0.999:  9.547 ms/op
                 getUser·p0.9999: 14.074 ms/op
                 getUser·p1.00:   14.877 ms/op

Iteration   3: 2.497 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.958 ms/op
                 getUser·p0.50:   2.507 ms/op
                 getUser·p0.90:   3.039 ms/op
                 getUser·p0.95:   3.133 ms/op
                 getUser·p0.99:   3.617 ms/op
                 getUser·p0.999:  7.990 ms/op
                 getUser·p0.9999: 11.649 ms/op
                 getUser·p1.00:   11.747 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 382724
  mean =      2.506 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 65 
    [ 1.250,  2.500) = 190207 
    [ 2.500,  3.750) = 188387 
    [ 3.750,  5.000) = 3204 
    [ 5.000,  6.250) = 437 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 27 
    [ 8.750, 10.000) = 106 
    [10.000, 11.250) = 48 
    [11.250, 12.500) = 107 
    [12.500, 13.750) = 81 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.868 ms/op
     p(50.0000) =      2.523 ms/op
     p(90.0000) =      3.047 ms/op
     p(95.0000) =      3.154 ms/op
     p(99.0000) =      3.789 ms/op
     p(99.9000) =      8.339 ms/op
     p(99.9900) =     13.255 ms/op
     p(99.9990) =     14.601 ms/op
     p(99.9999) =     14.877 ms/op
    p(100.0000) =     14.877 ms/op


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
# Warmup Iteration   1: 4.695 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.090 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.035 ±(99.9%) 0.009 ms/op
Iteration   1: 3.018 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.983 ms/op
                 listUser·p0.50:   2.953 ms/op
                 listUser·p0.90:   3.883 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.579 ms/op
                 listUser·p0.999:  10.093 ms/op
                 listUser·p0.9999: 12.475 ms/op
                 listUser·p1.00:   12.960 ms/op

Iteration   2: 3.007 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.948 ms/op
                 listUser·p0.50:   2.941 ms/op
                 listUser·p0.90:   3.858 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   5.562 ms/op
                 listUser·p0.999:  9.699 ms/op
                 listUser·p0.9999: 11.360 ms/op
                 listUser·p1.00:   12.141 ms/op

Iteration   3: 3.036 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.794 ms/op
                 listUser·p0.50:   2.961 ms/op
                 listUser·p0.90:   3.940 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   5.702 ms/op
                 listUser·p0.999:  10.072 ms/op
                 listUser·p0.9999: 11.804 ms/op
                 listUser·p1.00:   12.616 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 317470
  mean =      3.020 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 104 
    [ 1.250,  2.500) = 89093 
    [ 2.500,  3.750) = 188718 
    [ 3.750,  5.000) = 32170 
    [ 5.000,  6.250) = 5893 
    [ 6.250,  7.500) = 767 
    [ 7.500,  8.750) = 185 
    [ 8.750, 10.000) = 224 
    [10.000, 11.250) = 217 
    [11.250, 12.500) = 90 
    [12.500, 13.750) = 9 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.794 ms/op
     p(50.0000) =      2.953 ms/op
     p(90.0000) =      3.895 ms/op
     p(95.0000) =      4.399 ms/op
     p(99.0000) =      5.612 ms/op
     p(99.9000) =      9.994 ms/op
     p(99.9900) =     11.854 ms/op
     p(99.9990) =     12.646 ms/op
     p(99.9999) =     12.960 ms/op
    p(100.0000) =     12.960 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.744 ± 0.648  ops/ms
ClientPb.existUser                       thrpt       3  13.203 ± 1.749  ops/ms
ClientPb.getUser                         thrpt       3  13.206 ± 0.158  ops/ms
ClientPb.listUser                        thrpt       3  10.736 ± 0.934  ops/ms
ClientPb.createUser                       avgt       3   2.488 ± 0.148   ms/op
ClientPb.existUser                        avgt       3   2.411 ± 0.126   ms/op
ClientPb.getUser                          avgt       3   2.467 ± 0.187   ms/op
ClientPb.listUser                         avgt       3   2.992 ± 0.397   ms/op
ClientPb.createUser                     sample  382611   2.506 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.929           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.556           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.043           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.162           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.781           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.028           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.496           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.401           ms/op
ClientPb.existUser                      sample  396403   2.419 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.821           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.482           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.937           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.043           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.514           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.637           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.479           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.778           ms/op
ClientPb.getUser                        sample  382724   2.506 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.868           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.523           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.047           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.154           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.789           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.339           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.255           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.877           ms/op
ClientPb.listUser                       sample  317470   3.020 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.794           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.953           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.895           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.399           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.612           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.994           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.854           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.960           ms/op
