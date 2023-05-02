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
# Warmup Iteration   1: 3.344 ops/ms
# Warmup Iteration   2: 6.939 ops/ms
# Warmup Iteration   3: 8.332 ops/ms
Iteration   1: 8.498 ops/ms
Iteration   2: 8.596 ops/ms
Iteration   3: 8.482 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.525 ±(99.9%) 1.126 ops/ms [Average]
  (min, avg, max) = (8.482, 8.525, 8.596), stdev = 0.062
  CI (99.9%): [7.399, 9.652] (assumes normal distribution)


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
# Warmup Iteration   1: 6.819 ops/ms
# Warmup Iteration   2: 9.145 ops/ms
# Warmup Iteration   3: 9.013 ops/ms
Iteration   1: 9.414 ops/ms
Iteration   2: 9.316 ops/ms
Iteration   3: 9.349 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.360 ±(99.9%) 0.912 ops/ms [Average]
  (min, avg, max) = (9.316, 9.360, 9.414), stdev = 0.050
  CI (99.9%): [8.448, 10.272] (assumes normal distribution)


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
# Warmup Iteration   1: 5.800 ops/ms
# Warmup Iteration   2: 8.494 ops/ms
# Warmup Iteration   3: 8.812 ops/ms
Iteration   1: 8.980 ops/ms
Iteration   2: 8.926 ops/ms
Iteration   3: 9.009 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.972 ±(99.9%) 0.768 ops/ms [Average]
  (min, avg, max) = (8.926, 8.972, 9.009), stdev = 0.042
  CI (99.9%): [8.204, 9.739] (assumes normal distribution)


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
# Warmup Iteration   1: 4.827 ops/ms
# Warmup Iteration   2: 6.516 ops/ms
# Warmup Iteration   3: 6.687 ops/ms
Iteration   1: 6.755 ops/ms
Iteration   2: 6.787 ops/ms
Iteration   3: 6.761 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.768 ±(99.9%) 0.314 ops/ms [Average]
  (min, avg, max) = (6.755, 6.768, 6.787), stdev = 0.017
  CI (99.9%): [6.454, 7.082] (assumes normal distribution)


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
# Warmup Iteration   1: 5.281 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.802 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.747 ±(99.9%) 0.003 ms/op
Iteration   1: 3.664 ±(99.9%) 0.002 ms/op
Iteration   2: 3.520 ±(99.9%) 0.003 ms/op
Iteration   3: 3.601 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.595 ±(99.9%) 1.315 ms/op [Average]
  (min, avg, max) = (3.520, 3.595, 3.664), stdev = 0.072
  CI (99.9%): [2.280, 4.909] (assumes normal distribution)


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
# Warmup Iteration   1: 5.027 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.535 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.536 ±(99.9%) 0.004 ms/op
Iteration   1: 3.421 ±(99.9%) 0.003 ms/op
Iteration   2: 3.399 ±(99.9%) 0.003 ms/op
Iteration   3: 3.403 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.408 ±(99.9%) 0.217 ms/op [Average]
  (min, avg, max) = (3.399, 3.408, 3.421), stdev = 0.012
  CI (99.9%): [3.191, 3.625] (assumes normal distribution)


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
# Warmup Iteration   1: 5.326 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.843 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.630 ±(99.9%) 0.005 ms/op
Iteration   1: 3.749 ±(99.9%) 0.007 ms/op
Iteration   2: 3.599 ±(99.9%) 0.004 ms/op
Iteration   3: 3.585 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.645 ±(99.9%) 1.657 ms/op [Average]
  (min, avg, max) = (3.585, 3.645, 3.749), stdev = 0.091
  CI (99.9%): [1.988, 5.302] (assumes normal distribution)


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
# Warmup Iteration   1: 5.739 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 5.126 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.654 ±(99.9%) 0.012 ms/op
Iteration   1: 4.663 ±(99.9%) 0.017 ms/op
Iteration   2: 4.642 ±(99.9%) 0.011 ms/op
Iteration   3: 4.651 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.652 ±(99.9%) 0.195 ms/op [Average]
  (min, avg, max) = (4.642, 4.652, 4.663), stdev = 0.011
  CI (99.9%): [4.458, 4.847] (assumes normal distribution)


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
# Warmup Iteration   1: 5.182 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.814 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.584 ±(99.9%) 0.009 ms/op
Iteration   1: 3.637 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.866 ms/op
                 createUser·p0.50:   3.555 ms/op
                 createUser·p0.90:   4.366 ms/op
                 createUser·p0.95:   4.735 ms/op
                 createUser·p0.99:   6.144 ms/op
                 createUser·p0.999:  14.142 ms/op
                 createUser·p0.9999: 15.457 ms/op
                 createUser·p1.00:   15.647 ms/op

Iteration   2: 3.547 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.787 ms/op
                 createUser·p0.50:   3.482 ms/op
                 createUser·p0.90:   4.227 ms/op
                 createUser·p0.95:   4.563 ms/op
                 createUser·p0.99:   5.931 ms/op
                 createUser·p0.999:  11.332 ms/op
                 createUser·p0.9999: 15.810 ms/op
                 createUser·p1.00:   17.367 ms/op

Iteration   3: 3.451 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.665 ms/op
                 createUser·p0.50:   3.416 ms/op
                 createUser·p0.90:   4.100 ms/op
                 createUser·p0.95:   4.473 ms/op
                 createUser·p0.99:   5.726 ms/op
                 createUser·p0.999:  11.767 ms/op
                 createUser·p0.9999: 19.488 ms/op
                 createUser·p1.00:   20.546 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 270872
  mean =      3.543 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10543 
    [ 2.500,  5.000) = 253200 
    [ 5.000,  7.500) = 5920 
    [ 7.500, 10.000) = 643 
    [10.000, 12.500) = 307 
    [12.500, 15.000) = 174 
    [15.000, 17.500) = 53 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.665 ms/op
     p(50.0000) =      3.482 ms/op
     p(90.0000) =      4.235 ms/op
     p(95.0000) =      4.604 ms/op
     p(99.0000) =      5.915 ms/op
     p(99.9000) =     12.386 ms/op
     p(99.9900) =     19.169 ms/op
     p(99.9990) =     20.401 ms/op
     p(99.9999) =     20.546 ms/op
    p(100.0000) =     20.546 ms/op


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
# Warmup Iteration   1: 4.802 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.487 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.471 ±(99.9%) 0.010 ms/op
Iteration   1: 3.395 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.729 ms/op
                 existUser·p0.50:   3.346 ms/op
                 existUser·p0.90:   4.055 ms/op
                 existUser·p0.95:   4.399 ms/op
                 existUser·p0.99:   5.800 ms/op
                 existUser·p0.999:  13.213 ms/op
                 existUser·p0.9999: 33.030 ms/op
                 existUser·p1.00:   35.389 ms/op

Iteration   2: 3.346 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.791 ms/op
                 existUser·p0.50:   3.314 ms/op
                 existUser·p0.90:   3.981 ms/op
                 existUser·p0.95:   4.350 ms/op
                 existUser·p0.99:   6.218 ms/op
                 existUser·p0.999:  12.747 ms/op
                 existUser·p0.9999: 17.545 ms/op
                 existUser·p1.00:   17.891 ms/op

Iteration   3: 3.302 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.716 ms/op
                 existUser·p0.50:   3.297 ms/op
                 existUser·p0.90:   4.014 ms/op
                 existUser·p0.95:   4.342 ms/op
                 existUser·p0.99:   5.710 ms/op
                 existUser·p0.999:  11.878 ms/op
                 existUser·p0.9999: 33.227 ms/op
                 existUser·p1.00:   33.686 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 286880
  mean =      3.347 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22886 
    [ 2.500,  5.000) = 258264 
    [ 5.000,  7.500) = 4259 
    [ 7.500, 10.000) = 807 
    [10.000, 12.500) = 358 
    [12.500, 15.000) = 148 
    [15.000, 17.500) = 76 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 4 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 51 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.716 ms/op
     p(50.0000) =      3.322 ms/op
     p(90.0000) =      4.018 ms/op
     p(95.0000) =      4.366 ms/op
     p(99.0000) =      5.874 ms/op
     p(99.9000) =     12.667 ms/op
     p(99.9900) =     32.909 ms/op
     p(99.9990) =     33.629 ms/op
     p(99.9999) =     35.389 ms/op
    p(100.0000) =     35.389 ms/op


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
# Warmup Iteration   1: 5.064 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.852 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.622 ±(99.9%) 0.010 ms/op
Iteration   1: 3.755 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.667 ms/op
                 getUser·p0.50:   3.621 ms/op
                 getUser·p0.90:   4.678 ms/op
                 getUser·p0.95:   5.217 ms/op
                 getUser·p0.99:   7.815 ms/op
                 getUser·p0.999:  13.599 ms/op
                 getUser·p0.9999: 19.382 ms/op
                 getUser·p1.00:   19.497 ms/op

Iteration   2: 3.655 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.779 ms/op
                 getUser·p0.50:   3.568 ms/op
                 getUser·p0.90:   4.473 ms/op
                 getUser·p0.95:   4.841 ms/op
                 getUser·p0.99:   6.447 ms/op
                 getUser·p0.999:  10.852 ms/op
                 getUser·p0.9999: 18.817 ms/op
                 getUser·p1.00:   19.497 ms/op

Iteration   3: 3.746 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.366 ms/op
                 getUser·p0.50:   3.621 ms/op
                 getUser·p0.90:   4.694 ms/op
                 getUser·p0.95:   5.309 ms/op
                 getUser·p0.99:   7.168 ms/op
                 getUser·p0.999:  12.872 ms/op
                 getUser·p0.9999: 23.608 ms/op
                 getUser·p1.00:   23.855 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 258247
  mean =      3.718 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13335 
    [ 2.500,  5.000) = 230145 
    [ 5.000,  7.500) = 12653 
    [ 7.500, 10.000) = 1199 
    [10.000, 12.500) = 539 
    [12.500, 15.000) = 216 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 125 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.366 ms/op
     p(50.0000) =      3.600 ms/op
     p(90.0000) =      4.604 ms/op
     p(95.0000) =      5.112 ms/op
     p(99.0000) =      7.094 ms/op
     p(99.9000) =     13.107 ms/op
     p(99.9900) =     21.365 ms/op
     p(99.9990) =     23.784 ms/op
     p(99.9999) =     23.855 ms/op
    p(100.0000) =     23.855 ms/op


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
# Warmup Iteration   1: 5.866 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 4.956 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.771 ±(99.9%) 0.018 ms/op
Iteration   1: 4.703 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.661 ms/op
                 listUser·p0.50:   4.432 ms/op
                 listUser·p0.90:   6.119 ms/op
                 listUser·p0.95:   6.939 ms/op
                 listUser·p0.99:   9.470 ms/op
                 listUser·p0.999:  17.199 ms/op
                 listUser·p0.9999: 22.983 ms/op
                 listUser·p1.00:   24.150 ms/op

Iteration   2: 4.766 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.456 ms/op
                 listUser·p0.50:   4.514 ms/op
                 listUser·p0.90:   6.062 ms/op
                 listUser·p0.95:   6.980 ms/op
                 listUser·p0.99:   9.650 ms/op
                 listUser·p0.999:  17.138 ms/op
                 listUser·p0.9999: 23.504 ms/op
                 listUser·p1.00:   26.575 ms/op

Iteration   3: 4.589 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   0.825 ms/op
                 listUser·p0.50:   4.375 ms/op
                 listUser·p0.90:   5.874 ms/op
                 listUser·p0.95:   6.717 ms/op
                 listUser·p0.99:   9.306 ms/op
                 listUser·p0.999:  21.594 ms/op
                 listUser·p0.9999: 25.924 ms/op
                 listUser·p1.00:   26.280 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 204867
  mean =      4.685 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 939 
    [ 2.500,  5.000) = 155102 
    [ 5.000,  7.500) = 42623 
    [ 7.500, 10.000) = 4500 
    [10.000, 12.500) = 805 
    [12.500, 15.000) = 440 
    [15.000, 17.500) = 209 
    [17.500, 20.000) = 94 
    [20.000, 22.500) = 80 
    [22.500, 25.000) = 51 
    [25.000, 27.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.825 ms/op
     p(50.0000) =      4.440 ms/op
     p(90.0000) =      6.013 ms/op
     p(95.0000) =      6.881 ms/op
     p(99.0000) =      9.486 ms/op
     p(99.9000) =     18.252 ms/op
     p(99.9900) =     25.068 ms/op
     p(99.9990) =     26.275 ms/op
     p(99.9999) =     26.575 ms/op
    p(100.0000) =     26.575 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.525 ± 1.126  ops/ms
ClientGrpc.existUser                       thrpt       3   9.360 ± 0.912  ops/ms
ClientGrpc.getUser                         thrpt       3   8.972 ± 0.768  ops/ms
ClientGrpc.listUser                        thrpt       3   6.768 ± 0.314  ops/ms
ClientGrpc.createUser                       avgt       3   3.595 ± 1.315   ms/op
ClientGrpc.existUser                        avgt       3   3.408 ± 0.217   ms/op
ClientGrpc.getUser                          avgt       3   3.645 ± 1.657   ms/op
ClientGrpc.listUser                         avgt       3   4.652 ± 0.195   ms/op
ClientGrpc.createUser                     sample  270872   3.543 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.665           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.482           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.235           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.604           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.915           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.386           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.169           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.546           ms/op
ClientGrpc.existUser                      sample  286880   3.347 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.716           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.322           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.018           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.366           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.874           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.667           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          32.909           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          35.389           ms/op
ClientGrpc.getUser                        sample  258247   3.718 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.366           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.600           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.604           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.112           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.094           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          13.107           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.365           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.855           ms/op
ClientGrpc.listUser                       sample  204867   4.685 ± 0.010   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.825           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.440           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.013           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.881           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.486           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.252           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.068           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.575           ms/op
