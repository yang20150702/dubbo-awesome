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
# Warmup Iteration   1: 2.550 ops/ms
# Warmup Iteration   2: 6.102 ops/ms
# Warmup Iteration   3: 7.714 ops/ms
Iteration   1: 8.131 ops/ms
Iteration   2: 8.123 ops/ms
Iteration   3: 8.196 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.150 ±(99.9%) 0.727 ops/ms [Average]
  (min, avg, max) = (8.123, 8.150, 8.196), stdev = 0.040
  CI (99.9%): [7.423, 8.877] (assumes normal distribution)


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
# Warmup Iteration   1: 5.233 ops/ms
# Warmup Iteration   2: 8.167 ops/ms
# Warmup Iteration   3: 8.719 ops/ms
Iteration   1: 9.089 ops/ms
Iteration   2: 8.738 ops/ms
Iteration   3: 9.405 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.077 ±(99.9%) 6.082 ops/ms [Average]
  (min, avg, max) = (8.738, 9.077, 9.405), stdev = 0.333
  CI (99.9%): [2.996, 15.159] (assumes normal distribution)


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
# Warmup Iteration   1: 4.761 ops/ms
# Warmup Iteration   2: 7.478 ops/ms
# Warmup Iteration   3: 8.064 ops/ms
Iteration   1: 8.094 ops/ms
Iteration   2: 8.274 ops/ms
Iteration   3: 8.203 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.190 ±(99.9%) 1.657 ops/ms [Average]
  (min, avg, max) = (8.094, 8.190, 8.274), stdev = 0.091
  CI (99.9%): [6.533, 9.847] (assumes normal distribution)


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
# Warmup Iteration   1: 4.005 ops/ms
# Warmup Iteration   2: 5.786 ops/ms
# Warmup Iteration   3: 6.131 ops/ms
Iteration   1: 6.151 ops/ms
Iteration   2: 6.203 ops/ms
Iteration   3: 6.267 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.207 ±(99.9%) 1.062 ops/ms [Average]
  (min, avg, max) = (6.151, 6.207, 6.267), stdev = 0.058
  CI (99.9%): [5.145, 7.269] (assumes normal distribution)


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
# Warmup Iteration   1: 6.103 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.234 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.047 ±(99.9%) 0.004 ms/op
Iteration   1: 4.011 ±(99.9%) 0.003 ms/op
Iteration   2: 3.972 ±(99.9%) 0.004 ms/op
Iteration   3: 3.909 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.964 ±(99.9%) 0.939 ms/op [Average]
  (min, avg, max) = (3.909, 3.964, 4.011), stdev = 0.051
  CI (99.9%): [3.025, 4.903] (assumes normal distribution)


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
# Warmup Iteration   1: 5.653 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.928 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.795 ±(99.9%) 0.004 ms/op
Iteration   1: 3.661 ±(99.9%) 0.004 ms/op
Iteration   2: 3.738 ±(99.9%) 0.003 ms/op
Iteration   3: 3.711 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.703 ±(99.9%) 0.708 ms/op [Average]
  (min, avg, max) = (3.661, 3.703, 3.738), stdev = 0.039
  CI (99.9%): [2.996, 4.411] (assumes normal distribution)


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
# Warmup Iteration   1: 5.851 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.185 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.999 ±(99.9%) 0.004 ms/op
Iteration   1: 3.911 ±(99.9%) 0.005 ms/op
Iteration   2: 3.826 ±(99.9%) 0.005 ms/op
Iteration   3: 3.833 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.857 ±(99.9%) 0.861 ms/op [Average]
  (min, avg, max) = (3.826, 3.857, 3.911), stdev = 0.047
  CI (99.9%): [2.996, 4.717] (assumes normal distribution)


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
# Warmup Iteration   1: 7.329 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 5.543 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 5.105 ±(99.9%) 0.042 ms/op
Iteration   1: 5.194 ±(99.9%) 0.012 ms/op
Iteration   2: 5.177 ±(99.9%) 0.015 ms/op
Iteration   3: 5.054 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.141 ±(99.9%) 1.394 ms/op [Average]
  (min, avg, max) = (5.054, 5.141, 5.194), stdev = 0.076
  CI (99.9%): [3.747, 6.536] (assumes normal distribution)


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
# Warmup Iteration   1: 6.113 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 4.177 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.868 ±(99.9%) 0.013 ms/op
Iteration   1: 3.852 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.876 ms/op
                 createUser·p0.50:   3.781 ms/op
                 createUser·p0.90:   4.768 ms/op
                 createUser·p0.95:   5.210 ms/op
                 createUser·p0.99:   6.480 ms/op
                 createUser·p0.999:  13.828 ms/op
                 createUser·p0.9999: 20.855 ms/op
                 createUser·p1.00:   21.922 ms/op

Iteration   2: 3.825 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.811 ms/op
                 createUser·p0.50:   3.744 ms/op
                 createUser·p0.90:   4.661 ms/op
                 createUser·p0.95:   5.071 ms/op
                 createUser·p0.99:   6.095 ms/op
                 createUser·p0.999:  12.550 ms/op
                 createUser·p0.9999: 23.272 ms/op
                 createUser·p1.00:   23.626 ms/op

Iteration   3: 3.827 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.994 ms/op
                 createUser·p0.50:   3.760 ms/op
                 createUser·p0.90:   4.702 ms/op
                 createUser·p0.95:   5.136 ms/op
                 createUser·p0.99:   6.078 ms/op
                 createUser·p0.999:  13.688 ms/op
                 createUser·p0.9999: 40.018 ms/op
                 createUser·p1.00:   40.370 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 250759
  mean =      3.834 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 235182 
    [ 5.000, 10.000) = 15114 
    [10.000, 15.000) = 279 
    [15.000, 20.000) = 90 
    [20.000, 25.000) = 62 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 24 
    [40.000, 45.000) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.811 ms/op
     p(50.0000) =      3.760 ms/op
     p(90.0000) =      4.710 ms/op
     p(95.0000) =      5.136 ms/op
     p(99.0000) =      6.185 ms/op
     p(99.9000) =     13.455 ms/op
     p(99.9900) =     39.387 ms/op
     p(99.9990) =     40.304 ms/op
     p(99.9999) =     40.370 ms/op
    p(100.0000) =     40.370 ms/op


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
# Warmup Iteration   1: 5.312 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 4.019 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.858 ±(99.9%) 0.010 ms/op
Iteration   1: 3.642 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.776 ms/op
                 existUser·p0.50:   3.596 ms/op
                 existUser·p0.90:   4.645 ms/op
                 existUser·p0.95:   5.079 ms/op
                 existUser·p0.99:   6.455 ms/op
                 existUser·p0.999:  14.109 ms/op
                 existUser·p0.9999: 15.688 ms/op
                 existUser·p1.00:   16.499 ms/op

Iteration   2: 3.634 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.861 ms/op
                 existUser·p0.50:   3.580 ms/op
                 existUser·p0.90:   4.481 ms/op
                 existUser·p0.95:   4.825 ms/op
                 existUser·p0.99:   5.915 ms/op
                 existUser·p0.999:  12.157 ms/op
                 existUser·p0.9999: 18.619 ms/op
                 existUser·p1.00:   19.169 ms/op

Iteration   3: 3.679 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.024 ms/op
                 existUser·p0.50:   3.592 ms/op
                 existUser·p0.90:   4.530 ms/op
                 existUser·p0.95:   4.973 ms/op
                 existUser·p0.99:   5.853 ms/op
                 existUser·p0.999:  8.249 ms/op
                 existUser·p0.9999: 22.660 ms/op
                 existUser·p1.00:   24.609 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 262849
  mean =      3.652 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14540 
    [ 2.500,  5.000) = 236085 
    [ 5.000,  7.500) = 11377 
    [ 7.500, 10.000) = 535 
    [10.000, 12.500) = 119 
    [12.500, 15.000) = 71 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.776 ms/op
     p(50.0000) =      3.592 ms/op
     p(90.0000) =      4.555 ms/op
     p(95.0000) =      4.956 ms/op
     p(99.0000) =      6.046 ms/op
     p(99.9000) =     10.966 ms/op
     p(99.9900) =     20.962 ms/op
     p(99.9990) =     24.247 ms/op
     p(99.9999) =     24.609 ms/op
    p(100.0000) =     24.609 ms/op


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
# Warmup Iteration   1: 6.080 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 4.217 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.894 ±(99.9%) 0.011 ms/op
Iteration   1: 3.847 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.874 ms/op
                 getUser·p0.50:   3.772 ms/op
                 getUser·p0.90:   4.825 ms/op
                 getUser·p0.95:   5.243 ms/op
                 getUser·p0.99:   6.234 ms/op
                 getUser·p0.999:  13.039 ms/op
                 getUser·p0.9999: 15.321 ms/op
                 getUser·p1.00:   15.778 ms/op

Iteration   2: 3.787 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.878 ms/op
                 getUser·p0.50:   3.744 ms/op
                 getUser·p0.90:   4.724 ms/op
                 getUser·p0.95:   5.071 ms/op
                 getUser·p0.99:   5.874 ms/op
                 getUser·p0.999:  7.844 ms/op
                 getUser·p0.9999: 18.907 ms/op
                 getUser·p1.00:   19.169 ms/op

Iteration   3: 3.896 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.831 ms/op
                 getUser·p0.50:   3.805 ms/op
                 getUser·p0.90:   4.792 ms/op
                 getUser·p0.95:   5.161 ms/op
                 getUser·p0.99:   6.185 ms/op
                 getUser·p0.999:  11.174 ms/op
                 getUser·p0.9999: 22.931 ms/op
                 getUser·p1.00:   23.298 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 249679
  mean =      3.843 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10835 
    [ 2.500,  5.000) = 222141 
    [ 5.000,  7.500) = 15891 
    [ 7.500, 10.000) = 388 
    [10.000, 12.500) = 206 
    [12.500, 15.000) = 113 
    [15.000, 17.500) = 52 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.831 ms/op
     p(50.0000) =      3.777 ms/op
     p(90.0000) =      4.776 ms/op
     p(95.0000) =      5.161 ms/op
     p(99.0000) =      6.111 ms/op
     p(99.9000) =     12.091 ms/op
     p(99.9900) =     21.365 ms/op
     p(99.9990) =     23.167 ms/op
     p(99.9999) =     23.298 ms/op
    p(100.0000) =     23.298 ms/op


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
# Warmup Iteration   1: 7.762 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 5.493 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 5.104 ±(99.9%) 0.017 ms/op
Iteration   1: 5.006 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.716 ms/op
                 listUser·p0.50:   4.784 ms/op
                 listUser·p0.90:   6.373 ms/op
                 listUser·p0.95:   7.291 ms/op
                 listUser·p0.99:   9.126 ms/op
                 listUser·p0.999:  15.123 ms/op
                 listUser·p0.9999: 17.603 ms/op
                 listUser·p1.00:   17.859 ms/op

Iteration   2: 5.033 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.147 ms/op
                 listUser·p0.50:   4.784 ms/op
                 listUser·p0.90:   6.554 ms/op
                 listUser·p0.95:   7.315 ms/op
                 listUser·p0.99:   9.077 ms/op
                 listUser·p0.999:  16.476 ms/op
                 listUser·p0.9999: 18.862 ms/op
                 listUser·p1.00:   19.235 ms/op

Iteration   3: 5.106 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.194 ms/op
                 listUser·p0.50:   4.866 ms/op
                 listUser·p0.90:   6.676 ms/op
                 listUser·p0.95:   7.660 ms/op
                 listUser·p0.99:   9.601 ms/op
                 listUser·p0.999:  19.750 ms/op
                 listUser·p0.9999: 26.984 ms/op
                 listUser·p1.00:   27.361 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 190275
  mean =      5.048 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 301 
    [ 2.500,  5.000) = 113420 
    [ 5.000,  7.500) = 67513 
    [ 7.500, 10.000) = 7947 
    [10.000, 12.500) = 685 
    [12.500, 15.000) = 100 
    [15.000, 17.500) = 169 
    [17.500, 20.000) = 88 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      1.147 ms/op
     p(50.0000) =      4.809 ms/op
     p(90.0000) =      6.521 ms/op
     p(95.0000) =      7.438 ms/op
     p(99.0000) =      9.290 ms/op
     p(99.9000) =     16.494 ms/op
     p(99.9900) =     22.148 ms/op
     p(99.9990) =     27.213 ms/op
     p(99.9999) =     27.361 ms/op
    p(100.0000) =     27.361 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.150 ± 0.727  ops/ms
ClientGrpc.existUser                       thrpt       3   9.077 ± 6.082  ops/ms
ClientGrpc.getUser                         thrpt       3   8.190 ± 1.657  ops/ms
ClientGrpc.listUser                        thrpt       3   6.207 ± 1.062  ops/ms
ClientGrpc.createUser                       avgt       3   3.964 ± 0.939   ms/op
ClientGrpc.existUser                        avgt       3   3.703 ± 0.708   ms/op
ClientGrpc.getUser                          avgt       3   3.857 ± 0.861   ms/op
ClientGrpc.listUser                         avgt       3   5.141 ± 1.394   ms/op
ClientGrpc.createUser                     sample  250759   3.834 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.811           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.760           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.710           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.136           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.185           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.455           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          39.387           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          40.370           ms/op
ClientGrpc.existUser                      sample  262849   3.652 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.776           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.592           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.555           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.956           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.046           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.966           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.962           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          24.609           ms/op
ClientGrpc.getUser                        sample  249679   3.843 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.831           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.777           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.776           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.161           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.111           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.091           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.365           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.298           ms/op
ClientGrpc.listUser                       sample  190275   5.048 ± 0.010   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.147           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.809           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.521           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.438           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.290           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.494           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.148           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.361           ms/op
