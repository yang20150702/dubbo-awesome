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
# Warmup Iteration   1: 5.098 ops/ms
# Warmup Iteration   2: 12.408 ops/ms
# Warmup Iteration   3: 12.410 ops/ms
Iteration   1: 12.591 ops/ms
Iteration   2: 12.622 ops/ms
Iteration   3: 12.819 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.677 ±(99.9%) 2.255 ops/ms [Average]
  (min, avg, max) = (12.591, 12.677, 12.819), stdev = 0.124
  CI (99.9%): [10.422, 14.932] (assumes normal distribution)


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
# Warmup Iteration   1: 8.050 ops/ms
# Warmup Iteration   2: 13.074 ops/ms
# Warmup Iteration   3: 13.071 ops/ms
Iteration   1: 12.898 ops/ms
Iteration   2: 13.081 ops/ms
Iteration   3: 13.117 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.032 ±(99.9%) 2.143 ops/ms [Average]
  (min, avg, max) = (12.898, 13.032, 13.117), stdev = 0.117
  CI (99.9%): [10.888, 15.175] (assumes normal distribution)


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
# Warmup Iteration   1: 7.631 ops/ms
# Warmup Iteration   2: 12.586 ops/ms
# Warmup Iteration   3: 12.931 ops/ms
Iteration   1: 12.853 ops/ms
Iteration   2: 12.780 ops/ms
Iteration   3: 12.973 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.869 ±(99.9%) 1.772 ops/ms [Average]
  (min, avg, max) = (12.780, 12.869, 12.973), stdev = 0.097
  CI (99.9%): [11.096, 14.641] (assumes normal distribution)


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
# Warmup Iteration   1: 6.696 ops/ms
# Warmup Iteration   2: 10.483 ops/ms
# Warmup Iteration   3: 10.381 ops/ms
Iteration   1: 10.607 ops/ms
Iteration   2: 10.617 ops/ms
Iteration   3: 10.625 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.616 ±(99.9%) 0.166 ops/ms [Average]
  (min, avg, max) = (10.607, 10.616, 10.625), stdev = 0.009
  CI (99.9%): [10.450, 10.782] (assumes normal distribution)


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
# Warmup Iteration   1: 4.105 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 2.612 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.551 ±(99.9%) 0.005 ms/op
Iteration   1: 2.590 ±(99.9%) 0.004 ms/op
Iteration   2: 2.562 ±(99.9%) 0.004 ms/op
Iteration   3: 2.542 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.565 ±(99.9%) 0.437 ms/op [Average]
  (min, avg, max) = (2.542, 2.565, 2.590), stdev = 0.024
  CI (99.9%): [2.127, 3.002] (assumes normal distribution)


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
# Warmup Iteration   1: 3.642 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.456 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.445 ±(99.9%) 0.004 ms/op
Iteration   1: 2.443 ±(99.9%) 0.004 ms/op
Iteration   2: 2.419 ±(99.9%) 0.004 ms/op
Iteration   3: 2.425 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.429 ±(99.9%) 0.230 ms/op [Average]
  (min, avg, max) = (2.419, 2.429, 2.443), stdev = 0.013
  CI (99.9%): [2.199, 2.659] (assumes normal distribution)


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
# Warmup Iteration   1: 3.992 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.563 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.529 ±(99.9%) 0.004 ms/op
Iteration   1: 2.506 ±(99.9%) 0.004 ms/op
Iteration   2: 2.502 ±(99.9%) 0.003 ms/op
Iteration   3: 2.527 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.512 ±(99.9%) 0.242 ms/op [Average]
  (min, avg, max) = (2.502, 2.512, 2.527), stdev = 0.013
  CI (99.9%): [2.270, 2.753] (assumes normal distribution)


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
# Warmup Iteration   1: 4.691 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.045 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.043 ±(99.9%) 0.005 ms/op
Iteration   1: 3.060 ±(99.9%) 0.006 ms/op
Iteration   2: 3.041 ±(99.9%) 0.006 ms/op
Iteration   3: 3.055 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.052 ±(99.9%) 0.180 ms/op [Average]
  (min, avg, max) = (3.041, 3.052, 3.060), stdev = 0.010
  CI (99.9%): [2.872, 3.232] (assumes normal distribution)


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
# Warmup Iteration   1: 4.190 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.695 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.536 ±(99.9%) 0.006 ms/op
Iteration   1: 2.524 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.844 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.068 ms/op
                 createUser·p0.95:   3.187 ms/op
                 createUser·p0.99:   3.717 ms/op
                 createUser·p0.999:  11.273 ms/op
                 createUser·p0.9999: 13.555 ms/op
                 createUser·p1.00:   14.057 ms/op

Iteration   2: 2.517 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.937 ms/op
                 createUser·p0.50:   2.585 ms/op
                 createUser·p0.90:   3.060 ms/op
                 createUser·p0.95:   3.187 ms/op
                 createUser·p0.99:   3.744 ms/op
                 createUser·p0.999:  9.862 ms/op
                 createUser·p0.9999: 12.216 ms/op
                 createUser·p1.00:   13.500 ms/op

Iteration   3: 2.534 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.019 ms/op
                 createUser·p0.50:   2.548 ms/op
                 createUser·p0.90:   3.084 ms/op
                 createUser·p0.95:   3.244 ms/op
                 createUser·p0.99:   4.108 ms/op
                 createUser·p0.999:  9.171 ms/op
                 createUser·p0.9999: 10.852 ms/op
                 createUser·p1.00:   11.338 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 379908
  mean =      2.525 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 61 
    [ 1.250,  2.500) = 182588 
    [ 2.500,  3.750) = 192708 
    [ 3.750,  5.000) = 3676 
    [ 5.000,  6.250) = 393 
    [ 6.250,  7.500) = 31 
    [ 7.500,  8.750) = 62 
    [ 8.750, 10.000) = 67 
    [10.000, 11.250) = 145 
    [11.250, 12.500) = 91 
    [12.500, 13.750) = 80 
    [13.750, 15.000) = 6 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.844 ms/op
     p(50.0000) =      2.572 ms/op
     p(90.0000) =      3.072 ms/op
     p(95.0000) =      3.203 ms/op
     p(99.0000) =      3.846 ms/op
     p(99.9000) =      9.193 ms/op
     p(99.9900) =     13.173 ms/op
     p(99.9990) =     13.874 ms/op
     p(99.9999) =     14.057 ms/op
    p(100.0000) =     14.057 ms/op


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
# Warmup Iteration   1: 3.692 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.504 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.436 ±(99.9%) 0.005 ms/op
Iteration   1: 2.456 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.135 ms/op
                 existUser·p0.50:   2.515 ms/op
                 existUser·p0.90:   2.986 ms/op
                 existUser·p0.95:   3.092 ms/op
                 existUser·p0.99:   3.494 ms/op
                 existUser·p0.999:  6.142 ms/op
                 existUser·p0.9999: 14.582 ms/op
                 existUser·p1.00:   14.926 ms/op

Iteration   2: 2.446 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.942 ms/op
                 existUser·p0.50:   2.515 ms/op
                 existUser·p0.90:   2.982 ms/op
                 existUser·p0.95:   3.088 ms/op
                 existUser·p0.99:   3.531 ms/op
                 existUser·p0.999:  7.025 ms/op
                 existUser·p0.9999: 14.630 ms/op
                 existUser·p1.00:   15.155 ms/op

Iteration   3: 2.470 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.871 ms/op
                 existUser·p0.50:   2.523 ms/op
                 existUser·p0.90:   3.011 ms/op
                 existUser·p0.95:   3.138 ms/op
                 existUser·p0.99:   3.785 ms/op
                 existUser·p0.999:  6.263 ms/op
                 existUser·p0.9999: 13.517 ms/op
                 existUser·p1.00:   13.877 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 390396
  mean =      2.457 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 47 
    [ 1.250,  2.500) = 193403 
    [ 2.500,  3.750) = 193821 
    [ 3.750,  5.000) = 2379 
    [ 5.000,  6.250) = 337 
    [ 6.250,  7.500) = 54 
    [ 7.500,  8.750) = 37 
    [ 8.750, 10.000) = 35 
    [10.000, 11.250) = 54 
    [11.250, 12.500) = 64 
    [12.500, 13.750) = 93 
    [13.750, 15.000) = 66 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.871 ms/op
     p(50.0000) =      2.519 ms/op
     p(90.0000) =      2.994 ms/op
     p(95.0000) =      3.105 ms/op
     p(99.0000) =      3.617 ms/op
     p(99.9000) =      6.526 ms/op
     p(99.9900) =     14.336 ms/op
     p(99.9990) =     15.026 ms/op
     p(99.9999) =     15.155 ms/op
    p(100.0000) =     15.155 ms/op


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
# Warmup Iteration   1: 3.713 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.561 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.487 ±(99.9%) 0.006 ms/op
Iteration   1: 2.476 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.683 ms/op
                 getUser·p0.50:   2.490 ms/op
                 getUser·p0.90:   3.019 ms/op
                 getUser·p0.95:   3.142 ms/op
                 getUser·p0.99:   3.744 ms/op
                 getUser·p0.999:  6.918 ms/op
                 getUser·p0.9999: 15.654 ms/op
                 getUser·p1.00:   16.171 ms/op

Iteration   2: 2.531 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.049 ms/op
                 getUser·p0.50:   2.544 ms/op
                 getUser·p0.90:   3.080 ms/op
                 getUser·p0.95:   3.289 ms/op
                 getUser·p0.99:   4.711 ms/op
                 getUser·p0.999:  8.625 ms/op
                 getUser·p0.9999: 13.244 ms/op
                 getUser·p1.00:   13.681 ms/op

Iteration   3: 2.503 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.017 ms/op
                 getUser·p0.50:   2.531 ms/op
                 getUser·p0.90:   3.064 ms/op
                 getUser·p0.95:   3.215 ms/op
                 getUser·p0.99:   3.912 ms/op
                 getUser·p0.999:  5.714 ms/op
                 getUser·p0.9999: 9.771 ms/op
                 getUser·p1.00:   11.223 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 383167
  mean =      2.503 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 99 
    [ 1.250,  2.500) = 188991 
    [ 2.500,  3.750) = 188027 
    [ 3.750,  5.000) = 4838 
    [ 5.000,  6.250) = 779 
    [ 6.250,  7.500) = 78 
    [ 7.500,  8.750) = 47 
    [ 8.750, 10.000) = 63 
    [10.000, 11.250) = 57 
    [11.250, 12.500) = 64 
    [12.500, 13.750) = 76 
    [13.750, 15.000) = 22 
    [15.000, 16.250) = 26 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.683 ms/op
     p(50.0000) =      2.523 ms/op
     p(90.0000) =      3.052 ms/op
     p(95.0000) =      3.211 ms/op
     p(99.0000) =      4.067 ms/op
     p(99.9000) =      6.636 ms/op
     p(99.9900) =     14.445 ms/op
     p(99.9990) =     16.051 ms/op
     p(99.9999) =     16.171 ms/op
    p(100.0000) =     16.171 ms/op


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
# Warmup Iteration   1: 4.968 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.041 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.011 ±(99.9%) 0.008 ms/op
Iteration   1: 3.000 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.802 ms/op
                 listUser·p0.50:   2.933 ms/op
                 listUser·p0.90:   3.895 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   5.644 ms/op
                 listUser·p0.999:  8.894 ms/op
                 listUser·p0.9999: 11.518 ms/op
                 listUser·p1.00:   12.419 ms/op

Iteration   2: 3.014 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.897 ms/op
                 listUser·p0.50:   2.949 ms/op
                 listUser·p0.90:   3.936 ms/op
                 listUser·p0.95:   4.473 ms/op
                 listUser·p0.99:   5.579 ms/op
                 listUser·p0.999:  9.354 ms/op
                 listUser·p0.9999: 11.376 ms/op
                 listUser·p1.00:   12.681 ms/op

Iteration   3: 2.987 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.872 ms/op
                 listUser·p0.50:   2.937 ms/op
                 listUser·p0.90:   3.838 ms/op
                 listUser·p0.95:   4.309 ms/op
                 listUser·p0.99:   5.415 ms/op
                 listUser·p0.999:  9.126 ms/op
                 listUser·p0.9999: 10.015 ms/op
                 listUser·p1.00:   10.732 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 319688
  mean =      3.000 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 131 
    [ 1.250,  2.500) = 95404 
    [ 2.500,  3.750) = 184846 
    [ 3.750,  5.000) = 32056 
    [ 5.000,  6.250) = 5998 
    [ 6.250,  7.500) = 594 
    [ 7.500,  8.750) = 236 
    [ 8.750, 10.000) = 276 
    [10.000, 11.250) = 104 
    [11.250, 12.500) = 38 
    [12.500, 13.750) = 5 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.802 ms/op
     p(50.0000) =      2.937 ms/op
     p(90.0000) =      3.887 ms/op
     p(95.0000) =      4.399 ms/op
     p(99.0000) =      5.554 ms/op
     p(99.9000) =      9.142 ms/op
     p(99.9900) =     11.420 ms/op
     p(99.9990) =     12.560 ms/op
     p(99.9999) =     12.681 ms/op
    p(100.0000) =     12.681 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.677 ± 2.255  ops/ms
ClientPb.existUser                       thrpt       3  13.032 ± 2.143  ops/ms
ClientPb.getUser                         thrpt       3  12.869 ± 1.772  ops/ms
ClientPb.listUser                        thrpt       3  10.616 ± 0.166  ops/ms
ClientPb.createUser                       avgt       3   2.565 ± 0.437   ms/op
ClientPb.existUser                        avgt       3   2.429 ± 0.230   ms/op
ClientPb.getUser                          avgt       3   2.512 ± 0.242   ms/op
ClientPb.listUser                         avgt       3   3.052 ± 0.180   ms/op
ClientPb.createUser                     sample  379908   2.525 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.844           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.572           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.072           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.203           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.846           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.193           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.173           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.057           ms/op
ClientPb.existUser                      sample  390396   2.457 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.871           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.519           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.994           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.105           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.617           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.526           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.336           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.155           ms/op
ClientPb.getUser                        sample  383167   2.503 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.683           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.523           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.052           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.211           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.067           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.636           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.445           ms/op
ClientPb.getUser:getUser·p1.00          sample          16.171           ms/op
ClientPb.listUser                       sample  319688   3.000 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.802           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.937           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.887           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.399           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.554           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.142           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.420           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.681           ms/op
