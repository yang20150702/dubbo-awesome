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
# Warmup Iteration   1: 3.647 ops/ms
# Warmup Iteration   2: 7.556 ops/ms
# Warmup Iteration   3: 8.868 ops/ms
Iteration   1: 9.343 ops/ms
Iteration   2: 9.618 ops/ms
Iteration   3: 9.257 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.406 ±(99.9%) 3.433 ops/ms [Average]
  (min, avg, max) = (9.257, 9.406, 9.618), stdev = 0.188
  CI (99.9%): [5.973, 12.839] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 6.183 ops/ms
# Warmup Iteration   2: 9.516 ops/ms
# Warmup Iteration   3: 10.054 ops/ms
Iteration   1: 10.159 ops/ms
Iteration   2: 10.031 ops/ms
Iteration   3: 10.224 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.138 ±(99.9%) 1.796 ops/ms [Average]
  (min, avg, max) = (10.031, 10.138, 10.224), stdev = 0.098
  CI (99.9%): [8.342, 11.934] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 5.853 ops/ms
# Warmup Iteration   2: 8.693 ops/ms
# Warmup Iteration   3: 9.199 ops/ms
Iteration   1: 9.419 ops/ms
Iteration   2: 9.861 ops/ms
Iteration   3: 9.887 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.722 ±(99.9%) 4.797 ops/ms [Average]
  (min, avg, max) = (9.419, 9.722, 9.887), stdev = 0.263
  CI (99.9%): [4.925, 14.520] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 6.037 ops/ms
# Warmup Iteration   2: 7.134 ops/ms
# Warmup Iteration   3: 7.439 ops/ms
Iteration   1: 7.576 ops/ms
Iteration   2: 7.530 ops/ms
Iteration   3: 7.551 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.552 ±(99.9%) 0.419 ops/ms [Average]
  (min, avg, max) = (7.530, 7.552, 7.576), stdev = 0.023
  CI (99.9%): [7.134, 7.971] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 4.745 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.331 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.228 ±(99.9%) 0.001 ms/op
Iteration   1: 3.192 ±(99.9%) 0.002 ms/op
Iteration   2: 3.119 ±(99.9%) 0.003 ms/op
Iteration   3: 3.125 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.145 ±(99.9%) 0.744 ms/op [Average]
  (min, avg, max) = (3.119, 3.145, 3.192), stdev = 0.041
  CI (99.9%): [2.402, 3.889] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.296 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.140 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.013 ±(99.9%) 0.002 ms/op
Iteration   1: 2.945 ±(99.9%) 0.003 ms/op
Iteration   2: 2.949 ±(99.9%) 0.002 ms/op
Iteration   3: 2.984 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.959 ±(99.9%) 0.391 ms/op [Average]
  (min, avg, max) = (2.945, 2.959, 2.984), stdev = 0.021
  CI (99.9%): [2.569, 3.350] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 4.360 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.339 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.230 ±(99.9%) 0.002 ms/op
Iteration   1: 3.212 ±(99.9%) 0.002 ms/op
Iteration   2: 3.171 ±(99.9%) 0.002 ms/op
Iteration   3: 3.218 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.200 ±(99.9%) 0.471 ms/op [Average]
  (min, avg, max) = (3.171, 3.200, 3.218), stdev = 0.026
  CI (99.9%): [2.729, 3.671] (assumes normal distribution)


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
# Warmup Iteration   1: 6.008 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 4.571 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.275 ±(99.9%) 0.014 ms/op
Iteration   1: 4.292 ±(99.9%) 0.016 ms/op
Iteration   2: 4.199 ±(99.9%) 0.007 ms/op
Iteration   3: 4.270 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.254 ±(99.9%) 0.886 ms/op [Average]
  (min, avg, max) = (4.199, 4.254, 4.292), stdev = 0.049
  CI (99.9%): [3.368, 5.140] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 5.062 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.549 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.407 ±(99.9%) 0.009 ms/op
Iteration   1: 3.329 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.864 ms/op
                 createUser·p0.50:   3.305 ms/op
                 createUser·p0.90:   3.936 ms/op
                 createUser·p0.95:   4.194 ms/op
                 createUser·p0.99:   4.989 ms/op
                 createUser·p0.999:  8.500 ms/op
                 createUser·p0.9999: 22.000 ms/op
                 createUser·p1.00:   23.036 ms/op

Iteration   2: 3.297 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.835 ms/op
                 createUser·p0.50:   3.269 ms/op
                 createUser·p0.90:   3.895 ms/op
                 createUser·p0.95:   4.137 ms/op
                 createUser·p0.99:   4.850 ms/op
                 createUser·p0.999:  9.150 ms/op
                 createUser·p0.9999: 25.536 ms/op
                 createUser·p1.00:   25.657 ms/op

Iteration   3: 3.260 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.812 ms/op
                 createUser·p0.50:   3.211 ms/op
                 createUser·p0.90:   3.817 ms/op
                 createUser·p0.95:   4.076 ms/op
                 createUser·p0.99:   4.923 ms/op
                 createUser·p0.999:  10.054 ms/op
                 createUser·p0.9999: 21.430 ms/op
                 createUser·p1.00:   22.217 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 291286
  mean =      3.295 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12954 
    [ 2.500,  5.000) = 275766 
    [ 5.000,  7.500) = 2026 
    [ 7.500, 10.000) = 283 
    [10.000, 12.500) = 33 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 101 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.812 ms/op
     p(50.0000) =      3.260 ms/op
     p(90.0000) =      3.887 ms/op
     p(95.0000) =      4.141 ms/op
     p(99.0000) =      4.915 ms/op
     p(99.9000) =      8.700 ms/op
     p(99.9900) =     24.576 ms/op
     p(99.9990) =     25.627 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.621 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.380 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.064 ±(99.9%) 0.006 ms/op
Iteration   1: 3.054 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.784 ms/op
                 existUser·p0.50:   3.019 ms/op
                 existUser·p0.90:   3.674 ms/op
                 existUser·p0.95:   3.949 ms/op
                 existUser·p0.99:   4.530 ms/op
                 existUser·p0.999:  6.558 ms/op
                 existUser·p0.9999: 13.371 ms/op
                 existUser·p1.00:   13.844 ms/op

Iteration   2: 3.051 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.856 ms/op
                 existUser·p0.50:   3.023 ms/op
                 existUser·p0.90:   3.400 ms/op
                 existUser·p0.95:   3.596 ms/op
                 existUser·p0.99:   4.325 ms/op
                 existUser·p0.999:  7.315 ms/op
                 existUser·p0.9999: 17.334 ms/op
                 existUser·p1.00:   17.793 ms/op

Iteration   3: 3.010 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.648 ms/op
                 existUser·p0.50:   3.002 ms/op
                 existUser·p0.90:   3.473 ms/op
                 existUser·p0.95:   3.670 ms/op
                 existUser·p0.99:   4.317 ms/op
                 existUser·p0.999:  6.338 ms/op
                 existUser·p0.9999: 17.195 ms/op
                 existUser·p1.00:   18.186 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 315870
  mean =      3.038 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 900 
    [ 1.250,  2.500) = 17117 
    [ 2.500,  3.750) = 281351 
    [ 3.750,  5.000) = 15241 
    [ 5.000,  6.250) = 822 
    [ 6.250,  7.500) = 281 
    [ 7.500,  8.750) = 29 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 7 
    [12.500, 13.750) = 23 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 44 
    [17.500, 18.750) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.648 ms/op
     p(50.0000) =      3.015 ms/op
     p(90.0000) =      3.510 ms/op
     p(95.0000) =      3.768 ms/op
     p(99.0000) =      4.407 ms/op
     p(99.9000) =      6.586 ms/op
     p(99.9900) =     17.170 ms/op
     p(99.9990) =     17.919 ms/op
     p(99.9999) =     18.186 ms/op
    p(100.0000) =     18.186 ms/op


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
# Warmup Iteration   1: 4.681 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.397 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.336 ±(99.9%) 0.008 ms/op
Iteration   1: 3.364 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.900 ms/op
                 getUser·p0.50:   3.314 ms/op
                 getUser·p0.90:   3.973 ms/op
                 getUser·p0.95:   4.243 ms/op
                 getUser·p0.99:   5.022 ms/op
                 getUser·p0.999:  8.134 ms/op
                 getUser·p0.9999: 14.360 ms/op
                 getUser·p1.00:   14.844 ms/op

Iteration   2: 3.225 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.532 ms/op
                 getUser·p0.50:   3.195 ms/op
                 getUser·p0.90:   3.604 ms/op
                 getUser·p0.95:   3.817 ms/op
                 getUser·p0.99:   4.506 ms/op
                 getUser·p0.999:  7.878 ms/op
                 getUser·p0.9999: 15.305 ms/op
                 getUser·p1.00:   15.499 ms/op

Iteration   3: 3.274 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.897 ms/op
                 getUser·p0.50:   3.224 ms/op
                 getUser·p0.90:   3.887 ms/op
                 getUser·p0.95:   4.104 ms/op
                 getUser·p0.99:   4.588 ms/op
                 getUser·p0.999:  8.035 ms/op
                 getUser·p0.9999: 17.219 ms/op
                 getUser·p1.00:   17.727 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 291790
  mean =      3.287 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 121 
    [ 1.250,  2.500) = 5905 
    [ 2.500,  3.750) = 249621 
    [ 3.750,  5.000) = 34293 
    [ 5.000,  6.250) = 1019 
    [ 6.250,  7.500) = 429 
    [ 7.500,  8.750) = 181 
    [ 8.750, 10.000) = 23 
    [10.000, 11.250) = 12 
    [11.250, 12.500) = 19 
    [12.500, 13.750) = 42 
    [13.750, 15.000) = 40 
    [15.000, 16.250) = 47 
    [16.250, 17.500) = 35 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.532 ms/op
     p(50.0000) =      3.240 ms/op
     p(90.0000) =      3.838 ms/op
     p(95.0000) =      4.096 ms/op
     p(99.0000) =      4.743 ms/op
     p(99.9000) =      8.071 ms/op
     p(99.9900) =     16.506 ms/op
     p(99.9990) =     17.569 ms/op
     p(99.9999) =     17.727 ms/op
    p(100.0000) =     17.727 ms/op


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
# Warmup Iteration   1: 5.300 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.524 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.317 ±(99.9%) 0.013 ms/op
Iteration   1: 4.293 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.481 ms/op
                 listUser·p0.50:   4.092 ms/op
                 listUser·p0.90:   5.464 ms/op
                 listUser·p0.95:   6.013 ms/op
                 listUser·p0.99:   7.463 ms/op
                 listUser·p0.999:  14.653 ms/op
                 listUser·p0.9999: 16.713 ms/op
                 listUser·p1.00:   17.236 ms/op

Iteration   2: 4.257 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.366 ms/op
                 listUser·p0.50:   4.047 ms/op
                 listUser·p0.90:   5.439 ms/op
                 listUser·p0.95:   6.267 ms/op
                 listUser·p0.99:   7.504 ms/op
                 listUser·p0.999:  16.774 ms/op
                 listUser·p0.9999: 20.299 ms/op
                 listUser·p1.00:   20.644 ms/op

Iteration   3: 4.232 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.110 ms/op
                 listUser·p0.50:   4.030 ms/op
                 listUser·p0.90:   5.480 ms/op
                 listUser·p0.95:   6.177 ms/op
                 listUser·p0.99:   7.561 ms/op
                 listUser·p0.999:  17.446 ms/op
                 listUser·p0.9999: 28.256 ms/op
                 listUser·p1.00:   30.147 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 225428
  mean =      4.260 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1747 
    [ 2.500,  5.000) = 188604 
    [ 5.000,  7.500) = 32801 
    [ 7.500, 10.000) = 1774 
    [10.000, 12.500) = 120 
    [12.500, 15.000) = 100 
    [15.000, 17.500) = 181 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 18 
    [27.500, 30.000) = 12 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.110 ms/op
     p(50.0000) =      4.059 ms/op
     p(90.0000) =      5.464 ms/op
     p(95.0000) =      6.152 ms/op
     p(99.0000) =      7.512 ms/op
     p(99.9000) =     16.180 ms/op
     p(99.9900) =     26.670 ms/op
     p(99.9990) =     30.080 ms/op
     p(99.9999) =     30.147 ms/op
    p(100.0000) =     30.147 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.406 ± 3.433  ops/ms
ClientGrpc.existUser                       thrpt       3  10.138 ± 1.796  ops/ms
ClientGrpc.getUser                         thrpt       3   9.722 ± 4.797  ops/ms
ClientGrpc.listUser                        thrpt       3   7.552 ± 0.419  ops/ms
ClientGrpc.createUser                       avgt       3   3.145 ± 0.744   ms/op
ClientGrpc.existUser                        avgt       3   2.959 ± 0.391   ms/op
ClientGrpc.getUser                          avgt       3   3.200 ± 0.471   ms/op
ClientGrpc.listUser                         avgt       3   4.254 ± 0.886   ms/op
ClientGrpc.createUser                     sample  291286   3.295 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.812           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.260           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.887           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.141           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.915           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.700           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.576           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.657           ms/op
ClientGrpc.existUser                      sample  315870   3.038 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.648           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.015           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.510           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.768           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.407           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.586           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.170           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.186           ms/op
ClientGrpc.getUser                        sample  291790   3.287 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.532           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.240           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.838           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.096           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.743           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.071           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.506           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.727           ms/op
ClientGrpc.listUser                       sample  225428   4.260 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.110           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.059           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.464           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.152           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.512           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.180           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.670           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          30.147           ms/op
