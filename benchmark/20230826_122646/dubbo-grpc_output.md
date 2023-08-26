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
# Warmup Iteration   1: 3.149 ops/ms
# Warmup Iteration   2: 6.521 ops/ms
# Warmup Iteration   3: 7.921 ops/ms
Iteration   1: 8.300 ops/ms
Iteration   2: 8.292 ops/ms
Iteration   3: 8.406 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.333 ±(99.9%) 1.166 ops/ms [Average]
  (min, avg, max) = (8.292, 8.333, 8.406), stdev = 0.064
  CI (99.9%): [7.167, 9.498] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 5.682 ops/ms
# Warmup Iteration   2: 8.394 ops/ms
# Warmup Iteration   3: 8.868 ops/ms
Iteration   1: 8.962 ops/ms
Iteration   2: 8.939 ops/ms
Iteration   3: 9.159 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.020 ±(99.9%) 2.202 ops/ms [Average]
  (min, avg, max) = (8.939, 9.020, 9.159), stdev = 0.121
  CI (99.9%): [6.818, 11.222] (assumes normal distribution)


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
# Warmup Iteration   1: 5.385 ops/ms
# Warmup Iteration   2: 7.939 ops/ms
# Warmup Iteration   3: 8.295 ops/ms
Iteration   1: 8.463 ops/ms
Iteration   2: 8.394 ops/ms
Iteration   3: 8.877 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.578 ±(99.9%) 4.770 ops/ms [Average]
  (min, avg, max) = (8.394, 8.578, 8.877), stdev = 0.261
  CI (99.9%): [3.808, 13.348] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 4.685 ops/ms
# Warmup Iteration   2: 5.875 ops/ms
# Warmup Iteration   3: 6.438 ops/ms
Iteration   1: 6.504 ops/ms
Iteration   2: 6.464 ops/ms
Iteration   3: 6.283 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.417 ±(99.9%) 2.155 ops/ms [Average]
  (min, avg, max) = (6.283, 6.417, 6.504), stdev = 0.118
  CI (99.9%): [4.262, 8.572] (assumes normal distribution)


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
# Warmup Iteration   1: 5.542 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.959 ±(99.9%) 0.044 ms/op
# Warmup Iteration   3: 3.882 ±(99.9%) 0.012 ms/op
Iteration   1: 3.768 ±(99.9%) 0.005 ms/op
Iteration   2: 3.776 ±(99.9%) 0.003 ms/op
Iteration   3: 3.813 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.786 ±(99.9%) 0.438 ms/op [Average]
  (min, avg, max) = (3.768, 3.786, 3.813), stdev = 0.024
  CI (99.9%): [3.348, 4.224] (assumes normal distribution)


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
# Warmup Iteration   1: 5.303 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.824 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.573 ±(99.9%) 0.004 ms/op
Iteration   1: 3.601 ±(99.9%) 0.003 ms/op
Iteration   2: 3.603 ±(99.9%) 0.003 ms/op
Iteration   3: 3.597 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.601 ±(99.9%) 0.056 ms/op [Average]
  (min, avg, max) = (3.597, 3.601, 3.603), stdev = 0.003
  CI (99.9%): [3.544, 3.657] (assumes normal distribution)


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
# Warmup Iteration   1: 5.397 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 4.026 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.825 ±(99.9%) 0.004 ms/op
Iteration   1: 3.852 ±(99.9%) 0.009 ms/op
Iteration   2: 3.812 ±(99.9%) 0.004 ms/op
Iteration   3: 3.768 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.811 ±(99.9%) 0.773 ms/op [Average]
  (min, avg, max) = (3.768, 3.811, 3.852), stdev = 0.042
  CI (99.9%): [3.037, 4.584] (assumes normal distribution)


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
# Warmup Iteration   1: 7.581 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 5.199 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 5.026 ±(99.9%) 0.021 ms/op
Iteration   1: 4.943 ±(99.9%) 0.015 ms/op
Iteration   2: 4.934 ±(99.9%) 0.009 ms/op
Iteration   3: 4.820 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.899 ±(99.9%) 1.254 ms/op [Average]
  (min, avg, max) = (4.820, 4.899, 4.943), stdev = 0.069
  CI (99.9%): [3.645, 6.153] (assumes normal distribution)


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
# Warmup Iteration   1: 5.784 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 4.175 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.876 ±(99.9%) 0.010 ms/op
Iteration   1: 3.892 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.147 ms/op
                 createUser·p0.50:   3.822 ms/op
                 createUser·p0.90:   4.661 ms/op
                 createUser·p0.95:   5.022 ms/op
                 createUser·p0.99:   6.332 ms/op
                 createUser·p0.999:  9.470 ms/op
                 createUser·p0.9999: 16.184 ms/op
                 createUser·p1.00:   16.548 ms/op

Iteration   2: 3.867 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.048 ms/op
                 createUser·p0.50:   3.777 ms/op
                 createUser·p0.90:   4.588 ms/op
                 createUser·p0.95:   4.973 ms/op
                 createUser·p0.99:   6.267 ms/op
                 createUser·p0.999:  13.308 ms/op
                 createUser·p0.9999: 17.603 ms/op
                 createUser·p1.00:   17.990 ms/op

Iteration   3: 3.928 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.793 ms/op
                 createUser·p0.50:   3.850 ms/op
                 createUser·p0.90:   4.669 ms/op
                 createUser·p0.95:   4.981 ms/op
                 createUser·p0.99:   6.259 ms/op
                 createUser·p0.999:  11.498 ms/op
                 createUser·p0.9999: 21.972 ms/op
                 createUser·p1.00:   22.381 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 246466
  mean =      3.895 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4719 
    [ 2.500,  5.000) = 229688 
    [ 5.000,  7.500) = 10993 
    [ 7.500, 10.000) = 806 
    [10.000, 12.500) = 46 
    [12.500, 15.000) = 57 
    [15.000, 17.500) = 102 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.793 ms/op
     p(50.0000) =      3.813 ms/op
     p(90.0000) =      4.645 ms/op
     p(95.0000) =      4.989 ms/op
     p(99.0000) =      6.283 ms/op
     p(99.9000) =     10.430 ms/op
     p(99.9900) =     21.027 ms/op
     p(99.9990) =     22.285 ms/op
     p(99.9999) =     22.381 ms/op
    p(100.0000) =     22.381 ms/op


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
# Warmup Iteration   1: 4.969 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.795 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.646 ±(99.9%) 0.008 ms/op
Iteration   1: 3.625 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.893 ms/op
                 existUser·p0.50:   3.564 ms/op
                 existUser·p0.90:   4.137 ms/op
                 existUser·p0.95:   4.448 ms/op
                 existUser·p0.99:   5.833 ms/op
                 existUser·p0.999:  13.505 ms/op
                 existUser·p0.9999: 18.028 ms/op
                 existUser·p1.00:   18.547 ms/op

Iteration   2: 3.615 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.983 ms/op
                 existUser·p0.50:   3.580 ms/op
                 existUser·p0.90:   4.284 ms/op
                 existUser·p0.95:   4.620 ms/op
                 existUser·p0.99:   5.972 ms/op
                 existUser·p0.999:  9.355 ms/op
                 existUser·p0.9999: 30.661 ms/op
                 existUser·p1.00:   30.867 ms/op

Iteration   3: 3.583 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.083 ms/op
                 existUser·p0.50:   3.535 ms/op
                 existUser·p0.90:   4.063 ms/op
                 existUser·p0.95:   4.424 ms/op
                 existUser·p0.99:   5.759 ms/op
                 existUser·p0.999:  8.654 ms/op
                 existUser·p0.9999: 17.699 ms/op
                 existUser·p1.00:   18.186 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 266314
  mean =      3.608 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7851 
    [ 2.500,  5.000) = 252205 
    [ 5.000,  7.500) = 5340 
    [ 7.500, 10.000) = 659 
    [10.000, 12.500) = 92 
    [12.500, 15.000) = 57 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 14 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.893 ms/op
     p(50.0000) =      3.559 ms/op
     p(90.0000) =      4.174 ms/op
     p(95.0000) =      4.506 ms/op
     p(99.0000) =      5.865 ms/op
     p(99.9000) =      9.951 ms/op
     p(99.9900) =     29.721 ms/op
     p(99.9990) =     30.835 ms/op
     p(99.9999) =     30.867 ms/op
    p(100.0000) =     30.867 ms/op


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
# Warmup Iteration   1: 5.387 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.061 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.883 ±(99.9%) 0.010 ms/op
Iteration   1: 3.854 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.879 ms/op
                 getUser·p0.50:   3.768 ms/op
                 getUser·p0.90:   4.571 ms/op
                 getUser·p0.95:   4.915 ms/op
                 getUser·p0.99:   6.760 ms/op
                 getUser·p0.999:  13.993 ms/op
                 getUser·p0.9999: 18.593 ms/op
                 getUser·p1.00:   18.973 ms/op

Iteration   2: 3.822 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.726 ms/op
                 getUser·p0.50:   3.752 ms/op
                 getUser·p0.90:   4.588 ms/op
                 getUser·p0.95:   4.932 ms/op
                 getUser·p0.99:   6.488 ms/op
                 getUser·p0.999:  10.994 ms/op
                 getUser·p0.9999: 17.966 ms/op
                 getUser·p1.00:   18.383 ms/op

Iteration   3: 3.696 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.954 ms/op
                 getUser·p0.50:   3.654 ms/op
                 getUser·p0.90:   4.415 ms/op
                 getUser·p0.95:   4.817 ms/op
                 getUser·p0.99:   6.038 ms/op
                 getUser·p0.999:  13.154 ms/op
                 getUser·p0.9999: 20.470 ms/op
                 getUser·p1.00:   21.398 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 253217
  mean =      3.789 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8614 
    [ 2.500,  5.000) = 234326 
    [ 5.000,  7.500) = 8924 
    [ 7.500, 10.000) = 910 
    [10.000, 12.500) = 170 
    [12.500, 15.000) = 110 
    [15.000, 17.500) = 52 
    [17.500, 20.000) = 95 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.726 ms/op
     p(50.0000) =      3.723 ms/op
     p(90.0000) =      4.530 ms/op
     p(95.0000) =      4.891 ms/op
     p(99.0000) =      6.357 ms/op
     p(99.9000) =     13.120 ms/op
     p(99.9900) =     19.454 ms/op
     p(99.9990) =     21.297 ms/op
     p(99.9999) =     21.398 ms/op
    p(100.0000) =     21.398 ms/op


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
# Warmup Iteration   1: 6.820 ±(99.9%) 0.074 ms/op
# Warmup Iteration   2: 5.339 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 5.002 ±(99.9%) 0.017 ms/op
Iteration   1: 4.936 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.915 ms/op
                 listUser·p0.50:   4.760 ms/op
                 listUser·p0.90:   6.046 ms/op
                 listUser·p0.95:   6.939 ms/op
                 listUser·p0.99:   8.536 ms/op
                 listUser·p0.999:  15.783 ms/op
                 listUser·p0.9999: 18.502 ms/op
                 listUser·p1.00:   19.726 ms/op

Iteration   2: 4.902 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   0.939 ms/op
                 listUser·p0.50:   4.719 ms/op
                 listUser·p0.90:   6.078 ms/op
                 listUser·p0.95:   7.048 ms/op
                 listUser·p0.99:   8.946 ms/op
                 listUser·p0.999:  16.286 ms/op
                 listUser·p0.9999: 23.542 ms/op
                 listUser·p1.00:   27.066 ms/op

Iteration   3: 4.920 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.227 ms/op
                 listUser·p0.50:   4.710 ms/op
                 listUser·p0.90:   6.029 ms/op
                 listUser·p0.95:   6.930 ms/op
                 listUser·p0.99:   8.815 ms/op
                 listUser·p0.999:  18.612 ms/op
                 listUser·p0.9999: 21.267 ms/op
                 listUser·p1.00:   25.428 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 194918
  mean =      4.919 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 317 
    [ 2.500,  5.000) = 131933 
    [ 5.000,  7.500) = 56241 
    [ 7.500, 10.000) = 5549 
    [10.000, 12.500) = 522 
    [12.500, 15.000) = 87 
    [15.000, 17.500) = 118 
    [17.500, 20.000) = 110 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.939 ms/op
     p(50.0000) =      4.735 ms/op
     p(90.0000) =      6.046 ms/op
     p(95.0000) =      6.971 ms/op
     p(99.0000) =      8.749 ms/op
     p(99.9000) =     16.598 ms/op
     p(99.9900) =     22.627 ms/op
     p(99.9990) =     27.035 ms/op
     p(99.9999) =     27.066 ms/op
    p(100.0000) =     27.066 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.333 ± 1.166  ops/ms
ClientGrpc.existUser                       thrpt       3   9.020 ± 2.202  ops/ms
ClientGrpc.getUser                         thrpt       3   8.578 ± 4.770  ops/ms
ClientGrpc.listUser                        thrpt       3   6.417 ± 2.155  ops/ms
ClientGrpc.createUser                       avgt       3   3.786 ± 0.438   ms/op
ClientGrpc.existUser                        avgt       3   3.601 ± 0.056   ms/op
ClientGrpc.getUser                          avgt       3   3.811 ± 0.773   ms/op
ClientGrpc.listUser                         avgt       3   4.899 ± 1.254   ms/op
ClientGrpc.createUser                     sample  246466   3.895 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.793           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.813           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.645           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.989           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.283           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.430           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.027           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.381           ms/op
ClientGrpc.existUser                      sample  266314   3.608 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.893           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.559           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.174           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.506           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.865           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.951           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          29.721           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          30.867           ms/op
ClientGrpc.getUser                        sample  253217   3.789 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.726           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.723           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.530           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.891           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.357           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          13.120           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.454           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.398           ms/op
ClientGrpc.listUser                       sample  194918   4.919 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.939           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.735           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.046           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.971           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.749           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.598           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.627           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.066           ms/op
