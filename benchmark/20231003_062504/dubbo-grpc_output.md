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
# Warmup Iteration   1: 4.879 ops/ms
# Warmup Iteration   2: 9.022 ops/ms
# Warmup Iteration   3: 9.827 ops/ms
Iteration   1: 10.195 ops/ms
Iteration   2: 10.637 ops/ms
Iteration   3: 10.254 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.362 ±(99.9%) 4.385 ops/ms [Average]
  (min, avg, max) = (10.195, 10.362, 10.637), stdev = 0.240
  CI (99.9%): [5.977, 14.747] (assumes normal distribution)


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
# Warmup Iteration   1: 7.907 ops/ms
# Warmup Iteration   2: 10.552 ops/ms
# Warmup Iteration   3: 10.714 ops/ms
Iteration   1: 10.749 ops/ms
Iteration   2: 11.222 ops/ms
Iteration   3: 10.855 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.942 ±(99.9%) 4.531 ops/ms [Average]
  (min, avg, max) = (10.749, 10.942, 11.222), stdev = 0.248
  CI (99.9%): [6.411, 15.473] (assumes normal distribution)


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
# Warmup Iteration   1: 7.610 ops/ms
# Warmup Iteration   2: 10.223 ops/ms
# Warmup Iteration   3: 10.314 ops/ms
Iteration   1: 10.383 ops/ms
Iteration   2: 10.313 ops/ms
Iteration   3: 10.489 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.395 ±(99.9%) 1.616 ops/ms [Average]
  (min, avg, max) = (10.313, 10.395, 10.489), stdev = 0.089
  CI (99.9%): [8.779, 12.011] (assumes normal distribution)


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
# Warmup Iteration   1: 6.415 ops/ms
# Warmup Iteration   2: 8.019 ops/ms
# Warmup Iteration   3: 8.747 ops/ms
Iteration   1: 8.365 ops/ms
Iteration   2: 8.338 ops/ms
Iteration   3: 8.414 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.372 ±(99.9%) 0.703 ops/ms [Average]
  (min, avg, max) = (8.338, 8.372, 8.414), stdev = 0.039
  CI (99.9%): [7.670, 9.075] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.006 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.237 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.131 ±(99.9%) 0.002 ms/op
Iteration   1: 3.102 ±(99.9%) 0.004 ms/op
Iteration   2: 3.100 ±(99.9%) 0.002 ms/op
Iteration   3: 3.164 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.122 ±(99.9%) 0.665 ms/op [Average]
  (min, avg, max) = (3.100, 3.122, 3.164), stdev = 0.036
  CI (99.9%): [2.457, 3.787] (assumes normal distribution)


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
# Warmup Iteration   1: 3.963 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.079 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.991 ±(99.9%) 0.014 ms/op
Iteration   1: 2.949 ±(99.9%) 0.003 ms/op
Iteration   2: 2.914 ±(99.9%) 0.002 ms/op
Iteration   3: 2.994 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.952 ±(99.9%) 0.730 ms/op [Average]
  (min, avg, max) = (2.914, 2.952, 2.994), stdev = 0.040
  CI (99.9%): [2.222, 3.682] (assumes normal distribution)


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
# Warmup Iteration   1: 4.103 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.196 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.129 ±(99.9%) 0.003 ms/op
Iteration   1: 3.092 ±(99.9%) 0.002 ms/op
Iteration   2: 3.083 ±(99.9%) 0.004 ms/op
Iteration   3: 3.104 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.093 ±(99.9%) 0.195 ms/op [Average]
  (min, avg, max) = (3.083, 3.093, 3.104), stdev = 0.011
  CI (99.9%): [2.898, 3.287] (assumes normal distribution)


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
# Warmup Iteration   1: 5.117 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.893 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.846 ±(99.9%) 0.032 ms/op
Iteration   1: 3.796 ±(99.9%) 0.050 ms/op
Iteration   2: 3.776 ±(99.9%) 0.061 ms/op
Iteration   3: 3.806 ±(99.9%) 0.074 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.793 ±(99.9%) 0.275 ms/op [Average]
  (min, avg, max) = (3.776, 3.793, 3.806), stdev = 0.015
  CI (99.9%): [3.517, 4.068] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.003 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.241 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.088 ±(99.9%) 0.006 ms/op
Iteration   1: 3.058 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.671 ms/op
                 createUser·p0.50:   3.027 ms/op
                 createUser·p0.90:   3.502 ms/op
                 createUser·p0.95:   3.641 ms/op
                 createUser·p0.99:   4.309 ms/op
                 createUser·p0.999:  10.154 ms/op
                 createUser·p0.9999: 17.173 ms/op
                 createUser·p1.00:   18.416 ms/op

Iteration   2: 3.082 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.678 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.670 ms/op
                 createUser·p0.95:   3.920 ms/op
                 createUser·p0.99:   4.342 ms/op
                 createUser·p0.999:  8.407 ms/op
                 createUser·p0.9999: 20.271 ms/op
                 createUser·p1.00:   20.808 ms/op

Iteration   3: 3.075 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.656 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.609 ms/op
                 createUser·p0.95:   3.838 ms/op
                 createUser·p0.99:   4.309 ms/op
                 createUser·p0.999:  9.907 ms/op
                 createUser·p0.9999: 19.614 ms/op
                 createUser·p1.00:   19.923 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 312715
  mean =      3.072 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16190 
    [ 2.500,  5.000) = 294980 
    [ 5.000,  7.500) = 898 
    [ 7.500, 10.000) = 376 
    [10.000, 12.500) = 74 
    [12.500, 15.000) = 5 
    [15.000, 17.500) = 71 
    [17.500, 20.000) = 106 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.656 ms/op
     p(50.0000) =      3.035 ms/op
     p(90.0000) =      3.580 ms/op
     p(95.0000) =      3.805 ms/op
     p(99.0000) =      4.317 ms/op
     p(99.9000) =      9.496 ms/op
     p(99.9900) =     19.488 ms/op
     p(99.9990) =     20.607 ms/op
     p(99.9999) =     20.808 ms/op
    p(100.0000) =     20.808 ms/op


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
# Warmup Iteration   1: 3.700 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.099 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.980 ±(99.9%) 0.006 ms/op
Iteration   1: 2.981 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.527 ms/op
                 existUser·p0.50:   2.953 ms/op
                 existUser·p0.90:   3.432 ms/op
                 existUser·p0.95:   3.645 ms/op
                 existUser·p0.99:   4.293 ms/op
                 existUser·p0.999:  9.314 ms/op
                 existUser·p0.9999: 11.814 ms/op
                 existUser·p1.00:   12.255 ms/op

Iteration   2: 3.049 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.804 ms/op
                 existUser·p0.50:   2.986 ms/op
                 existUser·p0.90:   3.576 ms/op
                 existUser·p0.95:   3.731 ms/op
                 existUser·p0.99:   4.063 ms/op
                 existUser·p0.999:  12.583 ms/op
                 existUser·p0.9999: 13.779 ms/op
                 existUser·p1.00:   14.041 ms/op

Iteration   3: 2.992 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.750 ms/op
                 existUser·p0.50:   2.941 ms/op
                 existUser·p0.90:   3.592 ms/op
                 existUser·p0.95:   3.805 ms/op
                 existUser·p0.99:   4.522 ms/op
                 existUser·p0.999:  7.423 ms/op
                 existUser·p0.9999: 14.117 ms/op
                 existUser·p1.00:   14.402 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 319245
  mean =      3.007 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 795 
    [ 1.250,  2.500) = 20391 
    [ 2.500,  3.750) = 282647 
    [ 3.750,  5.000) = 14024 
    [ 5.000,  6.250) = 735 
    [ 6.250,  7.500) = 223 
    [ 7.500,  8.750) = 53 
    [ 8.750, 10.000) = 54 
    [10.000, 11.250) = 65 
    [11.250, 12.500) = 113 
    [12.500, 13.750) = 111 
    [13.750, 15.000) = 34 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.527 ms/op
     p(50.0000) =      2.957 ms/op
     p(90.0000) =      3.535 ms/op
     p(95.0000) =      3.744 ms/op
     p(99.0000) =      4.317 ms/op
     p(99.9000) =     10.076 ms/op
     p(99.9900) =     13.779 ms/op
     p(99.9990) =     14.307 ms/op
     p(99.9999) =     14.402 ms/op
    p(100.0000) =     14.402 ms/op


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
# Warmup Iteration   1: 4.024 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.249 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.144 ±(99.9%) 0.005 ms/op
Iteration   1: 3.155 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.905 ms/op
                 getUser·p0.50:   3.109 ms/op
                 getUser·p0.90:   3.777 ms/op
                 getUser·p0.95:   3.936 ms/op
                 getUser·p0.99:   4.377 ms/op
                 getUser·p0.999:  7.623 ms/op
                 getUser·p0.9999: 11.956 ms/op
                 getUser·p1.00:   12.190 ms/op

Iteration   2: 3.178 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.783 ms/op
                 getUser·p0.50:   3.117 ms/op
                 getUser·p0.90:   3.764 ms/op
                 getUser·p0.95:   3.912 ms/op
                 getUser·p0.99:   4.719 ms/op
                 getUser·p0.999:  10.834 ms/op
                 getUser·p0.9999: 15.888 ms/op
                 getUser·p1.00:   16.237 ms/op

Iteration   3: 3.198 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.649 ms/op
                 getUser·p0.50:   3.150 ms/op
                 getUser·p0.90:   3.850 ms/op
                 getUser·p0.95:   3.994 ms/op
                 getUser·p0.99:   4.260 ms/op
                 getUser·p0.999:  9.328 ms/op
                 getUser·p0.9999: 14.533 ms/op
                 getUser·p1.00:   14.696 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 302196
  mean =      3.177 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 596 
    [ 1.250,  2.500) = 6963 
    [ 2.500,  3.750) = 259117 
    [ 3.750,  5.000) = 33730 
    [ 5.000,  6.250) = 856 
    [ 6.250,  7.500) = 424 
    [ 7.500,  8.750) = 134 
    [ 8.750, 10.000) = 85 
    [10.000, 11.250) = 87 
    [11.250, 12.500) = 83 
    [12.500, 13.750) = 51 
    [13.750, 15.000) = 38 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.649 ms/op
     p(50.0000) =      3.125 ms/op
     p(90.0000) =      3.801 ms/op
     p(95.0000) =      3.953 ms/op
     p(99.0000) =      4.448 ms/op
     p(99.9000) =      9.775 ms/op
     p(99.9900) =     15.305 ms/op
     p(99.9990) =     16.171 ms/op
     p(99.9999) =     16.237 ms/op
    p(100.0000) =     16.237 ms/op


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
# Warmup Iteration   1: 5.029 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.904 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.829 ±(99.9%) 0.010 ms/op
Iteration   1: 3.888 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.039 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   4.317 ms/op
                 listUser·p0.95:   5.079 ms/op
                 listUser·p0.99:   6.537 ms/op
                 listUser·p0.999:  12.059 ms/op
                 listUser·p0.9999: 13.608 ms/op
                 listUser·p1.00:   13.894 ms/op

Iteration   2: 3.783 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.309 ms/op
                 listUser·p0.50:   3.719 ms/op
                 listUser·p0.90:   4.202 ms/op
                 listUser·p0.95:   4.620 ms/op
                 listUser·p0.99:   6.373 ms/op
                 listUser·p0.999:  13.173 ms/op
                 listUser·p0.9999: 15.008 ms/op
                 listUser·p1.00:   15.090 ms/op

Iteration   3: 3.802 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.204 ms/op
                 listUser·p0.50:   3.727 ms/op
                 listUser·p0.90:   4.301 ms/op
                 listUser·p0.95:   4.899 ms/op
                 listUser·p0.99:   6.398 ms/op
                 listUser·p0.999:  13.515 ms/op
                 listUser·p0.9999: 16.606 ms/op
                 listUser·p1.00:   18.285 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 250896
  mean =      3.824 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3 
    [ 1.250,  2.500) = 2347 
    [ 2.500,  3.750) = 122345 
    [ 3.750,  5.000) = 115149 
    [ 5.000,  6.250) = 7577 
    [ 6.250,  7.500) = 2429 
    [ 7.500,  8.750) = 310 
    [ 8.750, 10.000) = 191 
    [10.000, 11.250) = 112 
    [11.250, 12.500) = 155 
    [12.500, 13.750) = 170 
    [13.750, 15.000) = 67 
    [15.000, 16.250) = 30 
    [16.250, 17.500) = 8 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.039 ms/op
     p(50.0000) =      3.752 ms/op
     p(90.0000) =      4.268 ms/op
     p(95.0000) =      4.882 ms/op
     p(99.0000) =      6.439 ms/op
     p(99.9000) =     12.781 ms/op
     p(99.9900) =     15.286 ms/op
     p(99.9990) =     17.857 ms/op
     p(99.9999) =     18.285 ms/op
    p(100.0000) =     18.285 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.362 ± 4.385  ops/ms
ClientGrpc.existUser                       thrpt       3  10.942 ± 4.531  ops/ms
ClientGrpc.getUser                         thrpt       3  10.395 ± 1.616  ops/ms
ClientGrpc.listUser                        thrpt       3   8.372 ± 0.703  ops/ms
ClientGrpc.createUser                       avgt       3   3.122 ± 0.665   ms/op
ClientGrpc.existUser                        avgt       3   2.952 ± 0.730   ms/op
ClientGrpc.getUser                          avgt       3   3.093 ± 0.195   ms/op
ClientGrpc.listUser                         avgt       3   3.793 ± 0.275   ms/op
ClientGrpc.createUser                     sample  312715   3.072 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.656           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.035           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.580           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.805           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.317           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.496           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.488           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.808           ms/op
ClientGrpc.existUser                      sample  319245   3.007 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.527           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.957           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.535           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.744           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.317           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.076           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          13.779           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          14.402           ms/op
ClientGrpc.getUser                        sample  302196   3.177 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.649           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.125           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.801           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.953           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.448           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.775           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.305           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          16.237           ms/op
ClientGrpc.listUser                       sample  250896   3.824 ± 0.005   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.039           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.752           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.268           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           4.882           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.439           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          12.781           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          15.286           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          18.285           ms/op
