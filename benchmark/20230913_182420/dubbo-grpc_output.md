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
# Warmup Iteration   1: 2.463 ops/ms
# Warmup Iteration   2: 5.733 ops/ms
# Warmup Iteration   3: 7.816 ops/ms
Iteration   1: 7.680 ops/ms
Iteration   2: 8.037 ops/ms
Iteration   3: 8.221 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.979 ±(99.9%) 5.018 ops/ms [Average]
  (min, avg, max) = (7.680, 7.979, 8.221), stdev = 0.275
  CI (99.9%): [2.961, 12.997] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 5.643 ops/ms
# Warmup Iteration   2: 8.040 ops/ms
# Warmup Iteration   3: 8.552 ops/ms
Iteration   1: 8.830 ops/ms
Iteration   2: 8.880 ops/ms
Iteration   3: 8.836 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.849 ±(99.9%) 0.500 ops/ms [Average]
  (min, avg, max) = (8.830, 8.849, 8.880), stdev = 0.027
  CI (99.9%): [8.349, 9.349] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 4.472 ops/ms
# Warmup Iteration   2: 7.632 ops/ms
# Warmup Iteration   3: 8.046 ops/ms
Iteration   1: 8.261 ops/ms
Iteration   2: 8.253 ops/ms
Iteration   3: 8.470 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.328 ±(99.9%) 2.246 ops/ms [Average]
  (min, avg, max) = (8.253, 8.328, 8.470), stdev = 0.123
  CI (99.9%): [6.082, 10.574] (assumes normal distribution)


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
# Warmup Iteration   1: 3.975 ops/ms
# Warmup Iteration   2: 5.695 ops/ms
# Warmup Iteration   3: 5.911 ops/ms
Iteration   1: 6.243 ops/ms
Iteration   2: 6.262 ops/ms
Iteration   3: 6.331 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.279 ±(99.9%) 0.845 ops/ms [Average]
  (min, avg, max) = (6.243, 6.279, 6.331), stdev = 0.046
  CI (99.9%): [5.434, 7.124] (assumes normal distribution)


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
# Warmup Iteration   1: 6.417 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.353 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.189 ±(99.9%) 0.011 ms/op
Iteration   1: 4.054 ±(99.9%) 0.005 ms/op
Iteration   2: 3.869 ±(99.9%) 0.003 ms/op
Iteration   3: 3.843 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.922 ±(99.9%) 2.100 ms/op [Average]
  (min, avg, max) = (3.843, 3.922, 4.054), stdev = 0.115
  CI (99.9%): [1.821, 6.022] (assumes normal distribution)


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
# Warmup Iteration   1: 5.685 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.063 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.770 ±(99.9%) 0.018 ms/op
Iteration   1: 3.731 ±(99.9%) 0.004 ms/op
Iteration   2: 3.545 ±(99.9%) 0.003 ms/op
Iteration   3: 3.615 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.630 ±(99.9%) 1.712 ms/op [Average]
  (min, avg, max) = (3.545, 3.630, 3.731), stdev = 0.094
  CI (99.9%): [1.918, 5.343] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 6.088 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 4.364 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.964 ±(99.9%) 0.008 ms/op
Iteration   1: 3.858 ±(99.9%) 0.005 ms/op
Iteration   2: 3.862 ±(99.9%) 0.003 ms/op
Iteration   3: 3.865 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.862 ±(99.9%) 0.067 ms/op [Average]
  (min, avg, max) = (3.858, 3.862, 3.865), stdev = 0.004
  CI (99.9%): [3.795, 3.929] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 7.764 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 5.659 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 5.224 ±(99.9%) 0.021 ms/op
Iteration   1: 5.173 ±(99.9%) 0.040 ms/op
Iteration   2: 5.232 ±(99.9%) 0.019 ms/op
Iteration   3: 5.182 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.195 ±(99.9%) 0.586 ms/op [Average]
  (min, avg, max) = (5.173, 5.195, 5.232), stdev = 0.032
  CI (99.9%): [4.610, 5.781] (assumes normal distribution)


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
# Warmup Iteration   1: 6.629 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 4.379 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.051 ±(99.9%) 0.011 ms/op
Iteration   1: 3.983 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.918 ms/op
                 createUser·p0.50:   3.867 ms/op
                 createUser·p0.90:   5.038 ms/op
                 createUser·p0.95:   5.448 ms/op
                 createUser·p0.99:   6.605 ms/op
                 createUser·p0.999:  13.938 ms/op
                 createUser·p0.9999: 22.807 ms/op
                 createUser·p1.00:   23.069 ms/op

Iteration   2: 3.994 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.973 ms/op
                 createUser·p0.50:   3.879 ms/op
                 createUser·p0.90:   4.940 ms/op
                 createUser·p0.95:   5.358 ms/op
                 createUser·p0.99:   6.840 ms/op
                 createUser·p0.999:  10.368 ms/op
                 createUser·p0.9999: 15.761 ms/op
                 createUser·p1.00:   17.334 ms/op

Iteration   3: 4.064 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.913 ms/op
                 createUser·p0.50:   3.940 ms/op
                 createUser·p0.90:   5.038 ms/op
                 createUser·p0.95:   5.464 ms/op
                 createUser·p0.99:   7.078 ms/op
                 createUser·p0.999:  18.055 ms/op
                 createUser·p0.9999: 28.155 ms/op
                 createUser·p1.00:   29.688 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 239193
  mean =      4.013 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5060 
    [ 2.500,  5.000) = 209878 
    [ 5.000,  7.500) = 22782 
    [ 7.500, 10.000) = 1076 
    [10.000, 12.500) = 138 
    [12.500, 15.000) = 60 
    [15.000, 17.500) = 79 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.913 ms/op
     p(50.0000) =      3.895 ms/op
     p(90.0000) =      5.014 ms/op
     p(95.0000) =      5.423 ms/op
     p(99.0000) =      6.840 ms/op
     p(99.9000) =     13.563 ms/op
     p(99.9900) =     27.306 ms/op
     p(99.9990) =     29.538 ms/op
     p(99.9999) =     29.688 ms/op
    p(100.0000) =     29.688 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.268 ±(99.9%) 0.074 ms/op
# Warmup Iteration   2: 4.176 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.880 ±(99.9%) 0.010 ms/op
Iteration   1: 3.741 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.928 ms/op
                 existUser·p0.50:   3.629 ms/op
                 existUser·p0.90:   4.637 ms/op
                 existUser·p0.95:   5.120 ms/op
                 existUser·p0.99:   6.513 ms/op
                 existUser·p0.999:  11.639 ms/op
                 existUser·p0.9999: 16.200 ms/op
                 existUser·p1.00:   16.712 ms/op

Iteration   2: 3.722 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.776 ms/op
                 existUser·p0.50:   3.621 ms/op
                 existUser·p0.90:   4.637 ms/op
                 existUser·p0.95:   5.112 ms/op
                 existUser·p0.99:   6.521 ms/op
                 existUser·p0.999:  17.300 ms/op
                 existUser·p0.9999: 21.627 ms/op
                 existUser·p1.00:   22.348 ms/op

Iteration   3: 3.862 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.913 ms/op
                 existUser·p0.50:   3.719 ms/op
                 existUser·p0.90:   4.833 ms/op
                 existUser·p0.95:   5.423 ms/op
                 existUser·p0.99:   7.954 ms/op
                 existUser·p0.999:  14.909 ms/op
                 existUser·p0.9999: 18.420 ms/op
                 existUser·p1.00:   24.412 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 254546
  mean =      3.774 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10532 
    [ 2.500,  5.000) = 227344 
    [ 5.000,  7.500) = 14716 
    [ 7.500, 10.000) = 1303 
    [10.000, 12.500) = 322 
    [12.500, 15.000) = 126 
    [15.000, 17.500) = 105 
    [17.500, 20.000) = 63 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.776 ms/op
     p(50.0000) =      3.654 ms/op
     p(90.0000) =      4.702 ms/op
     p(95.0000) =      5.202 ms/op
     p(99.0000) =      7.021 ms/op
     p(99.9000) =     14.311 ms/op
     p(99.9900) =     21.103 ms/op
     p(99.9990) =     22.312 ms/op
     p(99.9999) =     24.412 ms/op
    p(100.0000) =     24.412 ms/op


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
# Warmup Iteration   1: 6.435 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 4.316 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.067 ±(99.9%) 0.012 ms/op
Iteration   1: 3.961 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.069 ms/op
                 getUser·p0.50:   3.842 ms/op
                 getUser·p0.90:   4.997 ms/op
                 getUser·p0.95:   5.497 ms/op
                 getUser·p0.99:   7.068 ms/op
                 getUser·p0.999:  11.239 ms/op
                 getUser·p0.9999: 15.869 ms/op
                 getUser·p1.00:   16.581 ms/op

Iteration   2: 4.044 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.979 ms/op
                 getUser·p0.50:   3.944 ms/op
                 getUser·p0.90:   5.054 ms/op
                 getUser·p0.95:   5.464 ms/op
                 getUser·p0.99:   6.882 ms/op
                 getUser·p0.999:  10.761 ms/op
                 getUser·p0.9999: 25.559 ms/op
                 getUser·p1.00:   25.821 ms/op

Iteration   3: 3.972 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.019 ms/op
                 getUser·p0.50:   3.871 ms/op
                 getUser·p0.90:   4.899 ms/op
                 getUser·p0.95:   5.292 ms/op
                 getUser·p0.99:   6.750 ms/op
                 getUser·p0.999:  12.343 ms/op
                 getUser·p0.9999: 18.547 ms/op
                 getUser·p1.00:   19.759 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 240562
  mean =      3.992 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6613 
    [ 2.500,  5.000) = 210756 
    [ 5.000,  7.500) = 21575 
    [ 7.500, 10.000) = 1171 
    [10.000, 12.500) = 271 
    [12.500, 15.000) = 60 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.979 ms/op
     p(50.0000) =      3.883 ms/op
     p(90.0000) =      4.981 ms/op
     p(95.0000) =      5.423 ms/op
     p(99.0000) =      6.898 ms/op
     p(99.9000) =     11.731 ms/op
     p(99.9900) =     22.741 ms/op
     p(99.9990) =     25.808 ms/op
     p(99.9999) =     25.821 ms/op
    p(100.0000) =     25.821 ms/op


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
# Warmup Iteration   1: 7.501 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 5.710 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 5.244 ±(99.9%) 0.019 ms/op
Iteration   1: 5.236 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.405 ms/op
                 listUser·p0.50:   4.907 ms/op
                 listUser·p0.90:   7.184 ms/op
                 listUser·p0.95:   8.077 ms/op
                 listUser·p0.99:   10.535 ms/op
                 listUser·p0.999:  18.672 ms/op
                 listUser·p0.9999: 23.982 ms/op
                 listUser·p1.00:   24.281 ms/op

Iteration   2: 5.265 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.192 ms/op
                 listUser·p0.50:   4.866 ms/op
                 listUser·p0.90:   7.234 ms/op
                 listUser·p0.95:   8.184 ms/op
                 listUser·p0.99:   10.764 ms/op
                 listUser·p0.999:  19.151 ms/op
                 listUser·p0.9999: 29.872 ms/op
                 listUser·p1.00:   30.605 ms/op

Iteration   3: 5.243 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.286 ms/op
                 listUser·p0.50:   4.858 ms/op
                 listUser·p0.90:   7.447 ms/op
                 listUser·p0.95:   8.217 ms/op
                 listUser·p0.99:   10.207 ms/op
                 listUser·p0.999:  19.399 ms/op
                 listUser·p0.9999: 24.445 ms/op
                 listUser·p1.00:   24.773 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 182967
  mean =      5.248 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 552 
    [ 2.500,  5.000) = 99767 
    [ 5.000,  7.500) = 66726 
    [ 7.500, 10.000) = 13454 
    [10.000, 12.500) = 1864 
    [12.500, 15.000) = 229 
    [15.000, 17.500) = 91 
    [17.500, 20.000) = 150 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 56 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 27 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.192 ms/op
     p(50.0000) =      4.882 ms/op
     p(90.0000) =      7.299 ms/op
     p(95.0000) =      8.167 ms/op
     p(99.0000) =     10.486 ms/op
     p(99.9000) =     19.268 ms/op
     p(99.9900) =     29.023 ms/op
     p(99.9990) =     30.442 ms/op
     p(99.9999) =     30.605 ms/op
    p(100.0000) =     30.605 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.979 ± 5.018  ops/ms
ClientGrpc.existUser                       thrpt       3   8.849 ± 0.500  ops/ms
ClientGrpc.getUser                         thrpt       3   8.328 ± 2.246  ops/ms
ClientGrpc.listUser                        thrpt       3   6.279 ± 0.845  ops/ms
ClientGrpc.createUser                       avgt       3   3.922 ± 2.100   ms/op
ClientGrpc.existUser                        avgt       3   3.630 ± 1.712   ms/op
ClientGrpc.getUser                          avgt       3   3.862 ± 0.067   ms/op
ClientGrpc.listUser                         avgt       3   5.195 ± 0.586   ms/op
ClientGrpc.createUser                     sample  239193   4.013 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.913           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.895           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.014           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.423           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.840           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.563           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          27.306           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          29.688           ms/op
ClientGrpc.existUser                      sample  254546   3.774 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.776           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.654           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.702           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.202           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.021           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          14.311           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.103           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          24.412           ms/op
ClientGrpc.getUser                        sample  240562   3.992 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.979           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.883           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.981           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.423           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.898           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.731           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.741           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.821           ms/op
ClientGrpc.listUser                       sample  182967   5.248 ± 0.012   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.192           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.882           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.299           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.167           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.486           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.268           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          29.023           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          30.605           ms/op
