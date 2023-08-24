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
# Warmup Iteration   1: 3.140 ops/ms
# Warmup Iteration   2: 6.618 ops/ms
# Warmup Iteration   3: 8.113 ops/ms
Iteration   1: 8.647 ops/ms
Iteration   2: 8.677 ops/ms
Iteration   3: 8.469 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.598 ±(99.9%) 2.051 ops/ms [Average]
  (min, avg, max) = (8.469, 8.598, 8.677), stdev = 0.112
  CI (99.9%): [6.546, 10.649] (assumes normal distribution)


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
# Warmup Iteration   1: 5.909 ops/ms
# Warmup Iteration   2: 8.613 ops/ms
# Warmup Iteration   3: 9.228 ops/ms
Iteration   1: 9.163 ops/ms
Iteration   2: 9.375 ops/ms
Iteration   3: 9.449 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.329 ±(99.9%) 2.702 ops/ms [Average]
  (min, avg, max) = (9.163, 9.329, 9.449), stdev = 0.148
  CI (99.9%): [6.627, 12.031] (assumes normal distribution)


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
# Warmup Iteration   1: 5.511 ops/ms
# Warmup Iteration   2: 8.273 ops/ms
# Warmup Iteration   3: 8.638 ops/ms
Iteration   1: 8.542 ops/ms
Iteration   2: 8.820 ops/ms
Iteration   3: 8.763 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.708 ±(99.9%) 2.677 ops/ms [Average]
  (min, avg, max) = (8.542, 8.708, 8.820), stdev = 0.147
  CI (99.9%): [6.031, 11.386] (assumes normal distribution)


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
# Warmup Iteration   1: 4.308 ops/ms
# Warmup Iteration   2: 6.002 ops/ms
# Warmup Iteration   3: 6.481 ops/ms
Iteration   1: 6.556 ops/ms
Iteration   2: 6.577 ops/ms
Iteration   3: 6.691 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.608 ±(99.9%) 1.321 ops/ms [Average]
  (min, avg, max) = (6.556, 6.608, 6.691), stdev = 0.072
  CI (99.9%): [5.287, 7.929] (assumes normal distribution)


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
# Warmup Iteration   1: 5.666 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.932 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.923 ±(99.9%) 0.008 ms/op
Iteration   1: 3.667 ±(99.9%) 0.005 ms/op
Iteration   2: 3.696 ±(99.9%) 0.004 ms/op
Iteration   3: 3.645 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.669 ±(99.9%) 0.467 ms/op [Average]
  (min, avg, max) = (3.645, 3.669, 3.696), stdev = 0.026
  CI (99.9%): [3.203, 4.136] (assumes normal distribution)


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
# Warmup Iteration   1: 4.754 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.635 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.566 ±(99.9%) 0.003 ms/op
Iteration   1: 3.471 ±(99.9%) 0.004 ms/op
Iteration   2: 3.409 ±(99.9%) 0.004 ms/op
Iteration   3: 3.455 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.445 ±(99.9%) 0.588 ms/op [Average]
  (min, avg, max) = (3.409, 3.445, 3.471), stdev = 0.032
  CI (99.9%): [2.857, 4.033] (assumes normal distribution)


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
# Warmup Iteration   1: 5.164 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.940 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.751 ±(99.9%) 0.004 ms/op
Iteration   1: 3.716 ±(99.9%) 0.010 ms/op
Iteration   2: 3.673 ±(99.9%) 0.004 ms/op
Iteration   3: 3.733 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.707 ±(99.9%) 0.564 ms/op [Average]
  (min, avg, max) = (3.673, 3.707, 3.733), stdev = 0.031
  CI (99.9%): [3.143, 4.271] (assumes normal distribution)


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
# Warmup Iteration   1: 6.093 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 5.453 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.912 ±(99.9%) 0.031 ms/op
Iteration   1: 4.833 ±(99.9%) 0.012 ms/op
Iteration   2: 4.898 ±(99.9%) 0.013 ms/op
Iteration   3: 4.978 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.903 ±(99.9%) 1.330 ms/op [Average]
  (min, avg, max) = (4.833, 4.903, 4.978), stdev = 0.073
  CI (99.9%): [3.573, 6.233] (assumes normal distribution)


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
# Warmup Iteration   1: 5.387 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 3.999 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.777 ±(99.9%) 0.010 ms/op
Iteration   1: 3.638 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.852 ms/op
                 createUser·p0.50:   3.580 ms/op
                 createUser·p0.90:   4.284 ms/op
                 createUser·p0.95:   4.678 ms/op
                 createUser·p0.99:   6.005 ms/op
                 createUser·p0.999:  11.995 ms/op
                 createUser·p0.9999: 24.609 ms/op
                 createUser·p1.00:   25.002 ms/op

Iteration   2: 3.708 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.895 ms/op
                 createUser·p0.50:   3.637 ms/op
                 createUser·p0.90:   4.456 ms/op
                 createUser·p0.95:   4.792 ms/op
                 createUser·p0.99:   6.242 ms/op
                 createUser·p0.999:  11.338 ms/op
                 createUser·p0.9999: 23.749 ms/op
                 createUser·p1.00:   24.216 ms/op

Iteration   3: 3.713 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.952 ms/op
                 createUser·p0.50:   3.641 ms/op
                 createUser·p0.90:   4.371 ms/op
                 createUser·p0.95:   4.653 ms/op
                 createUser·p0.99:   5.710 ms/op
                 createUser·p0.999:  14.716 ms/op
                 createUser·p0.9999: 25.309 ms/op
                 createUser·p1.00:   25.592 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 260337
  mean =      3.686 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6766 
    [ 2.500,  5.000) = 246068 
    [ 5.000,  7.500) = 6511 
    [ 7.500, 10.000) = 581 
    [10.000, 12.500) = 184 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 100 
    [25.000, 27.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.852 ms/op
     p(50.0000) =      3.617 ms/op
     p(90.0000) =      4.383 ms/op
     p(95.0000) =      4.710 ms/op
     p(99.0000) =      6.013 ms/op
     p(99.9000) =     11.878 ms/op
     p(99.9900) =     24.674 ms/op
     p(99.9990) =     25.487 ms/op
     p(99.9999) =     25.592 ms/op
    p(100.0000) =     25.592 ms/op


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
# Warmup Iteration   1: 5.048 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.736 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.602 ±(99.9%) 0.007 ms/op
Iteration   1: 3.547 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.777 ms/op
                 existUser·p0.50:   3.494 ms/op
                 existUser·p0.90:   4.219 ms/op
                 existUser·p0.95:   4.506 ms/op
                 existUser·p0.99:   5.997 ms/op
                 existUser·p0.999:  11.673 ms/op
                 existUser·p0.9999: 19.562 ms/op
                 existUser·p1.00:   19.988 ms/op

Iteration   2: 3.446 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.761 ms/op
                 existUser·p0.50:   3.412 ms/op
                 existUser·p0.90:   4.039 ms/op
                 existUser·p0.95:   4.391 ms/op
                 existUser·p0.99:   5.562 ms/op
                 existUser·p0.999:  9.080 ms/op
                 existUser·p0.9999: 15.444 ms/op
                 existUser·p1.00:   17.433 ms/op

Iteration   3: 3.471 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.784 ms/op
                 existUser·p0.50:   3.445 ms/op
                 existUser·p0.90:   4.112 ms/op
                 existUser·p0.95:   4.350 ms/op
                 existUser·p0.99:   5.554 ms/op
                 existUser·p0.999:  10.109 ms/op
                 existUser·p0.9999: 23.429 ms/op
                 existUser·p1.00:   24.019 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 275200
  mean =      3.487 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11810 
    [ 2.500,  5.000) = 258271 
    [ 5.000,  7.500) = 4151 
    [ 7.500, 10.000) = 631 
    [10.000, 12.500) = 178 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.761 ms/op
     p(50.0000) =      3.445 ms/op
     p(90.0000) =      4.133 ms/op
     p(95.0000) =      4.424 ms/op
     p(99.0000) =      5.661 ms/op
     p(99.9000) =     10.745 ms/op
     p(99.9900) =     21.740 ms/op
     p(99.9990) =     23.871 ms/op
     p(99.9999) =     24.019 ms/op
    p(100.0000) =     24.019 ms/op


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
# Warmup Iteration   1: 5.410 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 3.928 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.718 ±(99.9%) 0.009 ms/op
Iteration   1: 3.681 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.767 ms/op
                 getUser·p0.50:   3.604 ms/op
                 getUser·p0.90:   4.334 ms/op
                 getUser·p0.95:   4.669 ms/op
                 getUser·p0.99:   6.046 ms/op
                 getUser·p0.999:  12.093 ms/op
                 getUser·p0.9999: 16.820 ms/op
                 getUser·p1.00:   17.433 ms/op

Iteration   2: 3.677 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.026 ms/op
                 getUser·p0.50:   3.621 ms/op
                 getUser·p0.90:   4.391 ms/op
                 getUser·p0.95:   4.702 ms/op
                 getUser·p0.99:   5.718 ms/op
                 getUser·p0.999:  9.401 ms/op
                 getUser·p0.9999: 16.585 ms/op
                 getUser·p1.00:   18.317 ms/op

Iteration   3: 3.651 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.985 ms/op
                 getUser·p0.50:   3.600 ms/op
                 getUser·p0.90:   4.325 ms/op
                 getUser·p0.95:   4.678 ms/op
                 getUser·p0.99:   5.808 ms/op
                 getUser·p0.999:  13.893 ms/op
                 getUser·p0.9999: 34.306 ms/op
                 getUser·p1.00:   34.800 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 261663
  mean =      3.670 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8052 
    [ 2.500,  5.000) = 246310 
    [ 5.000,  7.500) = 6364 
    [ 7.500, 10.000) = 539 
    [10.000, 12.500) = 197 
    [12.500, 15.000) = 69 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 21 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 32 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.767 ms/op
     p(50.0000) =      3.609 ms/op
     p(90.0000) =      4.350 ms/op
     p(95.0000) =      4.686 ms/op
     p(99.0000) =      5.841 ms/op
     p(99.9000) =     11.420 ms/op
     p(99.9900) =     32.861 ms/op
     p(99.9990) =     34.734 ms/op
     p(99.9999) =     34.800 ms/op
    p(100.0000) =     34.800 ms/op


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
# Warmup Iteration   1: 6.918 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 5.316 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.911 ±(99.9%) 0.014 ms/op
Iteration   1: 4.827 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.874 ms/op
                 listUser·p0.50:   4.637 ms/op
                 listUser·p0.90:   5.898 ms/op
                 listUser·p0.95:   6.685 ms/op
                 listUser·p0.99:   8.569 ms/op
                 listUser·p0.999:  16.377 ms/op
                 listUser·p0.9999: 19.661 ms/op
                 listUser·p1.00:   20.382 ms/op

Iteration   2: 4.851 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.552 ms/op
                 listUser·p0.50:   4.653 ms/op
                 listUser·p0.90:   6.038 ms/op
                 listUser·p0.95:   6.857 ms/op
                 listUser·p0.99:   8.897 ms/op
                 listUser·p0.999:  16.404 ms/op
                 listUser·p0.9999: 19.144 ms/op
                 listUser·p1.00:   19.661 ms/op

Iteration   3: 4.828 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.059 ms/op
                 listUser·p0.50:   4.620 ms/op
                 listUser·p0.90:   5.956 ms/op
                 listUser·p0.95:   6.808 ms/op
                 listUser·p0.99:   8.438 ms/op
                 listUser·p0.999:  22.369 ms/op
                 listUser·p0.9999: 32.747 ms/op
                 listUser·p1.00:   33.161 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 198717
  mean =      4.835 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 280 
    [ 2.500,  5.000) = 144796 
    [ 5.000,  7.500) = 48266 
    [ 7.500, 10.000) = 4434 
    [10.000, 12.500) = 537 
    [12.500, 15.000) = 123 
    [15.000, 17.500) = 107 
    [17.500, 20.000) = 77 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 48 
    [32.500, 35.000) = 16 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.059 ms/op
     p(50.0000) =      4.637 ms/op
     p(90.0000) =      5.972 ms/op
     p(95.0000) =      6.783 ms/op
     p(99.0000) =      8.634 ms/op
     p(99.9000) =     16.852 ms/op
     p(99.9900) =     32.440 ms/op
     p(99.9990) =     32.999 ms/op
     p(99.9999) =     33.161 ms/op
    p(100.0000) =     33.161 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.598 ± 2.051  ops/ms
ClientGrpc.existUser                       thrpt       3   9.329 ± 2.702  ops/ms
ClientGrpc.getUser                         thrpt       3   8.708 ± 2.677  ops/ms
ClientGrpc.listUser                        thrpt       3   6.608 ± 1.321  ops/ms
ClientGrpc.createUser                       avgt       3   3.669 ± 0.467   ms/op
ClientGrpc.existUser                        avgt       3   3.445 ± 0.588   ms/op
ClientGrpc.getUser                          avgt       3   3.707 ± 0.564   ms/op
ClientGrpc.listUser                         avgt       3   4.903 ± 1.330   ms/op
ClientGrpc.createUser                     sample  260337   3.686 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.852           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.617           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.383           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.710           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.013           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.878           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.674           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.592           ms/op
ClientGrpc.existUser                      sample  275200   3.487 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.761           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.445           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.133           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.424           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.661           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.745           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.740           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          24.019           ms/op
ClientGrpc.getUser                        sample  261663   3.670 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.767           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.609           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.350           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.686           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.841           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.420           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          32.861           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          34.800           ms/op
ClientGrpc.listUser                       sample  198717   4.835 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.059           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.637           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.972           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.783           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.634           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.852           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          32.440           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          33.161           ms/op
