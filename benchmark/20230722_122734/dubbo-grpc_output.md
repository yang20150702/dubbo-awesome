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
# Warmup Iteration   1: 3.380 ops/ms
# Warmup Iteration   2: 7.200 ops/ms
# Warmup Iteration   3: 8.129 ops/ms
Iteration   1: 8.141 ops/ms
Iteration   2: 8.206 ops/ms
Iteration   3: 8.241 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.196 ±(99.9%) 0.933 ops/ms [Average]
  (min, avg, max) = (8.141, 8.196, 8.241), stdev = 0.051
  CI (99.9%): [7.263, 9.129] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 6.088 ops/ms
# Warmup Iteration   2: 8.318 ops/ms
# Warmup Iteration   3: 8.820 ops/ms
Iteration   1: 8.815 ops/ms
Iteration   2: 9.089 ops/ms
Iteration   3: 9.034 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.979 ±(99.9%) 2.640 ops/ms [Average]
  (min, avg, max) = (8.815, 8.979, 9.089), stdev = 0.145
  CI (99.9%): [6.340, 11.619] (assumes normal distribution)


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
# Warmup Iteration   1: 5.221 ops/ms
# Warmup Iteration   2: 8.065 ops/ms
# Warmup Iteration   3: 8.128 ops/ms
Iteration   1: 8.310 ops/ms
Iteration   2: 8.417 ops/ms
Iteration   3: 8.192 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.306 ±(99.9%) 2.048 ops/ms [Average]
  (min, avg, max) = (8.192, 8.306, 8.417), stdev = 0.112
  CI (99.9%): [6.258, 10.355] (assumes normal distribution)


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
# Warmup Iteration   1: 4.389 ops/ms
# Warmup Iteration   2: 6.012 ops/ms
# Warmup Iteration   3: 6.338 ops/ms
Iteration   1: 6.480 ops/ms
Iteration   2: 6.645 ops/ms
Iteration   3: 6.336 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.487 ±(99.9%) 2.824 ops/ms [Average]
  (min, avg, max) = (6.336, 6.487, 6.645), stdev = 0.155
  CI (99.9%): [3.663, 9.312] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.443 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.053 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.805 ±(99.9%) 0.003 ms/op
Iteration   1: 3.813 ±(99.9%) 0.006 ms/op
Iteration   2: 3.695 ±(99.9%) 0.003 ms/op
Iteration   3: 3.782 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.763 ±(99.9%) 1.117 ms/op [Average]
  (min, avg, max) = (3.695, 3.763, 3.813), stdev = 0.061
  CI (99.9%): [2.646, 4.881] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.923 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.802 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.595 ±(99.9%) 0.005 ms/op
Iteration   1: 3.506 ±(99.9%) 0.004 ms/op
Iteration   2: 3.600 ±(99.9%) 0.003 ms/op
Iteration   3: 3.572 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.559 ±(99.9%) 0.887 ms/op [Average]
  (min, avg, max) = (3.506, 3.559, 3.600), stdev = 0.049
  CI (99.9%): [2.672, 4.447] (assumes normal distribution)


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
# Warmup Iteration   1: 5.444 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.901 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.821 ±(99.9%) 0.003 ms/op
Iteration   1: 3.876 ±(99.9%) 0.003 ms/op
Iteration   2: 3.824 ±(99.9%) 0.002 ms/op
Iteration   3: 3.676 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.792 ±(99.9%) 1.900 ms/op [Average]
  (min, avg, max) = (3.676, 3.792, 3.876), stdev = 0.104
  CI (99.9%): [1.892, 5.692] (assumes normal distribution)


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
# Warmup Iteration   1: 5.972 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 5.300 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.891 ±(99.9%) 0.013 ms/op
Iteration   1: 4.926 ±(99.9%) 0.024 ms/op
Iteration   2: 4.995 ±(99.9%) 0.012 ms/op
Iteration   3: 4.970 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.964 ±(99.9%) 0.635 ms/op [Average]
  (min, avg, max) = (4.926, 4.964, 4.995), stdev = 0.035
  CI (99.9%): [4.329, 5.599] (assumes normal distribution)


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
# Warmup Iteration   1: 5.177 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 4.092 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.797 ±(99.9%) 0.010 ms/op
Iteration   1: 3.898 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.899 ms/op
                 createUser·p0.50:   3.781 ms/op
                 createUser·p0.90:   4.760 ms/op
                 createUser·p0.95:   5.192 ms/op
                 createUser·p0.99:   6.922 ms/op
                 createUser·p0.999:  10.846 ms/op
                 createUser·p0.9999: 16.571 ms/op
                 createUser·p1.00:   16.810 ms/op

Iteration   2: 3.819 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.167 ms/op
                 createUser·p0.50:   3.715 ms/op
                 createUser·p0.90:   4.596 ms/op
                 createUser·p0.95:   5.046 ms/op
                 createUser·p0.99:   6.660 ms/op
                 createUser·p0.999:  10.657 ms/op
                 createUser·p0.9999: 23.286 ms/op
                 createUser·p1.00:   23.757 ms/op

Iteration   3: 3.780 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.858 ms/op
                 createUser·p0.50:   3.658 ms/op
                 createUser·p0.90:   4.563 ms/op
                 createUser·p0.95:   4.956 ms/op
                 createUser·p0.99:   6.382 ms/op
                 createUser·p0.999:  14.434 ms/op
                 createUser·p0.9999: 29.229 ms/op
                 createUser·p1.00:   31.359 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 250467
  mean =      3.832 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5308 
    [ 2.500,  5.000) = 231360 
    [ 5.000,  7.500) = 12315 
    [ 7.500, 10.000) = 1049 
    [10.000, 12.500) = 216 
    [12.500, 15.000) = 85 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 27 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.858 ms/op
     p(50.0000) =      3.715 ms/op
     p(90.0000) =      4.645 ms/op
     p(95.0000) =      5.063 ms/op
     p(99.0000) =      6.668 ms/op
     p(99.9000) =     11.428 ms/op
     p(99.9900) =     29.164 ms/op
     p(99.9990) =     31.277 ms/op
     p(99.9999) =     31.359 ms/op
    p(100.0000) =     31.359 ms/op


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
# Warmup Iteration   1: 4.893 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.898 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.636 ±(99.9%) 0.008 ms/op
Iteration   1: 3.623 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.928 ms/op
                 existUser·p0.50:   3.559 ms/op
                 existUser·p0.90:   4.293 ms/op
                 existUser·p0.95:   4.645 ms/op
                 existUser·p0.99:   5.808 ms/op
                 existUser·p0.999:  10.800 ms/op
                 existUser·p0.9999: 15.029 ms/op
                 existUser·p1.00:   15.254 ms/op

Iteration   2: 3.556 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.018 ms/op
                 existUser·p0.50:   3.498 ms/op
                 existUser·p0.90:   4.219 ms/op
                 existUser·p0.95:   4.612 ms/op
                 existUser·p0.99:   5.846 ms/op
                 existUser·p0.999:  9.586 ms/op
                 existUser·p0.9999: 17.826 ms/op
                 existUser·p1.00:   18.285 ms/op

Iteration   3: 3.616 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.871 ms/op
                 existUser·p0.50:   3.527 ms/op
                 existUser·p0.90:   4.350 ms/op
                 existUser·p0.95:   4.702 ms/op
                 existUser·p0.99:   5.849 ms/op
                 existUser·p0.999:  10.676 ms/op
                 existUser·p0.9999: 20.087 ms/op
                 existUser·p1.00:   21.660 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 266827
  mean =      3.598 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7556 
    [ 2.500,  5.000) = 251724 
    [ 5.000,  7.500) = 6679 
    [ 7.500, 10.000) = 587 
    [10.000, 12.500) = 125 
    [12.500, 15.000) = 81 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.871 ms/op
     p(50.0000) =      3.527 ms/op
     p(90.0000) =      4.293 ms/op
     p(95.0000) =      4.653 ms/op
     p(99.0000) =      5.833 ms/op
     p(99.9000) =     10.226 ms/op
     p(99.9900) =     18.983 ms/op
     p(99.9990) =     21.583 ms/op
     p(99.9999) =     21.660 ms/op
    p(100.0000) =     21.660 ms/op


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
# Warmup Iteration   1: 5.113 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.123 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.852 ±(99.9%) 0.010 ms/op
Iteration   1: 3.926 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.965 ms/op
                 getUser·p0.50:   3.805 ms/op
                 getUser·p0.90:   4.801 ms/op
                 getUser·p0.95:   5.243 ms/op
                 getUser·p0.99:   7.281 ms/op
                 getUser·p0.999:  13.908 ms/op
                 getUser·p0.9999: 20.045 ms/op
                 getUser·p1.00:   20.382 ms/op

Iteration   2: 3.936 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.038 ms/op
                 getUser·p0.50:   3.817 ms/op
                 getUser·p0.90:   4.899 ms/op
                 getUser·p0.95:   5.374 ms/op
                 getUser·p0.99:   7.160 ms/op
                 getUser·p0.999:  12.829 ms/op
                 getUser·p0.9999: 18.342 ms/op
                 getUser·p1.00:   27.754 ms/op

Iteration   3: 3.823 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.130 ms/op
                 getUser·p0.50:   3.719 ms/op
                 getUser·p0.90:   4.579 ms/op
                 getUser·p0.95:   4.915 ms/op
                 getUser·p0.99:   5.988 ms/op
                 getUser·p0.999:  9.257 ms/op
                 getUser·p0.9999: 22.041 ms/op
                 getUser·p1.00:   22.708 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 246407
  mean =      3.895 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6240 
    [ 2.500,  5.000) = 223776 
    [ 5.000,  7.500) = 14812 
    [ 7.500, 10.000) = 1150 
    [10.000, 12.500) = 169 
    [12.500, 15.000) = 105 
    [15.000, 17.500) = 75 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.965 ms/op
     p(50.0000) =      3.777 ms/op
     p(90.0000) =      4.760 ms/op
     p(95.0000) =      5.186 ms/op
     p(99.0000) =      6.824 ms/op
     p(99.9000) =     12.756 ms/op
     p(99.9900) =     21.463 ms/op
     p(99.9990) =     22.647 ms/op
     p(99.9999) =     27.754 ms/op
    p(100.0000) =     27.754 ms/op


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
# Warmup Iteration   1: 6.940 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 5.430 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.899 ±(99.9%) 0.015 ms/op
Iteration   1: 4.964 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   0.974 ms/op
                 listUser·p0.50:   4.686 ms/op
                 listUser·p0.90:   6.480 ms/op
                 listUser·p0.95:   7.422 ms/op
                 listUser·p0.99:   9.241 ms/op
                 listUser·p0.999:  14.811 ms/op
                 listUser·p0.9999: 17.174 ms/op
                 listUser·p1.00:   19.137 ms/op

Iteration   2: 4.998 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.182 ms/op
                 listUser·p0.50:   4.751 ms/op
                 listUser·p0.90:   6.349 ms/op
                 listUser·p0.95:   7.225 ms/op
                 listUser·p0.99:   9.028 ms/op
                 listUser·p0.999:  18.512 ms/op
                 listUser·p0.9999: 21.587 ms/op
                 listUser·p1.00:   22.053 ms/op

Iteration   3: 4.912 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   0.921 ms/op
                 listUser·p0.50:   4.678 ms/op
                 listUser·p0.90:   6.283 ms/op
                 listUser·p0.95:   7.029 ms/op
                 listUser·p0.99:   8.880 ms/op
                 listUser·p0.999:  22.731 ms/op
                 listUser·p0.9999: 29.999 ms/op
                 listUser·p1.00:   33.358 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 193589
  mean =      4.958 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 427 
    [ 2.500,  5.000) = 126750 
    [ 5.000,  7.500) = 58742 
    [ 7.500, 10.000) = 6625 
    [10.000, 12.500) = 629 
    [12.500, 15.000) = 125 
    [15.000, 17.500) = 95 
    [17.500, 20.000) = 68 
    [20.000, 22.500) = 56 
    [22.500, 25.000) = 39 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 26 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.921 ms/op
     p(50.0000) =      4.710 ms/op
     p(90.0000) =      6.357 ms/op
     p(95.0000) =      7.217 ms/op
     p(99.0000) =      9.060 ms/op
     p(99.9000) =     17.793 ms/op
     p(99.9900) =     29.196 ms/op
     p(99.9990) =     33.112 ms/op
     p(99.9999) =     33.358 ms/op
    p(100.0000) =     33.358 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.196 ± 0.933  ops/ms
ClientGrpc.existUser                       thrpt       3   8.979 ± 2.640  ops/ms
ClientGrpc.getUser                         thrpt       3   8.306 ± 2.048  ops/ms
ClientGrpc.listUser                        thrpt       3   6.487 ± 2.824  ops/ms
ClientGrpc.createUser                       avgt       3   3.763 ± 1.117   ms/op
ClientGrpc.existUser                        avgt       3   3.559 ± 0.887   ms/op
ClientGrpc.getUser                          avgt       3   3.792 ± 1.900   ms/op
ClientGrpc.listUser                         avgt       3   4.964 ± 0.635   ms/op
ClientGrpc.createUser                     sample  250467   3.832 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.858           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.715           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.645           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.063           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.668           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.428           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          29.164           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          31.359           ms/op
ClientGrpc.existUser                      sample  266827   3.598 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.871           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.527           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.293           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.653           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.833           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.226           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.983           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.660           ms/op
ClientGrpc.getUser                        sample  246407   3.895 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.965           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.777           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.760           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.186           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.824           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.756           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.463           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          27.754           ms/op
ClientGrpc.listUser                       sample  193589   4.958 ± 0.010   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.921           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.710           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.357           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.217           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.060           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.793           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          29.196           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          33.358           ms/op
