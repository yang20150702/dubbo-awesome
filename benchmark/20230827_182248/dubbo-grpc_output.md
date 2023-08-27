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
# Warmup Iteration   1: 4.567 ops/ms
# Warmup Iteration   2: 9.673 ops/ms
# Warmup Iteration   3: 10.487 ops/ms
Iteration   1: 10.895 ops/ms
Iteration   2: 10.680 ops/ms
Iteration   3: 10.670 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.748 ±(99.9%) 2.319 ops/ms [Average]
  (min, avg, max) = (10.670, 10.748, 10.895), stdev = 0.127
  CI (99.9%): [8.429, 13.067] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.935 ops/ms
# Warmup Iteration   2: 10.791 ops/ms
# Warmup Iteration   3: 11.294 ops/ms
Iteration   1: 11.256 ops/ms
Iteration   2: 11.507 ops/ms
Iteration   3: 11.306 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.356 ±(99.9%) 2.420 ops/ms [Average]
  (min, avg, max) = (11.256, 11.356, 11.507), stdev = 0.133
  CI (99.9%): [8.936, 13.776] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.536 ops/ms
# Warmup Iteration   2: 10.189 ops/ms
# Warmup Iteration   3: 10.714 ops/ms
Iteration   1: 10.750 ops/ms
Iteration   2: 10.760 ops/ms
Iteration   3: 10.431 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.647 ±(99.9%) 3.416 ops/ms [Average]
  (min, avg, max) = (10.431, 10.647, 10.760), stdev = 0.187
  CI (99.9%): [7.231, 14.063] (assumes normal distribution)


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
# Warmup Iteration   1: 7.539 ops/ms
# Warmup Iteration   2: 7.802 ops/ms
# Warmup Iteration   3: 8.056 ops/ms
Iteration   1: 8.102 ops/ms
Iteration   2: 7.990 ops/ms
Iteration   3: 8.278 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.123 ±(99.9%) 2.648 ops/ms [Average]
  (min, avg, max) = (7.990, 8.123, 8.278), stdev = 0.145
  CI (99.9%): [5.476, 10.771] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 4.111 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.070 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.045 ±(99.9%) 0.003 ms/op
Iteration   1: 3.008 ±(99.9%) 0.003 ms/op
Iteration   2: 3.004 ±(99.9%) 0.003 ms/op
Iteration   3: 3.014 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.009 ±(99.9%) 0.085 ms/op [Average]
  (min, avg, max) = (3.004, 3.009, 3.014), stdev = 0.005
  CI (99.9%): [2.923, 3.094] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.695 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.945 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.836 ±(99.9%) 0.004 ms/op
Iteration   1: 2.849 ±(99.9%) 0.004 ms/op
Iteration   2: 2.811 ±(99.9%) 0.005 ms/op
Iteration   3: 2.861 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.840 ±(99.9%) 0.472 ms/op [Average]
  (min, avg, max) = (2.811, 2.840, 2.861), stdev = 0.026
  CI (99.9%): [2.369, 3.312] (assumes normal distribution)


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
# Warmup Iteration   1: 4.023 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.089 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.042 ±(99.9%) 0.003 ms/op
Iteration   1: 3.006 ±(99.9%) 0.003 ms/op
Iteration   2: 3.012 ±(99.9%) 0.003 ms/op
Iteration   3: 2.990 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.003 ±(99.9%) 0.207 ms/op [Average]
  (min, avg, max) = (2.990, 3.003, 3.012), stdev = 0.011
  CI (99.9%): [2.796, 3.209] (assumes normal distribution)


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
# Warmup Iteration   1: 4.849 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.050 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.927 ±(99.9%) 0.011 ms/op
Iteration   1: 3.878 ±(99.9%) 0.027 ms/op
Iteration   2: 3.944 ±(99.9%) 0.039 ms/op
Iteration   3: 3.815 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.879 ±(99.9%) 1.175 ms/op [Average]
  (min, avg, max) = (3.815, 3.879, 3.944), stdev = 0.064
  CI (99.9%): [2.704, 5.054] (assumes normal distribution)


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
# Warmup Iteration   1: 4.049 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.135 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.008 ±(99.9%) 0.007 ms/op
Iteration   1: 2.996 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.614 ms/op
                 createUser·p0.50:   2.998 ms/op
                 createUser·p0.90:   3.682 ms/op
                 createUser·p0.95:   3.953 ms/op
                 createUser·p0.99:   4.710 ms/op
                 createUser·p0.999:  7.423 ms/op
                 createUser·p0.9999: 12.200 ms/op
                 createUser·p1.00:   13.042 ms/op

Iteration   2: 3.016 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.670 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.441 ms/op
                 createUser·p0.95:   3.666 ms/op
                 createUser·p0.99:   4.424 ms/op
                 createUser·p0.999:  7.749 ms/op
                 createUser·p0.9999: 15.473 ms/op
                 createUser·p1.00:   15.925 ms/op

Iteration   3: 3.111 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.784 ms/op
                 createUser·p0.50:   3.088 ms/op
                 createUser·p0.90:   3.682 ms/op
                 createUser·p0.95:   3.858 ms/op
                 createUser·p0.99:   4.473 ms/op
                 createUser·p0.999:  7.815 ms/op
                 createUser·p0.9999: 28.901 ms/op
                 createUser·p1.00:   29.458 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 315848
  mean =      3.040 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29190 
    [ 2.500,  5.000) = 285064 
    [ 5.000,  7.500) = 1211 
    [ 7.500, 10.000) = 217 
    [10.000, 12.500) = 66 
    [12.500, 15.000) = 47 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.614 ms/op
     p(50.0000) =      3.035 ms/op
     p(90.0000) =      3.609 ms/op
     p(95.0000) =      3.850 ms/op
     p(99.0000) =      4.563 ms/op
     p(99.9000) =      7.709 ms/op
     p(99.9900) =     26.569 ms/op
     p(99.9990) =     29.257 ms/op
     p(99.9999) =     29.458 ms/op
    p(100.0000) =     29.458 ms/op


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
# Warmup Iteration   1: 3.661 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 2.999 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.926 ±(99.9%) 0.007 ms/op
Iteration   1: 2.928 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.548 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.453 ms/op
                 existUser·p0.95:   3.662 ms/op
                 existUser·p0.99:   4.645 ms/op
                 existUser·p0.999:  7.867 ms/op
                 existUser·p0.9999: 12.388 ms/op
                 existUser·p1.00:   12.616 ms/op

Iteration   2: 2.893 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.580 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.207 ms/op
                 existUser·p0.95:   3.338 ms/op
                 existUser·p0.99:   4.180 ms/op
                 existUser·p0.999:  6.963 ms/op
                 existUser·p0.9999: 16.105 ms/op
                 existUser·p1.00:   16.515 ms/op

Iteration   3: 2.942 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.764 ms/op
                 existUser·p0.50:   2.945 ms/op
                 existUser·p0.90:   3.461 ms/op
                 existUser·p0.95:   3.699 ms/op
                 existUser·p0.99:   4.637 ms/op
                 existUser·p0.999:  7.332 ms/op
                 existUser·p0.9999: 14.047 ms/op
                 existUser·p1.00:   14.451 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 328492
  mean =      2.921 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2364 
    [ 1.250,  2.500) = 32226 
    [ 2.500,  3.750) = 282838 
    [ 3.750,  5.000) = 9507 
    [ 5.000,  6.250) = 931 
    [ 6.250,  7.500) = 351 
    [ 7.500,  8.750) = 113 
    [ 8.750, 10.000) = 29 
    [10.000, 11.250) = 5 
    [11.250, 12.500) = 60 
    [12.500, 13.750) = 13 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 27 
    [16.250, 17.500) = 5 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.548 ms/op
     p(50.0000) =      2.916 ms/op
     p(90.0000) =      3.375 ms/op
     p(95.0000) =      3.604 ms/op
     p(99.0000) =      4.547 ms/op
     p(99.9000) =      7.344 ms/op
     p(99.9900) =     14.643 ms/op
     p(99.9990) =     16.297 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.184 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.085 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.024 ±(99.9%) 0.006 ms/op
Iteration   1: 2.984 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.656 ms/op
                 getUser·p0.50:   2.998 ms/op
                 getUser·p0.90:   3.355 ms/op
                 getUser·p0.95:   3.580 ms/op
                 getUser·p0.99:   4.375 ms/op
                 getUser·p0.999:  7.946 ms/op
                 getUser·p0.9999: 18.776 ms/op
                 getUser·p1.00:   18.907 ms/op

Iteration   2: 3.010 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.833 ms/op
                 getUser·p0.50:   2.990 ms/op
                 getUser·p0.90:   3.498 ms/op
                 getUser·p0.95:   3.736 ms/op
                 getUser·p0.99:   4.440 ms/op
                 getUser·p0.999:  7.918 ms/op
                 getUser·p0.9999: 12.796 ms/op
                 getUser·p1.00:   13.025 ms/op

Iteration   3: 2.966 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.562 ms/op
                 getUser·p0.50:   2.986 ms/op
                 getUser·p0.90:   3.469 ms/op
                 getUser·p0.95:   3.670 ms/op
                 getUser·p0.99:   4.399 ms/op
                 getUser·p0.999:  7.915 ms/op
                 getUser·p0.9999: 13.373 ms/op
                 getUser·p1.00:   14.483 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 321231
  mean =      2.987 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2665 
    [ 1.250,  2.500) = 22702 
    [ 2.500,  3.750) = 282989 
    [ 3.750,  5.000) = 11197 
    [ 5.000,  6.250) = 759 
    [ 6.250,  7.500) = 490 
    [ 7.500,  8.750) = 184 
    [ 8.750, 10.000) = 19 
    [10.000, 11.250) = 25 
    [11.250, 12.500) = 72 
    [12.500, 13.750) = 56 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 49 

  Percentiles, ms/op:
      p(0.0000) =      0.562 ms/op
     p(50.0000) =      2.994 ms/op
     p(90.0000) =      3.445 ms/op
     p(95.0000) =      3.670 ms/op
     p(99.0000) =      4.407 ms/op
     p(99.9000) =      7.920 ms/op
     p(99.9900) =     18.195 ms/op
     p(99.9990) =     18.867 ms/op
     p(99.9999) =     18.907 ms/op
    p(100.0000) =     18.907 ms/op


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
# Warmup Iteration   1: 4.963 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.966 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.999 ±(99.9%) 0.011 ms/op
Iteration   1: 3.909 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.305 ms/op
                 listUser·p0.50:   3.744 ms/op
                 listUser·p0.90:   4.940 ms/op
                 listUser·p0.95:   5.669 ms/op
                 listUser·p0.99:   6.906 ms/op
                 listUser·p0.999:  13.634 ms/op
                 listUser·p0.9999: 18.507 ms/op
                 listUser·p1.00:   18.678 ms/op

Iteration   2: 3.957 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.055 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   5.046 ms/op
                 listUser·p0.95:   5.710 ms/op
                 listUser·p0.99:   7.045 ms/op
                 listUser·p0.999:  14.860 ms/op
                 listUser·p0.9999: 16.396 ms/op
                 listUser·p1.00:   16.810 ms/op

Iteration   3: 4.021 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   0.874 ms/op
                 listUser·p0.50:   3.838 ms/op
                 listUser·p0.90:   5.169 ms/op
                 listUser·p0.95:   5.890 ms/op
                 listUser·p0.99:   7.272 ms/op
                 listUser·p0.999:  16.721 ms/op
                 listUser·p0.9999: 27.527 ms/op
                 listUser·p1.00:   27.886 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 242517
  mean =      3.962 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4951 
    [ 2.500,  5.000) = 211984 
    [ 5.000,  7.500) = 23952 
    [ 7.500, 10.000) = 1070 
    [10.000, 12.500) = 140 
    [12.500, 15.000) = 154 
    [15.000, 17.500) = 140 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.874 ms/op
     p(50.0000) =      3.801 ms/op
     p(90.0000) =      5.054 ms/op
     p(95.0000) =      5.759 ms/op
     p(99.0000) =      7.053 ms/op
     p(99.9000) =     15.425 ms/op
     p(99.9900) =     25.813 ms/op
     p(99.9990) =     27.872 ms/op
     p(99.9999) =     27.886 ms/op
    p(100.0000) =     27.886 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.748 ± 2.319  ops/ms
ClientGrpc.existUser                       thrpt       3  11.356 ± 2.420  ops/ms
ClientGrpc.getUser                         thrpt       3  10.647 ± 3.416  ops/ms
ClientGrpc.listUser                        thrpt       3   8.123 ± 2.648  ops/ms
ClientGrpc.createUser                       avgt       3   3.009 ± 0.085   ms/op
ClientGrpc.existUser                        avgt       3   2.840 ± 0.472   ms/op
ClientGrpc.getUser                          avgt       3   3.003 ± 0.207   ms/op
ClientGrpc.listUser                         avgt       3   3.879 ± 1.175   ms/op
ClientGrpc.createUser                     sample  315848   3.040 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.614           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.035           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.609           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.850           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.563           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.709           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          26.569           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          29.458           ms/op
ClientGrpc.existUser                      sample  328492   2.921 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.548           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.916           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.375           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.604           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.547           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.344           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.643           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.515           ms/op
ClientGrpc.getUser                        sample  321231   2.987 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.562           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.994           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.445           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.670           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.407           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.920           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.195           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.907           ms/op
ClientGrpc.listUser                       sample  242517   3.962 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.874           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.801           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.054           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.759           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.053           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.425           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.813           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.886           ms/op
