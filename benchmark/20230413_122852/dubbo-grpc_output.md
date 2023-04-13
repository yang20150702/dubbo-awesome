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
# Warmup Iteration   1: 2.177 ops/ms
# Warmup Iteration   2: 5.146 ops/ms
# Warmup Iteration   3: 6.739 ops/ms
Iteration   1: 7.142 ops/ms
Iteration   2: 7.137 ops/ms
Iteration   3: 7.236 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.172 ±(99.9%) 1.019 ops/ms [Average]
  (min, avg, max) = (7.137, 7.172, 7.236), stdev = 0.056
  CI (99.9%): [6.153, 8.191] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.266 ops/ms
# Warmup Iteration   2: 6.831 ops/ms
# Warmup Iteration   3: 7.517 ops/ms
Iteration   1: 7.588 ops/ms
Iteration   2: 7.421 ops/ms
Iteration   3: 7.757 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.589 ±(99.9%) 3.062 ops/ms [Average]
  (min, avg, max) = (7.421, 7.589, 7.757), stdev = 0.168
  CI (99.9%): [4.527, 10.651] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 4.060 ops/ms
# Warmup Iteration   2: 6.517 ops/ms
# Warmup Iteration   3: 6.875 ops/ms
Iteration   1: 7.149 ops/ms
Iteration   2: 7.152 ops/ms
Iteration   3: 7.123 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.141 ±(99.9%) 0.285 ops/ms [Average]
  (min, avg, max) = (7.123, 7.141, 7.152), stdev = 0.016
  CI (99.9%): [6.856, 7.426] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.334 ops/ms
# Warmup Iteration   2: 5.041 ops/ms
# Warmup Iteration   3: 5.471 ops/ms
Iteration   1: 5.532 ops/ms
Iteration   2: 5.575 ops/ms
Iteration   3: 5.603 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.570 ±(99.9%) 0.647 ops/ms [Average]
  (min, avg, max) = (5.532, 5.570, 5.603), stdev = 0.035
  CI (99.9%): [4.924, 6.217] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.903 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 5.025 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.700 ±(99.9%) 0.018 ms/op
Iteration   1: 4.563 ±(99.9%) 0.003 ms/op
Iteration   2: 4.603 ±(99.9%) 0.007 ms/op
Iteration   3: 4.649 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.605 ±(99.9%) 0.787 ms/op [Average]
  (min, avg, max) = (4.563, 4.605, 4.649), stdev = 0.043
  CI (99.9%): [3.817, 5.392] (assumes normal distribution)


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
# Warmup Iteration   1: 6.881 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.801 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.390 ±(99.9%) 0.007 ms/op
Iteration   1: 4.308 ±(99.9%) 0.004 ms/op
Iteration   2: 4.415 ±(99.9%) 0.003 ms/op
Iteration   3: 4.364 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.362 ±(99.9%) 0.975 ms/op [Average]
  (min, avg, max) = (4.308, 4.362, 4.415), stdev = 0.053
  CI (99.9%): [3.387, 5.338] (assumes normal distribution)


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
# Warmup Iteration   1: 6.800 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.917 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.578 ±(99.9%) 0.032 ms/op
Iteration   1: 4.488 ±(99.9%) 0.022 ms/op
Iteration   2: 4.426 ±(99.9%) 0.004 ms/op
Iteration   3: 4.487 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.467 ±(99.9%) 0.646 ms/op [Average]
  (min, avg, max) = (4.426, 4.467, 4.488), stdev = 0.035
  CI (99.9%): [3.821, 5.113] (assumes normal distribution)


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
# Warmup Iteration   1: 8.672 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 6.206 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 5.763 ±(99.9%) 0.014 ms/op
Iteration   1: 5.888 ±(99.9%) 0.018 ms/op
Iteration   2: 5.623 ±(99.9%) 0.025 ms/op
Iteration   3: 5.767 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.759 ±(99.9%) 2.426 ms/op [Average]
  (min, avg, max) = (5.623, 5.759, 5.888), stdev = 0.133
  CI (99.9%): [3.334, 8.185] (assumes normal distribution)


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
# Warmup Iteration   1: 6.827 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 5.274 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.695 ±(99.9%) 0.014 ms/op
Iteration   1: 4.681 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.100 ms/op
                 createUser·p0.50:   4.497 ms/op
                 createUser·p0.90:   5.931 ms/op
                 createUser·p0.95:   6.529 ms/op
                 createUser·p0.99:   8.929 ms/op
                 createUser·p0.999:  13.676 ms/op
                 createUser·p0.9999: 16.695 ms/op
                 createUser·p1.00:   17.990 ms/op

Iteration   2: 4.674 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.325 ms/op
                 createUser·p0.50:   4.547 ms/op
                 createUser·p0.90:   5.775 ms/op
                 createUser·p0.95:   6.300 ms/op
                 createUser·p0.99:   8.020 ms/op
                 createUser·p0.999:  13.889 ms/op
                 createUser·p0.9999: 19.251 ms/op
                 createUser·p1.00:   20.087 ms/op

Iteration   3: 4.645 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.268 ms/op
                 createUser·p0.50:   4.489 ms/op
                 createUser·p0.90:   5.849 ms/op
                 createUser·p0.95:   6.349 ms/op
                 createUser·p0.99:   8.184 ms/op
                 createUser·p0.999:  13.737 ms/op
                 createUser·p0.9999: 25.272 ms/op
                 createUser·p1.00:   25.821 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 205447
  mean =      4.667 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2008 
    [ 2.500,  5.000) = 143390 
    [ 5.000,  7.500) = 56398 
    [ 7.500, 10.000) = 2739 
    [10.000, 12.500) = 609 
    [12.500, 15.000) = 159 
    [15.000, 17.500) = 84 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      1.100 ms/op
     p(50.0000) =      4.506 ms/op
     p(90.0000) =      5.849 ms/op
     p(95.0000) =      6.398 ms/op
     p(99.0000) =      8.356 ms/op
     p(99.9000) =     13.730 ms/op
     p(99.9900) =     24.213 ms/op
     p(99.9990) =     25.718 ms/op
     p(99.9999) =     25.821 ms/op
    p(100.0000) =     25.821 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.367 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 4.686 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.259 ±(99.9%) 0.013 ms/op
Iteration   1: 4.395 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.137 ms/op
                 existUser·p0.50:   4.260 ms/op
                 existUser·p0.90:   5.546 ms/op
                 existUser·p0.95:   6.169 ms/op
                 existUser·p0.99:   8.389 ms/op
                 existUser·p0.999:  12.885 ms/op
                 existUser·p0.9999: 16.571 ms/op
                 existUser·p1.00:   19.038 ms/op

Iteration   2: 4.175 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.247 ms/op
                 existUser·p0.50:   4.104 ms/op
                 existUser·p0.90:   5.112 ms/op
                 existUser·p0.95:   5.538 ms/op
                 existUser·p0.99:   7.119 ms/op
                 existUser·p0.999:  12.747 ms/op
                 existUser·p0.9999: 21.048 ms/op
                 existUser·p1.00:   21.496 ms/op

Iteration   3: 4.304 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.833 ms/op
                 existUser·p0.50:   4.149 ms/op
                 existUser·p0.90:   5.341 ms/op
                 existUser·p0.95:   5.816 ms/op
                 existUser·p0.99:   8.151 ms/op
                 existUser·p0.999:  14.880 ms/op
                 existUser·p0.9999: 32.145 ms/op
                 existUser·p1.00:   32.473 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 223736
  mean =      4.290 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6226 
    [ 2.500,  5.000) = 180834 
    [ 5.000,  7.500) = 33801 
    [ 7.500, 10.000) = 2213 
    [10.000, 12.500) = 375 
    [12.500, 15.000) = 118 
    [15.000, 17.500) = 81 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 4 
    [27.500, 30.000) = 4 
    [30.000, 32.500) = 24 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.833 ms/op
     p(50.0000) =      4.166 ms/op
     p(90.0000) =      5.341 ms/op
     p(95.0000) =      5.841 ms/op
     p(99.0000) =      7.963 ms/op
     p(99.9000) =     13.128 ms/op
     p(99.9900) =     31.158 ms/op
     p(99.9990) =     32.301 ms/op
     p(99.9999) =     32.473 ms/op
    p(100.0000) =     32.473 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 7.146 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 4.959 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.606 ±(99.9%) 0.015 ms/op
Iteration   1: 4.566 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.122 ms/op
                 getUser·p0.50:   4.375 ms/op
                 getUser·p0.90:   5.816 ms/op
                 getUser·p0.95:   6.431 ms/op
                 getUser·p0.99:   9.028 ms/op
                 getUser·p0.999:  15.532 ms/op
                 getUser·p0.9999: 22.019 ms/op
                 getUser·p1.00:   22.348 ms/op

Iteration   2: 4.377 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.147 ms/op
                 getUser·p0.50:   4.252 ms/op
                 getUser·p0.90:   5.456 ms/op
                 getUser·p0.95:   5.915 ms/op
                 getUser·p0.99:   7.668 ms/op
                 getUser·p0.999:  13.939 ms/op
                 getUser·p0.9999: 24.218 ms/op
                 getUser·p1.00:   24.838 ms/op

Iteration   3: 4.520 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   0.970 ms/op
                 getUser·p0.50:   4.342 ms/op
                 getUser·p0.90:   5.612 ms/op
                 getUser·p0.95:   6.259 ms/op
                 getUser·p0.99:   9.155 ms/op
                 getUser·p0.999:  16.204 ms/op
                 getUser·p0.9999: 24.089 ms/op
                 getUser·p1.00:   24.412 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 213884
  mean =      4.486 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4896 
    [ 2.500,  5.000) = 160768 
    [ 5.000,  7.500) = 44350 
    [ 7.500, 10.000) = 2641 
    [10.000, 12.500) = 729 
    [12.500, 15.000) = 229 
    [15.000, 17.500) = 121 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 71 
    [22.500, 25.000) = 60 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.970 ms/op
     p(50.0000) =      4.317 ms/op
     p(90.0000) =      5.636 ms/op
     p(95.0000) =      6.193 ms/op
     p(99.0000) =      8.700 ms/op
     p(99.9000) =     15.698 ms/op
     p(99.9900) =     23.620 ms/op
     p(99.9990) =     24.759 ms/op
     p(99.9999) =     24.838 ms/op
    p(100.0000) =     24.838 ms/op


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
# Warmup Iteration   1: 9.020 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 6.444 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 5.959 ±(99.9%) 0.024 ms/op
Iteration   1: 5.641 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   0.513 ms/op
                 listUser·p0.50:   5.349 ms/op
                 listUser·p0.90:   7.619 ms/op
                 listUser·p0.95:   8.552 ms/op
                 listUser·p0.99:   10.764 ms/op
                 listUser·p0.999:  15.491 ms/op
                 listUser·p0.9999: 20.589 ms/op
                 listUser·p1.00:   21.168 ms/op

Iteration   2: 5.864 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.606 ms/op
                 listUser·p0.50:   5.538 ms/op
                 listUser·p0.90:   7.668 ms/op
                 listUser·p0.95:   8.618 ms/op
                 listUser·p0.99:   10.928 ms/op
                 listUser·p0.999:  19.511 ms/op
                 listUser·p0.9999: 22.875 ms/op
                 listUser·p1.00:   23.396 ms/op

Iteration   3: 5.728 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.268 ms/op
                 listUser·p0.50:   5.423 ms/op
                 listUser·p0.90:   7.561 ms/op
                 listUser·p0.95:   8.454 ms/op
                 listUser·p0.99:   10.740 ms/op
                 listUser·p0.999:  20.918 ms/op
                 listUser·p0.9999: 27.364 ms/op
                 listUser·p1.00:   27.820 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 167113
  mean =      5.743 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 186 
    [ 2.500,  5.000) = 51842 
    [ 5.000,  7.500) = 96968 
    [ 7.500, 10.000) = 15252 
    [10.000, 12.500) = 2151 
    [12.500, 15.000) = 389 
    [15.000, 17.500) = 108 
    [17.500, 20.000) = 85 
    [20.000, 22.500) = 70 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.513 ms/op
     p(50.0000) =      5.439 ms/op
     p(90.0000) =      7.619 ms/op
     p(95.0000) =      8.552 ms/op
     p(99.0000) =     10.797 ms/op
     p(99.9000) =     18.579 ms/op
     p(99.9900) =     25.657 ms/op
     p(99.9990) =     27.732 ms/op
     p(99.9999) =     27.820 ms/op
    p(100.0000) =     27.820 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.172 ± 1.019  ops/ms
ClientGrpc.existUser                       thrpt       3   7.589 ± 3.062  ops/ms
ClientGrpc.getUser                         thrpt       3   7.141 ± 0.285  ops/ms
ClientGrpc.listUser                        thrpt       3   5.570 ± 0.647  ops/ms
ClientGrpc.createUser                       avgt       3   4.605 ± 0.787   ms/op
ClientGrpc.existUser                        avgt       3   4.362 ± 0.975   ms/op
ClientGrpc.getUser                          avgt       3   4.467 ± 0.646   ms/op
ClientGrpc.listUser                         avgt       3   5.759 ± 2.426   ms/op
ClientGrpc.createUser                     sample  205447   4.667 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.100           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.506           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.849           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.398           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           8.356           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.730           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.213           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.821           ms/op
ClientGrpc.existUser                      sample  223736   4.290 ± 0.008   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.833           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.166           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.341           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.841           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.963           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          13.128           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          31.158           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          32.473           ms/op
ClientGrpc.getUser                        sample  213884   4.486 ± 0.009   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.970           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.317           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.636           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.193           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           8.700           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          15.698           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.620           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.838           ms/op
ClientGrpc.listUser                       sample  167113   5.743 ± 0.012   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.513           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.439           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.619           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.552           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.797           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.579           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.657           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.820           ms/op
