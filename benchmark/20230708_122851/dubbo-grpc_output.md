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
# Warmup Iteration   1: 4.334 ops/ms
# Warmup Iteration   2: 9.069 ops/ms
# Warmup Iteration   3: 10.015 ops/ms
Iteration   1: 10.522 ops/ms
Iteration   2: 10.598 ops/ms
Iteration   3: 10.457 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.526 ±(99.9%) 1.291 ops/ms [Average]
  (min, avg, max) = (10.457, 10.526, 10.598), stdev = 0.071
  CI (99.9%): [9.235, 11.817] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.423 ops/ms
# Warmup Iteration   2: 10.296 ops/ms
# Warmup Iteration   3: 10.849 ops/ms
Iteration   1: 11.104 ops/ms
Iteration   2: 11.062 ops/ms
Iteration   3: 10.963 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.043 ±(99.9%) 1.318 ops/ms [Average]
  (min, avg, max) = (10.963, 11.043, 11.104), stdev = 0.072
  CI (99.9%): [9.725, 12.361] (assumes normal distribution)


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
# Warmup Iteration   1: 6.897 ops/ms
# Warmup Iteration   2: 9.967 ops/ms
# Warmup Iteration   3: 10.603 ops/ms
Iteration   1: 10.501 ops/ms
Iteration   2: 10.520 ops/ms
Iteration   3: 10.693 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.571 ±(99.9%) 1.928 ops/ms [Average]
  (min, avg, max) = (10.501, 10.571, 10.693), stdev = 0.106
  CI (99.9%): [8.644, 12.499] (assumes normal distribution)


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
# Warmup Iteration   1: 5.918 ops/ms
# Warmup Iteration   2: 7.616 ops/ms
# Warmup Iteration   3: 8.019 ops/ms
Iteration   1: 7.912 ops/ms
Iteration   2: 7.959 ops/ms
Iteration   3: 7.967 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.946 ±(99.9%) 0.545 ops/ms [Average]
  (min, avg, max) = (7.912, 7.946, 7.967), stdev = 0.030
  CI (99.9%): [7.401, 8.490] (assumes normal distribution)


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
# Warmup Iteration   1: 4.402 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.216 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.059 ±(99.9%) 0.004 ms/op
Iteration   1: 3.033 ±(99.9%) 0.002 ms/op
Iteration   2: 3.014 ±(99.9%) 0.002 ms/op
Iteration   3: 3.019 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.022 ±(99.9%) 0.181 ms/op [Average]
  (min, avg, max) = (3.014, 3.022, 3.033), stdev = 0.010
  CI (99.9%): [2.841, 3.202] (assumes normal distribution)


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
# Warmup Iteration   1: 3.944 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.019 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.879 ±(99.9%) 0.003 ms/op
Iteration   1: 2.927 ±(99.9%) 0.002 ms/op
Iteration   2: 2.787 ±(99.9%) 0.003 ms/op
Iteration   3: 2.918 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.877 ±(99.9%) 1.436 ms/op [Average]
  (min, avg, max) = (2.787, 2.877, 2.927), stdev = 0.079
  CI (99.9%): [1.441, 4.313] (assumes normal distribution)


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
# Warmup Iteration   1: 4.410 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.093 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.064 ±(99.9%) 0.002 ms/op
Iteration   1: 3.011 ±(99.9%) 0.003 ms/op
Iteration   2: 3.019 ±(99.9%) 0.004 ms/op
Iteration   3: 2.990 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.007 ±(99.9%) 0.271 ms/op [Average]
  (min, avg, max) = (2.990, 3.007, 3.019), stdev = 0.015
  CI (99.9%): [2.735, 3.278] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.952 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.096 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.026 ±(99.9%) 0.024 ms/op
Iteration   1: 3.888 ±(99.9%) 0.025 ms/op
Iteration   2: 4.090 ±(99.9%) 0.027 ms/op
Iteration   3: 3.881 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.953 ±(99.9%) 2.171 ms/op [Average]
  (min, avg, max) = (3.881, 3.953, 4.090), stdev = 0.119
  CI (99.9%): [1.782, 6.124] (assumes normal distribution)


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
# Warmup Iteration   1: 4.272 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.229 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.046 ±(99.9%) 0.006 ms/op
Iteration   1: 3.035 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.853 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.731 ms/op
                 createUser·p0.95:   3.953 ms/op
                 createUser·p0.99:   4.768 ms/op
                 createUser·p0.999:  10.551 ms/op
                 createUser·p0.9999: 20.281 ms/op
                 createUser·p1.00:   21.299 ms/op

Iteration   2: 2.990 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.331 ms/op
                 createUser·p0.50:   2.982 ms/op
                 createUser·p0.90:   3.420 ms/op
                 createUser·p0.95:   3.654 ms/op
                 createUser·p0.99:   4.358 ms/op
                 createUser·p0.999:  6.922 ms/op
                 createUser·p0.9999: 15.742 ms/op
                 createUser·p1.00:   16.253 ms/op

Iteration   3: 3.076 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.694 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.604 ms/op
                 createUser·p0.95:   3.838 ms/op
                 createUser·p0.99:   4.358 ms/op
                 createUser·p0.999:  7.375 ms/op
                 createUser·p0.9999: 18.219 ms/op
                 createUser·p1.00:   18.514 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 316524
  mean =      3.033 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26696 
    [ 2.500,  5.000) = 288195 
    [ 5.000,  7.500) = 1196 
    [ 7.500, 10.000) = 151 
    [10.000, 12.500) = 47 
    [12.500, 15.000) = 81 
    [15.000, 17.500) = 98 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.331 ms/op
     p(50.0000) =      3.011 ms/op
     p(90.0000) =      3.584 ms/op
     p(95.0000) =      3.854 ms/op
     p(99.0000) =      4.497 ms/op
     p(99.9000) =      9.116 ms/op
     p(99.9900) =     19.269 ms/op
     p(99.9990) =     21.157 ms/op
     p(99.9999) =     21.299 ms/op
    p(100.0000) =     21.299 ms/op


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
# Warmup Iteration   1: 3.935 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.055 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.926 ±(99.9%) 0.005 ms/op
Iteration   1: 2.938 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.802 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.412 ms/op
                 existUser·p0.95:   3.641 ms/op
                 existUser·p0.99:   4.358 ms/op
                 existUser·p0.999:  8.885 ms/op
                 existUser·p0.9999: 13.420 ms/op
                 existUser·p1.00:   14.025 ms/op

Iteration   2: 2.992 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.927 ms/op
                 existUser·p0.50:   2.949 ms/op
                 existUser·p0.90:   3.531 ms/op
                 existUser·p0.95:   3.678 ms/op
                 existUser·p0.99:   4.096 ms/op
                 existUser·p0.999:  6.154 ms/op
                 existUser·p0.9999: 14.696 ms/op
                 existUser·p1.00:   14.909 ms/op

Iteration   3: 2.934 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.812 ms/op
                 existUser·p0.50:   2.920 ms/op
                 existUser·p0.90:   3.514 ms/op
                 existUser·p0.95:   3.690 ms/op
                 existUser·p0.99:   4.227 ms/op
                 existUser·p0.999:  6.955 ms/op
                 existUser·p0.9999: 15.891 ms/op
                 existUser·p1.00:   17.170 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 324702
  mean =      2.955 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1220 
    [ 1.250,  2.500) = 32270 
    [ 2.500,  3.750) = 279409 
    [ 3.750,  5.000) = 10864 
    [ 5.000,  6.250) = 447 
    [ 6.250,  7.500) = 252 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 35 
    [10.000, 11.250) = 13 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 69 
    [13.750, 15.000) = 59 
    [15.000, 16.250) = 24 
    [16.250, 17.500) = 8 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.802 ms/op
     p(50.0000) =      2.925 ms/op
     p(90.0000) =      3.494 ms/op
     p(95.0000) =      3.674 ms/op
     p(99.0000) =      4.227 ms/op
     p(99.9000) =      6.939 ms/op
     p(99.9900) =     15.100 ms/op
     p(99.9990) =     17.170 ms/op
     p(99.9999) =     17.170 ms/op
    p(100.0000) =     17.170 ms/op


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
# Warmup Iteration   1: 4.188 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.167 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.046 ±(99.9%) 0.006 ms/op
Iteration   1: 2.967 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.487 ms/op
                 getUser·p0.50:   2.957 ms/op
                 getUser·p0.90:   3.420 ms/op
                 getUser·p0.95:   3.760 ms/op
                 getUser·p0.99:   4.809 ms/op
                 getUser·p0.999:  7.694 ms/op
                 getUser·p0.9999: 15.090 ms/op
                 getUser·p1.00:   15.352 ms/op

Iteration   2: 3.036 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.703 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.621 ms/op
                 getUser·p0.95:   3.830 ms/op
                 getUser·p0.99:   4.440 ms/op
                 getUser·p0.999:  10.060 ms/op
                 getUser·p0.9999: 22.346 ms/op
                 getUser·p1.00:   24.117 ms/op

Iteration   3: 3.045 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.667 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.543 ms/op
                 getUser·p0.95:   3.744 ms/op
                 getUser·p0.99:   4.391 ms/op
                 getUser·p0.999:  7.724 ms/op
                 getUser·p0.9999: 24.674 ms/op
                 getUser·p1.00:   26.477 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 318161
  mean =      3.016 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28651 
    [ 2.500,  5.000) = 287661 
    [ 5.000,  7.500) = 1478 
    [ 7.500, 10.000) = 133 
    [10.000, 12.500) = 37 
    [12.500, 15.000) = 57 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.487 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.543 ms/op
     p(95.0000) =      3.785 ms/op
     p(99.0000) =      4.604 ms/op
     p(99.9000) =      7.881 ms/op
     p(99.9900) =     23.894 ms/op
     p(99.9990) =     26.301 ms/op
     p(99.9999) =     26.477 ms/op
    p(100.0000) =     26.477 ms/op


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
# Warmup Iteration   1: 5.616 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 4.090 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.121 ±(99.9%) 0.011 ms/op
Iteration   1: 4.082 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.579 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   5.243 ms/op
                 listUser·p0.95:   5.931 ms/op
                 listUser·p0.99:   7.184 ms/op
                 listUser·p0.999:  13.314 ms/op
                 listUser·p0.9999: 17.143 ms/op
                 listUser·p1.00:   17.760 ms/op

Iteration   2: 3.964 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.609 ms/op
                 listUser·p0.50:   3.805 ms/op
                 listUser·p0.90:   5.046 ms/op
                 listUser·p0.95:   5.906 ms/op
                 listUser·p0.99:   7.063 ms/op
                 listUser·p0.999:  14.767 ms/op
                 listUser·p0.9999: 17.196 ms/op
                 listUser·p1.00:   18.219 ms/op

Iteration   3: 4.047 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.912 ms/op
                 listUser·p0.50:   3.875 ms/op
                 listUser·p0.90:   5.087 ms/op
                 listUser·p0.95:   5.710 ms/op
                 listUser·p0.99:   6.980 ms/op
                 listUser·p0.999:  15.925 ms/op
                 listUser·p0.9999: 20.424 ms/op
                 listUser·p1.00:   22.381 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 238032
  mean =      4.030 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2418 
    [ 2.500,  5.000) = 208778 
    [ 5.000,  7.500) = 25319 
    [ 7.500, 10.000) = 1072 
    [10.000, 12.500) = 81 
    [12.500, 15.000) = 127 
    [15.000, 17.500) = 171 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.609 ms/op
     p(50.0000) =      3.858 ms/op
     p(90.0000) =      5.128 ms/op
     p(95.0000) =      5.857 ms/op
     p(99.0000) =      7.092 ms/op
     p(99.9000) =     14.991 ms/op
     p(99.9900) =     19.313 ms/op
     p(99.9990) =     20.934 ms/op
     p(99.9999) =     22.381 ms/op
    p(100.0000) =     22.381 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.526 ± 1.291  ops/ms
ClientGrpc.existUser                       thrpt       3  11.043 ± 1.318  ops/ms
ClientGrpc.getUser                         thrpt       3  10.571 ± 1.928  ops/ms
ClientGrpc.listUser                        thrpt       3   7.946 ± 0.545  ops/ms
ClientGrpc.createUser                       avgt       3   3.022 ± 0.181   ms/op
ClientGrpc.existUser                        avgt       3   2.877 ± 1.436   ms/op
ClientGrpc.getUser                          avgt       3   3.007 ± 0.271   ms/op
ClientGrpc.listUser                         avgt       3   3.953 ± 2.171   ms/op
ClientGrpc.createUser                     sample  316524   3.033 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.331           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.011           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.584           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.854           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.497           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.116           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.269           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.299           ms/op
ClientGrpc.existUser                      sample  324702   2.955 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.802           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.925           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.494           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.674           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.227           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.939           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.100           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.170           ms/op
ClientGrpc.getUser                        sample  318161   3.016 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.487           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.990           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.543           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.785           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.604           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.881           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.894           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          26.477           ms/op
ClientGrpc.listUser                       sample  238032   4.030 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.609           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.858           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.128           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.857           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.092           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.991           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.313           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.381           ms/op
