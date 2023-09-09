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
# Warmup Iteration   1: 3.941 ops/ms
# Warmup Iteration   2: 8.446 ops/ms
# Warmup Iteration   3: 9.867 ops/ms
Iteration   1: 10.168 ops/ms
Iteration   2: 10.176 ops/ms
Iteration   3: 10.436 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.260 ±(99.9%) 2.781 ops/ms [Average]
  (min, avg, max) = (10.168, 10.260, 10.436), stdev = 0.152
  CI (99.9%): [7.479, 13.041] (assumes normal distribution)


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
# Warmup Iteration   1: 7.366 ops/ms
# Warmup Iteration   2: 10.271 ops/ms
# Warmup Iteration   3: 10.871 ops/ms
Iteration   1: 10.719 ops/ms
Iteration   2: 10.806 ops/ms
Iteration   3: 10.814 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.780 ±(99.9%) 0.963 ops/ms [Average]
  (min, avg, max) = (10.719, 10.780, 10.814), stdev = 0.053
  CI (99.9%): [9.817, 11.743] (assumes normal distribution)


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
# Warmup Iteration   1: 6.502 ops/ms
# Warmup Iteration   2: 9.995 ops/ms
# Warmup Iteration   3: 10.207 ops/ms
Iteration   1: 10.381 ops/ms
Iteration   2: 10.292 ops/ms
Iteration   3: 10.376 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.350 ±(99.9%) 0.916 ops/ms [Average]
  (min, avg, max) = (10.292, 10.350, 10.381), stdev = 0.050
  CI (99.9%): [9.433, 11.266] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 4.946 ops/ms
# Warmup Iteration   2: 7.717 ops/ms
# Warmup Iteration   3: 7.824 ops/ms
Iteration   1: 7.770 ops/ms
Iteration   2: 7.785 ops/ms
Iteration   3: 7.825 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.793 ±(99.9%) 0.518 ops/ms [Average]
  (min, avg, max) = (7.770, 7.793, 7.825), stdev = 0.028
  CI (99.9%): [7.275, 8.312] (assumes normal distribution)


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
# Warmup Iteration   1: 4.467 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.255 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.097 ±(99.9%) 0.002 ms/op
Iteration   1: 3.108 ±(99.9%) 0.012 ms/op
Iteration   2: 3.146 ±(99.9%) 0.004 ms/op
Iteration   3: 3.094 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.116 ±(99.9%) 0.488 ms/op [Average]
  (min, avg, max) = (3.094, 3.116, 3.146), stdev = 0.027
  CI (99.9%): [2.628, 3.604] (assumes normal distribution)


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
# Warmup Iteration   1: 4.041 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.993 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.974 ±(99.9%) 0.002 ms/op
Iteration   1: 2.905 ±(99.9%) 0.002 ms/op
Iteration   2: 2.928 ±(99.9%) 0.003 ms/op
Iteration   3: 2.903 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.912 ±(99.9%) 0.256 ms/op [Average]
  (min, avg, max) = (2.903, 2.912, 2.928), stdev = 0.014
  CI (99.9%): [2.656, 3.168] (assumes normal distribution)


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
# Warmup Iteration   1: 4.299 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.194 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.106 ±(99.9%) 0.003 ms/op
Iteration   1: 3.098 ±(99.9%) 0.004 ms/op
Iteration   2: 3.129 ±(99.9%) 0.003 ms/op
Iteration   3: 3.122 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.116 ±(99.9%) 0.299 ms/op [Average]
  (min, avg, max) = (3.098, 3.116, 3.129), stdev = 0.016
  CI (99.9%): [2.818, 3.415] (assumes normal distribution)


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
# Warmup Iteration   1: 5.418 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 4.217 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.048 ±(99.9%) 0.014 ms/op
Iteration   1: 4.118 ±(99.9%) 0.011 ms/op
Iteration   2: 4.061 ±(99.9%) 0.009 ms/op
Iteration   3: 4.002 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.060 ±(99.9%) 1.055 ms/op [Average]
  (min, avg, max) = (4.002, 4.060, 4.118), stdev = 0.058
  CI (99.9%): [3.005, 5.115] (assumes normal distribution)


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
# Warmup Iteration   1: 4.068 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.246 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.134 ±(99.9%) 0.007 ms/op
Iteration   1: 3.150 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.593 ms/op
                 createUser·p0.50:   3.097 ms/op
                 createUser·p0.90:   3.727 ms/op
                 createUser·p0.95:   3.981 ms/op
                 createUser·p0.99:   4.727 ms/op
                 createUser·p0.999:  8.413 ms/op
                 createUser·p0.9999: 16.795 ms/op
                 createUser·p1.00:   17.105 ms/op

Iteration   2: 3.090 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.865 ms/op
                 createUser·p0.50:   3.047 ms/op
                 createUser·p0.90:   3.580 ms/op
                 createUser·p0.95:   3.830 ms/op
                 createUser·p0.99:   4.735 ms/op
                 createUser·p0.999:  9.200 ms/op
                 createUser·p0.9999: 32.047 ms/op
                 createUser·p1.00:   32.997 ms/op

Iteration   3: 3.093 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.892 ms/op
                 createUser·p0.50:   3.056 ms/op
                 createUser·p0.90:   3.510 ms/op
                 createUser·p0.95:   3.764 ms/op
                 createUser·p0.99:   4.437 ms/op
                 createUser·p0.999:  8.486 ms/op
                 createUser·p0.9999: 21.681 ms/op
                 createUser·p1.00:   22.217 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 308525
  mean =      3.111 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13374 
    [ 2.500,  5.000) = 292888 
    [ 5.000,  7.500) = 1756 
    [ 7.500, 10.000) = 263 
    [10.000, 12.500) = 52 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 66 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 31 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.593 ms/op
     p(50.0000) =      3.064 ms/op
     p(90.0000) =      3.613 ms/op
     p(95.0000) =      3.867 ms/op
     p(99.0000) =      4.628 ms/op
     p(99.9000) =      8.806 ms/op
     p(99.9900) =     31.425 ms/op
     p(99.9990) =     32.342 ms/op
     p(99.9999) =     32.997 ms/op
    p(100.0000) =     32.997 ms/op


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
# Warmup Iteration   1: 3.960 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.090 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.973 ±(99.9%) 0.007 ms/op
Iteration   1: 2.954 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.806 ms/op
                 existUser·p0.50:   2.941 ms/op
                 existUser·p0.90:   3.408 ms/op
                 existUser·p0.95:   3.645 ms/op
                 existUser·p0.99:   4.334 ms/op
                 existUser·p0.999:  7.073 ms/op
                 existUser·p0.9999: 11.062 ms/op
                 existUser·p1.00:   11.878 ms/op

Iteration   2: 2.968 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.822 ms/op
                 existUser·p0.50:   2.933 ms/op
                 existUser·p0.90:   3.494 ms/op
                 existUser·p0.95:   3.748 ms/op
                 existUser·p0.99:   4.309 ms/op
                 existUser·p0.999:  7.005 ms/op
                 existUser·p0.9999: 17.177 ms/op
                 existUser·p1.00:   18.874 ms/op

Iteration   3: 2.903 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.709 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.301 ms/op
                 existUser·p0.95:   3.514 ms/op
                 existUser·p0.99:   4.284 ms/op
                 existUser·p0.999:  8.471 ms/op
                 existUser·p0.9999: 16.843 ms/op
                 existUser·p1.00:   17.826 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 326379
  mean =      2.941 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1916 
    [ 1.250,  2.500) = 27591 
    [ 2.500,  3.750) = 284661 
    [ 3.750,  5.000) = 10643 
    [ 5.000,  6.250) = 718 
    [ 6.250,  7.500) = 448 
    [ 7.500,  8.750) = 167 
    [ 8.750, 10.000) = 29 
    [10.000, 11.250) = 41 
    [11.250, 12.500) = 12 
    [12.500, 13.750) = 30 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 12 
    [16.250, 17.500) = 72 
    [17.500, 18.750) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.709 ms/op
     p(50.0000) =      2.925 ms/op
     p(90.0000) =      3.391 ms/op
     p(95.0000) =      3.650 ms/op
     p(99.0000) =      4.317 ms/op
     p(99.9000) =      7.976 ms/op
     p(99.9900) =     16.908 ms/op
     p(99.9990) =     17.859 ms/op
     p(99.9999) =     18.874 ms/op
    p(100.0000) =     18.874 ms/op


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
# Warmup Iteration   1: 4.181 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.185 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.031 ±(99.9%) 0.006 ms/op
Iteration   1: 3.106 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.582 ms/op
                 getUser·p0.50:   3.068 ms/op
                 getUser·p0.90:   3.547 ms/op
                 getUser·p0.95:   3.756 ms/op
                 getUser·p0.99:   4.735 ms/op
                 getUser·p0.999:  7.486 ms/op
                 getUser·p0.9999: 13.102 ms/op
                 getUser·p1.00:   13.287 ms/op

Iteration   2: 3.078 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.831 ms/op
                 getUser·p0.50:   3.056 ms/op
                 getUser·p0.90:   3.535 ms/op
                 getUser·p0.95:   3.809 ms/op
                 getUser·p0.99:   4.694 ms/op
                 getUser·p0.999:  8.864 ms/op
                 getUser·p0.9999: 16.305 ms/op
                 getUser·p1.00:   16.843 ms/op

Iteration   3: 3.115 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.904 ms/op
                 getUser·p0.50:   3.080 ms/op
                 getUser·p0.90:   3.568 ms/op
                 getUser·p0.95:   3.830 ms/op
                 getUser·p0.99:   4.859 ms/op
                 getUser·p0.999:  7.971 ms/op
                 getUser·p0.9999: 17.883 ms/op
                 getUser·p1.00:   18.973 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 309814
  mean =      3.100 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 458 
    [ 1.250,  2.500) = 12594 
    [ 2.500,  3.750) = 279073 
    [ 3.750,  5.000) = 15205 
    [ 5.000,  6.250) = 1394 
    [ 6.250,  7.500) = 631 
    [ 7.500,  8.750) = 224 
    [ 8.750, 10.000) = 28 
    [10.000, 11.250) = 24 
    [11.250, 12.500) = 23 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 27 
    [16.250, 17.500) = 43 
    [17.500, 18.750) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.582 ms/op
     p(50.0000) =      3.068 ms/op
     p(90.0000) =      3.547 ms/op
     p(95.0000) =      3.797 ms/op
     p(99.0000) =      4.743 ms/op
     p(99.9000) =      8.106 ms/op
     p(99.9900) =     17.368 ms/op
     p(99.9990) =     18.619 ms/op
     p(99.9999) =     18.973 ms/op
    p(100.0000) =     18.973 ms/op


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
# Warmup Iteration   1: 5.854 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 4.387 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.104 ±(99.9%) 0.013 ms/op
Iteration   1: 4.078 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.041 ms/op
                 listUser·p0.50:   3.899 ms/op
                 listUser·p0.90:   5.112 ms/op
                 listUser·p0.95:   5.979 ms/op
                 listUser·p0.99:   7.504 ms/op
                 listUser·p0.999:  14.592 ms/op
                 listUser·p0.9999: 20.392 ms/op
                 listUser·p1.00:   20.873 ms/op

Iteration   2: 4.032 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.946 ms/op
                 listUser·p0.50:   3.871 ms/op
                 listUser·p0.90:   5.054 ms/op
                 listUser·p0.95:   5.997 ms/op
                 listUser·p0.99:   7.406 ms/op
                 listUser·p0.999:  16.467 ms/op
                 listUser·p0.9999: 18.645 ms/op
                 listUser·p1.00:   20.808 ms/op

Iteration   3: 4.088 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.993 ms/op
                 listUser·p0.50:   3.916 ms/op
                 listUser·p0.90:   5.112 ms/op
                 listUser·p0.95:   6.038 ms/op
                 listUser·p0.99:   7.217 ms/op
                 listUser·p0.999:  19.126 ms/op
                 listUser·p0.9999: 23.773 ms/op
                 listUser·p1.00:   24.216 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 236047
  mean =      4.066 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2548 
    [ 2.500,  5.000) = 207962 
    [ 5.000,  7.500) = 23414 
    [ 7.500, 10.000) = 1421 
    [10.000, 12.500) = 228 
    [12.500, 15.000) = 175 
    [15.000, 17.500) = 143 
    [17.500, 20.000) = 66 
    [20.000, 22.500) = 70 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.946 ms/op
     p(50.0000) =      3.895 ms/op
     p(90.0000) =      5.095 ms/op
     p(95.0000) =      6.005 ms/op
     p(99.0000) =      7.373 ms/op
     p(99.9000) =     16.236 ms/op
     p(99.9900) =     22.381 ms/op
     p(99.9990) =     24.117 ms/op
     p(99.9999) =     24.216 ms/op
    p(100.0000) =     24.216 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.260 ± 2.781  ops/ms
ClientGrpc.existUser                       thrpt       3  10.780 ± 0.963  ops/ms
ClientGrpc.getUser                         thrpt       3  10.350 ± 0.916  ops/ms
ClientGrpc.listUser                        thrpt       3   7.793 ± 0.518  ops/ms
ClientGrpc.createUser                       avgt       3   3.116 ± 0.488   ms/op
ClientGrpc.existUser                        avgt       3   2.912 ± 0.256   ms/op
ClientGrpc.getUser                          avgt       3   3.116 ± 0.299   ms/op
ClientGrpc.listUser                         avgt       3   4.060 ± 1.055   ms/op
ClientGrpc.createUser                     sample  308525   3.111 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.593           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.064           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.613           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.867           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.628           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.806           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          31.425           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          32.997           ms/op
ClientGrpc.existUser                      sample  326379   2.941 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.709           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.925           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.391           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.650           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.317           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.976           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.908           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.874           ms/op
ClientGrpc.getUser                        sample  309814   3.100 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.582           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.068           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.547           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.797           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.743           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.106           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.368           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.973           ms/op
ClientGrpc.listUser                       sample  236047   4.066 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.946           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.895           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.095           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.005           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.373           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.236           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.381           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.216           ms/op
