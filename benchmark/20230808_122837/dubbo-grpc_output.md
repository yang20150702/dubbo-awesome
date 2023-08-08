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
# Warmup Iteration   1: 4.083 ops/ms
# Warmup Iteration   2: 8.788 ops/ms
# Warmup Iteration   3: 10.129 ops/ms
Iteration   1: 10.218 ops/ms
Iteration   2: 10.634 ops/ms
Iteration   3: 10.452 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.434 ±(99.9%) 3.803 ops/ms [Average]
  (min, avg, max) = (10.218, 10.434, 10.634), stdev = 0.208
  CI (99.9%): [6.632, 14.237] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.127 ops/ms
# Warmup Iteration   2: 10.437 ops/ms
# Warmup Iteration   3: 10.753 ops/ms
Iteration   1: 11.197 ops/ms
Iteration   2: 10.899 ops/ms
Iteration   3: 11.156 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.084 ±(99.9%) 2.947 ops/ms [Average]
  (min, avg, max) = (10.899, 11.084, 11.197), stdev = 0.162
  CI (99.9%): [8.137, 14.031] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 6.523 ops/ms
# Warmup Iteration   2: 10.007 ops/ms
# Warmup Iteration   3: 10.163 ops/ms
Iteration   1: 10.295 ops/ms
Iteration   2: 10.473 ops/ms
Iteration   3: 10.338 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.369 ±(99.9%) 1.688 ops/ms [Average]
  (min, avg, max) = (10.295, 10.369, 10.473), stdev = 0.093
  CI (99.9%): [8.681, 12.056] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.890 ops/ms
# Warmup Iteration   2: 7.545 ops/ms
# Warmup Iteration   3: 7.823 ops/ms
Iteration   1: 7.876 ops/ms
Iteration   2: 7.809 ops/ms
Iteration   3: 7.995 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.893 ±(99.9%) 1.717 ops/ms [Average]
  (min, avg, max) = (7.809, 7.893, 7.995), stdev = 0.094
  CI (99.9%): [6.176, 9.610] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.101 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.206 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.086 ±(99.9%) 0.003 ms/op
Iteration   1: 3.039 ±(99.9%) 0.003 ms/op
Iteration   2: 3.019 ±(99.9%) 0.002 ms/op
Iteration   3: 3.041 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.033 ±(99.9%) 0.225 ms/op [Average]
  (min, avg, max) = (3.019, 3.033, 3.041), stdev = 0.012
  CI (99.9%): [2.808, 3.258] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.668 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.104 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.003 ±(99.9%) 0.002 ms/op
Iteration   1: 2.869 ±(99.9%) 0.003 ms/op
Iteration   2: 2.948 ±(99.9%) 0.002 ms/op
Iteration   3: 2.878 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.898 ±(99.9%) 0.787 ms/op [Average]
  (min, avg, max) = (2.869, 2.898, 2.948), stdev = 0.043
  CI (99.9%): [2.111, 3.686] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 4.263 ±(99.9%) 0.071 ms/op
# Warmup Iteration   2: 3.200 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.125 ±(99.9%) 0.003 ms/op
Iteration   1: 3.109 ±(99.9%) 0.004 ms/op
Iteration   2: 3.083 ±(99.9%) 0.004 ms/op
Iteration   3: 3.083 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.092 ±(99.9%) 0.269 ms/op [Average]
  (min, avg, max) = (3.083, 3.092, 3.109), stdev = 0.015
  CI (99.9%): [2.823, 3.361] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.223 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.201 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.132 ±(99.9%) 0.012 ms/op
Iteration   1: 4.016 ±(99.9%) 0.007 ms/op
Iteration   2: 3.859 ±(99.9%) 0.007 ms/op
Iteration   3: 4.027 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.967 ±(99.9%) 1.718 ms/op [Average]
  (min, avg, max) = (3.859, 3.967, 4.027), stdev = 0.094
  CI (99.9%): [2.250, 5.685] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.233 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.201 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.119 ±(99.9%) 0.007 ms/op
Iteration   1: 3.076 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.927 ms/op
                 createUser·p0.50:   3.023 ms/op
                 createUser·p0.90:   3.637 ms/op
                 createUser·p0.95:   3.879 ms/op
                 createUser·p0.99:   4.776 ms/op
                 createUser·p0.999:  8.602 ms/op
                 createUser·p0.9999: 18.435 ms/op
                 createUser·p1.00:   18.809 ms/op

Iteration   2: 3.058 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.696 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.554 ms/op
                 createUser·p0.95:   3.785 ms/op
                 createUser·p0.99:   4.719 ms/op
                 createUser·p0.999:  10.643 ms/op
                 createUser·p0.9999: 16.114 ms/op
                 createUser·p1.00:   17.793 ms/op

Iteration   3: 3.050 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.662 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.551 ms/op
                 createUser·p0.95:   3.727 ms/op
                 createUser·p0.99:   4.538 ms/op
                 createUser·p0.999:  12.917 ms/op
                 createUser·p0.9999: 20.185 ms/op
                 createUser·p1.00:   20.480 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 313454
  mean =      3.062 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21176 
    [ 2.500,  5.000) = 290164 
    [ 5.000,  7.500) = 1405 
    [ 7.500, 10.000) = 378 
    [10.000, 12.500) = 91 
    [12.500, 15.000) = 103 
    [15.000, 17.500) = 92 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.662 ms/op
     p(50.0000) =      3.019 ms/op
     p(90.0000) =      3.576 ms/op
     p(95.0000) =      3.801 ms/op
     p(99.0000) =      4.702 ms/op
     p(99.9000) =     10.314 ms/op
     p(99.9900) =     18.339 ms/op
     p(99.9990) =     20.447 ms/op
     p(99.9999) =     20.480 ms/op
    p(100.0000) =     20.480 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.932 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.027 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.970 ±(99.9%) 0.006 ms/op
Iteration   1: 2.979 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.792 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.506 ms/op
                 existUser·p0.95:   3.727 ms/op
                 existUser·p0.99:   4.653 ms/op
                 existUser·p0.999:  9.284 ms/op
                 existUser·p0.9999: 18.424 ms/op
                 existUser·p1.00:   18.940 ms/op

Iteration   2: 2.936 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.793 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.310 ms/op
                 existUser·p0.95:   3.547 ms/op
                 existUser·p0.99:   4.588 ms/op
                 existUser·p0.999:  8.423 ms/op
                 existUser·p0.9999: 19.141 ms/op
                 existUser·p1.00:   20.513 ms/op

Iteration   3: 2.932 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.762 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.338 ms/op
                 existUser·p0.95:   3.535 ms/op
                 existUser·p0.99:   4.481 ms/op
                 existUser·p0.999:  9.519 ms/op
                 existUser·p0.9999: 19.507 ms/op
                 existUser·p1.00:   20.120 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 325246
  mean =      2.949 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 30886 
    [ 2.500,  5.000) = 292489 
    [ 5.000,  7.500) = 1215 
    [ 7.500, 10.000) = 426 
    [10.000, 12.500) = 66 
    [12.500, 15.000) = 4 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 120 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.762 ms/op
     p(50.0000) =      2.908 ms/op
     p(90.0000) =      3.383 ms/op
     p(95.0000) =      3.621 ms/op
     p(99.0000) =      4.588 ms/op
     p(99.9000) =      9.126 ms/op
     p(99.9900) =     19.169 ms/op
     p(99.9990) =     20.144 ms/op
     p(99.9999) =     20.513 ms/op
    p(100.0000) =     20.513 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.520 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.222 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.093 ±(99.9%) 0.007 ms/op
Iteration   1: 3.059 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.754 ms/op
                 getUser·p0.50:   3.015 ms/op
                 getUser·p0.90:   3.576 ms/op
                 getUser·p0.95:   3.912 ms/op
                 getUser·p0.99:   4.932 ms/op
                 getUser·p0.999:  9.175 ms/op
                 getUser·p0.9999: 13.330 ms/op
                 getUser·p1.00:   13.664 ms/op

Iteration   2: 3.072 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.680 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.633 ms/op
                 getUser·p0.95:   3.875 ms/op
                 getUser·p0.99:   4.735 ms/op
                 getUser·p0.999:  8.326 ms/op
                 getUser·p0.9999: 14.964 ms/op
                 getUser·p1.00:   15.286 ms/op

Iteration   3: 3.049 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.833 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.523 ms/op
                 getUser·p0.95:   3.789 ms/op
                 getUser·p0.99:   4.743 ms/op
                 getUser·p0.999:  7.545 ms/op
                 getUser·p0.9999: 17.252 ms/op
                 getUser·p1.00:   17.727 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 313855
  mean =      3.060 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 589 
    [ 1.250,  2.500) = 20811 
    [ 2.500,  3.750) = 271745 
    [ 3.750,  5.000) = 18395 
    [ 5.000,  6.250) = 1333 
    [ 6.250,  7.500) = 435 
    [ 7.500,  8.750) = 215 
    [ 8.750, 10.000) = 124 
    [10.000, 11.250) = 12 
    [11.250, 12.500) = 6 
    [12.500, 13.750) = 67 
    [13.750, 15.000) = 50 
    [15.000, 16.250) = 33 
    [16.250, 17.500) = 36 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.680 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      3.580 ms/op
     p(95.0000) =      3.854 ms/op
     p(99.0000) =      4.833 ms/op
     p(99.9000) =      8.899 ms/op
     p(99.9900) =     16.597 ms/op
     p(99.9990) =     17.587 ms/op
     p(99.9999) =     17.727 ms/op
    p(100.0000) =     17.727 ms/op


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
# Warmup Iteration   1: 5.339 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.212 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.043 ±(99.9%) 0.011 ms/op
Iteration   1: 4.070 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.294 ms/op
                 listUser·p0.50:   3.879 ms/op
                 listUser·p0.90:   5.186 ms/op
                 listUser·p0.95:   6.005 ms/op
                 listUser·p0.99:   7.340 ms/op
                 listUser·p0.999:  14.467 ms/op
                 listUser·p0.9999: 17.727 ms/op
                 listUser·p1.00:   17.924 ms/op

Iteration   2: 4.038 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.553 ms/op
                 listUser·p0.50:   3.842 ms/op
                 listUser·p0.90:   5.087 ms/op
                 listUser·p0.95:   5.726 ms/op
                 listUser·p0.99:   7.373 ms/op
                 listUser·p0.999:  17.334 ms/op
                 listUser·p0.9999: 21.963 ms/op
                 listUser·p1.00:   22.446 ms/op

Iteration   3: 4.072 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.957 ms/op
                 listUser·p0.50:   3.883 ms/op
                 listUser·p0.90:   5.194 ms/op
                 listUser·p0.95:   5.980 ms/op
                 listUser·p0.99:   7.315 ms/op
                 listUser·p0.999:  16.728 ms/op
                 listUser·p0.9999: 18.579 ms/op
                 listUser·p1.00:   19.005 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 236435
  mean =      4.060 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2567 
    [ 2.500,  5.000) = 206297 
    [ 5.000,  7.500) = 25497 
    [ 7.500, 10.000) = 1507 
    [10.000, 12.500) = 139 
    [12.500, 15.000) = 136 
    [15.000, 17.500) = 176 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 52 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.553 ms/op
     p(50.0000) =      3.867 ms/op
     p(90.0000) =      5.153 ms/op
     p(95.0000) =      5.915 ms/op
     p(99.0000) =      7.348 ms/op
     p(99.9000) =     15.771 ms/op
     p(99.9900) =     20.513 ms/op
     p(99.9990) =     22.324 ms/op
     p(99.9999) =     22.446 ms/op
    p(100.0000) =     22.446 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.434 ± 3.803  ops/ms
ClientGrpc.existUser                       thrpt       3  11.084 ± 2.947  ops/ms
ClientGrpc.getUser                         thrpt       3  10.369 ± 1.688  ops/ms
ClientGrpc.listUser                        thrpt       3   7.893 ± 1.717  ops/ms
ClientGrpc.createUser                       avgt       3   3.033 ± 0.225   ms/op
ClientGrpc.existUser                        avgt       3   2.898 ± 0.787   ms/op
ClientGrpc.getUser                          avgt       3   3.092 ± 0.269   ms/op
ClientGrpc.listUser                         avgt       3   3.967 ± 1.718   ms/op
ClientGrpc.createUser                     sample  313454   3.062 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.662           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.019           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.576           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.801           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.702           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.314           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.339           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.480           ms/op
ClientGrpc.existUser                      sample  325246   2.949 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.762           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.908           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.383           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.621           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.588           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.126           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.169           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.513           ms/op
ClientGrpc.getUser                        sample  313855   3.060 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.680           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.023           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.580           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.854           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.833           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.899           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.597           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.727           ms/op
ClientGrpc.listUser                       sample  236435   4.060 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.553           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.867           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.153           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.915           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.348           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.771           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.513           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.446           ms/op
