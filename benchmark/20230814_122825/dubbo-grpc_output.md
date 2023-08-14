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
# Warmup Iteration   1: 2.838 ops/ms
# Warmup Iteration   2: 6.100 ops/ms
# Warmup Iteration   3: 7.364 ops/ms
Iteration   1: 7.591 ops/ms
Iteration   2: 7.784 ops/ms
Iteration   3: 7.833 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.736 ±(99.9%) 2.336 ops/ms [Average]
  (min, avg, max) = (7.591, 7.736, 7.833), stdev = 0.128
  CI (99.9%): [5.400, 10.072] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.891 ops/ms
# Warmup Iteration   2: 7.948 ops/ms
# Warmup Iteration   3: 8.351 ops/ms
Iteration   1: 8.598 ops/ms
Iteration   2: 8.614 ops/ms
Iteration   3: 8.375 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.529 ±(99.9%) 2.438 ops/ms [Average]
  (min, avg, max) = (8.375, 8.529, 8.614), stdev = 0.134
  CI (99.9%): [6.091, 10.967] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 4.747 ops/ms
# Warmup Iteration   2: 7.346 ops/ms
# Warmup Iteration   3: 7.532 ops/ms
Iteration   1: 7.898 ops/ms
Iteration   2: 8.148 ops/ms
Iteration   3: 8.165 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.070 ±(99.9%) 2.729 ops/ms [Average]
  (min, avg, max) = (7.898, 8.070, 8.165), stdev = 0.150
  CI (99.9%): [5.341, 10.799] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 3.579 ops/ms
# Warmup Iteration   2: 5.949 ops/ms
# Warmup Iteration   3: 6.159 ops/ms
Iteration   1: 6.150 ops/ms
Iteration   2: 6.242 ops/ms
Iteration   3: 6.025 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.139 ±(99.9%) 1.981 ops/ms [Average]
  (min, avg, max) = (6.025, 6.139, 6.242), stdev = 0.109
  CI (99.9%): [4.158, 8.120] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.550 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.588 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.034 ±(99.9%) 0.015 ms/op
Iteration   1: 4.008 ±(99.9%) 0.005 ms/op
Iteration   2: 3.988 ±(99.9%) 0.004 ms/op
Iteration   3: 4.030 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.009 ±(99.9%) 0.383 ms/op [Average]
  (min, avg, max) = (3.988, 4.009, 4.030), stdev = 0.021
  CI (99.9%): [3.626, 4.392] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 5.840 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.022 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.934 ±(99.9%) 0.004 ms/op
Iteration   1: 3.912 ±(99.9%) 0.003 ms/op
Iteration   2: 3.748 ±(99.9%) 0.003 ms/op
Iteration   3: 3.871 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.844 ±(99.9%) 1.556 ms/op [Average]
  (min, avg, max) = (3.748, 3.844, 3.912), stdev = 0.085
  CI (99.9%): [2.288, 5.400] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 6.210 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.565 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.348 ±(99.9%) 0.010 ms/op
Iteration   1: 4.048 ±(99.9%) 0.003 ms/op
Iteration   2: 4.065 ±(99.9%) 0.003 ms/op
Iteration   3: 4.045 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.053 ±(99.9%) 0.194 ms/op [Average]
  (min, avg, max) = (4.045, 4.053, 4.065), stdev = 0.011
  CI (99.9%): [3.859, 4.247] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 7.090 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 5.637 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 5.287 ±(99.9%) 0.011 ms/op
Iteration   1: 5.093 ±(99.9%) 0.010 ms/op
Iteration   2: 5.257 ±(99.9%) 0.016 ms/op
Iteration   3: 5.178 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.176 ±(99.9%) 1.500 ms/op [Average]
  (min, avg, max) = (5.093, 5.176, 5.257), stdev = 0.082
  CI (99.9%): [3.677, 6.676] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 6.121 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 4.368 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.189 ±(99.9%) 0.012 ms/op
Iteration   1: 4.224 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.151 ms/op
                 createUser·p0.50:   4.051 ms/op
                 createUser·p0.90:   5.235 ms/op
                 createUser·p0.95:   5.906 ms/op
                 createUser·p0.99:   8.946 ms/op
                 createUser·p0.999:  15.158 ms/op
                 createUser·p0.9999: 16.368 ms/op
                 createUser·p1.00:   18.612 ms/op

Iteration   2: 4.089 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.837 ms/op
                 createUser·p0.50:   3.977 ms/op
                 createUser·p0.90:   4.948 ms/op
                 createUser·p0.95:   5.308 ms/op
                 createUser·p0.99:   6.936 ms/op
                 createUser·p0.999:  14.030 ms/op
                 createUser·p0.9999: 18.213 ms/op
                 createUser·p1.00:   18.645 ms/op

Iteration   3: 4.080 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   0.885 ms/op
                 createUser·p0.50:   3.936 ms/op
                 createUser·p0.90:   4.981 ms/op
                 createUser·p0.95:   5.505 ms/op
                 createUser·p0.99:   8.225 ms/op
                 createUser·p0.999:  19.447 ms/op
                 createUser·p0.9999: 35.138 ms/op
                 createUser·p1.00:   35.521 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 232574
  mean =      4.130 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6080 
    [ 2.500,  5.000) = 201538 
    [ 5.000,  7.500) = 21728 
    [ 7.500, 10.000) = 2070 
    [10.000, 12.500) = 572 
    [12.500, 15.000) = 337 
    [15.000, 17.500) = 143 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 29 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 22 
    [35.000, 37.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.837 ms/op
     p(50.0000) =      3.985 ms/op
     p(90.0000) =      5.046 ms/op
     p(95.0000) =      5.554 ms/op
     p(99.0000) =      8.258 ms/op
     p(99.9000) =     15.162 ms/op
     p(99.9900) =     33.554 ms/op
     p(99.9990) =     35.368 ms/op
     p(99.9999) =     35.521 ms/op
    p(100.0000) =     35.521 ms/op


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
# Warmup Iteration   1: 5.765 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 4.075 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.871 ±(99.9%) 0.011 ms/op
Iteration   1: 3.898 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.719 ms/op
                 existUser·p0.50:   3.760 ms/op
                 existUser·p0.90:   4.743 ms/op
                 existUser·p0.95:   5.243 ms/op
                 existUser·p0.99:   7.176 ms/op
                 existUser·p0.999:  12.711 ms/op
                 existUser·p0.9999: 25.159 ms/op
                 existUser·p1.00:   25.723 ms/op

Iteration   2: 3.814 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.100 ms/op
                 existUser·p0.50:   3.727 ms/op
                 existUser·p0.90:   4.538 ms/op
                 existUser·p0.95:   4.940 ms/op
                 existUser·p0.99:   7.234 ms/op
                 existUser·p0.999:  12.173 ms/op
                 existUser·p0.9999: 15.755 ms/op
                 existUser·p1.00:   16.056 ms/op

Iteration   3: 3.908 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.862 ms/op
                 existUser·p0.50:   3.801 ms/op
                 existUser·p0.90:   4.751 ms/op
                 existUser·p0.95:   5.120 ms/op
                 existUser·p0.99:   7.414 ms/op
                 existUser·p0.999:  11.110 ms/op
                 existUser·p0.9999: 20.709 ms/op
                 existUser·p1.00:   21.266 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 247959
  mean =      3.873 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6072 
    [ 2.500,  5.000) = 227467 
    [ 5.000,  7.500) = 12255 
    [ 7.500, 10.000) = 1614 
    [10.000, 12.500) = 334 
    [12.500, 15.000) = 125 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.719 ms/op
     p(50.0000) =      3.760 ms/op
     p(90.0000) =      4.686 ms/op
     p(95.0000) =      5.104 ms/op
     p(99.0000) =      7.250 ms/op
     p(99.9000) =     12.174 ms/op
     p(99.9900) =     24.622 ms/op
     p(99.9990) =     25.610 ms/op
     p(99.9999) =     25.723 ms/op
    p(100.0000) =     25.723 ms/op


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
# Warmup Iteration   1: 5.502 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 4.323 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.998 ±(99.9%) 0.011 ms/op
Iteration   1: 3.880 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.999 ms/op
                 getUser·p0.50:   3.777 ms/op
                 getUser·p0.90:   4.669 ms/op
                 getUser·p0.95:   5.145 ms/op
                 getUser·p0.99:   7.135 ms/op
                 getUser·p0.999:  12.424 ms/op
                 getUser·p0.9999: 33.022 ms/op
                 getUser·p1.00:   33.423 ms/op

Iteration   2: 4.027 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.030 ms/op
                 getUser·p0.50:   3.908 ms/op
                 getUser·p0.90:   4.858 ms/op
                 getUser·p0.95:   5.407 ms/op
                 getUser·p0.99:   7.518 ms/op
                 getUser·p0.999:  14.219 ms/op
                 getUser·p0.9999: 29.067 ms/op
                 getUser·p1.00:   29.688 ms/op

Iteration   3: 4.045 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.083 ms/op
                 getUser·p0.50:   3.920 ms/op
                 getUser·p0.90:   4.973 ms/op
                 getUser·p0.95:   5.489 ms/op
                 getUser·p0.99:   7.692 ms/op
                 getUser·p0.999:  12.697 ms/op
                 getUser·p0.9999: 24.740 ms/op
                 getUser·p1.00:   25.494 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 241054
  mean =      3.983 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8004 
    [ 2.500,  5.000) = 214079 
    [ 5.000,  7.500) = 16586 
    [ 7.500, 10.000) = 1687 
    [10.000, 12.500) = 388 
    [12.500, 15.000) = 166 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 23 
    [27.500, 30.000) = 11 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 19 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.999 ms/op
     p(50.0000) =      3.863 ms/op
     p(90.0000) =      4.841 ms/op
     p(95.0000) =      5.358 ms/op
     p(99.0000) =      7.479 ms/op
     p(99.9000) =     13.057 ms/op
     p(99.9900) =     32.270 ms/op
     p(99.9990) =     33.383 ms/op
     p(99.9999) =     33.423 ms/op
    p(100.0000) =     33.423 ms/op


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
# Warmup Iteration   1: 8.186 ±(99.9%) 0.098 ms/op
# Warmup Iteration   2: 5.826 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 5.149 ±(99.9%) 0.019 ms/op
Iteration   1: 5.150 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.059 ms/op
                 listUser·p0.50:   4.866 ms/op
                 listUser·p0.90:   6.570 ms/op
                 listUser·p0.95:   7.643 ms/op
                 listUser·p0.99:   10.617 ms/op
                 listUser·p0.999:  16.031 ms/op
                 listUser·p0.9999: 18.874 ms/op
                 listUser·p1.00:   19.399 ms/op

Iteration   2: 5.124 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   0.869 ms/op
                 listUser·p0.50:   4.825 ms/op
                 listUser·p0.90:   6.603 ms/op
                 listUser·p0.95:   7.610 ms/op
                 listUser·p0.99:   10.158 ms/op
                 listUser·p0.999:  21.773 ms/op
                 listUser·p0.9999: 28.319 ms/op
                 listUser·p1.00:   28.672 ms/op

Iteration   3: 4.956 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.303 ms/op
                 listUser·p0.50:   4.678 ms/op
                 listUser·p0.90:   6.529 ms/op
                 listUser·p0.95:   7.315 ms/op
                 listUser·p0.99:   9.863 ms/op
                 listUser·p0.999:  20.447 ms/op
                 listUser·p0.9999: 24.183 ms/op
                 listUser·p1.00:   24.642 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 189173
  mean =      5.075 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 374 
    [ 2.500,  5.000) = 115589 
    [ 5.000,  7.500) = 63613 
    [ 7.500, 10.000) = 7546 
    [10.000, 12.500) = 1276 
    [12.500, 15.000) = 347 
    [15.000, 17.500) = 172 
    [17.500, 20.000) = 89 
    [20.000, 22.500) = 92 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.869 ms/op
     p(50.0000) =      4.792 ms/op
     p(90.0000) =      6.570 ms/op
     p(95.0000) =      7.512 ms/op
     p(99.0000) =     10.191 ms/op
     p(99.9000) =     19.557 ms/op
     p(99.9900) =     26.425 ms/op
     p(99.9990) =     28.555 ms/op
     p(99.9999) =     28.672 ms/op
    p(100.0000) =     28.672 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.736 ± 2.336  ops/ms
ClientGrpc.existUser                       thrpt       3   8.529 ± 2.438  ops/ms
ClientGrpc.getUser                         thrpt       3   8.070 ± 2.729  ops/ms
ClientGrpc.listUser                        thrpt       3   6.139 ± 1.981  ops/ms
ClientGrpc.createUser                       avgt       3   4.009 ± 0.383   ms/op
ClientGrpc.existUser                        avgt       3   3.844 ± 1.556   ms/op
ClientGrpc.getUser                          avgt       3   4.053 ± 0.194   ms/op
ClientGrpc.listUser                         avgt       3   5.176 ± 1.500   ms/op
ClientGrpc.createUser                     sample  232574   4.130 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.837           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.985           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.046           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.554           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           8.258           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          15.162           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          33.554           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          35.521           ms/op
ClientGrpc.existUser                      sample  247959   3.873 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.719           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.760           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.686           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.104           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.250           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.174           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          24.622           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.723           ms/op
ClientGrpc.getUser                        sample  241054   3.983 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.999           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.863           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.841           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.358           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.479           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          13.057           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          32.270           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          33.423           ms/op
ClientGrpc.listUser                       sample  189173   5.075 ± 0.011   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.869           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.792           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.570           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.512           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.191           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.557           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.425           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.672           ms/op
