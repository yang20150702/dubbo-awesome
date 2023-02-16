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
# Warmup Iteration   1: 2.868 ops/ms
# Warmup Iteration   2: 6.493 ops/ms
# Warmup Iteration   3: 7.934 ops/ms
Iteration   1: 8.210 ops/ms
Iteration   2: 8.201 ops/ms
Iteration   3: 8.656 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.356 ±(99.9%) 4.750 ops/ms [Average]
  (min, avg, max) = (8.201, 8.356, 8.656), stdev = 0.260
  CI (99.9%): [3.606, 13.106] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 5.827 ops/ms
# Warmup Iteration   2: 8.427 ops/ms
# Warmup Iteration   3: 8.431 ops/ms
Iteration   1: 8.761 ops/ms
Iteration   2: 8.813 ops/ms
Iteration   3: 8.631 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.735 ±(99.9%) 1.710 ops/ms [Average]
  (min, avg, max) = (8.631, 8.735, 8.813), stdev = 0.094
  CI (99.9%): [7.025, 10.445] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.416 ops/ms
# Warmup Iteration   2: 8.115 ops/ms
# Warmup Iteration   3: 8.100 ops/ms
Iteration   1: 8.114 ops/ms
Iteration   2: 8.255 ops/ms
Iteration   3: 8.128 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.166 ±(99.9%) 1.419 ops/ms [Average]
  (min, avg, max) = (8.114, 8.166, 8.255), stdev = 0.078
  CI (99.9%): [6.747, 9.585] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 4.443 ops/ms
# Warmup Iteration   2: 6.497 ops/ms
# Warmup Iteration   3: 6.535 ops/ms
Iteration   1: 6.662 ops/ms
Iteration   2: 6.972 ops/ms
Iteration   3: 6.440 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.691 ±(99.9%) 4.880 ops/ms [Average]
  (min, avg, max) = (6.440, 6.691, 6.972), stdev = 0.267
  CI (99.9%): [1.811, 11.572] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 5.295 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 4.041 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.923 ±(99.9%) 0.005 ms/op
Iteration   1: 3.805 ±(99.9%) 0.005 ms/op
Iteration   2: 3.792 ±(99.9%) 0.002 ms/op
Iteration   3: 3.635 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.744 ±(99.9%) 1.721 ms/op [Average]
  (min, avg, max) = (3.635, 3.744, 3.805), stdev = 0.094
  CI (99.9%): [2.023, 5.465] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 5.193 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.746 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.663 ±(99.9%) 0.006 ms/op
Iteration   1: 3.619 ±(99.9%) 0.004 ms/op
Iteration   2: 3.532 ±(99.9%) 0.004 ms/op
Iteration   3: 3.561 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.571 ±(99.9%) 0.810 ms/op [Average]
  (min, avg, max) = (3.532, 3.571, 3.619), stdev = 0.044
  CI (99.9%): [2.761, 4.381] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.218 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 4.032 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.844 ±(99.9%) 0.004 ms/op
Iteration   1: 3.929 ±(99.9%) 0.003 ms/op
Iteration   2: 3.867 ±(99.9%) 0.004 ms/op
Iteration   3: 3.891 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.895 ±(99.9%) 0.577 ms/op [Average]
  (min, avg, max) = (3.867, 3.895, 3.929), stdev = 0.032
  CI (99.9%): [3.319, 4.472] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 7.223 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.999 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 4.904 ±(99.9%) 0.007 ms/op
Iteration   1: 4.989 ±(99.9%) 0.009 ms/op
Iteration   2: 4.908 ±(99.9%) 0.033 ms/op
Iteration   3: 4.973 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.957 ±(99.9%) 0.786 ms/op [Average]
  (min, avg, max) = (4.908, 4.957, 4.989), stdev = 0.043
  CI (99.9%): [4.171, 5.743] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.959 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 4.086 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.909 ±(99.9%) 0.011 ms/op
Iteration   1: 3.808 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.843 ms/op
                 createUser·p0.50:   3.756 ms/op
                 createUser·p0.90:   4.653 ms/op
                 createUser·p0.95:   4.973 ms/op
                 createUser·p0.99:   6.382 ms/op
                 createUser·p0.999:  12.880 ms/op
                 createUser·p0.9999: 15.588 ms/op
                 createUser·p1.00:   16.548 ms/op

Iteration   2: 3.818 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.745 ms/op
                 createUser·p0.50:   3.723 ms/op
                 createUser·p0.90:   4.686 ms/op
                 createUser·p0.95:   5.046 ms/op
                 createUser·p0.99:   6.652 ms/op
                 createUser·p0.999:  14.008 ms/op
                 createUser·p0.9999: 19.108 ms/op
                 createUser·p1.00:   19.431 ms/op

Iteration   3: 3.842 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.795 ms/op
                 createUser·p0.50:   3.789 ms/op
                 createUser·p0.90:   4.710 ms/op
                 createUser·p0.95:   4.989 ms/op
                 createUser·p0.99:   5.800 ms/op
                 createUser·p0.999:  17.424 ms/op
                 createUser·p0.9999: 20.972 ms/op
                 createUser·p1.00:   21.004 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 250971
  mean =      3.823 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8249 
    [ 2.500,  5.000) = 230163 
    [ 5.000,  7.500) = 11364 
    [ 7.500, 10.000) = 750 
    [10.000, 12.500) = 69 
    [12.500, 15.000) = 190 
    [15.000, 17.500) = 96 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.745 ms/op
     p(50.0000) =      3.756 ms/op
     p(90.0000) =      4.686 ms/op
     p(95.0000) =      5.005 ms/op
     p(99.0000) =      6.212 ms/op
     p(99.9000) =     14.107 ms/op
     p(99.9900) =     20.673 ms/op
     p(99.9990) =     21.004 ms/op
     p(99.9999) =     21.004 ms/op
    p(100.0000) =     21.004 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.082 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.780 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.769 ±(99.9%) 0.011 ms/op
Iteration   1: 3.614 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.911 ms/op
                 existUser·p0.50:   3.613 ms/op
                 existUser·p0.90:   4.481 ms/op
                 existUser·p0.95:   4.768 ms/op
                 existUser·p0.99:   6.177 ms/op
                 existUser·p0.999:  14.197 ms/op
                 existUser·p0.9999: 17.760 ms/op
                 existUser·p1.00:   17.826 ms/op

Iteration   2: 3.572 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.009 ms/op
                 existUser·p0.50:   3.555 ms/op
                 existUser·p0.90:   4.260 ms/op
                 existUser·p0.95:   4.522 ms/op
                 existUser·p0.99:   5.620 ms/op
                 existUser·p0.999:  9.093 ms/op
                 existUser·p0.9999: 15.469 ms/op
                 existUser·p1.00:   16.384 ms/op

Iteration   3: 3.686 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.756 ms/op
                 existUser·p0.50:   3.625 ms/op
                 existUser·p0.90:   4.530 ms/op
                 existUser·p0.95:   4.784 ms/op
                 existUser·p0.99:   5.670 ms/op
                 existUser·p0.999:  9.110 ms/op
                 existUser·p0.9999: 21.320 ms/op
                 existUser·p1.00:   21.889 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 264874
  mean =      3.624 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13412 
    [ 2.500,  5.000) = 244463 
    [ 5.000,  7.500) = 6159 
    [ 7.500, 10.000) = 581 
    [10.000, 12.500) = 59 
    [12.500, 15.000) = 89 
    [15.000, 17.500) = 57 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.756 ms/op
     p(50.0000) =      3.596 ms/op
     p(90.0000) =      4.432 ms/op
     p(95.0000) =      4.710 ms/op
     p(99.0000) =      5.874 ms/op
     p(99.9000) =      9.554 ms/op
     p(99.9900) =     20.048 ms/op
     p(99.9990) =     21.781 ms/op
     p(99.9999) =     21.889 ms/op
    p(100.0000) =     21.889 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.287 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.970 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.859 ±(99.9%) 0.010 ms/op
Iteration   1: 3.821 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.839 ms/op
                 getUser·p0.50:   3.731 ms/op
                 getUser·p0.90:   4.637 ms/op
                 getUser·p0.95:   5.030 ms/op
                 getUser·p0.99:   6.324 ms/op
                 getUser·p0.999:  11.282 ms/op
                 getUser·p0.9999: 21.713 ms/op
                 getUser·p1.00:   22.118 ms/op

Iteration   2: 3.852 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.085 ms/op
                 getUser·p0.50:   3.797 ms/op
                 getUser·p0.90:   4.727 ms/op
                 getUser·p0.95:   5.005 ms/op
                 getUser·p0.99:   5.898 ms/op
                 getUser·p0.999:  8.946 ms/op
                 getUser·p0.9999: 22.328 ms/op
                 getUser·p1.00:   22.807 ms/op

Iteration   3: 3.657 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.948 ms/op
                 getUser·p0.50:   3.621 ms/op
                 getUser·p0.90:   4.178 ms/op
                 getUser·p0.95:   4.571 ms/op
                 getUser·p0.99:   5.652 ms/op
                 getUser·p0.999:  8.815 ms/op
                 getUser·p0.9999: 25.724 ms/op
                 getUser·p1.00:   26.411 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 254151
  mean =      3.775 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5859 
    [ 2.500,  5.000) = 237485 
    [ 5.000,  7.500) = 10034 
    [ 7.500, 10.000) = 536 
    [10.000, 12.500) = 77 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 56 
    [22.500, 25.000) = 53 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.839 ms/op
     p(50.0000) =      3.699 ms/op
     p(90.0000) =      4.571 ms/op
     p(95.0000) =      4.923 ms/op
     p(99.0000) =      5.997 ms/op
     p(99.9000) =      9.648 ms/op
     p(99.9900) =     23.658 ms/op
     p(99.9990) =     26.358 ms/op
     p(99.9999) =     26.411 ms/op
    p(100.0000) =     26.411 ms/op


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
# Warmup Iteration   1: 6.426 ±(99.9%) 0.074 ms/op
# Warmup Iteration   2: 5.552 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 5.067 ±(99.9%) 0.019 ms/op
Iteration   1: 4.975 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   0.404 ms/op
                 listUser·p0.50:   4.637 ms/op
                 listUser·p0.90:   6.832 ms/op
                 listUser·p0.95:   7.668 ms/op
                 listUser·p0.99:   9.748 ms/op
                 listUser·p0.999:  16.895 ms/op
                 listUser·p0.9999: 22.643 ms/op
                 listUser·p1.00:   22.872 ms/op

Iteration   2: 4.926 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   0.862 ms/op
                 listUser·p0.50:   4.661 ms/op
                 listUser·p0.90:   6.463 ms/op
                 listUser·p0.95:   7.291 ms/op
                 listUser·p0.99:   8.897 ms/op
                 listUser·p0.999:  20.381 ms/op
                 listUser·p0.9999: 28.311 ms/op
                 listUser·p1.00:   29.884 ms/op

Iteration   3: 4.911 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.266 ms/op
                 listUser·p0.50:   4.628 ms/op
                 listUser·p0.90:   6.308 ms/op
                 listUser·p0.95:   7.193 ms/op
                 listUser·p0.99:   9.257 ms/op
                 listUser·p0.999:  22.281 ms/op
                 listUser·p0.9999: 29.950 ms/op
                 listUser·p1.00:   31.949 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 194567
  mean =      4.937 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 508 
    [ 2.500,  5.000) = 130364 
    [ 5.000,  7.500) = 54871 
    [ 7.500, 10.000) = 7493 
    [10.000, 12.500) = 757 
    [12.500, 15.000) = 232 
    [15.000, 17.500) = 72 
    [17.500, 20.000) = 89 
    [20.000, 22.500) = 78 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 17 
    [27.500, 30.000) = 50 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.404 ms/op
     p(50.0000) =      4.645 ms/op
     p(90.0000) =      6.578 ms/op
     p(95.0000) =      7.389 ms/op
     p(99.0000) =      9.322 ms/op
     p(99.9000) =     19.661 ms/op
     p(99.9900) =     29.545 ms/op
     p(99.9990) =     30.368 ms/op
     p(99.9999) =     31.949 ms/op
    p(100.0000) =     31.949 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.356 ± 4.750  ops/ms
ClientGrpc.existUser                       thrpt       3   8.735 ± 1.710  ops/ms
ClientGrpc.getUser                         thrpt       3   8.166 ± 1.419  ops/ms
ClientGrpc.listUser                        thrpt       3   6.691 ± 4.880  ops/ms
ClientGrpc.createUser                       avgt       3   3.744 ± 1.721   ms/op
ClientGrpc.existUser                        avgt       3   3.571 ± 0.810   ms/op
ClientGrpc.getUser                          avgt       3   3.895 ± 0.577   ms/op
ClientGrpc.listUser                         avgt       3   4.957 ± 0.786   ms/op
ClientGrpc.createUser                     sample  250971   3.823 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.745           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.756           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.686           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.005           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.212           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          14.107           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.673           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.004           ms/op
ClientGrpc.existUser                      sample  264874   3.624 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.756           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.596           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.432           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.710           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.874           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.554           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.048           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.889           ms/op
ClientGrpc.getUser                        sample  254151   3.775 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.839           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.699           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.571           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.923           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.997           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.648           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.658           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          26.411           ms/op
ClientGrpc.listUser                       sample  194567   4.937 ± 0.011   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.404           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.645           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.578           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.389           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.322           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.661           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          29.545           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          31.949           ms/op
