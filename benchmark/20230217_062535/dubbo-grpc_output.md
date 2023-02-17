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
# Warmup Iteration   1: 2.374 ops/ms
# Warmup Iteration   2: 5.863 ops/ms
# Warmup Iteration   3: 6.971 ops/ms
Iteration   1: 7.226 ops/ms
Iteration   2: 7.145 ops/ms
Iteration   3: 7.365 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.245 ±(99.9%) 2.028 ops/ms [Average]
  (min, avg, max) = (7.145, 7.245, 7.365), stdev = 0.111
  CI (99.9%): [5.217, 9.273] (assumes normal distribution)


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
# Warmup Iteration   1: 4.907 ops/ms
# Warmup Iteration   2: 7.175 ops/ms
# Warmup Iteration   3: 7.586 ops/ms
Iteration   1: 7.460 ops/ms
Iteration   2: 7.560 ops/ms
Iteration   3: 7.490 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.503 ±(99.9%) 0.934 ops/ms [Average]
  (min, avg, max) = (7.460, 7.503, 7.560), stdev = 0.051
  CI (99.9%): [6.569, 8.438] (assumes normal distribution)


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
# Warmup Iteration   1: 4.330 ops/ms
# Warmup Iteration   2: 6.460 ops/ms
# Warmup Iteration   3: 6.862 ops/ms
Iteration   1: 6.981 ops/ms
Iteration   2: 7.188 ops/ms
Iteration   3: 6.908 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.026 ±(99.9%) 2.649 ops/ms [Average]
  (min, avg, max) = (6.908, 7.026, 7.188), stdev = 0.145
  CI (99.9%): [4.377, 9.674] (assumes normal distribution)


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
# Warmup Iteration   1: 3.770 ops/ms
# Warmup Iteration   2: 5.261 ops/ms
# Warmup Iteration   3: 5.732 ops/ms
Iteration   1: 6.127 ops/ms
Iteration   2: 5.933 ops/ms
Iteration   3: 5.722 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.927 ±(99.9%) 3.688 ops/ms [Average]
  (min, avg, max) = (5.722, 5.927, 6.127), stdev = 0.202
  CI (99.9%): [2.239, 9.615] (assumes normal distribution)


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
# Warmup Iteration   1: 6.651 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.717 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.614 ±(99.9%) 0.003 ms/op
Iteration   1: 4.497 ±(99.9%) 0.003 ms/op
Iteration   2: 4.588 ±(99.9%) 0.003 ms/op
Iteration   3: 4.528 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.537 ±(99.9%) 0.844 ms/op [Average]
  (min, avg, max) = (4.497, 4.537, 4.588), stdev = 0.046
  CI (99.9%): [3.694, 5.381] (assumes normal distribution)


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
# Warmup Iteration   1: 5.985 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.557 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.192 ±(99.9%) 0.004 ms/op
Iteration   1: 4.228 ±(99.9%) 0.005 ms/op
Iteration   2: 4.259 ±(99.9%) 0.003 ms/op
Iteration   3: 4.228 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.238 ±(99.9%) 0.333 ms/op [Average]
  (min, avg, max) = (4.228, 4.238, 4.259), stdev = 0.018
  CI (99.9%): [3.905, 4.572] (assumes normal distribution)


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
# Warmup Iteration   1: 6.237 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.716 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.382 ±(99.9%) 0.005 ms/op
Iteration   1: 4.260 ±(99.9%) 0.005 ms/op
Iteration   2: 4.432 ±(99.9%) 0.003 ms/op
Iteration   3: 4.239 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.310 ±(99.9%) 1.932 ms/op [Average]
  (min, avg, max) = (4.239, 4.310, 4.432), stdev = 0.106
  CI (99.9%): [2.379, 6.242] (assumes normal distribution)


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
# Warmup Iteration   1: 7.589 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 6.004 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 5.392 ±(99.9%) 0.011 ms/op
Iteration   1: 5.365 ±(99.9%) 0.007 ms/op
Iteration   2: 5.154 ±(99.9%) 0.010 ms/op
Iteration   3: 5.181 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.233 ±(99.9%) 2.099 ms/op [Average]
  (min, avg, max) = (5.154, 5.233, 5.365), stdev = 0.115
  CI (99.9%): [3.134, 7.332] (assumes normal distribution)


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
# Warmup Iteration   1: 6.569 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 4.665 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.526 ±(99.9%) 0.014 ms/op
Iteration   1: 4.452 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.149 ms/op
                 createUser·p0.50:   4.342 ms/op
                 createUser·p0.90:   5.718 ms/op
                 createUser·p0.95:   6.119 ms/op
                 createUser·p0.99:   7.704 ms/op
                 createUser·p0.999:  12.276 ms/op
                 createUser·p0.9999: 24.519 ms/op
                 createUser·p1.00:   25.035 ms/op

Iteration   2: 4.468 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.217 ms/op
                 createUser·p0.50:   4.366 ms/op
                 createUser·p0.90:   5.587 ms/op
                 createUser·p0.95:   6.005 ms/op
                 createUser·p0.99:   7.815 ms/op
                 createUser·p0.999:  12.865 ms/op
                 createUser·p0.9999: 17.919 ms/op
                 createUser·p1.00:   18.350 ms/op

Iteration   3: 4.459 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.182 ms/op
                 createUser·p0.50:   4.366 ms/op
                 createUser·p0.90:   5.726 ms/op
                 createUser·p0.95:   6.128 ms/op
                 createUser·p0.99:   7.643 ms/op
                 createUser·p0.999:  13.310 ms/op
                 createUser·p0.9999: 25.088 ms/op
                 createUser·p1.00:   25.559 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 215192
  mean =      4.460 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4166 
    [ 2.500,  5.000) = 155248 
    [ 5.000,  7.500) = 53260 
    [ 7.500, 10.000) = 2051 
    [10.000, 12.500) = 243 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 84 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 41 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      1.149 ms/op
     p(50.0000) =      4.358 ms/op
     p(90.0000) =      5.677 ms/op
     p(95.0000) =      6.095 ms/op
     p(99.0000) =      7.717 ms/op
     p(99.9000) =     12.908 ms/op
     p(99.9900) =     24.592 ms/op
     p(99.9990) =     25.511 ms/op
     p(99.9999) =     25.559 ms/op
    p(100.0000) =     25.559 ms/op


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
# Warmup Iteration   1: 6.039 ±(99.9%) 0.071 ms/op
# Warmup Iteration   2: 4.556 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.456 ±(99.9%) 0.013 ms/op
Iteration   1: 4.354 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.102 ms/op
                 existUser·p0.50:   4.235 ms/op
                 existUser·p0.90:   5.612 ms/op
                 existUser·p0.95:   6.087 ms/op
                 existUser·p0.99:   7.504 ms/op
                 existUser·p0.999:  10.284 ms/op
                 existUser·p0.9999: 17.356 ms/op
                 existUser·p1.00:   17.793 ms/op

Iteration   2: 4.295 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.231 ms/op
                 existUser·p0.50:   4.194 ms/op
                 existUser·p0.90:   5.407 ms/op
                 existUser·p0.95:   5.784 ms/op
                 existUser·p0.99:   6.955 ms/op
                 existUser·p0.999:  11.921 ms/op
                 existUser·p0.9999: 18.368 ms/op
                 existUser·p1.00:   18.711 ms/op

Iteration   3: 4.224 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.059 ms/op
                 existUser·p0.50:   4.145 ms/op
                 existUser·p0.90:   5.399 ms/op
                 existUser·p0.95:   5.767 ms/op
                 existUser·p0.99:   7.045 ms/op
                 existUser·p0.999:  10.794 ms/op
                 existUser·p0.9999: 20.513 ms/op
                 existUser·p1.00:   20.873 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 223627
  mean =      4.290 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4149 
    [ 2.500,  5.000) = 173221 
    [ 5.000,  7.500) = 44554 
    [ 7.500, 10.000) = 1334 
    [10.000, 12.500) = 258 
    [12.500, 15.000) = 7 
    [15.000, 17.500) = 46 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.059 ms/op
     p(50.0000) =      4.194 ms/op
     p(90.0000) =      5.464 ms/op
     p(95.0000) =      5.882 ms/op
     p(99.0000) =      7.193 ms/op
     p(99.9000) =     11.235 ms/op
     p(99.9900) =     19.723 ms/op
     p(99.9990) =     20.744 ms/op
     p(99.9999) =     20.873 ms/op
    p(100.0000) =     20.873 ms/op


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
# Warmup Iteration   1: 6.762 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 4.643 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.328 ±(99.9%) 0.013 ms/op
Iteration   1: 4.497 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.996 ms/op
                 getUser·p0.50:   4.366 ms/op
                 getUser·p0.90:   5.718 ms/op
                 getUser·p0.95:   6.128 ms/op
                 getUser·p0.99:   7.610 ms/op
                 getUser·p0.999:  10.759 ms/op
                 getUser·p0.9999: 19.562 ms/op
                 getUser·p1.00:   20.218 ms/op

Iteration   2: 4.404 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.214 ms/op
                 getUser·p0.50:   4.293 ms/op
                 getUser·p0.90:   5.636 ms/op
                 getUser·p0.95:   6.054 ms/op
                 getUser·p0.99:   7.619 ms/op
                 getUser·p0.999:  11.911 ms/op
                 getUser·p0.9999: 28.450 ms/op
                 getUser·p1.00:   29.786 ms/op

Iteration   3: 4.519 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.021 ms/op
                 getUser·p0.50:   4.415 ms/op
                 getUser·p0.90:   5.710 ms/op
                 getUser·p0.95:   6.128 ms/op
                 getUser·p0.99:   7.699 ms/op
                 getUser·p0.999:  14.617 ms/op
                 getUser·p0.9999: 26.304 ms/op
                 getUser·p1.00:   27.001 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 214643
  mean =      4.473 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4421 
    [ 2.500,  5.000) = 153567 
    [ 5.000,  7.500) = 54276 
    [ 7.500, 10.000) = 1930 
    [10.000, 12.500) = 244 
    [12.500, 15.000) = 67 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.996 ms/op
     p(50.0000) =      4.358 ms/op
     p(90.0000) =      5.685 ms/op
     p(95.0000) =      6.103 ms/op
     p(99.0000) =      7.643 ms/op
     p(99.9000) =     12.359 ms/op
     p(99.9900) =     28.067 ms/op
     p(99.9990) =     28.821 ms/op
     p(99.9999) =     29.786 ms/op
    p(100.0000) =     29.786 ms/op


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
# Warmup Iteration   1: 8.424 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 5.981 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 5.545 ±(99.9%) 0.019 ms/op
Iteration   1: 5.499 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.751 ms/op
                 listUser·p0.50:   5.202 ms/op
                 listUser·p0.90:   7.307 ms/op
                 listUser·p0.95:   8.077 ms/op
                 listUser·p0.99:   10.502 ms/op
                 listUser·p0.999:  14.917 ms/op
                 listUser·p0.9999: 18.362 ms/op
                 listUser·p1.00:   21.529 ms/op

Iteration   2: 5.419 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.870 ms/op
                 listUser·p0.50:   5.169 ms/op
                 listUser·p0.90:   6.939 ms/op
                 listUser·p0.95:   7.864 ms/op
                 listUser·p0.99:   10.191 ms/op
                 listUser·p0.999:  17.662 ms/op
                 listUser·p0.9999: 21.499 ms/op
                 listUser·p1.00:   21.758 ms/op

Iteration   3: 5.464 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.274 ms/op
                 listUser·p0.50:   5.161 ms/op
                 listUser·p0.90:   7.242 ms/op
                 listUser·p0.95:   8.094 ms/op
                 listUser·p0.99:   10.420 ms/op
                 listUser·p0.999:  19.808 ms/op
                 listUser·p0.9999: 23.696 ms/op
                 listUser·p1.00:   24.117 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 175705
  mean =      5.461 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 137 
    [ 2.500,  5.000) = 73416 
    [ 5.000,  7.500) = 88631 
    [ 7.500, 10.000) = 11338 
    [10.000, 12.500) = 1561 
    [12.500, 15.000) = 353 
    [15.000, 17.500) = 88 
    [17.500, 20.000) = 109 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.274 ms/op
     p(50.0000) =      5.177 ms/op
     p(90.0000) =      7.184 ms/op
     p(95.0000) =      8.012 ms/op
     p(99.0000) =     10.371 ms/op
     p(99.9000) =     17.662 ms/op
     p(99.9900) =     22.624 ms/op
     p(99.9990) =     24.068 ms/op
     p(99.9999) =     24.117 ms/op
    p(100.0000) =     24.117 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.245 ± 2.028  ops/ms
ClientGrpc.existUser                       thrpt       3   7.503 ± 0.934  ops/ms
ClientGrpc.getUser                         thrpt       3   7.026 ± 2.649  ops/ms
ClientGrpc.listUser                        thrpt       3   5.927 ± 3.688  ops/ms
ClientGrpc.createUser                       avgt       3   4.537 ± 0.844   ms/op
ClientGrpc.existUser                        avgt       3   4.238 ± 0.333   ms/op
ClientGrpc.getUser                          avgt       3   4.310 ± 1.932   ms/op
ClientGrpc.listUser                         avgt       3   5.233 ± 2.099   ms/op
ClientGrpc.createUser                     sample  215192   4.460 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.149           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.358           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.677           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.095           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.717           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.908           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.592           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.559           ms/op
ClientGrpc.existUser                      sample  223627   4.290 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           1.059           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.194           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.464           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.882           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.193           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.235           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.723           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.873           ms/op
ClientGrpc.getUser                        sample  214643   4.473 ± 0.008   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.996           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.358           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.685           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.103           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.643           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.359           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          28.067           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          29.786           ms/op
ClientGrpc.listUser                       sample  175705   5.461 ± 0.011   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.274           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.177           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.184           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.012           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.371           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.662           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.624           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.117           ms/op
