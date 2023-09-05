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
# Warmup Iteration   1: 3.033 ops/ms
# Warmup Iteration   2: 6.947 ops/ms
# Warmup Iteration   3: 8.494 ops/ms
Iteration   1: 8.684 ops/ms
Iteration   2: 8.962 ops/ms
Iteration   3: 9.125 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.924 ±(99.9%) 4.064 ops/ms [Average]
  (min, avg, max) = (8.684, 8.924, 9.125), stdev = 0.223
  CI (99.9%): [4.859, 12.988] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 6.024 ops/ms
# Warmup Iteration   2: 8.821 ops/ms
# Warmup Iteration   3: 9.376 ops/ms
Iteration   1: 9.351 ops/ms
Iteration   2: 9.771 ops/ms
Iteration   3: 9.421 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.514 ±(99.9%) 4.106 ops/ms [Average]
  (min, avg, max) = (9.351, 9.514, 9.771), stdev = 0.225
  CI (99.9%): [5.408, 13.620] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 5.562 ops/ms
# Warmup Iteration   2: 8.554 ops/ms
# Warmup Iteration   3: 8.925 ops/ms
Iteration   1: 8.685 ops/ms
Iteration   2: 8.754 ops/ms
Iteration   3: 8.628 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.689 ±(99.9%) 1.153 ops/ms [Average]
  (min, avg, max) = (8.628, 8.689, 8.754), stdev = 0.063
  CI (99.9%): [7.536, 9.841] (assumes normal distribution)


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
# Warmup Iteration   1: 4.357 ops/ms
# Warmup Iteration   2: 6.595 ops/ms
# Warmup Iteration   3: 6.896 ops/ms
Iteration   1: 6.829 ops/ms
Iteration   2: 6.908 ops/ms
Iteration   3: 7.056 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.931 ±(99.9%) 2.108 ops/ms [Average]
  (min, avg, max) = (6.829, 6.931, 7.056), stdev = 0.116
  CI (99.9%): [4.823, 9.039] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 4.901 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.755 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.594 ±(99.9%) 0.015 ms/op
Iteration   1: 3.463 ±(99.9%) 0.004 ms/op
Iteration   2: 3.398 ±(99.9%) 0.003 ms/op
Iteration   3: 3.404 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.422 ±(99.9%) 0.661 ms/op [Average]
  (min, avg, max) = (3.398, 3.422, 3.463), stdev = 0.036
  CI (99.9%): [2.761, 4.082] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.794 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.519 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.211 ±(99.9%) 0.003 ms/op
Iteration   1: 3.408 ±(99.9%) 0.003 ms/op
Iteration   2: 3.249 ±(99.9%) 0.004 ms/op
Iteration   3: 3.362 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.340 ±(99.9%) 1.496 ms/op [Average]
  (min, avg, max) = (3.249, 3.340, 3.408), stdev = 0.082
  CI (99.9%): [1.844, 4.836] (assumes normal distribution)


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
# Warmup Iteration   1: 5.321 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.691 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.682 ±(99.9%) 0.006 ms/op
Iteration   1: 3.586 ±(99.9%) 0.004 ms/op
Iteration   2: 3.543 ±(99.9%) 0.004 ms/op
Iteration   3: 3.803 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.644 ±(99.9%) 2.548 ms/op [Average]
  (min, avg, max) = (3.543, 3.644, 3.803), stdev = 0.140
  CI (99.9%): [1.096, 6.192] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 6.807 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 5.286 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 4.973 ±(99.9%) 0.019 ms/op
Iteration   1: 4.897 ±(99.9%) 0.015 ms/op
Iteration   2: 4.845 ±(99.9%) 0.014 ms/op
Iteration   3: 4.779 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.840 ±(99.9%) 1.084 ms/op [Average]
  (min, avg, max) = (4.779, 4.840, 4.897), stdev = 0.059
  CI (99.9%): [3.757, 5.924] (assumes normal distribution)


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
# Warmup Iteration   1: 5.270 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.965 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.693 ±(99.9%) 0.009 ms/op
Iteration   1: 3.666 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.854 ms/op
                 createUser·p0.50:   3.617 ms/op
                 createUser·p0.90:   4.571 ms/op
                 createUser·p0.95:   4.964 ms/op
                 createUser·p0.99:   6.509 ms/op
                 createUser·p0.999:  10.617 ms/op
                 createUser·p0.9999: 22.277 ms/op
                 createUser·p1.00:   23.953 ms/op

Iteration   2: 3.773 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.030 ms/op
                 createUser·p0.50:   3.695 ms/op
                 createUser·p0.90:   4.538 ms/op
                 createUser·p0.95:   4.891 ms/op
                 createUser·p0.99:   6.300 ms/op
                 createUser·p0.999:  10.568 ms/op
                 createUser·p0.9999: 21.922 ms/op
                 createUser·p1.00:   22.643 ms/op

Iteration   3: 3.608 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.802 ms/op
                 createUser·p0.50:   3.555 ms/op
                 createUser·p0.90:   4.268 ms/op
                 createUser·p0.95:   4.604 ms/op
                 createUser·p0.99:   6.341 ms/op
                 createUser·p0.999:  14.041 ms/op
                 createUser·p0.9999: 27.342 ms/op
                 createUser·p1.00:   28.541 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 260821
  mean =      3.681 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13017 
    [ 2.500,  5.000) = 237958 
    [ 5.000,  7.500) = 8505 
    [ 7.500, 10.000) = 913 
    [10.000, 12.500) = 150 
    [12.500, 15.000) = 118 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 70 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.802 ms/op
     p(50.0000) =      3.617 ms/op
     p(90.0000) =      4.473 ms/op
     p(95.0000) =      4.841 ms/op
     p(99.0000) =      6.373 ms/op
     p(99.9000) =     13.025 ms/op
     p(99.9900) =     23.820 ms/op
     p(99.9990) =     28.258 ms/op
     p(99.9999) =     28.541 ms/op
    p(100.0000) =     28.541 ms/op


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
# Warmup Iteration   1: 4.865 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.567 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.512 ±(99.9%) 0.008 ms/op
Iteration   1: 3.487 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.686 ms/op
                 existUser·p0.50:   3.424 ms/op
                 existUser·p0.90:   4.162 ms/op
                 existUser·p0.95:   4.538 ms/op
                 existUser·p0.99:   5.980 ms/op
                 existUser·p0.999:  12.379 ms/op
                 existUser·p0.9999: 18.672 ms/op
                 existUser·p1.00:   21.430 ms/op

Iteration   2: 3.455 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.629 ms/op
                 existUser·p0.50:   3.391 ms/op
                 existUser·p0.90:   4.133 ms/op
                 existUser·p0.95:   4.497 ms/op
                 existUser·p0.99:   5.849 ms/op
                 existUser·p0.999:  9.498 ms/op
                 existUser·p0.9999: 21.643 ms/op
                 existUser·p1.00:   22.217 ms/op

Iteration   3: 3.469 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.904 ms/op
                 existUser·p0.50:   3.416 ms/op
                 existUser·p0.90:   4.043 ms/op
                 existUser·p0.95:   4.407 ms/op
                 existUser·p0.99:   5.595 ms/op
                 existUser·p0.999:  12.517 ms/op
                 existUser·p0.9999: 22.548 ms/op
                 existUser·p1.00:   24.117 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 276500
  mean =      3.470 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10548 
    [ 2.500,  5.000) = 259780 
    [ 5.000,  7.500) = 5315 
    [ 7.500, 10.000) = 520 
    [10.000, 12.500) = 123 
    [12.500, 15.000) = 51 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 77 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.629 ms/op
     p(50.0000) =      3.408 ms/op
     p(90.0000) =      4.112 ms/op
     p(95.0000) =      4.481 ms/op
     p(99.0000) =      5.792 ms/op
     p(99.9000) =     11.665 ms/op
     p(99.9900) =     22.118 ms/op
     p(99.9990) =     24.042 ms/op
     p(99.9999) =     24.117 ms/op
    p(100.0000) =     24.117 ms/op


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
# Warmup Iteration   1: 5.284 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 3.807 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.716 ±(99.9%) 0.010 ms/op
Iteration   1: 3.671 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.044 ms/op
                 getUser·p0.50:   3.572 ms/op
                 getUser·p0.90:   4.416 ms/op
                 getUser·p0.95:   4.833 ms/op
                 getUser·p0.99:   6.912 ms/op
                 getUser·p0.999:  10.093 ms/op
                 getUser·p0.9999: 22.750 ms/op
                 getUser·p1.00:   23.134 ms/op

Iteration   2: 3.556 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.937 ms/op
                 getUser·p0.50:   3.486 ms/op
                 getUser·p0.90:   4.317 ms/op
                 getUser·p0.95:   4.588 ms/op
                 getUser·p0.99:   5.677 ms/op
                 getUser·p0.999:  9.126 ms/op
                 getUser·p0.9999: 17.072 ms/op
                 getUser·p1.00:   17.465 ms/op

Iteration   3: 3.517 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.722 ms/op
                 getUser·p0.50:   3.449 ms/op
                 getUser·p0.90:   4.170 ms/op
                 getUser·p0.95:   4.530 ms/op
                 getUser·p0.99:   6.234 ms/op
                 getUser·p0.999:  17.013 ms/op
                 getUser·p0.9999: 32.500 ms/op
                 getUser·p1.00:   34.275 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 268023
  mean =      3.580 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9087 
    [ 2.500,  5.000) = 251263 
    [ 5.000,  7.500) = 6412 
    [ 7.500, 10.000) = 1005 
    [10.000, 12.500) = 55 
    [12.500, 15.000) = 50 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 23 
    [32.500, 35.000) = 9 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.722 ms/op
     p(50.0000) =      3.506 ms/op
     p(90.0000) =      4.293 ms/op
     p(95.0000) =      4.645 ms/op
     p(99.0000) =      6.332 ms/op
     p(99.9000) =      9.945 ms/op
     p(99.9900) =     31.857 ms/op
     p(99.9990) =     34.079 ms/op
     p(99.9999) =     34.275 ms/op
    p(100.0000) =     34.275 ms/op


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
# Warmup Iteration   1: 6.683 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 4.976 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.723 ±(99.9%) 0.016 ms/op
Iteration   1: 4.802 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.036 ms/op
                 listUser·p0.50:   4.538 ms/op
                 listUser·p0.90:   6.267 ms/op
                 listUser·p0.95:   7.202 ms/op
                 listUser·p0.99:   9.404 ms/op
                 listUser·p0.999:  16.171 ms/op
                 listUser·p0.9999: 18.405 ms/op
                 listUser·p1.00:   21.463 ms/op

Iteration   2: 4.776 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.346 ms/op
                 listUser·p0.50:   4.514 ms/op
                 listUser·p0.90:   6.177 ms/op
                 listUser·p0.95:   7.102 ms/op
                 listUser·p0.99:   8.929 ms/op
                 listUser·p0.999:  18.940 ms/op
                 listUser·p0.9999: 26.264 ms/op
                 listUser·p1.00:   26.804 ms/op

Iteration   3: 4.758 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   0.812 ms/op
                 listUser·p0.50:   4.514 ms/op
                 listUser·p0.90:   6.169 ms/op
                 listUser·p0.95:   7.094 ms/op
                 listUser·p0.99:   8.962 ms/op
                 listUser·p0.999:  19.718 ms/op
                 listUser·p0.9999: 24.150 ms/op
                 listUser·p1.00:   25.494 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 200803
  mean =      4.779 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 500 
    [ 2.500,  5.000) = 147147 
    [ 5.000,  7.500) = 45995 
    [ 7.500, 10.000) = 5840 
    [10.000, 12.500) = 775 
    [12.500, 15.000) = 182 
    [15.000, 17.500) = 115 
    [17.500, 20.000) = 156 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.812 ms/op
     p(50.0000) =      4.522 ms/op
     p(90.0000) =      6.201 ms/op
     p(95.0000) =      7.127 ms/op
     p(99.0000) =      9.126 ms/op
     p(99.9000) =     18.645 ms/op
     p(99.9900) =     25.455 ms/op
     p(99.9990) =     26.673 ms/op
     p(99.9999) =     26.804 ms/op
    p(100.0000) =     26.804 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.924 ± 4.064  ops/ms
ClientGrpc.existUser                       thrpt       3   9.514 ± 4.106  ops/ms
ClientGrpc.getUser                         thrpt       3   8.689 ± 1.153  ops/ms
ClientGrpc.listUser                        thrpt       3   6.931 ± 2.108  ops/ms
ClientGrpc.createUser                       avgt       3   3.422 ± 0.661   ms/op
ClientGrpc.existUser                        avgt       3   3.340 ± 1.496   ms/op
ClientGrpc.getUser                          avgt       3   3.644 ± 2.548   ms/op
ClientGrpc.listUser                         avgt       3   4.840 ± 1.084   ms/op
ClientGrpc.createUser                     sample  260821   3.681 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.802           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.617           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.473           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.841           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.373           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.025           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.820           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          28.541           ms/op
ClientGrpc.existUser                      sample  276500   3.470 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.629           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.408           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.112           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.481           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.792           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.665           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          22.118           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          24.117           ms/op
ClientGrpc.getUser                        sample  268023   3.580 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.722           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.506           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.293           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.645           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.332           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.945           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          31.857           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          34.275           ms/op
ClientGrpc.listUser                       sample  200803   4.779 ± 0.010   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.812           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.522           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.201           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.127           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.126           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.645           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.455           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.804           ms/op
