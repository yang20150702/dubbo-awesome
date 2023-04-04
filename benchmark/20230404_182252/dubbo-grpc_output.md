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
# Warmup Iteration   1: 2.918 ops/ms
# Warmup Iteration   2: 7.266 ops/ms
# Warmup Iteration   3: 8.573 ops/ms
Iteration   1: 8.868 ops/ms
Iteration   2: 8.684 ops/ms
Iteration   3: 8.606 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.719 ±(99.9%) 2.450 ops/ms [Average]
  (min, avg, max) = (8.606, 8.719, 8.868), stdev = 0.134
  CI (99.9%): [6.270, 11.169] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 5.907 ops/ms
# Warmup Iteration   2: 8.572 ops/ms
# Warmup Iteration   3: 9.319 ops/ms
Iteration   1: 9.249 ops/ms
Iteration   2: 9.150 ops/ms
Iteration   3: 9.307 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.235 ±(99.9%) 1.452 ops/ms [Average]
  (min, avg, max) = (9.150, 9.235, 9.307), stdev = 0.080
  CI (99.9%): [7.783, 10.688] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 5.666 ops/ms
# Warmup Iteration   2: 8.598 ops/ms
# Warmup Iteration   3: 8.783 ops/ms
Iteration   1: 8.792 ops/ms
Iteration   2: 8.968 ops/ms
Iteration   3: 9.046 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.935 ±(99.9%) 2.381 ops/ms [Average]
  (min, avg, max) = (8.792, 8.935, 9.046), stdev = 0.131
  CI (99.9%): [6.555, 11.316] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 4.474 ops/ms
# Warmup Iteration   2: 6.479 ops/ms
# Warmup Iteration   3: 6.766 ops/ms
Iteration   1: 6.785 ops/ms
Iteration   2: 6.613 ops/ms
Iteration   3: 6.721 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.706 ±(99.9%) 1.589 ops/ms [Average]
  (min, avg, max) = (6.613, 6.706, 6.785), stdev = 0.087
  CI (99.9%): [5.118, 8.295] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.254 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.063 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.906 ±(99.9%) 0.012 ms/op
Iteration   1: 3.784 ±(99.9%) 0.003 ms/op
Iteration   2: 3.769 ±(99.9%) 0.003 ms/op
Iteration   3: 3.721 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.758 ±(99.9%) 0.599 ms/op [Average]
  (min, avg, max) = (3.721, 3.758, 3.784), stdev = 0.033
  CI (99.9%): [3.159, 4.357] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 5.006 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.833 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.496 ±(99.9%) 0.002 ms/op
Iteration   1: 3.520 ±(99.9%) 0.003 ms/op
Iteration   2: 3.536 ±(99.9%) 0.003 ms/op
Iteration   3: 3.561 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.539 ±(99.9%) 0.376 ms/op [Average]
  (min, avg, max) = (3.520, 3.539, 3.561), stdev = 0.021
  CI (99.9%): [3.163, 3.915] (assumes normal distribution)


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
# Warmup Iteration   1: 5.303 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 3.934 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.833 ±(99.9%) 0.004 ms/op
Iteration   1: 3.710 ±(99.9%) 0.003 ms/op
Iteration   2: 3.595 ±(99.9%) 0.003 ms/op
Iteration   3: 3.577 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.627 ±(99.9%) 1.316 ms/op [Average]
  (min, avg, max) = (3.577, 3.627, 3.710), stdev = 0.072
  CI (99.9%): [2.311, 4.943] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 6.705 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 5.157 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.776 ±(99.9%) 0.016 ms/op
Iteration   1: 4.851 ±(99.9%) 0.013 ms/op
Iteration   2: 4.718 ±(99.9%) 0.007 ms/op
Iteration   3: 4.752 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.773 ±(99.9%) 1.257 ms/op [Average]
  (min, avg, max) = (4.718, 4.773, 4.851), stdev = 0.069
  CI (99.9%): [3.517, 6.030] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.214 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 3.964 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.715 ±(99.9%) 0.010 ms/op
Iteration   1: 3.762 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.805 ms/op
                 createUser·p0.50:   3.662 ms/op
                 createUser·p0.90:   4.465 ms/op
                 createUser·p0.95:   4.817 ms/op
                 createUser·p0.99:   6.078 ms/op
                 createUser·p0.999:  11.091 ms/op
                 createUser·p0.9999: 39.649 ms/op
                 createUser·p1.00:   41.812 ms/op

Iteration   2: 3.685 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.993 ms/op
                 createUser·p0.50:   3.621 ms/op
                 createUser·p0.90:   4.415 ms/op
                 createUser·p0.95:   4.719 ms/op
                 createUser·p0.99:   5.702 ms/op
                 createUser·p0.999:  10.994 ms/op
                 createUser·p0.9999: 21.298 ms/op
                 createUser·p1.00:   22.905 ms/op

Iteration   3: 3.841 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.759 ms/op
                 createUser·p0.50:   3.736 ms/op
                 createUser·p0.90:   4.678 ms/op
                 createUser·p0.95:   5.128 ms/op
                 createUser·p0.99:   7.610 ms/op
                 createUser·p0.999:  13.466 ms/op
                 createUser·p0.9999: 25.078 ms/op
                 createUser·p1.00:   25.592 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 255157
  mean =      3.762 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 244794 
    [ 5.000, 10.000) = 9934 
    [10.000, 15.000) = 237 
    [15.000, 20.000) = 65 
    [20.000, 25.000) = 86 
    [25.000, 30.000) = 10 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 29 
    [40.000, 45.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.759 ms/op
     p(50.0000) =      3.670 ms/op
     p(90.0000) =      4.522 ms/op
     p(95.0000) =      4.882 ms/op
     p(99.0000) =      6.521 ms/op
     p(99.9000) =     12.154 ms/op
     p(99.9900) =     39.453 ms/op
     p(99.9990) =     40.538 ms/op
     p(99.9999) =     41.812 ms/op
    p(100.0000) =     41.812 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.251 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.775 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.616 ±(99.9%) 0.009 ms/op
Iteration   1: 3.443 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.856 ms/op
                 existUser·p0.50:   3.387 ms/op
                 existUser·p0.90:   4.047 ms/op
                 existUser·p0.95:   4.358 ms/op
                 existUser·p0.99:   5.317 ms/op
                 existUser·p0.999:  8.004 ms/op
                 existUser·p0.9999: 17.085 ms/op
                 existUser·p1.00:   17.695 ms/op

Iteration   2: 3.558 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.036 ms/op
                 existUser·p0.50:   3.457 ms/op
                 existUser·p0.90:   4.211 ms/op
                 existUser·p0.95:   4.555 ms/op
                 existUser·p0.99:   5.784 ms/op
                 existUser·p0.999:  12.500 ms/op
                 existUser·p0.9999: 30.140 ms/op
                 existUser·p1.00:   31.687 ms/op

Iteration   3: 3.415 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.845 ms/op
                 existUser·p0.50:   3.359 ms/op
                 existUser·p0.90:   3.998 ms/op
                 existUser·p0.95:   4.317 ms/op
                 existUser·p0.99:   5.237 ms/op
                 existUser·p0.999:  9.363 ms/op
                 existUser·p0.9999: 18.436 ms/op
                 existUser·p1.00:   18.907 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 276743
  mean =      3.471 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5549 
    [ 2.500,  5.000) = 266410 
    [ 5.000,  7.500) = 4241 
    [ 7.500, 10.000) = 321 
    [10.000, 12.500) = 36 
    [12.500, 15.000) = 67 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 22 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.845 ms/op
     p(50.0000) =      3.400 ms/op
     p(90.0000) =      4.092 ms/op
     p(95.0000) =      4.415 ms/op
     p(99.0000) =      5.431 ms/op
     p(99.9000) =      8.978 ms/op
     p(99.9900) =     27.132 ms/op
     p(99.9990) =     31.596 ms/op
     p(99.9999) =     31.687 ms/op
    p(100.0000) =     31.687 ms/op


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
# Warmup Iteration   1: 5.240 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.764 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.723 ±(99.9%) 0.009 ms/op
Iteration   1: 3.743 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.009 ms/op
                 getUser·p0.50:   3.650 ms/op
                 getUser·p0.90:   4.530 ms/op
                 getUser·p0.95:   4.858 ms/op
                 getUser·p0.99:   6.078 ms/op
                 getUser·p0.999:  13.684 ms/op
                 getUser·p0.9999: 21.919 ms/op
                 getUser·p1.00:   22.282 ms/op

Iteration   2: 3.746 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.000 ms/op
                 getUser·p0.50:   3.650 ms/op
                 getUser·p0.90:   4.465 ms/op
                 getUser·p0.95:   4.841 ms/op
                 getUser·p0.99:   6.767 ms/op
                 getUser·p0.999:  13.019 ms/op
                 getUser·p0.9999: 23.427 ms/op
                 getUser·p1.00:   24.084 ms/op

Iteration   3: 3.917 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.965 ms/op
                 getUser·p0.50:   3.793 ms/op
                 getUser·p0.90:   4.809 ms/op
                 getUser·p0.95:   5.333 ms/op
                 getUser·p0.99:   7.356 ms/op
                 getUser·p0.999:  11.379 ms/op
                 getUser·p0.9999: 22.604 ms/op
                 getUser·p1.00:   23.069 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 252483
  mean =      3.800 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6578 
    [ 2.500,  5.000) = 233172 
    [ 5.000,  7.500) = 11187 
    [ 7.500, 10.000) = 1180 
    [10.000, 12.500) = 104 
    [12.500, 15.000) = 110 
    [15.000, 17.500) = 52 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 56 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.965 ms/op
     p(50.0000) =      3.690 ms/op
     p(90.0000) =      4.596 ms/op
     p(95.0000) =      5.005 ms/op
     p(99.0000) =      6.808 ms/op
     p(99.9000) =     12.796 ms/op
     p(99.9900) =     23.003 ms/op
     p(99.9990) =     23.674 ms/op
     p(99.9999) =     24.084 ms/op
    p(100.0000) =     24.084 ms/op


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
# Warmup Iteration   1: 7.161 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 5.091 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.809 ±(99.9%) 0.015 ms/op
Iteration   1: 4.757 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.401 ms/op
                 listUser·p0.50:   4.547 ms/op
                 listUser·p0.90:   6.152 ms/op
                 listUser·p0.95:   7.021 ms/op
                 listUser·p0.99:   8.634 ms/op
                 listUser·p0.999:  15.964 ms/op
                 listUser·p0.9999: 23.187 ms/op
                 listUser·p1.00:   24.052 ms/op

Iteration   2: 4.807 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.499 ms/op
                 listUser·p0.50:   4.604 ms/op
                 listUser·p0.90:   5.915 ms/op
                 listUser·p0.95:   6.857 ms/op
                 listUser·p0.99:   8.651 ms/op
                 listUser·p0.999:  16.839 ms/op
                 listUser·p0.9999: 23.571 ms/op
                 listUser·p1.00:   23.953 ms/op

Iteration   3: 4.786 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.532 ms/op
                 listUser·p0.50:   4.571 ms/op
                 listUser·p0.90:   5.964 ms/op
                 listUser·p0.95:   6.873 ms/op
                 listUser·p0.99:   8.859 ms/op
                 listUser·p0.999:  21.496 ms/op
                 listUser·p0.9999: 34.669 ms/op
                 listUser·p1.00:   34.800 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 200702
  mean =      4.783 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 471 
    [ 2.500,  5.000) = 148534 
    [ 5.000,  7.500) = 45504 
    [ 7.500, 10.000) = 5384 
    [10.000, 12.500) = 485 
    [12.500, 15.000) = 52 
    [15.000, 17.500) = 111 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 12 
    [27.500, 30.000) = 18 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 32 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.401 ms/op
     p(50.0000) =      4.579 ms/op
     p(90.0000) =      6.013 ms/op
     p(95.0000) =      6.930 ms/op
     p(99.0000) =      8.716 ms/op
     p(99.9000) =     17.007 ms/op
     p(99.9900) =     34.406 ms/op
     p(99.9990) =     34.799 ms/op
     p(99.9999) =     34.800 ms/op
    p(100.0000) =     34.800 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.719 ± 2.450  ops/ms
ClientGrpc.existUser                       thrpt       3   9.235 ± 1.452  ops/ms
ClientGrpc.getUser                         thrpt       3   8.935 ± 2.381  ops/ms
ClientGrpc.listUser                        thrpt       3   6.706 ± 1.589  ops/ms
ClientGrpc.createUser                       avgt       3   3.758 ± 0.599   ms/op
ClientGrpc.existUser                        avgt       3   3.539 ± 0.376   ms/op
ClientGrpc.getUser                          avgt       3   3.627 ± 1.316   ms/op
ClientGrpc.listUser                         avgt       3   4.773 ± 1.257   ms/op
ClientGrpc.createUser                     sample  255157   3.762 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.759           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.670           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.522           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.882           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.521           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.154           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          39.453           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          41.812           ms/op
ClientGrpc.existUser                      sample  276743   3.471 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.845           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.400           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.092           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.415           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.431           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.978           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          27.132           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          31.687           ms/op
ClientGrpc.getUser                        sample  252483   3.800 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.965           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.690           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.596           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.005           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.808           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.796           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.003           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.084           ms/op
ClientGrpc.listUser                       sample  200702   4.783 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.401           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.579           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.013           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.930           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.716           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.007           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          34.406           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          34.800           ms/op
