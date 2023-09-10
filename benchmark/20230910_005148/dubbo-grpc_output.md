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
# Warmup Iteration   1: 3.365 ops/ms
# Warmup Iteration   2: 6.871 ops/ms
# Warmup Iteration   3: 8.308 ops/ms
Iteration   1: 8.655 ops/ms
Iteration   2: 8.335 ops/ms
Iteration   3: 8.787 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.592 ±(99.9%) 4.242 ops/ms [Average]
  (min, avg, max) = (8.335, 8.592, 8.787), stdev = 0.233
  CI (99.9%): [4.350, 12.834] (assumes normal distribution)


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
# Warmup Iteration   1: 6.079 ops/ms
# Warmup Iteration   2: 8.523 ops/ms
# Warmup Iteration   3: 8.959 ops/ms
Iteration   1: 9.475 ops/ms
Iteration   2: 9.361 ops/ms
Iteration   3: 9.357 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.398 ±(99.9%) 1.227 ops/ms [Average]
  (min, avg, max) = (9.357, 9.398, 9.475), stdev = 0.067
  CI (99.9%): [8.170, 10.625] (assumes normal distribution)


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
# Warmup Iteration   1: 5.505 ops/ms
# Warmup Iteration   2: 8.435 ops/ms
# Warmup Iteration   3: 8.675 ops/ms
Iteration   1: 8.608 ops/ms
Iteration   2: 8.831 ops/ms
Iteration   3: 8.849 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.762 ±(99.9%) 2.447 ops/ms [Average]
  (min, avg, max) = (8.608, 8.762, 8.849), stdev = 0.134
  CI (99.9%): [6.315, 11.210] (assumes normal distribution)


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
# Warmup Iteration   1: 5.378 ops/ms
# Warmup Iteration   2: 6.060 ops/ms
# Warmup Iteration   3: 6.452 ops/ms
Iteration   1: 6.645 ops/ms
Iteration   2: 6.632 ops/ms
Iteration   3: 6.673 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.650 ±(99.9%) 0.379 ops/ms [Average]
  (min, avg, max) = (6.632, 6.650, 6.673), stdev = 0.021
  CI (99.9%): [6.271, 7.029] (assumes normal distribution)


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
# Warmup Iteration   1: 5.119 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.953 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.740 ±(99.9%) 0.009 ms/op
Iteration   1: 3.778 ±(99.9%) 0.036 ms/op
Iteration   2: 3.688 ±(99.9%) 0.003 ms/op
Iteration   3: 3.691 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.719 ±(99.9%) 0.936 ms/op [Average]
  (min, avg, max) = (3.688, 3.719, 3.778), stdev = 0.051
  CI (99.9%): [2.783, 4.655] (assumes normal distribution)


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
# Warmup Iteration   1: 4.983 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.621 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.557 ±(99.9%) 0.003 ms/op
Iteration   1: 3.490 ±(99.9%) 0.003 ms/op
Iteration   2: 3.419 ±(99.9%) 0.004 ms/op
Iteration   3: 3.510 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.473 ±(99.9%) 0.876 ms/op [Average]
  (min, avg, max) = (3.419, 3.473, 3.510), stdev = 0.048
  CI (99.9%): [2.597, 4.349] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.040 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.939 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.721 ±(99.9%) 0.004 ms/op
Iteration   1: 3.620 ±(99.9%) 0.003 ms/op
Iteration   2: 3.616 ±(99.9%) 0.004 ms/op
Iteration   3: 3.616 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.617 ±(99.9%) 0.047 ms/op [Average]
  (min, avg, max) = (3.616, 3.617, 3.620), stdev = 0.003
  CI (99.9%): [3.570, 3.665] (assumes normal distribution)


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
# Warmup Iteration   1: 6.673 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 5.268 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.901 ±(99.9%) 0.013 ms/op
Iteration   1: 4.833 ±(99.9%) 0.011 ms/op
Iteration   2: 4.875 ±(99.9%) 0.017 ms/op
Iteration   3: 4.844 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.851 ±(99.9%) 0.398 ms/op [Average]
  (min, avg, max) = (4.833, 4.851, 4.875), stdev = 0.022
  CI (99.9%): [4.453, 5.249] (assumes normal distribution)


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
# Warmup Iteration   1: 5.522 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 3.780 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.669 ±(99.9%) 0.009 ms/op
Iteration   1: 3.616 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.825 ms/op
                 createUser·p0.50:   3.576 ms/op
                 createUser·p0.90:   4.293 ms/op
                 createUser·p0.95:   4.645 ms/op
                 createUser·p0.99:   5.693 ms/op
                 createUser·p0.999:  7.516 ms/op
                 createUser·p0.9999: 16.190 ms/op
                 createUser·p1.00:   16.728 ms/op

Iteration   2: 3.659 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.934 ms/op
                 createUser·p0.50:   3.584 ms/op
                 createUser·p0.90:   4.366 ms/op
                 createUser·p0.95:   4.678 ms/op
                 createUser·p0.99:   6.005 ms/op
                 createUser·p0.999:  11.141 ms/op
                 createUser·p0.9999: 24.150 ms/op
                 createUser·p1.00:   24.576 ms/op

Iteration   3: 3.647 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.839 ms/op
                 createUser·p0.50:   3.568 ms/op
                 createUser·p0.90:   4.325 ms/op
                 createUser·p0.95:   4.735 ms/op
                 createUser·p0.99:   6.144 ms/op
                 createUser·p0.999:  15.399 ms/op
                 createUser·p0.9999: 20.054 ms/op
                 createUser·p1.00:   20.414 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 263739
  mean =      3.641 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8107 
    [ 2.500,  5.000) = 248095 
    [ 5.000,  7.500) = 6647 
    [ 7.500, 10.000) = 505 
    [10.000, 12.500) = 158 
    [12.500, 15.000) = 40 
    [15.000, 17.500) = 66 
    [17.500, 20.000) = 79 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.825 ms/op
     p(50.0000) =      3.576 ms/op
     p(90.0000) =      4.325 ms/op
     p(95.0000) =      4.686 ms/op
     p(99.0000) =      5.923 ms/op
     p(99.9000) =     11.379 ms/op
     p(99.9900) =     23.220 ms/op
     p(99.9990) =     24.481 ms/op
     p(99.9999) =     24.576 ms/op
    p(100.0000) =     24.576 ms/op


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
# Warmup Iteration   1: 5.033 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.716 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.533 ±(99.9%) 0.008 ms/op
Iteration   1: 3.495 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.829 ms/op
                 existUser·p0.50:   3.478 ms/op
                 existUser·p0.90:   4.243 ms/op
                 existUser·p0.95:   4.604 ms/op
                 existUser·p0.99:   5.833 ms/op
                 existUser·p0.999:  10.082 ms/op
                 existUser·p0.9999: 15.068 ms/op
                 existUser·p1.00:   15.483 ms/op

Iteration   2: 3.559 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.924 ms/op
                 existUser·p0.50:   3.494 ms/op
                 existUser·p0.90:   4.342 ms/op
                 existUser·p0.95:   4.669 ms/op
                 existUser·p0.99:   6.365 ms/op
                 existUser·p0.999:  12.009 ms/op
                 existUser·p0.9999: 16.302 ms/op
                 existUser·p1.00:   16.712 ms/op

Iteration   3: 3.540 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.819 ms/op
                 existUser·p0.50:   3.469 ms/op
                 existUser·p0.90:   4.129 ms/op
                 existUser·p0.95:   4.522 ms/op
                 existUser·p0.99:   5.825 ms/op
                 existUser·p0.999:  11.944 ms/op
                 existUser·p0.9999: 21.067 ms/op
                 existUser·p1.00:   21.758 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 271858
  mean =      3.531 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13790 
    [ 2.500,  5.000) = 250927 
    [ 5.000,  7.500) = 6015 
    [ 7.500, 10.000) = 663 
    [10.000, 12.500) = 315 
    [12.500, 15.000) = 75 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.819 ms/op
     p(50.0000) =      3.478 ms/op
     p(90.0000) =      4.252 ms/op
     p(95.0000) =      4.604 ms/op
     p(99.0000) =      5.972 ms/op
     p(99.9000) =     11.684 ms/op
     p(99.9900) =     18.138 ms/op
     p(99.9990) =     21.655 ms/op
     p(99.9999) =     21.758 ms/op
    p(100.0000) =     21.758 ms/op


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
# Warmup Iteration   1: 5.397 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 3.822 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.731 ±(99.9%) 0.010 ms/op
Iteration   1: 3.719 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.114 ms/op
                 getUser·p0.50:   3.637 ms/op
                 getUser·p0.90:   4.456 ms/op
                 getUser·p0.95:   4.858 ms/op
                 getUser·p0.99:   6.701 ms/op
                 getUser·p0.999:  12.583 ms/op
                 getUser·p0.9999: 18.231 ms/op
                 getUser·p1.00:   18.579 ms/op

Iteration   2: 3.712 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.730 ms/op
                 getUser·p0.50:   3.637 ms/op
                 getUser·p0.90:   4.481 ms/op
                 getUser·p0.95:   4.866 ms/op
                 getUser·p0.99:   6.415 ms/op
                 getUser·p0.999:  12.042 ms/op
                 getUser·p0.9999: 16.802 ms/op
                 getUser·p1.00:   16.974 ms/op

Iteration   3: 3.614 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.859 ms/op
                 getUser·p0.50:   3.551 ms/op
                 getUser·p0.90:   4.162 ms/op
                 getUser·p0.95:   4.522 ms/op
                 getUser·p0.99:   5.980 ms/op
                 getUser·p0.999:  16.523 ms/op
                 getUser·p0.9999: 31.429 ms/op
                 getUser·p1.00:   31.916 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 260918
  mean =      3.681 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9492 
    [ 2.500,  5.000) = 242044 
    [ 5.000,  7.500) = 8139 
    [ 7.500, 10.000) = 781 
    [10.000, 12.500) = 211 
    [12.500, 15.000) = 81 
    [15.000, 17.500) = 72 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 11 
    [30.000, 32.500) = 21 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.730 ms/op
     p(50.0000) =      3.604 ms/op
     p(90.0000) =      4.383 ms/op
     p(95.0000) =      4.768 ms/op
     p(99.0000) =      6.390 ms/op
     p(99.9000) =     12.386 ms/op
     p(99.9900) =     29.536 ms/op
     p(99.9990) =     31.856 ms/op
     p(99.9999) =     31.916 ms/op
    p(100.0000) =     31.916 ms/op


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
# Warmup Iteration   1: 7.285 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 5.152 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.891 ±(99.9%) 0.016 ms/op
Iteration   1: 4.936 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.128 ms/op
                 listUser·p0.50:   4.661 ms/op
                 listUser·p0.90:   6.414 ms/op
                 listUser·p0.95:   7.324 ms/op
                 listUser·p0.99:   9.257 ms/op
                 listUser·p0.999:  20.061 ms/op
                 listUser·p0.9999: 22.512 ms/op
                 listUser·p1.00:   23.233 ms/op

Iteration   2: 4.920 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   0.997 ms/op
                 listUser·p0.50:   4.669 ms/op
                 listUser·p0.90:   6.234 ms/op
                 listUser·p0.95:   7.135 ms/op
                 listUser·p0.99:   9.044 ms/op
                 listUser·p0.999:  20.775 ms/op
                 listUser·p0.9999: 29.980 ms/op
                 listUser·p1.00:   30.573 ms/op

Iteration   3: 4.963 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.092 ms/op
                 listUser·p0.50:   4.710 ms/op
                 listUser·p0.90:   6.308 ms/op
                 listUser·p0.95:   7.143 ms/op
                 listUser·p0.99:   9.044 ms/op
                 listUser·p0.999:  18.926 ms/op
                 listUser·p0.9999: 22.989 ms/op
                 listUser·p1.00:   23.265 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 194331
  mean =      4.940 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 586 
    [ 2.500,  5.000) = 131066 
    [ 5.000,  7.500) = 55236 
    [ 7.500, 10.000) = 6166 
    [10.000, 12.500) = 732 
    [12.500, 15.000) = 223 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 70 
    [20.000, 22.500) = 145 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 14 
    [27.500, 30.000) = 19 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.997 ms/op
     p(50.0000) =      4.686 ms/op
     p(90.0000) =      6.316 ms/op
     p(95.0000) =      7.201 ms/op
     p(99.0000) =      9.126 ms/op
     p(99.9000) =     20.414 ms/op
     p(99.9900) =     28.068 ms/op
     p(99.9990) =     30.325 ms/op
     p(99.9999) =     30.573 ms/op
    p(100.0000) =     30.573 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.592 ± 4.242  ops/ms
ClientGrpc.existUser                       thrpt       3   9.398 ± 1.227  ops/ms
ClientGrpc.getUser                         thrpt       3   8.762 ± 2.447  ops/ms
ClientGrpc.listUser                        thrpt       3   6.650 ± 0.379  ops/ms
ClientGrpc.createUser                       avgt       3   3.719 ± 0.936   ms/op
ClientGrpc.existUser                        avgt       3   3.473 ± 0.876   ms/op
ClientGrpc.getUser                          avgt       3   3.617 ± 0.047   ms/op
ClientGrpc.listUser                         avgt       3   4.851 ± 0.398   ms/op
ClientGrpc.createUser                     sample  263739   3.641 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.825           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.576           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.325           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.686           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.923           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.379           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.220           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.576           ms/op
ClientGrpc.existUser                      sample  271858   3.531 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.819           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.478           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.252           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.604           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.972           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.684           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.138           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.758           ms/op
ClientGrpc.getUser                        sample  260918   3.681 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.730           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.604           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.383           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.768           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.390           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.386           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          29.536           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          31.916           ms/op
ClientGrpc.listUser                       sample  194331   4.940 ± 0.010   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.997           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.686           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.316           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.201           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.126           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          20.414           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          28.068           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          30.573           ms/op
