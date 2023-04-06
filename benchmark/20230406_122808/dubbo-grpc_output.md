# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.164 ops/ms
# Warmup Iteration   2: 7.371 ops/ms
# Warmup Iteration   3: 8.774 ops/ms
Iteration   1: 9.156 ops/ms
Iteration   2: 9.078 ops/ms
Iteration   3: 8.994 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.076 ±(99.9%) 1.475 ops/ms [Average]
  (min, avg, max) = (8.994, 9.076, 9.156), stdev = 0.081
  CI (99.9%): [7.601, 10.551] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 6.101 ops/ms
# Warmup Iteration   2: 8.761 ops/ms
# Warmup Iteration   3: 9.326 ops/ms
Iteration   1: 9.482 ops/ms
Iteration   2: 9.372 ops/ms
Iteration   3: 9.516 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.457 ±(99.9%) 1.380 ops/ms [Average]
  (min, avg, max) = (9.372, 9.457, 9.516), stdev = 0.076
  CI (99.9%): [8.077, 10.837] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.393 ops/ms
# Warmup Iteration   2: 8.641 ops/ms
# Warmup Iteration   3: 8.392 ops/ms
Iteration   1: 8.653 ops/ms
Iteration   2: 8.822 ops/ms
Iteration   3: 8.934 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.803 ±(99.9%) 2.581 ops/ms [Average]
  (min, avg, max) = (8.653, 8.803, 8.934), stdev = 0.141
  CI (99.9%): [6.221, 11.384] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 4.602 ops/ms
# Warmup Iteration   2: 6.648 ops/ms
# Warmup Iteration   3: 6.807 ops/ms
Iteration   1: 6.818 ops/ms
Iteration   2: 6.899 ops/ms
Iteration   3: 7.040 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.919 ±(99.9%) 2.051 ops/ms [Average]
  (min, avg, max) = (6.818, 6.919, 7.040), stdev = 0.112
  CI (99.9%): [4.868, 8.970] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 4.808 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.812 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 3.637 ±(99.9%) 0.011 ms/op
Iteration   1: 3.485 ±(99.9%) 0.004 ms/op
Iteration   2: 3.619 ±(99.9%) 0.003 ms/op
Iteration   3: 3.607 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.570 ±(99.9%) 1.350 ms/op [Average]
  (min, avg, max) = (3.485, 3.570, 3.619), stdev = 0.074
  CI (99.9%): [2.220, 4.920] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.819 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 3.571 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.427 ±(99.9%) 0.004 ms/op
Iteration   1: 3.360 ±(99.9%) 0.004 ms/op
Iteration   2: 3.375 ±(99.9%) 0.004 ms/op
Iteration   3: 3.442 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.392 ±(99.9%) 0.792 ms/op [Average]
  (min, avg, max) = (3.360, 3.392, 3.442), stdev = 0.043
  CI (99.9%): [2.600, 4.184] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.269 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.930 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.691 ±(99.9%) 0.004 ms/op
Iteration   1: 3.612 ±(99.9%) 0.003 ms/op
Iteration   2: 3.624 ±(99.9%) 0.004 ms/op
Iteration   3: 3.587 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.607 ±(99.9%) 0.345 ms/op [Average]
  (min, avg, max) = (3.587, 3.607, 3.624), stdev = 0.019
  CI (99.9%): [3.262, 3.953] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 5.948 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.884 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.670 ±(99.9%) 0.012 ms/op
Iteration   1: 4.738 ±(99.9%) 0.012 ms/op
Iteration   2: 4.704 ±(99.9%) 0.009 ms/op
Iteration   3: 4.707 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.717 ±(99.9%) 0.347 ms/op [Average]
  (min, avg, max) = (4.704, 4.717, 4.738), stdev = 0.019
  CI (99.9%): [4.369, 5.064] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.424 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.898 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.654 ±(99.9%) 0.008 ms/op
Iteration   1: 3.616 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.069 ms/op
                 createUser·p0.50:   3.584 ms/op
                 createUser·p0.90:   4.325 ms/op
                 createUser·p0.95:   4.596 ms/op
                 createUser·p0.99:   5.554 ms/op
                 createUser·p0.999:  7.946 ms/op
                 createUser·p0.9999: 14.303 ms/op
                 createUser·p1.00:   14.615 ms/op

Iteration   2: 3.587 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.344 ms/op
                 createUser·p0.50:   3.535 ms/op
                 createUser·p0.90:   4.293 ms/op
                 createUser·p0.95:   4.653 ms/op
                 createUser·p0.99:   5.775 ms/op
                 createUser·p0.999:  8.662 ms/op
                 createUser·p0.9999: 24.974 ms/op
                 createUser·p1.00:   25.362 ms/op

Iteration   3: 3.633 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.609 ms/op
                 createUser·p0.50:   3.543 ms/op
                 createUser·p0.90:   4.309 ms/op
                 createUser·p0.95:   4.669 ms/op
                 createUser·p0.99:   6.095 ms/op
                 createUser·p0.999:  16.974 ms/op
                 createUser·p0.9999: 24.647 ms/op
                 createUser·p1.00:   25.035 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 265926
  mean =      3.612 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8537 
    [ 2.500,  5.000) = 250320 
    [ 5.000,  7.500) = 6283 
    [ 7.500, 10.000) = 474 
    [10.000, 12.500) = 87 
    [12.500, 15.000) = 47 
    [15.000, 17.500) = 64 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 54 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.344 ms/op
     p(50.0000) =      3.551 ms/op
     p(90.0000) =      4.309 ms/op
     p(95.0000) =      4.628 ms/op
     p(99.0000) =      5.808 ms/op
     p(99.9000) =     11.780 ms/op
     p(99.9900) =     24.622 ms/op
     p(99.9990) =     25.275 ms/op
     p(99.9999) =     25.362 ms/op
    p(100.0000) =     25.362 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.846 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.680 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.428 ±(99.9%) 0.007 ms/op
Iteration   1: 3.471 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.893 ms/op
                 existUser·p0.50:   3.428 ms/op
                 existUser·p0.90:   4.051 ms/op
                 existUser·p0.95:   4.383 ms/op
                 existUser·p0.99:   5.500 ms/op
                 existUser·p0.999:  10.231 ms/op
                 existUser·p0.9999: 15.172 ms/op
                 existUser·p1.00:   15.417 ms/op

Iteration   2: 3.392 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.823 ms/op
                 existUser·p0.50:   3.375 ms/op
                 existUser·p0.90:   3.891 ms/op
                 existUser·p0.95:   4.116 ms/op
                 existUser·p0.99:   5.030 ms/op
                 existUser·p0.999:  9.160 ms/op
                 existUser·p0.9999: 16.435 ms/op
                 existUser·p1.00:   16.908 ms/op

Iteration   3: 3.351 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.878 ms/op
                 existUser·p0.50:   3.326 ms/op
                 existUser·p0.90:   4.022 ms/op
                 existUser·p0.95:   4.309 ms/op
                 existUser·p0.99:   5.333 ms/op
                 existUser·p0.999:  10.551 ms/op
                 existUser·p0.9999: 18.514 ms/op
                 existUser·p1.00:   19.005 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 282186
  mean =      3.404 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 242 
    [ 1.250,  2.500) = 13137 
    [ 2.500,  3.750) = 214776 
    [ 3.750,  5.000) = 50056 
    [ 5.000,  6.250) = 2859 
    [ 6.250,  7.500) = 492 
    [ 7.500,  8.750) = 237 
    [ 8.750, 10.000) = 118 
    [10.000, 11.250) = 93 
    [11.250, 12.500) = 7 
    [12.500, 13.750) = 26 
    [13.750, 15.000) = 40 
    [15.000, 16.250) = 36 
    [16.250, 17.500) = 33 
    [17.500, 18.750) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.823 ms/op
     p(50.0000) =      3.379 ms/op
     p(90.0000) =      3.985 ms/op
     p(95.0000) =      4.276 ms/op
     p(99.0000) =      5.308 ms/op
     p(99.9000) =      9.772 ms/op
     p(99.9900) =     18.015 ms/op
     p(99.9990) =     18.815 ms/op
     p(99.9999) =     19.005 ms/op
    p(100.0000) =     19.005 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.284 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.678 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.645 ±(99.9%) 0.008 ms/op
Iteration   1: 3.593 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.051 ms/op
                 getUser·p0.50:   3.535 ms/op
                 getUser·p0.90:   4.235 ms/op
                 getUser·p0.95:   4.612 ms/op
                 getUser·p0.99:   5.545 ms/op
                 getUser·p0.999:  12.304 ms/op
                 getUser·p0.9999: 14.311 ms/op
                 getUser·p1.00:   15.401 ms/op

Iteration   2: 3.563 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.986 ms/op
                 getUser·p0.50:   3.523 ms/op
                 getUser·p0.90:   4.129 ms/op
                 getUser·p0.95:   4.465 ms/op
                 getUser·p0.99:   5.530 ms/op
                 getUser·p0.999:  7.793 ms/op
                 getUser·p0.9999: 15.499 ms/op
                 getUser·p1.00:   15.679 ms/op

Iteration   3: 3.561 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.106 ms/op
                 getUser·p0.50:   3.502 ms/op
                 getUser·p0.90:   4.149 ms/op
                 getUser·p0.95:   4.456 ms/op
                 getUser·p0.99:   5.661 ms/op
                 getUser·p0.999:  10.649 ms/op
                 getUser·p0.9999: 31.457 ms/op
                 getUser·p1.00:   31.654 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 268765
  mean =      3.573 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6813 
    [ 2.500,  5.000) = 256387 
    [ 5.000,  7.500) = 5097 
    [ 7.500, 10.000) = 195 
    [10.000, 12.500) = 98 
    [12.500, 15.000) = 80 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.986 ms/op
     p(50.0000) =      3.523 ms/op
     p(90.0000) =      4.170 ms/op
     p(95.0000) =      4.514 ms/op
     p(99.0000) =      5.579 ms/op
     p(99.9000) =     10.227 ms/op
     p(99.9900) =     30.617 ms/op
     p(99.9990) =     31.599 ms/op
     p(99.9999) =     31.654 ms/op
    p(100.0000) =     31.654 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 6.582 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 4.747 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.668 ±(99.9%) 0.014 ms/op
Iteration   1: 4.611 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.696 ms/op
                 listUser·p0.50:   4.456 ms/op
                 listUser·p0.90:   5.562 ms/op
                 listUser·p0.95:   6.455 ms/op
                 listUser·p0.99:   8.036 ms/op
                 listUser·p0.999:  15.721 ms/op
                 listUser·p0.9999: 17.372 ms/op
                 listUser·p1.00:   17.826 ms/op

Iteration   2: 4.731 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.419 ms/op
                 listUser·p0.50:   4.538 ms/op
                 listUser·p0.90:   5.825 ms/op
                 listUser·p0.95:   6.824 ms/op
                 listUser·p0.99:   8.536 ms/op
                 listUser·p0.999:  16.466 ms/op
                 listUser·p0.9999: 29.335 ms/op
                 listUser·p1.00:   29.786 ms/op

Iteration   3: 4.704 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.530 ms/op
                 listUser·p0.50:   4.522 ms/op
                 listUser·p0.90:   5.661 ms/op
                 listUser·p0.95:   6.595 ms/op
                 listUser·p0.99:   8.094 ms/op
                 listUser·p0.999:  21.316 ms/op
                 listUser·p0.9999: 34.616 ms/op
                 listUser·p1.00:   34.800 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 205036
  mean =      4.681 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 322 
    [ 2.500,  5.000) = 164548 
    [ 5.000,  7.500) = 35878 
    [ 7.500, 10.000) = 3741 
    [10.000, 12.500) = 213 
    [12.500, 15.000) = 17 
    [15.000, 17.500) = 170 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 32 
    [30.000, 32.500) = 21 
    [32.500, 35.000) = 43 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.419 ms/op
     p(50.0000) =      4.506 ms/op
     p(90.0000) =      5.693 ms/op
     p(95.0000) =      6.611 ms/op
     p(99.0000) =      8.217 ms/op
     p(99.9000) =     16.220 ms/op
     p(99.9900) =     33.980 ms/op
     p(99.9990) =     34.731 ms/op
     p(99.9999) =     34.800 ms/op
    p(100.0000) =     34.800 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.076 ± 1.475  ops/ms
ClientGrpc.existUser                       thrpt       3   9.457 ± 1.380  ops/ms
ClientGrpc.getUser                         thrpt       3   8.803 ± 2.581  ops/ms
ClientGrpc.listUser                        thrpt       3   6.919 ± 2.051  ops/ms
ClientGrpc.createUser                       avgt       3   3.570 ± 1.350   ms/op
ClientGrpc.existUser                        avgt       3   3.392 ± 0.792   ms/op
ClientGrpc.getUser                          avgt       3   3.607 ± 0.345   ms/op
ClientGrpc.listUser                         avgt       3   4.717 ± 0.347   ms/op
ClientGrpc.createUser                     sample  265926   3.612 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.344           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.551           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.309           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.628           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.808           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.780           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.622           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.362           ms/op
ClientGrpc.existUser                      sample  282186   3.404 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.823           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.379           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.985           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.276           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.308           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.772           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.015           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.005           ms/op
ClientGrpc.getUser                        sample  268765   3.573 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.986           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.523           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.170           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.514           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.579           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.227           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          30.617           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          31.654           ms/op
ClientGrpc.listUser                       sample  205036   4.681 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.419           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.506           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.693           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.611           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.217           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.220           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          33.980           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          34.800           ms/op
