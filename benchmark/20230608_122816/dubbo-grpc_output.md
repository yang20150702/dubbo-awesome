# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.484 ops/ms
# Warmup Iteration   2: 9.313 ops/ms
# Warmup Iteration   3: 10.121 ops/ms
Iteration   1: 10.642 ops/ms
Iteration   2: 10.741 ops/ms
Iteration   3: 10.699 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.694 ±(99.9%) 0.908 ops/ms [Average]
  (min, avg, max) = (10.642, 10.694, 10.741), stdev = 0.050
  CI (99.9%): [9.786, 11.602] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 8.435 ops/ms
# Warmup Iteration   2: 10.729 ops/ms
# Warmup Iteration   3: 11.295 ops/ms
Iteration   1: 11.305 ops/ms
Iteration   2: 11.120 ops/ms
Iteration   3: 11.334 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.253 ±(99.9%) 2.112 ops/ms [Average]
  (min, avg, max) = (11.120, 11.253, 11.334), stdev = 0.116
  CI (99.9%): [9.141, 13.365] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.701 ops/ms
# Warmup Iteration   2: 10.316 ops/ms
# Warmup Iteration   3: 10.585 ops/ms
Iteration   1: 10.908 ops/ms
Iteration   2: 10.861 ops/ms
Iteration   3: 10.790 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.853 ±(99.9%) 1.082 ops/ms [Average]
  (min, avg, max) = (10.790, 10.853, 10.908), stdev = 0.059
  CI (99.9%): [9.771, 11.935] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.893 ops/ms
# Warmup Iteration   2: 7.917 ops/ms
# Warmup Iteration   3: 8.201 ops/ms
Iteration   1: 8.302 ops/ms
Iteration   2: 8.292 ops/ms
Iteration   3: 8.295 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.297 ±(99.9%) 0.098 ops/ms [Average]
  (min, avg, max) = (8.292, 8.297, 8.302), stdev = 0.005
  CI (99.9%): [8.198, 8.395] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.021 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.113 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.018 ±(99.9%) 0.002 ms/op
Iteration   1: 2.997 ±(99.9%) 0.005 ms/op
Iteration   2: 2.959 ±(99.9%) 0.003 ms/op
Iteration   3: 3.004 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.987 ±(99.9%) 0.440 ms/op [Average]
  (min, avg, max) = (2.959, 2.987, 3.004), stdev = 0.024
  CI (99.9%): [2.546, 3.427] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.398 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 2.980 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.867 ±(99.9%) 0.003 ms/op
Iteration   1: 2.872 ±(99.9%) 0.002 ms/op
Iteration   2: 2.828 ±(99.9%) 0.003 ms/op
Iteration   3: 2.873 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.858 ±(99.9%) 0.468 ms/op [Average]
  (min, avg, max) = (2.828, 2.858, 2.873), stdev = 0.026
  CI (99.9%): [2.389, 3.326] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 3.671 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.053 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.032 ±(99.9%) 0.002 ms/op
Iteration   1: 2.970 ±(99.9%) 0.002 ms/op
Iteration   2: 2.968 ±(99.9%) 0.003 ms/op
Iteration   3: 2.927 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.955 ±(99.9%) 0.443 ms/op [Average]
  (min, avg, max) = (2.927, 2.955, 2.970), stdev = 0.024
  CI (99.9%): [2.512, 3.398] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.626 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 4.061 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 3.931 ±(99.9%) 0.030 ms/op
Iteration   1: 3.904 ±(99.9%) 0.021 ms/op
Iteration   2: 3.918 ±(99.9%) 0.037 ms/op
Iteration   3: 3.823 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.882 ±(99.9%) 0.939 ms/op [Average]
  (min, avg, max) = (3.823, 3.882, 3.918), stdev = 0.051
  CI (99.9%): [2.942, 4.821] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.844 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.141 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.957 ±(99.9%) 0.006 ms/op
Iteration   1: 2.966 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.683 ms/op
                 createUser·p0.50:   2.966 ms/op
                 createUser·p0.90:   3.527 ms/op
                 createUser·p0.95:   3.727 ms/op
                 createUser·p0.99:   4.383 ms/op
                 createUser·p0.999:  6.850 ms/op
                 createUser·p0.9999: 11.485 ms/op
                 createUser·p1.00:   11.682 ms/op

Iteration   2: 2.966 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.818 ms/op
                 createUser·p0.50:   2.949 ms/op
                 createUser·p0.90:   3.383 ms/op
                 createUser·p0.95:   3.539 ms/op
                 createUser·p0.99:   4.194 ms/op
                 createUser·p0.999:  9.437 ms/op
                 createUser·p0.9999: 20.651 ms/op
                 createUser·p1.00:   21.004 ms/op

Iteration   3: 2.997 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.622 ms/op
                 createUser·p0.50:   2.978 ms/op
                 createUser·p0.90:   3.473 ms/op
                 createUser·p0.95:   3.666 ms/op
                 createUser·p0.99:   4.481 ms/op
                 createUser·p0.999:  7.438 ms/op
                 createUser·p0.9999: 16.732 ms/op
                 createUser·p1.00:   17.400 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 322573
  mean =      2.976 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29289 
    [ 2.500,  5.000) = 291895 
    [ 5.000,  7.500) = 1043 
    [ 7.500, 10.000) = 151 
    [10.000, 12.500) = 99 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 64 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.622 ms/op
     p(50.0000) =      2.961 ms/op
     p(90.0000) =      3.461 ms/op
     p(95.0000) =      3.654 ms/op
     p(99.0000) =      4.358 ms/op
     p(99.9000) =      7.709 ms/op
     p(99.9900) =     18.957 ms/op
     p(99.9990) =     20.899 ms/op
     p(99.9999) =     21.004 ms/op
    p(100.0000) =     21.004 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.635 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 2.961 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.807 ±(99.9%) 0.006 ms/op
Iteration   1: 2.875 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.522 ms/op
                 existUser·p0.50:   2.863 ms/op
                 existUser·p0.90:   3.424 ms/op
                 existUser·p0.95:   3.629 ms/op
                 existUser·p0.99:   4.350 ms/op
                 existUser·p0.999:  8.110 ms/op
                 existUser·p0.9999: 14.678 ms/op
                 existUser·p1.00:   15.827 ms/op

Iteration   2: 2.836 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.737 ms/op
                 existUser·p0.50:   2.818 ms/op
                 existUser·p0.90:   3.412 ms/op
                 existUser·p0.95:   3.584 ms/op
                 existUser·p0.99:   4.432 ms/op
                 existUser·p0.999:  7.039 ms/op
                 existUser·p0.9999: 20.298 ms/op
                 existUser·p1.00:   20.775 ms/op

Iteration   3: 2.837 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.653 ms/op
                 existUser·p0.50:   2.814 ms/op
                 existUser·p0.90:   3.363 ms/op
                 existUser·p0.95:   3.662 ms/op
                 existUser·p0.99:   4.334 ms/op
                 existUser·p0.999:  7.119 ms/op
                 existUser·p0.9999: 19.160 ms/op
                 existUser·p1.00:   19.268 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 336664
  mean =      2.849 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 59103 
    [ 2.500,  5.000) = 276540 
    [ 5.000,  7.500) = 712 
    [ 7.500, 10.000) = 149 
    [10.000, 12.500) = 41 
    [12.500, 15.000) = 46 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.522 ms/op
     p(50.0000) =      2.834 ms/op
     p(90.0000) =      3.404 ms/op
     p(95.0000) =      3.621 ms/op
     p(99.0000) =      4.375 ms/op
     p(99.9000) =      7.204 ms/op
     p(99.9900) =     19.246 ms/op
     p(99.9990) =     20.653 ms/op
     p(99.9999) =     20.775 ms/op
    p(100.0000) =     20.775 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.132 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.099 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.036 ±(99.9%) 0.007 ms/op
Iteration   1: 2.960 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.673 ms/op
                 getUser·p0.50:   2.966 ms/op
                 getUser·p0.90:   3.420 ms/op
                 getUser·p0.95:   3.666 ms/op
                 getUser·p0.99:   4.325 ms/op
                 getUser·p0.999:  10.092 ms/op
                 getUser·p0.9999: 15.339 ms/op
                 getUser·p1.00:   15.843 ms/op

Iteration   2: 3.009 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.758 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.428 ms/op
                 getUser·p0.95:   3.621 ms/op
                 getUser·p0.99:   4.375 ms/op
                 getUser·p0.999:  7.825 ms/op
                 getUser·p0.9999: 16.265 ms/op
                 getUser·p1.00:   16.531 ms/op

Iteration   3: 3.077 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.790 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.637 ms/op
                 getUser·p0.95:   3.842 ms/op
                 getUser·p0.99:   4.530 ms/op
                 getUser·p0.999:  10.940 ms/op
                 getUser·p0.9999: 31.673 ms/op
                 getUser·p1.00:   31.982 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 318385
  mean =      3.014 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25935 
    [ 2.500,  5.000) = 291132 
    [ 5.000,  7.500) = 818 
    [ 7.500, 10.000) = 196 
    [10.000, 12.500) = 111 
    [12.500, 15.000) = 65 
    [15.000, 17.500) = 64 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 20 
    [30.000, 32.500) = 12 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.673 ms/op
     p(50.0000) =      3.019 ms/op
     p(90.0000) =      3.502 ms/op
     p(95.0000) =      3.740 ms/op
     p(99.0000) =      4.399 ms/op
     p(99.9000) =      8.612 ms/op
     p(99.9900) =     29.229 ms/op
     p(99.9990) =     31.877 ms/op
     p(99.9999) =     31.982 ms/op
    p(100.0000) =     31.982 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.562 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.046 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.916 ±(99.9%) 0.010 ms/op
Iteration   1: 3.907 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.668 ms/op
                 listUser·p0.50:   3.785 ms/op
                 listUser·p0.90:   4.792 ms/op
                 listUser·p0.95:   5.448 ms/op
                 listUser·p0.99:   6.685 ms/op
                 listUser·p0.999:  12.241 ms/op
                 listUser·p0.9999: 19.485 ms/op
                 listUser·p1.00:   19.759 ms/op

Iteration   2: 3.786 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.114 ms/op
                 listUser·p0.50:   3.682 ms/op
                 listUser·p0.90:   4.645 ms/op
                 listUser·p0.95:   5.243 ms/op
                 listUser·p0.99:   6.570 ms/op
                 listUser·p0.999:  12.814 ms/op
                 listUser·p0.9999: 13.724 ms/op
                 listUser·p1.00:   15.630 ms/op

Iteration   3: 3.801 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.030 ms/op
                 listUser·p0.50:   3.658 ms/op
                 listUser·p0.90:   4.809 ms/op
                 listUser·p0.95:   5.333 ms/op
                 listUser·p0.99:   6.742 ms/op
                 listUser·p0.999:  13.320 ms/op
                 listUser·p0.9999: 18.387 ms/op
                 listUser·p1.00:   18.940 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 250622
  mean =      3.831 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 20 
    [ 1.250,  2.500) = 4824 
    [ 2.500,  3.750) = 129119 
    [ 3.750,  5.000) = 97922 
    [ 5.000,  6.250) = 14453 
    [ 6.250,  7.500) = 3264 
    [ 7.500,  8.750) = 536 
    [ 8.750, 10.000) = 66 
    [10.000, 11.250) = 34 
    [11.250, 12.500) = 91 
    [12.500, 13.750) = 176 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.668 ms/op
     p(50.0000) =      3.711 ms/op
     p(90.0000) =      4.743 ms/op
     p(95.0000) =      5.333 ms/op
     p(99.0000) =      6.668 ms/op
     p(99.9000) =     12.753 ms/op
     p(99.9900) =     18.940 ms/op
     p(99.9990) =     19.644 ms/op
     p(99.9999) =     19.759 ms/op
    p(100.0000) =     19.759 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.694 ± 0.908  ops/ms
ClientGrpc.existUser                       thrpt       3  11.253 ± 2.112  ops/ms
ClientGrpc.getUser                         thrpt       3  10.853 ± 1.082  ops/ms
ClientGrpc.listUser                        thrpt       3   8.297 ± 0.098  ops/ms
ClientGrpc.createUser                       avgt       3   2.987 ± 0.440   ms/op
ClientGrpc.existUser                        avgt       3   2.858 ± 0.468   ms/op
ClientGrpc.getUser                          avgt       3   2.955 ± 0.443   ms/op
ClientGrpc.listUser                         avgt       3   3.882 ± 0.939   ms/op
ClientGrpc.createUser                     sample  322573   2.976 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.622           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.961           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.461           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.654           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.358           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.709           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.957           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.004           ms/op
ClientGrpc.existUser                      sample  336664   2.849 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.522           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.834           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.404           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.621           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.375           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.204           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.246           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.775           ms/op
ClientGrpc.getUser                        sample  318385   3.014 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.673           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.019           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.502           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.740           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.399           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.612           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          29.229           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          31.982           ms/op
ClientGrpc.listUser                       sample  250622   3.831 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.668           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.711           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.743           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.333           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.668           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          12.753           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          18.940           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          19.759           ms/op
