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
# Warmup Iteration   1: 2.429 ops/ms
# Warmup Iteration   2: 6.078 ops/ms
# Warmup Iteration   3: 7.564 ops/ms
Iteration   1: 8.226 ops/ms
Iteration   2: 7.961 ops/ms
Iteration   3: 8.058 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.082 ±(99.9%) 2.446 ops/ms [Average]
  (min, avg, max) = (7.961, 8.082, 8.226), stdev = 0.134
  CI (99.9%): [5.636, 10.528] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 4.839 ops/ms
# Warmup Iteration   2: 7.888 ops/ms
# Warmup Iteration   3: 8.339 ops/ms
Iteration   1: 8.819 ops/ms
Iteration   2: 8.654 ops/ms
Iteration   3: 8.650 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.708 ±(99.9%) 1.754 ops/ms [Average]
  (min, avg, max) = (8.650, 8.708, 8.819), stdev = 0.096
  CI (99.9%): [6.954, 10.462] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 4.284 ops/ms
# Warmup Iteration   2: 7.331 ops/ms
# Warmup Iteration   3: 7.773 ops/ms
Iteration   1: 8.018 ops/ms
Iteration   2: 7.963 ops/ms
Iteration   3: 8.075 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.019 ±(99.9%) 1.019 ops/ms [Average]
  (min, avg, max) = (7.963, 8.019, 8.075), stdev = 0.056
  CI (99.9%): [7.000, 9.037] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 4.105 ops/ms
# Warmup Iteration   2: 5.595 ops/ms
# Warmup Iteration   3: 5.969 ops/ms
Iteration   1: 6.222 ops/ms
Iteration   2: 6.195 ops/ms
Iteration   3: 6.166 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.194 ±(99.9%) 0.510 ops/ms [Average]
  (min, avg, max) = (6.166, 6.194, 6.222), stdev = 0.028
  CI (99.9%): [5.684, 6.704] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.074 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.189 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.143 ±(99.9%) 0.011 ms/op
Iteration   1: 4.027 ±(99.9%) 0.002 ms/op
Iteration   2: 3.998 ±(99.9%) 0.003 ms/op
Iteration   3: 3.976 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.000 ±(99.9%) 0.469 ms/op [Average]
  (min, avg, max) = (3.976, 4.000, 4.027), stdev = 0.026
  CI (99.9%): [3.531, 4.469] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 5.672 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.109 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.865 ±(99.9%) 0.020 ms/op
Iteration   1: 3.660 ±(99.9%) 0.003 ms/op
Iteration   2: 3.719 ±(99.9%) 0.003 ms/op
Iteration   3: 3.641 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.673 ±(99.9%) 0.745 ms/op [Average]
  (min, avg, max) = (3.641, 3.673, 3.719), stdev = 0.041
  CI (99.9%): [2.928, 4.418] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 6.311 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.298 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.051 ±(99.9%) 0.008 ms/op
Iteration   1: 4.130 ±(99.9%) 0.003 ms/op
Iteration   2: 4.044 ±(99.9%) 0.004 ms/op
Iteration   3: 4.040 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.071 ±(99.9%) 0.925 ms/op [Average]
  (min, avg, max) = (4.040, 4.071, 4.130), stdev = 0.051
  CI (99.9%): [3.146, 4.996] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 7.803 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 5.694 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 5.318 ±(99.9%) 0.021 ms/op
Iteration   1: 5.153 ±(99.9%) 0.024 ms/op
Iteration   2: 5.180 ±(99.9%) 0.012 ms/op
Iteration   3: 5.136 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.156 ±(99.9%) 0.407 ms/op [Average]
  (min, avg, max) = (5.136, 5.156, 5.180), stdev = 0.022
  CI (99.9%): [4.749, 5.564] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 6.419 ±(99.9%) 0.074 ms/op
# Warmup Iteration   2: 4.134 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.912 ±(99.9%) 0.011 ms/op
Iteration   1: 3.887 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.924 ms/op
                 createUser·p0.50:   3.764 ms/op
                 createUser·p0.90:   4.981 ms/op
                 createUser·p0.95:   5.497 ms/op
                 createUser·p0.99:   7.422 ms/op
                 createUser·p0.999:  14.687 ms/op
                 createUser·p0.9999: 20.163 ms/op
                 createUser·p1.00:   22.118 ms/op

Iteration   2: 3.869 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.959 ms/op
                 createUser·p0.50:   3.748 ms/op
                 createUser·p0.90:   4.801 ms/op
                 createUser·p0.95:   5.276 ms/op
                 createUser·p0.99:   7.111 ms/op
                 createUser·p0.999:  17.072 ms/op
                 createUser·p0.9999: 19.137 ms/op
                 createUser·p1.00:   21.987 ms/op

Iteration   3: 3.828 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.763 ms/op
                 createUser·p0.50:   3.723 ms/op
                 createUser·p0.90:   4.743 ms/op
                 createUser·p0.95:   5.374 ms/op
                 createUser·p0.99:   7.086 ms/op
                 createUser·p0.999:  12.158 ms/op
                 createUser·p0.9999: 33.751 ms/op
                 createUser·p1.00:   34.013 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 248530
  mean =      3.861 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11653 
    [ 2.500,  5.000) = 216332 
    [ 5.000,  7.500) = 18539 
    [ 7.500, 10.000) = 1268 
    [10.000, 12.500) = 435 
    [12.500, 15.000) = 113 
    [15.000, 17.500) = 67 
    [17.500, 20.000) = 78 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 14 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.763 ms/op
     p(50.0000) =      3.744 ms/op
     p(90.0000) =      4.850 ms/op
     p(95.0000) =      5.390 ms/op
     p(99.0000) =      7.193 ms/op
     p(99.9000) =     13.066 ms/op
     p(99.9900) =     30.386 ms/op
     p(99.9990) =     33.882 ms/op
     p(99.9999) =     34.013 ms/op
    p(100.0000) =     34.013 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.782 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 3.962 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.752 ±(99.9%) 0.010 ms/op
Iteration   1: 3.668 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.507 ms/op
                 existUser·p0.50:   3.604 ms/op
                 existUser·p0.90:   4.571 ms/op
                 existUser·p0.95:   5.112 ms/op
                 existUser·p0.99:   6.850 ms/op
                 existUser·p0.999:  11.853 ms/op
                 existUser·p0.9999: 17.671 ms/op
                 existUser·p1.00:   17.990 ms/op

Iteration   2: 3.611 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.968 ms/op
                 existUser·p0.50:   3.547 ms/op
                 existUser·p0.90:   4.432 ms/op
                 existUser·p0.95:   4.956 ms/op
                 existUser·p0.99:   6.332 ms/op
                 existUser·p0.999:  10.868 ms/op
                 existUser·p0.9999: 17.310 ms/op
                 existUser·p1.00:   18.055 ms/op

Iteration   3: 3.660 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.863 ms/op
                 existUser·p0.50:   3.551 ms/op
                 existUser·p0.90:   4.399 ms/op
                 existUser·p0.95:   4.882 ms/op
                 existUser·p0.99:   6.621 ms/op
                 existUser·p0.999:  13.255 ms/op
                 existUser·p0.9999: 23.339 ms/op
                 existUser·p1.00:   23.527 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 263221
  mean =      3.646 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12310 
    [ 2.500,  5.000) = 237944 
    [ 5.000,  7.500) = 11587 
    [ 7.500, 10.000) = 928 
    [10.000, 12.500) = 216 
    [12.500, 15.000) = 79 
    [15.000, 17.500) = 107 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.507 ms/op
     p(50.0000) =      3.568 ms/op
     p(90.0000) =      4.465 ms/op
     p(95.0000) =      4.989 ms/op
     p(99.0000) =      6.603 ms/op
     p(99.9000) =     11.986 ms/op
     p(99.9900) =     20.633 ms/op
     p(99.9990) =     23.441 ms/op
     p(99.9999) =     23.527 ms/op
    p(100.0000) =     23.527 ms/op


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
# Warmup Iteration   1: 6.139 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 4.338 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.139 ±(99.9%) 0.012 ms/op
Iteration   1: 3.999 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.966 ms/op
                 getUser·p0.50:   3.875 ms/op
                 getUser·p0.90:   4.964 ms/op
                 getUser·p0.95:   5.472 ms/op
                 getUser·p0.99:   7.101 ms/op
                 getUser·p0.999:  13.548 ms/op
                 getUser·p0.9999: 16.073 ms/op
                 getUser·p1.00:   16.089 ms/op

Iteration   2: 4.040 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.049 ms/op
                 getUser·p0.50:   3.928 ms/op
                 getUser·p0.90:   5.054 ms/op
                 getUser·p0.95:   5.579 ms/op
                 getUser·p0.99:   7.397 ms/op
                 getUser·p0.999:  13.333 ms/op
                 getUser·p0.9999: 19.601 ms/op
                 getUser·p1.00:   20.185 ms/op

Iteration   3: 3.945 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.849 ms/op
                 getUser·p0.50:   3.838 ms/op
                 getUser·p0.90:   4.841 ms/op
                 getUser·p0.95:   5.284 ms/op
                 getUser·p0.99:   6.816 ms/op
                 getUser·p0.999:  11.551 ms/op
                 getUser·p0.9999: 18.576 ms/op
                 getUser·p1.00:   19.071 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 240329
  mean =      3.994 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6377 
    [ 2.500,  5.000) = 211478 
    [ 5.000,  7.500) = 20658 
    [ 7.500, 10.000) = 1264 
    [10.000, 12.500) = 284 
    [12.500, 15.000) = 92 
    [15.000, 17.500) = 118 
    [17.500, 20.000) = 55 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.849 ms/op
     p(50.0000) =      3.879 ms/op
     p(90.0000) =      4.956 ms/op
     p(95.0000) =      5.439 ms/op
     p(99.0000) =      7.127 ms/op
     p(99.9000) =     13.025 ms/op
     p(99.9900) =     18.547 ms/op
     p(99.9990) =     20.080 ms/op
     p(99.9999) =     20.185 ms/op
    p(100.0000) =     20.185 ms/op


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
# Warmup Iteration   1: 7.657 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 5.470 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 5.176 ±(99.9%) 0.017 ms/op
Iteration   1: 5.041 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.595 ms/op
                 listUser·p0.50:   4.776 ms/op
                 listUser·p0.90:   6.537 ms/op
                 listUser·p0.95:   7.479 ms/op
                 listUser·p0.99:   9.601 ms/op
                 listUser·p0.999:  15.697 ms/op
                 listUser·p0.9999: 19.625 ms/op
                 listUser·p1.00:   20.054 ms/op

Iteration   2: 5.190 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.325 ms/op
                 listUser·p0.50:   4.915 ms/op
                 listUser·p0.90:   6.676 ms/op
                 listUser·p0.95:   7.520 ms/op
                 listUser·p0.99:   9.880 ms/op
                 listUser·p0.999:  23.210 ms/op
                 listUser·p0.9999: 27.285 ms/op
                 listUser·p1.00:   27.984 ms/op

Iteration   3: 5.095 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.033 ms/op
                 listUser·p0.50:   4.801 ms/op
                 listUser·p0.90:   6.709 ms/op
                 listUser·p0.95:   7.700 ms/op
                 listUser·p0.99:   10.306 ms/op
                 listUser·p0.999:  20.717 ms/op
                 listUser·p0.9999: 24.951 ms/op
                 listUser·p1.00:   25.461 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 187915
  mean =      5.108 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 312 
    [ 2.500,  5.000) = 109694 
    [ 5.000,  7.500) = 68026 
    [ 7.500, 10.000) = 8120 
    [10.000, 12.500) = 1111 
    [12.500, 15.000) = 214 
    [15.000, 17.500) = 167 
    [17.500, 20.000) = 103 
    [20.000, 22.500) = 65 
    [22.500, 25.000) = 80 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      1.033 ms/op
     p(50.0000) =      4.833 ms/op
     p(90.0000) =      6.644 ms/op
     p(95.0000) =      7.569 ms/op
     p(99.0000) =      9.880 ms/op
     p(99.9000) =     19.270 ms/op
     p(99.9900) =     25.343 ms/op
     p(99.9990) =     27.552 ms/op
     p(99.9999) =     27.984 ms/op
    p(100.0000) =     27.984 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.082 ± 2.446  ops/ms
ClientGrpc.existUser                       thrpt       3   8.708 ± 1.754  ops/ms
ClientGrpc.getUser                         thrpt       3   8.019 ± 1.019  ops/ms
ClientGrpc.listUser                        thrpt       3   6.194 ± 0.510  ops/ms
ClientGrpc.createUser                       avgt       3   4.000 ± 0.469   ms/op
ClientGrpc.existUser                        avgt       3   3.673 ± 0.745   ms/op
ClientGrpc.getUser                          avgt       3   4.071 ± 0.925   ms/op
ClientGrpc.listUser                         avgt       3   5.156 ± 0.407   ms/op
ClientGrpc.createUser                     sample  248530   3.861 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.763           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.744           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.850           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.390           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.193           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.066           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          30.386           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          34.013           ms/op
ClientGrpc.existUser                      sample  263221   3.646 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.507           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.568           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.465           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.989           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.603           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.986           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.633           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.527           ms/op
ClientGrpc.getUser                        sample  240329   3.994 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.849           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.879           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.956           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.439           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.127           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          13.025           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.547           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.185           ms/op
ClientGrpc.listUser                       sample  187915   5.108 ± 0.011   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.033           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.833           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.644           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.569           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.880           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.270           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.343           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.984           ms/op
