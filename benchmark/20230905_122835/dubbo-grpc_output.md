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
# Warmup Iteration   1: 3.393 ops/ms
# Warmup Iteration   2: 8.021 ops/ms
# Warmup Iteration   3: 9.562 ops/ms
Iteration   1: 9.458 ops/ms
Iteration   2: 9.781 ops/ms
Iteration   3: 9.829 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.689 ±(99.9%) 3.680 ops/ms [Average]
  (min, avg, max) = (9.458, 9.689, 9.829), stdev = 0.202
  CI (99.9%): [6.009, 13.369] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 6.838 ops/ms
# Warmup Iteration   2: 10.049 ops/ms
# Warmup Iteration   3: 10.575 ops/ms
Iteration   1: 10.718 ops/ms
Iteration   2: 10.645 ops/ms
Iteration   3: 10.711 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.691 ±(99.9%) 0.739 ops/ms [Average]
  (min, avg, max) = (10.645, 10.691, 10.718), stdev = 0.040
  CI (99.9%): [9.953, 11.430] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 6.839 ops/ms
# Warmup Iteration   2: 9.934 ops/ms
# Warmup Iteration   3: 10.022 ops/ms
Iteration   1: 10.205 ops/ms
Iteration   2: 10.127 ops/ms
Iteration   3: 10.129 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.154 ±(99.9%) 0.804 ops/ms [Average]
  (min, avg, max) = (10.127, 10.154, 10.205), stdev = 0.044
  CI (99.9%): [9.349, 10.958] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.631 ops/ms
# Warmup Iteration   2: 7.528 ops/ms
# Warmup Iteration   3: 7.820 ops/ms
Iteration   1: 7.748 ops/ms
Iteration   2: 7.753 ops/ms
Iteration   3: 7.811 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.770 ±(99.9%) 0.640 ops/ms [Average]
  (min, avg, max) = (7.748, 7.770, 7.811), stdev = 0.035
  CI (99.9%): [7.131, 8.410] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.732 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.335 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.157 ±(99.9%) 0.002 ms/op
Iteration   1: 3.128 ±(99.9%) 0.018 ms/op
Iteration   2: 3.137 ±(99.9%) 0.002 ms/op
Iteration   3: 3.130 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.132 ±(99.9%) 0.091 ms/op [Average]
  (min, avg, max) = (3.128, 3.132, 3.137), stdev = 0.005
  CI (99.9%): [3.041, 3.222] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.230 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.051 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.983 ±(99.9%) 0.003 ms/op
Iteration   1: 2.991 ±(99.9%) 0.002 ms/op
Iteration   2: 2.968 ±(99.9%) 0.002 ms/op
Iteration   3: 2.983 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.980 ±(99.9%) 0.213 ms/op [Average]
  (min, avg, max) = (2.968, 2.980, 2.991), stdev = 0.012
  CI (99.9%): [2.767, 3.194] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.347 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.270 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.156 ±(99.9%) 0.003 ms/op
Iteration   1: 3.150 ±(99.9%) 0.003 ms/op
Iteration   2: 3.181 ±(99.9%) 0.002 ms/op
Iteration   3: 3.084 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.138 ±(99.9%) 0.897 ms/op [Average]
  (min, avg, max) = (3.084, 3.138, 3.181), stdev = 0.049
  CI (99.9%): [2.241, 4.036] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.860 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.276 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.282 ±(99.9%) 0.009 ms/op
Iteration   1: 4.209 ±(99.9%) 0.022 ms/op
Iteration   2: 4.201 ±(99.9%) 0.026 ms/op
Iteration   3: 4.252 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.221 ±(99.9%) 0.498 ms/op [Average]
  (min, avg, max) = (4.201, 4.221, 4.252), stdev = 0.027
  CI (99.9%): [3.723, 4.719] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.735 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.366 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.148 ±(99.9%) 0.007 ms/op
Iteration   1: 3.154 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.764 ms/op
                 createUser·p0.50:   3.125 ms/op
                 createUser·p0.90:   3.789 ms/op
                 createUser·p0.95:   4.043 ms/op
                 createUser·p0.99:   5.014 ms/op
                 createUser·p0.999:  8.421 ms/op
                 createUser·p0.9999: 13.741 ms/op
                 createUser·p1.00:   14.041 ms/op

Iteration   2: 3.125 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.774 ms/op
                 createUser·p0.50:   3.076 ms/op
                 createUser·p0.90:   3.707 ms/op
                 createUser·p0.95:   3.949 ms/op
                 createUser·p0.99:   5.104 ms/op
                 createUser·p0.999:  8.634 ms/op
                 createUser·p0.9999: 15.705 ms/op
                 createUser·p1.00:   16.187 ms/op

Iteration   3: 3.150 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.595 ms/op
                 createUser·p0.50:   3.064 ms/op
                 createUser·p0.90:   3.662 ms/op
                 createUser·p0.95:   4.026 ms/op
                 createUser·p0.99:   5.562 ms/op
                 createUser·p0.999:  15.128 ms/op
                 createUser·p0.9999: 29.218 ms/op
                 createUser·p1.00:   29.655 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 305480
  mean =      3.143 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17053 
    [ 2.500,  5.000) = 284590 
    [ 5.000,  7.500) = 3063 
    [ 7.500, 10.000) = 488 
    [10.000, 12.500) = 34 
    [12.500, 15.000) = 91 
    [15.000, 17.500) = 96 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.595 ms/op
     p(50.0000) =      3.084 ms/op
     p(90.0000) =      3.727 ms/op
     p(95.0000) =      4.006 ms/op
     p(99.0000) =      5.210 ms/op
     p(99.9000) =      9.651 ms/op
     p(99.9900) =     28.508 ms/op
     p(99.9990) =     29.457 ms/op
     p(99.9999) =     29.655 ms/op
    p(100.0000) =     29.655 ms/op


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
# Warmup Iteration   1: 4.268 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.126 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.038 ±(99.9%) 0.007 ms/op
Iteration   1: 2.998 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.292 ms/op
                 existUser·p0.50:   2.957 ms/op
                 existUser·p0.90:   3.502 ms/op
                 existUser·p0.95:   3.723 ms/op
                 existUser·p0.99:   4.850 ms/op
                 existUser·p0.999:  7.569 ms/op
                 existUser·p0.9999: 13.532 ms/op
                 existUser·p1.00:   13.910 ms/op

Iteration   2: 3.029 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.830 ms/op
                 existUser·p0.50:   2.974 ms/op
                 existUser·p0.90:   3.564 ms/op
                 existUser·p0.95:   3.785 ms/op
                 existUser·p0.99:   4.960 ms/op
                 existUser·p0.999:  10.763 ms/op
                 existUser·p0.9999: 22.053 ms/op
                 existUser·p1.00:   23.724 ms/op

Iteration   3: 3.009 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.795 ms/op
                 existUser·p0.50:   2.970 ms/op
                 existUser·p0.90:   3.531 ms/op
                 existUser·p0.95:   3.805 ms/op
                 existUser·p0.99:   4.702 ms/op
                 existUser·p0.999:  8.895 ms/op
                 existUser·p0.9999: 19.542 ms/op
                 existUser·p1.00:   19.595 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 318645
  mean =      3.012 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26919 
    [ 2.500,  5.000) = 288994 
    [ 5.000,  7.500) = 2141 
    [ 7.500, 10.000) = 345 
    [10.000, 12.500) = 71 
    [12.500, 15.000) = 63 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.292 ms/op
     p(50.0000) =      2.966 ms/op
     p(90.0000) =      3.531 ms/op
     p(95.0000) =      3.768 ms/op
     p(99.0000) =      4.841 ms/op
     p(99.9000) =      9.388 ms/op
     p(99.9900) =     21.631 ms/op
     p(99.9990) =     22.276 ms/op
     p(99.9999) =     23.724 ms/op
    p(100.0000) =     23.724 ms/op


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
# Warmup Iteration   1: 4.418 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.367 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.168 ±(99.9%) 0.008 ms/op
Iteration   1: 3.112 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.664 ms/op
                 getUser·p0.50:   3.076 ms/op
                 getUser·p0.90:   3.604 ms/op
                 getUser·p0.95:   4.010 ms/op
                 getUser·p0.99:   5.292 ms/op
                 getUser·p0.999:  8.831 ms/op
                 getUser·p0.9999: 14.907 ms/op
                 getUser·p1.00:   17.170 ms/op

Iteration   2: 3.157 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.802 ms/op
                 getUser·p0.50:   3.117 ms/op
                 getUser·p0.90:   3.686 ms/op
                 getUser·p0.95:   3.981 ms/op
                 getUser·p0.99:   4.891 ms/op
                 getUser·p0.999:  8.564 ms/op
                 getUser·p0.9999: 26.071 ms/op
                 getUser·p1.00:   26.706 ms/op

Iteration   3: 3.179 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.923 ms/op
                 getUser·p0.50:   3.117 ms/op
                 getUser·p0.90:   3.736 ms/op
                 getUser·p0.95:   3.990 ms/op
                 getUser·p0.99:   5.194 ms/op
                 getUser·p0.999:  13.586 ms/op
                 getUser·p0.9999: 33.616 ms/op
                 getUser·p1.00:   34.406 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 304780
  mean =      3.149 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15453 
    [ 2.500,  5.000) = 285893 
    [ 5.000,  7.500) = 2564 
    [ 7.500, 10.000) = 589 
    [10.000, 12.500) = 50 
    [12.500, 15.000) = 98 
    [15.000, 17.500) = 62 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 12 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 26 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.664 ms/op
     p(50.0000) =      3.105 ms/op
     p(90.0000) =      3.686 ms/op
     p(95.0000) =      3.994 ms/op
     p(99.0000) =      5.128 ms/op
     p(99.9000) =      9.408 ms/op
     p(99.9900) =     32.031 ms/op
     p(99.9990) =     34.076 ms/op
     p(99.9999) =     34.406 ms/op
    p(100.0000) =     34.406 ms/op


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
# Warmup Iteration   1: 5.703 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.542 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.269 ±(99.9%) 0.015 ms/op
Iteration   1: 4.258 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.180 ms/op
                 listUser·p0.50:   3.990 ms/op
                 listUser·p0.90:   5.693 ms/op
                 listUser·p0.95:   6.349 ms/op
                 listUser·p0.99:   7.692 ms/op
                 listUser·p0.999:  15.807 ms/op
                 listUser·p0.9999: 22.888 ms/op
                 listUser·p1.00:   23.396 ms/op

Iteration   2: 4.279 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.057 ms/op
                 listUser·p0.50:   4.014 ms/op
                 listUser·p0.90:   5.775 ms/op
                 listUser·p0.95:   6.447 ms/op
                 listUser·p0.99:   7.801 ms/op
                 listUser·p0.999:  22.122 ms/op
                 listUser·p0.9999: 29.247 ms/op
                 listUser·p1.00:   31.064 ms/op

Iteration   3: 4.159 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.090 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   5.472 ms/op
                 listUser·p0.95:   6.210 ms/op
                 listUser·p0.99:   7.988 ms/op
                 listUser·p0.999:  19.726 ms/op
                 listUser·p0.9999: 36.014 ms/op
                 listUser·p1.00:   37.683 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 227013
  mean =      4.231 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2394 
    [ 2.500,  5.000) = 186431 
    [ 5.000,  7.500) = 35139 
    [ 7.500, 10.000) = 2359 
    [10.000, 12.500) = 244 
    [12.500, 15.000) = 114 
    [15.000, 17.500) = 75 
    [17.500, 20.000) = 74 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 43 
    [27.500, 30.000) = 28 
    [30.000, 32.500) = 28 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.057 ms/op
     p(50.0000) =      3.969 ms/op
     p(90.0000) =      5.644 ms/op
     p(95.0000) =      6.357 ms/op
     p(99.0000) =      7.822 ms/op
     p(99.9000) =     18.251 ms/op
     p(99.9900) =     31.683 ms/op
     p(99.9990) =     37.582 ms/op
     p(99.9999) =     37.683 ms/op
    p(100.0000) =     37.683 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.689 ± 3.680  ops/ms
ClientGrpc.existUser                       thrpt       3  10.691 ± 0.739  ops/ms
ClientGrpc.getUser                         thrpt       3  10.154 ± 0.804  ops/ms
ClientGrpc.listUser                        thrpt       3   7.770 ± 0.640  ops/ms
ClientGrpc.createUser                       avgt       3   3.132 ± 0.091   ms/op
ClientGrpc.existUser                        avgt       3   2.980 ± 0.213   ms/op
ClientGrpc.getUser                          avgt       3   3.138 ± 0.897   ms/op
ClientGrpc.listUser                         avgt       3   4.221 ± 0.498   ms/op
ClientGrpc.createUser                     sample  305480   3.143 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.595           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.084           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.727           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.006           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.210           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.651           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          28.508           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          29.655           ms/op
ClientGrpc.existUser                      sample  318645   3.012 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.292           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.966           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.531           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.768           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.841           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.388           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.631           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.724           ms/op
ClientGrpc.getUser                        sample  304780   3.149 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.664           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.105           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.686           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.994           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.128           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.408           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          32.031           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          34.406           ms/op
ClientGrpc.listUser                       sample  227013   4.231 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.057           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.969           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.644           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.357           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.822           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.251           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          31.683           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          37.683           ms/op
