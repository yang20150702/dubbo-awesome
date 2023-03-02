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
# Warmup Iteration   1: 1.869 ops/ms
# Warmup Iteration   2: 4.654 ops/ms
# Warmup Iteration   3: 6.356 ops/ms
Iteration   1: 6.501 ops/ms
Iteration   2: 6.450 ops/ms
Iteration   3: 6.579 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  6.510 ±(99.9%) 1.187 ops/ms [Average]
  (min, avg, max) = (6.450, 6.510, 6.579), stdev = 0.065
  CI (99.9%): [5.323, 7.696] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.792 ops/ms
# Warmup Iteration   2: 5.952 ops/ms
# Warmup Iteration   3: 6.484 ops/ms
Iteration   1: 6.931 ops/ms
Iteration   2: 7.082 ops/ms
Iteration   3: 7.099 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.037 ±(99.9%) 1.688 ops/ms [Average]
  (min, avg, max) = (6.931, 7.037, 7.099), stdev = 0.093
  CI (99.9%): [5.349, 8.726] (assumes normal distribution)


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
# Warmup Iteration   1: 3.877 ops/ms
# Warmup Iteration   2: 6.041 ops/ms
# Warmup Iteration   3: 6.371 ops/ms
Iteration   1: 6.901 ops/ms
Iteration   2: 6.621 ops/ms
Iteration   3: 6.836 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  6.786 ±(99.9%) 2.679 ops/ms [Average]
  (min, avg, max) = (6.621, 6.786, 6.901), stdev = 0.147
  CI (99.9%): [4.107, 9.465] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.417 ops/ms
# Warmup Iteration   2: 4.754 ops/ms
# Warmup Iteration   3: 5.222 ops/ms
Iteration   1: 5.183 ops/ms
Iteration   2: 5.385 ops/ms
Iteration   3: 5.347 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.305 ±(99.9%) 1.958 ops/ms [Average]
  (min, avg, max) = (5.183, 5.305, 5.385), stdev = 0.107
  CI (99.9%): [3.347, 7.263] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 7.345 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 5.106 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.066 ±(99.9%) 0.006 ms/op
Iteration   1: 4.813 ±(99.9%) 0.005 ms/op
Iteration   2: 4.733 ±(99.9%) 0.004 ms/op
Iteration   3: 4.855 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.800 ±(99.9%) 1.129 ms/op [Average]
  (min, avg, max) = (4.733, 4.800, 4.855), stdev = 0.062
  CI (99.9%): [3.671, 5.929] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 7.294 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.899 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.667 ±(99.9%) 0.007 ms/op
Iteration   1: 4.655 ±(99.9%) 0.004 ms/op
Iteration   2: 4.666 ±(99.9%) 0.004 ms/op
Iteration   3: 4.717 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.679 ±(99.9%) 0.605 ms/op [Average]
  (min, avg, max) = (4.655, 4.679, 4.717), stdev = 0.033
  CI (99.9%): [4.075, 5.284] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 7.564 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 5.382 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.003 ±(99.9%) 0.006 ms/op
Iteration   1: 4.895 ±(99.9%) 0.006 ms/op
Iteration   2: 4.931 ±(99.9%) 0.004 ms/op
Iteration   3: 4.784 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.870 ±(99.9%) 1.394 ms/op [Average]
  (min, avg, max) = (4.784, 4.870, 4.931), stdev = 0.076
  CI (99.9%): [3.476, 6.264] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 9.220 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 6.600 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 6.270 ±(99.9%) 0.039 ms/op
Iteration   1: 6.110 ±(99.9%) 0.013 ms/op
Iteration   2: 6.064 ±(99.9%) 0.022 ms/op
Iteration   3: 5.983 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.052 ±(99.9%) 1.171 ms/op [Average]
  (min, avg, max) = (5.983, 6.052, 6.110), stdev = 0.064
  CI (99.9%): [4.881, 7.224] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 7.330 ±(99.9%) 0.100 ms/op
# Warmup Iteration   2: 5.298 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 5.051 ±(99.9%) 0.019 ms/op
Iteration   1: 4.850 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   1.243 ms/op
                 createUser·p0.50:   4.628 ms/op
                 createUser·p0.90:   6.300 ms/op
                 createUser·p0.95:   7.053 ms/op
                 createUser·p0.99:   9.585 ms/op
                 createUser·p0.999:  15.139 ms/op
                 createUser·p0.9999: 26.444 ms/op
                 createUser·p1.00:   26.477 ms/op

Iteration   2: 4.976 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   1.286 ms/op
                 createUser·p0.50:   4.760 ms/op
                 createUser·p0.90:   6.562 ms/op
                 createUser·p0.95:   7.447 ms/op
                 createUser·p0.99:   10.158 ms/op
                 createUser·p0.999:  20.709 ms/op
                 createUser·p0.9999: 37.814 ms/op
                 createUser·p1.00:   38.207 ms/op

Iteration   3: 4.829 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   1.096 ms/op
                 createUser·p0.50:   4.604 ms/op
                 createUser·p0.90:   6.390 ms/op
                 createUser·p0.95:   7.152 ms/op
                 createUser·p0.99:   9.583 ms/op
                 createUser·p0.999:  14.582 ms/op
                 createUser·p0.9999: 24.752 ms/op
                 createUser·p1.00:   28.508 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 196385
  mean =      4.884 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2674 
    [ 2.500,  5.000) = 118112 
    [ 5.000,  7.500) = 67563 
    [ 7.500, 10.000) = 6345 
    [10.000, 12.500) = 1106 
    [12.500, 15.000) = 357 
    [15.000, 17.500) = 82 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 54 
    [25.000, 27.500) = 38 
    [27.500, 30.000) = 2 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      1.096 ms/op
     p(50.0000) =      4.661 ms/op
     p(90.0000) =      6.423 ms/op
     p(95.0000) =      7.217 ms/op
     p(99.0000) =      9.748 ms/op
     p(99.9000) =     15.683 ms/op
     p(99.9900) =     36.729 ms/op
     p(99.9990) =     38.144 ms/op
     p(99.9999) =     38.207 ms/op
    p(100.0000) =     38.207 ms/op


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
# Warmup Iteration   1: 7.495 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 5.199 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.568 ±(99.9%) 0.017 ms/op
Iteration   1: 4.687 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   1.118 ms/op
                 existUser·p0.50:   4.334 ms/op
                 existUser·p0.90:   6.259 ms/op
                 existUser·p0.95:   7.299 ms/op
                 existUser·p0.99:   10.420 ms/op
                 existUser·p0.999:  17.367 ms/op
                 existUser·p0.9999: 25.729 ms/op
                 existUser·p1.00:   26.345 ms/op

Iteration   2: 4.658 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   1.245 ms/op
                 existUser·p0.50:   4.465 ms/op
                 existUser·p0.90:   6.021 ms/op
                 existUser·p0.95:   6.734 ms/op
                 existUser·p0.99:   9.044 ms/op
                 existUser·p0.999:  13.479 ms/op
                 existUser·p0.9999: 20.353 ms/op
                 existUser·p1.00:   20.644 ms/op

Iteration   3: 4.650 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   0.781 ms/op
                 existUser·p0.50:   4.399 ms/op
                 existUser·p0.90:   6.267 ms/op
                 existUser·p0.95:   7.242 ms/op
                 existUser·p0.99:   10.125 ms/op
                 existUser·p0.999:  15.307 ms/op
                 existUser·p0.9999: 31.404 ms/op
                 existUser·p1.00:   32.047 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 205636
  mean =      4.665 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4267 
    [ 2.500,  5.000) = 139591 
    [ 5.000,  7.500) = 53750 
    [ 7.500, 10.000) = 6169 
    [10.000, 12.500) = 1197 
    [12.500, 15.000) = 370 
    [15.000, 17.500) = 165 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 14 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 16 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.781 ms/op
     p(50.0000) =      4.399 ms/op
     p(90.0000) =      6.169 ms/op
     p(95.0000) =      7.094 ms/op
     p(99.0000) =      9.830 ms/op
     p(99.9000) =     15.997 ms/op
     p(99.9900) =     25.864 ms/op
     p(99.9990) =     31.996 ms/op
     p(99.9999) =     32.047 ms/op
    p(100.0000) =     32.047 ms/op


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
# Warmup Iteration   1: 7.719 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 5.610 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 5.008 ±(99.9%) 0.020 ms/op
Iteration   1: 5.003 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   1.219 ms/op
                 getUser·p0.50:   4.751 ms/op
                 getUser·p0.90:   6.717 ms/op
                 getUser·p0.95:   7.684 ms/op
                 getUser·p0.99:   10.207 ms/op
                 getUser·p0.999:  15.452 ms/op
                 getUser·p0.9999: 17.996 ms/op
                 getUser·p1.00:   18.416 ms/op

Iteration   2: 4.913 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   0.563 ms/op
                 getUser·p0.50:   4.669 ms/op
                 getUser·p0.90:   6.521 ms/op
                 getUser·p0.95:   7.291 ms/op
                 getUser·p0.99:   9.716 ms/op
                 getUser·p0.999:  21.561 ms/op
                 getUser·p0.9999: 26.361 ms/op
                 getUser·p1.00:   26.903 ms/op

Iteration   3: 4.982 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   1.317 ms/op
                 getUser·p0.50:   4.817 ms/op
                 getUser·p0.90:   6.488 ms/op
                 getUser·p0.95:   7.184 ms/op
                 getUser·p0.99:   9.393 ms/op
                 getUser·p0.999:  13.381 ms/op
                 getUser·p0.9999: 34.594 ms/op
                 getUser·p1.00:   35.258 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 193330
  mean =      4.966 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2768 
    [ 2.500,  5.000) = 109807 
    [ 5.000,  7.500) = 72006 
    [ 7.500, 10.000) = 7022 
    [10.000, 12.500) = 1256 
    [12.500, 15.000) = 240 
    [15.000, 17.500) = 100 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 23 
    [27.500, 30.000) = 6 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 14 
    [35.000, 37.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.563 ms/op
     p(50.0000) =      4.743 ms/op
     p(90.0000) =      6.570 ms/op
     p(95.0000) =      7.365 ms/op
     p(99.0000) =      9.830 ms/op
     p(99.9000) =     15.756 ms/op
     p(99.9900) =     31.272 ms/op
     p(99.9990) =     35.197 ms/op
     p(99.9999) =     35.258 ms/op
    p(100.0000) =     35.258 ms/op


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
# Warmup Iteration   1: 9.969 ±(99.9%) 0.135 ms/op
# Warmup Iteration   2: 6.436 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 6.247 ±(99.9%) 0.029 ms/op
Iteration   1: 6.311 ±(99.9%) 0.031 ms/op
                 listUser·p0.00:   1.225 ms/op
                 listUser·p0.50:   5.792 ms/op
                 listUser·p0.90:   8.913 ms/op
                 listUser·p0.95:   10.224 ms/op
                 listUser·p0.99:   13.402 ms/op
                 listUser·p0.999:  23.167 ms/op
                 listUser·p0.9999: 29.622 ms/op
                 listUser·p1.00:   30.179 ms/op

Iteration   2: 6.206 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   1.974 ms/op
                 listUser·p0.50:   5.751 ms/op
                 listUser·p0.90:   8.667 ms/op
                 listUser·p0.95:   9.748 ms/op
                 listUser·p0.99:   12.567 ms/op
                 listUser·p0.999:  18.721 ms/op
                 listUser·p0.9999: 25.521 ms/op
                 listUser·p1.00:   26.739 ms/op

Iteration   3: 6.283 ±(99.9%) 0.031 ms/op
                 listUser·p0.00:   1.405 ms/op
                 listUser·p0.50:   5.775 ms/op
                 listUser·p0.90:   8.782 ms/op
                 listUser·p0.95:   9.912 ms/op
                 listUser·p0.99:   13.156 ms/op
                 listUser·p0.999:  25.100 ms/op
                 listUser·p0.9999: 31.127 ms/op
                 listUser·p1.00:   31.621 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 153253
  mean =      6.266 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 146 
    [ 2.500,  5.000) = 39408 
    [ 5.000,  7.500) = 82264 
    [ 7.500, 10.000) = 23951 
    [10.000, 12.500) = 5477 
    [12.500, 15.000) = 1227 
    [15.000, 17.500) = 379 
    [17.500, 20.000) = 151 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 89 
    [25.000, 27.500) = 42 
    [27.500, 30.000) = 40 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.225 ms/op
     p(50.0000) =      5.775 ms/op
     p(90.0000) =      8.782 ms/op
     p(95.0000) =      9.961 ms/op
     p(99.0000) =     13.066 ms/op
     p(99.9000) =     23.183 ms/op
     p(99.9900) =     30.115 ms/op
     p(99.9990) =     31.604 ms/op
     p(99.9999) =     31.621 ms/op
    p(100.0000) =     31.621 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   6.510 ± 1.187  ops/ms
ClientGrpc.existUser                       thrpt       3   7.037 ± 1.688  ops/ms
ClientGrpc.getUser                         thrpt       3   6.786 ± 2.679  ops/ms
ClientGrpc.listUser                        thrpt       3   5.305 ± 1.958  ops/ms
ClientGrpc.createUser                       avgt       3   4.800 ± 1.129   ms/op
ClientGrpc.existUser                        avgt       3   4.679 ± 0.605   ms/op
ClientGrpc.getUser                          avgt       3   4.870 ± 1.394   ms/op
ClientGrpc.listUser                         avgt       3   6.052 ± 1.171   ms/op
ClientGrpc.createUser                     sample  196385   4.884 ± 0.011   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.096           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.661           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           6.423           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           7.217           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           9.748           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          15.683           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          36.729           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          38.207           ms/op
ClientGrpc.existUser                      sample  205636   4.665 ± 0.011   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.781           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.399           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           6.169           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           7.094           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           9.830           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          15.997           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          25.864           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          32.047           ms/op
ClientGrpc.getUser                        sample  193330   4.966 ± 0.011   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.563           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.743           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           6.570           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           7.365           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           9.830           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          15.756           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          31.272           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          35.258           ms/op
ClientGrpc.listUser                       sample  153253   6.266 ± 0.017   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.225           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.775           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           8.782           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           9.961           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          13.066           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          23.183           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          30.115           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          31.621           ms/op
