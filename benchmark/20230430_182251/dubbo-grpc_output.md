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
# Warmup Iteration   1: 3.212 ops/ms
# Warmup Iteration   2: 7.103 ops/ms
# Warmup Iteration   3: 8.205 ops/ms
Iteration   1: 8.682 ops/ms
Iteration   2: 8.903 ops/ms
Iteration   3: 8.702 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.762 ±(99.9%) 2.236 ops/ms [Average]
  (min, avg, max) = (8.682, 8.762, 8.903), stdev = 0.123
  CI (99.9%): [6.526, 10.999] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 6.062 ops/ms
# Warmup Iteration   2: 8.733 ops/ms
# Warmup Iteration   3: 9.196 ops/ms
Iteration   1: 9.485 ops/ms
Iteration   2: 9.443 ops/ms
Iteration   3: 9.353 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.427 ±(99.9%) 1.230 ops/ms [Average]
  (min, avg, max) = (9.353, 9.427, 9.485), stdev = 0.067
  CI (99.9%): [8.196, 10.657] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.748 ops/ms
# Warmup Iteration   2: 8.377 ops/ms
# Warmup Iteration   3: 8.692 ops/ms
Iteration   1: 8.443 ops/ms
Iteration   2: 8.776 ops/ms
Iteration   3: 8.748 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.656 ±(99.9%) 3.370 ops/ms [Average]
  (min, avg, max) = (8.443, 8.656, 8.776), stdev = 0.185
  CI (99.9%): [5.286, 12.026] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 4.558 ops/ms
# Warmup Iteration   2: 6.421 ops/ms
# Warmup Iteration   3: 6.749 ops/ms
Iteration   1: 6.668 ops/ms
Iteration   2: 6.792 ops/ms
Iteration   3: 7.215 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.892 ±(99.9%) 5.235 ops/ms [Average]
  (min, avg, max) = (6.668, 6.892, 7.215), stdev = 0.287
  CI (99.9%): [1.657, 12.127] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 5.060 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.827 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.675 ±(99.9%) 0.003 ms/op
Iteration   1: 3.685 ±(99.9%) 0.007 ms/op
Iteration   2: 3.569 ±(99.9%) 0.003 ms/op
Iteration   3: 3.613 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.622 ±(99.9%) 1.069 ms/op [Average]
  (min, avg, max) = (3.569, 3.622, 3.685), stdev = 0.059
  CI (99.9%): [2.554, 4.691] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.615 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.555 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.478 ±(99.9%) 0.002 ms/op
Iteration   1: 3.497 ±(99.9%) 0.002 ms/op
Iteration   2: 3.544 ±(99.9%) 0.004 ms/op
Iteration   3: 3.455 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.499 ±(99.9%) 0.814 ms/op [Average]
  (min, avg, max) = (3.455, 3.499, 3.544), stdev = 0.045
  CI (99.9%): [2.685, 4.312] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.131 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.776 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.661 ±(99.9%) 0.003 ms/op
Iteration   1: 3.655 ±(99.9%) 0.005 ms/op
Iteration   2: 3.527 ±(99.9%) 0.004 ms/op
Iteration   3: 3.611 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.598 ±(99.9%) 1.190 ms/op [Average]
  (min, avg, max) = (3.527, 3.598, 3.655), stdev = 0.065
  CI (99.9%): [2.407, 4.788] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 6.476 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 5.087 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 4.807 ±(99.9%) 0.015 ms/op
Iteration   1: 4.716 ±(99.9%) 0.007 ms/op
Iteration   2: 4.781 ±(99.9%) 0.019 ms/op
Iteration   3: 4.615 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.704 ±(99.9%) 1.525 ms/op [Average]
  (min, avg, max) = (4.615, 4.704, 4.781), stdev = 0.084
  CI (99.9%): [3.179, 6.229] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 4.992 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.766 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.607 ±(99.9%) 0.009 ms/op
Iteration   1: 3.670 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.920 ms/op
                 createUser·p0.50:   3.592 ms/op
                 createUser·p0.90:   4.375 ms/op
                 createUser·p0.95:   4.694 ms/op
                 createUser·p0.99:   5.751 ms/op
                 createUser·p0.999:  9.961 ms/op
                 createUser·p0.9999: 14.844 ms/op
                 createUser·p1.00:   16.335 ms/op

Iteration   2: 3.797 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.962 ms/op
                 createUser·p0.50:   3.715 ms/op
                 createUser·p0.90:   4.620 ms/op
                 createUser·p0.95:   4.964 ms/op
                 createUser·p0.99:   6.341 ms/op
                 createUser·p0.999:  10.221 ms/op
                 createUser·p0.9999: 18.055 ms/op
                 createUser·p1.00:   18.416 ms/op

Iteration   3: 3.692 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.926 ms/op
                 createUser·p0.50:   3.613 ms/op
                 createUser·p0.90:   4.399 ms/op
                 createUser·p0.95:   4.686 ms/op
                 createUser·p0.99:   5.702 ms/op
                 createUser·p0.999:  16.433 ms/op
                 createUser·p0.9999: 22.588 ms/op
                 createUser·p1.00:   22.872 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 257965
  mean =      3.719 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6137 
    [ 2.500,  5.000) = 243333 
    [ 5.000,  7.500) = 7561 
    [ 7.500, 10.000) = 567 
    [10.000, 12.500) = 115 
    [12.500, 15.000) = 111 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 65 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.920 ms/op
     p(50.0000) =      3.637 ms/op
     p(90.0000) =      4.465 ms/op
     p(95.0000) =      4.792 ms/op
     p(99.0000) =      5.947 ms/op
     p(99.9000) =     12.256 ms/op
     p(99.9900) =     21.902 ms/op
     p(99.9990) =     22.801 ms/op
     p(99.9999) =     22.872 ms/op
    p(100.0000) =     22.872 ms/op


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
# Warmup Iteration   1: 4.645 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.706 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.457 ±(99.9%) 0.007 ms/op
Iteration   1: 3.437 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.877 ms/op
                 existUser·p0.50:   3.412 ms/op
                 existUser·p0.90:   4.006 ms/op
                 existUser·p0.95:   4.301 ms/op
                 existUser·p0.99:   5.202 ms/op
                 existUser·p0.999:  7.421 ms/op
                 existUser·p0.9999: 14.272 ms/op
                 existUser·p1.00:   16.155 ms/op

Iteration   2: 3.472 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.638 ms/op
                 existUser·p0.50:   3.412 ms/op
                 existUser·p0.90:   4.047 ms/op
                 existUser·p0.95:   4.375 ms/op
                 existUser·p0.99:   5.456 ms/op
                 existUser·p0.999:  10.502 ms/op
                 existUser·p0.9999: 16.579 ms/op
                 existUser·p1.00:   17.269 ms/op

Iteration   3: 3.510 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.906 ms/op
                 existUser·p0.50:   3.441 ms/op
                 existUser·p0.90:   4.149 ms/op
                 existUser·p0.95:   4.440 ms/op
                 existUser·p0.99:   5.595 ms/op
                 existUser·p0.999:  9.810 ms/op
                 existUser·p0.9999: 17.855 ms/op
                 existUser·p1.00:   18.678 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 276332
  mean =      3.473 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 264 
    [ 1.250,  2.500) = 7513 
    [ 2.500,  3.750) = 208765 
    [ 3.750,  5.000) = 55263 
    [ 5.000,  6.250) = 3259 
    [ 6.250,  7.500) = 756 
    [ 7.500,  8.750) = 248 
    [ 8.750, 10.000) = 31 
    [10.000, 11.250) = 50 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 51 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 23 
    [17.500, 18.750) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.638 ms/op
     p(50.0000) =      3.420 ms/op
     p(90.0000) =      4.067 ms/op
     p(95.0000) =      4.375 ms/op
     p(99.0000) =      5.431 ms/op
     p(99.9000) =      8.634 ms/op
     p(99.9900) =     16.627 ms/op
     p(99.9990) =     18.554 ms/op
     p(99.9999) =     18.678 ms/op
    p(100.0000) =     18.678 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.174 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.937 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.666 ±(99.9%) 0.008 ms/op
Iteration   1: 3.698 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.844 ms/op
                 getUser·p0.50:   3.625 ms/op
                 getUser·p0.90:   4.424 ms/op
                 getUser·p0.95:   4.776 ms/op
                 getUser·p0.99:   5.906 ms/op
                 getUser·p0.999:  9.307 ms/op
                 getUser·p0.9999: 22.905 ms/op
                 getUser·p1.00:   23.167 ms/op

Iteration   2: 3.662 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.959 ms/op
                 getUser·p0.50:   3.592 ms/op
                 getUser·p0.90:   4.325 ms/op
                 getUser·p0.95:   4.645 ms/op
                 getUser·p0.99:   5.652 ms/op
                 getUser·p0.999:  9.879 ms/op
                 getUser·p0.9999: 20.763 ms/op
                 getUser·p1.00:   21.365 ms/op

Iteration   3: 3.649 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.654 ms/op
                 getUser·p0.50:   3.600 ms/op
                 getUser·p0.90:   4.293 ms/op
                 getUser·p0.95:   4.579 ms/op
                 getUser·p0.99:   5.513 ms/op
                 getUser·p0.999:  10.502 ms/op
                 getUser·p0.9999: 24.795 ms/op
                 getUser·p1.00:   25.821 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 261584
  mean =      3.669 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6023 
    [ 2.500,  5.000) = 248460 
    [ 5.000,  7.500) = 6373 
    [ 7.500, 10.000) = 479 
    [10.000, 12.500) = 88 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 63 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.654 ms/op
     p(50.0000) =      3.604 ms/op
     p(90.0000) =      4.342 ms/op
     p(95.0000) =      4.669 ms/op
     p(99.0000) =      5.693 ms/op
     p(99.9000) =      9.703 ms/op
     p(99.9900) =     23.457 ms/op
     p(99.9990) =     25.592 ms/op
     p(99.9999) =     25.821 ms/op
    p(100.0000) =     25.821 ms/op


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
# Warmup Iteration   1: 6.845 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 4.939 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.738 ±(99.9%) 0.013 ms/op
Iteration   1: 4.643 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.782 ms/op
                 listUser·p0.50:   4.489 ms/op
                 listUser·p0.90:   5.603 ms/op
                 listUser·p0.95:   6.480 ms/op
                 listUser·p0.99:   8.184 ms/op
                 listUser·p0.999:  14.543 ms/op
                 listUser·p0.9999: 22.970 ms/op
                 listUser·p1.00:   23.200 ms/op

Iteration   2: 4.758 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.362 ms/op
                 listUser·p0.50:   4.547 ms/op
                 listUser·p0.90:   5.874 ms/op
                 listUser·p0.95:   6.775 ms/op
                 listUser·p0.99:   8.487 ms/op
                 listUser·p0.999:  17.531 ms/op
                 listUser·p0.9999: 23.087 ms/op
                 listUser·p1.00:   23.331 ms/op

Iteration   3: 4.689 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   0.965 ms/op
                 listUser·p0.50:   4.481 ms/op
                 listUser·p0.90:   5.939 ms/op
                 listUser·p0.95:   6.644 ms/op
                 listUser·p0.99:   8.200 ms/op
                 listUser·p0.999:  19.748 ms/op
                 listUser·p0.9999: 24.232 ms/op
                 listUser·p1.00:   26.444 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 204414
  mean =      4.696 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 343 
    [ 2.500,  5.000) = 159490 
    [ 5.000,  7.500) = 39900 
    [ 7.500, 10.000) = 4112 
    [10.000, 12.500) = 213 
    [12.500, 15.000) = 43 
    [15.000, 17.500) = 113 
    [17.500, 20.000) = 72 
    [20.000, 22.500) = 83 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.965 ms/op
     p(50.0000) =      4.506 ms/op
     p(90.0000) =      5.816 ms/op
     p(95.0000) =      6.636 ms/op
     p(99.0000) =      8.307 ms/op
     p(99.9000) =     17.438 ms/op
     p(99.9900) =     23.069 ms/op
     p(99.9990) =     26.432 ms/op
     p(99.9999) =     26.444 ms/op
    p(100.0000) =     26.444 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.762 ± 2.236  ops/ms
ClientGrpc.existUser                       thrpt       3   9.427 ± 1.230  ops/ms
ClientGrpc.getUser                         thrpt       3   8.656 ± 3.370  ops/ms
ClientGrpc.listUser                        thrpt       3   6.892 ± 5.235  ops/ms
ClientGrpc.createUser                       avgt       3   3.622 ± 1.069   ms/op
ClientGrpc.existUser                        avgt       3   3.499 ± 0.814   ms/op
ClientGrpc.getUser                          avgt       3   3.598 ± 1.190   ms/op
ClientGrpc.listUser                         avgt       3   4.704 ± 1.525   ms/op
ClientGrpc.createUser                     sample  257965   3.719 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.920           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.637           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.465           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.792           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.947           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.256           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.902           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.872           ms/op
ClientGrpc.existUser                      sample  276332   3.473 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.638           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.420           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.067           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.375           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.431           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.634           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.627           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.678           ms/op
ClientGrpc.getUser                        sample  261584   3.669 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.654           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.604           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.342           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.669           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.693           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.703           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.457           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.821           ms/op
ClientGrpc.listUser                       sample  204414   4.696 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.965           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.506           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.816           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.636           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.307           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.438           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.069           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.444           ms/op
