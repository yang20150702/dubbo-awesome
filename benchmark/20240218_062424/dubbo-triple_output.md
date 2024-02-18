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
# Warmup Iteration   1: 5.458 ops/ms
# Warmup Iteration   2: 12.284 ops/ms
# Warmup Iteration   3: 12.545 ops/ms
Iteration   1: 12.669 ops/ms
Iteration   2: 12.806 ops/ms
Iteration   3: 12.869 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.781 ±(99.9%) 1.871 ops/ms [Average]
  (min, avg, max) = (12.669, 12.781, 12.869), stdev = 0.103
  CI (99.9%): [10.911, 14.652] (assumes normal distribution)


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
# Warmup Iteration   1: 8.304 ops/ms
# Warmup Iteration   2: 13.221 ops/ms
# Warmup Iteration   3: 13.229 ops/ms
Iteration   1: 13.341 ops/ms
Iteration   2: 13.363 ops/ms
Iteration   3: 13.292 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.332 ±(99.9%) 0.661 ops/ms [Average]
  (min, avg, max) = (13.292, 13.332, 13.363), stdev = 0.036
  CI (99.9%): [12.671, 13.993] (assumes normal distribution)


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
# Warmup Iteration   1: 8.063 ops/ms
# Warmup Iteration   2: 12.545 ops/ms
# Warmup Iteration   3: 12.802 ops/ms
Iteration   1: 12.771 ops/ms
Iteration   2: 12.866 ops/ms
Iteration   3: 12.589 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.742 ±(99.9%) 2.567 ops/ms [Average]
  (min, avg, max) = (12.589, 12.742, 12.866), stdev = 0.141
  CI (99.9%): [10.176, 15.309] (assumes normal distribution)


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
# Warmup Iteration   1: 6.707 ops/ms
# Warmup Iteration   2: 10.521 ops/ms
# Warmup Iteration   3: 10.541 ops/ms
Iteration   1: 10.603 ops/ms
Iteration   2: 10.616 ops/ms
Iteration   3: 10.691 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.637 ±(99.9%) 0.868 ops/ms [Average]
  (min, avg, max) = (10.603, 10.637, 10.691), stdev = 0.048
  CI (99.9%): [9.769, 11.505] (assumes normal distribution)


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
# Warmup Iteration   1: 4.060 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.600 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.460 ±(99.9%) 0.003 ms/op
Iteration   1: 2.526 ±(99.9%) 0.004 ms/op
Iteration   2: 2.494 ±(99.9%) 0.004 ms/op
Iteration   3: 2.519 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.513 ±(99.9%) 0.301 ms/op [Average]
  (min, avg, max) = (2.494, 2.513, 2.526), stdev = 0.016
  CI (99.9%): [2.212, 2.814] (assumes normal distribution)


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
# Warmup Iteration   1: 3.568 ±(99.9%) 0.008 ms/op
# Warmup Iteration   2: 2.465 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.456 ±(99.9%) 0.004 ms/op
Iteration   1: 2.429 ±(99.9%) 0.004 ms/op
Iteration   2: 2.479 ±(99.9%) 0.004 ms/op
Iteration   3: 2.494 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.467 ±(99.9%) 0.621 ms/op [Average]
  (min, avg, max) = (2.429, 2.467, 2.494), stdev = 0.034
  CI (99.9%): [1.846, 3.089] (assumes normal distribution)


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
# Warmup Iteration   1: 4.012 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.511 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.477 ±(99.9%) 0.004 ms/op
Iteration   1: 2.463 ±(99.9%) 0.005 ms/op
Iteration   2: 2.486 ±(99.9%) 0.004 ms/op
Iteration   3: 2.462 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.470 ±(99.9%) 0.251 ms/op [Average]
  (min, avg, max) = (2.462, 2.470, 2.486), stdev = 0.014
  CI (99.9%): [2.220, 2.721] (assumes normal distribution)


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
# Warmup Iteration   1: 4.694 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.034 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.026 ±(99.9%) 0.006 ms/op
Iteration   1: 3.007 ±(99.9%) 0.005 ms/op
Iteration   2: 3.031 ±(99.9%) 0.004 ms/op
Iteration   3: 3.019 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.019 ±(99.9%) 0.218 ms/op [Average]
  (min, avg, max) = (3.007, 3.019, 3.031), stdev = 0.012
  CI (99.9%): [2.801, 3.238] (assumes normal distribution)


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
# Warmup Iteration   1: 4.086 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.649 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 2.494 ±(99.9%) 0.005 ms/op
Iteration   1: 2.535 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.981 ms/op
                 createUser·p0.50:   2.564 ms/op
                 createUser·p0.90:   3.092 ms/op
                 createUser·p0.95:   3.240 ms/op
                 createUser·p0.99:   4.035 ms/op
                 createUser·p0.999:  11.927 ms/op
                 createUser·p0.9999: 14.320 ms/op
                 createUser·p1.00:   15.139 ms/op

Iteration   2: 2.541 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.006 ms/op
                 createUser·p0.50:   2.593 ms/op
                 createUser·p0.90:   3.092 ms/op
                 createUser·p0.95:   3.211 ms/op
                 createUser·p0.99:   3.740 ms/op
                 createUser·p0.999:  9.515 ms/op
                 createUser·p0.9999: 12.648 ms/op
                 createUser·p1.00:   13.566 ms/op

Iteration   3: 2.525 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.968 ms/op
                 createUser·p0.50:   2.572 ms/op
                 createUser·p0.90:   3.076 ms/op
                 createUser·p0.95:   3.207 ms/op
                 createUser·p0.99:   3.850 ms/op
                 createUser·p0.999:  8.805 ms/op
                 createUser·p0.9999: 10.705 ms/op
                 createUser·p1.00:   11.567 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 378560
  mean =      2.534 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 70 
    [ 1.250,  2.500) = 181889 
    [ 2.500,  3.750) = 191939 
    [ 3.750,  5.000) = 3834 
    [ 5.000,  6.250) = 362 
    [ 6.250,  7.500) = 37 
    [ 7.500,  8.750) = 40 
    [ 8.750, 10.000) = 93 
    [10.000, 11.250) = 101 
    [11.250, 12.500) = 70 
    [12.500, 13.750) = 99 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.968 ms/op
     p(50.0000) =      2.576 ms/op
     p(90.0000) =      3.088 ms/op
     p(95.0000) =      3.219 ms/op
     p(99.0000) =      3.871 ms/op
     p(99.9000) =      8.822 ms/op
     p(99.9900) =     13.522 ms/op
     p(99.9990) =     14.953 ms/op
     p(99.9999) =     15.139 ms/op
    p(100.0000) =     15.139 ms/op


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
# Warmup Iteration   1: 3.576 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.458 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.430 ±(99.9%) 0.005 ms/op
Iteration   1: 2.418 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.528 ms/op
                 existUser·p0.50:   2.507 ms/op
                 existUser·p0.90:   2.929 ms/op
                 existUser·p0.95:   3.023 ms/op
                 existUser·p0.99:   3.424 ms/op
                 existUser·p0.999:  8.033 ms/op
                 existUser·p0.9999: 13.641 ms/op
                 existUser·p1.00:   13.910 ms/op

Iteration   2: 2.432 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.980 ms/op
                 existUser·p0.50:   2.499 ms/op
                 existUser·p0.90:   2.953 ms/op
                 existUser·p0.95:   3.068 ms/op
                 existUser·p0.99:   3.805 ms/op
                 existUser·p0.999:  6.509 ms/op
                 existUser·p0.9999: 12.246 ms/op
                 existUser·p1.00:   13.255 ms/op

Iteration   3: 2.445 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.919 ms/op
                 existUser·p0.50:   2.482 ms/op
                 existUser·p0.90:   2.970 ms/op
                 existUser·p0.95:   3.080 ms/op
                 existUser·p0.99:   3.756 ms/op
                 existUser·p0.999:  8.394 ms/op
                 existUser·p0.9999: 11.795 ms/op
                 existUser·p1.00:   17.170 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 394323
  mean =      2.431 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 59 
    [ 1.250,  2.500) = 197565 
    [ 2.500,  3.750) = 193175 
    [ 3.750,  5.000) = 2669 
    [ 5.000,  6.250) = 407 
    [ 6.250,  7.500) = 24 
    [ 7.500,  8.750) = 86 
    [ 8.750, 10.000) = 93 
    [10.000, 11.250) = 81 
    [11.250, 12.500) = 84 
    [12.500, 13.750) = 70 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.528 ms/op
     p(50.0000) =      2.494 ms/op
     p(90.0000) =      2.949 ms/op
     p(95.0000) =      3.056 ms/op
     p(99.0000) =      3.670 ms/op
     p(99.9000) =      8.323 ms/op
     p(99.9900) =     13.100 ms/op
     p(99.9990) =     13.845 ms/op
     p(99.9999) =     17.170 ms/op
    p(100.0000) =     17.170 ms/op


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
# Warmup Iteration   1: 3.803 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.582 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.490 ±(99.9%) 0.005 ms/op
Iteration   1: 2.487 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.925 ms/op
                 getUser·p0.50:   2.511 ms/op
                 getUser·p0.90:   3.031 ms/op
                 getUser·p0.95:   3.150 ms/op
                 getUser·p0.99:   3.766 ms/op
                 getUser·p0.999:  11.050 ms/op
                 getUser·p0.9999: 14.839 ms/op
                 getUser·p1.00:   16.073 ms/op

Iteration   2: 2.525 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.038 ms/op
                 getUser·p0.50:   2.572 ms/op
                 getUser·p0.90:   3.064 ms/op
                 getUser·p0.95:   3.244 ms/op
                 getUser·p0.99:   4.440 ms/op
                 getUser·p0.999:  9.476 ms/op
                 getUser·p0.9999: 13.047 ms/op
                 getUser·p1.00:   13.402 ms/op

Iteration   3: 2.480 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.772 ms/op
                 getUser·p0.50:   2.507 ms/op
                 getUser·p0.90:   3.019 ms/op
                 getUser·p0.95:   3.125 ms/op
                 getUser·p0.99:   3.662 ms/op
                 getUser·p0.999:  5.522 ms/op
                 getUser·p0.9999: 11.030 ms/op
                 getUser·p1.00:   11.502 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 384108
  mean =      2.497 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 77 
    [ 1.250,  2.500) = 189675 
    [ 2.500,  3.750) = 189229 
    [ 3.750,  5.000) = 4013 
    [ 5.000,  6.250) = 689 
    [ 6.250,  7.500) = 64 
    [ 7.500,  8.750) = 8 
    [ 8.750, 10.000) = 54 
    [10.000, 11.250) = 115 
    [11.250, 12.500) = 118 
    [12.500, 13.750) = 34 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 7 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.772 ms/op
     p(50.0000) =      2.531 ms/op
     p(90.0000) =      3.035 ms/op
     p(95.0000) =      3.166 ms/op
     p(99.0000) =      3.952 ms/op
     p(99.9000) =      6.906 ms/op
     p(99.9900) =     13.206 ms/op
     p(99.9990) =     15.559 ms/op
     p(99.9999) =     16.073 ms/op
    p(100.0000) =     16.073 ms/op


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
# Warmup Iteration   1: 4.871 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.013 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.000 ±(99.9%) 0.009 ms/op
Iteration   1: 3.013 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.818 ms/op
                 listUser·p0.50:   2.953 ms/op
                 listUser·p0.90:   3.912 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   5.579 ms/op
                 listUser·p0.999:  9.257 ms/op
                 listUser·p0.9999: 10.613 ms/op
                 listUser·p1.00:   11.649 ms/op

Iteration   2: 2.981 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.784 ms/op
                 listUser·p0.50:   2.925 ms/op
                 listUser·p0.90:   3.858 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   5.497 ms/op
                 listUser·p0.999:  9.699 ms/op
                 listUser·p0.9999: 12.007 ms/op
                 listUser·p1.00:   13.468 ms/op

Iteration   3: 2.996 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.839 ms/op
                 listUser·p0.50:   2.933 ms/op
                 listUser·p0.90:   3.871 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   5.530 ms/op
                 listUser·p0.999:  8.671 ms/op
                 listUser·p0.9999: 10.136 ms/op
                 listUser·p1.00:   11.469 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 320093
  mean =      2.996 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 163 
    [ 1.250,  2.500) = 96356 
    [ 2.500,  3.750) = 184763 
    [ 3.750,  5.000) = 31566 
    [ 5.000,  6.250) = 6066 
    [ 6.250,  7.500) = 560 
    [ 7.500,  8.750) = 235 
    [ 8.750, 10.000) = 228 
    [10.000, 11.250) = 121 
    [11.250, 12.500) = 28 
    [12.500, 13.750) = 7 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.784 ms/op
     p(50.0000) =      2.937 ms/op
     p(90.0000) =      3.879 ms/op
     p(95.0000) =      4.391 ms/op
     p(99.0000) =      5.538 ms/op
     p(99.9000) =      9.123 ms/op
     p(99.9900) =     11.435 ms/op
     p(99.9990) =     13.222 ms/op
     p(99.9999) =     13.468 ms/op
    p(100.0000) =     13.468 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.781 ± 1.871  ops/ms
ClientPb.existUser                       thrpt       3  13.332 ± 0.661  ops/ms
ClientPb.getUser                         thrpt       3  12.742 ± 2.567  ops/ms
ClientPb.listUser                        thrpt       3  10.637 ± 0.868  ops/ms
ClientPb.createUser                       avgt       3   2.513 ± 0.301   ms/op
ClientPb.existUser                        avgt       3   2.467 ± 0.621   ms/op
ClientPb.getUser                          avgt       3   2.470 ± 0.251   ms/op
ClientPb.listUser                         avgt       3   3.019 ± 0.218   ms/op
ClientPb.createUser                     sample  378560   2.534 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.968           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.576           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.088           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.219           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.871           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.822           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.522           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.139           ms/op
ClientPb.existUser                      sample  394323   2.431 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.528           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.494           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.949           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.056           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.670           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.323           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.100           ms/op
ClientPb.existUser:existUser·p1.00      sample          17.170           ms/op
ClientPb.getUser                        sample  384108   2.497 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.772           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.531           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.035           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.166           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.952           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.906           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.206           ms/op
ClientPb.getUser:getUser·p1.00          sample          16.073           ms/op
ClientPb.listUser                       sample  320093   2.996 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.784           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.937           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.879           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.391           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.538           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.123           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.435           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.468           ms/op
