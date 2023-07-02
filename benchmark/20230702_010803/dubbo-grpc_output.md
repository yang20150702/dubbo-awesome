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
# Warmup Iteration   1: 4.725 ops/ms
# Warmup Iteration   2: 8.887 ops/ms
# Warmup Iteration   3: 10.196 ops/ms
Iteration   1: 10.506 ops/ms
Iteration   2: 10.521 ops/ms
Iteration   3: 10.596 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.541 ±(99.9%) 0.876 ops/ms [Average]
  (min, avg, max) = (10.506, 10.541, 10.596), stdev = 0.048
  CI (99.9%): [9.665, 11.417] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 8.178 ops/ms
# Warmup Iteration   2: 10.553 ops/ms
# Warmup Iteration   3: 10.951 ops/ms
Iteration   1: 10.955 ops/ms
Iteration   2: 11.098 ops/ms
Iteration   3: 10.868 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.974 ±(99.9%) 2.111 ops/ms [Average]
  (min, avg, max) = (10.868, 10.974, 11.098), stdev = 0.116
  CI (99.9%): [8.863, 13.084] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 7.269 ops/ms
# Warmup Iteration   2: 10.117 ops/ms
# Warmup Iteration   3: 10.276 ops/ms
Iteration   1: 10.591 ops/ms
Iteration   2: 10.363 ops/ms
Iteration   3: 10.474 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.476 ±(99.9%) 2.075 ops/ms [Average]
  (min, avg, max) = (10.363, 10.476, 10.591), stdev = 0.114
  CI (99.9%): [8.401, 12.551] (assumes normal distribution)


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
# Warmup Iteration   1: 6.016 ops/ms
# Warmup Iteration   2: 7.867 ops/ms
# Warmup Iteration   3: 7.997 ops/ms
Iteration   1: 8.191 ops/ms
Iteration   2: 8.198 ops/ms
Iteration   3: 8.214 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.201 ±(99.9%) 0.216 ops/ms [Average]
  (min, avg, max) = (8.191, 8.201, 8.214), stdev = 0.012
  CI (99.9%): [7.985, 8.416] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.876 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.140 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.046 ±(99.9%) 0.003 ms/op
Iteration   1: 3.104 ±(99.9%) 0.005 ms/op
Iteration   2: 3.041 ±(99.9%) 0.005 ms/op
Iteration   3: 3.073 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.073 ±(99.9%) 0.571 ms/op [Average]
  (min, avg, max) = (3.041, 3.073, 3.104), stdev = 0.031
  CI (99.9%): [2.502, 3.643] (assumes normal distribution)


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
# Warmup Iteration   1: 3.918 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.031 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.822 ±(99.9%) 0.005 ms/op
Iteration   1: 2.984 ±(99.9%) 0.004 ms/op
Iteration   2: 2.997 ±(99.9%) 0.004 ms/op
Iteration   3: 2.955 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.979 ±(99.9%) 0.391 ms/op [Average]
  (min, avg, max) = (2.955, 2.979, 2.997), stdev = 0.021
  CI (99.9%): [2.587, 3.370] (assumes normal distribution)


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
# Warmup Iteration   1: 3.914 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.166 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.083 ±(99.9%) 0.003 ms/op
Iteration   1: 3.100 ±(99.9%) 0.003 ms/op
Iteration   2: 3.041 ±(99.9%) 0.003 ms/op
Iteration   3: 3.012 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.051 ±(99.9%) 0.817 ms/op [Average]
  (min, avg, max) = (3.012, 3.051, 3.100), stdev = 0.045
  CI (99.9%): [2.234, 3.868] (assumes normal distribution)


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
# Warmup Iteration   1: 4.945 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.031 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.027 ±(99.9%) 0.019 ms/op
Iteration   1: 3.889 ±(99.9%) 0.015 ms/op
Iteration   2: 3.911 ±(99.9%) 0.036 ms/op
Iteration   3: 3.980 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.927 ±(99.9%) 0.870 ms/op [Average]
  (min, avg, max) = (3.889, 3.927, 3.980), stdev = 0.048
  CI (99.9%): [3.057, 4.797] (assumes normal distribution)


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
# Warmup Iteration   1: 4.075 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.166 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.035 ±(99.9%) 0.007 ms/op
Iteration   1: 2.986 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.572 ms/op
                 createUser·p0.50:   2.986 ms/op
                 createUser·p0.90:   3.473 ms/op
                 createUser·p0.95:   3.740 ms/op
                 createUser·p0.99:   4.424 ms/op
                 createUser·p0.999:  6.537 ms/op
                 createUser·p0.9999: 11.446 ms/op
                 createUser·p1.00:   11.649 ms/op

Iteration   2: 3.082 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.663 ms/op
                 createUser·p0.50:   3.076 ms/op
                 createUser·p0.90:   3.596 ms/op
                 createUser·p0.95:   3.711 ms/op
                 createUser·p0.99:   4.178 ms/op
                 createUser·p0.999:  7.143 ms/op
                 createUser·p0.9999: 14.219 ms/op
                 createUser·p1.00:   14.664 ms/op

Iteration   3: 3.030 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.727 ms/op
                 createUser·p0.50:   3.011 ms/op
                 createUser·p0.90:   3.494 ms/op
                 createUser·p0.95:   3.715 ms/op
                 createUser·p0.99:   4.407 ms/op
                 createUser·p0.999:  11.221 ms/op
                 createUser·p0.9999: 15.015 ms/op
                 createUser·p1.00:   15.434 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 316557
  mean =      3.032 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1322 
    [ 1.250,  2.500) = 19122 
    [ 2.500,  3.750) = 281997 
    [ 3.750,  5.000) = 12843 
    [ 5.000,  6.250) = 720 
    [ 6.250,  7.500) = 168 
    [ 7.500,  8.750) = 67 
    [ 8.750, 10.000) = 30 
    [10.000, 11.250) = 68 
    [11.250, 12.500) = 51 
    [12.500, 13.750) = 75 
    [13.750, 15.000) = 83 
    [15.000, 16.250) = 11 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.572 ms/op
     p(50.0000) =      3.019 ms/op
     p(90.0000) =      3.539 ms/op
     p(95.0000) =      3.719 ms/op
     p(99.0000) =      4.325 ms/op
     p(99.9000) =      9.180 ms/op
     p(99.9900) =     14.795 ms/op
     p(99.9990) =     15.295 ms/op
     p(99.9999) =     15.434 ms/op
    p(100.0000) =     15.434 ms/op


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
# Warmup Iteration   1: 3.654 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.012 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.870 ±(99.9%) 0.007 ms/op
Iteration   1: 2.876 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.659 ms/op
                 existUser·p0.50:   2.888 ms/op
                 existUser·p0.90:   3.461 ms/op
                 existUser·p0.95:   3.678 ms/op
                 existUser·p0.99:   4.465 ms/op
                 existUser·p0.999:  6.316 ms/op
                 existUser·p0.9999: 12.501 ms/op
                 existUser·p1.00:   12.861 ms/op

Iteration   2: 2.923 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.519 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.441 ms/op
                 existUser·p0.95:   3.654 ms/op
                 existUser·p0.99:   4.637 ms/op
                 existUser·p0.999:  5.496 ms/op
                 existUser·p0.9999: 17.368 ms/op
                 existUser·p1.00:   18.219 ms/op

Iteration   3: 2.898 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.700 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.346 ms/op
                 existUser·p0.95:   3.650 ms/op
                 existUser·p0.99:   4.751 ms/op
                 existUser·p0.999:  12.748 ms/op
                 existUser·p0.9999: 16.742 ms/op
                 existUser·p1.00:   17.138 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 331228
  mean =      2.899 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3181 
    [ 1.250,  2.500) = 44227 
    [ 2.500,  3.750) = 270658 
    [ 3.750,  5.000) = 11780 
    [ 5.000,  6.250) = 891 
    [ 6.250,  7.500) = 132 
    [ 7.500,  8.750) = 49 
    [ 8.750, 10.000) = 51 
    [10.000, 11.250) = 67 
    [11.250, 12.500) = 22 
    [12.500, 13.750) = 45 
    [13.750, 15.000) = 60 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 51 
    [17.500, 18.750) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.519 ms/op
     p(50.0000) =      2.904 ms/op
     p(90.0000) =      3.420 ms/op
     p(95.0000) =      3.662 ms/op
     p(99.0000) =      4.637 ms/op
     p(99.9000) =      7.994 ms/op
     p(99.9900) =     16.839 ms/op
     p(99.9990) =     17.969 ms/op
     p(99.9999) =     18.219 ms/op
    p(100.0000) =     18.219 ms/op


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
# Warmup Iteration   1: 4.014 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.151 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.054 ±(99.9%) 0.007 ms/op
Iteration   1: 3.017 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.590 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.478 ms/op
                 getUser·p0.95:   3.764 ms/op
                 getUser·p0.99:   4.719 ms/op
                 getUser·p0.999:  10.977 ms/op
                 getUser·p0.9999: 14.120 ms/op
                 getUser·p1.00:   14.287 ms/op

Iteration   2: 3.037 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.587 ms/op
                 getUser·p0.50:   3.039 ms/op
                 getUser·p0.90:   3.428 ms/op
                 getUser·p0.95:   3.654 ms/op
                 getUser·p0.99:   4.522 ms/op
                 getUser·p0.999:  10.717 ms/op
                 getUser·p0.9999: 22.035 ms/op
                 getUser·p1.00:   22.249 ms/op

Iteration   3: 3.041 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.618 ms/op
                 getUser·p0.50:   3.052 ms/op
                 getUser·p0.90:   3.461 ms/op
                 getUser·p0.95:   3.596 ms/op
                 getUser·p0.99:   4.358 ms/op
                 getUser·p0.999:  7.430 ms/op
                 getUser·p0.9999: 25.837 ms/op
                 getUser·p1.00:   26.116 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 316626
  mean =      3.031 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20894 
    [ 2.500,  5.000) = 294167 
    [ 5.000,  7.500) = 1074 
    [ 7.500, 10.000) = 111 
    [10.000, 12.500) = 169 
    [12.500, 15.000) = 146 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.587 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      3.457 ms/op
     p(95.0000) =      3.670 ms/op
     p(99.0000) =      4.588 ms/op
     p(99.9000) =     10.600 ms/op
     p(99.9900) =     24.937 ms/op
     p(99.9990) =     26.051 ms/op
     p(99.9999) =     26.116 ms/op
    p(100.0000) =     26.116 ms/op


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
# Warmup Iteration   1: 5.273 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.970 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.987 ±(99.9%) 0.012 ms/op
Iteration   1: 3.899 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.212 ms/op
                 listUser·p0.50:   3.789 ms/op
                 listUser·p0.90:   4.751 ms/op
                 listUser·p0.95:   5.521 ms/op
                 listUser·p0.99:   6.922 ms/op
                 listUser·p0.999:  13.091 ms/op
                 listUser·p0.9999: 16.016 ms/op
                 listUser·p1.00:   18.448 ms/op

Iteration   2: 3.987 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.942 ms/op
                 listUser·p0.50:   3.846 ms/op
                 listUser·p0.90:   5.038 ms/op
                 listUser·p0.95:   5.652 ms/op
                 listUser·p0.99:   6.873 ms/op
                 listUser·p0.999:  15.860 ms/op
                 listUser·p0.9999: 21.487 ms/op
                 listUser·p1.00:   22.118 ms/op

Iteration   3: 3.866 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.570 ms/op
                 listUser·p0.50:   3.719 ms/op
                 listUser·p0.90:   4.874 ms/op
                 listUser·p0.95:   5.612 ms/op
                 listUser·p0.99:   6.947 ms/op
                 listUser·p0.999:  18.055 ms/op
                 listUser·p0.9999: 21.174 ms/op
                 listUser·p1.00:   21.496 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 245181
  mean =      3.916 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5360 
    [ 2.500,  5.000) = 217488 
    [ 5.000,  7.500) = 20892 
    [ 7.500, 10.000) = 852 
    [10.000, 12.500) = 148 
    [12.500, 15.000) = 171 
    [15.000, 17.500) = 150 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 87 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.570 ms/op
     p(50.0000) =      3.785 ms/op
     p(90.0000) =      4.907 ms/op
     p(95.0000) =      5.595 ms/op
     p(99.0000) =      6.914 ms/op
     p(99.9000) =     15.332 ms/op
     p(99.9900) =     20.955 ms/op
     p(99.9990) =     21.990 ms/op
     p(99.9999) =     22.118 ms/op
    p(100.0000) =     22.118 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.541 ± 0.876  ops/ms
ClientGrpc.existUser                       thrpt       3  10.974 ± 2.111  ops/ms
ClientGrpc.getUser                         thrpt       3  10.476 ± 2.075  ops/ms
ClientGrpc.listUser                        thrpt       3   8.201 ± 0.216  ops/ms
ClientGrpc.createUser                       avgt       3   3.073 ± 0.571   ms/op
ClientGrpc.existUser                        avgt       3   2.979 ± 0.391   ms/op
ClientGrpc.getUser                          avgt       3   3.051 ± 0.817   ms/op
ClientGrpc.listUser                         avgt       3   3.927 ± 0.870   ms/op
ClientGrpc.createUser                     sample  316557   3.032 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.572           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.019           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.539           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.719           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.325           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.180           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          14.795           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          15.434           ms/op
ClientGrpc.existUser                      sample  331228   2.899 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.519           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.904           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.420           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.662           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.637           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.994           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.839           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.219           ms/op
ClientGrpc.getUser                        sample  316626   3.031 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.587           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.031           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.457           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.670           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.588           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.600           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          24.937           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          26.116           ms/op
ClientGrpc.listUser                       sample  245181   3.916 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.570           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.785           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.907           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.595           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.914           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.332           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.955           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.118           ms/op
