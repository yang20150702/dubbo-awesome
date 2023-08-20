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
# Warmup Iteration   1: 4.023 ops/ms
# Warmup Iteration   2: 8.840 ops/ms
# Warmup Iteration   3: 9.898 ops/ms
Iteration   1: 10.169 ops/ms
Iteration   2: 10.339 ops/ms
Iteration   3: 10.567 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.358 ±(99.9%) 3.648 ops/ms [Average]
  (min, avg, max) = (10.169, 10.358, 10.567), stdev = 0.200
  CI (99.9%): [6.711, 14.006] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 7.123 ops/ms
# Warmup Iteration   2: 10.303 ops/ms
# Warmup Iteration   3: 11.164 ops/ms
Iteration   1: 11.076 ops/ms
Iteration   2: 11.035 ops/ms
Iteration   3: 10.994 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.035 ±(99.9%) 0.745 ops/ms [Average]
  (min, avg, max) = (10.994, 11.035, 11.076), stdev = 0.041
  CI (99.9%): [10.290, 11.780] (assumes normal distribution)


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
# Warmup Iteration   1: 7.155 ops/ms
# Warmup Iteration   2: 9.868 ops/ms
# Warmup Iteration   3: 10.215 ops/ms
Iteration   1: 10.515 ops/ms
Iteration   2: 10.528 ops/ms
Iteration   3: 10.439 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.494 ±(99.9%) 0.875 ops/ms [Average]
  (min, avg, max) = (10.439, 10.494, 10.528), stdev = 0.048
  CI (99.9%): [9.619, 11.369] (assumes normal distribution)


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
# Warmup Iteration   1: 5.076 ops/ms
# Warmup Iteration   2: 7.614 ops/ms
# Warmup Iteration   3: 8.034 ops/ms
Iteration   1: 7.984 ops/ms
Iteration   2: 7.814 ops/ms
Iteration   3: 7.919 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.906 ±(99.9%) 1.568 ops/ms [Average]
  (min, avg, max) = (7.814, 7.906, 7.984), stdev = 0.086
  CI (99.9%): [6.337, 9.474] (assumes normal distribution)


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
# Warmup Iteration   1: 4.249 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.236 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.090 ±(99.9%) 0.003 ms/op
Iteration   1: 3.145 ±(99.9%) 0.004 ms/op
Iteration   2: 3.122 ±(99.9%) 0.003 ms/op
Iteration   3: 3.056 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.108 ±(99.9%) 0.843 ms/op [Average]
  (min, avg, max) = (3.056, 3.108, 3.145), stdev = 0.046
  CI (99.9%): [2.264, 3.951] (assumes normal distribution)


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
# Warmup Iteration   1: 4.064 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.093 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.968 ±(99.9%) 0.003 ms/op
Iteration   1: 2.971 ±(99.9%) 0.003 ms/op
Iteration   2: 2.941 ±(99.9%) 0.003 ms/op
Iteration   3: 2.950 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.954 ±(99.9%) 0.283 ms/op [Average]
  (min, avg, max) = (2.941, 2.954, 2.971), stdev = 0.016
  CI (99.9%): [2.671, 3.237] (assumes normal distribution)


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
# Warmup Iteration   1: 4.357 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.127 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.099 ±(99.9%) 0.003 ms/op
Iteration   1: 3.063 ±(99.9%) 0.003 ms/op
Iteration   2: 3.051 ±(99.9%) 0.003 ms/op
Iteration   3: 3.057 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.057 ±(99.9%) 0.104 ms/op [Average]
  (min, avg, max) = (3.051, 3.057, 3.063), stdev = 0.006
  CI (99.9%): [2.953, 3.161] (assumes normal distribution)


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
# Warmup Iteration   1: 4.811 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 4.119 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.037 ±(99.9%) 0.010 ms/op
Iteration   1: 4.008 ±(99.9%) 0.033 ms/op
Iteration   2: 3.969 ±(99.9%) 0.026 ms/op
Iteration   3: 3.972 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.983 ±(99.9%) 0.399 ms/op [Average]
  (min, avg, max) = (3.969, 3.983, 4.008), stdev = 0.022
  CI (99.9%): [3.585, 4.382] (assumes normal distribution)


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
# Warmup Iteration   1: 4.391 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.320 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.098 ±(99.9%) 0.007 ms/op
Iteration   1: 3.052 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.752 ms/op
                 createUser·p0.50:   3.023 ms/op
                 createUser·p0.90:   3.535 ms/op
                 createUser·p0.95:   3.723 ms/op
                 createUser·p0.99:   4.596 ms/op
                 createUser·p0.999:  7.718 ms/op
                 createUser·p0.9999: 17.891 ms/op
                 createUser·p1.00:   18.285 ms/op

Iteration   2: 3.046 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.655 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.551 ms/op
                 createUser·p0.95:   3.842 ms/op
                 createUser·p0.99:   4.882 ms/op
                 createUser·p0.999:  10.928 ms/op
                 createUser·p0.9999: 18.530 ms/op
                 createUser·p1.00:   18.907 ms/op

Iteration   3: 3.122 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.793 ms/op
                 createUser·p0.50:   3.076 ms/op
                 createUser·p0.90:   3.727 ms/op
                 createUser·p0.95:   3.973 ms/op
                 createUser·p0.99:   4.694 ms/op
                 createUser·p0.999:  8.949 ms/op
                 createUser·p0.9999: 20.505 ms/op
                 createUser·p1.00:   20.546 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 312306
  mean =      3.073 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22740 
    [ 2.500,  5.000) = 287312 
    [ 5.000,  7.500) = 1767 
    [ 7.500, 10.000) = 200 
    [10.000, 12.500) = 83 
    [12.500, 15.000) = 14 
    [15.000, 17.500) = 66 
    [17.500, 20.000) = 96 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.655 ms/op
     p(50.0000) =      3.035 ms/op
     p(90.0000) =      3.617 ms/op
     p(95.0000) =      3.850 ms/op
     p(99.0000) =      4.743 ms/op
     p(99.9000) =      8.629 ms/op
     p(99.9900) =     19.973 ms/op
     p(99.9990) =     20.546 ms/op
     p(99.9999) =     20.546 ms/op
    p(100.0000) =     20.546 ms/op


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
# Warmup Iteration   1: 3.982 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.182 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.941 ±(99.9%) 0.007 ms/op
Iteration   1: 2.953 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.742 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.494 ms/op
                 existUser·p0.95:   3.715 ms/op
                 existUser·p0.99:   4.620 ms/op
                 existUser·p0.999:  8.304 ms/op
                 existUser·p0.9999: 14.295 ms/op
                 existUser·p1.00:   15.024 ms/op

Iteration   2: 2.927 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.831 ms/op
                 existUser·p0.50:   2.904 ms/op
                 existUser·p0.90:   3.330 ms/op
                 existUser·p0.95:   3.547 ms/op
                 existUser·p0.99:   4.563 ms/op
                 existUser·p0.999:  8.520 ms/op
                 existUser·p0.9999: 15.780 ms/op
                 existUser·p1.00:   16.237 ms/op

Iteration   3: 2.914 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.802 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.269 ms/op
                 existUser·p0.95:   3.469 ms/op
                 existUser·p0.99:   4.252 ms/op
                 existUser·p0.999:  8.442 ms/op
                 existUser·p0.9999: 18.351 ms/op
                 existUser·p1.00:   19.005 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 327400
  mean =      2.931 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1129 
    [ 1.250,  2.500) = 30067 
    [ 2.500,  3.750) = 285557 
    [ 3.750,  5.000) = 8910 
    [ 5.000,  6.250) = 789 
    [ 6.250,  7.500) = 399 
    [ 7.500,  8.750) = 276 
    [ 8.750, 10.000) = 19 
    [10.000, 11.250) = 64 
    [11.250, 12.500) = 44 
    [12.500, 13.750) = 36 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 46 
    [16.250, 17.500) = 20 
    [17.500, 18.750) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.742 ms/op
     p(50.0000) =      2.908 ms/op
     p(90.0000) =      3.355 ms/op
     p(95.0000) =      3.604 ms/op
     p(99.0000) =      4.473 ms/op
     p(99.9000) =      8.448 ms/op
     p(99.9900) =     17.360 ms/op
     p(99.9990) =     18.585 ms/op
     p(99.9999) =     19.005 ms/op
    p(100.0000) =     19.005 ms/op


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
# Warmup Iteration   1: 4.271 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.214 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.059 ±(99.9%) 0.006 ms/op
Iteration   1: 3.100 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.827 ms/op
                 getUser·p0.50:   3.052 ms/op
                 getUser·p0.90:   3.703 ms/op
                 getUser·p0.95:   3.912 ms/op
                 getUser·p0.99:   4.784 ms/op
                 getUser·p0.999:  8.837 ms/op
                 getUser·p0.9999: 18.448 ms/op
                 getUser·p1.00:   18.612 ms/op

Iteration   2: 3.121 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.861 ms/op
                 getUser·p0.50:   3.097 ms/op
                 getUser·p0.90:   3.658 ms/op
                 getUser·p0.95:   3.850 ms/op
                 getUser·p0.99:   4.605 ms/op
                 getUser·p0.999:  8.348 ms/op
                 getUser·p0.9999: 14.983 ms/op
                 getUser·p1.00:   15.237 ms/op

Iteration   3: 3.094 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.768 ms/op
                 getUser·p0.50:   3.068 ms/op
                 getUser·p0.90:   3.527 ms/op
                 getUser·p0.95:   3.740 ms/op
                 getUser·p0.99:   4.383 ms/op
                 getUser·p0.999:  8.085 ms/op
                 getUser·p0.9999: 16.744 ms/op
                 getUser·p1.00:   17.105 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 309123
  mean =      3.105 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 486 
    [ 1.250,  2.500) = 14468 
    [ 2.500,  3.750) = 272653 
    [ 3.750,  5.000) = 19522 
    [ 5.000,  6.250) = 1064 
    [ 6.250,  7.500) = 433 
    [ 7.500,  8.750) = 257 
    [ 8.750, 10.000) = 46 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 28 
    [12.500, 13.750) = 36 
    [13.750, 15.000) = 47 
    [15.000, 16.250) = 20 
    [16.250, 17.500) = 31 
    [17.500, 18.750) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.768 ms/op
     p(50.0000) =      3.072 ms/op
     p(90.0000) =      3.637 ms/op
     p(95.0000) =      3.850 ms/op
     p(99.0000) =      4.588 ms/op
     p(99.9000) =      8.314 ms/op
     p(99.9900) =     17.760 ms/op
     p(99.9990) =     18.544 ms/op
     p(99.9999) =     18.612 ms/op
    p(100.0000) =     18.612 ms/op


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
# Warmup Iteration   1: 5.478 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 4.456 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.084 ±(99.9%) 0.012 ms/op
Iteration   1: 4.071 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.694 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   5.308 ms/op
                 listUser·p0.95:   6.095 ms/op
                 listUser·p0.99:   7.250 ms/op
                 listUser·p0.999:  14.835 ms/op
                 listUser·p0.9999: 22.053 ms/op
                 listUser·p1.00:   22.381 ms/op

Iteration   2: 4.026 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.880 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   4.923 ms/op
                 listUser·p0.95:   5.833 ms/op
                 listUser·p0.99:   7.045 ms/op
                 listUser·p0.999:  15.270 ms/op
                 listUser·p0.9999: 28.903 ms/op
                 listUser·p1.00:   29.458 ms/op

Iteration   3: 4.059 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.986 ms/op
                 listUser·p0.50:   3.879 ms/op
                 listUser·p0.90:   4.973 ms/op
                 listUser·p0.95:   5.800 ms/op
                 listUser·p0.99:   7.333 ms/op
                 listUser·p0.999:  17.826 ms/op
                 listUser·p0.9999: 24.747 ms/op
                 listUser·p1.00:   26.444 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 236735
  mean =      4.052 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3553 
    [ 2.500,  5.000) = 208813 
    [ 5.000,  7.500) = 22588 
    [ 7.500, 10.000) = 1260 
    [10.000, 12.500) = 160 
    [12.500, 15.000) = 67 
    [15.000, 17.500) = 96 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 84 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.694 ms/op
     p(50.0000) =      3.887 ms/op
     p(90.0000) =      5.038 ms/op
     p(95.0000) =      5.933 ms/op
     p(99.0000) =      7.198 ms/op
     p(99.9000) =     15.942 ms/op
     p(99.9900) =     27.448 ms/op
     p(99.9990) =     29.240 ms/op
     p(99.9999) =     29.458 ms/op
    p(100.0000) =     29.458 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.358 ± 3.648  ops/ms
ClientGrpc.existUser                       thrpt       3  11.035 ± 0.745  ops/ms
ClientGrpc.getUser                         thrpt       3  10.494 ± 0.875  ops/ms
ClientGrpc.listUser                        thrpt       3   7.906 ± 1.568  ops/ms
ClientGrpc.createUser                       avgt       3   3.108 ± 0.843   ms/op
ClientGrpc.existUser                        avgt       3   2.954 ± 0.283   ms/op
ClientGrpc.getUser                          avgt       3   3.057 ± 0.104   ms/op
ClientGrpc.listUser                         avgt       3   3.983 ± 0.399   ms/op
ClientGrpc.createUser                     sample  312306   3.073 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.655           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.035           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.617           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.850           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.743           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.629           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.973           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.546           ms/op
ClientGrpc.existUser                      sample  327400   2.931 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.742           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.908           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.355           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.604           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.473           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.448           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.360           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.005           ms/op
ClientGrpc.getUser                        sample  309123   3.105 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.768           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.072           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.637           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.850           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.588           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.314           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.760           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.612           ms/op
ClientGrpc.listUser                       sample  236735   4.052 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.694           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.887           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.038           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.933           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.198           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.942           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.448           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.458           ms/op
