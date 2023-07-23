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
# Warmup Iteration   1: 2.674 ops/ms
# Warmup Iteration   2: 6.412 ops/ms
# Warmup Iteration   3: 8.072 ops/ms
Iteration   1: 8.088 ops/ms
Iteration   2: 8.531 ops/ms
Iteration   3: 8.412 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.343 ±(99.9%) 4.185 ops/ms [Average]
  (min, avg, max) = (8.088, 8.343, 8.531), stdev = 0.229
  CI (99.9%): [4.159, 12.528] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.791 ops/ms
# Warmup Iteration   2: 8.222 ops/ms
# Warmup Iteration   3: 8.989 ops/ms
Iteration   1: 8.781 ops/ms
Iteration   2: 8.893 ops/ms
Iteration   3: 8.954 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.876 ±(99.9%) 1.601 ops/ms [Average]
  (min, avg, max) = (8.781, 8.876, 8.954), stdev = 0.088
  CI (99.9%): [7.275, 10.477] (assumes normal distribution)


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
# Warmup Iteration   1: 4.938 ops/ms
# Warmup Iteration   2: 7.521 ops/ms
# Warmup Iteration   3: 8.443 ops/ms
Iteration   1: 8.390 ops/ms
Iteration   2: 8.503 ops/ms
Iteration   3: 8.316 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.403 ±(99.9%) 1.713 ops/ms [Average]
  (min, avg, max) = (8.316, 8.403, 8.503), stdev = 0.094
  CI (99.9%): [6.689, 10.116] (assumes normal distribution)


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
# Warmup Iteration   1: 4.453 ops/ms
# Warmup Iteration   2: 6.033 ops/ms
# Warmup Iteration   3: 6.647 ops/ms
Iteration   1: 6.650 ops/ms
Iteration   2: 6.648 ops/ms
Iteration   3: 6.872 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.723 ±(99.9%) 2.355 ops/ms [Average]
  (min, avg, max) = (6.648, 6.723, 6.872), stdev = 0.129
  CI (99.9%): [4.368, 9.078] (assumes normal distribution)


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
# Warmup Iteration   1: 5.493 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.002 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.873 ±(99.9%) 0.004 ms/op
Iteration   1: 3.731 ±(99.9%) 0.005 ms/op
Iteration   2: 3.786 ±(99.9%) 0.003 ms/op
Iteration   3: 3.866 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.794 ±(99.9%) 1.240 ms/op [Average]
  (min, avg, max) = (3.731, 3.794, 3.866), stdev = 0.068
  CI (99.9%): [2.554, 5.035] (assumes normal distribution)


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
# Warmup Iteration   1: 5.128 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.709 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.520 ±(99.9%) 0.004 ms/op
Iteration   1: 3.625 ±(99.9%) 0.003 ms/op
Iteration   2: 3.506 ±(99.9%) 0.004 ms/op
Iteration   3: 3.588 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.573 ±(99.9%) 1.106 ms/op [Average]
  (min, avg, max) = (3.506, 3.573, 3.625), stdev = 0.061
  CI (99.9%): [2.467, 4.679] (assumes normal distribution)


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
# Warmup Iteration   1: 5.444 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 4.024 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 3.768 ±(99.9%) 0.003 ms/op
Iteration   1: 3.723 ±(99.9%) 0.004 ms/op
Iteration   2: 3.679 ±(99.9%) 0.004 ms/op
Iteration   3: 3.730 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.711 ±(99.9%) 0.509 ms/op [Average]
  (min, avg, max) = (3.679, 3.711, 3.730), stdev = 0.028
  CI (99.9%): [3.202, 4.220] (assumes normal distribution)


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
# Warmup Iteration   1: 7.124 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 5.051 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.868 ±(99.9%) 0.010 ms/op
Iteration   1: 4.793 ±(99.9%) 0.010 ms/op
Iteration   2: 4.855 ±(99.9%) 0.014 ms/op
Iteration   3: 4.807 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.818 ±(99.9%) 0.591 ms/op [Average]
  (min, avg, max) = (4.793, 4.818, 4.855), stdev = 0.032
  CI (99.9%): [4.227, 5.410] (assumes normal distribution)


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
# Warmup Iteration   1: 5.589 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 4.110 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.778 ±(99.9%) 0.010 ms/op
Iteration   1: 3.800 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.889 ms/op
                 createUser·p0.50:   3.707 ms/op
                 createUser·p0.90:   4.514 ms/op
                 createUser·p0.95:   4.817 ms/op
                 createUser·p0.99:   6.226 ms/op
                 createUser·p0.999:  11.246 ms/op
                 createUser·p0.9999: 26.247 ms/op
                 createUser·p1.00:   26.706 ms/op

Iteration   2: 3.691 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.872 ms/op
                 createUser·p0.50:   3.633 ms/op
                 createUser·p0.90:   4.350 ms/op
                 createUser·p0.95:   4.702 ms/op
                 createUser·p0.99:   5.923 ms/op
                 createUser·p0.999:  15.603 ms/op
                 createUser·p0.9999: 25.723 ms/op
                 createUser·p1.00:   27.984 ms/op

Iteration   3: 3.712 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   0.939 ms/op
                 createUser·p0.50:   3.650 ms/op
                 createUser·p0.90:   4.375 ms/op
                 createUser·p0.95:   4.727 ms/op
                 createUser·p0.99:   5.997 ms/op
                 createUser·p0.999:  12.864 ms/op
                 createUser·p0.9999: 47.841 ms/op
                 createUser·p1.00:   48.497 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 257083
  mean =      3.734 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 248750 
    [ 5.000, 10.000) = 7862 
    [10.000, 15.000) = 236 
    [15.000, 20.000) = 75 
    [20.000, 25.000) = 35 
    [25.000, 30.000) = 92 
    [30.000, 35.000) = 1 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.872 ms/op
     p(50.0000) =      3.662 ms/op
     p(90.0000) =      4.424 ms/op
     p(95.0000) =      4.751 ms/op
     p(99.0000) =      6.021 ms/op
     p(99.9000) =     12.059 ms/op
     p(99.9900) =     47.139 ms/op
     p(99.9990) =     48.356 ms/op
     p(99.9999) =     48.497 ms/op
    p(100.0000) =     48.497 ms/op


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
# Warmup Iteration   1: 5.043 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.778 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.551 ±(99.9%) 0.008 ms/op
Iteration   1: 3.616 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.971 ms/op
                 existUser·p0.50:   3.535 ms/op
                 existUser·p0.90:   4.358 ms/op
                 existUser·p0.95:   4.686 ms/op
                 existUser·p0.99:   6.091 ms/op
                 existUser·p0.999:  11.117 ms/op
                 existUser·p0.9999: 14.620 ms/op
                 existUser·p1.00:   15.614 ms/op

Iteration   2: 3.577 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.046 ms/op
                 existUser·p0.50:   3.486 ms/op
                 existUser·p0.90:   4.190 ms/op
                 existUser·p0.95:   4.669 ms/op
                 existUser·p0.99:   6.226 ms/op
                 existUser·p0.999:  10.909 ms/op
                 existUser·p0.9999: 17.662 ms/op
                 existUser·p1.00:   18.022 ms/op

Iteration   3: 3.427 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.845 ms/op
                 existUser·p0.50:   3.437 ms/op
                 existUser·p0.90:   3.977 ms/op
                 existUser·p0.95:   4.399 ms/op
                 existUser·p0.99:   5.931 ms/op
                 existUser·p0.999:  10.677 ms/op
                 existUser·p0.9999: 20.928 ms/op
                 existUser·p1.00:   22.643 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 271322
  mean =      3.538 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12697 
    [ 2.500,  5.000) = 251030 
    [ 5.000,  7.500) = 6356 
    [ 7.500, 10.000) = 852 
    [10.000, 12.500) = 256 
    [12.500, 15.000) = 58 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.845 ms/op
     p(50.0000) =      3.482 ms/op
     p(90.0000) =      4.202 ms/op
     p(95.0000) =      4.596 ms/op
     p(99.0000) =      6.068 ms/op
     p(99.9000) =     10.863 ms/op
     p(99.9900) =     20.508 ms/op
     p(99.9990) =     21.656 ms/op
     p(99.9999) =     22.643 ms/op
    p(100.0000) =     22.643 ms/op


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
# Warmup Iteration   1: 5.695 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 4.007 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.862 ±(99.9%) 0.009 ms/op
Iteration   1: 3.760 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.202 ms/op
                 getUser·p0.50:   3.690 ms/op
                 getUser·p0.90:   4.489 ms/op
                 getUser·p0.95:   4.817 ms/op
                 getUser·p0.99:   6.013 ms/op
                 getUser·p0.999:  14.694 ms/op
                 getUser·p0.9999: 23.412 ms/op
                 getUser·p1.00:   24.019 ms/op

Iteration   2: 3.716 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.106 ms/op
                 getUser·p0.50:   3.645 ms/op
                 getUser·p0.90:   4.407 ms/op
                 getUser·p0.95:   4.792 ms/op
                 getUser·p0.99:   6.162 ms/op
                 getUser·p0.999:  10.961 ms/op
                 getUser·p0.9999: 15.221 ms/op
                 getUser·p1.00:   15.811 ms/op

Iteration   3: 3.794 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.897 ms/op
                 getUser·p0.50:   3.727 ms/op
                 getUser·p0.90:   4.481 ms/op
                 getUser·p0.95:   4.833 ms/op
                 getUser·p0.99:   5.956 ms/op
                 getUser·p0.999:  11.563 ms/op
                 getUser·p0.9999: 19.829 ms/op
                 getUser·p1.00:   21.201 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 255642
  mean =      3.756 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6398 
    [ 2.500,  5.000) = 239982 
    [ 5.000,  7.500) = 8272 
    [ 7.500, 10.000) = 617 
    [10.000, 12.500) = 150 
    [12.500, 15.000) = 85 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.897 ms/op
     p(50.0000) =      3.686 ms/op
     p(90.0000) =      4.465 ms/op
     p(95.0000) =      4.817 ms/op
     p(99.0000) =      6.038 ms/op
     p(99.9000) =     11.524 ms/op
     p(99.9900) =     22.741 ms/op
     p(99.9990) =     23.607 ms/op
     p(99.9999) =     24.019 ms/op
    p(100.0000) =     24.019 ms/op


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
# Warmup Iteration   1: 7.470 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 5.103 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.849 ±(99.9%) 0.015 ms/op
Iteration   1: 4.858 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   0.909 ms/op
                 listUser·p0.50:   4.563 ms/op
                 listUser·p0.90:   6.500 ms/op
                 listUser·p0.95:   7.340 ms/op
                 listUser·p0.99:   9.290 ms/op
                 listUser·p0.999:  17.596 ms/op
                 listUser·p0.9999: 20.094 ms/op
                 listUser·p1.00:   21.561 ms/op

Iteration   2: 4.968 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.188 ms/op
                 listUser·p0.50:   4.661 ms/op
                 listUser·p0.90:   6.701 ms/op
                 listUser·p0.95:   7.561 ms/op
                 listUser·p0.99:   9.541 ms/op
                 listUser·p0.999:  17.287 ms/op
                 listUser·p0.9999: 19.694 ms/op
                 listUser·p1.00:   20.873 ms/op

Iteration   3: 4.764 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.452 ms/op
                 listUser·p0.50:   4.489 ms/op
                 listUser·p0.90:   6.414 ms/op
                 listUser·p0.95:   7.324 ms/op
                 listUser·p0.99:   9.175 ms/op
                 listUser·p0.999:  19.825 ms/op
                 listUser·p0.9999: 36.457 ms/op
                 listUser·p1.00:   37.028 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 197368
  mean =      4.862 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 692 
    [ 2.500,  5.000) = 137390 
    [ 5.000,  7.500) = 50071 
    [ 7.500, 10.000) = 7912 
    [10.000, 12.500) = 763 
    [12.500, 15.000) = 214 
    [15.000, 17.500) = 95 
    [17.500, 20.000) = 155 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.909 ms/op
     p(50.0000) =      4.571 ms/op
     p(90.0000) =      6.529 ms/op
     p(95.0000) =      7.422 ms/op
     p(99.0000) =      9.339 ms/op
     p(99.9000) =     17.859 ms/op
     p(99.9900) =     35.865 ms/op
     p(99.9990) =     36.900 ms/op
     p(99.9999) =     37.028 ms/op
    p(100.0000) =     37.028 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.343 ± 4.185  ops/ms
ClientGrpc.existUser                       thrpt       3   8.876 ± 1.601  ops/ms
ClientGrpc.getUser                         thrpt       3   8.403 ± 1.713  ops/ms
ClientGrpc.listUser                        thrpt       3   6.723 ± 2.355  ops/ms
ClientGrpc.createUser                       avgt       3   3.794 ± 1.240   ms/op
ClientGrpc.existUser                        avgt       3   3.573 ± 1.106   ms/op
ClientGrpc.getUser                          avgt       3   3.711 ± 0.509   ms/op
ClientGrpc.listUser                         avgt       3   4.818 ± 0.591   ms/op
ClientGrpc.createUser                     sample  257083   3.734 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.872           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.662           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.424           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.751           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.021           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.059           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          47.139           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          48.497           ms/op
ClientGrpc.existUser                      sample  271322   3.538 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.845           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.482           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.202           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.596           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.068           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.863           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.508           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.643           ms/op
ClientGrpc.getUser                        sample  255642   3.756 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.897           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.686           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.465           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.817           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.038           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.524           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.741           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.019           ms/op
ClientGrpc.listUser                       sample  197368   4.862 ± 0.010   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.909           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.571           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.529           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.422           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.339           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.859           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          35.865           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          37.028           ms/op
