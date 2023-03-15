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
# Warmup Iteration   1: 4.063 ops/ms
# Warmup Iteration   2: 9.004 ops/ms
# Warmup Iteration   3: 10.222 ops/ms
Iteration   1: 10.580 ops/ms
Iteration   2: 10.715 ops/ms
Iteration   3: 10.458 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.584 ±(99.9%) 2.342 ops/ms [Average]
  (min, avg, max) = (10.458, 10.584, 10.715), stdev = 0.128
  CI (99.9%): [8.242, 12.926] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.536 ops/ms
# Warmup Iteration   2: 10.666 ops/ms
# Warmup Iteration   3: 11.018 ops/ms
Iteration   1: 11.237 ops/ms
Iteration   2: 10.926 ops/ms
Iteration   3: 11.008 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.057 ±(99.9%) 2.942 ops/ms [Average]
  (min, avg, max) = (10.926, 11.057, 11.237), stdev = 0.161
  CI (99.9%): [8.115, 13.998] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.395 ops/ms
# Warmup Iteration   2: 10.354 ops/ms
# Warmup Iteration   3: 10.725 ops/ms
Iteration   1: 10.799 ops/ms
Iteration   2: 10.700 ops/ms
Iteration   3: 10.453 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.650 ±(99.9%) 3.251 ops/ms [Average]
  (min, avg, max) = (10.453, 10.650, 10.799), stdev = 0.178
  CI (99.9%): [7.399, 13.902] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.665 ops/ms
# Warmup Iteration   2: 7.785 ops/ms
# Warmup Iteration   3: 8.184 ops/ms
Iteration   1: 8.311 ops/ms
Iteration   2: 8.098 ops/ms
Iteration   3: 8.198 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.202 ±(99.9%) 1.944 ops/ms [Average]
  (min, avg, max) = (8.098, 8.202, 8.311), stdev = 0.107
  CI (99.9%): [6.259, 10.146] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.058 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.129 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.973 ±(99.9%) 0.003 ms/op
Iteration   1: 2.997 ±(99.9%) 0.007 ms/op
Iteration   2: 2.948 ±(99.9%) 0.003 ms/op
Iteration   3: 3.001 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.982 ±(99.9%) 0.539 ms/op [Average]
  (min, avg, max) = (2.948, 2.982, 3.001), stdev = 0.030
  CI (99.9%): [2.443, 3.521] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.869 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.936 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.874 ±(99.9%) 0.003 ms/op
Iteration   1: 2.923 ±(99.9%) 0.002 ms/op
Iteration   2: 2.905 ±(99.9%) 0.002 ms/op
Iteration   3: 2.873 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.900 ±(99.9%) 0.463 ms/op [Average]
  (min, avg, max) = (2.873, 2.900, 2.923), stdev = 0.025
  CI (99.9%): [2.437, 3.363] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.307 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.106 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.011 ±(99.9%) 0.003 ms/op
Iteration   1: 2.996 ±(99.9%) 0.003 ms/op
Iteration   2: 2.975 ±(99.9%) 0.002 ms/op
Iteration   3: 2.980 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.983 ±(99.9%) 0.197 ms/op [Average]
  (min, avg, max) = (2.975, 2.983, 2.996), stdev = 0.011
  CI (99.9%): [2.786, 3.180] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.222 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.990 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.959 ±(99.9%) 0.018 ms/op
Iteration   1: 3.941 ±(99.9%) 0.008 ms/op
Iteration   2: 3.917 ±(99.9%) 0.034 ms/op
Iteration   3: 3.870 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.910 ±(99.9%) 0.656 ms/op [Average]
  (min, avg, max) = (3.870, 3.910, 3.941), stdev = 0.036
  CI (99.9%): [3.253, 4.566] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.226 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.198 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.094 ±(99.9%) 0.007 ms/op
Iteration   1: 2.991 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.786 ms/op
                 createUser·p0.50:   2.982 ms/op
                 createUser·p0.90:   3.535 ms/op
                 createUser·p0.95:   3.768 ms/op
                 createUser·p0.99:   4.440 ms/op
                 createUser·p0.999:  6.128 ms/op
                 createUser·p0.9999: 15.247 ms/op
                 createUser·p1.00:   16.155 ms/op

Iteration   2: 3.045 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.758 ms/op
                 createUser·p0.50:   3.002 ms/op
                 createUser·p0.90:   3.600 ms/op
                 createUser·p0.95:   3.805 ms/op
                 createUser·p0.99:   4.620 ms/op
                 createUser·p0.999:  6.807 ms/op
                 createUser·p0.9999: 19.693 ms/op
                 createUser·p1.00:   20.873 ms/op

Iteration   3: 3.062 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.910 ms/op
                 createUser·p0.50:   3.023 ms/op
                 createUser·p0.90:   3.600 ms/op
                 createUser·p0.95:   3.772 ms/op
                 createUser·p0.99:   4.317 ms/op
                 createUser·p0.999:  11.658 ms/op
                 createUser·p0.9999: 16.093 ms/op
                 createUser·p1.00:   16.564 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 316455
  mean =      3.032 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25651 
    [ 2.500,  5.000) = 289308 
    [ 5.000,  7.500) = 1237 
    [ 7.500, 10.000) = 3 
    [10.000, 12.500) = 62 
    [12.500, 15.000) = 97 
    [15.000, 17.500) = 65 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.758 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.580 ms/op
     p(95.0000) =      3.785 ms/op
     p(99.0000) =      4.465 ms/op
     p(99.9000) =      6.853 ms/op
     p(99.9900) =     18.745 ms/op
     p(99.9990) =     20.677 ms/op
     p(99.9999) =     20.873 ms/op
    p(100.0000) =     20.873 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.803 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.037 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.963 ±(99.9%) 0.005 ms/op
Iteration   1: 2.912 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.371 ms/op
                 existUser·p0.50:   2.863 ms/op
                 existUser·p0.90:   3.269 ms/op
                 existUser·p0.95:   3.527 ms/op
                 existUser·p0.99:   4.760 ms/op
                 existUser·p0.999:  9.994 ms/op
                 existUser·p0.9999: 13.714 ms/op
                 existUser·p1.00:   14.008 ms/op

Iteration   2: 2.916 ±(99.9%) 0.004 ms/op
                 existUser·p0.00:   0.817 ms/op
                 existUser·p0.50:   2.888 ms/op
                 existUser·p0.90:   3.351 ms/op
                 existUser·p0.95:   3.486 ms/op
                 existUser·p0.99:   3.838 ms/op
                 existUser·p0.999:  6.529 ms/op
                 existUser·p0.9999: 13.683 ms/op
                 existUser·p1.00:   14.303 ms/op

Iteration   3: 2.865 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.534 ms/op
                 existUser·p0.50:   2.867 ms/op
                 existUser·p0.90:   3.166 ms/op
                 existUser·p0.95:   3.334 ms/op
                 existUser·p0.99:   3.965 ms/op
                 existUser·p0.999:  7.137 ms/op
                 existUser·p0.9999: 19.726 ms/op
                 existUser·p1.00:   21.627 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 331232
  mean =      2.898 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 33928 
    [ 2.500,  5.000) = 295885 
    [ 5.000,  7.500) = 856 
    [ 7.500, 10.000) = 327 
    [10.000, 12.500) = 77 
    [12.500, 15.000) = 105 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.371 ms/op
     p(50.0000) =      2.871 ms/op
     p(90.0000) =      3.269 ms/op
     p(95.0000) =      3.465 ms/op
     p(99.0000) =      4.129 ms/op
     p(99.9000) =      8.778 ms/op
     p(99.9900) =     17.531 ms/op
     p(99.9990) =     21.111 ms/op
     p(99.9999) =     21.627 ms/op
    p(100.0000) =     21.627 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.295 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.104 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.024 ±(99.9%) 0.007 ms/op
Iteration   1: 3.000 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.924 ms/op
                 getUser·p0.50:   2.957 ms/op
                 getUser·p0.90:   3.465 ms/op
                 getUser·p0.95:   3.699 ms/op
                 getUser·p0.99:   4.383 ms/op
                 getUser·p0.999:  7.675 ms/op
                 getUser·p0.9999: 16.548 ms/op
                 getUser·p1.00:   16.941 ms/op

Iteration   2: 3.012 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.676 ms/op
                 getUser·p0.50:   2.986 ms/op
                 getUser·p0.90:   3.490 ms/op
                 getUser·p0.95:   3.707 ms/op
                 getUser·p0.99:   4.319 ms/op
                 getUser·p0.999:  7.683 ms/op
                 getUser·p0.9999: 16.979 ms/op
                 getUser·p1.00:   17.662 ms/op

Iteration   3: 2.976 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.717 ms/op
                 getUser·p0.50:   2.959 ms/op
                 getUser·p0.90:   3.412 ms/op
                 getUser·p0.95:   3.617 ms/op
                 getUser·p0.99:   4.201 ms/op
                 getUser·p0.999:  7.453 ms/op
                 getUser·p0.9999: 19.407 ms/op
                 getUser·p1.00:   19.661 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 320081
  mean =      2.996 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 612 
    [ 1.250,  2.500) = 21591 
    [ 2.500,  3.750) = 285333 
    [ 3.750,  5.000) = 11504 
    [ 5.000,  6.250) = 522 
    [ 6.250,  7.500) = 180 
    [ 7.500,  8.750) = 86 
    [ 8.750, 10.000) = 12 
    [10.000, 11.250) = 19 
    [11.250, 12.500) = 28 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 60 
    [16.250, 17.500) = 69 
    [17.500, 18.750) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.676 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      3.457 ms/op
     p(95.0000) =      3.670 ms/op
     p(99.0000) =      4.293 ms/op
     p(99.9000) =      7.627 ms/op
     p(99.9900) =     18.973 ms/op
     p(99.9990) =     19.523 ms/op
     p(99.9999) =     19.661 ms/op
    p(100.0000) =     19.661 ms/op


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
# Warmup Iteration   1: 4.488 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.263 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 3.874 ±(99.9%) 0.010 ms/op
Iteration   1: 3.879 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.859 ms/op
                 listUser·p0.50:   3.748 ms/op
                 listUser·p0.90:   4.710 ms/op
                 listUser·p0.95:   5.644 ms/op
                 listUser·p0.99:   6.808 ms/op
                 listUser·p0.999:  13.156 ms/op
                 listUser·p0.9999: 19.792 ms/op
                 listUser·p1.00:   20.087 ms/op

Iteration   2: 3.904 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.696 ms/op
                 listUser·p0.50:   3.756 ms/op
                 listUser·p0.90:   4.760 ms/op
                 listUser·p0.95:   5.751 ms/op
                 listUser·p0.99:   6.758 ms/op
                 listUser·p0.999:  16.090 ms/op
                 listUser·p0.9999: 22.466 ms/op
                 listUser·p1.00:   23.003 ms/op

Iteration   3: 3.863 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.399 ms/op
                 listUser·p0.50:   3.731 ms/op
                 listUser·p0.90:   4.547 ms/op
                 listUser·p0.95:   5.259 ms/op
                 listUser·p0.99:   6.562 ms/op
                 listUser·p0.999:  17.078 ms/op
                 listUser·p0.9999: 26.729 ms/op
                 listUser·p1.00:   27.886 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 247339
  mean =      3.882 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3724 
    [ 2.500,  5.000) = 224903 
    [ 5.000,  7.500) = 17768 
    [ 7.500, 10.000) = 547 
    [10.000, 12.500) = 24 
    [12.500, 15.000) = 68 
    [15.000, 17.500) = 167 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.696 ms/op
     p(50.0000) =      3.748 ms/op
     p(90.0000) =      4.661 ms/op
     p(95.0000) =      5.603 ms/op
     p(99.0000) =      6.717 ms/op
     p(99.9000) =     16.034 ms/op
     p(99.9900) =     25.102 ms/op
     p(99.9990) =     27.773 ms/op
     p(99.9999) =     27.886 ms/op
    p(100.0000) =     27.886 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.584 ± 2.342  ops/ms
ClientGrpc.existUser                       thrpt       3  11.057 ± 2.942  ops/ms
ClientGrpc.getUser                         thrpt       3  10.650 ± 3.251  ops/ms
ClientGrpc.listUser                        thrpt       3   8.202 ± 1.944  ops/ms
ClientGrpc.createUser                       avgt       3   2.982 ± 0.539   ms/op
ClientGrpc.existUser                        avgt       3   2.900 ± 0.463   ms/op
ClientGrpc.getUser                          avgt       3   2.983 ± 0.197   ms/op
ClientGrpc.listUser                         avgt       3   3.910 ± 0.656   ms/op
ClientGrpc.createUser                     sample  316455   3.032 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.758           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.002           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.580           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.785           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.465           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           6.853           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.745           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.873           ms/op
ClientGrpc.existUser                      sample  331232   2.898 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.371           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.871           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.269           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.465           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.129           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.778           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.531           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.627           ms/op
ClientGrpc.getUser                        sample  320081   2.996 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.676           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.970           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.457           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.670           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.293           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.627           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.973           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.661           ms/op
ClientGrpc.listUser                       sample  247339   3.882 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.696           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.748           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.661           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.603           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.717           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.034           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.102           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.886           ms/op
