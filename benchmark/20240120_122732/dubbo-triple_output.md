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
# Warmup Iteration   1: 4.765 ops/ms
# Warmup Iteration   2: 12.029 ops/ms
# Warmup Iteration   3: 12.110 ops/ms
Iteration   1: 12.478 ops/ms
Iteration   2: 12.478 ops/ms
Iteration   3: 12.689 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.548 ±(99.9%) 2.218 ops/ms [Average]
  (min, avg, max) = (12.478, 12.548, 12.689), stdev = 0.122
  CI (99.9%): [10.330, 14.767] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 8.391 ops/ms
# Warmup Iteration   2: 12.990 ops/ms
# Warmup Iteration   3: 13.087 ops/ms
Iteration   1: 13.078 ops/ms
Iteration   2: 13.042 ops/ms
Iteration   3: 13.131 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.084 ±(99.9%) 0.816 ops/ms [Average]
  (min, avg, max) = (13.042, 13.084, 13.131), stdev = 0.045
  CI (99.9%): [12.268, 13.899] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.745 ops/ms
# Warmup Iteration   2: 12.494 ops/ms
# Warmup Iteration   3: 12.844 ops/ms
Iteration   1: 13.002 ops/ms
Iteration   2: 12.941 ops/ms
Iteration   3: 12.892 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.945 ±(99.9%) 1.001 ops/ms [Average]
  (min, avg, max) = (12.892, 12.945, 13.002), stdev = 0.055
  CI (99.9%): [11.944, 13.946] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 6.422 ops/ms
# Warmup Iteration   2: 10.552 ops/ms
# Warmup Iteration   3: 10.522 ops/ms
Iteration   1: 10.515 ops/ms
Iteration   2: 10.551 ops/ms
Iteration   3: 10.476 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.514 ±(99.9%) 0.687 ops/ms [Average]
  (min, avg, max) = (10.476, 10.514, 10.551), stdev = 0.038
  CI (99.9%): [9.827, 11.201] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.102 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 2.597 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.533 ±(99.9%) 0.003 ms/op
Iteration   1: 2.564 ±(99.9%) 0.003 ms/op
Iteration   2: 2.559 ±(99.9%) 0.005 ms/op
Iteration   3: 2.555 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.560 ±(99.9%) 0.081 ms/op [Average]
  (min, avg, max) = (2.555, 2.560, 2.564), stdev = 0.004
  CI (99.9%): [2.479, 2.640] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.890 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.467 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.457 ±(99.9%) 0.004 ms/op
Iteration   1: 2.446 ±(99.9%) 0.004 ms/op
Iteration   2: 2.456 ±(99.9%) 0.004 ms/op
Iteration   3: 2.468 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.457 ±(99.9%) 0.194 ms/op [Average]
  (min, avg, max) = (2.446, 2.457, 2.468), stdev = 0.011
  CI (99.9%): [2.263, 2.650] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 3.956 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.533 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.500 ±(99.9%) 0.004 ms/op
Iteration   1: 2.478 ±(99.9%) 0.005 ms/op
Iteration   2: 2.473 ±(99.9%) 0.004 ms/op
Iteration   3: 2.487 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.479 ±(99.9%) 0.122 ms/op [Average]
  (min, avg, max) = (2.473, 2.479, 2.487), stdev = 0.007
  CI (99.9%): [2.357, 2.601] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 4.747 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.043 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.052 ±(99.9%) 0.006 ms/op
Iteration   1: 3.006 ±(99.9%) 0.004 ms/op
Iteration   2: 3.032 ±(99.9%) 0.005 ms/op
Iteration   3: 3.032 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.023 ±(99.9%) 0.275 ms/op [Average]
  (min, avg, max) = (3.006, 3.023, 3.032), stdev = 0.015
  CI (99.9%): [2.748, 3.299] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.342 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 2.658 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.521 ±(99.9%) 0.006 ms/op
Iteration   1: 2.534 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.922 ms/op
                 createUser·p0.50:   2.580 ms/op
                 createUser·p0.90:   3.084 ms/op
                 createUser·p0.95:   3.211 ms/op
                 createUser·p0.99:   3.920 ms/op
                 createUser·p0.999:  11.895 ms/op
                 createUser·p0.9999: 16.691 ms/op
                 createUser·p1.00:   17.007 ms/op

Iteration   2: 2.524 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.841 ms/op
                 createUser·p0.50:   2.601 ms/op
                 createUser·p0.90:   3.060 ms/op
                 createUser·p0.95:   3.178 ms/op
                 createUser·p0.99:   3.891 ms/op
                 createUser·p0.999:  9.332 ms/op
                 createUser·p0.9999: 11.976 ms/op
                 createUser·p1.00:   12.550 ms/op

Iteration   3: 2.525 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.890 ms/op
                 createUser·p0.50:   2.585 ms/op
                 createUser·p0.90:   3.072 ms/op
                 createUser·p0.95:   3.187 ms/op
                 createUser·p0.99:   3.817 ms/op
                 createUser·p0.999:  8.722 ms/op
                 createUser·p0.9999: 10.945 ms/op
                 createUser·p1.00:   12.239 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 379564
  mean =      2.527 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 58 
    [ 1.250,  2.500) = 182480 
    [ 2.500,  3.750) = 192364 
    [ 3.750,  5.000) = 3894 
    [ 5.000,  6.250) = 356 
    [ 6.250,  7.500) = 26 
    [ 7.500,  8.750) = 9 
    [ 8.750, 10.000) = 106 
    [10.000, 11.250) = 104 
    [11.250, 12.500) = 55 
    [12.500, 13.750) = 51 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 15 
    [16.250, 17.500) = 19 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.841 ms/op
     p(50.0000) =      2.589 ms/op
     p(90.0000) =      3.072 ms/op
     p(95.0000) =      3.191 ms/op
     p(99.0000) =      3.871 ms/op
     p(99.9000) =      8.749 ms/op
     p(99.9900) =     14.830 ms/op
     p(99.9990) =     16.882 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.899 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.526 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.475 ±(99.9%) 0.005 ms/op
Iteration   1: 2.487 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.937 ms/op
                 existUser·p0.50:   2.540 ms/op
                 existUser·p0.90:   3.019 ms/op
                 existUser·p0.95:   3.138 ms/op
                 existUser·p0.99:   3.879 ms/op
                 existUser·p0.999:  9.656 ms/op
                 existUser·p0.9999: 14.975 ms/op
                 existUser·p1.00:   16.105 ms/op

Iteration   2: 2.485 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.881 ms/op
                 existUser·p0.50:   2.523 ms/op
                 existUser·p0.90:   3.035 ms/op
                 existUser·p0.95:   3.142 ms/op
                 existUser·p0.99:   3.645 ms/op
                 existUser·p0.999:  5.620 ms/op
                 existUser·p0.9999: 12.962 ms/op
                 existUser·p1.00:   13.468 ms/op

Iteration   3: 2.506 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.976 ms/op
                 existUser·p0.50:   2.576 ms/op
                 existUser·p0.90:   3.039 ms/op
                 existUser·p0.95:   3.146 ms/op
                 existUser·p0.99:   3.719 ms/op
                 existUser·p0.999:  9.558 ms/op
                 existUser·p0.9999: 15.814 ms/op
                 existUser·p1.00:   16.663 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 384738
  mean =      2.493 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 45 
    [ 1.250,  2.500) = 188884 
    [ 2.500,  3.750) = 192008 
    [ 3.750,  5.000) = 2890 
    [ 5.000,  6.250) = 529 
    [ 6.250,  7.500) = 20 
    [ 7.500,  8.750) = 6 
    [ 8.750, 10.000) = 15 
    [10.000, 11.250) = 53 
    [11.250, 12.500) = 95 
    [12.500, 13.750) = 116 
    [13.750, 15.000) = 44 
    [15.000, 16.250) = 30 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.881 ms/op
     p(50.0000) =      2.544 ms/op
     p(90.0000) =      3.031 ms/op
     p(95.0000) =      3.142 ms/op
     p(99.0000) =      3.740 ms/op
     p(99.9000) =      6.228 ms/op
     p(99.9900) =     14.967 ms/op
     p(99.9990) =     16.247 ms/op
     p(99.9999) =     16.663 ms/op
    p(100.0000) =     16.663 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.821 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.561 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.533 ±(99.9%) 0.006 ms/op
Iteration   1: 2.491 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.948 ms/op
                 getUser·p0.50:   2.470 ms/op
                 getUser·p0.90:   3.052 ms/op
                 getUser·p0.95:   3.191 ms/op
                 getUser·p0.99:   3.846 ms/op
                 getUser·p0.999:  5.546 ms/op
                 getUser·p0.9999: 14.560 ms/op
                 getUser·p1.00:   15.335 ms/op

Iteration   2: 2.524 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.889 ms/op
                 getUser·p0.50:   2.511 ms/op
                 getUser·p0.90:   3.072 ms/op
                 getUser·p0.95:   3.236 ms/op
                 getUser·p0.99:   4.301 ms/op
                 getUser·p0.999:  9.874 ms/op
                 getUser·p0.9999: 13.921 ms/op
                 getUser·p1.00:   14.778 ms/op

Iteration   3: 2.485 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.907 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   3.023 ms/op
                 getUser·p0.95:   3.125 ms/op
                 getUser·p0.99:   3.650 ms/op
                 getUser·p0.999:  7.168 ms/op
                 getUser·p0.9999: 12.096 ms/op
                 getUser·p1.00:   12.354 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 383716
  mean =      2.500 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 95 
    [ 1.250,  2.500) = 192269 
    [ 2.500,  3.750) = 186107 
    [ 3.750,  5.000) = 4117 
    [ 5.000,  6.250) = 748 
    [ 6.250,  7.500) = 27 
    [ 7.500,  8.750) = 21 
    [ 8.750, 10.000) = 44 
    [10.000, 11.250) = 87 
    [11.250, 12.500) = 102 
    [12.500, 13.750) = 66 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.889 ms/op
     p(50.0000) =      2.494 ms/op
     p(90.0000) =      3.047 ms/op
     p(95.0000) =      3.183 ms/op
     p(99.0000) =      3.928 ms/op
     p(99.9000) =      6.218 ms/op
     p(99.9900) =     13.511 ms/op
     p(99.9990) =     15.221 ms/op
     p(99.9999) =     15.335 ms/op
    p(100.0000) =     15.335 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.595 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.033 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.013 ±(99.9%) 0.008 ms/op
Iteration   1: 2.982 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.651 ms/op
                 listUser·p0.50:   2.920 ms/op
                 listUser·p0.90:   3.842 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.595 ms/op
                 listUser·p0.999:  8.929 ms/op
                 listUser·p0.9999: 10.502 ms/op
                 listUser·p1.00:   11.125 ms/op

Iteration   2: 2.989 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.768 ms/op
                 listUser·p0.50:   2.925 ms/op
                 listUser·p0.90:   3.850 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.530 ms/op
                 listUser·p0.999:  10.208 ms/op
                 listUser·p0.9999: 11.921 ms/op
                 listUser·p1.00:   12.829 ms/op

Iteration   3: 2.980 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.813 ms/op
                 listUser·p0.50:   2.916 ms/op
                 listUser·p0.90:   3.838 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   5.595 ms/op
                 listUser·p0.999:  9.498 ms/op
                 listUser·p0.9999: 12.227 ms/op
                 listUser·p1.00:   13.238 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 321444
  mean =      2.984 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 145 
    [ 1.250,  2.500) = 98707 
    [ 2.500,  3.750) = 185556 
    [ 3.750,  5.000) = 29896 
    [ 5.000,  6.250) = 5689 
    [ 6.250,  7.500) = 763 
    [ 7.500,  8.750) = 254 
    [ 8.750, 10.000) = 212 
    [10.000, 11.250) = 161 
    [11.250, 12.500) = 54 
    [12.500, 13.750) = 7 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.651 ms/op
     p(50.0000) =      2.920 ms/op
     p(90.0000) =      3.846 ms/op
     p(95.0000) =      4.350 ms/op
     p(99.0000) =      5.571 ms/op
     p(99.9000) =      9.388 ms/op
     p(99.9900) =     11.745 ms/op
     p(99.9990) =     12.671 ms/op
     p(99.9999) =     13.238 ms/op
    p(100.0000) =     13.238 ms/op


# Run complete. Total time: 00:13:02

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.548 ± 2.218  ops/ms
ClientPb.existUser                       thrpt       3  13.084 ± 0.816  ops/ms
ClientPb.getUser                         thrpt       3  12.945 ± 1.001  ops/ms
ClientPb.listUser                        thrpt       3  10.514 ± 0.687  ops/ms
ClientPb.createUser                       avgt       3   2.560 ± 0.081   ms/op
ClientPb.existUser                        avgt       3   2.457 ± 0.194   ms/op
ClientPb.getUser                          avgt       3   2.479 ± 0.122   ms/op
ClientPb.listUser                         avgt       3   3.023 ± 0.275   ms/op
ClientPb.createUser                     sample  379564   2.527 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.841           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.589           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.072           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.191           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.871           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.749           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.830           ms/op
ClientPb.createUser:createUser·p1.00    sample          17.007           ms/op
ClientPb.existUser                      sample  384738   2.493 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.881           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.544           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.031           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.142           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.740           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.228           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.967           ms/op
ClientPb.existUser:existUser·p1.00      sample          16.663           ms/op
ClientPb.getUser                        sample  383716   2.500 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.889           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.494           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.047           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.183           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.928           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.218           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.511           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.335           ms/op
ClientPb.listUser                       sample  321444   2.984 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.651           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.920           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.846           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.350           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.571           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.388           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.745           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.238           ms/op
