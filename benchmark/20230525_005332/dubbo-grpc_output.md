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
# Warmup Iteration   1: 2.545 ops/ms
# Warmup Iteration   2: 6.112 ops/ms
# Warmup Iteration   3: 7.768 ops/ms
Iteration   1: 7.654 ops/ms
Iteration   2: 7.694 ops/ms
Iteration   3: 8.033 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.793 ±(99.9%) 3.797 ops/ms [Average]
  (min, avg, max) = (7.654, 7.793, 8.033), stdev = 0.208
  CI (99.9%): [3.996, 11.591] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 5.012 ops/ms
# Warmup Iteration   2: 7.780 ops/ms
# Warmup Iteration   3: 8.088 ops/ms
Iteration   1: 8.103 ops/ms
Iteration   2: 8.272 ops/ms
Iteration   3: 8.291 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.222 ±(99.9%) 1.888 ops/ms [Average]
  (min, avg, max) = (8.103, 8.222, 8.291), stdev = 0.104
  CI (99.9%): [6.334, 10.110] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 4.764 ops/ms
# Warmup Iteration   2: 7.251 ops/ms
# Warmup Iteration   3: 7.409 ops/ms
Iteration   1: 7.511 ops/ms
Iteration   2: 7.557 ops/ms
Iteration   3: 7.609 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.559 ±(99.9%) 0.892 ops/ms [Average]
  (min, avg, max) = (7.511, 7.559, 7.609), stdev = 0.049
  CI (99.9%): [6.666, 8.451] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.944 ops/ms
# Warmup Iteration   2: 5.470 ops/ms
# Warmup Iteration   3: 5.866 ops/ms
Iteration   1: 5.972 ops/ms
Iteration   2: 6.100 ops/ms
Iteration   3: 6.063 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.045 ±(99.9%) 1.202 ops/ms [Average]
  (min, avg, max) = (5.972, 6.045, 6.100), stdev = 0.066
  CI (99.9%): [4.843, 7.247] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.247 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.323 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.201 ±(99.9%) 0.020 ms/op
Iteration   1: 4.114 ±(99.9%) 0.003 ms/op
Iteration   2: 4.075 ±(99.9%) 0.002 ms/op
Iteration   3: 3.988 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.059 ±(99.9%) 1.174 ms/op [Average]
  (min, avg, max) = (3.988, 4.059, 4.114), stdev = 0.064
  CI (99.9%): [2.885, 5.234] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 5.621 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.093 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.928 ±(99.9%) 0.003 ms/op
Iteration   1: 3.695 ±(99.9%) 0.004 ms/op
Iteration   2: 3.797 ±(99.9%) 0.003 ms/op
Iteration   3: 3.623 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.705 ±(99.9%) 1.591 ms/op [Average]
  (min, avg, max) = (3.623, 3.705, 3.797), stdev = 0.087
  CI (99.9%): [2.114, 5.296] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 6.440 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.394 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.196 ±(99.9%) 0.005 ms/op
Iteration   1: 4.242 ±(99.9%) 0.003 ms/op
Iteration   2: 4.251 ±(99.9%) 0.002 ms/op
Iteration   3: 4.086 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.193 ±(99.9%) 1.696 ms/op [Average]
  (min, avg, max) = (4.086, 4.193, 4.251), stdev = 0.093
  CI (99.9%): [2.497, 5.889] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 8.164 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 5.696 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 5.819 ±(99.9%) 0.018 ms/op
Iteration   1: 5.443 ±(99.9%) 0.013 ms/op
Iteration   2: 5.226 ±(99.9%) 0.016 ms/op
Iteration   3: 5.230 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.300 ±(99.9%) 2.259 ms/op [Average]
  (min, avg, max) = (5.226, 5.300, 5.443), stdev = 0.124
  CI (99.9%): [3.040, 7.559] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.504 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 4.472 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.162 ±(99.9%) 0.013 ms/op
Iteration   1: 4.007 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.032 ms/op
                 createUser·p0.50:   3.887 ms/op
                 createUser·p0.90:   5.120 ms/op
                 createUser·p0.95:   5.579 ms/op
                 createUser·p0.99:   6.840 ms/op
                 createUser·p0.999:  10.836 ms/op
                 createUser·p0.9999: 16.240 ms/op
                 createUser·p1.00:   18.186 ms/op

Iteration   2: 4.084 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.128 ms/op
                 createUser·p0.50:   3.953 ms/op
                 createUser·p0.90:   5.267 ms/op
                 createUser·p0.95:   5.718 ms/op
                 createUser·p0.99:   7.086 ms/op
                 createUser·p0.999:  13.850 ms/op
                 createUser·p0.9999: 20.322 ms/op
                 createUser·p1.00:   21.135 ms/op

Iteration   3: 4.068 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.106 ms/op
                 createUser·p0.50:   3.940 ms/op
                 createUser·p0.90:   5.251 ms/op
                 createUser·p0.95:   5.702 ms/op
                 createUser·p0.99:   6.889 ms/op
                 createUser·p0.999:  16.028 ms/op
                 createUser·p0.9999: 20.325 ms/op
                 createUser·p1.00:   20.808 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 236823
  mean =      4.053 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3489 
    [ 2.500,  5.000) = 201017 
    [ 5.000,  7.500) = 30749 
    [ 7.500, 10.000) = 1078 
    [10.000, 12.500) = 211 
    [12.500, 15.000) = 82 
    [15.000, 17.500) = 98 
    [17.500, 20.000) = 68 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.032 ms/op
     p(50.0000) =      3.924 ms/op
     p(90.0000) =      5.210 ms/op
     p(95.0000) =      5.669 ms/op
     p(99.0000) =      6.930 ms/op
     p(99.9000) =     13.951 ms/op
     p(99.9900) =     20.152 ms/op
     p(99.9990) =     20.808 ms/op
     p(99.9999) =     21.135 ms/op
    p(100.0000) =     21.135 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.491 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 4.067 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.993 ±(99.9%) 0.012 ms/op
Iteration   1: 3.878 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.214 ms/op
                 existUser·p0.50:   3.734 ms/op
                 existUser·p0.90:   4.973 ms/op
                 existUser·p0.95:   5.448 ms/op
                 existUser·p0.99:   6.963 ms/op
                 existUser·p0.999:  10.101 ms/op
                 existUser·p0.9999: 16.544 ms/op
                 existUser·p1.00:   18.907 ms/op

Iteration   2: 3.814 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.767 ms/op
                 existUser·p0.50:   3.678 ms/op
                 existUser·p0.90:   4.841 ms/op
                 existUser·p0.95:   5.276 ms/op
                 existUser·p0.99:   6.824 ms/op
                 existUser·p0.999:  12.469 ms/op
                 existUser·p0.9999: 21.530 ms/op
                 existUser·p1.00:   21.987 ms/op

Iteration   3: 3.700 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.705 ms/op
                 existUser·p0.50:   3.572 ms/op
                 existUser·p0.90:   4.776 ms/op
                 existUser·p0.95:   5.186 ms/op
                 existUser·p0.99:   6.406 ms/op
                 existUser·p0.999:  11.639 ms/op
                 existUser·p0.9999: 22.359 ms/op
                 existUser·p1.00:   22.905 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 253007
  mean =      3.796 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7871 
    [ 2.500,  5.000) = 224947 
    [ 5.000,  7.500) = 18716 
    [ 7.500, 10.000) = 1051 
    [10.000, 12.500) = 231 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 84 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.705 ms/op
     p(50.0000) =      3.662 ms/op
     p(90.0000) =      4.866 ms/op
     p(95.0000) =      5.300 ms/op
     p(99.0000) =      6.750 ms/op
     p(99.9000) =     11.796 ms/op
     p(99.9900) =     20.928 ms/op
     p(99.9990) =     22.805 ms/op
     p(99.9999) =     22.905 ms/op
    p(100.0000) =     22.905 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 6.115 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 4.222 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.984 ±(99.9%) 0.011 ms/op
Iteration   1: 3.976 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.889 ms/op
                 getUser·p0.50:   3.875 ms/op
                 getUser·p0.90:   5.161 ms/op
                 getUser·p0.95:   5.644 ms/op
                 getUser·p0.99:   6.996 ms/op
                 getUser·p0.999:  11.314 ms/op
                 getUser·p0.9999: 18.152 ms/op
                 getUser·p1.00:   20.251 ms/op

Iteration   2: 4.078 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.887 ms/op
                 getUser·p0.50:   3.953 ms/op
                 getUser·p0.90:   5.218 ms/op
                 getUser·p0.95:   5.677 ms/op
                 getUser·p0.99:   6.971 ms/op
                 getUser·p0.999:  14.440 ms/op
                 getUser·p0.9999: 23.205 ms/op
                 getUser·p1.00:   24.445 ms/op

Iteration   3: 3.990 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.016 ms/op
                 getUser·p0.50:   3.871 ms/op
                 getUser·p0.90:   5.104 ms/op
                 getUser·p0.95:   5.554 ms/op
                 getUser·p0.99:   6.868 ms/op
                 getUser·p0.999:  11.980 ms/op
                 getUser·p0.9999: 27.721 ms/op
                 getUser·p1.00:   28.246 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 239054
  mean =      4.014 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8287 
    [ 2.500,  5.000) = 200237 
    [ 5.000,  7.500) = 28894 
    [ 7.500, 10.000) = 1071 
    [10.000, 12.500) = 323 
    [12.500, 15.000) = 102 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 55 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.887 ms/op
     p(50.0000) =      3.899 ms/op
     p(90.0000) =      5.161 ms/op
     p(95.0000) =      5.628 ms/op
     p(99.0000) =      6.930 ms/op
     p(99.9000) =     12.566 ms/op
     p(99.9900) =     26.843 ms/op
     p(99.9990) =     28.155 ms/op
     p(99.9999) =     28.246 ms/op
    p(100.0000) =     28.246 ms/op


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
# Warmup Iteration   1: 8.423 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 5.517 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 5.162 ±(99.9%) 0.022 ms/op
Iteration   1: 5.274 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.386 ms/op
                 listUser·p0.50:   5.005 ms/op
                 listUser·p0.90:   6.914 ms/op
                 listUser·p0.95:   7.823 ms/op
                 listUser·p0.99:   10.158 ms/op
                 listUser·p0.999:  21.725 ms/op
                 listUser·p0.9999: 35.441 ms/op
                 listUser·p1.00:   35.979 ms/op

Iteration   2: 5.093 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.065 ms/op
                 listUser·p0.50:   4.850 ms/op
                 listUser·p0.90:   6.668 ms/op
                 listUser·p0.95:   7.438 ms/op
                 listUser·p0.99:   9.419 ms/op
                 listUser·p0.999:  23.448 ms/op
                 listUser·p0.9999: 29.590 ms/op
                 listUser·p1.00:   30.507 ms/op

Iteration   3: 5.255 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.208 ms/op
                 listUser·p0.50:   4.989 ms/op
                 listUser·p0.90:   6.930 ms/op
                 listUser·p0.95:   7.733 ms/op
                 listUser·p0.99:   10.016 ms/op
                 listUser·p0.999:  27.206 ms/op
                 listUser·p0.9999: 36.492 ms/op
                 listUser·p1.00:   37.028 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 184363
  mean =      5.206 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 447 
    [ 2.500,  5.000) = 95157 
    [ 5.000,  7.500) = 78185 
    [ 7.500, 10.000) = 8846 
    [10.000, 12.500) = 1156 
    [12.500, 15.000) = 201 
    [15.000, 17.500) = 62 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 57 
    [22.500, 25.000) = 61 
    [25.000, 27.500) = 34 
    [27.500, 30.000) = 52 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 41 
    [35.000, 37.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      1.065 ms/op
     p(50.0000) =      4.948 ms/op
     p(90.0000) =      6.832 ms/op
     p(95.0000) =      7.651 ms/op
     p(99.0000) =      9.880 ms/op
     p(99.9000) =     23.790 ms/op
     p(99.9900) =     35.492 ms/op
     p(99.9990) =     36.917 ms/op
     p(99.9999) =     37.028 ms/op
    p(100.0000) =     37.028 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.793 ± 3.797  ops/ms
ClientGrpc.existUser                       thrpt       3   8.222 ± 1.888  ops/ms
ClientGrpc.getUser                         thrpt       3   7.559 ± 0.892  ops/ms
ClientGrpc.listUser                        thrpt       3   6.045 ± 1.202  ops/ms
ClientGrpc.createUser                       avgt       3   4.059 ± 1.174   ms/op
ClientGrpc.existUser                        avgt       3   3.705 ± 1.591   ms/op
ClientGrpc.getUser                          avgt       3   4.193 ± 1.696   ms/op
ClientGrpc.listUser                         avgt       3   5.300 ± 2.259   ms/op
ClientGrpc.createUser                     sample  236823   4.053 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.032           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.924           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.210           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.669           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.930           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.951           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.152           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.135           ms/op
ClientGrpc.existUser                      sample  253007   3.796 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.705           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.662           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.866           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.300           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.750           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.796           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.928           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.905           ms/op
ClientGrpc.getUser                        sample  239054   4.014 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.887           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.899           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.161           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.628           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.930           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.566           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          26.843           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          28.246           ms/op
ClientGrpc.listUser                       sample  184363   5.206 ± 0.012   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.065           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.948           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.832           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.651           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.880           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          23.790           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          35.492           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          37.028           ms/op
