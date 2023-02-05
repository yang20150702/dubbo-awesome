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
# Warmup Iteration   1: 2.398 ops/ms
# Warmup Iteration   2: 5.960 ops/ms
# Warmup Iteration   3: 7.206 ops/ms
Iteration   1: 8.123 ops/ms
Iteration   2: 7.672 ops/ms
Iteration   3: 7.478 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.758 ±(99.9%) 6.040 ops/ms [Average]
  (min, avg, max) = (7.478, 7.758, 8.123), stdev = 0.331
  CI (99.9%): [1.717, 13.798] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 5.514 ops/ms
# Warmup Iteration   2: 7.804 ops/ms
# Warmup Iteration   3: 8.021 ops/ms
Iteration   1: 7.738 ops/ms
Iteration   2: 8.071 ops/ms
Iteration   3: 7.968 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.926 ±(99.9%) 3.105 ops/ms [Average]
  (min, avg, max) = (7.738, 7.926, 8.071), stdev = 0.170
  CI (99.9%): [4.821, 11.030] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 4.527 ops/ms
# Warmup Iteration   2: 7.253 ops/ms
# Warmup Iteration   3: 7.275 ops/ms
Iteration   1: 7.357 ops/ms
Iteration   2: 7.676 ops/ms
Iteration   3: 7.581 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.538 ±(99.9%) 2.988 ops/ms [Average]
  (min, avg, max) = (7.357, 7.538, 7.676), stdev = 0.164
  CI (99.9%): [4.550, 10.526] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 4.276 ops/ms
# Warmup Iteration   2: 5.470 ops/ms
# Warmup Iteration   3: 5.948 ops/ms
Iteration   1: 6.223 ops/ms
Iteration   2: 6.143 ops/ms
Iteration   3: 6.173 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.180 ±(99.9%) 0.741 ops/ms [Average]
  (min, avg, max) = (6.143, 6.180, 6.223), stdev = 0.041
  CI (99.9%): [5.438, 6.921] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.184 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.270 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.263 ±(99.9%) 0.019 ms/op
Iteration   1: 4.327 ±(99.9%) 0.002 ms/op
Iteration   2: 4.496 ±(99.9%) 0.002 ms/op
Iteration   3: 4.534 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.452 ±(99.9%) 2.011 ms/op [Average]
  (min, avg, max) = (4.327, 4.452, 4.534), stdev = 0.110
  CI (99.9%): [2.442, 6.463] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 5.774 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 4.492 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.371 ±(99.9%) 0.003 ms/op
Iteration   1: 4.080 ±(99.9%) 0.003 ms/op
Iteration   2: 3.989 ±(99.9%) 0.002 ms/op
Iteration   3: 3.885 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.985 ±(99.9%) 1.781 ms/op [Average]
  (min, avg, max) = (3.885, 3.985, 4.080), stdev = 0.098
  CI (99.9%): [2.204, 5.766] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 6.482 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.438 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.332 ±(99.9%) 0.003 ms/op
Iteration   1: 4.248 ±(99.9%) 0.003 ms/op
Iteration   2: 4.285 ±(99.9%) 0.002 ms/op
Iteration   3: 4.290 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.274 ±(99.9%) 0.423 ms/op [Average]
  (min, avg, max) = (4.248, 4.274, 4.290), stdev = 0.023
  CI (99.9%): [3.851, 4.697] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 7.912 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 5.365 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 5.234 ±(99.9%) 0.008 ms/op
Iteration   1: 5.191 ±(99.9%) 0.010 ms/op
Iteration   2: 5.429 ±(99.9%) 0.011 ms/op
Iteration   3: 5.413 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.344 ±(99.9%) 2.429 ms/op [Average]
  (min, avg, max) = (5.191, 5.344, 5.429), stdev = 0.133
  CI (99.9%): [2.916, 7.773] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 6.313 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 4.646 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.355 ±(99.9%) 0.014 ms/op
Iteration   1: 4.340 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.981 ms/op
                 createUser·p0.50:   4.219 ms/op
                 createUser·p0.90:   5.505 ms/op
                 createUser·p0.95:   5.980 ms/op
                 createUser·p0.99:   7.907 ms/op
                 createUser·p0.999:  13.113 ms/op
                 createUser·p0.9999: 17.298 ms/op
                 createUser·p1.00:   18.088 ms/op

Iteration   2: 4.562 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.126 ms/op
                 createUser·p0.50:   4.514 ms/op
                 createUser·p0.90:   5.841 ms/op
                 createUser·p0.95:   6.201 ms/op
                 createUser·p0.99:   7.086 ms/op
                 createUser·p0.999:  10.894 ms/op
                 createUser·p0.9999: 18.514 ms/op
                 createUser·p1.00:   18.743 ms/op

Iteration   3: 4.280 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.927 ms/op
                 createUser·p0.50:   4.190 ms/op
                 createUser·p0.90:   5.210 ms/op
                 createUser·p0.95:   5.628 ms/op
                 createUser·p0.99:   7.102 ms/op
                 createUser·p0.999:  13.107 ms/op
                 createUser·p0.9999: 21.480 ms/op
                 createUser·p1.00:   22.413 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 218503
  mean =      4.391 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3342 
    [ 2.500,  5.000) = 166650 
    [ 5.000,  7.500) = 46522 
    [ 7.500, 10.000) = 1411 
    [10.000, 12.500) = 335 
    [12.500, 15.000) = 116 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 68 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.927 ms/op
     p(50.0000) =      4.284 ms/op
     p(90.0000) =      5.562 ms/op
     p(95.0000) =      6.005 ms/op
     p(99.0000) =      7.372 ms/op
     p(99.9000) =     12.829 ms/op
     p(99.9900) =     20.414 ms/op
     p(99.9990) =     22.381 ms/op
     p(99.9999) =     22.413 ms/op
    p(100.0000) =     22.413 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.731 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 4.326 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.046 ±(99.9%) 0.011 ms/op
Iteration   1: 4.238 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.925 ms/op
                 existUser·p0.50:   4.166 ms/op
                 existUser·p0.90:   5.399 ms/op
                 existUser·p0.95:   5.759 ms/op
                 existUser·p0.99:   6.852 ms/op
                 existUser·p0.999:  9.617 ms/op
                 existUser·p0.9999: 20.021 ms/op
                 existUser·p1.00:   21.561 ms/op

Iteration   2: 4.228 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.760 ms/op
                 existUser·p0.50:   4.153 ms/op
                 existUser·p0.90:   5.341 ms/op
                 existUser·p0.95:   5.677 ms/op
                 existUser·p0.99:   6.586 ms/op
                 existUser·p0.999:  12.141 ms/op
                 existUser·p0.9999: 36.372 ms/op
                 existUser·p1.00:   36.700 ms/op

Iteration   3: 4.079 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.145 ms/op
                 existUser·p0.50:   4.006 ms/op
                 existUser·p0.90:   5.226 ms/op
                 existUser·p0.95:   5.587 ms/op
                 existUser·p0.99:   6.726 ms/op
                 existUser·p0.999:  10.256 ms/op
                 existUser·p0.9999: 24.740 ms/op
                 existUser·p1.00:   24.936 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 229476
  mean =      4.180 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6494 
    [ 2.500,  5.000) = 183070 
    [ 5.000,  7.500) = 38679 
    [ 7.500, 10.000) = 968 
    [10.000, 12.500) = 129 
    [12.500, 15.000) = 10 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 9 
    [27.500, 30.000) = 23 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 12 
    [35.000, 37.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.760 ms/op
     p(50.0000) =      4.108 ms/op
     p(90.0000) =      5.325 ms/op
     p(95.0000) =      5.685 ms/op
     p(99.0000) =      6.717 ms/op
     p(99.9000) =     10.412 ms/op
     p(99.9900) =     34.741 ms/op
     p(99.9990) =     36.635 ms/op
     p(99.9999) =     36.700 ms/op
    p(100.0000) =     36.700 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 6.144 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 4.415 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.177 ±(99.9%) 0.013 ms/op
Iteration   1: 4.228 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.149 ms/op
                 getUser·p0.50:   4.100 ms/op
                 getUser·p0.90:   5.464 ms/op
                 getUser·p0.95:   5.825 ms/op
                 getUser·p0.99:   6.971 ms/op
                 getUser·p0.999:  9.208 ms/op
                 getUser·p0.9999: 19.337 ms/op
                 getUser·p1.00:   19.956 ms/op

Iteration   2: 4.338 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.921 ms/op
                 getUser·p0.50:   4.268 ms/op
                 getUser·p0.90:   5.513 ms/op
                 getUser·p0.95:   5.865 ms/op
                 getUser·p0.99:   7.078 ms/op
                 getUser·p0.999:  10.865 ms/op
                 getUser·p0.9999: 17.498 ms/op
                 getUser·p1.00:   17.793 ms/op

Iteration   3: 4.126 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.951 ms/op
                 getUser·p0.50:   4.055 ms/op
                 getUser·p0.90:   5.235 ms/op
                 getUser·p0.95:   5.612 ms/op
                 getUser·p0.99:   6.791 ms/op
                 getUser·p0.999:  12.237 ms/op
                 getUser·p0.9999: 22.306 ms/op
                 getUser·p1.00:   23.265 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 227166
  mean =      4.229 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4324 
    [ 2.500,  5.000) = 178990 
    [ 5.000,  7.500) = 42379 
    [ 7.500, 10.000) = 1177 
    [10.000, 12.500) = 159 
    [12.500, 15.000) = 15 
    [15.000, 17.500) = 71 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.921 ms/op
     p(50.0000) =      4.133 ms/op
     p(90.0000) =      5.415 ms/op
     p(95.0000) =      5.784 ms/op
     p(99.0000) =      6.955 ms/op
     p(99.9000) =     10.630 ms/op
     p(99.9900) =     21.299 ms/op
     p(99.9990) =     23.090 ms/op
     p(99.9999) =     23.265 ms/op
    p(100.0000) =     23.265 ms/op


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
# Warmup Iteration   1: 6.896 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 5.760 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 5.202 ±(99.9%) 0.017 ms/op
Iteration   1: 5.114 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.970 ms/op
                 listUser·p0.50:   4.907 ms/op
                 listUser·p0.90:   6.537 ms/op
                 listUser·p0.95:   7.463 ms/op
                 listUser·p0.99:   9.765 ms/op
                 listUser·p0.999:  15.712 ms/op
                 listUser·p0.9999: 24.043 ms/op
                 listUser·p1.00:   24.838 ms/op

Iteration   2: 5.419 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.368 ms/op
                 listUser·p0.50:   5.169 ms/op
                 listUser·p0.90:   7.053 ms/op
                 listUser·p0.95:   7.782 ms/op
                 listUser·p0.99:   9.470 ms/op
                 listUser·p0.999:  17.661 ms/op
                 listUser·p0.9999: 24.120 ms/op
                 listUser·p1.00:   25.035 ms/op

Iteration   3: 5.284 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.726 ms/op
                 listUser·p0.50:   5.054 ms/op
                 listUser·p0.90:   6.849 ms/op
                 listUser·p0.95:   7.692 ms/op
                 listUser·p0.99:   9.486 ms/op
                 listUser·p0.999:  21.216 ms/op
                 listUser·p0.9999: 25.033 ms/op
                 listUser·p1.00:   28.180 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 182069
  mean =      5.269 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 245 
    [ 2.500,  5.000) = 87738 
    [ 5.000,  7.500) = 83536 
    [ 7.500, 10.000) = 9170 
    [10.000, 12.500) = 938 
    [12.500, 15.000) = 157 
    [15.000, 17.500) = 79 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 68 
    [22.500, 25.000) = 81 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.368 ms/op
     p(50.0000) =      5.038 ms/op
     p(90.0000) =      6.840 ms/op
     p(95.0000) =      7.660 ms/op
     p(99.0000) =      9.585 ms/op
     p(99.9000) =     18.542 ms/op
     p(99.9900) =     24.668 ms/op
     p(99.9990) =     28.073 ms/op
     p(99.9999) =     28.180 ms/op
    p(100.0000) =     28.180 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.758 ± 6.040  ops/ms
ClientGrpc.existUser                       thrpt       3   7.926 ± 3.105  ops/ms
ClientGrpc.getUser                         thrpt       3   7.538 ± 2.988  ops/ms
ClientGrpc.listUser                        thrpt       3   6.180 ± 0.741  ops/ms
ClientGrpc.createUser                       avgt       3   4.452 ± 2.011   ms/op
ClientGrpc.existUser                        avgt       3   3.985 ± 1.781   ms/op
ClientGrpc.getUser                          avgt       3   4.274 ± 0.423   ms/op
ClientGrpc.listUser                         avgt       3   5.344 ± 2.429   ms/op
ClientGrpc.createUser                     sample  218503   4.391 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.927           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.284           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.562           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.005           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.372           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.829           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.414           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.413           ms/op
ClientGrpc.existUser                      sample  229476   4.180 ± 0.008   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.760           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.108           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.325           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.685           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.717           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.412           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          34.741           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          36.700           ms/op
ClientGrpc.getUser                        sample  227166   4.229 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.921           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.133           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.415           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.784           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.955           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.630           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.299           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.265           ms/op
ClientGrpc.listUser                       sample  182069   5.269 ± 0.011   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.368           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.038           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.840           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.660           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.585           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.542           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.668           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.180           ms/op
