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
# Warmup Iteration   1: 4.979 ops/ms
# Warmup Iteration   2: 11.875 ops/ms
# Warmup Iteration   3: 12.156 ops/ms
Iteration   1: 12.449 ops/ms
Iteration   2: 12.261 ops/ms
Iteration   3: 12.481 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.397 ±(99.9%) 2.172 ops/ms [Average]
  (min, avg, max) = (12.261, 12.397, 12.481), stdev = 0.119
  CI (99.9%): [10.225, 14.569] (assumes normal distribution)


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
# Warmup Iteration   1: 7.619 ops/ms
# Warmup Iteration   2: 12.991 ops/ms
# Warmup Iteration   3: 12.968 ops/ms
Iteration   1: 13.078 ops/ms
Iteration   2: 12.969 ops/ms
Iteration   3: 13.228 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.092 ±(99.9%) 2.372 ops/ms [Average]
  (min, avg, max) = (12.969, 13.092, 13.228), stdev = 0.130
  CI (99.9%): [10.720, 15.464] (assumes normal distribution)


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
# Warmup Iteration   1: 7.435 ops/ms
# Warmup Iteration   2: 12.206 ops/ms
# Warmup Iteration   3: 12.590 ops/ms
Iteration   1: 12.570 ops/ms
Iteration   2: 12.480 ops/ms
Iteration   3: 12.548 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.533 ±(99.9%) 0.850 ops/ms [Average]
  (min, avg, max) = (12.480, 12.533, 12.570), stdev = 0.047
  CI (99.9%): [11.683, 13.382] (assumes normal distribution)


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
# Warmup Iteration   1: 6.753 ops/ms
# Warmup Iteration   2: 10.339 ops/ms
# Warmup Iteration   3: 10.483 ops/ms
Iteration   1: 10.437 ops/ms
Iteration   2: 10.477 ops/ms
Iteration   3: 10.558 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.491 ±(99.9%) 1.120 ops/ms [Average]
  (min, avg, max) = (10.437, 10.491, 10.558), stdev = 0.061
  CI (99.9%): [9.371, 11.611] (assumes normal distribution)


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
# Warmup Iteration   1: 4.043 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.659 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.609 ±(99.9%) 0.005 ms/op
Iteration   1: 2.624 ±(99.9%) 0.004 ms/op
Iteration   2: 2.668 ±(99.9%) 0.004 ms/op
Iteration   3: 2.598 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.630 ±(99.9%) 0.640 ms/op [Average]
  (min, avg, max) = (2.598, 2.630, 2.668), stdev = 0.035
  CI (99.9%): [1.990, 3.270] (assumes normal distribution)


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
# Warmup Iteration   1: 3.889 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.472 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.410 ±(99.9%) 0.006 ms/op
Iteration   1: 2.443 ±(99.9%) 0.006 ms/op
Iteration   2: 2.498 ±(99.9%) 0.004 ms/op
Iteration   3: 2.475 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.472 ±(99.9%) 0.507 ms/op [Average]
  (min, avg, max) = (2.443, 2.472, 2.498), stdev = 0.028
  CI (99.9%): [1.965, 2.978] (assumes normal distribution)


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
# Warmup Iteration   1: 3.941 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.631 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.579 ±(99.9%) 0.005 ms/op
Iteration   1: 2.578 ±(99.9%) 0.005 ms/op
Iteration   2: 2.574 ±(99.9%) 0.005 ms/op
Iteration   3: 2.520 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.557 ±(99.9%) 0.594 ms/op [Average]
  (min, avg, max) = (2.520, 2.557, 2.578), stdev = 0.033
  CI (99.9%): [1.963, 3.152] (assumes normal distribution)


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
# Warmup Iteration   1: 4.794 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.047 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.999 ±(99.9%) 0.007 ms/op
Iteration   1: 2.999 ±(99.9%) 0.008 ms/op
Iteration   2: 2.986 ±(99.9%) 0.009 ms/op
Iteration   3: 3.020 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.002 ±(99.9%) 0.315 ms/op [Average]
  (min, avg, max) = (2.986, 3.002, 3.020), stdev = 0.017
  CI (99.9%): [2.687, 3.317] (assumes normal distribution)


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
# Warmup Iteration   1: 4.480 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 2.650 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.562 ±(99.9%) 0.006 ms/op
Iteration   1: 2.565 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.108 ms/op
                 createUser·p0.50:   2.613 ms/op
                 createUser·p0.90:   3.117 ms/op
                 createUser·p0.95:   3.236 ms/op
                 createUser·p0.99:   3.793 ms/op
                 createUser·p0.999:  11.639 ms/op
                 createUser·p0.9999: 15.221 ms/op
                 createUser·p1.00:   15.630 ms/op

Iteration   2: 2.555 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.910 ms/op
                 createUser·p0.50:   2.617 ms/op
                 createUser·p0.90:   3.105 ms/op
                 createUser·p0.95:   3.224 ms/op
                 createUser·p0.99:   3.750 ms/op
                 createUser·p0.999:  10.200 ms/op
                 createUser·p0.9999: 12.829 ms/op
                 createUser·p1.00:   13.795 ms/op

Iteration   3: 2.570 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.544 ms/op
                 createUser·p0.50:   2.609 ms/op
                 createUser·p0.90:   3.125 ms/op
                 createUser·p0.95:   3.256 ms/op
                 createUser·p0.99:   3.916 ms/op
                 createUser·p0.999:  9.191 ms/op
                 createUser·p0.9999: 11.158 ms/op
                 createUser·p1.00:   11.452 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 374200
  mean =      2.563 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 61 
    [ 1.250,  2.500) = 177927 
    [ 2.500,  3.750) = 191957 
    [ 3.750,  5.000) = 3357 
    [ 5.000,  6.250) = 373 
    [ 6.250,  7.500) = 95 
    [ 7.500,  8.750) = 38 
    [ 8.750, 10.000) = 67 
    [10.000, 11.250) = 132 
    [11.250, 12.500) = 76 
    [12.500, 13.750) = 57 
    [13.750, 15.000) = 45 
    [15.000, 16.250) = 15 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.544 ms/op
     p(50.0000) =      2.613 ms/op
     p(90.0000) =      3.117 ms/op
     p(95.0000) =      3.240 ms/op
     p(99.0000) =      3.822 ms/op
     p(99.9000) =      9.241 ms/op
     p(99.9900) =     14.221 ms/op
     p(99.9990) =     15.540 ms/op
     p(99.9999) =     15.630 ms/op
    p(100.0000) =     15.630 ms/op


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
# Warmup Iteration   1: 3.889 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.532 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.517 ±(99.9%) 0.005 ms/op
Iteration   1: 2.503 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.913 ms/op
                 existUser·p0.50:   2.564 ms/op
                 existUser·p0.90:   3.035 ms/op
                 existUser·p0.95:   3.133 ms/op
                 existUser·p0.99:   3.576 ms/op
                 existUser·p0.999:  11.026 ms/op
                 existUser·p0.9999: 13.577 ms/op
                 existUser·p1.00:   14.549 ms/op

Iteration   2: 2.524 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.449 ms/op
                 existUser·p0.50:   2.531 ms/op
                 existUser·p0.90:   3.080 ms/op
                 existUser·p0.95:   3.199 ms/op
                 existUser·p0.99:   3.674 ms/op
                 existUser·p0.999:  6.789 ms/op
                 existUser·p0.9999: 13.189 ms/op
                 existUser·p1.00:   13.779 ms/op

Iteration   3: 2.514 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.029 ms/op
                 existUser·p0.50:   2.519 ms/op
                 existUser·p0.90:   3.060 ms/op
                 existUser·p0.95:   3.170 ms/op
                 existUser·p0.99:   3.666 ms/op
                 existUser·p0.999:  8.517 ms/op
                 existUser·p0.9999: 12.878 ms/op
                 existUser·p1.00:   13.091 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 381645
  mean =      2.513 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 83 
    [ 1.250,  2.500) = 187859 
    [ 2.500,  3.750) = 190577 
    [ 3.750,  5.000) = 2207 
    [ 5.000,  6.250) = 493 
    [ 6.250,  7.500) = 61 
    [ 7.500,  8.750) = 27 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 55 
    [11.250, 12.500) = 131 
    [12.500, 13.750) = 113 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.449 ms/op
     p(50.0000) =      2.535 ms/op
     p(90.0000) =      3.056 ms/op
     p(95.0000) =      3.170 ms/op
     p(99.0000) =      3.637 ms/op
     p(99.9000) =      6.944 ms/op
     p(99.9900) =     13.320 ms/op
     p(99.9990) =     13.990 ms/op
     p(99.9999) =     14.549 ms/op
    p(100.0000) =     14.549 ms/op


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
# Warmup Iteration   1: 4.087 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.649 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.551 ±(99.9%) 0.006 ms/op
Iteration   1: 2.523 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.879 ms/op
                 getUser·p0.50:   2.531 ms/op
                 getUser·p0.90:   3.072 ms/op
                 getUser·p0.95:   3.183 ms/op
                 getUser·p0.99:   3.707 ms/op
                 getUser·p0.999:  11.678 ms/op
                 getUser·p0.9999: 13.965 ms/op
                 getUser·p1.00:   14.238 ms/op

Iteration   2: 2.578 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.366 ms/op
                 getUser·p0.50:   2.605 ms/op
                 getUser·p0.90:   3.113 ms/op
                 getUser·p0.95:   3.265 ms/op
                 getUser·p0.99:   4.735 ms/op
                 getUser·p0.999:  10.438 ms/op
                 getUser·p0.9999: 25.087 ms/op
                 getUser·p1.00:   25.657 ms/op

Iteration   3: 2.549 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.077 ms/op
                 getUser·p0.50:   2.572 ms/op
                 getUser·p0.90:   3.101 ms/op
                 getUser·p0.95:   3.232 ms/op
                 getUser·p0.99:   3.879 ms/op
                 getUser·p0.999:  9.660 ms/op
                 getUser·p0.9999: 11.910 ms/op
                 getUser·p1.00:   12.239 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 376123
  mean =      2.550 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 183295 
    [ 2.500,  5.000) = 191454 
    [ 5.000,  7.500) = 985 
    [ 7.500, 10.000) = 44 
    [10.000, 12.500) = 157 
    [12.500, 15.000) = 153 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.366 ms/op
     p(50.0000) =      2.568 ms/op
     p(90.0000) =      3.097 ms/op
     p(95.0000) =      3.224 ms/op
     p(99.0000) =      4.076 ms/op
     p(99.9000) =      9.716 ms/op
     p(99.9900) =     14.816 ms/op
     p(99.9990) =     25.272 ms/op
     p(99.9999) =     25.657 ms/op
    p(100.0000) =     25.657 ms/op


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
# Warmup Iteration   1: 4.652 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.042 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.046 ±(99.9%) 0.009 ms/op
Iteration   1: 3.046 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.737 ms/op
                 listUser·p0.50:   2.974 ms/op
                 listUser·p0.90:   3.957 ms/op
                 listUser·p0.95:   4.506 ms/op
                 listUser·p0.99:   5.784 ms/op
                 listUser·p0.999:  9.290 ms/op
                 listUser·p0.9999: 11.092 ms/op
                 listUser·p1.00:   12.272 ms/op

Iteration   2: 3.031 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.953 ms/op
                 listUser·p0.50:   2.982 ms/op
                 listUser·p0.90:   3.920 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.472 ms/op
                 listUser·p0.999:  9.570 ms/op
                 listUser·p0.9999: 12.419 ms/op
                 listUser·p1.00:   13.058 ms/op

Iteration   3: 3.027 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.921 ms/op
                 listUser·p0.50:   2.966 ms/op
                 listUser·p0.90:   3.908 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   5.628 ms/op
                 listUser·p0.999:  9.133 ms/op
                 listUser·p0.9999: 18.463 ms/op
                 listUser·p1.00:   18.842 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 316107
  mean =      3.035 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 153 
    [ 1.250,  2.500) = 91074 
    [ 2.500,  3.750) = 183630 
    [ 3.750,  5.000) = 33544 
    [ 5.000,  6.250) = 6363 
    [ 6.250,  7.500) = 679 
    [ 7.500,  8.750) = 256 
    [ 8.750, 10.000) = 178 
    [10.000, 11.250) = 131 
    [11.250, 12.500) = 55 
    [12.500, 13.750) = 12 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 10 
    [17.500, 18.750) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.737 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.928 ms/op
     p(95.0000) =      4.424 ms/op
     p(99.0000) =      5.644 ms/op
     p(99.9000) =      9.322 ms/op
     p(99.9900) =     16.727 ms/op
     p(99.9990) =     18.640 ms/op
     p(99.9999) =     18.842 ms/op
    p(100.0000) =     18.842 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.397 ± 2.172  ops/ms
ClientPb.existUser                       thrpt       3  13.092 ± 2.372  ops/ms
ClientPb.getUser                         thrpt       3  12.533 ± 0.850  ops/ms
ClientPb.listUser                        thrpt       3  10.491 ± 1.120  ops/ms
ClientPb.createUser                       avgt       3   2.630 ± 0.640   ms/op
ClientPb.existUser                        avgt       3   2.472 ± 0.507   ms/op
ClientPb.getUser                          avgt       3   2.557 ± 0.594   ms/op
ClientPb.listUser                         avgt       3   3.002 ± 0.315   ms/op
ClientPb.createUser                     sample  374200   2.563 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.544           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.613           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.117           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.240           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.822           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.241           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.221           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.630           ms/op
ClientPb.existUser                      sample  381645   2.513 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.449           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.535           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.056           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.170           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.637           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.944           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.320           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.549           ms/op
ClientPb.getUser                        sample  376123   2.550 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.366           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.568           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.097           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.224           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.076           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.716           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.816           ms/op
ClientPb.getUser:getUser·p1.00          sample          25.657           ms/op
ClientPb.listUser                       sample  316107   3.035 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.737           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.974           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.928           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.424           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.644           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.322           ms/op
ClientPb.listUser:listUser·p0.9999      sample          16.727           ms/op
ClientPb.listUser:listUser·p1.00        sample          18.842           ms/op
