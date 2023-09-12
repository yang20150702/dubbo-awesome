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
# Warmup Iteration   1: 3.419 ops/ms
# Warmup Iteration   2: 6.689 ops/ms
# Warmup Iteration   3: 8.141 ops/ms
Iteration   1: 8.357 ops/ms
Iteration   2: 8.420 ops/ms
Iteration   3: 8.621 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.466 ±(99.9%) 2.513 ops/ms [Average]
  (min, avg, max) = (8.357, 8.466, 8.621), stdev = 0.138
  CI (99.9%): [5.953, 10.979] (assumes normal distribution)


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
# Warmup Iteration   1: 5.824 ops/ms
# Warmup Iteration   2: 8.472 ops/ms
# Warmup Iteration   3: 8.618 ops/ms
Iteration   1: 8.893 ops/ms
Iteration   2: 9.089 ops/ms
Iteration   3: 8.870 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.950 ±(99.9%) 2.198 ops/ms [Average]
  (min, avg, max) = (8.870, 8.950, 9.089), stdev = 0.120
  CI (99.9%): [6.753, 11.148] (assumes normal distribution)


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
# Warmup Iteration   1: 5.156 ops/ms
# Warmup Iteration   2: 7.724 ops/ms
# Warmup Iteration   3: 7.906 ops/ms
Iteration   1: 8.562 ops/ms
Iteration   2: 8.419 ops/ms
Iteration   3: 8.112 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.364 ±(99.9%) 4.188 ops/ms [Average]
  (min, avg, max) = (8.112, 8.364, 8.562), stdev = 0.230
  CI (99.9%): [4.176, 12.552] (assumes normal distribution)


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
# Warmup Iteration   1: 4.608 ops/ms
# Warmup Iteration   2: 6.032 ops/ms
# Warmup Iteration   3: 6.478 ops/ms
Iteration   1: 6.573 ops/ms
Iteration   2: 6.585 ops/ms
Iteration   3: 6.503 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.553 ±(99.9%) 0.812 ops/ms [Average]
  (min, avg, max) = (6.503, 6.553, 6.585), stdev = 0.044
  CI (99.9%): [5.742, 7.365] (assumes normal distribution)


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
# Warmup Iteration   1: 5.892 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.051 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.911 ±(99.9%) 0.006 ms/op
Iteration   1: 3.745 ±(99.9%) 0.004 ms/op
Iteration   2: 3.742 ±(99.9%) 0.004 ms/op
Iteration   3: 3.755 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.747 ±(99.9%) 0.121 ms/op [Average]
  (min, avg, max) = (3.742, 3.747, 3.755), stdev = 0.007
  CI (99.9%): [3.626, 3.868] (assumes normal distribution)


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
# Warmup Iteration   1: 5.465 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.743 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.669 ±(99.9%) 0.004 ms/op
Iteration   1: 3.535 ±(99.9%) 0.003 ms/op
Iteration   2: 3.537 ±(99.9%) 0.004 ms/op
Iteration   3: 3.548 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.540 ±(99.9%) 0.124 ms/op [Average]
  (min, avg, max) = (3.535, 3.540, 3.548), stdev = 0.007
  CI (99.9%): [3.416, 3.665] (assumes normal distribution)


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
# Warmup Iteration   1: 5.410 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.918 ±(99.9%) 0.054 ms/op
# Warmup Iteration   3: 3.886 ±(99.9%) 0.004 ms/op
Iteration   1: 3.753 ±(99.9%) 0.005 ms/op
Iteration   2: 3.764 ±(99.9%) 0.004 ms/op
Iteration   3: 3.758 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.758 ±(99.9%) 0.102 ms/op [Average]
  (min, avg, max) = (3.753, 3.758, 3.764), stdev = 0.006
  CI (99.9%): [3.656, 3.860] (assumes normal distribution)


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
# Warmup Iteration   1: 5.890 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 5.153 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 5.013 ±(99.9%) 0.012 ms/op
Iteration   1: 4.944 ±(99.9%) 0.019 ms/op
Iteration   2: 4.802 ±(99.9%) 0.010 ms/op
Iteration   3: 4.704 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.817 ±(99.9%) 2.207 ms/op [Average]
  (min, avg, max) = (4.704, 4.817, 4.944), stdev = 0.121
  CI (99.9%): [2.610, 7.024] (assumes normal distribution)


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
# Warmup Iteration   1: 5.436 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 4.071 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.852 ±(99.9%) 0.010 ms/op
Iteration   1: 3.767 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.100 ms/op
                 createUser·p0.50:   3.678 ms/op
                 createUser·p0.90:   4.588 ms/op
                 createUser·p0.95:   5.014 ms/op
                 createUser·p0.99:   6.512 ms/op
                 createUser·p0.999:  11.293 ms/op
                 createUser·p0.9999: 16.393 ms/op
                 createUser·p1.00:   17.007 ms/op

Iteration   2: 3.736 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.940 ms/op
                 createUser·p0.50:   3.674 ms/op
                 createUser·p0.90:   4.538 ms/op
                 createUser·p0.95:   4.923 ms/op
                 createUser·p0.99:   6.065 ms/op
                 createUser·p0.999:  11.168 ms/op
                 createUser·p0.9999: 16.155 ms/op
                 createUser·p1.00:   16.351 ms/op

Iteration   3: 3.788 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.760 ms/op
                 createUser·p0.50:   3.686 ms/op
                 createUser·p0.90:   4.530 ms/op
                 createUser·p0.95:   4.907 ms/op
                 createUser·p0.99:   6.061 ms/op
                 createUser·p0.999:  11.804 ms/op
                 createUser·p0.9999: 18.630 ms/op
                 createUser·p1.00:   21.725 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 255094
  mean =      3.764 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7013 
    [ 2.500,  5.000) = 236478 
    [ 5.000,  7.500) = 10439 
    [ 7.500, 10.000) = 755 
    [10.000, 12.500) = 205 
    [12.500, 15.000) = 52 
    [15.000, 17.500) = 121 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.760 ms/op
     p(50.0000) =      3.682 ms/op
     p(90.0000) =      4.555 ms/op
     p(95.0000) =      4.948 ms/op
     p(99.0000) =      6.169 ms/op
     p(99.9000) =     11.402 ms/op
     p(99.9900) =     17.972 ms/op
     p(99.9990) =     20.094 ms/op
     p(99.9999) =     21.725 ms/op
    p(100.0000) =     21.725 ms/op


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
# Warmup Iteration   1: 5.255 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.896 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.676 ±(99.9%) 0.008 ms/op
Iteration   1: 3.649 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.980 ms/op
                 existUser·p0.50:   3.539 ms/op
                 existUser·p0.90:   4.440 ms/op
                 existUser·p0.95:   4.801 ms/op
                 existUser·p0.99:   6.218 ms/op
                 existUser·p0.999:  13.447 ms/op
                 existUser·p0.9999: 18.350 ms/op
                 existUser·p1.00:   18.579 ms/op

Iteration   2: 3.644 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.916 ms/op
                 existUser·p0.50:   3.559 ms/op
                 existUser·p0.90:   4.350 ms/op
                 existUser·p0.95:   4.678 ms/op
                 existUser·p0.99:   5.825 ms/op
                 existUser·p0.999:  9.421 ms/op
                 existUser·p0.9999: 17.676 ms/op
                 existUser·p1.00:   18.153 ms/op

Iteration   3: 3.624 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.655 ms/op
                 existUser·p0.50:   3.518 ms/op
                 existUser·p0.90:   4.325 ms/op
                 existUser·p0.95:   4.628 ms/op
                 existUser·p0.99:   5.956 ms/op
                 existUser·p0.999:  11.354 ms/op
                 existUser·p0.9999: 19.020 ms/op
                 existUser·p1.00:   21.594 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 263965
  mean =      3.639 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5314 
    [ 2.500,  5.000) = 251146 
    [ 5.000,  7.500) = 6246 
    [ 7.500, 10.000) = 798 
    [10.000, 12.500) = 250 
    [12.500, 15.000) = 72 
    [15.000, 17.500) = 72 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.655 ms/op
     p(50.0000) =      3.539 ms/op
     p(90.0000) =      4.375 ms/op
     p(95.0000) =      4.702 ms/op
     p(99.0000) =      5.975 ms/op
     p(99.9000) =     11.519 ms/op
     p(99.9900) =     18.390 ms/op
     p(99.9990) =     20.363 ms/op
     p(99.9999) =     21.594 ms/op
    p(100.0000) =     21.594 ms/op


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
# Warmup Iteration   1: 5.630 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 4.157 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.936 ±(99.9%) 0.010 ms/op
Iteration   1: 3.938 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.033 ms/op
                 getUser·p0.50:   3.777 ms/op
                 getUser·p0.90:   4.866 ms/op
                 getUser·p0.95:   5.317 ms/op
                 getUser·p0.99:   6.832 ms/op
                 getUser·p0.999:  10.253 ms/op
                 getUser·p0.9999: 15.035 ms/op
                 getUser·p1.00:   15.139 ms/op

Iteration   2: 3.787 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.998 ms/op
                 getUser·p0.50:   3.695 ms/op
                 getUser·p0.90:   4.612 ms/op
                 getUser·p0.95:   5.022 ms/op
                 getUser·p0.99:   6.078 ms/op
                 getUser·p0.999:  10.201 ms/op
                 getUser·p0.9999: 18.860 ms/op
                 getUser·p1.00:   19.137 ms/op

Iteration   3: 3.850 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.886 ms/op
                 getUser·p0.50:   3.760 ms/op
                 getUser·p0.90:   4.776 ms/op
                 getUser·p0.95:   5.226 ms/op
                 getUser·p0.99:   6.447 ms/op
                 getUser·p0.999:  10.008 ms/op
                 getUser·p0.9999: 18.547 ms/op
                 getUser·p1.00:   20.840 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 248803
  mean =      3.857 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6181 
    [ 2.500,  5.000) = 225953 
    [ 5.000,  7.500) = 15425 
    [ 7.500, 10.000) = 971 
    [10.000, 12.500) = 168 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.886 ms/op
     p(50.0000) =      3.744 ms/op
     p(90.0000) =      4.760 ms/op
     p(95.0000) =      5.186 ms/op
     p(99.0000) =      6.472 ms/op
     p(99.9000) =     10.129 ms/op
     p(99.9900) =     18.448 ms/op
     p(99.9990) =     20.776 ms/op
     p(99.9999) =     20.840 ms/op
    p(100.0000) =     20.840 ms/op


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
# Warmup Iteration   1: 6.088 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 5.434 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.658 ±(99.9%) 0.014 ms/op
Iteration   1: 4.832 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.432 ms/op
                 listUser·p0.50:   4.596 ms/op
                 listUser·p0.90:   6.078 ms/op
                 listUser·p0.95:   7.078 ms/op
                 listUser·p0.99:   9.191 ms/op
                 listUser·p0.999:  16.499 ms/op
                 listUser·p0.9999: 19.857 ms/op
                 listUser·p1.00:   20.251 ms/op

Iteration   2: 4.876 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   0.992 ms/op
                 listUser·p0.50:   4.628 ms/op
                 listUser·p0.90:   6.128 ms/op
                 listUser·p0.95:   6.914 ms/op
                 listUser·p0.99:   8.962 ms/op
                 listUser·p0.999:  17.649 ms/op
                 listUser·p0.9999: 25.690 ms/op
                 listUser·p1.00:   27.591 ms/op

Iteration   3: 4.896 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.710 ms/op
                 listUser·p0.50:   4.628 ms/op
                 listUser·p0.90:   6.193 ms/op
                 listUser·p0.95:   7.160 ms/op
                 listUser·p0.99:   9.290 ms/op
                 listUser·p0.999:  19.683 ms/op
                 listUser·p0.9999: 32.192 ms/op
                 listUser·p1.00:   35.848 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 197130
  mean =      4.868 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 149 
    [ 2.500,  5.000) = 142309 
    [ 5.000,  7.500) = 47970 
    [ 7.500, 10.000) = 5496 
    [10.000, 12.500) = 751 
    [12.500, 15.000) = 145 
    [15.000, 17.500) = 113 
    [17.500, 20.000) = 75 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 45 
    [25.000, 27.500) = 18 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 28 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.992 ms/op
     p(50.0000) =      4.620 ms/op
     p(90.0000) =      6.136 ms/op
     p(95.0000) =      7.053 ms/op
     p(99.0000) =      9.126 ms/op
     p(99.9000) =     17.522 ms/op
     p(99.9900) =     31.312 ms/op
     p(99.9990) =     35.848 ms/op
     p(99.9999) =     35.848 ms/op
    p(100.0000) =     35.848 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.466 ± 2.513  ops/ms
ClientGrpc.existUser                       thrpt       3   8.950 ± 2.198  ops/ms
ClientGrpc.getUser                         thrpt       3   8.364 ± 4.188  ops/ms
ClientGrpc.listUser                        thrpt       3   6.553 ± 0.812  ops/ms
ClientGrpc.createUser                       avgt       3   3.747 ± 0.121   ms/op
ClientGrpc.existUser                        avgt       3   3.540 ± 0.124   ms/op
ClientGrpc.getUser                          avgt       3   3.758 ± 0.102   ms/op
ClientGrpc.listUser                         avgt       3   4.817 ± 2.207   ms/op
ClientGrpc.createUser                     sample  255094   3.764 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.760           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.682           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.555           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.948           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.169           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.402           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.972           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.725           ms/op
ClientGrpc.existUser                      sample  263965   3.639 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.655           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.539           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.375           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.702           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.975           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.519           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.390           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.594           ms/op
ClientGrpc.getUser                        sample  248803   3.857 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.886           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.744           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.760           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.186           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.472           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.129           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.448           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.840           ms/op
ClientGrpc.listUser                       sample  197130   4.868 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.992           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.620           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.136           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.053           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.126           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.522           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          31.312           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          35.848           ms/op
