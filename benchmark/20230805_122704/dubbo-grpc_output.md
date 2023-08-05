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
# Warmup Iteration   1: 2.419 ops/ms
# Warmup Iteration   2: 6.387 ops/ms
# Warmup Iteration   3: 7.589 ops/ms
Iteration   1: 7.764 ops/ms
Iteration   2: 8.269 ops/ms
Iteration   3: 8.079 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.038 ±(99.9%) 4.654 ops/ms [Average]
  (min, avg, max) = (7.764, 8.038, 8.269), stdev = 0.255
  CI (99.9%): [3.383, 12.692] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 5.969 ops/ms
# Warmup Iteration   2: 7.865 ops/ms
# Warmup Iteration   3: 8.434 ops/ms
Iteration   1: 8.802 ops/ms
Iteration   2: 8.720 ops/ms
Iteration   3: 8.818 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.780 ±(99.9%) 0.960 ops/ms [Average]
  (min, avg, max) = (8.720, 8.780, 8.818), stdev = 0.053
  CI (99.9%): [7.820, 9.740] (assumes normal distribution)


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
# Warmup Iteration   1: 5.250 ops/ms
# Warmup Iteration   2: 7.257 ops/ms
# Warmup Iteration   3: 7.178 ops/ms
Iteration   1: 8.130 ops/ms
Iteration   2: 7.663 ops/ms
Iteration   3: 8.144 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.979 ±(99.9%) 4.998 ops/ms [Average]
  (min, avg, max) = (7.663, 7.979, 8.144), stdev = 0.274
  CI (99.9%): [2.981, 12.976] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 4.356 ops/ms
# Warmup Iteration   2: 5.905 ops/ms
# Warmup Iteration   3: 6.254 ops/ms
Iteration   1: 6.113 ops/ms
Iteration   2: 6.206 ops/ms
Iteration   3: 6.304 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.208 ±(99.9%) 1.737 ops/ms [Average]
  (min, avg, max) = (6.113, 6.208, 6.304), stdev = 0.095
  CI (99.9%): [4.471, 7.944] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.493 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 4.252 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.984 ±(99.9%) 0.003 ms/op
Iteration   1: 3.857 ±(99.9%) 0.002 ms/op
Iteration   2: 4.046 ±(99.9%) 0.003 ms/op
Iteration   3: 3.863 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.922 ±(99.9%) 1.965 ms/op [Average]
  (min, avg, max) = (3.857, 3.922, 4.046), stdev = 0.108
  CI (99.9%): [1.956, 5.887] (assumes normal distribution)


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
# Warmup Iteration   1: 5.303 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.989 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.896 ±(99.9%) 0.003 ms/op
Iteration   1: 3.673 ±(99.9%) 0.002 ms/op
Iteration   2: 3.645 ±(99.9%) 0.003 ms/op
Iteration   3: 3.620 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.646 ±(99.9%) 0.482 ms/op [Average]
  (min, avg, max) = (3.620, 3.646, 3.673), stdev = 0.026
  CI (99.9%): [3.163, 4.128] (assumes normal distribution)


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
# Warmup Iteration   1: 5.747 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.142 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 3.853 ±(99.9%) 0.002 ms/op
Iteration   1: 4.090 ±(99.9%) 0.004 ms/op
Iteration   2: 3.792 ±(99.9%) 0.004 ms/op
Iteration   3: 3.892 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.925 ±(99.9%) 2.771 ms/op [Average]
  (min, avg, max) = (3.792, 3.925, 4.090), stdev = 0.152
  CI (99.9%): [1.154, 6.695] (assumes normal distribution)


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
# Warmup Iteration   1: 7.566 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 5.290 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 5.211 ±(99.9%) 0.011 ms/op
Iteration   1: 5.042 ±(99.9%) 0.016 ms/op
Iteration   2: 5.130 ±(99.9%) 0.017 ms/op
Iteration   3: 4.921 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.031 ±(99.9%) 1.907 ms/op [Average]
  (min, avg, max) = (4.921, 5.031, 5.130), stdev = 0.105
  CI (99.9%): [3.124, 6.938] (assumes normal distribution)


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
# Warmup Iteration   1: 6.423 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 4.286 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.289 ±(99.9%) 0.014 ms/op
Iteration   1: 3.901 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.997 ms/op
                 createUser·p0.50:   3.789 ms/op
                 createUser·p0.90:   4.850 ms/op
                 createUser·p0.95:   5.276 ms/op
                 createUser·p0.99:   6.889 ms/op
                 createUser·p0.999:  13.943 ms/op
                 createUser·p0.9999: 31.883 ms/op
                 createUser·p1.00:   32.276 ms/op

Iteration   2: 3.816 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.813 ms/op
                 createUser·p0.50:   3.740 ms/op
                 createUser·p0.90:   4.710 ms/op
                 createUser·p0.95:   5.104 ms/op
                 createUser·p0.99:   6.259 ms/op
                 createUser·p0.999:  9.173 ms/op
                 createUser·p0.9999: 25.887 ms/op
                 createUser·p1.00:   26.411 ms/op

Iteration   3: 4.055 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.853 ms/op
                 createUser·p0.50:   3.940 ms/op
                 createUser·p0.90:   5.063 ms/op
                 createUser·p0.95:   5.538 ms/op
                 createUser·p0.99:   6.849 ms/op
                 createUser·p0.999:  12.237 ms/op
                 createUser·p0.9999: 33.757 ms/op
                 createUser·p1.00:   34.275 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 244829
  mean =      3.921 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6295 
    [ 2.500,  5.000) = 218486 
    [ 5.000,  7.500) = 18717 
    [ 7.500, 10.000) = 890 
    [10.000, 12.500) = 200 
    [12.500, 15.000) = 81 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 40 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 30 
    [32.500, 35.000) = 24 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.813 ms/op
     p(50.0000) =      3.817 ms/op
     p(90.0000) =      4.882 ms/op
     p(95.0000) =      5.317 ms/op
     p(99.0000) =      6.685 ms/op
     p(99.9000) =     12.425 ms/op
     p(99.9900) =     32.490 ms/op
     p(99.9990) =     34.085 ms/op
     p(99.9999) =     34.275 ms/op
    p(100.0000) =     34.275 ms/op


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
# Warmup Iteration   1: 5.151 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 4.107 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.725 ±(99.9%) 0.009 ms/op
Iteration   1: 3.744 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.815 ms/op
                 existUser·p0.50:   3.613 ms/op
                 existUser·p0.90:   4.735 ms/op
                 existUser·p0.95:   5.112 ms/op
                 existUser·p0.99:   6.116 ms/op
                 existUser·p0.999:  9.379 ms/op
                 existUser·p0.9999: 21.230 ms/op
                 existUser·p1.00:   22.381 ms/op

Iteration   2: 3.646 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.986 ms/op
                 existUser·p0.50:   3.547 ms/op
                 existUser·p0.90:   4.497 ms/op
                 existUser·p0.95:   4.915 ms/op
                 existUser·p0.99:   5.972 ms/op
                 existUser·p0.999:  10.534 ms/op
                 existUser·p0.9999: 23.076 ms/op
                 existUser·p1.00:   23.527 ms/op

Iteration   3: 3.604 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.799 ms/op
                 existUser·p0.50:   3.510 ms/op
                 existUser·p0.90:   4.448 ms/op
                 existUser·p0.95:   4.825 ms/op
                 existUser·p0.99:   5.947 ms/op
                 existUser·p0.999:  10.605 ms/op
                 existUser·p0.9999: 18.096 ms/op
                 existUser·p1.00:   18.645 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 262029
  mean =      3.664 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5870 
    [ 2.500,  5.000) = 243863 
    [ 5.000,  7.500) = 11395 
    [ 7.500, 10.000) = 594 
    [10.000, 12.500) = 172 
    [12.500, 15.000) = 7 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.799 ms/op
     p(50.0000) =      3.551 ms/op
     p(90.0000) =      4.563 ms/op
     p(95.0000) =      4.964 ms/op
     p(99.0000) =      6.021 ms/op
     p(99.9000) =     10.371 ms/op
     p(99.9900) =     21.004 ms/op
     p(99.9990) =     23.429 ms/op
     p(99.9999) =     23.527 ms/op
    p(100.0000) =     23.527 ms/op


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
# Warmup Iteration   1: 5.770 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 4.117 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.003 ±(99.9%) 0.011 ms/op
Iteration   1: 3.907 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.773 ms/op
                 getUser·p0.50:   3.801 ms/op
                 getUser·p0.90:   4.956 ms/op
                 getUser·p0.95:   5.333 ms/op
                 getUser·p0.99:   6.537 ms/op
                 getUser·p0.999:  12.065 ms/op
                 getUser·p0.9999: 23.396 ms/op
                 getUser·p1.00:   23.658 ms/op

Iteration   2: 4.080 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.746 ms/op
                 getUser·p0.50:   3.949 ms/op
                 getUser·p0.90:   5.169 ms/op
                 getUser·p0.95:   5.571 ms/op
                 getUser·p0.99:   6.825 ms/op
                 getUser·p0.999:  11.200 ms/op
                 getUser·p0.9999: 29.764 ms/op
                 getUser·p1.00:   30.212 ms/op

Iteration   3: 3.881 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.024 ms/op
                 getUser·p0.50:   3.756 ms/op
                 getUser·p0.90:   4.825 ms/op
                 getUser·p0.95:   5.300 ms/op
                 getUser·p0.99:   6.693 ms/op
                 getUser·p0.999:  12.831 ms/op
                 getUser·p0.9999: 19.522 ms/op
                 getUser·p1.00:   19.857 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 242678
  mean =      3.954 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6292 
    [ 2.500,  5.000) = 212478 
    [ 5.000,  7.500) = 22409 
    [ 7.500, 10.000) = 902 
    [10.000, 12.500) = 372 
    [12.500, 15.000) = 95 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 6 
    [27.500, 30.000) = 20 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.746 ms/op
     p(50.0000) =      3.830 ms/op
     p(90.0000) =      4.989 ms/op
     p(95.0000) =      5.423 ms/op
     p(99.0000) =      6.693 ms/op
     p(99.9000) =     12.370 ms/op
     p(99.9900) =     27.599 ms/op
     p(99.9990) =     30.119 ms/op
     p(99.9999) =     30.212 ms/op
    p(100.0000) =     30.212 ms/op


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
# Warmup Iteration   1: 8.681 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 5.352 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 5.448 ±(99.9%) 0.022 ms/op
Iteration   1: 5.535 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.794 ms/op
                 listUser·p0.50:   5.235 ms/op
                 listUser·p0.90:   7.381 ms/op
                 listUser·p0.95:   8.405 ms/op
                 listUser·p0.99:   10.682 ms/op
                 listUser·p0.999:  14.408 ms/op
                 listUser·p0.9999: 15.949 ms/op
                 listUser·p1.00:   20.546 ms/op

Iteration   2: 5.072 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.714 ms/op
                 listUser·p0.50:   4.891 ms/op
                 listUser·p0.90:   6.431 ms/op
                 listUser·p0.95:   7.373 ms/op
                 listUser·p0.99:   9.699 ms/op
                 listUser·p0.999:  17.069 ms/op
                 listUser·p0.9999: 21.781 ms/op
                 listUser·p1.00:   22.184 ms/op

Iteration   3: 5.473 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   0.491 ms/op
                 listUser·p0.50:   5.186 ms/op
                 listUser·p0.90:   7.045 ms/op
                 listUser·p0.95:   8.094 ms/op
                 listUser·p0.99:   10.977 ms/op
                 listUser·p0.999:  22.558 ms/op
                 listUser·p0.9999: 30.273 ms/op
                 listUser·p1.00:   31.425 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 179418
  mean =      5.352 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 232 
    [ 2.500,  5.000) = 82173 
    [ 5.000,  7.500) = 84474 
    [ 7.500, 10.000) = 10105 
    [10.000, 12.500) = 1753 
    [12.500, 15.000) = 297 
    [15.000, 17.500) = 202 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 81 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 21 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.491 ms/op
     p(50.0000) =      5.095 ms/op
     p(90.0000) =      6.963 ms/op
     p(95.0000) =      7.971 ms/op
     p(99.0000) =     10.551 ms/op
     p(99.9000) =     17.615 ms/op
     p(99.9900) =     25.598 ms/op
     p(99.9990) =     31.320 ms/op
     p(99.9999) =     31.425 ms/op
    p(100.0000) =     31.425 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.038 ± 4.654  ops/ms
ClientGrpc.existUser                       thrpt       3   8.780 ± 0.960  ops/ms
ClientGrpc.getUser                         thrpt       3   7.979 ± 4.998  ops/ms
ClientGrpc.listUser                        thrpt       3   6.208 ± 1.737  ops/ms
ClientGrpc.createUser                       avgt       3   3.922 ± 1.965   ms/op
ClientGrpc.existUser                        avgt       3   3.646 ± 0.482   ms/op
ClientGrpc.getUser                          avgt       3   3.925 ± 2.771   ms/op
ClientGrpc.listUser                         avgt       3   5.031 ± 1.907   ms/op
ClientGrpc.createUser                     sample  244829   3.921 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.813           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.817           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.882           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.317           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.685           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.425           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          32.490           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          34.275           ms/op
ClientGrpc.existUser                      sample  262029   3.664 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.799           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.551           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.563           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.964           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.021           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.371           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.004           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.527           ms/op
ClientGrpc.getUser                        sample  242678   3.954 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.746           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.830           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.989           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.423           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.693           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.370           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          27.599           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          30.212           ms/op
ClientGrpc.listUser                       sample  179418   5.352 ± 0.012   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.491           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.095           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.963           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.971           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.551           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.615           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.598           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          31.425           ms/op
