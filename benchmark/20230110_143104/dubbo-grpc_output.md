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
# Warmup Iteration   1: 2.320 ops/ms
# Warmup Iteration   2: 5.713 ops/ms
# Warmup Iteration   3: 7.247 ops/ms
Iteration   1: 7.326 ops/ms
Iteration   2: 6.919 ops/ms
Iteration   3: 6.904 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.050 ±(99.9%) 4.372 ops/ms [Average]
  (min, avg, max) = (6.904, 7.050, 7.326), stdev = 0.240
  CI (99.9%): [2.678, 11.421] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.150 ops/ms
# Warmup Iteration   2: 7.135 ops/ms
# Warmup Iteration   3: 7.660 ops/ms
Iteration   1: 7.725 ops/ms
Iteration   2: 7.747 ops/ms
Iteration   3: 7.876 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.783 ±(99.9%) 1.488 ops/ms [Average]
  (min, avg, max) = (7.725, 7.783, 7.876), stdev = 0.082
  CI (99.9%): [6.294, 9.271] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 4.180 ops/ms
# Warmup Iteration   2: 6.772 ops/ms
# Warmup Iteration   3: 7.042 ops/ms
Iteration   1: 7.025 ops/ms
Iteration   2: 7.076 ops/ms
Iteration   3: 7.090 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.064 ±(99.9%) 0.625 ops/ms [Average]
  (min, avg, max) = (7.025, 7.064, 7.090), stdev = 0.034
  CI (99.9%): [6.439, 7.688] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 4.206 ops/ms
# Warmup Iteration   2: 5.331 ops/ms
# Warmup Iteration   3: 5.746 ops/ms
Iteration   1: 5.696 ops/ms
Iteration   2: 5.909 ops/ms
Iteration   3: 5.697 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.767 ±(99.9%) 2.243 ops/ms [Average]
  (min, avg, max) = (5.696, 5.767, 5.909), stdev = 0.123
  CI (99.9%): [3.524, 8.011] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.962 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.707 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.457 ±(99.9%) 0.002 ms/op
Iteration   1: 4.477 ±(99.9%) 0.002 ms/op
Iteration   2: 4.514 ±(99.9%) 0.006 ms/op
Iteration   3: 4.583 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.525 ±(99.9%) 0.983 ms/op [Average]
  (min, avg, max) = (4.477, 4.525, 4.583), stdev = 0.054
  CI (99.9%): [3.541, 5.508] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 6.067 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.498 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.398 ±(99.9%) 0.003 ms/op
Iteration   1: 4.337 ±(99.9%) 0.003 ms/op
Iteration   2: 4.246 ±(99.9%) 0.004 ms/op
Iteration   3: 4.298 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.294 ±(99.9%) 0.839 ms/op [Average]
  (min, avg, max) = (4.246, 4.294, 4.337), stdev = 0.046
  CI (99.9%): [3.455, 5.132] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 6.494 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.553 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.523 ±(99.9%) 0.002 ms/op
Iteration   1: 4.532 ±(99.9%) 0.003 ms/op
Iteration   2: 4.530 ±(99.9%) 0.003 ms/op
Iteration   3: 4.452 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.505 ±(99.9%) 0.836 ms/op [Average]
  (min, avg, max) = (4.452, 4.505, 4.532), stdev = 0.046
  CI (99.9%): [3.668, 5.341] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 8.096 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 5.922 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 5.511 ±(99.9%) 0.015 ms/op
Iteration   1: 5.346 ±(99.9%) 0.009 ms/op
Iteration   2: 5.426 ±(99.9%) 0.009 ms/op
Iteration   3: 5.447 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.407 ±(99.9%) 0.971 ms/op [Average]
  (min, avg, max) = (5.346, 5.407, 5.447), stdev = 0.053
  CI (99.9%): [4.436, 6.378] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 6.306 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 4.619 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.456 ±(99.9%) 0.012 ms/op
Iteration   1: 4.390 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.990 ms/op
                 createUser·p0.50:   4.268 ms/op
                 createUser·p0.90:   5.480 ms/op
                 createUser·p0.95:   5.874 ms/op
                 createUser·p0.99:   7.607 ms/op
                 createUser·p0.999:  11.223 ms/op
                 createUser·p0.9999: 23.935 ms/op
                 createUser·p1.00:   27.394 ms/op

Iteration   2: 4.457 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.410 ms/op
                 createUser·p0.50:   4.391 ms/op
                 createUser·p0.90:   5.685 ms/op
                 createUser·p0.95:   6.038 ms/op
                 createUser·p0.99:   6.947 ms/op
                 createUser·p0.999:  11.878 ms/op
                 createUser·p0.9999: 18.076 ms/op
                 createUser·p1.00:   18.612 ms/op

Iteration   3: 4.400 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.116 ms/op
                 createUser·p0.50:   4.325 ms/op
                 createUser·p0.90:   5.554 ms/op
                 createUser·p0.95:   5.947 ms/op
                 createUser·p0.99:   7.203 ms/op
                 createUser·p0.999:  12.543 ms/op
                 createUser·p0.9999: 23.500 ms/op
                 createUser·p1.00:   24.052 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 217416
  mean =      4.415 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3499 
    [ 2.500,  5.000) = 161662 
    [ 5.000,  7.500) = 50414 
    [ 7.500, 10.000) = 1341 
    [10.000, 12.500) = 328 
    [12.500, 15.000) = 51 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.410 ms/op
     p(50.0000) =      4.325 ms/op
     p(90.0000) =      5.579 ms/op
     p(95.0000) =      5.964 ms/op
     p(99.0000) =      7.225 ms/op
     p(99.9000) =     11.698 ms/op
     p(99.9900) =     23.044 ms/op
     p(99.9990) =     27.196 ms/op
     p(99.9999) =     27.394 ms/op
    p(100.0000) =     27.394 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.596 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 4.485 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.452 ±(99.9%) 0.012 ms/op
Iteration   1: 4.127 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.944 ms/op
                 existUser·p0.50:   4.076 ms/op
                 existUser·p0.90:   5.374 ms/op
                 existUser·p0.95:   5.767 ms/op
                 existUser·p0.99:   6.898 ms/op
                 existUser·p0.999:  12.455 ms/op
                 existUser·p0.9999: 17.219 ms/op
                 existUser·p1.00:   17.695 ms/op

Iteration   2: 4.205 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.980 ms/op
                 existUser·p0.50:   4.104 ms/op
                 existUser·p0.90:   5.382 ms/op
                 existUser·p0.95:   5.743 ms/op
                 existUser·p0.99:   6.791 ms/op
                 existUser·p0.999:  10.137 ms/op
                 existUser·p0.9999: 18.383 ms/op
                 existUser·p1.00:   18.711 ms/op

Iteration   3: 4.158 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.092 ms/op
                 existUser·p0.50:   4.092 ms/op
                 existUser·p0.90:   5.439 ms/op
                 existUser·p0.95:   5.784 ms/op
                 existUser·p0.99:   6.709 ms/op
                 existUser·p0.999:  12.557 ms/op
                 existUser·p0.9999: 21.057 ms/op
                 existUser·p1.00:   21.594 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 230647
  mean =      4.163 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10282 
    [ 2.500,  5.000) = 177762 
    [ 5.000,  7.500) = 41214 
    [ 7.500, 10.000) = 1006 
    [10.000, 12.500) = 196 
    [12.500, 15.000) = 66 
    [15.000, 17.500) = 65 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.944 ms/op
     p(50.0000) =      4.092 ms/op
     p(90.0000) =      5.399 ms/op
     p(95.0000) =      5.767 ms/op
     p(99.0000) =      6.808 ms/op
     p(99.9000) =     11.796 ms/op
     p(99.9900) =     18.383 ms/op
     p(99.9990) =     21.564 ms/op
     p(99.9999) =     21.594 ms/op
    p(100.0000) =     21.594 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 6.091 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 4.525 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.359 ±(99.9%) 0.012 ms/op
Iteration   1: 4.510 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.139 ms/op
                 getUser·p0.50:   4.432 ms/op
                 getUser·p0.90:   5.677 ms/op
                 getUser·p0.95:   6.013 ms/op
                 getUser·p0.99:   7.037 ms/op
                 getUser·p0.999:  12.582 ms/op
                 getUser·p0.9999: 17.069 ms/op
                 getUser·p1.00:   17.302 ms/op

Iteration   2: 4.438 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.120 ms/op
                 getUser·p0.50:   4.358 ms/op
                 getUser·p0.90:   5.620 ms/op
                 getUser·p0.95:   5.980 ms/op
                 getUser·p0.99:   7.086 ms/op
                 getUser·p0.999:  9.912 ms/op
                 getUser·p0.9999: 25.093 ms/op
                 getUser·p1.00:   25.461 ms/op

Iteration   3: 4.336 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.931 ms/op
                 getUser·p0.50:   4.235 ms/op
                 getUser·p0.90:   5.439 ms/op
                 getUser·p0.95:   5.833 ms/op
                 getUser·p0.99:   6.840 ms/op
                 getUser·p0.999:  11.346 ms/op
                 getUser·p0.9999: 19.517 ms/op
                 getUser·p1.00:   20.480 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 216857
  mean =      4.427 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3158 
    [ 2.500,  5.000) = 159933 
    [ 5.000,  7.500) = 52417 
    [ 7.500, 10.000) = 1062 
    [10.000, 12.500) = 118 
    [12.500, 15.000) = 36 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.931 ms/op
     p(50.0000) =      4.334 ms/op
     p(90.0000) =      5.587 ms/op
     p(95.0000) =      5.947 ms/op
     p(99.0000) =      6.988 ms/op
     p(99.9000) =     11.062 ms/op
     p(99.9900) =     23.593 ms/op
     p(99.9990) =     25.406 ms/op
     p(99.9999) =     25.461 ms/op
    p(100.0000) =     25.461 ms/op


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
# Warmup Iteration   1: 6.718 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 6.085 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 5.517 ±(99.9%) 0.018 ms/op
Iteration   1: 5.684 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.612 ms/op
                 listUser·p0.50:   5.382 ms/op
                 listUser·p0.90:   7.537 ms/op
                 listUser·p0.95:   8.364 ms/op
                 listUser·p0.99:   10.306 ms/op
                 listUser·p0.999:  15.945 ms/op
                 listUser·p0.9999: 18.633 ms/op
                 listUser·p1.00:   19.530 ms/op

Iteration   2: 5.481 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.610 ms/op
                 listUser·p0.50:   5.218 ms/op
                 listUser·p0.90:   7.184 ms/op
                 listUser·p0.95:   8.143 ms/op
                 listUser·p0.99:   10.568 ms/op
                 listUser·p0.999:  18.383 ms/op
                 listUser·p0.9999: 26.847 ms/op
                 listUser·p1.00:   27.427 ms/op

Iteration   3: 5.545 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.206 ms/op
                 listUser·p0.50:   5.333 ms/op
                 listUser·p0.90:   7.086 ms/op
                 listUser·p0.95:   7.995 ms/op
                 listUser·p0.99:   9.912 ms/op
                 listUser·p0.999:  20.382 ms/op
                 listUser·p0.9999: 28.710 ms/op
                 listUser·p1.00:   29.622 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 172393
  mean =      5.569 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 167 
    [ 2.500,  5.000) = 62306 
    [ 5.000,  7.500) = 95110 
    [ 7.500, 10.000) = 12756 
    [10.000, 12.500) = 1479 
    [12.500, 15.000) = 249 
    [15.000, 17.500) = 137 
    [17.500, 20.000) = 89 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 33 

  Percentiles, ms/op:
      p(0.0000) =      1.206 ms/op
     p(50.0000) =      5.308 ms/op
     p(90.0000) =      7.291 ms/op
     p(95.0000) =      8.184 ms/op
     p(99.0000) =     10.273 ms/op
     p(99.9000) =     17.859 ms/op
     p(99.9900) =     27.133 ms/op
     p(99.9990) =     29.622 ms/op
     p(99.9999) =     29.622 ms/op
    p(100.0000) =     29.622 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.050 ± 4.372  ops/ms
ClientGrpc.existUser                       thrpt       3   7.783 ± 1.488  ops/ms
ClientGrpc.getUser                         thrpt       3   7.064 ± 0.625  ops/ms
ClientGrpc.listUser                        thrpt       3   5.767 ± 2.243  ops/ms
ClientGrpc.createUser                       avgt       3   4.525 ± 0.983   ms/op
ClientGrpc.existUser                        avgt       3   4.294 ± 0.839   ms/op
ClientGrpc.getUser                          avgt       3   4.505 ± 0.836   ms/op
ClientGrpc.listUser                         avgt       3   5.407 ± 0.971   ms/op
ClientGrpc.createUser                     sample  217416   4.415 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.410           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.325           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.579           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.964           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.225           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.698           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.044           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.394           ms/op
ClientGrpc.existUser                      sample  230647   4.163 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.944           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.092           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.399           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.767           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.808           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.796           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.383           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.594           ms/op
ClientGrpc.getUser                        sample  216857   4.427 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.931           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.334           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.587           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.947           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.988           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.062           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.593           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.461           ms/op
ClientGrpc.listUser                       sample  172393   5.569 ± 0.012   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.206           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.308           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.291           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.184           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.273           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.859           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.133           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.622           ms/op
