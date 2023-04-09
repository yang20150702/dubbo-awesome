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
# Warmup Iteration   1: 4.125 ops/ms
# Warmup Iteration   2: 8.892 ops/ms
# Warmup Iteration   3: 9.983 ops/ms
Iteration   1: 10.341 ops/ms
Iteration   2: 10.404 ops/ms
Iteration   3: 10.307 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.351 ±(99.9%) 0.893 ops/ms [Average]
  (min, avg, max) = (10.307, 10.351, 10.404), stdev = 0.049
  CI (99.9%): [9.457, 11.244] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.903 ops/ms
# Warmup Iteration   2: 10.416 ops/ms
# Warmup Iteration   3: 11.020 ops/ms
Iteration   1: 11.062 ops/ms
Iteration   2: 10.906 ops/ms
Iteration   3: 10.897 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.955 ±(99.9%) 1.688 ops/ms [Average]
  (min, avg, max) = (10.897, 10.955, 11.062), stdev = 0.093
  CI (99.9%): [9.267, 12.643] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 7.253 ops/ms
# Warmup Iteration   2: 9.931 ops/ms
# Warmup Iteration   3: 10.504 ops/ms
Iteration   1: 10.583 ops/ms
Iteration   2: 10.568 ops/ms
Iteration   3: 10.499 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.550 ±(99.9%) 0.814 ops/ms [Average]
  (min, avg, max) = (10.499, 10.550, 10.583), stdev = 0.045
  CI (99.9%): [9.736, 11.364] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.292 ops/ms
# Warmup Iteration   2: 7.787 ops/ms
# Warmup Iteration   3: 7.960 ops/ms
Iteration   1: 7.885 ops/ms
Iteration   2: 7.975 ops/ms
Iteration   3: 8.077 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.979 ±(99.9%) 1.753 ops/ms [Average]
  (min, avg, max) = (7.885, 7.979, 8.077), stdev = 0.096
  CI (99.9%): [6.226, 9.732] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.253 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.136 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.008 ±(99.9%) 0.003 ms/op
Iteration   1: 3.063 ±(99.9%) 0.011 ms/op
Iteration   2: 3.054 ±(99.9%) 0.003 ms/op
Iteration   3: 3.019 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.045 ±(99.9%) 0.425 ms/op [Average]
  (min, avg, max) = (3.019, 3.045, 3.063), stdev = 0.023
  CI (99.9%): [2.620, 3.470] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.883 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.014 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.925 ±(99.9%) 0.003 ms/op
Iteration   1: 2.922 ±(99.9%) 0.002 ms/op
Iteration   2: 2.912 ±(99.9%) 0.001 ms/op
Iteration   3: 2.890 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.908 ±(99.9%) 0.295 ms/op [Average]
  (min, avg, max) = (2.890, 2.908, 2.922), stdev = 0.016
  CI (99.9%): [2.613, 3.203] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.367 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.155 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.044 ±(99.9%) 0.003 ms/op
Iteration   1: 3.010 ±(99.9%) 0.002 ms/op
Iteration   2: 3.026 ±(99.9%) 0.004 ms/op
Iteration   3: 3.037 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.024 ±(99.9%) 0.253 ms/op [Average]
  (min, avg, max) = (3.010, 3.024, 3.037), stdev = 0.014
  CI (99.9%): [2.771, 3.278] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.101 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.063 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.879 ±(99.9%) 0.022 ms/op
Iteration   1: 3.889 ±(99.9%) 0.024 ms/op
Iteration   2: 3.973 ±(99.9%) 0.017 ms/op
Iteration   3: 3.957 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.940 ±(99.9%) 0.814 ms/op [Average]
  (min, avg, max) = (3.889, 3.940, 3.973), stdev = 0.045
  CI (99.9%): [3.125, 4.754] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.164 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.230 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.148 ±(99.9%) 0.006 ms/op
Iteration   1: 3.013 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.844 ms/op
                 createUser·p0.50:   2.998 ms/op
                 createUser·p0.90:   3.428 ms/op
                 createUser·p0.95:   3.699 ms/op
                 createUser·p0.99:   4.719 ms/op
                 createUser·p0.999:  8.348 ms/op
                 createUser·p0.9999: 12.841 ms/op
                 createUser·p1.00:   13.140 ms/op

Iteration   2: 2.971 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.730 ms/op
                 createUser·p0.50:   2.974 ms/op
                 createUser·p0.90:   3.506 ms/op
                 createUser·p0.95:   3.748 ms/op
                 createUser·p0.99:   4.538 ms/op
                 createUser·p0.999:  6.860 ms/op
                 createUser·p0.9999: 13.734 ms/op
                 createUser·p1.00:   14.057 ms/op

Iteration   3: 2.923 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.831 ms/op
                 createUser·p0.50:   2.953 ms/op
                 createUser·p0.90:   3.396 ms/op
                 createUser·p0.95:   3.637 ms/op
                 createUser·p0.99:   4.506 ms/op
                 createUser·p0.999:  10.300 ms/op
                 createUser·p0.9999: 26.116 ms/op
                 createUser·p1.00:   26.345 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 323085
  mean =      2.969 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31587 
    [ 2.500,  5.000) = 289721 
    [ 5.000,  7.500) = 1373 
    [ 7.500, 10.000) = 153 
    [10.000, 12.500) = 79 
    [12.500, 15.000) = 114 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.730 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.445 ms/op
     p(95.0000) =      3.703 ms/op
     p(99.0000) =      4.604 ms/op
     p(99.9000) =      8.142 ms/op
     p(99.9900) =     21.600 ms/op
     p(99.9990) =     26.298 ms/op
     p(99.9999) =     26.345 ms/op
    p(100.0000) =     26.345 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.813 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.103 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.923 ±(99.9%) 0.006 ms/op
Iteration   1: 2.889 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.860 ms/op
                 existUser·p0.50:   2.888 ms/op
                 existUser·p0.90:   3.396 ms/op
                 existUser·p0.95:   3.658 ms/op
                 existUser·p0.99:   4.284 ms/op
                 existUser·p0.999:  6.734 ms/op
                 existUser·p0.9999: 13.546 ms/op
                 existUser·p1.00:   13.763 ms/op

Iteration   2: 2.918 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.878 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.432 ms/op
                 existUser·p0.95:   3.584 ms/op
                 existUser·p0.99:   4.243 ms/op
                 existUser·p0.999:  5.413 ms/op
                 existUser·p0.9999: 28.083 ms/op
                 existUser·p1.00:   28.606 ms/op

Iteration   3: 2.921 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.856 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.334 ms/op
                 existUser·p0.95:   3.547 ms/op
                 existUser·p0.99:   4.424 ms/op
                 existUser·p0.999:  8.055 ms/op
                 existUser·p0.9999: 20.283 ms/op
                 existUser·p1.00:   21.168 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 329610
  mean =      2.909 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 41526 
    [ 2.500,  5.000) = 287216 
    [ 5.000,  7.500) = 588 
    [ 7.500, 10.000) = 119 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.856 ms/op
     p(50.0000) =      2.900 ms/op
     p(90.0000) =      3.391 ms/op
     p(95.0000) =      3.592 ms/op
     p(99.0000) =      4.309 ms/op
     p(99.9000) =      7.122 ms/op
     p(99.9900) =     21.400 ms/op
     p(99.9990) =     28.466 ms/op
     p(99.9999) =     28.606 ms/op
    p(100.0000) =     28.606 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.397 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.152 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.062 ±(99.9%) 0.006 ms/op
Iteration   1: 3.044 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.874 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.400 ms/op
                 getUser·p0.95:   3.600 ms/op
                 getUser·p0.99:   4.317 ms/op
                 getUser·p0.999:  6.692 ms/op
                 getUser·p0.9999: 21.463 ms/op
                 getUser·p1.00:   21.856 ms/op

Iteration   2: 3.095 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.604 ms/op
                 getUser·p0.50:   3.076 ms/op
                 getUser·p0.90:   3.686 ms/op
                 getUser·p0.95:   3.850 ms/op
                 getUser·p0.99:   4.260 ms/op
                 getUser·p0.999:  7.203 ms/op
                 getUser·p0.9999: 17.946 ms/op
                 getUser·p1.00:   18.186 ms/op

Iteration   3: 3.069 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.006 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.510 ms/op
                 getUser·p0.95:   3.772 ms/op
                 getUser·p0.99:   4.391 ms/op
                 getUser·p0.999:  8.670 ms/op
                 getUser·p0.9999: 23.500 ms/op
                 getUser·p1.00:   24.019 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 312649
  mean =      3.069 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13432 
    [ 2.500,  5.000) = 297890 
    [ 5.000,  7.500) = 1022 
    [ 7.500, 10.000) = 66 
    [10.000, 12.500) = 47 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 50 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.604 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      3.547 ms/op
     p(95.0000) =      3.781 ms/op
     p(99.0000) =      4.325 ms/op
     p(99.9000) =      7.395 ms/op
     p(99.9900) =     21.577 ms/op
     p(99.9990) =     23.916 ms/op
     p(99.9999) =     24.019 ms/op
    p(100.0000) =     24.019 ms/op


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
# Warmup Iteration   1: 5.539 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.097 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.012 ±(99.9%) 0.010 ms/op
Iteration   1: 4.014 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.329 ms/op
                 listUser·p0.50:   3.834 ms/op
                 listUser·p0.90:   5.005 ms/op
                 listUser·p0.95:   5.767 ms/op
                 listUser·p0.99:   7.062 ms/op
                 listUser·p0.999:  13.457 ms/op
                 listUser·p0.9999: 21.104 ms/op
                 listUser·p1.00:   21.299 ms/op

Iteration   2: 4.049 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.995 ms/op
                 listUser·p0.50:   3.863 ms/op
                 listUser·p0.90:   5.104 ms/op
                 listUser·p0.95:   5.792 ms/op
                 listUser·p0.99:   7.037 ms/op
                 listUser·p0.999:  16.122 ms/op
                 listUser·p0.9999: 21.928 ms/op
                 listUser·p1.00:   24.969 ms/op

Iteration   3: 4.015 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.311 ms/op
                 listUser·p0.50:   3.842 ms/op
                 listUser·p0.90:   5.063 ms/op
                 listUser·p0.95:   5.734 ms/op
                 listUser·p0.99:   6.947 ms/op
                 listUser·p0.999:  16.941 ms/op
                 listUser·p0.9999: 21.672 ms/op
                 listUser·p1.00:   30.507 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 238309
  mean =      4.026 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2188 
    [ 2.500,  5.000) = 211103 
    [ 5.000,  7.500) = 23675 
    [ 7.500, 10.000) = 879 
    [10.000, 12.500) = 118 
    [12.500, 15.000) = 94 
    [15.000, 17.500) = 109 
    [17.500, 20.000) = 73 
    [20.000, 22.500) = 62 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.311 ms/op
     p(50.0000) =      3.846 ms/op
     p(90.0000) =      5.054 ms/op
     p(95.0000) =      5.767 ms/op
     p(99.0000) =      7.012 ms/op
     p(99.9000) =     15.587 ms/op
     p(99.9900) =     21.501 ms/op
     p(99.9990) =     30.112 ms/op
     p(99.9999) =     30.507 ms/op
    p(100.0000) =     30.507 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.351 ± 0.893  ops/ms
ClientGrpc.existUser                       thrpt       3  10.955 ± 1.688  ops/ms
ClientGrpc.getUser                         thrpt       3  10.550 ± 0.814  ops/ms
ClientGrpc.listUser                        thrpt       3   7.979 ± 1.753  ops/ms
ClientGrpc.createUser                       avgt       3   3.045 ± 0.425   ms/op
ClientGrpc.existUser                        avgt       3   2.908 ± 0.295   ms/op
ClientGrpc.getUser                          avgt       3   3.024 ± 0.253   ms/op
ClientGrpc.listUser                         avgt       3   3.940 ± 0.814   ms/op
ClientGrpc.createUser                     sample  323085   2.969 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.730           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.978           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.445           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.703           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.604           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.142           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.600           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.345           ms/op
ClientGrpc.existUser                      sample  329610   2.909 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.856           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.900           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.391           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.592           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.309           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.122           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.400           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          28.606           ms/op
ClientGrpc.getUser                        sample  312649   3.069 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.604           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.039           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.547           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.781           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.325           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.395           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.577           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.019           ms/op
ClientGrpc.listUser                       sample  238309   4.026 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.311           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.846           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.054           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.767           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.012           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.587           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.501           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          30.507           ms/op
