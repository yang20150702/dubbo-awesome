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
# Warmup Iteration   1: 4.820 ops/ms
# Warmup Iteration   2: 12.139 ops/ms
# Warmup Iteration   3: 12.364 ops/ms
Iteration   1: 12.684 ops/ms
Iteration   2: 12.698 ops/ms
Iteration   3: 12.675 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.686 ±(99.9%) 0.219 ops/ms [Average]
  (min, avg, max) = (12.675, 12.686, 12.698), stdev = 0.012
  CI (99.9%): [12.467, 12.904] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:53
# Fork: 1 of 1
# Warmup Iteration   1: 8.008 ops/ms
# Warmup Iteration   2: 13.008 ops/ms
# Warmup Iteration   3: 12.845 ops/ms
Iteration   1: 13.075 ops/ms
Iteration   2: 13.049 ops/ms
Iteration   3: 12.880 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.001 ±(99.9%) 1.934 ops/ms [Average]
  (min, avg, max) = (12.880, 13.001, 13.075), stdev = 0.106
  CI (99.9%): [11.068, 14.935] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:48
# Fork: 1 of 1
# Warmup Iteration   1: 7.639 ops/ms
# Warmup Iteration   2: 12.657 ops/ms
# Warmup Iteration   3: 12.810 ops/ms
Iteration   1: 12.835 ops/ms
Iteration   2: 12.895 ops/ms
Iteration   3: 12.893 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.874 ±(99.9%) 0.618 ops/ms [Average]
  (min, avg, max) = (12.835, 12.874, 12.895), stdev = 0.034
  CI (99.9%): [12.256, 13.492] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:43
# Fork: 1 of 1
# Warmup Iteration   1: 6.476 ops/ms
# Warmup Iteration   2: 10.243 ops/ms
# Warmup Iteration   3: 10.370 ops/ms
Iteration   1: 10.523 ops/ms
Iteration   2: 10.417 ops/ms
Iteration   3: 10.469 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.470 ±(99.9%) 0.974 ops/ms [Average]
  (min, avg, max) = (10.417, 10.470, 10.523), stdev = 0.053
  CI (99.9%): [9.496, 11.443] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.058 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.635 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.583 ±(99.9%) 0.003 ms/op
Iteration   1: 2.579 ±(99.9%) 0.003 ms/op
Iteration   2: 2.578 ±(99.9%) 0.005 ms/op
Iteration   3: 2.578 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.578 ±(99.9%) 0.013 ms/op [Average]
  (min, avg, max) = (2.578, 2.578, 2.579), stdev = 0.001
  CI (99.9%): [2.565, 2.592] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:33
# Fork: 1 of 1
# Warmup Iteration   1: 3.709 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.510 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.535 ±(99.9%) 0.003 ms/op
Iteration   1: 2.484 ±(99.9%) 0.004 ms/op
Iteration   2: 2.496 ±(99.9%) 0.004 ms/op
Iteration   3: 2.507 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.495 ±(99.9%) 0.210 ms/op [Average]
  (min, avg, max) = (2.484, 2.495, 2.507), stdev = 0.011
  CI (99.9%): [2.286, 2.705] (assumes normal distribution)


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
# Warmup Iteration   1: 4.188 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.623 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.577 ±(99.9%) 0.003 ms/op
Iteration   1: 2.556 ±(99.9%) 0.004 ms/op
Iteration   2: 2.549 ±(99.9%) 0.005 ms/op
Iteration   3: 2.569 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.558 ±(99.9%) 0.192 ms/op [Average]
  (min, avg, max) = (2.549, 2.558, 2.569), stdev = 0.011
  CI (99.9%): [2.367, 2.750] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.715 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.160 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.093 ±(99.9%) 0.005 ms/op
Iteration   1: 3.092 ±(99.9%) 0.007 ms/op
Iteration   2: 3.073 ±(99.9%) 0.005 ms/op
Iteration   3: 3.082 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.082 ±(99.9%) 0.177 ms/op [Average]
  (min, avg, max) = (3.073, 3.082, 3.092), stdev = 0.010
  CI (99.9%): [2.906, 3.259] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.805 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 2.689 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.613 ±(99.9%) 0.006 ms/op
Iteration   1: 2.575 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.710 ms/op
                 createUser·p0.50:   2.626 ms/op
                 createUser·p0.90:   3.125 ms/op
                 createUser·p0.95:   3.260 ms/op
                 createUser·p0.99:   3.961 ms/op
                 createUser·p0.999:  12.334 ms/op
                 createUser·p0.9999: 14.116 ms/op
                 createUser·p1.00:   14.598 ms/op

Iteration   2: 2.579 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.992 ms/op
                 createUser·p0.50:   2.662 ms/op
                 createUser·p0.90:   3.142 ms/op
                 createUser·p0.95:   3.285 ms/op
                 createUser·p0.99:   3.944 ms/op
                 createUser·p0.999:  10.273 ms/op
                 createUser·p0.9999: 12.960 ms/op
                 createUser·p1.00:   13.877 ms/op

Iteration   3: 2.553 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.057 ms/op
                 createUser·p0.50:   2.646 ms/op
                 createUser·p0.90:   3.097 ms/op
                 createUser·p0.95:   3.211 ms/op
                 createUser·p0.99:   3.838 ms/op
                 createUser·p0.999:  9.053 ms/op
                 createUser·p0.9999: 11.387 ms/op
                 createUser·p1.00:   12.255 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 373383
  mean =      2.569 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 45 
    [ 1.250,  2.500) = 175487 
    [ 2.500,  3.750) = 192748 
    [ 3.750,  5.000) = 4131 
    [ 5.000,  6.250) = 549 
    [ 6.250,  7.500) = 34 
    [ 7.500,  8.750) = 6 
    [ 8.750, 10.000) = 42 
    [10.000, 11.250) = 133 
    [11.250, 12.500) = 73 
    [12.500, 13.750) = 102 
    [13.750, 15.000) = 33 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.710 ms/op
     p(50.0000) =      2.646 ms/op
     p(90.0000) =      3.121 ms/op
     p(95.0000) =      3.252 ms/op
     p(99.0000) =      3.920 ms/op
     p(99.9000) =      9.087 ms/op
     p(99.9900) =     13.566 ms/op
     p(99.9990) =     14.440 ms/op
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
# Warmup Iteration   1: 3.912 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.530 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.493 ±(99.9%) 0.005 ms/op
Iteration   1: 2.482 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.000 ms/op
                 existUser·p0.50:   2.568 ms/op
                 existUser·p0.90:   3.011 ms/op
                 existUser·p0.95:   3.117 ms/op
                 existUser·p0.99:   3.633 ms/op
                 existUser·p0.999:  7.761 ms/op
                 existUser·p0.9999: 14.254 ms/op
                 existUser·p1.00:   14.713 ms/op

Iteration   2: 2.454 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.992 ms/op
                 existUser·p0.50:   2.556 ms/op
                 existUser·p0.90:   2.970 ms/op
                 existUser·p0.95:   3.084 ms/op
                 existUser·p0.99:   3.887 ms/op
                 existUser·p0.999:  6.250 ms/op
                 existUser·p0.9999: 12.550 ms/op
                 existUser·p1.00:   12.861 ms/op

Iteration   3: 2.458 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.009 ms/op
                 existUser·p0.50:   2.527 ms/op
                 existUser·p0.90:   2.986 ms/op
                 existUser·p0.95:   3.097 ms/op
                 existUser·p0.99:   3.711 ms/op
                 existUser·p0.999:  8.857 ms/op
                 existUser·p0.9999: 13.156 ms/op
                 existUser·p1.00:   16.974 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 389112
  mean =      2.465 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 35 
    [ 1.250,  2.500) = 190068 
    [ 2.500,  3.750) = 195175 
    [ 3.750,  5.000) = 2950 
    [ 5.000,  6.250) = 474 
    [ 6.250,  7.500) = 45 
    [ 7.500,  8.750) = 9 
    [ 8.750, 10.000) = 100 
    [10.000, 11.250) = 59 
    [11.250, 12.500) = 62 
    [12.500, 13.750) = 95 
    [13.750, 15.000) = 34 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 6 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.992 ms/op
     p(50.0000) =      2.548 ms/op
     p(90.0000) =      2.990 ms/op
     p(95.0000) =      3.101 ms/op
     p(99.0000) =      3.740 ms/op
     p(99.9000) =      6.527 ms/op
     p(99.9900) =     13.779 ms/op
     p(99.9990) =     16.879 ms/op
     p(99.9999) =     16.974 ms/op
    p(100.0000) =     16.974 ms/op


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
# Warmup Iteration   1: 3.896 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.578 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.518 ±(99.9%) 0.006 ms/op
Iteration   1: 2.526 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.071 ms/op
                 getUser·p0.50:   2.552 ms/op
                 getUser·p0.90:   3.084 ms/op
                 getUser·p0.95:   3.244 ms/op
                 getUser·p0.99:   3.891 ms/op
                 getUser·p0.999:  12.370 ms/op
                 getUser·p0.9999: 14.139 ms/op
                 getUser·p1.00:   14.402 ms/op

Iteration   2: 2.550 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.891 ms/op
                 getUser·p0.50:   2.576 ms/op
                 getUser·p0.90:   3.097 ms/op
                 getUser·p0.95:   3.203 ms/op
                 getUser·p0.99:   3.934 ms/op
                 getUser·p0.999:  9.698 ms/op
                 getUser·p0.9999: 14.074 ms/op
                 getUser·p1.00:   14.270 ms/op

Iteration   3: 2.594 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.980 ms/op
                 getUser·p0.50:   2.626 ms/op
                 getUser·p0.90:   3.154 ms/op
                 getUser·p0.95:   3.363 ms/op
                 getUser·p0.99:   4.915 ms/op
                 getUser·p0.999:  8.864 ms/op
                 getUser·p0.9999: 12.834 ms/op
                 getUser·p1.00:   13.746 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 375131
  mean =      2.557 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 63 
    [ 1.250,  2.500) = 181553 
    [ 2.500,  3.750) = 186587 
    [ 3.750,  5.000) = 5221 
    [ 5.000,  6.250) = 1254 
    [ 6.250,  7.500) = 65 
    [ 7.500,  8.750) = 5 
    [ 8.750, 10.000) = 73 
    [10.000, 11.250) = 85 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 124 
    [13.750, 15.000) = 69 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.891 ms/op
     p(50.0000) =      2.585 ms/op
     p(90.0000) =      3.109 ms/op
     p(95.0000) =      3.260 ms/op
     p(99.0000) =      4.274 ms/op
     p(99.9000) =      8.994 ms/op
     p(99.9900) =     14.074 ms/op
     p(99.9990) =     14.254 ms/op
     p(99.9999) =     14.402 ms/op
    p(100.0000) =     14.402 ms/op


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
# Warmup Iteration   1: 4.915 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 3.177 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.090 ±(99.9%) 0.009 ms/op
Iteration   1: 3.117 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.761 ms/op
                 listUser·p0.50:   3.035 ms/op
                 listUser·p0.90:   4.084 ms/op
                 listUser·p0.95:   4.702 ms/op
                 listUser·p0.99:   5.857 ms/op
                 listUser·p0.999:  9.295 ms/op
                 listUser·p0.9999: 11.530 ms/op
                 listUser·p1.00:   12.403 ms/op

Iteration   2: 3.080 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.991 ms/op
                 listUser·p0.50:   3.011 ms/op
                 listUser·p0.90:   3.981 ms/op
                 listUser·p0.95:   4.506 ms/op
                 listUser·p0.99:   5.808 ms/op
                 listUser·p0.999:  9.948 ms/op
                 listUser·p0.9999: 11.838 ms/op
                 listUser·p1.00:   12.173 ms/op

Iteration   3: 3.086 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.955 ms/op
                 listUser·p0.50:   3.027 ms/op
                 listUser·p0.90:   3.994 ms/op
                 listUser·p0.95:   4.506 ms/op
                 listUser·p0.99:   5.628 ms/op
                 listUser·p0.999:  9.165 ms/op
                 listUser·p0.9999: 10.644 ms/op
                 listUser·p1.00:   10.945 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 309937
  mean =      3.094 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 110 
    [ 1.250,  2.500) = 78861 
    [ 2.500,  3.750) = 184868 
    [ 3.750,  5.000) = 36850 
    [ 5.000,  6.250) = 7637 
    [ 6.250,  7.500) = 958 
    [ 7.500,  8.750) = 230 
    [ 8.750, 10.000) = 237 
    [10.000, 11.250) = 139 
    [11.250, 12.500) = 47 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.761 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      4.018 ms/op
     p(95.0000) =      4.571 ms/op
     p(99.0000) =      5.759 ms/op
     p(99.9000) =      9.454 ms/op
     p(99.9900) =     11.485 ms/op
     p(99.9990) =     12.232 ms/op
     p(99.9999) =     12.403 ms/op
    p(100.0000) =     12.403 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.686 ± 0.219  ops/ms
ClientPb.existUser                       thrpt       3  13.001 ± 1.934  ops/ms
ClientPb.getUser                         thrpt       3  12.874 ± 0.618  ops/ms
ClientPb.listUser                        thrpt       3  10.470 ± 0.974  ops/ms
ClientPb.createUser                       avgt       3   2.578 ± 0.013   ms/op
ClientPb.existUser                        avgt       3   2.495 ± 0.210   ms/op
ClientPb.getUser                          avgt       3   2.558 ± 0.192   ms/op
ClientPb.listUser                         avgt       3   3.082 ± 0.177   ms/op
ClientPb.createUser                     sample  373383   2.569 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.710           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.646           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.121           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.252           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.920           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.087           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.566           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.598           ms/op
ClientPb.existUser                      sample  389112   2.465 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.992           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.548           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.990           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.101           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.740           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.527           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.779           ms/op
ClientPb.existUser:existUser·p1.00      sample          16.974           ms/op
ClientPb.getUser                        sample  375131   2.557 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.891           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.585           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.109           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.260           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.274           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.994           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.074           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.402           ms/op
ClientPb.listUser                       sample  309937   3.094 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.761           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.023           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.018           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.571           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.759           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.454           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.485           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.403           ms/op
