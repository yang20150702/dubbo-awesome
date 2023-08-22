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
# Warmup Iteration   1: 2.988 ops/ms
# Warmup Iteration   2: 6.752 ops/ms
# Warmup Iteration   3: 8.321 ops/ms
Iteration   1: 8.352 ops/ms
Iteration   2: 8.476 ops/ms
Iteration   3: 8.736 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.521 ±(99.9%) 3.580 ops/ms [Average]
  (min, avg, max) = (8.352, 8.521, 8.736), stdev = 0.196
  CI (99.9%): [4.942, 12.101] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.932 ops/ms
# Warmup Iteration   2: 8.352 ops/ms
# Warmup Iteration   3: 8.860 ops/ms
Iteration   1: 8.897 ops/ms
Iteration   2: 9.037 ops/ms
Iteration   3: 9.042 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.992 ±(99.9%) 1.495 ops/ms [Average]
  (min, avg, max) = (8.897, 8.992, 9.042), stdev = 0.082
  CI (99.9%): [7.497, 10.487] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.267 ops/ms
# Warmup Iteration   2: 7.976 ops/ms
# Warmup Iteration   3: 8.457 ops/ms
Iteration   1: 8.699 ops/ms
Iteration   2: 8.864 ops/ms
Iteration   3: 8.554 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.706 ±(99.9%) 2.834 ops/ms [Average]
  (min, avg, max) = (8.554, 8.706, 8.864), stdev = 0.155
  CI (99.9%): [5.872, 11.539] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 4.145 ops/ms
# Warmup Iteration   2: 6.093 ops/ms
# Warmup Iteration   3: 6.373 ops/ms
Iteration   1: 6.445 ops/ms
Iteration   2: 6.419 ops/ms
Iteration   3: 6.398 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.420 ±(99.9%) 0.431 ops/ms [Average]
  (min, avg, max) = (6.398, 6.420, 6.445), stdev = 0.024
  CI (99.9%): [5.989, 6.851] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 5.535 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.980 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.980 ±(99.9%) 0.037 ms/op
Iteration   1: 3.966 ±(99.9%) 0.004 ms/op
Iteration   2: 3.811 ±(99.9%) 0.004 ms/op
Iteration   3: 3.711 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.830 ±(99.9%) 2.348 ms/op [Average]
  (min, avg, max) = (3.711, 3.830, 3.966), stdev = 0.129
  CI (99.9%): [1.481, 6.178] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 5.356 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.798 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.710 ±(99.9%) 0.006 ms/op
Iteration   1: 3.571 ±(99.9%) 0.004 ms/op
Iteration   2: 3.506 ±(99.9%) 0.004 ms/op
Iteration   3: 3.520 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.532 ±(99.9%) 0.628 ms/op [Average]
  (min, avg, max) = (3.506, 3.532, 3.571), stdev = 0.034
  CI (99.9%): [2.904, 4.161] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.083 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.313 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.014 ±(99.9%) 0.004 ms/op
Iteration   1: 3.716 ±(99.9%) 0.004 ms/op
Iteration   2: 3.868 ±(99.9%) 0.005 ms/op
Iteration   3: 3.910 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.831 ±(99.9%) 1.864 ms/op [Average]
  (min, avg, max) = (3.716, 3.831, 3.910), stdev = 0.102
  CI (99.9%): [1.967, 5.695] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 6.503 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 5.252 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.942 ±(99.9%) 0.013 ms/op
Iteration   1: 4.946 ±(99.9%) 0.010 ms/op
Iteration   2: 4.862 ±(99.9%) 0.011 ms/op
Iteration   3: 4.973 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.927 ±(99.9%) 1.062 ms/op [Average]
  (min, avg, max) = (4.862, 4.927, 4.973), stdev = 0.058
  CI (99.9%): [3.865, 5.989] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.195 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.944 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.771 ±(99.9%) 0.011 ms/op
Iteration   1: 3.802 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.978 ms/op
                 createUser·p0.50:   3.678 ms/op
                 createUser·p0.90:   4.637 ms/op
                 createUser·p0.95:   5.112 ms/op
                 createUser·p0.99:   7.324 ms/op
                 createUser·p0.999:  11.663 ms/op
                 createUser·p0.9999: 15.909 ms/op
                 createUser·p1.00:   16.417 ms/op

Iteration   2: 3.770 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.694 ms/op
                 createUser·p0.50:   3.629 ms/op
                 createUser·p0.90:   4.604 ms/op
                 createUser·p0.95:   5.161 ms/op
                 createUser·p0.99:   7.758 ms/op
                 createUser·p0.999:  13.076 ms/op
                 createUser·p0.9999: 32.867 ms/op
                 createUser·p1.00:   33.128 ms/op

Iteration   3: 3.767 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.038 ms/op
                 createUser·p0.50:   3.662 ms/op
                 createUser·p0.90:   4.547 ms/op
                 createUser·p0.95:   4.997 ms/op
                 createUser·p0.99:   7.209 ms/op
                 createUser·p0.999:  13.699 ms/op
                 createUser·p0.9999: 25.167 ms/op
                 createUser·p1.00:   25.854 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 253911
  mean =      3.780 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9109 
    [ 2.500,  5.000) = 230810 
    [ 5.000,  7.500) = 11564 
    [ 7.500, 10.000) = 1719 
    [10.000, 12.500) = 443 
    [12.500, 15.000) = 148 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 11 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 12 
    [32.500, 35.000) = 20 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.694 ms/op
     p(50.0000) =      3.658 ms/op
     p(90.0000) =      4.604 ms/op
     p(95.0000) =      5.087 ms/op
     p(99.0000) =      7.414 ms/op
     p(99.9000) =     12.650 ms/op
     p(99.9900) =     32.047 ms/op
     p(99.9990) =     33.078 ms/op
     p(99.9999) =     33.128 ms/op
    p(100.0000) =     33.128 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 5.125 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 3.892 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.654 ±(99.9%) 0.011 ms/op
Iteration   1: 3.635 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.740 ms/op
                 existUser·p0.50:   3.531 ms/op
                 existUser·p0.90:   4.432 ms/op
                 existUser·p0.95:   4.964 ms/op
                 existUser·p0.99:   7.086 ms/op
                 existUser·p0.999:  9.765 ms/op
                 existUser·p0.9999: 14.949 ms/op
                 existUser·p1.00:   15.188 ms/op

Iteration   2: 3.590 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.891 ms/op
                 existUser·p0.50:   3.506 ms/op
                 existUser·p0.90:   4.407 ms/op
                 existUser·p0.95:   4.841 ms/op
                 existUser·p0.99:   7.053 ms/op
                 existUser·p0.999:  12.837 ms/op
                 existUser·p0.9999: 18.058 ms/op
                 existUser·p1.00:   22.446 ms/op

Iteration   3: 3.600 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.844 ms/op
                 existUser·p0.50:   3.490 ms/op
                 existUser·p0.90:   4.309 ms/op
                 existUser·p0.95:   4.751 ms/op
                 existUser·p0.99:   6.906 ms/op
                 existUser·p0.999:  11.752 ms/op
                 existUser·p0.9999: 21.729 ms/op
                 existUser·p1.00:   22.020 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 266022
  mean =      3.608 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12322 
    [ 2.500,  5.000) = 242243 
    [ 5.000,  7.500) = 9575 
    [ 7.500, 10.000) = 1424 
    [10.000, 12.500) = 224 
    [12.500, 15.000) = 143 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.740 ms/op
     p(50.0000) =      3.510 ms/op
     p(90.0000) =      4.383 ms/op
     p(95.0000) =      4.850 ms/op
     p(99.0000) =      7.029 ms/op
     p(99.9000) =     12.124 ms/op
     p(99.9900) =     20.965 ms/op
     p(99.9990) =     22.020 ms/op
     p(99.9999) =     22.446 ms/op
    p(100.0000) =     22.446 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.219 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 3.871 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.846 ±(99.9%) 0.011 ms/op
Iteration   1: 3.792 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.031 ms/op
                 getUser·p0.50:   3.670 ms/op
                 getUser·p0.90:   4.588 ms/op
                 getUser·p0.95:   5.145 ms/op
                 getUser·p0.99:   7.651 ms/op
                 getUser·p0.999:  11.399 ms/op
                 getUser·p0.9999: 15.126 ms/op
                 getUser·p1.00:   15.761 ms/op

Iteration   2: 3.912 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.428 ms/op
                 getUser·p0.50:   3.785 ms/op
                 getUser·p0.90:   4.768 ms/op
                 getUser·p0.95:   5.251 ms/op
                 getUser·p0.99:   7.717 ms/op
                 getUser·p0.999:  11.637 ms/op
                 getUser·p0.9999: 18.443 ms/op
                 getUser·p1.00:   19.366 ms/op

Iteration   3: 3.801 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.944 ms/op
                 getUser·p0.50:   3.674 ms/op
                 getUser·p0.90:   4.637 ms/op
                 getUser·p0.95:   5.218 ms/op
                 getUser·p0.99:   7.512 ms/op
                 getUser·p0.999:  15.151 ms/op
                 getUser·p0.9999: 20.349 ms/op
                 getUser·p1.00:   20.414 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 250279
  mean =      3.834 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8146 
    [ 2.500,  5.000) = 226262 
    [ 5.000,  7.500) = 13201 
    [ 7.500, 10.000) = 2033 
    [10.000, 12.500) = 390 
    [12.500, 15.000) = 83 
    [15.000, 17.500) = 100 
    [17.500, 20.000) = 51 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.428 ms/op
     p(50.0000) =      3.707 ms/op
     p(90.0000) =      4.669 ms/op
     p(95.0000) =      5.202 ms/op
     p(99.0000) =      7.610 ms/op
     p(99.9000) =     12.419 ms/op
     p(99.9900) =     18.447 ms/op
     p(99.9990) =     20.414 ms/op
     p(99.9999) =     20.414 ms/op
    p(100.0000) =     20.414 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 6.899 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 5.486 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 5.166 ±(99.9%) 0.021 ms/op
Iteration   1: 5.241 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.176 ms/op
                 listUser·p0.50:   4.809 ms/op
                 listUser·p0.90:   7.291 ms/op
                 listUser·p0.95:   8.135 ms/op
                 listUser·p0.99:   10.486 ms/op
                 listUser·p0.999:  24.347 ms/op
                 listUser·p0.9999: 29.747 ms/op
                 listUser·p1.00:   30.147 ms/op

Iteration   2: 5.162 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.421 ms/op
                 listUser·p0.50:   4.743 ms/op
                 listUser·p0.90:   7.143 ms/op
                 listUser·p0.95:   8.233 ms/op
                 listUser·p0.99:   11.223 ms/op
                 listUser·p0.999:  25.631 ms/op
                 listUser·p0.9999: 30.553 ms/op
                 listUser·p1.00:   30.933 ms/op

Iteration   3: 5.055 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.325 ms/op
                 listUser·p0.50:   4.735 ms/op
                 listUser·p0.90:   6.734 ms/op
                 listUser·p0.95:   7.799 ms/op
                 listUser·p0.99:   10.011 ms/op
                 listUser·p0.999:  26.665 ms/op
                 listUser·p0.9999: 34.757 ms/op
                 listUser·p1.00:   35.127 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 186210
  mean =      5.152 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 675 
    [ 2.500,  5.000) = 112179 
    [ 5.000,  7.500) = 59273 
    [ 7.500, 10.000) = 11496 
    [10.000, 12.500) = 1867 
    [12.500, 15.000) = 333 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 70 
    [25.000, 27.500) = 63 
    [27.500, 30.000) = 48 
    [30.000, 32.500) = 29 
    [32.500, 35.000) = 30 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.176 ms/op
     p(50.0000) =      4.760 ms/op
     p(90.0000) =      7.078 ms/op
     p(95.0000) =      8.045 ms/op
     p(99.0000) =     10.631 ms/op
     p(99.9000) =     24.510 ms/op
     p(99.9900) =     33.543 ms/op
     p(99.9990) =     35.071 ms/op
     p(99.9999) =     35.127 ms/op
    p(100.0000) =     35.127 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.521 ± 3.580  ops/ms
ClientGrpc.existUser                       thrpt       3   8.992 ± 1.495  ops/ms
ClientGrpc.getUser                         thrpt       3   8.706 ± 2.834  ops/ms
ClientGrpc.listUser                        thrpt       3   6.420 ± 0.431  ops/ms
ClientGrpc.createUser                       avgt       3   3.830 ± 2.348   ms/op
ClientGrpc.existUser                        avgt       3   3.532 ± 0.628   ms/op
ClientGrpc.getUser                          avgt       3   3.831 ± 1.864   ms/op
ClientGrpc.listUser                         avgt       3   4.927 ± 1.062   ms/op
ClientGrpc.createUser                     sample  253911   3.780 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.694           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.658           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.604           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.087           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.414           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.650           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          32.047           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          33.128           ms/op
ClientGrpc.existUser                      sample  266022   3.608 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.740           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.510           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.383           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.850           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.029           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.124           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.965           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.446           ms/op
ClientGrpc.getUser                        sample  250279   3.834 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.428           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.707           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.669           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.202           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.610           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.419           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.447           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.414           ms/op
ClientGrpc.listUser                       sample  186210   5.152 ± 0.013   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.176           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.760           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.078           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.045           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.631           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          24.510           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          33.543           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          35.127           ms/op
