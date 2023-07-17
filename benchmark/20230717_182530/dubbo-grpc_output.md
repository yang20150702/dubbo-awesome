# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.444 ops/ms
# Warmup Iteration   2: 5.971 ops/ms
# Warmup Iteration   3: 7.687 ops/ms
Iteration   1: 7.907 ops/ms
Iteration   2: 8.045 ops/ms
Iteration   3: 8.138 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.030 ±(99.9%) 2.121 ops/ms [Average]
  (min, avg, max) = (7.907, 8.030, 8.138), stdev = 0.116
  CI (99.9%): [5.909, 10.151] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 5.176 ops/ms
# Warmup Iteration   2: 8.202 ops/ms
# Warmup Iteration   3: 8.726 ops/ms
Iteration   1: 8.973 ops/ms
Iteration   2: 8.682 ops/ms
Iteration   3: 9.023 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.892 ±(99.9%) 3.356 ops/ms [Average]
  (min, avg, max) = (8.682, 8.892, 9.023), stdev = 0.184
  CI (99.9%): [5.537, 12.248] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 4.653 ops/ms
# Warmup Iteration   2: 7.609 ops/ms
# Warmup Iteration   3: 8.218 ops/ms
Iteration   1: 8.360 ops/ms
Iteration   2: 8.162 ops/ms
Iteration   3: 8.457 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.326 ±(99.9%) 2.748 ops/ms [Average]
  (min, avg, max) = (8.162, 8.326, 8.457), stdev = 0.151
  CI (99.9%): [5.579, 11.074] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 4.129 ops/ms
# Warmup Iteration   2: 6.053 ops/ms
# Warmup Iteration   3: 6.410 ops/ms
Iteration   1: 6.225 ops/ms
Iteration   2: 6.153 ops/ms
Iteration   3: 6.106 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.161 ±(99.9%) 1.094 ops/ms [Average]
  (min, avg, max) = (6.106, 6.161, 6.225), stdev = 0.060
  CI (99.9%): [5.067, 7.255] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.578 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.107 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 4.082 ±(99.9%) 0.014 ms/op
Iteration   1: 3.808 ±(99.9%) 0.003 ms/op
Iteration   2: 3.593 ±(99.9%) 0.001 ms/op
Iteration   3: 3.538 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.646 ±(99.9%) 2.598 ms/op [Average]
  (min, avg, max) = (3.538, 3.646, 3.808), stdev = 0.142
  CI (99.9%): [1.048, 6.244] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 5.508 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.802 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.833 ±(99.9%) 0.003 ms/op
Iteration   1: 3.714 ±(99.9%) 0.003 ms/op
Iteration   2: 3.611 ±(99.9%) 0.003 ms/op
Iteration   3: 3.562 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.629 ±(99.9%) 1.418 ms/op [Average]
  (min, avg, max) = (3.562, 3.629, 3.714), stdev = 0.078
  CI (99.9%): [2.211, 5.047] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 5.702 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.853 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.735 ±(99.9%) 0.004 ms/op
Iteration   1: 3.676 ±(99.9%) 0.004 ms/op
Iteration   2: 3.526 ±(99.9%) 0.004 ms/op
Iteration   3: 3.525 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.575 ±(99.9%) 1.582 ms/op [Average]
  (min, avg, max) = (3.525, 3.575, 3.676), stdev = 0.087
  CI (99.9%): [1.993, 5.158] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 7.024 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 5.242 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.847 ±(99.9%) 0.020 ms/op
Iteration   1: 4.677 ±(99.9%) 0.015 ms/op
Iteration   2: 4.802 ±(99.9%) 0.032 ms/op
Iteration   3: 4.659 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.713 ±(99.9%) 1.421 ms/op [Average]
  (min, avg, max) = (4.659, 4.713, 4.802), stdev = 0.078
  CI (99.9%): [3.291, 6.134] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.483 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 3.883 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.700 ±(99.9%) 0.012 ms/op
Iteration   1: 3.711 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.867 ms/op
                 createUser·p0.50:   3.645 ms/op
                 createUser·p0.90:   4.669 ms/op
                 createUser·p0.95:   5.112 ms/op
                 createUser·p0.99:   6.332 ms/op
                 createUser·p0.999:  12.278 ms/op
                 createUser·p0.9999: 15.464 ms/op
                 createUser·p1.00:   15.843 ms/op

Iteration   2: 3.727 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.879 ms/op
                 createUser·p0.50:   3.637 ms/op
                 createUser·p0.90:   4.612 ms/op
                 createUser·p0.95:   5.120 ms/op
                 createUser·p0.99:   6.476 ms/op
                 createUser·p0.999:  12.457 ms/op
                 createUser·p0.9999: 16.302 ms/op
                 createUser·p1.00:   16.843 ms/op

Iteration   3: 3.826 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   0.923 ms/op
                 createUser·p0.50:   3.752 ms/op
                 createUser·p0.90:   4.948 ms/op
                 createUser·p0.95:   5.423 ms/op
                 createUser·p0.99:   7.086 ms/op
                 createUser·p0.999:  21.627 ms/op
                 createUser·p0.9999: 30.613 ms/op
                 createUser·p1.00:   32.178 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 255649
  mean =      3.754 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14681 
    [ 2.500,  5.000) = 222940 
    [ 5.000,  7.500) = 16541 
    [ 7.500, 10.000) = 847 
    [10.000, 12.500) = 373 
    [12.500, 15.000) = 123 
    [15.000, 17.500) = 46 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 10 
    [27.500, 30.000) = 12 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.867 ms/op
     p(50.0000) =      3.674 ms/op
     p(90.0000) =      4.743 ms/op
     p(95.0000) =      5.235 ms/op
     p(99.0000) =      6.595 ms/op
     p(99.9000) =     12.616 ms/op
     p(99.9900) =     26.884 ms/op
     p(99.9990) =     31.654 ms/op
     p(99.9999) =     32.178 ms/op
    p(100.0000) =     32.178 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.555 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 3.888 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.764 ±(99.9%) 0.012 ms/op
Iteration   1: 3.665 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.933 ms/op
                 existUser·p0.50:   3.527 ms/op
                 existUser·p0.90:   4.596 ms/op
                 existUser·p0.95:   5.104 ms/op
                 existUser·p0.99:   6.463 ms/op
                 existUser·p0.999:  13.318 ms/op
                 existUser·p0.9999: 15.733 ms/op
                 existUser·p1.00:   18.186 ms/op

Iteration   2: 3.611 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.891 ms/op
                 existUser·p0.50:   3.490 ms/op
                 existUser·p0.90:   4.415 ms/op
                 existUser·p0.95:   4.866 ms/op
                 existUser·p0.99:   6.423 ms/op
                 existUser·p0.999:  12.059 ms/op
                 existUser·p0.9999: 17.540 ms/op
                 existUser·p1.00:   17.990 ms/op

Iteration   3: 3.555 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.993 ms/op
                 existUser·p0.50:   3.432 ms/op
                 existUser·p0.90:   4.440 ms/op
                 existUser·p0.95:   4.915 ms/op
                 existUser·p0.99:   6.750 ms/op
                 existUser·p0.999:  11.535 ms/op
                 existUser·p0.9999: 32.834 ms/op
                 existUser·p1.00:   34.537 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 266016
  mean =      3.610 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7420 
    [ 2.500,  5.000) = 245878 
    [ 5.000,  7.500) = 11258 
    [ 7.500, 10.000) = 875 
    [10.000, 12.500) = 339 
    [12.500, 15.000) = 134 
    [15.000, 17.500) = 70 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 14 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.891 ms/op
     p(50.0000) =      3.482 ms/op
     p(90.0000) =      4.481 ms/op
     p(95.0000) =      4.973 ms/op
     p(99.0000) =      6.545 ms/op
     p(99.9000) =     12.108 ms/op
     p(99.9900) =     31.746 ms/op
     p(99.9990) =     34.494 ms/op
     p(99.9999) =     34.537 ms/op
    p(100.0000) =     34.537 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 6.121 ±(99.9%) 0.071 ms/op
# Warmup Iteration   2: 3.851 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.720 ±(99.9%) 0.013 ms/op
Iteration   1: 3.720 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.937 ms/op
                 getUser·p0.50:   3.641 ms/op
                 getUser·p0.90:   4.801 ms/op
                 getUser·p0.95:   5.341 ms/op
                 getUser·p0.99:   7.143 ms/op
                 getUser·p0.999:  12.976 ms/op
                 getUser·p0.9999: 18.901 ms/op
                 getUser·p1.00:   19.431 ms/op

Iteration   2: 3.940 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   0.952 ms/op
                 getUser·p0.50:   3.768 ms/op
                 getUser·p0.90:   5.038 ms/op
                 getUser·p0.95:   5.628 ms/op
                 getUser·p0.99:   8.471 ms/op
                 getUser·p0.999:  14.104 ms/op
                 getUser·p0.9999: 23.840 ms/op
                 getUser·p1.00:   24.347 ms/op

Iteration   3: 4.063 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   0.898 ms/op
                 getUser·p0.50:   3.887 ms/op
                 getUser·p0.90:   5.177 ms/op
                 getUser·p0.95:   5.833 ms/op
                 getUser·p0.99:   8.471 ms/op
                 getUser·p0.999:  13.362 ms/op
                 getUser·p0.9999: 41.288 ms/op
                 getUser·p1.00:   42.336 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 245908
  mean =      3.902 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 220944 
    [ 5.000, 10.000) = 24033 
    [10.000, 15.000) = 768 
    [15.000, 20.000) = 79 
    [20.000, 25.000) = 52 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.898 ms/op
     p(50.0000) =      3.764 ms/op
     p(90.0000) =      5.014 ms/op
     p(95.0000) =      5.603 ms/op
     p(99.0000) =      8.086 ms/op
     p(99.9000) =     13.451 ms/op
     p(99.9900) =     40.763 ms/op
     p(99.9990) =     41.454 ms/op
     p(99.9999) =     42.336 ms/op
    p(100.0000) =     42.336 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 7.852 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 5.278 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.996 ±(99.9%) 0.019 ms/op
Iteration   1: 4.771 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.278 ms/op
                 listUser·p0.50:   4.465 ms/op
                 listUser·p0.90:   6.365 ms/op
                 listUser·p0.95:   7.283 ms/op
                 listUser·p0.99:   9.388 ms/op
                 listUser·p0.999:  13.582 ms/op
                 listUser·p0.9999: 15.825 ms/op
                 listUser·p1.00:   16.269 ms/op

Iteration   2: 4.736 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.665 ms/op
                 listUser·p0.50:   4.440 ms/op
                 listUser·p0.90:   6.308 ms/op
                 listUser·p0.95:   7.250 ms/op
                 listUser·p0.99:   9.634 ms/op
                 listUser·p0.999:  16.908 ms/op
                 listUser·p0.9999: 26.887 ms/op
                 listUser·p1.00:   30.376 ms/op

Iteration   3: 4.737 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   0.890 ms/op
                 listUser·p0.50:   4.391 ms/op
                 listUser·p0.90:   6.390 ms/op
                 listUser·p0.95:   7.373 ms/op
                 listUser·p0.99:   10.502 ms/op
                 listUser·p0.999:  25.113 ms/op
                 listUser·p0.9999: 33.348 ms/op
                 listUser·p1.00:   33.751 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 202087
  mean =      4.748 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 719 
    [ 2.500,  5.000) = 145758 
    [ 5.000,  7.500) = 46968 
    [ 7.500, 10.000) = 6816 
    [10.000, 12.500) = 1062 
    [12.500, 15.000) = 378 
    [15.000, 17.500) = 149 
    [17.500, 20.000) = 121 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 52 
    [27.500, 30.000) = 9 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 23 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.890 ms/op
     p(50.0000) =      4.432 ms/op
     p(90.0000) =      6.357 ms/op
     p(95.0000) =      7.299 ms/op
     p(99.0000) =      9.830 ms/op
     p(99.9000) =     18.249 ms/op
     p(99.9900) =     32.663 ms/op
     p(99.9990) =     33.748 ms/op
     p(99.9999) =     33.751 ms/op
    p(100.0000) =     33.751 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.030 ± 2.121  ops/ms
ClientGrpc.existUser                       thrpt       3   8.892 ± 3.356  ops/ms
ClientGrpc.getUser                         thrpt       3   8.326 ± 2.748  ops/ms
ClientGrpc.listUser                        thrpt       3   6.161 ± 1.094  ops/ms
ClientGrpc.createUser                       avgt       3   3.646 ± 2.598   ms/op
ClientGrpc.existUser                        avgt       3   3.629 ± 1.418   ms/op
ClientGrpc.getUser                          avgt       3   3.575 ± 1.582   ms/op
ClientGrpc.listUser                         avgt       3   4.713 ± 1.421   ms/op
ClientGrpc.createUser                     sample  255649   3.754 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.867           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.674           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.743           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.235           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.595           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.616           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          26.884           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          32.178           ms/op
ClientGrpc.existUser                      sample  266016   3.610 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.891           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.482           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.481           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.973           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.545           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.108           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          31.746           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          34.537           ms/op
ClientGrpc.getUser                        sample  245908   3.902 ± 0.008   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.898           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.764           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.014           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.603           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           8.086           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          13.451           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          40.763           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          42.336           ms/op
ClientGrpc.listUser                       sample  202087   4.748 ± 0.011   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.890           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.432           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.357           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.299           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.830           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.249           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          32.663           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          33.751           ms/op
