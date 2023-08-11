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
# Warmup Iteration   1: 1.972 ops/ms
# Warmup Iteration   2: 5.016 ops/ms
# Warmup Iteration   3: 6.853 ops/ms
Iteration   1: 7.189 ops/ms
Iteration   2: 7.319 ops/ms
Iteration   3: 7.220 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.243 ±(99.9%) 1.246 ops/ms [Average]
  (min, avg, max) = (7.189, 7.243, 7.319), stdev = 0.068
  CI (99.9%): [5.997, 8.488] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.640 ops/ms
# Warmup Iteration   2: 6.936 ops/ms
# Warmup Iteration   3: 7.553 ops/ms
Iteration   1: 7.881 ops/ms
Iteration   2: 7.763 ops/ms
Iteration   3: 7.931 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.858 ±(99.9%) 1.577 ops/ms [Average]
  (min, avg, max) = (7.763, 7.858, 7.931), stdev = 0.086
  CI (99.9%): [6.282, 9.435] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 4.277 ops/ms
# Warmup Iteration   2: 6.712 ops/ms
# Warmup Iteration   3: 7.159 ops/ms
Iteration   1: 7.380 ops/ms
Iteration   2: 7.391 ops/ms
Iteration   3: 7.210 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.327 ±(99.9%) 1.850 ops/ms [Average]
  (min, avg, max) = (7.210, 7.327, 7.391), stdev = 0.101
  CI (99.9%): [5.477, 9.177] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 3.562 ops/ms
# Warmup Iteration   2: 5.114 ops/ms
# Warmup Iteration   3: 5.566 ops/ms
Iteration   1: 5.674 ops/ms
Iteration   2: 5.836 ops/ms
Iteration   3: 5.861 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.791 ±(99.9%) 1.848 ops/ms [Average]
  (min, avg, max) = (5.674, 5.791, 5.861), stdev = 0.101
  CI (99.9%): [3.943, 7.638] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.883 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.887 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.603 ±(99.9%) 0.010 ms/op
Iteration   1: 4.443 ±(99.9%) 0.004 ms/op
Iteration   2: 4.441 ±(99.9%) 0.003 ms/op
Iteration   3: 4.395 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.426 ±(99.9%) 0.498 ms/op [Average]
  (min, avg, max) = (4.395, 4.426, 4.443), stdev = 0.027
  CI (99.9%): [3.928, 4.924] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 6.500 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.475 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.177 ±(99.9%) 0.005 ms/op
Iteration   1: 4.182 ±(99.9%) 0.004 ms/op
Iteration   2: 3.988 ±(99.9%) 0.004 ms/op
Iteration   3: 4.090 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.087 ±(99.9%) 1.766 ms/op [Average]
  (min, avg, max) = (3.988, 4.087, 4.182), stdev = 0.097
  CI (99.9%): [2.321, 5.852] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 6.869 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.698 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 4.476 ±(99.9%) 0.005 ms/op
Iteration   1: 4.349 ±(99.9%) 0.003 ms/op
Iteration   2: 4.256 ±(99.9%) 0.005 ms/op
Iteration   3: 4.381 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.329 ±(99.9%) 1.185 ms/op [Average]
  (min, avg, max) = (4.256, 4.329, 4.381), stdev = 0.065
  CI (99.9%): [3.144, 5.514] (assumes normal distribution)


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
# Warmup Iteration   1: 8.892 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 5.910 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 5.569 ±(99.9%) 0.022 ms/op
Iteration   1: 5.610 ±(99.9%) 0.023 ms/op
Iteration   2: 5.558 ±(99.9%) 0.013 ms/op
Iteration   3: 5.474 ±(99.9%) 0.024 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.547 ±(99.9%) 1.249 ms/op [Average]
  (min, avg, max) = (5.474, 5.547, 5.610), stdev = 0.068
  CI (99.9%): [4.298, 6.797] (assumes normal distribution)


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
# Warmup Iteration   1: 6.756 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 4.880 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.551 ±(99.9%) 0.016 ms/op
Iteration   1: 4.381 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   0.925 ms/op
                 createUser·p0.50:   4.202 ms/op
                 createUser·p0.90:   5.579 ms/op
                 createUser·p0.95:   6.136 ms/op
                 createUser·p0.99:   8.178 ms/op
                 createUser·p0.999:  13.777 ms/op
                 createUser·p0.9999: 27.298 ms/op
                 createUser·p1.00:   27.951 ms/op

Iteration   2: 4.391 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   0.809 ms/op
                 createUser·p0.50:   4.243 ms/op
                 createUser·p0.90:   5.480 ms/op
                 createUser·p0.95:   5.997 ms/op
                 createUser·p0.99:   8.192 ms/op
                 createUser·p0.999:  12.979 ms/op
                 createUser·p0.9999: 25.999 ms/op
                 createUser·p1.00:   26.378 ms/op

Iteration   3: 4.388 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   0.948 ms/op
                 createUser·p0.50:   4.194 ms/op
                 createUser·p0.90:   5.497 ms/op
                 createUser·p0.95:   6.119 ms/op
                 createUser·p0.99:   9.329 ms/op
                 createUser·p0.999:  17.857 ms/op
                 createUser·p0.9999: 27.016 ms/op
                 createUser·p1.00:   27.394 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 218941
  mean =      4.387 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3614 
    [ 2.500,  5.000) = 172928 
    [ 5.000,  7.500) = 38803 
    [ 7.500, 10.000) = 2335 
    [10.000, 12.500) = 783 
    [12.500, 15.000) = 273 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 60 
    [25.000, 27.500) = 64 

  Percentiles, ms/op:
      p(0.0000) =      0.809 ms/op
     p(50.0000) =      4.211 ms/op
     p(90.0000) =      5.521 ms/op
     p(95.0000) =      6.087 ms/op
     p(99.0000) =      8.585 ms/op
     p(99.9000) =     14.420 ms/op
     p(99.9900) =     26.647 ms/op
     p(99.9990) =     27.901 ms/op
     p(99.9999) =     27.951 ms/op
    p(100.0000) =     27.951 ms/op


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
# Warmup Iteration   1: 6.174 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 4.378 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.193 ±(99.9%) 0.013 ms/op
Iteration   1: 4.123 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.081 ms/op
                 existUser·p0.50:   3.957 ms/op
                 existUser·p0.90:   5.079 ms/op
                 existUser·p0.95:   5.669 ms/op
                 existUser·p0.99:   8.569 ms/op
                 existUser·p0.999:  13.917 ms/op
                 existUser·p0.9999: 18.350 ms/op
                 existUser·p1.00:   22.970 ms/op

Iteration   2: 4.047 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.032 ms/op
                 existUser·p0.50:   3.957 ms/op
                 existUser·p0.90:   5.030 ms/op
                 existUser·p0.95:   5.464 ms/op
                 existUser·p0.99:   6.873 ms/op
                 existUser·p0.999:  12.349 ms/op
                 existUser·p0.9999: 23.658 ms/op
                 existUser·p1.00:   24.740 ms/op

Iteration   3: 4.132 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.904 ms/op
                 existUser·p0.50:   4.022 ms/op
                 existUser·p0.90:   5.063 ms/op
                 existUser·p0.95:   5.537 ms/op
                 existUser·p0.99:   8.184 ms/op
                 existUser·p0.999:  13.602 ms/op
                 existUser·p0.9999: 20.481 ms/op
                 existUser·p1.00:   20.742 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 234133
  mean =      4.100 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7452 
    [ 2.500,  5.000) = 201243 
    [ 5.000,  7.500) = 22670 
    [ 7.500, 10.000) = 1923 
    [10.000, 12.500) = 448 
    [12.500, 15.000) = 244 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 67 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.904 ms/op
     p(50.0000) =      3.977 ms/op
     p(90.0000) =      5.054 ms/op
     p(95.0000) =      5.546 ms/op
     p(99.0000) =      7.881 ms/op
     p(99.9000) =     13.678 ms/op
     p(99.9900) =     22.326 ms/op
     p(99.9990) =     24.650 ms/op
     p(99.9999) =     24.740 ms/op
    p(100.0000) =     24.740 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 7.189 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 4.674 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.408 ±(99.9%) 0.016 ms/op
Iteration   1: 4.360 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   0.506 ms/op
                 getUser·p0.50:   4.202 ms/op
                 getUser·p0.90:   5.472 ms/op
                 getUser·p0.95:   6.160 ms/op
                 getUser·p0.99:   9.339 ms/op
                 getUser·p0.999:  15.766 ms/op
                 getUser·p0.9999: 19.103 ms/op
                 getUser·p1.00:   19.497 ms/op

Iteration   2: 4.387 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.051 ms/op
                 getUser·p0.50:   4.235 ms/op
                 getUser·p0.90:   5.431 ms/op
                 getUser·p0.95:   5.980 ms/op
                 getUser·p0.99:   8.897 ms/op
                 getUser·p0.999:  13.320 ms/op
                 getUser·p0.9999: 19.366 ms/op
                 getUser·p1.00:   20.939 ms/op

Iteration   3: 4.428 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.206 ms/op
                 getUser·p0.50:   4.284 ms/op
                 getUser·p0.90:   5.464 ms/op
                 getUser·p0.95:   5.964 ms/op
                 getUser·p0.99:   8.405 ms/op
                 getUser·p0.999:  14.247 ms/op
                 getUser·p0.9999: 26.251 ms/op
                 getUser·p1.00:   26.542 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 218512
  mean =      4.392 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4227 
    [ 2.500,  5.000) = 174390 
    [ 5.000,  7.500) = 35798 
    [ 7.500, 10.000) = 2876 
    [10.000, 12.500) = 791 
    [12.500, 15.000) = 234 
    [15.000, 17.500) = 87 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.506 ms/op
     p(50.0000) =      4.235 ms/op
     p(90.0000) =      5.456 ms/op
     p(95.0000) =      6.029 ms/op
     p(99.0000) =      8.913 ms/op
     p(99.9000) =     14.475 ms/op
     p(99.9900) =     25.208 ms/op
     p(99.9990) =     26.458 ms/op
     p(99.9999) =     26.542 ms/op
    p(100.0000) =     26.542 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 8.989 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 6.109 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 5.583 ±(99.9%) 0.024 ms/op
Iteration   1: 5.770 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   1.106 ms/op
                 listUser·p0.50:   5.333 ms/op
                 listUser·p0.90:   8.061 ms/op
                 listUser·p0.95:   9.077 ms/op
                 listUser·p0.99:   12.026 ms/op
                 listUser·p0.999:  20.236 ms/op
                 listUser·p0.9999: 22.804 ms/op
                 listUser·p1.00:   24.019 ms/op

Iteration   2: 5.713 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   1.368 ms/op
                 listUser·p0.50:   5.276 ms/op
                 listUser·p0.90:   8.012 ms/op
                 listUser·p0.95:   8.978 ms/op
                 listUser·p0.99:   12.157 ms/op
                 listUser·p0.999:  19.987 ms/op
                 listUser·p0.9999: 26.129 ms/op
                 listUser·p1.00:   26.575 ms/op

Iteration   3: 5.698 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   1.331 ms/op
                 listUser·p0.50:   5.210 ms/op
                 listUser·p0.90:   7.995 ms/op
                 listUser·p0.95:   9.093 ms/op
                 listUser·p0.99:   12.632 ms/op
                 listUser·p0.999:  21.917 ms/op
                 listUser·p0.9999: 38.863 ms/op
                 listUser·p1.00:   39.125 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 167650
  mean =      5.727 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 234 
    [ 2.500,  5.000) = 67116 
    [ 5.000,  7.500) = 77739 
    [ 7.500, 10.000) = 17853 
    [10.000, 12.500) = 3208 
    [12.500, 15.000) = 847 
    [15.000, 17.500) = 308 
    [17.500, 20.000) = 144 
    [20.000, 22.500) = 123 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 25 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 17 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.106 ms/op
     p(50.0000) =      5.276 ms/op
     p(90.0000) =      8.020 ms/op
     p(95.0000) =      9.060 ms/op
     p(99.0000) =     12.239 ms/op
     p(99.9000) =     20.578 ms/op
     p(99.9900) =     33.832 ms/op
     p(99.9990) =     39.125 ms/op
     p(99.9999) =     39.125 ms/op
    p(100.0000) =     39.125 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.243 ± 1.246  ops/ms
ClientGrpc.existUser                       thrpt       3   7.858 ± 1.577  ops/ms
ClientGrpc.getUser                         thrpt       3   7.327 ± 1.850  ops/ms
ClientGrpc.listUser                        thrpt       3   5.791 ± 1.848  ops/ms
ClientGrpc.createUser                       avgt       3   4.426 ± 0.498   ms/op
ClientGrpc.existUser                        avgt       3   4.087 ± 1.766   ms/op
ClientGrpc.getUser                          avgt       3   4.329 ± 1.185   ms/op
ClientGrpc.listUser                         avgt       3   5.547 ± 1.249   ms/op
ClientGrpc.createUser                     sample  218941   4.387 ± 0.009   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.809           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.211           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.521           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.087           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           8.585           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          14.420           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          26.647           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.951           ms/op
ClientGrpc.existUser                      sample  234133   4.100 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.904           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.977           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.054           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.546           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.881           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          13.678           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          22.326           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          24.740           ms/op
ClientGrpc.getUser                        sample  218512   4.392 ± 0.008   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.506           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.235           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.456           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.029           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           8.913           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          14.475           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          25.208           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          26.542           ms/op
ClientGrpc.listUser                       sample  167650   5.727 ± 0.015   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.106           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.276           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           8.020           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           9.060           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          12.239           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          20.578           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          33.832           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          39.125           ms/op
