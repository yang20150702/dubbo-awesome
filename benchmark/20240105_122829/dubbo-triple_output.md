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
# Warmup Iteration   1: 4.846 ops/ms
# Warmup Iteration   2: 11.962 ops/ms
# Warmup Iteration   3: 12.220 ops/ms
Iteration   1: 12.421 ops/ms
Iteration   2: 12.397 ops/ms
Iteration   3: 12.556 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.458 ±(99.9%) 1.563 ops/ms [Average]
  (min, avg, max) = (12.397, 12.458, 12.556), stdev = 0.086
  CI (99.9%): [10.895, 14.021] (assumes normal distribution)


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
# Warmup Iteration   1: 8.663 ops/ms
# Warmup Iteration   2: 12.897 ops/ms
# Warmup Iteration   3: 13.152 ops/ms
Iteration   1: 13.274 ops/ms
Iteration   2: 13.083 ops/ms
Iteration   3: 13.100 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.152 ±(99.9%) 1.924 ops/ms [Average]
  (min, avg, max) = (13.083, 13.152, 13.274), stdev = 0.105
  CI (99.9%): [11.229, 15.076] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:46
# Fork: 1 of 1
# Warmup Iteration   1: 7.512 ops/ms
# Warmup Iteration   2: 12.657 ops/ms
# Warmup Iteration   3: 12.852 ops/ms
Iteration   1: 12.863 ops/ms
Iteration   2: 12.742 ops/ms
Iteration   3: 12.819 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.808 ±(99.9%) 1.118 ops/ms [Average]
  (min, avg, max) = (12.742, 12.808, 12.863), stdev = 0.061
  CI (99.9%): [11.690, 13.926] (assumes normal distribution)


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
# Warmup Iteration   1: 6.341 ops/ms
# Warmup Iteration   2: 10.485 ops/ms
# Warmup Iteration   3: 10.604 ops/ms
Iteration   1: 10.564 ops/ms
Iteration   2: 10.565 ops/ms
Iteration   3: 10.531 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.553 ±(99.9%) 0.356 ops/ms [Average]
  (min, avg, max) = (10.531, 10.553, 10.565), stdev = 0.020
  CI (99.9%): [10.197, 10.910] (assumes normal distribution)


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
# Warmup Iteration   1: 4.150 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.570 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.515 ±(99.9%) 0.004 ms/op
Iteration   1: 2.536 ±(99.9%) 0.003 ms/op
Iteration   2: 2.504 ±(99.9%) 0.005 ms/op
Iteration   3: 2.523 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.521 ±(99.9%) 0.292 ms/op [Average]
  (min, avg, max) = (2.504, 2.521, 2.536), stdev = 0.016
  CI (99.9%): [2.229, 2.813] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.591 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.451 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.433 ±(99.9%) 0.003 ms/op
Iteration   1: 2.421 ±(99.9%) 0.005 ms/op
Iteration   2: 2.423 ±(99.9%) 0.004 ms/op
Iteration   3: 2.429 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.424 ±(99.9%) 0.074 ms/op [Average]
  (min, avg, max) = (2.421, 2.424, 2.429), stdev = 0.004
  CI (99.9%): [2.350, 2.499] (assumes normal distribution)


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
# Warmup Iteration   1: 3.675 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.534 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.503 ±(99.9%) 0.005 ms/op
Iteration   1: 2.486 ±(99.9%) 0.004 ms/op
Iteration   2: 2.481 ±(99.9%) 0.004 ms/op
Iteration   3: 2.485 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.484 ±(99.9%) 0.052 ms/op [Average]
  (min, avg, max) = (2.481, 2.484, 2.486), stdev = 0.003
  CI (99.9%): [2.432, 2.536] (assumes normal distribution)


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
# Warmup Iteration   1: 4.566 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.012 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.026 ±(99.9%) 0.006 ms/op
Iteration   1: 2.976 ±(99.9%) 0.006 ms/op
Iteration   2: 2.980 ±(99.9%) 0.006 ms/op
Iteration   3: 2.990 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.982 ±(99.9%) 0.133 ms/op [Average]
  (min, avg, max) = (2.976, 2.982, 2.990), stdev = 0.007
  CI (99.9%): [2.849, 3.115] (assumes normal distribution)


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
# Warmup Iteration   1: 3.868 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.635 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.498 ±(99.9%) 0.005 ms/op
Iteration   1: 2.513 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.961 ms/op
                 createUser·p0.50:   2.544 ms/op
                 createUser·p0.90:   3.072 ms/op
                 createUser·p0.95:   3.203 ms/op
                 createUser·p0.99:   3.727 ms/op
                 createUser·p0.999:  10.420 ms/op
                 createUser·p0.9999: 13.730 ms/op
                 createUser·p1.00:   13.943 ms/op

Iteration   2: 2.466 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.042 ms/op
                 createUser·p0.50:   2.531 ms/op
                 createUser·p0.90:   2.986 ms/op
                 createUser·p0.95:   3.080 ms/op
                 createUser·p0.99:   3.533 ms/op
                 createUser·p0.999:  7.420 ms/op
                 createUser·p0.9999: 18.678 ms/op
                 createUser·p1.00:   18.940 ms/op

Iteration   3: 2.510 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.963 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.042 ms/op
                 createUser·p0.95:   3.170 ms/op
                 createUser·p0.99:   4.092 ms/op
                 createUser·p0.999:  8.520 ms/op
                 createUser·p0.9999: 10.682 ms/op
                 createUser·p1.00:   11.682 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 384250
  mean =      2.496 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 50 
    [ 1.250,  2.500) = 188127 
    [ 2.500,  3.750) = 192146 
    [ 3.750,  5.000) = 3162 
    [ 5.000,  6.250) = 337 
    [ 6.250,  7.500) = 11 
    [ 7.500,  8.750) = 62 
    [ 8.750, 10.000) = 65 
    [10.000, 11.250) = 92 
    [11.250, 12.500) = 88 
    [12.500, 13.750) = 68 
    [13.750, 15.000) = 10 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.961 ms/op
     p(50.0000) =      2.548 ms/op
     p(90.0000) =      3.031 ms/op
     p(95.0000) =      3.154 ms/op
     p(99.0000) =      3.764 ms/op
     p(99.9000) =      8.507 ms/op
     p(99.9900) =     13.814 ms/op
     p(99.9990) =     18.809 ms/op
     p(99.9999) =     18.940 ms/op
    p(100.0000) =     18.940 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.750 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.494 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.447 ±(99.9%) 0.005 ms/op
Iteration   1: 2.463 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.085 ms/op
                 existUser·p0.50:   2.568 ms/op
                 existUser·p0.90:   2.986 ms/op
                 existUser·p0.95:   3.072 ms/op
                 existUser·p0.99:   3.396 ms/op
                 existUser·p0.999:  6.510 ms/op
                 existUser·p0.9999: 17.698 ms/op
                 existUser·p1.00:   18.121 ms/op

Iteration   2: 2.457 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.988 ms/op
                 existUser·p0.50:   2.490 ms/op
                 existUser·p0.90:   2.994 ms/op
                 existUser·p0.95:   3.092 ms/op
                 existUser·p0.99:   3.559 ms/op
                 existUser·p0.999:  9.126 ms/op
                 existUser·p0.9999: 13.205 ms/op
                 existUser·p1.00:   14.270 ms/op

Iteration   3: 2.465 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.026 ms/op
                 existUser·p0.50:   2.519 ms/op
                 existUser·p0.90:   3.002 ms/op
                 existUser·p0.95:   3.105 ms/op
                 existUser·p0.99:   3.539 ms/op
                 existUser·p0.999:  5.956 ms/op
                 existUser·p0.9999: 11.846 ms/op
                 existUser·p1.00:   12.878 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 389687
  mean =      2.462 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 40 
    [ 1.250,  2.500) = 193354 
    [ 2.500,  3.750) = 193597 
    [ 3.750,  5.000) = 1981 
    [ 5.000,  6.250) = 308 
    [ 6.250,  7.500) = 47 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 75 
    [10.000, 11.250) = 95 
    [11.250, 12.500) = 90 
    [12.500, 13.750) = 58 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 16 
    [17.500, 18.750) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.988 ms/op
     p(50.0000) =      2.523 ms/op
     p(90.0000) =      2.994 ms/op
     p(95.0000) =      3.088 ms/op
     p(99.0000) =      3.494 ms/op
     p(99.9000) =      6.701 ms/op
     p(99.9900) =     13.763 ms/op
     p(99.9990) =     18.022 ms/op
     p(99.9999) =     18.121 ms/op
    p(100.0000) =     18.121 ms/op


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
# Warmup Iteration   1: 3.760 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.572 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.500 ±(99.9%) 0.006 ms/op
Iteration   1: 2.483 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.737 ms/op
                 getUser·p0.50:   2.507 ms/op
                 getUser·p0.90:   3.019 ms/op
                 getUser·p0.95:   3.117 ms/op
                 getUser·p0.99:   3.625 ms/op
                 getUser·p0.999:  7.329 ms/op
                 getUser·p0.9999: 13.208 ms/op
                 getUser·p1.00:   13.713 ms/op

Iteration   2: 2.518 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.974 ms/op
                 getUser·p0.50:   2.544 ms/op
                 getUser·p0.90:   3.060 ms/op
                 getUser·p0.95:   3.191 ms/op
                 getUser·p0.99:   4.227 ms/op
                 getUser·p0.999:  5.825 ms/op
                 getUser·p0.9999: 15.853 ms/op
                 getUser·p1.00:   17.596 ms/op

Iteration   3: 2.486 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.874 ms/op
                 getUser·p0.50:   2.499 ms/op
                 getUser·p0.90:   3.039 ms/op
                 getUser·p0.95:   3.178 ms/op
                 getUser·p0.99:   3.830 ms/op
                 getUser·p0.999:  8.605 ms/op
                 getUser·p0.9999: 11.420 ms/op
                 getUser·p1.00:   12.354 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 384277
  mean =      2.496 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 66 
    [ 1.250,  2.500) = 191011 
    [ 2.500,  3.750) = 188557 
    [ 3.750,  5.000) = 3701 
    [ 5.000,  6.250) = 566 
    [ 6.250,  7.500) = 17 
    [ 7.500,  8.750) = 7 
    [ 8.750, 10.000) = 52 
    [10.000, 11.250) = 104 
    [11.250, 12.500) = 119 
    [12.500, 13.750) = 45 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 23 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.737 ms/op
     p(50.0000) =      2.515 ms/op
     p(90.0000) =      3.039 ms/op
     p(95.0000) =      3.162 ms/op
     p(99.0000) =      3.863 ms/op
     p(99.9000) =      5.976 ms/op
     p(99.9900) =     13.543 ms/op
     p(99.9990) =     17.339 ms/op
     p(99.9999) =     17.596 ms/op
    p(100.0000) =     17.596 ms/op


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
# Warmup Iteration   1: 4.830 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.076 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.037 ±(99.9%) 0.009 ms/op
Iteration   1: 2.984 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.961 ms/op
                 listUser·p0.50:   2.912 ms/op
                 listUser·p0.90:   3.871 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   5.693 ms/op
                 listUser·p0.999:  8.960 ms/op
                 listUser·p0.9999: 12.094 ms/op
                 listUser·p1.00:   13.599 ms/op

Iteration   2: 3.002 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.851 ms/op
                 listUser·p0.50:   2.941 ms/op
                 listUser·p0.90:   3.883 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.571 ms/op
                 listUser·p0.999:  9.208 ms/op
                 listUser·p0.9999: 10.470 ms/op
                 listUser·p1.00:   11.272 ms/op

Iteration   3: 2.989 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.861 ms/op
                 listUser·p0.50:   2.920 ms/op
                 listUser·p0.90:   3.883 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   5.706 ms/op
                 listUser·p0.999:  8.995 ms/op
                 listUser·p0.9999: 11.735 ms/op
                 listUser·p1.00:   12.567 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 320581
  mean =      2.992 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 166 
    [ 1.250,  2.500) = 96815 
    [ 2.500,  3.750) = 184492 
    [ 3.750,  5.000) = 31547 
    [ 5.000,  6.250) = 6022 
    [ 6.250,  7.500) = 935 
    [ 7.500,  8.750) = 233 
    [ 8.750, 10.000) = 256 
    [10.000, 11.250) = 82 
    [11.250, 12.500) = 27 
    [12.500, 13.750) = 6 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.851 ms/op
     p(50.0000) =      2.925 ms/op
     p(90.0000) =      3.879 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      5.662 ms/op
     p(99.9000) =      9.044 ms/op
     p(99.9900) =     11.596 ms/op
     p(99.9990) =     13.009 ms/op
     p(99.9999) =     13.599 ms/op
    p(100.0000) =     13.599 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.458 ± 1.563  ops/ms
ClientPb.existUser                       thrpt       3  13.152 ± 1.924  ops/ms
ClientPb.getUser                         thrpt       3  12.808 ± 1.118  ops/ms
ClientPb.listUser                        thrpt       3  10.553 ± 0.356  ops/ms
ClientPb.createUser                       avgt       3   2.521 ± 0.292   ms/op
ClientPb.existUser                        avgt       3   2.424 ± 0.074   ms/op
ClientPb.getUser                          avgt       3   2.484 ± 0.052   ms/op
ClientPb.listUser                         avgt       3   2.982 ± 0.133   ms/op
ClientPb.createUser                     sample  384250   2.496 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.961           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.548           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.031           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.154           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.764           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.507           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.814           ms/op
ClientPb.createUser:createUser·p1.00    sample          18.940           ms/op
ClientPb.existUser                      sample  389687   2.462 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.988           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.523           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.994           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.088           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.494           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.701           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.763           ms/op
ClientPb.existUser:existUser·p1.00      sample          18.121           ms/op
ClientPb.getUser                        sample  384277   2.496 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.737           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.515           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.039           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.162           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.863           ms/op
ClientPb.getUser:getUser·p0.999         sample           5.976           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.543           ms/op
ClientPb.getUser:getUser·p1.00          sample          17.596           ms/op
ClientPb.listUser                       sample  320581   2.992 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.851           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.925           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.879           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.383           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.662           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.044           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.596           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.599           ms/op
