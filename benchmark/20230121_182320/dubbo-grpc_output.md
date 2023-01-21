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
# Warmup Iteration   1: 3.271 ops/ms
# Warmup Iteration   2: 6.767 ops/ms
# Warmup Iteration   3: 8.003 ops/ms
Iteration   1: 8.600 ops/ms
Iteration   2: 8.517 ops/ms
Iteration   3: 8.259 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.459 ±(99.9%) 3.244 ops/ms [Average]
  (min, avg, max) = (8.259, 8.459, 8.600), stdev = 0.178
  CI (99.9%): [5.215, 11.702] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 6.148 ops/ms
# Warmup Iteration   2: 8.440 ops/ms
# Warmup Iteration   3: 8.883 ops/ms
Iteration   1: 8.857 ops/ms
Iteration   2: 8.869 ops/ms
Iteration   3: 9.121 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.949 ±(99.9%) 2.724 ops/ms [Average]
  (min, avg, max) = (8.857, 8.949, 9.121), stdev = 0.149
  CI (99.9%): [6.225, 11.673] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 5.618 ops/ms
# Warmup Iteration   2: 8.033 ops/ms
# Warmup Iteration   3: 8.577 ops/ms
Iteration   1: 9.050 ops/ms
Iteration   2: 8.840 ops/ms
Iteration   3: 8.778 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.889 ±(99.9%) 2.602 ops/ms [Average]
  (min, avg, max) = (8.778, 8.889, 9.050), stdev = 0.143
  CI (99.9%): [6.287, 11.491] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 4.518 ops/ms
# Warmup Iteration   2: 6.428 ops/ms
# Warmup Iteration   3: 6.770 ops/ms
Iteration   1: 6.985 ops/ms
Iteration   2: 6.831 ops/ms
Iteration   3: 6.893 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.903 ±(99.9%) 1.415 ops/ms [Average]
  (min, avg, max) = (6.831, 6.903, 6.985), stdev = 0.078
  CI (99.9%): [5.488, 8.318] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 5.118 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.696 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.655 ±(99.9%) 0.003 ms/op
Iteration   1: 3.570 ±(99.9%) 0.002 ms/op
Iteration   2: 3.632 ±(99.9%) 0.003 ms/op
Iteration   3: 3.621 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.607 ±(99.9%) 0.601 ms/op [Average]
  (min, avg, max) = (3.570, 3.607, 3.632), stdev = 0.033
  CI (99.9%): [3.006, 4.209] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.888 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.701 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.523 ±(99.9%) 0.002 ms/op
Iteration   1: 3.465 ±(99.9%) 0.002 ms/op
Iteration   2: 3.496 ±(99.9%) 0.002 ms/op
Iteration   3: 3.472 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.477 ±(99.9%) 0.302 ms/op [Average]
  (min, avg, max) = (3.465, 3.477, 3.496), stdev = 0.017
  CI (99.9%): [3.175, 3.779] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.148 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.828 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.721 ±(99.9%) 0.005 ms/op
Iteration   1: 3.685 ±(99.9%) 0.003 ms/op
Iteration   2: 3.593 ±(99.9%) 0.003 ms/op
Iteration   3: 3.529 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.602 ±(99.9%) 1.424 ms/op [Average]
  (min, avg, max) = (3.529, 3.602, 3.685), stdev = 0.078
  CI (99.9%): [2.179, 5.026] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 6.712 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.905 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.720 ±(99.9%) 0.022 ms/op
Iteration   1: 4.717 ±(99.9%) 0.005 ms/op
Iteration   2: 4.749 ±(99.9%) 0.011 ms/op
Iteration   3: 4.692 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.719 ±(99.9%) 0.515 ms/op [Average]
  (min, avg, max) = (4.692, 4.719, 4.749), stdev = 0.028
  CI (99.9%): [4.205, 5.234] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.944 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.735 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.642 ±(99.9%) 0.009 ms/op
Iteration   1: 3.692 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.087 ms/op
                 createUser·p0.50:   3.645 ms/op
                 createUser·p0.90:   4.579 ms/op
                 createUser·p0.95:   4.858 ms/op
                 createUser·p0.99:   6.005 ms/op
                 createUser·p0.999:  13.940 ms/op
                 createUser·p0.9999: 22.719 ms/op
                 createUser·p1.00:   23.003 ms/op

Iteration   2: 3.654 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.919 ms/op
                 createUser·p0.50:   3.625 ms/op
                 createUser·p0.90:   4.424 ms/op
                 createUser·p0.95:   4.653 ms/op
                 createUser·p0.99:   5.218 ms/op
                 createUser·p0.999:  7.836 ms/op
                 createUser·p0.9999: 18.309 ms/op
                 createUser·p1.00:   19.530 ms/op

Iteration   3: 3.659 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.896 ms/op
                 createUser·p0.50:   3.617 ms/op
                 createUser·p0.90:   4.440 ms/op
                 createUser·p0.95:   4.653 ms/op
                 createUser·p0.99:   5.276 ms/op
                 createUser·p0.999:  17.826 ms/op
                 createUser·p0.9999: 29.884 ms/op
                 createUser·p1.00:   30.048 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 261540
  mean =      3.668 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9900 
    [ 2.500,  5.000) = 245833 
    [ 5.000,  7.500) = 5046 
    [ 7.500, 10.000) = 444 
    [10.000, 12.500) = 47 
    [12.500, 15.000) = 51 
    [15.000, 17.500) = 75 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 30 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.896 ms/op
     p(50.0000) =      3.629 ms/op
     p(90.0000) =      4.481 ms/op
     p(95.0000) =      4.727 ms/op
     p(99.0000) =      5.456 ms/op
     p(99.9000) =     12.769 ms/op
     p(99.9900) =     29.753 ms/op
     p(99.9990) =     29.995 ms/op
     p(99.9999) =     30.048 ms/op
    p(100.0000) =     30.048 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.769 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.575 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.613 ±(99.9%) 0.009 ms/op
Iteration   1: 3.588 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.961 ms/op
                 existUser·p0.50:   3.543 ms/op
                 existUser·p0.90:   4.383 ms/op
                 existUser·p0.95:   4.678 ms/op
                 existUser·p0.99:   5.693 ms/op
                 existUser·p0.999:  10.135 ms/op
                 existUser·p0.9999: 15.551 ms/op
                 existUser·p1.00:   16.056 ms/op

Iteration   2: 3.495 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.804 ms/op
                 existUser·p0.50:   3.486 ms/op
                 existUser·p0.90:   4.301 ms/op
                 existUser·p0.95:   4.563 ms/op
                 existUser·p0.99:   5.216 ms/op
                 existUser·p0.999:  7.358 ms/op
                 existUser·p0.9999: 19.726 ms/op
                 existUser·p1.00:   19.956 ms/op

Iteration   3: 3.424 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.962 ms/op
                 existUser·p0.50:   3.432 ms/op
                 existUser·p0.90:   4.219 ms/op
                 existUser·p0.95:   4.424 ms/op
                 existUser·p0.99:   4.776 ms/op
                 existUser·p0.999:  6.513 ms/op
                 existUser·p0.9999: 18.372 ms/op
                 existUser·p1.00:   19.300 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 274156
  mean =      3.501 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 358 
    [ 1.250,  2.500) = 16344 
    [ 2.500,  3.750) = 167824 
    [ 3.750,  5.000) = 85675 
    [ 5.000,  6.250) = 3020 
    [ 6.250,  7.500) = 389 
    [ 7.500,  8.750) = 230 
    [ 8.750, 10.000) = 113 
    [10.000, 11.250) = 68 
    [11.250, 12.500) = 4 
    [12.500, 13.750) = 6 
    [13.750, 15.000) = 37 
    [15.000, 16.250) = 24 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.804 ms/op
     p(50.0000) =      3.486 ms/op
     p(90.0000) =      4.301 ms/op
     p(95.0000) =      4.547 ms/op
     p(99.0000) =      5.197 ms/op
     p(99.9000) =      9.241 ms/op
     p(99.9900) =     18.978 ms/op
     p(99.9990) =     19.956 ms/op
     p(99.9999) =     19.956 ms/op
    p(100.0000) =     19.956 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.040 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.722 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.623 ±(99.9%) 0.008 ms/op
Iteration   1: 3.705 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.813 ms/op
                 getUser·p0.50:   3.645 ms/op
                 getUser·p0.90:   4.530 ms/op
                 getUser·p0.95:   4.850 ms/op
                 getUser·p0.99:   5.808 ms/op
                 getUser·p0.999:  15.270 ms/op
                 getUser·p0.9999: 22.831 ms/op
                 getUser·p1.00:   23.331 ms/op

Iteration   2: 3.707 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.632 ms/op
                 getUser·p0.50:   3.654 ms/op
                 getUser·p0.90:   4.522 ms/op
                 getUser·p0.95:   4.809 ms/op
                 getUser·p0.99:   5.792 ms/op
                 getUser·p0.999:  9.686 ms/op
                 getUser·p0.9999: 19.652 ms/op
                 getUser·p1.00:   20.316 ms/op

Iteration   3: 3.575 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.842 ms/op
                 getUser·p0.50:   3.535 ms/op
                 getUser·p0.90:   4.301 ms/op
                 getUser·p0.95:   4.653 ms/op
                 getUser·p0.99:   5.849 ms/op
                 getUser·p0.999:  10.060 ms/op
                 getUser·p0.9999: 20.021 ms/op
                 getUser·p1.00:   20.382 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 262049
  mean =      3.661 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10873 
    [ 2.500,  5.000) = 243092 
    [ 5.000,  7.500) = 7188 
    [ 7.500, 10.000) = 624 
    [10.000, 12.500) = 77 
    [12.500, 15.000) = 4 
    [15.000, 17.500) = 84 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.632 ms/op
     p(50.0000) =      3.609 ms/op
     p(90.0000) =      4.465 ms/op
     p(95.0000) =      4.784 ms/op
     p(99.0000) =      5.825 ms/op
     p(99.9000) =     10.058 ms/op
     p(99.9900) =     22.210 ms/op
     p(99.9990) =     23.192 ms/op
     p(99.9999) =     23.331 ms/op
    p(100.0000) =     23.331 ms/op


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
# Warmup Iteration   1: 5.766 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 5.047 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.722 ±(99.9%) 0.014 ms/op
Iteration   1: 4.646 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.626 ms/op
                 listUser·p0.50:   4.481 ms/op
                 listUser·p0.90:   5.677 ms/op
                 listUser·p0.95:   6.660 ms/op
                 listUser·p0.99:   8.618 ms/op
                 listUser·p0.999:  14.786 ms/op
                 listUser·p0.9999: 19.825 ms/op
                 listUser·p1.00:   20.480 ms/op

Iteration   2: 4.831 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.180 ms/op
                 listUser·p0.50:   4.604 ms/op
                 listUser·p0.90:   6.177 ms/op
                 listUser·p0.95:   6.947 ms/op
                 listUser·p0.99:   8.421 ms/op
                 listUser·p0.999:  16.232 ms/op
                 listUser·p0.9999: 23.933 ms/op
                 listUser·p1.00:   27.492 ms/op

Iteration   3: 4.744 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.106 ms/op
                 listUser·p0.50:   4.563 ms/op
                 listUser·p0.90:   6.021 ms/op
                 listUser·p0.95:   6.709 ms/op
                 listUser·p0.99:   8.241 ms/op
                 listUser·p0.999:  19.628 ms/op
                 listUser·p0.9999: 24.716 ms/op
                 listUser·p1.00:   25.166 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 202498
  mean =      4.739 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 579 
    [ 2.500,  5.000) = 150495 
    [ 5.000,  7.500) = 46305 
    [ 7.500, 10.000) = 4482 
    [10.000, 12.500) = 305 
    [12.500, 15.000) = 53 
    [15.000, 17.500) = 103 
    [17.500, 20.000) = 102 
    [20.000, 22.500) = 58 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.106 ms/op
     p(50.0000) =      4.547 ms/op
     p(90.0000) =      5.988 ms/op
     p(95.0000) =      6.783 ms/op
     p(99.0000) =      8.438 ms/op
     p(99.9000) =     16.974 ms/op
     p(99.9900) =     21.946 ms/op
     p(99.9990) =     25.163 ms/op
     p(99.9999) =     27.492 ms/op
    p(100.0000) =     27.492 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.459 ± 3.244  ops/ms
ClientGrpc.existUser                       thrpt       3   8.949 ± 2.724  ops/ms
ClientGrpc.getUser                         thrpt       3   8.889 ± 2.602  ops/ms
ClientGrpc.listUser                        thrpt       3   6.903 ± 1.415  ops/ms
ClientGrpc.createUser                       avgt       3   3.607 ± 0.601   ms/op
ClientGrpc.existUser                        avgt       3   3.477 ± 0.302   ms/op
ClientGrpc.getUser                          avgt       3   3.602 ± 1.424   ms/op
ClientGrpc.listUser                         avgt       3   4.719 ± 0.515   ms/op
ClientGrpc.createUser                     sample  261540   3.668 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.896           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.629           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.481           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.727           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.456           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.769           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          29.753           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          30.048           ms/op
ClientGrpc.existUser                      sample  274156   3.501 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.804           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.486           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.301           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.547           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.197           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.241           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.978           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.956           ms/op
ClientGrpc.getUser                        sample  262049   3.661 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.632           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.609           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.465           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.784           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.825           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.058           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.210           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.331           ms/op
ClientGrpc.listUser                       sample  202498   4.739 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.106           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.547           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.988           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.783           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.438           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.974           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.946           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.492           ms/op
