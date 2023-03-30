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
# Warmup Iteration   1: 2.169 ops/ms
# Warmup Iteration   2: 5.367 ops/ms
# Warmup Iteration   3: 7.133 ops/ms
Iteration   1: 7.094 ops/ms
Iteration   2: 7.336 ops/ms
Iteration   3: 7.497 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.309 ±(99.9%) 3.706 ops/ms [Average]
  (min, avg, max) = (7.094, 7.309, 7.497), stdev = 0.203
  CI (99.9%): [3.603, 11.015] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 5.027 ops/ms
# Warmup Iteration   2: 7.014 ops/ms
# Warmup Iteration   3: 7.727 ops/ms
Iteration   1: 7.795 ops/ms
Iteration   2: 7.643 ops/ms
Iteration   3: 8.038 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.825 ±(99.9%) 3.640 ops/ms [Average]
  (min, avg, max) = (7.643, 7.825, 8.038), stdev = 0.199
  CI (99.9%): [4.186, 11.465] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 4.083 ops/ms
# Warmup Iteration   2: 6.557 ops/ms
# Warmup Iteration   3: 7.250 ops/ms
Iteration   1: 7.320 ops/ms
Iteration   2: 7.460 ops/ms
Iteration   3: 7.240 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.340 ±(99.9%) 2.031 ops/ms [Average]
  (min, avg, max) = (7.240, 7.340, 7.460), stdev = 0.111
  CI (99.9%): [5.309, 9.370] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 3.556 ops/ms
# Warmup Iteration   2: 5.160 ops/ms
# Warmup Iteration   3: 5.558 ops/ms
Iteration   1: 5.605 ops/ms
Iteration   2: 5.557 ops/ms
Iteration   3: 5.591 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.584 ±(99.9%) 0.457 ops/ms [Average]
  (min, avg, max) = (5.557, 5.584, 5.605), stdev = 0.025
  CI (99.9%): [5.127, 6.041] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.441 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.578 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.476 ±(99.9%) 0.018 ms/op
Iteration   1: 4.263 ±(99.9%) 0.004 ms/op
Iteration   2: 4.220 ±(99.9%) 0.004 ms/op
Iteration   3: 4.190 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.224 ±(99.9%) 0.675 ms/op [Average]
  (min, avg, max) = (4.190, 4.224, 4.263), stdev = 0.037
  CI (99.9%): [3.550, 4.899] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 6.178 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.309 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 4.146 ±(99.9%) 0.005 ms/op
Iteration   1: 4.022 ±(99.9%) 0.004 ms/op
Iteration   2: 4.014 ±(99.9%) 0.004 ms/op
Iteration   3: 3.998 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.011 ±(99.9%) 0.221 ms/op [Average]
  (min, avg, max) = (3.998, 4.011, 4.022), stdev = 0.012
  CI (99.9%): [3.790, 4.232] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 6.558 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.653 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.315 ±(99.9%) 0.005 ms/op
Iteration   1: 4.197 ±(99.9%) 0.006 ms/op
Iteration   2: 4.285 ±(99.9%) 0.003 ms/op
Iteration   3: 4.373 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.285 ±(99.9%) 1.604 ms/op [Average]
  (min, avg, max) = (4.197, 4.285, 4.373), stdev = 0.088
  CI (99.9%): [2.681, 5.890] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 8.086 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 6.207 ±(99.9%) 0.041 ms/op
# Warmup Iteration   3: 5.793 ±(99.9%) 0.017 ms/op
Iteration   1: 5.846 ±(99.9%) 0.028 ms/op
Iteration   2: 5.689 ±(99.9%) 0.028 ms/op
Iteration   3: 5.833 ±(99.9%) 0.026 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.789 ±(99.9%) 1.592 ms/op [Average]
  (min, avg, max) = (5.689, 5.789, 5.846), stdev = 0.087
  CI (99.9%): [4.198, 7.381] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 6.890 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 4.703 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.513 ±(99.9%) 0.019 ms/op
Iteration   1: 4.344 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   0.869 ms/op
                 createUser·p0.50:   4.162 ms/op
                 createUser·p0.90:   5.448 ms/op
                 createUser·p0.95:   6.136 ms/op
                 createUser·p0.99:   9.994 ms/op
                 createUser·p0.999:  16.649 ms/op
                 createUser·p0.9999: 17.868 ms/op
                 createUser·p1.00:   23.953 ms/op

Iteration   2: 4.342 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   0.974 ms/op
                 createUser·p0.50:   4.129 ms/op
                 createUser·p0.90:   5.456 ms/op
                 createUser·p0.95:   6.087 ms/op
                 createUser·p0.99:   10.387 ms/op
                 createUser·p0.999:  18.197 ms/op
                 createUser·p0.9999: 25.035 ms/op
                 createUser·p1.00:   27.853 ms/op

Iteration   3: 4.247 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.094 ms/op
                 createUser·p0.50:   4.096 ms/op
                 createUser·p0.90:   5.399 ms/op
                 createUser·p0.95:   5.964 ms/op
                 createUser·p0.99:   9.142 ms/op
                 createUser·p0.999:  17.334 ms/op
                 createUser·p0.9999: 21.031 ms/op
                 createUser·p1.00:   22.053 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 222576
  mean =      4.310 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6821 
    [ 2.500,  5.000) = 178789 
    [ 5.000,  7.500) = 32611 
    [ 7.500, 10.000) = 2274 
    [10.000, 12.500) = 941 
    [12.500, 15.000) = 501 
    [15.000, 17.500) = 460 
    [17.500, 20.000) = 107 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.869 ms/op
     p(50.0000) =      4.129 ms/op
     p(90.0000) =      5.431 ms/op
     p(95.0000) =      6.062 ms/op
     p(99.0000) =      9.834 ms/op
     p(99.9000) =     17.170 ms/op
     p(99.9900) =     24.642 ms/op
     p(99.9990) =     27.344 ms/op
     p(99.9999) =     27.853 ms/op
    p(100.0000) =     27.853 ms/op


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
# Warmup Iteration   1: 6.136 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 4.376 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.123 ±(99.9%) 0.014 ms/op
Iteration   1: 4.117 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.905 ms/op
                 existUser·p0.50:   3.969 ms/op
                 existUser·p0.90:   5.284 ms/op
                 existUser·p0.95:   5.800 ms/op
                 existUser·p0.99:   9.093 ms/op
                 existUser·p0.999:  16.908 ms/op
                 existUser·p0.9999: 18.685 ms/op
                 existUser·p1.00:   19.005 ms/op

Iteration   2: 4.119 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.057 ms/op
                 existUser·p0.50:   3.973 ms/op
                 existUser·p0.90:   5.112 ms/op
                 existUser·p0.95:   5.587 ms/op
                 existUser·p0.99:   8.454 ms/op
                 existUser·p0.999:  16.729 ms/op
                 existUser·p0.9999: 22.560 ms/op
                 existUser·p1.00:   23.101 ms/op

Iteration   3: 4.079 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.027 ms/op
                 existUser·p0.50:   3.928 ms/op
                 existUser·p0.90:   4.989 ms/op
                 existUser·p0.95:   5.456 ms/op
                 existUser·p0.99:   8.290 ms/op
                 existUser·p0.999:  17.727 ms/op
                 existUser·p0.9999: 22.658 ms/op
                 existUser·p1.00:   23.495 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 233837
  mean =      4.105 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7104 
    [ 2.500,  5.000) = 198832 
    [ 5.000,  7.500) = 24484 
    [ 7.500, 10.000) = 2114 
    [10.000, 12.500) = 550 
    [12.500, 15.000) = 296 
    [15.000, 17.500) = 249 
    [17.500, 20.000) = 151 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.905 ms/op
     p(50.0000) =      3.957 ms/op
     p(90.0000) =      5.128 ms/op
     p(95.0000) =      5.628 ms/op
     p(99.0000) =      8.634 ms/op
     p(99.9000) =     17.302 ms/op
     p(99.9900) =     22.381 ms/op
     p(99.9990) =     23.298 ms/op
     p(99.9999) =     23.495 ms/op
    p(100.0000) =     23.495 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 6.758 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 4.655 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.381 ±(99.9%) 0.015 ms/op
Iteration   1: 4.294 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   0.970 ms/op
                 getUser·p0.50:   4.149 ms/op
                 getUser·p0.90:   5.292 ms/op
                 getUser·p0.95:   5.808 ms/op
                 getUser·p0.99:   9.339 ms/op
                 getUser·p0.999:  15.303 ms/op
                 getUser·p0.9999: 21.640 ms/op
                 getUser·p1.00:   22.807 ms/op

Iteration   2: 4.297 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.079 ms/op
                 getUser·p0.50:   4.141 ms/op
                 getUser·p0.90:   5.407 ms/op
                 getUser·p0.95:   5.939 ms/op
                 getUser·p0.99:   8.732 ms/op
                 getUser·p0.999:  18.645 ms/op
                 getUser·p0.9999: 20.039 ms/op
                 getUser·p1.00:   22.282 ms/op

Iteration   3: 4.268 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   0.819 ms/op
                 getUser·p0.50:   4.133 ms/op
                 getUser·p0.90:   5.259 ms/op
                 getUser·p0.95:   5.760 ms/op
                 getUser·p0.99:   8.700 ms/op
                 getUser·p0.999:  18.285 ms/op
                 getUser·p0.9999: 23.494 ms/op
                 getUser·p1.00:   23.986 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 224138
  mean =      4.286 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6401 
    [ 2.500,  5.000) = 182243 
    [ 5.000,  7.500) = 32057 
    [ 7.500, 10.000) = 1809 
    [10.000, 12.500) = 671 
    [12.500, 15.000) = 493 
    [15.000, 17.500) = 227 
    [17.500, 20.000) = 184 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.819 ms/op
     p(50.0000) =      4.141 ms/op
     p(90.0000) =      5.325 ms/op
     p(95.0000) =      5.841 ms/op
     p(99.0000) =      8.956 ms/op
     p(99.9000) =     17.760 ms/op
     p(99.9900) =     22.282 ms/op
     p(99.9990) =     23.880 ms/op
     p(99.9999) =     23.986 ms/op
    p(100.0000) =     23.986 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 8.658 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 6.116 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 5.722 ±(99.9%) 0.024 ms/op
Iteration   1: 5.781 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   1.614 ms/op
                 listUser·p0.50:   5.374 ms/op
                 listUser·p0.90:   7.823 ms/op
                 listUser·p0.95:   8.946 ms/op
                 listUser·p0.99:   12.527 ms/op
                 listUser·p0.999:  21.627 ms/op
                 listUser·p0.9999: 25.131 ms/op
                 listUser·p1.00:   25.428 ms/op

Iteration   2: 5.740 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   1.690 ms/op
                 listUser·p0.50:   5.366 ms/op
                 listUser·p0.90:   7.733 ms/op
                 listUser·p0.95:   8.946 ms/op
                 listUser·p0.99:   12.534 ms/op
                 listUser·p0.999:  19.735 ms/op
                 listUser·p0.9999: 24.276 ms/op
                 listUser·p1.00:   24.543 ms/op

Iteration   3: 5.973 ±(99.9%) 0.030 ms/op
                 listUser·p0.00:   1.282 ms/op
                 listUser·p0.50:   5.489 ms/op
                 listUser·p0.90:   8.298 ms/op
                 listUser·p0.95:   9.503 ms/op
                 listUser·p0.99:   13.140 ms/op
                 listUser·p0.999:  28.399 ms/op
                 listUser·p0.9999: 33.510 ms/op
                 listUser·p1.00:   36.372 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 164731
  mean =      5.830 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 318 
    [ 2.500,  5.000) = 57681 
    [ 5.000,  7.500) = 85018 
    [ 7.500, 10.000) = 16570 
    [10.000, 12.500) = 3339 
    [12.500, 15.000) = 869 
    [15.000, 17.500) = 424 
    [17.500, 20.000) = 246 
    [20.000, 22.500) = 102 
    [22.500, 25.000) = 92 
    [25.000, 27.500) = 10 
    [27.500, 30.000) = 26 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 23 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.282 ms/op
     p(50.0000) =      5.407 ms/op
     p(90.0000) =      7.946 ms/op
     p(95.0000) =      9.142 ms/op
     p(99.0000) =     12.730 ms/op
     p(99.9000) =     22.496 ms/op
     p(99.9900) =     33.084 ms/op
     p(99.9990) =     36.118 ms/op
     p(99.9999) =     36.372 ms/op
    p(100.0000) =     36.372 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.309 ± 3.706  ops/ms
ClientGrpc.existUser                       thrpt       3   7.825 ± 3.640  ops/ms
ClientGrpc.getUser                         thrpt       3   7.340 ± 2.031  ops/ms
ClientGrpc.listUser                        thrpt       3   5.584 ± 0.457  ops/ms
ClientGrpc.createUser                       avgt       3   4.224 ± 0.675   ms/op
ClientGrpc.existUser                        avgt       3   4.011 ± 0.221   ms/op
ClientGrpc.getUser                          avgt       3   4.285 ± 1.604   ms/op
ClientGrpc.listUser                         avgt       3   5.789 ± 1.592   ms/op
ClientGrpc.createUser                     sample  222576   4.310 ± 0.010   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.869           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.129           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.431           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.062           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           9.834           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          17.170           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.642           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.853           ms/op
ClientGrpc.existUser                      sample  233837   4.105 ± 0.008   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.905           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.957           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.128           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.628           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           8.634           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          17.302           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          22.381           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.495           ms/op
ClientGrpc.getUser                        sample  224138   4.286 ± 0.009   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.819           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.141           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.325           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.841           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           8.956           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          17.760           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.282           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.986           ms/op
ClientGrpc.listUser                       sample  164731   5.830 ± 0.016   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.282           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.407           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.946           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           9.142           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          12.730           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          22.496           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          33.084           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          36.372           ms/op
