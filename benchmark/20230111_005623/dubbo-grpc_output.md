# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.091 ops/ms
# Warmup Iteration   2: 8.917 ops/ms
# Warmup Iteration   3: 9.884 ops/ms
Iteration   1: 10.003 ops/ms
Iteration   2: 10.124 ops/ms
Iteration   3: 9.910 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.012 ±(99.9%) 1.955 ops/ms [Average]
  (min, avg, max) = (9.910, 10.012, 10.124), stdev = 0.107
  CI (99.9%): [8.057, 11.968] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.485 ops/ms
# Warmup Iteration   2: 10.417 ops/ms
# Warmup Iteration   3: 10.383 ops/ms
Iteration   1: 10.504 ops/ms
Iteration   2: 10.310 ops/ms
Iteration   3: 10.417 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.410 ±(99.9%) 1.773 ops/ms [Average]
  (min, avg, max) = (10.310, 10.410, 10.504), stdev = 0.097
  CI (99.9%): [8.637, 12.184] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 6.278 ops/ms
# Warmup Iteration   2: 9.632 ops/ms
# Warmup Iteration   3: 10.027 ops/ms
Iteration   1: 10.268 ops/ms
Iteration   2: 9.998 ops/ms
Iteration   3: 9.933 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.066 ±(99.9%) 3.243 ops/ms [Average]
  (min, avg, max) = (9.933, 10.066, 10.268), stdev = 0.178
  CI (99.9%): [6.823, 13.309] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.772 ops/ms
# Warmup Iteration   2: 7.032 ops/ms
# Warmup Iteration   3: 7.558 ops/ms
Iteration   1: 7.765 ops/ms
Iteration   2: 7.854 ops/ms
Iteration   3: 7.884 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.834 ±(99.9%) 1.130 ops/ms [Average]
  (min, avg, max) = (7.765, 7.834, 7.884), stdev = 0.062
  CI (99.9%): [6.705, 8.964] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.541 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.237 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.186 ±(99.9%) 0.002 ms/op
Iteration   1: 3.137 ±(99.9%) 0.002 ms/op
Iteration   2: 3.210 ±(99.9%) 0.002 ms/op
Iteration   3: 3.232 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.193 ±(99.9%) 0.904 ms/op [Average]
  (min, avg, max) = (3.137, 3.193, 3.232), stdev = 0.050
  CI (99.9%): [2.289, 4.097] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.952 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.161 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.134 ±(99.9%) 0.002 ms/op
Iteration   1: 3.031 ±(99.9%) 0.003 ms/op
Iteration   2: 3.099 ±(99.9%) 0.002 ms/op
Iteration   3: 3.074 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.068 ±(99.9%) 0.627 ms/op [Average]
  (min, avg, max) = (3.031, 3.068, 3.099), stdev = 0.034
  CI (99.9%): [2.441, 3.695] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.269 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.251 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.221 ±(99.9%) 0.003 ms/op
Iteration   1: 3.187 ±(99.9%) 0.002 ms/op
Iteration   2: 3.209 ±(99.9%) 0.003 ms/op
Iteration   3: 3.170 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.189 ±(99.9%) 0.358 ms/op [Average]
  (min, avg, max) = (3.170, 3.189, 3.209), stdev = 0.020
  CI (99.9%): [2.831, 3.547] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.982 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 4.244 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 4.056 ±(99.9%) 0.019 ms/op
Iteration   1: 4.007 ±(99.9%) 0.006 ms/op
Iteration   2: 4.061 ±(99.9%) 0.112 ms/op
Iteration   3: 4.009 ±(99.9%) 0.033 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.026 ±(99.9%) 0.559 ms/op [Average]
  (min, avg, max) = (4.007, 4.026, 4.061), stdev = 0.031
  CI (99.9%): [3.466, 4.585] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.595 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.315 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.262 ±(99.9%) 0.007 ms/op
Iteration   1: 3.225 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.298 ms/op
                 createUser·p0.50:   3.187 ms/op
                 createUser·p0.90:   3.895 ms/op
                 createUser·p0.95:   4.092 ms/op
                 createUser·p0.99:   4.489 ms/op
                 createUser·p0.999:  9.687 ms/op
                 createUser·p0.9999: 14.306 ms/op
                 createUser·p1.00:   14.631 ms/op

Iteration   2: 3.209 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.679 ms/op
                 createUser·p0.50:   3.187 ms/op
                 createUser·p0.90:   3.908 ms/op
                 createUser·p0.95:   4.104 ms/op
                 createUser·p0.99:   4.456 ms/op
                 createUser·p0.999:  7.964 ms/op
                 createUser·p0.9999: 16.335 ms/op
                 createUser·p1.00:   16.679 ms/op

Iteration   3: 3.157 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.639 ms/op
                 createUser·p0.50:   3.121 ms/op
                 createUser·p0.90:   3.760 ms/op
                 createUser·p0.95:   3.969 ms/op
                 createUser·p0.99:   4.440 ms/op
                 createUser·p0.999:  7.371 ms/op
                 createUser·p0.9999: 22.245 ms/op
                 createUser·p1.00:   23.331 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 300346
  mean =      3.197 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19299 
    [ 2.500,  5.000) = 279958 
    [ 5.000,  7.500) = 713 
    [ 7.500, 10.000) = 117 
    [10.000, 12.500) = 41 
    [12.500, 15.000) = 69 
    [15.000, 17.500) = 116 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.298 ms/op
     p(50.0000) =      3.162 ms/op
     p(90.0000) =      3.858 ms/op
     p(95.0000) =      4.063 ms/op
     p(99.0000) =      4.465 ms/op
     p(99.9000) =      8.520 ms/op
     p(99.9900) =     19.380 ms/op
     p(99.9990) =     22.249 ms/op
     p(99.9999) =     23.331 ms/op
    p(100.0000) =     23.331 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 4.041 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.123 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.034 ±(99.9%) 0.007 ms/op
Iteration   1: 3.023 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.819 ms/op
                 existUser·p0.50:   3.006 ms/op
                 existUser·p0.90:   3.727 ms/op
                 existUser·p0.95:   3.924 ms/op
                 existUser·p0.99:   4.293 ms/op
                 existUser·p0.999:  6.587 ms/op
                 existUser·p0.9999: 14.471 ms/op
                 existUser·p1.00:   14.991 ms/op

Iteration   2: 3.058 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.697 ms/op
                 existUser·p0.50:   3.039 ms/op
                 existUser·p0.90:   3.719 ms/op
                 existUser·p0.95:   3.908 ms/op
                 existUser·p0.99:   4.243 ms/op
                 existUser·p0.999:  8.756 ms/op
                 existUser·p0.9999: 16.721 ms/op
                 existUser·p1.00:   18.153 ms/op

Iteration   3: 3.041 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.746 ms/op
                 existUser·p0.50:   3.039 ms/op
                 existUser·p0.90:   3.740 ms/op
                 existUser·p0.95:   3.920 ms/op
                 existUser·p0.99:   4.219 ms/op
                 existUser·p0.999:  7.043 ms/op
                 existUser·p0.9999: 19.431 ms/op
                 existUser·p1.00:   19.956 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 315653
  mean =      3.041 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1084 
    [ 1.250,  2.500) = 41210 
    [ 2.500,  3.750) = 243847 
    [ 3.750,  5.000) = 28622 
    [ 5.000,  6.250) = 437 
    [ 6.250,  7.500) = 190 
    [ 7.500,  8.750) = 71 
    [ 8.750, 10.000) = 8 
    [10.000, 11.250) = 23 
    [11.250, 12.500) = 9 
    [12.500, 13.750) = 9 
    [13.750, 15.000) = 47 
    [15.000, 16.250) = 22 
    [16.250, 17.500) = 44 
    [17.500, 18.750) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.697 ms/op
     p(50.0000) =      3.027 ms/op
     p(90.0000) =      3.727 ms/op
     p(95.0000) =      3.916 ms/op
     p(99.0000) =      4.243 ms/op
     p(99.9000) =      7.040 ms/op
     p(99.9900) =     17.498 ms/op
     p(99.9990) =     19.749 ms/op
     p(99.9999) =     19.956 ms/op
    p(100.0000) =     19.956 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.297 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.301 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.232 ±(99.9%) 0.007 ms/op
Iteration   1: 3.183 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.748 ms/op
                 getUser·p0.50:   3.158 ms/op
                 getUser·p0.90:   3.838 ms/op
                 getUser·p0.95:   4.035 ms/op
                 getUser·p0.99:   4.547 ms/op
                 getUser·p0.999:  7.843 ms/op
                 getUser·p0.9999: 17.070 ms/op
                 getUser·p1.00:   17.695 ms/op

Iteration   2: 3.180 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.878 ms/op
                 getUser·p0.50:   3.150 ms/op
                 getUser·p0.90:   3.846 ms/op
                 getUser·p0.95:   4.014 ms/op
                 getUser·p0.99:   4.440 ms/op
                 getUser·p0.999:  8.536 ms/op
                 getUser·p0.9999: 18.608 ms/op
                 getUser·p1.00:   19.530 ms/op

Iteration   3: 3.212 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.819 ms/op
                 getUser·p0.50:   3.191 ms/op
                 getUser·p0.90:   3.916 ms/op
                 getUser·p0.95:   4.096 ms/op
                 getUser·p0.99:   4.481 ms/op
                 getUser·p0.999:  8.729 ms/op
                 getUser·p0.9999: 19.793 ms/op
                 getUser·p1.00:   20.677 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 300840
  mean =      3.192 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19968 
    [ 2.500,  5.000) = 279383 
    [ 5.000,  7.500) = 1111 
    [ 7.500, 10.000) = 192 
    [10.000, 12.500) = 26 
    [12.500, 15.000) = 9 
    [15.000, 17.500) = 96 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.748 ms/op
     p(50.0000) =      3.166 ms/op
     p(90.0000) =      3.867 ms/op
     p(95.0000) =      4.051 ms/op
     p(99.0000) =      4.489 ms/op
     p(99.9000) =      8.569 ms/op
     p(99.9900) =     19.164 ms/op
     p(99.9990) =     20.021 ms/op
     p(99.9999) =     20.677 ms/op
    p(100.0000) =     20.677 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.895 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.409 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.242 ±(99.9%) 0.012 ms/op
Iteration   1: 4.156 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.403 ms/op
                 listUser·p0.50:   3.965 ms/op
                 listUser·p0.90:   5.274 ms/op
                 listUser·p0.95:   6.005 ms/op
                 listUser·p0.99:   7.135 ms/op
                 listUser·p0.999:  14.616 ms/op
                 listUser·p0.9999: 16.476 ms/op
                 listUser·p1.00:   17.367 ms/op

Iteration   2: 4.201 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.802 ms/op
                 listUser·p0.50:   3.990 ms/op
                 listUser·p0.90:   5.374 ms/op
                 listUser·p0.95:   5.882 ms/op
                 listUser·p0.99:   7.135 ms/op
                 listUser·p0.999:  16.302 ms/op
                 listUser·p0.9999: 19.391 ms/op
                 listUser·p1.00:   19.890 ms/op

Iteration   3: 4.020 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.090 ms/op
                 listUser·p0.50:   3.871 ms/op
                 listUser·p0.90:   4.899 ms/op
                 listUser·p0.95:   5.612 ms/op
                 listUser·p0.99:   6.971 ms/op
                 listUser·p0.999:  17.990 ms/op
                 listUser·p0.9999: 22.123 ms/op
                 listUser·p1.00:   23.331 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 232590
  mean =      4.124 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1217 
    [ 2.500,  5.000) = 201347 
    [ 5.000,  7.500) = 28607 
    [ 7.500, 10.000) = 1005 
    [10.000, 12.500) = 62 
    [12.500, 15.000) = 72 
    [15.000, 17.500) = 145 
    [17.500, 20.000) = 99 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.802 ms/op
     p(50.0000) =      3.936 ms/op
     p(90.0000) =      5.243 ms/op
     p(95.0000) =      5.841 ms/op
     p(99.0000) =      7.078 ms/op
     p(99.9000) =     15.892 ms/op
     p(99.9900) =     20.578 ms/op
     p(99.9990) =     23.096 ms/op
     p(99.9999) =     23.331 ms/op
    p(100.0000) =     23.331 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.012 ± 1.955  ops/ms
ClientGrpc.existUser                       thrpt       3  10.410 ± 1.773  ops/ms
ClientGrpc.getUser                         thrpt       3  10.066 ± 3.243  ops/ms
ClientGrpc.listUser                        thrpt       3   7.834 ± 1.130  ops/ms
ClientGrpc.createUser                       avgt       3   3.193 ± 0.904   ms/op
ClientGrpc.existUser                        avgt       3   3.068 ± 0.627   ms/op
ClientGrpc.getUser                          avgt       3   3.189 ± 0.358   ms/op
ClientGrpc.listUser                         avgt       3   4.026 ± 0.559   ms/op
ClientGrpc.createUser                     sample  300346   3.197 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.298           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.162           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.858           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.063           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.465           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.520           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.380           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.331           ms/op
ClientGrpc.existUser                      sample  315653   3.041 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.697           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.027           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.727           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.916           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.243           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.040           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.498           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.956           ms/op
ClientGrpc.getUser                        sample  300840   3.192 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.748           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.166           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.867           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.051           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.489           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.569           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.164           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.677           ms/op
ClientGrpc.listUser                       sample  232590   4.124 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.802           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.936           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.243           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.841           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.078           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.892           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.578           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.331           ms/op
