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
# Warmup Iteration   1: 5.016 ops/ms
# Warmup Iteration   2: 9.754 ops/ms
# Warmup Iteration   3: 10.569 ops/ms
Iteration   1: 10.543 ops/ms
Iteration   2: 10.443 ops/ms
Iteration   3: 10.553 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.513 ±(99.9%) 1.116 ops/ms [Average]
  (min, avg, max) = (10.443, 10.513, 10.553), stdev = 0.061
  CI (99.9%): [9.397, 11.629] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 8.003 ops/ms
# Warmup Iteration   2: 10.687 ops/ms
# Warmup Iteration   3: 10.850 ops/ms
Iteration   1: 11.001 ops/ms
Iteration   2: 11.081 ops/ms
Iteration   3: 10.951 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.011 ±(99.9%) 1.197 ops/ms [Average]
  (min, avg, max) = (10.951, 11.011, 11.081), stdev = 0.066
  CI (99.9%): [9.814, 12.208] (assumes normal distribution)


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
# Warmup Iteration   1: 6.977 ops/ms
# Warmup Iteration   2: 10.272 ops/ms
# Warmup Iteration   3: 10.519 ops/ms
Iteration   1: 10.916 ops/ms
Iteration   2: 10.922 ops/ms
Iteration   3: 10.584 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.808 ±(99.9%) 3.528 ops/ms [Average]
  (min, avg, max) = (10.584, 10.808, 10.922), stdev = 0.193
  CI (99.9%): [7.279, 14.336] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.294 ops/ms
# Warmup Iteration   2: 8.069 ops/ms
# Warmup Iteration   3: 8.264 ops/ms
Iteration   1: 7.824 ops/ms
Iteration   2: 7.938 ops/ms
Iteration   3: 8.240 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.001 ±(99.9%) 3.925 ops/ms [Average]
  (min, avg, max) = (7.824, 8.001, 8.240), stdev = 0.215
  CI (99.9%): [4.076, 11.926] (assumes normal distribution)


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
# Warmup Iteration   1: 3.954 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.135 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.094 ±(99.9%) 0.007 ms/op
Iteration   1: 3.002 ±(99.9%) 0.003 ms/op
Iteration   2: 3.037 ±(99.9%) 0.002 ms/op
Iteration   3: 3.098 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.046 ±(99.9%) 0.888 ms/op [Average]
  (min, avg, max) = (3.002, 3.046, 3.098), stdev = 0.049
  CI (99.9%): [2.157, 3.934] (assumes normal distribution)


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
# Warmup Iteration   1: 3.645 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.076 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.929 ±(99.9%) 0.002 ms/op
Iteration   1: 2.992 ±(99.9%) 0.002 ms/op
Iteration   2: 2.812 ±(99.9%) 0.004 ms/op
Iteration   3: 2.845 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.883 ±(99.9%) 1.746 ms/op [Average]
  (min, avg, max) = (2.812, 2.883, 2.992), stdev = 0.096
  CI (99.9%): [1.137, 4.628] (assumes normal distribution)


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
# Warmup Iteration   1: 3.750 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.110 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.996 ±(99.9%) 0.003 ms/op
Iteration   1: 3.006 ±(99.9%) 0.002 ms/op
Iteration   2: 3.015 ±(99.9%) 0.003 ms/op
Iteration   3: 2.962 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.994 ±(99.9%) 0.513 ms/op [Average]
  (min, avg, max) = (2.962, 2.994, 3.015), stdev = 0.028
  CI (99.9%): [2.481, 3.507] (assumes normal distribution)


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
# Warmup Iteration   1: 4.764 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 4.038 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.976 ±(99.9%) 0.009 ms/op
Iteration   1: 3.810 ±(99.9%) 0.013 ms/op
Iteration   2: 3.787 ±(99.9%) 0.014 ms/op
Iteration   3: 3.955 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.850 ±(99.9%) 1.661 ms/op [Average]
  (min, avg, max) = (3.787, 3.850, 3.955), stdev = 0.091
  CI (99.9%): [2.190, 5.511] (assumes normal distribution)


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
# Warmup Iteration   1: 3.941 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.192 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.992 ±(99.9%) 0.006 ms/op
Iteration   1: 3.034 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.712 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.682 ms/op
                 createUser·p0.95:   3.883 ms/op
                 createUser·p0.99:   4.284 ms/op
                 createUser·p0.999:  8.874 ms/op
                 createUser·p0.9999: 22.396 ms/op
                 createUser·p1.00:   22.839 ms/op

Iteration   2: 3.054 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.502 ms/op
                 createUser·p0.50:   3.027 ms/op
                 createUser·p0.90:   3.633 ms/op
                 createUser·p0.95:   3.813 ms/op
                 createUser·p0.99:   4.194 ms/op
                 createUser·p0.999:  6.447 ms/op
                 createUser·p0.9999: 16.744 ms/op
                 createUser·p1.00:   17.203 ms/op

Iteration   3: 3.097 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.422 ms/op
                 createUser·p0.50:   3.068 ms/op
                 createUser·p0.90:   3.781 ms/op
                 createUser·p0.95:   3.977 ms/op
                 createUser·p0.99:   4.260 ms/op
                 createUser·p0.999:  8.298 ms/op
                 createUser·p0.9999: 17.488 ms/op
                 createUser·p1.00:   18.612 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 313394
  mean =      3.061 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29664 
    [ 2.500,  5.000) = 282903 
    [ 5.000,  7.500) = 470 
    [ 7.500, 10.000) = 164 
    [10.000, 12.500) = 4 
    [12.500, 15.000) = 52 
    [15.000, 17.500) = 95 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.422 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      3.699 ms/op
     p(95.0000) =      3.895 ms/op
     p(99.0000) =      4.252 ms/op
     p(99.9000) =      8.156 ms/op
     p(99.9900) =     21.812 ms/op
     p(99.9990) =     22.732 ms/op
     p(99.9999) =     22.839 ms/op
    p(100.0000) =     22.839 ms/op


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
# Warmup Iteration   1: 3.752 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.002 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.809 ±(99.9%) 0.007 ms/op
Iteration   1: 2.959 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.647 ms/op
                 existUser·p0.50:   2.966 ms/op
                 existUser·p0.90:   3.600 ms/op
                 existUser·p0.95:   3.781 ms/op
                 existUser·p0.99:   4.096 ms/op
                 existUser·p0.999:  6.051 ms/op
                 existUser·p0.9999: 16.292 ms/op
                 existUser·p1.00:   16.761 ms/op

Iteration   2: 2.906 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.681 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.535 ms/op
                 existUser·p0.95:   3.715 ms/op
                 existUser·p0.99:   4.235 ms/op
                 existUser·p0.999:  7.053 ms/op
                 existUser·p0.9999: 14.254 ms/op
                 existUser·p1.00:   14.598 ms/op

Iteration   3: 2.974 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.558 ms/op
                 existUser·p0.50:   2.945 ms/op
                 existUser·p0.90:   3.596 ms/op
                 existUser·p0.95:   3.764 ms/op
                 existUser·p0.99:   4.227 ms/op
                 existUser·p0.999:  6.344 ms/op
                 existUser·p0.9999: 16.613 ms/op
                 existUser·p1.00:   16.646 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 325784
  mean =      2.946 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2973 
    [ 1.250,  2.500) = 44970 
    [ 2.500,  3.750) = 261078 
    [ 3.750,  5.000) = 16021 
    [ 5.000,  6.250) = 376 
    [ 6.250,  7.500) = 146 
    [ 7.500,  8.750) = 10 
    [ 8.750, 10.000) = 9 
    [10.000, 11.250) = 9 
    [11.250, 12.500) = 33 
    [12.500, 13.750) = 53 
    [13.750, 15.000) = 55 
    [15.000, 16.250) = 23 
    [16.250, 17.500) = 28 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.558 ms/op
     p(50.0000) =      2.941 ms/op
     p(90.0000) =      3.580 ms/op
     p(95.0000) =      3.756 ms/op
     p(99.0000) =      4.166 ms/op
     p(99.9000) =      6.392 ms/op
     p(99.9900) =     16.143 ms/op
     p(99.9990) =     16.646 ms/op
     p(99.9999) =     16.761 ms/op
    p(100.0000) =     16.761 ms/op


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
# Warmup Iteration   1: 3.623 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.059 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.071 ±(99.9%) 0.007 ms/op
Iteration   1: 3.028 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.763 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.568 ms/op
                 getUser·p0.95:   3.740 ms/op
                 getUser·p0.99:   4.140 ms/op
                 getUser·p0.999:  6.966 ms/op
                 getUser·p0.9999: 13.122 ms/op
                 getUser·p1.00:   13.386 ms/op

Iteration   2: 3.096 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.844 ms/op
                 getUser·p0.50:   3.076 ms/op
                 getUser·p0.90:   3.781 ms/op
                 getUser·p0.95:   3.940 ms/op
                 getUser·p0.99:   4.293 ms/op
                 getUser·p0.999:  8.078 ms/op
                 getUser·p0.9999: 21.419 ms/op
                 getUser·p1.00:   21.823 ms/op

Iteration   3: 3.077 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.650 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.752 ms/op
                 getUser·p0.95:   3.944 ms/op
                 getUser·p0.99:   4.301 ms/op
                 getUser·p0.999:  9.912 ms/op
                 getUser·p0.9999: 15.679 ms/op
                 getUser·p1.00:   15.696 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 312844
  mean =      3.067 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28359 
    [ 2.500,  5.000) = 283551 
    [ 5.000,  7.500) = 596 
    [ 7.500, 10.000) = 89 
    [10.000, 12.500) = 75 
    [12.500, 15.000) = 116 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.650 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      3.703 ms/op
     p(95.0000) =      3.895 ms/op
     p(99.0000) =      4.252 ms/op
     p(99.9000) =      8.352 ms/op
     p(99.9900) =     20.906 ms/op
     p(99.9990) =     21.717 ms/op
     p(99.9999) =     21.823 ms/op
    p(100.0000) =     21.823 ms/op


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
# Warmup Iteration   1: 5.178 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.026 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.036 ±(99.9%) 0.011 ms/op
Iteration   1: 3.861 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.087 ms/op
                 listUser·p0.50:   3.715 ms/op
                 listUser·p0.90:   4.809 ms/op
                 listUser·p0.95:   5.521 ms/op
                 listUser·p0.99:   6.447 ms/op
                 listUser·p0.999:  12.258 ms/op
                 listUser·p0.9999: 15.431 ms/op
                 listUser·p1.00:   16.040 ms/op

Iteration   2: 3.838 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.085 ms/op
                 listUser·p0.50:   3.727 ms/op
                 listUser·p0.90:   4.620 ms/op
                 listUser·p0.95:   5.374 ms/op
                 listUser·p0.99:   6.595 ms/op
                 listUser·p0.999:  12.788 ms/op
                 listUser·p0.9999: 18.501 ms/op
                 listUser·p1.00:   19.169 ms/op

Iteration   3: 3.926 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.219 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   5.095 ms/op
                 listUser·p0.95:   5.718 ms/op
                 listUser·p0.99:   6.799 ms/op
                 listUser·p0.999:  14.174 ms/op
                 listUser·p0.9999: 18.214 ms/op
                 listUser·p1.00:   18.711 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 247786
  mean =      3.874 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 10 
    [ 1.250,  2.500) = 4714 
    [ 2.500,  3.750) = 122432 
    [ 3.750,  5.000) = 99136 
    [ 5.000,  6.250) = 17009 
    [ 6.250,  7.500) = 3573 
    [ 7.500,  8.750) = 409 
    [ 8.750, 10.000) = 74 
    [10.000, 11.250) = 38 
    [11.250, 12.500) = 111 
    [12.500, 13.750) = 84 
    [13.750, 15.000) = 64 
    [15.000, 16.250) = 63 
    [16.250, 17.500) = 36 
    [17.500, 18.750) = 28 

  Percentiles, ms/op:
      p(0.0000) =      1.085 ms/op
     p(50.0000) =      3.736 ms/op
     p(90.0000) =      4.858 ms/op
     p(95.0000) =      5.562 ms/op
     p(99.0000) =      6.603 ms/op
     p(99.9000) =     12.832 ms/op
     p(99.9900) =     17.939 ms/op
     p(99.9990) =     19.024 ms/op
     p(99.9999) =     19.169 ms/op
    p(100.0000) =     19.169 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.513 ± 1.116  ops/ms
ClientGrpc.existUser                       thrpt       3  11.011 ± 1.197  ops/ms
ClientGrpc.getUser                         thrpt       3  10.808 ± 3.528  ops/ms
ClientGrpc.listUser                        thrpt       3   8.001 ± 3.925  ops/ms
ClientGrpc.createUser                       avgt       3   3.046 ± 0.888   ms/op
ClientGrpc.existUser                        avgt       3   2.883 ± 1.746   ms/op
ClientGrpc.getUser                          avgt       3   2.994 ± 0.513   ms/op
ClientGrpc.listUser                         avgt       3   3.850 ± 1.661   ms/op
ClientGrpc.createUser                     sample  313394   3.061 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.422           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.039           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.699           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.895           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.252           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.156           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.812           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.839           ms/op
ClientGrpc.existUser                      sample  325784   2.946 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.558           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.941           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.580           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.756           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.166           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.392           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.143           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.761           ms/op
ClientGrpc.getUser                        sample  312844   3.067 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.650           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.039           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.703           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.895           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.252           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.352           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.906           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.823           ms/op
ClientGrpc.listUser                       sample  247786   3.874 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.085           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.736           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.858           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.562           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.603           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          12.832           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          17.939           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          19.169           ms/op
