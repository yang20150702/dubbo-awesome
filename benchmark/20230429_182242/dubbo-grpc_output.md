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
# Warmup Iteration   1: 3.008 ops/ms
# Warmup Iteration   2: 6.732 ops/ms
# Warmup Iteration   3: 8.251 ops/ms
Iteration   1: 8.571 ops/ms
Iteration   2: 8.826 ops/ms
Iteration   3: 8.740 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.712 ±(99.9%) 2.373 ops/ms [Average]
  (min, avg, max) = (8.571, 8.712, 8.826), stdev = 0.130
  CI (99.9%): [6.339, 11.085] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.824 ops/ms
# Warmup Iteration   2: 8.524 ops/ms
# Warmup Iteration   3: 9.223 ops/ms
Iteration   1: 9.140 ops/ms
Iteration   2: 9.090 ops/ms
Iteration   3: 8.955 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.062 ±(99.9%) 1.743 ops/ms [Average]
  (min, avg, max) = (8.955, 9.062, 9.140), stdev = 0.096
  CI (99.9%): [7.319, 10.805] (assumes normal distribution)


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
# Warmup Iteration   1: 5.311 ops/ms
# Warmup Iteration   2: 8.132 ops/ms
# Warmup Iteration   3: 8.522 ops/ms
Iteration   1: 8.543 ops/ms
Iteration   2: 8.413 ops/ms
Iteration   3: 8.551 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.502 ±(99.9%) 1.415 ops/ms [Average]
  (min, avg, max) = (8.413, 8.502, 8.551), stdev = 0.078
  CI (99.9%): [7.087, 9.918] (assumes normal distribution)


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
# Warmup Iteration   1: 5.105 ops/ms
# Warmup Iteration   2: 6.285 ops/ms
# Warmup Iteration   3: 6.930 ops/ms
Iteration   1: 6.836 ops/ms
Iteration   2: 6.744 ops/ms
Iteration   3: 6.688 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.756 ±(99.9%) 1.356 ops/ms [Average]
  (min, avg, max) = (6.688, 6.756, 6.836), stdev = 0.074
  CI (99.9%): [5.400, 8.111] (assumes normal distribution)


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
# Warmup Iteration   1: 5.441 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.885 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.720 ±(99.9%) 0.013 ms/op
Iteration   1: 3.635 ±(99.9%) 0.003 ms/op
Iteration   2: 3.666 ±(99.9%) 0.003 ms/op
Iteration   3: 3.669 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.657 ±(99.9%) 0.342 ms/op [Average]
  (min, avg, max) = (3.635, 3.657, 3.669), stdev = 0.019
  CI (99.9%): [3.315, 3.998] (assumes normal distribution)


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
# Warmup Iteration   1: 4.991 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.728 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.545 ±(99.9%) 0.003 ms/op
Iteration   1: 3.469 ±(99.9%) 0.003 ms/op
Iteration   2: 3.462 ±(99.9%) 0.003 ms/op
Iteration   3: 3.391 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.441 ±(99.9%) 0.788 ms/op [Average]
  (min, avg, max) = (3.391, 3.441, 3.469), stdev = 0.043
  CI (99.9%): [2.653, 4.229] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.345 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.899 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.846 ±(99.9%) 0.003 ms/op
Iteration   1: 3.573 ±(99.9%) 0.003 ms/op
Iteration   2: 3.577 ±(99.9%) 0.003 ms/op
Iteration   3: 3.692 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.614 ±(99.9%) 1.230 ms/op [Average]
  (min, avg, max) = (3.573, 3.614, 3.692), stdev = 0.067
  CI (99.9%): [2.384, 4.844] (assumes normal distribution)


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
# Warmup Iteration   1: 6.808 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.892 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.670 ±(99.9%) 0.009 ms/op
Iteration   1: 4.808 ±(99.9%) 0.015 ms/op
Iteration   2: 4.642 ±(99.9%) 0.017 ms/op
Iteration   3: 4.655 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.702 ±(99.9%) 1.682 ms/op [Average]
  (min, avg, max) = (4.642, 4.702, 4.808), stdev = 0.092
  CI (99.9%): [3.020, 6.383] (assumes normal distribution)


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
# Warmup Iteration   1: 5.321 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.852 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.638 ±(99.9%) 0.009 ms/op
Iteration   1: 3.608 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.941 ms/op
                 createUser·p0.50:   3.568 ms/op
                 createUser·p0.90:   4.260 ms/op
                 createUser·p0.95:   4.637 ms/op
                 createUser·p0.99:   5.759 ms/op
                 createUser·p0.999:  14.489 ms/op
                 createUser·p0.9999: 19.702 ms/op
                 createUser·p1.00:   20.742 ms/op

Iteration   2: 3.636 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.608 ms/op
                 createUser·p0.50:   3.625 ms/op
                 createUser·p0.90:   4.415 ms/op
                 createUser·p0.95:   4.719 ms/op
                 createUser·p0.99:   5.939 ms/op
                 createUser·p0.999:  9.288 ms/op
                 createUser·p0.9999: 19.503 ms/op
                 createUser·p1.00:   21.266 ms/op

Iteration   3: 3.654 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.866 ms/op
                 createUser·p0.50:   3.596 ms/op
                 createUser·p0.90:   4.366 ms/op
                 createUser·p0.95:   4.702 ms/op
                 createUser·p0.99:   5.792 ms/op
                 createUser·p0.999:  17.698 ms/op
                 createUser·p0.9999: 27.427 ms/op
                 createUser·p1.00:   27.656 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 264129
  mean =      3.633 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13064 
    [ 2.500,  5.000) = 243744 
    [ 5.000,  7.500) = 6431 
    [ 7.500, 10.000) = 545 
    [10.000, 12.500) = 90 
    [12.500, 15.000) = 53 
    [15.000, 17.500) = 45 
    [17.500, 20.000) = 85 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.608 ms/op
     p(50.0000) =      3.596 ms/op
     p(90.0000) =      4.358 ms/op
     p(95.0000) =      4.694 ms/op
     p(99.0000) =      5.825 ms/op
     p(99.9000) =     11.104 ms/op
     p(99.9900) =     26.272 ms/op
     p(99.9990) =     27.593 ms/op
     p(99.9999) =     27.656 ms/op
    p(100.0000) =     27.656 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.900 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.727 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.629 ±(99.9%) 0.010 ms/op
Iteration   1: 3.456 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.666 ms/op
                 existUser·p0.50:   3.441 ms/op
                 existUser·p0.90:   4.174 ms/op
                 existUser·p0.95:   4.579 ms/op
                 existUser·p0.99:   5.808 ms/op
                 existUser·p0.999:  12.997 ms/op
                 existUser·p0.9999: 26.613 ms/op
                 existUser·p1.00:   27.460 ms/op

Iteration   2: 3.447 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.839 ms/op
                 existUser·p0.50:   3.428 ms/op
                 existUser·p0.90:   3.981 ms/op
                 existUser·p0.95:   4.260 ms/op
                 existUser·p0.99:   5.276 ms/op
                 existUser·p0.999:  11.308 ms/op
                 existUser·p0.9999: 17.348 ms/op
                 existUser·p1.00:   19.694 ms/op

Iteration   3: 3.356 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.786 ms/op
                 existUser·p0.50:   3.391 ms/op
                 existUser·p0.90:   3.965 ms/op
                 existUser·p0.95:   4.284 ms/op
                 existUser·p0.99:   5.513 ms/op
                 existUser·p0.999:  9.011 ms/op
                 existUser·p0.9999: 22.182 ms/op
                 existUser·p1.00:   22.643 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 280670
  mean =      3.419 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20382 
    [ 2.500,  5.000) = 254723 
    [ 5.000,  7.500) = 4841 
    [ 7.500, 10.000) = 426 
    [10.000, 12.500) = 67 
    [12.500, 15.000) = 63 
    [15.000, 17.500) = 67 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.666 ms/op
     p(50.0000) =      3.420 ms/op
     p(90.0000) =      4.030 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      5.571 ms/op
     p(99.9000) =     10.721 ms/op
     p(99.9900) =     25.461 ms/op
     p(99.9990) =     27.400 ms/op
     p(99.9999) =     27.460 ms/op
    p(100.0000) =     27.460 ms/op


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
# Warmup Iteration   1: 5.481 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 3.918 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.653 ±(99.9%) 0.009 ms/op
Iteration   1: 3.832 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.184 ms/op
                 getUser·p0.50:   3.744 ms/op
                 getUser·p0.90:   4.522 ms/op
                 getUser·p0.95:   4.841 ms/op
                 getUser·p0.99:   6.636 ms/op
                 getUser·p0.999:  12.916 ms/op
                 getUser·p0.9999: 15.270 ms/op
                 getUser·p1.00:   15.417 ms/op

Iteration   2: 3.604 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.059 ms/op
                 getUser·p0.50:   3.576 ms/op
                 getUser·p0.90:   4.067 ms/op
                 getUser·p0.95:   4.342 ms/op
                 getUser·p0.99:   5.390 ms/op
                 getUser·p0.999:  8.169 ms/op
                 getUser·p0.9999: 19.202 ms/op
                 getUser·p1.00:   19.694 ms/op

Iteration   3: 3.651 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.683 ms/op
                 getUser·p0.50:   3.596 ms/op
                 getUser·p0.90:   4.276 ms/op
                 getUser·p0.95:   4.596 ms/op
                 getUser·p0.99:   5.718 ms/op
                 getUser·p0.999:  8.980 ms/op
                 getUser·p0.9999: 20.398 ms/op
                 getUser·p1.00:   22.544 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 260002
  mean =      3.693 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4101 
    [ 2.500,  5.000) = 249416 
    [ 5.000,  7.500) = 5599 
    [ 7.500, 10.000) = 601 
    [10.000, 12.500) = 99 
    [12.500, 15.000) = 68 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.683 ms/op
     p(50.0000) =      3.621 ms/op
     p(90.0000) =      4.325 ms/op
     p(95.0000) =      4.628 ms/op
     p(99.0000) =      5.857 ms/op
     p(99.9000) =     11.256 ms/op
     p(99.9900) =     20.152 ms/op
     p(99.9990) =     20.985 ms/op
     p(99.9999) =     22.544 ms/op
    p(100.0000) =     22.544 ms/op


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
# Warmup Iteration   1: 6.643 ±(99.9%) 0.071 ms/op
# Warmup Iteration   2: 5.129 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.705 ±(99.9%) 0.016 ms/op
Iteration   1: 4.693 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.534 ms/op
                 listUser·p0.50:   4.506 ms/op
                 listUser·p0.90:   5.677 ms/op
                 listUser·p0.95:   6.603 ms/op
                 listUser·p0.99:   8.192 ms/op
                 listUser·p0.999:  16.412 ms/op
                 listUser·p0.9999: 31.857 ms/op
                 listUser·p1.00:   32.178 ms/op

Iteration   2: 4.722 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.692 ms/op
                 listUser·p0.50:   4.514 ms/op
                 listUser·p0.90:   5.923 ms/op
                 listUser·p0.95:   6.889 ms/op
                 listUser·p0.99:   8.487 ms/op
                 listUser·p0.999:  16.433 ms/op
                 listUser·p0.9999: 19.497 ms/op
                 listUser·p1.00:   22.643 ms/op

Iteration   3: 4.721 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.081 ms/op
                 listUser·p0.50:   4.481 ms/op
                 listUser·p0.90:   6.095 ms/op
                 listUser·p0.95:   6.857 ms/op
                 listUser·p0.99:   8.405 ms/op
                 listUser·p0.999:  21.430 ms/op
                 listUser·p0.9999: 38.811 ms/op
                 listUser·p1.00:   39.387 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 203724
  mean =      4.712 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 359 
    [ 2.500,  5.000) = 158294 
    [ 5.000,  7.500) = 40104 
    [ 7.500, 10.000) = 4367 
    [10.000, 12.500) = 242 
    [12.500, 15.000) = 110 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 78 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 10 
    [27.500, 30.000) = 14 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      1.081 ms/op
     p(50.0000) =      4.506 ms/op
     p(90.0000) =      5.915 ms/op
     p(95.0000) =      6.791 ms/op
     p(99.0000) =      8.356 ms/op
     p(99.9000) =     18.073 ms/op
     p(99.9900) =     36.217 ms/op
     p(99.9990) =     39.251 ms/op
     p(99.9999) =     39.387 ms/op
    p(100.0000) =     39.387 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.712 ± 2.373  ops/ms
ClientGrpc.existUser                       thrpt       3   9.062 ± 1.743  ops/ms
ClientGrpc.getUser                         thrpt       3   8.502 ± 1.415  ops/ms
ClientGrpc.listUser                        thrpt       3   6.756 ± 1.356  ops/ms
ClientGrpc.createUser                       avgt       3   3.657 ± 0.342   ms/op
ClientGrpc.existUser                        avgt       3   3.441 ± 0.788   ms/op
ClientGrpc.getUser                          avgt       3   3.614 ± 1.230   ms/op
ClientGrpc.listUser                         avgt       3   4.702 ± 1.682   ms/op
ClientGrpc.createUser                     sample  264129   3.633 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.608           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.596           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.358           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.694           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.825           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.104           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          26.272           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.656           ms/op
ClientGrpc.existUser                      sample  280670   3.419 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.666           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.420           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.030           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.383           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.571           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.721           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          25.461           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          27.460           ms/op
ClientGrpc.getUser                        sample  260002   3.693 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.683           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.621           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.325           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.628           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.857           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.256           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.152           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.544           ms/op
ClientGrpc.listUser                       sample  203724   4.712 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.081           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.506           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.915           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.791           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.356           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.073           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          36.217           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          39.387           ms/op
