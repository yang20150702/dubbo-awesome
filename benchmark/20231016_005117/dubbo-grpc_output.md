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
# Warmup Iteration   1: 2.385 ops/ms
# Warmup Iteration   2: 6.622 ops/ms
# Warmup Iteration   3: 8.170 ops/ms
Iteration   1: 8.496 ops/ms
Iteration   2: 8.339 ops/ms
Iteration   3: 8.659 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.498 ±(99.9%) 2.925 ops/ms [Average]
  (min, avg, max) = (8.339, 8.498, 8.659), stdev = 0.160
  CI (99.9%): [5.573, 11.423] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.437 ops/ms
# Warmup Iteration   2: 8.285 ops/ms
# Warmup Iteration   3: 9.133 ops/ms
Iteration   1: 9.244 ops/ms
Iteration   2: 9.205 ops/ms
Iteration   3: 8.947 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.132 ±(99.9%) 2.949 ops/ms [Average]
  (min, avg, max) = (8.947, 9.132, 9.244), stdev = 0.162
  CI (99.9%): [6.183, 12.080] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 4.359 ops/ms
# Warmup Iteration   2: 7.744 ops/ms
# Warmup Iteration   3: 8.487 ops/ms
Iteration   1: 8.363 ops/ms
Iteration   2: 8.373 ops/ms
Iteration   3: 8.081 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.272 ±(99.9%) 3.025 ops/ms [Average]
  (min, avg, max) = (8.081, 8.272, 8.373), stdev = 0.166
  CI (99.9%): [5.247, 11.298] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.604 ops/ms
# Warmup Iteration   2: 5.768 ops/ms
# Warmup Iteration   3: 6.396 ops/ms
Iteration   1: 6.925 ops/ms
Iteration   2: 6.889 ops/ms
Iteration   3: 6.673 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.829 ±(99.9%) 2.484 ops/ms [Average]
  (min, avg, max) = (6.673, 6.829, 6.925), stdev = 0.136
  CI (99.9%): [4.345, 9.313] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.881 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.023 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.858 ±(99.9%) 0.008 ms/op
Iteration   1: 3.763 ±(99.9%) 0.005 ms/op
Iteration   2: 3.768 ±(99.9%) 0.004 ms/op
Iteration   3: 3.745 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.759 ±(99.9%) 0.222 ms/op [Average]
  (min, avg, max) = (3.745, 3.759, 3.768), stdev = 0.012
  CI (99.9%): [3.537, 3.981] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 5.160 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.627 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.431 ±(99.9%) 0.004 ms/op
Iteration   1: 3.468 ±(99.9%) 0.003 ms/op
Iteration   2: 3.298 ±(99.9%) 0.005 ms/op
Iteration   3: 3.522 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.429 ±(99.9%) 2.132 ms/op [Average]
  (min, avg, max) = (3.298, 3.429, 3.522), stdev = 0.117
  CI (99.9%): [1.297, 5.562] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 5.479 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.932 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.791 ±(99.9%) 0.005 ms/op
Iteration   1: 3.845 ±(99.9%) 0.004 ms/op
Iteration   2: 3.715 ±(99.9%) 0.008 ms/op
Iteration   3: 3.613 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.724 ±(99.9%) 2.119 ms/op [Average]
  (min, avg, max) = (3.613, 3.724, 3.845), stdev = 0.116
  CI (99.9%): [1.605, 5.844] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 6.732 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 5.237 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 4.835 ±(99.9%) 0.009 ms/op
Iteration   1: 4.704 ±(99.9%) 0.012 ms/op
Iteration   2: 4.757 ±(99.9%) 0.012 ms/op
Iteration   3: 4.642 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.701 ±(99.9%) 1.052 ms/op [Average]
  (min, avg, max) = (4.642, 4.701, 4.757), stdev = 0.058
  CI (99.9%): [3.649, 5.753] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.946 ±(99.9%) 0.071 ms/op
# Warmup Iteration   2: 3.945 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.011 ±(99.9%) 0.013 ms/op
Iteration   1: 3.861 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.933 ms/op
                 createUser·p0.50:   3.723 ms/op
                 createUser·p0.90:   4.981 ms/op
                 createUser·p0.95:   5.431 ms/op
                 createUser·p0.99:   7.463 ms/op
                 createUser·p0.999:  16.320 ms/op
                 createUser·p0.9999: 21.823 ms/op
                 createUser·p1.00:   26.313 ms/op

Iteration   2: 3.718 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.659 ms/op
                 createUser·p0.50:   3.580 ms/op
                 createUser·p0.90:   4.669 ms/op
                 createUser·p0.95:   5.095 ms/op
                 createUser·p0.99:   6.726 ms/op
                 createUser·p0.999:  12.485 ms/op
                 createUser·p0.9999: 37.736 ms/op
                 createUser·p1.00:   40.960 ms/op

Iteration   3: 3.757 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.772 ms/op
                 createUser·p0.50:   3.650 ms/op
                 createUser·p0.90:   4.825 ms/op
                 createUser·p0.95:   5.226 ms/op
                 createUser·p0.99:   6.906 ms/op
                 createUser·p0.999:  16.040 ms/op
                 createUser·p0.9999: 22.707 ms/op
                 createUser·p1.00:   24.871 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 254082
  mean =      3.778 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 234828 
    [ 5.000, 10.000) = 18668 
    [10.000, 15.000) = 340 
    [15.000, 20.000) = 116 
    [20.000, 25.000) = 97 
    [25.000, 30.000) = 1 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 30 
    [40.000, 45.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.659 ms/op
     p(50.0000) =      3.645 ms/op
     p(90.0000) =      4.833 ms/op
     p(95.0000) =      5.259 ms/op
     p(99.0000) =      7.037 ms/op
     p(99.9000) =     14.645 ms/op
     p(99.9900) =     35.848 ms/op
     p(99.9990) =     39.787 ms/op
     p(99.9999) =     40.960 ms/op
    p(100.0000) =     40.960 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.915 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 4.167 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.832 ±(99.9%) 0.013 ms/op
Iteration   1: 3.780 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.434 ms/op
                 existUser·p0.50:   3.662 ms/op
                 existUser·p0.90:   4.727 ms/op
                 existUser·p0.95:   5.210 ms/op
                 existUser·p0.99:   7.258 ms/op
                 existUser·p0.999:  13.696 ms/op
                 existUser·p0.9999: 19.379 ms/op
                 existUser·p1.00:   20.578 ms/op

Iteration   2: 3.618 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.807 ms/op
                 existUser·p0.50:   3.506 ms/op
                 existUser·p0.90:   4.375 ms/op
                 existUser·p0.95:   4.838 ms/op
                 existUser·p0.99:   6.750 ms/op
                 existUser·p0.999:  11.460 ms/op
                 existUser·p0.9999: 29.693 ms/op
                 existUser·p1.00:   30.278 ms/op

Iteration   3: 3.466 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.574 ms/op
                 existUser·p0.50:   3.342 ms/op
                 existUser·p0.90:   4.260 ms/op
                 existUser·p0.95:   4.710 ms/op
                 existUser·p0.99:   6.602 ms/op
                 existUser·p0.999:  12.381 ms/op
                 existUser·p0.9999: 22.118 ms/op
                 existUser·p1.00:   22.381 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 265443
  mean =      3.617 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8316 
    [ 2.500,  5.000) = 244748 
    [ 5.000,  7.500) = 10603 
    [ 7.500, 10.000) = 1196 
    [10.000, 12.500) = 329 
    [12.500, 15.000) = 55 
    [15.000, 17.500) = 97 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 21 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.434 ms/op
     p(50.0000) =      3.494 ms/op
     p(90.0000) =      4.473 ms/op
     p(95.0000) =      4.948 ms/op
     p(99.0000) =      6.857 ms/op
     p(99.9000) =     12.091 ms/op
     p(99.9900) =     22.199 ms/op
     p(99.9990) =     30.104 ms/op
     p(99.9999) =     30.278 ms/op
    p(100.0000) =     30.278 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.516 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 4.005 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.795 ±(99.9%) 0.011 ms/op
Iteration   1: 3.655 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.104 ms/op
                 getUser·p0.50:   3.551 ms/op
                 getUser·p0.90:   4.481 ms/op
                 getUser·p0.95:   4.940 ms/op
                 getUser·p0.99:   6.693 ms/op
                 getUser·p0.999:  14.123 ms/op
                 getUser·p0.9999: 15.528 ms/op
                 getUser·p1.00:   18.514 ms/op

Iteration   2: 3.671 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.476 ms/op
                 getUser·p0.50:   3.572 ms/op
                 getUser·p0.90:   4.563 ms/op
                 getUser·p0.95:   4.997 ms/op
                 getUser·p0.99:   6.595 ms/op
                 getUser·p0.999:  12.132 ms/op
                 getUser·p0.9999: 21.336 ms/op
                 getUser·p1.00:   22.970 ms/op

Iteration   3: 3.742 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.807 ms/op
                 getUser·p0.50:   3.625 ms/op
                 getUser·p0.90:   4.686 ms/op
                 getUser·p0.95:   5.071 ms/op
                 getUser·p0.99:   6.816 ms/op
                 getUser·p0.999:  13.765 ms/op
                 getUser·p0.9999: 26.932 ms/op
                 getUser·p1.00:   27.329 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 260137
  mean =      3.689 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9387 
    [ 2.500,  5.000) = 237622 
    [ 5.000,  7.500) = 11495 
    [ 7.500, 10.000) = 1062 
    [10.000, 12.500) = 260 
    [12.500, 15.000) = 185 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.476 ms/op
     p(50.0000) =      3.580 ms/op
     p(90.0000) =      4.588 ms/op
     p(95.0000) =      5.005 ms/op
     p(99.0000) =      6.685 ms/op
     p(99.9000) =     13.330 ms/op
     p(99.9900) =     25.067 ms/op
     p(99.9990) =     27.263 ms/op
     p(99.9999) =     27.329 ms/op
    p(100.0000) =     27.329 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 7.655 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 4.936 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.731 ±(99.9%) 0.017 ms/op
Iteration   1: 4.698 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.100 ms/op
                 listUser·p0.50:   4.456 ms/op
                 listUser·p0.90:   6.201 ms/op
                 listUser·p0.95:   7.012 ms/op
                 listUser·p0.99:   9.126 ms/op
                 listUser·p0.999:  17.170 ms/op
                 listUser·p0.9999: 19.181 ms/op
                 listUser·p1.00:   23.953 ms/op

Iteration   2: 4.625 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.110 ms/op
                 listUser·p0.50:   4.407 ms/op
                 listUser·p0.90:   5.865 ms/op
                 listUser·p0.95:   6.939 ms/op
                 listUser·p0.99:   8.978 ms/op
                 listUser·p0.999:  19.882 ms/op
                 listUser·p0.9999: 22.580 ms/op
                 listUser·p1.00:   23.265 ms/op

Iteration   3: 4.750 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.186 ms/op
                 listUser·p0.50:   4.481 ms/op
                 listUser·p0.90:   6.357 ms/op
                 listUser·p0.95:   7.201 ms/op
                 listUser·p0.99:   9.077 ms/op
                 listUser·p0.999:  21.864 ms/op
                 listUser·p0.9999: 25.895 ms/op
                 listUser·p1.00:   26.509 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 204846
  mean =      4.690 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 900 
    [ 2.500,  5.000) = 150983 
    [ 5.000,  7.500) = 45909 
    [ 7.500, 10.000) = 6011 
    [10.000, 12.500) = 585 
    [12.500, 15.000) = 81 
    [15.000, 17.500) = 70 
    [17.500, 20.000) = 110 
    [20.000, 22.500) = 136 
    [22.500, 25.000) = 52 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      1.100 ms/op
     p(50.0000) =      4.448 ms/op
     p(90.0000) =      6.169 ms/op
     p(95.0000) =      7.062 ms/op
     p(99.0000) =      9.060 ms/op
     p(99.9000) =     19.830 ms/op
     p(99.9900) =     24.543 ms/op
     p(99.9990) =     26.277 ms/op
     p(99.9999) =     26.509 ms/op
    p(100.0000) =     26.509 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.498 ± 2.925  ops/ms
ClientGrpc.existUser                       thrpt       3   9.132 ± 2.949  ops/ms
ClientGrpc.getUser                         thrpt       3   8.272 ± 3.025  ops/ms
ClientGrpc.listUser                        thrpt       3   6.829 ± 2.484  ops/ms
ClientGrpc.createUser                       avgt       3   3.759 ± 0.222   ms/op
ClientGrpc.existUser                        avgt       3   3.429 ± 2.132   ms/op
ClientGrpc.getUser                          avgt       3   3.724 ± 2.119   ms/op
ClientGrpc.listUser                         avgt       3   4.701 ± 1.052   ms/op
ClientGrpc.createUser                     sample  254082   3.778 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.659           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.645           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.833           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.259           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.037           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          14.645           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          35.848           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          40.960           ms/op
ClientGrpc.existUser                      sample  265443   3.617 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.434           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.494           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.473           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.948           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.857           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.091           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          22.199           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          30.278           ms/op
ClientGrpc.getUser                        sample  260137   3.689 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.476           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.580           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.588           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.005           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.685           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          13.330           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          25.067           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          27.329           ms/op
ClientGrpc.listUser                       sample  204846   4.690 ± 0.010   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.100           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.448           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.169           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.062           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.060           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.830           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.543           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.509           ms/op
