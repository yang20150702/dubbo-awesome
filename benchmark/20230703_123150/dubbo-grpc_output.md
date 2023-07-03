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
# Warmup Iteration   1: 4.416 ops/ms
# Warmup Iteration   2: 9.181 ops/ms
# Warmup Iteration   3: 10.378 ops/ms
Iteration   1: 10.411 ops/ms
Iteration   2: 10.620 ops/ms
Iteration   3: 10.658 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.563 ±(99.9%) 2.426 ops/ms [Average]
  (min, avg, max) = (10.411, 10.563, 10.658), stdev = 0.133
  CI (99.9%): [8.137, 12.990] (assumes normal distribution)


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
# Warmup Iteration   1: 8.011 ops/ms
# Warmup Iteration   2: 10.853 ops/ms
# Warmup Iteration   3: 11.007 ops/ms
Iteration   1: 11.039 ops/ms
Iteration   2: 11.102 ops/ms
Iteration   3: 11.326 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.156 ±(99.9%) 2.750 ops/ms [Average]
  (min, avg, max) = (11.039, 11.156, 11.326), stdev = 0.151
  CI (99.9%): [8.406, 13.906] (assumes normal distribution)


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
# Warmup Iteration   1: 7.705 ops/ms
# Warmup Iteration   2: 10.313 ops/ms
# Warmup Iteration   3: 10.551 ops/ms
Iteration   1: 10.671 ops/ms
Iteration   2: 10.722 ops/ms
Iteration   3: 10.842 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.745 ±(99.9%) 1.603 ops/ms [Average]
  (min, avg, max) = (10.671, 10.745, 10.842), stdev = 0.088
  CI (99.9%): [9.142, 12.348] (assumes normal distribution)


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
# Warmup Iteration   1: 6.801 ops/ms
# Warmup Iteration   2: 8.208 ops/ms
# Warmup Iteration   3: 8.207 ops/ms
Iteration   1: 8.384 ops/ms
Iteration   2: 8.197 ops/ms
Iteration   3: 8.217 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.266 ±(99.9%) 1.877 ops/ms [Average]
  (min, avg, max) = (8.197, 8.266, 8.384), stdev = 0.103
  CI (99.9%): [6.390, 10.143] (assumes normal distribution)


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
# Warmup Iteration   1: 3.963 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.087 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.009 ±(99.9%) 0.003 ms/op
Iteration   1: 2.967 ±(99.9%) 0.001 ms/op
Iteration   2: 2.968 ±(99.9%) 0.003 ms/op
Iteration   3: 3.021 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.986 ±(99.9%) 0.559 ms/op [Average]
  (min, avg, max) = (2.967, 2.986, 3.021), stdev = 0.031
  CI (99.9%): [2.426, 3.545] (assumes normal distribution)


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
# Warmup Iteration   1: 3.929 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.912 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.837 ±(99.9%) 0.004 ms/op
Iteration   1: 2.846 ±(99.9%) 0.003 ms/op
Iteration   2: 2.842 ±(99.9%) 0.004 ms/op
Iteration   3: 2.842 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.844 ±(99.9%) 0.036 ms/op [Average]
  (min, avg, max) = (2.842, 2.844, 2.846), stdev = 0.002
  CI (99.9%): [2.808, 2.879] (assumes normal distribution)


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
# Warmup Iteration   1: 3.876 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.070 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.004 ±(99.9%) 0.003 ms/op
Iteration   1: 3.029 ±(99.9%) 0.005 ms/op
Iteration   2: 3.023 ±(99.9%) 0.003 ms/op
Iteration   3: 2.979 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.010 ±(99.9%) 0.496 ms/op [Average]
  (min, avg, max) = (2.979, 3.010, 3.029), stdev = 0.027
  CI (99.9%): [2.514, 3.506] (assumes normal distribution)


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
# Warmup Iteration   1: 4.958 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.950 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 3.880 ±(99.9%) 0.007 ms/op
Iteration   1: 3.844 ±(99.9%) 0.008 ms/op
Iteration   2: 3.866 ±(99.9%) 0.015 ms/op
Iteration   3: 3.780 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.830 ±(99.9%) 0.814 ms/op [Average]
  (min, avg, max) = (3.780, 3.830, 3.866), stdev = 0.045
  CI (99.9%): [3.016, 4.644] (assumes normal distribution)


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
# Warmup Iteration   1: 4.173 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.213 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.998 ±(99.9%) 0.007 ms/op
Iteration   1: 2.989 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.588 ms/op
                 createUser·p0.50:   2.970 ms/op
                 createUser·p0.90:   3.559 ms/op
                 createUser·p0.95:   3.871 ms/op
                 createUser·p0.99:   4.571 ms/op
                 createUser·p0.999:  9.241 ms/op
                 createUser·p0.9999: 15.106 ms/op
                 createUser·p1.00:   15.548 ms/op

Iteration   2: 2.994 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.545 ms/op
                 createUser·p0.50:   2.990 ms/op
                 createUser·p0.90:   3.551 ms/op
                 createUser·p0.95:   3.760 ms/op
                 createUser·p0.99:   4.473 ms/op
                 createUser·p0.999:  9.515 ms/op
                 createUser·p0.9999: 20.828 ms/op
                 createUser·p1.00:   21.168 ms/op

Iteration   3: 3.013 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.708 ms/op
                 createUser·p0.50:   2.974 ms/op
                 createUser·p0.90:   3.490 ms/op
                 createUser·p0.95:   3.731 ms/op
                 createUser·p0.99:   4.407 ms/op
                 createUser·p0.999:  12.489 ms/op
                 createUser·p0.9999: 21.966 ms/op
                 createUser·p1.00:   22.577 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 320226
  mean =      2.999 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31164 
    [ 2.500,  5.000) = 287686 
    [ 5.000,  7.500) = 911 
    [ 7.500, 10.000) = 108 
    [10.000, 12.500) = 91 
    [12.500, 15.000) = 91 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 55 
    [20.000, 22.500) = 68 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.545 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.531 ms/op
     p(95.0000) =      3.789 ms/op
     p(99.0000) =      4.506 ms/op
     p(99.9000) =     10.515 ms/op
     p(99.9900) =     20.742 ms/op
     p(99.9990) =     22.538 ms/op
     p(99.9999) =     22.577 ms/op
    p(100.0000) =     22.577 ms/op


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
# Warmup Iteration   1: 3.573 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 2.968 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.937 ±(99.9%) 0.006 ms/op
Iteration   1: 2.944 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.699 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.404 ms/op
                 existUser·p0.95:   3.645 ms/op
                 existUser·p0.99:   4.067 ms/op
                 existUser·p0.999:  7.892 ms/op
                 existUser·p0.9999: 15.537 ms/op
                 existUser·p1.00:   22.053 ms/op

Iteration   2: 2.887 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.768 ms/op
                 existUser·p0.50:   2.859 ms/op
                 existUser·p0.90:   3.437 ms/op
                 existUser·p0.95:   3.650 ms/op
                 existUser·p0.99:   4.391 ms/op
                 existUser·p0.999:  5.778 ms/op
                 existUser·p0.9999: 12.877 ms/op
                 existUser·p1.00:   13.140 ms/op

Iteration   3: 2.953 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.596 ms/op
                 existUser·p0.50:   2.916 ms/op
                 existUser·p0.90:   3.461 ms/op
                 existUser·p0.95:   3.625 ms/op
                 existUser·p0.99:   4.514 ms/op
                 existUser·p0.999:  8.618 ms/op
                 existUser·p0.9999: 18.066 ms/op
                 existUser·p1.00:   18.252 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 327701
  mean =      2.928 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 41302 
    [ 2.500,  5.000) = 285168 
    [ 5.000,  7.500) = 830 
    [ 7.500, 10.000) = 208 
    [10.000, 12.500) = 51 
    [12.500, 15.000) = 63 
    [15.000, 17.500) = 60 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.596 ms/op
     p(50.0000) =      2.896 ms/op
     p(90.0000) =      3.441 ms/op
     p(95.0000) =      3.641 ms/op
     p(99.0000) =      4.358 ms/op
     p(99.9000) =      7.946 ms/op
     p(99.9900) =     15.818 ms/op
     p(99.9990) =     18.177 ms/op
     p(99.9999) =     22.053 ms/op
    p(100.0000) =     22.053 ms/op


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
# Warmup Iteration   1: 3.835 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.028 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.024 ±(99.9%) 0.006 ms/op
Iteration   1: 2.986 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.565 ms/op
                 getUser·p0.50:   2.990 ms/op
                 getUser·p0.90:   3.621 ms/op
                 getUser·p0.95:   3.891 ms/op
                 getUser·p0.99:   4.497 ms/op
                 getUser·p0.999:  9.454 ms/op
                 getUser·p0.9999: 23.953 ms/op
                 getUser·p1.00:   24.216 ms/op

Iteration   2: 3.001 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.785 ms/op
                 getUser·p0.50:   2.998 ms/op
                 getUser·p0.90:   3.551 ms/op
                 getUser·p0.95:   3.719 ms/op
                 getUser·p0.99:   4.227 ms/op
                 getUser·p0.999:  6.368 ms/op
                 getUser·p0.9999: 16.886 ms/op
                 getUser·p1.00:   17.236 ms/op

Iteration   3: 2.961 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.600 ms/op
                 getUser·p0.50:   2.957 ms/op
                 getUser·p0.90:   3.420 ms/op
                 getUser·p0.95:   3.633 ms/op
                 getUser·p0.99:   4.317 ms/op
                 getUser·p0.999:  7.537 ms/op
                 getUser·p0.9999: 27.532 ms/op
                 getUser·p1.00:   28.148 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 321676
  mean =      2.983 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31441 
    [ 2.500,  5.000) = 289111 
    [ 5.000,  7.500) = 839 
    [ 7.500, 10.000) = 77 
    [10.000, 12.500) = 28 
    [12.500, 15.000) = 52 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.565 ms/op
     p(50.0000) =      2.982 ms/op
     p(90.0000) =      3.535 ms/op
     p(95.0000) =      3.748 ms/op
     p(99.0000) =      4.358 ms/op
     p(99.9000) =      7.244 ms/op
     p(99.9900) =     25.225 ms/op
     p(99.9990) =     28.010 ms/op
     p(99.9999) =     28.148 ms/op
    p(100.0000) =     28.148 ms/op


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
# Warmup Iteration   1: 4.693 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.979 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.921 ±(99.9%) 0.011 ms/op
Iteration   1: 3.821 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.935 ms/op
                 listUser·p0.50:   3.736 ms/op
                 listUser·p0.90:   4.604 ms/op
                 listUser·p0.95:   5.333 ms/op
                 listUser·p0.99:   6.717 ms/op
                 listUser·p0.999:  12.337 ms/op
                 listUser·p0.9999: 15.231 ms/op
                 listUser·p1.00:   15.745 ms/op

Iteration   2: 3.900 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.939 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   4.776 ms/op
                 listUser·p0.95:   5.497 ms/op
                 listUser·p0.99:   7.004 ms/op
                 listUser·p0.999:  15.137 ms/op
                 listUser·p0.9999: 19.169 ms/op
                 listUser·p1.00:   21.856 ms/op

Iteration   3: 3.977 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.671 ms/op
                 listUser·p0.50:   3.830 ms/op
                 listUser·p0.90:   4.874 ms/op
                 listUser·p0.95:   5.530 ms/op
                 listUser·p0.99:   6.857 ms/op
                 listUser·p0.999:  15.319 ms/op
                 listUser·p0.9999: 27.754 ms/op
                 listUser·p1.00:   30.147 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 246147
  mean =      3.898 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3555 
    [ 2.500,  5.000) = 223363 
    [ 5.000,  7.500) = 17879 
    [ 7.500, 10.000) = 877 
    [10.000, 12.500) = 100 
    [12.500, 15.000) = 178 
    [15.000, 17.500) = 99 
    [17.500, 20.000) = 58 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 9 
    [27.500, 30.000) = 10 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.671 ms/op
     p(50.0000) =      3.777 ms/op
     p(90.0000) =      4.760 ms/op
     p(95.0000) =      5.456 ms/op
     p(99.0000) =      6.849 ms/op
     p(99.9000) =     14.057 ms/op
     p(99.9900) =     23.500 ms/op
     p(99.9990) =     27.959 ms/op
     p(99.9999) =     30.147 ms/op
    p(100.0000) =     30.147 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.563 ± 2.426  ops/ms
ClientGrpc.existUser                       thrpt       3  11.156 ± 2.750  ops/ms
ClientGrpc.getUser                         thrpt       3  10.745 ± 1.603  ops/ms
ClientGrpc.listUser                        thrpt       3   8.266 ± 1.877  ops/ms
ClientGrpc.createUser                       avgt       3   2.986 ± 0.559   ms/op
ClientGrpc.existUser                        avgt       3   2.844 ± 0.036   ms/op
ClientGrpc.getUser                          avgt       3   3.010 ± 0.496   ms/op
ClientGrpc.listUser                         avgt       3   3.830 ± 0.814   ms/op
ClientGrpc.createUser                     sample  320226   2.999 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.545           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.978           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.531           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.789           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.506           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.515           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.742           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.577           ms/op
ClientGrpc.existUser                      sample  327701   2.928 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.596           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.896           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.441           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.641           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.358           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.946           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.818           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.053           ms/op
ClientGrpc.getUser                        sample  321676   2.983 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.565           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.982           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.535           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.748           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.358           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.244           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          25.225           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          28.148           ms/op
ClientGrpc.listUser                       sample  246147   3.898 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.671           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.777           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.760           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.456           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.849           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.057           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.500           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          30.147           ms/op
