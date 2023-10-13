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
# Warmup Iteration   1: 1.712 ops/ms
# Warmup Iteration   2: 4.678 ops/ms
# Warmup Iteration   3: 6.551 ops/ms
Iteration   1: 6.659 ops/ms
Iteration   2: 6.634 ops/ms
Iteration   3: 6.847 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  6.713 ±(99.9%) 2.124 ops/ms [Average]
  (min, avg, max) = (6.634, 6.713, 6.847), stdev = 0.116
  CI (99.9%): [4.589, 8.837] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 4.296 ops/ms
# Warmup Iteration   2: 6.765 ops/ms
# Warmup Iteration   3: 6.978 ops/ms
Iteration   1: 7.034 ops/ms
Iteration   2: 7.102 ops/ms
Iteration   3: 7.190 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.109 ±(99.9%) 1.427 ops/ms [Average]
  (min, avg, max) = (7.034, 7.109, 7.190), stdev = 0.078
  CI (99.9%): [5.682, 8.536] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 3.926 ops/ms
# Warmup Iteration   2: 5.961 ops/ms
# Warmup Iteration   3: 6.404 ops/ms
Iteration   1: 6.550 ops/ms
Iteration   2: 6.944 ops/ms
Iteration   3: 6.885 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  6.793 ±(99.9%) 3.873 ops/ms [Average]
  (min, avg, max) = (6.550, 6.793, 6.944), stdev = 0.212
  CI (99.9%): [2.920, 10.666] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.132 ops/ms
# Warmup Iteration   2: 4.571 ops/ms
# Warmup Iteration   3: 5.055 ops/ms
Iteration   1: 5.251 ops/ms
Iteration   2: 5.127 ops/ms
Iteration   3: 5.293 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.223 ±(99.9%) 1.578 ops/ms [Average]
  (min, avg, max) = (5.127, 5.223, 5.293), stdev = 0.086
  CI (99.9%): [3.646, 6.801] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 7.694 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 5.298 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.920 ±(99.9%) 0.014 ms/op
Iteration   1: 4.876 ±(99.9%) 0.006 ms/op
Iteration   2: 4.857 ±(99.9%) 0.003 ms/op
Iteration   3: 4.690 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.808 ±(99.9%) 1.862 ms/op [Average]
  (min, avg, max) = (4.690, 4.808, 4.876), stdev = 0.102
  CI (99.9%): [2.945, 6.670] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.707 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.785 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.439 ±(99.9%) 0.013 ms/op
Iteration   1: 4.487 ±(99.9%) 0.004 ms/op
Iteration   2: 4.362 ±(99.9%) 0.004 ms/op
Iteration   3: 4.350 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.400 ±(99.9%) 1.389 ms/op [Average]
  (min, avg, max) = (4.350, 4.400, 4.487), stdev = 0.076
  CI (99.9%): [3.011, 5.788] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 7.824 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 5.255 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.906 ±(99.9%) 0.004 ms/op
Iteration   1: 4.835 ±(99.9%) 0.003 ms/op
Iteration   2: 4.591 ±(99.9%) 0.005 ms/op
Iteration   3: 4.920 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.782 ±(99.9%) 3.121 ms/op [Average]
  (min, avg, max) = (4.591, 4.782, 4.920), stdev = 0.171
  CI (99.9%): [1.661, 7.903] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 9.231 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 6.539 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 6.027 ±(99.9%) 0.021 ms/op
Iteration   1: 6.070 ±(99.9%) 0.017 ms/op
Iteration   2: 6.291 ±(99.9%) 0.018 ms/op
Iteration   3: 6.269 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.210 ±(99.9%) 2.217 ms/op [Average]
  (min, avg, max) = (6.070, 6.210, 6.291), stdev = 0.122
  CI (99.9%): [3.993, 8.427] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 7.632 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 5.249 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.930 ±(99.9%) 0.016 ms/op
Iteration   1: 4.769 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.000 ms/op
                 createUser·p0.50:   4.686 ms/op
                 createUser·p0.90:   5.906 ms/op
                 createUser·p0.95:   6.357 ms/op
                 createUser·p0.99:   7.864 ms/op
                 createUser·p0.999:  11.665 ms/op
                 createUser·p0.9999: 17.573 ms/op
                 createUser·p1.00:   17.990 ms/op

Iteration   2: 4.719 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.307 ms/op
                 createUser·p0.50:   4.563 ms/op
                 createUser·p0.90:   5.841 ms/op
                 createUser·p0.95:   6.341 ms/op
                 createUser·p0.99:   8.520 ms/op
                 createUser·p0.999:  14.221 ms/op
                 createUser·p0.9999: 20.844 ms/op
                 createUser·p1.00:   21.201 ms/op

Iteration   3: 4.928 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   1.268 ms/op
                 createUser·p0.50:   4.743 ms/op
                 createUser·p0.90:   6.234 ms/op
                 createUser·p0.95:   6.808 ms/op
                 createUser·p0.99:   9.798 ms/op
                 createUser·p0.999:  14.078 ms/op
                 createUser·p0.9999: 28.526 ms/op
                 createUser·p1.00:   29.131 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 199832
  mean =      4.804 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2293 
    [ 2.500,  5.000) = 127659 
    [ 5.000,  7.500) = 65908 
    [ 7.500, 10.000) = 2831 
    [10.000, 12.500) = 850 
    [12.500, 15.000) = 161 
    [15.000, 17.500) = 55 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.000 ms/op
     p(50.0000) =      4.653 ms/op
     p(90.0000) =      6.005 ms/op
     p(95.0000) =      6.513 ms/op
     p(99.0000) =      8.815 ms/op
     p(99.9000) =     13.637 ms/op
     p(99.9900) =     22.120 ms/op
     p(99.9990) =     29.065 ms/op
     p(99.9999) =     29.131 ms/op
    p(100.0000) =     29.131 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 7.034 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 4.868 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.496 ±(99.9%) 0.012 ms/op
Iteration   1: 4.590 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.133 ms/op
                 existUser·p0.50:   4.424 ms/op
                 existUser·p0.90:   5.800 ms/op
                 existUser·p0.95:   6.291 ms/op
                 existUser·p0.99:   7.848 ms/op
                 existUser·p0.999:  11.026 ms/op
                 existUser·p0.9999: 24.281 ms/op
                 existUser·p1.00:   24.314 ms/op

Iteration   2: 4.568 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.053 ms/op
                 existUser·p0.50:   4.415 ms/op
                 existUser·p0.90:   5.702 ms/op
                 existUser·p0.95:   6.213 ms/op
                 existUser·p0.99:   8.569 ms/op
                 existUser·p0.999:  14.385 ms/op
                 existUser·p0.9999: 24.674 ms/op
                 existUser·p1.00:   27.558 ms/op

Iteration   3: 4.446 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.687 ms/op
                 existUser·p0.50:   4.342 ms/op
                 existUser·p0.90:   5.587 ms/op
                 existUser·p0.95:   6.054 ms/op
                 existUser·p0.99:   7.619 ms/op
                 existUser·p0.999:  12.406 ms/op
                 existUser·p0.9999: 26.569 ms/op
                 existUser·p1.00:   28.508 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 211667
  mean =      4.534 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4521 
    [ 2.500,  5.000) = 153353 
    [ 5.000,  7.500) = 50825 
    [ 7.500, 10.000) = 2346 
    [10.000, 12.500) = 406 
    [12.500, 15.000) = 107 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.687 ms/op
     p(50.0000) =      4.391 ms/op
     p(90.0000) =      5.702 ms/op
     p(95.0000) =      6.185 ms/op
     p(99.0000) =      7.987 ms/op
     p(99.9000) =     12.605 ms/op
     p(99.9900) =     25.941 ms/op
     p(99.9990) =     27.523 ms/op
     p(99.9999) =     28.508 ms/op
    p(100.0000) =     28.508 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 7.700 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 5.218 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.894 ±(99.9%) 0.014 ms/op
Iteration   1: 4.814 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.278 ms/op
                 getUser·p0.50:   4.669 ms/op
                 getUser·p0.90:   6.062 ms/op
                 getUser·p0.95:   6.660 ms/op
                 getUser·p0.99:   9.056 ms/op
                 getUser·p0.999:  15.616 ms/op
                 getUser·p0.9999: 19.553 ms/op
                 getUser·p1.00:   19.988 ms/op

Iteration   2: 4.724 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.053 ms/op
                 getUser·p0.50:   4.628 ms/op
                 getUser·p0.90:   5.784 ms/op
                 getUser·p0.95:   6.234 ms/op
                 getUser·p0.99:   8.569 ms/op
                 getUser·p0.999:  13.853 ms/op
                 getUser·p0.9999: 17.899 ms/op
                 getUser·p1.00:   18.088 ms/op

Iteration   3: 4.797 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.249 ms/op
                 getUser·p0.50:   4.653 ms/op
                 getUser·p0.90:   6.136 ms/op
                 getUser·p0.95:   6.619 ms/op
                 getUser·p0.99:   8.114 ms/op
                 getUser·p0.999:  15.178 ms/op
                 getUser·p0.9999: 20.546 ms/op
                 getUser·p1.00:   23.134 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 200802
  mean =      4.778 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3271 
    [ 2.500,  5.000) = 127572 
    [ 5.000,  7.500) = 66275 
    [ 7.500, 10.000) = 2708 
    [10.000, 12.500) = 576 
    [12.500, 15.000) = 213 
    [15.000, 17.500) = 90 
    [17.500, 20.000) = 83 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.053 ms/op
     p(50.0000) =      4.653 ms/op
     p(90.0000) =      5.997 ms/op
     p(95.0000) =      6.521 ms/op
     p(99.0000) =      8.569 ms/op
     p(99.9000) =     14.516 ms/op
     p(99.9900) =     19.756 ms/op
     p(99.9990) =     22.805 ms/op
     p(99.9999) =     23.134 ms/op
    p(100.0000) =     23.134 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 8.870 ±(99.9%) 0.119 ms/op
# Warmup Iteration   2: 6.569 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 6.197 ±(99.9%) 0.023 ms/op
Iteration   1: 5.981 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.548 ms/op
                 listUser·p0.50:   5.759 ms/op
                 listUser·p0.90:   7.750 ms/op
                 listUser·p0.95:   8.946 ms/op
                 listUser·p0.99:   11.272 ms/op
                 listUser·p0.999:  22.641 ms/op
                 listUser·p0.9999: 29.185 ms/op
                 listUser·p1.00:   29.917 ms/op

Iteration   2: 6.057 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.696 ms/op
                 listUser·p0.50:   5.743 ms/op
                 listUser·p0.90:   7.930 ms/op
                 listUser·p0.95:   9.028 ms/op
                 listUser·p0.99:   11.354 ms/op
                 listUser·p0.999:  23.167 ms/op
                 listUser·p0.9999: 31.228 ms/op
                 listUser·p1.00:   31.425 ms/op

Iteration   3: 6.153 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.626 ms/op
                 listUser·p0.50:   5.865 ms/op
                 listUser·p0.90:   7.987 ms/op
                 listUser·p0.95:   9.208 ms/op
                 listUser·p0.99:   11.518 ms/op
                 listUser·p0.999:  24.742 ms/op
                 listUser·p0.9999: 28.850 ms/op
                 listUser·p1.00:   33.620 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 158239
  mean =      6.063 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 67 
    [ 2.500,  5.000) = 32585 
    [ 5.000,  7.500) = 105907 
    [ 7.500, 10.000) = 15514 
    [10.000, 12.500) = 3306 
    [12.500, 15.000) = 472 
    [15.000, 17.500) = 104 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 65 
    [22.500, 25.000) = 84 
    [25.000, 27.500) = 67 
    [27.500, 30.000) = 23 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.548 ms/op
     p(50.0000) =      5.792 ms/op
     p(90.0000) =      7.889 ms/op
     p(95.0000) =      9.077 ms/op
     p(99.0000) =     11.387 ms/op
     p(99.9000) =     23.429 ms/op
     p(99.9900) =     29.399 ms/op
     p(99.9990) =     32.341 ms/op
     p(99.9999) =     33.620 ms/op
    p(100.0000) =     33.620 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   6.713 ± 2.124  ops/ms
ClientGrpc.existUser                       thrpt       3   7.109 ± 1.427  ops/ms
ClientGrpc.getUser                         thrpt       3   6.793 ± 3.873  ops/ms
ClientGrpc.listUser                        thrpt       3   5.223 ± 1.578  ops/ms
ClientGrpc.createUser                       avgt       3   4.808 ± 1.862   ms/op
ClientGrpc.existUser                        avgt       3   4.400 ± 1.389   ms/op
ClientGrpc.getUser                          avgt       3   4.782 ± 3.121   ms/op
ClientGrpc.listUser                         avgt       3   6.210 ± 2.217   ms/op
ClientGrpc.createUser                     sample  199832   4.804 ± 0.009   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.000           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.653           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           6.005           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.513           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           8.815           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.637           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.120           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          29.131           ms/op
ClientGrpc.existUser                      sample  211667   4.534 ± 0.008   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.687           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.391           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.702           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           6.185           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.987           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.605           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          25.941           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          28.508           ms/op
ClientGrpc.getUser                        sample  200802   4.778 ± 0.009   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.053           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.653           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.997           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.521           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           8.569           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          14.516           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.756           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.134           ms/op
ClientGrpc.listUser                       sample  158239   6.063 ± 0.014   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.548           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.792           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.889           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           9.077           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          11.387           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          23.429           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          29.399           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          33.620           ms/op
