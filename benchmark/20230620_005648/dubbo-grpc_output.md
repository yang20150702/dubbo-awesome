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
# Warmup Iteration   1: 3.039 ops/ms
# Warmup Iteration   2: 7.322 ops/ms
# Warmup Iteration   3: 8.224 ops/ms
Iteration   1: 8.365 ops/ms
Iteration   2: 8.517 ops/ms
Iteration   3: 8.112 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.331 ±(99.9%) 3.734 ops/ms [Average]
  (min, avg, max) = (8.112, 8.331, 8.517), stdev = 0.205
  CI (99.9%): [4.598, 12.065] (assumes normal distribution)


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
# Warmup Iteration   1: 5.247 ops/ms
# Warmup Iteration   2: 8.378 ops/ms
# Warmup Iteration   3: 8.633 ops/ms
Iteration   1: 8.592 ops/ms
Iteration   2: 8.406 ops/ms
Iteration   3: 8.436 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.478 ±(99.9%) 1.825 ops/ms [Average]
  (min, avg, max) = (8.406, 8.478, 8.592), stdev = 0.100
  CI (99.9%): [6.653, 10.303] (assumes normal distribution)


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
# Warmup Iteration   1: 4.575 ops/ms
# Warmup Iteration   2: 7.438 ops/ms
# Warmup Iteration   3: 8.003 ops/ms
Iteration   1: 7.923 ops/ms
Iteration   2: 7.874 ops/ms
Iteration   3: 8.316 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.038 ±(99.9%) 4.426 ops/ms [Average]
  (min, avg, max) = (7.874, 8.038, 8.316), stdev = 0.243
  CI (99.9%): [3.612, 12.464] (assumes normal distribution)


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
# Warmup Iteration   1: 4.271 ops/ms
# Warmup Iteration   2: 5.774 ops/ms
# Warmup Iteration   3: 6.317 ops/ms
Iteration   1: 6.216 ops/ms
Iteration   2: 6.364 ops/ms
Iteration   3: 6.621 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.400 ±(99.9%) 3.733 ops/ms [Average]
  (min, avg, max) = (6.216, 6.400, 6.621), stdev = 0.205
  CI (99.9%): [2.667, 10.134] (assumes normal distribution)


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
# Warmup Iteration   1: 5.070 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.964 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.843 ±(99.9%) 0.004 ms/op
Iteration   1: 3.849 ±(99.9%) 0.011 ms/op
Iteration   2: 3.944 ±(99.9%) 0.003 ms/op
Iteration   3: 3.835 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.876 ±(99.9%) 1.087 ms/op [Average]
  (min, avg, max) = (3.835, 3.876, 3.944), stdev = 0.060
  CI (99.9%): [2.789, 4.963] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 5.296 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.909 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.682 ±(99.9%) 0.002 ms/op
Iteration   1: 3.788 ±(99.9%) 0.002 ms/op
Iteration   2: 3.767 ±(99.9%) 0.003 ms/op
Iteration   3: 3.598 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.718 ±(99.9%) 1.896 ms/op [Average]
  (min, avg, max) = (3.598, 3.718, 3.788), stdev = 0.104
  CI (99.9%): [1.822, 5.614] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 5.755 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 4.281 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.299 ±(99.9%) 0.004 ms/op
Iteration   1: 4.085 ±(99.9%) 0.004 ms/op
Iteration   2: 3.997 ±(99.9%) 0.003 ms/op
Iteration   3: 3.868 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.983 ±(99.9%) 1.992 ms/op [Average]
  (min, avg, max) = (3.868, 3.983, 4.085), stdev = 0.109
  CI (99.9%): [1.992, 5.975] (assumes normal distribution)


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
# Warmup Iteration   1: 7.639 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 5.344 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 5.114 ±(99.9%) 0.014 ms/op
Iteration   1: 4.812 ±(99.9%) 0.011 ms/op
Iteration   2: 5.084 ±(99.9%) 0.012 ms/op
Iteration   3: 5.011 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.969 ±(99.9%) 2.573 ms/op [Average]
  (min, avg, max) = (4.812, 4.969, 5.084), stdev = 0.141
  CI (99.9%): [2.396, 7.542] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 6.010 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 4.151 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.906 ±(99.9%) 0.011 ms/op
Iteration   1: 3.726 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.993 ms/op
                 createUser·p0.50:   3.613 ms/op
                 createUser·p0.90:   4.702 ms/op
                 createUser·p0.95:   5.136 ms/op
                 createUser·p0.99:   6.545 ms/op
                 createUser·p0.999:  10.541 ms/op
                 createUser·p0.9999: 24.369 ms/op
                 createUser·p1.00:   26.608 ms/op

Iteration   2: 3.670 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.994 ms/op
                 createUser·p0.50:   3.568 ms/op
                 createUser·p0.90:   4.571 ms/op
                 createUser·p0.95:   4.923 ms/op
                 createUser·p0.99:   5.751 ms/op
                 createUser·p0.999:  9.975 ms/op
                 createUser·p0.9999: 27.197 ms/op
                 createUser·p1.00:   27.787 ms/op

Iteration   3: 3.723 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.042 ms/op
                 createUser·p0.50:   3.637 ms/op
                 createUser·p0.90:   4.489 ms/op
                 createUser·p0.95:   4.784 ms/op
                 createUser·p0.99:   5.997 ms/op
                 createUser·p0.999:  11.581 ms/op
                 createUser·p0.9999: 30.291 ms/op
                 createUser·p1.00:   31.752 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 259000
  mean =      3.706 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6219 
    [ 2.500,  5.000) = 241038 
    [ 5.000,  7.500) = 10841 
    [ 7.500, 10.000) = 555 
    [10.000, 12.500) = 154 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 54 
    [25.000, 27.500) = 59 
    [27.500, 30.000) = 35 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.993 ms/op
     p(50.0000) =      3.609 ms/op
     p(90.0000) =      4.588 ms/op
     p(95.0000) =      4.948 ms/op
     p(99.0000) =      6.111 ms/op
     p(99.9000) =     11.026 ms/op
     p(99.9900) =     29.626 ms/op
     p(99.9990) =     31.203 ms/op
     p(99.9999) =     31.752 ms/op
    p(100.0000) =     31.752 ms/op


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
# Warmup Iteration   1: 5.040 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.792 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.586 ±(99.9%) 0.010 ms/op
Iteration   1: 3.401 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.933 ms/op
                 existUser·p0.50:   3.322 ms/op
                 existUser·p0.90:   4.211 ms/op
                 existUser·p0.95:   4.530 ms/op
                 existUser·p0.99:   5.710 ms/op
                 existUser·p0.999:  11.076 ms/op
                 existUser·p0.9999: 21.142 ms/op
                 existUser·p1.00:   21.561 ms/op

Iteration   2: 3.578 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.784 ms/op
                 existUser·p0.50:   3.518 ms/op
                 existUser·p0.90:   4.407 ms/op
                 existUser·p0.95:   4.678 ms/op
                 existUser·p0.99:   5.366 ms/op
                 existUser·p0.999:  8.082 ms/op
                 existUser·p0.9999: 24.481 ms/op
                 existUser·p1.00:   24.969 ms/op

Iteration   3: 3.597 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.908 ms/op
                 existUser·p0.50:   3.518 ms/op
                 existUser·p0.90:   4.456 ms/op
                 existUser·p0.95:   4.768 ms/op
                 existUser·p0.99:   5.644 ms/op
                 existUser·p0.999:  18.415 ms/op
                 existUser·p0.9999: 25.369 ms/op
                 existUser·p1.00:   25.690 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 272528
  mean =      3.523 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11238 
    [ 2.500,  5.000) = 254581 
    [ 5.000,  7.500) = 6114 
    [ 7.500, 10.000) = 277 
    [10.000, 12.500) = 147 
    [12.500, 15.000) = 8 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 61 
    [22.500, 25.000) = 49 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.784 ms/op
     p(50.0000) =      3.449 ms/op
     p(90.0000) =      4.366 ms/op
     p(95.0000) =      4.678 ms/op
     p(99.0000) =      5.554 ms/op
     p(99.9000) =     10.608 ms/op
     p(99.9900) =     24.101 ms/op
     p(99.9990) =     25.690 ms/op
     p(99.9999) =     25.690 ms/op
    p(100.0000) =     25.690 ms/op


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
# Warmup Iteration   1: 5.681 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.887 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.743 ±(99.9%) 0.009 ms/op
Iteration   1: 3.719 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.688 ms/op
                 getUser·p0.50:   3.625 ms/op
                 getUser·p0.90:   4.612 ms/op
                 getUser·p0.95:   4.997 ms/op
                 getUser·p0.99:   6.210 ms/op
                 getUser·p0.999:  9.667 ms/op
                 getUser·p0.9999: 17.413 ms/op
                 getUser·p1.00:   17.695 ms/op

Iteration   2: 3.681 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.834 ms/op
                 getUser·p0.50:   3.596 ms/op
                 getUser·p0.90:   4.620 ms/op
                 getUser·p0.95:   5.014 ms/op
                 getUser·p0.99:   5.939 ms/op
                 getUser·p0.999:  9.339 ms/op
                 getUser·p0.9999: 16.798 ms/op
                 getUser·p1.00:   17.072 ms/op

Iteration   3: 3.659 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.069 ms/op
                 getUser·p0.50:   3.584 ms/op
                 getUser·p0.90:   4.465 ms/op
                 getUser·p0.95:   4.760 ms/op
                 getUser·p0.99:   5.931 ms/op
                 getUser·p0.999:  17.577 ms/op
                 getUser·p0.9999: 26.035 ms/op
                 getUser·p1.00:   26.378 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 260244
  mean =      3.686 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7751 
    [ 2.500,  5.000) = 241013 
    [ 5.000,  7.500) = 10435 
    [ 7.500, 10.000) = 746 
    [10.000, 12.500) = 108 
    [12.500, 15.000) = 58 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 60 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.688 ms/op
     p(50.0000) =      3.600 ms/op
     p(90.0000) =      4.563 ms/op
     p(95.0000) =      4.923 ms/op
     p(99.0000) =      6.013 ms/op
     p(99.9000) =     10.871 ms/op
     p(99.9900) =     24.244 ms/op
     p(99.9990) =     26.345 ms/op
     p(99.9999) =     26.378 ms/op
    p(100.0000) =     26.378 ms/op


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
# Warmup Iteration   1: 7.201 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 5.327 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 5.097 ±(99.9%) 0.017 ms/op
Iteration   1: 4.966 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.776 ms/op
                 listUser·p0.50:   4.760 ms/op
                 listUser·p0.90:   6.373 ms/op
                 listUser·p0.95:   7.258 ms/op
                 listUser·p0.99:   9.142 ms/op
                 listUser·p0.999:  16.286 ms/op
                 listUser·p0.9999: 20.376 ms/op
                 listUser·p1.00:   22.217 ms/op

Iteration   2: 5.079 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.274 ms/op
                 listUser·p0.50:   4.882 ms/op
                 listUser·p0.90:   6.332 ms/op
                 listUser·p0.95:   7.193 ms/op
                 listUser·p0.99:   8.897 ms/op
                 listUser·p0.999:  16.513 ms/op
                 listUser·p0.9999: 37.205 ms/op
                 listUser·p1.00:   37.618 ms/op

Iteration   3: 4.967 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   0.930 ms/op
                 listUser·p0.50:   4.735 ms/op
                 listUser·p0.90:   6.349 ms/op
                 listUser·p0.95:   7.193 ms/op
                 listUser·p0.99:   9.224 ms/op
                 listUser·p0.999:  19.961 ms/op
                 listUser·p0.9999: 28.749 ms/op
                 listUser·p1.00:   29.262 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 191866
  mean =      5.003 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 259 
    [ 2.500,  5.000) = 113892 
    [ 5.000,  7.500) = 70242 
    [ 7.500, 10.000) = 6377 
    [10.000, 12.500) = 623 
    [12.500, 15.000) = 180 
    [15.000, 17.500) = 91 
    [17.500, 20.000) = 100 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 22 
    [27.500, 30.000) = 10 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.930 ms/op
     p(50.0000) =      4.792 ms/op
     p(90.0000) =      6.349 ms/op
     p(95.0000) =      7.217 ms/op
     p(99.0000) =      9.093 ms/op
     p(99.9000) =     17.872 ms/op
     p(99.9900) =     36.372 ms/op
     p(99.9990) =     37.618 ms/op
     p(99.9999) =     37.618 ms/op
    p(100.0000) =     37.618 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.331 ± 3.734  ops/ms
ClientGrpc.existUser                       thrpt       3   8.478 ± 1.825  ops/ms
ClientGrpc.getUser                         thrpt       3   8.038 ± 4.426  ops/ms
ClientGrpc.listUser                        thrpt       3   6.400 ± 3.733  ops/ms
ClientGrpc.createUser                       avgt       3   3.876 ± 1.087   ms/op
ClientGrpc.existUser                        avgt       3   3.718 ± 1.896   ms/op
ClientGrpc.getUser                          avgt       3   3.983 ± 1.992   ms/op
ClientGrpc.listUser                         avgt       3   4.969 ± 2.573   ms/op
ClientGrpc.createUser                     sample  259000   3.706 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.993           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.609           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.588           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.948           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.111           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.026           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          29.626           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          31.752           ms/op
ClientGrpc.existUser                      sample  272528   3.523 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.784           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.449           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.366           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.678           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.554           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.608           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          24.101           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.690           ms/op
ClientGrpc.getUser                        sample  260244   3.686 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.688           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.600           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.563           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.923           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.013           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.871           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          24.244           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          26.378           ms/op
ClientGrpc.listUser                       sample  191866   5.003 ± 0.010   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.930           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.792           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.349           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.217           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.093           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.872           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          36.372           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          37.618           ms/op
