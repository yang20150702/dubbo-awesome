# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.623 ops/ms
# Warmup Iteration   2: 9.170 ops/ms
# Warmup Iteration   3: 10.476 ops/ms
Iteration   1: 10.945 ops/ms
Iteration   2: 10.890 ops/ms
Iteration   3: 11.035 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.957 ±(99.9%) 1.335 ops/ms [Average]
  (min, avg, max) = (10.890, 10.957, 11.035), stdev = 0.073
  CI (99.9%): [9.622, 12.291] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 8.270 ops/ms
# Warmup Iteration   2: 10.827 ops/ms
# Warmup Iteration   3: 11.509 ops/ms
Iteration   1: 11.285 ops/ms
Iteration   2: 11.632 ops/ms
Iteration   3: 11.460 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.459 ±(99.9%) 3.165 ops/ms [Average]
  (min, avg, max) = (11.285, 11.459, 11.632), stdev = 0.173
  CI (99.9%): [8.295, 14.624] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.988 ops/ms
# Warmup Iteration   2: 10.724 ops/ms
# Warmup Iteration   3: 10.802 ops/ms
Iteration   1: 10.985 ops/ms
Iteration   2: 10.891 ops/ms
Iteration   3: 11.079 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.985 ±(99.9%) 1.716 ops/ms [Average]
  (min, avg, max) = (10.891, 10.985, 11.079), stdev = 0.094
  CI (99.9%): [9.269, 12.701] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.223 ops/ms
# Warmup Iteration   2: 8.181 ops/ms
# Warmup Iteration   3: 8.271 ops/ms
Iteration   1: 8.146 ops/ms
Iteration   2: 8.081 ops/ms
Iteration   3: 8.138 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.122 ±(99.9%) 0.643 ops/ms [Average]
  (min, avg, max) = (8.081, 8.122, 8.146), stdev = 0.035
  CI (99.9%): [7.479, 8.765] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 4.016 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.051 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.976 ±(99.9%) 0.003 ms/op
Iteration   1: 2.887 ±(99.9%) 0.003 ms/op
Iteration   2: 2.966 ±(99.9%) 0.004 ms/op
Iteration   3: 2.950 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.935 ±(99.9%) 0.760 ms/op [Average]
  (min, avg, max) = (2.887, 2.935, 2.966), stdev = 0.042
  CI (99.9%): [2.175, 3.694] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.742 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.914 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.755 ±(99.9%) 0.003 ms/op
Iteration   1: 2.792 ±(99.9%) 0.004 ms/op
Iteration   2: 2.825 ±(99.9%) 0.002 ms/op
Iteration   3: 2.807 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.808 ±(99.9%) 0.301 ms/op [Average]
  (min, avg, max) = (2.792, 2.808, 2.825), stdev = 0.016
  CI (99.9%): [2.508, 3.109] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.766 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.034 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.936 ±(99.9%) 0.003 ms/op
Iteration   1: 2.939 ±(99.9%) 0.003 ms/op
Iteration   2: 2.983 ±(99.9%) 0.002 ms/op
Iteration   3: 2.909 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.944 ±(99.9%) 0.682 ms/op [Average]
  (min, avg, max) = (2.909, 2.944, 2.983), stdev = 0.037
  CI (99.9%): [2.262, 3.626] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.946 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.859 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.820 ±(99.9%) 0.021 ms/op
Iteration   1: 3.761 ±(99.9%) 0.004 ms/op
Iteration   2: 3.802 ±(99.9%) 0.017 ms/op
Iteration   3: 3.603 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.722 ±(99.9%) 1.916 ms/op [Average]
  (min, avg, max) = (3.603, 3.722, 3.802), stdev = 0.105
  CI (99.9%): [1.806, 5.638] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.927 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.075 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.946 ±(99.9%) 0.006 ms/op
Iteration   1: 2.912 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.769 ms/op
                 createUser·p0.50:   2.904 ms/op
                 createUser·p0.90:   3.240 ms/op
                 createUser·p0.95:   3.375 ms/op
                 createUser·p0.99:   4.186 ms/op
                 createUser·p0.999:  7.841 ms/op
                 createUser·p0.9999: 15.958 ms/op
                 createUser·p1.00:   16.417 ms/op

Iteration   2: 2.895 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.421 ms/op
                 createUser·p0.50:   2.912 ms/op
                 createUser·p0.90:   3.400 ms/op
                 createUser·p0.95:   3.715 ms/op
                 createUser·p0.99:   4.309 ms/op
                 createUser·p0.999:  10.519 ms/op
                 createUser·p0.9999: 15.663 ms/op
                 createUser·p1.00:   16.581 ms/op

Iteration   3: 2.922 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.586 ms/op
                 createUser·p0.50:   2.908 ms/op
                 createUser·p0.90:   3.457 ms/op
                 createUser·p0.95:   3.695 ms/op
                 createUser·p0.99:   4.235 ms/op
                 createUser·p0.999:  10.109 ms/op
                 createUser·p0.9999: 22.943 ms/op
                 createUser·p1.00:   23.495 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 329720
  mean =      2.910 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 34244 
    [ 2.500,  5.000) = 294301 
    [ 5.000,  7.500) = 779 
    [ 7.500, 10.000) = 59 
    [10.000, 12.500) = 99 
    [12.500, 15.000) = 89 
    [15.000, 17.500) = 117 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.421 ms/op
     p(50.0000) =      2.908 ms/op
     p(90.0000) =      3.351 ms/op
     p(95.0000) =      3.629 ms/op
     p(99.0000) =      4.252 ms/op
     p(99.9000) =     10.093 ms/op
     p(99.9900) =     16.673 ms/op
     p(99.9990) =     23.256 ms/op
     p(99.9999) =     23.495 ms/op
    p(100.0000) =     23.495 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.721 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 2.928 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.820 ±(99.9%) 0.005 ms/op
Iteration   1: 2.810 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.565 ms/op
                 existUser·p0.50:   2.830 ms/op
                 existUser·p0.90:   3.346 ms/op
                 existUser·p0.95:   3.596 ms/op
                 existUser·p0.99:   4.383 ms/op
                 existUser·p0.999:  6.703 ms/op
                 existUser·p0.9999: 13.250 ms/op
                 existUser·p1.00:   13.533 ms/op

Iteration   2: 2.872 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.485 ms/op
                 existUser·p0.50:   2.855 ms/op
                 existUser·p0.90:   3.445 ms/op
                 existUser·p0.95:   3.588 ms/op
                 existUser·p0.99:   4.260 ms/op
                 existUser·p0.999:  5.620 ms/op
                 existUser·p0.9999: 19.525 ms/op
                 existUser·p1.00:   19.694 ms/op

Iteration   3: 2.781 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.554 ms/op
                 existUser·p0.50:   2.818 ms/op
                 existUser·p0.90:   3.314 ms/op
                 existUser·p0.95:   3.510 ms/op
                 existUser·p0.99:   4.342 ms/op
                 existUser·p0.999:  7.206 ms/op
                 existUser·p0.9999: 15.262 ms/op
                 existUser·p1.00:   15.516 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 340328
  mean =      2.820 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 4697 
    [ 1.250,  2.500) = 56265 
    [ 2.500,  3.750) = 269281 
    [ 3.750,  5.000) = 9226 
    [ 5.000,  6.250) = 412 
    [ 6.250,  7.500) = 224 
    [ 7.500,  8.750) = 31 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 31 
    [13.750, 15.000) = 39 
    [15.000, 16.250) = 52 
    [16.250, 17.500) = 5 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.485 ms/op
     p(50.0000) =      2.834 ms/op
     p(90.0000) =      3.379 ms/op
     p(95.0000) =      3.564 ms/op
     p(99.0000) =      4.325 ms/op
     p(99.9000) =      6.674 ms/op
     p(99.9900) =     16.350 ms/op
     p(99.9990) =     19.648 ms/op
     p(99.9999) =     19.694 ms/op
    p(100.0000) =     19.694 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.953 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.032 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.974 ±(99.9%) 0.006 ms/op
Iteration   1: 2.952 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.718 ms/op
                 getUser·p0.50:   2.937 ms/op
                 getUser·p0.90:   3.432 ms/op
                 getUser·p0.95:   3.670 ms/op
                 getUser·p0.99:   4.284 ms/op
                 getUser·p0.999:  7.862 ms/op
                 getUser·p0.9999: 12.192 ms/op
                 getUser·p1.00:   14.057 ms/op

Iteration   2: 2.946 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.787 ms/op
                 getUser·p0.50:   2.949 ms/op
                 getUser·p0.90:   3.391 ms/op
                 getUser·p0.95:   3.527 ms/op
                 getUser·p0.99:   4.194 ms/op
                 getUser·p0.999:  7.901 ms/op
                 getUser·p0.9999: 12.894 ms/op
                 getUser·p1.00:   13.058 ms/op

Iteration   3: 2.981 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.539 ms/op
                 getUser·p0.50:   2.970 ms/op
                 getUser·p0.90:   3.531 ms/op
                 getUser·p0.95:   3.711 ms/op
                 getUser·p0.99:   4.215 ms/op
                 getUser·p0.999:  7.169 ms/op
                 getUser·p0.9999: 13.877 ms/op
                 getUser·p1.00:   14.156 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 324338
  mean =      2.960 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1361 
    [ 1.250,  2.500) = 28955 
    [ 2.500,  3.750) = 281781 
    [ 3.750,  5.000) = 11131 
    [ 5.000,  6.250) = 633 
    [ 6.250,  7.500) = 138 
    [ 7.500,  8.750) = 131 
    [ 8.750, 10.000) = 25 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 117 
    [12.500, 13.750) = 45 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.539 ms/op
     p(50.0000) =      2.949 ms/op
     p(90.0000) =      3.453 ms/op
     p(95.0000) =      3.645 ms/op
     p(99.0000) =      4.227 ms/op
     p(99.9000) =      7.567 ms/op
     p(99.9900) =     13.568 ms/op
     p(99.9990) =     14.070 ms/op
     p(99.9999) =     14.156 ms/op
    p(100.0000) =     14.156 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.816 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.986 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.830 ±(99.9%) 0.009 ms/op
Iteration   1: 3.897 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.550 ms/op
                 listUser·p0.50:   3.756 ms/op
                 listUser·p0.90:   4.809 ms/op
                 listUser·p0.95:   5.497 ms/op
                 listUser·p0.99:   6.717 ms/op
                 listUser·p0.999:  12.386 ms/op
                 listUser·p0.9999: 14.322 ms/op
                 listUser·p1.00:   15.663 ms/op

Iteration   2: 3.910 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.938 ms/op
                 listUser·p0.50:   3.781 ms/op
                 listUser·p0.90:   4.858 ms/op
                 listUser·p0.95:   5.408 ms/op
                 listUser·p0.99:   6.898 ms/op
                 listUser·p0.999:  19.302 ms/op
                 listUser·p0.9999: 20.939 ms/op
                 listUser·p1.00:   21.103 ms/op

Iteration   3: 3.875 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.039 ms/op
                 listUser·p0.50:   3.736 ms/op
                 listUser·p0.90:   4.702 ms/op
                 listUser·p0.95:   5.333 ms/op
                 listUser·p0.99:   6.619 ms/op
                 listUser·p0.999:  12.580 ms/op
                 listUser·p0.9999: 20.987 ms/op
                 listUser·p1.00:   21.987 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 246654
  mean =      3.894 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4037 
    [ 2.500,  5.000) = 223458 
    [ 5.000,  7.500) = 17996 
    [ 7.500, 10.000) = 628 
    [10.000, 12.500) = 265 
    [12.500, 15.000) = 104 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 88 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.550 ms/op
     p(50.0000) =      3.756 ms/op
     p(90.0000) =      4.792 ms/op
     p(95.0000) =      5.415 ms/op
     p(99.0000) =      6.750 ms/op
     p(99.9000) =     12.698 ms/op
     p(99.9900) =     20.840 ms/op
     p(99.9990) =     21.823 ms/op
     p(99.9999) =     21.987 ms/op
    p(100.0000) =     21.987 ms/op


# Run complete. Total time: 00:13:02

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.957 ± 1.335  ops/ms
ClientGrpc.existUser                       thrpt       3  11.459 ± 3.165  ops/ms
ClientGrpc.getUser                         thrpt       3  10.985 ± 1.716  ops/ms
ClientGrpc.listUser                        thrpt       3   8.122 ± 0.643  ops/ms
ClientGrpc.createUser                       avgt       3   2.935 ± 0.760   ms/op
ClientGrpc.existUser                        avgt       3   2.808 ± 0.301   ms/op
ClientGrpc.getUser                          avgt       3   2.944 ± 0.682   ms/op
ClientGrpc.listUser                         avgt       3   3.722 ± 1.916   ms/op
ClientGrpc.createUser                     sample  329720   2.910 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.421           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.908           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.351           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.629           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.252           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.093           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.673           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.495           ms/op
ClientGrpc.existUser                      sample  340328   2.820 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.485           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.834           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.379           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.564           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.325           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.674           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.350           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.694           ms/op
ClientGrpc.getUser                        sample  324338   2.960 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.539           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.949           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.453           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.645           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.227           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.567           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          13.568           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          14.156           ms/op
ClientGrpc.listUser                       sample  246654   3.894 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.550           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.756           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.792           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.415           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.750           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          12.698           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.840           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.987           ms/op
