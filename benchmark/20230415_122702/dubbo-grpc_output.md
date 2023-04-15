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
# Warmup Iteration   1: 4.790 ops/ms
# Warmup Iteration   2: 9.116 ops/ms
# Warmup Iteration   3: 10.407 ops/ms
Iteration   1: 10.540 ops/ms
Iteration   2: 10.722 ops/ms
Iteration   3: 10.659 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.640 ±(99.9%) 1.689 ops/ms [Average]
  (min, avg, max) = (10.540, 10.640, 10.722), stdev = 0.093
  CI (99.9%): [8.951, 12.329] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.861 ops/ms
# Warmup Iteration   2: 10.968 ops/ms
# Warmup Iteration   3: 11.651 ops/ms
Iteration   1: 11.198 ops/ms
Iteration   2: 11.261 ops/ms
Iteration   3: 10.962 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.140 ±(99.9%) 2.871 ops/ms [Average]
  (min, avg, max) = (10.962, 11.140, 11.261), stdev = 0.157
  CI (99.9%): [8.269, 14.011] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.269 ops/ms
# Warmup Iteration   2: 10.463 ops/ms
# Warmup Iteration   3: 10.696 ops/ms
Iteration   1: 10.799 ops/ms
Iteration   2: 10.824 ops/ms
Iteration   3: 10.894 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.839 ±(99.9%) 0.895 ops/ms [Average]
  (min, avg, max) = (10.799, 10.839, 10.894), stdev = 0.049
  CI (99.9%): [9.944, 11.735] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.758 ops/ms
# Warmup Iteration   2: 7.922 ops/ms
# Warmup Iteration   3: 8.135 ops/ms
Iteration   1: 8.328 ops/ms
Iteration   2: 8.200 ops/ms
Iteration   3: 8.245 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.258 ±(99.9%) 1.191 ops/ms [Average]
  (min, avg, max) = (8.200, 8.258, 8.328), stdev = 0.065
  CI (99.9%): [7.067, 9.449] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 3.937 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.116 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.980 ±(99.9%) 0.002 ms/op
Iteration   1: 2.946 ±(99.9%) 0.003 ms/op
Iteration   2: 2.961 ±(99.9%) 0.002 ms/op
Iteration   3: 2.961 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.956 ±(99.9%) 0.158 ms/op [Average]
  (min, avg, max) = (2.946, 2.956, 2.961), stdev = 0.009
  CI (99.9%): [2.798, 3.114] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.390 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.942 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.745 ±(99.9%) 0.005 ms/op
Iteration   1: 2.840 ±(99.9%) 0.003 ms/op
Iteration   2: 2.816 ±(99.9%) 0.003 ms/op
Iteration   3: 2.878 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.844 ±(99.9%) 0.569 ms/op [Average]
  (min, avg, max) = (2.816, 2.844, 2.878), stdev = 0.031
  CI (99.9%): [2.275, 3.413] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.777 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.052 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.964 ±(99.9%) 0.003 ms/op
Iteration   1: 2.958 ±(99.9%) 0.003 ms/op
Iteration   2: 2.929 ±(99.9%) 0.004 ms/op
Iteration   3: 2.969 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.952 ±(99.9%) 0.376 ms/op [Average]
  (min, avg, max) = (2.929, 2.952, 2.969), stdev = 0.021
  CI (99.9%): [2.576, 3.328] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.464 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 4.086 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.934 ±(99.9%) 0.014 ms/op
Iteration   1: 3.870 ±(99.9%) 0.011 ms/op
Iteration   2: 3.935 ±(99.9%) 0.030 ms/op
Iteration   3: 3.871 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.892 ±(99.9%) 0.672 ms/op [Average]
  (min, avg, max) = (3.870, 3.892, 3.935), stdev = 0.037
  CI (99.9%): [3.220, 4.564] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.974 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.110 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.976 ±(99.9%) 0.006 ms/op
Iteration   1: 2.919 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.779 ms/op
                 createUser·p0.50:   2.925 ms/op
                 createUser·p0.90:   3.334 ms/op
                 createUser·p0.95:   3.621 ms/op
                 createUser·p0.99:   4.579 ms/op
                 createUser·p0.999:  6.914 ms/op
                 createUser·p0.9999: 17.073 ms/op
                 createUser·p1.00:   17.269 ms/op

Iteration   2: 2.982 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.672 ms/op
                 createUser·p0.50:   2.953 ms/op
                 createUser·p0.90:   3.535 ms/op
                 createUser·p0.95:   3.752 ms/op
                 createUser·p0.99:   4.358 ms/op
                 createUser·p0.999:  8.874 ms/op
                 createUser·p0.9999: 18.153 ms/op
                 createUser·p1.00:   18.481 ms/op

Iteration   3: 2.944 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.674 ms/op
                 createUser·p0.50:   2.941 ms/op
                 createUser·p0.90:   3.416 ms/op
                 createUser·p0.95:   3.666 ms/op
                 createUser·p0.99:   4.383 ms/op
                 createUser·p0.999:  10.139 ms/op
                 createUser·p0.9999: 17.542 ms/op
                 createUser·p1.00:   18.514 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 325560
  mean =      2.948 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1607 
    [ 1.250,  2.500) = 33585 
    [ 2.500,  3.750) = 276314 
    [ 3.750,  5.000) = 12756 
    [ 5.000,  6.250) = 685 
    [ 6.250,  7.500) = 210 
    [ 7.500,  8.750) = 97 
    [ 8.750, 10.000) = 35 
    [10.000, 11.250) = 33 
    [11.250, 12.500) = 61 
    [12.500, 13.750) = 31 
    [13.750, 15.000) = 48 
    [15.000, 16.250) = 7 
    [16.250, 17.500) = 49 
    [17.500, 18.750) = 42 

  Percentiles, ms/op:
      p(0.0000) =      0.672 ms/op
     p(50.0000) =      2.937 ms/op
     p(90.0000) =      3.441 ms/op
     p(95.0000) =      3.690 ms/op
     p(99.0000) =      4.448 ms/op
     p(99.9000) =      8.326 ms/op
     p(99.9900) =     18.022 ms/op
     p(99.9990) =     18.407 ms/op
     p(99.9999) =     18.514 ms/op
    p(100.0000) =     18.514 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.742 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 2.857 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.874 ±(99.9%) 0.006 ms/op
Iteration   1: 2.887 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.651 ms/op
                 existUser·p0.50:   2.863 ms/op
                 existUser·p0.90:   3.375 ms/op
                 existUser·p0.95:   3.576 ms/op
                 existUser·p0.99:   4.514 ms/op
                 existUser·p0.999:  6.793 ms/op
                 existUser·p0.9999: 12.745 ms/op
                 existUser·p1.00:   13.091 ms/op

Iteration   2: 2.819 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.546 ms/op
                 existUser·p0.50:   2.839 ms/op
                 existUser·p0.90:   3.342 ms/op
                 existUser·p0.95:   3.568 ms/op
                 existUser·p0.99:   4.268 ms/op
                 existUser·p0.999:  5.862 ms/op
                 existUser·p0.9999: 21.604 ms/op
                 existUser·p1.00:   22.184 ms/op

Iteration   3: 2.897 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.603 ms/op
                 existUser·p0.50:   2.888 ms/op
                 existUser·p0.90:   3.437 ms/op
                 existUser·p0.95:   3.613 ms/op
                 existUser·p0.99:   4.276 ms/op
                 existUser·p0.999:  7.318 ms/op
                 existUser·p0.9999: 17.465 ms/op
                 existUser·p1.00:   17.826 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 334600
  mean =      2.867 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 51422 
    [ 2.500,  5.000) = 282033 
    [ 5.000,  7.500) = 945 
    [ 7.500, 10.000) = 40 
    [10.000, 12.500) = 41 
    [12.500, 15.000) = 23 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.546 ms/op
     p(50.0000) =      2.863 ms/op
     p(90.0000) =      3.387 ms/op
     p(95.0000) =      3.592 ms/op
     p(99.0000) =      4.375 ms/op
     p(99.9000) =      6.521 ms/op
     p(99.9900) =     17.826 ms/op
     p(99.9990) =     21.997 ms/op
     p(99.9999) =     22.184 ms/op
    p(100.0000) =     22.184 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.075 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.044 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.964 ±(99.9%) 0.006 ms/op
Iteration   1: 2.951 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.524 ms/op
                 getUser·p0.50:   2.945 ms/op
                 getUser·p0.90:   3.482 ms/op
                 getUser·p0.95:   3.801 ms/op
                 getUser·p0.99:   4.481 ms/op
                 getUser·p0.999:  7.217 ms/op
                 getUser·p0.9999: 11.291 ms/op
                 getUser·p1.00:   11.583 ms/op

Iteration   2: 2.999 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.763 ms/op
                 getUser·p0.50:   2.982 ms/op
                 getUser·p0.90:   3.547 ms/op
                 getUser·p0.95:   3.752 ms/op
                 getUser·p0.99:   4.243 ms/op
                 getUser·p0.999:  5.936 ms/op
                 getUser·p0.9999: 12.583 ms/op
                 getUser·p1.00:   12.861 ms/op

Iteration   3: 2.967 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.757 ms/op
                 getUser·p0.50:   2.953 ms/op
                 getUser·p0.90:   3.502 ms/op
                 getUser·p0.95:   3.772 ms/op
                 getUser·p0.99:   4.358 ms/op
                 getUser·p0.999:  7.945 ms/op
                 getUser·p0.9999: 18.252 ms/op
                 getUser·p1.00:   20.152 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 323026
  mean =      2.972 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31340 
    [ 2.500,  5.000) = 290427 
    [ 5.000,  7.500) = 998 
    [ 7.500, 10.000) = 101 
    [10.000, 12.500) = 80 
    [12.500, 15.000) = 36 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.524 ms/op
     p(50.0000) =      2.961 ms/op
     p(90.0000) =      3.510 ms/op
     p(95.0000) =      3.768 ms/op
     p(99.0000) =      4.358 ms/op
     p(99.9000) =      7.053 ms/op
     p(99.9900) =     15.740 ms/op
     p(99.9990) =     19.338 ms/op
     p(99.9999) =     20.152 ms/op
    p(100.0000) =     20.152 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.062 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.974 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.873 ±(99.9%) 0.011 ms/op
Iteration   1: 3.890 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.281 ms/op
                 listUser·p0.50:   3.760 ms/op
                 listUser·p0.90:   4.932 ms/op
                 listUser·p0.95:   5.546 ms/op
                 listUser·p0.99:   6.611 ms/op
                 listUser·p0.999:  12.563 ms/op
                 listUser·p0.9999: 15.654 ms/op
                 listUser·p1.00:   17.629 ms/op

Iteration   2: 3.868 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.916 ms/op
                 listUser·p0.50:   3.736 ms/op
                 listUser·p0.90:   4.719 ms/op
                 listUser·p0.95:   5.702 ms/op
                 listUser·p0.99:   6.619 ms/op
                 listUser·p0.999:  13.605 ms/op
                 listUser·p0.9999: 19.151 ms/op
                 listUser·p1.00:   19.497 ms/op

Iteration   3: 3.857 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.087 ms/op
                 listUser·p0.50:   3.707 ms/op
                 listUser·p0.90:   5.186 ms/op
                 listUser·p0.95:   5.865 ms/op
                 listUser·p0.99:   6.838 ms/op
                 listUser·p0.999:  14.647 ms/op
                 listUser·p0.9999: 26.238 ms/op
                 listUser·p1.00:   26.542 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 247926
  mean =      3.872 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9294 
    [ 2.500,  5.000) = 215200 
    [ 5.000,  7.500) = 22201 
    [ 7.500, 10.000) = 714 
    [10.000, 12.500) = 159 
    [12.500, 15.000) = 210 
    [15.000, 17.500) = 64 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.281 ms/op
     p(50.0000) =      3.736 ms/op
     p(90.0000) =      4.923 ms/op
     p(95.0000) =      5.710 ms/op
     p(99.0000) =      6.676 ms/op
     p(99.9000) =     13.321 ms/op
     p(99.9900) =     25.723 ms/op
     p(99.9990) =     26.448 ms/op
     p(99.9999) =     26.542 ms/op
    p(100.0000) =     26.542 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.640 ± 1.689  ops/ms
ClientGrpc.existUser                       thrpt       3  11.140 ± 2.871  ops/ms
ClientGrpc.getUser                         thrpt       3  10.839 ± 0.895  ops/ms
ClientGrpc.listUser                        thrpt       3   8.258 ± 1.191  ops/ms
ClientGrpc.createUser                       avgt       3   2.956 ± 0.158   ms/op
ClientGrpc.existUser                        avgt       3   2.844 ± 0.569   ms/op
ClientGrpc.getUser                          avgt       3   2.952 ± 0.376   ms/op
ClientGrpc.listUser                         avgt       3   3.892 ± 0.672   ms/op
ClientGrpc.createUser                     sample  325560   2.948 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.672           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.937           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.441           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.690           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.448           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.326           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.022           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.514           ms/op
ClientGrpc.existUser                      sample  334600   2.867 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.546           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.863           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.387           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.592           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.375           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.521           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.826           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.184           ms/op
ClientGrpc.getUser                        sample  323026   2.972 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.524           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.961           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.510           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.768           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.358           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.053           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.740           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.152           ms/op
ClientGrpc.listUser                       sample  247926   3.872 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.281           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.736           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.923           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.710           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.676           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.321           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.723           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.542           ms/op
