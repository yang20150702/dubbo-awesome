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
# Warmup Iteration   1: 3.934 ops/ms
# Warmup Iteration   2: 8.909 ops/ms
# Warmup Iteration   3: 9.838 ops/ms
Iteration   1: 10.229 ops/ms
Iteration   2: 10.053 ops/ms
Iteration   3: 10.119 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.134 ±(99.9%) 1.628 ops/ms [Average]
  (min, avg, max) = (10.053, 10.134, 10.229), stdev = 0.089
  CI (99.9%): [8.505, 11.762] (assumes normal distribution)


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
# Warmup Iteration   1: 7.272 ops/ms
# Warmup Iteration   2: 10.124 ops/ms
# Warmup Iteration   3: 10.576 ops/ms
Iteration   1: 10.637 ops/ms
Iteration   2: 10.692 ops/ms
Iteration   3: 10.723 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.684 ±(99.9%) 0.794 ops/ms [Average]
  (min, avg, max) = (10.637, 10.684, 10.723), stdev = 0.044
  CI (99.9%): [9.889, 11.478] (assumes normal distribution)


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
# Warmup Iteration   1: 6.954 ops/ms
# Warmup Iteration   2: 9.727 ops/ms
# Warmup Iteration   3: 9.925 ops/ms
Iteration   1: 9.932 ops/ms
Iteration   2: 10.149 ops/ms
Iteration   3: 10.231 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.104 ±(99.9%) 2.813 ops/ms [Average]
  (min, avg, max) = (9.932, 10.104, 10.231), stdev = 0.154
  CI (99.9%): [7.290, 12.917] (assumes normal distribution)


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
# Warmup Iteration   1: 5.789 ops/ms
# Warmup Iteration   2: 7.395 ops/ms
# Warmup Iteration   3: 7.726 ops/ms
Iteration   1: 7.794 ops/ms
Iteration   2: 7.645 ops/ms
Iteration   3: 7.608 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.682 ±(99.9%) 1.796 ops/ms [Average]
  (min, avg, max) = (7.608, 7.682, 7.794), stdev = 0.098
  CI (99.9%): [5.887, 9.478] (assumes normal distribution)


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
# Warmup Iteration   1: 4.604 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.248 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.148 ±(99.9%) 0.003 ms/op
Iteration   1: 3.129 ±(99.9%) 0.003 ms/op
Iteration   2: 3.185 ±(99.9%) 0.003 ms/op
Iteration   3: 3.121 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.145 ±(99.9%) 0.638 ms/op [Average]
  (min, avg, max) = (3.121, 3.145, 3.185), stdev = 0.035
  CI (99.9%): [2.507, 3.783] (assumes normal distribution)


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
# Warmup Iteration   1: 4.066 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.114 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.007 ±(99.9%) 0.003 ms/op
Iteration   1: 3.000 ±(99.9%) 0.007 ms/op
Iteration   2: 2.974 ±(99.9%) 0.004 ms/op
Iteration   3: 2.993 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.989 ±(99.9%) 0.242 ms/op [Average]
  (min, avg, max) = (2.974, 2.989, 3.000), stdev = 0.013
  CI (99.9%): [2.747, 3.231] (assumes normal distribution)


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
# Warmup Iteration   1: 4.251 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.272 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.124 ±(99.9%) 0.003 ms/op
Iteration   1: 3.181 ±(99.9%) 0.002 ms/op
Iteration   2: 3.145 ±(99.9%) 0.002 ms/op
Iteration   3: 3.095 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.140 ±(99.9%) 0.788 ms/op [Average]
  (min, avg, max) = (3.095, 3.140, 3.181), stdev = 0.043
  CI (99.9%): [2.352, 3.929] (assumes normal distribution)


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
# Warmup Iteration   1: 5.414 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.227 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.111 ±(99.9%) 0.031 ms/op
Iteration   1: 4.120 ±(99.9%) 0.025 ms/op
Iteration   2: 4.123 ±(99.9%) 0.022 ms/op
Iteration   3: 4.110 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.118 ±(99.9%) 0.124 ms/op [Average]
  (min, avg, max) = (4.110, 4.118, 4.123), stdev = 0.007
  CI (99.9%): [3.994, 4.242] (assumes normal distribution)


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
# Warmup Iteration   1: 4.363 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.392 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.165 ±(99.9%) 0.007 ms/op
Iteration   1: 3.139 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.665 ms/op
                 createUser·p0.50:   3.117 ms/op
                 createUser·p0.90:   3.635 ms/op
                 createUser·p0.95:   3.875 ms/op
                 createUser·p0.99:   4.522 ms/op
                 createUser·p0.999:  7.758 ms/op
                 createUser·p0.9999: 12.724 ms/op
                 createUser·p1.00:   13.091 ms/op

Iteration   2: 3.141 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.746 ms/op
                 createUser·p0.50:   3.105 ms/op
                 createUser·p0.90:   3.654 ms/op
                 createUser·p0.95:   3.883 ms/op
                 createUser·p0.99:   4.645 ms/op
                 createUser·p0.999:  10.519 ms/op
                 createUser·p0.9999: 15.168 ms/op
                 createUser·p1.00:   15.598 ms/op

Iteration   3: 3.117 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.558 ms/op
                 createUser·p0.50:   3.109 ms/op
                 createUser·p0.90:   3.559 ms/op
                 createUser·p0.95:   3.752 ms/op
                 createUser·p0.99:   4.350 ms/op
                 createUser·p0.999:  8.511 ms/op
                 createUser·p0.9999: 17.718 ms/op
                 createUser·p1.00:   18.022 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 306635
  mean =      3.132 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 474 
    [ 1.250,  2.500) = 12119 
    [ 2.500,  3.750) = 273835 
    [ 3.750,  5.000) = 18875 
    [ 5.000,  6.250) = 744 
    [ 6.250,  7.500) = 211 
    [ 7.500,  8.750) = 52 
    [ 8.750, 10.000) = 36 
    [10.000, 11.250) = 85 
    [11.250, 12.500) = 44 
    [12.500, 13.750) = 55 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 43 
    [16.250, 17.500) = 22 
    [17.500, 18.750) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.558 ms/op
     p(50.0000) =      3.109 ms/op
     p(90.0000) =      3.613 ms/op
     p(95.0000) =      3.838 ms/op
     p(99.0000) =      4.506 ms/op
     p(99.9000) =      9.138 ms/op
     p(99.9900) =     16.455 ms/op
     p(99.9990) =     17.957 ms/op
     p(99.9999) =     18.022 ms/op
    p(100.0000) =     18.022 ms/op


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
# Warmup Iteration   1: 4.232 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.119 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.010 ±(99.9%) 0.005 ms/op
Iteration   1: 3.032 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.793 ms/op
                 existUser·p0.50:   3.011 ms/op
                 existUser·p0.90:   3.531 ms/op
                 existUser·p0.95:   3.772 ms/op
                 existUser·p0.99:   4.448 ms/op
                 existUser·p0.999:  6.327 ms/op
                 existUser·p0.9999: 12.890 ms/op
                 existUser·p1.00:   13.451 ms/op

Iteration   2: 2.974 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.895 ms/op
                 existUser·p0.50:   2.949 ms/op
                 existUser·p0.90:   3.461 ms/op
                 existUser·p0.95:   3.703 ms/op
                 existUser·p0.99:   4.497 ms/op
                 existUser·p0.999:  6.361 ms/op
                 existUser·p0.9999: 15.102 ms/op
                 existUser·p1.00:   15.368 ms/op

Iteration   3: 3.032 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.715 ms/op
                 existUser·p0.50:   3.023 ms/op
                 existUser·p0.90:   3.342 ms/op
                 existUser·p0.95:   3.490 ms/op
                 existUser·p0.99:   4.211 ms/op
                 existUser·p0.999:  9.856 ms/op
                 existUser·p0.9999: 26.056 ms/op
                 existUser·p1.00:   26.575 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 318640
  mean =      3.012 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20398 
    [ 2.500,  5.000) = 297059 
    [ 5.000,  7.500) = 931 
    [ 7.500, 10.000) = 53 
    [10.000, 12.500) = 54 
    [12.500, 15.000) = 88 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.715 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.441 ms/op
     p(95.0000) =      3.674 ms/op
     p(99.0000) =      4.424 ms/op
     p(99.9000) =      6.846 ms/op
     p(99.9900) =     24.296 ms/op
     p(99.9990) =     26.274 ms/op
     p(99.9999) =     26.575 ms/op
    p(100.0000) =     26.575 ms/op


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
# Warmup Iteration   1: 4.433 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.317 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.149 ±(99.9%) 0.006 ms/op
Iteration   1: 3.188 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.896 ms/op
                 getUser·p0.50:   3.162 ms/op
                 getUser·p0.90:   3.678 ms/op
                 getUser·p0.95:   3.887 ms/op
                 getUser·p0.99:   4.465 ms/op
                 getUser·p0.999:  7.868 ms/op
                 getUser·p0.9999: 19.824 ms/op
                 getUser·p1.00:   20.251 ms/op

Iteration   2: 3.162 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.829 ms/op
                 getUser·p0.50:   3.138 ms/op
                 getUser·p0.90:   3.596 ms/op
                 getUser·p0.95:   3.887 ms/op
                 getUser·p0.99:   4.399 ms/op
                 getUser·p0.999:  7.266 ms/op
                 getUser·p0.9999: 13.613 ms/op
                 getUser·p1.00:   13.926 ms/op

Iteration   3: 3.105 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.693 ms/op
                 getUser·p0.50:   3.113 ms/op
                 getUser·p0.90:   3.645 ms/op
                 getUser·p0.95:   3.891 ms/op
                 getUser·p0.99:   4.628 ms/op
                 getUser·p0.999:  8.027 ms/op
                 getUser·p0.9999: 17.564 ms/op
                 getUser·p1.00:   17.662 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 304655
  mean =      3.152 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14426 
    [ 2.500,  5.000) = 288820 
    [ 5.000,  7.500) = 1077 
    [ 7.500, 10.000) = 121 
    [10.000, 12.500) = 50 
    [12.500, 15.000) = 67 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.693 ms/op
     p(50.0000) =      3.138 ms/op
     p(90.0000) =      3.645 ms/op
     p(95.0000) =      3.887 ms/op
     p(99.0000) =      4.506 ms/op
     p(99.9000) =      7.794 ms/op
     p(99.9900) =     18.990 ms/op
     p(99.9990) =     20.118 ms/op
     p(99.9999) =     20.251 ms/op
    p(100.0000) =     20.251 ms/op


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
# Warmup Iteration   1: 5.826 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 4.274 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.142 ±(99.9%) 0.013 ms/op
Iteration   1: 4.176 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.077 ms/op
                 listUser·p0.50:   4.014 ms/op
                 listUser·p0.90:   5.046 ms/op
                 listUser·p0.95:   6.021 ms/op
                 listUser·p0.99:   7.422 ms/op
                 listUser·p0.999:  22.260 ms/op
                 listUser·p0.9999: 28.027 ms/op
                 listUser·p1.00:   29.884 ms/op

Iteration   2: 4.117 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.071 ms/op
                 listUser·p0.50:   3.944 ms/op
                 listUser·p0.90:   5.120 ms/op
                 listUser·p0.95:   5.718 ms/op
                 listUser·p0.99:   7.234 ms/op
                 listUser·p0.999:  14.924 ms/op
                 listUser·p0.9999: 17.506 ms/op
                 listUser·p1.00:   17.793 ms/op

Iteration   3: 4.137 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.100 ms/op
                 listUser·p0.50:   4.002 ms/op
                 listUser·p0.90:   5.054 ms/op
                 listUser·p0.95:   5.726 ms/op
                 listUser·p0.99:   7.037 ms/op
                 listUser·p0.999:  16.383 ms/op
                 listUser·p0.9999: 24.585 ms/op
                 listUser·p1.00:   25.166 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 231733
  mean =      4.143 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1742 
    [ 2.500,  5.000) = 205212 
    [ 5.000,  7.500) = 23023 
    [ 7.500, 10.000) = 1273 
    [10.000, 12.500) = 131 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 118 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 66 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      1.071 ms/op
     p(50.0000) =      3.990 ms/op
     p(90.0000) =      5.079 ms/op
     p(95.0000) =      5.825 ms/op
     p(99.0000) =      7.217 ms/op
     p(99.9000) =     16.524 ms/op
     p(99.9900) =     25.297 ms/op
     p(99.9990) =     29.166 ms/op
     p(99.9999) =     29.884 ms/op
    p(100.0000) =     29.884 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.134 ± 1.628  ops/ms
ClientGrpc.existUser                       thrpt       3  10.684 ± 0.794  ops/ms
ClientGrpc.getUser                         thrpt       3  10.104 ± 2.813  ops/ms
ClientGrpc.listUser                        thrpt       3   7.682 ± 1.796  ops/ms
ClientGrpc.createUser                       avgt       3   3.145 ± 0.638   ms/op
ClientGrpc.existUser                        avgt       3   2.989 ± 0.242   ms/op
ClientGrpc.getUser                          avgt       3   3.140 ± 0.788   ms/op
ClientGrpc.listUser                         avgt       3   4.118 ± 0.124   ms/op
ClientGrpc.createUser                     sample  306635   3.132 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.558           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.109           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.613           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.838           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.506           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.138           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.455           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.022           ms/op
ClientGrpc.existUser                      sample  318640   3.012 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.715           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.998           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.441           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.674           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.424           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.846           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          24.296           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          26.575           ms/op
ClientGrpc.getUser                        sample  304655   3.152 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.693           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.138           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.645           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.887           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.506           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.794           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.990           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.251           ms/op
ClientGrpc.listUser                       sample  231733   4.143 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.071           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.990           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.079           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.825           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.217           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.524           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.297           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.884           ms/op
