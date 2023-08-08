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
# Warmup Iteration   1: 2.211 ops/ms
# Warmup Iteration   2: 5.624 ops/ms
# Warmup Iteration   3: 7.102 ops/ms
Iteration   1: 7.228 ops/ms
Iteration   2: 7.749 ops/ms
Iteration   3: 7.392 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.456 ±(99.9%) 4.858 ops/ms [Average]
  (min, avg, max) = (7.228, 7.456, 7.749), stdev = 0.266
  CI (99.9%): [2.598, 12.314] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.496 ops/ms
# Warmup Iteration   2: 7.432 ops/ms
# Warmup Iteration   3: 7.485 ops/ms
Iteration   1: 7.830 ops/ms
Iteration   2: 7.866 ops/ms
Iteration   3: 7.827 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.841 ±(99.9%) 0.391 ops/ms [Average]
  (min, avg, max) = (7.827, 7.841, 7.866), stdev = 0.021
  CI (99.9%): [7.450, 8.232] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 4.304 ops/ms
# Warmup Iteration   2: 7.112 ops/ms
# Warmup Iteration   3: 7.482 ops/ms
Iteration   1: 7.784 ops/ms
Iteration   2: 7.642 ops/ms
Iteration   3: 7.874 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.767 ±(99.9%) 2.132 ops/ms [Average]
  (min, avg, max) = (7.642, 7.767, 7.874), stdev = 0.117
  CI (99.9%): [5.634, 9.899] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.621 ops/ms
# Warmup Iteration   2: 5.152 ops/ms
# Warmup Iteration   3: 5.654 ops/ms
Iteration   1: 5.792 ops/ms
Iteration   2: 5.790 ops/ms
Iteration   3: 5.900 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.827 ±(99.9%) 1.150 ops/ms [Average]
  (min, avg, max) = (5.790, 5.827, 5.900), stdev = 0.063
  CI (99.9%): [4.677, 6.978] (assumes normal distribution)


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
# Warmup Iteration   1: 5.959 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.420 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.311 ±(99.9%) 0.004 ms/op
Iteration   1: 4.168 ±(99.9%) 0.002 ms/op
Iteration   2: 4.403 ±(99.9%) 0.003 ms/op
Iteration   3: 4.158 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.243 ±(99.9%) 2.530 ms/op [Average]
  (min, avg, max) = (4.158, 4.243, 4.403), stdev = 0.139
  CI (99.9%): [1.713, 6.772] (assumes normal distribution)


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
# Warmup Iteration   1: 6.218 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.414 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.080 ±(99.9%) 0.004 ms/op
Iteration   1: 3.863 ±(99.9%) 0.004 ms/op
Iteration   2: 3.798 ±(99.9%) 0.003 ms/op
Iteration   3: 3.726 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.796 ±(99.9%) 1.251 ms/op [Average]
  (min, avg, max) = (3.726, 3.796, 3.863), stdev = 0.069
  CI (99.9%): [2.545, 5.047] (assumes normal distribution)


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
# Warmup Iteration   1: 6.406 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.410 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.277 ±(99.9%) 0.003 ms/op
Iteration   1: 4.205 ±(99.9%) 0.004 ms/op
Iteration   2: 4.188 ±(99.9%) 0.003 ms/op
Iteration   3: 4.150 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.181 ±(99.9%) 0.511 ms/op [Average]
  (min, avg, max) = (4.150, 4.181, 4.205), stdev = 0.028
  CI (99.9%): [3.670, 4.692] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 7.742 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 6.068 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 5.480 ±(99.9%) 0.017 ms/op
Iteration   1: 5.539 ±(99.9%) 0.018 ms/op
Iteration   2: 5.448 ±(99.9%) 0.019 ms/op
Iteration   3: 5.405 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.464 ±(99.9%) 1.244 ms/op [Average]
  (min, avg, max) = (5.405, 5.464, 5.539), stdev = 0.068
  CI (99.9%): [4.220, 6.708] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 6.685 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 4.686 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.325 ±(99.9%) 0.012 ms/op
Iteration   1: 4.208 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.135 ms/op
                 createUser·p0.50:   4.116 ms/op
                 createUser·p0.90:   5.145 ms/op
                 createUser·p0.95:   5.587 ms/op
                 createUser·p0.99:   7.143 ms/op
                 createUser·p0.999:  11.780 ms/op
                 createUser·p0.9999: 17.957 ms/op
                 createUser·p1.00:   18.252 ms/op

Iteration   2: 4.249 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.840 ms/op
                 createUser·p0.50:   4.125 ms/op
                 createUser·p0.90:   5.317 ms/op
                 createUser·p0.95:   5.685 ms/op
                 createUser·p0.99:   6.930 ms/op
                 createUser·p0.999:  16.241 ms/op
                 createUser·p0.9999: 20.281 ms/op
                 createUser·p1.00:   21.103 ms/op

Iteration   3: 4.150 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.831 ms/op
                 createUser·p0.50:   4.100 ms/op
                 createUser·p0.90:   5.120 ms/op
                 createUser·p0.95:   5.439 ms/op
                 createUser·p0.99:   6.701 ms/op
                 createUser·p0.999:  13.156 ms/op
                 createUser·p0.9999: 22.577 ms/op
                 createUser·p1.00:   22.610 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 228474
  mean =      4.202 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4564 
    [ 2.500,  5.000) = 191836 
    [ 5.000,  7.500) = 30388 
    [ 7.500, 10.000) = 1167 
    [10.000, 12.500) = 281 
    [12.500, 15.000) = 55 
    [15.000, 17.500) = 68 
    [17.500, 20.000) = 83 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.831 ms/op
     p(50.0000) =      4.112 ms/op
     p(90.0000) =      5.194 ms/op
     p(95.0000) =      5.571 ms/op
     p(99.0000) =      6.906 ms/op
     p(99.9000) =     13.345 ms/op
     p(99.9900) =     21.272 ms/op
     p(99.9990) =     22.610 ms/op
     p(99.9999) =     22.610 ms/op
    p(100.0000) =     22.610 ms/op


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
# Warmup Iteration   1: 6.182 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 4.432 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.072 ±(99.9%) 0.010 ms/op
Iteration   1: 4.101 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.009 ms/op
                 existUser·p0.50:   4.002 ms/op
                 existUser·p0.90:   4.981 ms/op
                 existUser·p0.95:   5.317 ms/op
                 existUser·p0.99:   6.678 ms/op
                 existUser·p0.999:  12.010 ms/op
                 existUser·p0.9999: 15.512 ms/op
                 existUser·p1.00:   17.302 ms/op

Iteration   2: 3.942 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.143 ms/op
                 existUser·p0.50:   3.867 ms/op
                 existUser·p0.90:   5.039 ms/op
                 existUser·p0.95:   5.485 ms/op
                 existUser·p0.99:   7.029 ms/op
                 existUser·p0.999:  11.911 ms/op
                 existUser·p0.9999: 20.087 ms/op
                 existUser·p1.00:   20.185 ms/op

Iteration   3: 3.912 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.124 ms/op
                 existUser·p0.50:   3.838 ms/op
                 existUser·p0.90:   4.751 ms/op
                 existUser·p0.95:   5.120 ms/op
                 existUser·p0.99:   6.332 ms/op
                 existUser·p0.999:  9.998 ms/op
                 existUser·p0.9999: 20.573 ms/op
                 existUser·p1.00:   20.840 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 240855
  mean =      3.983 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8492 
    [ 2.500,  5.000) = 211124 
    [ 5.000,  7.500) = 19680 
    [ 7.500, 10.000) = 1072 
    [10.000, 12.500) = 320 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.009 ms/op
     p(50.0000) =      3.895 ms/op
     p(90.0000) =      4.932 ms/op
     p(95.0000) =      5.318 ms/op
     p(99.0000) =      6.693 ms/op
     p(99.9000) =     11.354 ms/op
     p(99.9900) =     20.120 ms/op
     p(99.9990) =     20.729 ms/op
     p(99.9999) =     20.840 ms/op
    p(100.0000) =     20.840 ms/op


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
# Warmup Iteration   1: 6.052 ±(99.9%) 0.071 ms/op
# Warmup Iteration   2: 4.428 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.255 ±(99.9%) 0.012 ms/op
Iteration   1: 4.220 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.126 ms/op
                 getUser·p0.50:   4.116 ms/op
                 getUser·p0.90:   5.235 ms/op
                 getUser·p0.95:   5.587 ms/op
                 getUser·p0.99:   7.202 ms/op
                 getUser·p0.999:  11.751 ms/op
                 getUser·p0.9999: 16.611 ms/op
                 getUser·p1.00:   16.941 ms/op

Iteration   2: 4.170 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.174 ms/op
                 getUser·p0.50:   4.067 ms/op
                 getUser·p0.90:   5.177 ms/op
                 getUser·p0.95:   5.562 ms/op
                 getUser·p0.99:   6.857 ms/op
                 getUser·p0.999:  13.096 ms/op
                 getUser·p0.9999: 21.223 ms/op
                 getUser·p1.00:   21.856 ms/op

Iteration   3: 4.143 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.264 ms/op
                 getUser·p0.50:   4.059 ms/op
                 getUser·p0.90:   4.932 ms/op
                 getUser·p0.95:   5.243 ms/op
                 getUser·p0.99:   6.359 ms/op
                 getUser·p0.999:  10.729 ms/op
                 getUser·p0.9999: 32.834 ms/op
                 getUser·p1.00:   33.554 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 229657
  mean =      4.177 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3063 
    [ 2.500,  5.000) = 198277 
    [ 5.000,  7.500) = 26666 
    [ 7.500, 10.000) = 1135 
    [10.000, 12.500) = 301 
    [12.500, 15.000) = 87 
    [15.000, 17.500) = 63 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 19 
    [32.500, 35.000) = 13 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.126 ms/op
     p(50.0000) =      4.080 ms/op
     p(90.0000) =      5.120 ms/op
     p(95.0000) =      5.480 ms/op
     p(99.0000) =      6.799 ms/op
     p(99.9000) =     12.179 ms/op
     p(99.9900) =     31.721 ms/op
     p(99.9990) =     33.329 ms/op
     p(99.9999) =     33.554 ms/op
    p(100.0000) =     33.554 ms/op


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
# Warmup Iteration   1: 7.599 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 6.032 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 5.668 ±(99.9%) 0.020 ms/op
Iteration   1: 5.461 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.954 ms/op
                 listUser·p0.50:   5.243 ms/op
                 listUser·p0.90:   6.783 ms/op
                 listUser·p0.95:   7.889 ms/op
                 listUser·p0.99:   9.945 ms/op
                 listUser·p0.999:  15.991 ms/op
                 listUser·p0.9999: 19.108 ms/op
                 listUser·p1.00:   19.661 ms/op

Iteration   2: 5.502 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.706 ms/op
                 listUser·p0.50:   5.276 ms/op
                 listUser·p0.90:   6.799 ms/op
                 listUser·p0.95:   7.766 ms/op
                 listUser·p0.99:   9.880 ms/op
                 listUser·p0.999:  19.464 ms/op
                 listUser·p0.9999: 22.065 ms/op
                 listUser·p1.00:   24.052 ms/op

Iteration   3: 5.347 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.477 ms/op
                 listUser·p0.50:   5.120 ms/op
                 listUser·p0.90:   6.783 ms/op
                 listUser·p0.95:   7.799 ms/op
                 listUser·p0.99:   10.043 ms/op
                 listUser·p0.999:  19.759 ms/op
                 listUser·p0.9999: 23.627 ms/op
                 listUser·p1.00:   24.216 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 176612
  mean =      5.436 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 66 
    [ 2.500,  5.000) = 68775 
    [ 5.000,  7.500) = 96807 
    [ 7.500, 10.000) = 9257 
    [10.000, 12.500) = 1180 
    [12.500, 15.000) = 206 
    [15.000, 17.500) = 102 
    [17.500, 20.000) = 139 
    [20.000, 22.500) = 70 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.477 ms/op
     p(50.0000) =      5.218 ms/op
     p(90.0000) =      6.791 ms/op
     p(95.0000) =      7.815 ms/op
     p(99.0000) =      9.945 ms/op
     p(99.9000) =     18.461 ms/op
     p(99.9900) =     21.922 ms/op
     p(99.9990) =     24.140 ms/op
     p(99.9999) =     24.216 ms/op
    p(100.0000) =     24.216 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.456 ± 4.858  ops/ms
ClientGrpc.existUser                       thrpt       3   7.841 ± 0.391  ops/ms
ClientGrpc.getUser                         thrpt       3   7.767 ± 2.132  ops/ms
ClientGrpc.listUser                        thrpt       3   5.827 ± 1.150  ops/ms
ClientGrpc.createUser                       avgt       3   4.243 ± 2.530   ms/op
ClientGrpc.existUser                        avgt       3   3.796 ± 1.251   ms/op
ClientGrpc.getUser                          avgt       3   4.181 ± 0.511   ms/op
ClientGrpc.listUser                         avgt       3   5.464 ± 1.244   ms/op
ClientGrpc.createUser                     sample  228474   4.202 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.831           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.112           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.194           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.571           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.906           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.345           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.272           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.610           ms/op
ClientGrpc.existUser                      sample  240855   3.983 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           1.009           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.895           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.932           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.318           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.693           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.354           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.120           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.840           ms/op
ClientGrpc.getUser                        sample  229657   4.177 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.126           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.080           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.120           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.480           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.799           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.179           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          31.721           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          33.554           ms/op
ClientGrpc.listUser                       sample  176612   5.436 ± 0.010   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.477           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.218           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.791           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.815           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.945           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.461           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.922           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.216           ms/op
