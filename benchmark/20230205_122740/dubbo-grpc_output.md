# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.817 ops/ms
# Warmup Iteration   2: 8.926 ops/ms
# Warmup Iteration   3: 10.209 ops/ms
Iteration   1: 10.489 ops/ms
Iteration   2: 10.162 ops/ms
Iteration   3: 9.933 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.195 ±(99.9%) 5.092 ops/ms [Average]
  (min, avg, max) = (9.933, 10.195, 10.489), stdev = 0.279
  CI (99.9%): [5.102, 15.287] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 8.022 ops/ms
# Warmup Iteration   2: 10.636 ops/ms
# Warmup Iteration   3: 10.812 ops/ms
Iteration   1: 11.147 ops/ms
Iteration   2: 11.160 ops/ms
Iteration   3: 11.020 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.109 ±(99.9%) 1.407 ops/ms [Average]
  (min, avg, max) = (11.020, 11.109, 11.160), stdev = 0.077
  CI (99.9%): [9.702, 12.516] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.956 ops/ms
# Warmup Iteration   2: 10.046 ops/ms
# Warmup Iteration   3: 10.693 ops/ms
Iteration   1: 10.629 ops/ms
Iteration   2: 10.393 ops/ms
Iteration   3: 10.501 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.508 ±(99.9%) 2.148 ops/ms [Average]
  (min, avg, max) = (10.393, 10.508, 10.629), stdev = 0.118
  CI (99.9%): [8.360, 12.655] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 7.347 ops/ms
# Warmup Iteration   2: 7.724 ops/ms
# Warmup Iteration   3: 7.938 ops/ms
Iteration   1: 8.262 ops/ms
Iteration   2: 8.007 ops/ms
Iteration   3: 8.104 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.124 ±(99.9%) 2.349 ops/ms [Average]
  (min, avg, max) = (8.007, 8.124, 8.262), stdev = 0.129
  CI (99.9%): [5.775, 10.473] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 3.951 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.113 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.051 ±(99.9%) 0.002 ms/op
Iteration   1: 3.086 ±(99.9%) 0.002 ms/op
Iteration   2: 3.122 ±(99.9%) 0.002 ms/op
Iteration   3: 3.138 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.115 ±(99.9%) 0.487 ms/op [Average]
  (min, avg, max) = (3.086, 3.115, 3.138), stdev = 0.027
  CI (99.9%): [2.628, 3.602] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.849 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.981 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.939 ±(99.9%) 0.003 ms/op
Iteration   1: 2.883 ±(99.9%) 0.003 ms/op
Iteration   2: 2.953 ±(99.9%) 0.002 ms/op
Iteration   3: 2.903 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.913 ±(99.9%) 0.658 ms/op [Average]
  (min, avg, max) = (2.883, 2.913, 2.953), stdev = 0.036
  CI (99.9%): [2.255, 3.571] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.768 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.066 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.047 ±(99.9%) 0.003 ms/op
Iteration   1: 3.093 ±(99.9%) 0.002 ms/op
Iteration   2: 3.015 ±(99.9%) 0.003 ms/op
Iteration   3: 3.004 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.037 ±(99.9%) 0.885 ms/op [Average]
  (min, avg, max) = (3.004, 3.037, 3.093), stdev = 0.048
  CI (99.9%): [2.153, 3.922] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.700 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.977 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.997 ±(99.9%) 0.011 ms/op
Iteration   1: 3.935 ±(99.9%) 0.036 ms/op
Iteration   2: 3.889 ±(99.9%) 0.038 ms/op
Iteration   3: 3.891 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.905 ±(99.9%) 0.478 ms/op [Average]
  (min, avg, max) = (3.889, 3.905, 3.935), stdev = 0.026
  CI (99.9%): [3.427, 4.383] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.996 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.092 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.013 ±(99.9%) 0.007 ms/op
Iteration   1: 3.103 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.429 ms/op
                 createUser·p0.50:   3.101 ms/op
                 createUser·p0.90:   3.748 ms/op
                 createUser·p0.95:   3.916 ms/op
                 createUser·p0.99:   4.243 ms/op
                 createUser·p0.999:  7.109 ms/op
                 createUser·p0.9999: 12.720 ms/op
                 createUser·p1.00:   13.206 ms/op

Iteration   2: 3.067 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.464 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.654 ms/op
                 createUser·p0.95:   3.858 ms/op
                 createUser·p0.99:   4.456 ms/op
                 createUser·p0.999:  8.831 ms/op
                 createUser·p0.9999: 20.564 ms/op
                 createUser·p1.00:   20.840 ms/op

Iteration   3: 3.048 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.662 ms/op
                 createUser·p0.50:   3.023 ms/op
                 createUser·p0.90:   3.637 ms/op
                 createUser·p0.95:   3.813 ms/op
                 createUser·p0.99:   4.364 ms/op
                 createUser·p0.999:  10.216 ms/op
                 createUser·p0.9999: 15.131 ms/op
                 createUser·p1.00:   15.516 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 312461
  mean =      3.072 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27991 
    [ 2.500,  5.000) = 283012 
    [ 5.000,  7.500) = 931 
    [ 7.500, 10.000) = 294 
    [10.000, 12.500) = 89 
    [12.500, 15.000) = 99 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.429 ms/op
     p(50.0000) =      3.052 ms/op
     p(90.0000) =      3.686 ms/op
     p(95.0000) =      3.871 ms/op
     p(99.0000) =      4.342 ms/op
     p(99.9000) =      8.831 ms/op
     p(99.9900) =     20.054 ms/op
     p(99.9990) =     20.771 ms/op
     p(99.9999) =     20.840 ms/op
    p(100.0000) =     20.840 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.819 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.060 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.940 ±(99.9%) 0.006 ms/op
Iteration   1: 2.974 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.759 ms/op
                 existUser·p0.50:   2.949 ms/op
                 existUser·p0.90:   3.596 ms/op
                 existUser·p0.95:   3.809 ms/op
                 existUser·p0.99:   4.137 ms/op
                 existUser·p0.999:  6.808 ms/op
                 existUser·p0.9999: 18.547 ms/op
                 existUser·p1.00:   18.907 ms/op

Iteration   2: 2.889 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.496 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.465 ms/op
                 existUser·p0.95:   3.666 ms/op
                 existUser·p0.99:   4.125 ms/op
                 existUser·p0.999:  5.710 ms/op
                 existUser·p0.9999: 19.986 ms/op
                 existUser·p1.00:   20.382 ms/op

Iteration   3: 3.037 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.656 ms/op
                 existUser·p0.50:   3.019 ms/op
                 existUser·p0.90:   3.650 ms/op
                 existUser·p0.95:   3.793 ms/op
                 existUser·p0.99:   4.202 ms/op
                 existUser·p0.999:  9.251 ms/op
                 existUser·p0.9999: 21.380 ms/op
                 existUser·p1.00:   21.692 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 323573
  mean =      2.965 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 46358 
    [ 2.500,  5.000) = 276298 
    [ 5.000,  7.500) = 635 
    [ 7.500, 10.000) = 107 
    [10.000, 12.500) = 29 
    [12.500, 15.000) = 49 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.496 ms/op
     p(50.0000) =      2.949 ms/op
     p(90.0000) =      3.584 ms/op
     p(95.0000) =      3.772 ms/op
     p(99.0000) =      4.162 ms/op
     p(99.9000) =      7.081 ms/op
     p(99.9900) =     20.075 ms/op
     p(99.9990) =     21.619 ms/op
     p(99.9999) =     21.692 ms/op
    p(100.0000) =     21.692 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.108 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.068 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.086 ±(99.9%) 0.006 ms/op
Iteration   1: 3.033 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.817 ms/op
                 getUser·p0.50:   3.023 ms/op
                 getUser·p0.90:   3.551 ms/op
                 getUser·p0.95:   3.727 ms/op
                 getUser·p0.99:   4.186 ms/op
                 getUser·p0.999:  9.445 ms/op
                 getUser·p0.9999: 14.016 ms/op
                 getUser·p1.00:   14.205 ms/op

Iteration   2: 2.966 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.490 ms/op
                 getUser·p0.50:   2.978 ms/op
                 getUser·p0.90:   3.531 ms/op
                 getUser·p0.95:   3.731 ms/op
                 getUser·p0.99:   4.276 ms/op
                 getUser·p0.999:  7.620 ms/op
                 getUser·p0.9999: 13.609 ms/op
                 getUser·p1.00:   13.795 ms/op

Iteration   3: 3.056 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.652 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.658 ms/op
                 getUser·p0.95:   3.842 ms/op
                 getUser·p0.99:   4.157 ms/op
                 getUser·p0.999:  6.531 ms/op
                 getUser·p0.9999: 25.461 ms/op
                 getUser·p1.00:   25.887 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 318153
  mean =      3.018 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29392 
    [ 2.500,  5.000) = 287779 
    [ 5.000,  7.500) = 621 
    [ 7.500, 10.000) = 143 
    [10.000, 12.500) = 83 
    [12.500, 15.000) = 79 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.490 ms/op
     p(50.0000) =      3.006 ms/op
     p(90.0000) =      3.580 ms/op
     p(95.0000) =      3.772 ms/op
     p(99.0000) =      4.194 ms/op
     p(99.9000) =      7.798 ms/op
     p(99.9900) =     24.588 ms/op
     p(99.9990) =     25.750 ms/op
     p(99.9999) =     25.887 ms/op
    p(100.0000) =     25.887 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.688 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.063 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.012 ±(99.9%) 0.012 ms/op
Iteration   1: 3.995 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.952 ms/op
                 listUser·p0.50:   3.838 ms/op
                 listUser·p0.90:   5.104 ms/op
                 listUser·p0.95:   5.646 ms/op
                 listUser·p0.99:   6.963 ms/op
                 listUser·p0.999:  15.663 ms/op
                 listUser·p0.9999: 21.199 ms/op
                 listUser·p1.00:   22.020 ms/op

Iteration   2: 3.932 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.346 ms/op
                 listUser·p0.50:   3.756 ms/op
                 listUser·p0.90:   5.169 ms/op
                 listUser·p0.95:   5.571 ms/op
                 listUser·p0.99:   6.889 ms/op
                 listUser·p0.999:  14.156 ms/op
                 listUser·p0.9999: 16.583 ms/op
                 listUser·p1.00:   18.579 ms/op

Iteration   3: 3.994 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.194 ms/op
                 listUser·p0.50:   3.822 ms/op
                 listUser·p0.90:   5.177 ms/op
                 listUser·p0.95:   5.636 ms/op
                 listUser·p0.99:   6.603 ms/op
                 listUser·p0.999:  14.330 ms/op
                 listUser·p0.9999: 20.873 ms/op
                 listUser·p1.00:   22.708 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 241466
  mean =      3.973 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5070 
    [ 2.500,  5.000) = 206847 
    [ 5.000,  7.500) = 28437 
    [ 7.500, 10.000) = 726 
    [10.000, 12.500) = 44 
    [12.500, 15.000) = 131 
    [15.000, 17.500) = 112 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.346 ms/op
     p(50.0000) =      3.809 ms/op
     p(90.0000) =      5.153 ms/op
     p(95.0000) =      5.612 ms/op
     p(99.0000) =      6.808 ms/op
     p(99.9000) =     14.509 ms/op
     p(99.9900) =     20.742 ms/op
     p(99.9990) =     22.602 ms/op
     p(99.9999) =     22.708 ms/op
    p(100.0000) =     22.708 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.195 ± 5.092  ops/ms
ClientGrpc.existUser                       thrpt       3  11.109 ± 1.407  ops/ms
ClientGrpc.getUser                         thrpt       3  10.508 ± 2.148  ops/ms
ClientGrpc.listUser                        thrpt       3   8.124 ± 2.349  ops/ms
ClientGrpc.createUser                       avgt       3   3.115 ± 0.487   ms/op
ClientGrpc.existUser                        avgt       3   2.913 ± 0.658   ms/op
ClientGrpc.getUser                          avgt       3   3.037 ± 0.885   ms/op
ClientGrpc.listUser                         avgt       3   3.905 ± 0.478   ms/op
ClientGrpc.createUser                     sample  312461   3.072 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.429           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.052           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.686           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.871           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.342           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.831           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.054           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.840           ms/op
ClientGrpc.existUser                      sample  323573   2.965 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.496           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.949           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.584           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.772           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.162           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.081           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.075           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.692           ms/op
ClientGrpc.getUser                        sample  318153   3.018 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.490           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.006           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.580           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.772           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.194           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.798           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          24.588           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.887           ms/op
ClientGrpc.listUser                       sample  241466   3.973 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.346           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.809           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.153           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.612           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.808           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.509           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.742           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.708           ms/op
