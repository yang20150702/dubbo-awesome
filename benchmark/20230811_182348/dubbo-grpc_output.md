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
# Warmup Iteration   1: 3.335 ops/ms
# Warmup Iteration   2: 7.246 ops/ms
# Warmup Iteration   3: 7.542 ops/ms
Iteration   1: 8.280 ops/ms
Iteration   2: 8.828 ops/ms
Iteration   3: 8.934 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.681 ±(99.9%) 6.407 ops/ms [Average]
  (min, avg, max) = (8.280, 8.681, 8.934), stdev = 0.351
  CI (99.9%): [2.274, 15.088] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 5.295 ops/ms
# Warmup Iteration   2: 7.748 ops/ms
# Warmup Iteration   3: 8.064 ops/ms
Iteration   1: 7.959 ops/ms
Iteration   2: 7.627 ops/ms
Iteration   3: 8.037 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.874 ±(99.9%) 3.977 ops/ms [Average]
  (min, avg, max) = (7.627, 7.874, 8.037), stdev = 0.218
  CI (99.9%): [3.897, 11.851] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 4.713 ops/ms
# Warmup Iteration   2: 7.376 ops/ms
# Warmup Iteration   3: 7.693 ops/ms
Iteration   1: 7.980 ops/ms
Iteration   2: 8.108 ops/ms
Iteration   3: 8.013 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.034 ±(99.9%) 1.210 ops/ms [Average]
  (min, avg, max) = (7.980, 8.034, 8.108), stdev = 0.066
  CI (99.9%): [6.823, 9.244] (assumes normal distribution)


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
# Warmup Iteration   1: 3.658 ops/ms
# Warmup Iteration   2: 5.785 ops/ms
# Warmup Iteration   3: 6.052 ops/ms
Iteration   1: 6.191 ops/ms
Iteration   2: 6.175 ops/ms
Iteration   3: 6.103 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.156 ±(99.9%) 0.857 ops/ms [Average]
  (min, avg, max) = (6.103, 6.156, 6.191), stdev = 0.047
  CI (99.9%): [5.300, 7.013] (assumes normal distribution)


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
# Warmup Iteration   1: 6.095 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.260 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.139 ±(99.9%) 0.005 ms/op
Iteration   1: 4.097 ±(99.9%) 0.002 ms/op
Iteration   2: 4.159 ±(99.9%) 0.002 ms/op
Iteration   3: 4.002 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.086 ±(99.9%) 1.438 ms/op [Average]
  (min, avg, max) = (4.002, 4.086, 4.159), stdev = 0.079
  CI (99.9%): [2.648, 5.524] (assumes normal distribution)


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
# Warmup Iteration   1: 5.984 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 4.035 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 3.796 ±(99.9%) 0.004 ms/op
Iteration   1: 3.728 ±(99.9%) 0.002 ms/op
Iteration   2: 3.685 ±(99.9%) 0.003 ms/op
Iteration   3: 3.622 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.678 ±(99.9%) 0.973 ms/op [Average]
  (min, avg, max) = (3.622, 3.678, 3.728), stdev = 0.053
  CI (99.9%): [2.706, 4.651] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 6.063 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.320 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.980 ±(99.9%) 0.003 ms/op
Iteration   1: 4.042 ±(99.9%) 0.004 ms/op
Iteration   2: 3.986 ±(99.9%) 0.003 ms/op
Iteration   3: 4.068 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.032 ±(99.9%) 0.766 ms/op [Average]
  (min, avg, max) = (3.986, 4.032, 4.068), stdev = 0.042
  CI (99.9%): [3.265, 4.798] (assumes normal distribution)


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
# Warmup Iteration   1: 6.782 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 5.696 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 5.241 ±(99.9%) 0.018 ms/op
Iteration   1: 5.156 ±(99.9%) 0.025 ms/op
Iteration   2: 5.211 ±(99.9%) 0.016 ms/op
Iteration   3: 5.152 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.173 ±(99.9%) 0.601 ms/op [Average]
  (min, avg, max) = (5.152, 5.173, 5.211), stdev = 0.033
  CI (99.9%): [4.572, 5.774] (assumes normal distribution)


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
# Warmup Iteration   1: 5.846 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 4.389 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.004 ±(99.9%) 0.012 ms/op
Iteration   1: 3.946 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.538 ms/op
                 createUser·p0.50:   3.863 ms/op
                 createUser·p0.90:   4.792 ms/op
                 createUser·p0.95:   5.177 ms/op
                 createUser·p0.99:   6.513 ms/op
                 createUser·p0.999:  9.978 ms/op
                 createUser·p0.9999: 21.030 ms/op
                 createUser·p1.00:   21.496 ms/op

Iteration   2: 4.018 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.983 ms/op
                 createUser·p0.50:   3.891 ms/op
                 createUser·p0.90:   4.907 ms/op
                 createUser·p0.95:   5.292 ms/op
                 createUser·p0.99:   7.332 ms/op
                 createUser·p0.999:  14.139 ms/op
                 createUser·p0.9999: 21.760 ms/op
                 createUser·p1.00:   22.184 ms/op

Iteration   3: 3.830 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.961 ms/op
                 createUser·p0.50:   3.768 ms/op
                 createUser·p0.90:   4.702 ms/op
                 createUser·p0.95:   5.153 ms/op
                 createUser·p0.99:   6.490 ms/op
                 createUser·p0.999:  15.562 ms/op
                 createUser·p0.9999: 36.372 ms/op
                 createUser·p1.00:   37.028 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 244301
  mean =      3.930 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5961 
    [ 2.500,  5.000) = 220927 
    [ 5.000,  7.500) = 15703 
    [ 7.500, 10.000) = 1245 
    [10.000, 12.500) = 234 
    [12.500, 15.000) = 43 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 89 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 12 
    [27.500, 30.000) = 9 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 7 
    [35.000, 37.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.538 ms/op
     p(50.0000) =      3.838 ms/op
     p(90.0000) =      4.809 ms/op
     p(95.0000) =      5.210 ms/op
     p(99.0000) =      6.775 ms/op
     p(99.9000) =     12.185 ms/op
     p(99.9900) =     35.099 ms/op
     p(99.9990) =     36.868 ms/op
     p(99.9999) =     37.028 ms/op
    p(100.0000) =     37.028 ms/op


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
# Warmup Iteration   1: 5.324 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 3.876 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.725 ±(99.9%) 0.010 ms/op
Iteration   1: 3.731 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.613 ms/op
                 existUser·p0.50:   3.641 ms/op
                 existUser·p0.90:   4.489 ms/op
                 existUser·p0.95:   4.858 ms/op
                 existUser·p0.99:   6.275 ms/op
                 existUser·p0.999:  9.578 ms/op
                 existUser·p0.9999: 23.050 ms/op
                 existUser·p1.00:   23.265 ms/op

Iteration   2: 3.749 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.975 ms/op
                 existUser·p0.50:   3.650 ms/op
                 existUser·p0.90:   4.539 ms/op
                 existUser·p0.95:   4.923 ms/op
                 existUser·p0.99:   6.365 ms/op
                 existUser·p0.999:  16.215 ms/op
                 existUser·p0.9999: 20.004 ms/op
                 existUser·p1.00:   21.070 ms/op

Iteration   3: 3.684 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.802 ms/op
                 existUser·p0.50:   3.625 ms/op
                 existUser·p0.90:   4.473 ms/op
                 existUser·p0.95:   4.850 ms/op
                 existUser·p0.99:   6.242 ms/op
                 existUser·p0.999:  10.781 ms/op
                 existUser·p0.9999: 21.211 ms/op
                 existUser·p1.00:   21.594 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 257977
  mean =      3.721 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6870 
    [ 2.500,  5.000) = 240642 
    [ 5.000,  7.500) = 9170 
    [ 7.500, 10.000) = 936 
    [10.000, 12.500) = 185 
    [12.500, 15.000) = 14 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.613 ms/op
     p(50.0000) =      3.637 ms/op
     p(90.0000) =      4.506 ms/op
     p(95.0000) =      4.874 ms/op
     p(99.0000) =      6.291 ms/op
     p(99.9000) =     10.732 ms/op
     p(99.9900) =     22.427 ms/op
     p(99.9990) =     23.181 ms/op
     p(99.9999) =     23.265 ms/op
    p(100.0000) =     23.265 ms/op


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
# Warmup Iteration   1: 5.477 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 4.258 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.058 ±(99.9%) 0.011 ms/op
Iteration   1: 3.933 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.806 ms/op
                 getUser·p0.50:   3.850 ms/op
                 getUser·p0.90:   4.760 ms/op
                 getUser·p0.95:   5.136 ms/op
                 getUser·p0.99:   6.750 ms/op
                 getUser·p0.999:  12.552 ms/op
                 getUser·p0.9999: 20.054 ms/op
                 getUser·p1.00:   20.611 ms/op

Iteration   2: 3.962 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.096 ms/op
                 getUser·p0.50:   3.863 ms/op
                 getUser·p0.90:   4.874 ms/op
                 getUser·p0.95:   5.325 ms/op
                 getUser·p0.99:   6.898 ms/op
                 getUser·p0.999:  14.526 ms/op
                 getUser·p0.9999: 23.720 ms/op
                 getUser·p1.00:   24.052 ms/op

Iteration   3: 4.042 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.947 ms/op
                 getUser·p0.50:   3.940 ms/op
                 getUser·p0.90:   5.005 ms/op
                 getUser·p0.95:   5.349 ms/op
                 getUser·p0.99:   6.488 ms/op
                 getUser·p0.999:  10.153 ms/op
                 getUser·p0.9999: 25.300 ms/op
                 getUser·p1.00:   25.756 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 241153
  mean =      3.978 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5240 
    [ 2.500,  5.000) = 216123 
    [ 5.000,  7.500) = 18210 
    [ 7.500, 10.000) = 1118 
    [10.000, 12.500) = 236 
    [12.500, 15.000) = 52 
    [15.000, 17.500) = 46 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 46 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.806 ms/op
     p(50.0000) =      3.879 ms/op
     p(90.0000) =      4.891 ms/op
     p(95.0000) =      5.284 ms/op
     p(99.0000) =      6.750 ms/op
     p(99.9000) =     12.316 ms/op
     p(99.9900) =     24.400 ms/op
     p(99.9990) =     25.630 ms/op
     p(99.9999) =     25.756 ms/op
    p(100.0000) =     25.756 ms/op


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
# Warmup Iteration   1: 7.698 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 5.413 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 5.164 ±(99.9%) 0.018 ms/op
Iteration   1: 5.132 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.790 ms/op
                 listUser·p0.50:   4.915 ms/op
                 listUser·p0.90:   6.406 ms/op
                 listUser·p0.95:   7.201 ms/op
                 listUser·p0.99:   9.683 ms/op
                 listUser·p0.999:  15.444 ms/op
                 listUser·p0.9999: 24.084 ms/op
                 listUser·p1.00:   26.706 ms/op

Iteration   2: 4.995 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   0.468 ms/op
                 listUser·p0.50:   4.817 ms/op
                 listUser·p0.90:   6.185 ms/op
                 listUser·p0.95:   7.127 ms/op
                 listUser·p0.99:   9.421 ms/op
                 listUser·p0.999:  16.449 ms/op
                 listUser·p0.9999: 18.966 ms/op
                 listUser·p1.00:   21.201 ms/op

Iteration   3: 5.198 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.110 ms/op
                 listUser·p0.50:   4.923 ms/op
                 listUser·p0.90:   6.717 ms/op
                 listUser·p0.95:   7.643 ms/op
                 listUser·p0.99:   9.781 ms/op
                 listUser·p0.999:  19.179 ms/op
                 listUser·p0.9999: 26.860 ms/op
                 listUser·p1.00:   27.329 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 187950
  mean =      5.107 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 143 
    [ 2.500,  5.000) = 105296 
    [ 5.000,  7.500) = 74104 
    [ 7.500, 10.000) = 6955 
    [10.000, 12.500) = 929 
    [12.500, 15.000) = 241 
    [15.000, 17.500) = 134 
    [17.500, 20.000) = 58 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.468 ms/op
     p(50.0000) =      4.882 ms/op
     p(90.0000) =      6.447 ms/op
     p(95.0000) =      7.340 ms/op
     p(99.0000) =      9.634 ms/op
     p(99.9000) =     16.728 ms/op
     p(99.9900) =     25.018 ms/op
     p(99.9990) =     27.271 ms/op
     p(99.9999) =     27.329 ms/op
    p(100.0000) =     27.329 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.681 ± 6.407  ops/ms
ClientGrpc.existUser                       thrpt       3   7.874 ± 3.977  ops/ms
ClientGrpc.getUser                         thrpt       3   8.034 ± 1.210  ops/ms
ClientGrpc.listUser                        thrpt       3   6.156 ± 0.857  ops/ms
ClientGrpc.createUser                       avgt       3   4.086 ± 1.438   ms/op
ClientGrpc.existUser                        avgt       3   3.678 ± 0.973   ms/op
ClientGrpc.getUser                          avgt       3   4.032 ± 0.766   ms/op
ClientGrpc.listUser                         avgt       3   5.173 ± 0.601   ms/op
ClientGrpc.createUser                     sample  244301   3.930 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.538           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.838           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.809           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.210           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.775           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.185           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          35.099           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          37.028           ms/op
ClientGrpc.existUser                      sample  257977   3.721 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.613           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.637           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.506           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.874           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.291           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.732           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          22.427           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.265           ms/op
ClientGrpc.getUser                        sample  241153   3.978 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.806           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.879           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.891           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.284           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.750           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.316           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          24.400           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.756           ms/op
ClientGrpc.listUser                       sample  187950   5.107 ± 0.010   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.468           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.882           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.447           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.340           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.634           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.728           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.018           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.329           ms/op
