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
# Warmup Iteration   1: 4.920 ops/ms
# Warmup Iteration   2: 12.073 ops/ms
# Warmup Iteration   3: 12.598 ops/ms
Iteration   1: 12.777 ops/ms
Iteration   2: 12.702 ops/ms
Iteration   3: 12.688 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.723 ±(99.9%) 0.874 ops/ms [Average]
  (min, avg, max) = (12.688, 12.723, 12.777), stdev = 0.048
  CI (99.9%): [11.848, 13.597] (assumes normal distribution)


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
# Warmup Iteration   1: 8.175 ops/ms
# Warmup Iteration   2: 13.349 ops/ms
# Warmup Iteration   3: 13.148 ops/ms
Iteration   1: 13.066 ops/ms
Iteration   2: 13.501 ops/ms
Iteration   3: 13.331 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.299 ±(99.9%) 3.996 ops/ms [Average]
  (min, avg, max) = (13.066, 13.299, 13.501), stdev = 0.219
  CI (99.9%): [9.304, 17.295] (assumes normal distribution)


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
# Warmup Iteration   1: 7.785 ops/ms
# Warmup Iteration   2: 12.619 ops/ms
# Warmup Iteration   3: 12.812 ops/ms
Iteration   1: 12.860 ops/ms
Iteration   2: 12.811 ops/ms
Iteration   3: 12.916 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.863 ±(99.9%) 0.957 ops/ms [Average]
  (min, avg, max) = (12.811, 12.863, 12.916), stdev = 0.052
  CI (99.9%): [11.905, 13.820] (assumes normal distribution)


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
# Warmup Iteration   1: 6.895 ops/ms
# Warmup Iteration   2: 10.518 ops/ms
# Warmup Iteration   3: 10.519 ops/ms
Iteration   1: 10.765 ops/ms
Iteration   2: 10.686 ops/ms
Iteration   3: 10.636 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.696 ±(99.9%) 1.188 ops/ms [Average]
  (min, avg, max) = (10.636, 10.696, 10.765), stdev = 0.065
  CI (99.9%): [9.508, 11.883] (assumes normal distribution)


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
# Warmup Iteration   1: 4.071 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.541 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.525 ±(99.9%) 0.004 ms/op
Iteration   1: 2.503 ±(99.9%) 0.004 ms/op
Iteration   2: 2.496 ±(99.9%) 0.005 ms/op
Iteration   3: 2.483 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.494 ±(99.9%) 0.180 ms/op [Average]
  (min, avg, max) = (2.483, 2.494, 2.503), stdev = 0.010
  CI (99.9%): [2.314, 2.674] (assumes normal distribution)


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
# Warmup Iteration   1: 3.753 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.470 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.493 ±(99.9%) 0.003 ms/op
Iteration   1: 2.459 ±(99.9%) 0.004 ms/op
Iteration   2: 2.446 ±(99.9%) 0.004 ms/op
Iteration   3: 2.444 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.450 ±(99.9%) 0.153 ms/op [Average]
  (min, avg, max) = (2.444, 2.450, 2.459), stdev = 0.008
  CI (99.9%): [2.297, 2.602] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 3.854 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.524 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.518 ±(99.9%) 0.004 ms/op
Iteration   1: 2.479 ±(99.9%) 0.004 ms/op
Iteration   2: 2.471 ±(99.9%) 0.004 ms/op
Iteration   3: 2.484 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.478 ±(99.9%) 0.118 ms/op [Average]
  (min, avg, max) = (2.471, 2.478, 2.484), stdev = 0.006
  CI (99.9%): [2.360, 2.596] (assumes normal distribution)


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
# Warmup Iteration   1: 4.659 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.990 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.986 ±(99.9%) 0.004 ms/op
Iteration   1: 2.955 ±(99.9%) 0.005 ms/op
Iteration   2: 2.964 ±(99.9%) 0.005 ms/op
Iteration   3: 2.968 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.962 ±(99.9%) 0.123 ms/op [Average]
  (min, avg, max) = (2.955, 2.962, 2.968), stdev = 0.007
  CI (99.9%): [2.840, 3.085] (assumes normal distribution)


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
# Warmup Iteration   1: 4.158 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.653 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.542 ±(99.9%) 0.006 ms/op
Iteration   1: 2.526 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.922 ms/op
                 createUser·p0.50:   2.585 ms/op
                 createUser·p0.90:   3.060 ms/op
                 createUser·p0.95:   3.191 ms/op
                 createUser·p0.99:   3.944 ms/op
                 createUser·p0.999:  12.284 ms/op
                 createUser·p0.9999: 13.610 ms/op
                 createUser·p1.00:   14.238 ms/op

Iteration   2: 2.503 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.998 ms/op
                 createUser·p0.50:   2.544 ms/op
                 createUser·p0.90:   3.052 ms/op
                 createUser·p0.95:   3.166 ms/op
                 createUser·p0.99:   3.686 ms/op
                 createUser·p0.999:  9.446 ms/op
                 createUser·p0.9999: 12.115 ms/op
                 createUser·p1.00:   12.698 ms/op

Iteration   3: 2.493 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.010 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.015 ms/op
                 createUser·p0.95:   3.133 ms/op
                 createUser·p0.99:   3.875 ms/op
                 createUser·p0.999:  8.092 ms/op
                 createUser·p0.9999: 9.719 ms/op
                 createUser·p1.00:   13.713 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 382572
  mean =      2.507 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 68 
    [ 1.250,  2.500) = 185316 
    [ 2.500,  3.750) = 192938 
    [ 3.750,  5.000) = 3189 
    [ 5.000,  6.250) = 542 
    [ 6.250,  7.500) = 70 
    [ 7.500,  8.750) = 59 
    [ 8.750, 10.000) = 117 
    [10.000, 11.250) = 58 
    [11.250, 12.500) = 98 
    [12.500, 13.750) = 109 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.922 ms/op
     p(50.0000) =      2.568 ms/op
     p(90.0000) =      3.043 ms/op
     p(95.0000) =      3.162 ms/op
     p(99.0000) =      3.817 ms/op
     p(99.9000) =      8.946 ms/op
     p(99.9900) =     13.332 ms/op
     p(99.9990) =     13.995 ms/op
     p(99.9999) =     14.238 ms/op
    p(100.0000) =     14.238 ms/op


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
# Warmup Iteration   1: 3.783 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.476 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.434 ±(99.9%) 0.005 ms/op
Iteration   1: 2.421 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.933 ms/op
                 existUser·p0.50:   2.482 ms/op
                 existUser·p0.90:   2.941 ms/op
                 existUser·p0.95:   3.035 ms/op
                 existUser·p0.99:   3.449 ms/op
                 existUser·p0.999:  7.463 ms/op
                 existUser·p0.9999: 13.874 ms/op
                 existUser·p1.00:   14.598 ms/op

Iteration   2: 2.443 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.872 ms/op
                 existUser·p0.50:   2.458 ms/op
                 existUser·p0.90:   2.978 ms/op
                 existUser·p0.95:   3.084 ms/op
                 existUser·p0.99:   3.498 ms/op
                 existUser·p0.999:  5.259 ms/op
                 existUser·p0.9999: 12.676 ms/op
                 existUser·p1.00:   13.337 ms/op

Iteration   3: 2.469 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.059 ms/op
                 existUser·p0.50:   2.580 ms/op
                 existUser·p0.90:   2.982 ms/op
                 existUser·p0.95:   3.105 ms/op
                 existUser·p0.99:   3.998 ms/op
                 existUser·p0.999:  8.780 ms/op
                 existUser·p0.9999: 11.668 ms/op
                 existUser·p1.00:   12.534 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 392387
  mean =      2.444 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 41 
    [ 1.250,  2.500) = 195526 
    [ 2.500,  3.750) = 193492 
    [ 3.750,  5.000) = 2622 
    [ 5.000,  6.250) = 281 
    [ 6.250,  7.500) = 57 
    [ 7.500,  8.750) = 15 
    [ 8.750, 10.000) = 105 
    [10.000, 11.250) = 48 
    [11.250, 12.500) = 92 
    [12.500, 13.750) = 84 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.872 ms/op
     p(50.0000) =      2.507 ms/op
     p(90.0000) =      2.966 ms/op
     p(95.0000) =      3.072 ms/op
     p(99.0000) =      3.637 ms/op
     p(99.9000) =      6.595 ms/op
     p(99.9900) =     13.424 ms/op
     p(99.9990) =     14.405 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.415 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.549 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.522 ±(99.9%) 0.006 ms/op
Iteration   1: 2.493 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.921 ms/op
                 getUser·p0.50:   2.527 ms/op
                 getUser·p0.90:   3.027 ms/op
                 getUser·p0.95:   3.146 ms/op
                 getUser·p0.99:   3.817 ms/op
                 getUser·p0.999:  11.320 ms/op
                 getUser·p0.9999: 13.550 ms/op
                 getUser·p1.00:   14.156 ms/op

Iteration   2: 2.540 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.918 ms/op
                 getUser·p0.50:   2.560 ms/op
                 getUser·p0.90:   3.088 ms/op
                 getUser·p0.95:   3.277 ms/op
                 getUser·p0.99:   4.456 ms/op
                 getUser·p0.999:  9.187 ms/op
                 getUser·p0.9999: 13.795 ms/op
                 getUser·p1.00:   14.008 ms/op

Iteration   3: 2.505 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.977 ms/op
                 getUser·p0.50:   2.531 ms/op
                 getUser·p0.90:   3.052 ms/op
                 getUser·p0.95:   3.183 ms/op
                 getUser·p0.99:   3.891 ms/op
                 getUser·p0.999:  9.241 ms/op
                 getUser·p0.9999: 12.094 ms/op
                 getUser·p1.00:   12.878 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 381844
  mean =      2.512 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 82 
    [ 1.250,  2.500) = 187783 
    [ 2.500,  3.750) = 188215 
    [ 3.750,  5.000) = 4361 
    [ 5.000,  6.250) = 872 
    [ 6.250,  7.500) = 86 
    [ 7.500,  8.750) = 30 
    [ 8.750, 10.000) = 70 
    [10.000, 11.250) = 130 
    [11.250, 12.500) = 80 
    [12.500, 13.750) = 116 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.918 ms/op
     p(50.0000) =      2.540 ms/op
     p(90.0000) =      3.056 ms/op
     p(95.0000) =      3.195 ms/op
     p(99.0000) =      4.035 ms/op
     p(99.9000) =      9.437 ms/op
     p(99.9900) =     13.353 ms/op
     p(99.9990) =     13.995 ms/op
     p(99.9999) =     14.156 ms/op
    p(100.0000) =     14.156 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.704 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.022 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.005 ±(99.9%) 0.009 ms/op
Iteration   1: 2.989 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.024 ms/op
                 listUser·p0.50:   2.920 ms/op
                 listUser·p0.90:   3.875 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   5.628 ms/op
                 listUser·p0.999:  8.570 ms/op
                 listUser·p0.9999: 11.035 ms/op
                 listUser·p1.00:   11.534 ms/op

Iteration   2: 2.988 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.753 ms/op
                 listUser·p0.50:   2.920 ms/op
                 listUser·p0.90:   3.903 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   5.546 ms/op
                 listUser·p0.999:  9.142 ms/op
                 listUser·p0.9999: 15.781 ms/op
                 listUser·p1.00:   16.515 ms/op

Iteration   3: 2.976 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.834 ms/op
                 listUser·p0.50:   2.920 ms/op
                 listUser·p0.90:   3.854 ms/op
                 listUser·p0.95:   4.293 ms/op
                 listUser·p0.99:   5.407 ms/op
                 listUser·p0.999:  9.322 ms/op
                 listUser·p0.9999: 10.600 ms/op
                 listUser·p1.00:   10.977 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 321339
  mean =      2.984 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 158 
    [ 1.250,  2.500) = 97391 
    [ 2.500,  3.750) = 185115 
    [ 3.750,  5.000) = 31733 
    [ 5.000,  6.250) = 5621 
    [ 6.250,  7.500) = 679 
    [ 7.500,  8.750) = 263 
    [ 8.750, 10.000) = 248 
    [10.000, 11.250) = 88 
    [11.250, 12.500) = 10 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 19 
    [16.250, 17.500) = 5 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.753 ms/op
     p(50.0000) =      2.920 ms/op
     p(90.0000) =      3.875 ms/op
     p(95.0000) =      4.375 ms/op
     p(99.0000) =      5.546 ms/op
     p(99.9000) =      9.022 ms/op
     p(99.9900) =     13.991 ms/op
     p(99.9990) =     16.374 ms/op
     p(99.9999) =     16.515 ms/op
    p(100.0000) =     16.515 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.723 ± 0.874  ops/ms
ClientPb.existUser                       thrpt       3  13.299 ± 3.996  ops/ms
ClientPb.getUser                         thrpt       3  12.863 ± 0.957  ops/ms
ClientPb.listUser                        thrpt       3  10.696 ± 1.188  ops/ms
ClientPb.createUser                       avgt       3   2.494 ± 0.180   ms/op
ClientPb.existUser                        avgt       3   2.450 ± 0.153   ms/op
ClientPb.getUser                          avgt       3   2.478 ± 0.118   ms/op
ClientPb.listUser                         avgt       3   2.962 ± 0.123   ms/op
ClientPb.createUser                     sample  382572   2.507 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.922           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.568           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.043           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.162           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.817           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.946           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.332           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.238           ms/op
ClientPb.existUser                      sample  392387   2.444 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.872           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.507           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.966           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.072           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.637           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.595           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.424           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.598           ms/op
ClientPb.getUser                        sample  381844   2.512 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.918           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.540           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.056           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.195           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.035           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.437           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.353           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.156           ms/op
ClientPb.listUser                       sample  321339   2.984 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.753           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.920           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.875           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.375           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.546           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.022           ms/op
ClientPb.listUser:listUser·p0.9999      sample          13.991           ms/op
ClientPb.listUser:listUser·p1.00        sample          16.515           ms/op
