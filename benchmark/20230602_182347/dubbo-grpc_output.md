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
# Warmup Iteration   1: 3.110 ops/ms
# Warmup Iteration   2: 6.452 ops/ms
# Warmup Iteration   3: 7.591 ops/ms
Iteration   1: 8.224 ops/ms
Iteration   2: 8.209 ops/ms
Iteration   3: 8.136 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.189 ±(99.9%) 0.852 ops/ms [Average]
  (min, avg, max) = (8.136, 8.189, 8.224), stdev = 0.047
  CI (99.9%): [7.337, 9.042] (assumes normal distribution)


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
# Warmup Iteration   1: 5.559 ops/ms
# Warmup Iteration   2: 8.407 ops/ms
# Warmup Iteration   3: 8.957 ops/ms
Iteration   1: 8.909 ops/ms
Iteration   2: 8.792 ops/ms
Iteration   3: 8.418 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.706 ±(99.9%) 4.681 ops/ms [Average]
  (min, avg, max) = (8.418, 8.706, 8.909), stdev = 0.257
  CI (99.9%): [4.025, 13.388] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 5.051 ops/ms
# Warmup Iteration   2: 7.928 ops/ms
# Warmup Iteration   3: 8.071 ops/ms
Iteration   1: 8.127 ops/ms
Iteration   2: 8.477 ops/ms
Iteration   3: 8.546 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.383 ±(99.9%) 4.093 ops/ms [Average]
  (min, avg, max) = (8.127, 8.383, 8.546), stdev = 0.224
  CI (99.9%): [4.290, 12.476] (assumes normal distribution)


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
# Warmup Iteration   1: 4.326 ops/ms
# Warmup Iteration   2: 5.938 ops/ms
# Warmup Iteration   3: 6.354 ops/ms
Iteration   1: 6.354 ops/ms
Iteration   2: 6.512 ops/ms
Iteration   3: 6.399 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.422 ±(99.9%) 1.492 ops/ms [Average]
  (min, avg, max) = (6.354, 6.422, 6.512), stdev = 0.082
  CI (99.9%): [4.930, 7.913] (assumes normal distribution)


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
# Warmup Iteration   1: 5.662 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.086 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.011 ±(99.9%) 0.014 ms/op
Iteration   1: 3.991 ±(99.9%) 0.003 ms/op
Iteration   2: 3.901 ±(99.9%) 0.003 ms/op
Iteration   3: 3.887 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.926 ±(99.9%) 1.027 ms/op [Average]
  (min, avg, max) = (3.887, 3.926, 3.991), stdev = 0.056
  CI (99.9%): [2.899, 4.954] (assumes normal distribution)


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
# Warmup Iteration   1: 5.311 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.849 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.884 ±(99.9%) 0.004 ms/op
Iteration   1: 3.646 ±(99.9%) 0.002 ms/op
Iteration   2: 3.601 ±(99.9%) 0.004 ms/op
Iteration   3: 3.619 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.622 ±(99.9%) 0.419 ms/op [Average]
  (min, avg, max) = (3.601, 3.622, 3.646), stdev = 0.023
  CI (99.9%): [3.203, 4.041] (assumes normal distribution)


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
# Warmup Iteration   1: 5.683 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.917 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.765 ±(99.9%) 0.004 ms/op
Iteration   1: 3.823 ±(99.9%) 0.003 ms/op
Iteration   2: 3.799 ±(99.9%) 0.003 ms/op
Iteration   3: 3.714 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.779 ±(99.9%) 1.048 ms/op [Average]
  (min, avg, max) = (3.714, 3.779, 3.823), stdev = 0.057
  CI (99.9%): [2.731, 4.827] (assumes normal distribution)


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
# Warmup Iteration   1: 7.327 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 5.126 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.888 ±(99.9%) 0.012 ms/op
Iteration   1: 4.884 ±(99.9%) 0.019 ms/op
Iteration   2: 4.923 ±(99.9%) 0.012 ms/op
Iteration   3: 4.865 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.890 ±(99.9%) 0.541 ms/op [Average]
  (min, avg, max) = (4.865, 4.890, 4.923), stdev = 0.030
  CI (99.9%): [4.349, 5.432] (assumes normal distribution)


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
# Warmup Iteration   1: 5.720 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 4.103 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.941 ±(99.9%) 0.012 ms/op
Iteration   1: 3.930 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.976 ms/op
                 createUser·p0.50:   3.830 ms/op
                 createUser·p0.90:   4.743 ms/op
                 createUser·p0.95:   5.079 ms/op
                 createUser·p0.99:   6.742 ms/op
                 createUser·p0.999:  14.999 ms/op
                 createUser·p0.9999: 19.066 ms/op
                 createUser·p1.00:   19.333 ms/op

Iteration   2: 3.765 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.104 ms/op
                 createUser·p0.50:   3.699 ms/op
                 createUser·p0.90:   4.448 ms/op
                 createUser·p0.95:   4.801 ms/op
                 createUser·p0.99:   6.111 ms/op
                 createUser·p0.999:  9.256 ms/op
                 createUser·p0.9999: 16.015 ms/op
                 createUser·p1.00:   18.121 ms/op

Iteration   3: 3.801 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.957 ms/op
                 createUser·p0.50:   3.707 ms/op
                 createUser·p0.90:   4.604 ms/op
                 createUser·p0.95:   5.022 ms/op
                 createUser·p0.99:   6.663 ms/op
                 createUser·p0.999:  12.694 ms/op
                 createUser·p0.9999: 23.108 ms/op
                 createUser·p1.00:   23.331 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 250622
  mean =      3.831 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5970 
    [ 2.500,  5.000) = 232735 
    [ 5.000,  7.500) = 10532 
    [ 7.500, 10.000) = 961 
    [10.000, 12.500) = 128 
    [12.500, 15.000) = 101 
    [15.000, 17.500) = 79 
    [17.500, 20.000) = 71 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.957 ms/op
     p(50.0000) =      3.740 ms/op
     p(90.0000) =      4.612 ms/op
     p(95.0000) =      4.973 ms/op
     p(99.0000) =      6.488 ms/op
     p(99.9000) =     13.955 ms/op
     p(99.9900) =     22.870 ms/op
     p(99.9990) =     23.281 ms/op
     p(99.9999) =     23.331 ms/op
    p(100.0000) =     23.331 ms/op


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
# Warmup Iteration   1: 4.878 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.716 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.572 ±(99.9%) 0.009 ms/op
Iteration   1: 3.588 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.807 ms/op
                 existUser·p0.50:   3.523 ms/op
                 existUser·p0.90:   4.407 ms/op
                 existUser·p0.95:   4.809 ms/op
                 existUser·p0.99:   6.177 ms/op
                 existUser·p0.999:  9.994 ms/op
                 existUser·p0.9999: 15.355 ms/op
                 existUser·p1.00:   15.679 ms/op

Iteration   2: 3.660 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.817 ms/op
                 existUser·p0.50:   3.547 ms/op
                 existUser·p0.90:   4.579 ms/op
                 existUser·p0.95:   5.210 ms/op
                 existUser·p0.99:   6.857 ms/op
                 existUser·p0.999:  10.437 ms/op
                 existUser·p0.9999: 19.907 ms/op
                 existUser·p1.00:   20.742 ms/op

Iteration   3: 3.529 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.900 ms/op
                 existUser·p0.50:   3.445 ms/op
                 existUser·p0.90:   4.170 ms/op
                 existUser·p0.95:   4.637 ms/op
                 existUser·p0.99:   6.054 ms/op
                 existUser·p0.999:  11.190 ms/op
                 existUser·p0.9999: 25.229 ms/op
                 existUser·p1.00:   25.559 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 267217
  mean =      3.591 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13342 
    [ 2.500,  5.000) = 242278 
    [ 5.000,  7.500) = 10400 
    [ 7.500, 10.000) = 876 
    [10.000, 12.500) = 160 
    [12.500, 15.000) = 49 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 48 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.807 ms/op
     p(50.0000) =      3.502 ms/op
     p(90.0000) =      4.399 ms/op
     p(95.0000) =      4.891 ms/op
     p(99.0000) =      6.382 ms/op
     p(99.9000) =     10.351 ms/op
     p(99.9900) =     24.112 ms/op
     p(99.9990) =     25.362 ms/op
     p(99.9999) =     25.559 ms/op
    p(100.0000) =     25.559 ms/op


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
# Warmup Iteration   1: 5.516 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 3.952 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.799 ±(99.9%) 0.009 ms/op
Iteration   1: 3.809 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.079 ms/op
                 getUser·p0.50:   3.695 ms/op
                 getUser·p0.90:   4.628 ms/op
                 getUser·p0.95:   5.071 ms/op
                 getUser·p0.99:   6.787 ms/op
                 getUser·p0.999:  9.926 ms/op
                 getUser·p0.9999: 14.680 ms/op
                 getUser·p1.00:   14.975 ms/op

Iteration   2: 3.703 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.929 ms/op
                 getUser·p0.50:   3.637 ms/op
                 getUser·p0.90:   4.645 ms/op
                 getUser·p0.95:   5.112 ms/op
                 getUser·p0.99:   6.906 ms/op
                 getUser·p0.999:  9.808 ms/op
                 getUser·p0.9999: 18.439 ms/op
                 getUser·p1.00:   18.907 ms/op

Iteration   3: 3.777 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.864 ms/op
                 getUser·p0.50:   3.690 ms/op
                 getUser·p0.90:   4.637 ms/op
                 getUser·p0.95:   5.177 ms/op
                 getUser·p0.99:   6.889 ms/op
                 getUser·p0.999:  10.130 ms/op
                 getUser·p0.9999: 27.772 ms/op
                 getUser·p1.00:   28.312 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 255106
  mean =      3.762 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12553 
    [ 2.500,  5.000) = 227611 
    [ 5.000,  7.500) = 13272 
    [ 7.500, 10.000) = 1428 
    [10.000, 12.500) = 80 
    [12.500, 15.000) = 80 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.864 ms/op
     p(50.0000) =      3.678 ms/op
     p(90.0000) =      4.637 ms/op
     p(95.0000) =      5.120 ms/op
     p(99.0000) =      6.857 ms/op
     p(99.9000) =      9.894 ms/op
     p(99.9900) =     27.131 ms/op
     p(99.9990) =     28.097 ms/op
     p(99.9999) =     28.312 ms/op
    p(100.0000) =     28.312 ms/op


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
# Warmup Iteration   1: 6.555 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 5.311 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.756 ±(99.9%) 0.015 ms/op
Iteration   1: 4.968 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.452 ms/op
                 listUser·p0.50:   4.686 ms/op
                 listUser·p0.90:   6.488 ms/op
                 listUser·p0.95:   7.356 ms/op
                 listUser·p0.99:   8.978 ms/op
                 listUser·p0.999:  15.242 ms/op
                 listUser·p0.9999: 18.158 ms/op
                 listUser·p1.00:   18.547 ms/op

Iteration   2: 5.033 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   0.935 ms/op
                 listUser·p0.50:   4.694 ms/op
                 listUser·p0.90:   6.849 ms/op
                 listUser·p0.95:   7.610 ms/op
                 listUser·p0.99:   9.634 ms/op
                 listUser·p0.999:  18.448 ms/op
                 listUser·p0.9999: 30.470 ms/op
                 listUser·p1.00:   30.802 ms/op

Iteration   3: 4.982 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.241 ms/op
                 listUser·p0.50:   4.678 ms/op
                 listUser·p0.90:   6.709 ms/op
                 listUser·p0.95:   7.553 ms/op
                 listUser·p0.99:   9.339 ms/op
                 listUser·p0.999:  19.792 ms/op
                 listUser·p0.9999: 23.167 ms/op
                 listUser·p1.00:   23.658 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 192085
  mean =      4.994 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 454 
    [ 2.500,  5.000) = 125449 
    [ 5.000,  7.500) = 56434 
    [ 7.500, 10.000) = 8529 
    [10.000, 12.500) = 789 
    [12.500, 15.000) = 166 
    [15.000, 17.500) = 80 
    [17.500, 20.000) = 75 
    [20.000, 22.500) = 60 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 21 
    [27.500, 30.000) = 3 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.935 ms/op
     p(50.0000) =      4.686 ms/op
     p(90.0000) =      6.693 ms/op
     p(95.0000) =      7.512 ms/op
     p(99.0000) =      9.306 ms/op
     p(99.9000) =     17.433 ms/op
     p(99.9900) =     25.892 ms/op
     p(99.9990) =     30.681 ms/op
     p(99.9999) =     30.802 ms/op
    p(100.0000) =     30.802 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.189 ± 0.852  ops/ms
ClientGrpc.existUser                       thrpt       3   8.706 ± 4.681  ops/ms
ClientGrpc.getUser                         thrpt       3   8.383 ± 4.093  ops/ms
ClientGrpc.listUser                        thrpt       3   6.422 ± 1.492  ops/ms
ClientGrpc.createUser                       avgt       3   3.926 ± 1.027   ms/op
ClientGrpc.existUser                        avgt       3   3.622 ± 0.419   ms/op
ClientGrpc.getUser                          avgt       3   3.779 ± 1.048   ms/op
ClientGrpc.listUser                         avgt       3   4.890 ± 0.541   ms/op
ClientGrpc.createUser                     sample  250622   3.831 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.957           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.740           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.612           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.973           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.488           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.955           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.870           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.331           ms/op
ClientGrpc.existUser                      sample  267217   3.591 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.807           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.502           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.399           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.891           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.382           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.351           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          24.112           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.559           ms/op
ClientGrpc.getUser                        sample  255106   3.762 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.864           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.678           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.637           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.120           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.857           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.894           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          27.131           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          28.312           ms/op
ClientGrpc.listUser                       sample  192085   4.994 ± 0.010   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.935           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.686           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.693           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.512           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.306           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.433           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.892           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          30.802           ms/op
