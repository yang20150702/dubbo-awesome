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
# Warmup Iteration   1: 1.803 ops/ms
# Warmup Iteration   2: 4.377 ops/ms
# Warmup Iteration   3: 6.232 ops/ms
Iteration   1: 6.385 ops/ms
Iteration   2: 6.414 ops/ms
Iteration   3: 6.336 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  6.378 ±(99.9%) 0.718 ops/ms [Average]
  (min, avg, max) = (6.336, 6.378, 6.414), stdev = 0.039
  CI (99.9%): [5.661, 7.096] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.852 ops/ms
# Warmup Iteration   2: 6.115 ops/ms
# Warmup Iteration   3: 6.609 ops/ms
Iteration   1: 6.757 ops/ms
Iteration   2: 6.847 ops/ms
Iteration   3: 7.058 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  6.887 ±(99.9%) 2.813 ops/ms [Average]
  (min, avg, max) = (6.757, 6.887, 7.058), stdev = 0.154
  CI (99.9%): [4.074, 9.700] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:03
# Fork: 1 of 1
# Warmup Iteration   1: 3.303 ops/ms
# Warmup Iteration   2: 6.052 ops/ms
# Warmup Iteration   3: 6.548 ops/ms
Iteration   1: 6.728 ops/ms
Iteration   2: 6.614 ops/ms
Iteration   3: 6.472 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  6.605 ±(99.9%) 2.346 ops/ms [Average]
  (min, avg, max) = (6.472, 6.605, 6.728), stdev = 0.129
  CI (99.9%): [4.259, 8.951] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.366 ops/ms
# Warmup Iteration   2: 4.657 ops/ms
# Warmup Iteration   3: 5.025 ops/ms
Iteration   1: 4.948 ops/ms
Iteration   2: 5.280 ops/ms
Iteration   3: 5.169 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.132 ±(99.9%) 3.077 ops/ms [Average]
  (min, avg, max) = (4.948, 5.132, 5.280), stdev = 0.169
  CI (99.9%): [2.056, 8.209] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 7.767 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 5.321 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 5.006 ±(99.9%) 0.006 ms/op
Iteration   1: 4.955 ±(99.9%) 0.005 ms/op
Iteration   2: 5.041 ±(99.9%) 0.004 ms/op
Iteration   3: 5.053 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  5.016 ±(99.9%) 0.977 ms/op [Average]
  (min, avg, max) = (4.955, 5.016, 5.053), stdev = 0.054
  CI (99.9%): [4.039, 5.993] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 6.883 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.782 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.729 ±(99.9%) 0.013 ms/op
Iteration   1: 4.563 ±(99.9%) 0.002 ms/op
Iteration   2: 4.738 ±(99.9%) 0.007 ms/op
Iteration   3: 4.469 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.590 ±(99.9%) 2.496 ms/op [Average]
  (min, avg, max) = (4.469, 4.590, 4.738), stdev = 0.137
  CI (99.9%): [2.094, 7.086] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 7.891 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 5.228 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 5.009 ±(99.9%) 0.005 ms/op
Iteration   1: 5.078 ±(99.9%) 0.004 ms/op
Iteration   2: 4.978 ±(99.9%) 0.003 ms/op
Iteration   3: 4.936 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.997 ±(99.9%) 1.337 ms/op [Average]
  (min, avg, max) = (4.936, 4.997, 5.078), stdev = 0.073
  CI (99.9%): [3.660, 6.334] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 9.015 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 6.740 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 5.907 ±(99.9%) 0.010 ms/op
Iteration   1: 6.227 ±(99.9%) 0.014 ms/op
Iteration   2: 6.554 ±(99.9%) 0.021 ms/op
Iteration   3: 6.149 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.310 ±(99.9%) 3.918 ms/op [Average]
  (min, avg, max) = (6.149, 6.310, 6.554), stdev = 0.215
  CI (99.9%): [2.392, 10.227] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 7.377 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 5.260 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.898 ±(99.9%) 0.016 ms/op
Iteration   1: 5.034 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   1.341 ms/op
                 createUser·p0.50:   4.866 ms/op
                 createUser·p0.90:   6.455 ms/op
                 createUser·p0.95:   7.143 ms/op
                 createUser·p0.99:   9.437 ms/op
                 createUser·p0.999:  13.233 ms/op
                 createUser·p0.9999: 23.200 ms/op
                 createUser·p1.00:   23.298 ms/op

Iteration   2: 4.954 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   1.358 ms/op
                 createUser·p0.50:   4.817 ms/op
                 createUser·p0.90:   6.414 ms/op
                 createUser·p0.95:   6.939 ms/op
                 createUser·p0.99:   8.765 ms/op
                 createUser·p0.999:  12.068 ms/op
                 createUser·p0.9999: 24.795 ms/op
                 createUser·p1.00:   25.494 ms/op

Iteration   3: 4.957 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   1.255 ms/op
                 createUser·p0.50:   4.809 ms/op
                 createUser·p0.90:   6.423 ms/op
                 createUser·p0.95:   7.012 ms/op
                 createUser·p0.99:   9.634 ms/op
                 createUser·p0.999:  27.607 ms/op
                 createUser·p0.9999: 33.590 ms/op
                 createUser·p1.00:   33.948 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 192666
  mean =      4.982 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2884 
    [ 2.500,  5.000) = 104992 
    [ 5.000,  7.500) = 78676 
    [ 7.500, 10.000) = 4840 
    [10.000, 12.500) = 859 
    [12.500, 15.000) = 218 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 27 
    [27.500, 30.000) = 35 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 21 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.255 ms/op
     p(50.0000) =      4.825 ms/op
     p(90.0000) =      6.431 ms/op
     p(95.0000) =      7.029 ms/op
     p(99.0000) =      9.224 ms/op
     p(99.9000) =     15.188 ms/op
     p(99.9900) =     32.980 ms/op
     p(99.9990) =     33.826 ms/op
     p(99.9999) =     33.948 ms/op
    p(100.0000) =     33.948 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.755 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 4.817 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.903 ±(99.9%) 0.018 ms/op
Iteration   1: 4.734 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   1.087 ms/op
                 existUser·p0.50:   4.604 ms/op
                 existUser·p0.90:   6.087 ms/op
                 existUser·p0.95:   6.726 ms/op
                 existUser·p0.99:   8.995 ms/op
                 existUser·p0.999:  12.923 ms/op
                 existUser·p0.9999: 17.645 ms/op
                 existUser·p1.00:   18.317 ms/op

Iteration   2: 4.597 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.151 ms/op
                 existUser·p0.50:   4.506 ms/op
                 existUser·p0.90:   5.784 ms/op
                 existUser·p0.95:   6.218 ms/op
                 existUser·p0.99:   7.586 ms/op
                 existUser·p0.999:  13.315 ms/op
                 existUser·p0.9999: 21.269 ms/op
                 existUser·p1.00:   21.660 ms/op

Iteration   3: 4.677 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   1.085 ms/op
                 existUser·p0.50:   4.571 ms/op
                 existUser·p0.90:   5.980 ms/op
                 existUser·p0.95:   6.537 ms/op
                 existUser·p0.99:   8.579 ms/op
                 existUser·p0.999:  12.119 ms/op
                 existUser·p0.9999: 21.927 ms/op
                 existUser·p1.00:   22.413 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 205656
  mean =      4.669 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4444 
    [ 2.500,  5.000) = 132213 
    [ 5.000,  7.500) = 65075 
    [ 7.500, 10.000) = 3036 
    [10.000, 12.500) = 629 
    [12.500, 15.000) = 166 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.085 ms/op
     p(50.0000) =      4.563 ms/op
     p(90.0000) =      5.947 ms/op
     p(95.0000) =      6.488 ms/op
     p(99.0000) =      8.461 ms/op
     p(99.9000) =     12.796 ms/op
     p(99.9900) =     21.445 ms/op
     p(99.9990) =     22.277 ms/op
     p(99.9999) =     22.413 ms/op
    p(100.0000) =     22.413 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 7.240 ±(99.9%) 0.098 ms/op
# Warmup Iteration   2: 5.780 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 5.038 ±(99.9%) 0.017 ms/op
Iteration   1: 4.963 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   1.333 ms/op
                 getUser·p0.50:   4.743 ms/op
                 getUser·p0.90:   6.455 ms/op
                 getUser·p0.95:   7.250 ms/op
                 getUser·p0.99:   9.372 ms/op
                 getUser·p0.999:  14.100 ms/op
                 getUser·p0.9999: 17.797 ms/op
                 getUser·p1.00:   18.252 ms/op

Iteration   2: 5.027 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   1.210 ms/op
                 getUser·p0.50:   4.882 ms/op
                 getUser·p0.90:   6.488 ms/op
                 getUser·p0.95:   7.143 ms/op
                 getUser·p0.99:   9.159 ms/op
                 getUser·p0.999:  15.943 ms/op
                 getUser·p0.9999: 19.208 ms/op
                 getUser·p1.00:   20.611 ms/op

Iteration   3: 4.974 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   0.906 ms/op
                 getUser·p0.50:   4.817 ms/op
                 getUser·p0.90:   6.382 ms/op
                 getUser·p0.95:   6.971 ms/op
                 getUser·p0.99:   8.880 ms/op
                 getUser·p0.999:  13.704 ms/op
                 getUser·p0.9999: 19.174 ms/op
                 getUser·p1.00:   21.889 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 192359
  mean =      4.988 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3028 
    [ 2.500,  5.000) = 106606 
    [ 5.000,  7.500) = 75925 
    [ 7.500, 10.000) = 5569 
    [10.000, 12.500) = 704 
    [12.500, 15.000) = 367 
    [15.000, 17.500) = 90 
    [17.500, 20.000) = 66 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.906 ms/op
     p(50.0000) =      4.809 ms/op
     p(90.0000) =      6.439 ms/op
     p(95.0000) =      7.119 ms/op
     p(99.0000) =      9.149 ms/op
     p(99.9000) =     14.576 ms/op
     p(99.9900) =     18.990 ms/op
     p(99.9990) =     21.768 ms/op
     p(99.9999) =     21.889 ms/op
    p(100.0000) =     21.889 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 8.614 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 6.824 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 6.323 ±(99.9%) 0.027 ms/op
Iteration   1: 6.092 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.788 ms/op
                 listUser·p0.50:   5.734 ms/op
                 listUser·p0.90:   8.110 ms/op
                 listUser·p0.95:   9.159 ms/op
                 listUser·p0.99:   11.993 ms/op
                 listUser·p0.999:  19.758 ms/op
                 listUser·p0.9999: 21.979 ms/op
                 listUser·p1.00:   22.413 ms/op

Iteration   2: 6.274 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   0.742 ms/op
                 listUser·p0.50:   5.865 ms/op
                 listUser·p0.90:   8.421 ms/op
                 listUser·p0.95:   9.454 ms/op
                 listUser·p0.99:   12.157 ms/op
                 listUser·p0.999:  19.333 ms/op
                 listUser·p0.9999: 23.371 ms/op
                 listUser·p1.00:   24.445 ms/op

Iteration   3: 5.873 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   1.309 ms/op
                 listUser·p0.50:   5.562 ms/op
                 listUser·p0.90:   8.045 ms/op
                 listUser·p0.95:   9.142 ms/op
                 listUser·p0.99:   11.410 ms/op
                 listUser·p0.999:  22.905 ms/op
                 listUser·p0.9999: 31.022 ms/op
                 listUser·p1.00:   31.326 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 158075
  mean =      6.075 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 72 
    [ 2.500,  5.000) = 39101 
    [ 5.000,  7.500) = 93549 
    [ 7.500, 10.000) = 20474 
    [10.000, 12.500) = 3795 
    [12.500, 15.000) = 670 
    [15.000, 17.500) = 148 
    [17.500, 20.000) = 97 
    [20.000, 22.500) = 104 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 16 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.742 ms/op
     p(50.0000) =      5.718 ms/op
     p(90.0000) =      8.217 ms/op
     p(95.0000) =      9.257 ms/op
     p(99.0000) =     11.813 ms/op
     p(99.9000) =     20.316 ms/op
     p(99.9900) =     26.850 ms/op
     p(99.9990) =     31.307 ms/op
     p(99.9999) =     31.326 ms/op
    p(100.0000) =     31.326 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   6.378 ± 0.718  ops/ms
ClientGrpc.existUser                       thrpt       3   6.887 ± 2.813  ops/ms
ClientGrpc.getUser                         thrpt       3   6.605 ± 2.346  ops/ms
ClientGrpc.listUser                        thrpt       3   5.132 ± 3.077  ops/ms
ClientGrpc.createUser                       avgt       3   5.016 ± 0.977   ms/op
ClientGrpc.existUser                        avgt       3   4.590 ± 2.496   ms/op
ClientGrpc.getUser                          avgt       3   4.997 ± 1.337   ms/op
ClientGrpc.listUser                         avgt       3   6.310 ± 3.918   ms/op
ClientGrpc.createUser                     sample  192666   4.982 ± 0.011   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.255           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.825           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           6.431           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           7.029           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           9.224           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          15.188           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          32.980           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          33.948           ms/op
ClientGrpc.existUser                      sample  205656   4.669 ± 0.009   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           1.085           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.563           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.947           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           6.488           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           8.461           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.796           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.445           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.413           ms/op
ClientGrpc.getUser                        sample  192359   4.988 ± 0.010   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.906           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.809           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           6.439           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           7.119           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           9.149           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          14.576           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.990           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.889           ms/op
ClientGrpc.listUser                       sample  158075   6.075 ± 0.015   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.742           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.718           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           8.217           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           9.257           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          11.813           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          20.316           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.850           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          31.326           ms/op
