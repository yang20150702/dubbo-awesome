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
# Warmup Iteration   1: 3.763 ops/ms
# Warmup Iteration   2: 8.321 ops/ms
# Warmup Iteration   3: 9.712 ops/ms
Iteration   1: 10.131 ops/ms
Iteration   2: 10.408 ops/ms
Iteration   3: 10.145 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.228 ±(99.9%) 2.842 ops/ms [Average]
  (min, avg, max) = (10.131, 10.228, 10.408), stdev = 0.156
  CI (99.9%): [7.386, 13.070] (assumes normal distribution)


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
# Warmup Iteration   1: 7.555 ops/ms
# Warmup Iteration   2: 10.405 ops/ms
# Warmup Iteration   3: 10.780 ops/ms
Iteration   1: 11.041 ops/ms
Iteration   2: 10.896 ops/ms
Iteration   3: 10.819 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.918 ±(99.9%) 2.057 ops/ms [Average]
  (min, avg, max) = (10.819, 10.918, 11.041), stdev = 0.113
  CI (99.9%): [8.861, 12.975] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 6.617 ops/ms
# Warmup Iteration   2: 9.890 ops/ms
# Warmup Iteration   3: 10.229 ops/ms
Iteration   1: 10.437 ops/ms
Iteration   2: 10.548 ops/ms
Iteration   3: 10.585 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.523 ±(99.9%) 1.396 ops/ms [Average]
  (min, avg, max) = (10.437, 10.523, 10.585), stdev = 0.077
  CI (99.9%): [9.127, 11.920] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.143 ops/ms
# Warmup Iteration   2: 7.658 ops/ms
# Warmup Iteration   3: 7.830 ops/ms
Iteration   1: 8.046 ops/ms
Iteration   2: 8.364 ops/ms
Iteration   3: 8.062 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.157 ±(99.9%) 3.277 ops/ms [Average]
  (min, avg, max) = (8.046, 8.157, 8.364), stdev = 0.180
  CI (99.9%): [4.880, 11.434] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.401 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.234 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.086 ±(99.9%) 0.005 ms/op
Iteration   1: 3.028 ±(99.9%) 0.002 ms/op
Iteration   2: 3.068 ±(99.9%) 0.002 ms/op
Iteration   3: 3.037 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.044 ±(99.9%) 0.387 ms/op [Average]
  (min, avg, max) = (3.028, 3.044, 3.068), stdev = 0.021
  CI (99.9%): [2.657, 3.431] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 4.311 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.075 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.923 ±(99.9%) 0.003 ms/op
Iteration   1: 2.903 ±(99.9%) 0.002 ms/op
Iteration   2: 2.870 ±(99.9%) 0.004 ms/op
Iteration   3: 2.935 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.903 ±(99.9%) 0.597 ms/op [Average]
  (min, avg, max) = (2.870, 2.903, 2.935), stdev = 0.033
  CI (99.9%): [2.306, 3.499] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.331 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.145 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.055 ±(99.9%) 0.004 ms/op
Iteration   1: 3.044 ±(99.9%) 0.005 ms/op
Iteration   2: 3.057 ±(99.9%) 0.002 ms/op
Iteration   3: 3.036 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.046 ±(99.9%) 0.189 ms/op [Average]
  (min, avg, max) = (3.036, 3.046, 3.057), stdev = 0.010
  CI (99.9%): [2.856, 3.235] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.405 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.209 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.057 ±(99.9%) 0.011 ms/op
Iteration   1: 4.093 ±(99.9%) 0.014 ms/op
Iteration   2: 4.019 ±(99.9%) 0.012 ms/op
Iteration   3: 4.052 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.055 ±(99.9%) 0.680 ms/op [Average]
  (min, avg, max) = (4.019, 4.055, 4.093), stdev = 0.037
  CI (99.9%): [3.375, 4.735] (assumes normal distribution)


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
# Warmup Iteration   1: 4.523 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.329 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.038 ±(99.9%) 0.007 ms/op
Iteration   1: 3.015 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.861 ms/op
                 createUser·p0.50:   2.990 ms/op
                 createUser·p0.90:   3.576 ms/op
                 createUser·p0.95:   3.801 ms/op
                 createUser·p0.99:   4.399 ms/op
                 createUser·p0.999:  7.178 ms/op
                 createUser·p0.9999: 18.309 ms/op
                 createUser·p1.00:   19.005 ms/op

Iteration   2: 3.076 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.901 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.584 ms/op
                 createUser·p0.95:   3.793 ms/op
                 createUser·p0.99:   4.415 ms/op
                 createUser·p0.999:  9.586 ms/op
                 createUser·p0.9999: 22.977 ms/op
                 createUser·p1.00:   23.396 ms/op

Iteration   3: 3.061 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.756 ms/op
                 createUser·p0.50:   3.027 ms/op
                 createUser·p0.90:   3.551 ms/op
                 createUser·p0.95:   3.752 ms/op
                 createUser·p0.99:   4.415 ms/op
                 createUser·p0.999:  12.244 ms/op
                 createUser·p0.9999: 34.050 ms/op
                 createUser·p1.00:   34.472 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 314582
  mean =      3.050 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22332 
    [ 2.500,  5.000) = 290860 
    [ 5.000,  7.500) = 965 
    [ 7.500, 10.000) = 116 
    [10.000, 12.500) = 61 
    [12.500, 15.000) = 38 
    [15.000, 17.500) = 62 
    [17.500, 20.000) = 62 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 32 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.756 ms/op
     p(50.0000) =      3.019 ms/op
     p(90.0000) =      3.568 ms/op
     p(95.0000) =      3.785 ms/op
     p(99.0000) =      4.407 ms/op
     p(99.9000) =      9.575 ms/op
     p(99.9900) =     32.556 ms/op
     p(99.9990) =     34.406 ms/op
     p(99.9999) =     34.472 ms/op
    p(100.0000) =     34.472 ms/op


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
# Warmup Iteration   1: 3.864 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.064 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.004 ±(99.9%) 0.005 ms/op
Iteration   1: 2.887 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.798 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.396 ms/op
                 existUser·p0.95:   3.650 ms/op
                 existUser·p0.99:   4.440 ms/op
                 existUser·p0.999:  7.771 ms/op
                 existUser·p0.9999: 15.857 ms/op
                 existUser·p1.00:   16.155 ms/op

Iteration   2: 2.953 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.686 ms/op
                 existUser·p0.50:   2.953 ms/op
                 existUser·p0.90:   3.420 ms/op
                 existUser·p0.95:   3.621 ms/op
                 existUser·p0.99:   4.182 ms/op
                 existUser·p0.999:  9.594 ms/op
                 existUser·p0.9999: 21.698 ms/op
                 existUser·p1.00:   21.889 ms/op

Iteration   3: 2.932 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.845 ms/op
                 existUser·p0.50:   2.904 ms/op
                 existUser·p0.90:   3.322 ms/op
                 existUser·p0.95:   3.498 ms/op
                 existUser·p0.99:   4.010 ms/op
                 existUser·p0.999:  6.692 ms/op
                 existUser·p0.9999: 17.727 ms/op
                 existUser·p1.00:   18.022 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 328217
  mean =      2.924 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 33842 
    [ 2.500,  5.000) = 293125 
    [ 5.000,  7.500) = 881 
    [ 7.500, 10.000) = 177 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 58 
    [15.000, 17.500) = 90 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.686 ms/op
     p(50.0000) =      2.925 ms/op
     p(90.0000) =      3.379 ms/op
     p(95.0000) =      3.592 ms/op
     p(99.0000) =      4.202 ms/op
     p(99.9000) =      7.684 ms/op
     p(99.9900) =     18.589 ms/op
     p(99.9990) =     21.856 ms/op
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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.582 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.194 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.112 ±(99.9%) 0.006 ms/op
Iteration   1: 3.080 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.853 ms/op
                 getUser·p0.50:   3.052 ms/op
                 getUser·p0.90:   3.588 ms/op
                 getUser·p0.95:   3.809 ms/op
                 getUser·p0.99:   4.612 ms/op
                 getUser·p0.999:  7.990 ms/op
                 getUser·p0.9999: 13.176 ms/op
                 getUser·p1.00:   13.451 ms/op

Iteration   2: 3.053 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.874 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.461 ms/op
                 getUser·p0.95:   3.674 ms/op
                 getUser·p0.99:   4.407 ms/op
                 getUser·p0.999:  7.463 ms/op
                 getUser·p0.9999: 25.626 ms/op
                 getUser·p1.00:   25.952 ms/op

Iteration   3: 3.067 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.759 ms/op
                 getUser·p0.50:   3.039 ms/op
                 getUser·p0.90:   3.576 ms/op
                 getUser·p0.95:   3.801 ms/op
                 getUser·p0.99:   4.514 ms/op
                 getUser·p0.999:  6.675 ms/op
                 getUser·p0.9999: 17.287 ms/op
                 getUser·p1.00:   19.038 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 313040
  mean =      3.067 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15017 
    [ 2.500,  5.000) = 296508 
    [ 5.000,  7.500) = 1214 
    [ 7.500, 10.000) = 89 
    [10.000, 12.500) = 42 
    [12.500, 15.000) = 42 
    [15.000, 17.500) = 89 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.759 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      3.543 ms/op
     p(95.0000) =      3.772 ms/op
     p(99.0000) =      4.506 ms/op
     p(99.9000) =      7.463 ms/op
     p(99.9900) =     24.710 ms/op
     p(99.9990) =     25.878 ms/op
     p(99.9999) =     25.952 ms/op
    p(100.0000) =     25.952 ms/op


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
# Warmup Iteration   1: 5.535 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.153 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.072 ±(99.9%) 0.011 ms/op
Iteration   1: 4.100 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.364 ms/op
                 listUser·p0.50:   3.912 ms/op
                 listUser·p0.90:   5.317 ms/op
                 listUser·p0.95:   6.011 ms/op
                 listUser·p0.99:   7.119 ms/op
                 listUser·p0.999:  14.074 ms/op
                 listUser·p0.9999: 16.007 ms/op
                 listUser·p1.00:   17.891 ms/op

Iteration   2: 3.961 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.346 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   4.858 ms/op
                 listUser·p0.95:   5.726 ms/op
                 listUser·p0.99:   6.906 ms/op
                 listUser·p0.999:  16.020 ms/op
                 listUser·p0.9999: 23.525 ms/op
                 listUser·p1.00:   23.953 ms/op

Iteration   3: 4.022 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.989 ms/op
                 listUser·p0.50:   3.838 ms/op
                 listUser·p0.90:   5.030 ms/op
                 listUser·p0.95:   5.775 ms/op
                 listUser·p0.99:   7.062 ms/op
                 listUser·p0.999:  16.777 ms/op
                 listUser·p0.9999: 18.777 ms/op
                 listUser·p1.00:   19.268 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 238395
  mean =      4.027 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2581 
    [ 2.500,  5.000) = 210508 
    [ 5.000,  7.500) = 23947 
    [ 7.500, 10.000) = 966 
    [10.000, 12.500) = 41 
    [12.500, 15.000) = 101 
    [15.000, 17.500) = 155 
    [17.500, 20.000) = 63 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.989 ms/op
     p(50.0000) =      3.854 ms/op
     p(90.0000) =      5.063 ms/op
     p(95.0000) =      5.874 ms/op
     p(99.0000) =      7.029 ms/op
     p(99.9000) =     15.221 ms/op
     p(99.9900) =     23.036 ms/op
     p(99.9990) =     23.843 ms/op
     p(99.9999) =     23.953 ms/op
    p(100.0000) =     23.953 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.228 ± 2.842  ops/ms
ClientGrpc.existUser                       thrpt       3  10.918 ± 2.057  ops/ms
ClientGrpc.getUser                         thrpt       3  10.523 ± 1.396  ops/ms
ClientGrpc.listUser                        thrpt       3   8.157 ± 3.277  ops/ms
ClientGrpc.createUser                       avgt       3   3.044 ± 0.387   ms/op
ClientGrpc.existUser                        avgt       3   2.903 ± 0.597   ms/op
ClientGrpc.getUser                          avgt       3   3.046 ± 0.189   ms/op
ClientGrpc.listUser                         avgt       3   4.055 ± 0.680   ms/op
ClientGrpc.createUser                     sample  314582   3.050 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.756           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.019           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.568           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.785           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.407           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.575           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          32.556           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          34.472           ms/op
ClientGrpc.existUser                      sample  328217   2.924 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.686           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.925           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.379           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.592           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.202           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.684           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.589           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.889           ms/op
ClientGrpc.getUser                        sample  313040   3.067 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.759           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.039           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.543           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.772           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.506           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.463           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          24.710           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.952           ms/op
ClientGrpc.listUser                       sample  238395   4.027 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.989           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.854           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.063           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.874           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.029           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.221           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.036           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.953           ms/op
