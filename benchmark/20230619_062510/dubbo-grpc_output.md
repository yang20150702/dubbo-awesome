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
# Warmup Iteration   1: 4.555 ops/ms
# Warmup Iteration   2: 9.491 ops/ms
# Warmup Iteration   3: 10.369 ops/ms
Iteration   1: 10.686 ops/ms
Iteration   2: 10.779 ops/ms
Iteration   3: 10.577 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.681 ±(99.9%) 1.839 ops/ms [Average]
  (min, avg, max) = (10.577, 10.681, 10.779), stdev = 0.101
  CI (99.9%): [8.842, 12.519] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 8.019 ops/ms
# Warmup Iteration   2: 10.809 ops/ms
# Warmup Iteration   3: 11.351 ops/ms
Iteration   1: 11.291 ops/ms
Iteration   2: 11.296 ops/ms
Iteration   3: 11.598 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.395 ±(99.9%) 3.214 ops/ms [Average]
  (min, avg, max) = (11.291, 11.395, 11.598), stdev = 0.176
  CI (99.9%): [8.181, 14.609] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.563 ops/ms
# Warmup Iteration   2: 10.604 ops/ms
# Warmup Iteration   3: 11.026 ops/ms
Iteration   1: 10.879 ops/ms
Iteration   2: 10.871 ops/ms
Iteration   3: 10.895 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.882 ±(99.9%) 0.221 ops/ms [Average]
  (min, avg, max) = (10.871, 10.882, 10.895), stdev = 0.012
  CI (99.9%): [10.661, 11.103] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.951 ops/ms
# Warmup Iteration   2: 8.088 ops/ms
# Warmup Iteration   3: 8.116 ops/ms
Iteration   1: 8.300 ops/ms
Iteration   2: 8.187 ops/ms
Iteration   3: 8.420 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.303 ±(99.9%) 2.124 ops/ms [Average]
  (min, avg, max) = (8.187, 8.303, 8.420), stdev = 0.116
  CI (99.9%): [6.179, 10.426] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.972 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.159 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.035 ±(99.9%) 0.003 ms/op
Iteration   1: 2.996 ±(99.9%) 0.003 ms/op
Iteration   2: 3.024 ±(99.9%) 0.002 ms/op
Iteration   3: 3.025 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.015 ±(99.9%) 0.302 ms/op [Average]
  (min, avg, max) = (2.996, 3.015, 3.025), stdev = 0.017
  CI (99.9%): [2.713, 3.316] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.572 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.918 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.838 ±(99.9%) 0.003 ms/op
Iteration   1: 2.808 ±(99.9%) 0.003 ms/op
Iteration   2: 2.805 ±(99.9%) 0.003 ms/op
Iteration   3: 2.819 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.811 ±(99.9%) 0.138 ms/op [Average]
  (min, avg, max) = (2.805, 2.811, 2.819), stdev = 0.008
  CI (99.9%): [2.672, 2.949] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.911 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.987 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.956 ±(99.9%) 0.004 ms/op
Iteration   1: 2.959 ±(99.9%) 0.002 ms/op
Iteration   2: 2.921 ±(99.9%) 0.003 ms/op
Iteration   3: 2.955 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.945 ±(99.9%) 0.384 ms/op [Average]
  (min, avg, max) = (2.921, 2.945, 2.959), stdev = 0.021
  CI (99.9%): [2.561, 3.329] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.102 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.994 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.880 ±(99.9%) 0.019 ms/op
Iteration   1: 3.849 ±(99.9%) 0.008 ms/op
Iteration   2: 3.918 ±(99.9%) 0.009 ms/op
Iteration   3: 3.845 ±(99.9%) 0.028 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.871 ±(99.9%) 0.752 ms/op [Average]
  (min, avg, max) = (3.845, 3.871, 3.918), stdev = 0.041
  CI (99.9%): [3.119, 4.623] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.825 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.050 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.991 ±(99.9%) 0.006 ms/op
Iteration   1: 2.963 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.582 ms/op
                 createUser·p0.50:   2.953 ms/op
                 createUser·p0.90:   3.494 ms/op
                 createUser·p0.95:   3.703 ms/op
                 createUser·p0.99:   4.317 ms/op
                 createUser·p0.999:  7.684 ms/op
                 createUser·p0.9999: 12.389 ms/op
                 createUser·p1.00:   12.714 ms/op

Iteration   2: 2.939 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.644 ms/op
                 createUser·p0.50:   2.933 ms/op
                 createUser·p0.90:   3.535 ms/op
                 createUser·p0.95:   3.777 ms/op
                 createUser·p0.99:   4.404 ms/op
                 createUser·p0.999:  7.448 ms/op
                 createUser·p0.9999: 13.072 ms/op
                 createUser·p1.00:   13.943 ms/op

Iteration   3: 2.946 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.633 ms/op
                 createUser·p0.50:   2.953 ms/op
                 createUser·p0.90:   3.457 ms/op
                 createUser·p0.95:   3.703 ms/op
                 createUser·p0.99:   4.489 ms/op
                 createUser·p0.999:  7.389 ms/op
                 createUser·p0.9999: 16.075 ms/op
                 createUser·p1.00:   16.663 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 325493
  mean =      2.949 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2536 
    [ 1.250,  2.500) = 36908 
    [ 2.500,  3.750) = 270721 
    [ 3.750,  5.000) = 14093 
    [ 5.000,  6.250) = 562 
    [ 6.250,  7.500) = 367 
    [ 7.500,  8.750) = 101 
    [ 8.750, 10.000) = 13 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 86 
    [12.500, 13.750) = 53 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 28 
    [16.250, 17.500) = 6 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.582 ms/op
     p(50.0000) =      2.945 ms/op
     p(90.0000) =      3.494 ms/op
     p(95.0000) =      3.727 ms/op
     p(99.0000) =      4.399 ms/op
     p(99.9000) =      7.426 ms/op
     p(99.9900) =     15.565 ms/op
     p(99.9990) =     16.646 ms/op
     p(99.9999) =     16.663 ms/op
    p(100.0000) =     16.663 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.813 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 2.884 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.765 ±(99.9%) 0.007 ms/op
Iteration   1: 2.854 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.791 ms/op
                 existUser·p0.50:   2.830 ms/op
                 existUser·p0.90:   3.293 ms/op
                 existUser·p0.95:   3.543 ms/op
                 existUser·p0.99:   4.563 ms/op
                 existUser·p0.999:  6.455 ms/op
                 existUser·p0.9999: 11.593 ms/op
                 existUser·p1.00:   11.846 ms/op

Iteration   2: 2.826 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.742 ms/op
                 existUser·p0.50:   2.839 ms/op
                 existUser·p0.90:   3.355 ms/op
                 existUser·p0.95:   3.543 ms/op
                 existUser·p0.99:   4.423 ms/op
                 existUser·p0.999:  8.269 ms/op
                 existUser·p0.9999: 13.927 ms/op
                 existUser·p1.00:   14.238 ms/op

Iteration   3: 2.907 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.606 ms/op
                 existUser·p0.50:   2.875 ms/op
                 existUser·p0.90:   3.408 ms/op
                 existUser·p0.95:   3.564 ms/op
                 existUser·p0.99:   4.293 ms/op
                 existUser·p0.999:  7.075 ms/op
                 existUser·p0.9999: 14.794 ms/op
                 existUser·p1.00:   16.368 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 335403
  mean =      2.862 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2552 
    [ 1.250,  2.500) = 49443 
    [ 2.500,  3.750) = 274012 
    [ 3.750,  5.000) = 8262 
    [ 5.000,  6.250) = 647 
    [ 6.250,  7.500) = 220 
    [ 7.500,  8.750) = 43 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 83 
    [11.250, 12.500) = 44 
    [12.500, 13.750) = 40 
    [13.750, 15.000) = 49 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.606 ms/op
     p(50.0000) =      2.847 ms/op
     p(90.0000) =      3.359 ms/op
     p(95.0000) =      3.551 ms/op
     p(99.0000) =      4.456 ms/op
     p(99.9000) =      6.947 ms/op
     p(99.9900) =     14.187 ms/op
     p(99.9990) =     16.190 ms/op
     p(99.9999) =     16.368 ms/op
    p(100.0000) =     16.368 ms/op


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
# Warmup Iteration   1: 3.794 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.119 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.988 ±(99.9%) 0.006 ms/op
Iteration   1: 2.969 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.743 ms/op
                 getUser·p0.50:   2.961 ms/op
                 getUser·p0.90:   3.338 ms/op
                 getUser·p0.95:   3.576 ms/op
                 getUser·p0.99:   4.514 ms/op
                 getUser·p0.999:  6.208 ms/op
                 getUser·p0.9999: 17.203 ms/op
                 getUser·p1.00:   17.367 ms/op

Iteration   2: 2.947 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.840 ms/op
                 getUser·p0.50:   2.949 ms/op
                 getUser·p0.90:   3.465 ms/op
                 getUser·p0.95:   3.678 ms/op
                 getUser·p0.99:   4.235 ms/op
                 getUser·p0.999:  7.548 ms/op
                 getUser·p0.9999: 12.279 ms/op
                 getUser·p1.00:   12.976 ms/op

Iteration   3: 2.938 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.577 ms/op
                 getUser·p0.50:   2.953 ms/op
                 getUser·p0.90:   3.367 ms/op
                 getUser·p0.95:   3.539 ms/op
                 getUser·p0.99:   4.227 ms/op
                 getUser·p0.999:  7.135 ms/op
                 getUser·p0.9999: 23.531 ms/op
                 getUser·p1.00:   24.707 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 325129
  mean =      2.951 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28040 
    [ 2.500,  5.000) = 296020 
    [ 5.000,  7.500) = 787 
    [ 7.500, 10.000) = 90 
    [10.000, 12.500) = 95 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.577 ms/op
     p(50.0000) =      2.953 ms/op
     p(90.0000) =      3.396 ms/op
     p(95.0000) =      3.604 ms/op
     p(99.0000) =      4.309 ms/op
     p(99.9000) =      7.110 ms/op
     p(99.9900) =     19.697 ms/op
     p(99.9990) =     23.773 ms/op
     p(99.9999) =     24.707 ms/op
    p(100.0000) =     24.707 ms/op


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
# Warmup Iteration   1: 4.330 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.099 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.853 ±(99.9%) 0.010 ms/op
Iteration   1: 3.863 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.061 ms/op
                 listUser·p0.50:   3.752 ms/op
                 listUser·p0.90:   4.669 ms/op
                 listUser·p0.95:   5.431 ms/op
                 listUser·p0.99:   6.595 ms/op
                 listUser·p0.999:  12.360 ms/op
                 listUser·p0.9999: 13.950 ms/op
                 listUser·p1.00:   14.828 ms/op

Iteration   2: 3.896 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.067 ms/op
                 listUser·p0.50:   3.760 ms/op
                 listUser·p0.90:   4.694 ms/op
                 listUser·p0.95:   5.579 ms/op
                 listUser·p0.99:   6.693 ms/op
                 listUser·p0.999:  13.833 ms/op
                 listUser·p0.9999: 25.801 ms/op
                 listUser·p1.00:   26.247 ms/op

Iteration   3: 3.926 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.927 ms/op
                 listUser·p0.50:   3.764 ms/op
                 listUser·p0.90:   5.095 ms/op
                 listUser·p0.95:   5.603 ms/op
                 listUser·p0.99:   6.750 ms/op
                 listUser·p0.999:  13.435 ms/op
                 listUser·p0.9999: 17.792 ms/op
                 listUser·p1.00:   21.135 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 246371
  mean =      3.895 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5260 
    [ 2.500,  5.000) = 219233 
    [ 5.000,  7.500) = 20915 
    [ 7.500, 10.000) = 532 
    [10.000, 12.500) = 156 
    [12.500, 15.000) = 167 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.927 ms/op
     p(50.0000) =      3.760 ms/op
     p(90.0000) =      4.891 ms/op
     p(95.0000) =      5.554 ms/op
     p(99.0000) =      6.685 ms/op
     p(99.9000) =     12.894 ms/op
     p(99.9900) =     24.058 ms/op
     p(99.9990) =     26.199 ms/op
     p(99.9999) =     26.247 ms/op
    p(100.0000) =     26.247 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.681 ± 1.839  ops/ms
ClientGrpc.existUser                       thrpt       3  11.395 ± 3.214  ops/ms
ClientGrpc.getUser                         thrpt       3  10.882 ± 0.221  ops/ms
ClientGrpc.listUser                        thrpt       3   8.303 ± 2.124  ops/ms
ClientGrpc.createUser                       avgt       3   3.015 ± 0.302   ms/op
ClientGrpc.existUser                        avgt       3   2.811 ± 0.138   ms/op
ClientGrpc.getUser                          avgt       3   2.945 ± 0.384   ms/op
ClientGrpc.listUser                         avgt       3   3.871 ± 0.752   ms/op
ClientGrpc.createUser                     sample  325493   2.949 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.582           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.945           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.494           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.727           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.399           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.426           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          15.565           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          16.663           ms/op
ClientGrpc.existUser                      sample  335403   2.862 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.606           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.847           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.359           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.551           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.456           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.947           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.187           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.368           ms/op
ClientGrpc.getUser                        sample  325129   2.951 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.577           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.953           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.396           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.604           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.309           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.110           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.697           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.707           ms/op
ClientGrpc.listUser                       sample  246371   3.895 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.927           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.760           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.891           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.554           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.685           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          12.894           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.058           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.247           ms/op
