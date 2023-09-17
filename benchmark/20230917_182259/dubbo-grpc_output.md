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
# Warmup Iteration   1: 2.261 ops/ms
# Warmup Iteration   2: 5.889 ops/ms
# Warmup Iteration   3: 7.735 ops/ms
Iteration   1: 8.295 ops/ms
Iteration   2: 8.380 ops/ms
Iteration   3: 8.299 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.325 ±(99.9%) 0.876 ops/ms [Average]
  (min, avg, max) = (8.295, 8.325, 8.380), stdev = 0.048
  CI (99.9%): [7.448, 9.201] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 5.117 ops/ms
# Warmup Iteration   2: 8.079 ops/ms
# Warmup Iteration   3: 8.629 ops/ms
Iteration   1: 9.019 ops/ms
Iteration   2: 8.784 ops/ms
Iteration   3: 8.810 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.871 ±(99.9%) 2.355 ops/ms [Average]
  (min, avg, max) = (8.784, 8.871, 9.019), stdev = 0.129
  CI (99.9%): [6.516, 11.226] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 4.836 ops/ms
# Warmup Iteration   2: 7.947 ops/ms
# Warmup Iteration   3: 8.077 ops/ms
Iteration   1: 8.354 ops/ms
Iteration   2: 8.374 ops/ms
Iteration   3: 8.261 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.330 ±(99.9%) 1.103 ops/ms [Average]
  (min, avg, max) = (8.261, 8.330, 8.374), stdev = 0.060
  CI (99.9%): [7.227, 9.432] (assumes normal distribution)


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
# Warmup Iteration   1: 4.506 ops/ms
# Warmup Iteration   2: 5.818 ops/ms
# Warmup Iteration   3: 6.173 ops/ms
Iteration   1: 6.399 ops/ms
Iteration   2: 6.438 ops/ms
Iteration   3: 6.095 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.311 ±(99.9%) 3.423 ops/ms [Average]
  (min, avg, max) = (6.095, 6.311, 6.438), stdev = 0.188
  CI (99.9%): [2.888, 9.733] (assumes normal distribution)


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
# Warmup Iteration   1: 5.825 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.007 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.910 ±(99.9%) 0.003 ms/op
Iteration   1: 3.940 ±(99.9%) 0.002 ms/op
Iteration   2: 3.866 ±(99.9%) 0.002 ms/op
Iteration   3: 3.969 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.925 ±(99.9%) 0.966 ms/op [Average]
  (min, avg, max) = (3.866, 3.925, 3.969), stdev = 0.053
  CI (99.9%): [2.959, 4.891] (assumes normal distribution)


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
# Warmup Iteration   1: 5.378 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.890 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.812 ±(99.9%) 0.003 ms/op
Iteration   1: 3.743 ±(99.9%) 0.002 ms/op
Iteration   2: 3.826 ±(99.9%) 0.003 ms/op
Iteration   3: 3.495 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.688 ±(99.9%) 3.144 ms/op [Average]
  (min, avg, max) = (3.495, 3.688, 3.826), stdev = 0.172
  CI (99.9%): [0.544, 6.832] (assumes normal distribution)


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
# Warmup Iteration   1: 6.077 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.139 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.969 ±(99.9%) 0.003 ms/op
Iteration   1: 3.930 ±(99.9%) 0.004 ms/op
Iteration   2: 3.940 ±(99.9%) 0.004 ms/op
Iteration   3: 3.977 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.949 ±(99.9%) 0.451 ms/op [Average]
  (min, avg, max) = (3.930, 3.949, 3.977), stdev = 0.025
  CI (99.9%): [3.499, 4.400] (assumes normal distribution)


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
# Warmup Iteration   1: 7.789 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 5.324 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 4.986 ±(99.9%) 0.011 ms/op
Iteration   1: 5.135 ±(99.9%) 0.018 ms/op
Iteration   2: 5.181 ±(99.9%) 0.011 ms/op
Iteration   3: 5.006 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.108 ±(99.9%) 1.656 ms/op [Average]
  (min, avg, max) = (5.006, 5.108, 5.181), stdev = 0.091
  CI (99.9%): [3.451, 6.764] (assumes normal distribution)


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
# Warmup Iteration   1: 5.754 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 4.236 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.048 ±(99.9%) 0.014 ms/op
Iteration   1: 3.912 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.153 ms/op
                 createUser·p0.50:   3.793 ms/op
                 createUser·p0.90:   5.030 ms/op
                 createUser·p0.95:   5.505 ms/op
                 createUser·p0.99:   7.047 ms/op
                 createUser·p0.999:  12.337 ms/op
                 createUser·p0.9999: 15.516 ms/op
                 createUser·p1.00:   16.040 ms/op

Iteration   2: 4.063 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.233 ms/op
                 createUser·p0.50:   3.883 ms/op
                 createUser·p0.90:   5.218 ms/op
                 createUser·p0.95:   5.743 ms/op
                 createUser·p0.99:   7.545 ms/op
                 createUser·p0.999:  13.251 ms/op
                 createUser·p0.9999: 25.002 ms/op
                 createUser·p1.00:   25.756 ms/op

Iteration   3: 3.983 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.092 ms/op
                 createUser·p0.50:   3.826 ms/op
                 createUser·p0.90:   5.046 ms/op
                 createUser·p0.95:   5.538 ms/op
                 createUser·p0.99:   7.397 ms/op
                 createUser·p0.999:  12.788 ms/op
                 createUser·p0.9999: 19.726 ms/op
                 createUser·p1.00:   20.251 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 240627
  mean =      3.985 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4140 
    [ 2.500,  5.000) = 208965 
    [ 5.000,  7.500) = 25402 
    [ 7.500, 10.000) = 1645 
    [10.000, 12.500) = 219 
    [12.500, 15.000) = 138 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      1.092 ms/op
     p(50.0000) =      3.834 ms/op
     p(90.0000) =      5.095 ms/op
     p(95.0000) =      5.603 ms/op
     p(99.0000) =      7.313 ms/op
     p(99.9000) =     12.655 ms/op
     p(99.9900) =     23.427 ms/op
     p(99.9990) =     25.309 ms/op
     p(99.9999) =     25.756 ms/op
    p(100.0000) =     25.756 ms/op


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
# Warmup Iteration   1: 5.720 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 4.872 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.434 ±(99.9%) 0.016 ms/op
Iteration   1: 4.361 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.108 ms/op
                 existUser·p0.50:   4.219 ms/op
                 existUser·p0.90:   5.439 ms/op
                 existUser·p0.95:   5.947 ms/op
                 existUser·p0.99:   7.848 ms/op
                 existUser·p0.999:  10.675 ms/op
                 existUser·p0.9999: 18.098 ms/op
                 existUser·p1.00:   18.743 ms/op

Iteration   2: 4.004 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.840 ms/op
                 existUser·p0.50:   3.846 ms/op
                 existUser·p0.90:   5.038 ms/op
                 existUser·p0.95:   5.489 ms/op
                 existUser·p0.99:   7.545 ms/op
                 existUser·p0.999:  11.061 ms/op
                 existUser·p0.9999: 16.204 ms/op
                 existUser·p1.00:   17.170 ms/op

Iteration   3: 3.883 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.065 ms/op
                 existUser·p0.50:   3.715 ms/op
                 existUser·p0.90:   4.907 ms/op
                 existUser·p0.95:   5.415 ms/op
                 existUser·p0.99:   7.455 ms/op
                 existUser·p0.999:  11.152 ms/op
                 existUser·p0.9999: 25.143 ms/op
                 existUser·p1.00:   27.623 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 235693
  mean =      4.073 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3192 
    [ 2.500,  5.000) = 202981 
    [ 5.000,  7.500) = 26948 
    [ 7.500, 10.000) = 2027 
    [10.000, 12.500) = 438 
    [12.500, 15.000) = 13 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.840 ms/op
     p(50.0000) =      3.908 ms/op
     p(90.0000) =      5.153 ms/op
     p(95.0000) =      5.644 ms/op
     p(99.0000) =      7.635 ms/op
     p(99.9000) =     11.026 ms/op
     p(99.9900) =     24.047 ms/op
     p(99.9990) =     26.891 ms/op
     p(99.9999) =     27.623 ms/op
    p(100.0000) =     27.623 ms/op


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
# Warmup Iteration   1: 6.774 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 4.685 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.131 ±(99.9%) 0.013 ms/op
Iteration   1: 3.995 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.931 ms/op
                 getUser·p0.50:   3.834 ms/op
                 getUser·p0.90:   5.186 ms/op
                 getUser·p0.95:   5.759 ms/op
                 getUser·p0.99:   7.884 ms/op
                 getUser·p0.999:  12.712 ms/op
                 getUser·p0.9999: 15.810 ms/op
                 getUser·p1.00:   16.089 ms/op

Iteration   2: 3.988 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.198 ms/op
                 getUser·p0.50:   3.834 ms/op
                 getUser·p0.90:   5.153 ms/op
                 getUser·p0.95:   5.685 ms/op
                 getUser·p0.99:   7.635 ms/op
                 getUser·p0.999:  10.966 ms/op
                 getUser·p0.9999: 22.544 ms/op
                 getUser·p1.00:   22.839 ms/op

Iteration   3: 3.937 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.952 ms/op
                 getUser·p0.50:   3.777 ms/op
                 getUser·p0.90:   5.054 ms/op
                 getUser·p0.95:   5.546 ms/op
                 getUser·p0.99:   7.062 ms/op
                 getUser·p0.999:  10.730 ms/op
                 getUser·p0.9999: 32.469 ms/op
                 getUser·p1.00:   32.997 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 241530
  mean =      3.973 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6870 
    [ 2.500,  5.000) = 206004 
    [ 5.000,  7.500) = 26188 
    [ 7.500, 10.000) = 1977 
    [10.000, 12.500) = 298 
    [12.500, 15.000) = 80 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 25 
    [32.500, 35.000) = 7 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.931 ms/op
     p(50.0000) =      3.813 ms/op
     p(90.0000) =      5.128 ms/op
     p(95.0000) =      5.661 ms/op
     p(99.0000) =      7.528 ms/op
     p(99.9000) =     11.575 ms/op
     p(99.9900) =     31.939 ms/op
     p(99.9990) =     32.885 ms/op
     p(99.9999) =     32.997 ms/op
    p(100.0000) =     32.997 ms/op


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
# Warmup Iteration   1: 8.021 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 5.491 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 5.382 ±(99.9%) 0.021 ms/op
Iteration   1: 5.156 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.368 ms/op
                 listUser·p0.50:   4.809 ms/op
                 listUser·p0.90:   7.201 ms/op
                 listUser·p0.95:   8.110 ms/op
                 listUser·p0.99:   10.420 ms/op
                 listUser·p0.999:  17.754 ms/op
                 listUser·p0.9999: 20.447 ms/op
                 listUser·p1.00:   20.742 ms/op

Iteration   2: 5.314 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.071 ms/op
                 listUser·p0.50:   5.030 ms/op
                 listUser·p0.90:   6.996 ms/op
                 listUser·p0.95:   7.995 ms/op
                 listUser·p0.99:   10.371 ms/op
                 listUser·p0.999:  19.392 ms/op
                 listUser·p0.9999: 22.413 ms/op
                 listUser·p1.00:   22.839 ms/op

Iteration   3: 5.471 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.133 ms/op
                 listUser·p0.50:   5.120 ms/op
                 listUser·p0.90:   7.291 ms/op
                 listUser·p0.95:   8.298 ms/op
                 listUser·p0.99:   10.748 ms/op
                 listUser·p0.999:  23.708 ms/op
                 listUser·p0.9999: 30.817 ms/op
                 listUser·p1.00:   31.425 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 180883
  mean =      5.310 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 568 
    [ 2.500,  5.000) = 90016 
    [ 5.000,  7.500) = 76171 
    [ 7.500, 10.000) = 11628 
    [10.000, 12.500) = 1838 
    [12.500, 15.000) = 265 
    [15.000, 17.500) = 103 
    [17.500, 20.000) = 117 
    [20.000, 22.500) = 96 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 11 
    [27.500, 30.000) = 19 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.071 ms/op
     p(50.0000) =      4.997 ms/op
     p(90.0000) =      7.160 ms/op
     p(95.0000) =      8.126 ms/op
     p(99.0000) =     10.519 ms/op
     p(99.9000) =     19.956 ms/op
     p(99.9900) =     28.988 ms/op
     p(99.9990) =     31.265 ms/op
     p(99.9999) =     31.425 ms/op
    p(100.0000) =     31.425 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.325 ± 0.876  ops/ms
ClientGrpc.existUser                       thrpt       3   8.871 ± 2.355  ops/ms
ClientGrpc.getUser                         thrpt       3   8.330 ± 1.103  ops/ms
ClientGrpc.listUser                        thrpt       3   6.311 ± 3.423  ops/ms
ClientGrpc.createUser                       avgt       3   3.925 ± 0.966   ms/op
ClientGrpc.existUser                        avgt       3   3.688 ± 3.144   ms/op
ClientGrpc.getUser                          avgt       3   3.949 ± 0.451   ms/op
ClientGrpc.listUser                         avgt       3   5.108 ± 1.656   ms/op
ClientGrpc.createUser                     sample  240627   3.985 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.092           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.834           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.095           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.603           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.313           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.655           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.427           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.756           ms/op
ClientGrpc.existUser                      sample  235693   4.073 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.840           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.908           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.153           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.644           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.635           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.026           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          24.047           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          27.623           ms/op
ClientGrpc.getUser                        sample  241530   3.973 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.931           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.813           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.128           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.661           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.528           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.575           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          31.939           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          32.997           ms/op
ClientGrpc.listUser                       sample  180883   5.310 ± 0.013   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.071           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.997           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.160           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.126           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.519           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.956           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          28.988           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          31.425           ms/op
