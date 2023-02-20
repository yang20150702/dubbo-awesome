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
# Warmup Iteration   1: 4.245 ops/ms
# Warmup Iteration   2: 8.921 ops/ms
# Warmup Iteration   3: 10.094 ops/ms
Iteration   1: 10.588 ops/ms
Iteration   2: 10.100 ops/ms
Iteration   3: 10.156 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.282 ±(99.9%) 4.874 ops/ms [Average]
  (min, avg, max) = (10.100, 10.282, 10.588), stdev = 0.267
  CI (99.9%): [5.407, 15.156] (assumes normal distribution)


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
# Warmup Iteration   1: 7.382 ops/ms
# Warmup Iteration   2: 10.221 ops/ms
# Warmup Iteration   3: 10.524 ops/ms
Iteration   1: 10.927 ops/ms
Iteration   2: 10.623 ops/ms
Iteration   3: 10.568 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.706 ±(99.9%) 3.531 ops/ms [Average]
  (min, avg, max) = (10.568, 10.706, 10.927), stdev = 0.194
  CI (99.9%): [7.175, 14.237] (assumes normal distribution)


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
# Warmup Iteration   1: 6.814 ops/ms
# Warmup Iteration   2: 9.978 ops/ms
# Warmup Iteration   3: 10.188 ops/ms
Iteration   1: 10.072 ops/ms
Iteration   2: 10.217 ops/ms
Iteration   3: 10.020 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.103 ±(99.9%) 1.863 ops/ms [Average]
  (min, avg, max) = (10.020, 10.103, 10.217), stdev = 0.102
  CI (99.9%): [8.240, 11.965] (assumes normal distribution)


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
# Warmup Iteration   1: 5.631 ops/ms
# Warmup Iteration   2: 7.526 ops/ms
# Warmup Iteration   3: 7.836 ops/ms
Iteration   1: 7.721 ops/ms
Iteration   2: 7.804 ops/ms
Iteration   3: 7.855 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.793 ±(99.9%) 1.230 ops/ms [Average]
  (min, avg, max) = (7.721, 7.793, 7.855), stdev = 0.067
  CI (99.9%): [6.563, 9.024] (assumes normal distribution)


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
# Warmup Iteration   1: 4.368 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.230 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.137 ±(99.9%) 0.002 ms/op
Iteration   1: 3.137 ±(99.9%) 0.009 ms/op
Iteration   2: 3.124 ±(99.9%) 0.002 ms/op
Iteration   3: 3.149 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.137 ±(99.9%) 0.233 ms/op [Average]
  (min, avg, max) = (3.124, 3.137, 3.149), stdev = 0.013
  CI (99.9%): [2.904, 3.370] (assumes normal distribution)


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
# Warmup Iteration   1: 3.904 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.140 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.068 ±(99.9%) 0.002 ms/op
Iteration   1: 3.067 ±(99.9%) 0.002 ms/op
Iteration   2: 2.909 ±(99.9%) 0.002 ms/op
Iteration   3: 2.965 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.980 ±(99.9%) 1.459 ms/op [Average]
  (min, avg, max) = (2.909, 2.980, 3.067), stdev = 0.080
  CI (99.9%): [1.522, 4.439] (assumes normal distribution)


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
# Warmup Iteration   1: 4.346 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.261 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.130 ±(99.9%) 0.003 ms/op
Iteration   1: 3.151 ±(99.9%) 0.003 ms/op
Iteration   2: 3.130 ±(99.9%) 0.002 ms/op
Iteration   3: 3.186 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.156 ±(99.9%) 0.515 ms/op [Average]
  (min, avg, max) = (3.130, 3.156, 3.186), stdev = 0.028
  CI (99.9%): [2.641, 3.670] (assumes normal distribution)


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
# Warmup Iteration   1: 4.482 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 4.349 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.110 ±(99.9%) 0.020 ms/op
Iteration   1: 4.162 ±(99.9%) 0.020 ms/op
Iteration   2: 4.001 ±(99.9%) 0.012 ms/op
Iteration   3: 4.001 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.054 ±(99.9%) 1.700 ms/op [Average]
  (min, avg, max) = (4.001, 4.054, 4.162), stdev = 0.093
  CI (99.9%): [2.355, 5.754] (assumes normal distribution)


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
# Warmup Iteration   1: 4.370 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.244 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.183 ±(99.9%) 0.008 ms/op
Iteration   1: 3.157 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.793 ms/op
                 createUser·p0.50:   3.142 ms/op
                 createUser·p0.90:   3.879 ms/op
                 createUser·p0.95:   4.059 ms/op
                 createUser·p0.99:   4.440 ms/op
                 createUser·p0.999:  7.128 ms/op
                 createUser·p0.9999: 17.924 ms/op
                 createUser·p1.00:   18.579 ms/op

Iteration   2: 3.197 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.837 ms/op
                 createUser·p0.50:   3.187 ms/op
                 createUser·p0.90:   3.924 ms/op
                 createUser·p0.95:   4.080 ms/op
                 createUser·p0.99:   4.432 ms/op
                 createUser·p0.999:  7.618 ms/op
                 createUser·p0.9999: 19.525 ms/op
                 createUser·p1.00:   20.447 ms/op

Iteration   3: 3.143 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.770 ms/op
                 createUser·p0.50:   3.113 ms/op
                 createUser·p0.90:   3.826 ms/op
                 createUser·p0.95:   4.002 ms/op
                 createUser·p0.99:   4.358 ms/op
                 createUser·p0.999:  7.104 ms/op
                 createUser·p0.9999: 37.010 ms/op
                 createUser·p1.00:   37.683 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 303247
  mean =      3.165 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28605 
    [ 2.500,  5.000) = 273626 
    [ 5.000,  7.500) = 736 
    [ 7.500, 10.000) = 87 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.770 ms/op
     p(50.0000) =      3.146 ms/op
     p(90.0000) =      3.879 ms/op
     p(95.0000) =      4.051 ms/op
     p(99.0000) =      4.415 ms/op
     p(99.9000) =      7.223 ms/op
     p(99.9900) =     35.783 ms/op
     p(99.9990) =     37.618 ms/op
     p(99.9999) =     37.683 ms/op
    p(100.0000) =     37.683 ms/op


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
# Warmup Iteration   1: 3.722 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.135 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.084 ±(99.9%) 0.006 ms/op
Iteration   1: 3.067 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.708 ms/op
                 existUser·p0.50:   3.056 ms/op
                 existUser·p0.90:   3.727 ms/op
                 existUser·p0.95:   3.920 ms/op
                 existUser·p0.99:   4.301 ms/op
                 existUser·p0.999:  6.985 ms/op
                 existUser·p0.9999: 13.133 ms/op
                 existUser·p1.00:   13.484 ms/op

Iteration   2: 3.035 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.784 ms/op
                 existUser·p0.50:   3.006 ms/op
                 existUser·p0.90:   3.744 ms/op
                 existUser·p0.95:   3.932 ms/op
                 existUser·p0.99:   4.284 ms/op
                 existUser·p0.999:  6.916 ms/op
                 existUser·p0.9999: 16.939 ms/op
                 existUser·p1.00:   17.433 ms/op

Iteration   3: 3.025 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.515 ms/op
                 existUser·p0.50:   3.002 ms/op
                 existUser·p0.90:   3.629 ms/op
                 existUser·p0.95:   3.793 ms/op
                 existUser·p0.99:   4.293 ms/op
                 existUser·p0.999:  10.101 ms/op
                 existUser·p0.9999: 17.179 ms/op
                 existUser·p1.00:   19.137 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 315430
  mean =      3.042 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1198 
    [ 1.250,  2.500) = 40042 
    [ 2.500,  3.750) = 247769 
    [ 3.750,  5.000) = 25467 
    [ 5.000,  6.250) = 388 
    [ 6.250,  7.500) = 250 
    [ 7.500,  8.750) = 69 
    [ 8.750, 10.000) = 43 
    [10.000, 11.250) = 37 
    [11.250, 12.500) = 7 
    [12.500, 13.750) = 34 
    [13.750, 15.000) = 38 
    [15.000, 16.250) = 21 
    [16.250, 17.500) = 59 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.515 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      3.703 ms/op
     p(95.0000) =      3.883 ms/op
     p(99.0000) =      4.293 ms/op
     p(99.9000) =      7.517 ms/op
     p(99.9900) =     16.843 ms/op
     p(99.9990) =     18.942 ms/op
     p(99.9999) =     19.137 ms/op
    p(100.0000) =     19.137 ms/op


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
# Warmup Iteration   1: 4.365 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.314 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.153 ±(99.9%) 0.006 ms/op
Iteration   1: 3.152 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.838 ms/op
                 getUser·p0.50:   3.131 ms/op
                 getUser·p0.90:   3.838 ms/op
                 getUser·p0.95:   4.039 ms/op
                 getUser·p0.99:   4.473 ms/op
                 getUser·p0.999:  9.454 ms/op
                 getUser·p0.9999: 14.153 ms/op
                 getUser·p1.00:   14.467 ms/op

Iteration   2: 3.109 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.631 ms/op
                 getUser·p0.50:   3.101 ms/op
                 getUser·p0.90:   3.690 ms/op
                 getUser·p0.95:   3.842 ms/op
                 getUser·p0.99:   4.284 ms/op
                 getUser·p0.999:  8.159 ms/op
                 getUser·p0.9999: 14.228 ms/op
                 getUser·p1.00:   14.582 ms/op

Iteration   3: 3.094 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.638 ms/op
                 getUser·p0.50:   3.084 ms/op
                 getUser·p0.90:   3.666 ms/op
                 getUser·p0.95:   3.834 ms/op
                 getUser·p0.99:   4.350 ms/op
                 getUser·p0.999:  7.307 ms/op
                 getUser·p0.9999: 18.121 ms/op
                 getUser·p1.00:   18.153 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 307988
  mean =      3.118 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 785 
    [ 1.250,  2.500) = 23636 
    [ 2.500,  3.750) = 254834 
    [ 3.750,  5.000) = 27465 
    [ 5.000,  6.250) = 613 
    [ 6.250,  7.500) = 217 
    [ 7.500,  8.750) = 161 
    [ 8.750, 10.000) = 97 
    [10.000, 11.250) = 20 
    [11.250, 12.500) = 10 
    [12.500, 13.750) = 61 
    [13.750, 15.000) = 57 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 6 
    [17.500, 18.750) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.631 ms/op
     p(50.0000) =      3.101 ms/op
     p(90.0000) =      3.731 ms/op
     p(95.0000) =      3.912 ms/op
     p(99.0000) =      4.399 ms/op
     p(99.9000) =      8.471 ms/op
     p(99.9900) =     17.020 ms/op
     p(99.9990) =     18.153 ms/op
     p(99.9999) =     18.153 ms/op
    p(100.0000) =     18.153 ms/op


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
# Warmup Iteration   1: 5.833 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 4.194 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.087 ±(99.9%) 0.011 ms/op
Iteration   1: 3.974 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.270 ms/op
                 listUser·p0.50:   3.826 ms/op
                 listUser·p0.90:   5.079 ms/op
                 listUser·p0.95:   5.816 ms/op
                 listUser·p0.99:   7.197 ms/op
                 listUser·p0.999:  13.697 ms/op
                 listUser·p0.9999: 16.674 ms/op
                 listUser·p1.00:   17.170 ms/op

Iteration   2: 4.104 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.434 ms/op
                 listUser·p0.50:   3.932 ms/op
                 listUser·p0.90:   5.243 ms/op
                 listUser·p0.95:   5.800 ms/op
                 listUser·p0.99:   6.865 ms/op
                 listUser·p0.999:  16.269 ms/op
                 listUser·p0.9999: 21.870 ms/op
                 listUser·p1.00:   22.348 ms/op

Iteration   3: 4.070 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.954 ms/op
                 listUser·p0.50:   3.908 ms/op
                 listUser·p0.90:   5.153 ms/op
                 listUser·p0.95:   5.833 ms/op
                 listUser·p0.99:   7.004 ms/op
                 listUser·p0.999:  13.589 ms/op
                 listUser·p0.9999: 19.534 ms/op
                 listUser·p1.00:   19.825 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 236985
  mean =      4.048 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2635 
    [ 2.500,  5.000) = 206963 
    [ 5.000,  7.500) = 25999 
    [ 7.500, 10.000) = 906 
    [10.000, 12.500) = 128 
    [12.500, 15.000) = 160 
    [15.000, 17.500) = 71 
    [17.500, 20.000) = 83 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.954 ms/op
     p(50.0000) =      3.887 ms/op
     p(90.0000) =      5.161 ms/op
     p(95.0000) =      5.816 ms/op
     p(99.0000) =      6.996 ms/op
     p(99.9000) =     14.058 ms/op
     p(99.9900) =     21.407 ms/op
     p(99.9990) =     22.267 ms/op
     p(99.9999) =     22.348 ms/op
    p(100.0000) =     22.348 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.282 ± 4.874  ops/ms
ClientGrpc.existUser                       thrpt       3  10.706 ± 3.531  ops/ms
ClientGrpc.getUser                         thrpt       3  10.103 ± 1.863  ops/ms
ClientGrpc.listUser                        thrpt       3   7.793 ± 1.230  ops/ms
ClientGrpc.createUser                       avgt       3   3.137 ± 0.233   ms/op
ClientGrpc.existUser                        avgt       3   2.980 ± 1.459   ms/op
ClientGrpc.getUser                          avgt       3   3.156 ± 0.515   ms/op
ClientGrpc.listUser                         avgt       3   4.054 ± 1.700   ms/op
ClientGrpc.createUser                     sample  303247   3.165 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.770           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.146           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.879           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.051           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.415           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.223           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          35.783           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          37.683           ms/op
ClientGrpc.existUser                      sample  315430   3.042 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.515           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.023           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.703           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.883           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.293           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.517           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.843           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.137           ms/op
ClientGrpc.getUser                        sample  307988   3.118 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.631           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.101           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.731           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.912           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.399           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.471           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.020           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.153           ms/op
ClientGrpc.listUser                       sample  236985   4.048 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.954           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.887           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.161           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.816           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.996           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.058           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.407           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.348           ms/op
