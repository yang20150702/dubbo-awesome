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
# Warmup Iteration   1: 2.464 ops/ms
# Warmup Iteration   2: 5.844 ops/ms
# Warmup Iteration   3: 7.539 ops/ms
Iteration   1: 7.976 ops/ms
Iteration   2: 8.052 ops/ms
Iteration   3: 8.075 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.034 ±(99.9%) 0.939 ops/ms [Average]
  (min, avg, max) = (7.976, 8.034, 8.075), stdev = 0.051
  CI (99.9%): [7.095, 8.973] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 5.100 ops/ms
# Warmup Iteration   2: 7.847 ops/ms
# Warmup Iteration   3: 8.620 ops/ms
Iteration   1: 8.663 ops/ms
Iteration   2: 8.723 ops/ms
Iteration   3: 8.682 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.689 ±(99.9%) 0.558 ops/ms [Average]
  (min, avg, max) = (8.663, 8.689, 8.723), stdev = 0.031
  CI (99.9%): [8.131, 9.247] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 4.529 ops/ms
# Warmup Iteration   2: 6.826 ops/ms
# Warmup Iteration   3: 7.702 ops/ms
Iteration   1: 7.957 ops/ms
Iteration   2: 7.883 ops/ms
Iteration   3: 7.777 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.872 ±(99.9%) 1.642 ops/ms [Average]
  (min, avg, max) = (7.777, 7.872, 7.957), stdev = 0.090
  CI (99.9%): [6.230, 9.515] (assumes normal distribution)


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
# Warmup Iteration   1: 3.675 ops/ms
# Warmup Iteration   2: 5.965 ops/ms
# Warmup Iteration   3: 6.251 ops/ms
Iteration   1: 6.112 ops/ms
Iteration   2: 6.220 ops/ms
Iteration   3: 6.376 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.236 ±(99.9%) 2.428 ops/ms [Average]
  (min, avg, max) = (6.112, 6.236, 6.376), stdev = 0.133
  CI (99.9%): [3.808, 8.664] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.497 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.279 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.054 ±(99.9%) 0.003 ms/op
Iteration   1: 3.802 ±(99.9%) 0.004 ms/op
Iteration   2: 3.904 ±(99.9%) 0.003 ms/op
Iteration   3: 4.021 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.909 ±(99.9%) 1.998 ms/op [Average]
  (min, avg, max) = (3.802, 3.909, 4.021), stdev = 0.110
  CI (99.9%): [1.911, 5.908] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 5.835 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.008 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.801 ±(99.9%) 0.006 ms/op
Iteration   1: 3.792 ±(99.9%) 0.004 ms/op
Iteration   2: 3.793 ±(99.9%) 0.002 ms/op
Iteration   3: 3.791 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.792 ±(99.9%) 0.019 ms/op [Average]
  (min, avg, max) = (3.791, 3.792, 3.793), stdev = 0.001
  CI (99.9%): [3.773, 3.811] (assumes normal distribution)


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
# Warmup Iteration   1: 5.699 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.275 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.195 ±(99.9%) 0.007 ms/op
Iteration   1: 4.037 ±(99.9%) 0.004 ms/op
Iteration   2: 3.948 ±(99.9%) 0.004 ms/op
Iteration   3: 4.002 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.996 ±(99.9%) 0.815 ms/op [Average]
  (min, avg, max) = (3.948, 3.996, 4.037), stdev = 0.045
  CI (99.9%): [3.181, 4.810] (assumes normal distribution)


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
# Warmup Iteration   1: 7.359 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 5.564 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 5.234 ±(99.9%) 0.028 ms/op
Iteration   1: 5.148 ±(99.9%) 0.022 ms/op
Iteration   2: 5.084 ±(99.9%) 0.014 ms/op
Iteration   3: 5.078 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.103 ±(99.9%) 0.706 ms/op [Average]
  (min, avg, max) = (5.078, 5.103, 5.148), stdev = 0.039
  CI (99.9%): [4.397, 5.809] (assumes normal distribution)


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
# Warmup Iteration   1: 6.332 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 4.474 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.090 ±(99.9%) 0.012 ms/op
Iteration   1: 4.075 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.227 ms/op
                 createUser·p0.50:   3.912 ms/op
                 createUser·p0.90:   5.005 ms/op
                 createUser·p0.95:   5.480 ms/op
                 createUser·p0.99:   8.061 ms/op
                 createUser·p0.999:  15.802 ms/op
                 createUser·p0.9999: 36.037 ms/op
                 createUser·p1.00:   37.552 ms/op

Iteration   2: 3.935 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.929 ms/op
                 createUser·p0.50:   3.838 ms/op
                 createUser·p0.90:   4.776 ms/op
                 createUser·p0.95:   5.226 ms/op
                 createUser·p0.99:   6.865 ms/op
                 createUser·p0.999:  13.948 ms/op
                 createUser·p0.9999: 25.191 ms/op
                 createUser·p1.00:   25.821 ms/op

Iteration   3: 3.939 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.964 ms/op
                 createUser·p0.50:   3.830 ms/op
                 createUser·p0.90:   4.784 ms/op
                 createUser·p0.95:   5.226 ms/op
                 createUser·p0.99:   6.709 ms/op
                 createUser·p0.999:  17.191 ms/op
                 createUser·p0.9999: 20.013 ms/op
                 createUser·p1.00:   20.578 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 240912
  mean =      3.982 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5373 
    [ 2.500,  5.000) = 216294 
    [ 5.000,  7.500) = 17165 
    [ 7.500, 10.000) = 1236 
    [10.000, 12.500) = 408 
    [12.500, 15.000) = 159 
    [15.000, 17.500) = 140 
    [17.500, 20.000) = 80 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 14 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 20 
    [35.000, 37.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.929 ms/op
     p(50.0000) =      3.858 ms/op
     p(90.0000) =      4.858 ms/op
     p(95.0000) =      5.325 ms/op
     p(99.0000) =      7.160 ms/op
     p(99.9000) =     15.486 ms/op
     p(99.9900) =     33.411 ms/op
     p(99.9990) =     37.329 ms/op
     p(99.9999) =     37.552 ms/op
    p(100.0000) =     37.552 ms/op


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
# Warmup Iteration   1: 5.978 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 4.306 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.052 ±(99.9%) 0.014 ms/op
Iteration   1: 3.772 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.012 ms/op
                 existUser·p0.50:   3.658 ms/op
                 existUser·p0.90:   4.563 ms/op
                 existUser·p0.95:   4.964 ms/op
                 existUser·p0.99:   6.537 ms/op
                 existUser·p0.999:  11.603 ms/op
                 existUser·p0.9999: 16.941 ms/op
                 existUser·p1.00:   17.269 ms/op

Iteration   2: 3.744 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.745 ms/op
                 existUser·p0.50:   3.641 ms/op
                 existUser·p0.90:   4.547 ms/op
                 existUser·p0.95:   5.014 ms/op
                 existUser·p0.99:   6.906 ms/op
                 existUser·p0.999:  13.208 ms/op
                 existUser·p0.9999: 18.872 ms/op
                 existUser·p1.00:   19.333 ms/op

Iteration   3: 3.832 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.467 ms/op
                 existUser·p0.50:   3.650 ms/op
                 existUser·p0.90:   4.686 ms/op
                 existUser·p0.95:   5.226 ms/op
                 existUser·p0.99:   8.634 ms/op
                 existUser·p0.999:  16.090 ms/op
                 existUser·p0.9999: 19.191 ms/op
                 existUser·p1.00:   20.021 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 253783
  mean =      3.783 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6152 
    [ 2.500,  5.000) = 233729 
    [ 5.000,  7.500) = 11494 
    [ 7.500, 10.000) = 1365 
    [10.000, 12.500) = 616 
    [12.500, 15.000) = 221 
    [15.000, 17.500) = 132 
    [17.500, 20.000) = 73 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.467 ms/op
     p(50.0000) =      3.650 ms/op
     p(90.0000) =      4.596 ms/op
     p(95.0000) =      5.063 ms/op
     p(99.0000) =      7.324 ms/op
     p(99.9000) =     13.746 ms/op
     p(99.9900) =     18.907 ms/op
     p(99.9990) =     19.757 ms/op
     p(99.9999) =     20.021 ms/op
    p(100.0000) =     20.021 ms/op


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
# Warmup Iteration   1: 6.339 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 4.289 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.296 ±(99.9%) 0.016 ms/op
Iteration   1: 3.987 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.881 ms/op
                 getUser·p0.50:   3.916 ms/op
                 getUser·p0.90:   5.038 ms/op
                 getUser·p0.95:   5.480 ms/op
                 getUser·p0.99:   6.742 ms/op
                 getUser·p0.999:  12.291 ms/op
                 getUser·p0.9999: 17.170 ms/op
                 getUser·p1.00:   17.564 ms/op

Iteration   2: 3.941 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.966 ms/op
                 getUser·p0.50:   3.846 ms/op
                 getUser·p0.90:   4.891 ms/op
                 getUser·p0.95:   5.317 ms/op
                 getUser·p0.99:   6.947 ms/op
                 getUser·p0.999:  12.042 ms/op
                 getUser·p0.9999: 19.038 ms/op
                 getUser·p1.00:   21.168 ms/op

Iteration   3: 4.076 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.873 ms/op
                 getUser·p0.50:   3.998 ms/op
                 getUser·p0.90:   5.095 ms/op
                 getUser·p0.95:   5.415 ms/op
                 getUser·p0.99:   6.365 ms/op
                 getUser·p0.999:  10.375 ms/op
                 getUser·p0.9999: 21.057 ms/op
                 getUser·p1.00:   22.053 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 239811
  mean =      4.001 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9960 
    [ 2.500,  5.000) = 204944 
    [ 5.000,  7.500) = 23590 
    [ 7.500, 10.000) = 820 
    [10.000, 12.500) = 311 
    [12.500, 15.000) = 53 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 63 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.873 ms/op
     p(50.0000) =      3.916 ms/op
     p(90.0000) =      5.022 ms/op
     p(95.0000) =      5.415 ms/op
     p(99.0000) =      6.652 ms/op
     p(99.9000) =     11.721 ms/op
     p(99.9900) =     18.907 ms/op
     p(99.9990) =     21.653 ms/op
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
# Warmup Iteration   1: 7.646 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 5.645 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 5.470 ±(99.9%) 0.024 ms/op
Iteration   1: 5.325 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.638 ms/op
                 listUser·p0.50:   4.973 ms/op
                 listUser·p0.90:   7.242 ms/op
                 listUser·p0.95:   8.233 ms/op
                 listUser·p0.99:   10.945 ms/op
                 listUser·p0.999:  21.168 ms/op
                 listUser·p0.9999: 27.295 ms/op
                 listUser·p1.00:   27.820 ms/op

Iteration   2: 5.298 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.194 ms/op
                 listUser·p0.50:   4.981 ms/op
                 listUser·p0.90:   7.201 ms/op
                 listUser·p0.95:   8.118 ms/op
                 listUser·p0.99:   10.502 ms/op
                 listUser·p0.999:  17.014 ms/op
                 listUser·p0.9999: 21.423 ms/op
                 listUser·p1.00:   21.758 ms/op

Iteration   3: 5.324 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.300 ms/op
                 listUser·p0.50:   4.964 ms/op
                 listUser·p0.90:   7.201 ms/op
                 listUser·p0.95:   8.135 ms/op
                 listUser·p0.99:   10.617 ms/op
                 listUser·p0.999:  20.152 ms/op
                 listUser·p0.9999: 24.510 ms/op
                 listUser·p1.00:   25.035 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 180591
  mean =      5.316 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 422 
    [ 2.500,  5.000) = 92141 
    [ 5.000,  7.500) = 73099 
    [ 7.500, 10.000) = 12403 
    [10.000, 12.500) = 1589 
    [12.500, 15.000) = 461 
    [15.000, 17.500) = 183 
    [17.500, 20.000) = 125 
    [20.000, 22.500) = 107 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      1.194 ms/op
     p(50.0000) =      4.973 ms/op
     p(90.0000) =      7.217 ms/op
     p(95.0000) =      8.159 ms/op
     p(99.0000) =     10.666 ms/op
     p(99.9000) =     19.772 ms/op
     p(99.9900) =     25.330 ms/op
     p(99.9990) =     27.767 ms/op
     p(99.9999) =     27.820 ms/op
    p(100.0000) =     27.820 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.034 ± 0.939  ops/ms
ClientGrpc.existUser                       thrpt       3   8.689 ± 0.558  ops/ms
ClientGrpc.getUser                         thrpt       3   7.872 ± 1.642  ops/ms
ClientGrpc.listUser                        thrpt       3   6.236 ± 2.428  ops/ms
ClientGrpc.createUser                       avgt       3   3.909 ± 1.998   ms/op
ClientGrpc.existUser                        avgt       3   3.792 ± 0.019   ms/op
ClientGrpc.getUser                          avgt       3   3.996 ± 0.815   ms/op
ClientGrpc.listUser                         avgt       3   5.103 ± 0.706   ms/op
ClientGrpc.createUser                     sample  240912   3.982 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.929           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.858           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.858           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.325           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.160           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          15.486           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          33.411           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          37.552           ms/op
ClientGrpc.existUser                      sample  253783   3.783 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.467           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.650           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.596           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.063           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.324           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          13.746           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.907           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.021           ms/op
ClientGrpc.getUser                        sample  239811   4.001 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.873           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.916           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.022           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.415           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.652           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.721           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.907           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.053           ms/op
ClientGrpc.listUser                       sample  180591   5.316 ± 0.012   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.194           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.973           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.217           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.159           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.666           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.772           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.330           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.820           ms/op
