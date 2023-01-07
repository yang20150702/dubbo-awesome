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
# Warmup Iteration   1: 2.211 ops/ms
# Warmup Iteration   2: 5.078 ops/ms
# Warmup Iteration   3: 6.419 ops/ms
Iteration   1: 6.740 ops/ms
Iteration   2: 6.920 ops/ms
Iteration   3: 6.644 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  6.768 ±(99.9%) 2.556 ops/ms [Average]
  (min, avg, max) = (6.644, 6.768, 6.920), stdev = 0.140
  CI (99.9%): [4.213, 9.324] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.604 ops/ms
# Warmup Iteration   2: 6.885 ops/ms
# Warmup Iteration   3: 7.082 ops/ms
Iteration   1: 7.029 ops/ms
Iteration   2: 7.142 ops/ms
Iteration   3: 7.233 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.135 ±(99.9%) 1.866 ops/ms [Average]
  (min, avg, max) = (7.029, 7.135, 7.233), stdev = 0.102
  CI (99.9%): [5.269, 9.001] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 3.970 ops/ms
# Warmup Iteration   2: 6.098 ops/ms
# Warmup Iteration   3: 6.347 ops/ms
Iteration   1: 6.845 ops/ms
Iteration   2: 6.568 ops/ms
Iteration   3: 6.638 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  6.684 ±(99.9%) 2.628 ops/ms [Average]
  (min, avg, max) = (6.568, 6.684, 6.845), stdev = 0.144
  CI (99.9%): [4.056, 9.312] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.270 ops/ms
# Warmup Iteration   2: 4.939 ops/ms
# Warmup Iteration   3: 5.007 ops/ms
Iteration   1: 5.198 ops/ms
Iteration   2: 5.181 ops/ms
Iteration   3: 5.161 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.180 ±(99.9%) 0.340 ops/ms [Average]
  (min, avg, max) = (5.161, 5.180, 5.198), stdev = 0.019
  CI (99.9%): [4.840, 5.520] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 7.860 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 5.114 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.851 ±(99.9%) 0.007 ms/op
Iteration   1: 4.798 ±(99.9%) 0.004 ms/op
Iteration   2: 4.712 ±(99.9%) 0.003 ms/op
Iteration   3: 4.921 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.810 ±(99.9%) 1.916 ms/op [Average]
  (min, avg, max) = (4.712, 4.810, 4.921), stdev = 0.105
  CI (99.9%): [2.895, 6.726] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.611 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.666 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.579 ±(99.9%) 0.006 ms/op
Iteration   1: 4.508 ±(99.9%) 0.005 ms/op
Iteration   2: 4.366 ±(99.9%) 0.004 ms/op
Iteration   3: 4.359 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.411 ±(99.9%) 1.537 ms/op [Average]
  (min, avg, max) = (4.359, 4.411, 4.508), stdev = 0.084
  CI (99.9%): [2.874, 5.949] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 7.035 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 5.274 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 5.033 ±(99.9%) 0.005 ms/op
Iteration   1: 4.792 ±(99.9%) 0.004 ms/op
Iteration   2: 4.795 ±(99.9%) 0.005 ms/op
Iteration   3: 4.692 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.759 ±(99.9%) 1.068 ms/op [Average]
  (min, avg, max) = (4.692, 4.759, 4.795), stdev = 0.059
  CI (99.9%): [3.691, 5.828] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 8.272 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 6.836 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 6.208 ±(99.9%) 0.028 ms/op
Iteration   1: 6.100 ±(99.9%) 0.046 ms/op
Iteration   2: 5.969 ±(99.9%) 0.026 ms/op
Iteration   3: 5.987 ±(99.9%) 0.028 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.019 ±(99.9%) 1.290 ms/op [Average]
  (min, avg, max) = (5.969, 6.019, 6.100), stdev = 0.071
  CI (99.9%): [4.728, 7.309] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 7.649 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 5.057 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.851 ±(99.9%) 0.017 ms/op
Iteration   1: 4.656 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.012 ms/op
                 createUser·p0.50:   4.456 ms/op
                 createUser·p0.90:   6.005 ms/op
                 createUser·p0.95:   6.652 ms/op
                 createUser·p0.99:   8.978 ms/op
                 createUser·p0.999:  13.010 ms/op
                 createUser·p0.9999: 23.803 ms/op
                 createUser·p1.00:   24.609 ms/op

Iteration   2: 4.578 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   0.895 ms/op
                 createUser·p0.50:   4.424 ms/op
                 createUser·p0.90:   5.931 ms/op
                 createUser·p0.95:   6.570 ms/op
                 createUser·p0.99:   9.126 ms/op
                 createUser·p0.999:  12.326 ms/op
                 createUser·p0.9999: 22.971 ms/op
                 createUser·p1.00:   23.527 ms/op

Iteration   3: 4.511 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.061 ms/op
                 createUser·p0.50:   4.325 ms/op
                 createUser·p0.90:   5.800 ms/op
                 createUser·p0.95:   6.463 ms/op
                 createUser·p0.99:   8.595 ms/op
                 createUser·p0.999:  12.157 ms/op
                 createUser·p0.9999: 26.768 ms/op
                 createUser·p1.00:   28.246 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 209431
  mean =      4.581 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3512 
    [ 2.500,  5.000) = 148276 
    [ 5.000,  7.500) = 52867 
    [ 7.500, 10.000) = 3513 
    [10.000, 12.500) = 1046 
    [12.500, 15.000) = 87 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.895 ms/op
     p(50.0000) =      4.399 ms/op
     p(90.0000) =      5.915 ms/op
     p(95.0000) =      6.570 ms/op
     p(99.0000) =      8.946 ms/op
     p(99.9000) =     12.576 ms/op
     p(99.9900) =     25.790 ms/op
     p(99.9990) =     27.984 ms/op
     p(99.9999) =     28.246 ms/op
    p(100.0000) =     28.246 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.856 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 4.796 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.705 ±(99.9%) 0.017 ms/op
Iteration   1: 4.652 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.948 ms/op
                 existUser·p0.50:   4.465 ms/op
                 existUser·p0.90:   6.029 ms/op
                 existUser·p0.95:   6.799 ms/op
                 existUser·p0.99:   9.224 ms/op
                 existUser·p0.999:  13.804 ms/op
                 existUser·p0.9999: 17.367 ms/op
                 existUser·p1.00:   17.662 ms/op

Iteration   2: 4.534 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   1.114 ms/op
                 existUser·p0.50:   4.375 ms/op
                 existUser·p0.90:   5.890 ms/op
                 existUser·p0.95:   6.554 ms/op
                 existUser·p0.99:   9.171 ms/op
                 existUser·p0.999:  14.926 ms/op
                 existUser·p0.9999: 18.676 ms/op
                 existUser·p1.00:   19.366 ms/op

Iteration   3: 4.526 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   1.065 ms/op
                 existUser·p0.50:   4.350 ms/op
                 existUser·p0.90:   5.825 ms/op
                 existUser·p0.95:   6.554 ms/op
                 existUser·p0.99:   9.654 ms/op
                 existUser·p0.999:  16.668 ms/op
                 existUser·p0.9999: 26.612 ms/op
                 existUser·p1.00:   27.689 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 209937
  mean =      4.570 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6047 
    [ 2.500,  5.000) = 143767 
    [ 5.000,  7.500) = 54202 
    [ 7.500, 10.000) = 4495 
    [10.000, 12.500) = 933 
    [12.500, 15.000) = 275 
    [15.000, 17.500) = 153 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.948 ms/op
     p(50.0000) =      4.399 ms/op
     p(90.0000) =      5.915 ms/op
     p(95.0000) =      6.652 ms/op
     p(99.0000) =      9.306 ms/op
     p(99.9000) =     15.124 ms/op
     p(99.9900) =     23.233 ms/op
     p(99.9990) =     27.611 ms/op
     p(99.9999) =     27.689 ms/op
    p(100.0000) =     27.689 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 7.042 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 4.905 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.831 ±(99.9%) 0.015 ms/op
Iteration   1: 4.668 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.223 ms/op
                 getUser·p0.50:   4.497 ms/op
                 getUser·p0.90:   5.991 ms/op
                 getUser·p0.95:   6.595 ms/op
                 getUser·p0.99:   9.079 ms/op
                 getUser·p0.999:  13.795 ms/op
                 getUser·p0.9999: 17.961 ms/op
                 getUser·p1.00:   18.481 ms/op

Iteration   2: 4.780 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.753 ms/op
                 getUser·p0.50:   4.612 ms/op
                 getUser·p0.90:   6.160 ms/op
                 getUser·p0.95:   6.808 ms/op
                 getUser·p0.99:   8.933 ms/op
                 getUser·p0.999:  17.203 ms/op
                 getUser·p0.9999: 26.224 ms/op
                 getUser·p1.00:   26.575 ms/op

Iteration   3: 4.769 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   1.235 ms/op
                 getUser·p0.50:   4.620 ms/op
                 getUser·p0.90:   6.128 ms/op
                 getUser·p0.95:   6.808 ms/op
                 getUser·p0.99:   9.223 ms/op
                 getUser·p0.999:  14.855 ms/op
                 getUser·p0.9999: 24.670 ms/op
                 getUser·p1.00:   25.723 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 202670
  mean =      4.739 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3760 
    [ 2.500,  5.000) = 129189 
    [ 5.000,  7.500) = 64064 
    [ 7.500, 10.000) = 4497 
    [10.000, 12.500) = 719 
    [12.500, 15.000) = 201 
    [15.000, 17.500) = 144 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.753 ms/op
     p(50.0000) =      4.571 ms/op
     p(90.0000) =      6.095 ms/op
     p(95.0000) =      6.742 ms/op
     p(99.0000) =      9.093 ms/op
     p(99.9000) =     15.450 ms/op
     p(99.9900) =     24.567 ms/op
     p(99.9990) =     26.508 ms/op
     p(99.9999) =     26.575 ms/op
    p(100.0000) =     26.575 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 9.274 ±(99.9%) 0.130 ms/op
# Warmup Iteration   2: 6.271 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 5.968 ±(99.9%) 0.024 ms/op
Iteration   1: 5.820 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.524 ms/op
                 listUser·p0.50:   5.472 ms/op
                 listUser·p0.90:   7.840 ms/op
                 listUser·p0.95:   8.880 ms/op
                 listUser·p0.99:   11.387 ms/op
                 listUser·p0.999:  15.746 ms/op
                 listUser·p0.9999: 19.661 ms/op
                 listUser·p1.00:   21.135 ms/op

Iteration   2: 6.132 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   1.247 ms/op
                 listUser·p0.50:   5.693 ms/op
                 listUser·p0.90:   8.552 ms/op
                 listUser·p0.95:   9.667 ms/op
                 listUser·p0.99:   12.599 ms/op
                 listUser·p0.999:  21.654 ms/op
                 listUser·p0.9999: 25.870 ms/op
                 listUser·p1.00:   28.541 ms/op

Iteration   3: 6.097 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   1.608 ms/op
                 listUser·p0.50:   5.693 ms/op
                 listUser·p0.90:   8.274 ms/op
                 listUser·p0.95:   9.339 ms/op
                 listUser·p0.99:   12.250 ms/op
                 listUser·p0.999:  20.921 ms/op
                 listUser·p0.9999: 27.131 ms/op
                 listUser·p1.00:   30.015 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 159674
  mean =      6.013 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 155 
    [ 2.500,  5.000) = 45606 
    [ 5.000,  7.500) = 88746 
    [ 7.500, 10.000) = 20027 
    [10.000, 12.500) = 3849 
    [12.500, 15.000) = 857 
    [15.000, 17.500) = 217 
    [17.500, 20.000) = 85 
    [20.000, 22.500) = 50 
    [22.500, 25.000) = 50 
    [25.000, 27.500) = 26 
    [27.500, 30.000) = 5 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.247 ms/op
     p(50.0000) =      5.612 ms/op
     p(90.0000) =      8.241 ms/op
     p(95.0000) =      9.322 ms/op
     p(99.0000) =     12.108 ms/op
     p(99.9000) =     19.158 ms/op
     p(99.9900) =     25.986 ms/op
     p(99.9990) =     29.859 ms/op
     p(99.9999) =     30.015 ms/op
    p(100.0000) =     30.015 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   6.768 ± 2.556  ops/ms
ClientGrpc.existUser                       thrpt       3   7.135 ± 1.866  ops/ms
ClientGrpc.getUser                         thrpt       3   6.684 ± 2.628  ops/ms
ClientGrpc.listUser                        thrpt       3   5.180 ± 0.340  ops/ms
ClientGrpc.createUser                       avgt       3   4.810 ± 1.916   ms/op
ClientGrpc.existUser                        avgt       3   4.411 ± 1.537   ms/op
ClientGrpc.getUser                          avgt       3   4.759 ± 1.068   ms/op
ClientGrpc.listUser                         avgt       3   6.019 ± 1.290   ms/op
ClientGrpc.createUser                     sample  209431   4.581 ± 0.009   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.895           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.399           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.915           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.570           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           8.946           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.576           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          25.790           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          28.246           ms/op
ClientGrpc.existUser                      sample  209937   4.570 ± 0.010   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.948           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.399           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.915           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           6.652           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           9.306           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          15.124           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          23.233           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          27.689           ms/op
ClientGrpc.getUser                        sample  202670   4.739 ± 0.010   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.753           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.571           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           6.095           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.742           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           9.093           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          15.450           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          24.567           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          26.575           ms/op
ClientGrpc.listUser                       sample  159674   6.013 ± 0.015   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.247           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.612           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           8.241           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           9.322           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          12.108           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.158           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.986           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          30.015           ms/op
