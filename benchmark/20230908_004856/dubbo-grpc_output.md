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
# Warmup Iteration   1: 3.440 ops/ms
# Warmup Iteration   2: 7.288 ops/ms
# Warmup Iteration   3: 8.409 ops/ms
Iteration   1: 8.730 ops/ms
Iteration   2: 8.937 ops/ms
Iteration   3: 8.917 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.861 ±(99.9%) 2.079 ops/ms [Average]
  (min, avg, max) = (8.730, 8.861, 8.937), stdev = 0.114
  CI (99.9%): [6.782, 10.941] (assumes normal distribution)


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
# Warmup Iteration   1: 6.361 ops/ms
# Warmup Iteration   2: 9.058 ops/ms
# Warmup Iteration   3: 9.428 ops/ms
Iteration   1: 9.373 ops/ms
Iteration   2: 9.463 ops/ms
Iteration   3: 9.445 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.427 ±(99.9%) 0.874 ops/ms [Average]
  (min, avg, max) = (9.373, 9.427, 9.463), stdev = 0.048
  CI (99.9%): [8.553, 10.301] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.682 ops/ms
# Warmup Iteration   2: 8.543 ops/ms
# Warmup Iteration   3: 8.772 ops/ms
Iteration   1: 8.958 ops/ms
Iteration   2: 9.009 ops/ms
Iteration   3: 8.931 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.966 ±(99.9%) 0.720 ops/ms [Average]
  (min, avg, max) = (8.931, 8.966, 9.009), stdev = 0.039
  CI (99.9%): [8.246, 9.685] (assumes normal distribution)


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
# Warmup Iteration   1: 4.419 ops/ms
# Warmup Iteration   2: 6.398 ops/ms
# Warmup Iteration   3: 6.785 ops/ms
Iteration   1: 6.762 ops/ms
Iteration   2: 6.835 ops/ms
Iteration   3: 6.838 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.812 ±(99.9%) 0.783 ops/ms [Average]
  (min, avg, max) = (6.762, 6.812, 6.838), stdev = 0.043
  CI (99.9%): [6.029, 7.595] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 5.348 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.832 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.753 ±(99.9%) 0.014 ms/op
Iteration   1: 3.689 ±(99.9%) 0.004 ms/op
Iteration   2: 3.647 ±(99.9%) 0.004 ms/op
Iteration   3: 3.600 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.645 ±(99.9%) 0.809 ms/op [Average]
  (min, avg, max) = (3.600, 3.645, 3.689), stdev = 0.044
  CI (99.9%): [2.836, 4.454] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.941 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.726 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.500 ±(99.9%) 0.004 ms/op
Iteration   1: 3.560 ±(99.9%) 0.003 ms/op
Iteration   2: 3.476 ±(99.9%) 0.004 ms/op
Iteration   3: 3.456 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.497 ±(99.9%) 1.010 ms/op [Average]
  (min, avg, max) = (3.456, 3.497, 3.560), stdev = 0.055
  CI (99.9%): [2.488, 4.507] (assumes normal distribution)


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
# Warmup Iteration   1: 5.187 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.785 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.762 ±(99.9%) 0.004 ms/op
Iteration   1: 3.697 ±(99.9%) 0.004 ms/op
Iteration   2: 3.597 ±(99.9%) 0.005 ms/op
Iteration   3: 3.572 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.622 ±(99.9%) 1.209 ms/op [Average]
  (min, avg, max) = (3.572, 3.622, 3.697), stdev = 0.066
  CI (99.9%): [2.414, 4.831] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 7.231 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.753 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.685 ±(99.9%) 0.016 ms/op
Iteration   1: 4.609 ±(99.9%) 0.020 ms/op
Iteration   2: 4.744 ±(99.9%) 0.022 ms/op
Iteration   3: 4.592 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.648 ±(99.9%) 1.522 ms/op [Average]
  (min, avg, max) = (4.592, 4.648, 4.744), stdev = 0.083
  CI (99.9%): [3.126, 6.170] (assumes normal distribution)


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
# Warmup Iteration   1: 5.329 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.820 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.722 ±(99.9%) 0.010 ms/op
Iteration   1: 3.680 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.204 ms/op
                 createUser·p0.50:   3.600 ms/op
                 createUser·p0.90:   4.432 ms/op
                 createUser·p0.95:   4.801 ms/op
                 createUser·p0.99:   6.128 ms/op
                 createUser·p0.999:  12.781 ms/op
                 createUser·p0.9999: 14.843 ms/op
                 createUser·p1.00:   15.106 ms/op

Iteration   2: 3.550 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.847 ms/op
                 createUser·p0.50:   3.518 ms/op
                 createUser·p0.90:   4.006 ms/op
                 createUser·p0.95:   4.358 ms/op
                 createUser·p0.99:   5.858 ms/op
                 createUser·p0.999:  10.337 ms/op
                 createUser·p0.9999: 28.639 ms/op
                 createUser·p1.00:   29.032 ms/op

Iteration   3: 3.575 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.842 ms/op
                 createUser·p0.50:   3.531 ms/op
                 createUser·p0.90:   4.133 ms/op
                 createUser·p0.95:   4.440 ms/op
                 createUser·p0.99:   5.767 ms/op
                 createUser·p0.999:  8.579 ms/op
                 createUser·p0.9999: 20.221 ms/op
                 createUser·p1.00:   20.808 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 266435
  mean =      3.601 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7826 
    [ 2.500,  5.000) = 251541 
    [ 5.000,  7.500) = 6127 
    [ 7.500, 10.000) = 601 
    [10.000, 12.500) = 151 
    [12.500, 15.000) = 91 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.842 ms/op
     p(50.0000) =      3.543 ms/op
     p(90.0000) =      4.202 ms/op
     p(95.0000) =      4.579 ms/op
     p(99.0000) =      5.923 ms/op
     p(99.9000) =     10.479 ms/op
     p(99.9900) =     26.958 ms/op
     p(99.9990) =     28.945 ms/op
     p(99.9999) =     29.032 ms/op
    p(100.0000) =     29.032 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.923 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.688 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.392 ±(99.9%) 0.008 ms/op
Iteration   1: 3.457 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.901 ms/op
                 existUser·p0.50:   3.424 ms/op
                 existUser·p0.90:   3.858 ms/op
                 existUser·p0.95:   4.055 ms/op
                 existUser·p0.99:   5.530 ms/op
                 existUser·p0.999:  9.011 ms/op
                 existUser·p0.9999: 14.741 ms/op
                 existUser·p1.00:   14.909 ms/op

Iteration   2: 3.406 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.730 ms/op
                 existUser·p0.50:   3.383 ms/op
                 existUser·p0.90:   3.875 ms/op
                 existUser·p0.95:   4.137 ms/op
                 existUser·p0.99:   5.661 ms/op
                 existUser·p0.999:  12.124 ms/op
                 existUser·p0.9999: 16.007 ms/op
                 existUser·p1.00:   16.105 ms/op

Iteration   3: 3.361 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.749 ms/op
                 existUser·p0.50:   3.338 ms/op
                 existUser·p0.90:   3.883 ms/op
                 existUser·p0.95:   4.153 ms/op
                 existUser·p0.99:   5.169 ms/op
                 existUser·p0.999:  8.550 ms/op
                 existUser·p0.9999: 20.824 ms/op
                 existUser·p1.00:   22.020 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 281748
  mean =      3.407 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8466 
    [ 2.500,  5.000) = 268867 
    [ 5.000,  7.500) = 3697 
    [ 7.500, 10.000) = 492 
    [10.000, 12.500) = 51 
    [12.500, 15.000) = 66 
    [15.000, 17.500) = 59 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.730 ms/op
     p(50.0000) =      3.383 ms/op
     p(90.0000) =      3.871 ms/op
     p(95.0000) =      4.116 ms/op
     p(99.0000) =      5.464 ms/op
     p(99.9000) =      8.864 ms/op
     p(99.9900) =     20.382 ms/op
     p(99.9990) =     21.698 ms/op
     p(99.9999) =     22.020 ms/op
    p(100.0000) =     22.020 ms/op


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
# Warmup Iteration   1: 4.889 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.829 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.653 ±(99.9%) 0.008 ms/op
Iteration   1: 3.628 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.829 ms/op
                 getUser·p0.50:   3.572 ms/op
                 getUser·p0.90:   4.227 ms/op
                 getUser·p0.95:   4.579 ms/op
                 getUser·p0.99:   5.923 ms/op
                 getUser·p0.999:  9.425 ms/op
                 getUser·p0.9999: 16.065 ms/op
                 getUser·p1.00:   16.237 ms/op

Iteration   2: 3.653 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.741 ms/op
                 getUser·p0.50:   3.600 ms/op
                 getUser·p0.90:   4.350 ms/op
                 getUser·p0.95:   4.702 ms/op
                 getUser·p0.99:   5.865 ms/op
                 getUser·p0.999:  9.716 ms/op
                 getUser·p0.9999: 16.028 ms/op
                 getUser·p1.00:   16.450 ms/op

Iteration   3: 3.658 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.804 ms/op
                 getUser·p0.50:   3.600 ms/op
                 getUser·p0.90:   4.268 ms/op
                 getUser·p0.95:   4.628 ms/op
                 getUser·p0.99:   5.893 ms/op
                 getUser·p0.999:  13.908 ms/op
                 getUser·p0.9999: 30.679 ms/op
                 getUser·p1.00:   30.999 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 263260
  mean =      3.646 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7678 
    [ 2.500,  5.000) = 248651 
    [ 5.000,  7.500) = 6019 
    [ 7.500, 10.000) = 658 
    [10.000, 12.500) = 62 
    [12.500, 15.000) = 82 
    [15.000, 17.500) = 46 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 10 
    [30.000, 32.500) = 22 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.741 ms/op
     p(50.0000) =      3.592 ms/op
     p(90.0000) =      4.284 ms/op
     p(95.0000) =      4.645 ms/op
     p(99.0000) =      5.898 ms/op
     p(99.9000) =      9.896 ms/op
     p(99.9900) =     29.498 ms/op
     p(99.9990) =     30.978 ms/op
     p(99.9999) =     30.999 ms/op
    p(100.0000) =     30.999 ms/op


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
# Warmup Iteration   1: 6.571 ±(99.9%) 0.071 ms/op
# Warmup Iteration   2: 4.945 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.678 ±(99.9%) 0.014 ms/op
Iteration   1: 4.657 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.569 ms/op
                 listUser·p0.50:   4.465 ms/op
                 listUser·p0.90:   5.800 ms/op
                 listUser·p0.95:   6.701 ms/op
                 listUser·p0.99:   8.033 ms/op
                 listUser·p0.999:  14.332 ms/op
                 listUser·p0.9999: 17.990 ms/op
                 listUser·p1.00:   18.579 ms/op

Iteration   2: 4.591 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.835 ms/op
                 listUser·p0.50:   4.375 ms/op
                 listUser·p0.90:   5.800 ms/op
                 listUser·p0.95:   6.513 ms/op
                 listUser·p0.99:   8.200 ms/op
                 listUser·p0.999:  19.202 ms/op
                 listUser·p0.9999: 25.921 ms/op
                 listUser·p1.00:   26.182 ms/op

Iteration   3: 4.675 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.143 ms/op
                 listUser·p0.50:   4.497 ms/op
                 listUser·p0.90:   5.710 ms/op
                 listUser·p0.95:   6.636 ms/op
                 listUser·p0.99:   8.059 ms/op
                 listUser·p0.999:  19.857 ms/op
                 listUser·p0.9999: 29.856 ms/op
                 listUser·p1.00:   32.440 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 206982
  mean =      4.641 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 359 
    [ 2.500,  5.000) = 166955 
    [ 5.000,  7.500) = 35683 
    [ 7.500, 10.000) = 3351 
    [10.000, 12.500) = 238 
    [12.500, 15.000) = 117 
    [15.000, 17.500) = 77 
    [17.500, 20.000) = 86 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 14 
    [27.500, 30.000) = 27 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.143 ms/op
     p(50.0000) =      4.448 ms/op
     p(90.0000) =      5.767 ms/op
     p(95.0000) =      6.619 ms/op
     p(99.0000) =      8.094 ms/op
     p(99.9000) =     16.648 ms/op
     p(99.9900) =     28.997 ms/op
     p(99.9990) =     32.075 ms/op
     p(99.9999) =     32.440 ms/op
    p(100.0000) =     32.440 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.861 ± 2.079  ops/ms
ClientGrpc.existUser                       thrpt       3   9.427 ± 0.874  ops/ms
ClientGrpc.getUser                         thrpt       3   8.966 ± 0.720  ops/ms
ClientGrpc.listUser                        thrpt       3   6.812 ± 0.783  ops/ms
ClientGrpc.createUser                       avgt       3   3.645 ± 0.809   ms/op
ClientGrpc.existUser                        avgt       3   3.497 ± 1.010   ms/op
ClientGrpc.getUser                          avgt       3   3.622 ± 1.209   ms/op
ClientGrpc.listUser                         avgt       3   4.648 ± 1.522   ms/op
ClientGrpc.createUser                     sample  266435   3.601 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.842           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.543           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.202           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.579           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.923           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.479           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          26.958           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          29.032           ms/op
ClientGrpc.existUser                      sample  281748   3.407 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.730           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.383           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.871           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.116           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.464           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.864           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.382           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.020           ms/op
ClientGrpc.getUser                        sample  263260   3.646 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.741           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.592           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.284           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.645           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.898           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.896           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          29.498           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          30.999           ms/op
ClientGrpc.listUser                       sample  206982   4.641 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.143           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.448           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.767           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.619           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.094           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.648           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          28.997           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          32.440           ms/op
