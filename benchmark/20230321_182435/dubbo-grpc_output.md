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
# Warmup Iteration   1: 2.337 ops/ms
# Warmup Iteration   2: 5.840 ops/ms
# Warmup Iteration   3: 7.207 ops/ms
Iteration   1: 7.641 ops/ms
Iteration   2: 7.739 ops/ms
Iteration   3: 7.806 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.729 ±(99.9%) 1.508 ops/ms [Average]
  (min, avg, max) = (7.641, 7.729, 7.806), stdev = 0.083
  CI (99.9%): [6.221, 9.237] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.905 ops/ms
# Warmup Iteration   2: 7.785 ops/ms
# Warmup Iteration   3: 8.333 ops/ms
Iteration   1: 8.385 ops/ms
Iteration   2: 8.508 ops/ms
Iteration   3: 8.470 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.454 ±(99.9%) 1.149 ops/ms [Average]
  (min, avg, max) = (8.385, 8.454, 8.508), stdev = 0.063
  CI (99.9%): [7.306, 9.603] (assumes normal distribution)


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
# Warmup Iteration   1: 4.685 ops/ms
# Warmup Iteration   2: 6.865 ops/ms
# Warmup Iteration   3: 7.195 ops/ms
Iteration   1: 7.448 ops/ms
Iteration   2: 7.699 ops/ms
Iteration   3: 7.764 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.637 ±(99.9%) 3.051 ops/ms [Average]
  (min, avg, max) = (7.448, 7.637, 7.764), stdev = 0.167
  CI (99.9%): [4.586, 10.688] (assumes normal distribution)


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
# Warmup Iteration   1: 3.964 ops/ms
# Warmup Iteration   2: 5.275 ops/ms
# Warmup Iteration   3: 5.962 ops/ms
Iteration   1: 5.730 ops/ms
Iteration   2: 5.787 ops/ms
Iteration   3: 5.921 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.813 ±(99.9%) 1.790 ops/ms [Average]
  (min, avg, max) = (5.730, 5.813, 5.921), stdev = 0.098
  CI (99.9%): [4.023, 7.602] (assumes normal distribution)


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
# Warmup Iteration   1: 6.658 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.646 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.297 ±(99.9%) 0.009 ms/op
Iteration   1: 4.351 ±(99.9%) 0.003 ms/op
Iteration   2: 4.229 ±(99.9%) 0.003 ms/op
Iteration   3: 4.213 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.265 ±(99.9%) 1.377 ms/op [Average]
  (min, avg, max) = (4.213, 4.265, 4.351), stdev = 0.075
  CI (99.9%): [2.888, 5.642] (assumes normal distribution)


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
# Warmup Iteration   1: 5.441 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.616 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.145 ±(99.9%) 0.011 ms/op
Iteration   1: 4.031 ±(99.9%) 0.004 ms/op
Iteration   2: 4.196 ±(99.9%) 0.004 ms/op
Iteration   3: 4.005 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.077 ±(99.9%) 1.895 ms/op [Average]
  (min, avg, max) = (4.005, 4.077, 4.196), stdev = 0.104
  CI (99.9%): [2.183, 5.972] (assumes normal distribution)


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
# Warmup Iteration   1: 6.732 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.551 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.197 ±(99.9%) 0.004 ms/op
Iteration   1: 4.099 ±(99.9%) 0.004 ms/op
Iteration   2: 4.211 ±(99.9%) 0.003 ms/op
Iteration   3: 4.185 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.165 ±(99.9%) 1.071 ms/op [Average]
  (min, avg, max) = (4.099, 4.165, 4.211), stdev = 0.059
  CI (99.9%): [3.094, 5.236] (assumes normal distribution)


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
# Warmup Iteration   1: 7.663 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 5.713 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 5.337 ±(99.9%) 0.014 ms/op
Iteration   1: 5.263 ±(99.9%) 0.027 ms/op
Iteration   2: 5.228 ±(99.9%) 0.017 ms/op
Iteration   3: 5.282 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.258 ±(99.9%) 0.503 ms/op [Average]
  (min, avg, max) = (5.228, 5.258, 5.282), stdev = 0.028
  CI (99.9%): [4.755, 5.760] (assumes normal distribution)


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
# Warmup Iteration   1: 6.462 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 4.568 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.157 ±(99.9%) 0.012 ms/op
Iteration   1: 4.147 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.912 ms/op
                 createUser·p0.50:   4.039 ms/op
                 createUser·p0.90:   5.063 ms/op
                 createUser·p0.95:   5.439 ms/op
                 createUser·p0.99:   7.430 ms/op
                 createUser·p0.999:  13.641 ms/op
                 createUser·p0.9999: 20.588 ms/op
                 createUser·p1.00:   21.135 ms/op

Iteration   2: 4.149 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.229 ms/op
                 createUser·p0.50:   4.063 ms/op
                 createUser·p0.90:   5.046 ms/op
                 createUser·p0.95:   5.407 ms/op
                 createUser·p0.99:   6.586 ms/op
                 createUser·p0.999:  12.381 ms/op
                 createUser·p0.9999: 21.383 ms/op
                 createUser·p1.00:   22.544 ms/op

Iteration   3: 4.076 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.851 ms/op
                 createUser·p0.50:   3.957 ms/op
                 createUser·p0.90:   4.940 ms/op
                 createUser·p0.95:   5.333 ms/op
                 createUser·p0.99:   6.808 ms/op
                 createUser·p0.999:  17.909 ms/op
                 createUser·p0.9999: 26.509 ms/op
                 createUser·p1.00:   26.673 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 232742
  mean =      4.124 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4093 
    [ 2.500,  5.000) = 204593 
    [ 5.000,  7.500) = 22295 
    [ 7.500, 10.000) = 1049 
    [10.000, 12.500) = 378 
    [12.500, 15.000) = 122 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 77 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.851 ms/op
     p(50.0000) =      4.018 ms/op
     p(90.0000) =      5.022 ms/op
     p(95.0000) =      5.399 ms/op
     p(99.0000) =      6.889 ms/op
     p(99.9000) =     13.636 ms/op
     p(99.9900) =     25.395 ms/op
     p(99.9990) =     26.673 ms/op
     p(99.9999) =     26.673 ms/op
    p(100.0000) =     26.673 ms/op


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
# Warmup Iteration   1: 5.855 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 4.285 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.929 ±(99.9%) 0.010 ms/op
Iteration   1: 3.799 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.021 ms/op
                 existUser·p0.50:   3.785 ms/op
                 existUser·p0.90:   4.678 ms/op
                 existUser·p0.95:   5.046 ms/op
                 existUser·p0.99:   6.373 ms/op
                 existUser·p0.999:  10.813 ms/op
                 existUser·p0.9999: 15.341 ms/op
                 existUser·p1.00:   15.712 ms/op

Iteration   2: 3.881 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.800 ms/op
                 existUser·p0.50:   3.817 ms/op
                 existUser·p0.90:   4.669 ms/op
                 existUser·p0.95:   5.063 ms/op
                 existUser·p0.99:   6.332 ms/op
                 existUser·p0.999:  14.555 ms/op
                 existUser·p0.9999: 18.014 ms/op
                 existUser·p1.00:   18.317 ms/op

Iteration   3: 3.859 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.069 ms/op
                 existUser·p0.50:   3.817 ms/op
                 existUser·p0.90:   4.784 ms/op
                 existUser·p0.95:   5.136 ms/op
                 existUser·p0.99:   6.152 ms/op
                 existUser·p0.999:  9.144 ms/op
                 existUser·p0.9999: 20.428 ms/op
                 existUser·p1.00:   20.775 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 249613
  mean =      3.846 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12761 
    [ 2.500,  5.000) = 222265 
    [ 5.000,  7.500) = 13488 
    [ 7.500, 10.000) = 768 
    [10.000, 12.500) = 161 
    [12.500, 15.000) = 39 
    [15.000, 17.500) = 81 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.800 ms/op
     p(50.0000) =      3.805 ms/op
     p(90.0000) =      4.710 ms/op
     p(95.0000) =      5.087 ms/op
     p(99.0000) =      6.283 ms/op
     p(99.9000) =     10.764 ms/op
     p(99.9900) =     19.568 ms/op
     p(99.9990) =     20.644 ms/op
     p(99.9999) =     20.775 ms/op
    p(100.0000) =     20.775 ms/op


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
# Warmup Iteration   1: 6.009 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 4.609 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.238 ±(99.9%) 0.014 ms/op
Iteration   1: 4.258 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.049 ms/op
                 getUser·p0.50:   4.108 ms/op
                 getUser·p0.90:   5.505 ms/op
                 getUser·p0.95:   6.095 ms/op
                 getUser·p0.99:   8.315 ms/op
                 getUser·p0.999:  12.778 ms/op
                 getUser·p0.9999: 21.725 ms/op
                 getUser·p1.00:   22.053 ms/op

Iteration   2: 4.255 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.180 ms/op
                 getUser·p0.50:   4.137 ms/op
                 getUser·p0.90:   5.333 ms/op
                 getUser·p0.95:   5.784 ms/op
                 getUser·p0.99:   7.447 ms/op
                 getUser·p0.999:  13.091 ms/op
                 getUser·p0.9999: 18.775 ms/op
                 getUser·p1.00:   20.546 ms/op

Iteration   3: 4.222 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.870 ms/op
                 getUser·p0.50:   4.108 ms/op
                 getUser·p0.90:   5.226 ms/op
                 getUser·p0.95:   5.685 ms/op
                 getUser·p0.99:   7.291 ms/op
                 getUser·p0.999:  11.715 ms/op
                 getUser·p0.9999: 23.391 ms/op
                 getUser·p1.00:   23.953 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 226012
  mean =      4.245 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7086 
    [ 2.500,  5.000) = 181405 
    [ 5.000,  7.500) = 34886 
    [ 7.500, 10.000) = 1938 
    [10.000, 12.500) = 437 
    [12.500, 15.000) = 164 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.870 ms/op
     p(50.0000) =      4.116 ms/op
     p(90.0000) =      5.349 ms/op
     p(95.0000) =      5.852 ms/op
     p(99.0000) =      7.766 ms/op
     p(99.9000) =     12.780 ms/op
     p(99.9900) =     22.577 ms/op
     p(99.9990) =     23.830 ms/op
     p(99.9999) =     23.953 ms/op
    p(100.0000) =     23.953 ms/op


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
# Warmup Iteration   1: 7.770 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 6.150 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 5.444 ±(99.9%) 0.018 ms/op
Iteration   1: 5.373 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.384 ms/op
                 listUser·p0.50:   5.030 ms/op
                 listUser·p0.90:   7.225 ms/op
                 listUser·p0.95:   8.118 ms/op
                 listUser·p0.99:   10.482 ms/op
                 listUser·p0.999:  17.515 ms/op
                 listUser·p0.9999: 21.825 ms/op
                 listUser·p1.00:   22.184 ms/op

Iteration   2: 5.304 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.694 ms/op
                 listUser·p0.50:   5.022 ms/op
                 listUser·p0.90:   6.857 ms/op
                 listUser·p0.95:   7.897 ms/op
                 listUser·p0.99:   10.322 ms/op
                 listUser·p0.999:  17.718 ms/op
                 listUser·p0.9999: 21.127 ms/op
                 listUser·p1.00:   24.117 ms/op

Iteration   3: 5.204 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.313 ms/op
                 listUser·p0.50:   4.989 ms/op
                 listUser·p0.90:   6.701 ms/op
                 listUser·p0.95:   7.553 ms/op
                 listUser·p0.99:   9.437 ms/op
                 listUser·p0.999:  20.957 ms/op
                 listUser·p0.9999: 28.265 ms/op
                 listUser·p1.00:   29.295 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 181358
  mean =      5.293 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 120 
    [ 2.500,  5.000) = 89583 
    [ 5.000,  7.500) = 79596 
    [ 7.500, 10.000) = 10102 
    [10.000, 12.500) = 1373 
    [12.500, 15.000) = 206 
    [15.000, 17.500) = 160 
    [17.500, 20.000) = 107 
    [20.000, 22.500) = 75 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      1.313 ms/op
     p(50.0000) =      5.014 ms/op
     p(90.0000) =      6.939 ms/op
     p(95.0000) =      7.864 ms/op
     p(99.0000) =     10.125 ms/op
     p(99.9000) =     18.219 ms/op
     p(99.9900) =     26.903 ms/op
     p(99.9990) =     29.188 ms/op
     p(99.9999) =     29.295 ms/op
    p(100.0000) =     29.295 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.729 ± 1.508  ops/ms
ClientGrpc.existUser                       thrpt       3   8.454 ± 1.149  ops/ms
ClientGrpc.getUser                         thrpt       3   7.637 ± 3.051  ops/ms
ClientGrpc.listUser                        thrpt       3   5.813 ± 1.790  ops/ms
ClientGrpc.createUser                       avgt       3   4.265 ± 1.377   ms/op
ClientGrpc.existUser                        avgt       3   4.077 ± 1.895   ms/op
ClientGrpc.getUser                          avgt       3   4.165 ± 1.071   ms/op
ClientGrpc.listUser                         avgt       3   5.258 ± 0.503   ms/op
ClientGrpc.createUser                     sample  232742   4.124 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.851           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.018           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.022           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.399           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.889           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.636           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          25.395           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.673           ms/op
ClientGrpc.existUser                      sample  249613   3.846 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.800           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.805           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.710           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.087           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.283           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.764           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.568           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.775           ms/op
ClientGrpc.getUser                        sample  226012   4.245 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.870           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.116           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.349           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.852           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.766           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.780           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.577           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.953           ms/op
ClientGrpc.listUser                       sample  181358   5.293 ± 0.011   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.313           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.014           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.939           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.864           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.125           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.219           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.903           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.295           ms/op
