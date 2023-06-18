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
# Warmup Iteration   1: 1.821 ops/ms
# Warmup Iteration   2: 4.805 ops/ms
# Warmup Iteration   3: 6.209 ops/ms
Iteration   1: 6.464 ops/ms
Iteration   2: 6.803 ops/ms
Iteration   3: 6.816 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  6.694 ±(99.9%) 3.632 ops/ms [Average]
  (min, avg, max) = (6.464, 6.694, 6.816), stdev = 0.199
  CI (99.9%): [3.062, 10.326] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.855 ops/ms
# Warmup Iteration   2: 6.478 ops/ms
# Warmup Iteration   3: 7.042 ops/ms
Iteration   1: 6.951 ops/ms
Iteration   2: 7.183 ops/ms
Iteration   3: 7.130 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.088 ±(99.9%) 2.215 ops/ms [Average]
  (min, avg, max) = (6.951, 7.088, 7.183), stdev = 0.121
  CI (99.9%): [4.873, 9.303] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 3.590 ops/ms
# Warmup Iteration   2: 5.814 ops/ms
# Warmup Iteration   3: 6.369 ops/ms
Iteration   1: 6.802 ops/ms
Iteration   2: 6.841 ops/ms
Iteration   3: 6.937 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  6.860 ±(99.9%) 1.271 ops/ms [Average]
  (min, avg, max) = (6.802, 6.860, 6.937), stdev = 0.070
  CI (99.9%): [5.588, 8.131] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.997 ops/ms
# Warmup Iteration   2: 4.588 ops/ms
# Warmup Iteration   3: 4.871 ops/ms
Iteration   1: 4.983 ops/ms
Iteration   2: 5.078 ops/ms
Iteration   3: 5.108 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.056 ±(99.9%) 1.193 ops/ms [Average]
  (min, avg, max) = (4.983, 5.056, 5.108), stdev = 0.065
  CI (99.9%): [3.863, 6.249] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 7.965 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 5.036 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.731 ±(99.9%) 0.016 ms/op
Iteration   1: 4.646 ±(99.9%) 0.005 ms/op
Iteration   2: 4.661 ±(99.9%) 0.006 ms/op
Iteration   3: 4.630 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.646 ±(99.9%) 0.280 ms/op [Average]
  (min, avg, max) = (4.630, 4.646, 4.661), stdev = 0.015
  CI (99.9%): [4.366, 4.925] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 6.805 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.863 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.483 ±(99.9%) 0.009 ms/op
Iteration   1: 4.392 ±(99.9%) 0.007 ms/op
Iteration   2: 4.268 ±(99.9%) 0.004 ms/op
Iteration   3: 4.361 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.340 ±(99.9%) 1.171 ms/op [Average]
  (min, avg, max) = (4.268, 4.340, 4.392), stdev = 0.064
  CI (99.9%): [3.170, 5.511] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 7.873 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 5.486 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.793 ±(99.9%) 0.009 ms/op
Iteration   1: 4.644 ±(99.9%) 0.005 ms/op
Iteration   2: 4.780 ±(99.9%) 0.005 ms/op
Iteration   3: 4.636 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.687 ±(99.9%) 1.478 ms/op [Average]
  (min, avg, max) = (4.636, 4.687, 4.780), stdev = 0.081
  CI (99.9%): [3.209, 6.165] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 10.445 ±(99.9%) 0.122 ms/op
# Warmup Iteration   2: 6.688 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 6.270 ±(99.9%) 0.028 ms/op
Iteration   1: 6.241 ±(99.9%) 0.012 ms/op
Iteration   2: 6.284 ±(99.9%) 0.020 ms/op
Iteration   3: 6.238 ±(99.9%) 0.026 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.255 ±(99.9%) 0.472 ms/op [Average]
  (min, avg, max) = (6.238, 6.255, 6.284), stdev = 0.026
  CI (99.9%): [5.783, 6.726] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 7.512 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 5.116 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.742 ±(99.9%) 0.015 ms/op
Iteration   1: 4.590 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   0.964 ms/op
                 createUser·p0.50:   4.456 ms/op
                 createUser·p0.90:   6.005 ms/op
                 createUser·p0.95:   6.676 ms/op
                 createUser·p0.99:   9.241 ms/op
                 createUser·p0.999:  15.394 ms/op
                 createUser·p0.9999: 17.730 ms/op
                 createUser·p1.00:   18.088 ms/op

Iteration   2: 4.626 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.006 ms/op
                 createUser·p0.50:   4.497 ms/op
                 createUser·p0.90:   5.972 ms/op
                 createUser·p0.95:   6.619 ms/op
                 createUser·p0.99:   8.864 ms/op
                 createUser·p0.999:  12.409 ms/op
                 createUser·p0.9999: 22.985 ms/op
                 createUser·p1.00:   23.691 ms/op

Iteration   3: 4.670 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   0.427 ms/op
                 createUser·p0.50:   4.481 ms/op
                 createUser·p0.90:   6.005 ms/op
                 createUser·p0.95:   6.742 ms/op
                 createUser·p0.99:   9.315 ms/op
                 createUser·p0.999:  14.021 ms/op
                 createUser·p0.9999: 46.944 ms/op
                 createUser·p1.00:   47.645 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 207274
  mean =      4.629 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 146842 
    [ 5.000, 10.000) = 59254 
    [10.000, 15.000) = 1000 
    [15.000, 20.000) = 130 
    [20.000, 25.000) = 16 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.427 ms/op
     p(50.0000) =      4.473 ms/op
     p(90.0000) =      5.997 ms/op
     p(95.0000) =      6.676 ms/op
     p(99.0000) =      9.159 ms/op
     p(99.9000) =     14.725 ms/op
     p(99.9900) =     44.273 ms/op
     p(99.9990) =     47.251 ms/op
     p(99.9999) =     47.645 ms/op
    p(100.0000) =     47.645 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.826 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 4.765 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.399 ±(99.9%) 0.015 ms/op
Iteration   1: 4.330 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.223 ms/op
                 existUser·p0.50:   4.174 ms/op
                 existUser·p0.90:   5.374 ms/op
                 existUser·p0.95:   6.070 ms/op
                 existUser·p0.99:   8.618 ms/op
                 existUser·p0.999:  13.463 ms/op
                 existUser·p0.9999: 16.342 ms/op
                 existUser·p1.00:   22.413 ms/op

Iteration   2: 4.280 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.787 ms/op
                 existUser·p0.50:   4.157 ms/op
                 existUser·p0.90:   5.267 ms/op
                 existUser·p0.95:   5.988 ms/op
                 existUser·p0.99:   8.208 ms/op
                 existUser·p0.999:  14.270 ms/op
                 existUser·p0.9999: 27.198 ms/op
                 existUser·p1.00:   27.558 ms/op

Iteration   3: 4.508 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.967 ms/op
                 existUser·p0.50:   4.317 ms/op
                 existUser·p0.90:   5.800 ms/op
                 existUser·p0.95:   6.652 ms/op
                 existUser·p0.99:   8.995 ms/op
                 existUser·p0.999:  15.402 ms/op
                 existUser·p0.9999: 25.618 ms/op
                 existUser·p1.00:   37.224 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 219630
  mean =      4.370 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6759 
    [ 2.500,  5.000) = 174210 
    [ 5.000,  7.500) = 34091 
    [ 7.500, 10.000) = 3603 
    [10.000, 12.500) = 578 
    [12.500, 15.000) = 236 
    [15.000, 17.500) = 57 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 46 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.787 ms/op
     p(50.0000) =      4.211 ms/op
     p(90.0000) =      5.497 ms/op
     p(95.0000) =      6.259 ms/op
     p(99.0000) =      8.618 ms/op
     p(99.9000) =     14.336 ms/op
     p(99.9900) =     26.186 ms/op
     p(99.9990) =     27.539 ms/op
     p(99.9999) =     37.224 ms/op
    p(100.0000) =     37.224 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 7.466 ±(99.9%) 0.098 ms/op
# Warmup Iteration   2: 5.051 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.853 ±(99.9%) 0.019 ms/op
Iteration   1: 4.876 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   0.963 ms/op
                 getUser·p0.50:   4.628 ms/op
                 getUser·p0.90:   6.463 ms/op
                 getUser·p0.95:   7.496 ms/op
                 getUser·p0.99:   9.732 ms/op
                 getUser·p0.999:  16.076 ms/op
                 getUser·p0.9999: 28.457 ms/op
                 getUser·p1.00:   28.869 ms/op

Iteration   2: 4.916 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   1.178 ms/op
                 getUser·p0.50:   4.702 ms/op
                 getUser·p0.90:   6.603 ms/op
                 getUser·p0.95:   7.569 ms/op
                 getUser·p0.99:   10.027 ms/op
                 getUser·p0.999:  14.221 ms/op
                 getUser·p0.9999: 32.145 ms/op
                 getUser·p1.00:   32.702 ms/op

Iteration   3: 4.795 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   1.130 ms/op
                 getUser·p0.50:   4.604 ms/op
                 getUser·p0.90:   6.095 ms/op
                 getUser·p0.95:   6.930 ms/op
                 getUser·p0.99:   9.159 ms/op
                 getUser·p0.999:  14.127 ms/op
                 getUser·p0.9999: 35.914 ms/op
                 getUser·p1.00:   36.372 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 197389
  mean =      4.862 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4864 
    [ 2.500,  5.000) = 122203 
    [ 5.000,  7.500) = 61398 
    [ 7.500, 10.000) = 7367 
    [10.000, 12.500) = 975 
    [12.500, 15.000) = 371 
    [15.000, 17.500) = 113 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 9 
    [27.500, 30.000) = 42 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.963 ms/op
     p(50.0000) =      4.637 ms/op
     p(90.0000) =      6.390 ms/op
     p(95.0000) =      7.348 ms/op
     p(99.0000) =      9.634 ms/op
     p(99.9000) =     15.149 ms/op
     p(99.9900) =     35.538 ms/op
     p(99.9990) =     36.245 ms/op
     p(99.9999) =     36.372 ms/op
    p(100.0000) =     36.372 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 9.539 ±(99.9%) 0.129 ms/op
# Warmup Iteration   2: 7.067 ±(99.9%) 0.038 ms/op
# Warmup Iteration   3: 6.258 ±(99.9%) 0.027 ms/op
Iteration   1: 6.356 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   1.982 ms/op
                 listUser·p0.50:   5.972 ms/op
                 listUser·p0.90:   8.602 ms/op
                 listUser·p0.95:   9.634 ms/op
                 listUser·p0.99:   12.304 ms/op
                 listUser·p0.999:  19.680 ms/op
                 listUser·p0.9999: 22.312 ms/op
                 listUser·p1.00:   24.248 ms/op

Iteration   2: 6.163 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   1.612 ms/op
                 listUser·p0.50:   5.767 ms/op
                 listUser·p0.90:   8.356 ms/op
                 listUser·p0.95:   9.355 ms/op
                 listUser·p0.99:   11.796 ms/op
                 listUser·p0.999:  21.430 ms/op
                 listUser·p0.9999: 31.103 ms/op
                 listUser·p1.00:   31.687 ms/op

Iteration   3: 6.145 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   1.923 ms/op
                 listUser·p0.50:   5.734 ms/op
                 listUser·p0.90:   8.315 ms/op
                 listUser·p0.95:   9.421 ms/op
                 listUser·p0.99:   12.337 ms/op
                 listUser·p0.999:  25.592 ms/op
                 listUser·p0.9999: 30.041 ms/op
                 listUser·p1.00:   34.996 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 154528
  mean =      6.220 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 101 
    [ 2.500,  5.000) = 32982 
    [ 5.000,  7.500) = 93929 
    [ 7.500, 10.000) = 21967 
    [10.000, 12.500) = 4296 
    [12.500, 15.000) = 751 
    [15.000, 17.500) = 186 
    [17.500, 20.000) = 102 
    [20.000, 22.500) = 76 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 29 
    [27.500, 30.000) = 45 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.612 ms/op
     p(50.0000) =      5.825 ms/op
     p(90.0000) =      8.421 ms/op
     p(95.0000) =      9.486 ms/op
     p(99.0000) =     12.124 ms/op
     p(99.9000) =     21.689 ms/op
     p(99.9900) =     30.477 ms/op
     p(99.9990) =     34.925 ms/op
     p(99.9999) =     34.996 ms/op
    p(100.0000) =     34.996 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   6.694 ± 3.632  ops/ms
ClientGrpc.existUser                       thrpt       3   7.088 ± 2.215  ops/ms
ClientGrpc.getUser                         thrpt       3   6.860 ± 1.271  ops/ms
ClientGrpc.listUser                        thrpt       3   5.056 ± 1.193  ops/ms
ClientGrpc.createUser                       avgt       3   4.646 ± 0.280   ms/op
ClientGrpc.existUser                        avgt       3   4.340 ± 1.171   ms/op
ClientGrpc.getUser                          avgt       3   4.687 ± 1.478   ms/op
ClientGrpc.listUser                         avgt       3   6.255 ± 0.472   ms/op
ClientGrpc.createUser                     sample  207274   4.629 ± 0.010   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.427           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.473           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.997           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.676           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           9.159           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          14.725           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          44.273           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          47.645           ms/op
ClientGrpc.existUser                      sample  219630   4.370 ± 0.009   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.787           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.211           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.497           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           6.259           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           8.618           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          14.336           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          26.186           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          37.224           ms/op
ClientGrpc.getUser                        sample  197389   4.862 ± 0.011   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.963           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.637           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           6.390           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           7.348           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           9.634           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          15.149           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          35.538           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          36.372           ms/op
ClientGrpc.listUser                       sample  154528   6.220 ± 0.015   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.612           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.825           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           8.421           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           9.486           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          12.124           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          21.689           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          30.477           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          34.996           ms/op
