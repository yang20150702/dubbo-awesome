# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.106 ops/ms
# Warmup Iteration   2: 4.936 ops/ms
# Warmup Iteration   3: 6.804 ops/ms
Iteration   1: 6.739 ops/ms
Iteration   2: 6.889 ops/ms
Iteration   3: 6.912 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  6.847 ±(99.9%) 1.720 ops/ms [Average]
  (min, avg, max) = (6.739, 6.847, 6.912), stdev = 0.094
  CI (99.9%): [5.127, 8.566] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 4.819 ops/ms
# Warmup Iteration   2: 7.200 ops/ms
# Warmup Iteration   3: 7.468 ops/ms
Iteration   1: 7.807 ops/ms
Iteration   2: 7.700 ops/ms
Iteration   3: 7.609 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.705 ±(99.9%) 1.806 ops/ms [Average]
  (min, avg, max) = (7.609, 7.705, 7.807), stdev = 0.099
  CI (99.9%): [5.900, 9.511] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 4.230 ops/ms
# Warmup Iteration   2: 6.965 ops/ms
# Warmup Iteration   3: 7.018 ops/ms
Iteration   1: 7.030 ops/ms
Iteration   2: 7.193 ops/ms
Iteration   3: 7.160 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.128 ±(99.9%) 1.576 ops/ms [Average]
  (min, avg, max) = (7.030, 7.128, 7.193), stdev = 0.086
  CI (99.9%): [5.552, 8.704] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.752 ops/ms
# Warmup Iteration   2: 4.816 ops/ms
# Warmup Iteration   3: 5.278 ops/ms
Iteration   1: 5.368 ops/ms
Iteration   2: 5.407 ops/ms
Iteration   3: 5.176 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.317 ±(99.9%) 2.253 ops/ms [Average]
  (min, avg, max) = (5.176, 5.317, 5.407), stdev = 0.124
  CI (99.9%): [3.064, 7.570] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 6.935 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 5.120 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 4.811 ±(99.9%) 0.009 ms/op
Iteration   1: 4.637 ±(99.9%) 0.003 ms/op
Iteration   2: 4.560 ±(99.9%) 0.004 ms/op
Iteration   3: 4.451 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.550 ±(99.9%) 1.699 ms/op [Average]
  (min, avg, max) = (4.451, 4.550, 4.637), stdev = 0.093
  CI (99.9%): [2.851, 6.248] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.657 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 4.469 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.233 ±(99.9%) 0.004 ms/op
Iteration   1: 4.378 ±(99.9%) 0.005 ms/op
Iteration   2: 4.269 ±(99.9%) 0.002 ms/op
Iteration   3: 4.127 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.258 ±(99.9%) 2.295 ms/op [Average]
  (min, avg, max) = (4.127, 4.258, 4.378), stdev = 0.126
  CI (99.9%): [1.963, 6.553] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 6.890 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.838 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 4.663 ±(99.9%) 0.004 ms/op
Iteration   1: 4.506 ±(99.9%) 0.004 ms/op
Iteration   2: 4.387 ±(99.9%) 0.004 ms/op
Iteration   3: 4.525 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.473 ±(99.9%) 1.367 ms/op [Average]
  (min, avg, max) = (4.387, 4.473, 4.525), stdev = 0.075
  CI (99.9%): [3.105, 5.840] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 8.882 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 6.488 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 5.993 ±(99.9%) 0.018 ms/op
Iteration   1: 5.734 ±(99.9%) 0.026 ms/op
Iteration   2: 5.872 ±(99.9%) 0.017 ms/op
Iteration   3: 6.193 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.933 ±(99.9%) 4.295 ms/op [Average]
  (min, avg, max) = (5.734, 5.933, 6.193), stdev = 0.235
  CI (99.9%): [1.638, 10.227] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 6.865 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 4.989 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.561 ±(99.9%) 0.013 ms/op
Iteration   1: 4.543 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.092 ms/op
                 createUser·p0.50:   4.399 ms/op
                 createUser·p0.90:   5.579 ms/op
                 createUser·p0.95:   6.054 ms/op
                 createUser·p0.99:   7.915 ms/op
                 createUser·p0.999:  17.735 ms/op
                 createUser·p0.9999: 22.868 ms/op
                 createUser·p1.00:   23.527 ms/op

Iteration   2: 4.635 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   0.740 ms/op
                 createUser·p0.50:   4.489 ms/op
                 createUser·p0.90:   5.865 ms/op
                 createUser·p0.95:   6.349 ms/op
                 createUser·p0.99:   9.046 ms/op
                 createUser·p0.999:  12.780 ms/op
                 createUser·p0.9999: 27.463 ms/op
                 createUser·p1.00:   28.017 ms/op

Iteration   3: 4.392 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.943 ms/op
                 createUser·p0.50:   4.309 ms/op
                 createUser·p0.90:   5.415 ms/op
                 createUser·p0.95:   5.898 ms/op
                 createUser·p0.99:   7.291 ms/op
                 createUser·p0.999:  11.272 ms/op
                 createUser·p0.9999: 27.483 ms/op
                 createUser·p1.00:   27.689 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 212267
  mean =      4.521 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4972 
    [ 2.500,  5.000) = 158641 
    [ 5.000,  7.500) = 45727 
    [ 7.500, 10.000) = 2107 
    [10.000, 12.500) = 545 
    [12.500, 15.000) = 96 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 42 

  Percentiles, ms/op:
      p(0.0000) =      0.740 ms/op
     p(50.0000) =      4.391 ms/op
     p(90.0000) =      5.644 ms/op
     p(95.0000) =      6.119 ms/op
     p(99.0000) =      8.028 ms/op
     p(99.9000) =     13.648 ms/op
     p(99.9900) =     27.321 ms/op
     p(99.9990) =     27.874 ms/op
     p(99.9999) =     28.017 ms/op
    p(100.0000) =     28.017 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.547 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 4.696 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.325 ±(99.9%) 0.011 ms/op
Iteration   1: 4.574 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   1.157 ms/op
                 existUser·p0.50:   4.391 ms/op
                 existUser·p0.90:   5.669 ms/op
                 existUser·p0.95:   6.341 ms/op
                 existUser·p0.99:   8.913 ms/op
                 existUser·p0.999:  13.566 ms/op
                 existUser·p0.9999: 41.615 ms/op
                 existUser·p1.00:   41.746 ms/op

Iteration   2: 4.388 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.810 ms/op
                 existUser·p0.50:   4.235 ms/op
                 existUser·p0.90:   5.366 ms/op
                 existUser·p0.95:   5.857 ms/op
                 existUser·p0.99:   8.389 ms/op
                 existUser·p0.999:  15.687 ms/op
                 existUser·p0.9999: 30.367 ms/op
                 existUser·p1.00:   30.867 ms/op

Iteration   3: 4.226 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.021 ms/op
                 existUser·p0.50:   4.170 ms/op
                 existUser·p0.90:   5.259 ms/op
                 existUser·p0.95:   5.636 ms/op
                 existUser·p0.99:   7.294 ms/op
                 existUser·p0.999:  12.720 ms/op
                 existUser·p0.9999: 21.398 ms/op
                 existUser·p1.00:   22.053 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 218512
  mean =      4.392 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 177224 
    [ 5.000, 10.000) = 40331 
    [10.000, 15.000) = 798 
    [15.000, 20.000) = 78 
    [20.000, 25.000) = 17 
    [25.000, 30.000) = 18 
    [30.000, 35.000) = 18 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.810 ms/op
     p(50.0000) =      4.260 ms/op
     p(90.0000) =      5.439 ms/op
     p(95.0000) =      5.923 ms/op
     p(99.0000) =      8.348 ms/op
     p(99.9000) =     13.558 ms/op
     p(99.9900) =     41.222 ms/op
     p(99.9990) =     41.681 ms/op
     p(99.9999) =     41.746 ms/op
    p(100.0000) =     41.746 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 7.039 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 4.927 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.738 ±(99.9%) 0.016 ms/op
Iteration   1: 4.538 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.135 ms/op
                 getUser·p0.50:   4.407 ms/op
                 getUser·p0.90:   5.702 ms/op
                 getUser·p0.95:   6.316 ms/op
                 getUser·p0.99:   8.920 ms/op
                 getUser·p0.999:  12.772 ms/op
                 getUser·p0.9999: 19.235 ms/op
                 getUser·p1.00:   19.759 ms/op

Iteration   2: 4.450 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   0.919 ms/op
                 getUser·p0.50:   4.309 ms/op
                 getUser·p0.90:   5.456 ms/op
                 getUser·p0.95:   6.054 ms/op
                 getUser·p0.99:   8.471 ms/op
                 getUser·p0.999:  15.534 ms/op
                 getUser·p0.9999: 20.193 ms/op
                 getUser·p1.00:   20.808 ms/op

Iteration   3: 4.493 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.149 ms/op
                 getUser·p0.50:   4.375 ms/op
                 getUser·p0.90:   5.480 ms/op
                 getUser·p0.95:   5.898 ms/op
                 getUser·p0.99:   7.643 ms/op
                 getUser·p0.999:  12.219 ms/op
                 getUser·p0.9999: 21.230 ms/op
                 getUser·p1.00:   21.332 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 213433
  mean =      4.493 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3746 
    [ 2.500,  5.000) = 164023 
    [ 5.000,  7.500) = 42404 
    [ 7.500, 10.000) = 2239 
    [10.000, 12.500) = 714 
    [12.500, 15.000) = 130 
    [15.000, 17.500) = 91 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.919 ms/op
     p(50.0000) =      4.358 ms/op
     p(90.0000) =      5.546 ms/op
     p(95.0000) =      6.095 ms/op
     p(99.0000) =      8.405 ms/op
     p(99.9000) =     13.320 ms/op
     p(99.9900) =     20.502 ms/op
     p(99.9990) =     21.328 ms/op
     p(99.9999) =     21.332 ms/op
    p(100.0000) =     21.332 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 8.627 ±(99.9%) 0.110 ms/op
# Warmup Iteration   2: 6.749 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 6.217 ±(99.9%) 0.028 ms/op
Iteration   1: 6.025 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.475 ms/op
                 listUser·p0.50:   5.685 ms/op
                 listUser·p0.90:   7.954 ms/op
                 listUser·p0.95:   9.060 ms/op
                 listUser·p0.99:   11.764 ms/op
                 listUser·p0.999:  18.645 ms/op
                 listUser·p0.9999: 24.379 ms/op
                 listUser·p1.00:   24.871 ms/op

Iteration   2: 5.978 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   2.589 ms/op
                 listUser·p0.50:   5.652 ms/op
                 listUser·p0.90:   7.725 ms/op
                 listUser·p0.95:   8.765 ms/op
                 listUser·p0.99:   12.075 ms/op
                 listUser·p0.999:  18.712 ms/op
                 listUser·p0.9999: 22.631 ms/op
                 listUser·p1.00:   22.872 ms/op

Iteration   3: 5.907 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   1.513 ms/op
                 listUser·p0.50:   5.546 ms/op
                 listUser·p0.90:   7.799 ms/op
                 listUser·p0.95:   8.946 ms/op
                 listUser·p0.99:   12.152 ms/op
                 listUser·p0.999:  27.226 ms/op
                 listUser·p0.9999: 31.900 ms/op
                 listUser·p1.00:   33.522 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 160706
  mean =      5.969 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 72 
    [ 2.500,  5.000) = 38639 
    [ 5.000,  7.500) = 102199 
    [ 7.500, 10.000) = 15434 
    [10.000, 12.500) = 3114 
    [12.500, 15.000) = 717 
    [15.000, 17.500) = 218 
    [17.500, 20.000) = 169 
    [20.000, 22.500) = 58 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 13 
    [27.500, 30.000) = 28 
    [30.000, 32.500) = 19 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.475 ms/op
     p(50.0000) =      5.628 ms/op
     p(90.0000) =      7.823 ms/op
     p(95.0000) =      8.913 ms/op
     p(99.0000) =     11.977 ms/op
     p(99.9000) =     19.562 ms/op
     p(99.9900) =     30.570 ms/op
     p(99.9990) =     33.422 ms/op
     p(99.9999) =     33.522 ms/op
    p(100.0000) =     33.522 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   6.847 ± 1.720  ops/ms
ClientGrpc.existUser                       thrpt       3   7.705 ± 1.806  ops/ms
ClientGrpc.getUser                         thrpt       3   7.128 ± 1.576  ops/ms
ClientGrpc.listUser                        thrpt       3   5.317 ± 2.253  ops/ms
ClientGrpc.createUser                       avgt       3   4.550 ± 1.699   ms/op
ClientGrpc.existUser                        avgt       3   4.258 ± 2.295   ms/op
ClientGrpc.getUser                          avgt       3   4.473 ± 1.367   ms/op
ClientGrpc.listUser                         avgt       3   5.933 ± 4.295   ms/op
ClientGrpc.createUser                     sample  212267   4.521 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.740           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.391           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.644           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.119           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           8.028           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.648           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          27.321           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          28.017           ms/op
ClientGrpc.existUser                      sample  218512   4.392 ± 0.008   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.810           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.260           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.439           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.923           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           8.348           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          13.558           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          41.222           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          41.746           ms/op
ClientGrpc.getUser                        sample  213433   4.493 ± 0.008   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.919           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.358           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.546           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.095           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           8.405           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          13.320           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.502           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.332           ms/op
ClientGrpc.listUser                       sample  160706   5.969 ± 0.014   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.475           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.628           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.823           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.913           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          11.977           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.562           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          30.570           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          33.522           ms/op
