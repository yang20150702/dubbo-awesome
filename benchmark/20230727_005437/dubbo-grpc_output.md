# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.823 ops/ms
# Warmup Iteration   2: 4.194 ops/ms
# Warmup Iteration   3: 6.434 ops/ms
Iteration   1: 6.552 ops/ms
Iteration   2: 6.816 ops/ms
Iteration   3: 7.136 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  6.834 ±(99.9%) 5.334 ops/ms [Average]
  (min, avg, max) = (6.552, 6.834, 7.136), stdev = 0.292
  CI (99.9%): [1.501, 12.168] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.458 ops/ms
# Warmup Iteration   2: 6.551 ops/ms
# Warmup Iteration   3: 7.120 ops/ms
Iteration   1: 6.994 ops/ms
Iteration   2: 7.500 ops/ms
Iteration   3: 7.195 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.229 ±(99.9%) 4.651 ops/ms [Average]
  (min, avg, max) = (6.994, 7.229, 7.500), stdev = 0.255
  CI (99.9%): [2.578, 11.880] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 4.109 ops/ms
# Warmup Iteration   2: 5.953 ops/ms
# Warmup Iteration   3: 6.644 ops/ms
Iteration   1: 7.014 ops/ms
Iteration   2: 6.951 ops/ms
Iteration   3: 6.837 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  6.934 ±(99.9%) 1.628 ops/ms [Average]
  (min, avg, max) = (6.837, 6.934, 7.014), stdev = 0.089
  CI (99.9%): [5.306, 8.562] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.817 ops/ms
# Warmup Iteration   2: 4.627 ops/ms
# Warmup Iteration   3: 5.259 ops/ms
Iteration   1: 5.181 ops/ms
Iteration   2: 5.286 ops/ms
Iteration   3: 5.044 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.170 ±(99.9%) 2.213 ops/ms [Average]
  (min, avg, max) = (5.044, 5.170, 5.286), stdev = 0.121
  CI (99.9%): [2.957, 7.383] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 7.293 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 5.205 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 5.002 ±(99.9%) 0.009 ms/op
Iteration   1: 4.863 ±(99.9%) 0.004 ms/op
Iteration   2: 4.783 ±(99.9%) 0.004 ms/op
Iteration   3: 4.784 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.810 ±(99.9%) 0.844 ms/op [Average]
  (min, avg, max) = (4.783, 4.810, 4.863), stdev = 0.046
  CI (99.9%): [3.966, 5.653] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 7.035 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.610 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.298 ±(99.9%) 0.006 ms/op
Iteration   1: 4.365 ±(99.9%) 0.003 ms/op
Iteration   2: 4.349 ±(99.9%) 0.004 ms/op
Iteration   3: 4.383 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.366 ±(99.9%) 0.314 ms/op [Average]
  (min, avg, max) = (4.349, 4.366, 4.383), stdev = 0.017
  CI (99.9%): [4.052, 4.680] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 6.658 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.942 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.531 ±(99.9%) 0.006 ms/op
Iteration   1: 4.432 ±(99.9%) 0.005 ms/op
Iteration   2: 4.473 ±(99.9%) 0.004 ms/op
Iteration   3: 4.811 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.572 ±(99.9%) 3.793 ms/op [Average]
  (min, avg, max) = (4.432, 4.572, 4.811), stdev = 0.208
  CI (99.9%): [0.779, 8.365] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 9.098 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 6.455 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 5.894 ±(99.9%) 0.024 ms/op
Iteration   1: 5.966 ±(99.9%) 0.013 ms/op
Iteration   2: 5.803 ±(99.9%) 0.020 ms/op
Iteration   3: 6.111 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.960 ±(99.9%) 2.813 ms/op [Average]
  (min, avg, max) = (5.803, 5.960, 6.111), stdev = 0.154
  CI (99.9%): [3.147, 8.772] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 6.773 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 5.272 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.972 ±(99.9%) 0.018 ms/op
Iteration   1: 5.149 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   1.321 ms/op
                 createUser·p0.50:   4.948 ms/op
                 createUser·p0.90:   6.726 ms/op
                 createUser·p0.95:   7.610 ms/op
                 createUser·p0.99:   10.191 ms/op
                 createUser·p0.999:  16.704 ms/op
                 createUser·p0.9999: 24.183 ms/op
                 createUser·p1.00:   24.576 ms/op

Iteration   2: 4.966 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   1.319 ms/op
                 createUser·p0.50:   4.760 ms/op
                 createUser·p0.90:   6.537 ms/op
                 createUser·p0.95:   7.266 ms/op
                 createUser·p0.99:   9.535 ms/op
                 createUser·p0.999:  12.829 ms/op
                 createUser·p0.9999: 19.927 ms/op
                 createUser·p1.00:   22.151 ms/op

Iteration   3: 4.916 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.405 ms/op
                 createUser·p0.50:   4.760 ms/op
                 createUser·p0.90:   6.144 ms/op
                 createUser·p0.95:   6.709 ms/op
                 createUser·p0.99:   8.618 ms/op
                 createUser·p0.999:  16.724 ms/op
                 createUser·p0.9999: 28.705 ms/op
                 createUser·p1.00:   29.393 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 191516
  mean =      5.008 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3233 
    [ 2.500,  5.000) = 106297 
    [ 5.000,  7.500) = 74407 
    [ 7.500, 10.000) = 6245 
    [10.000, 12.500) = 963 
    [12.500, 15.000) = 155 
    [15.000, 17.500) = 72 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      1.319 ms/op
     p(50.0000) =      4.817 ms/op
     p(90.0000) =      6.463 ms/op
     p(95.0000) =      7.201 ms/op
     p(99.0000) =      9.486 ms/op
     p(99.9000) =     16.056 ms/op
     p(99.9900) =     28.213 ms/op
     p(99.9990) =     29.153 ms/op
     p(99.9999) =     29.393 ms/op
    p(100.0000) =     29.393 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.974 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 4.782 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.431 ±(99.9%) 0.014 ms/op
Iteration   1: 4.718 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   1.145 ms/op
                 existUser·p0.50:   4.506 ms/op
                 existUser·p0.90:   6.316 ms/op
                 existUser·p0.95:   7.217 ms/op
                 existUser·p0.99:   9.601 ms/op
                 existUser·p0.999:  14.183 ms/op
                 existUser·p0.9999: 22.675 ms/op
                 existUser·p1.00:   26.608 ms/op

Iteration   2: 4.661 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.940 ms/op
                 existUser·p0.50:   4.481 ms/op
                 existUser·p0.90:   5.849 ms/op
                 existUser·p0.95:   6.488 ms/op
                 existUser·p0.99:   9.322 ms/op
                 existUser·p0.999:  14.680 ms/op
                 existUser·p0.9999: 20.120 ms/op
                 existUser·p1.00:   22.413 ms/op

Iteration   3: 4.417 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.973 ms/op
                 existUser·p0.50:   4.260 ms/op
                 existUser·p0.90:   5.489 ms/op
                 existUser·p0.95:   6.078 ms/op
                 existUser·p0.99:   8.389 ms/op
                 existUser·p0.999:  12.789 ms/op
                 existUser·p0.9999: 35.258 ms/op
                 existUser·p1.00:   36.962 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 208822
  mean =      4.595 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4510 
    [ 2.500,  5.000) = 148260 
    [ 5.000,  7.500) = 50317 
    [ 7.500, 10.000) = 4529 
    [10.000, 12.500) = 790 
    [12.500, 15.000) = 245 
    [15.000, 17.500) = 70 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 2 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 17 
    [35.000, 37.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.940 ms/op
     p(50.0000) =      4.399 ms/op
     p(90.0000) =      5.890 ms/op
     p(95.0000) =      6.636 ms/op
     p(99.0000) =      9.159 ms/op
     p(99.9000) =     14.565 ms/op
     p(99.9900) =     34.734 ms/op
     p(99.9990) =     35.455 ms/op
     p(99.9999) =     36.962 ms/op
    p(100.0000) =     36.962 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 7.406 ±(99.9%) 0.100 ms/op
# Warmup Iteration   2: 5.192 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.848 ±(99.9%) 0.017 ms/op
Iteration   1: 4.652 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.202 ms/op
                 getUser·p0.50:   4.489 ms/op
                 getUser·p0.90:   5.923 ms/op
                 getUser·p0.95:   6.611 ms/op
                 getUser·p0.99:   9.110 ms/op
                 getUser·p0.999:  14.553 ms/op
                 getUser·p0.9999: 19.444 ms/op
                 getUser·p1.00:   19.956 ms/op

Iteration   2: 4.727 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.014 ms/op
                 getUser·p0.50:   4.588 ms/op
                 getUser·p0.90:   5.923 ms/op
                 getUser·p0.95:   6.492 ms/op
                 getUser·p0.99:   8.880 ms/op
                 getUser·p0.999:  14.852 ms/op
                 getUser·p0.9999: 21.953 ms/op
                 getUser·p1.00:   22.577 ms/op

Iteration   3: 4.522 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.214 ms/op
                 getUser·p0.50:   4.383 ms/op
                 getUser·p0.90:   5.751 ms/op
                 getUser·p0.95:   6.373 ms/op
                 getUser·p0.99:   8.454 ms/op
                 getUser·p0.999:  11.478 ms/op
                 getUser·p0.9999: 26.835 ms/op
                 getUser·p1.00:   29.131 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 207094
  mean =      4.632 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4538 
    [ 2.500,  5.000) = 144300 
    [ 5.000,  7.500) = 53614 
    [ 7.500, 10.000) = 3662 
    [10.000, 12.500) = 700 
    [12.500, 15.000) = 116 
    [15.000, 17.500) = 39 
    [17.500, 20.000) = 65 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      1.014 ms/op
     p(50.0000) =      4.481 ms/op
     p(90.0000) =      5.874 ms/op
     p(95.0000) =      6.488 ms/op
     p(99.0000) =      8.815 ms/op
     p(99.9000) =     13.953 ms/op
     p(99.9900) =     25.068 ms/op
     p(99.9990) =     29.058 ms/op
     p(99.9999) =     29.131 ms/op
    p(100.0000) =     29.131 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 8.732 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 6.510 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 6.147 ±(99.9%) 0.024 ms/op
Iteration   1: 6.201 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   1.683 ms/op
                 listUser·p0.50:   5.841 ms/op
                 listUser·p0.90:   8.249 ms/op
                 listUser·p0.95:   9.273 ms/op
                 listUser·p0.99:   11.895 ms/op
                 listUser·p0.999:  19.084 ms/op
                 listUser·p0.9999: 25.342 ms/op
                 listUser·p1.00:   25.690 ms/op

Iteration   2: 5.935 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   1.538 ms/op
                 listUser·p0.50:   5.571 ms/op
                 listUser·p0.90:   8.020 ms/op
                 listUser·p0.95:   9.142 ms/op
                 listUser·p0.99:   11.977 ms/op
                 listUser·p0.999:  20.087 ms/op
                 listUser·p0.9999: 25.854 ms/op
                 listUser·p1.00:   26.018 ms/op

Iteration   3: 6.101 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   2.228 ms/op
                 listUser·p0.50:   5.767 ms/op
                 listUser·p0.90:   7.954 ms/op
                 listUser·p0.95:   9.126 ms/op
                 listUser·p0.99:   11.780 ms/op
                 listUser·p0.999:  22.566 ms/op
                 listUser·p0.9999: 31.187 ms/op
                 listUser·p1.00:   31.588 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 157932
  mean =      6.077 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 74 
    [ 2.500,  5.000) = 35624 
    [ 5.000,  7.500) = 99586 
    [ 7.500, 10.000) = 17852 
    [10.000, 12.500) = 3644 
    [12.500, 15.000) = 725 
    [15.000, 17.500) = 176 
    [17.500, 20.000) = 103 
    [20.000, 22.500) = 55 
    [22.500, 25.000) = 41 
    [25.000, 27.500) = 20 
    [27.500, 30.000) = 24 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.538 ms/op
     p(50.0000) =      5.726 ms/op
     p(90.0000) =      8.086 ms/op
     p(95.0000) =      9.191 ms/op
     p(99.0000) =     11.878 ms/op
     p(99.9000) =     19.726 ms/op
     p(99.9900) =     29.786 ms/op
     p(99.9990) =     31.474 ms/op
     p(99.9999) =     31.588 ms/op
    p(100.0000) =     31.588 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   6.834 ± 5.334  ops/ms
ClientGrpc.existUser                       thrpt       3   7.229 ± 4.651  ops/ms
ClientGrpc.getUser                         thrpt       3   6.934 ± 1.628  ops/ms
ClientGrpc.listUser                        thrpt       3   5.170 ± 2.213  ops/ms
ClientGrpc.createUser                       avgt       3   4.810 ± 0.844   ms/op
ClientGrpc.existUser                        avgt       3   4.366 ± 0.314   ms/op
ClientGrpc.getUser                          avgt       3   4.572 ± 3.793   ms/op
ClientGrpc.listUser                         avgt       3   5.960 ± 2.813   ms/op
ClientGrpc.createUser                     sample  191516   5.008 ± 0.010   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.319           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.817           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           6.463           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           7.201           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           9.486           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          16.056           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          28.213           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          29.393           ms/op
ClientGrpc.existUser                      sample  208822   4.595 ± 0.009   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.940           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.399           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.890           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           6.636           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           9.159           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          14.565           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          34.734           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          36.962           ms/op
ClientGrpc.getUser                        sample  207094   4.632 ± 0.009   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.014           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.481           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.874           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.488           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           8.815           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          13.953           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          25.068           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          29.131           ms/op
ClientGrpc.listUser                       sample  157932   6.077 ± 0.014   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.538           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.726           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           8.086           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           9.191           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          11.878           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.726           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          29.786           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          31.588           ms/op
