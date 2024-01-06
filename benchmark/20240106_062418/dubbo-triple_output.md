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
# Warmup Iteration   1: 5.157 ops/ms
# Warmup Iteration   2: 12.082 ops/ms
# Warmup Iteration   3: 12.409 ops/ms
Iteration   1: 12.634 ops/ms
Iteration   2: 12.797 ops/ms
Iteration   3: 12.751 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.727 ±(99.9%) 1.531 ops/ms [Average]
  (min, avg, max) = (12.634, 12.727, 12.797), stdev = 0.084
  CI (99.9%): [11.196, 14.258] (assumes normal distribution)


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
# Warmup Iteration   1: 8.260 ops/ms
# Warmup Iteration   2: 12.914 ops/ms
# Warmup Iteration   3: 12.919 ops/ms
Iteration   1: 12.976 ops/ms
Iteration   2: 13.009 ops/ms
Iteration   3: 12.884 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.956 ±(99.9%) 1.187 ops/ms [Average]
  (min, avg, max) = (12.884, 12.956, 13.009), stdev = 0.065
  CI (99.9%): [11.770, 14.143] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.696 ops/ms
# Warmup Iteration   2: 12.319 ops/ms
# Warmup Iteration   3: 12.803 ops/ms
Iteration   1: 12.885 ops/ms
Iteration   2: 12.834 ops/ms
Iteration   3: 12.710 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.810 ±(99.9%) 1.648 ops/ms [Average]
  (min, avg, max) = (12.710, 12.810, 12.885), stdev = 0.090
  CI (99.9%): [11.161, 14.458] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:44
# Fork: 1 of 1
# Warmup Iteration   1: 6.712 ops/ms
# Warmup Iteration   2: 10.588 ops/ms
# Warmup Iteration   3: 10.622 ops/ms
Iteration   1: 10.636 ops/ms
Iteration   2: 10.656 ops/ms
Iteration   3: 10.614 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.635 ±(99.9%) 0.384 ops/ms [Average]
  (min, avg, max) = (10.614, 10.635, 10.656), stdev = 0.021
  CI (99.9%): [10.251, 11.020] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.975 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.654 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.567 ±(99.9%) 0.005 ms/op
Iteration   1: 2.595 ±(99.9%) 0.004 ms/op
Iteration   2: 2.566 ±(99.9%) 0.004 ms/op
Iteration   3: 2.585 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.582 ±(99.9%) 0.262 ms/op [Average]
  (min, avg, max) = (2.566, 2.582, 2.595), stdev = 0.014
  CI (99.9%): [2.320, 2.844] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.585 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.495 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.473 ±(99.9%) 0.004 ms/op
Iteration   1: 2.464 ±(99.9%) 0.004 ms/op
Iteration   2: 2.486 ±(99.9%) 0.004 ms/op
Iteration   3: 2.454 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.468 ±(99.9%) 0.293 ms/op [Average]
  (min, avg, max) = (2.454, 2.468, 2.486), stdev = 0.016
  CI (99.9%): [2.175, 2.761] (assumes normal distribution)


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
# Warmup Iteration   1: 3.989 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.551 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.506 ±(99.9%) 0.004 ms/op
Iteration   1: 2.507 ±(99.9%) 0.004 ms/op
Iteration   2: 2.511 ±(99.9%) 0.004 ms/op
Iteration   3: 2.510 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.509 ±(99.9%) 0.037 ms/op [Average]
  (min, avg, max) = (2.507, 2.509, 2.511), stdev = 0.002
  CI (99.9%): [2.472, 2.546] (assumes normal distribution)


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
# Warmup Iteration   1: 4.738 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.069 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.038 ±(99.9%) 0.005 ms/op
Iteration   1: 2.988 ±(99.9%) 0.005 ms/op
Iteration   2: 2.998 ±(99.9%) 0.005 ms/op
Iteration   3: 2.976 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.987 ±(99.9%) 0.194 ms/op [Average]
  (min, avg, max) = (2.976, 2.987, 2.998), stdev = 0.011
  CI (99.9%): [2.793, 3.181] (assumes normal distribution)


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
# Warmup Iteration   1: 4.161 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.642 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.526 ±(99.9%) 0.005 ms/op
Iteration   1: 2.516 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.888 ms/op
                 createUser·p0.50:   2.617 ms/op
                 createUser·p0.90:   3.043 ms/op
                 createUser·p0.95:   3.154 ms/op
                 createUser·p0.99:   3.787 ms/op
                 createUser·p0.999:  11.829 ms/op
                 createUser·p0.9999: 13.599 ms/op
                 createUser·p1.00:   14.254 ms/op

Iteration   2: 2.517 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.921 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.064 ms/op
                 createUser·p0.95:   3.178 ms/op
                 createUser·p0.99:   3.640 ms/op
                 createUser·p0.999:  10.453 ms/op
                 createUser·p0.9999: 15.815 ms/op
                 createUser·p1.00:   16.318 ms/op

Iteration   3: 2.528 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.729 ms/op
                 createUser·p0.50:   2.597 ms/op
                 createUser·p0.90:   3.076 ms/op
                 createUser·p0.95:   3.207 ms/op
                 createUser·p0.99:   3.908 ms/op
                 createUser·p0.999:  9.069 ms/op
                 createUser·p0.9999: 11.163 ms/op
                 createUser·p1.00:   12.304 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 380527
  mean =      2.520 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 24 
    [ 1.250,  2.500) = 183168 
    [ 2.500,  3.750) = 193343 
    [ 3.750,  5.000) = 3196 
    [ 5.000,  6.250) = 326 
    [ 6.250,  7.500) = 38 
    [ 7.500,  8.750) = 23 
    [ 8.750, 10.000) = 94 
    [10.000, 11.250) = 77 
    [11.250, 12.500) = 106 
    [12.500, 13.750) = 94 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 24 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.729 ms/op
     p(50.0000) =      2.597 ms/op
     p(90.0000) =      3.060 ms/op
     p(95.0000) =      3.178 ms/op
     p(99.0000) =      3.777 ms/op
     p(99.9000) =      9.077 ms/op
     p(99.9900) =     14.084 ms/op
     p(99.9990) =     16.043 ms/op
     p(99.9999) =     16.318 ms/op
    p(100.0000) =     16.318 ms/op


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
# Warmup Iteration   1: 3.796 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.525 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.481 ±(99.9%) 0.006 ms/op
Iteration   1: 2.459 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.856 ms/op
                 existUser·p0.50:   2.478 ms/op
                 existUser·p0.90:   2.990 ms/op
                 existUser·p0.95:   3.092 ms/op
                 existUser·p0.99:   3.527 ms/op
                 existUser·p0.999:  5.941 ms/op
                 existUser·p0.9999: 14.172 ms/op
                 existUser·p1.00:   14.516 ms/op

Iteration   2: 2.445 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.996 ms/op
                 existUser·p0.50:   2.507 ms/op
                 existUser·p0.90:   2.970 ms/op
                 existUser·p0.95:   3.060 ms/op
                 existUser·p0.99:   3.453 ms/op
                 existUser·p0.999:  5.620 ms/op
                 existUser·p0.9999: 13.678 ms/op
                 existUser·p1.00:   13.812 ms/op

Iteration   3: 2.463 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.915 ms/op
                 existUser·p0.50:   2.490 ms/op
                 existUser·p0.90:   2.994 ms/op
                 existUser·p0.95:   3.101 ms/op
                 existUser·p0.99:   3.744 ms/op
                 existUser·p0.999:  8.336 ms/op
                 existUser·p0.9999: 13.206 ms/op
                 existUser·p1.00:   14.189 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 390459
  mean =      2.456 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 65 
    [ 1.250,  2.500) = 195988 
    [ 2.500,  3.750) = 191460 
    [ 3.750,  5.000) = 2183 
    [ 5.000,  6.250) = 359 
    [ 6.250,  7.500) = 15 
    [ 7.500,  8.750) = 45 
    [ 8.750, 10.000) = 39 
    [10.000, 11.250) = 81 
    [11.250, 12.500) = 74 
    [12.500, 13.750) = 116 
    [13.750, 15.000) = 34 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.856 ms/op
     p(50.0000) =      2.490 ms/op
     p(90.0000) =      2.986 ms/op
     p(95.0000) =      3.084 ms/op
     p(99.0000) =      3.576 ms/op
     p(99.9000) =      7.307 ms/op
     p(99.9900) =     13.713 ms/op
     p(99.9990) =     14.403 ms/op
     p(99.9999) =     14.516 ms/op
    p(100.0000) =     14.516 ms/op


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
# Warmup Iteration   1: 3.834 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.580 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.509 ±(99.9%) 0.006 ms/op
Iteration   1: 2.503 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.787 ms/op
                 getUser·p0.50:   2.556 ms/op
                 getUser·p0.90:   3.047 ms/op
                 getUser·p0.95:   3.191 ms/op
                 getUser·p0.99:   3.826 ms/op
                 getUser·p0.999:  10.284 ms/op
                 getUser·p0.9999: 13.622 ms/op
                 getUser·p1.00:   14.041 ms/op

Iteration   2: 2.518 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.879 ms/op
                 getUser·p0.50:   2.544 ms/op
                 getUser·p0.90:   3.060 ms/op
                 getUser·p0.95:   3.224 ms/op
                 getUser·p0.99:   4.157 ms/op
                 getUser·p0.999:  9.847 ms/op
                 getUser·p0.9999: 12.986 ms/op
                 getUser·p1.00:   14.418 ms/op

Iteration   3: 2.500 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.955 ms/op
                 getUser·p0.50:   2.519 ms/op
                 getUser·p0.90:   3.060 ms/op
                 getUser·p0.95:   3.187 ms/op
                 getUser·p0.99:   3.715 ms/op
                 getUser·p0.999:  5.170 ms/op
                 getUser·p0.9999: 11.771 ms/op
                 getUser·p1.00:   12.780 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 382618
  mean =      2.507 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 62 
    [ 1.250,  2.500) = 187930 
    [ 2.500,  3.750) = 189622 
    [ 3.750,  5.000) = 4191 
    [ 5.000,  6.250) = 450 
    [ 6.250,  7.500) = 11 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 56 
    [10.000, 11.250) = 128 
    [11.250, 12.500) = 89 
    [12.500, 13.750) = 62 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.787 ms/op
     p(50.0000) =      2.540 ms/op
     p(90.0000) =      3.056 ms/op
     p(95.0000) =      3.199 ms/op
     p(99.0000) =      3.891 ms/op
     p(99.9000) =      5.988 ms/op
     p(99.9900) =     13.250 ms/op
     p(99.9990) =     14.369 ms/op
     p(99.9999) =     14.418 ms/op
    p(100.0000) =     14.418 ms/op


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
# Warmup Iteration   1: 4.766 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.100 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.047 ±(99.9%) 0.008 ms/op
Iteration   1: 3.053 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.966 ms/op
                 listUser·p0.50:   2.998 ms/op
                 listUser·p0.90:   3.949 ms/op
                 listUser·p0.95:   4.481 ms/op
                 listUser·p0.99:   5.677 ms/op
                 listUser·p0.999:  9.273 ms/op
                 listUser·p0.9999: 10.691 ms/op
                 listUser·p1.00:   11.813 ms/op

Iteration   2: 3.050 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.800 ms/op
                 listUser·p0.50:   2.990 ms/op
                 listUser·p0.90:   3.932 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   5.644 ms/op
                 listUser·p0.999:  9.784 ms/op
                 listUser·p0.9999: 11.608 ms/op
                 listUser·p1.00:   12.337 ms/op

Iteration   3: 3.035 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.110 ms/op
                 listUser·p0.50:   2.978 ms/op
                 listUser·p0.90:   3.879 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   5.480 ms/op
                 listUser·p0.999:  9.464 ms/op
                 listUser·p0.9999: 11.558 ms/op
                 listUser·p1.00:   12.091 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 314850
  mean =      3.046 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 99 
    [ 1.250,  2.500) = 85029 
    [ 2.500,  3.750) = 188516 
    [ 3.750,  5.000) = 33821 
    [ 5.000,  6.250) = 6018 
    [ 6.250,  7.500) = 752 
    [ 7.500,  8.750) = 183 
    [ 8.750, 10.000) = 213 
    [10.000, 11.250) = 176 
    [11.250, 12.500) = 43 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.800 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      3.920 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      5.603 ms/op
     p(99.9000) =      9.374 ms/op
     p(99.9900) =     11.477 ms/op
     p(99.9990) =     12.082 ms/op
     p(99.9999) =     12.337 ms/op
    p(100.0000) =     12.337 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.727 ± 1.531  ops/ms
ClientPb.existUser                       thrpt       3  12.956 ± 1.187  ops/ms
ClientPb.getUser                         thrpt       3  12.810 ± 1.648  ops/ms
ClientPb.listUser                        thrpt       3  10.635 ± 0.384  ops/ms
ClientPb.createUser                       avgt       3   2.582 ± 0.262   ms/op
ClientPb.existUser                        avgt       3   2.468 ± 0.293   ms/op
ClientPb.getUser                          avgt       3   2.509 ± 0.037   ms/op
ClientPb.listUser                         avgt       3   2.987 ± 0.194   ms/op
ClientPb.createUser                     sample  380527   2.520 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.729           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.597           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.060           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.178           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.777           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.077           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.084           ms/op
ClientPb.createUser:createUser·p1.00    sample          16.318           ms/op
ClientPb.existUser                      sample  390459   2.456 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.856           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.490           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.986           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.084           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.576           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.307           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.713           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.516           ms/op
ClientPb.getUser                        sample  382618   2.507 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.787           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.540           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.056           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.199           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.891           ms/op
ClientPb.getUser:getUser·p0.999         sample           5.988           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.250           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.418           ms/op
ClientPb.listUser                       sample  314850   3.046 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.800           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.986           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.920           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.407           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.603           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.374           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.477           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.337           ms/op
