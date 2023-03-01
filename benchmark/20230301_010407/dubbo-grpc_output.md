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
# Warmup Iteration   1: 4.145 ops/ms
# Warmup Iteration   2: 8.409 ops/ms
# Warmup Iteration   3: 9.985 ops/ms
Iteration   1: 10.028 ops/ms
Iteration   2: 10.227 ops/ms
Iteration   3: 10.191 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.149 ±(99.9%) 1.934 ops/ms [Average]
  (min, avg, max) = (10.028, 10.149, 10.227), stdev = 0.106
  CI (99.9%): [8.215, 12.083] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 6.943 ops/ms
# Warmup Iteration   2: 10.252 ops/ms
# Warmup Iteration   3: 10.648 ops/ms
Iteration   1: 10.583 ops/ms
Iteration   2: 10.791 ops/ms
Iteration   3: 10.833 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.736 ±(99.9%) 2.443 ops/ms [Average]
  (min, avg, max) = (10.583, 10.736, 10.833), stdev = 0.134
  CI (99.9%): [8.293, 13.178] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.109 ops/ms
# Warmup Iteration   2: 9.901 ops/ms
# Warmup Iteration   3: 10.083 ops/ms
Iteration   1: 10.057 ops/ms
Iteration   2: 10.161 ops/ms
Iteration   3: 10.056 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.091 ±(99.9%) 1.098 ops/ms [Average]
  (min, avg, max) = (10.056, 10.091, 10.161), stdev = 0.060
  CI (99.9%): [8.994, 11.189] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.283 ops/ms
# Warmup Iteration   2: 7.720 ops/ms
# Warmup Iteration   3: 7.871 ops/ms
Iteration   1: 7.915 ops/ms
Iteration   2: 8.242 ops/ms
Iteration   3: 7.981 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.046 ±(99.9%) 3.156 ops/ms [Average]
  (min, avg, max) = (7.915, 8.046, 8.242), stdev = 0.173
  CI (99.9%): [4.890, 11.203] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.521 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.296 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.192 ±(99.9%) 0.002 ms/op
Iteration   1: 3.229 ±(99.9%) 0.004 ms/op
Iteration   2: 3.222 ±(99.9%) 0.001 ms/op
Iteration   3: 3.294 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.248 ±(99.9%) 0.722 ms/op [Average]
  (min, avg, max) = (3.222, 3.248, 3.294), stdev = 0.040
  CI (99.9%): [2.526, 3.971] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.790 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.046 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.019 ±(99.9%) 0.002 ms/op
Iteration   1: 3.005 ±(99.9%) 0.002 ms/op
Iteration   2: 2.955 ±(99.9%) 0.002 ms/op
Iteration   3: 3.014 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.991 ±(99.9%) 0.582 ms/op [Average]
  (min, avg, max) = (2.955, 2.991, 3.014), stdev = 0.032
  CI (99.9%): [2.410, 3.573] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 4.166 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.198 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.117 ±(99.9%) 0.003 ms/op
Iteration   1: 3.064 ±(99.9%) 0.002 ms/op
Iteration   2: 3.115 ±(99.9%) 0.002 ms/op
Iteration   3: 3.139 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.106 ±(99.9%) 0.706 ms/op [Average]
  (min, avg, max) = (3.064, 3.106, 3.139), stdev = 0.039
  CI (99.9%): [2.400, 3.812] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.528 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.068 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.021 ±(99.9%) 0.022 ms/op
Iteration   1: 3.940 ±(99.9%) 0.014 ms/op
Iteration   2: 4.025 ±(99.9%) 0.012 ms/op
Iteration   3: 3.948 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.971 ±(99.9%) 0.854 ms/op [Average]
  (min, avg, max) = (3.940, 3.971, 4.025), stdev = 0.047
  CI (99.9%): [3.116, 4.825] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.350 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.285 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.056 ±(99.9%) 0.006 ms/op
Iteration   1: 3.115 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.787 ms/op
                 createUser·p0.50:   3.084 ms/op
                 createUser·p0.90:   3.760 ms/op
                 createUser·p0.95:   3.940 ms/op
                 createUser·p0.99:   4.276 ms/op
                 createUser·p0.999:  7.102 ms/op
                 createUser·p0.9999: 18.776 ms/op
                 createUser·p1.00:   19.268 ms/op

Iteration   2: 3.167 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.292 ms/op
                 createUser·p0.50:   3.133 ms/op
                 createUser·p0.90:   3.842 ms/op
                 createUser·p0.95:   3.990 ms/op
                 createUser·p0.99:   4.301 ms/op
                 createUser·p0.999:  7.913 ms/op
                 createUser·p0.9999: 17.590 ms/op
                 createUser·p1.00:   19.988 ms/op

Iteration   3: 3.068 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.802 ms/op
                 createUser·p0.50:   3.047 ms/op
                 createUser·p0.90:   3.555 ms/op
                 createUser·p0.95:   3.744 ms/op
                 createUser·p0.99:   4.235 ms/op
                 createUser·p0.999:  10.827 ms/op
                 createUser·p0.9999: 19.589 ms/op
                 createUser·p1.00:   22.807 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 307851
  mean =      3.116 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24637 
    [ 2.500,  5.000) = 282173 
    [ 5.000,  7.500) = 594 
    [ 7.500, 10.000) = 148 
    [10.000, 12.500) = 95 
    [12.500, 15.000) = 5 
    [15.000, 17.500) = 91 
    [17.500, 20.000) = 101 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.292 ms/op
     p(50.0000) =      3.080 ms/op
     p(90.0000) =      3.740 ms/op
     p(95.0000) =      3.928 ms/op
     p(99.0000) =      4.284 ms/op
     p(99.9000) =      8.803 ms/op
     p(99.9900) =     18.776 ms/op
     p(99.9990) =     20.245 ms/op
     p(99.9999) =     22.807 ms/op
    p(100.0000) =     22.807 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.955 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.137 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.082 ±(99.9%) 0.006 ms/op
Iteration   1: 3.059 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.859 ms/op
                 existUser·p0.50:   3.056 ms/op
                 existUser·p0.90:   3.785 ms/op
                 existUser·p0.95:   3.940 ms/op
                 existUser·p0.99:   4.243 ms/op
                 existUser·p0.999:  5.361 ms/op
                 existUser·p0.9999: 11.960 ms/op
                 existUser·p1.00:   12.796 ms/op

Iteration   2: 2.966 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.675 ms/op
                 existUser·p0.50:   2.974 ms/op
                 existUser·p0.90:   3.596 ms/op
                 existUser·p0.95:   3.797 ms/op
                 existUser·p0.99:   4.141 ms/op
                 existUser·p0.999:  11.814 ms/op
                 existUser·p0.9999: 18.881 ms/op
                 existUser·p1.00:   19.169 ms/op

Iteration   3: 2.951 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.695 ms/op
                 existUser·p0.50:   2.949 ms/op
                 existUser·p0.90:   3.551 ms/op
                 existUser·p0.95:   3.736 ms/op
                 existUser·p0.99:   4.174 ms/op
                 existUser·p0.999:  8.126 ms/op
                 existUser·p0.9999: 18.553 ms/op
                 existUser·p1.00:   18.973 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 320704
  mean =      2.991 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2180 
    [ 1.250,  2.500) = 45619 
    [ 2.500,  3.750) = 249563 
    [ 3.750,  5.000) = 22679 
    [ 5.000,  6.250) = 171 
    [ 6.250,  7.500) = 92 
    [ 7.500,  8.750) = 141 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 30 
    [11.250, 12.500) = 86 
    [12.500, 13.750) = 16 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 20 
    [16.250, 17.500) = 27 
    [17.500, 18.750) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.675 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.658 ms/op
     p(95.0000) =      3.846 ms/op
     p(99.0000) =      4.194 ms/op
     p(99.9000) =      8.211 ms/op
     p(99.9900) =     18.577 ms/op
     p(99.9990) =     18.999 ms/op
     p(99.9999) =     19.169 ms/op
    p(100.0000) =     19.169 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.261 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.253 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.119 ±(99.9%) 0.007 ms/op
Iteration   1: 3.209 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.825 ms/op
                 getUser·p0.50:   3.170 ms/op
                 getUser·p0.90:   3.895 ms/op
                 getUser·p0.95:   4.092 ms/op
                 getUser·p0.99:   4.497 ms/op
                 getUser·p0.999:  8.165 ms/op
                 getUser·p0.9999: 28.180 ms/op
                 getUser·p1.00:   28.606 ms/op

Iteration   2: 3.093 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.862 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.658 ms/op
                 getUser·p0.95:   3.822 ms/op
                 getUser·p0.99:   4.153 ms/op
                 getUser·p0.999:  7.230 ms/op
                 getUser·p0.9999: 19.584 ms/op
                 getUser·p1.00:   20.021 ms/op

Iteration   3: 3.128 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.671 ms/op
                 getUser·p0.50:   3.088 ms/op
                 getUser·p0.90:   3.817 ms/op
                 getUser·p0.95:   4.022 ms/op
                 getUser·p0.99:   4.383 ms/op
                 getUser·p0.999:  7.293 ms/op
                 getUser·p0.9999: 29.196 ms/op
                 getUser·p1.00:   29.721 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 305440
  mean =      3.143 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22878 
    [ 2.500,  5.000) = 281427 
    [ 5.000,  7.500) = 796 
    [ 7.500, 10.000) = 147 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 7 
    [15.000, 17.500) = 55 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.671 ms/op
     p(50.0000) =      3.101 ms/op
     p(90.0000) =      3.793 ms/op
     p(95.0000) =      3.990 ms/op
     p(99.0000) =      4.366 ms/op
     p(99.9000) =      7.677 ms/op
     p(99.9900) =     28.475 ms/op
     p(99.9990) =     29.488 ms/op
     p(99.9999) =     29.721 ms/op
    p(100.0000) =     29.721 ms/op


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
# Warmup Iteration   1: 5.743 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.119 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.008 ±(99.9%) 0.011 ms/op
Iteration   1: 3.941 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.956 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   4.678 ms/op
                 listUser·p0.95:   5.579 ms/op
                 listUser·p0.99:   6.791 ms/op
                 listUser·p0.999:  13.997 ms/op
                 listUser·p0.9999: 17.429 ms/op
                 listUser·p1.00:   17.760 ms/op

Iteration   2: 3.937 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.325 ms/op
                 listUser·p0.50:   3.760 ms/op
                 listUser·p0.90:   5.046 ms/op
                 listUser·p0.95:   5.579 ms/op
                 listUser·p0.99:   6.644 ms/op
                 listUser·p0.999:  16.695 ms/op
                 listUser·p0.9999: 22.794 ms/op
                 listUser·p1.00:   23.200 ms/op

Iteration   3: 3.912 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.059 ms/op
                 listUser·p0.50:   3.764 ms/op
                 listUser·p0.90:   4.801 ms/op
                 listUser·p0.95:   5.521 ms/op
                 listUser·p0.99:   6.729 ms/op
                 listUser·p0.999:  20.422 ms/op
                 listUser·p0.9999: 23.713 ms/op
                 listUser·p1.00:   25.068 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 244164
  mean =      3.930 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2122 
    [ 2.500,  5.000) = 220433 
    [ 5.000,  7.500) = 20701 
    [ 7.500, 10.000) = 498 
    [10.000, 12.500) = 43 
    [12.500, 15.000) = 97 
    [15.000, 17.500) = 112 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 61 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.956 ms/op
     p(50.0000) =      3.785 ms/op
     p(90.0000) =      4.858 ms/op
     p(95.0000) =      5.562 ms/op
     p(99.0000) =      6.726 ms/op
     p(99.9000) =     15.734 ms/op
     p(99.9900) =     23.331 ms/op
     p(99.9990) =     24.936 ms/op
     p(99.9999) =     25.068 ms/op
    p(100.0000) =     25.068 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.149 ± 1.934  ops/ms
ClientGrpc.existUser                       thrpt       3  10.736 ± 2.443  ops/ms
ClientGrpc.getUser                         thrpt       3  10.091 ± 1.098  ops/ms
ClientGrpc.listUser                        thrpt       3   8.046 ± 3.156  ops/ms
ClientGrpc.createUser                       avgt       3   3.248 ± 0.722   ms/op
ClientGrpc.existUser                        avgt       3   2.991 ± 0.582   ms/op
ClientGrpc.getUser                          avgt       3   3.106 ± 0.706   ms/op
ClientGrpc.listUser                         avgt       3   3.971 ± 0.854   ms/op
ClientGrpc.createUser                     sample  307851   3.116 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.292           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.080           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.740           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.928           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.284           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.803           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.776           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.807           ms/op
ClientGrpc.existUser                      sample  320704   2.991 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.675           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.990           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.658           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.846           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.194           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.211           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.577           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.169           ms/op
ClientGrpc.getUser                        sample  305440   3.143 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.671           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.101           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.793           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.990           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.366           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.677           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          28.475           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          29.721           ms/op
ClientGrpc.listUser                       sample  244164   3.930 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.956           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.785           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.858           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.562           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.726           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.734           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.331           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.068           ms/op
