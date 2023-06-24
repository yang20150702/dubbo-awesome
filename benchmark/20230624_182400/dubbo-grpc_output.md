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
# Warmup Iteration   1: 5.091 ops/ms
# Warmup Iteration   2: 9.071 ops/ms
# Warmup Iteration   3: 10.342 ops/ms
Iteration   1: 10.969 ops/ms
Iteration   2: 10.717 ops/ms
Iteration   3: 10.546 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.744 ±(99.9%) 3.883 ops/ms [Average]
  (min, avg, max) = (10.546, 10.744, 10.969), stdev = 0.213
  CI (99.9%): [6.861, 14.628] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 8.153 ops/ms
# Warmup Iteration   2: 10.854 ops/ms
# Warmup Iteration   3: 11.475 ops/ms
Iteration   1: 11.179 ops/ms
Iteration   2: 11.160 ops/ms
Iteration   3: 11.040 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.126 ±(99.9%) 1.374 ops/ms [Average]
  (min, avg, max) = (11.040, 11.126, 11.179), stdev = 0.075
  CI (99.9%): [9.752, 12.500] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 6.897 ops/ms
# Warmup Iteration   2: 10.132 ops/ms
# Warmup Iteration   3: 10.553 ops/ms
Iteration   1: 10.545 ops/ms
Iteration   2: 10.412 ops/ms
Iteration   3: 10.483 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.480 ±(99.9%) 1.209 ops/ms [Average]
  (min, avg, max) = (10.412, 10.480, 10.545), stdev = 0.066
  CI (99.9%): [9.271, 11.689] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.636 ops/ms
# Warmup Iteration   2: 7.600 ops/ms
# Warmup Iteration   3: 7.993 ops/ms
Iteration   1: 8.127 ops/ms
Iteration   2: 7.979 ops/ms
Iteration   3: 8.030 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.045 ±(99.9%) 1.366 ops/ms [Average]
  (min, avg, max) = (7.979, 8.045, 8.127), stdev = 0.075
  CI (99.9%): [6.679, 9.412] (assumes normal distribution)


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
# Warmup Iteration   1: 4.190 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.171 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.089 ±(99.9%) 0.003 ms/op
Iteration   1: 3.028 ±(99.9%) 0.007 ms/op
Iteration   2: 3.043 ±(99.9%) 0.002 ms/op
Iteration   3: 2.952 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.007 ±(99.9%) 0.889 ms/op [Average]
  (min, avg, max) = (2.952, 3.007, 3.043), stdev = 0.049
  CI (99.9%): [2.119, 3.896] (assumes normal distribution)


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
# Warmup Iteration   1: 3.583 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.950 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.912 ±(99.9%) 0.003 ms/op
Iteration   1: 2.928 ±(99.9%) 0.003 ms/op
Iteration   2: 2.889 ±(99.9%) 0.003 ms/op
Iteration   3: 2.825 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.881 ±(99.9%) 0.951 ms/op [Average]
  (min, avg, max) = (2.825, 2.881, 2.928), stdev = 0.052
  CI (99.9%): [1.930, 3.831] (assumes normal distribution)


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
# Warmup Iteration   1: 4.027 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 3.098 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.019 ±(99.9%) 0.003 ms/op
Iteration   1: 3.057 ±(99.9%) 0.003 ms/op
Iteration   2: 2.965 ±(99.9%) 0.003 ms/op
Iteration   3: 2.950 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.991 ±(99.9%) 1.056 ms/op [Average]
  (min, avg, max) = (2.950, 2.991, 3.057), stdev = 0.058
  CI (99.9%): [1.934, 4.047] (assumes normal distribution)


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
# Warmup Iteration   1: 5.288 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.869 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.923 ±(99.9%) 0.023 ms/op
Iteration   1: 3.875 ±(99.9%) 0.012 ms/op
Iteration   2: 3.841 ±(99.9%) 0.017 ms/op
Iteration   3: 3.814 ±(99.9%) 0.029 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.843 ±(99.9%) 0.559 ms/op [Average]
  (min, avg, max) = (3.814, 3.843, 3.875), stdev = 0.031
  CI (99.9%): [3.284, 4.402] (assumes normal distribution)


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
# Warmup Iteration   1: 4.066 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.141 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.348 ±(99.9%) 0.012 ms/op
Iteration   1: 2.949 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.772 ms/op
                 createUser·p0.50:   2.941 ms/op
                 createUser·p0.90:   3.400 ms/op
                 createUser·p0.95:   3.686 ms/op
                 createUser·p0.99:   4.440 ms/op
                 createUser·p0.999:  13.191 ms/op
                 createUser·p0.9999: 18.491 ms/op
                 createUser·p1.00:   18.743 ms/op

Iteration   2: 2.918 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.581 ms/op
                 createUser·p0.50:   2.937 ms/op
                 createUser·p0.90:   3.334 ms/op
                 createUser·p0.95:   3.527 ms/op
                 createUser·p0.99:   4.268 ms/op
                 createUser·p0.999:  6.973 ms/op
                 createUser·p0.9999: 19.077 ms/op
                 createUser·p1.00:   19.890 ms/op

Iteration   3: 2.961 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.302 ms/op
                 createUser·p0.50:   2.966 ms/op
                 createUser·p0.90:   3.469 ms/op
                 createUser·p0.95:   3.686 ms/op
                 createUser·p0.99:   4.342 ms/op
                 createUser·p0.999:  11.043 ms/op
                 createUser·p0.9999: 22.452 ms/op
                 createUser·p1.00:   22.872 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 326262
  mean =      2.942 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 32858 
    [ 2.500,  5.000) = 292320 
    [ 5.000,  7.500) = 717 
    [ 7.500, 10.000) = 19 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 60 
    [15.000, 17.500) = 75 
    [17.500, 20.000) = 97 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.302 ms/op
     p(50.0000) =      2.949 ms/op
     p(90.0000) =      3.396 ms/op
     p(95.0000) =      3.637 ms/op
     p(99.0000) =      4.350 ms/op
     p(99.9000) =     10.142 ms/op
     p(99.9900) =     21.135 ms/op
     p(99.9990) =     22.872 ms/op
     p(99.9999) =     22.872 ms/op
    p(100.0000) =     22.872 ms/op


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
# Warmup Iteration   1: 3.913 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 2.937 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.971 ±(99.9%) 0.005 ms/op
Iteration   1: 2.871 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.687 ms/op
                 existUser·p0.50:   2.875 ms/op
                 existUser·p0.90:   3.334 ms/op
                 existUser·p0.95:   3.564 ms/op
                 existUser·p0.99:   4.276 ms/op
                 existUser·p0.999:  6.108 ms/op
                 existUser·p0.9999: 10.767 ms/op
                 existUser·p1.00:   13.451 ms/op

Iteration   2: 2.871 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.769 ms/op
                 existUser·p0.50:   2.863 ms/op
                 existUser·p0.90:   3.289 ms/op
                 existUser·p0.95:   3.576 ms/op
                 existUser·p0.99:   4.366 ms/op
                 existUser·p0.999:  5.939 ms/op
                 existUser·p0.9999: 12.040 ms/op
                 existUser·p1.00:   14.090 ms/op

Iteration   3: 2.857 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.502 ms/op
                 existUser·p0.50:   2.879 ms/op
                 existUser·p0.90:   3.355 ms/op
                 existUser·p0.95:   3.559 ms/op
                 existUser·p0.99:   4.260 ms/op
                 existUser·p0.999:  9.095 ms/op
                 existUser·p0.9999: 14.906 ms/op
                 existUser·p1.00:   15.352 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 334833
  mean =      2.866 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3805 
    [ 1.250,  2.500) = 38840 
    [ 2.500,  3.750) = 282708 
    [ 3.750,  5.000) = 8433 
    [ 5.000,  6.250) = 684 
    [ 6.250,  7.500) = 120 
    [ 7.500,  8.750) = 14 
    [ 8.750, 10.000) = 36 
    [10.000, 11.250) = 62 
    [11.250, 12.500) = 62 
    [12.500, 13.750) = 19 
    [13.750, 15.000) = 43 
    [15.000, 16.250) = 7 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.502 ms/op
     p(50.0000) =      2.871 ms/op
     p(90.0000) =      3.330 ms/op
     p(95.0000) =      3.564 ms/op
     p(99.0000) =      4.309 ms/op
     p(99.9000) =      6.431 ms/op
     p(99.9900) =     14.041 ms/op
     p(99.9990) =     15.220 ms/op
     p(99.9999) =     15.352 ms/op
    p(100.0000) =     15.352 ms/op


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
# Warmup Iteration   1: 3.835 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.142 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.034 ±(99.9%) 0.005 ms/op
Iteration   1: 2.987 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.794 ms/op
                 getUser·p0.50:   2.974 ms/op
                 getUser·p0.90:   3.465 ms/op
                 getUser·p0.95:   3.760 ms/op
                 getUser·p0.99:   4.547 ms/op
                 getUser·p0.999:  8.262 ms/op
                 getUser·p0.9999: 11.502 ms/op
                 getUser·p1.00:   11.829 ms/op

Iteration   2: 2.987 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.459 ms/op
                 getUser·p0.50:   2.978 ms/op
                 getUser·p0.90:   3.351 ms/op
                 getUser·p0.95:   3.547 ms/op
                 getUser·p0.99:   4.170 ms/op
                 getUser·p0.999:  7.376 ms/op
                 getUser·p0.9999: 30.638 ms/op
                 getUser·p1.00:   30.999 ms/op

Iteration   3: 2.980 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.797 ms/op
                 getUser·p0.50:   2.970 ms/op
                 getUser·p0.90:   3.486 ms/op
                 getUser·p0.95:   3.658 ms/op
                 getUser·p0.99:   4.497 ms/op
                 getUser·p0.999:  6.054 ms/op
                 getUser·p0.9999: 14.291 ms/op
                 getUser·p1.00:   14.729 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 321518
  mean =      2.985 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24361 
    [ 2.500,  5.000) = 295836 
    [ 5.000,  7.500) = 1043 
    [ 7.500, 10.000) = 86 
    [10.000, 12.500) = 102 
    [12.500, 15.000) = 58 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 7 
    [30.000, 32.500) = 25 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.459 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.432 ms/op
     p(95.0000) =      3.658 ms/op
     p(99.0000) =      4.448 ms/op
     p(99.9000) =      6.906 ms/op
     p(99.9900) =     27.555 ms/op
     p(99.9990) =     30.853 ms/op
     p(99.9999) =     30.999 ms/op
    p(100.0000) =     30.999 ms/op


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
# Warmup Iteration   1: 4.649 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.002 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.930 ±(99.9%) 0.011 ms/op
Iteration   1: 3.915 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.298 ms/op
                 listUser·p0.50:   3.772 ms/op
                 listUser·p0.90:   4.727 ms/op
                 listUser·p0.95:   5.589 ms/op
                 listUser·p0.99:   7.004 ms/op
                 listUser·p0.999:  13.749 ms/op
                 listUser·p0.9999: 15.779 ms/op
                 listUser·p1.00:   16.007 ms/op

Iteration   2: 3.904 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.513 ms/op
                 listUser·p0.50:   3.744 ms/op
                 listUser·p0.90:   4.858 ms/op
                 listUser·p0.95:   5.743 ms/op
                 listUser·p0.99:   6.783 ms/op
                 listUser·p0.999:  15.487 ms/op
                 listUser·p0.9999: 22.997 ms/op
                 listUser·p1.00:   23.364 ms/op

Iteration   3: 3.905 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.959 ms/op
                 listUser·p0.50:   3.772 ms/op
                 listUser·p0.90:   4.768 ms/op
                 listUser·p0.95:   5.521 ms/op
                 listUser·p0.99:   6.865 ms/op
                 listUser·p0.999:  14.696 ms/op
                 listUser·p0.9999: 21.358 ms/op
                 listUser·p1.00:   21.922 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 245785
  mean =      3.908 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3893 
    [ 2.500,  5.000) = 221916 
    [ 5.000,  7.500) = 18713 
    [ 7.500, 10.000) = 801 
    [10.000, 12.500) = 56 
    [12.500, 15.000) = 197 
    [15.000, 17.500) = 139 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.959 ms/op
     p(50.0000) =      3.764 ms/op
     p(90.0000) =      4.792 ms/op
     p(95.0000) =      5.628 ms/op
     p(99.0000) =      6.881 ms/op
     p(99.9000) =     14.696 ms/op
     p(99.9900) =     22.558 ms/op
     p(99.9990) =     23.319 ms/op
     p(99.9999) =     23.364 ms/op
    p(100.0000) =     23.364 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.744 ± 3.883  ops/ms
ClientGrpc.existUser                       thrpt       3  11.126 ± 1.374  ops/ms
ClientGrpc.getUser                         thrpt       3  10.480 ± 1.209  ops/ms
ClientGrpc.listUser                        thrpt       3   8.045 ± 1.366  ops/ms
ClientGrpc.createUser                       avgt       3   3.007 ± 0.889   ms/op
ClientGrpc.existUser                        avgt       3   2.881 ± 0.951   ms/op
ClientGrpc.getUser                          avgt       3   2.991 ± 1.056   ms/op
ClientGrpc.listUser                         avgt       3   3.843 ± 0.559   ms/op
ClientGrpc.createUser                     sample  326262   2.942 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.302           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.949           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.396           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.637           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.350           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.142           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.135           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.872           ms/op
ClientGrpc.existUser                      sample  334833   2.866 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.502           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.871           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.330           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.564           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.309           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.431           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.041           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          15.352           ms/op
ClientGrpc.getUser                        sample  321518   2.985 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.459           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.974           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.432           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.658           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.448           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.906           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          27.555           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          30.999           ms/op
ClientGrpc.listUser                       sample  245785   3.908 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.959           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.764           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.792           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.628           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.881           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.696           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.558           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.364           ms/op
