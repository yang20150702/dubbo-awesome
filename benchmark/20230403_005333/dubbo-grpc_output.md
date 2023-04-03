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
# Warmup Iteration   1: 3.134 ops/ms
# Warmup Iteration   2: 6.295 ops/ms
# Warmup Iteration   3: 8.351 ops/ms
Iteration   1: 8.784 ops/ms
Iteration   2: 9.033 ops/ms
Iteration   3: 8.985 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.934 ±(99.9%) 2.408 ops/ms [Average]
  (min, avg, max) = (8.784, 8.934, 9.033), stdev = 0.132
  CI (99.9%): [6.525, 11.342] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.808 ops/ms
# Warmup Iteration   2: 8.991 ops/ms
# Warmup Iteration   3: 9.307 ops/ms
Iteration   1: 9.247 ops/ms
Iteration   2: 9.451 ops/ms
Iteration   3: 9.637 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.445 ±(99.9%) 3.556 ops/ms [Average]
  (min, avg, max) = (9.247, 9.445, 9.637), stdev = 0.195
  CI (99.9%): [5.890, 13.001] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.438 ops/ms
# Warmup Iteration   2: 8.385 ops/ms
# Warmup Iteration   3: 8.699 ops/ms
Iteration   1: 8.863 ops/ms
Iteration   2: 8.775 ops/ms
Iteration   3: 8.611 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.750 ±(99.9%) 2.331 ops/ms [Average]
  (min, avg, max) = (8.611, 8.750, 8.863), stdev = 0.128
  CI (99.9%): [6.419, 11.081] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 4.572 ops/ms
# Warmup Iteration   2: 6.273 ops/ms
# Warmup Iteration   3: 6.822 ops/ms
Iteration   1: 6.736 ops/ms
Iteration   2: 6.806 ops/ms
Iteration   3: 6.931 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.824 ±(99.9%) 1.809 ops/ms [Average]
  (min, avg, max) = (6.736, 6.824, 6.931), stdev = 0.099
  CI (99.9%): [5.015, 8.634] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 5.133 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.853 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.595 ±(99.9%) 0.005 ms/op
Iteration   1: 3.584 ±(99.9%) 0.006 ms/op
Iteration   2: 3.595 ±(99.9%) 0.005 ms/op
Iteration   3: 3.587 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.589 ±(99.9%) 0.106 ms/op [Average]
  (min, avg, max) = (3.584, 3.589, 3.595), stdev = 0.006
  CI (99.9%): [3.483, 3.694] (assumes normal distribution)


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
# Warmup Iteration   1: 4.689 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.577 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.427 ±(99.9%) 0.004 ms/op
Iteration   1: 3.433 ±(99.9%) 0.003 ms/op
Iteration   2: 3.367 ±(99.9%) 0.003 ms/op
Iteration   3: 3.433 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.411 ±(99.9%) 0.691 ms/op [Average]
  (min, avg, max) = (3.367, 3.411, 3.433), stdev = 0.038
  CI (99.9%): [2.720, 4.102] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.037 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.837 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.675 ±(99.9%) 0.005 ms/op
Iteration   1: 3.687 ±(99.9%) 0.003 ms/op
Iteration   2: 3.543 ±(99.9%) 0.003 ms/op
Iteration   3: 3.603 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.611 ±(99.9%) 1.314 ms/op [Average]
  (min, avg, max) = (3.543, 3.611, 3.687), stdev = 0.072
  CI (99.9%): [2.297, 4.925] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 6.162 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.989 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.730 ±(99.9%) 0.018 ms/op
Iteration   1: 4.655 ±(99.9%) 0.008 ms/op
Iteration   2: 4.667 ±(99.9%) 0.017 ms/op
Iteration   3: 4.748 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.690 ±(99.9%) 0.928 ms/op [Average]
  (min, avg, max) = (4.655, 4.690, 4.748), stdev = 0.051
  CI (99.9%): [3.761, 5.618] (assumes normal distribution)


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
# Warmup Iteration   1: 4.842 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 3.784 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.555 ±(99.9%) 0.008 ms/op
Iteration   1: 3.560 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.869 ms/op
                 createUser·p0.50:   3.506 ms/op
                 createUser·p0.90:   4.149 ms/op
                 createUser·p0.95:   4.497 ms/op
                 createUser·p0.99:   5.440 ms/op
                 createUser·p0.999:  11.207 ms/op
                 createUser·p0.9999: 23.036 ms/op
                 createUser·p1.00:   23.757 ms/op

Iteration   2: 3.511 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.841 ms/op
                 createUser·p0.50:   3.486 ms/op
                 createUser·p0.90:   4.092 ms/op
                 createUser·p0.95:   4.350 ms/op
                 createUser·p0.99:   5.456 ms/op
                 createUser·p0.999:  7.719 ms/op
                 createUser·p0.9999: 15.577 ms/op
                 createUser·p1.00:   16.335 ms/op

Iteration   3: 3.524 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.621 ms/op
                 createUser·p0.50:   3.490 ms/op
                 createUser·p0.90:   4.067 ms/op
                 createUser·p0.95:   4.424 ms/op
                 createUser·p0.99:   5.423 ms/op
                 createUser·p0.999:  14.357 ms/op
                 createUser·p0.9999: 33.053 ms/op
                 createUser·p1.00:   33.882 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 271961
  mean =      3.532 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7963 
    [ 2.500,  5.000) = 259518 
    [ 5.000,  7.500) = 3898 
    [ 7.500, 10.000) = 223 
    [10.000, 12.500) = 135 
    [12.500, 15.000) = 105 
    [15.000, 17.500) = 46 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 26 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.621 ms/op
     p(50.0000) =      3.494 ms/op
     p(90.0000) =      4.100 ms/op
     p(95.0000) =      4.424 ms/op
     p(99.0000) =      5.439 ms/op
     p(99.9000) =     11.191 ms/op
     p(99.9900) =     32.427 ms/op
     p(99.9990) =     33.358 ms/op
     p(99.9999) =     33.882 ms/op
    p(100.0000) =     33.882 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 5.088 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.625 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.438 ±(99.9%) 0.008 ms/op
Iteration   1: 3.433 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.805 ms/op
                 existUser·p0.50:   3.408 ms/op
                 existUser·p0.90:   4.067 ms/op
                 existUser·p0.95:   4.366 ms/op
                 existUser·p0.99:   5.439 ms/op
                 existUser·p0.999:  7.502 ms/op
                 existUser·p0.9999: 21.858 ms/op
                 existUser·p1.00:   23.101 ms/op

Iteration   2: 3.428 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.911 ms/op
                 existUser·p0.50:   3.404 ms/op
                 existUser·p0.90:   3.940 ms/op
                 existUser·p0.95:   4.145 ms/op
                 existUser·p0.99:   5.276 ms/op
                 existUser·p0.999:  11.143 ms/op
                 existUser·p0.9999: 16.182 ms/op
                 existUser·p1.00:   18.612 ms/op

Iteration   3: 3.403 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.763 ms/op
                 existUser·p0.50:   3.375 ms/op
                 existUser·p0.90:   3.867 ms/op
                 existUser·p0.95:   4.133 ms/op
                 existUser·p0.99:   5.186 ms/op
                 existUser·p0.999:  7.471 ms/op
                 existUser·p0.9999: 20.303 ms/op
                 existUser·p1.00:   20.677 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 280472
  mean =      3.421 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10323 
    [ 2.500,  5.000) = 266232 
    [ 5.000,  7.500) = 3558 
    [ 7.500, 10.000) = 97 
    [10.000, 12.500) = 95 
    [12.500, 15.000) = 41 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.763 ms/op
     p(50.0000) =      3.396 ms/op
     p(90.0000) =      3.957 ms/op
     p(95.0000) =      4.227 ms/op
     p(99.0000) =      5.325 ms/op
     p(99.9000) =      8.423 ms/op
     p(99.9900) =     21.296 ms/op
     p(99.9990) =     22.910 ms/op
     p(99.9999) =     23.101 ms/op
    p(100.0000) =     23.101 ms/op


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
# Warmup Iteration   1: 5.275 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 3.776 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.573 ±(99.9%) 0.008 ms/op
Iteration   1: 3.597 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.758 ms/op
                 getUser·p0.50:   3.547 ms/op
                 getUser·p0.90:   4.211 ms/op
                 getUser·p0.95:   4.489 ms/op
                 getUser·p0.99:   5.439 ms/op
                 getUser·p0.999:  12.837 ms/op
                 getUser·p0.9999: 21.823 ms/op
                 getUser·p1.00:   22.053 ms/op

Iteration   2: 3.599 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.868 ms/op
                 getUser·p0.50:   3.555 ms/op
                 getUser·p0.90:   4.174 ms/op
                 getUser·p0.95:   4.456 ms/op
                 getUser·p0.99:   5.202 ms/op
                 getUser·p0.999:  9.080 ms/op
                 getUser·p0.9999: 18.505 ms/op
                 getUser·p1.00:   19.825 ms/op

Iteration   3: 3.655 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.059 ms/op
                 getUser·p0.50:   3.600 ms/op
                 getUser·p0.90:   4.375 ms/op
                 getUser·p0.95:   4.620 ms/op
                 getUser·p0.99:   5.480 ms/op
                 getUser·p0.999:  7.764 ms/op
                 getUser·p0.9999: 20.684 ms/op
                 getUser·p1.00:   20.775 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 265423
  mean =      3.617 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5356 
    [ 2.500,  5.000) = 255528 
    [ 5.000,  7.500) = 4083 
    [ 7.500, 10.000) = 230 
    [10.000, 12.500) = 19 
    [12.500, 15.000) = 45 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 51 
    [20.000, 22.500) = 79 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.758 ms/op
     p(50.0000) =      3.564 ms/op
     p(90.0000) =      4.260 ms/op
     p(95.0000) =      4.538 ms/op
     p(99.0000) =      5.390 ms/op
     p(99.9000) =      8.864 ms/op
     p(99.9900) =     21.576 ms/op
     p(99.9990) =     21.966 ms/op
     p(99.9999) =     22.053 ms/op
    p(100.0000) =     22.053 ms/op


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
# Warmup Iteration   1: 6.335 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 4.943 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.700 ±(99.9%) 0.013 ms/op
Iteration   1: 4.716 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.671 ms/op
                 listUser·p0.50:   4.547 ms/op
                 listUser·p0.90:   5.759 ms/op
                 listUser·p0.95:   6.603 ms/op
                 listUser·p0.99:   8.249 ms/op
                 listUser·p0.999:  13.829 ms/op
                 listUser·p0.9999: 16.355 ms/op
                 listUser·p1.00:   16.974 ms/op

Iteration   2: 4.696 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.321 ms/op
                 listUser·p0.50:   4.555 ms/op
                 listUser·p0.90:   5.259 ms/op
                 listUser·p0.95:   6.218 ms/op
                 listUser·p0.99:   8.126 ms/op
                 listUser·p0.999:  17.200 ms/op
                 listUser·p0.9999: 23.448 ms/op
                 listUser·p1.00:   23.822 ms/op

Iteration   3: 4.705 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.196 ms/op
                 listUser·p0.50:   4.538 ms/op
                 listUser·p0.90:   5.612 ms/op
                 listUser·p0.95:   6.373 ms/op
                 listUser·p0.99:   8.028 ms/op
                 listUser·p0.999:  17.877 ms/op
                 listUser·p0.9999: 30.481 ms/op
                 listUser·p1.00:   31.982 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 203952
  mean =      4.706 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 226 
    [ 2.500,  5.000) = 165335 
    [ 5.000,  7.500) = 34350 
    [ 7.500, 10.000) = 3535 
    [10.000, 12.500) = 150 
    [12.500, 15.000) = 109 
    [15.000, 17.500) = 119 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 8 
    [30.000, 32.500) = 24 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.671 ms/op
     p(50.0000) =      4.547 ms/op
     p(90.0000) =      5.546 ms/op
     p(95.0000) =      6.423 ms/op
     p(99.0000) =      8.135 ms/op
     p(99.9000) =     16.304 ms/op
     p(99.9900) =     30.278 ms/op
     p(99.9990) =     31.974 ms/op
     p(99.9999) =     31.982 ms/op
    p(100.0000) =     31.982 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.934 ± 2.408  ops/ms
ClientGrpc.existUser                       thrpt       3   9.445 ± 3.556  ops/ms
ClientGrpc.getUser                         thrpt       3   8.750 ± 2.331  ops/ms
ClientGrpc.listUser                        thrpt       3   6.824 ± 1.809  ops/ms
ClientGrpc.createUser                       avgt       3   3.589 ± 0.106   ms/op
ClientGrpc.existUser                        avgt       3   3.411 ± 0.691   ms/op
ClientGrpc.getUser                          avgt       3   3.611 ± 1.314   ms/op
ClientGrpc.listUser                         avgt       3   4.690 ± 0.928   ms/op
ClientGrpc.createUser                     sample  271961   3.532 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.621           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.494           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.100           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.424           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.439           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.191           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          32.427           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          33.882           ms/op
ClientGrpc.existUser                      sample  280472   3.421 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.763           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.396           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.957           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.227           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.325           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.423           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.296           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.101           ms/op
ClientGrpc.getUser                        sample  265423   3.617 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.758           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.564           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.260           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.538           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.390           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.864           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.576           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.053           ms/op
ClientGrpc.listUser                       sample  203952   4.706 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.671           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.547           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.546           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.423           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.135           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.304           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          30.278           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          31.982           ms/op
