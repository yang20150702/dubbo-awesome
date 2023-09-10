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
# Warmup Iteration   1: 3.114 ops/ms
# Warmup Iteration   2: 6.736 ops/ms
# Warmup Iteration   3: 8.287 ops/ms
Iteration   1: 8.556 ops/ms
Iteration   2: 8.634 ops/ms
Iteration   3: 8.719 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.636 ±(99.9%) 1.482 ops/ms [Average]
  (min, avg, max) = (8.556, 8.636, 8.719), stdev = 0.081
  CI (99.9%): [7.154, 10.118] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 6.015 ops/ms
# Warmup Iteration   2: 8.389 ops/ms
# Warmup Iteration   3: 8.970 ops/ms
Iteration   1: 8.936 ops/ms
Iteration   2: 9.021 ops/ms
Iteration   3: 9.184 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.047 ±(99.9%) 2.298 ops/ms [Average]
  (min, avg, max) = (8.936, 9.047, 9.184), stdev = 0.126
  CI (99.9%): [6.748, 11.345] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.475 ops/ms
# Warmup Iteration   2: 7.796 ops/ms
# Warmup Iteration   3: 8.301 ops/ms
Iteration   1: 8.653 ops/ms
Iteration   2: 8.456 ops/ms
Iteration   3: 8.614 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.574 ±(99.9%) 1.911 ops/ms [Average]
  (min, avg, max) = (8.456, 8.574, 8.653), stdev = 0.105
  CI (99.9%): [6.663, 10.485] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 4.248 ops/ms
# Warmup Iteration   2: 5.995 ops/ms
# Warmup Iteration   3: 6.615 ops/ms
Iteration   1: 6.745 ops/ms
Iteration   2: 6.623 ops/ms
Iteration   3: 6.879 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.749 ±(99.9%) 2.335 ops/ms [Average]
  (min, avg, max) = (6.623, 6.749, 6.879), stdev = 0.128
  CI (99.9%): [4.414, 9.084] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.441 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.910 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.792 ±(99.9%) 0.005 ms/op
Iteration   1: 3.773 ±(99.9%) 0.003 ms/op
Iteration   2: 3.733 ±(99.9%) 0.005 ms/op
Iteration   3: 3.750 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.752 ±(99.9%) 0.358 ms/op [Average]
  (min, avg, max) = (3.733, 3.752, 3.773), stdev = 0.020
  CI (99.9%): [3.394, 4.110] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 5.056 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.733 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.520 ±(99.9%) 0.003 ms/op
Iteration   1: 3.614 ±(99.9%) 0.003 ms/op
Iteration   2: 3.595 ±(99.9%) 0.002 ms/op
Iteration   3: 3.545 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.584 ±(99.9%) 0.651 ms/op [Average]
  (min, avg, max) = (3.545, 3.584, 3.614), stdev = 0.036
  CI (99.9%): [2.934, 4.235] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.277 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 3.915 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 3.789 ±(99.9%) 0.003 ms/op
Iteration   1: 3.789 ±(99.9%) 0.003 ms/op
Iteration   2: 3.728 ±(99.9%) 0.004 ms/op
Iteration   3: 3.732 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.749 ±(99.9%) 0.622 ms/op [Average]
  (min, avg, max) = (3.728, 3.749, 3.789), stdev = 0.034
  CI (99.9%): [3.127, 4.372] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 6.199 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 5.090 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.833 ±(99.9%) 0.015 ms/op
Iteration   1: 4.814 ±(99.9%) 0.010 ms/op
Iteration   2: 4.754 ±(99.9%) 0.028 ms/op
Iteration   3: 4.659 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.742 ±(99.9%) 1.422 ms/op [Average]
  (min, avg, max) = (4.659, 4.742, 4.814), stdev = 0.078
  CI (99.9%): [3.320, 6.164] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.629 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 4.021 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.717 ±(99.9%) 0.012 ms/op
Iteration   1: 3.714 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.346 ms/op
                 createUser·p0.50:   3.658 ms/op
                 createUser·p0.90:   4.383 ms/op
                 createUser·p0.95:   4.719 ms/op
                 createUser·p0.99:   5.784 ms/op
                 createUser·p0.999:  18.416 ms/op
                 createUser·p0.9999: 25.113 ms/op
                 createUser·p1.00:   25.756 ms/op

Iteration   2: 3.742 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.986 ms/op
                 createUser·p0.50:   3.678 ms/op
                 createUser·p0.90:   4.424 ms/op
                 createUser·p0.95:   4.678 ms/op
                 createUser·p0.99:   5.644 ms/op
                 createUser·p0.999:  9.496 ms/op
                 createUser·p0.9999: 24.573 ms/op
                 createUser·p1.00:   25.166 ms/op

Iteration   3: 3.720 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.660 ms/op
                 createUser·p0.50:   3.654 ms/op
                 createUser·p0.90:   4.456 ms/op
                 createUser·p0.95:   4.686 ms/op
                 createUser·p0.99:   5.382 ms/op
                 createUser·p0.999:  12.387 ms/op
                 createUser·p0.9999: 21.863 ms/op
                 createUser·p1.00:   22.282 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 257662
  mean =      3.725 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5446 
    [ 2.500,  5.000) = 246305 
    [ 5.000,  7.500) = 5159 
    [ 7.500, 10.000) = 445 
    [10.000, 12.500) = 68 
    [12.500, 15.000) = 49 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 81 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 41 
    [25.000, 27.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.346 ms/op
     p(50.0000) =      3.662 ms/op
     p(90.0000) =      4.424 ms/op
     p(95.0000) =      4.686 ms/op
     p(99.0000) =      5.603 ms/op
     p(99.9000) =     11.770 ms/op
     p(99.9900) =     24.453 ms/op
     p(99.9990) =     25.357 ms/op
     p(99.9999) =     25.756 ms/op
    p(100.0000) =     25.756 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.004 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.792 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.543 ±(99.9%) 0.007 ms/op
Iteration   1: 3.558 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.865 ms/op
                 existUser·p0.50:   3.518 ms/op
                 existUser·p0.90:   4.243 ms/op
                 existUser·p0.95:   4.547 ms/op
                 existUser·p0.99:   5.719 ms/op
                 existUser·p0.999:  9.519 ms/op
                 existUser·p0.9999: 22.512 ms/op
                 existUser·p1.00:   22.774 ms/op

Iteration   2: 3.481 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.965 ms/op
                 existUser·p0.50:   3.469 ms/op
                 existUser·p0.90:   3.973 ms/op
                 existUser·p0.95:   4.235 ms/op
                 existUser·p0.99:   5.374 ms/op
                 existUser·p0.999:  12.815 ms/op
                 existUser·p0.9999: 15.152 ms/op
                 existUser·p1.00:   17.269 ms/op

Iteration   3: 3.558 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.813 ms/op
                 existUser·p0.50:   3.506 ms/op
                 existUser·p0.90:   4.153 ms/op
                 existUser·p0.95:   4.440 ms/op
                 existUser·p0.99:   5.300 ms/op
                 existUser·p0.999:  11.796 ms/op
                 existUser·p0.9999: 21.103 ms/op
                 existUser·p1.00:   21.496 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 271621
  mean =      3.532 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9619 
    [ 2.500,  5.000) = 257563 
    [ 5.000,  7.500) = 3680 
    [ 7.500, 10.000) = 397 
    [10.000, 12.500) = 113 
    [12.500, 15.000) = 130 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 52 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.813 ms/op
     p(50.0000) =      3.494 ms/op
     p(90.0000) =      4.125 ms/op
     p(95.0000) =      4.432 ms/op
     p(99.0000) =      5.505 ms/op
     p(99.9000) =     12.114 ms/op
     p(99.9900) =     21.982 ms/op
     p(99.9990) =     22.741 ms/op
     p(99.9999) =     22.774 ms/op
    p(100.0000) =     22.774 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.434 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 3.981 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.863 ±(99.9%) 0.011 ms/op
Iteration   1: 3.695 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.812 ms/op
                 getUser·p0.50:   3.662 ms/op
                 getUser·p0.90:   4.456 ms/op
                 getUser·p0.95:   4.801 ms/op
                 getUser·p0.99:   6.054 ms/op
                 getUser·p0.999:  9.288 ms/op
                 getUser·p0.9999: 23.747 ms/op
                 getUser·p1.00:   24.216 ms/op

Iteration   2: 3.682 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.936 ms/op
                 getUser·p0.50:   3.641 ms/op
                 getUser·p0.90:   4.325 ms/op
                 getUser·p0.95:   4.620 ms/op
                 getUser·p0.99:   5.833 ms/op
                 getUser·p0.999:  12.240 ms/op
                 getUser·p0.9999: 25.264 ms/op
                 getUser·p1.00:   25.657 ms/op

Iteration   3: 3.708 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.885 ms/op
                 getUser·p0.50:   3.666 ms/op
                 getUser·p0.90:   4.399 ms/op
                 getUser·p0.95:   4.727 ms/op
                 getUser·p0.99:   5.792 ms/op
                 getUser·p0.999:  11.674 ms/op
                 getUser·p0.9999: 28.795 ms/op
                 getUser·p1.00:   29.295 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 259716
  mean =      3.695 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11207 
    [ 2.500,  5.000) = 241204 
    [ 5.000,  7.500) = 6512 
    [ 7.500, 10.000) = 435 
    [10.000, 12.500) = 208 
    [12.500, 15.000) = 22 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 62 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.812 ms/op
     p(50.0000) =      3.654 ms/op
     p(90.0000) =      4.391 ms/op
     p(95.0000) =      4.719 ms/op
     p(99.0000) =      5.882 ms/op
     p(99.9000) =     11.583 ms/op
     p(99.9900) =     28.117 ms/op
     p(99.9990) =     29.190 ms/op
     p(99.9999) =     29.295 ms/op
    p(100.0000) =     29.295 ms/op


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
# Warmup Iteration   1: 6.764 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 5.196 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 5.071 ±(99.9%) 0.018 ms/op
Iteration   1: 4.862 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.880 ms/op
                 listUser·p0.50:   4.653 ms/op
                 listUser·p0.90:   6.152 ms/op
                 listUser·p0.95:   7.094 ms/op
                 listUser·p0.99:   9.142 ms/op
                 listUser·p0.999:  15.995 ms/op
                 listUser·p0.9999: 19.118 ms/op
                 listUser·p1.00:   19.726 ms/op

Iteration   2: 4.782 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.581 ms/op
                 listUser·p0.50:   4.579 ms/op
                 listUser·p0.90:   6.087 ms/op
                 listUser·p0.95:   6.832 ms/op
                 listUser·p0.99:   8.569 ms/op
                 listUser·p0.999:  18.488 ms/op
                 listUser·p0.9999: 23.144 ms/op
                 listUser·p1.00:   23.626 ms/op

Iteration   3: 4.833 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.266 ms/op
                 listUser·p0.50:   4.637 ms/op
                 listUser·p0.90:   5.931 ms/op
                 listUser·p0.95:   6.865 ms/op
                 listUser·p0.99:   8.389 ms/op
                 listUser·p0.999:  20.546 ms/op
                 listUser·p0.9999: 23.880 ms/op
                 listUser·p1.00:   24.150 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 198911
  mean =      4.825 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 382 
    [ 2.500,  5.000) = 142995 
    [ 5.000,  7.500) = 49529 
    [ 7.500, 10.000) = 5021 
    [10.000, 12.500) = 533 
    [12.500, 15.000) = 151 
    [15.000, 17.500) = 115 
    [17.500, 20.000) = 83 
    [20.000, 22.500) = 74 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.266 ms/op
     p(50.0000) =      4.620 ms/op
     p(90.0000) =      6.062 ms/op
     p(95.0000) =      6.922 ms/op
     p(99.0000) =      8.716 ms/op
     p(99.9000) =     17.141 ms/op
     p(99.9900) =     23.047 ms/op
     p(99.9990) =     23.956 ms/op
     p(99.9999) =     24.150 ms/op
    p(100.0000) =     24.150 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.636 ± 1.482  ops/ms
ClientGrpc.existUser                       thrpt       3   9.047 ± 2.298  ops/ms
ClientGrpc.getUser                         thrpt       3   8.574 ± 1.911  ops/ms
ClientGrpc.listUser                        thrpt       3   6.749 ± 2.335  ops/ms
ClientGrpc.createUser                       avgt       3   3.752 ± 0.358   ms/op
ClientGrpc.existUser                        avgt       3   3.584 ± 0.651   ms/op
ClientGrpc.getUser                          avgt       3   3.749 ± 0.622   ms/op
ClientGrpc.listUser                         avgt       3   4.742 ± 1.422   ms/op
ClientGrpc.createUser                     sample  257662   3.725 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.346           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.662           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.424           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.686           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.603           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.770           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.453           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.756           ms/op
ClientGrpc.existUser                      sample  271621   3.532 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.813           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.494           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.125           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.432           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.505           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.114           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.982           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.774           ms/op
ClientGrpc.getUser                        sample  259716   3.695 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.812           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.654           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.391           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.719           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.882           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.583           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          28.117           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          29.295           ms/op
ClientGrpc.listUser                       sample  198911   4.825 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.266           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.620           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.062           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.922           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.716           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.141           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.047           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.150           ms/op
