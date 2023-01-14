# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.528 ops/ms
# Warmup Iteration   2: 7.100 ops/ms
# Warmup Iteration   3: 8.572 ops/ms
Iteration   1: 8.668 ops/ms
Iteration   2: 8.476 ops/ms
Iteration   3: 8.496 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.547 ±(99.9%) 1.926 ops/ms [Average]
  (min, avg, max) = (8.476, 8.547, 8.668), stdev = 0.106
  CI (99.9%): [6.621, 10.472] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 5.984 ops/ms
# Warmup Iteration   2: 8.698 ops/ms
# Warmup Iteration   3: 9.030 ops/ms
Iteration   1: 8.912 ops/ms
Iteration   2: 9.207 ops/ms
Iteration   3: 9.331 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.150 ±(99.9%) 3.926 ops/ms [Average]
  (min, avg, max) = (8.912, 9.150, 9.331), stdev = 0.215
  CI (99.9%): [5.224, 13.076] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.722 ops/ms
# Warmup Iteration   2: 8.356 ops/ms
# Warmup Iteration   3: 9.094 ops/ms
Iteration   1: 8.777 ops/ms
Iteration   2: 8.772 ops/ms
Iteration   3: 8.638 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.729 ±(99.9%) 1.444 ops/ms [Average]
  (min, avg, max) = (8.638, 8.729, 8.777), stdev = 0.079
  CI (99.9%): [7.285, 10.173] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 4.675 ops/ms
# Warmup Iteration   2: 6.482 ops/ms
# Warmup Iteration   3: 6.821 ops/ms
Iteration   1: 6.745 ops/ms
Iteration   2: 6.676 ops/ms
Iteration   3: 6.788 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.736 ±(99.9%) 1.028 ops/ms [Average]
  (min, avg, max) = (6.676, 6.736, 6.788), stdev = 0.056
  CI (99.9%): [5.708, 7.765] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 5.243 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.892 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.763 ±(99.9%) 0.002 ms/op
Iteration   1: 3.730 ±(99.9%) 0.003 ms/op
Iteration   2: 3.795 ±(99.9%) 0.002 ms/op
Iteration   3: 3.730 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.752 ±(99.9%) 0.688 ms/op [Average]
  (min, avg, max) = (3.730, 3.752, 3.795), stdev = 0.038
  CI (99.9%): [3.064, 4.440] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 5.130 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.660 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.566 ±(99.9%) 0.003 ms/op
Iteration   1: 3.576 ±(99.9%) 0.003 ms/op
Iteration   2: 3.601 ±(99.9%) 0.002 ms/op
Iteration   3: 3.524 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.567 ±(99.9%) 0.714 ms/op [Average]
  (min, avg, max) = (3.524, 3.567, 3.601), stdev = 0.039
  CI (99.9%): [2.853, 4.280] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 5.023 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.862 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.723 ±(99.9%) 0.003 ms/op
Iteration   1: 3.728 ±(99.9%) 0.002 ms/op
Iteration   2: 3.645 ±(99.9%) 0.004 ms/op
Iteration   3: 3.690 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.688 ±(99.9%) 0.764 ms/op [Average]
  (min, avg, max) = (3.645, 3.688, 3.728), stdev = 0.042
  CI (99.9%): [2.924, 4.452] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 7.505 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.990 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.908 ±(99.9%) 0.012 ms/op
Iteration   1: 4.721 ±(99.9%) 0.008 ms/op
Iteration   2: 4.731 ±(99.9%) 0.019 ms/op
Iteration   3: 4.681 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.711 ±(99.9%) 0.483 ms/op [Average]
  (min, avg, max) = (4.681, 4.711, 4.731), stdev = 0.026
  CI (99.9%): [4.228, 5.194] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 5.364 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 3.831 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.871 ±(99.9%) 0.009 ms/op
Iteration   1: 3.683 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.995 ms/op
                 createUser·p0.50:   3.621 ms/op
                 createUser·p0.90:   4.481 ms/op
                 createUser·p0.95:   4.776 ms/op
                 createUser·p0.99:   5.825 ms/op
                 createUser·p0.999:  13.631 ms/op
                 createUser·p0.9999: 19.343 ms/op
                 createUser·p1.00:   19.661 ms/op

Iteration   2: 3.691 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.124 ms/op
                 createUser·p0.50:   3.633 ms/op
                 createUser·p0.90:   4.604 ms/op
                 createUser·p0.95:   4.907 ms/op
                 createUser·p0.99:   5.903 ms/op
                 createUser·p0.999:  12.660 ms/op
                 createUser·p0.9999: 15.112 ms/op
                 createUser·p1.00:   17.072 ms/op

Iteration   3: 3.740 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.866 ms/op
                 createUser·p0.50:   3.666 ms/op
                 createUser·p0.90:   4.555 ms/op
                 createUser·p0.95:   4.833 ms/op
                 createUser·p0.99:   5.841 ms/op
                 createUser·p0.999:  13.098 ms/op
                 createUser·p0.9999: 29.004 ms/op
                 createUser·p1.00:   29.655 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 259042
  mean =      3.705 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7861 
    [ 2.500,  5.000) = 242156 
    [ 5.000,  7.500) = 8166 
    [ 7.500, 10.000) = 449 
    [10.000, 12.500) = 113 
    [12.500, 15.000) = 176 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.866 ms/op
     p(50.0000) =      3.637 ms/op
     p(90.0000) =      4.547 ms/op
     p(95.0000) =      4.841 ms/op
     p(99.0000) =      5.857 ms/op
     p(99.9000) =     12.894 ms/op
     p(99.9900) =     27.115 ms/op
     p(99.9990) =     29.499 ms/op
     p(99.9999) =     29.655 ms/op
    p(100.0000) =     29.655 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.706 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.764 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.607 ±(99.9%) 0.010 ms/op
Iteration   1: 3.604 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.759 ms/op
                 existUser·p0.50:   3.559 ms/op
                 existUser·p0.90:   4.456 ms/op
                 existUser·p0.95:   4.727 ms/op
                 existUser·p0.99:   5.620 ms/op
                 existUser·p0.999:  11.010 ms/op
                 existUser·p0.9999: 13.933 ms/op
                 existUser·p1.00:   14.270 ms/op

Iteration   2: 3.541 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.733 ms/op
                 existUser·p0.50:   3.514 ms/op
                 existUser·p0.90:   4.407 ms/op
                 existUser·p0.95:   4.694 ms/op
                 existUser·p0.99:   5.521 ms/op
                 existUser·p0.999:  7.755 ms/op
                 existUser·p0.9999: 24.772 ms/op
                 existUser·p1.00:   25.330 ms/op

Iteration   3: 3.580 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.738 ms/op
                 existUser·p0.50:   3.523 ms/op
                 existUser·p0.90:   4.334 ms/op
                 existUser·p0.95:   4.710 ms/op
                 existUser·p0.99:   6.488 ms/op
                 existUser·p0.999:  11.871 ms/op
                 existUser·p0.9999: 25.892 ms/op
                 existUser·p1.00:   26.411 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 268500
  mean =      3.575 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13802 
    [ 2.500,  5.000) = 247313 
    [ 5.000,  7.500) = 6489 
    [ 7.500, 10.000) = 500 
    [10.000, 12.500) = 247 
    [12.500, 15.000) = 85 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.733 ms/op
     p(50.0000) =      3.531 ms/op
     p(90.0000) =      4.407 ms/op
     p(95.0000) =      4.710 ms/op
     p(99.0000) =      5.792 ms/op
     p(99.9000) =     10.969 ms/op
     p(99.9900) =     25.082 ms/op
     p(99.9990) =     26.301 ms/op
     p(99.9999) =     26.411 ms/op
    p(100.0000) =     26.411 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.050 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.750 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.666 ±(99.9%) 0.009 ms/op
Iteration   1: 3.691 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.705 ms/op
                 getUser·p0.50:   3.654 ms/op
                 getUser·p0.90:   4.538 ms/op
                 getUser·p0.95:   4.833 ms/op
                 getUser·p0.99:   5.890 ms/op
                 getUser·p0.999:  9.486 ms/op
                 getUser·p0.9999: 18.940 ms/op
                 getUser·p1.00:   19.530 ms/op

Iteration   2: 3.654 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.795 ms/op
                 getUser·p0.50:   3.629 ms/op
                 getUser·p0.90:   4.489 ms/op
                 getUser·p0.95:   4.801 ms/op
                 getUser·p0.99:   5.767 ms/op
                 getUser·p0.999:  7.929 ms/op
                 getUser·p0.9999: 17.940 ms/op
                 getUser·p1.00:   18.383 ms/op

Iteration   3: 3.750 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.931 ms/op
                 getUser·p0.50:   3.682 ms/op
                 getUser·p0.90:   4.588 ms/op
                 getUser·p0.95:   4.866 ms/op
                 getUser·p0.99:   6.103 ms/op
                 getUser·p0.999:  9.917 ms/op
                 getUser·p0.9999: 26.951 ms/op
                 getUser·p1.00:   28.541 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 259440
  mean =      3.698 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10014 
    [ 2.500,  5.000) = 240244 
    [ 5.000,  7.500) = 8518 
    [ 7.500, 10.000) = 470 
    [10.000, 12.500) = 34 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 79 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.705 ms/op
     p(50.0000) =      3.654 ms/op
     p(90.0000) =      4.547 ms/op
     p(95.0000) =      4.833 ms/op
     p(99.0000) =      5.915 ms/op
     p(99.9000) =      9.201 ms/op
     p(99.9900) =     25.636 ms/op
     p(99.9990) =     28.072 ms/op
     p(99.9999) =     28.541 ms/op
    p(100.0000) =     28.541 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 6.574 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 4.950 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.778 ±(99.9%) 0.015 ms/op
Iteration   1: 4.694 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.280 ms/op
                 listUser·p0.50:   4.473 ms/op
                 listUser·p0.90:   6.087 ms/op
                 listUser·p0.95:   6.562 ms/op
                 listUser·p0.99:   8.069 ms/op
                 listUser·p0.999:  15.335 ms/op
                 listUser·p0.9999: 22.452 ms/op
                 listUser·p1.00:   23.888 ms/op

Iteration   2: 4.726 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.139 ms/op
                 listUser·p0.50:   4.489 ms/op
                 listUser·p0.90:   6.111 ms/op
                 listUser·p0.95:   6.865 ms/op
                 listUser·p0.99:   8.552 ms/op
                 listUser·p0.999:  16.563 ms/op
                 listUser·p0.9999: 24.689 ms/op
                 listUser·p1.00:   24.969 ms/op

Iteration   3: 4.711 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   0.397 ms/op
                 listUser·p0.50:   4.481 ms/op
                 listUser·p0.90:   6.095 ms/op
                 listUser·p0.95:   6.791 ms/op
                 listUser·p0.99:   8.417 ms/op
                 listUser·p0.999:  18.416 ms/op
                 listUser·p0.9999: 20.533 ms/op
                 listUser·p1.00:   21.004 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 203820
  mean =      4.711 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 493 
    [ 2.500,  5.000) = 149179 
    [ 5.000,  7.500) = 49521 
    [ 7.500, 10.000) = 3933 
    [10.000, 12.500) = 334 
    [12.500, 15.000) = 73 
    [15.000, 17.500) = 111 
    [17.500, 20.000) = 102 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.397 ms/op
     p(50.0000) =      4.481 ms/op
     p(90.0000) =      6.095 ms/op
     p(95.0000) =      6.734 ms/op
     p(99.0000) =      8.364 ms/op
     p(99.9000) =     16.557 ms/op
     p(99.9900) =     24.158 ms/op
     p(99.9990) =     24.934 ms/op
     p(99.9999) =     24.969 ms/op
    p(100.0000) =     24.969 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.547 ± 1.926  ops/ms
ClientGrpc.existUser                       thrpt       3   9.150 ± 3.926  ops/ms
ClientGrpc.getUser                         thrpt       3   8.729 ± 1.444  ops/ms
ClientGrpc.listUser                        thrpt       3   6.736 ± 1.028  ops/ms
ClientGrpc.createUser                       avgt       3   3.752 ± 0.688   ms/op
ClientGrpc.existUser                        avgt       3   3.567 ± 0.714   ms/op
ClientGrpc.getUser                          avgt       3   3.688 ± 0.764   ms/op
ClientGrpc.listUser                         avgt       3   4.711 ± 0.483   ms/op
ClientGrpc.createUser                     sample  259042   3.705 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.866           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.637           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.547           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.841           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.857           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.894           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          27.115           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          29.655           ms/op
ClientGrpc.existUser                      sample  268500   3.575 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.733           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.531           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.407           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.710           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.792           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.969           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          25.082           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          26.411           ms/op
ClientGrpc.getUser                        sample  259440   3.698 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.705           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.654           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.547           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.833           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.915           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.201           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          25.636           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          28.541           ms/op
ClientGrpc.listUser                       sample  203820   4.711 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.397           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.481           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.095           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.734           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.364           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.557           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.158           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.969           ms/op
