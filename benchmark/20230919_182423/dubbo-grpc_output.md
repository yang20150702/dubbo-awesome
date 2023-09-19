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
# Warmup Iteration   1: 3.934 ops/ms
# Warmup Iteration   2: 8.314 ops/ms
# Warmup Iteration   3: 9.167 ops/ms
Iteration   1: 9.793 ops/ms
Iteration   2: 9.888 ops/ms
Iteration   3: 9.888 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.856 ±(99.9%) 1.004 ops/ms [Average]
  (min, avg, max) = (9.793, 9.856, 9.888), stdev = 0.055
  CI (99.9%): [8.852, 10.860] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 6.535 ops/ms
# Warmup Iteration   2: 9.169 ops/ms
# Warmup Iteration   3: 10.247 ops/ms
Iteration   1: 10.031 ops/ms
Iteration   2: 10.506 ops/ms
Iteration   3: 10.950 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.496 ±(99.9%) 8.382 ops/ms [Average]
  (min, avg, max) = (10.031, 10.496, 10.950), stdev = 0.459
  CI (99.9%): [2.114, 18.878] (assumes normal distribution)


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
# Warmup Iteration   1: 6.986 ops/ms
# Warmup Iteration   2: 9.896 ops/ms
# Warmup Iteration   3: 10.255 ops/ms
Iteration   1: 10.410 ops/ms
Iteration   2: 10.338 ops/ms
Iteration   3: 10.400 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.383 ±(99.9%) 0.716 ops/ms [Average]
  (min, avg, max) = (10.338, 10.383, 10.410), stdev = 0.039
  CI (99.9%): [9.666, 11.099] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 5.539 ops/ms
# Warmup Iteration   2: 7.858 ops/ms
# Warmup Iteration   3: 8.038 ops/ms
Iteration   1: 7.621 ops/ms
Iteration   2: 7.607 ops/ms
Iteration   3: 7.725 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.651 ±(99.9%) 1.168 ops/ms [Average]
  (min, avg, max) = (7.607, 7.651, 7.725), stdev = 0.064
  CI (99.9%): [6.483, 8.819] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.106 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.283 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.204 ±(99.9%) 0.007 ms/op
Iteration   1: 3.222 ±(99.9%) 0.002 ms/op
Iteration   2: 3.263 ±(99.9%) 0.002 ms/op
Iteration   3: 3.270 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.252 ±(99.9%) 0.468 ms/op [Average]
  (min, avg, max) = (3.222, 3.252, 3.270), stdev = 0.026
  CI (99.9%): [2.784, 3.720] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.007 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.202 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.072 ±(99.9%) 0.003 ms/op
Iteration   1: 3.105 ±(99.9%) 0.003 ms/op
Iteration   2: 3.049 ±(99.9%) 0.004 ms/op
Iteration   3: 3.188 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.114 ±(99.9%) 1.283 ms/op [Average]
  (min, avg, max) = (3.049, 3.114, 3.188), stdev = 0.070
  CI (99.9%): [1.831, 4.397] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 4.408 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.417 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.404 ±(99.9%) 0.005 ms/op
Iteration   1: 3.222 ±(99.9%) 0.002 ms/op
Iteration   2: 3.054 ±(99.9%) 0.002 ms/op
Iteration   3: 3.084 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.120 ±(99.9%) 1.637 ms/op [Average]
  (min, avg, max) = (3.054, 3.120, 3.222), stdev = 0.090
  CI (99.9%): [1.483, 4.757] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.021 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.973 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 3.858 ±(99.9%) 0.007 ms/op
Iteration   1: 3.821 ±(99.9%) 0.023 ms/op
Iteration   2: 3.864 ±(99.9%) 0.021 ms/op
Iteration   3: 3.853 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.846 ±(99.9%) 0.406 ms/op [Average]
  (min, avg, max) = (3.821, 3.846, 3.864), stdev = 0.022
  CI (99.9%): [3.440, 4.252] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 3.786 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.156 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.154 ±(99.9%) 0.006 ms/op
Iteration   1: 3.139 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.824 ms/op
                 createUser·p0.50:   3.105 ms/op
                 createUser·p0.90:   3.768 ms/op
                 createUser·p0.95:   4.026 ms/op
                 createUser·p0.99:   4.874 ms/op
                 createUser·p0.999:  8.882 ms/op
                 createUser·p0.9999: 13.301 ms/op
                 createUser·p1.00:   13.566 ms/op

Iteration   2: 3.193 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.823 ms/op
                 createUser·p0.50:   3.113 ms/op
                 createUser·p0.90:   3.793 ms/op
                 createUser·p0.95:   4.059 ms/op
                 createUser·p0.99:   5.095 ms/op
                 createUser·p0.999:  12.386 ms/op
                 createUser·p0.9999: 13.892 ms/op
                 createUser·p1.00:   14.434 ms/op

Iteration   3: 3.235 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.802 ms/op
                 createUser·p0.50:   3.187 ms/op
                 createUser·p0.90:   3.781 ms/op
                 createUser·p0.95:   3.957 ms/op
                 createUser·p0.99:   4.801 ms/op
                 createUser·p0.999:  11.571 ms/op
                 createUser·p0.9999: 15.868 ms/op
                 createUser·p1.00:   16.220 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 300793
  mean =      3.189 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 724 
    [ 1.250,  2.500) = 9580 
    [ 2.500,  3.750) = 257612 
    [ 3.750,  5.000) = 30091 
    [ 5.000,  6.250) = 1642 
    [ 6.250,  7.500) = 580 
    [ 7.500,  8.750) = 138 
    [ 8.750, 10.000) = 77 
    [10.000, 11.250) = 54 
    [11.250, 12.500) = 78 
    [12.500, 13.750) = 151 
    [13.750, 15.000) = 38 
    [15.000, 16.250) = 28 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.802 ms/op
     p(50.0000) =      3.129 ms/op
     p(90.0000) =      3.781 ms/op
     p(95.0000) =      4.010 ms/op
     p(99.0000) =      4.923 ms/op
     p(99.9000) =     10.837 ms/op
     p(99.9900) =     14.449 ms/op
     p(99.9990) =     16.154 ms/op
     p(99.9999) =     16.220 ms/op
    p(100.0000) =     16.220 ms/op


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
# Warmup Iteration   1: 4.203 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.271 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.120 ±(99.9%) 0.005 ms/op
Iteration   1: 3.143 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.733 ms/op
                 existUser·p0.50:   3.088 ms/op
                 existUser·p0.90:   3.678 ms/op
                 existUser·p0.95:   3.908 ms/op
                 existUser·p0.99:   4.792 ms/op
                 existUser·p0.999:  9.951 ms/op
                 existUser·p0.9999: 13.039 ms/op
                 existUser·p1.00:   13.763 ms/op

Iteration   2: 3.077 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.827 ms/op
                 existUser·p0.50:   3.023 ms/op
                 existUser·p0.90:   3.584 ms/op
                 existUser·p0.95:   3.817 ms/op
                 existUser·p0.99:   4.571 ms/op
                 existUser·p0.999:  8.824 ms/op
                 existUser·p0.9999: 13.337 ms/op
                 existUser·p1.00:   13.992 ms/op

Iteration   3: 3.119 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.777 ms/op
                 existUser·p0.50:   3.076 ms/op
                 existUser·p0.90:   3.682 ms/op
                 existUser·p0.95:   3.854 ms/op
                 existUser·p0.99:   4.358 ms/op
                 existUser·p0.999:  6.453 ms/op
                 existUser·p0.9999: 15.982 ms/op
                 existUser·p1.00:   16.499 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 308542
  mean =      3.113 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 724 
    [ 1.250,  2.500) = 10353 
    [ 2.500,  3.750) = 274841 
    [ 3.750,  5.000) = 20728 
    [ 5.000,  6.250) = 999 
    [ 6.250,  7.500) = 397 
    [ 7.500,  8.750) = 152 
    [ 8.750, 10.000) = 88 
    [10.000, 11.250) = 19 
    [11.250, 12.500) = 89 
    [12.500, 13.750) = 91 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 24 
    [16.250, 17.500) = 5 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.733 ms/op
     p(50.0000) =      3.064 ms/op
     p(90.0000) =      3.654 ms/op
     p(95.0000) =      3.858 ms/op
     p(99.0000) =      4.538 ms/op
     p(99.9000) =      9.150 ms/op
     p(99.9900) =     14.682 ms/op
     p(99.9990) =     16.396 ms/op
     p(99.9999) =     16.499 ms/op
    p(100.0000) =     16.499 ms/op


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
# Warmup Iteration   1: 4.654 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.507 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.488 ±(99.9%) 0.008 ms/op
Iteration   1: 3.441 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.915 ms/op
                 getUser·p0.50:   3.355 ms/op
                 getUser·p0.90:   4.162 ms/op
                 getUser·p0.95:   4.530 ms/op
                 getUser·p0.99:   5.587 ms/op
                 getUser·p0.999:  8.700 ms/op
                 getUser·p0.9999: 12.627 ms/op
                 getUser·p1.00:   12.861 ms/op

Iteration   2: 3.386 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.784 ms/op
                 getUser·p0.50:   3.236 ms/op
                 getUser·p0.90:   4.190 ms/op
                 getUser·p0.95:   4.694 ms/op
                 getUser·p0.99:   6.223 ms/op
                 getUser·p0.999:  11.165 ms/op
                 getUser·p0.9999: 15.983 ms/op
                 getUser·p1.00:   20.316 ms/op

Iteration   3: 3.361 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.827 ms/op
                 getUser·p0.50:   3.285 ms/op
                 getUser·p0.90:   4.014 ms/op
                 getUser·p0.95:   4.317 ms/op
                 getUser·p0.99:   5.235 ms/op
                 getUser·p0.999:  8.438 ms/op
                 getUser·p0.9999: 15.842 ms/op
                 getUser·p1.00:   17.170 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 282853
  mean =      3.395 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5786 
    [ 2.500,  5.000) = 270356 
    [ 5.000,  7.500) = 6087 
    [ 7.500, 10.000) = 385 
    [10.000, 12.500) = 108 
    [12.500, 15.000) = 69 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.784 ms/op
     p(50.0000) =      3.289 ms/op
     p(90.0000) =      4.121 ms/op
     p(95.0000) =      4.497 ms/op
     p(99.0000) =      5.718 ms/op
     p(99.9000) =      9.028 ms/op
     p(99.9900) =     15.773 ms/op
     p(99.9990) =     17.143 ms/op
     p(99.9999) =     20.316 ms/op
    p(100.0000) =     20.316 ms/op


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
# Warmup Iteration   1: 5.568 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.440 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.288 ±(99.9%) 0.011 ms/op
Iteration   1: 4.435 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.425 ms/op
                 listUser·p0.50:   4.243 ms/op
                 listUser·p0.90:   5.521 ms/op
                 listUser·p0.95:   6.177 ms/op
                 listUser·p0.99:   7.905 ms/op
                 listUser·p0.999:  14.664 ms/op
                 listUser·p0.9999: 15.889 ms/op
                 listUser·p1.00:   16.040 ms/op

Iteration   2: 4.274 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.737 ms/op
                 listUser·p0.50:   4.088 ms/op
                 listUser·p0.90:   5.243 ms/op
                 listUser·p0.95:   5.898 ms/op
                 listUser·p0.99:   7.569 ms/op
                 listUser·p0.999:  14.929 ms/op
                 listUser·p0.9999: 16.704 ms/op
                 listUser·p1.00:   18.153 ms/op

Iteration   3: 4.172 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.288 ms/op
                 listUser·p0.50:   4.018 ms/op
                 listUser·p0.90:   5.071 ms/op
                 listUser·p0.95:   5.734 ms/op
                 listUser·p0.99:   7.217 ms/op
                 listUser·p0.999:  15.565 ms/op
                 listUser·p0.9999: 21.529 ms/op
                 listUser·p1.00:   21.955 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 223584
  mean =      4.291 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 665 
    [ 2.500,  5.000) = 193055 
    [ 5.000,  7.500) = 27417 
    [ 7.500, 10.000) = 1812 
    [10.000, 12.500) = 269 
    [12.500, 15.000) = 163 
    [15.000, 17.500) = 169 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.288 ms/op
     p(50.0000) =      4.112 ms/op
     p(90.0000) =      5.284 ms/op
     p(95.0000) =      5.947 ms/op
     p(99.0000) =      7.594 ms/op
     p(99.9000) =     14.844 ms/op
     p(99.9900) =     19.825 ms/op
     p(99.9990) =     21.955 ms/op
     p(99.9999) =     21.955 ms/op
    p(100.0000) =     21.955 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.856 ± 1.004  ops/ms
ClientGrpc.existUser                       thrpt       3  10.496 ± 8.382  ops/ms
ClientGrpc.getUser                         thrpt       3  10.383 ± 0.716  ops/ms
ClientGrpc.listUser                        thrpt       3   7.651 ± 1.168  ops/ms
ClientGrpc.createUser                       avgt       3   3.252 ± 0.468   ms/op
ClientGrpc.existUser                        avgt       3   3.114 ± 1.283   ms/op
ClientGrpc.getUser                          avgt       3   3.120 ± 1.637   ms/op
ClientGrpc.listUser                         avgt       3   3.846 ± 0.406   ms/op
ClientGrpc.createUser                     sample  300793   3.189 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.802           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.129           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.781           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.010           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.923           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.837           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          14.449           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          16.220           ms/op
ClientGrpc.existUser                      sample  308542   3.113 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.733           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.064           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.654           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.858           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.538           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.150           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.682           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.499           ms/op
ClientGrpc.getUser                        sample  282853   3.395 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.784           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.289           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.121           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.497           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.718           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.028           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.773           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.316           ms/op
ClientGrpc.listUser                       sample  223584   4.291 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.288           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.112           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.284           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.947           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.594           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.844           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.825           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.955           ms/op
