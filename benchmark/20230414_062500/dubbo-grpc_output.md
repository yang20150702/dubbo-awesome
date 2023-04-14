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
# Warmup Iteration   1: 2.607 ops/ms
# Warmup Iteration   2: 6.310 ops/ms
# Warmup Iteration   3: 7.853 ops/ms
Iteration   1: 7.942 ops/ms
Iteration   2: 8.269 ops/ms
Iteration   3: 8.069 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.093 ±(99.9%) 3.015 ops/ms [Average]
  (min, avg, max) = (7.942, 8.093, 8.269), stdev = 0.165
  CI (99.9%): [5.078, 11.108] (assumes normal distribution)


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
# Warmup Iteration   1: 5.526 ops/ms
# Warmup Iteration   2: 7.924 ops/ms
# Warmup Iteration   3: 8.645 ops/ms
Iteration   1: 8.801 ops/ms
Iteration   2: 8.742 ops/ms
Iteration   3: 9.026 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.857 ±(99.9%) 2.731 ops/ms [Average]
  (min, avg, max) = (8.742, 8.857, 9.026), stdev = 0.150
  CI (99.9%): [6.125, 11.588] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 4.508 ops/ms
# Warmup Iteration   2: 7.560 ops/ms
# Warmup Iteration   3: 7.879 ops/ms
Iteration   1: 8.204 ops/ms
Iteration   2: 8.376 ops/ms
Iteration   3: 8.075 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.218 ±(99.9%) 2.753 ops/ms [Average]
  (min, avg, max) = (8.075, 8.218, 8.376), stdev = 0.151
  CI (99.9%): [5.465, 10.971] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 4.089 ops/ms
# Warmup Iteration   2: 5.720 ops/ms
# Warmup Iteration   3: 6.433 ops/ms
Iteration   1: 6.353 ops/ms
Iteration   2: 6.403 ops/ms
Iteration   3: 6.528 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.428 ±(99.9%) 1.646 ops/ms [Average]
  (min, avg, max) = (6.353, 6.428, 6.528), stdev = 0.090
  CI (99.9%): [4.781, 8.074] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.277 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.120 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.989 ±(99.9%) 0.006 ms/op
Iteration   1: 3.924 ±(99.9%) 0.003 ms/op
Iteration   2: 3.953 ±(99.9%) 0.003 ms/op
Iteration   3: 3.948 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.942 ±(99.9%) 0.284 ms/op [Average]
  (min, avg, max) = (3.924, 3.942, 3.953), stdev = 0.016
  CI (99.9%): [3.658, 4.226] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 5.144 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.974 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.684 ±(99.9%) 0.005 ms/op
Iteration   1: 3.668 ±(99.9%) 0.003 ms/op
Iteration   2: 3.664 ±(99.9%) 0.003 ms/op
Iteration   3: 3.600 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.644 ±(99.9%) 0.698 ms/op [Average]
  (min, avg, max) = (3.600, 3.644, 3.668), stdev = 0.038
  CI (99.9%): [2.946, 4.343] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 5.935 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.100 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.978 ±(99.9%) 0.006 ms/op
Iteration   1: 3.832 ±(99.9%) 0.004 ms/op
Iteration   2: 3.783 ±(99.9%) 0.003 ms/op
Iteration   3: 3.811 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.809 ±(99.9%) 0.448 ms/op [Average]
  (min, avg, max) = (3.783, 3.809, 3.832), stdev = 0.025
  CI (99.9%): [3.361, 4.256] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 7.751 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 5.205 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 5.030 ±(99.9%) 0.021 ms/op
Iteration   1: 4.879 ±(99.9%) 0.020 ms/op
Iteration   2: 4.958 ±(99.9%) 0.018 ms/op
Iteration   3: 5.019 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.952 ±(99.9%) 1.281 ms/op [Average]
  (min, avg, max) = (4.879, 4.952, 5.019), stdev = 0.070
  CI (99.9%): [3.671, 6.233] (assumes normal distribution)


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
# Warmup Iteration   1: 5.596 ±(99.9%) 0.071 ms/op
# Warmup Iteration   2: 4.163 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.974 ±(99.9%) 0.011 ms/op
Iteration   1: 3.844 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.014 ms/op
                 createUser·p0.50:   3.760 ms/op
                 createUser·p0.90:   4.784 ms/op
                 createUser·p0.95:   5.169 ms/op
                 createUser·p0.99:   6.349 ms/op
                 createUser·p0.999:  9.791 ms/op
                 createUser·p0.9999: 14.702 ms/op
                 createUser·p1.00:   17.072 ms/op

Iteration   2: 3.918 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.135 ms/op
                 createUser·p0.50:   3.813 ms/op
                 createUser·p0.90:   4.809 ms/op
                 createUser·p0.95:   5.169 ms/op
                 createUser·p0.99:   6.270 ms/op
                 createUser·p0.999:  9.826 ms/op
                 createUser·p0.9999: 17.382 ms/op
                 createUser·p1.00:   18.448 ms/op

Iteration   3: 3.908 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.803 ms/op
                 createUser·p0.50:   3.809 ms/op
                 createUser·p0.90:   4.801 ms/op
                 createUser·p0.95:   5.169 ms/op
                 createUser·p0.99:   6.426 ms/op
                 createUser·p0.999:  13.690 ms/op
                 createUser·p0.9999: 18.724 ms/op
                 createUser·p1.00:   20.611 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 246923
  mean =      3.890 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4226 
    [ 2.500,  5.000) = 225741 
    [ 5.000,  7.500) = 15849 
    [ 7.500, 10.000) = 804 
    [10.000, 12.500) = 80 
    [12.500, 15.000) = 94 
    [15.000, 17.500) = 84 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.803 ms/op
     p(50.0000) =      3.793 ms/op
     p(90.0000) =      4.801 ms/op
     p(95.0000) =      5.169 ms/op
     p(99.0000) =      6.357 ms/op
     p(99.9000) =     11.638 ms/op
     p(99.9900) =     18.219 ms/op
     p(99.9990) =     19.898 ms/op
     p(99.9999) =     20.611 ms/op
    p(100.0000) =     20.611 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.656 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 3.847 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.601 ±(99.9%) 0.008 ms/op
Iteration   1: 3.650 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.846 ms/op
                 existUser·p0.50:   3.580 ms/op
                 existUser·p0.90:   4.497 ms/op
                 existUser·p0.95:   4.858 ms/op
                 existUser·p0.99:   6.226 ms/op
                 existUser·p0.999:  12.304 ms/op
                 existUser·p0.9999: 14.962 ms/op
                 existUser·p1.00:   15.303 ms/op

Iteration   2: 3.741 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.892 ms/op
                 existUser·p0.50:   3.645 ms/op
                 existUser·p0.90:   4.489 ms/op
                 existUser·p0.95:   4.817 ms/op
                 existUser·p0.99:   6.252 ms/op
                 existUser·p0.999:  14.590 ms/op
                 existUser·p0.9999: 30.620 ms/op
                 existUser·p1.00:   31.392 ms/op

Iteration   3: 3.489 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.794 ms/op
                 existUser·p0.50:   3.465 ms/op
                 existUser·p0.90:   4.293 ms/op
                 existUser·p0.95:   4.620 ms/op
                 existUser·p0.99:   5.554 ms/op
                 existUser·p0.999:  8.243 ms/op
                 existUser·p0.9999: 17.072 ms/op
                 existUser·p1.00:   17.433 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 264944
  mean =      3.624 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10180 
    [ 2.500,  5.000) = 246275 
    [ 5.000,  7.500) = 7485 
    [ 7.500, 10.000) = 638 
    [10.000, 12.500) = 125 
    [12.500, 15.000) = 137 
    [15.000, 17.500) = 65 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 2 
    [30.000, 32.500) = 16 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.794 ms/op
     p(50.0000) =      3.559 ms/op
     p(90.0000) =      4.432 ms/op
     p(95.0000) =      4.768 ms/op
     p(99.0000) =      5.939 ms/op
     p(99.9000) =     11.522 ms/op
     p(99.9900) =     24.299 ms/op
     p(99.9990) =     31.199 ms/op
     p(99.9999) =     31.392 ms/op
    p(100.0000) =     31.392 ms/op


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
# Warmup Iteration   1: 5.711 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 4.045 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.887 ±(99.9%) 0.011 ms/op
Iteration   1: 3.916 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.785 ms/op
                 getUser·p0.50:   3.830 ms/op
                 getUser·p0.90:   4.784 ms/op
                 getUser·p0.95:   5.145 ms/op
                 getUser·p0.99:   6.431 ms/op
                 getUser·p0.999:  13.069 ms/op
                 getUser·p0.9999: 15.311 ms/op
                 getUser·p1.00:   15.647 ms/op

Iteration   2: 3.789 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.037 ms/op
                 getUser·p0.50:   3.703 ms/op
                 getUser·p0.90:   4.612 ms/op
                 getUser·p0.95:   5.063 ms/op
                 getUser·p0.99:   6.390 ms/op
                 getUser·p0.999:  10.042 ms/op
                 getUser·p0.9999: 17.141 ms/op
                 getUser·p1.00:   17.695 ms/op

Iteration   3: 3.940 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.180 ms/op
                 getUser·p0.50:   3.846 ms/op
                 getUser·p0.90:   4.817 ms/op
                 getUser·p0.95:   5.161 ms/op
                 getUser·p0.99:   6.427 ms/op
                 getUser·p0.999:  12.843 ms/op
                 getUser·p0.9999: 20.243 ms/op
                 getUser·p1.00:   22.807 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 247330
  mean =      3.881 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5025 
    [ 2.500,  5.000) = 226807 
    [ 5.000,  7.500) = 14294 
    [ 7.500, 10.000) = 856 
    [10.000, 12.500) = 118 
    [12.500, 15.000) = 124 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.785 ms/op
     p(50.0000) =      3.789 ms/op
     p(90.0000) =      4.751 ms/op
     p(95.0000) =      5.128 ms/op
     p(99.0000) =      6.414 ms/op
     p(99.9000) =     12.266 ms/op
     p(99.9900) =     19.473 ms/op
     p(99.9990) =     22.196 ms/op
     p(99.9999) =     22.807 ms/op
    p(100.0000) =     22.807 ms/op


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
# Warmup Iteration   1: 6.506 ±(99.9%) 0.074 ms/op
# Warmup Iteration   2: 5.385 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.857 ±(99.9%) 0.015 ms/op
Iteration   1: 4.853 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.511 ms/op
                 listUser·p0.50:   4.628 ms/op
                 listUser·p0.90:   6.062 ms/op
                 listUser·p0.95:   7.053 ms/op
                 listUser·p0.99:   9.159 ms/op
                 listUser·p0.999:  16.400 ms/op
                 listUser·p0.9999: 19.235 ms/op
                 listUser·p1.00:   19.661 ms/op

Iteration   2: 4.871 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.784 ms/op
                 listUser·p0.50:   4.678 ms/op
                 listUser·p0.90:   6.136 ms/op
                 listUser·p0.95:   6.971 ms/op
                 listUser·p0.99:   8.946 ms/op
                 listUser·p0.999:  17.236 ms/op
                 listUser·p0.9999: 21.117 ms/op
                 listUser·p1.00:   21.463 ms/op

Iteration   3: 4.815 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.092 ms/op
                 listUser·p0.50:   4.628 ms/op
                 listUser·p0.90:   5.956 ms/op
                 listUser·p0.95:   6.869 ms/op
                 listUser·p0.99:   8.602 ms/op
                 listUser·p0.999:  17.714 ms/op
                 listUser·p0.9999: 23.312 ms/op
                 listUser·p1.00:   24.642 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 197954
  mean =      4.846 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 177 
    [ 2.500,  5.000) = 135795 
    [ 5.000,  7.500) = 55711 
    [ 7.500, 10.000) = 5295 
    [10.000, 12.500) = 509 
    [12.500, 15.000) = 138 
    [15.000, 17.500) = 174 
    [17.500, 20.000) = 94 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.092 ms/op
     p(50.0000) =      4.645 ms/op
     p(90.0000) =      6.046 ms/op
     p(95.0000) =      6.963 ms/op
     p(99.0000) =      8.897 ms/op
     p(99.9000) =     17.203 ms/op
     p(99.9900) =     21.266 ms/op
     p(99.9990) =     24.642 ms/op
     p(99.9999) =     24.642 ms/op
    p(100.0000) =     24.642 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.093 ± 3.015  ops/ms
ClientGrpc.existUser                       thrpt       3   8.857 ± 2.731  ops/ms
ClientGrpc.getUser                         thrpt       3   8.218 ± 2.753  ops/ms
ClientGrpc.listUser                        thrpt       3   6.428 ± 1.646  ops/ms
ClientGrpc.createUser                       avgt       3   3.942 ± 0.284   ms/op
ClientGrpc.existUser                        avgt       3   3.644 ± 0.698   ms/op
ClientGrpc.getUser                          avgt       3   3.809 ± 0.448   ms/op
ClientGrpc.listUser                         avgt       3   4.952 ± 1.281   ms/op
ClientGrpc.createUser                     sample  246923   3.890 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.803           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.793           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.801           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.169           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.357           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.638           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.219           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.611           ms/op
ClientGrpc.existUser                      sample  264944   3.624 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.794           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.559           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.432           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.768           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.939           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.522           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          24.299           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          31.392           ms/op
ClientGrpc.getUser                        sample  247330   3.881 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.785           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.789           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.751           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.128           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.414           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.266           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.473           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.807           ms/op
ClientGrpc.listUser                       sample  197954   4.846 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.092           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.645           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.046           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.963           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.897           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.203           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.266           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.642           ms/op
