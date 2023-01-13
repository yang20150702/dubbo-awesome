# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.947 ops/ms
# Warmup Iteration   2: 8.883 ops/ms
# Warmup Iteration   3: 9.748 ops/ms
Iteration   1: 9.985 ops/ms
Iteration   2: 9.788 ops/ms
Iteration   3: 9.737 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.836 ±(99.9%) 2.392 ops/ms [Average]
  (min, avg, max) = (9.737, 9.836, 9.985), stdev = 0.131
  CI (99.9%): [7.444, 12.229] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 7.245 ops/ms
# Warmup Iteration   2: 9.867 ops/ms
# Warmup Iteration   3: 10.145 ops/ms
Iteration   1: 10.125 ops/ms
Iteration   2: 10.243 ops/ms
Iteration   3: 10.114 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.161 ±(99.9%) 1.302 ops/ms [Average]
  (min, avg, max) = (10.114, 10.161, 10.243), stdev = 0.071
  CI (99.9%): [8.858, 11.463] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 6.335 ops/ms
# Warmup Iteration   2: 9.534 ops/ms
# Warmup Iteration   3: 9.924 ops/ms
Iteration   1: 9.940 ops/ms
Iteration   2: 9.841 ops/ms
Iteration   3: 9.982 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.921 ±(99.9%) 1.326 ops/ms [Average]
  (min, avg, max) = (9.841, 9.921, 9.982), stdev = 0.073
  CI (99.9%): [8.595, 11.247] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 5.551 ops/ms
# Warmup Iteration   2: 7.475 ops/ms
# Warmup Iteration   3: 7.562 ops/ms
Iteration   1: 7.692 ops/ms
Iteration   2: 7.541 ops/ms
Iteration   3: 7.651 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.628 ±(99.9%) 1.422 ops/ms [Average]
  (min, avg, max) = (7.541, 7.628, 7.692), stdev = 0.078
  CI (99.9%): [6.206, 9.051] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.395 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.281 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.217 ±(99.9%) 0.003 ms/op
Iteration   1: 3.231 ±(99.9%) 0.002 ms/op
Iteration   2: 3.238 ±(99.9%) 0.002 ms/op
Iteration   3: 3.217 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.228 ±(99.9%) 0.196 ms/op [Average]
  (min, avg, max) = (3.217, 3.228, 3.238), stdev = 0.011
  CI (99.9%): [3.033, 3.424] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 3.933 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.247 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.068 ±(99.9%) 0.001 ms/op
Iteration   1: 3.117 ±(99.9%) 0.002 ms/op
Iteration   2: 3.075 ±(99.9%) 0.002 ms/op
Iteration   3: 3.073 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.089 ±(99.9%) 0.453 ms/op [Average]
  (min, avg, max) = (3.073, 3.089, 3.117), stdev = 0.025
  CI (99.9%): [2.636, 3.541] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.491 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.237 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.219 ±(99.9%) 0.005 ms/op
Iteration   1: 3.053 ±(99.9%) 0.002 ms/op
Iteration   2: 3.255 ±(99.9%) 0.002 ms/op
Iteration   3: 3.202 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.170 ±(99.9%) 1.910 ms/op [Average]
  (min, avg, max) = (3.053, 3.170, 3.255), stdev = 0.105
  CI (99.9%): [1.259, 5.080] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.433 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.309 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.076 ±(99.9%) 0.017 ms/op
Iteration   1: 4.236 ±(99.9%) 0.006 ms/op
Iteration   2: 4.139 ±(99.9%) 0.013 ms/op
Iteration   3: 4.068 ±(99.9%) 0.029 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.148 ±(99.9%) 1.531 ms/op [Average]
  (min, avg, max) = (4.068, 4.148, 4.236), stdev = 0.084
  CI (99.9%): [2.617, 5.678] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.736 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.283 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.230 ±(99.9%) 0.007 ms/op
Iteration   1: 3.204 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.782 ms/op
                 createUser·p0.50:   3.183 ms/op
                 createUser·p0.90:   3.871 ms/op
                 createUser·p0.95:   4.051 ms/op
                 createUser·p0.99:   4.489 ms/op
                 createUser·p0.999:  10.446 ms/op
                 createUser·p0.9999: 17.663 ms/op
                 createUser·p1.00:   18.907 ms/op

Iteration   2: 3.252 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.652 ms/op
                 createUser·p0.50:   3.207 ms/op
                 createUser·p0.90:   3.973 ms/op
                 createUser·p0.95:   4.170 ms/op
                 createUser·p0.99:   4.506 ms/op
                 createUser·p0.999:  7.735 ms/op
                 createUser·p0.9999: 19.399 ms/op
                 createUser·p1.00:   19.464 ms/op

Iteration   3: 3.232 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.807 ms/op
                 createUser·p0.50:   3.195 ms/op
                 createUser·p0.90:   3.879 ms/op
                 createUser·p0.95:   4.059 ms/op
                 createUser·p0.99:   4.497 ms/op
                 createUser·p0.999:  9.880 ms/op
                 createUser·p0.9999: 22.337 ms/op
                 createUser·p1.00:   22.643 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 297147
  mean =      3.229 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16353 
    [ 2.500,  5.000) = 279512 
    [ 5.000,  7.500) = 813 
    [ 7.500, 10.000) = 211 
    [10.000, 12.500) = 66 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 77 
    [17.500, 20.000) = 62 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.652 ms/op
     p(50.0000) =      3.195 ms/op
     p(90.0000) =      3.903 ms/op
     p(95.0000) =      4.096 ms/op
     p(99.0000) =      4.497 ms/op
     p(99.9000) =      9.748 ms/op
     p(99.9900) =     21.079 ms/op
     p(99.9990) =     22.611 ms/op
     p(99.9999) =     22.643 ms/op
    p(100.0000) =     22.643 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.290 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.173 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.087 ±(99.9%) 0.007 ms/op
Iteration   1: 3.057 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.920 ms/op
                 existUser·p0.50:   3.039 ms/op
                 existUser·p0.90:   3.662 ms/op
                 existUser·p0.95:   3.858 ms/op
                 existUser·p0.99:   4.276 ms/op
                 existUser·p0.999:  7.501 ms/op
                 existUser·p0.9999: 13.388 ms/op
                 existUser·p1.00:   13.812 ms/op

Iteration   2: 3.120 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.894 ms/op
                 existUser·p0.50:   3.105 ms/op
                 existUser·p0.90:   3.764 ms/op
                 existUser·p0.95:   3.953 ms/op
                 existUser·p0.99:   4.317 ms/op
                 existUser·p0.999:  7.261 ms/op
                 existUser·p0.9999: 15.814 ms/op
                 existUser·p1.00:   16.302 ms/op

Iteration   3: 3.093 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.557 ms/op
                 existUser·p0.50:   3.068 ms/op
                 existUser·p0.90:   3.772 ms/op
                 existUser·p0.95:   3.957 ms/op
                 existUser·p0.99:   4.350 ms/op
                 existUser·p0.999:  9.102 ms/op
                 existUser·p0.9999: 17.662 ms/op
                 existUser·p1.00:   17.760 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 310602
  mean =      3.090 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 885 
    [ 1.250,  2.500) = 29377 
    [ 2.500,  3.750) = 250588 
    [ 3.750,  5.000) = 28721 
    [ 5.000,  6.250) = 439 
    [ 6.250,  7.500) = 247 
    [ 7.500,  8.750) = 124 
    [ 8.750, 10.000) = 44 
    [10.000, 11.250) = 12 
    [11.250, 12.500) = 35 
    [12.500, 13.750) = 35 
    [13.750, 15.000) = 36 
    [15.000, 16.250) = 26 
    [16.250, 17.500) = 19 
    [17.500, 18.750) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.557 ms/op
     p(50.0000) =      3.072 ms/op
     p(90.0000) =      3.736 ms/op
     p(95.0000) =      3.924 ms/op
     p(99.0000) =      4.317 ms/op
     p(99.9000) =      7.758 ms/op
     p(99.9900) =     16.300 ms/op
     p(99.9990) =     17.760 ms/op
     p(99.9999) =     17.760 ms/op
    p(100.0000) =     17.760 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.246 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.268 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.161 ±(99.9%) 0.007 ms/op
Iteration   1: 3.191 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.574 ms/op
                 getUser·p0.50:   3.170 ms/op
                 getUser·p0.90:   3.809 ms/op
                 getUser·p0.95:   4.002 ms/op
                 getUser·p0.99:   4.456 ms/op
                 getUser·p0.999:  6.906 ms/op
                 getUser·p0.9999: 20.183 ms/op
                 getUser·p1.00:   20.677 ms/op

Iteration   2: 3.220 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.712 ms/op
                 getUser·p0.50:   3.178 ms/op
                 getUser·p0.90:   3.871 ms/op
                 getUser·p0.95:   4.047 ms/op
                 getUser·p0.99:   4.415 ms/op
                 getUser·p0.999:  8.405 ms/op
                 getUser·p0.9999: 23.169 ms/op
                 getUser·p1.00:   23.986 ms/op

Iteration   3: 3.255 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.814 ms/op
                 getUser·p0.50:   3.232 ms/op
                 getUser·p0.90:   3.932 ms/op
                 getUser·p0.95:   4.145 ms/op
                 getUser·p0.99:   4.538 ms/op
                 getUser·p0.999:  7.283 ms/op
                 getUser·p0.9999: 24.433 ms/op
                 getUser·p1.00:   25.788 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 298027
  mean =      3.222 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14163 
    [ 2.500,  5.000) = 282593 
    [ 5.000,  7.500) = 961 
    [ 7.500, 10.000) = 150 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 87 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.574 ms/op
     p(50.0000) =      3.191 ms/op
     p(90.0000) =      3.871 ms/op
     p(95.0000) =      4.067 ms/op
     p(99.0000) =      4.481 ms/op
     p(99.9000) =      7.594 ms/op
     p(99.9900) =     23.829 ms/op
     p(99.9990) =     25.465 ms/op
     p(99.9999) =     25.788 ms/op
    p(100.0000) =     25.788 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.533 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.330 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.162 ±(99.9%) 0.012 ms/op
Iteration   1: 4.189 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.001 ms/op
                 listUser·p0.50:   3.957 ms/op
                 listUser·p0.90:   5.612 ms/op
                 listUser·p0.95:   6.201 ms/op
                 listUser·p0.99:   7.127 ms/op
                 listUser·p0.999:  14.395 ms/op
                 listUser·p0.9999: 22.032 ms/op
                 listUser·p1.00:   22.348 ms/op

Iteration   2: 4.071 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.065 ms/op
                 listUser·p0.50:   3.912 ms/op
                 listUser·p0.90:   4.932 ms/op
                 listUser·p0.95:   5.800 ms/op
                 listUser·p0.99:   7.023 ms/op
                 listUser·p0.999:  17.932 ms/op
                 listUser·p0.9999: 22.581 ms/op
                 listUser·p1.00:   23.822 ms/op

Iteration   3: 4.107 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.214 ms/op
                 listUser·p0.50:   3.920 ms/op
                 listUser·p0.90:   5.186 ms/op
                 listUser·p0.95:   5.906 ms/op
                 listUser·p0.99:   7.127 ms/op
                 listUser·p0.999:  19.930 ms/op
                 listUser·p0.9999: 31.661 ms/op
                 listUser·p1.00:   32.866 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 233227
  mean =      4.122 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1990 
    [ 2.500,  5.000) = 201489 
    [ 5.000,  7.500) = 28209 
    [ 7.500, 10.000) = 1001 
    [10.000, 12.500) = 99 
    [12.500, 15.000) = 139 
    [15.000, 17.500) = 80 
    [17.500, 20.000) = 78 
    [20.000, 22.500) = 98 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 29 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.001 ms/op
     p(50.0000) =      3.928 ms/op
     p(90.0000) =      5.276 ms/op
     p(95.0000) =      5.997 ms/op
     p(99.0000) =      7.086 ms/op
     p(99.9000) =     17.294 ms/op
     p(99.9900) =     31.185 ms/op
     p(99.9990) =     32.823 ms/op
     p(99.9999) =     32.866 ms/op
    p(100.0000) =     32.866 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.836 ± 2.392  ops/ms
ClientGrpc.existUser                       thrpt       3  10.161 ± 1.302  ops/ms
ClientGrpc.getUser                         thrpt       3   9.921 ± 1.326  ops/ms
ClientGrpc.listUser                        thrpt       3   7.628 ± 1.422  ops/ms
ClientGrpc.createUser                       avgt       3   3.228 ± 0.196   ms/op
ClientGrpc.existUser                        avgt       3   3.089 ± 0.453   ms/op
ClientGrpc.getUser                          avgt       3   3.170 ± 1.910   ms/op
ClientGrpc.listUser                         avgt       3   4.148 ± 1.531   ms/op
ClientGrpc.createUser                     sample  297147   3.229 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.652           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.195           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.903           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.096           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.497           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.748           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.079           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.643           ms/op
ClientGrpc.existUser                      sample  310602   3.090 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.557           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.072           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.736           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.924           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.317           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.758           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.300           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.760           ms/op
ClientGrpc.getUser                        sample  298027   3.222 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.574           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.191           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.871           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.067           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.481           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.594           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.829           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.788           ms/op
ClientGrpc.listUser                       sample  233227   4.122 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.001           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.928           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.276           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.997           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.086           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.294           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          31.185           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          32.866           ms/op
