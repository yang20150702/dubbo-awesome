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
# Warmup Iteration   1: 4.581 ops/ms
# Warmup Iteration   2: 11.950 ops/ms
# Warmup Iteration   3: 12.287 ops/ms
Iteration   1: 12.479 ops/ms
Iteration   2: 12.487 ops/ms
Iteration   3: 12.542 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.503 ±(99.9%) 0.625 ops/ms [Average]
  (min, avg, max) = (12.479, 12.503, 12.542), stdev = 0.034
  CI (99.9%): [11.877, 13.128] (assumes normal distribution)


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
# Warmup Iteration   1: 8.305 ops/ms
# Warmup Iteration   2: 13.206 ops/ms
# Warmup Iteration   3: 13.157 ops/ms
Iteration   1: 13.106 ops/ms
Iteration   2: 13.210 ops/ms
Iteration   3: 13.123 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.146 ±(99.9%) 1.020 ops/ms [Average]
  (min, avg, max) = (13.106, 13.146, 13.210), stdev = 0.056
  CI (99.9%): [12.126, 14.167] (assumes normal distribution)


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
# Warmup Iteration   1: 7.442 ops/ms
# Warmup Iteration   2: 12.346 ops/ms
# Warmup Iteration   3: 12.799 ops/ms
Iteration   1: 12.703 ops/ms
Iteration   2: 12.790 ops/ms
Iteration   3: 12.789 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.761 ±(99.9%) 0.914 ops/ms [Average]
  (min, avg, max) = (12.703, 12.761, 12.790), stdev = 0.050
  CI (99.9%): [11.847, 13.674] (assumes normal distribution)


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
# Warmup Iteration   1: 6.775 ops/ms
# Warmup Iteration   2: 10.503 ops/ms
# Warmup Iteration   3: 10.637 ops/ms
Iteration   1: 10.694 ops/ms
Iteration   2: 10.686 ops/ms
Iteration   3: 10.745 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.709 ±(99.9%) 0.588 ops/ms [Average]
  (min, avg, max) = (10.686, 10.709, 10.745), stdev = 0.032
  CI (99.9%): [10.121, 11.297] (assumes normal distribution)


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
# Warmup Iteration   1: 3.895 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.553 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.514 ±(99.9%) 0.003 ms/op
Iteration   1: 2.510 ±(99.9%) 0.003 ms/op
Iteration   2: 2.525 ±(99.9%) 0.004 ms/op
Iteration   3: 2.499 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.511 ±(99.9%) 0.239 ms/op [Average]
  (min, avg, max) = (2.499, 2.511, 2.525), stdev = 0.013
  CI (99.9%): [2.273, 2.750] (assumes normal distribution)


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
# Warmup Iteration   1: 3.664 ±(99.9%) 0.008 ms/op
# Warmup Iteration   2: 2.461 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.447 ±(99.9%) 0.003 ms/op
Iteration   1: 2.468 ±(99.9%) 0.003 ms/op
Iteration   2: 2.462 ±(99.9%) 0.003 ms/op
Iteration   3: 2.451 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.460 ±(99.9%) 0.159 ms/op [Average]
  (min, avg, max) = (2.451, 2.460, 2.468), stdev = 0.009
  CI (99.9%): [2.301, 2.619] (assumes normal distribution)


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
# Warmup Iteration   1: 3.891 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.553 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.490 ±(99.9%) 0.004 ms/op
Iteration   1: 2.460 ±(99.9%) 0.004 ms/op
Iteration   2: 2.480 ±(99.9%) 0.004 ms/op
Iteration   3: 2.510 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.483 ±(99.9%) 0.459 ms/op [Average]
  (min, avg, max) = (2.460, 2.483, 2.510), stdev = 0.025
  CI (99.9%): [2.024, 2.942] (assumes normal distribution)


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
# Warmup Iteration   1: 4.711 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.053 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.993 ±(99.9%) 0.005 ms/op
Iteration   1: 2.982 ±(99.9%) 0.005 ms/op
Iteration   2: 2.985 ±(99.9%) 0.005 ms/op
Iteration   3: 2.971 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.979 ±(99.9%) 0.128 ms/op [Average]
  (min, avg, max) = (2.971, 2.979, 2.985), stdev = 0.007
  CI (99.9%): [2.851, 3.108] (assumes normal distribution)


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
# Warmup Iteration   1: 4.313 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 2.662 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.535 ±(99.9%) 0.006 ms/op
Iteration   1: 2.507 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.726 ms/op
                 createUser·p0.50:   2.585 ms/op
                 createUser·p0.90:   3.031 ms/op
                 createUser·p0.95:   3.138 ms/op
                 createUser·p0.99:   3.711 ms/op
                 createUser·p0.999:  11.607 ms/op
                 createUser·p0.9999: 13.652 ms/op
                 createUser·p1.00:   14.238 ms/op

Iteration   2: 2.527 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.048 ms/op
                 createUser·p0.50:   2.609 ms/op
                 createUser·p0.90:   3.068 ms/op
                 createUser·p0.95:   3.178 ms/op
                 createUser·p0.99:   3.662 ms/op
                 createUser·p0.999:  9.543 ms/op
                 createUser·p0.9999: 11.960 ms/op
                 createUser·p1.00:   12.190 ms/op

Iteration   3: 2.544 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.811 ms/op
                 createUser·p0.50:   2.597 ms/op
                 createUser·p0.90:   3.097 ms/op
                 createUser·p0.95:   3.228 ms/op
                 createUser·p0.99:   3.846 ms/op
                 createUser·p0.999:  8.634 ms/op
                 createUser·p0.9999: 10.453 ms/op
                 createUser·p1.00:   11.305 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 379659
  mean =      2.526 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 50 
    [ 1.250,  2.500) = 182470 
    [ 2.500,  3.750) = 193374 
    [ 3.750,  5.000) = 2892 
    [ 5.000,  6.250) = 336 
    [ 6.250,  7.500) = 64 
    [ 7.500,  8.750) = 81 
    [ 8.750, 10.000) = 114 
    [10.000, 11.250) = 114 
    [11.250, 12.500) = 96 
    [12.500, 13.750) = 60 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.726 ms/op
     p(50.0000) =      2.597 ms/op
     p(90.0000) =      3.064 ms/op
     p(95.0000) =      3.178 ms/op
     p(99.0000) =      3.744 ms/op
     p(99.9000) =      8.995 ms/op
     p(99.9900) =     12.829 ms/op
     p(99.9990) =     14.077 ms/op
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
# Warmup Iteration   1: 3.666 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.486 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.479 ±(99.9%) 0.005 ms/op
Iteration   1: 2.475 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.807 ms/op
                 existUser·p0.50:   2.515 ms/op
                 existUser·p0.90:   3.011 ms/op
                 existUser·p0.95:   3.121 ms/op
                 existUser·p0.99:   3.604 ms/op
                 existUser·p0.999:  7.782 ms/op
                 existUser·p0.9999: 13.457 ms/op
                 existUser·p1.00:   14.221 ms/op

Iteration   2: 2.450 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.112 ms/op
                 existUser·p0.50:   2.527 ms/op
                 existUser·p0.90:   2.970 ms/op
                 existUser·p0.95:   3.060 ms/op
                 existUser·p0.99:   3.469 ms/op
                 existUser·p0.999:  8.401 ms/op
                 existUser·p0.9999: 12.254 ms/op
                 existUser·p1.00:   13.058 ms/op

Iteration   3: 2.451 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.055 ms/op
                 existUser·p0.50:   2.470 ms/op
                 existUser·p0.90:   2.994 ms/op
                 existUser·p0.95:   3.101 ms/op
                 existUser·p0.99:   3.617 ms/op
                 existUser·p0.999:  5.397 ms/op
                 existUser·p0.9999: 12.059 ms/op
                 existUser·p1.00:   13.025 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 390017
  mean =      2.459 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 38 
    [ 1.250,  2.500) = 194741 
    [ 2.500,  3.750) = 192346 
    [ 3.750,  5.000) = 2129 
    [ 5.000,  6.250) = 384 
    [ 6.250,  7.500) = 20 
    [ 7.500,  8.750) = 6 
    [ 8.750, 10.000) = 77 
    [10.000, 11.250) = 76 
    [11.250, 12.500) = 96 
    [12.500, 13.750) = 97 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.807 ms/op
     p(50.0000) =      2.503 ms/op
     p(90.0000) =      2.990 ms/op
     p(95.0000) =      3.097 ms/op
     p(99.0000) =      3.572 ms/op
     p(99.9000) =      6.119 ms/op
     p(99.9900) =     13.140 ms/op
     p(99.9990) =     14.139 ms/op
     p(99.9999) =     14.221 ms/op
    p(100.0000) =     14.221 ms/op


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
# Warmup Iteration   1: 3.960 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.576 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.533 ±(99.9%) 0.006 ms/op
Iteration   1: 2.532 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.037 ms/op
                 getUser·p0.50:   2.548 ms/op
                 getUser·p0.90:   3.092 ms/op
                 getUser·p0.95:   3.224 ms/op
                 getUser·p0.99:   3.899 ms/op
                 getUser·p0.999:  11.808 ms/op
                 getUser·p0.9999: 15.401 ms/op
                 getUser·p1.00:   16.237 ms/op

Iteration   2: 2.513 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.008 ms/op
                 getUser·p0.50:   2.519 ms/op
                 getUser·p0.90:   3.060 ms/op
                 getUser·p0.95:   3.178 ms/op
                 getUser·p0.99:   3.838 ms/op
                 getUser·p0.999:  8.926 ms/op
                 getUser·p0.9999: 14.244 ms/op
                 getUser·p1.00:   14.877 ms/op

Iteration   3: 2.527 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.059 ms/op
                 getUser·p0.50:   2.564 ms/op
                 getUser·p0.90:   3.080 ms/op
                 getUser·p0.95:   3.207 ms/op
                 getUser·p0.99:   3.932 ms/op
                 getUser·p0.999:  9.084 ms/op
                 getUser·p0.9999: 11.108 ms/op
                 getUser·p1.00:   11.993 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 380009
  mean =      2.524 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 46 
    [ 1.250,  2.500) = 186779 
    [ 2.500,  3.750) = 188393 
    [ 3.750,  5.000) = 3891 
    [ 5.000,  6.250) = 509 
    [ 6.250,  7.500) = 7 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 70 
    [10.000, 11.250) = 116 
    [11.250, 12.500) = 59 
    [12.500, 13.750) = 84 
    [13.750, 15.000) = 38 
    [15.000, 16.250) = 17 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.008 ms/op
     p(50.0000) =      2.544 ms/op
     p(90.0000) =      3.076 ms/op
     p(95.0000) =      3.203 ms/op
     p(99.0000) =      3.891 ms/op
     p(99.9000) =      9.076 ms/op
     p(99.9900) =     14.533 ms/op
     p(99.9990) =     15.850 ms/op
     p(99.9999) =     16.237 ms/op
    p(100.0000) =     16.237 ms/op


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
# Warmup Iteration   1: 4.554 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.042 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.001 ±(99.9%) 0.008 ms/op
Iteration   1: 3.001 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.016 ms/op
                 listUser·p0.50:   2.937 ms/op
                 listUser·p0.90:   3.887 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.521 ms/op
                 listUser·p0.999:  9.830 ms/op
                 listUser·p0.9999: 14.604 ms/op
                 listUser·p1.00:   15.073 ms/op

Iteration   2: 2.972 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.872 ms/op
                 listUser·p0.50:   2.912 ms/op
                 listUser·p0.90:   3.805 ms/op
                 listUser·p0.95:   4.276 ms/op
                 listUser·p0.99:   5.407 ms/op
                 listUser·p0.999:  9.476 ms/op
                 listUser·p0.9999: 12.108 ms/op
                 listUser·p1.00:   12.747 ms/op

Iteration   3: 3.009 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.862 ms/op
                 listUser·p0.50:   2.945 ms/op
                 listUser·p0.90:   3.902 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   5.521 ms/op
                 listUser·p0.999:  9.133 ms/op
                 listUser·p0.9999: 12.949 ms/op
                 listUser·p1.00:   13.615 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 320439
  mean =      2.994 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 170 
    [ 1.250,  2.500) = 95331 
    [ 2.500,  3.750) = 186644 
    [ 3.750,  5.000) = 31586 
    [ 5.000,  6.250) = 5576 
    [ 6.250,  7.500) = 496 
    [ 7.500,  8.750) = 164 
    [ 8.750, 10.000) = 254 
    [10.000, 11.250) = 132 
    [11.250, 12.500) = 34 
    [12.500, 13.750) = 30 
    [13.750, 15.000) = 20 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.862 ms/op
     p(50.0000) =      2.933 ms/op
     p(90.0000) =      3.867 ms/op
     p(95.0000) =      4.350 ms/op
     p(99.0000) =      5.497 ms/op
     p(99.9000) =      9.503 ms/op
     p(99.9900) =     13.521 ms/op
     p(99.9990) =     14.972 ms/op
     p(99.9999) =     15.073 ms/op
    p(100.0000) =     15.073 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.503 ± 0.625  ops/ms
ClientPb.existUser                       thrpt       3  13.146 ± 1.020  ops/ms
ClientPb.getUser                         thrpt       3  12.761 ± 0.914  ops/ms
ClientPb.listUser                        thrpt       3  10.709 ± 0.588  ops/ms
ClientPb.createUser                       avgt       3   2.511 ± 0.239   ms/op
ClientPb.existUser                        avgt       3   2.460 ± 0.159   ms/op
ClientPb.getUser                          avgt       3   2.483 ± 0.459   ms/op
ClientPb.listUser                         avgt       3   2.979 ± 0.128   ms/op
ClientPb.createUser                     sample  379659   2.526 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.726           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.597           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.064           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.178           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.744           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.995           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.829           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.238           ms/op
ClientPb.existUser                      sample  390017   2.459 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.807           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.503           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.990           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.097           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.572           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.119           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.140           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.221           ms/op
ClientPb.getUser                        sample  380009   2.524 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.008           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.544           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.076           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.203           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.891           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.076           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.533           ms/op
ClientPb.getUser:getUser·p1.00          sample          16.237           ms/op
ClientPb.listUser                       sample  320439   2.994 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.862           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.933           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.867           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.350           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.497           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.503           ms/op
ClientPb.listUser:listUser·p0.9999      sample          13.521           ms/op
ClientPb.listUser:listUser·p1.00        sample          15.073           ms/op
