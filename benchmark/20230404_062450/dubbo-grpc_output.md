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
# Warmup Iteration   1: 2.231 ops/ms
# Warmup Iteration   2: 4.941 ops/ms
# Warmup Iteration   3: 6.726 ops/ms
Iteration   1: 7.206 ops/ms
Iteration   2: 7.075 ops/ms
Iteration   3: 7.014 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.099 ±(99.9%) 1.790 ops/ms [Average]
  (min, avg, max) = (7.014, 7.099, 7.206), stdev = 0.098
  CI (99.9%): [5.308, 8.889] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 4.702 ops/ms
# Warmup Iteration   2: 6.734 ops/ms
# Warmup Iteration   3: 7.362 ops/ms
Iteration   1: 7.633 ops/ms
Iteration   2: 7.543 ops/ms
Iteration   3: 7.625 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.600 ±(99.9%) 0.906 ops/ms [Average]
  (min, avg, max) = (7.543, 7.600, 7.633), stdev = 0.050
  CI (99.9%): [6.695, 8.506] (assumes normal distribution)


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
# Warmup Iteration   1: 4.513 ops/ms
# Warmup Iteration   2: 7.222 ops/ms
# Warmup Iteration   3: 7.590 ops/ms
Iteration   1: 7.723 ops/ms
Iteration   2: 7.457 ops/ms
Iteration   3: 7.146 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.442 ±(99.9%) 5.264 ops/ms [Average]
  (min, avg, max) = (7.146, 7.442, 7.723), stdev = 0.289
  CI (99.9%): [2.178, 12.706] (assumes normal distribution)


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
# Warmup Iteration   1: 3.709 ops/ms
# Warmup Iteration   2: 5.029 ops/ms
# Warmup Iteration   3: 5.577 ops/ms
Iteration   1: 5.630 ops/ms
Iteration   2: 5.631 ops/ms
Iteration   3: 5.652 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.638 ±(99.9%) 0.230 ops/ms [Average]
  (min, avg, max) = (5.630, 5.638, 5.652), stdev = 0.013
  CI (99.9%): [5.408, 5.868] (assumes normal distribution)


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
# Warmup Iteration   1: 6.353 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.416 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.390 ±(99.9%) 0.004 ms/op
Iteration   1: 4.433 ±(99.9%) 0.003 ms/op
Iteration   2: 4.633 ±(99.9%) 0.004 ms/op
Iteration   3: 4.583 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.550 ±(99.9%) 1.907 ms/op [Average]
  (min, avg, max) = (4.433, 4.550, 4.633), stdev = 0.105
  CI (99.9%): [2.643, 6.456] (assumes normal distribution)


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
# Warmup Iteration   1: 6.705 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.341 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.317 ±(99.9%) 0.007 ms/op
Iteration   1: 3.928 ±(99.9%) 0.003 ms/op
Iteration   2: 3.993 ±(99.9%) 0.004 ms/op
Iteration   3: 4.057 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.992 ±(99.9%) 1.176 ms/op [Average]
  (min, avg, max) = (3.928, 3.992, 4.057), stdev = 0.064
  CI (99.9%): [2.817, 5.168] (assumes normal distribution)


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
# Warmup Iteration   1: 6.724 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.701 ±(99.9%) 0.052 ms/op
# Warmup Iteration   3: 4.658 ±(99.9%) 0.009 ms/op
Iteration   1: 4.269 ±(99.9%) 0.004 ms/op
Iteration   2: 4.249 ±(99.9%) 0.004 ms/op
Iteration   3: 4.140 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.219 ±(99.9%) 1.266 ms/op [Average]
  (min, avg, max) = (4.140, 4.219, 4.269), stdev = 0.069
  CI (99.9%): [2.953, 5.486] (assumes normal distribution)


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
# Warmup Iteration   1: 7.935 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 5.712 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 5.641 ±(99.9%) 0.018 ms/op
Iteration   1: 5.670 ±(99.9%) 0.014 ms/op
Iteration   2: 5.471 ±(99.9%) 0.013 ms/op
Iteration   3: 5.806 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.649 ±(99.9%) 3.072 ms/op [Average]
  (min, avg, max) = (5.471, 5.649, 5.806), stdev = 0.168
  CI (99.9%): [2.578, 8.721] (assumes normal distribution)


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
# Warmup Iteration   1: 6.843 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 5.183 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.488 ±(99.9%) 0.015 ms/op
Iteration   1: 4.288 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.000 ms/op
                 createUser·p0.50:   4.157 ms/op
                 createUser·p0.90:   5.538 ms/op
                 createUser·p0.95:   6.291 ms/op
                 createUser·p0.99:   8.667 ms/op
                 createUser·p0.999:  14.051 ms/op
                 createUser·p0.9999: 26.773 ms/op
                 createUser·p1.00:   27.296 ms/op

Iteration   2: 4.408 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   0.888 ms/op
                 createUser·p0.50:   4.268 ms/op
                 createUser·p0.90:   5.513 ms/op
                 createUser·p0.95:   6.111 ms/op
                 createUser·p0.99:   8.438 ms/op
                 createUser·p0.999:  12.214 ms/op
                 createUser·p0.9999: 21.258 ms/op
                 createUser·p1.00:   21.889 ms/op

Iteration   3: 4.292 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   0.768 ms/op
                 createUser·p0.50:   4.162 ms/op
                 createUser·p0.90:   5.349 ms/op
                 createUser·p0.95:   5.947 ms/op
                 createUser·p0.99:   8.207 ms/op
                 createUser·p0.999:  14.057 ms/op
                 createUser·p0.9999: 20.498 ms/op
                 createUser·p1.00:   23.331 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 221890
  mean =      4.329 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7048 
    [ 2.500,  5.000) = 175605 
    [ 5.000,  7.500) = 35376 
    [ 7.500, 10.000) = 2799 
    [10.000, 12.500) = 622 
    [12.500, 15.000) = 282 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.768 ms/op
     p(50.0000) =      4.194 ms/op
     p(90.0000) =      5.472 ms/op
     p(95.0000) =      6.111 ms/op
     p(99.0000) =      8.472 ms/op
     p(99.9000) =     13.846 ms/op
     p(99.9900) =     25.737 ms/op
     p(99.9990) =     27.169 ms/op
     p(99.9999) =     27.296 ms/op
    p(100.0000) =     27.296 ms/op


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
# Warmup Iteration   1: 5.910 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 4.373 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.070 ±(99.9%) 0.014 ms/op
Iteration   1: 3.984 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.603 ms/op
                 existUser·p0.50:   3.875 ms/op
                 existUser·p0.90:   5.063 ms/op
                 existUser·p0.95:   5.669 ms/op
                 existUser·p0.99:   7.930 ms/op
                 existUser·p0.999:  13.500 ms/op
                 existUser·p0.9999: 32.439 ms/op
                 existUser·p1.00:   32.801 ms/op

Iteration   2: 4.040 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.015 ms/op
                 existUser·p0.50:   3.908 ms/op
                 existUser·p0.90:   5.145 ms/op
                 existUser·p0.95:   5.792 ms/op
                 existUser·p0.99:   8.684 ms/op
                 existUser·p0.999:  15.532 ms/op
                 existUser·p0.9999: 19.765 ms/op
                 existUser·p1.00:   20.349 ms/op

Iteration   3: 4.007 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.916 ms/op
                 existUser·p0.50:   3.899 ms/op
                 existUser·p0.90:   5.030 ms/op
                 existUser·p0.95:   5.603 ms/op
                 existUser·p0.99:   7.782 ms/op
                 existUser·p0.999:  12.665 ms/op
                 existUser·p0.9999: 21.266 ms/op
                 existUser·p1.00:   21.627 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 239222
  mean =      4.010 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13054 
    [ 2.500,  5.000) = 199704 
    [ 5.000,  7.500) = 23102 
    [ 7.500, 10.000) = 2506 
    [10.000, 12.500) = 465 
    [12.500, 15.000) = 196 
    [15.000, 17.500) = 72 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 26 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.603 ms/op
     p(50.0000) =      3.895 ms/op
     p(90.0000) =      5.079 ms/op
     p(95.0000) =      5.685 ms/op
     p(99.0000) =      8.110 ms/op
     p(99.9000) =     13.824 ms/op
     p(99.9900) =     31.588 ms/op
     p(99.9990) =     32.644 ms/op
     p(99.9999) =     32.801 ms/op
    p(100.0000) =     32.801 ms/op


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
# Warmup Iteration   1: 7.129 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 4.836 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.350 ±(99.9%) 0.013 ms/op
Iteration   1: 4.516 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.315 ms/op
                 getUser·p0.50:   4.366 ms/op
                 getUser·p0.90:   5.718 ms/op
                 getUser·p0.95:   6.357 ms/op
                 getUser·p0.99:   8.503 ms/op
                 getUser·p0.999:  13.681 ms/op
                 getUser·p0.9999: 19.227 ms/op
                 getUser·p1.00:   19.988 ms/op

Iteration   2: 4.351 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.157 ms/op
                 getUser·p0.50:   4.190 ms/op
                 getUser·p0.90:   5.521 ms/op
                 getUser·p0.95:   6.078 ms/op
                 getUser·p0.99:   8.135 ms/op
                 getUser·p0.999:  11.846 ms/op
                 getUser·p0.9999: 22.707 ms/op
                 getUser·p1.00:   23.069 ms/op

Iteration   3: 4.121 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.681 ms/op
                 getUser·p0.50:   3.994 ms/op
                 getUser·p0.90:   5.071 ms/op
                 getUser·p0.95:   5.661 ms/op
                 getUser·p0.99:   7.676 ms/op
                 getUser·p0.999:  11.200 ms/op
                 getUser·p0.9999: 18.816 ms/op
                 getUser·p1.00:   19.857 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 221982
  mean =      4.323 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4627 
    [ 2.500,  5.000) = 177640 
    [ 5.000,  7.500) = 36312 
    [ 7.500, 10.000) = 2719 
    [10.000, 12.500) = 441 
    [12.500, 15.000) = 110 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 84 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.681 ms/op
     p(50.0000) =      4.162 ms/op
     p(90.0000) =      5.472 ms/op
     p(95.0000) =      6.054 ms/op
     p(99.0000) =      8.102 ms/op
     p(99.9000) =     12.681 ms/op
     p(99.9900) =     21.929 ms/op
     p(99.9990) =     23.036 ms/op
     p(99.9999) =     23.069 ms/op
    p(100.0000) =     23.069 ms/op


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
# Warmup Iteration   1: 8.048 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 6.188 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 5.962 ±(99.9%) 0.026 ms/op
Iteration   1: 5.665 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.546 ms/op
                 listUser·p0.50:   5.276 ms/op
                 listUser·p0.90:   7.889 ms/op
                 listUser·p0.95:   8.929 ms/op
                 listUser·p0.99:   11.502 ms/op
                 listUser·p0.999:  15.313 ms/op
                 listUser·p0.9999: 31.951 ms/op
                 listUser·p1.00:   32.866 ms/op

Iteration   2: 5.573 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.292 ms/op
                 listUser·p0.50:   5.235 ms/op
                 listUser·p0.90:   7.578 ms/op
                 listUser·p0.95:   8.536 ms/op
                 listUser·p0.99:   11.305 ms/op
                 listUser·p0.999:  19.452 ms/op
                 listUser·p0.9999: 28.124 ms/op
                 listUser·p1.00:   31.523 ms/op

Iteration   3: 5.555 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.475 ms/op
                 listUser·p0.50:   5.186 ms/op
                 listUser·p0.90:   7.569 ms/op
                 listUser·p0.95:   8.634 ms/op
                 listUser·p0.99:   11.239 ms/op
                 listUser·p0.999:  24.490 ms/op
                 listUser·p0.9999: 28.137 ms/op
                 listUser·p1.00:   29.360 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 171436
  mean =      5.597 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 347 
    [ 2.500,  5.000) = 71017 
    [ 5.000,  7.500) = 80738 
    [ 7.500, 10.000) = 15655 
    [10.000, 12.500) = 2655 
    [12.500, 15.000) = 658 
    [15.000, 17.500) = 134 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 51 
    [25.000, 27.500) = 59 
    [27.500, 30.000) = 23 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.292 ms/op
     p(50.0000) =      5.226 ms/op
     p(90.0000) =      7.684 ms/op
     p(95.0000) =      8.716 ms/op
     p(99.0000) =     11.354 ms/op
     p(99.9000) =     20.054 ms/op
     p(99.9900) =     28.288 ms/op
     p(99.9990) =     32.726 ms/op
     p(99.9999) =     32.866 ms/op
    p(100.0000) =     32.866 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.099 ± 1.790  ops/ms
ClientGrpc.existUser                       thrpt       3   7.600 ± 0.906  ops/ms
ClientGrpc.getUser                         thrpt       3   7.442 ± 5.264  ops/ms
ClientGrpc.listUser                        thrpt       3   5.638 ± 0.230  ops/ms
ClientGrpc.createUser                       avgt       3   4.550 ± 1.907   ms/op
ClientGrpc.existUser                        avgt       3   3.992 ± 1.176   ms/op
ClientGrpc.getUser                          avgt       3   4.219 ± 1.266   ms/op
ClientGrpc.listUser                         avgt       3   5.649 ± 3.072   ms/op
ClientGrpc.createUser                     sample  221890   4.329 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.768           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.194           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.472           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.111           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           8.472           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.846           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          25.737           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.296           ms/op
ClientGrpc.existUser                      sample  239222   4.010 ± 0.008   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.603           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.895           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.079           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.685           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           8.110           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          13.824           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          31.588           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          32.801           ms/op
ClientGrpc.getUser                        sample  221982   4.323 ± 0.008   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.681           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.162           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.472           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.054           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           8.102           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.681           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.929           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.069           ms/op
ClientGrpc.listUser                       sample  171436   5.597 ± 0.014   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.292           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.226           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.684           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.716           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          11.354           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          20.054           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          28.288           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          32.866           ms/op
