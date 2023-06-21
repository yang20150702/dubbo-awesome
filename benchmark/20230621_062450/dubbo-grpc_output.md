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
# Warmup Iteration   1: 3.065 ops/ms
# Warmup Iteration   2: 7.050 ops/ms
# Warmup Iteration   3: 8.227 ops/ms
Iteration   1: 8.483 ops/ms
Iteration   2: 8.663 ops/ms
Iteration   3: 8.517 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.555 ±(99.9%) 1.741 ops/ms [Average]
  (min, avg, max) = (8.483, 8.555, 8.663), stdev = 0.095
  CI (99.9%): [6.814, 10.295] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.595 ops/ms
# Warmup Iteration   2: 8.504 ops/ms
# Warmup Iteration   3: 9.120 ops/ms
Iteration   1: 9.260 ops/ms
Iteration   2: 9.344 ops/ms
Iteration   3: 9.154 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.253 ±(99.9%) 1.739 ops/ms [Average]
  (min, avg, max) = (9.154, 9.253, 9.344), stdev = 0.095
  CI (99.9%): [7.514, 10.992] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 5.552 ops/ms
# Warmup Iteration   2: 8.148 ops/ms
# Warmup Iteration   3: 8.651 ops/ms
Iteration   1: 8.819 ops/ms
Iteration   2: 8.627 ops/ms
Iteration   3: 8.672 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.706 ±(99.9%) 1.832 ops/ms [Average]
  (min, avg, max) = (8.627, 8.706, 8.819), stdev = 0.100
  CI (99.9%): [6.874, 10.537] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 4.673 ops/ms
# Warmup Iteration   2: 7.135 ops/ms
# Warmup Iteration   3: 6.308 ops/ms
Iteration   1: 6.622 ops/ms
Iteration   2: 6.598 ops/ms
Iteration   3: 6.785 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.668 ±(99.9%) 1.853 ops/ms [Average]
  (min, avg, max) = (6.598, 6.668, 6.785), stdev = 0.102
  CI (99.9%): [4.815, 8.522] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.056 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.895 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.670 ±(99.9%) 0.005 ms/op
Iteration   1: 3.722 ±(99.9%) 0.007 ms/op
Iteration   2: 3.653 ±(99.9%) 0.004 ms/op
Iteration   3: 3.666 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.681 ±(99.9%) 0.667 ms/op [Average]
  (min, avg, max) = (3.653, 3.681, 3.722), stdev = 0.037
  CI (99.9%): [3.014, 4.348] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 5.089 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.707 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.526 ±(99.9%) 0.003 ms/op
Iteration   1: 3.587 ±(99.9%) 0.003 ms/op
Iteration   2: 3.396 ±(99.9%) 0.003 ms/op
Iteration   3: 3.496 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.493 ±(99.9%) 1.742 ms/op [Average]
  (min, avg, max) = (3.396, 3.493, 3.587), stdev = 0.095
  CI (99.9%): [1.751, 5.235] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 5.169 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.940 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.704 ±(99.9%) 0.005 ms/op
Iteration   1: 3.704 ±(99.9%) 0.003 ms/op
Iteration   2: 3.628 ±(99.9%) 0.003 ms/op
Iteration   3: 3.577 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.636 ±(99.9%) 1.168 ms/op [Average]
  (min, avg, max) = (3.577, 3.636, 3.704), stdev = 0.064
  CI (99.9%): [2.468, 4.804] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 6.692 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 5.022 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.799 ±(99.9%) 0.011 ms/op
Iteration   1: 4.744 ±(99.9%) 0.011 ms/op
Iteration   2: 4.796 ±(99.9%) 0.012 ms/op
Iteration   3: 4.664 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.735 ±(99.9%) 1.210 ms/op [Average]
  (min, avg, max) = (4.664, 4.735, 4.796), stdev = 0.066
  CI (99.9%): [3.525, 5.945] (assumes normal distribution)


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
# Warmup Iteration   1: 5.485 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 3.933 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.699 ±(99.9%) 0.011 ms/op
Iteration   1: 3.633 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.900 ms/op
                 createUser·p0.50:   3.580 ms/op
                 createUser·p0.90:   4.375 ms/op
                 createUser·p0.95:   4.743 ms/op
                 createUser·p0.99:   6.406 ms/op
                 createUser·p0.999:  10.338 ms/op
                 createUser·p0.9999: 22.708 ms/op
                 createUser·p1.00:   23.331 ms/op

Iteration   2: 3.626 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.962 ms/op
                 createUser·p0.50:   3.572 ms/op
                 createUser·p0.90:   4.235 ms/op
                 createUser·p0.95:   4.547 ms/op
                 createUser·p0.99:   5.726 ms/op
                 createUser·p0.999:  12.468 ms/op
                 createUser·p0.9999: 25.729 ms/op
                 createUser·p1.00:   26.083 ms/op

Iteration   3: 3.683 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.778 ms/op
                 createUser·p0.50:   3.625 ms/op
                 createUser·p0.90:   4.456 ms/op
                 createUser·p0.95:   4.817 ms/op
                 createUser·p0.99:   6.300 ms/op
                 createUser·p0.999:  9.836 ms/op
                 createUser·p0.9999: 29.042 ms/op
                 createUser·p1.00:   29.098 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 263202
  mean =      3.647 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11825 
    [ 2.500,  5.000) = 243095 
    [ 5.000,  7.500) = 7109 
    [ 7.500, 10.000) = 755 
    [10.000, 12.500) = 214 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 62 
    [25.000, 27.500) = 52 

  Percentiles, ms/op:
      p(0.0000) =      0.778 ms/op
     p(50.0000) =      3.592 ms/op
     p(90.0000) =      4.350 ms/op
     p(95.0000) =      4.710 ms/op
     p(99.0000) =      6.160 ms/op
     p(99.9000) =     12.157 ms/op
     p(99.9900) =     26.674 ms/op
     p(99.9990) =     29.098 ms/op
     p(99.9999) =     29.098 ms/op
    p(100.0000) =     29.098 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.053 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.668 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.399 ±(99.9%) 0.009 ms/op
Iteration   1: 3.500 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.962 ms/op
                 existUser·p0.50:   3.428 ms/op
                 existUser·p0.90:   4.039 ms/op
                 existUser·p0.95:   4.407 ms/op
                 existUser·p0.99:   5.784 ms/op
                 existUser·p0.999:  12.665 ms/op
                 existUser·p0.9999: 18.378 ms/op
                 existUser·p1.00:   18.678 ms/op

Iteration   2: 3.548 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.057 ms/op
                 existUser·p0.50:   3.478 ms/op
                 existUser·p0.90:   4.141 ms/op
                 existUser·p0.95:   4.497 ms/op
                 existUser·p0.99:   5.775 ms/op
                 existUser·p0.999:  10.009 ms/op
                 existUser·p0.9999: 16.301 ms/op
                 existUser·p1.00:   16.761 ms/op

Iteration   3: 3.468 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.927 ms/op
                 existUser·p0.50:   3.408 ms/op
                 existUser·p0.90:   3.936 ms/op
                 existUser·p0.95:   4.358 ms/op
                 existUser·p0.99:   5.980 ms/op
                 existUser·p0.999:  9.735 ms/op
                 existUser·p0.9999: 27.256 ms/op
                 existUser·p1.00:   27.787 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 273801
  mean =      3.505 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6392 
    [ 2.500,  5.000) = 261236 
    [ 5.000,  7.500) = 5200 
    [ 7.500, 10.000) = 703 
    [10.000, 12.500) = 63 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 73 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.927 ms/op
     p(50.0000) =      3.437 ms/op
     p(90.0000) =      4.055 ms/op
     p(95.0000) =      4.424 ms/op
     p(99.0000) =      5.857 ms/op
     p(99.9000) =      9.961 ms/op
     p(99.9900) =     25.194 ms/op
     p(99.9990) =     27.510 ms/op
     p(99.9999) =     27.787 ms/op
    p(100.0000) =     27.787 ms/op


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
# Warmup Iteration   1: 5.210 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.832 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.660 ±(99.9%) 0.008 ms/op
Iteration   1: 3.592 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.973 ms/op
                 getUser·p0.50:   3.527 ms/op
                 getUser·p0.90:   4.190 ms/op
                 getUser·p0.95:   4.563 ms/op
                 getUser·p0.99:   6.055 ms/op
                 getUser·p0.999:  10.107 ms/op
                 getUser·p0.9999: 19.372 ms/op
                 getUser·p1.00:   19.890 ms/op

Iteration   2: 3.575 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.700 ms/op
                 getUser·p0.50:   3.518 ms/op
                 getUser·p0.90:   4.108 ms/op
                 getUser·p0.95:   4.424 ms/op
                 getUser·p0.99:   5.743 ms/op
                 getUser·p0.999:  9.436 ms/op
                 getUser·p0.9999: 33.359 ms/op
                 getUser·p1.00:   33.620 ms/op

Iteration   3: 3.624 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.055 ms/op
                 getUser·p0.50:   3.600 ms/op
                 getUser·p0.90:   4.399 ms/op
                 getUser·p0.95:   4.678 ms/op
                 getUser·p0.99:   5.694 ms/op
                 getUser·p0.999:  9.516 ms/op
                 getUser·p0.9999: 30.966 ms/op
                 getUser·p1.00:   31.130 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 266991
  mean =      3.597 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9788 
    [ 2.500,  5.000) = 250905 
    [ 5.000,  7.500) = 5396 
    [ 7.500, 10.000) = 672 
    [10.000, 12.500) = 67 
    [12.500, 15.000) = 3 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 14 
    [27.500, 30.000) = 5 
    [30.000, 32.500) = 36 
    [32.500, 35.000) = 23 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.700 ms/op
     p(50.0000) =      3.543 ms/op
     p(90.0000) =      4.252 ms/op
     p(95.0000) =      4.579 ms/op
     p(99.0000) =      5.816 ms/op
     p(99.9000) =      9.748 ms/op
     p(99.9900) =     32.329 ms/op
     p(99.9990) =     33.532 ms/op
     p(99.9999) =     33.620 ms/op
    p(100.0000) =     33.620 ms/op


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
# Warmup Iteration   1: 6.791 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 5.100 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.634 ±(99.9%) 0.014 ms/op
Iteration   1: 4.748 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   0.835 ms/op
                 listUser·p0.50:   4.514 ms/op
                 listUser·p0.90:   6.169 ms/op
                 listUser·p0.95:   6.971 ms/op
                 listUser·p0.99:   8.585 ms/op
                 listUser·p0.999:  15.206 ms/op
                 listUser·p0.9999: 17.949 ms/op
                 listUser·p1.00:   18.317 ms/op

Iteration   2: 4.731 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.237 ms/op
                 listUser·p0.50:   4.473 ms/op
                 listUser·p0.90:   6.111 ms/op
                 listUser·p0.95:   6.767 ms/op
                 listUser·p0.99:   8.946 ms/op
                 listUser·p0.999:  16.168 ms/op
                 listUser·p0.9999: 20.791 ms/op
                 listUser·p1.00:   21.201 ms/op

Iteration   3: 4.717 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   0.905 ms/op
                 listUser·p0.50:   4.514 ms/op
                 listUser·p0.90:   5.890 ms/op
                 listUser·p0.95:   6.390 ms/op
                 listUser·p0.99:   7.848 ms/op
                 listUser·p0.999:  22.843 ms/op
                 listUser·p0.9999: 30.446 ms/op
                 listUser·p1.00:   32.670 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 202958
  mean =      4.732 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 340 
    [ 2.500,  5.000) = 152766 
    [ 5.000,  7.500) = 45081 
    [ 7.500, 10.000) = 3981 
    [10.000, 12.500) = 367 
    [12.500, 15.000) = 117 
    [15.000, 17.500) = 122 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 19 
    [27.500, 30.000) = 6 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.835 ms/op
     p(50.0000) =      4.497 ms/op
     p(90.0000) =      6.038 ms/op
     p(95.0000) =      6.726 ms/op
     p(99.0000) =      8.454 ms/op
     p(99.9000) =     16.941 ms/op
     p(99.9900) =     25.811 ms/op
     p(99.9990) =     32.143 ms/op
     p(99.9999) =     32.670 ms/op
    p(100.0000) =     32.670 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.555 ± 1.741  ops/ms
ClientGrpc.existUser                       thrpt       3   9.253 ± 1.739  ops/ms
ClientGrpc.getUser                         thrpt       3   8.706 ± 1.832  ops/ms
ClientGrpc.listUser                        thrpt       3   6.668 ± 1.853  ops/ms
ClientGrpc.createUser                       avgt       3   3.681 ± 0.667   ms/op
ClientGrpc.existUser                        avgt       3   3.493 ± 1.742   ms/op
ClientGrpc.getUser                          avgt       3   3.636 ± 1.168   ms/op
ClientGrpc.listUser                         avgt       3   4.735 ± 1.210   ms/op
ClientGrpc.createUser                     sample  263202   3.647 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.778           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.592           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.350           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.710           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.160           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.157           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          26.674           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          29.098           ms/op
ClientGrpc.existUser                      sample  273801   3.505 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.927           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.437           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.055           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.424           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.857           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.961           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          25.194           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          27.787           ms/op
ClientGrpc.getUser                        sample  266991   3.597 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.700           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.543           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.252           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.579           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.816           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.748           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          32.329           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          33.620           ms/op
ClientGrpc.listUser                       sample  202958   4.732 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.835           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.497           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.038           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.726           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.454           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.941           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.811           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          32.670           ms/op
