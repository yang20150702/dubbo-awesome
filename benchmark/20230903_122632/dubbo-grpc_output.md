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
# Warmup Iteration   1: 4.548 ops/ms
# Warmup Iteration   2: 9.287 ops/ms
# Warmup Iteration   3: 10.610 ops/ms
Iteration   1: 10.643 ops/ms
Iteration   2: 10.823 ops/ms
Iteration   3: 10.827 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.764 ±(99.9%) 1.917 ops/ms [Average]
  (min, avg, max) = (10.643, 10.764, 10.827), stdev = 0.105
  CI (99.9%): [8.847, 12.681] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 7.720 ops/ms
# Warmup Iteration   2: 10.938 ops/ms
# Warmup Iteration   3: 11.176 ops/ms
Iteration   1: 11.183 ops/ms
Iteration   2: 11.171 ops/ms
Iteration   3: 11.713 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.356 ±(99.9%) 5.647 ops/ms [Average]
  (min, avg, max) = (11.171, 11.356, 11.713), stdev = 0.310
  CI (99.9%): [5.709, 17.002] (assumes normal distribution)


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
# Warmup Iteration   1: 7.865 ops/ms
# Warmup Iteration   2: 10.312 ops/ms
# Warmup Iteration   3: 10.824 ops/ms
Iteration   1: 10.908 ops/ms
Iteration   2: 10.836 ops/ms
Iteration   3: 10.719 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.821 ±(99.9%) 1.736 ops/ms [Average]
  (min, avg, max) = (10.719, 10.821, 10.908), stdev = 0.095
  CI (99.9%): [9.085, 12.557] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.877 ops/ms
# Warmup Iteration   2: 8.039 ops/ms
# Warmup Iteration   3: 8.176 ops/ms
Iteration   1: 8.306 ops/ms
Iteration   2: 8.250 ops/ms
Iteration   3: 8.211 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.255 ±(99.9%) 0.871 ops/ms [Average]
  (min, avg, max) = (8.211, 8.255, 8.306), stdev = 0.048
  CI (99.9%): [7.385, 9.126] (assumes normal distribution)


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
# Warmup Iteration   1: 3.985 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.100 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.006 ±(99.9%) 0.008 ms/op
Iteration   1: 3.075 ±(99.9%) 0.002 ms/op
Iteration   2: 2.924 ±(99.9%) 0.004 ms/op
Iteration   3: 2.990 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.996 ±(99.9%) 1.375 ms/op [Average]
  (min, avg, max) = (2.924, 2.996, 3.075), stdev = 0.075
  CI (99.9%): [1.621, 4.372] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.842 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.950 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.872 ±(99.9%) 0.003 ms/op
Iteration   1: 2.832 ±(99.9%) 0.003 ms/op
Iteration   2: 2.831 ±(99.9%) 0.004 ms/op
Iteration   3: 2.820 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.828 ±(99.9%) 0.120 ms/op [Average]
  (min, avg, max) = (2.820, 2.828, 2.832), stdev = 0.007
  CI (99.9%): [2.707, 2.948] (assumes normal distribution)


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
# Warmup Iteration   1: 3.985 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.060 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.986 ±(99.9%) 0.002 ms/op
Iteration   1: 2.962 ±(99.9%) 0.003 ms/op
Iteration   2: 2.965 ±(99.9%) 0.004 ms/op
Iteration   3: 2.946 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.958 ±(99.9%) 0.184 ms/op [Average]
  (min, avg, max) = (2.946, 2.958, 2.965), stdev = 0.010
  CI (99.9%): [2.774, 3.141] (assumes normal distribution)


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
# Warmup Iteration   1: 4.363 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.071 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 3.878 ±(99.9%) 0.014 ms/op
Iteration   1: 3.931 ±(99.9%) 0.006 ms/op
Iteration   2: 3.868 ±(99.9%) 0.029 ms/op
Iteration   3: 3.852 ±(99.9%) 0.035 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.884 ±(99.9%) 0.760 ms/op [Average]
  (min, avg, max) = (3.852, 3.884, 3.931), stdev = 0.042
  CI (99.9%): [3.123, 4.644] (assumes normal distribution)


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
# Warmup Iteration   1: 4.152 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.098 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.932 ±(99.9%) 0.008 ms/op
Iteration   1: 2.949 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.598 ms/op
                 createUser·p0.50:   2.925 ms/op
                 createUser·p0.90:   3.473 ms/op
                 createUser·p0.95:   3.760 ms/op
                 createUser·p0.99:   4.653 ms/op
                 createUser·p0.999:  7.556 ms/op
                 createUser·p0.9999: 18.813 ms/op
                 createUser·p1.00:   19.431 ms/op

Iteration   2: 2.923 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.588 ms/op
                 createUser·p0.50:   2.945 ms/op
                 createUser·p0.90:   3.383 ms/op
                 createUser·p0.95:   3.654 ms/op
                 createUser·p0.99:   4.424 ms/op
                 createUser·p0.999:  7.234 ms/op
                 createUser·p0.9999: 18.159 ms/op
                 createUser·p1.00:   19.988 ms/op

Iteration   3: 2.959 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.484 ms/op
                 createUser·p0.50:   2.945 ms/op
                 createUser·p0.90:   3.416 ms/op
                 createUser·p0.95:   3.715 ms/op
                 createUser·p0.99:   4.669 ms/op
                 createUser·p0.999:  9.859 ms/op
                 createUser·p0.9999: 21.216 ms/op
                 createUser·p1.00:   21.889 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 326262
  mean =      2.944 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 37082 
    [ 2.500,  5.000) = 287314 
    [ 5.000,  7.500) = 1419 
    [ 7.500, 10.000) = 216 
    [10.000, 12.500) = 33 
    [12.500, 15.000) = 6 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 121 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.484 ms/op
     p(50.0000) =      2.937 ms/op
     p(90.0000) =      3.424 ms/op
     p(95.0000) =      3.711 ms/op
     p(99.0000) =      4.612 ms/op
     p(99.9000) =      8.020 ms/op
     p(99.9900) =     19.554 ms/op
     p(99.9990) =     21.889 ms/op
     p(99.9999) =     21.889 ms/op
    p(100.0000) =     21.889 ms/op


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
# Warmup Iteration   1: 3.534 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 2.956 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.875 ±(99.9%) 0.006 ms/op
Iteration   1: 2.897 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.660 ms/op
                 existUser·p0.50:   2.879 ms/op
                 existUser·p0.90:   3.412 ms/op
                 existUser·p0.95:   3.609 ms/op
                 existUser·p0.99:   4.481 ms/op
                 existUser·p0.999:  7.842 ms/op
                 existUser·p0.9999: 16.726 ms/op
                 existUser·p1.00:   16.908 ms/op

Iteration   2: 2.862 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.696 ms/op
                 existUser·p0.50:   2.871 ms/op
                 existUser·p0.90:   3.445 ms/op
                 existUser·p0.95:   3.690 ms/op
                 existUser·p0.99:   4.555 ms/op
                 existUser·p0.999:  7.127 ms/op
                 existUser·p0.9999: 13.009 ms/op
                 existUser·p1.00:   14.320 ms/op

Iteration   3: 2.768 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.621 ms/op
                 existUser·p0.50:   2.830 ms/op
                 existUser·p0.90:   3.273 ms/op
                 existUser·p0.95:   3.502 ms/op
                 existUser·p0.99:   4.252 ms/op
                 existUser·p0.999:  7.056 ms/op
                 existUser·p0.9999: 22.657 ms/op
                 existUser·p1.00:   24.150 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 337958
  mean =      2.841 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 56987 
    [ 2.500,  5.000) = 279547 
    [ 5.000,  7.500) = 1113 
    [ 7.500, 10.000) = 119 
    [10.000, 12.500) = 59 
    [12.500, 15.000) = 40 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.621 ms/op
     p(50.0000) =      2.859 ms/op
     p(90.0000) =      3.379 ms/op
     p(95.0000) =      3.609 ms/op
     p(99.0000) =      4.432 ms/op
     p(99.9000) =      7.422 ms/op
     p(99.9900) =     17.079 ms/op
     p(99.9990) =     22.872 ms/op
     p(99.9999) =     24.150 ms/op
    p(100.0000) =     24.150 ms/op


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
# Warmup Iteration   1: 3.956 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 2.999 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.992 ±(99.9%) 0.006 ms/op
Iteration   1: 2.974 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.742 ms/op
                 getUser·p0.50:   2.966 ms/op
                 getUser·p0.90:   3.527 ms/op
                 getUser·p0.95:   3.822 ms/op
                 getUser·p0.99:   4.514 ms/op
                 getUser·p0.999:  8.240 ms/op
                 getUser·p0.9999: 20.873 ms/op
                 getUser·p1.00:   21.037 ms/op

Iteration   2: 2.961 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.531 ms/op
                 getUser·p0.50:   2.945 ms/op
                 getUser·p0.90:   3.518 ms/op
                 getUser·p0.95:   3.781 ms/op
                 getUser·p0.99:   4.506 ms/op
                 getUser·p0.999:  7.493 ms/op
                 getUser·p0.9999: 22.839 ms/op
                 getUser·p1.00:   23.036 ms/op

Iteration   3: 2.971 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.592 ms/op
                 getUser·p0.50:   2.966 ms/op
                 getUser·p0.90:   3.445 ms/op
                 getUser·p0.95:   3.715 ms/op
                 getUser·p0.99:   4.391 ms/op
                 getUser·p0.999:  8.065 ms/op
                 getUser·p0.9999: 16.712 ms/op
                 getUser·p1.00:   16.744 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 323632
  mean =      2.969 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 34638 
    [ 2.500,  5.000) = 287312 
    [ 5.000,  7.500) = 1292 
    [ 7.500, 10.000) = 213 
    [10.000, 12.500) = 17 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.531 ms/op
     p(50.0000) =      2.957 ms/op
     p(90.0000) =      3.498 ms/op
     p(95.0000) =      3.772 ms/op
     p(99.0000) =      4.473 ms/op
     p(99.9000) =      7.913 ms/op
     p(99.9900) =     21.037 ms/op
     p(99.9990) =     23.020 ms/op
     p(99.9999) =     23.036 ms/op
    p(100.0000) =     23.036 ms/op


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
# Warmup Iteration   1: 4.572 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.061 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.895 ±(99.9%) 0.010 ms/op
Iteration   1: 3.819 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.065 ms/op
                 listUser·p0.50:   3.699 ms/op
                 listUser·p0.90:   4.710 ms/op
                 listUser·p0.95:   5.464 ms/op
                 listUser·p0.99:   7.029 ms/op
                 listUser·p0.999:  12.096 ms/op
                 listUser·p0.9999: 13.740 ms/op
                 listUser·p1.00:   14.877 ms/op

Iteration   2: 3.893 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.059 ms/op
                 listUser·p0.50:   3.740 ms/op
                 listUser·p0.90:   4.882 ms/op
                 listUser·p0.95:   5.579 ms/op
                 listUser·p0.99:   6.988 ms/op
                 listUser·p0.999:  16.364 ms/op
                 listUser·p0.9999: 23.709 ms/op
                 listUser·p1.00:   23.986 ms/op

Iteration   3: 3.959 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.431 ms/op
                 listUser·p0.50:   3.752 ms/op
                 listUser·p0.90:   5.259 ms/op
                 listUser·p0.95:   5.857 ms/op
                 listUser·p0.99:   6.816 ms/op
                 listUser·p0.999:  15.425 ms/op
                 listUser·p0.9999: 20.107 ms/op
                 listUser·p1.00:   20.709 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 246725
  mean =      3.890 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6884 
    [ 2.500,  5.000) = 215283 
    [ 5.000,  7.500) = 22965 
    [ 7.500, 10.000) = 1031 
    [10.000, 12.500) = 157 
    [12.500, 15.000) = 172 
    [15.000, 17.500) = 134 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.431 ms/op
     p(50.0000) =      3.727 ms/op
     p(90.0000) =      4.997 ms/op
     p(95.0000) =      5.669 ms/op
     p(99.0000) =      6.963 ms/op
     p(99.9000) =     14.750 ms/op
     p(99.9900) =     21.463 ms/op
     p(99.9990) =     23.923 ms/op
     p(99.9999) =     23.986 ms/op
    p(100.0000) =     23.986 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.764 ± 1.917  ops/ms
ClientGrpc.existUser                       thrpt       3  11.356 ± 5.647  ops/ms
ClientGrpc.getUser                         thrpt       3  10.821 ± 1.736  ops/ms
ClientGrpc.listUser                        thrpt       3   8.255 ± 0.871  ops/ms
ClientGrpc.createUser                       avgt       3   2.996 ± 1.375   ms/op
ClientGrpc.existUser                        avgt       3   2.828 ± 0.120   ms/op
ClientGrpc.getUser                          avgt       3   2.958 ± 0.184   ms/op
ClientGrpc.listUser                         avgt       3   3.884 ± 0.760   ms/op
ClientGrpc.createUser                     sample  326262   2.944 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.484           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.937           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.424           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.711           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.612           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.020           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.554           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.889           ms/op
ClientGrpc.existUser                      sample  337958   2.841 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.621           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.859           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.379           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.609           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.432           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.422           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.079           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          24.150           ms/op
ClientGrpc.getUser                        sample  323632   2.969 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.531           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.957           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.498           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.772           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.473           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.913           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.037           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.036           ms/op
ClientGrpc.listUser                       sample  246725   3.890 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.431           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.727           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.997           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.669           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.963           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.750           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.463           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.986           ms/op
