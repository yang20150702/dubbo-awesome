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
# Warmup Iteration   1: 4.518 ops/ms
# Warmup Iteration   2: 8.834 ops/ms
# Warmup Iteration   3: 9.864 ops/ms
Iteration   1: 10.602 ops/ms
Iteration   2: 10.613 ops/ms
Iteration   3: 10.747 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.654 ±(99.9%) 1.465 ops/ms [Average]
  (min, avg, max) = (10.602, 10.654, 10.747), stdev = 0.080
  CI (99.9%): [9.189, 12.120] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 8.033 ops/ms
# Warmup Iteration   2: 10.834 ops/ms
# Warmup Iteration   3: 11.041 ops/ms
Iteration   1: 11.364 ops/ms
Iteration   2: 11.062 ops/ms
Iteration   3: 11.134 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.187 ±(99.9%) 2.879 ops/ms [Average]
  (min, avg, max) = (11.062, 11.187, 11.364), stdev = 0.158
  CI (99.9%): [8.308, 14.066] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.689 ops/ms
# Warmup Iteration   2: 10.256 ops/ms
# Warmup Iteration   3: 10.563 ops/ms
Iteration   1: 10.598 ops/ms
Iteration   2: 10.580 ops/ms
Iteration   3: 10.580 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.586 ±(99.9%) 0.191 ops/ms [Average]
  (min, avg, max) = (10.580, 10.586, 10.598), stdev = 0.010
  CI (99.9%): [10.395, 10.777] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.748 ops/ms
# Warmup Iteration   2: 7.749 ops/ms
# Warmup Iteration   3: 8.240 ops/ms
Iteration   1: 8.289 ops/ms
Iteration   2: 8.222 ops/ms
Iteration   3: 8.300 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.271 ±(99.9%) 0.769 ops/ms [Average]
  (min, avg, max) = (8.222, 8.271, 8.300), stdev = 0.042
  CI (99.9%): [7.501, 9.040] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 4.146 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.149 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.077 ±(99.9%) 0.010 ms/op
Iteration   1: 2.941 ±(99.9%) 0.004 ms/op
Iteration   2: 2.996 ±(99.9%) 0.004 ms/op
Iteration   3: 3.027 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.988 ±(99.9%) 0.803 ms/op [Average]
  (min, avg, max) = (2.941, 2.988, 3.027), stdev = 0.044
  CI (99.9%): [2.185, 3.791] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.783 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.999 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 2.874 ±(99.9%) 0.004 ms/op
Iteration   1: 2.889 ±(99.9%) 0.004 ms/op
Iteration   2: 2.777 ±(99.9%) 0.004 ms/op
Iteration   3: 2.841 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.836 ±(99.9%) 1.029 ms/op [Average]
  (min, avg, max) = (2.777, 2.836, 2.889), stdev = 0.056
  CI (99.9%): [1.806, 3.865] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.966 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.088 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.025 ±(99.9%) 0.003 ms/op
Iteration   1: 2.980 ±(99.9%) 0.002 ms/op
Iteration   2: 2.981 ±(99.9%) 0.003 ms/op
Iteration   3: 3.012 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.991 ±(99.9%) 0.326 ms/op [Average]
  (min, avg, max) = (2.980, 2.991, 3.012), stdev = 0.018
  CI (99.9%): [2.665, 3.317] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.181 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.876 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.793 ±(99.9%) 0.018 ms/op
Iteration   1: 3.868 ±(99.9%) 0.008 ms/op
Iteration   2: 3.826 ±(99.9%) 0.026 ms/op
Iteration   3: 3.897 ±(99.9%) 0.032 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.863 ±(99.9%) 0.651 ms/op [Average]
  (min, avg, max) = (3.826, 3.863, 3.897), stdev = 0.036
  CI (99.9%): [3.212, 4.515] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.201 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.121 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.009 ±(99.9%) 0.007 ms/op
Iteration   1: 3.036 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.663 ms/op
                 createUser·p0.50:   2.998 ms/op
                 createUser·p0.90:   3.588 ms/op
                 createUser·p0.95:   3.858 ms/op
                 createUser·p0.99:   4.888 ms/op
                 createUser·p0.999:  10.584 ms/op
                 createUser·p0.9999: 15.096 ms/op
                 createUser·p1.00:   16.941 ms/op

Iteration   2: 2.918 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.606 ms/op
                 createUser·p0.50:   2.961 ms/op
                 createUser·p0.90:   3.359 ms/op
                 createUser·p0.95:   3.645 ms/op
                 createUser·p0.99:   4.506 ms/op
                 createUser·p0.999:  8.174 ms/op
                 createUser·p0.9999: 21.432 ms/op
                 createUser·p1.00:   21.594 ms/op

Iteration   3: 3.034 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.804 ms/op
                 createUser·p0.50:   3.011 ms/op
                 createUser·p0.90:   3.592 ms/op
                 createUser·p0.95:   3.772 ms/op
                 createUser·p0.99:   4.538 ms/op
                 createUser·p0.999:  8.094 ms/op
                 createUser·p0.9999: 25.788 ms/op
                 createUser·p1.00:   26.116 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 320402
  mean =      2.995 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 32121 
    [ 2.500,  5.000) = 286237 
    [ 5.000,  7.500) = 1551 
    [ 7.500, 10.000) = 177 
    [10.000, 12.500) = 112 
    [12.500, 15.000) = 115 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.606 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      3.535 ms/op
     p(95.0000) =      3.768 ms/op
     p(99.0000) =      4.661 ms/op
     p(99.9000) =      9.889 ms/op
     p(99.9900) =     23.701 ms/op
     p(99.9990) =     25.985 ms/op
     p(99.9999) =     26.116 ms/op
    p(100.0000) =     26.116 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.740 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 2.986 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.892 ±(99.9%) 0.006 ms/op
Iteration   1: 2.862 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.500 ms/op
                 existUser·p0.50:   2.892 ms/op
                 existUser·p0.90:   3.486 ms/op
                 existUser·p0.95:   3.719 ms/op
                 existUser·p0.99:   4.432 ms/op
                 existUser·p0.999:  7.078 ms/op
                 existUser·p0.9999: 17.885 ms/op
                 existUser·p1.00:   18.612 ms/op

Iteration   2: 2.834 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.643 ms/op
                 existUser·p0.50:   2.859 ms/op
                 existUser·p0.90:   3.383 ms/op
                 existUser·p0.95:   3.633 ms/op
                 existUser·p0.99:   4.538 ms/op
                 existUser·p0.999:  6.934 ms/op
                 existUser·p0.9999: 20.634 ms/op
                 existUser·p1.00:   21.004 ms/op

Iteration   3: 2.925 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.656 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.363 ms/op
                 existUser·p0.95:   3.482 ms/op
                 existUser·p0.99:   4.096 ms/op
                 existUser·p0.999:  7.296 ms/op
                 existUser·p0.9999: 15.305 ms/op
                 existUser·p1.00:   15.679 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 334021
  mean =      2.873 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 46408 
    [ 2.500,  5.000) = 286102 
    [ 5.000,  7.500) = 1294 
    [ 7.500, 10.000) = 57 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 66 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.500 ms/op
     p(50.0000) =      2.888 ms/op
     p(90.0000) =      3.400 ms/op
     p(95.0000) =      3.617 ms/op
     p(99.0000) =      4.407 ms/op
     p(99.9000) =      7.078 ms/op
     p(99.9900) =     18.586 ms/op
     p(99.9990) =     20.939 ms/op
     p(99.9999) =     21.004 ms/op
    p(100.0000) =     21.004 ms/op


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
# Warmup Iteration   1: 3.956 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.075 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.025 ±(99.9%) 0.007 ms/op
Iteration   1: 3.053 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.672 ms/op
                 getUser·p0.50:   3.015 ms/op
                 getUser·p0.90:   3.674 ms/op
                 getUser·p0.95:   3.871 ms/op
                 getUser·p0.99:   4.715 ms/op
                 getUser·p0.999:  8.393 ms/op
                 getUser·p0.9999: 13.763 ms/op
                 getUser·p1.00:   14.205 ms/op

Iteration   2: 3.003 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.281 ms/op
                 getUser·p0.50:   2.974 ms/op
                 getUser·p0.90:   3.518 ms/op
                 getUser·p0.95:   3.809 ms/op
                 getUser·p0.99:   4.686 ms/op
                 getUser·p0.999:  7.889 ms/op
                 getUser·p0.9999: 15.008 ms/op
                 getUser·p1.00:   15.024 ms/op

Iteration   3: 2.985 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.623 ms/op
                 getUser·p0.50:   2.974 ms/op
                 getUser·p0.90:   3.478 ms/op
                 getUser·p0.95:   3.748 ms/op
                 getUser·p0.99:   4.686 ms/op
                 getUser·p0.999:  10.367 ms/op
                 getUser·p0.9999: 17.025 ms/op
                 getUser·p1.00:   18.579 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 318448
  mean =      3.013 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1377 
    [ 1.250,  2.500) = 26888 
    [ 2.500,  3.750) = 270478 
    [ 3.750,  5.000) = 17442 
    [ 5.000,  6.250) = 1057 
    [ 6.250,  7.500) = 630 
    [ 7.500,  8.750) = 267 
    [ 8.750, 10.000) = 62 
    [10.000, 11.250) = 49 
    [11.250, 12.500) = 38 
    [12.500, 13.750) = 25 
    [13.750, 15.000) = 50 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 51 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.281 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      3.568 ms/op
     p(95.0000) =      3.822 ms/op
     p(99.0000) =      4.702 ms/op
     p(99.9000) =      8.552 ms/op
     p(99.9900) =     16.649 ms/op
     p(99.9990) =     17.269 ms/op
     p(99.9999) =     18.579 ms/op
    p(100.0000) =     18.579 ms/op


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
# Warmup Iteration   1: 5.195 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.955 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.900 ±(99.9%) 0.012 ms/op
Iteration   1: 3.898 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.888 ms/op
                 listUser·p0.50:   3.752 ms/op
                 listUser·p0.90:   4.817 ms/op
                 listUser·p0.95:   5.333 ms/op
                 listUser·p0.99:   6.775 ms/op
                 listUser·p0.999:  18.545 ms/op
                 listUser·p0.9999: 19.431 ms/op
                 listUser·p1.00:   19.923 ms/op

Iteration   2: 3.901 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.808 ms/op
                 listUser·p0.50:   3.703 ms/op
                 listUser·p0.90:   5.005 ms/op
                 listUser·p0.95:   5.857 ms/op
                 listUser·p0.99:   6.956 ms/op
                 listUser·p0.999:  17.042 ms/op
                 listUser·p0.9999: 26.293 ms/op
                 listUser·p1.00:   28.246 ms/op

Iteration   3: 3.816 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.920 ms/op
                 listUser·p0.50:   3.703 ms/op
                 listUser·p0.90:   4.743 ms/op
                 listUser·p0.95:   5.620 ms/op
                 listUser·p0.99:   6.939 ms/op
                 listUser·p0.999:  14.059 ms/op
                 listUser·p0.9999: 16.797 ms/op
                 listUser·p1.00:   17.203 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 247907
  mean =      3.871 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5277 
    [ 2.500,  5.000) = 221169 
    [ 5.000,  7.500) = 19881 
    [ 7.500, 10.000) = 1040 
    [10.000, 12.500) = 107 
    [12.500, 15.000) = 175 
    [15.000, 17.500) = 87 
    [17.500, 20.000) = 107 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.808 ms/op
     p(50.0000) =      3.719 ms/op
     p(90.0000) =      4.866 ms/op
     p(95.0000) =      5.603 ms/op
     p(99.0000) =      6.889 ms/op
     p(99.9000) =     15.188 ms/op
     p(99.9900) =     24.065 ms/op
     p(99.9990) =     28.132 ms/op
     p(99.9999) =     28.246 ms/op
    p(100.0000) =     28.246 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.654 ± 1.465  ops/ms
ClientGrpc.existUser                       thrpt       3  11.187 ± 2.879  ops/ms
ClientGrpc.getUser                         thrpt       3  10.586 ± 0.191  ops/ms
ClientGrpc.listUser                        thrpt       3   8.271 ± 0.769  ops/ms
ClientGrpc.createUser                       avgt       3   2.988 ± 0.803   ms/op
ClientGrpc.existUser                        avgt       3   2.836 ± 1.029   ms/op
ClientGrpc.getUser                          avgt       3   2.991 ± 0.326   ms/op
ClientGrpc.listUser                         avgt       3   3.863 ± 0.651   ms/op
ClientGrpc.createUser                     sample  320402   2.995 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.606           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.986           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.535           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.768           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.661           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.889           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.701           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.116           ms/op
ClientGrpc.existUser                      sample  334021   2.873 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.500           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.888           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.400           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.617           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.407           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.078           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.586           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.004           ms/op
ClientGrpc.getUser                        sample  318448   3.013 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.281           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.986           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.568           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.822           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.702           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.552           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.649           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.579           ms/op
ClientGrpc.listUser                       sample  247907   3.871 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.808           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.719           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.866           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.603           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.889           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.188           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.065           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.246           ms/op
