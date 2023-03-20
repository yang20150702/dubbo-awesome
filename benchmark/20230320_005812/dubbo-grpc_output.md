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
# Warmup Iteration   1: 4.819 ops/ms
# Warmup Iteration   2: 8.929 ops/ms
# Warmup Iteration   3: 10.231 ops/ms
Iteration   1: 10.891 ops/ms
Iteration   2: 11.173 ops/ms
Iteration   3: 10.942 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  11.002 ±(99.9%) 2.749 ops/ms [Average]
  (min, avg, max) = (10.891, 11.002, 11.173), stdev = 0.151
  CI (99.9%): [8.253, 13.750] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.975 ops/ms
# Warmup Iteration   2: 11.018 ops/ms
# Warmup Iteration   3: 11.456 ops/ms
Iteration   1: 11.459 ops/ms
Iteration   2: 11.473 ops/ms
Iteration   3: 11.532 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.488 ±(99.9%) 0.708 ops/ms [Average]
  (min, avg, max) = (11.459, 11.488, 11.532), stdev = 0.039
  CI (99.9%): [10.780, 12.196] (assumes normal distribution)


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
# Warmup Iteration   1: 7.889 ops/ms
# Warmup Iteration   2: 10.613 ops/ms
# Warmup Iteration   3: 10.607 ops/ms
Iteration   1: 10.979 ops/ms
Iteration   2: 10.803 ops/ms
Iteration   3: 10.789 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.857 ±(99.9%) 1.939 ops/ms [Average]
  (min, avg, max) = (10.789, 10.857, 10.979), stdev = 0.106
  CI (99.9%): [8.918, 12.796] (assumes normal distribution)


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
# Warmup Iteration   1: 5.963 ops/ms
# Warmup Iteration   2: 8.217 ops/ms
# Warmup Iteration   3: 8.426 ops/ms
Iteration   1: 8.464 ops/ms
Iteration   2: 8.544 ops/ms
Iteration   3: 8.575 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.527 ±(99.9%) 1.042 ops/ms [Average]
  (min, avg, max) = (8.464, 8.527, 8.575), stdev = 0.057
  CI (99.9%): [7.485, 9.569] (assumes normal distribution)


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
# Warmup Iteration   1: 3.777 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.102 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.028 ±(99.9%) 0.003 ms/op
Iteration   1: 3.008 ±(99.9%) 0.003 ms/op
Iteration   2: 2.958 ±(99.9%) 0.003 ms/op
Iteration   3: 2.939 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.968 ±(99.9%) 0.647 ms/op [Average]
  (min, avg, max) = (2.939, 2.968, 3.008), stdev = 0.035
  CI (99.9%): [2.321, 3.616] (assumes normal distribution)


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
# Warmup Iteration   1: 3.570 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.870 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.816 ±(99.9%) 0.004 ms/op
Iteration   1: 2.858 ±(99.9%) 0.003 ms/op
Iteration   2: 2.761 ±(99.9%) 0.003 ms/op
Iteration   3: 2.764 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.794 ±(99.9%) 1.011 ms/op [Average]
  (min, avg, max) = (2.761, 2.794, 2.858), stdev = 0.055
  CI (99.9%): [1.783, 3.806] (assumes normal distribution)


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
# Warmup Iteration   1: 3.960 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.016 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.934 ±(99.9%) 0.003 ms/op
Iteration   1: 2.988 ±(99.9%) 0.003 ms/op
Iteration   2: 3.010 ±(99.9%) 0.003 ms/op
Iteration   3: 2.959 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.986 ±(99.9%) 0.462 ms/op [Average]
  (min, avg, max) = (2.959, 2.986, 3.010), stdev = 0.025
  CI (99.9%): [2.524, 3.448] (assumes normal distribution)


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
# Warmup Iteration   1: 5.181 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.919 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.721 ±(99.9%) 0.014 ms/op
Iteration   1: 3.804 ±(99.9%) 0.034 ms/op
Iteration   2: 3.724 ±(99.9%) 0.018 ms/op
Iteration   3: 3.783 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.770 ±(99.9%) 0.758 ms/op [Average]
  (min, avg, max) = (3.724, 3.770, 3.804), stdev = 0.042
  CI (99.9%): [3.012, 4.529] (assumes normal distribution)


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
# Warmup Iteration   1: 4.007 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.121 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.998 ±(99.9%) 0.007 ms/op
Iteration   1: 2.987 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.663 ms/op
                 createUser·p0.50:   2.970 ms/op
                 createUser·p0.90:   3.531 ms/op
                 createUser·p0.95:   3.785 ms/op
                 createUser·p0.99:   4.549 ms/op
                 createUser·p0.999:  7.242 ms/op
                 createUser·p0.9999: 13.538 ms/op
                 createUser·p1.00:   13.861 ms/op

Iteration   2: 2.986 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.694 ms/op
                 createUser·p0.50:   2.978 ms/op
                 createUser·p0.90:   3.564 ms/op
                 createUser·p0.95:   3.805 ms/op
                 createUser·p0.99:   4.247 ms/op
                 createUser·p0.999:  8.995 ms/op
                 createUser·p0.9999: 14.952 ms/op
                 createUser·p1.00:   15.139 ms/op

Iteration   3: 2.982 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.641 ms/op
                 createUser·p0.50:   2.949 ms/op
                 createUser·p0.90:   3.416 ms/op
                 createUser·p0.95:   3.572 ms/op
                 createUser·p0.99:   4.456 ms/op
                 createUser·p0.999:  9.429 ms/op
                 createUser·p0.9999: 26.780 ms/op
                 createUser·p1.00:   27.034 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 321472
  mean =      2.985 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29738 
    [ 2.500,  5.000) = 290042 
    [ 5.000,  7.500) = 1321 
    [ 7.500, 10.000) = 114 
    [10.000, 12.500) = 99 
    [12.500, 15.000) = 119 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.641 ms/op
     p(50.0000) =      2.966 ms/op
     p(90.0000) =      3.498 ms/op
     p(95.0000) =      3.723 ms/op
     p(99.0000) =      4.440 ms/op
     p(99.9000) =      8.684 ms/op
     p(99.9900) =     24.723 ms/op
     p(99.9990) =     26.961 ms/op
     p(99.9999) =     27.034 ms/op
    p(100.0000) =     27.034 ms/op


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
# Warmup Iteration   1: 3.726 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 2.910 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.859 ±(99.9%) 0.005 ms/op
Iteration   1: 2.766 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.766 ms/op
                 existUser·p0.50:   2.785 ms/op
                 existUser·p0.90:   3.260 ms/op
                 existUser·p0.95:   3.559 ms/op
                 existUser·p0.99:   4.456 ms/op
                 existUser·p0.999:  7.047 ms/op
                 existUser·p0.9999: 12.583 ms/op
                 existUser·p1.00:   12.780 ms/op

Iteration   2: 2.797 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.558 ms/op
                 existUser·p0.50:   2.793 ms/op
                 existUser·p0.90:   3.326 ms/op
                 existUser·p0.95:   3.564 ms/op
                 existUser·p0.99:   4.375 ms/op
                 existUser·p0.999:  7.393 ms/op
                 existUser·p0.9999: 19.843 ms/op
                 existUser·p1.00:   20.283 ms/op

Iteration   3: 2.885 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.586 ms/op
                 existUser·p0.50:   2.859 ms/op
                 existUser·p0.90:   3.449 ms/op
                 existUser·p0.95:   3.658 ms/op
                 existUser·p0.99:   4.358 ms/op
                 existUser·p0.999:  7.586 ms/op
                 existUser·p0.9999: 16.938 ms/op
                 existUser·p1.00:   17.334 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 341236
  mean =      2.815 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 68525 
    [ 2.500,  5.000) = 271350 
    [ 5.000,  7.500) = 1030 
    [ 7.500, 10.000) = 74 
    [10.000, 12.500) = 140 
    [12.500, 15.000) = 21 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.558 ms/op
     p(50.0000) =      2.810 ms/op
     p(90.0000) =      3.359 ms/op
     p(95.0000) =      3.600 ms/op
     p(99.0000) =      4.407 ms/op
     p(99.9000) =      7.430 ms/op
     p(99.9900) =     18.018 ms/op
     p(99.9990) =     20.150 ms/op
     p(99.9999) =     20.283 ms/op
    p(100.0000) =     20.283 ms/op


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
# Warmup Iteration   1: 3.709 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.011 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.972 ±(99.9%) 0.006 ms/op
Iteration   1: 2.918 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.726 ms/op
                 getUser·p0.50:   2.908 ms/op
                 getUser·p0.90:   3.351 ms/op
                 getUser·p0.95:   3.654 ms/op
                 getUser·p0.99:   4.547 ms/op
                 getUser·p0.999:  8.257 ms/op
                 getUser·p0.9999: 22.676 ms/op
                 getUser·p1.00:   23.134 ms/op

Iteration   2: 2.926 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.799 ms/op
                 getUser·p0.50:   2.912 ms/op
                 getUser·p0.90:   3.367 ms/op
                 getUser·p0.95:   3.740 ms/op
                 getUser·p0.99:   4.547 ms/op
                 getUser·p0.999:  7.763 ms/op
                 getUser·p0.9999: 24.843 ms/op
                 getUser·p1.00:   25.231 ms/op

Iteration   3: 2.975 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.633 ms/op
                 getUser·p0.50:   2.945 ms/op
                 getUser·p0.90:   3.412 ms/op
                 getUser·p0.95:   3.633 ms/op
                 getUser·p0.99:   4.243 ms/op
                 getUser·p0.999:  6.869 ms/op
                 getUser·p0.9999: 23.962 ms/op
                 getUser·p1.00:   24.773 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 326508
  mean =      2.939 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29188 
    [ 2.500,  5.000) = 295782 
    [ 5.000,  7.500) = 1169 
    [ 7.500, 10.000) = 176 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 38 
    [15.000, 17.500) = 45 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 72 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.633 ms/op
     p(50.0000) =      2.920 ms/op
     p(90.0000) =      3.375 ms/op
     p(95.0000) =      3.666 ms/op
     p(99.0000) =      4.481 ms/op
     p(99.9000) =      7.848 ms/op
     p(99.9900) =     24.161 ms/op
     p(99.9990) =     25.124 ms/op
     p(99.9999) =     25.231 ms/op
    p(100.0000) =     25.231 ms/op


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
# Warmup Iteration   1: 5.157 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.895 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.768 ±(99.9%) 0.010 ms/op
Iteration   1: 3.735 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.861 ms/op
                 listUser·p0.50:   3.592 ms/op
                 listUser·p0.90:   4.817 ms/op
                 listUser·p0.95:   5.456 ms/op
                 listUser·p0.99:   6.601 ms/op
                 listUser·p0.999:  13.603 ms/op
                 listUser·p0.9999: 18.201 ms/op
                 listUser·p1.00:   18.579 ms/op

Iteration   2: 3.824 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.092 ms/op
                 listUser·p0.50:   3.645 ms/op
                 listUser·p0.90:   4.973 ms/op
                 listUser·p0.95:   5.767 ms/op
                 listUser·p0.99:   6.709 ms/op
                 listUser·p0.999:  15.036 ms/op
                 listUser·p0.9999: 21.386 ms/op
                 listUser·p1.00:   22.577 ms/op

Iteration   3: 3.830 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.719 ms/op
                 listUser·p0.50:   3.637 ms/op
                 listUser·p0.90:   4.915 ms/op
                 listUser·p0.95:   5.464 ms/op
                 listUser·p0.99:   6.726 ms/op
                 listUser·p0.999:  14.493 ms/op
                 listUser·p0.9999: 17.683 ms/op
                 listUser·p1.00:   20.218 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 252968
  mean =      3.796 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7350 
    [ 2.500,  5.000) = 222795 
    [ 5.000,  7.500) = 21635 
    [ 7.500, 10.000) = 549 
    [10.000, 12.500) = 194 
    [12.500, 15.000) = 250 
    [15.000, 17.500) = 104 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.719 ms/op
     p(50.0000) =      3.625 ms/op
     p(90.0000) =      4.899 ms/op
     p(95.0000) =      5.562 ms/op
     p(99.0000) =      6.676 ms/op
     p(99.9000) =     14.582 ms/op
     p(99.9900) =     20.241 ms/op
     p(99.9990) =     21.725 ms/op
     p(99.9999) =     22.577 ms/op
    p(100.0000) =     22.577 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  11.002 ± 2.749  ops/ms
ClientGrpc.existUser                       thrpt       3  11.488 ± 0.708  ops/ms
ClientGrpc.getUser                         thrpt       3  10.857 ± 1.939  ops/ms
ClientGrpc.listUser                        thrpt       3   8.527 ± 1.042  ops/ms
ClientGrpc.createUser                       avgt       3   2.968 ± 0.647   ms/op
ClientGrpc.existUser                        avgt       3   2.794 ± 1.011   ms/op
ClientGrpc.getUser                          avgt       3   2.986 ± 0.462   ms/op
ClientGrpc.listUser                         avgt       3   3.770 ± 0.758   ms/op
ClientGrpc.createUser                     sample  321472   2.985 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.641           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.966           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.498           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.723           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.440           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.684           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.723           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.034           ms/op
ClientGrpc.existUser                      sample  341236   2.815 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.558           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.810           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.359           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.600           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.407           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.430           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.018           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.283           ms/op
ClientGrpc.getUser                        sample  326508   2.939 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.633           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.920           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.375           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.666           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.481           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.848           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          24.161           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.231           ms/op
ClientGrpc.listUser                       sample  252968   3.796 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.719           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.625           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.899           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.562           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.676           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.582           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.241           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.577           ms/op
