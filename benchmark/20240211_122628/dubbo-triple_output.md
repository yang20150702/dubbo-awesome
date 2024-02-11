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
# Warmup Iteration   1: 4.891 ops/ms
# Warmup Iteration   2: 12.005 ops/ms
# Warmup Iteration   3: 12.257 ops/ms
Iteration   1: 12.537 ops/ms
Iteration   2: 12.607 ops/ms
Iteration   3: 12.584 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.576 ±(99.9%) 0.656 ops/ms [Average]
  (min, avg, max) = (12.537, 12.576, 12.607), stdev = 0.036
  CI (99.9%): [11.920, 13.232] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:53
# Fork: 1 of 1
# Warmup Iteration   1: 8.163 ops/ms
# Warmup Iteration   2: 13.020 ops/ms
# Warmup Iteration   3: 12.994 ops/ms
Iteration   1: 13.066 ops/ms
Iteration   2: 12.953 ops/ms
Iteration   3: 12.868 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.962 ±(99.9%) 1.814 ops/ms [Average]
  (min, avg, max) = (12.868, 12.962, 13.066), stdev = 0.099
  CI (99.9%): [11.148, 14.776] (assumes normal distribution)


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
# Warmup Iteration   1: 7.678 ops/ms
# Warmup Iteration   2: 12.635 ops/ms
# Warmup Iteration   3: 12.969 ops/ms
Iteration   1: 13.018 ops/ms
Iteration   2: 12.907 ops/ms
Iteration   3: 13.012 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.979 ±(99.9%) 1.140 ops/ms [Average]
  (min, avg, max) = (12.907, 12.979, 13.018), stdev = 0.062
  CI (99.9%): [11.839, 14.119] (assumes normal distribution)


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
# Warmup Iteration   1: 6.750 ops/ms
# Warmup Iteration   2: 10.508 ops/ms
# Warmup Iteration   3: 10.637 ops/ms
Iteration   1: 10.624 ops/ms
Iteration   2: 10.633 ops/ms
Iteration   3: 10.617 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.625 ±(99.9%) 0.146 ops/ms [Average]
  (min, avg, max) = (10.617, 10.625, 10.633), stdev = 0.008
  CI (99.9%): [10.479, 10.770] (assumes normal distribution)


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
# Warmup Iteration   1: 4.100 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.602 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.543 ±(99.9%) 0.004 ms/op
Iteration   1: 2.580 ±(99.9%) 0.004 ms/op
Iteration   2: 2.567 ±(99.9%) 0.004 ms/op
Iteration   3: 2.539 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.562 ±(99.9%) 0.381 ms/op [Average]
  (min, avg, max) = (2.539, 2.562, 2.580), stdev = 0.021
  CI (99.9%): [2.181, 2.943] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:33
# Fork: 1 of 1
# Warmup Iteration   1: 3.718 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.455 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.440 ±(99.9%) 0.004 ms/op
Iteration   1: 2.450 ±(99.9%) 0.004 ms/op
Iteration   2: 2.439 ±(99.9%) 0.004 ms/op
Iteration   3: 2.446 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.445 ±(99.9%) 0.103 ms/op [Average]
  (min, avg, max) = (2.439, 2.445, 2.450), stdev = 0.006
  CI (99.9%): [2.342, 2.548] (assumes normal distribution)


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
# Warmup Iteration   1: 3.810 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.494 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.490 ±(99.9%) 0.003 ms/op
Iteration   1: 2.501 ±(99.9%) 0.004 ms/op
Iteration   2: 2.452 ±(99.9%) 0.004 ms/op
Iteration   3: 2.477 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.477 ±(99.9%) 0.452 ms/op [Average]
  (min, avg, max) = (2.452, 2.477, 2.501), stdev = 0.025
  CI (99.9%): [2.025, 2.928] (assumes normal distribution)


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
# Warmup Iteration   1: 4.592 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.031 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.021 ±(99.9%) 0.006 ms/op
Iteration   1: 3.002 ±(99.9%) 0.005 ms/op
Iteration   2: 2.985 ±(99.9%) 0.005 ms/op
Iteration   3: 2.994 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.994 ±(99.9%) 0.158 ms/op [Average]
  (min, avg, max) = (2.985, 2.994, 3.002), stdev = 0.009
  CI (99.9%): [2.836, 3.152] (assumes normal distribution)


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
# Warmup Iteration   1: 4.295 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 2.627 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.531 ±(99.9%) 0.005 ms/op
Iteration   1: 2.553 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.959 ms/op
                 createUser·p0.50:   2.609 ms/op
                 createUser·p0.90:   3.109 ms/op
                 createUser·p0.95:   3.232 ms/op
                 createUser·p0.99:   3.846 ms/op
                 createUser·p0.999:  11.797 ms/op
                 createUser·p0.9999: 13.557 ms/op
                 createUser·p1.00:   13.861 ms/op

Iteration   2: 2.514 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.936 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.056 ms/op
                 createUser·p0.95:   3.170 ms/op
                 createUser·p0.99:   3.693 ms/op
                 createUser·p0.999:  9.614 ms/op
                 createUser·p0.9999: 12.817 ms/op
                 createUser·p1.00:   13.959 ms/op

Iteration   3: 2.524 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.721 ms/op
                 createUser·p0.50:   2.621 ms/op
                 createUser·p0.90:   3.056 ms/op
                 createUser·p0.95:   3.166 ms/op
                 createUser·p0.99:   3.863 ms/op
                 createUser·p0.999:  8.765 ms/op
                 createUser·p0.9999: 11.753 ms/op
                 createUser·p1.00:   12.993 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 379090
  mean =      2.531 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 58 
    [ 1.250,  2.500) = 182493 
    [ 2.500,  3.750) = 192445 
    [ 3.750,  5.000) = 3303 
    [ 5.000,  6.250) = 345 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 87 
    [10.000, 11.250) = 55 
    [11.250, 12.500) = 132 
    [12.500, 13.750) = 106 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.721 ms/op
     p(50.0000) =      2.605 ms/op
     p(90.0000) =      3.076 ms/op
     p(95.0000) =      3.191 ms/op
     p(99.0000) =      3.797 ms/op
     p(99.9000) =      8.928 ms/op
     p(99.9900) =     13.143 ms/op
     p(99.9990) =     13.662 ms/op
     p(99.9999) =     13.959 ms/op
    p(100.0000) =     13.959 ms/op


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
# Warmup Iteration   1: 3.659 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.478 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.460 ±(99.9%) 0.005 ms/op
Iteration   1: 2.422 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.852 ms/op
                 existUser·p0.50:   2.482 ms/op
                 existUser·p0.90:   2.941 ms/op
                 existUser·p0.95:   3.047 ms/op
                 existUser·p0.99:   3.543 ms/op
                 existUser·p0.999:  6.584 ms/op
                 existUser·p0.9999: 13.527 ms/op
                 existUser·p1.00:   13.894 ms/op

Iteration   2: 2.433 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.988 ms/op
                 existUser·p0.50:   2.552 ms/op
                 existUser·p0.90:   2.949 ms/op
                 existUser·p0.95:   3.043 ms/op
                 existUser·p0.99:   3.502 ms/op
                 existUser·p0.999:  6.086 ms/op
                 existUser·p0.9999: 13.435 ms/op
                 existUser·p1.00:   13.959 ms/op

Iteration   3: 2.466 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.738 ms/op
                 existUser·p0.50:   2.523 ms/op
                 existUser·p0.90:   3.011 ms/op
                 existUser·p0.95:   3.142 ms/op
                 existUser·p0.99:   3.778 ms/op
                 existUser·p0.999:  5.904 ms/op
                 existUser·p0.9999: 11.764 ms/op
                 existUser·p1.00:   12.616 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 393055
  mean =      2.440 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 49 
    [ 1.250,  2.500) = 194886 
    [ 2.500,  3.750) = 195000 
    [ 3.750,  5.000) = 2400 
    [ 5.000,  6.250) = 342 
    [ 6.250,  7.500) = 23 
    [ 7.500,  8.750) = 21 
    [ 8.750, 10.000) = 62 
    [10.000, 11.250) = 49 
    [11.250, 12.500) = 100 
    [12.500, 13.750) = 115 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.738 ms/op
     p(50.0000) =      2.515 ms/op
     p(90.0000) =      2.966 ms/op
     p(95.0000) =      3.080 ms/op
     p(99.0000) =      3.613 ms/op
     p(99.9000) =      6.062 ms/op
     p(99.9900) =     13.381 ms/op
     p(99.9990) =     13.911 ms/op
     p(99.9999) =     13.959 ms/op
    p(100.0000) =     13.959 ms/op


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
# Warmup Iteration   1: 4.142 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.616 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.528 ±(99.9%) 0.006 ms/op
Iteration   1: 2.536 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.818 ms/op
                 getUser·p0.50:   2.568 ms/op
                 getUser·p0.90:   3.088 ms/op
                 getUser·p0.95:   3.219 ms/op
                 getUser·p0.99:   4.002 ms/op
                 getUser·p0.999:  11.009 ms/op
                 getUser·p0.9999: 13.513 ms/op
                 getUser·p1.00:   14.270 ms/op

Iteration   2: 2.509 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.918 ms/op
                 getUser·p0.50:   2.527 ms/op
                 getUser·p0.90:   3.060 ms/op
                 getUser·p0.95:   3.162 ms/op
                 getUser·p0.99:   3.641 ms/op
                 getUser·p0.999:  9.233 ms/op
                 getUser·p0.9999: 12.452 ms/op
                 getUser·p1.00:   12.714 ms/op

Iteration   3: 2.511 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.997 ms/op
                 getUser·p0.50:   2.564 ms/op
                 getUser·p0.90:   3.031 ms/op
                 getUser·p0.95:   3.133 ms/op
                 getUser·p0.99:   4.032 ms/op
                 getUser·p0.999:  8.625 ms/op
                 getUser·p0.9999: 10.588 ms/op
                 getUser·p1.00:   10.945 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 380865
  mean =      2.519 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 42 
    [ 1.250,  2.500) = 187284 
    [ 2.500,  3.750) = 189001 
    [ 3.750,  5.000) = 3258 
    [ 5.000,  6.250) = 798 
    [ 6.250,  7.500) = 84 
    [ 7.500,  8.750) = 21 
    [ 8.750, 10.000) = 134 
    [10.000, 11.250) = 93 
    [11.250, 12.500) = 97 
    [12.500, 13.750) = 45 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.818 ms/op
     p(50.0000) =      2.552 ms/op
     p(90.0000) =      3.060 ms/op
     p(95.0000) =      3.174 ms/op
     p(99.0000) =      3.875 ms/op
     p(99.9000) =      8.733 ms/op
     p(99.9900) =     12.976 ms/op
     p(99.9990) =     13.863 ms/op
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
# Warmup Iteration   1: 4.666 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.060 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.056 ±(99.9%) 0.008 ms/op
Iteration   1: 3.016 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.825 ms/op
                 listUser·p0.50:   2.953 ms/op
                 listUser·p0.90:   3.887 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   5.636 ms/op
                 listUser·p0.999:  8.995 ms/op
                 listUser·p0.9999: 10.486 ms/op
                 listUser·p1.00:   11.272 ms/op

Iteration   2: 3.025 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.945 ms/op
                 listUser·p0.50:   2.966 ms/op
                 listUser·p0.90:   3.916 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   5.538 ms/op
                 listUser·p0.999:  9.807 ms/op
                 listUser·p0.9999: 11.382 ms/op
                 listUser·p1.00:   11.846 ms/op

Iteration   3: 3.008 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.692 ms/op
                 listUser·p0.50:   2.957 ms/op
                 listUser·p0.90:   3.875 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.472 ms/op
                 listUser·p0.999:  8.575 ms/op
                 listUser·p0.9999: 10.066 ms/op
                 listUser·p1.00:   10.289 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 318057
  mean =      3.016 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 105 
    [ 1.250,  2.500) = 91371 
    [ 2.500,  3.750) = 187418 
    [ 3.750,  5.000) = 31895 
    [ 5.000,  6.250) = 6156 
    [ 6.250,  7.500) = 500 
    [ 7.500,  8.750) = 203 
    [ 8.750, 10.000) = 291 
    [10.000, 11.250) = 106 
    [11.250, 12.500) = 12 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.692 ms/op
     p(50.0000) =      2.957 ms/op
     p(90.0000) =      3.891 ms/op
     p(95.0000) =      4.399 ms/op
     p(99.0000) =      5.546 ms/op
     p(99.9000) =      9.093 ms/op
     p(99.9900) =     10.757 ms/op
     p(99.9990) =     11.630 ms/op
     p(99.9999) =     11.846 ms/op
    p(100.0000) =     11.846 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.576 ± 0.656  ops/ms
ClientPb.existUser                       thrpt       3  12.962 ± 1.814  ops/ms
ClientPb.getUser                         thrpt       3  12.979 ± 1.140  ops/ms
ClientPb.listUser                        thrpt       3  10.625 ± 0.146  ops/ms
ClientPb.createUser                       avgt       3   2.562 ± 0.381   ms/op
ClientPb.existUser                        avgt       3   2.445 ± 0.103   ms/op
ClientPb.getUser                          avgt       3   2.477 ± 0.452   ms/op
ClientPb.listUser                         avgt       3   2.994 ± 0.158   ms/op
ClientPb.createUser                     sample  379090   2.531 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.721           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.605           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.076           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.191           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.797           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.928           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.143           ms/op
ClientPb.createUser:createUser·p1.00    sample          13.959           ms/op
ClientPb.existUser                      sample  393055   2.440 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.738           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.515           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.966           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.080           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.613           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.062           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.381           ms/op
ClientPb.existUser:existUser·p1.00      sample          13.959           ms/op
ClientPb.getUser                        sample  380865   2.519 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.818           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.552           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.060           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.174           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.875           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.733           ms/op
ClientPb.getUser:getUser·p0.9999        sample          12.976           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.270           ms/op
ClientPb.listUser                       sample  318057   3.016 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.692           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.957           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.891           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.399           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.546           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.093           ms/op
ClientPb.listUser:listUser·p0.9999      sample          10.757           ms/op
ClientPb.listUser:listUser·p1.00        sample          11.846           ms/op
