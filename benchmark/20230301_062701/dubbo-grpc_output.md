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
# Warmup Iteration   1: 2.754 ops/ms
# Warmup Iteration   2: 6.222 ops/ms
# Warmup Iteration   3: 7.474 ops/ms
Iteration   1: 7.694 ops/ms
Iteration   2: 7.885 ops/ms
Iteration   3: 7.785 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.788 ±(99.9%) 1.735 ops/ms [Average]
  (min, avg, max) = (7.694, 7.788, 7.885), stdev = 0.095
  CI (99.9%): [6.053, 9.523] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 5.358 ops/ms
# Warmup Iteration   2: 7.722 ops/ms
# Warmup Iteration   3: 8.052 ops/ms
Iteration   1: 8.222 ops/ms
Iteration   2: 8.150 ops/ms
Iteration   3: 8.467 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.279 ±(99.9%) 3.030 ops/ms [Average]
  (min, avg, max) = (8.150, 8.279, 8.467), stdev = 0.166
  CI (99.9%): [5.250, 11.309] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.133 ops/ms
# Warmup Iteration   2: 7.387 ops/ms
# Warmup Iteration   3: 7.858 ops/ms
Iteration   1: 8.181 ops/ms
Iteration   2: 8.081 ops/ms
Iteration   3: 7.912 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.058 ±(99.9%) 2.486 ops/ms [Average]
  (min, avg, max) = (7.912, 8.058, 8.181), stdev = 0.136
  CI (99.9%): [5.572, 10.544] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 4.076 ops/ms
# Warmup Iteration   2: 5.605 ops/ms
# Warmup Iteration   3: 5.954 ops/ms
Iteration   1: 6.282 ops/ms
Iteration   2: 6.191 ops/ms
Iteration   3: 6.153 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.209 ±(99.9%) 1.212 ops/ms [Average]
  (min, avg, max) = (6.153, 6.209, 6.282), stdev = 0.066
  CI (99.9%): [4.997, 7.421] (assumes normal distribution)


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
# Warmup Iteration   1: 6.245 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.368 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 3.977 ±(99.9%) 0.007 ms/op
Iteration   1: 4.122 ±(99.9%) 0.005 ms/op
Iteration   2: 4.093 ±(99.9%) 0.003 ms/op
Iteration   3: 4.072 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.096 ±(99.9%) 0.457 ms/op [Average]
  (min, avg, max) = (4.072, 4.096, 4.122), stdev = 0.025
  CI (99.9%): [3.638, 4.553] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 5.774 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.119 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.896 ±(99.9%) 0.015 ms/op
Iteration   1: 3.787 ±(99.9%) 0.003 ms/op
Iteration   2: 3.889 ±(99.9%) 0.002 ms/op
Iteration   3: 3.900 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.859 ±(99.9%) 1.133 ms/op [Average]
  (min, avg, max) = (3.787, 3.859, 3.900), stdev = 0.062
  CI (99.9%): [2.726, 4.991] (assumes normal distribution)


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
# Warmup Iteration   1: 6.305 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.300 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.091 ±(99.9%) 0.003 ms/op
Iteration   1: 4.282 ±(99.9%) 0.006 ms/op
Iteration   2: 4.202 ±(99.9%) 0.003 ms/op
Iteration   3: 4.026 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.170 ±(99.9%) 2.390 ms/op [Average]
  (min, avg, max) = (4.026, 4.170, 4.282), stdev = 0.131
  CI (99.9%): [1.780, 6.560] (assumes normal distribution)


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
# Warmup Iteration   1: 6.490 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 5.398 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.981 ±(99.9%) 0.017 ms/op
Iteration   1: 5.000 ±(99.9%) 0.010 ms/op
Iteration   2: 5.037 ±(99.9%) 0.013 ms/op
Iteration   3: 4.793 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.943 ±(99.9%) 2.396 ms/op [Average]
  (min, avg, max) = (4.793, 4.943, 5.037), stdev = 0.131
  CI (99.9%): [2.548, 7.339] (assumes normal distribution)


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
# Warmup Iteration   1: 5.992 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 4.073 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.957 ±(99.9%) 0.010 ms/op
Iteration   1: 4.102 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.212 ms/op
                 createUser·p0.50:   4.030 ms/op
                 createUser·p0.90:   5.276 ms/op
                 createUser·p0.95:   5.587 ms/op
                 createUser·p0.99:   6.578 ms/op
                 createUser·p0.999:  10.645 ms/op
                 createUser·p0.9999: 22.905 ms/op
                 createUser·p1.00:   23.331 ms/op

Iteration   2: 3.934 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.075 ms/op
                 createUser·p0.50:   3.850 ms/op
                 createUser·p0.90:   4.784 ms/op
                 createUser·p0.95:   5.169 ms/op
                 createUser·p0.99:   6.341 ms/op
                 createUser·p0.999:  12.038 ms/op
                 createUser·p0.9999: 25.985 ms/op
                 createUser·p1.00:   26.542 ms/op

Iteration   3: 4.151 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.889 ms/op
                 createUser·p0.50:   4.076 ms/op
                 createUser·p0.90:   5.317 ms/op
                 createUser·p0.95:   5.667 ms/op
                 createUser·p0.99:   6.779 ms/op
                 createUser·p0.999:  12.730 ms/op
                 createUser·p0.9999: 25.307 ms/op
                 createUser·p1.00:   26.018 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 236519
  mean =      4.060 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5160 
    [ 2.500,  5.000) = 199935 
    [ 5.000,  7.500) = 30149 
    [ 7.500, 10.000) = 900 
    [10.000, 12.500) = 174 
    [12.500, 15.000) = 68 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 58 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.889 ms/op
     p(50.0000) =      3.965 ms/op
     p(90.0000) =      5.169 ms/op
     p(95.0000) =      5.521 ms/op
     p(99.0000) =      6.578 ms/op
     p(99.9000) =     12.083 ms/op
     p(99.9900) =     25.375 ms/op
     p(99.9990) =     26.408 ms/op
     p(99.9999) =     26.542 ms/op
    p(100.0000) =     26.542 ms/op


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
# Warmup Iteration   1: 5.564 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 4.165 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.788 ±(99.9%) 0.011 ms/op
Iteration   1: 3.825 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.599 ms/op
                 existUser·p0.50:   3.736 ms/op
                 existUser·p0.90:   4.899 ms/op
                 existUser·p0.95:   5.235 ms/op
                 existUser·p0.99:   6.407 ms/op
                 existUser·p0.999:  9.159 ms/op
                 existUser·p0.9999: 14.573 ms/op
                 existUser·p1.00:   15.008 ms/op

Iteration   2: 3.783 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.813 ms/op
                 existUser·p0.50:   3.678 ms/op
                 existUser·p0.90:   4.915 ms/op
                 existUser·p0.95:   5.235 ms/op
                 existUser·p0.99:   6.177 ms/op
                 existUser·p0.999:  8.412 ms/op
                 existUser·p0.9999: 15.700 ms/op
                 existUser·p1.00:   16.335 ms/op

Iteration   3: 3.903 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.862 ms/op
                 existUser·p0.50:   3.867 ms/op
                 existUser·p0.90:   4.923 ms/op
                 existUser·p0.95:   5.194 ms/op
                 existUser·p0.99:   5.984 ms/op
                 existUser·p0.999:  12.750 ms/op
                 existUser·p0.9999: 18.770 ms/op
                 existUser·p1.00:   19.726 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 250108
  mean =      3.836 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 198 
    [ 1.250,  2.500) = 9336 
    [ 2.500,  3.750) = 114796 
    [ 3.750,  5.000) = 105094 
    [ 5.000,  6.250) = 18318 
    [ 6.250,  7.500) = 1483 
    [ 7.500,  8.750) = 546 
    [ 8.750, 10.000) = 142 
    [10.000, 11.250) = 12 
    [11.250, 12.500) = 34 
    [12.500, 13.750) = 43 
    [13.750, 15.000) = 42 
    [15.000, 16.250) = 30 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.599 ms/op
     p(50.0000) =      3.756 ms/op
     p(90.0000) =      4.915 ms/op
     p(95.0000) =      5.218 ms/op
     p(99.0000) =      6.193 ms/op
     p(99.9000) =      9.208 ms/op
     p(99.9900) =     18.219 ms/op
     p(99.9990) =     19.513 ms/op
     p(99.9999) =     19.726 ms/op
    p(100.0000) =     19.726 ms/op


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
# Warmup Iteration   1: 5.806 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 4.202 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.095 ±(99.9%) 0.011 ms/op
Iteration   1: 4.166 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.085 ms/op
                 getUser·p0.50:   4.084 ms/op
                 getUser·p0.90:   5.300 ms/op
                 getUser·p0.95:   5.636 ms/op
                 getUser·p0.99:   6.611 ms/op
                 getUser·p0.999:  10.764 ms/op
                 getUser·p0.9999: 15.175 ms/op
                 getUser·p1.00:   15.811 ms/op

Iteration   2: 4.068 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.773 ms/op
                 getUser·p0.50:   3.985 ms/op
                 getUser·p0.90:   5.128 ms/op
                 getUser·p0.95:   5.505 ms/op
                 getUser·p0.99:   6.778 ms/op
                 getUser·p0.999:  12.698 ms/op
                 getUser·p0.9999: 18.555 ms/op
                 getUser·p1.00:   19.137 ms/op

Iteration   3: 4.117 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.085 ms/op
                 getUser·p0.50:   4.026 ms/op
                 getUser·p0.90:   5.153 ms/op
                 getUser·p0.95:   5.521 ms/op
                 getUser·p0.99:   6.406 ms/op
                 getUser·p0.999:  11.916 ms/op
                 getUser·p0.9999: 20.717 ms/op
                 getUser·p1.00:   21.004 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 233182
  mean =      4.117 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5333 
    [ 2.500,  5.000) = 195064 
    [ 5.000,  7.500) = 31410 
    [ 7.500, 10.000) = 913 
    [10.000, 12.500) = 256 
    [12.500, 15.000) = 104 
    [15.000, 17.500) = 50 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.773 ms/op
     p(50.0000) =      4.030 ms/op
     p(90.0000) =      5.194 ms/op
     p(95.0000) =      5.554 ms/op
     p(99.0000) =      6.570 ms/op
     p(99.9000) =     11.925 ms/op
     p(99.9900) =     19.892 ms/op
     p(99.9990) =     20.939 ms/op
     p(99.9999) =     21.004 ms/op
    p(100.0000) =     21.004 ms/op


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
# Warmup Iteration   1: 7.775 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 5.220 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.879 ±(99.9%) 0.015 ms/op
Iteration   1: 4.830 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.853 ms/op
                 listUser·p0.50:   4.661 ms/op
                 listUser·p0.90:   6.078 ms/op
                 listUser·p0.95:   6.914 ms/op
                 listUser·p0.99:   9.006 ms/op
                 listUser·p0.999:  13.984 ms/op
                 listUser·p0.9999: 18.531 ms/op
                 listUser·p1.00:   20.021 ms/op

Iteration   2: 4.888 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.399 ms/op
                 listUser·p0.50:   4.669 ms/op
                 listUser·p0.90:   6.300 ms/op
                 listUser·p0.95:   7.045 ms/op
                 listUser·p0.99:   8.897 ms/op
                 listUser·p0.999:  16.539 ms/op
                 listUser·p0.9999: 20.061 ms/op
                 listUser·p1.00:   22.938 ms/op

Iteration   3: 4.954 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.122 ms/op
                 listUser·p0.50:   4.768 ms/op
                 listUser·p0.90:   6.218 ms/op
                 listUser·p0.95:   7.045 ms/op
                 listUser·p0.99:   9.028 ms/op
                 listUser·p0.999:  18.612 ms/op
                 listUser·p0.9999: 22.381 ms/op
                 listUser·p1.00:   22.970 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 196356
  mean =      4.890 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 404 
    [ 2.500,  5.000) = 127324 
    [ 5.000,  7.500) = 62281 
    [ 7.500, 10.000) = 5354 
    [10.000, 12.500) = 589 
    [12.500, 15.000) = 176 
    [15.000, 17.500) = 97 
    [17.500, 20.000) = 102 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.122 ms/op
     p(50.0000) =      4.702 ms/op
     p(90.0000) =      6.201 ms/op
     p(95.0000) =      7.004 ms/op
     p(99.0000) =      8.978 ms/op
     p(99.9000) =     16.351 ms/op
     p(99.9900) =     21.094 ms/op
     p(99.9990) =     22.970 ms/op
     p(99.9999) =     22.970 ms/op
    p(100.0000) =     22.970 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.788 ± 1.735  ops/ms
ClientGrpc.existUser                       thrpt       3   8.279 ± 3.030  ops/ms
ClientGrpc.getUser                         thrpt       3   8.058 ± 2.486  ops/ms
ClientGrpc.listUser                        thrpt       3   6.209 ± 1.212  ops/ms
ClientGrpc.createUser                       avgt       3   4.096 ± 0.457   ms/op
ClientGrpc.existUser                        avgt       3   3.859 ± 1.133   ms/op
ClientGrpc.getUser                          avgt       3   4.170 ± 2.390   ms/op
ClientGrpc.listUser                         avgt       3   4.943 ± 2.396   ms/op
ClientGrpc.createUser                     sample  236519   4.060 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.889           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.965           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.169           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.521           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.578           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.083           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          25.375           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.542           ms/op
ClientGrpc.existUser                      sample  250108   3.836 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.599           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.756           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.915           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.218           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.193           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.208           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.219           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.726           ms/op
ClientGrpc.getUser                        sample  233182   4.117 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.773           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.030           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.194           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.554           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.570           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.925           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.892           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.004           ms/op
ClientGrpc.listUser                       sample  196356   4.890 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.122           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.702           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.201           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.004           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.978           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.351           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.094           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.970           ms/op
