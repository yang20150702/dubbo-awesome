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
# Warmup Iteration   1: 1.869 ops/ms
# Warmup Iteration   2: 5.055 ops/ms
# Warmup Iteration   3: 6.716 ops/ms
Iteration   1: 7.138 ops/ms
Iteration   2: 7.037 ops/ms
Iteration   3: 7.113 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.096 ±(99.9%) 0.958 ops/ms [Average]
  (min, avg, max) = (7.037, 7.096, 7.138), stdev = 0.052
  CI (99.9%): [6.139, 8.054] (assumes normal distribution)


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
# Warmup Iteration   1: 4.155 ops/ms
# Warmup Iteration   2: 6.791 ops/ms
# Warmup Iteration   3: 7.201 ops/ms
Iteration   1: 7.779 ops/ms
Iteration   2: 7.986 ops/ms
Iteration   3: 7.792 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.853 ±(99.9%) 2.115 ops/ms [Average]
  (min, avg, max) = (7.779, 7.853, 7.986), stdev = 0.116
  CI (99.9%): [5.738, 9.967] (assumes normal distribution)


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
# Warmup Iteration   1: 4.126 ops/ms
# Warmup Iteration   2: 6.932 ops/ms
# Warmup Iteration   3: 6.953 ops/ms
Iteration   1: 7.351 ops/ms
Iteration   2: 7.387 ops/ms
Iteration   3: 7.144 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.294 ±(99.9%) 2.394 ops/ms [Average]
  (min, avg, max) = (7.144, 7.294, 7.387), stdev = 0.131
  CI (99.9%): [4.900, 9.688] (assumes normal distribution)


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
# Warmup Iteration   1: 3.613 ops/ms
# Warmup Iteration   2: 4.976 ops/ms
# Warmup Iteration   3: 5.420 ops/ms
Iteration   1: 5.468 ops/ms
Iteration   2: 5.579 ops/ms
Iteration   3: 5.599 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.549 ±(99.9%) 1.282 ops/ms [Average]
  (min, avg, max) = (5.468, 5.549, 5.599), stdev = 0.070
  CI (99.9%): [4.266, 6.831] (assumes normal distribution)


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
# Warmup Iteration   1: 7.247 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.808 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.749 ±(99.9%) 0.008 ms/op
Iteration   1: 4.446 ±(99.9%) 0.003 ms/op
Iteration   2: 4.543 ±(99.9%) 0.003 ms/op
Iteration   3: 4.397 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.462 ±(99.9%) 1.352 ms/op [Average]
  (min, avg, max) = (4.397, 4.462, 4.543), stdev = 0.074
  CI (99.9%): [3.110, 5.813] (assumes normal distribution)


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
# Warmup Iteration   1: 6.406 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.652 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.518 ±(99.9%) 0.004 ms/op
Iteration   1: 4.428 ±(99.9%) 0.003 ms/op
Iteration   2: 4.430 ±(99.9%) 0.003 ms/op
Iteration   3: 4.264 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.374 ±(99.9%) 1.730 ms/op [Average]
  (min, avg, max) = (4.264, 4.374, 4.430), stdev = 0.095
  CI (99.9%): [2.644, 6.103] (assumes normal distribution)


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
# Warmup Iteration   1: 7.292 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.742 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.529 ±(99.9%) 0.005 ms/op
Iteration   1: 4.383 ±(99.9%) 0.003 ms/op
Iteration   2: 4.476 ±(99.9%) 0.003 ms/op
Iteration   3: 4.476 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.445 ±(99.9%) 0.979 ms/op [Average]
  (min, avg, max) = (4.383, 4.445, 4.476), stdev = 0.054
  CI (99.9%): [3.466, 5.424] (assumes normal distribution)


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
# Warmup Iteration   1: 8.033 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 6.361 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 5.969 ±(99.9%) 0.015 ms/op
Iteration   1: 5.682 ±(99.9%) 0.015 ms/op
Iteration   2: 5.673 ±(99.9%) 0.009 ms/op
Iteration   3: 5.730 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.695 ±(99.9%) 0.555 ms/op [Average]
  (min, avg, max) = (5.673, 5.695, 5.730), stdev = 0.030
  CI (99.9%): [5.140, 6.250] (assumes normal distribution)


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
# Warmup Iteration   1: 7.253 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 4.740 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.705 ±(99.9%) 0.014 ms/op
Iteration   1: 4.507 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.288 ms/op
                 createUser·p0.50:   4.424 ms/op
                 createUser·p0.90:   5.521 ms/op
                 createUser·p0.95:   5.947 ms/op
                 createUser·p0.99:   7.637 ms/op
                 createUser·p0.999:  13.451 ms/op
                 createUser·p0.9999: 25.864 ms/op
                 createUser·p1.00:   28.082 ms/op

Iteration   2: 4.714 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.362 ms/op
                 createUser·p0.50:   4.563 ms/op
                 createUser·p0.90:   5.833 ms/op
                 createUser·p0.95:   6.267 ms/op
                 createUser·p0.99:   8.454 ms/op
                 createUser·p0.999:  13.042 ms/op
                 createUser·p0.9999: 27.886 ms/op
                 createUser·p1.00:   28.246 ms/op

Iteration   3: 4.461 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   0.858 ms/op
                 createUser·p0.50:   4.399 ms/op
                 createUser·p0.90:   5.448 ms/op
                 createUser·p0.95:   5.849 ms/op
                 createUser·p0.99:   7.012 ms/op
                 createUser·p0.999:  13.794 ms/op
                 createUser·p0.9999: 31.309 ms/op
                 createUser·p1.00:   31.850 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 210561
  mean =      4.558 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4221 
    [ 2.500,  5.000) = 154187 
    [ 5.000,  7.500) = 49739 
    [ 7.500, 10.000) = 1643 
    [10.000, 12.500) = 447 
    [12.500, 15.000) = 183 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 52 
    [27.500, 30.000) = 38 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.858 ms/op
     p(50.0000) =      4.456 ms/op
     p(90.0000) =      5.612 ms/op
     p(95.0000) =      6.029 ms/op
     p(99.0000) =      7.761 ms/op
     p(99.9000) =     13.206 ms/op
     p(99.9900) =     28.277 ms/op
     p(99.9990) =     31.850 ms/op
     p(99.9999) =     31.850 ms/op
    p(100.0000) =     31.850 ms/op


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
# Warmup Iteration   1: 5.911 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 4.626 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.246 ±(99.9%) 0.011 ms/op
Iteration   1: 4.297 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.243 ms/op
                 existUser·p0.50:   4.190 ms/op
                 existUser·p0.90:   5.243 ms/op
                 existUser·p0.95:   5.743 ms/op
                 existUser·p0.99:   7.714 ms/op
                 existUser·p0.999:  11.623 ms/op
                 existUser·p0.9999: 16.591 ms/op
                 existUser·p1.00:   17.072 ms/op

Iteration   2: 4.456 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.982 ms/op
                 existUser·p0.50:   4.342 ms/op
                 existUser·p0.90:   5.497 ms/op
                 existUser·p0.95:   5.898 ms/op
                 existUser·p0.99:   8.207 ms/op
                 existUser·p0.999:  12.882 ms/op
                 existUser·p0.9999: 20.567 ms/op
                 existUser·p1.00:   21.004 ms/op

Iteration   3: 4.327 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.811 ms/op
                 existUser·p0.50:   4.276 ms/op
                 existUser·p0.90:   5.431 ms/op
                 existUser·p0.95:   5.759 ms/op
                 existUser·p0.99:   7.135 ms/op
                 existUser·p0.999:  15.378 ms/op
                 existUser·p0.9999: 24.616 ms/op
                 existUser·p1.00:   24.740 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 220129
  mean =      4.359 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6441 
    [ 2.500,  5.000) = 172089 
    [ 5.000,  7.500) = 39242 
    [ 7.500, 10.000) = 1650 
    [10.000, 12.500) = 409 
    [12.500, 15.000) = 170 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.811 ms/op
     p(50.0000) =      4.260 ms/op
     p(90.0000) =      5.407 ms/op
     p(95.0000) =      5.800 ms/op
     p(99.0000) =      7.641 ms/op
     p(99.9000) =     13.255 ms/op
     p(99.9900) =     23.587 ms/op
     p(99.9990) =     24.733 ms/op
     p(99.9999) =     24.740 ms/op
    p(100.0000) =     24.740 ms/op


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
# Warmup Iteration   1: 7.041 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 4.946 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.628 ±(99.9%) 0.012 ms/op
Iteration   1: 4.619 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.065 ms/op
                 getUser·p0.50:   4.473 ms/op
                 getUser·p0.90:   5.677 ms/op
                 getUser·p0.95:   6.152 ms/op
                 getUser·p0.99:   8.110 ms/op
                 getUser·p0.999:  13.418 ms/op
                 getUser·p0.9999: 15.997 ms/op
                 getUser·p1.00:   21.037 ms/op

Iteration   2: 4.479 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.178 ms/op
                 getUser·p0.50:   4.407 ms/op
                 getUser·p0.90:   5.480 ms/op
                 getUser·p0.95:   5.882 ms/op
                 getUser·p0.99:   7.086 ms/op
                 getUser·p0.999:  11.970 ms/op
                 getUser·p0.9999: 15.937 ms/op
                 getUser·p1.00:   19.694 ms/op

Iteration   3: 4.501 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.848 ms/op
                 getUser·p0.50:   4.407 ms/op
                 getUser·p0.90:   5.554 ms/op
                 getUser·p0.95:   5.898 ms/op
                 getUser·p0.99:   7.070 ms/op
                 getUser·p0.999:  12.056 ms/op
                 getUser·p0.9999: 20.939 ms/op
                 getUser·p1.00:   21.070 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 211824
  mean =      4.532 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2842 
    [ 2.500,  5.000) = 158554 
    [ 5.000,  7.500) = 48395 
    [ 7.500, 10.000) = 1480 
    [10.000, 12.500) = 336 
    [12.500, 15.000) = 121 
    [15.000, 17.500) = 62 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.848 ms/op
     p(50.0000) =      4.432 ms/op
     p(90.0000) =      5.571 ms/op
     p(95.0000) =      5.972 ms/op
     p(99.0000) =      7.430 ms/op
     p(99.9000) =     12.553 ms/op
     p(99.9900) =     20.337 ms/op
     p(99.9990) =     21.037 ms/op
     p(99.9999) =     21.070 ms/op
    p(100.0000) =     21.070 ms/op


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
# Warmup Iteration   1: 8.289 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 6.442 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 5.832 ±(99.9%) 0.021 ms/op
Iteration   1: 5.645 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.898 ms/op
                 listUser·p0.50:   5.399 ms/op
                 listUser·p0.90:   7.127 ms/op
                 listUser·p0.95:   8.102 ms/op
                 listUser·p0.99:   10.371 ms/op
                 listUser·p0.999:  20.461 ms/op
                 listUser·p0.9999: 26.848 ms/op
                 listUser·p1.00:   27.820 ms/op

Iteration   2: 5.692 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.477 ms/op
                 listUser·p0.50:   5.456 ms/op
                 listUser·p0.90:   7.127 ms/op
                 listUser·p0.95:   8.282 ms/op
                 listUser·p0.99:   10.387 ms/op
                 listUser·p0.999:  21.791 ms/op
                 listUser·p0.9999: 29.849 ms/op
                 listUser·p1.00:   30.540 ms/op

Iteration   3: 5.485 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.526 ms/op
                 listUser·p0.50:   5.276 ms/op
                 listUser·p0.90:   6.783 ms/op
                 listUser·p0.95:   7.832 ms/op
                 listUser·p0.99:   9.912 ms/op
                 listUser·p0.999:  26.991 ms/op
                 listUser·p0.9999: 31.376 ms/op
                 listUser·p1.00:   32.932 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 171120
  mean =      5.606 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 111 
    [ 2.500,  5.000) = 53995 
    [ 5.000,  7.500) = 104528 
    [ 7.500, 10.000) = 10486 
    [10.000, 12.500) = 1402 
    [12.500, 15.000) = 263 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 99 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 28 
    [27.500, 30.000) = 54 
    [30.000, 32.500) = 33 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.477 ms/op
     p(50.0000) =      5.374 ms/op
     p(90.0000) =      7.012 ms/op
     p(95.0000) =      8.077 ms/op
     p(99.0000) =     10.240 ms/op
     p(99.9000) =     21.783 ms/op
     p(99.9900) =     30.521 ms/op
     p(99.9990) =     32.116 ms/op
     p(99.9999) =     32.932 ms/op
    p(100.0000) =     32.932 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.096 ± 0.958  ops/ms
ClientGrpc.existUser                       thrpt       3   7.853 ± 2.115  ops/ms
ClientGrpc.getUser                         thrpt       3   7.294 ± 2.394  ops/ms
ClientGrpc.listUser                        thrpt       3   5.549 ± 1.282  ops/ms
ClientGrpc.createUser                       avgt       3   4.462 ± 1.352   ms/op
ClientGrpc.existUser                        avgt       3   4.374 ± 1.730   ms/op
ClientGrpc.getUser                          avgt       3   4.445 ± 0.979   ms/op
ClientGrpc.listUser                         avgt       3   5.695 ± 0.555   ms/op
ClientGrpc.createUser                     sample  210561   4.558 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.858           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.456           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.612           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.029           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.761           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.206           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          28.277           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          31.850           ms/op
ClientGrpc.existUser                      sample  220129   4.359 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.811           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.260           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.407           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.800           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.641           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          13.255           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          23.587           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          24.740           ms/op
ClientGrpc.getUser                        sample  211824   4.532 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.848           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.432           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.571           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.972           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.430           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.553           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.337           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.070           ms/op
ClientGrpc.listUser                       sample  171120   5.606 ± 0.012   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.477           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.374           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.012           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.077           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.240           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          21.783           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          30.521           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          32.932           ms/op
