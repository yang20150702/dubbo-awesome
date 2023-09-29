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
# Warmup Iteration   1: 4.133 ops/ms
# Warmup Iteration   2: 8.785 ops/ms
# Warmup Iteration   3: 9.673 ops/ms
Iteration   1: 10.147 ops/ms
Iteration   2: 10.222 ops/ms
Iteration   3: 10.355 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.241 ±(99.9%) 1.917 ops/ms [Average]
  (min, avg, max) = (10.147, 10.241, 10.355), stdev = 0.105
  CI (99.9%): [8.324, 12.158] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 7.769 ops/ms
# Warmup Iteration   2: 10.563 ops/ms
# Warmup Iteration   3: 10.882 ops/ms
Iteration   1: 10.770 ops/ms
Iteration   2: 10.769 ops/ms
Iteration   3: 10.766 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.768 ±(99.9%) 0.042 ops/ms [Average]
  (min, avg, max) = (10.766, 10.768, 10.770), stdev = 0.002
  CI (99.9%): [10.727, 10.810] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 7.266 ops/ms
# Warmup Iteration   2: 10.062 ops/ms
# Warmup Iteration   3: 10.100 ops/ms
Iteration   1: 10.421 ops/ms
Iteration   2: 10.588 ops/ms
Iteration   3: 10.286 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.432 ±(99.9%) 2.755 ops/ms [Average]
  (min, avg, max) = (10.286, 10.432, 10.588), stdev = 0.151
  CI (99.9%): [7.677, 13.186] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 5.839 ops/ms
# Warmup Iteration   2: 8.111 ops/ms
# Warmup Iteration   3: 8.140 ops/ms
Iteration   1: 8.371 ops/ms
Iteration   2: 8.440 ops/ms
Iteration   3: 8.448 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.420 ±(99.9%) 0.769 ops/ms [Average]
  (min, avg, max) = (8.371, 8.420, 8.448), stdev = 0.042
  CI (99.9%): [7.650, 9.189] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 3.866 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.280 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.131 ±(99.9%) 0.008 ms/op
Iteration   1: 3.080 ±(99.9%) 0.003 ms/op
Iteration   2: 3.138 ±(99.9%) 0.003 ms/op
Iteration   3: 3.125 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.114 ±(99.9%) 0.559 ms/op [Average]
  (min, avg, max) = (3.080, 3.114, 3.138), stdev = 0.031
  CI (99.9%): [2.555, 3.674] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 3.729 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.067 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.993 ±(99.9%) 0.001 ms/op
Iteration   1: 2.949 ±(99.9%) 0.002 ms/op
Iteration   2: 2.985 ±(99.9%) 0.003 ms/op
Iteration   3: 2.988 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.974 ±(99.9%) 0.399 ms/op [Average]
  (min, avg, max) = (2.949, 2.974, 2.988), stdev = 0.022
  CI (99.9%): [2.575, 3.373] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 4.146 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.133 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.097 ±(99.9%) 0.002 ms/op
Iteration   1: 3.098 ±(99.9%) 0.002 ms/op
Iteration   2: 3.122 ±(99.9%) 0.001 ms/op
Iteration   3: 3.082 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.101 ±(99.9%) 0.369 ms/op [Average]
  (min, avg, max) = (3.082, 3.101, 3.122), stdev = 0.020
  CI (99.9%): [2.732, 3.470] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 4.442 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.957 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 3.861 ±(99.9%) 0.021 ms/op
Iteration   1: 3.826 ±(99.9%) 0.016 ms/op
Iteration   2: 3.889 ±(99.9%) 0.028 ms/op
Iteration   3: 3.864 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.860 ±(99.9%) 0.577 ms/op [Average]
  (min, avg, max) = (3.826, 3.860, 3.889), stdev = 0.032
  CI (99.9%): [3.283, 4.436] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.230 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.272 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.143 ±(99.9%) 0.007 ms/op
Iteration   1: 3.114 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.634 ms/op
                 createUser·p0.50:   3.088 ms/op
                 createUser·p0.90:   3.645 ms/op
                 createUser·p0.95:   3.772 ms/op
                 createUser·p0.99:   4.276 ms/op
                 createUser·p0.999:  7.389 ms/op
                 createUser·p0.9999: 19.399 ms/op
                 createUser·p1.00:   19.890 ms/op

Iteration   2: 3.119 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.846 ms/op
                 createUser·p0.50:   3.072 ms/op
                 createUser·p0.90:   3.645 ms/op
                 createUser·p0.95:   3.850 ms/op
                 createUser·p0.99:   4.325 ms/op
                 createUser·p0.999:  9.624 ms/op
                 createUser·p0.9999: 17.686 ms/op
                 createUser·p1.00:   18.153 ms/op

Iteration   3: 3.149 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.565 ms/op
                 createUser·p0.50:   3.097 ms/op
                 createUser·p0.90:   3.752 ms/op
                 createUser·p0.95:   3.920 ms/op
                 createUser·p0.99:   4.441 ms/op
                 createUser·p0.999:  9.582 ms/op
                 createUser·p0.9999: 18.874 ms/op
                 createUser·p1.00:   19.202 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 307061
  mean =      3.127 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 583 
    [ 1.250,  2.500) = 10039 
    [ 2.500,  3.750) = 272849 
    [ 3.750,  5.000) = 21958 
    [ 5.000,  6.250) = 803 
    [ 6.250,  7.500) = 395 
    [ 7.500,  8.750) = 99 
    [ 8.750, 10.000) = 89 
    [10.000, 11.250) = 54 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 12 
    [13.750, 15.000) = 20 
    [15.000, 16.250) = 20 
    [16.250, 17.500) = 46 
    [17.500, 18.750) = 57 

  Percentiles, ms/op:
      p(0.0000) =      0.565 ms/op
     p(50.0000) =      3.084 ms/op
     p(90.0000) =      3.682 ms/op
     p(95.0000) =      3.854 ms/op
     p(99.0000) =      4.342 ms/op
     p(99.9000) =      9.126 ms/op
     p(99.9900) =     18.917 ms/op
     p(99.9990) =     19.691 ms/op
     p(99.9999) =     19.890 ms/op
    p(100.0000) =     19.890 ms/op


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
# Warmup Iteration   1: 3.802 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.028 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.039 ±(99.9%) 0.005 ms/op
Iteration   1: 3.053 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.949 ms/op
                 existUser·p0.50:   3.011 ms/op
                 existUser·p0.90:   3.555 ms/op
                 existUser·p0.95:   3.670 ms/op
                 existUser·p0.99:   4.260 ms/op
                 existUser·p0.999:  9.241 ms/op
                 existUser·p0.9999: 13.632 ms/op
                 existUser·p1.00:   13.943 ms/op

Iteration   2: 3.073 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.609 ms/op
                 existUser·p0.50:   3.027 ms/op
                 existUser·p0.90:   3.666 ms/op
                 existUser·p0.95:   3.785 ms/op
                 existUser·p0.99:   4.276 ms/op
                 existUser·p0.999:  10.779 ms/op
                 existUser·p0.9999: 14.309 ms/op
                 existUser·p1.00:   14.877 ms/op

Iteration   3: 3.029 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.641 ms/op
                 existUser·p0.50:   2.982 ms/op
                 existUser·p0.90:   3.498 ms/op
                 existUser·p0.95:   3.699 ms/op
                 existUser·p0.99:   4.497 ms/op
                 existUser·p0.999:  9.388 ms/op
                 existUser·p0.9999: 15.994 ms/op
                 existUser·p1.00:   16.744 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 314622
  mean =      3.052 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 554 
    [ 1.250,  2.500) = 18344 
    [ 2.500,  3.750) = 281610 
    [ 3.750,  5.000) = 12527 
    [ 5.000,  6.250) = 736 
    [ 6.250,  7.500) = 347 
    [ 7.500,  8.750) = 103 
    [ 8.750, 10.000) = 156 
    [10.000, 11.250) = 70 
    [11.250, 12.500) = 15 
    [12.500, 13.750) = 67 
    [13.750, 15.000) = 51 
    [15.000, 16.250) = 37 
    [16.250, 17.500) = 5 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.609 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.584 ms/op
     p(95.0000) =      3.727 ms/op
     p(99.0000) =      4.334 ms/op
     p(99.9000) =      9.378 ms/op
     p(99.9900) =     15.444 ms/op
     p(99.9990) =     16.374 ms/op
     p(99.9999) =     16.744 ms/op
    p(100.0000) =     16.744 ms/op


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
# Warmup Iteration   1: 3.671 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.209 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.088 ±(99.9%) 0.005 ms/op
Iteration   1: 3.100 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.462 ms/op
                 getUser·p0.50:   3.068 ms/op
                 getUser·p0.90:   3.617 ms/op
                 getUser·p0.95:   3.809 ms/op
                 getUser·p0.99:   4.399 ms/op
                 getUser·p0.999:  9.994 ms/op
                 getUser·p0.9999: 12.818 ms/op
                 getUser·p1.00:   13.140 ms/op

Iteration   2: 3.156 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.739 ms/op
                 getUser·p0.50:   3.117 ms/op
                 getUser·p0.90:   3.699 ms/op
                 getUser·p0.95:   3.920 ms/op
                 getUser·p0.99:   4.653 ms/op
                 getUser·p0.999:  8.867 ms/op
                 getUser·p0.9999: 14.629 ms/op
                 getUser·p1.00:   14.877 ms/op

Iteration   3: 3.117 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.540 ms/op
                 getUser·p0.50:   3.080 ms/op
                 getUser·p0.90:   3.584 ms/op
                 getUser·p0.95:   3.777 ms/op
                 getUser·p0.99:   4.301 ms/op
                 getUser·p0.999:  7.805 ms/op
                 getUser·p0.9999: 15.597 ms/op
                 getUser·p1.00:   16.515 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 307033
  mean =      3.124 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 694 
    [ 1.250,  2.500) = 8388 
    [ 2.500,  3.750) = 276879 
    [ 3.750,  5.000) = 19342 
    [ 5.000,  6.250) = 674 
    [ 6.250,  7.500) = 553 
    [ 7.500,  8.750) = 222 
    [ 8.750, 10.000) = 43 
    [10.000, 11.250) = 76 
    [11.250, 12.500) = 16 
    [12.500, 13.750) = 52 
    [13.750, 15.000) = 79 
    [15.000, 16.250) = 11 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.462 ms/op
     p(50.0000) =      3.088 ms/op
     p(90.0000) =      3.625 ms/op
     p(95.0000) =      3.846 ms/op
     p(99.0000) =      4.456 ms/op
     p(99.9000) =      8.454 ms/op
     p(99.9900) =     14.680 ms/op
     p(99.9990) =     16.430 ms/op
     p(99.9999) =     16.515 ms/op
    p(100.0000) =     16.515 ms/op


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
# Warmup Iteration   1: 5.233 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.968 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.917 ±(99.9%) 0.009 ms/op
Iteration   1: 3.897 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.282 ms/op
                 listUser·p0.50:   3.805 ms/op
                 listUser·p0.90:   4.276 ms/op
                 listUser·p0.95:   5.104 ms/op
                 listUser·p0.99:   6.775 ms/op
                 listUser·p0.999:  12.974 ms/op
                 listUser·p0.9999: 14.254 ms/op
                 listUser·p1.00:   15.466 ms/op

Iteration   2: 3.836 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.767 ms/op
                 listUser·p0.50:   3.781 ms/op
                 listUser·p0.90:   4.202 ms/op
                 listUser·p0.95:   4.489 ms/op
                 listUser·p0.99:   6.414 ms/op
                 listUser·p0.999:  13.844 ms/op
                 listUser·p0.9999: 16.071 ms/op
                 listUser·p1.00:   17.269 ms/op

Iteration   3: 3.891 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.128 ms/op
                 listUser·p0.50:   3.777 ms/op
                 listUser·p0.90:   4.596 ms/op
                 listUser·p0.95:   5.677 ms/op
                 listUser·p0.99:   6.570 ms/op
                 listUser·p0.999:  13.523 ms/op
                 listUser·p0.9999: 15.550 ms/op
                 listUser·p1.00:   17.334 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 247829
  mean =      3.874 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 18 
    [ 1.250,  2.500) = 3471 
    [ 2.500,  3.750) = 108853 
    [ 3.750,  5.000) = 122160 
    [ 5.000,  6.250) = 8899 
    [ 6.250,  7.500) = 3276 
    [ 7.500,  8.750) = 518 
    [ 8.750, 10.000) = 148 
    [10.000, 11.250) = 80 
    [11.250, 12.500) = 40 
    [12.500, 13.750) = 159 
    [13.750, 15.000) = 122 
    [15.000, 16.250) = 77 
    [16.250, 17.500) = 8 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.282 ms/op
     p(50.0000) =      3.789 ms/op
     p(90.0000) =      4.301 ms/op
     p(95.0000) =      5.136 ms/op
     p(99.0000) =      6.586 ms/op
     p(99.9000) =     13.451 ms/op
     p(99.9900) =     15.506 ms/op
     p(99.9990) =     17.128 ms/op
     p(99.9999) =     17.334 ms/op
    p(100.0000) =     17.334 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.241 ± 1.917  ops/ms
ClientGrpc.existUser                       thrpt       3  10.768 ± 0.042  ops/ms
ClientGrpc.getUser                         thrpt       3  10.432 ± 2.755  ops/ms
ClientGrpc.listUser                        thrpt       3   8.420 ± 0.769  ops/ms
ClientGrpc.createUser                       avgt       3   3.114 ± 0.559   ms/op
ClientGrpc.existUser                        avgt       3   2.974 ± 0.399   ms/op
ClientGrpc.getUser                          avgt       3   3.101 ± 0.369   ms/op
ClientGrpc.listUser                         avgt       3   3.860 ± 0.577   ms/op
ClientGrpc.createUser                     sample  307061   3.127 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.565           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.084           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.682           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.854           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.342           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.126           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.917           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.890           ms/op
ClientGrpc.existUser                      sample  314622   3.052 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.609           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.002           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.584           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.727           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.334           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.378           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.444           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.744           ms/op
ClientGrpc.getUser                        sample  307033   3.124 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.462           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.088           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.625           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.846           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.456           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.454           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          14.680           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          16.515           ms/op
ClientGrpc.listUser                       sample  247829   3.874 ± 0.005   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.282           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.789           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.301           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.136           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.586           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.451           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          15.506           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          17.334           ms/op
