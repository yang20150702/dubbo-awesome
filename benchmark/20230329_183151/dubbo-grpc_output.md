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
# Warmup Iteration   1: 4.388 ops/ms
# Warmup Iteration   2: 8.761 ops/ms
# Warmup Iteration   3: 10.224 ops/ms
Iteration   1: 10.692 ops/ms
Iteration   2: 10.595 ops/ms
Iteration   3: 10.536 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.608 ±(99.9%) 1.436 ops/ms [Average]
  (min, avg, max) = (10.536, 10.608, 10.692), stdev = 0.079
  CI (99.9%): [9.172, 12.044] (assumes normal distribution)


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
# Warmup Iteration   1: 7.616 ops/ms
# Warmup Iteration   2: 10.786 ops/ms
# Warmup Iteration   3: 10.964 ops/ms
Iteration   1: 11.219 ops/ms
Iteration   2: 11.278 ops/ms
Iteration   3: 11.197 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.231 ±(99.9%) 0.771 ops/ms [Average]
  (min, avg, max) = (11.197, 11.231, 11.278), stdev = 0.042
  CI (99.9%): [10.460, 12.003] (assumes normal distribution)


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
# Warmup Iteration   1: 6.869 ops/ms
# Warmup Iteration   2: 10.055 ops/ms
# Warmup Iteration   3: 10.619 ops/ms
Iteration   1: 10.513 ops/ms
Iteration   2: 10.698 ops/ms
Iteration   3: 10.732 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.648 ±(99.9%) 2.151 ops/ms [Average]
  (min, avg, max) = (10.513, 10.648, 10.732), stdev = 0.118
  CI (99.9%): [8.497, 12.799] (assumes normal distribution)


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
# Warmup Iteration   1: 5.513 ops/ms
# Warmup Iteration   2: 7.840 ops/ms
# Warmup Iteration   3: 7.993 ops/ms
Iteration   1: 8.225 ops/ms
Iteration   2: 8.130 ops/ms
Iteration   3: 8.227 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.194 ±(99.9%) 1.012 ops/ms [Average]
  (min, avg, max) = (8.130, 8.194, 8.227), stdev = 0.055
  CI (99.9%): [7.182, 9.205] (assumes normal distribution)


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
# Warmup Iteration   1: 4.404 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.124 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.056 ±(99.9%) 0.002 ms/op
Iteration   1: 2.969 ±(99.9%) 0.003 ms/op
Iteration   2: 2.993 ±(99.9%) 0.002 ms/op
Iteration   3: 3.027 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.996 ±(99.9%) 0.534 ms/op [Average]
  (min, avg, max) = (2.969, 2.996, 3.027), stdev = 0.029
  CI (99.9%): [2.462, 3.530] (assumes normal distribution)


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
# Warmup Iteration   1: 3.992 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 2.982 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 2.896 ±(99.9%) 0.002 ms/op
Iteration   1: 2.817 ±(99.9%) 0.003 ms/op
Iteration   2: 2.837 ±(99.9%) 0.002 ms/op
Iteration   3: 2.870 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.841 ±(99.9%) 0.484 ms/op [Average]
  (min, avg, max) = (2.817, 2.841, 2.870), stdev = 0.027
  CI (99.9%): [2.357, 3.326] (assumes normal distribution)


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
# Warmup Iteration   1: 4.047 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.104 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.019 ±(99.9%) 0.002 ms/op
Iteration   1: 2.990 ±(99.9%) 0.002 ms/op
Iteration   2: 2.999 ±(99.9%) 0.002 ms/op
Iteration   3: 3.012 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.000 ±(99.9%) 0.206 ms/op [Average]
  (min, avg, max) = (2.990, 3.000, 3.012), stdev = 0.011
  CI (99.9%): [2.794, 3.206] (assumes normal distribution)


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
# Warmup Iteration   1: 5.264 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.050 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 3.905 ±(99.9%) 0.005 ms/op
Iteration   1: 3.929 ±(99.9%) 0.011 ms/op
Iteration   2: 3.854 ±(99.9%) 0.029 ms/op
Iteration   3: 3.897 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.893 ±(99.9%) 0.690 ms/op [Average]
  (min, avg, max) = (3.854, 3.893, 3.929), stdev = 0.038
  CI (99.9%): [3.203, 4.584] (assumes normal distribution)


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
# Warmup Iteration   1: 4.163 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.169 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.004 ±(99.9%) 0.005 ms/op
Iteration   1: 3.026 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.809 ms/op
                 createUser·p0.50:   2.982 ms/op
                 createUser·p0.90:   3.486 ms/op
                 createUser·p0.95:   3.744 ms/op
                 createUser·p0.99:   4.645 ms/op
                 createUser·p0.999:  9.568 ms/op
                 createUser·p0.9999: 17.302 ms/op
                 createUser·p1.00:   17.760 ms/op

Iteration   2: 3.014 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.856 ms/op
                 createUser·p0.50:   2.978 ms/op
                 createUser·p0.90:   3.502 ms/op
                 createUser·p0.95:   3.727 ms/op
                 createUser·p0.99:   4.211 ms/op
                 createUser·p0.999:  7.099 ms/op
                 createUser·p0.9999: 14.329 ms/op
                 createUser·p1.00:   15.024 ms/op

Iteration   3: 3.050 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.781 ms/op
                 createUser·p0.50:   2.990 ms/op
                 createUser·p0.90:   3.682 ms/op
                 createUser·p0.95:   3.891 ms/op
                 createUser·p0.99:   4.555 ms/op
                 createUser·p0.999:  12.861 ms/op
                 createUser·p0.9999: 24.003 ms/op
                 createUser·p1.00:   24.347 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 316654
  mean =      3.030 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24011 
    [ 2.500,  5.000) = 291301 
    [ 5.000,  7.500) = 882 
    [ 7.500, 10.000) = 174 
    [10.000, 12.500) = 43 
    [12.500, 15.000) = 130 
    [15.000, 17.500) = 80 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.781 ms/op
     p(50.0000) =      2.982 ms/op
     p(90.0000) =      3.564 ms/op
     p(95.0000) =      3.805 ms/op
     p(99.0000) =      4.465 ms/op
     p(99.9000) =      9.459 ms/op
     p(99.9900) =     17.553 ms/op
     p(99.9990) =     24.177 ms/op
     p(99.9999) =     24.347 ms/op
    p(100.0000) =     24.347 ms/op


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
# Warmup Iteration   1: 3.942 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.006 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.912 ±(99.9%) 0.005 ms/op
Iteration   1: 2.884 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.584 ms/op
                 existUser·p0.50:   2.875 ms/op
                 existUser·p0.90:   3.351 ms/op
                 existUser·p0.95:   3.510 ms/op
                 existUser·p0.99:   4.211 ms/op
                 existUser·p0.999:  6.446 ms/op
                 existUser·p0.9999: 12.693 ms/op
                 existUser·p1.00:   14.877 ms/op

Iteration   2: 2.948 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.756 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.498 ms/op
                 existUser·p0.95:   3.699 ms/op
                 existUser·p0.99:   4.129 ms/op
                 existUser·p0.999:  6.267 ms/op
                 existUser·p0.9999: 14.142 ms/op
                 existUser·p1.00:   15.090 ms/op

Iteration   3: 2.885 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.758 ms/op
                 existUser·p0.50:   2.867 ms/op
                 existUser·p0.90:   3.342 ms/op
                 existUser·p0.95:   3.514 ms/op
                 existUser·p0.99:   4.074 ms/op
                 existUser·p0.999:  6.222 ms/op
                 existUser·p0.9999: 14.860 ms/op
                 existUser·p1.00:   16.089 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 330315
  mean =      2.905 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1388 
    [ 1.250,  2.500) = 41551 
    [ 2.500,  3.750) = 278393 
    [ 3.750,  5.000) = 7975 
    [ 5.000,  6.250) = 666 
    [ 6.250,  7.500) = 118 
    [ 7.500,  8.750) = 53 
    [ 8.750, 10.000) = 11 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 50 
    [12.500, 13.750) = 62 
    [13.750, 15.000) = 34 
    [15.000, 16.250) = 14 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.584 ms/op
     p(50.0000) =      2.888 ms/op
     p(90.0000) =      3.396 ms/op
     p(95.0000) =      3.588 ms/op
     p(99.0000) =      4.137 ms/op
     p(99.9000) =      6.300 ms/op
     p(99.9900) =     14.581 ms/op
     p(99.9990) =     15.438 ms/op
     p(99.9999) =     16.089 ms/op
    p(100.0000) =     16.089 ms/op


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
# Warmup Iteration   1: 4.326 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.118 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.002 ±(99.9%) 0.006 ms/op
Iteration   1: 3.030 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.910 ms/op
                 getUser·p0.50:   2.986 ms/op
                 getUser·p0.90:   3.596 ms/op
                 getUser·p0.95:   3.785 ms/op
                 getUser·p0.99:   4.276 ms/op
                 getUser·p0.999:  6.799 ms/op
                 getUser·p0.9999: 18.022 ms/op
                 getUser·p1.00:   18.383 ms/op

Iteration   2: 2.977 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.859 ms/op
                 getUser·p0.50:   2.953 ms/op
                 getUser·p0.90:   3.404 ms/op
                 getUser·p0.95:   3.617 ms/op
                 getUser·p0.99:   4.383 ms/op
                 getUser·p0.999:  6.612 ms/op
                 getUser·p0.9999: 20.160 ms/op
                 getUser·p1.00:   20.546 ms/op

Iteration   3: 2.945 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.760 ms/op
                 getUser·p0.50:   2.957 ms/op
                 getUser·p0.90:   3.502 ms/op
                 getUser·p0.95:   3.695 ms/op
                 getUser·p0.99:   4.588 ms/op
                 getUser·p0.999:  7.130 ms/op
                 getUser·p0.9999: 15.799 ms/op
                 getUser·p1.00:   16.105 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 321677
  mean =      2.983 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29379 
    [ 2.500,  5.000) = 291001 
    [ 5.000,  7.500) = 1057 
    [ 7.500, 10.000) = 30 
    [10.000, 12.500) = 47 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 46 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.760 ms/op
     p(50.0000) =      2.966 ms/op
     p(90.0000) =      3.510 ms/op
     p(95.0000) =      3.711 ms/op
     p(99.0000) =      4.399 ms/op
     p(99.9000) =      6.939 ms/op
     p(99.9900) =     19.583 ms/op
     p(99.9990) =     20.400 ms/op
     p(99.9999) =     20.546 ms/op
    p(100.0000) =     20.546 ms/op


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
# Warmup Iteration   1: 5.231 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.172 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.925 ±(99.9%) 0.010 ms/op
Iteration   1: 3.906 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.325 ms/op
                 listUser·p0.50:   3.756 ms/op
                 listUser·p0.90:   4.801 ms/op
                 listUser·p0.95:   5.464 ms/op
                 listUser·p0.99:   6.824 ms/op
                 listUser·p0.999:  13.515 ms/op
                 listUser·p0.9999: 15.103 ms/op
                 listUser·p1.00:   15.630 ms/op

Iteration   2: 3.877 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.444 ms/op
                 listUser·p0.50:   3.731 ms/op
                 listUser·p0.90:   4.768 ms/op
                 listUser·p0.95:   5.644 ms/op
                 listUser·p0.99:   6.640 ms/op
                 listUser·p0.999:  16.229 ms/op
                 listUser·p0.9999: 24.240 ms/op
                 listUser·p1.00:   24.609 ms/op

Iteration   3: 3.839 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.748 ms/op
                 listUser·p0.50:   3.678 ms/op
                 listUser·p0.90:   4.932 ms/op
                 listUser·p0.95:   5.669 ms/op
                 listUser·p0.99:   6.742 ms/op
                 listUser·p0.999:  17.072 ms/op
                 listUser·p0.9999: 20.349 ms/op
                 listUser·p1.00:   20.742 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 247778
  mean =      3.874 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4167 
    [ 2.500,  5.000) = 222615 
    [ 5.000,  7.500) = 19853 
    [ 7.500, 10.000) = 746 
    [10.000, 12.500) = 13 
    [12.500, 15.000) = 144 
    [15.000, 17.500) = 101 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 58 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.748 ms/op
     p(50.0000) =      3.723 ms/op
     p(90.0000) =      4.833 ms/op
     p(95.0000) =      5.603 ms/op
     p(99.0000) =      6.734 ms/op
     p(99.9000) =     14.864 ms/op
     p(99.9900) =     22.148 ms/op
     p(99.9990) =     24.498 ms/op
     p(99.9999) =     24.609 ms/op
    p(100.0000) =     24.609 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.608 ± 1.436  ops/ms
ClientGrpc.existUser                       thrpt       3  11.231 ± 0.771  ops/ms
ClientGrpc.getUser                         thrpt       3  10.648 ± 2.151  ops/ms
ClientGrpc.listUser                        thrpt       3   8.194 ± 1.012  ops/ms
ClientGrpc.createUser                       avgt       3   2.996 ± 0.534   ms/op
ClientGrpc.existUser                        avgt       3   2.841 ± 0.484   ms/op
ClientGrpc.getUser                          avgt       3   3.000 ± 0.206   ms/op
ClientGrpc.listUser                         avgt       3   3.893 ± 0.690   ms/op
ClientGrpc.createUser                     sample  316654   3.030 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.781           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.982           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.564           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.805           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.465           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.459           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.553           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.347           ms/op
ClientGrpc.existUser                      sample  330315   2.905 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.584           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.888           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.396           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.588           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.137           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.300           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.581           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.089           ms/op
ClientGrpc.getUser                        sample  321677   2.983 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.760           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.966           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.510           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.711           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.399           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.939           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.583           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.546           ms/op
ClientGrpc.listUser                       sample  247778   3.874 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.748           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.723           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.833           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.603           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.734           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.864           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.148           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.609           ms/op
