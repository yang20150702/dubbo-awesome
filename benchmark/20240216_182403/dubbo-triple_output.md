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
# Warmup Iteration   1: 4.957 ops/ms
# Warmup Iteration   2: 12.028 ops/ms
# Warmup Iteration   3: 12.280 ops/ms
Iteration   1: 12.624 ops/ms
Iteration   2: 12.696 ops/ms
Iteration   3: 12.681 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.667 ±(99.9%) 0.691 ops/ms [Average]
  (min, avg, max) = (12.624, 12.667, 12.696), stdev = 0.038
  CI (99.9%): [11.976, 13.358] (assumes normal distribution)


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
# Warmup Iteration   1: 8.019 ops/ms
# Warmup Iteration   2: 12.647 ops/ms
# Warmup Iteration   3: 13.052 ops/ms
Iteration   1: 13.090 ops/ms
Iteration   2: 13.073 ops/ms
Iteration   3: 12.933 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.032 ±(99.9%) 1.575 ops/ms [Average]
  (min, avg, max) = (12.933, 13.032, 13.090), stdev = 0.086
  CI (99.9%): [11.458, 14.607] (assumes normal distribution)


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
# Warmup Iteration   1: 7.836 ops/ms
# Warmup Iteration   2: 12.615 ops/ms
# Warmup Iteration   3: 12.954 ops/ms
Iteration   1: 13.108 ops/ms
Iteration   2: 12.990 ops/ms
Iteration   3: 12.906 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.001 ±(99.9%) 1.851 ops/ms [Average]
  (min, avg, max) = (12.906, 13.001, 13.108), stdev = 0.101
  CI (99.9%): [11.150, 14.852] (assumes normal distribution)


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
# Warmup Iteration   1: 6.710 ops/ms
# Warmup Iteration   2: 10.400 ops/ms
# Warmup Iteration   3: 10.540 ops/ms
Iteration   1: 10.580 ops/ms
Iteration   2: 10.502 ops/ms
Iteration   3: 10.522 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.535 ±(99.9%) 0.741 ops/ms [Average]
  (min, avg, max) = (10.502, 10.535, 10.580), stdev = 0.041
  CI (99.9%): [9.793, 11.276] (assumes normal distribution)


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
# Warmup Iteration   1: 3.952 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 2.597 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.563 ±(99.9%) 0.004 ms/op
Iteration   1: 2.578 ±(99.9%) 0.004 ms/op
Iteration   2: 2.527 ±(99.9%) 0.004 ms/op
Iteration   3: 2.546 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.550 ±(99.9%) 0.471 ms/op [Average]
  (min, avg, max) = (2.527, 2.550, 2.578), stdev = 0.026
  CI (99.9%): [2.080, 3.021] (assumes normal distribution)


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
# Warmup Iteration   1: 3.723 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.525 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.490 ±(99.9%) 0.004 ms/op
Iteration   1: 2.502 ±(99.9%) 0.004 ms/op
Iteration   2: 2.457 ±(99.9%) 0.004 ms/op
Iteration   3: 2.513 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.491 ±(99.9%) 0.546 ms/op [Average]
  (min, avg, max) = (2.457, 2.491, 2.513), stdev = 0.030
  CI (99.9%): [1.945, 3.036] (assumes normal distribution)


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
# Warmup Iteration   1: 3.943 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.535 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.529 ±(99.9%) 0.005 ms/op
Iteration   1: 2.513 ±(99.9%) 0.004 ms/op
Iteration   2: 2.507 ±(99.9%) 0.004 ms/op
Iteration   3: 2.504 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.508 ±(99.9%) 0.087 ms/op [Average]
  (min, avg, max) = (2.504, 2.508, 2.513), stdev = 0.005
  CI (99.9%): [2.421, 2.595] (assumes normal distribution)


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
# Warmup Iteration   1: 4.704 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.094 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.036 ±(99.9%) 0.005 ms/op
Iteration   1: 3.056 ±(99.9%) 0.005 ms/op
Iteration   2: 3.100 ±(99.9%) 0.007 ms/op
Iteration   3: 3.047 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.068 ±(99.9%) 0.522 ms/op [Average]
  (min, avg, max) = (3.047, 3.068, 3.100), stdev = 0.029
  CI (99.9%): [2.546, 3.590] (assumes normal distribution)


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
# Warmup Iteration   1: 4.179 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.675 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.551 ±(99.9%) 0.005 ms/op
Iteration   1: 2.541 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.756 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.088 ms/op
                 createUser·p0.95:   3.203 ms/op
                 createUser·p0.99:   3.731 ms/op
                 createUser·p0.999:  12.195 ms/op
                 createUser·p0.9999: 14.303 ms/op
                 createUser·p1.00:   14.909 ms/op

Iteration   2: 2.537 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.944 ms/op
                 createUser·p0.50:   2.609 ms/op
                 createUser·p0.90:   3.076 ms/op
                 createUser·p0.95:   3.203 ms/op
                 createUser·p0.99:   3.846 ms/op
                 createUser·p0.999:  9.994 ms/op
                 createUser·p0.9999: 12.852 ms/op
                 createUser·p1.00:   14.107 ms/op

Iteration   3: 2.540 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.903 ms/op
                 createUser·p0.50:   2.580 ms/op
                 createUser·p0.90:   3.088 ms/op
                 createUser·p0.95:   3.211 ms/op
                 createUser·p0.99:   3.895 ms/op
                 createUser·p0.999:  9.929 ms/op
                 createUser·p0.9999: 11.239 ms/op
                 createUser·p1.00:   11.928 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 377680
  mean =      2.539 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 52 
    [ 1.250,  2.500) = 181781 
    [ 2.500,  3.750) = 191498 
    [ 3.750,  5.000) = 3499 
    [ 5.000,  6.250) = 379 
    [ 6.250,  7.500) = 54 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 47 
    [10.000, 11.250) = 139 
    [11.250, 12.500) = 76 
    [12.500, 13.750) = 115 
    [13.750, 15.000) = 38 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.756 ms/op
     p(50.0000) =      2.593 ms/op
     p(90.0000) =      3.084 ms/op
     p(95.0000) =      3.207 ms/op
     p(99.0000) =      3.826 ms/op
     p(99.9000) =      9.934 ms/op
     p(99.9900) =     13.832 ms/op
     p(99.9990) =     14.817 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.681 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.498 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.499 ±(99.9%) 0.005 ms/op
Iteration   1: 2.508 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.114 ms/op
                 existUser·p0.50:   2.597 ms/op
                 existUser·p0.90:   3.039 ms/op
                 existUser·p0.95:   3.154 ms/op
                 existUser·p0.99:   3.727 ms/op
                 existUser·p0.999:  12.093 ms/op
                 existUser·p0.9999: 13.972 ms/op
                 existUser·p1.00:   14.385 ms/op

Iteration   2: 2.482 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.147 ms/op
                 existUser·p0.50:   2.617 ms/op
                 existUser·p0.90:   2.994 ms/op
                 existUser·p0.95:   3.080 ms/op
                 existUser·p0.99:   3.396 ms/op
                 existUser·p0.999:  6.162 ms/op
                 existUser·p0.9999: 13.273 ms/op
                 existUser·p1.00:   13.533 ms/op

Iteration   3: 2.507 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.983 ms/op
                 existUser·p0.50:   2.564 ms/op
                 existUser·p0.90:   3.047 ms/op
                 existUser·p0.95:   3.170 ms/op
                 existUser·p0.99:   3.826 ms/op
                 existUser·p0.999:  8.603 ms/op
                 existUser·p0.9999: 16.679 ms/op
                 existUser·p1.00:   16.908 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 383849
  mean =      2.499 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 27 
    [ 1.250,  2.500) = 185390 
    [ 2.500,  3.750) = 195027 
    [ 3.750,  5.000) = 2418 
    [ 5.000,  6.250) = 496 
    [ 6.250,  7.500) = 93 
    [ 7.500,  8.750) = 53 
    [ 8.750, 10.000) = 57 
    [10.000, 11.250) = 3 
    [11.250, 12.500) = 89 
    [12.500, 13.750) = 150 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 12 
    [16.250, 17.500) = 20 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.983 ms/op
     p(50.0000) =      2.589 ms/op
     p(90.0000) =      3.027 ms/op
     p(95.0000) =      3.133 ms/op
     p(99.0000) =      3.678 ms/op
     p(99.9000) =      7.786 ms/op
     p(99.9900) =     14.274 ms/op
     p(99.9990) =     16.848 ms/op
     p(99.9999) =     16.908 ms/op
    p(100.0000) =     16.908 ms/op


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
# Warmup Iteration   1: 4.019 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.603 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.572 ±(99.9%) 0.006 ms/op
Iteration   1: 2.564 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.929 ms/op
                 getUser·p0.50:   2.585 ms/op
                 getUser·p0.90:   3.125 ms/op
                 getUser·p0.95:   3.273 ms/op
                 getUser·p0.99:   4.035 ms/op
                 getUser·p0.999:  11.364 ms/op
                 getUser·p0.9999: 13.969 ms/op
                 getUser·p1.00:   14.270 ms/op

Iteration   2: 2.563 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.869 ms/op
                 getUser·p0.50:   2.593 ms/op
                 getUser·p0.90:   3.129 ms/op
                 getUser·p0.95:   3.273 ms/op
                 getUser·p0.99:   4.059 ms/op
                 getUser·p0.999:  9.660 ms/op
                 getUser·p0.9999: 13.189 ms/op
                 getUser·p1.00:   13.877 ms/op

Iteration   3: 2.524 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.972 ms/op
                 getUser·p0.50:   2.564 ms/op
                 getUser·p0.90:   3.068 ms/op
                 getUser·p0.95:   3.174 ms/op
                 getUser·p0.99:   3.699 ms/op
                 getUser·p0.999:  8.972 ms/op
                 getUser·p0.9999: 12.080 ms/op
                 getUser·p1.00:   12.386 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 376105
  mean =      2.550 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 47 
    [ 1.250,  2.500) = 181978 
    [ 2.500,  3.750) = 188783 
    [ 3.750,  5.000) = 4460 
    [ 5.000,  6.250) = 444 
    [ 6.250,  7.500) = 9 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 51 
    [10.000, 11.250) = 104 
    [11.250, 12.500) = 131 
    [12.500, 13.750) = 77 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.869 ms/op
     p(50.0000) =      2.580 ms/op
     p(90.0000) =      3.109 ms/op
     p(95.0000) =      3.236 ms/op
     p(99.0000) =      3.940 ms/op
     p(99.9000) =      9.088 ms/op
     p(99.9900) =     13.402 ms/op
     p(99.9990) =     14.111 ms/op
     p(99.9999) =     14.270 ms/op
    p(100.0000) =     14.270 ms/op


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
# Warmup Iteration   1: 4.739 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.053 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.002 ±(99.9%) 0.008 ms/op
Iteration   1: 3.000 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.995 ms/op
                 listUser·p0.50:   2.937 ms/op
                 listUser·p0.90:   3.883 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   5.554 ms/op
                 listUser·p0.999:  9.451 ms/op
                 listUser·p0.9999: 12.474 ms/op
                 listUser·p1.00:   12.698 ms/op

Iteration   2: 2.993 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.867 ms/op
                 listUser·p0.50:   2.937 ms/op
                 listUser·p0.90:   3.858 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   5.530 ms/op
                 listUser·p0.999:  8.847 ms/op
                 listUser·p0.9999: 11.092 ms/op
                 listUser·p1.00:   12.272 ms/op

Iteration   3: 2.987 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.988 ms/op
                 listUser·p0.50:   2.933 ms/op
                 listUser·p0.90:   3.826 ms/op
                 listUser·p0.95:   4.276 ms/op
                 listUser·p0.99:   5.374 ms/op
                 listUser·p0.999:  9.617 ms/op
                 listUser·p0.9999: 11.534 ms/op
                 listUser·p1.00:   12.370 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 320415
  mean =      2.993 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 120 
    [ 1.250,  2.500) = 93859 
    [ 2.500,  3.750) = 188594 
    [ 3.750,  5.000) = 31612 
    [ 5.000,  6.250) = 4911 
    [ 6.250,  7.500) = 621 
    [ 7.500,  8.750) = 257 
    [ 8.750, 10.000) = 236 
    [10.000, 11.250) = 138 
    [11.250, 12.500) = 59 
    [12.500, 13.750) = 8 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.867 ms/op
     p(50.0000) =      2.937 ms/op
     p(90.0000) =      3.854 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      5.480 ms/op
     p(99.9000) =      9.241 ms/op
     p(99.9900) =     11.828 ms/op
     p(99.9990) =     12.622 ms/op
     p(99.9999) =     12.698 ms/op
    p(100.0000) =     12.698 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.667 ± 0.691  ops/ms
ClientPb.existUser                       thrpt       3  13.032 ± 1.575  ops/ms
ClientPb.getUser                         thrpt       3  13.001 ± 1.851  ops/ms
ClientPb.listUser                        thrpt       3  10.535 ± 0.741  ops/ms
ClientPb.createUser                       avgt       3   2.550 ± 0.471   ms/op
ClientPb.existUser                        avgt       3   2.491 ± 0.546   ms/op
ClientPb.getUser                          avgt       3   2.508 ± 0.087   ms/op
ClientPb.listUser                         avgt       3   3.068 ± 0.522   ms/op
ClientPb.createUser                     sample  377680   2.539 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.756           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.593           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.084           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.207           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.826           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.934           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.832           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.909           ms/op
ClientPb.existUser                      sample  383849   2.499 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.983           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.589           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.027           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.133           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.678           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.786           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.274           ms/op
ClientPb.existUser:existUser·p1.00      sample          16.908           ms/op
ClientPb.getUser                        sample  376105   2.550 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.869           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.580           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.109           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.236           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.940           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.088           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.402           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.270           ms/op
ClientPb.listUser                       sample  320415   2.993 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.867           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.937           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.854           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.334           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.480           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.241           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.828           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.698           ms/op
