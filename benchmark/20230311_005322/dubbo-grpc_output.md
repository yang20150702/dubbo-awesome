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
# Warmup Iteration   1: 4.923 ops/ms
# Warmup Iteration   2: 9.377 ops/ms
# Warmup Iteration   3: 10.493 ops/ms
Iteration   1: 10.807 ops/ms
Iteration   2: 10.762 ops/ms
Iteration   3: 10.696 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.755 ±(99.9%) 1.019 ops/ms [Average]
  (min, avg, max) = (10.696, 10.755, 10.807), stdev = 0.056
  CI (99.9%): [9.737, 11.774] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 8.892 ops/ms
# Warmup Iteration   2: 10.793 ops/ms
# Warmup Iteration   3: 11.022 ops/ms
Iteration   1: 11.170 ops/ms
Iteration   2: 11.423 ops/ms
Iteration   3: 11.209 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.267 ±(99.9%) 2.483 ops/ms [Average]
  (min, avg, max) = (11.170, 11.267, 11.423), stdev = 0.136
  CI (99.9%): [8.785, 13.750] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.713 ops/ms
# Warmup Iteration   2: 10.665 ops/ms
# Warmup Iteration   3: 10.888 ops/ms
Iteration   1: 10.878 ops/ms
Iteration   2: 11.057 ops/ms
Iteration   3: 10.944 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.959 ±(99.9%) 1.657 ops/ms [Average]
  (min, avg, max) = (10.878, 10.959, 11.057), stdev = 0.091
  CI (99.9%): [9.303, 12.616] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.721 ops/ms
# Warmup Iteration   2: 8.103 ops/ms
# Warmup Iteration   3: 8.441 ops/ms
Iteration   1: 8.292 ops/ms
Iteration   2: 8.333 ops/ms
Iteration   3: 8.369 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.331 ±(99.9%) 0.703 ops/ms [Average]
  (min, avg, max) = (8.292, 8.331, 8.369), stdev = 0.039
  CI (99.9%): [7.629, 9.034] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 3.954 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.032 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.946 ±(99.9%) 0.003 ms/op
Iteration   1: 2.947 ±(99.9%) 0.003 ms/op
Iteration   2: 3.000 ±(99.9%) 0.002 ms/op
Iteration   3: 2.960 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.969 ±(99.9%) 0.506 ms/op [Average]
  (min, avg, max) = (2.947, 2.969, 3.000), stdev = 0.028
  CI (99.9%): [2.463, 3.475] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.585 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.875 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.799 ±(99.9%) 0.004 ms/op
Iteration   1: 2.799 ±(99.9%) 0.004 ms/op
Iteration   2: 2.841 ±(99.9%) 0.003 ms/op
Iteration   3: 2.785 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.808 ±(99.9%) 0.538 ms/op [Average]
  (min, avg, max) = (2.785, 2.808, 2.841), stdev = 0.029
  CI (99.9%): [2.271, 3.346] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.612 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.986 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 2.947 ±(99.9%) 0.002 ms/op
Iteration   1: 2.939 ±(99.9%) 0.005 ms/op
Iteration   2: 2.881 ±(99.9%) 0.003 ms/op
Iteration   3: 2.944 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.921 ±(99.9%) 0.638 ms/op [Average]
  (min, avg, max) = (2.881, 2.921, 2.944), stdev = 0.035
  CI (99.9%): [2.283, 3.559] (assumes normal distribution)


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
# Warmup Iteration   1: 4.182 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.934 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 3.812 ±(99.9%) 0.020 ms/op
Iteration   1: 3.808 ±(99.9%) 0.009 ms/op
Iteration   2: 3.835 ±(99.9%) 0.036 ms/op
Iteration   3: 3.677 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.773 ±(99.9%) 1.546 ms/op [Average]
  (min, avg, max) = (3.677, 3.773, 3.835), stdev = 0.085
  CI (99.9%): [2.227, 5.319] (assumes normal distribution)


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
# Warmup Iteration   1: 3.874 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.037 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.968 ±(99.9%) 0.007 ms/op
Iteration   1: 2.910 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.760 ms/op
                 createUser·p0.50:   2.904 ms/op
                 createUser·p0.90:   3.326 ms/op
                 createUser·p0.95:   3.580 ms/op
                 createUser·p0.99:   4.288 ms/op
                 createUser·p0.999:  7.069 ms/op
                 createUser·p0.9999: 19.824 ms/op
                 createUser·p1.00:   22.053 ms/op

Iteration   2: 2.910 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.643 ms/op
                 createUser·p0.50:   2.908 ms/op
                 createUser·p0.90:   3.273 ms/op
                 createUser·p0.95:   3.490 ms/op
                 createUser·p0.99:   4.063 ms/op
                 createUser·p0.999:  7.556 ms/op
                 createUser·p0.9999: 13.812 ms/op
                 createUser·p1.00:   14.107 ms/op

Iteration   3: 2.917 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.635 ms/op
                 createUser·p0.50:   2.896 ms/op
                 createUser·p0.90:   3.400 ms/op
                 createUser·p0.95:   3.572 ms/op
                 createUser·p0.99:   4.342 ms/op
                 createUser·p0.999:  9.656 ms/op
                 createUser·p0.9999: 26.019 ms/op
                 createUser·p1.00:   33.030 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 329541
  mean =      2.913 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 35193 
    [ 2.500,  5.000) = 293322 
    [ 5.000,  7.500) = 681 
    [ 7.500, 10.000) = 120 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 27 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.635 ms/op
     p(50.0000) =      2.904 ms/op
     p(90.0000) =      3.342 ms/op
     p(95.0000) =      3.555 ms/op
     p(99.0000) =      4.252 ms/op
     p(99.9000) =      7.606 ms/op
     p(99.9900) =     24.745 ms/op
     p(99.9990) =     33.020 ms/op
     p(99.9999) =     33.030 ms/op
    p(100.0000) =     33.030 ms/op


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
# Warmup Iteration   1: 3.752 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 2.877 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.854 ±(99.9%) 0.006 ms/op
Iteration   1: 2.856 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.664 ms/op
                 existUser·p0.50:   2.822 ms/op
                 existUser·p0.90:   3.375 ms/op
                 existUser·p0.95:   3.604 ms/op
                 existUser·p0.99:   4.424 ms/op
                 existUser·p0.999:  6.438 ms/op
                 existUser·p0.9999: 18.474 ms/op
                 existUser·p1.00:   18.743 ms/op

Iteration   2: 2.897 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.610 ms/op
                 existUser·p0.50:   2.859 ms/op
                 existUser·p0.90:   3.379 ms/op
                 existUser·p0.95:   3.502 ms/op
                 existUser·p0.99:   4.100 ms/op
                 existUser·p0.999:  10.250 ms/op
                 existUser·p0.9999: 22.312 ms/op
                 existUser·p1.00:   22.708 ms/op

Iteration   3: 2.817 ±(99.9%) 0.004 ms/op
                 existUser·p0.00:   0.522 ms/op
                 existUser·p0.50:   2.810 ms/op
                 existUser·p0.90:   3.113 ms/op
                 existUser·p0.95:   3.203 ms/op
                 existUser·p0.99:   3.711 ms/op
                 existUser·p0.999:  5.763 ms/op
                 existUser·p0.9999: 16.012 ms/op
                 existUser·p1.00:   16.384 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 336047
  mean =      2.856 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 49122 
    [ 2.500,  5.000) = 286121 
    [ 5.000,  7.500) = 536 
    [ 7.500, 10.000) = 27 
    [10.000, 12.500) = 65 
    [12.500, 15.000) = 85 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.522 ms/op
     p(50.0000) =      2.826 ms/op
     p(90.0000) =      3.305 ms/op
     p(95.0000) =      3.482 ms/op
     p(99.0000) =      4.170 ms/op
     p(99.9000) =      6.684 ms/op
     p(99.9900) =     18.723 ms/op
     p(99.9990) =     22.598 ms/op
     p(99.9999) =     22.708 ms/op
    p(100.0000) =     22.708 ms/op


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
# Warmup Iteration   1: 3.774 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.046 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.972 ±(99.9%) 0.007 ms/op
Iteration   1: 2.955 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.762 ms/op
                 getUser·p0.50:   2.937 ms/op
                 getUser·p0.90:   3.457 ms/op
                 getUser·p0.95:   3.648 ms/op
                 getUser·p0.99:   4.211 ms/op
                 getUser·p0.999:  6.783 ms/op
                 getUser·p0.9999: 11.062 ms/op
                 getUser·p1.00:   14.123 ms/op

Iteration   2: 2.892 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.541 ms/op
                 getUser·p0.50:   2.916 ms/op
                 getUser·p0.90:   3.322 ms/op
                 getUser·p0.95:   3.539 ms/op
                 getUser·p0.99:   4.194 ms/op
                 getUser·p0.999:  11.698 ms/op
                 getUser·p0.9999: 16.627 ms/op
                 getUser·p1.00:   16.941 ms/op

Iteration   3: 2.977 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.630 ms/op
                 getUser·p0.50:   2.949 ms/op
                 getUser·p0.90:   3.584 ms/op
                 getUser·p0.95:   3.813 ms/op
                 getUser·p0.99:   4.186 ms/op
                 getUser·p0.999:  6.465 ms/op
                 getUser·p0.9999: 26.321 ms/op
                 getUser·p1.00:   26.640 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 326264
  mean =      2.941 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 32426 
    [ 2.500,  5.000) = 292804 
    [ 5.000,  7.500) = 687 
    [ 7.500, 10.000) = 116 
    [10.000, 12.500) = 132 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.541 ms/op
     p(50.0000) =      2.933 ms/op
     p(90.0000) =      3.453 ms/op
     p(95.0000) =      3.699 ms/op
     p(99.0000) =      4.194 ms/op
     p(99.9000) =      7.815 ms/op
     p(99.9900) =     19.780 ms/op
     p(99.9990) =     26.566 ms/op
     p(99.9999) =     26.640 ms/op
    p(100.0000) =     26.640 ms/op


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
# Warmup Iteration   1: 5.025 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.956 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.789 ±(99.9%) 0.009 ms/op
Iteration   1: 3.820 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.842 ms/op
                 listUser·p0.50:   3.678 ms/op
                 listUser·p0.90:   4.841 ms/op
                 listUser·p0.95:   5.415 ms/op
                 listUser·p0.99:   6.423 ms/op
                 listUser·p0.999:  11.553 ms/op
                 listUser·p0.9999: 13.327 ms/op
                 listUser·p1.00:   14.713 ms/op

Iteration   2: 3.725 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.649 ms/op
                 listUser·p0.50:   3.604 ms/op
                 listUser·p0.90:   4.719 ms/op
                 listUser·p0.95:   5.341 ms/op
                 listUser·p0.99:   6.668 ms/op
                 listUser·p0.999:  13.156 ms/op
                 listUser·p0.9999: 16.260 ms/op
                 listUser·p1.00:   16.843 ms/op

Iteration   3: 3.724 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.096 ms/op
                 listUser·p0.50:   3.592 ms/op
                 listUser·p0.90:   4.825 ms/op
                 listUser·p0.95:   5.423 ms/op
                 listUser·p0.99:   6.554 ms/op
                 listUser·p0.999:  13.435 ms/op
                 listUser·p0.9999: 16.253 ms/op
                 listUser·p1.00:   16.695 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 255558
  mean =      3.756 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 15 
    [ 1.250,  2.500) = 5906 
    [ 2.500,  3.750) = 148807 
    [ 3.750,  5.000) = 81055 
    [ 5.000,  6.250) = 15864 
    [ 6.250,  7.500) = 3035 
    [ 7.500,  8.750) = 406 
    [ 8.750, 10.000) = 61 
    [10.000, 11.250) = 57 
    [11.250, 12.500) = 102 
    [12.500, 13.750) = 114 
    [13.750, 15.000) = 71 
    [15.000, 16.250) = 47 
    [16.250, 17.500) = 18 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.649 ms/op
     p(50.0000) =      3.629 ms/op
     p(90.0000) =      4.801 ms/op
     p(95.0000) =      5.399 ms/op
     p(99.0000) =      6.545 ms/op
     p(99.9000) =     12.419 ms/op
     p(99.9900) =     16.036 ms/op
     p(99.9990) =     16.770 ms/op
     p(99.9999) =     16.843 ms/op
    p(100.0000) =     16.843 ms/op


# Run complete. Total time: 00:13:02

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.755 ± 1.019  ops/ms
ClientGrpc.existUser                       thrpt       3  11.267 ± 2.483  ops/ms
ClientGrpc.getUser                         thrpt       3  10.959 ± 1.657  ops/ms
ClientGrpc.listUser                        thrpt       3   8.331 ± 0.703  ops/ms
ClientGrpc.createUser                       avgt       3   2.969 ± 0.506   ms/op
ClientGrpc.existUser                        avgt       3   2.808 ± 0.538   ms/op
ClientGrpc.getUser                          avgt       3   2.921 ± 0.638   ms/op
ClientGrpc.listUser                         avgt       3   3.773 ± 1.546   ms/op
ClientGrpc.createUser                     sample  329541   2.913 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.635           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.904           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.342           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.555           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.252           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.606           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.745           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          33.030           ms/op
ClientGrpc.existUser                      sample  336047   2.856 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.522           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.826           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.305           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.482           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.170           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.684           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.723           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.708           ms/op
ClientGrpc.getUser                        sample  326264   2.941 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.541           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.933           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.453           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.699           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.194           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.815           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.780           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          26.640           ms/op
ClientGrpc.listUser                       sample  255558   3.756 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.649           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.629           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.801           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.399           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.545           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          12.419           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          16.036           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          16.843           ms/op
