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
# Warmup Iteration   1: 2.249 ops/ms
# Warmup Iteration   2: 5.234 ops/ms
# Warmup Iteration   3: 6.914 ops/ms
Iteration   1: 7.117 ops/ms
Iteration   2: 6.869 ops/ms
Iteration   3: 7.102 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.029 ±(99.9%) 2.534 ops/ms [Average]
  (min, avg, max) = (6.869, 7.029, 7.117), stdev = 0.139
  CI (99.9%): [4.495, 9.564] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 4.340 ops/ms
# Warmup Iteration   2: 6.902 ops/ms
# Warmup Iteration   3: 7.412 ops/ms
Iteration   1: 7.685 ops/ms
Iteration   2: 7.365 ops/ms
Iteration   3: 7.246 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.432 ±(99.9%) 4.148 ops/ms [Average]
  (min, avg, max) = (7.246, 7.432, 7.685), stdev = 0.227
  CI (99.9%): [3.284, 11.580] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 4.342 ops/ms
# Warmup Iteration   2: 6.350 ops/ms
# Warmup Iteration   3: 6.869 ops/ms
Iteration   1: 7.007 ops/ms
Iteration   2: 7.001 ops/ms
Iteration   3: 7.137 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.048 ±(99.9%) 1.406 ops/ms [Average]
  (min, avg, max) = (7.001, 7.048, 7.137), stdev = 0.077
  CI (99.9%): [5.643, 8.454] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 3.718 ops/ms
# Warmup Iteration   2: 4.612 ops/ms
# Warmup Iteration   3: 5.152 ops/ms
Iteration   1: 5.276 ops/ms
Iteration   2: 5.515 ops/ms
Iteration   3: 5.247 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.346 ±(99.9%) 2.687 ops/ms [Average]
  (min, avg, max) = (5.247, 5.346, 5.515), stdev = 0.147
  CI (99.9%): [2.659, 8.033] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.242 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 5.327 ±(99.9%) 0.047 ms/op
# Warmup Iteration   3: 5.139 ±(99.9%) 0.005 ms/op
Iteration   1: 4.948 ±(99.9%) 0.005 ms/op
Iteration   2: 4.735 ±(99.9%) 0.004 ms/op
Iteration   3: 4.760 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.814 ±(99.9%) 2.121 ms/op [Average]
  (min, avg, max) = (4.735, 4.814, 4.948), stdev = 0.116
  CI (99.9%): [2.693, 6.935] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 7.304 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.937 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.629 ±(99.9%) 0.002 ms/op
Iteration   1: 4.560 ±(99.9%) 0.003 ms/op
Iteration   2: 4.570 ±(99.9%) 0.002 ms/op
Iteration   3: 4.482 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.537 ±(99.9%) 0.881 ms/op [Average]
  (min, avg, max) = (4.482, 4.537, 4.570), stdev = 0.048
  CI (99.9%): [3.656, 5.418] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 7.657 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 5.415 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 5.174 ±(99.9%) 0.004 ms/op
Iteration   1: 4.757 ±(99.9%) 0.005 ms/op
Iteration   2: 4.727 ±(99.9%) 0.002 ms/op
Iteration   3: 4.692 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.725 ±(99.9%) 0.588 ms/op [Average]
  (min, avg, max) = (4.692, 4.725, 4.757), stdev = 0.032
  CI (99.9%): [4.137, 5.314] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 8.411 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 6.829 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 6.030 ±(99.9%) 0.020 ms/op
Iteration   1: 5.767 ±(99.9%) 0.020 ms/op
Iteration   2: 5.951 ±(99.9%) 0.018 ms/op
Iteration   3: 5.553 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.757 ±(99.9%) 3.629 ms/op [Average]
  (min, avg, max) = (5.553, 5.757, 5.951), stdev = 0.199
  CI (99.9%): [2.128, 9.386] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 7.120 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 5.102 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.841 ±(99.9%) 0.014 ms/op
Iteration   1: 4.667 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.313 ms/op
                 createUser·p0.50:   4.538 ms/op
                 createUser·p0.90:   5.677 ms/op
                 createUser·p0.95:   6.054 ms/op
                 createUser·p0.99:   7.829 ms/op
                 createUser·p0.999:  13.197 ms/op
                 createUser·p0.9999: 26.252 ms/op
                 createUser·p1.00:   27.918 ms/op

Iteration   2: 4.706 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.264 ms/op
                 createUser·p0.50:   4.530 ms/op
                 createUser·p0.90:   5.882 ms/op
                 createUser·p0.95:   6.390 ms/op
                 createUser·p0.99:   8.421 ms/op
                 createUser·p0.999:  15.219 ms/op
                 createUser·p0.9999: 23.520 ms/op
                 createUser·p1.00:   24.084 ms/op

Iteration   3: 4.854 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.118 ms/op
                 createUser·p0.50:   4.719 ms/op
                 createUser·p0.90:   6.062 ms/op
                 createUser·p0.95:   6.570 ms/op
                 createUser·p0.99:   8.520 ms/op
                 createUser·p0.999:  14.557 ms/op
                 createUser·p0.9999: 23.770 ms/op
                 createUser·p1.00:   26.608 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 202470
  mean =      4.741 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1321 
    [ 2.500,  5.000) = 135619 
    [ 5.000,  7.500) = 62236 
    [ 7.500, 10.000) = 2436 
    [10.000, 12.500) = 454 
    [12.500, 15.000) = 244 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 50 
    [22.500, 25.000) = 53 
    [25.000, 27.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      1.118 ms/op
     p(50.0000) =      4.588 ms/op
     p(90.0000) =      5.874 ms/op
     p(95.0000) =      6.357 ms/op
     p(99.0000) =      8.276 ms/op
     p(99.9000) =     14.451 ms/op
     p(99.9900) =     25.387 ms/op
     p(99.9990) =     27.785 ms/op
     p(99.9999) =     27.918 ms/op
    p(100.0000) =     27.918 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 7.167 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 4.693 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.281 ±(99.9%) 0.011 ms/op
Iteration   1: 4.526 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.514 ms/op
                 existUser·p0.50:   4.399 ms/op
                 existUser·p0.90:   5.628 ms/op
                 existUser·p0.95:   6.054 ms/op
                 existUser·p0.99:   7.463 ms/op
                 existUser·p0.999:  11.534 ms/op
                 existUser·p0.9999: 16.428 ms/op
                 existUser·p1.00:   16.744 ms/op

Iteration   2: 4.548 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.362 ms/op
                 existUser·p0.50:   4.465 ms/op
                 existUser·p0.90:   5.530 ms/op
                 existUser·p0.95:   5.890 ms/op
                 existUser·p0.99:   7.217 ms/op
                 existUser·p0.999:  10.743 ms/op
                 existUser·p0.9999: 16.938 ms/op
                 existUser·p1.00:   18.121 ms/op

Iteration   3: 4.699 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.621 ms/op
                 existUser·p0.50:   4.522 ms/op
                 existUser·p0.90:   5.841 ms/op
                 existUser·p0.95:   6.472 ms/op
                 existUser·p0.99:   8.929 ms/op
                 existUser·p0.999:  19.000 ms/op
                 existUser·p0.9999: 24.746 ms/op
                 existUser·p1.00:   25.035 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 209110
  mean =      4.590 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1539 
    [ 2.500,  5.000) = 151503 
    [ 5.000,  7.500) = 53268 
    [ 7.500, 10.000) = 2187 
    [10.000, 12.500) = 341 
    [12.500, 15.000) = 68 
    [15.000, 17.500) = 97 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.514 ms/op
     p(50.0000) =      4.456 ms/op
     p(90.0000) =      5.652 ms/op
     p(95.0000) =      6.128 ms/op
     p(99.0000) =      7.963 ms/op
     p(99.9000) =     14.858 ms/op
     p(99.9900) =     24.510 ms/op
     p(99.9990) =     24.963 ms/op
     p(99.9999) =     25.035 ms/op
    p(100.0000) =     25.035 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 7.487 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 4.912 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.795 ±(99.9%) 0.016 ms/op
Iteration   1: 4.826 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.415 ms/op
                 getUser·p0.50:   4.686 ms/op
                 getUser·p0.90:   5.997 ms/op
                 getUser·p0.95:   6.578 ms/op
                 getUser·p0.99:   8.503 ms/op
                 getUser·p0.999:  13.713 ms/op
                 getUser·p0.9999: 18.579 ms/op
                 getUser·p1.00:   18.940 ms/op

Iteration   2: 4.574 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.032 ms/op
                 getUser·p0.50:   4.424 ms/op
                 getUser·p0.90:   5.800 ms/op
                 getUser·p0.95:   6.316 ms/op
                 getUser·p0.99:   7.954 ms/op
                 getUser·p0.999:  12.435 ms/op
                 getUser·p0.9999: 19.366 ms/op
                 getUser·p1.00:   20.546 ms/op

Iteration   3: 4.713 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.475 ms/op
                 getUser·p0.50:   4.596 ms/op
                 getUser·p0.90:   5.931 ms/op
                 getUser·p0.95:   6.423 ms/op
                 getUser·p0.99:   7.946 ms/op
                 getUser·p0.999:  13.768 ms/op
                 getUser·p0.9999: 22.722 ms/op
                 getUser·p1.00:   24.248 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 204094
  mean =      4.702 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2512 
    [ 2.500,  5.000) = 137820 
    [ 5.000,  7.500) = 60308 
    [ 7.500, 10.000) = 2850 
    [10.000, 12.500) = 341 
    [12.500, 15.000) = 128 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 55 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.032 ms/op
     p(50.0000) =      4.563 ms/op
     p(90.0000) =      5.915 ms/op
     p(95.0000) =      6.431 ms/op
     p(99.0000) =      8.151 ms/op
     p(99.9000) =     13.694 ms/op
     p(99.9900) =     21.561 ms/op
     p(99.9990) =     24.100 ms/op
     p(99.9999) =     24.248 ms/op
    p(100.0000) =     24.248 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 7.817 ±(99.9%) 0.102 ms/op
# Warmup Iteration   2: 6.835 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 5.942 ±(99.9%) 0.021 ms/op
Iteration   1: 6.084 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.997 ms/op
                 listUser·p0.50:   5.792 ms/op
                 listUser·p0.90:   7.922 ms/op
                 listUser·p0.95:   8.897 ms/op
                 listUser·p0.99:   11.338 ms/op
                 listUser·p0.999:  17.513 ms/op
                 listUser·p0.9999: 26.140 ms/op
                 listUser·p1.00:   26.477 ms/op

Iteration   2: 5.900 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   2.003 ms/op
                 listUser·p0.50:   5.612 ms/op
                 listUser·p0.90:   7.594 ms/op
                 listUser·p0.95:   8.684 ms/op
                 listUser·p0.99:   10.905 ms/op
                 listUser·p0.999:  16.966 ms/op
                 listUser·p0.9999: 21.735 ms/op
                 listUser·p1.00:   22.348 ms/op

Iteration   3: 5.917 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.507 ms/op
                 listUser·p0.50:   5.612 ms/op
                 listUser·p0.90:   7.848 ms/op
                 listUser·p0.95:   8.880 ms/op
                 listUser·p0.99:   11.158 ms/op
                 listUser·p0.999:  21.786 ms/op
                 listUser·p0.9999: 26.260 ms/op
                 listUser·p1.00:   27.329 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 160839
  mean =      5.966 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 83 
    [ 2.500,  5.000) = 36760 
    [ 5.000,  7.500) = 104641 
    [ 7.500, 10.000) = 15960 
    [10.000, 12.500) = 2705 
    [12.500, 15.000) = 322 
    [15.000, 17.500) = 175 
    [17.500, 20.000) = 88 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      1.507 ms/op
     p(50.0000) =      5.669 ms/op
     p(90.0000) =      7.799 ms/op
     p(95.0000) =      8.831 ms/op
     p(99.0000) =     11.108 ms/op
     p(99.9000) =     18.721 ms/op
     p(99.9900) =     25.982 ms/op
     p(99.9990) =     26.950 ms/op
     p(99.9999) =     27.329 ms/op
    p(100.0000) =     27.329 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.029 ± 2.534  ops/ms
ClientGrpc.existUser                       thrpt       3   7.432 ± 4.148  ops/ms
ClientGrpc.getUser                         thrpt       3   7.048 ± 1.406  ops/ms
ClientGrpc.listUser                        thrpt       3   5.346 ± 2.687  ops/ms
ClientGrpc.createUser                       avgt       3   4.814 ± 2.121   ms/op
ClientGrpc.existUser                        avgt       3   4.537 ± 0.881   ms/op
ClientGrpc.getUser                          avgt       3   4.725 ± 0.588   ms/op
ClientGrpc.listUser                         avgt       3   5.757 ± 3.629   ms/op
ClientGrpc.createUser                     sample  202470   4.741 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.118           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.588           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.874           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.357           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           8.276           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          14.451           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          25.387           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.918           ms/op
ClientGrpc.existUser                      sample  209110   4.590 ± 0.008   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.514           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.456           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.652           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           6.128           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.963           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          14.858           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          24.510           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.035           ms/op
ClientGrpc.getUser                        sample  204094   4.702 ± 0.008   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.032           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.563           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.915           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.431           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           8.151           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          13.694           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.561           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.248           ms/op
ClientGrpc.listUser                       sample  160839   5.966 ± 0.013   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.507           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.669           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.799           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.831           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          11.108           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.721           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.982           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.329           ms/op
