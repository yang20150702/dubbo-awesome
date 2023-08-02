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
# Warmup Iteration   1: 4.828 ops/ms
# Warmup Iteration   2: 9.312 ops/ms
# Warmup Iteration   3: 10.299 ops/ms
Iteration   1: 10.533 ops/ms
Iteration   2: 10.826 ops/ms
Iteration   3: 10.752 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.703 ±(99.9%) 2.777 ops/ms [Average]
  (min, avg, max) = (10.533, 10.703, 10.826), stdev = 0.152
  CI (99.9%): [7.927, 13.480] (assumes normal distribution)


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
# Warmup Iteration   1: 7.846 ops/ms
# Warmup Iteration   2: 10.919 ops/ms
# Warmup Iteration   3: 11.235 ops/ms
Iteration   1: 11.222 ops/ms
Iteration   2: 11.302 ops/ms
Iteration   3: 11.303 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.275 ±(99.9%) 0.842 ops/ms [Average]
  (min, avg, max) = (11.222, 11.275, 11.303), stdev = 0.046
  CI (99.9%): [10.433, 12.118] (assumes normal distribution)


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
# Warmup Iteration   1: 7.914 ops/ms
# Warmup Iteration   2: 10.460 ops/ms
# Warmup Iteration   3: 10.685 ops/ms
Iteration   1: 10.704 ops/ms
Iteration   2: 10.636 ops/ms
Iteration   3: 10.835 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.725 ±(99.9%) 1.847 ops/ms [Average]
  (min, avg, max) = (10.636, 10.725, 10.835), stdev = 0.101
  CI (99.9%): [8.878, 12.573] (assumes normal distribution)


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
# Warmup Iteration   1: 6.322 ops/ms
# Warmup Iteration   2: 7.811 ops/ms
# Warmup Iteration   3: 8.461 ops/ms
Iteration   1: 8.098 ops/ms
Iteration   2: 8.054 ops/ms
Iteration   3: 8.050 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.067 ±(99.9%) 0.488 ops/ms [Average]
  (min, avg, max) = (8.050, 8.067, 8.098), stdev = 0.027
  CI (99.9%): [7.579, 8.555] (assumes normal distribution)


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
# Warmup Iteration   1: 3.999 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.060 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.013 ±(99.9%) 0.003 ms/op
Iteration   1: 2.961 ±(99.9%) 0.004 ms/op
Iteration   2: 2.998 ±(99.9%) 0.004 ms/op
Iteration   3: 3.015 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.991 ±(99.9%) 0.503 ms/op [Average]
  (min, avg, max) = (2.961, 2.991, 3.015), stdev = 0.028
  CI (99.9%): [2.489, 3.494] (assumes normal distribution)


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
# Warmup Iteration   1: 3.514 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.944 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.841 ±(99.9%) 0.003 ms/op
Iteration   1: 2.847 ±(99.9%) 0.004 ms/op
Iteration   2: 2.895 ±(99.9%) 0.003 ms/op
Iteration   3: 2.965 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.902 ±(99.9%) 1.075 ms/op [Average]
  (min, avg, max) = (2.847, 2.902, 2.965), stdev = 0.059
  CI (99.9%): [1.827, 3.977] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.335 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.159 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.966 ±(99.9%) 0.003 ms/op
Iteration   1: 3.026 ±(99.9%) 0.002 ms/op
Iteration   2: 2.982 ±(99.9%) 0.003 ms/op
Iteration   3: 2.979 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.996 ±(99.9%) 0.484 ms/op [Average]
  (min, avg, max) = (2.979, 2.996, 3.026), stdev = 0.027
  CI (99.9%): [2.512, 3.479] (assumes normal distribution)


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
# Warmup Iteration   1: 4.623 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 4.034 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 3.941 ±(99.9%) 0.025 ms/op
Iteration   1: 3.937 ±(99.9%) 0.022 ms/op
Iteration   2: 3.925 ±(99.9%) 0.013 ms/op
Iteration   3: 3.811 ±(99.9%) 0.029 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.891 ±(99.9%) 1.269 ms/op [Average]
  (min, avg, max) = (3.811, 3.891, 3.937), stdev = 0.070
  CI (99.9%): [2.621, 5.160] (assumes normal distribution)


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
# Warmup Iteration   1: 3.804 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.111 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.080 ±(99.9%) 0.007 ms/op
Iteration   1: 2.967 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.583 ms/op
                 createUser·p0.50:   2.953 ms/op
                 createUser·p0.90:   3.391 ms/op
                 createUser·p0.95:   3.629 ms/op
                 createUser·p0.99:   4.407 ms/op
                 createUser·p0.999:  8.034 ms/op
                 createUser·p0.9999: 18.743 ms/op
                 createUser·p1.00:   19.235 ms/op

Iteration   2: 2.964 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.689 ms/op
                 createUser·p0.50:   2.941 ms/op
                 createUser·p0.90:   3.551 ms/op
                 createUser·p0.95:   3.826 ms/op
                 createUser·p0.99:   4.637 ms/op
                 createUser·p0.999:  7.958 ms/op
                 createUser·p0.9999: 29.793 ms/op
                 createUser·p1.00:   30.048 ms/op

Iteration   3: 3.051 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.577 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.617 ms/op
                 createUser·p0.95:   3.822 ms/op
                 createUser·p0.99:   4.497 ms/op
                 createUser·p0.999:  10.355 ms/op
                 createUser·p0.9999: 17.875 ms/op
                 createUser·p1.00:   19.595 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 320678
  mean =      2.993 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31158 
    [ 2.500,  5.000) = 287682 
    [ 5.000,  7.500) = 1394 
    [ 7.500, 10.000) = 195 
    [10.000, 12.500) = 25 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 71 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 29 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.577 ms/op
     p(50.0000) =      2.966 ms/op
     p(90.0000) =      3.531 ms/op
     p(95.0000) =      3.777 ms/op
     p(99.0000) =      4.538 ms/op
     p(99.9000) =      8.946 ms/op
     p(99.9900) =     28.667 ms/op
     p(99.9990) =     30.002 ms/op
     p(99.9999) =     30.048 ms/op
    p(100.0000) =     30.048 ms/op


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
# Warmup Iteration   1: 3.771 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.006 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.917 ±(99.9%) 0.006 ms/op
Iteration   1: 2.943 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.748 ms/op
                 existUser·p0.50:   2.916 ms/op
                 existUser·p0.90:   3.428 ms/op
                 existUser·p0.95:   3.613 ms/op
                 existUser·p0.99:   4.243 ms/op
                 existUser·p0.999:  9.093 ms/op
                 existUser·p0.9999: 11.637 ms/op
                 existUser·p1.00:   12.255 ms/op

Iteration   2: 2.868 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.638 ms/op
                 existUser·p0.50:   2.867 ms/op
                 existUser·p0.90:   3.219 ms/op
                 existUser·p0.95:   3.342 ms/op
                 existUser·p0.99:   4.202 ms/op
                 existUser·p0.999:  8.650 ms/op
                 existUser·p0.9999: 16.499 ms/op
                 existUser·p1.00:   19.399 ms/op

Iteration   3: 2.882 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.540 ms/op
                 existUser·p0.50:   2.867 ms/op
                 existUser·p0.90:   3.445 ms/op
                 existUser·p0.95:   3.678 ms/op
                 existUser·p0.99:   4.563 ms/op
                 existUser·p0.999:  9.028 ms/op
                 existUser·p0.9999: 16.122 ms/op
                 existUser·p1.00:   16.564 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 331219
  mean =      2.897 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2456 
    [ 1.250,  2.500) = 38301 
    [ 2.500,  3.750) = 281183 
    [ 3.750,  5.000) = 7605 
    [ 5.000,  6.250) = 572 
    [ 6.250,  7.500) = 437 
    [ 7.500,  8.750) = 263 
    [ 8.750, 10.000) = 195 
    [10.000, 11.250) = 53 
    [11.250, 12.500) = 27 
    [12.500, 13.750) = 39 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 36 
    [16.250, 17.500) = 27 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.540 ms/op
     p(50.0000) =      2.884 ms/op
     p(90.0000) =      3.355 ms/op
     p(95.0000) =      3.584 ms/op
     p(99.0000) =      4.391 ms/op
     p(99.9000) =      8.995 ms/op
     p(99.9900) =     16.218 ms/op
     p(99.9990) =     17.895 ms/op
     p(99.9999) =     19.399 ms/op
    p(100.0000) =     19.399 ms/op


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
# Warmup Iteration   1: 4.204 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.068 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.975 ±(99.9%) 0.007 ms/op
Iteration   1: 3.009 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.681 ms/op
                 getUser·p0.50:   2.978 ms/op
                 getUser·p0.90:   3.523 ms/op
                 getUser·p0.95:   3.752 ms/op
                 getUser·p0.99:   4.391 ms/op
                 getUser·p0.999:  9.355 ms/op
                 getUser·p0.9999: 17.105 ms/op
                 getUser·p1.00:   17.138 ms/op

Iteration   2: 2.963 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.768 ms/op
                 getUser·p0.50:   2.945 ms/op
                 getUser·p0.90:   3.482 ms/op
                 getUser·p0.95:   3.760 ms/op
                 getUser·p0.99:   4.456 ms/op
                 getUser·p0.999:  8.405 ms/op
                 getUser·p0.9999: 17.308 ms/op
                 getUser·p1.00:   17.662 ms/op

Iteration   3: 3.008 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.722 ms/op
                 getUser·p0.50:   2.994 ms/op
                 getUser·p0.90:   3.486 ms/op
                 getUser·p0.95:   3.707 ms/op
                 getUser·p0.99:   4.243 ms/op
                 getUser·p0.999:  7.807 ms/op
                 getUser·p0.9999: 23.637 ms/op
                 getUser·p1.00:   23.724 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 320629
  mean =      2.993 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28498 
    [ 2.500,  5.000) = 290695 
    [ 5.000,  7.500) = 960 
    [ 7.500, 10.000) = 260 
    [10.000, 12.500) = 43 
    [12.500, 15.000) = 67 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.681 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.502 ms/op
     p(95.0000) =      3.740 ms/op
     p(99.0000) =      4.358 ms/op
     p(99.9000) =      8.503 ms/op
     p(99.9900) =     21.115 ms/op
     p(99.9990) =     23.724 ms/op
     p(99.9999) =     23.724 ms/op
    p(100.0000) =     23.724 ms/op


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
# Warmup Iteration   1: 4.501 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.033 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.947 ±(99.9%) 0.010 ms/op
Iteration   1: 3.966 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.180 ms/op
                 listUser·p0.50:   3.826 ms/op
                 listUser·p0.90:   4.882 ms/op
                 listUser·p0.95:   5.743 ms/op
                 listUser·p0.99:   7.102 ms/op
                 listUser·p0.999:  12.743 ms/op
                 listUser·p0.9999: 14.188 ms/op
                 listUser·p1.00:   16.138 ms/op

Iteration   2: 3.869 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.857 ms/op
                 listUser·p0.50:   3.736 ms/op
                 listUser·p0.90:   4.899 ms/op
                 listUser·p0.95:   5.513 ms/op
                 listUser·p0.99:   6.939 ms/op
                 listUser·p0.999:  13.654 ms/op
                 listUser·p0.9999: 21.937 ms/op
                 listUser·p1.00:   22.446 ms/op

Iteration   3: 3.834 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.071 ms/op
                 listUser·p0.50:   3.699 ms/op
                 listUser·p0.90:   4.391 ms/op
                 listUser·p0.95:   5.341 ms/op
                 listUser·p0.99:   6.906 ms/op
                 listUser·p0.999:  15.675 ms/op
                 listUser·p0.9999: 26.608 ms/op
                 listUser·p1.00:   27.787 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 246682
  mean =      3.889 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4191 
    [ 2.500,  5.000) = 222728 
    [ 5.000,  7.500) = 18127 
    [ 7.500, 10.000) = 1126 
    [10.000, 12.500) = 157 
    [12.500, 15.000) = 193 
    [15.000, 17.500) = 60 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 55 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.857 ms/op
     p(50.0000) =      3.756 ms/op
     p(90.0000) =      4.751 ms/op
     p(95.0000) =      5.554 ms/op
     p(99.0000) =      6.996 ms/op
     p(99.9000) =     13.566 ms/op
     p(99.9900) =     25.035 ms/op
     p(99.9990) =     27.757 ms/op
     p(99.9999) =     27.787 ms/op
    p(100.0000) =     27.787 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.703 ± 2.777  ops/ms
ClientGrpc.existUser                       thrpt       3  11.275 ± 0.842  ops/ms
ClientGrpc.getUser                         thrpt       3  10.725 ± 1.847  ops/ms
ClientGrpc.listUser                        thrpt       3   8.067 ± 0.488  ops/ms
ClientGrpc.createUser                       avgt       3   2.991 ± 0.503   ms/op
ClientGrpc.existUser                        avgt       3   2.902 ± 1.075   ms/op
ClientGrpc.getUser                          avgt       3   2.996 ± 0.484   ms/op
ClientGrpc.listUser                         avgt       3   3.891 ± 1.269   ms/op
ClientGrpc.createUser                     sample  320678   2.993 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.577           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.966           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.531           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.777           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.538           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.946           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          28.667           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          30.048           ms/op
ClientGrpc.existUser                      sample  331219   2.897 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.540           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.884           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.355           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.584           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.391           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.995           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.218           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.399           ms/op
ClientGrpc.getUser                        sample  320629   2.993 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.681           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.974           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.502           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.740           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.358           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.503           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.115           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.724           ms/op
ClientGrpc.listUser                       sample  246682   3.889 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.857           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.756           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.751           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.554           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.996           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.566           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.035           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.787           ms/op
