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
# Warmup Iteration   1: 4.002 ops/ms
# Warmup Iteration   2: 9.031 ops/ms
# Warmup Iteration   3: 9.961 ops/ms
Iteration   1: 10.723 ops/ms
Iteration   2: 10.526 ops/ms
Iteration   3: 10.300 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.516 ±(99.9%) 3.866 ops/ms [Average]
  (min, avg, max) = (10.300, 10.516, 10.723), stdev = 0.212
  CI (99.9%): [6.650, 14.382] (assumes normal distribution)


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
# Warmup Iteration   1: 7.040 ops/ms
# Warmup Iteration   2: 10.305 ops/ms
# Warmup Iteration   3: 11.059 ops/ms
Iteration   1: 11.218 ops/ms
Iteration   2: 11.106 ops/ms
Iteration   3: 10.815 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.047 ±(99.9%) 3.803 ops/ms [Average]
  (min, avg, max) = (10.815, 11.047, 11.218), stdev = 0.208
  CI (99.9%): [7.243, 14.850] (assumes normal distribution)


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
# Warmup Iteration   1: 7.198 ops/ms
# Warmup Iteration   2: 10.138 ops/ms
# Warmup Iteration   3: 10.173 ops/ms
Iteration   1: 10.447 ops/ms
Iteration   2: 10.319 ops/ms
Iteration   3: 10.289 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.352 ±(99.9%) 1.528 ops/ms [Average]
  (min, avg, max) = (10.289, 10.352, 10.447), stdev = 0.084
  CI (99.9%): [8.823, 11.880] (assumes normal distribution)


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
# Warmup Iteration   1: 5.529 ops/ms
# Warmup Iteration   2: 7.619 ops/ms
# Warmup Iteration   3: 7.856 ops/ms
Iteration   1: 7.942 ops/ms
Iteration   2: 7.873 ops/ms
Iteration   3: 8.063 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.959 ±(99.9%) 1.755 ops/ms [Average]
  (min, avg, max) = (7.873, 7.959, 8.063), stdev = 0.096
  CI (99.9%): [6.204, 9.715] (assumes normal distribution)


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
# Warmup Iteration   1: 4.268 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.233 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.105 ±(99.9%) 0.003 ms/op
Iteration   1: 3.088 ±(99.9%) 0.003 ms/op
Iteration   2: 3.084 ±(99.9%) 0.003 ms/op
Iteration   3: 3.073 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.082 ±(99.9%) 0.139 ms/op [Average]
  (min, avg, max) = (3.073, 3.082, 3.088), stdev = 0.008
  CI (99.9%): [2.943, 3.221] (assumes normal distribution)


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
# Warmup Iteration   1: 4.232 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.060 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 2.944 ±(99.9%) 0.003 ms/op
Iteration   1: 2.952 ±(99.9%) 0.002 ms/op
Iteration   2: 2.928 ±(99.9%) 0.002 ms/op
Iteration   3: 2.985 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.955 ±(99.9%) 0.523 ms/op [Average]
  (min, avg, max) = (2.928, 2.955, 2.985), stdev = 0.029
  CI (99.9%): [2.432, 3.478] (assumes normal distribution)


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
# Warmup Iteration   1: 4.233 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.160 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.102 ±(99.9%) 0.003 ms/op
Iteration   1: 3.085 ±(99.9%) 0.003 ms/op
Iteration   2: 3.076 ±(99.9%) 0.003 ms/op
Iteration   3: 3.114 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.092 ±(99.9%) 0.362 ms/op [Average]
  (min, avg, max) = (3.076, 3.092, 3.114), stdev = 0.020
  CI (99.9%): [2.729, 3.454] (assumes normal distribution)


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
# Warmup Iteration   1: 5.280 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.250 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.114 ±(99.9%) 0.010 ms/op
Iteration   1: 4.096 ±(99.9%) 0.013 ms/op
Iteration   2: 4.120 ±(99.9%) 0.019 ms/op
Iteration   3: 4.125 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.114 ±(99.9%) 0.283 ms/op [Average]
  (min, avg, max) = (4.096, 4.114, 4.125), stdev = 0.016
  CI (99.9%): [3.831, 4.397] (assumes normal distribution)


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
# Warmup Iteration   1: 4.523 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.247 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.126 ±(99.9%) 0.007 ms/op
Iteration   1: 3.048 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.565 ms/op
                 createUser·p0.50:   3.035 ms/op
                 createUser·p0.90:   3.453 ms/op
                 createUser·p0.95:   3.641 ms/op
                 createUser·p0.99:   4.145 ms/op
                 createUser·p0.999:  6.693 ms/op
                 createUser·p0.9999: 19.660 ms/op
                 createUser·p1.00:   19.825 ms/op

Iteration   2: 3.104 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.751 ms/op
                 createUser·p0.50:   3.076 ms/op
                 createUser·p0.90:   3.613 ms/op
                 createUser·p0.95:   3.793 ms/op
                 createUser·p0.99:   4.325 ms/op
                 createUser·p0.999:  7.479 ms/op
                 createUser·p0.9999: 20.765 ms/op
                 createUser·p1.00:   21.332 ms/op

Iteration   3: 3.072 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.869 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.576 ms/op
                 createUser·p0.95:   3.740 ms/op
                 createUser·p0.99:   4.473 ms/op
                 createUser·p0.999:  13.126 ms/op
                 createUser·p0.9999: 25.840 ms/op
                 createUser·p1.00:   26.411 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 312349
  mean =      3.075 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16180 
    [ 2.500,  5.000) = 294661 
    [ 5.000,  7.500) = 1173 
    [ 7.500, 10.000) = 79 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 49 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 110 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.565 ms/op
     p(50.0000) =      3.052 ms/op
     p(90.0000) =      3.555 ms/op
     p(95.0000) =      3.736 ms/op
     p(99.0000) =      4.309 ms/op
     p(99.9000) =      7.777 ms/op
     p(99.9900) =     24.084 ms/op
     p(99.9990) =     26.264 ms/op
     p(99.9999) =     26.411 ms/op
    p(100.0000) =     26.411 ms/op


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
# Warmup Iteration   1: 4.295 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.083 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.963 ±(99.9%) 0.005 ms/op
Iteration   1: 2.941 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.903 ms/op
                 existUser·p0.50:   2.916 ms/op
                 existUser·p0.90:   3.326 ms/op
                 existUser·p0.95:   3.514 ms/op
                 existUser·p0.99:   3.985 ms/op
                 existUser·p0.999:  7.299 ms/op
                 existUser·p0.9999: 19.664 ms/op
                 existUser·p1.00:   20.087 ms/op

Iteration   2: 2.988 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.768 ms/op
                 existUser·p0.50:   2.970 ms/op
                 existUser·p0.90:   3.510 ms/op
                 existUser·p0.95:   3.690 ms/op
                 existUser·p0.99:   4.156 ms/op
                 existUser·p0.999:  6.150 ms/op
                 existUser·p0.9999: 14.645 ms/op
                 existUser·p1.00:   14.991 ms/op

Iteration   3: 2.990 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.830 ms/op
                 existUser·p0.50:   2.953 ms/op
                 existUser·p0.90:   3.559 ms/op
                 existUser·p0.95:   3.740 ms/op
                 existUser·p0.99:   4.170 ms/op
                 existUser·p0.999:  6.776 ms/op
                 existUser·p0.9999: 26.890 ms/op
                 existUser·p1.00:   27.230 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 322932
  mean =      2.973 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27913 
    [ 2.500,  5.000) = 294224 
    [ 5.000,  7.500) = 582 
    [ 7.500, 10.000) = 21 
    [10.000, 12.500) = 60 
    [12.500, 15.000) = 41 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.768 ms/op
     p(50.0000) =      2.945 ms/op
     p(90.0000) =      3.465 ms/op
     p(95.0000) =      3.678 ms/op
     p(99.0000) =      4.112 ms/op
     p(99.9000) =      6.702 ms/op
     p(99.9900) =     24.278 ms/op
     p(99.9990) =     27.190 ms/op
     p(99.9999) =     27.230 ms/op
    p(100.0000) =     27.230 ms/op


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
# Warmup Iteration   1: 4.310 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.257 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.133 ±(99.9%) 0.006 ms/op
Iteration   1: 3.069 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.754 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.518 ms/op
                 getUser·p0.95:   3.740 ms/op
                 getUser·p0.99:   4.456 ms/op
                 getUser·p0.999:  7.869 ms/op
                 getUser·p0.9999: 15.925 ms/op
                 getUser·p1.00:   16.761 ms/op

Iteration   2: 3.048 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.720 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.547 ms/op
                 getUser·p0.95:   3.743 ms/op
                 getUser·p0.99:   4.407 ms/op
                 getUser·p0.999:  6.924 ms/op
                 getUser·p0.9999: 18.334 ms/op
                 getUser·p1.00:   19.137 ms/op

Iteration   3: 3.127 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.845 ms/op
                 getUser·p0.50:   3.092 ms/op
                 getUser·p0.90:   3.678 ms/op
                 getUser·p0.95:   3.875 ms/op
                 getUser·p0.99:   4.563 ms/op
                 getUser·p0.999:  8.763 ms/op
                 getUser·p0.9999: 34.406 ms/op
                 getUser·p1.00:   34.931 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 311417
  mean =      3.081 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17605 
    [ 2.500,  5.000) = 292155 
    [ 5.000,  7.500) = 1335 
    [ 7.500, 10.000) = 128 
    [10.000, 12.500) = 2 
    [12.500, 15.000) = 38 
    [15.000, 17.500) = 77 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 32 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.720 ms/op
     p(50.0000) =      3.064 ms/op
     p(90.0000) =      3.584 ms/op
     p(95.0000) =      3.793 ms/op
     p(99.0000) =      4.481 ms/op
     p(99.9000) =      7.574 ms/op
     p(99.9900) =     33.779 ms/op
     p(99.9990) =     34.800 ms/op
     p(99.9999) =     34.931 ms/op
    p(100.0000) =     34.931 ms/op


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
# Warmup Iteration   1: 5.322 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.341 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.107 ±(99.9%) 0.011 ms/op
Iteration   1: 4.112 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.280 ms/op
                 listUser·p0.50:   3.936 ms/op
                 listUser·p0.90:   5.218 ms/op
                 listUser·p0.95:   5.808 ms/op
                 listUser·p0.99:   7.176 ms/op
                 listUser·p0.999:  13.862 ms/op
                 listUser·p0.9999: 16.948 ms/op
                 listUser·p1.00:   17.170 ms/op

Iteration   2: 4.196 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.454 ms/op
                 listUser·p0.50:   3.994 ms/op
                 listUser·p0.90:   5.349 ms/op
                 listUser·p0.95:   5.841 ms/op
                 listUser·p0.99:   7.168 ms/op
                 listUser·p0.999:  14.902 ms/op
                 listUser·p0.9999: 16.636 ms/op
                 listUser·p1.00:   18.121 ms/op

Iteration   3: 4.152 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.038 ms/op
                 listUser·p0.50:   3.985 ms/op
                 listUser·p0.90:   5.292 ms/op
                 listUser·p0.95:   6.029 ms/op
                 listUser·p0.99:   7.193 ms/op
                 listUser·p0.999:  16.611 ms/op
                 listUser·p0.9999: 23.832 ms/op
                 listUser·p1.00:   24.216 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 231323
  mean =      4.153 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2145 
    [ 2.500,  5.000) = 196944 
    [ 5.000,  7.500) = 30611 
    [ 7.500, 10.000) = 1153 
    [10.000, 12.500) = 140 
    [12.500, 15.000) = 117 
    [15.000, 17.500) = 152 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.038 ms/op
     p(50.0000) =      3.969 ms/op
     p(90.0000) =      5.292 ms/op
     p(95.0000) =      5.898 ms/op
     p(99.0000) =      7.176 ms/op
     p(99.9000) =     14.729 ms/op
     p(99.9900) =     22.962 ms/op
     p(99.9990) =     24.173 ms/op
     p(99.9999) =     24.216 ms/op
    p(100.0000) =     24.216 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.516 ± 3.866  ops/ms
ClientGrpc.existUser                       thrpt       3  11.047 ± 3.803  ops/ms
ClientGrpc.getUser                         thrpt       3  10.352 ± 1.528  ops/ms
ClientGrpc.listUser                        thrpt       3   7.959 ± 1.755  ops/ms
ClientGrpc.createUser                       avgt       3   3.082 ± 0.139   ms/op
ClientGrpc.existUser                        avgt       3   2.955 ± 0.523   ms/op
ClientGrpc.getUser                          avgt       3   3.092 ± 0.362   ms/op
ClientGrpc.listUser                         avgt       3   4.114 ± 0.283   ms/op
ClientGrpc.createUser                     sample  312349   3.075 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.565           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.052           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.555           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.736           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.309           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.777           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.084           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.411           ms/op
ClientGrpc.existUser                      sample  322932   2.973 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.768           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.945           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.465           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.678           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.112           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.702           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          24.278           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          27.230           ms/op
ClientGrpc.getUser                        sample  311417   3.081 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.720           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.064           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.584           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.793           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.481           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.574           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          33.779           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          34.931           ms/op
ClientGrpc.listUser                       sample  231323   4.153 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.038           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.969           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.292           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.898           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.176           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.729           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.962           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.216           ms/op
