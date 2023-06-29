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
# Warmup Iteration   1: 3.317 ops/ms
# Warmup Iteration   2: 7.830 ops/ms
# Warmup Iteration   3: 9.436 ops/ms
Iteration   1: 9.370 ops/ms
Iteration   2: 9.543 ops/ms
Iteration   3: 9.427 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.447 ±(99.9%) 1.605 ops/ms [Average]
  (min, avg, max) = (9.370, 9.447, 9.543), stdev = 0.088
  CI (99.9%): [7.841, 11.052] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 6.316 ops/ms
# Warmup Iteration   2: 9.247 ops/ms
# Warmup Iteration   3: 9.467 ops/ms
Iteration   1: 9.936 ops/ms
Iteration   2: 9.938 ops/ms
Iteration   3: 9.826 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.900 ±(99.9%) 1.169 ops/ms [Average]
  (min, avg, max) = (9.826, 9.900, 9.938), stdev = 0.064
  CI (99.9%): [8.731, 11.069] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 6.002 ops/ms
# Warmup Iteration   2: 8.884 ops/ms
# Warmup Iteration   3: 8.992 ops/ms
Iteration   1: 9.041 ops/ms
Iteration   2: 9.651 ops/ms
Iteration   3: 9.264 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.319 ±(99.9%) 5.635 ops/ms [Average]
  (min, avg, max) = (9.041, 9.319, 9.651), stdev = 0.309
  CI (99.9%): [3.683, 14.954] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 4.989 ops/ms
# Warmup Iteration   2: 6.709 ops/ms
# Warmup Iteration   3: 6.814 ops/ms
Iteration   1: 6.954 ops/ms
Iteration   2: 7.016 ops/ms
Iteration   3: 6.884 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.951 ±(99.9%) 1.201 ops/ms [Average]
  (min, avg, max) = (6.884, 6.951, 7.016), stdev = 0.066
  CI (99.9%): [5.750, 8.153] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.938 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.653 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.559 ±(99.9%) 0.002 ms/op
Iteration   1: 3.481 ±(99.9%) 0.004 ms/op
Iteration   2: 3.426 ±(99.9%) 0.002 ms/op
Iteration   3: 3.473 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.460 ±(99.9%) 0.544 ms/op [Average]
  (min, avg, max) = (3.426, 3.460, 3.481), stdev = 0.030
  CI (99.9%): [2.916, 4.004] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.573 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 3.412 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.385 ±(99.9%) 0.002 ms/op
Iteration   1: 3.294 ±(99.9%) 0.002 ms/op
Iteration   2: 3.172 ±(99.9%) 0.003 ms/op
Iteration   3: 3.268 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.245 ±(99.9%) 1.173 ms/op [Average]
  (min, avg, max) = (3.172, 3.245, 3.294), stdev = 0.064
  CI (99.9%): [2.072, 4.417] (assumes normal distribution)


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
# Warmup Iteration   1: 5.090 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.647 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.458 ±(99.9%) 0.002 ms/op
Iteration   1: 3.550 ±(99.9%) 0.002 ms/op
Iteration   2: 3.424 ±(99.9%) 0.002 ms/op
Iteration   3: 3.443 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.473 ±(99.9%) 1.239 ms/op [Average]
  (min, avg, max) = (3.424, 3.473, 3.550), stdev = 0.068
  CI (99.9%): [2.234, 4.711] (assumes normal distribution)


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
# Warmup Iteration   1: 6.683 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.960 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.608 ±(99.9%) 0.020 ms/op
Iteration   1: 4.578 ±(99.9%) 0.010 ms/op
Iteration   2: 4.725 ±(99.9%) 0.018 ms/op
Iteration   3: 4.639 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.647 ±(99.9%) 1.344 ms/op [Average]
  (min, avg, max) = (4.578, 4.647, 4.725), stdev = 0.074
  CI (99.9%): [3.303, 5.991] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 5.370 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 3.646 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.423 ±(99.9%) 0.010 ms/op
Iteration   1: 3.476 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.827 ms/op
                 createUser·p0.50:   3.338 ms/op
                 createUser·p0.90:   4.432 ms/op
                 createUser·p0.95:   4.899 ms/op
                 createUser·p0.99:   6.169 ms/op
                 createUser·p0.999:  10.797 ms/op
                 createUser·p0.9999: 19.366 ms/op
                 createUser·p1.00:   19.399 ms/op

Iteration   2: 3.449 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.944 ms/op
                 createUser·p0.50:   3.330 ms/op
                 createUser·p0.90:   4.375 ms/op
                 createUser·p0.95:   4.784 ms/op
                 createUser·p0.99:   5.767 ms/op
                 createUser·p0.999:  11.384 ms/op
                 createUser·p0.9999: 23.093 ms/op
                 createUser·p1.00:   24.084 ms/op

Iteration   3: 3.437 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.379 ms/op
                 createUser·p0.50:   3.318 ms/op
                 createUser·p0.90:   4.276 ms/op
                 createUser·p0.95:   4.669 ms/op
                 createUser·p0.99:   5.972 ms/op
                 createUser·p0.999:  11.902 ms/op
                 createUser·p0.9999: 20.099 ms/op
                 createUser·p1.00:   20.480 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 277903
  mean =      3.454 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12952 
    [ 2.500,  5.000) = 255118 
    [ 5.000,  7.500) = 9091 
    [ 7.500, 10.000) = 406 
    [10.000, 12.500) = 136 
    [12.500, 15.000) = 8 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 116 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.379 ms/op
     p(50.0000) =      3.330 ms/op
     p(90.0000) =      4.358 ms/op
     p(95.0000) =      4.784 ms/op
     p(99.0000) =      5.964 ms/op
     p(99.9000) =     11.603 ms/op
     p(99.9900) =     22.270 ms/op
     p(99.9990) =     23.247 ms/op
     p(99.9999) =     24.084 ms/op
    p(100.0000) =     24.084 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.303 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.376 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.309 ±(99.9%) 0.009 ms/op
Iteration   1: 3.176 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.756 ms/op
                 existUser·p0.50:   3.068 ms/op
                 existUser·p0.90:   3.936 ms/op
                 existUser·p0.95:   4.375 ms/op
                 existUser·p0.99:   5.628 ms/op
                 existUser·p0.999:  9.415 ms/op
                 existUser·p0.9999: 15.711 ms/op
                 existUser·p1.00:   16.335 ms/op

Iteration   2: 3.234 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.771 ms/op
                 existUser·p0.50:   3.125 ms/op
                 existUser·p0.90:   4.035 ms/op
                 existUser·p0.95:   4.415 ms/op
                 existUser·p0.99:   5.579 ms/op
                 existUser·p0.999:  11.655 ms/op
                 existUser·p0.9999: 18.652 ms/op
                 existUser·p1.00:   19.202 ms/op

Iteration   3: 3.080 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.719 ms/op
                 existUser·p0.50:   3.027 ms/op
                 existUser·p0.90:   3.797 ms/op
                 existUser·p0.95:   4.174 ms/op
                 existUser·p0.99:   5.138 ms/op
                 existUser·p0.999:  7.497 ms/op
                 existUser·p0.9999: 17.682 ms/op
                 existUser·p1.00:   20.480 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 303476
  mean =      3.162 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29576 
    [ 2.500,  5.000) = 268590 
    [ 5.000,  7.500) = 4794 
    [ 7.500, 10.000) = 246 
    [10.000, 12.500) = 99 
    [12.500, 15.000) = 46 
    [15.000, 17.500) = 98 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.719 ms/op
     p(50.0000) =      3.072 ms/op
     p(90.0000) =      3.924 ms/op
     p(95.0000) =      4.325 ms/op
     p(99.0000) =      5.456 ms/op
     p(99.9000) =      9.486 ms/op
     p(99.9900) =     16.908 ms/op
     p(99.9990) =     19.932 ms/op
     p(99.9999) =     20.480 ms/op
    p(100.0000) =     20.480 ms/op


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
# Warmup Iteration   1: 5.051 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.577 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.537 ±(99.9%) 0.008 ms/op
Iteration   1: 3.464 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.910 ms/op
                 getUser·p0.50:   3.359 ms/op
                 getUser·p0.90:   4.358 ms/op
                 getUser·p0.95:   4.784 ms/op
                 getUser·p0.99:   5.906 ms/op
                 getUser·p0.999:  9.756 ms/op
                 getUser·p0.9999: 13.844 ms/op
                 getUser·p1.00:   14.877 ms/op

Iteration   2: 3.545 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.993 ms/op
                 getUser·p0.50:   3.437 ms/op
                 getUser·p0.90:   4.432 ms/op
                 getUser·p0.95:   4.858 ms/op
                 getUser·p0.99:   6.185 ms/op
                 getUser·p0.999:  9.577 ms/op
                 getUser·p0.9999: 15.826 ms/op
                 getUser·p1.00:   16.204 ms/op

Iteration   3: 3.504 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.984 ms/op
                 getUser·p0.50:   3.396 ms/op
                 getUser·p0.90:   4.350 ms/op
                 getUser·p0.95:   4.817 ms/op
                 getUser·p0.99:   6.578 ms/op
                 getUser·p0.999:  12.206 ms/op
                 getUser·p0.9999: 17.793 ms/op
                 getUser·p1.00:   18.186 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 273871
  mean =      3.504 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 222 
    [ 1.250,  2.500) = 10777 
    [ 2.500,  3.750) = 183353 
    [ 3.750,  5.000) = 69145 
    [ 5.000,  6.250) = 7761 
    [ 6.250,  7.500) = 1523 
    [ 7.500,  8.750) = 533 
    [ 8.750, 10.000) = 188 
    [10.000, 11.250) = 74 
    [11.250, 12.500) = 96 
    [12.500, 13.750) = 74 
    [13.750, 15.000) = 35 
    [15.000, 16.250) = 54 
    [16.250, 17.500) = 11 
    [17.500, 18.750) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.910 ms/op
     p(50.0000) =      3.396 ms/op
     p(90.0000) =      4.383 ms/op
     p(95.0000) =      4.817 ms/op
     p(99.0000) =      6.193 ms/op
     p(99.9000) =     11.633 ms/op
     p(99.9900) =     17.465 ms/op
     p(99.9990) =     17.998 ms/op
     p(99.9999) =     18.186 ms/op
    p(100.0000) =     18.186 ms/op


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
# Warmup Iteration   1: 6.553 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 4.725 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.540 ±(99.9%) 0.014 ms/op
Iteration   1: 4.597 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   0.894 ms/op
                 listUser·p0.50:   4.317 ms/op
                 listUser·p0.90:   6.160 ms/op
                 listUser·p0.95:   6.955 ms/op
                 listUser·p0.99:   8.995 ms/op
                 listUser·p0.999:  14.026 ms/op
                 listUser·p0.9999: 19.892 ms/op
                 listUser·p1.00:   20.414 ms/op

Iteration   2: 4.709 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.427 ms/op
                 listUser·p0.50:   4.432 ms/op
                 listUser·p0.90:   6.250 ms/op
                 listUser·p0.95:   7.029 ms/op
                 listUser·p0.99:   9.289 ms/op
                 listUser·p0.999:  17.010 ms/op
                 listUser·p0.9999: 23.829 ms/op
                 listUser·p1.00:   24.216 ms/op

Iteration   3: 4.517 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.077 ms/op
                 listUser·p0.50:   4.235 ms/op
                 listUser·p0.90:   6.062 ms/op
                 listUser·p0.95:   6.881 ms/op
                 listUser·p0.99:   8.569 ms/op
                 listUser·p0.999:  17.366 ms/op
                 listUser·p0.9999: 25.225 ms/op
                 listUser·p1.00:   25.756 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 208475
  mean =      4.606 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1039 
    [ 2.500,  5.000) = 153894 
    [ 5.000,  7.500) = 47216 
    [ 7.500, 10.000) = 5211 
    [10.000, 12.500) = 674 
    [12.500, 15.000) = 163 
    [15.000, 17.500) = 103 
    [17.500, 20.000) = 89 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 53 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.894 ms/op
     p(50.0000) =      4.325 ms/op
     p(90.0000) =      6.160 ms/op
     p(95.0000) =      6.955 ms/op
     p(99.0000) =      8.929 ms/op
     p(99.9000) =     16.646 ms/op
     p(99.9900) =     24.483 ms/op
     p(99.9990) =     25.720 ms/op
     p(99.9999) =     25.756 ms/op
    p(100.0000) =     25.756 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.447 ± 1.605  ops/ms
ClientGrpc.existUser                       thrpt       3   9.900 ± 1.169  ops/ms
ClientGrpc.getUser                         thrpt       3   9.319 ± 5.635  ops/ms
ClientGrpc.listUser                        thrpt       3   6.951 ± 1.201  ops/ms
ClientGrpc.createUser                       avgt       3   3.460 ± 0.544   ms/op
ClientGrpc.existUser                        avgt       3   3.245 ± 1.173   ms/op
ClientGrpc.getUser                          avgt       3   3.473 ± 1.239   ms/op
ClientGrpc.listUser                         avgt       3   4.647 ± 1.344   ms/op
ClientGrpc.createUser                     sample  277903   3.454 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.379           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.330           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.358           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.784           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.964           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.603           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.270           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.084           ms/op
ClientGrpc.existUser                      sample  303476   3.162 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.719           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.072           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.924           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.325           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.456           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.486           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.908           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.480           ms/op
ClientGrpc.getUser                        sample  273871   3.504 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.910           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.396           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.383           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.817           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.193           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.633           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.465           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.186           ms/op
ClientGrpc.listUser                       sample  208475   4.606 ± 0.010   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.894           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.325           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.160           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.955           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.929           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.646           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.483           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.756           ms/op
