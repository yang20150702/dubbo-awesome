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
# Warmup Iteration   1: 4.581 ops/ms
# Warmup Iteration   2: 9.286 ops/ms
# Warmup Iteration   3: 10.189 ops/ms
Iteration   1: 10.653 ops/ms
Iteration   2: 10.732 ops/ms
Iteration   3: 10.577 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.654 ±(99.9%) 1.416 ops/ms [Average]
  (min, avg, max) = (10.577, 10.654, 10.732), stdev = 0.078
  CI (99.9%): [9.238, 12.071] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 8.125 ops/ms
# Warmup Iteration   2: 10.997 ops/ms
# Warmup Iteration   3: 11.335 ops/ms
Iteration   1: 11.218 ops/ms
Iteration   2: 11.336 ops/ms
Iteration   3: 11.312 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.289 ±(99.9%) 1.135 ops/ms [Average]
  (min, avg, max) = (11.218, 11.289, 11.336), stdev = 0.062
  CI (99.9%): [10.153, 12.424] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.421 ops/ms
# Warmup Iteration   2: 10.403 ops/ms
# Warmup Iteration   3: 10.662 ops/ms
Iteration   1: 10.844 ops/ms
Iteration   2: 10.808 ops/ms
Iteration   3: 10.802 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.818 ±(99.9%) 0.418 ops/ms [Average]
  (min, avg, max) = (10.802, 10.818, 10.844), stdev = 0.023
  CI (99.9%): [10.400, 11.236] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.269 ops/ms
# Warmup Iteration   2: 8.141 ops/ms
# Warmup Iteration   3: 8.194 ops/ms
Iteration   1: 8.297 ops/ms
Iteration   2: 8.405 ops/ms
Iteration   3: 8.400 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.367 ±(99.9%) 1.116 ops/ms [Average]
  (min, avg, max) = (8.297, 8.367, 8.405), stdev = 0.061
  CI (99.9%): [7.251, 9.483] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.054 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.103 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.027 ±(99.9%) 0.003 ms/op
Iteration   1: 3.045 ±(99.9%) 0.003 ms/op
Iteration   2: 2.958 ±(99.9%) 0.002 ms/op
Iteration   3: 2.979 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.994 ±(99.9%) 0.821 ms/op [Average]
  (min, avg, max) = (2.958, 2.994, 3.045), stdev = 0.045
  CI (99.9%): [2.173, 3.815] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.467 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.969 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.852 ±(99.9%) 0.003 ms/op
Iteration   1: 2.951 ±(99.9%) 0.004 ms/op
Iteration   2: 2.835 ±(99.9%) 0.003 ms/op
Iteration   3: 2.855 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.881 ±(99.9%) 1.131 ms/op [Average]
  (min, avg, max) = (2.835, 2.881, 2.951), stdev = 0.062
  CI (99.9%): [1.749, 4.012] (assumes normal distribution)


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
# Warmup Iteration   1: 3.920 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.033 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.953 ±(99.9%) 0.003 ms/op
Iteration   1: 2.939 ±(99.9%) 0.002 ms/op
Iteration   2: 2.945 ±(99.9%) 0.002 ms/op
Iteration   3: 2.924 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.936 ±(99.9%) 0.195 ms/op [Average]
  (min, avg, max) = (2.924, 2.936, 2.945), stdev = 0.011
  CI (99.9%): [2.741, 3.131] (assumes normal distribution)


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
# Warmup Iteration   1: 4.403 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.979 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.826 ±(99.9%) 0.026 ms/op
Iteration   1: 3.838 ±(99.9%) 0.011 ms/op
Iteration   2: 3.835 ±(99.9%) 0.021 ms/op
Iteration   3: 3.804 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.826 ±(99.9%) 0.342 ms/op [Average]
  (min, avg, max) = (3.804, 3.826, 3.838), stdev = 0.019
  CI (99.9%): [3.483, 4.168] (assumes normal distribution)


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
# Warmup Iteration   1: 4.055 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.059 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.967 ±(99.9%) 0.007 ms/op
Iteration   1: 2.907 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.580 ms/op
                 createUser·p0.50:   2.925 ms/op
                 createUser·p0.90:   3.355 ms/op
                 createUser·p0.95:   3.613 ms/op
                 createUser·p0.99:   4.497 ms/op
                 createUser·p0.999:  11.305 ms/op
                 createUser·p0.9999: 13.892 ms/op
                 createUser·p1.00:   16.007 ms/op

Iteration   2: 2.989 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.553 ms/op
                 createUser·p0.50:   2.949 ms/op
                 createUser·p0.90:   3.596 ms/op
                 createUser·p0.95:   3.883 ms/op
                 createUser·p0.99:   4.645 ms/op
                 createUser·p0.999:  10.295 ms/op
                 createUser·p0.9999: 20.588 ms/op
                 createUser·p1.00:   21.004 ms/op

Iteration   3: 2.969 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.720 ms/op
                 createUser·p0.50:   2.949 ms/op
                 createUser·p0.90:   3.473 ms/op
                 createUser·p0.95:   3.744 ms/op
                 createUser·p0.99:   4.563 ms/op
                 createUser·p0.999:  11.715 ms/op
                 createUser·p0.9999: 15.680 ms/op
                 createUser·p1.00:   16.679 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 325068
  mean =      2.954 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 34779 
    [ 2.500,  5.000) = 288437 
    [ 5.000,  7.500) = 1305 
    [ 7.500, 10.000) = 175 
    [10.000, 12.500) = 154 
    [12.500, 15.000) = 129 
    [15.000, 17.500) = 57 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.553 ms/op
     p(50.0000) =      2.941 ms/op
     p(90.0000) =      3.486 ms/op
     p(95.0000) =      3.752 ms/op
     p(99.0000) =      4.579 ms/op
     p(99.9000) =     11.090 ms/op
     p(99.9900) =     18.198 ms/op
     p(99.9990) =     20.898 ms/op
     p(99.9999) =     21.004 ms/op
    p(100.0000) =     21.004 ms/op


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
# Warmup Iteration   1: 3.610 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 2.967 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.848 ±(99.9%) 0.006 ms/op
Iteration   1: 2.854 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.532 ms/op
                 existUser·p0.50:   2.839 ms/op
                 existUser·p0.90:   3.359 ms/op
                 existUser·p0.95:   3.633 ms/op
                 existUser·p0.99:   4.432 ms/op
                 existUser·p0.999:  8.102 ms/op
                 existUser·p0.9999: 16.895 ms/op
                 existUser·p1.00:   18.153 ms/op

Iteration   2: 2.887 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.462 ms/op
                 existUser·p0.50:   2.888 ms/op
                 existUser·p0.90:   3.387 ms/op
                 existUser·p0.95:   3.543 ms/op
                 existUser·p0.99:   3.981 ms/op
                 existUser·p0.999:  6.223 ms/op
                 existUser·p0.9999: 16.286 ms/op
                 existUser·p1.00:   17.302 ms/op

Iteration   3: 2.872 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.660 ms/op
                 existUser·p0.50:   2.847 ms/op
                 existUser·p0.90:   3.314 ms/op
                 existUser·p0.95:   3.584 ms/op
                 existUser·p0.99:   4.415 ms/op
                 existUser·p0.999:  8.438 ms/op
                 existUser·p0.9999: 16.297 ms/op
                 existUser·p1.00:   17.891 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 334392
  mean =      2.871 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2821 
    [ 1.250,  2.500) = 43814 
    [ 2.500,  3.750) = 277672 
    [ 3.750,  5.000) = 9071 
    [ 5.000,  6.250) = 523 
    [ 6.250,  7.500) = 138 
    [ 7.500,  8.750) = 100 
    [ 8.750, 10.000) = 17 
    [10.000, 11.250) = 31 
    [11.250, 12.500) = 65 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 15 
    [15.000, 16.250) = 68 
    [16.250, 17.500) = 46 
    [17.500, 18.750) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.462 ms/op
     p(50.0000) =      2.859 ms/op
     p(90.0000) =      3.359 ms/op
     p(95.0000) =      3.576 ms/op
     p(99.0000) =      4.317 ms/op
     p(99.9000) =      7.892 ms/op
     p(99.9900) =     16.641 ms/op
     p(99.9990) =     18.065 ms/op
     p(99.9999) =     18.153 ms/op
    p(100.0000) =     18.153 ms/op


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
# Warmup Iteration   1: 3.768 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.051 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.991 ±(99.9%) 0.006 ms/op
Iteration   1: 2.964 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.584 ms/op
                 getUser·p0.50:   2.949 ms/op
                 getUser·p0.90:   3.473 ms/op
                 getUser·p0.95:   3.711 ms/op
                 getUser·p0.99:   4.538 ms/op
                 getUser·p0.999:  8.054 ms/op
                 getUser·p0.9999: 23.895 ms/op
                 getUser·p1.00:   24.445 ms/op

Iteration   2: 2.925 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.701 ms/op
                 getUser·p0.50:   2.912 ms/op
                 getUser·p0.90:   3.478 ms/op
                 getUser·p0.95:   3.744 ms/op
                 getUser·p0.99:   4.514 ms/op
                 getUser·p0.999:  7.987 ms/op
                 getUser·p0.9999: 18.352 ms/op
                 getUser·p1.00:   19.726 ms/op

Iteration   3: 2.905 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.653 ms/op
                 getUser·p0.50:   2.916 ms/op
                 getUser·p0.90:   3.342 ms/op
                 getUser·p0.95:   3.564 ms/op
                 getUser·p0.99:   4.268 ms/op
                 getUser·p0.999:  7.634 ms/op
                 getUser·p0.9999: 19.595 ms/op
                 getUser·p1.00:   20.087 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 327528
  mean =      2.931 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 37949 
    [ 2.500,  5.000) = 287826 
    [ 5.000,  7.500) = 1345 
    [ 7.500, 10.000) = 178 
    [10.000, 12.500) = 38 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 87 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.584 ms/op
     p(50.0000) =      2.925 ms/op
     p(90.0000) =      3.428 ms/op
     p(95.0000) =      3.678 ms/op
     p(99.0000) =      4.473 ms/op
     p(99.9000) =      7.832 ms/op
     p(99.9900) =     21.427 ms/op
     p(99.9990) =     24.117 ms/op
     p(99.9999) =     24.445 ms/op
    p(100.0000) =     24.445 ms/op


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
# Warmup Iteration   1: 4.987 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.035 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.872 ±(99.9%) 0.013 ms/op
Iteration   1: 3.863 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.098 ms/op
                 listUser·p0.50:   3.699 ms/op
                 listUser·p0.90:   5.005 ms/op
                 listUser·p0.95:   5.497 ms/op
                 listUser·p0.99:   6.799 ms/op
                 listUser·p0.999:  15.352 ms/op
                 listUser·p0.9999: 18.734 ms/op
                 listUser·p1.00:   19.726 ms/op

Iteration   2: 3.853 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.771 ms/op
                 listUser·p0.50:   3.707 ms/op
                 listUser·p0.90:   4.973 ms/op
                 listUser·p0.95:   5.571 ms/op
                 listUser·p0.99:   6.914 ms/op
                 listUser·p0.999:  16.234 ms/op
                 listUser·p0.9999: 24.818 ms/op
                 listUser·p1.00:   25.428 ms/op

Iteration   3: 3.821 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.551 ms/op
                 listUser·p0.50:   3.645 ms/op
                 listUser·p0.90:   4.932 ms/op
                 listUser·p0.95:   5.521 ms/op
                 listUser·p0.99:   7.012 ms/op
                 listUser·p0.999:  15.286 ms/op
                 listUser·p0.9999: 18.444 ms/op
                 listUser·p1.00:   19.562 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 249813
  mean =      3.845 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7473 
    [ 2.500,  5.000) = 218152 
    [ 5.000,  7.500) = 22863 
    [ 7.500, 10.000) = 815 
    [10.000, 12.500) = 55 
    [12.500, 15.000) = 144 
    [15.000, 17.500) = 199 
    [17.500, 20.000) = 67 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.551 ms/op
     p(50.0000) =      3.686 ms/op
     p(90.0000) =      4.973 ms/op
     p(95.0000) =      5.530 ms/op
     p(99.0000) =      6.906 ms/op
     p(99.9000) =     15.470 ms/op
     p(99.9900) =     24.084 ms/op
     p(99.9990) =     25.297 ms/op
     p(99.9999) =     25.428 ms/op
    p(100.0000) =     25.428 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.654 ± 1.416  ops/ms
ClientGrpc.existUser                       thrpt       3  11.289 ± 1.135  ops/ms
ClientGrpc.getUser                         thrpt       3  10.818 ± 0.418  ops/ms
ClientGrpc.listUser                        thrpt       3   8.367 ± 1.116  ops/ms
ClientGrpc.createUser                       avgt       3   2.994 ± 0.821   ms/op
ClientGrpc.existUser                        avgt       3   2.881 ± 1.131   ms/op
ClientGrpc.getUser                          avgt       3   2.936 ± 0.195   ms/op
ClientGrpc.listUser                         avgt       3   3.826 ± 0.342   ms/op
ClientGrpc.createUser                     sample  325068   2.954 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.553           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.941           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.486           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.752           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.579           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.090           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.198           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.004           ms/op
ClientGrpc.existUser                      sample  334392   2.871 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.462           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.859           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.359           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.576           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.317           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.892           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.641           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.153           ms/op
ClientGrpc.getUser                        sample  327528   2.931 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.584           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.925           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.428           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.678           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.473           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.832           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.427           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.445           ms/op
ClientGrpc.listUser                       sample  249813   3.845 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.551           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.686           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.973           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.530           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.906           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.470           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.084           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.428           ms/op
