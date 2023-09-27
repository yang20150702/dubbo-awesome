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
# Warmup Iteration   1: 3.812 ops/ms
# Warmup Iteration   2: 8.802 ops/ms
# Warmup Iteration   3: 9.707 ops/ms
Iteration   1: 10.022 ops/ms
Iteration   2: 10.015 ops/ms
Iteration   3: 10.176 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.071 ±(99.9%) 1.652 ops/ms [Average]
  (min, avg, max) = (10.015, 10.071, 10.176), stdev = 0.091
  CI (99.9%): [8.419, 11.723] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.185 ops/ms
# Warmup Iteration   2: 10.164 ops/ms
# Warmup Iteration   3: 10.903 ops/ms
Iteration   1: 10.709 ops/ms
Iteration   2: 10.856 ops/ms
Iteration   3: 10.597 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.721 ±(99.9%) 2.368 ops/ms [Average]
  (min, avg, max) = (10.597, 10.721, 10.856), stdev = 0.130
  CI (99.9%): [8.353, 13.088] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 6.236 ops/ms
# Warmup Iteration   2: 9.801 ops/ms
# Warmup Iteration   3: 9.963 ops/ms
Iteration   1: 9.902 ops/ms
Iteration   2: 10.131 ops/ms
Iteration   3: 10.392 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.141 ±(99.9%) 4.470 ops/ms [Average]
  (min, avg, max) = (9.902, 10.141, 10.392), stdev = 0.245
  CI (99.9%): [5.672, 14.611] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 5.977 ops/ms
# Warmup Iteration   2: 7.441 ops/ms
# Warmup Iteration   3: 7.909 ops/ms
Iteration   1: 8.067 ops/ms
Iteration   2: 7.981 ops/ms
Iteration   3: 8.105 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.051 ±(99.9%) 1.159 ops/ms [Average]
  (min, avg, max) = (7.981, 8.051, 8.105), stdev = 0.064
  CI (99.9%): [6.892, 9.210] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.498 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.260 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.155 ±(99.9%) 0.002 ms/op
Iteration   1: 3.159 ±(99.9%) 0.005 ms/op
Iteration   2: 3.114 ±(99.9%) 0.004 ms/op
Iteration   3: 3.156 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.143 ±(99.9%) 0.458 ms/op [Average]
  (min, avg, max) = (3.114, 3.143, 3.159), stdev = 0.025
  CI (99.9%): [2.685, 3.601] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.193 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.113 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.045 ±(99.9%) 0.002 ms/op
Iteration   1: 2.930 ±(99.9%) 0.004 ms/op
Iteration   2: 3.004 ±(99.9%) 0.002 ms/op
Iteration   3: 3.005 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.980 ±(99.9%) 0.783 ms/op [Average]
  (min, avg, max) = (2.930, 2.980, 3.005), stdev = 0.043
  CI (99.9%): [2.197, 3.763] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 4.462 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.234 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.159 ±(99.9%) 0.004 ms/op
Iteration   1: 3.185 ±(99.9%) 0.005 ms/op
Iteration   2: 3.152 ±(99.9%) 0.003 ms/op
Iteration   3: 3.101 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.146 ±(99.9%) 0.779 ms/op [Average]
  (min, avg, max) = (3.101, 3.146, 3.185), stdev = 0.043
  CI (99.9%): [2.367, 3.925] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.801 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.086 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 3.981 ±(99.9%) 0.015 ms/op
Iteration   1: 3.925 ±(99.9%) 0.012 ms/op
Iteration   2: 4.009 ±(99.9%) 0.020 ms/op
Iteration   3: 3.960 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.965 ±(99.9%) 0.768 ms/op [Average]
  (min, avg, max) = (3.925, 3.965, 4.009), stdev = 0.042
  CI (99.9%): [3.197, 4.733] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.353 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.322 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.136 ±(99.9%) 0.007 ms/op
Iteration   1: 3.099 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.693 ms/op
                 createUser·p0.50:   3.068 ms/op
                 createUser·p0.90:   3.650 ms/op
                 createUser·p0.95:   3.871 ms/op
                 createUser·p0.99:   4.727 ms/op
                 createUser·p0.999:  10.911 ms/op
                 createUser·p0.9999: 17.422 ms/op
                 createUser·p1.00:   17.695 ms/op

Iteration   2: 3.061 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.861 ms/op
                 createUser·p0.50:   3.023 ms/op
                 createUser·p0.90:   3.535 ms/op
                 createUser·p0.95:   3.731 ms/op
                 createUser·p0.99:   4.424 ms/op
                 createUser·p0.999:  9.275 ms/op
                 createUser·p0.9999: 17.469 ms/op
                 createUser·p1.00:   18.907 ms/op

Iteration   3: 3.160 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.640 ms/op
                 createUser·p0.50:   3.113 ms/op
                 createUser·p0.90:   3.711 ms/op
                 createUser·p0.95:   3.875 ms/op
                 createUser·p0.99:   5.054 ms/op
                 createUser·p0.999:  15.428 ms/op
                 createUser·p0.9999: 23.101 ms/op
                 createUser·p1.00:   23.495 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 309180
  mean =      3.106 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18041 
    [ 2.500,  5.000) = 288788 
    [ 5.000,  7.500) = 1729 
    [ 7.500, 10.000) = 240 
    [10.000, 12.500) = 57 
    [12.500, 15.000) = 78 
    [15.000, 17.500) = 173 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.640 ms/op
     p(50.0000) =      3.064 ms/op
     p(90.0000) =      3.641 ms/op
     p(95.0000) =      3.838 ms/op
     p(99.0000) =      4.735 ms/op
     p(99.9000) =     12.856 ms/op
     p(99.9900) =     22.473 ms/op
     p(99.9990) =     23.230 ms/op
     p(99.9999) =     23.495 ms/op
    p(100.0000) =     23.495 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 3.979 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.040 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.020 ±(99.9%) 0.007 ms/op
Iteration   1: 2.968 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.675 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.428 ms/op
                 existUser·p0.95:   3.588 ms/op
                 existUser·p0.99:   4.432 ms/op
                 existUser·p0.999:  8.360 ms/op
                 existUser·p0.9999: 24.976 ms/op
                 existUser·p1.00:   25.559 ms/op

Iteration   2: 2.960 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.738 ms/op
                 existUser·p0.50:   2.937 ms/op
                 existUser·p0.90:   3.420 ms/op
                 existUser·p0.95:   3.613 ms/op
                 existUser·p0.99:   4.645 ms/op
                 existUser·p0.999:  11.600 ms/op
                 existUser·p0.9999: 17.739 ms/op
                 existUser·p1.00:   18.776 ms/op

Iteration   3: 3.005 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.796 ms/op
                 existUser·p0.50:   2.966 ms/op
                 existUser·p0.90:   3.580 ms/op
                 existUser·p0.95:   3.736 ms/op
                 existUser·p0.99:   4.219 ms/op
                 existUser·p0.999:  10.051 ms/op
                 existUser·p0.9999: 22.621 ms/op
                 existUser·p1.00:   22.741 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 322589
  mean =      2.977 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 30232 
    [ 2.500,  5.000) = 290730 
    [ 5.000,  7.500) = 1063 
    [ 7.500, 10.000) = 244 
    [10.000, 12.500) = 115 
    [12.500, 15.000) = 92 
    [15.000, 17.500) = 55 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.675 ms/op
     p(50.0000) =      2.941 ms/op
     p(90.0000) =      3.482 ms/op
     p(95.0000) =      3.658 ms/op
     p(99.0000) =      4.433 ms/op
     p(99.9000) =      9.923 ms/op
     p(99.9900) =     22.733 ms/op
     p(99.9990) =     25.486 ms/op
     p(99.9999) =     25.559 ms/op
    p(100.0000) =     25.559 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.399 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.282 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.137 ±(99.9%) 0.007 ms/op
Iteration   1: 3.107 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.794 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.617 ms/op
                 getUser·p0.95:   3.891 ms/op
                 getUser·p0.99:   4.555 ms/op
                 getUser·p0.999:  7.855 ms/op
                 getUser·p0.9999: 16.646 ms/op
                 getUser·p1.00:   19.759 ms/op

Iteration   2: 3.143 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.644 ms/op
                 getUser·p0.50:   3.088 ms/op
                 getUser·p0.90:   3.637 ms/op
                 getUser·p0.95:   3.895 ms/op
                 getUser·p0.99:   4.829 ms/op
                 getUser·p0.999:  16.400 ms/op
                 getUser·p0.9999: 21.856 ms/op
                 getUser·p1.00:   22.020 ms/op

Iteration   3: 3.117 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.717 ms/op
                 getUser·p0.50:   3.076 ms/op
                 getUser·p0.90:   3.682 ms/op
                 getUser·p0.95:   3.899 ms/op
                 getUser·p0.99:   4.702 ms/op
                 getUser·p0.999:  9.706 ms/op
                 getUser·p0.9999: 20.578 ms/op
                 getUser·p1.00:   22.249 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 307415
  mean =      3.122 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12541 
    [ 2.500,  5.000) = 292714 
    [ 5.000,  7.500) = 1622 
    [ 7.500, 10.000) = 244 
    [10.000, 12.500) = 34 
    [12.500, 15.000) = 41 
    [15.000, 17.500) = 60 
    [17.500, 20.000) = 97 
    [20.000, 22.500) = 62 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.644 ms/op
     p(50.0000) =      3.076 ms/op
     p(90.0000) =      3.645 ms/op
     p(95.0000) =      3.895 ms/op
     p(99.0000) =      4.669 ms/op
     p(99.9000) =      9.587 ms/op
     p(99.9900) =     20.939 ms/op
     p(99.9990) =     22.146 ms/op
     p(99.9999) =     22.249 ms/op
    p(100.0000) =     22.249 ms/op


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
# Warmup Iteration   1: 5.656 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.102 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.990 ±(99.9%) 0.011 ms/op
Iteration   1: 3.995 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.440 ms/op
                 listUser·p0.50:   3.879 ms/op
                 listUser·p0.90:   4.694 ms/op
                 listUser·p0.95:   5.767 ms/op
                 listUser·p0.99:   6.865 ms/op
                 listUser·p0.999:  13.468 ms/op
                 listUser·p0.9999: 16.677 ms/op
                 listUser·p1.00:   19.530 ms/op

Iteration   2: 3.938 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.026 ms/op
                 listUser·p0.50:   3.854 ms/op
                 listUser·p0.90:   4.366 ms/op
                 listUser·p0.95:   5.014 ms/op
                 listUser·p0.99:   6.865 ms/op
                 listUser·p0.999:  14.418 ms/op
                 listUser·p0.9999: 17.662 ms/op
                 listUser·p1.00:   18.285 ms/op

Iteration   3: 4.012 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.949 ms/op
                 listUser·p0.50:   3.903 ms/op
                 listUser·p0.90:   4.489 ms/op
                 listUser·p0.95:   5.194 ms/op
                 listUser·p0.99:   7.021 ms/op
                 listUser·p0.999:  16.318 ms/op
                 listUser·p0.9999: 26.083 ms/op
                 listUser·p1.00:   26.477 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 241027
  mean =      3.981 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2255 
    [ 2.500,  5.000) = 223503 
    [ 5.000,  7.500) = 13951 
    [ 7.500, 10.000) = 743 
    [10.000, 12.500) = 107 
    [12.500, 15.000) = 241 
    [15.000, 17.500) = 165 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.949 ms/op
     p(50.0000) =      3.879 ms/op
     p(90.0000) =      4.497 ms/op
     p(95.0000) =      5.341 ms/op
     p(99.0000) =      6.914 ms/op
     p(99.9000) =     14.712 ms/op
     p(99.9900) =     18.671 ms/op
     p(99.9990) =     26.357 ms/op
     p(99.9999) =     26.477 ms/op
    p(100.0000) =     26.477 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.071 ± 1.652  ops/ms
ClientGrpc.existUser                       thrpt       3  10.721 ± 2.368  ops/ms
ClientGrpc.getUser                         thrpt       3  10.141 ± 4.470  ops/ms
ClientGrpc.listUser                        thrpt       3   8.051 ± 1.159  ops/ms
ClientGrpc.createUser                       avgt       3   3.143 ± 0.458   ms/op
ClientGrpc.existUser                        avgt       3   2.980 ± 0.783   ms/op
ClientGrpc.getUser                          avgt       3   3.146 ± 0.779   ms/op
ClientGrpc.listUser                         avgt       3   3.965 ± 0.768   ms/op
ClientGrpc.createUser                     sample  309180   3.106 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.640           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.064           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.641           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.838           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.735           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.856           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.473           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.495           ms/op
ClientGrpc.existUser                      sample  322589   2.977 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.675           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.941           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.482           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.658           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.433           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.923           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          22.733           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.559           ms/op
ClientGrpc.getUser                        sample  307415   3.122 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.644           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.076           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.645           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.895           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.669           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.587           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.939           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.249           ms/op
ClientGrpc.listUser                       sample  241027   3.981 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.949           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.879           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.497           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.341           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.914           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.712           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          18.671           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.477           ms/op
