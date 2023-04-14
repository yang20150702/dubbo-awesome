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
# Warmup Iteration   1: 4.789 ops/ms
# Warmup Iteration   2: 9.359 ops/ms
# Warmup Iteration   3: 10.342 ops/ms
Iteration   1: 10.500 ops/ms
Iteration   2: 10.831 ops/ms
Iteration   3: 10.680 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.670 ±(99.9%) 3.027 ops/ms [Average]
  (min, avg, max) = (10.500, 10.670, 10.831), stdev = 0.166
  CI (99.9%): [7.644, 13.697] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.763 ops/ms
# Warmup Iteration   2: 10.950 ops/ms
# Warmup Iteration   3: 11.547 ops/ms
Iteration   1: 11.289 ops/ms
Iteration   2: 11.378 ops/ms
Iteration   3: 11.238 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.302 ±(99.9%) 1.295 ops/ms [Average]
  (min, avg, max) = (11.238, 11.302, 11.378), stdev = 0.071
  CI (99.9%): [10.006, 12.597] (assumes normal distribution)


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
# Warmup Iteration   1: 8.188 ops/ms
# Warmup Iteration   2: 10.422 ops/ms
# Warmup Iteration   3: 10.753 ops/ms
Iteration   1: 10.862 ops/ms
Iteration   2: 10.880 ops/ms
Iteration   3: 10.977 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.906 ±(99.9%) 1.128 ops/ms [Average]
  (min, avg, max) = (10.862, 10.906, 10.977), stdev = 0.062
  CI (99.9%): [9.778, 12.034] (assumes normal distribution)


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
# Warmup Iteration   1: 6.165 ops/ms
# Warmup Iteration   2: 7.901 ops/ms
# Warmup Iteration   3: 8.200 ops/ms
Iteration   1: 8.048 ops/ms
Iteration   2: 8.246 ops/ms
Iteration   3: 8.239 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.178 ±(99.9%) 2.056 ops/ms [Average]
  (min, avg, max) = (8.048, 8.178, 8.246), stdev = 0.113
  CI (99.9%): [6.122, 10.233] (assumes normal distribution)


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
# Warmup Iteration   1: 3.931 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.061 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.053 ±(99.9%) 0.004 ms/op
Iteration   1: 3.016 ±(99.9%) 0.003 ms/op
Iteration   2: 3.044 ±(99.9%) 0.002 ms/op
Iteration   3: 2.976 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.012 ±(99.9%) 0.622 ms/op [Average]
  (min, avg, max) = (2.976, 3.012, 3.044), stdev = 0.034
  CI (99.9%): [2.390, 3.634] (assumes normal distribution)


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
# Warmup Iteration   1: 3.817 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.897 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.879 ±(99.9%) 0.003 ms/op
Iteration   1: 2.845 ±(99.9%) 0.003 ms/op
Iteration   2: 2.821 ±(99.9%) 0.004 ms/op
Iteration   3: 2.832 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.833 ±(99.9%) 0.223 ms/op [Average]
  (min, avg, max) = (2.821, 2.833, 2.845), stdev = 0.012
  CI (99.9%): [2.610, 3.056] (assumes normal distribution)


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
# Warmup Iteration   1: 3.822 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.013 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.962 ±(99.9%) 0.003 ms/op
Iteration   1: 2.978 ±(99.9%) 0.002 ms/op
Iteration   2: 2.990 ±(99.9%) 0.003 ms/op
Iteration   3: 2.990 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.986 ±(99.9%) 0.121 ms/op [Average]
  (min, avg, max) = (2.978, 2.986, 2.990), stdev = 0.007
  CI (99.9%): [2.865, 3.106] (assumes normal distribution)


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
# Warmup Iteration   1: 4.888 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.899 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.850 ±(99.9%) 0.009 ms/op
Iteration   1: 3.806 ±(99.9%) 0.014 ms/op
Iteration   2: 3.841 ±(99.9%) 0.011 ms/op
Iteration   3: 3.852 ±(99.9%) 0.036 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.833 ±(99.9%) 0.438 ms/op [Average]
  (min, avg, max) = (3.806, 3.833, 3.852), stdev = 0.024
  CI (99.9%): [3.394, 4.271] (assumes normal distribution)


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
# Warmup Iteration   1: 4.007 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.145 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.983 ±(99.9%) 0.006 ms/op
Iteration   1: 2.944 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.822 ms/op
                 createUser·p0.50:   2.933 ms/op
                 createUser·p0.90:   3.330 ms/op
                 createUser·p0.95:   3.490 ms/op
                 createUser·p0.99:   4.293 ms/op
                 createUser·p0.999:  7.574 ms/op
                 createUser·p0.9999: 14.633 ms/op
                 createUser·p1.00:   15.024 ms/op

Iteration   2: 2.977 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.748 ms/op
                 createUser·p0.50:   2.978 ms/op
                 createUser·p0.90:   3.498 ms/op
                 createUser·p0.95:   3.756 ms/op
                 createUser·p0.99:   4.522 ms/op
                 createUser·p0.999:  7.676 ms/op
                 createUser·p0.9999: 12.923 ms/op
                 createUser·p1.00:   13.271 ms/op

Iteration   3: 2.996 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.681 ms/op
                 createUser·p0.50:   2.974 ms/op
                 createUser·p0.90:   3.539 ms/op
                 createUser·p0.95:   3.752 ms/op
                 createUser·p0.99:   4.588 ms/op
                 createUser·p0.999:  8.922 ms/op
                 createUser·p0.9999: 26.127 ms/op
                 createUser·p1.00:   26.608 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 323020
  mean =      2.972 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29935 
    [ 2.500,  5.000) = 291687 
    [ 5.000,  7.500) = 998 
    [ 7.500, 10.000) = 168 
    [10.000, 12.500) = 68 
    [12.500, 15.000) = 99 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.681 ms/op
     p(50.0000) =      2.957 ms/op
     p(90.0000) =      3.449 ms/op
     p(95.0000) =      3.678 ms/op
     p(99.0000) =      4.473 ms/op
     p(99.9000) =      8.241 ms/op
     p(99.9900) =     24.795 ms/op
     p(99.9990) =     26.371 ms/op
     p(99.9999) =     26.608 ms/op
    p(100.0000) =     26.608 ms/op


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
# Warmup Iteration   1: 3.579 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 2.960 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.854 ±(99.9%) 0.006 ms/op
Iteration   1: 2.922 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.666 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.482 ms/op
                 existUser·p0.95:   3.690 ms/op
                 existUser·p0.99:   4.268 ms/op
                 existUser·p0.999:  7.277 ms/op
                 existUser·p0.9999: 15.550 ms/op
                 existUser·p1.00:   15.925 ms/op

Iteration   2: 2.863 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.777 ms/op
                 existUser·p0.50:   2.851 ms/op
                 existUser·p0.90:   3.224 ms/op
                 existUser·p0.95:   3.465 ms/op
                 existUser·p0.99:   4.518 ms/op
                 existUser·p0.999:  7.160 ms/op
                 existUser·p0.9999: 14.740 ms/op
                 existUser·p1.00:   15.254 ms/op

Iteration   3: 2.896 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.496 ms/op
                 existUser·p0.50:   2.863 ms/op
                 existUser·p0.90:   3.455 ms/op
                 existUser·p0.95:   3.633 ms/op
                 existUser·p0.99:   4.473 ms/op
                 existUser·p0.999:  7.975 ms/op
                 existUser·p0.9999: 15.826 ms/op
                 existUser·p1.00:   16.843 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 331499
  mean =      2.894 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2183 
    [ 1.250,  2.500) = 39044 
    [ 2.500,  3.750) = 279336 
    [ 3.750,  5.000) = 9527 
    [ 5.000,  6.250) = 849 
    [ 6.250,  7.500) = 266 
    [ 7.500,  8.750) = 84 
    [ 8.750, 10.000) = 22 
    [10.000, 11.250) = 22 
    [11.250, 12.500) = 24 
    [12.500, 13.750) = 28 
    [13.750, 15.000) = 40 
    [15.000, 16.250) = 73 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.496 ms/op
     p(50.0000) =      2.871 ms/op
     p(90.0000) =      3.400 ms/op
     p(95.0000) =      3.629 ms/op
     p(99.0000) =      4.440 ms/op
     p(99.9000) =      7.193 ms/op
     p(99.9900) =     15.562 ms/op
     p(99.9990) =     16.090 ms/op
     p(99.9999) =     16.843 ms/op
    p(100.0000) =     16.843 ms/op


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
# Warmup Iteration   1: 3.788 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.053 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.040 ±(99.9%) 0.006 ms/op
Iteration   1: 2.986 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.863 ms/op
                 getUser·p0.50:   2.986 ms/op
                 getUser·p0.90:   3.445 ms/op
                 getUser·p0.95:   3.658 ms/op
                 getUser·p0.99:   4.375 ms/op
                 getUser·p0.999:  6.119 ms/op
                 getUser·p0.9999: 14.837 ms/op
                 getUser·p1.00:   15.122 ms/op

Iteration   2: 2.970 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.554 ms/op
                 getUser·p0.50:   2.970 ms/op
                 getUser·p0.90:   3.449 ms/op
                 getUser·p0.95:   3.744 ms/op
                 getUser·p0.99:   4.391 ms/op
                 getUser·p0.999:  7.235 ms/op
                 getUser·p0.9999: 14.826 ms/op
                 getUser·p1.00:   15.286 ms/op

Iteration   3: 2.995 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.545 ms/op
                 getUser·p0.50:   2.982 ms/op
                 getUser·p0.90:   3.486 ms/op
                 getUser·p0.95:   3.723 ms/op
                 getUser·p0.99:   4.424 ms/op
                 getUser·p0.999:  11.161 ms/op
                 getUser·p0.9999: 28.355 ms/op
                 getUser·p1.00:   28.672 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 321595
  mean =      2.983 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27378 
    [ 2.500,  5.000) = 292979 
    [ 5.000,  7.500) = 970 
    [ 7.500, 10.000) = 45 
    [10.000, 12.500) = 88 
    [12.500, 15.000) = 65 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.545 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.461 ms/op
     p(95.0000) =      3.711 ms/op
     p(99.0000) =      4.399 ms/op
     p(99.9000) =      6.855 ms/op
     p(99.9900) =     25.026 ms/op
     p(99.9990) =     28.560 ms/op
     p(99.9999) =     28.672 ms/op
    p(100.0000) =     28.672 ms/op


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
# Warmup Iteration   1: 5.023 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.941 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.922 ±(99.9%) 0.011 ms/op
Iteration   1: 3.922 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.962 ms/op
                 listUser·p0.50:   3.772 ms/op
                 listUser·p0.90:   4.760 ms/op
                 listUser·p0.95:   5.464 ms/op
                 listUser·p0.99:   6.934 ms/op
                 listUser·p0.999:  12.574 ms/op
                 listUser·p0.9999: 16.165 ms/op
                 listUser·p1.00:   16.941 ms/op

Iteration   2: 3.934 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.081 ms/op
                 listUser·p0.50:   3.781 ms/op
                 listUser·p0.90:   4.981 ms/op
                 listUser·p0.95:   5.710 ms/op
                 listUser·p0.99:   6.652 ms/op
                 listUser·p0.999:  14.044 ms/op
                 listUser·p0.9999: 16.298 ms/op
                 listUser·p1.00:   16.630 ms/op

Iteration   3: 3.893 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.393 ms/op
                 listUser·p0.50:   3.764 ms/op
                 listUser·p0.90:   4.571 ms/op
                 listUser·p0.95:   5.382 ms/op
                 listUser·p0.99:   6.794 ms/op
                 listUser·p0.999:  16.152 ms/op
                 listUser·p0.9999: 22.137 ms/op
                 listUser·p1.00:   22.381 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 244991
  mean =      3.916 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3625 
    [ 2.500,  5.000) = 221496 
    [ 5.000,  7.500) = 18583 
    [ 7.500, 10.000) = 739 
    [10.000, 12.500) = 184 
    [12.500, 15.000) = 209 
    [15.000, 17.500) = 87 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.962 ms/op
     p(50.0000) =      3.772 ms/op
     p(90.0000) =      4.792 ms/op
     p(95.0000) =      5.530 ms/op
     p(99.0000) =      6.783 ms/op
     p(99.9000) =     13.566 ms/op
     p(99.9900) =     20.464 ms/op
     p(99.9990) =     22.292 ms/op
     p(99.9999) =     22.381 ms/op
    p(100.0000) =     22.381 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.670 ± 3.027  ops/ms
ClientGrpc.existUser                       thrpt       3  11.302 ± 1.295  ops/ms
ClientGrpc.getUser                         thrpt       3  10.906 ± 1.128  ops/ms
ClientGrpc.listUser                        thrpt       3   8.178 ± 2.056  ops/ms
ClientGrpc.createUser                       avgt       3   3.012 ± 0.622   ms/op
ClientGrpc.existUser                        avgt       3   2.833 ± 0.223   ms/op
ClientGrpc.getUser                          avgt       3   2.986 ± 0.121   ms/op
ClientGrpc.listUser                         avgt       3   3.833 ± 0.438   ms/op
ClientGrpc.createUser                     sample  323020   2.972 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.681           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.957           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.449           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.678           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.473           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.241           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.795           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.608           ms/op
ClientGrpc.existUser                      sample  331499   2.894 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.496           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.871           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.400           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.629           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.440           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.193           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.562           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.843           ms/op
ClientGrpc.getUser                        sample  321595   2.983 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.545           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.978           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.461           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.711           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.399           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.855           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          25.026           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          28.672           ms/op
ClientGrpc.listUser                       sample  244991   3.916 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.962           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.772           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.792           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.530           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.783           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.566           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.464           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.381           ms/op
