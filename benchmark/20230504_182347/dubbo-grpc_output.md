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
# Warmup Iteration   1: 3.990 ops/ms
# Warmup Iteration   2: 8.867 ops/ms
# Warmup Iteration   3: 9.800 ops/ms
Iteration   1: 10.259 ops/ms
Iteration   2: 10.450 ops/ms
Iteration   3: 10.426 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.378 ±(99.9%) 1.905 ops/ms [Average]
  (min, avg, max) = (10.259, 10.378, 10.450), stdev = 0.104
  CI (99.9%): [8.473, 12.283] (assumes normal distribution)


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
# Warmup Iteration   1: 6.924 ops/ms
# Warmup Iteration   2: 10.538 ops/ms
# Warmup Iteration   3: 11.053 ops/ms
Iteration   1: 10.834 ops/ms
Iteration   2: 10.967 ops/ms
Iteration   3: 11.052 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.951 ±(99.9%) 2.003 ops/ms [Average]
  (min, avg, max) = (10.834, 10.951, 11.052), stdev = 0.110
  CI (99.9%): [8.948, 12.954] (assumes normal distribution)


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
# Warmup Iteration   1: 6.679 ops/ms
# Warmup Iteration   2: 9.992 ops/ms
# Warmup Iteration   3: 10.383 ops/ms
Iteration   1: 10.801 ops/ms
Iteration   2: 10.402 ops/ms
Iteration   3: 10.543 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.582 ±(99.9%) 3.684 ops/ms [Average]
  (min, avg, max) = (10.402, 10.582, 10.801), stdev = 0.202
  CI (99.9%): [6.898, 14.266] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.465 ops/ms
# Warmup Iteration   2: 7.343 ops/ms
# Warmup Iteration   3: 8.009 ops/ms
Iteration   1: 8.338 ops/ms
Iteration   2: 7.988 ops/ms
Iteration   3: 8.174 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.166 ±(99.9%) 3.200 ops/ms [Average]
  (min, avg, max) = (7.988, 8.166, 8.338), stdev = 0.175
  CI (99.9%): [4.966, 11.366] (assumes normal distribution)


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
# Warmup Iteration   1: 4.449 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.178 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.063 ±(99.9%) 0.005 ms/op
Iteration   1: 3.060 ±(99.9%) 0.009 ms/op
Iteration   2: 3.083 ±(99.9%) 0.001 ms/op
Iteration   3: 3.035 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.059 ±(99.9%) 0.437 ms/op [Average]
  (min, avg, max) = (3.035, 3.059, 3.083), stdev = 0.024
  CI (99.9%): [2.622, 3.496] (assumes normal distribution)


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
# Warmup Iteration   1: 4.039 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.015 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.950 ±(99.9%) 0.002 ms/op
Iteration   1: 2.923 ±(99.9%) 0.002 ms/op
Iteration   2: 2.930 ±(99.9%) 0.002 ms/op
Iteration   3: 2.947 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.933 ±(99.9%) 0.231 ms/op [Average]
  (min, avg, max) = (2.923, 2.933, 2.947), stdev = 0.013
  CI (99.9%): [2.703, 3.164] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.432 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.178 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.091 ±(99.9%) 0.004 ms/op
Iteration   1: 3.050 ±(99.9%) 0.002 ms/op
Iteration   2: 3.091 ±(99.9%) 0.003 ms/op
Iteration   3: 3.001 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.048 ±(99.9%) 0.820 ms/op [Average]
  (min, avg, max) = (3.001, 3.048, 3.091), stdev = 0.045
  CI (99.9%): [2.227, 3.868] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.505 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 4.141 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 3.989 ±(99.9%) 0.009 ms/op
Iteration   1: 3.976 ±(99.9%) 0.014 ms/op
Iteration   2: 3.933 ±(99.9%) 0.009 ms/op
Iteration   3: 3.856 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.922 ±(99.9%) 1.111 ms/op [Average]
  (min, avg, max) = (3.856, 3.922, 3.976), stdev = 0.061
  CI (99.9%): [2.811, 5.033] (assumes normal distribution)


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
# Warmup Iteration   1: 4.363 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.225 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.063 ±(99.9%) 0.007 ms/op
Iteration   1: 3.060 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.934 ms/op
                 createUser·p0.50:   3.027 ms/op
                 createUser·p0.90:   3.482 ms/op
                 createUser·p0.95:   3.727 ms/op
                 createUser·p0.99:   4.393 ms/op
                 createUser·p0.999:  6.865 ms/op
                 createUser·p0.9999: 23.315 ms/op
                 createUser·p1.00:   23.658 ms/op

Iteration   2: 3.053 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.874 ms/op
                 createUser·p0.50:   3.031 ms/op
                 createUser·p0.90:   3.531 ms/op
                 createUser·p0.95:   3.768 ms/op
                 createUser·p0.99:   4.399 ms/op
                 createUser·p0.999:  8.749 ms/op
                 createUser·p0.9999: 15.066 ms/op
                 createUser·p1.00:   15.286 ms/op

Iteration   3: 3.060 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.902 ms/op
                 createUser·p0.50:   3.027 ms/op
                 createUser·p0.90:   3.564 ms/op
                 createUser·p0.95:   3.826 ms/op
                 createUser·p0.99:   4.473 ms/op
                 createUser·p0.999:  13.255 ms/op
                 createUser·p0.9999: 17.859 ms/op
                 createUser·p1.00:   18.285 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 313905
  mean =      3.058 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18381 
    [ 2.500,  5.000) = 294053 
    [ 5.000,  7.500) = 1086 
    [ 7.500, 10.000) = 125 
    [10.000, 12.500) = 39 
    [12.500, 15.000) = 119 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.874 ms/op
     p(50.0000) =      3.027 ms/op
     p(90.0000) =      3.527 ms/op
     p(95.0000) =      3.772 ms/op
     p(99.0000) =      4.424 ms/op
     p(99.9000) =      8.882 ms/op
     p(99.9900) =     22.577 ms/op
     p(99.9990) =     23.527 ms/op
     p(99.9999) =     23.658 ms/op
    p(100.0000) =     23.658 ms/op


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
# Warmup Iteration   1: 3.753 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.019 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.923 ±(99.9%) 0.005 ms/op
Iteration   1: 2.907 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.621 ms/op
                 existUser·p0.50:   2.888 ms/op
                 existUser·p0.90:   3.293 ms/op
                 existUser·p0.95:   3.486 ms/op
                 existUser·p0.99:   4.239 ms/op
                 existUser·p0.999:  6.958 ms/op
                 existUser·p0.9999: 14.385 ms/op
                 existUser·p1.00:   14.795 ms/op

Iteration   2: 2.863 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.763 ms/op
                 existUser·p0.50:   2.859 ms/op
                 existUser·p0.90:   3.273 ms/op
                 existUser·p0.95:   3.527 ms/op
                 existUser·p0.99:   4.211 ms/op
                 existUser·p0.999:  6.832 ms/op
                 existUser·p0.9999: 12.842 ms/op
                 existUser·p1.00:   13.435 ms/op

Iteration   3: 2.919 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.660 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.387 ms/op
                 existUser·p0.95:   3.555 ms/op
                 existUser·p0.99:   4.301 ms/op
                 existUser·p0.999:  6.586 ms/op
                 existUser·p0.9999: 24.224 ms/op
                 existUser·p1.00:   25.068 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 331582
  mean =      2.896 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 37866 
    [ 2.500,  5.000) = 292489 
    [ 5.000,  7.500) = 1016 
    [ 7.500, 10.000) = 51 
    [10.000, 12.500) = 37 
    [12.500, 15.000) = 65 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.621 ms/op
     p(50.0000) =      2.879 ms/op
     p(90.0000) =      3.326 ms/op
     p(95.0000) =      3.531 ms/op
     p(99.0000) =      4.252 ms/op
     p(99.9000) =      6.824 ms/op
     p(99.9900) =     15.964 ms/op
     p(99.9990) =     24.992 ms/op
     p(99.9999) =     25.068 ms/op
    p(100.0000) =     25.068 ms/op


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
# Warmup Iteration   1: 4.035 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.091 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.019 ±(99.9%) 0.006 ms/op
Iteration   1: 3.029 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.612 ms/op
                 getUser·p0.50:   2.994 ms/op
                 getUser·p0.90:   3.555 ms/op
                 getUser·p0.95:   3.801 ms/op
                 getUser·p0.99:   4.456 ms/op
                 getUser·p0.999:  7.921 ms/op
                 getUser·p0.9999: 12.441 ms/op
                 getUser·p1.00:   12.976 ms/op

Iteration   2: 3.028 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.773 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.633 ms/op
                 getUser·p0.95:   3.813 ms/op
                 getUser·p0.99:   4.325 ms/op
                 getUser·p0.999:  10.682 ms/op
                 getUser·p0.9999: 13.688 ms/op
                 getUser·p1.00:   13.926 ms/op

Iteration   3: 2.957 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.859 ms/op
                 getUser·p0.50:   2.953 ms/op
                 getUser·p0.90:   3.305 ms/op
                 getUser·p0.95:   3.441 ms/op
                 getUser·p0.99:   4.628 ms/op
                 getUser·p0.999:  6.608 ms/op
                 getUser·p0.9999: 25.211 ms/op
                 getUser·p1.00:   25.657 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 319365
  mean =      3.004 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24335 
    [ 2.500,  5.000) = 293797 
    [ 5.000,  7.500) = 895 
    [ 7.500, 10.000) = 54 
    [10.000, 12.500) = 177 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.612 ms/op
     p(50.0000) =      2.982 ms/op
     p(90.0000) =      3.506 ms/op
     p(95.0000) =      3.748 ms/op
     p(99.0000) =      4.440 ms/op
     p(99.9000) =      7.945 ms/op
     p(99.9900) =     24.056 ms/op
     p(99.9990) =     25.579 ms/op
     p(99.9999) =     25.657 ms/op
    p(100.0000) =     25.657 ms/op


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
# Warmup Iteration   1: 5.279 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.226 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.963 ±(99.9%) 0.011 ms/op
Iteration   1: 3.806 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.135 ms/op
                 listUser·p0.50:   3.666 ms/op
                 listUser·p0.90:   4.760 ms/op
                 listUser·p0.95:   5.431 ms/op
                 listUser·p0.99:   6.906 ms/op
                 listUser·p0.999:  13.217 ms/op
                 listUser·p0.9999: 17.162 ms/op
                 listUser·p1.00:   18.055 ms/op

Iteration   2: 3.927 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.317 ms/op
                 listUser·p0.50:   3.789 ms/op
                 listUser·p0.90:   4.628 ms/op
                 listUser·p0.95:   5.464 ms/op
                 listUser·p0.99:   6.676 ms/op
                 listUser·p0.999:  16.296 ms/op
                 listUser·p0.9999: 25.690 ms/op
                 listUser·p1.00:   27.263 ms/op

Iteration   3: 3.973 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.481 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   5.030 ms/op
                 listUser·p0.95:   5.792 ms/op
                 listUser·p0.99:   7.029 ms/op
                 listUser·p0.999:  16.588 ms/op
                 listUser·p0.9999: 23.559 ms/op
                 listUser·p1.00:   23.724 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 246137
  mean =      3.901 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3481 
    [ 2.500,  5.000) = 222212 
    [ 5.000,  7.500) = 19184 
    [ 7.500, 10.000) = 792 
    [10.000, 12.500) = 95 
    [12.500, 15.000) = 81 
    [15.000, 17.500) = 181 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.481 ms/op
     p(50.0000) =      3.760 ms/op
     p(90.0000) =      4.809 ms/op
     p(95.0000) =      5.595 ms/op
     p(99.0000) =      6.865 ms/op
     p(99.9000) =     15.827 ms/op
     p(99.9900) =     25.375 ms/op
     p(99.9990) =     26.459 ms/op
     p(99.9999) =     27.263 ms/op
    p(100.0000) =     27.263 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.378 ± 1.905  ops/ms
ClientGrpc.existUser                       thrpt       3  10.951 ± 2.003  ops/ms
ClientGrpc.getUser                         thrpt       3  10.582 ± 3.684  ops/ms
ClientGrpc.listUser                        thrpt       3   8.166 ± 3.200  ops/ms
ClientGrpc.createUser                       avgt       3   3.059 ± 0.437   ms/op
ClientGrpc.existUser                        avgt       3   2.933 ± 0.231   ms/op
ClientGrpc.getUser                          avgt       3   3.048 ± 0.820   ms/op
ClientGrpc.listUser                         avgt       3   3.922 ± 1.111   ms/op
ClientGrpc.createUser                     sample  313905   3.058 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.874           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.027           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.527           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.772           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.424           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.882           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.577           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.658           ms/op
ClientGrpc.existUser                      sample  331582   2.896 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.621           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.879           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.326           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.531           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.252           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.824           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.964           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.068           ms/op
ClientGrpc.getUser                        sample  319365   3.004 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.612           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.982           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.506           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.748           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.440           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.945           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          24.056           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.657           ms/op
ClientGrpc.listUser                       sample  246137   3.901 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.481           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.760           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.809           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.595           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.865           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.827           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.375           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.263           ms/op
