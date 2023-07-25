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
# Warmup Iteration   1: 3.998 ops/ms
# Warmup Iteration   2: 8.582 ops/ms
# Warmup Iteration   3: 9.719 ops/ms
Iteration   1: 10.476 ops/ms
Iteration   2: 10.447 ops/ms
Iteration   3: 10.454 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.459 ±(99.9%) 0.271 ops/ms [Average]
  (min, avg, max) = (10.447, 10.459, 10.476), stdev = 0.015
  CI (99.9%): [10.188, 10.730] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.683 ops/ms
# Warmup Iteration   2: 10.304 ops/ms
# Warmup Iteration   3: 10.992 ops/ms
Iteration   1: 11.016 ops/ms
Iteration   2: 10.897 ops/ms
Iteration   3: 11.067 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.994 ±(99.9%) 1.592 ops/ms [Average]
  (min, avg, max) = (10.897, 10.994, 11.067), stdev = 0.087
  CI (99.9%): [9.402, 12.585] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 6.693 ops/ms
# Warmup Iteration   2: 9.833 ops/ms
# Warmup Iteration   3: 10.134 ops/ms
Iteration   1: 10.281 ops/ms
Iteration   2: 10.454 ops/ms
Iteration   3: 10.584 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.439 ±(99.9%) 2.772 ops/ms [Average]
  (min, avg, max) = (10.281, 10.439, 10.584), stdev = 0.152
  CI (99.9%): [7.667, 13.211] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.421 ops/ms
# Warmup Iteration   2: 7.129 ops/ms
# Warmup Iteration   3: 7.816 ops/ms
Iteration   1: 7.937 ops/ms
Iteration   2: 7.969 ops/ms
Iteration   3: 7.906 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.937 ±(99.9%) 0.571 ops/ms [Average]
  (min, avg, max) = (7.906, 7.937, 7.969), stdev = 0.031
  CI (99.9%): [7.366, 8.509] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.202 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 3.184 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.009 ±(99.9%) 0.004 ms/op
Iteration   1: 3.010 ±(99.9%) 0.002 ms/op
Iteration   2: 3.023 ±(99.9%) 0.003 ms/op
Iteration   3: 3.063 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.032 ±(99.9%) 0.509 ms/op [Average]
  (min, avg, max) = (3.010, 3.032, 3.063), stdev = 0.028
  CI (99.9%): [2.523, 3.541] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 4.066 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.039 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.945 ±(99.9%) 0.003 ms/op
Iteration   1: 2.912 ±(99.9%) 0.001 ms/op
Iteration   2: 2.966 ±(99.9%) 0.001 ms/op
Iteration   3: 2.930 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.936 ±(99.9%) 0.500 ms/op [Average]
  (min, avg, max) = (2.912, 2.936, 2.966), stdev = 0.027
  CI (99.9%): [2.436, 3.436] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 3.981 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.192 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.091 ±(99.9%) 0.003 ms/op
Iteration   1: 3.068 ±(99.9%) 0.003 ms/op
Iteration   2: 3.055 ±(99.9%) 0.002 ms/op
Iteration   3: 3.097 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.073 ±(99.9%) 0.392 ms/op [Average]
  (min, avg, max) = (3.055, 3.073, 3.097), stdev = 0.021
  CI (99.9%): [2.681, 3.465] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.584 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.122 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.969 ±(99.9%) 0.015 ms/op
Iteration   1: 4.051 ±(99.9%) 0.011 ms/op
Iteration   2: 4.055 ±(99.9%) 0.013 ms/op
Iteration   3: 3.986 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.031 ±(99.9%) 0.704 ms/op [Average]
  (min, avg, max) = (3.986, 4.031, 4.055), stdev = 0.039
  CI (99.9%): [3.326, 4.735] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.348 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.252 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.047 ±(99.9%) 0.006 ms/op
Iteration   1: 3.050 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.752 ms/op
                 createUser·p0.50:   3.031 ms/op
                 createUser·p0.90:   3.547 ms/op
                 createUser·p0.95:   3.826 ms/op
                 createUser·p0.99:   4.571 ms/op
                 createUser·p0.999:  8.506 ms/op
                 createUser·p0.9999: 13.025 ms/op
                 createUser·p1.00:   14.107 ms/op

Iteration   2: 3.060 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.965 ms/op
                 createUser·p0.50:   3.035 ms/op
                 createUser·p0.90:   3.498 ms/op
                 createUser·p0.95:   3.674 ms/op
                 createUser·p0.99:   4.055 ms/op
                 createUser·p0.999:  7.018 ms/op
                 createUser·p0.9999: 14.468 ms/op
                 createUser·p1.00:   14.647 ms/op

Iteration   3: 3.078 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.769 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.613 ms/op
                 createUser·p0.95:   3.850 ms/op
                 createUser·p0.99:   4.669 ms/op
                 createUser·p0.999:  8.913 ms/op
                 createUser·p0.9999: 19.792 ms/op
                 createUser·p1.00:   19.923 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 313356
  mean =      3.062 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 611 
    [ 1.250,  2.500) = 16043 
    [ 2.500,  3.750) = 279487 
    [ 3.750,  5.000) = 15591 
    [ 5.000,  6.250) = 944 
    [ 6.250,  7.500) = 296 
    [ 7.500,  8.750) = 108 
    [ 8.750, 10.000) = 52 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 27 
    [12.500, 13.750) = 58 
    [13.750, 15.000) = 43 
    [15.000, 16.250) = 31 
    [16.250, 17.500) = 22 
    [17.500, 18.750) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.752 ms/op
     p(50.0000) =      3.035 ms/op
     p(90.0000) =      3.547 ms/op
     p(95.0000) =      3.781 ms/op
     p(99.0000) =      4.448 ms/op
     p(99.9000) =      8.238 ms/op
     p(99.9900) =     19.682 ms/op
     p(99.9990) =     19.825 ms/op
     p(99.9999) =     19.923 ms/op
    p(100.0000) =     19.923 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.948 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.025 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.999 ±(99.9%) 0.006 ms/op
Iteration   1: 2.967 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.916 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.396 ms/op
                 existUser·p0.95:   3.666 ms/op
                 existUser·p0.99:   4.071 ms/op
                 existUser·p0.999:  6.915 ms/op
                 existUser·p0.9999: 14.257 ms/op
                 existUser·p1.00:   14.598 ms/op

Iteration   2: 2.954 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.701 ms/op
                 existUser·p0.50:   2.933 ms/op
                 existUser·p0.90:   3.453 ms/op
                 existUser·p0.95:   3.699 ms/op
                 existUser·p0.99:   4.448 ms/op
                 existUser·p0.999:  6.322 ms/op
                 existUser·p0.9999: 14.434 ms/op
                 existUser·p1.00:   17.105 ms/op

Iteration   3: 2.953 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.693 ms/op
                 existUser·p0.50:   2.933 ms/op
                 existUser·p0.90:   3.453 ms/op
                 existUser·p0.95:   3.699 ms/op
                 existUser·p0.99:   4.489 ms/op
                 existUser·p0.999:  7.043 ms/op
                 existUser·p0.9999: 26.837 ms/op
                 existUser·p1.00:   28.049 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 324442
  mean =      2.958 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31607 
    [ 2.500,  5.000) = 291495 
    [ 5.000,  7.500) = 1104 
    [ 7.500, 10.000) = 44 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 92 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.693 ms/op
     p(50.0000) =      2.929 ms/op
     p(90.0000) =      3.437 ms/op
     p(95.0000) =      3.686 ms/op
     p(99.0000) =      4.391 ms/op
     p(99.9000) =      6.874 ms/op
     p(99.9900) =     22.112 ms/op
     p(99.9990) =     27.001 ms/op
     p(99.9999) =     28.049 ms/op
    p(100.0000) =     28.049 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.351 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.255 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.166 ±(99.9%) 0.006 ms/op
Iteration   1: 3.086 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.051 ms/op
                 getUser·p0.50:   3.052 ms/op
                 getUser·p0.90:   3.604 ms/op
                 getUser·p0.95:   3.842 ms/op
                 getUser·p0.99:   4.530 ms/op
                 getUser·p0.999:  7.332 ms/op
                 getUser·p0.9999: 13.707 ms/op
                 getUser·p1.00:   14.057 ms/op

Iteration   2: 3.052 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.934 ms/op
                 getUser·p0.50:   3.039 ms/op
                 getUser·p0.90:   3.543 ms/op
                 getUser·p0.95:   3.797 ms/op
                 getUser·p0.99:   4.661 ms/op
                 getUser·p0.999:  7.589 ms/op
                 getUser·p0.9999: 15.583 ms/op
                 getUser·p1.00:   16.777 ms/op

Iteration   3: 3.054 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.871 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.502 ms/op
                 getUser·p0.95:   3.699 ms/op
                 getUser·p0.99:   4.276 ms/op
                 getUser·p0.999:  6.308 ms/op
                 getUser·p0.9999: 16.156 ms/op
                 getUser·p1.00:   17.695 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 313061
  mean =      3.064 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 339 
    [ 1.250,  2.500) = 17846 
    [ 2.500,  3.750) = 277721 
    [ 3.750,  5.000) = 15684 
    [ 5.000,  6.250) = 959 
    [ 6.250,  7.500) = 260 
    [ 7.500,  8.750) = 58 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 10 
    [12.500, 13.750) = 61 
    [13.750, 15.000) = 41 
    [15.000, 16.250) = 71 
    [16.250, 17.500) = 5 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.871 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      3.551 ms/op
     p(95.0000) =      3.777 ms/op
     p(99.0000) =      4.489 ms/op
     p(99.9000) =      7.234 ms/op
     p(99.9900) =     15.794 ms/op
     p(99.9990) =     17.592 ms/op
     p(99.9999) =     17.695 ms/op
    p(100.0000) =     17.695 ms/op


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
# Warmup Iteration   1: 4.642 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.640 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.103 ±(99.9%) 0.012 ms/op
Iteration   1: 4.127 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.190 ms/op
                 listUser·p0.50:   3.944 ms/op
                 listUser·p0.90:   5.145 ms/op
                 listUser·p0.95:   5.857 ms/op
                 listUser·p0.99:   7.250 ms/op
                 listUser·p0.999:  16.515 ms/op
                 listUser·p0.9999: 22.838 ms/op
                 listUser·p1.00:   23.167 ms/op

Iteration   2: 4.054 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.997 ms/op
                 listUser·p0.50:   3.883 ms/op
                 listUser·p0.90:   5.112 ms/op
                 listUser·p0.95:   5.743 ms/op
                 listUser·p0.99:   7.152 ms/op
                 listUser·p0.999:  16.723 ms/op
                 listUser·p0.9999: 19.796 ms/op
                 listUser·p1.00:   20.152 ms/op

Iteration   3: 4.067 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.268 ms/op
                 listUser·p0.50:   3.916 ms/op
                 listUser·p0.90:   4.743 ms/op
                 listUser·p0.95:   5.718 ms/op
                 listUser·p0.99:   6.988 ms/op
                 listUser·p0.999:  25.638 ms/op
                 listUser·p0.9999: 31.040 ms/op
                 listUser·p1.00:   31.392 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 235138
  mean =      4.082 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1704 
    [ 2.500,  5.000) = 208963 
    [ 5.000,  7.500) = 22787 
    [ 7.500, 10.000) = 1188 
    [10.000, 12.500) = 131 
    [12.500, 15.000) = 42 
    [15.000, 17.500) = 102 
    [17.500, 20.000) = 91 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 14 
    [27.500, 30.000) = 21 
    [30.000, 32.500) = 43 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.997 ms/op
     p(50.0000) =      3.916 ms/op
     p(90.0000) =      5.038 ms/op
     p(95.0000) =      5.775 ms/op
     p(99.0000) =      7.143 ms/op
     p(99.9000) =     17.231 ms/op
     p(99.9900) =     30.523 ms/op
     p(99.9990) =     31.347 ms/op
     p(99.9999) =     31.392 ms/op
    p(100.0000) =     31.392 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.459 ± 0.271  ops/ms
ClientGrpc.existUser                       thrpt       3  10.994 ± 1.592  ops/ms
ClientGrpc.getUser                         thrpt       3  10.439 ± 2.772  ops/ms
ClientGrpc.listUser                        thrpt       3   7.937 ± 0.571  ops/ms
ClientGrpc.createUser                       avgt       3   3.032 ± 0.509   ms/op
ClientGrpc.existUser                        avgt       3   2.936 ± 0.500   ms/op
ClientGrpc.getUser                          avgt       3   3.073 ± 0.392   ms/op
ClientGrpc.listUser                         avgt       3   4.031 ± 0.704   ms/op
ClientGrpc.createUser                     sample  313356   3.062 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.752           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.035           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.547           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.781           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.448           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.238           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.682           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.923           ms/op
ClientGrpc.existUser                      sample  324442   2.958 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.693           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.929           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.437           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.686           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.391           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.874           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          22.112           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          28.049           ms/op
ClientGrpc.getUser                        sample  313061   3.064 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.871           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.039           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.551           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.777           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.489           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.234           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.794           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.695           ms/op
ClientGrpc.listUser                       sample  235138   4.082 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.997           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.916           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.038           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.775           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.143           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.231           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          30.523           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          31.392           ms/op
