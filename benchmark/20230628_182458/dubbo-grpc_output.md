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
# Warmup Iteration   1: 4.053 ops/ms
# Warmup Iteration   2: 9.055 ops/ms
# Warmup Iteration   3: 10.119 ops/ms
Iteration   1: 10.626 ops/ms
Iteration   2: 10.448 ops/ms
Iteration   3: 10.463 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.512 ±(99.9%) 1.808 ops/ms [Average]
  (min, avg, max) = (10.448, 10.512, 10.626), stdev = 0.099
  CI (99.9%): [8.705, 12.320] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.324 ops/ms
# Warmup Iteration   2: 10.618 ops/ms
# Warmup Iteration   3: 11.245 ops/ms
Iteration   1: 10.821 ops/ms
Iteration   2: 10.944 ops/ms
Iteration   3: 11.034 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.933 ±(99.9%) 1.956 ops/ms [Average]
  (min, avg, max) = (10.821, 10.933, 11.034), stdev = 0.107
  CI (99.9%): [8.977, 12.890] (assumes normal distribution)


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
# Warmup Iteration   1: 7.870 ops/ms
# Warmup Iteration   2: 10.130 ops/ms
# Warmup Iteration   3: 10.411 ops/ms
Iteration   1: 10.491 ops/ms
Iteration   2: 10.643 ops/ms
Iteration   3: 10.464 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.533 ±(99.9%) 1.757 ops/ms [Average]
  (min, avg, max) = (10.464, 10.533, 10.643), stdev = 0.096
  CI (99.9%): [8.776, 12.289] (assumes normal distribution)


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
# Warmup Iteration   1: 6.299 ops/ms
# Warmup Iteration   2: 7.742 ops/ms
# Warmup Iteration   3: 8.218 ops/ms
Iteration   1: 8.167 ops/ms
Iteration   2: 8.243 ops/ms
Iteration   3: 8.158 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.190 ±(99.9%) 0.852 ops/ms [Average]
  (min, avg, max) = (8.158, 8.190, 8.243), stdev = 0.047
  CI (99.9%): [7.338, 9.041] (assumes normal distribution)


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
# Warmup Iteration   1: 4.105 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.137 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.053 ±(99.9%) 0.003 ms/op
Iteration   1: 3.022 ±(99.9%) 0.002 ms/op
Iteration   2: 2.892 ±(99.9%) 0.003 ms/op
Iteration   3: 2.994 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.969 ±(99.9%) 1.250 ms/op [Average]
  (min, avg, max) = (2.892, 2.969, 3.022), stdev = 0.069
  CI (99.9%): [1.720, 4.219] (assumes normal distribution)


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
# Warmup Iteration   1: 3.978 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.987 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.868 ±(99.9%) 0.003 ms/op
Iteration   1: 2.930 ±(99.9%) 0.002 ms/op
Iteration   2: 2.865 ±(99.9%) 0.002 ms/op
Iteration   3: 2.866 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.887 ±(99.9%) 0.675 ms/op [Average]
  (min, avg, max) = (2.865, 2.887, 2.930), stdev = 0.037
  CI (99.9%): [2.212, 3.562] (assumes normal distribution)


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
# Warmup Iteration   1: 4.207 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.110 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.009 ±(99.9%) 0.004 ms/op
Iteration   1: 3.012 ±(99.9%) 0.004 ms/op
Iteration   2: 2.994 ±(99.9%) 0.003 ms/op
Iteration   3: 3.014 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.007 ±(99.9%) 0.206 ms/op [Average]
  (min, avg, max) = (2.994, 3.007, 3.014), stdev = 0.011
  CI (99.9%): [2.801, 3.212] (assumes normal distribution)


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
# Warmup Iteration   1: 5.550 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.199 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.127 ±(99.9%) 0.020 ms/op
Iteration   1: 4.166 ±(99.9%) 0.020 ms/op
Iteration   2: 4.017 ±(99.9%) 0.026 ms/op
Iteration   3: 4.037 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.073 ±(99.9%) 1.471 ms/op [Average]
  (min, avg, max) = (4.017, 4.073, 4.166), stdev = 0.081
  CI (99.9%): [2.602, 5.544] (assumes normal distribution)


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
# Warmup Iteration   1: 4.433 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.812 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.567 ±(99.9%) 0.012 ms/op
Iteration   1: 3.518 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.831 ms/op
                 createUser·p0.50:   3.256 ms/op
                 createUser·p0.90:   4.628 ms/op
                 createUser·p0.95:   5.369 ms/op
                 createUser·p0.99:   7.496 ms/op
                 createUser·p0.999:  12.796 ms/op
                 createUser·p0.9999: 20.972 ms/op
                 createUser·p1.00:   21.299 ms/op

Iteration   2: 3.176 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.722 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.867 ms/op
                 createUser·p0.95:   4.415 ms/op
                 createUser·p0.99:   6.283 ms/op
                 createUser·p0.999:  11.968 ms/op
                 createUser·p0.9999: 32.274 ms/op
                 createUser·p1.00:   33.620 ms/op

Iteration   3: 3.375 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.761 ms/op
                 createUser·p0.50:   3.236 ms/op
                 createUser·p0.90:   4.211 ms/op
                 createUser·p0.95:   4.760 ms/op
                 createUser·p0.99:   6.390 ms/op
                 createUser·p0.999:  9.047 ms/op
                 createUser·p0.9999: 28.003 ms/op
                 createUser·p1.00:   31.719 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 286486
  mean =      3.350 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15637 
    [ 2.500,  5.000) = 258347 
    [ 5.000,  7.500) = 10851 
    [ 7.500, 10.000) = 1270 
    [10.000, 12.500) = 123 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 79 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 14 
    [27.500, 30.000) = 15 
    [30.000, 32.500) = 30 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.722 ms/op
     p(50.0000) =      3.170 ms/op
     p(90.0000) =      4.260 ms/op
     p(95.0000) =      4.874 ms/op
     p(99.0000) =      6.832 ms/op
     p(99.9000) =     11.494 ms/op
     p(99.9900) =     31.818 ms/op
     p(99.9990) =     33.554 ms/op
     p(99.9999) =     33.620 ms/op
    p(100.0000) =     33.620 ms/op


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
# Warmup Iteration   1: 5.046 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 3.576 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.403 ±(99.9%) 0.009 ms/op
Iteration   1: 3.322 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.806 ms/op
                 existUser·p0.50:   3.199 ms/op
                 existUser·p0.90:   4.104 ms/op
                 existUser·p0.95:   4.661 ms/op
                 existUser·p0.99:   6.218 ms/op
                 existUser·p0.999:  11.246 ms/op
                 existUser·p0.9999: 18.547 ms/op
                 existUser·p1.00:   19.202 ms/op

Iteration   2: 3.131 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.568 ms/op
                 existUser·p0.50:   3.052 ms/op
                 existUser·p0.90:   3.674 ms/op
                 existUser·p0.95:   3.912 ms/op
                 existUser·p0.99:   5.489 ms/op
                 existUser·p0.999:  8.329 ms/op
                 existUser·p0.9999: 15.833 ms/op
                 existUser·p1.00:   16.335 ms/op

Iteration   3: 3.476 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.990 ms/op
                 existUser·p0.50:   3.334 ms/op
                 existUser·p0.90:   4.260 ms/op
                 existUser·p0.95:   4.907 ms/op
                 existUser·p0.99:   6.366 ms/op
                 existUser·p0.999:  9.945 ms/op
                 existUser·p0.9999: 18.186 ms/op
                 existUser·p1.00:   18.645 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 290509
  mean =      3.304 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 500 
    [ 1.250,  2.500) = 11607 
    [ 2.500,  3.750) = 229846 
    [ 3.750,  5.000) = 39333 
    [ 5.000,  6.250) = 6625 
    [ 6.250,  7.500) = 2005 
    [ 7.500,  8.750) = 244 
    [ 8.750, 10.000) = 86 
    [10.000, 11.250) = 71 
    [11.250, 12.500) = 11 
    [12.500, 13.750) = 30 
    [13.750, 15.000) = 33 
    [15.000, 16.250) = 47 
    [16.250, 17.500) = 22 
    [17.500, 18.750) = 43 

  Percentiles, ms/op:
      p(0.0000) =      0.568 ms/op
     p(50.0000) =      3.183 ms/op
     p(90.0000) =      4.010 ms/op
     p(95.0000) =      4.514 ms/op
     p(99.0000) =      6.144 ms/op
     p(99.9000) =      9.650 ms/op
     p(99.9900) =     18.121 ms/op
     p(99.9990) =     19.044 ms/op
     p(99.9999) =     19.202 ms/op
    p(100.0000) =     19.202 ms/op


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
# Warmup Iteration   1: 5.370 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 3.796 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.707 ±(99.9%) 0.013 ms/op
Iteration   1: 3.784 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.846 ms/op
                 getUser·p0.50:   3.572 ms/op
                 getUser·p0.90:   4.973 ms/op
                 getUser·p0.95:   5.710 ms/op
                 getUser·p0.99:   7.111 ms/op
                 getUser·p0.999:  13.477 ms/op
                 getUser·p0.9999: 20.443 ms/op
                 getUser·p1.00:   22.970 ms/op

Iteration   2: 3.548 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.965 ms/op
                 getUser·p0.50:   3.351 ms/op
                 getUser·p0.90:   4.604 ms/op
                 getUser·p0.95:   5.399 ms/op
                 getUser·p0.99:   6.988 ms/op
                 getUser·p0.999:  10.420 ms/op
                 getUser·p0.9999: 43.842 ms/op
                 getUser·p1.00:   44.499 ms/op

Iteration   3: 3.618 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.711 ms/op
                 getUser·p0.50:   3.412 ms/op
                 getUser·p0.90:   4.678 ms/op
                 getUser·p0.95:   5.374 ms/op
                 getUser·p0.99:   6.898 ms/op
                 getUser·p0.999:  11.725 ms/op
                 getUser·p0.9999: 34.210 ms/op
                 getUser·p1.00:   34.537 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 263133
  mean =      3.647 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 242134 
    [ 5.000, 10.000) = 20655 
    [10.000, 15.000) = 158 
    [15.000, 20.000) = 82 
    [20.000, 25.000) = 40 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 32 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.711 ms/op
     p(50.0000) =      3.453 ms/op
     p(90.0000) =      4.760 ms/op
     p(95.0000) =      5.505 ms/op
     p(99.0000) =      7.004 ms/op
     p(99.9000) =     11.338 ms/op
     p(99.9900) =     41.378 ms/op
     p(99.9990) =     44.302 ms/op
     p(99.9999) =     44.499 ms/op
    p(100.0000) =     44.499 ms/op


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
# Warmup Iteration   1: 6.773 ±(99.9%) 0.102 ms/op
# Warmup Iteration   2: 4.307 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.153 ±(99.9%) 0.013 ms/op
Iteration   1: 4.277 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.741 ms/op
                 listUser·p0.50:   3.953 ms/op
                 listUser·p0.90:   5.612 ms/op
                 listUser·p0.95:   6.693 ms/op
                 listUser·p0.99:   8.618 ms/op
                 listUser·p0.999:  18.894 ms/op
                 listUser·p0.9999: 30.215 ms/op
                 listUser·p1.00:   30.933 ms/op

Iteration   2: 4.441 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.104 ms/op
                 listUser·p0.50:   4.133 ms/op
                 listUser·p0.90:   5.988 ms/op
                 listUser·p0.95:   6.636 ms/op
                 listUser·p0.99:   8.339 ms/op
                 listUser·p0.999:  18.474 ms/op
                 listUser·p0.9999: 27.177 ms/op
                 listUser·p1.00:   27.656 ms/op

Iteration   3: 4.459 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.542 ms/op
                 listUser·p0.50:   4.186 ms/op
                 listUser·p0.90:   5.857 ms/op
                 listUser·p0.95:   6.463 ms/op
                 listUser·p0.99:   8.028 ms/op
                 listUser·p0.999:  18.774 ms/op
                 listUser·p0.9999: 23.863 ms/op
                 listUser·p1.00:   25.068 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 218672
  mean =      4.391 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1110 
    [ 2.500,  5.000) = 176108 
    [ 5.000,  7.500) = 36578 
    [ 7.500, 10.000) = 4037 
    [10.000, 12.500) = 407 
    [12.500, 15.000) = 83 
    [15.000, 17.500) = 98 
    [17.500, 20.000) = 85 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 45 
    [27.500, 30.000) = 44 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.104 ms/op
     p(50.0000) =      4.080 ms/op
     p(90.0000) =      5.841 ms/op
     p(95.0000) =      6.595 ms/op
     p(99.0000) =      8.356 ms/op
     p(99.9000) =     18.623 ms/op
     p(99.9900) =     28.353 ms/op
     p(99.9990) =     30.796 ms/op
     p(99.9999) =     30.933 ms/op
    p(100.0000) =     30.933 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.512 ± 1.808  ops/ms
ClientGrpc.existUser                       thrpt       3  10.933 ± 1.956  ops/ms
ClientGrpc.getUser                         thrpt       3  10.533 ± 1.757  ops/ms
ClientGrpc.listUser                        thrpt       3   8.190 ± 0.852  ops/ms
ClientGrpc.createUser                       avgt       3   2.969 ± 1.250   ms/op
ClientGrpc.existUser                        avgt       3   2.887 ± 0.675   ms/op
ClientGrpc.getUser                          avgt       3   3.007 ± 0.206   ms/op
ClientGrpc.listUser                         avgt       3   4.073 ± 1.471   ms/op
ClientGrpc.createUser                     sample  286486   3.350 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.722           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.170           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.260           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.874           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.832           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.494           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          31.818           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          33.620           ms/op
ClientGrpc.existUser                      sample  290509   3.304 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.568           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.183           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.010           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.514           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.144           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.650           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.121           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.202           ms/op
ClientGrpc.getUser                        sample  263133   3.647 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.711           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.453           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.760           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.505           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.004           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.338           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          41.378           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          44.499           ms/op
ClientGrpc.listUser                       sample  218672   4.391 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.104           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.080           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.841           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.595           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.356           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.623           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          28.353           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          30.933           ms/op
