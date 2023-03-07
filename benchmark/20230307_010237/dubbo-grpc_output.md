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
# Warmup Iteration   1: 5.145 ops/ms
# Warmup Iteration   2: 9.146 ops/ms
# Warmup Iteration   3: 10.545 ops/ms
Iteration   1: 11.144 ops/ms
Iteration   2: 10.373 ops/ms
Iteration   3: 10.029 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.515 ±(99.9%) 10.418 ops/ms [Average]
  (min, avg, max) = (10.029, 10.515, 11.144), stdev = 0.571
  CI (99.9%): [0.097, 20.933] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 8.219 ops/ms
# Warmup Iteration   2: 10.611 ops/ms
# Warmup Iteration   3: 10.773 ops/ms
Iteration   1: 10.924 ops/ms
Iteration   2: 11.042 ops/ms
Iteration   3: 10.672 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.879 ±(99.9%) 3.445 ops/ms [Average]
  (min, avg, max) = (10.672, 10.879, 11.042), stdev = 0.189
  CI (99.9%): [7.435, 14.324] (assumes normal distribution)


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
# Warmup Iteration   1: 7.599 ops/ms
# Warmup Iteration   2: 10.673 ops/ms
# Warmup Iteration   3: 10.387 ops/ms
Iteration   1: 10.402 ops/ms
Iteration   2: 10.352 ops/ms
Iteration   3: 10.559 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.438 ±(99.9%) 1.974 ops/ms [Average]
  (min, avg, max) = (10.352, 10.438, 10.559), stdev = 0.108
  CI (99.9%): [8.464, 12.411] (assumes normal distribution)


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
# Warmup Iteration   1: 5.750 ops/ms
# Warmup Iteration   2: 7.837 ops/ms
# Warmup Iteration   3: 7.823 ops/ms
Iteration   1: 8.139 ops/ms
Iteration   2: 8.307 ops/ms
Iteration   3: 8.024 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.157 ±(99.9%) 2.601 ops/ms [Average]
  (min, avg, max) = (8.024, 8.157, 8.307), stdev = 0.143
  CI (99.9%): [5.556, 10.758] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 3.918 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.105 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.064 ±(99.9%) 0.003 ms/op
Iteration   1: 3.058 ±(99.9%) 0.011 ms/op
Iteration   2: 3.020 ±(99.9%) 0.003 ms/op
Iteration   3: 3.198 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.092 ±(99.9%) 1.713 ms/op [Average]
  (min, avg, max) = (3.020, 3.092, 3.198), stdev = 0.094
  CI (99.9%): [1.379, 4.805] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.800 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.912 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.872 ±(99.9%) 0.003 ms/op
Iteration   1: 3.011 ±(99.9%) 0.002 ms/op
Iteration   2: 2.894 ±(99.9%) 0.003 ms/op
Iteration   3: 2.907 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.937 ±(99.9%) 1.165 ms/op [Average]
  (min, avg, max) = (2.894, 2.937, 3.011), stdev = 0.064
  CI (99.9%): [1.772, 4.102] (assumes normal distribution)


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
# Warmup Iteration   1: 3.862 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.081 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.070 ±(99.9%) 0.003 ms/op
Iteration   1: 3.032 ±(99.9%) 0.002 ms/op
Iteration   2: 3.062 ±(99.9%) 0.002 ms/op
Iteration   3: 2.993 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.029 ±(99.9%) 0.631 ms/op [Average]
  (min, avg, max) = (2.993, 3.029, 3.062), stdev = 0.035
  CI (99.9%): [2.398, 3.659] (assumes normal distribution)


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
# Warmup Iteration   1: 4.903 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.069 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.932 ±(99.9%) 0.042 ms/op
Iteration   1: 3.772 ±(99.9%) 0.022 ms/op
Iteration   2: 3.821 ±(99.9%) 0.015 ms/op
Iteration   3: 3.958 ±(99.9%) 0.051 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.850 ±(99.9%) 1.763 ms/op [Average]
  (min, avg, max) = (3.772, 3.850, 3.958), stdev = 0.097
  CI (99.9%): [2.087, 5.613] (assumes normal distribution)


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
# Warmup Iteration   1: 4.085 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.129 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.026 ±(99.9%) 0.007 ms/op
Iteration   1: 2.951 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.282 ms/op
                 createUser·p0.50:   2.998 ms/op
                 createUser·p0.90:   3.379 ms/op
                 createUser·p0.95:   3.600 ms/op
                 createUser·p0.99:   4.157 ms/op
                 createUser·p0.999:  6.048 ms/op
                 createUser·p0.9999: 15.057 ms/op
                 createUser·p1.00:   15.303 ms/op

Iteration   2: 3.127 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.667 ms/op
                 createUser·p0.50:   3.101 ms/op
                 createUser·p0.90:   3.817 ms/op
                 createUser·p0.95:   3.985 ms/op
                 createUser·p0.99:   4.243 ms/op
                 createUser·p0.999:  8.274 ms/op
                 createUser·p0.9999: 16.356 ms/op
                 createUser·p1.00:   17.498 ms/op

Iteration   3: 3.087 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.522 ms/op
                 createUser·p0.50:   3.072 ms/op
                 createUser·p0.90:   3.658 ms/op
                 createUser·p0.95:   3.822 ms/op
                 createUser·p0.99:   4.178 ms/op
                 createUser·p0.999:  11.213 ms/op
                 createUser·p0.9999: 17.945 ms/op
                 createUser·p1.00:   18.973 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 314291
  mean =      3.053 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2218 
    [ 1.250,  2.500) = 23491 
    [ 2.500,  3.750) = 264853 
    [ 3.750,  5.000) = 22911 
    [ 5.000,  6.250) = 360 
    [ 6.250,  7.500) = 108 
    [ 7.500,  8.750) = 43 
    [ 8.750, 10.000) = 19 
    [10.000, 11.250) = 62 
    [11.250, 12.500) = 47 
    [12.500, 13.750) = 8 
    [13.750, 15.000) = 60 
    [15.000, 16.250) = 51 
    [16.250, 17.500) = 27 
    [17.500, 18.750) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.282 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      3.662 ms/op
     p(95.0000) =      3.871 ms/op
     p(99.0000) =      4.202 ms/op
     p(99.9000) =      8.571 ms/op
     p(99.9900) =     17.582 ms/op
     p(99.9990) =     18.439 ms/op
     p(99.9999) =     18.973 ms/op
    p(100.0000) =     18.973 ms/op


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
# Warmup Iteration   1: 3.804 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 2.999 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.937 ±(99.9%) 0.007 ms/op
Iteration   1: 2.959 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.766 ms/op
                 existUser·p0.50:   2.957 ms/op
                 existUser·p0.90:   3.604 ms/op
                 existUser·p0.95:   3.793 ms/op
                 existUser·p0.99:   4.174 ms/op
                 existUser·p0.999:  6.996 ms/op
                 existUser·p0.9999: 11.128 ms/op
                 existUser·p1.00:   11.420 ms/op

Iteration   2: 2.992 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.676 ms/op
                 existUser·p0.50:   2.998 ms/op
                 existUser·p0.90:   3.650 ms/op
                 existUser·p0.95:   3.817 ms/op
                 existUser·p0.99:   4.253 ms/op
                 existUser·p0.999:  6.939 ms/op
                 existUser·p0.9999: 16.475 ms/op
                 existUser·p1.00:   17.072 ms/op

Iteration   3: 2.902 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.490 ms/op
                 existUser·p0.50:   2.875 ms/op
                 existUser·p0.90:   3.522 ms/op
                 existUser·p0.95:   3.777 ms/op
                 existUser·p0.99:   4.506 ms/op
                 existUser·p0.999:  10.646 ms/op
                 existUser·p0.9999: 15.837 ms/op
                 existUser·p1.00:   16.974 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 325300
  mean =      2.950 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2481 
    [ 1.250,  2.500) = 50187 
    [ 2.500,  3.750) = 253200 
    [ 3.750,  5.000) = 18354 
    [ 5.000,  6.250) = 475 
    [ 6.250,  7.500) = 271 
    [ 7.500,  8.750) = 103 
    [ 8.750, 10.000) = 8 
    [10.000, 11.250) = 58 
    [11.250, 12.500) = 27 
    [12.500, 13.750) = 39 
    [13.750, 15.000) = 33 
    [15.000, 16.250) = 40 
    [16.250, 17.500) = 24 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.490 ms/op
     p(50.0000) =      2.941 ms/op
     p(90.0000) =      3.604 ms/op
     p(95.0000) =      3.797 ms/op
     p(99.0000) =      4.309 ms/op
     p(99.9000) =      7.569 ms/op
     p(99.9900) =     16.014 ms/op
     p(99.9990) =     16.974 ms/op
     p(99.9999) =     17.072 ms/op
    p(100.0000) =     17.072 ms/op


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
# Warmup Iteration   1: 4.080 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.145 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.083 ±(99.9%) 0.006 ms/op
Iteration   1: 3.010 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.723 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.543 ms/op
                 getUser·p0.95:   3.736 ms/op
                 getUser·p0.99:   4.211 ms/op
                 getUser·p0.999:  6.957 ms/op
                 getUser·p0.9999: 14.211 ms/op
                 getUser·p1.00:   14.500 ms/op

Iteration   2: 3.063 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.350 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.592 ms/op
                 getUser·p0.95:   3.777 ms/op
                 getUser·p0.99:   4.252 ms/op
                 getUser·p0.999:  7.203 ms/op
                 getUser·p0.9999: 17.564 ms/op
                 getUser·p1.00:   17.793 ms/op

Iteration   3: 3.065 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.287 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.625 ms/op
                 getUser·p0.95:   3.846 ms/op
                 getUser·p0.99:   4.268 ms/op
                 getUser·p0.999:  6.719 ms/op
                 getUser·p0.9999: 13.313 ms/op
                 getUser·p1.00:   13.631 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 315234
  mean =      3.046 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1181 
    [ 1.250,  2.500) = 23941 
    [ 2.500,  3.750) = 272105 
    [ 3.750,  5.000) = 17064 
    [ 5.000,  6.250) = 514 
    [ 6.250,  7.500) = 176 
    [ 7.500,  8.750) = 71 
    [ 8.750, 10.000) = 19 
    [10.000, 11.250) = 33 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 42 
    [13.750, 15.000) = 37 
    [15.000, 16.250) = 17 
    [16.250, 17.500) = 19 
    [17.500, 18.750) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.287 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      3.584 ms/op
     p(95.0000) =      3.789 ms/op
     p(99.0000) =      4.243 ms/op
     p(99.9000) =      6.963 ms/op
     p(99.9900) =     16.858 ms/op
     p(99.9990) =     17.695 ms/op
     p(99.9999) =     17.793 ms/op
    p(100.0000) =     17.793 ms/op


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
# Warmup Iteration   1: 4.768 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.075 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.962 ±(99.9%) 0.011 ms/op
Iteration   1: 3.916 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.870 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   4.612 ms/op
                 listUser·p0.95:   5.276 ms/op
                 listUser·p0.99:   6.611 ms/op
                 listUser·p0.999:  12.905 ms/op
                 listUser·p0.9999: 14.705 ms/op
                 listUser·p1.00:   15.155 ms/op

Iteration   2: 3.947 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.043 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   4.956 ms/op
                 listUser·p0.95:   5.571 ms/op
                 listUser·p0.99:   6.799 ms/op
                 listUser·p0.999:  13.616 ms/op
                 listUser·p0.9999: 25.330 ms/op
                 listUser·p1.00:   25.625 ms/op

Iteration   3: 4.013 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.966 ms/op
                 listUser·p0.50:   3.838 ms/op
                 listUser·p0.90:   5.079 ms/op
                 listUser·p0.95:   5.505 ms/op
                 listUser·p0.99:   6.881 ms/op
                 listUser·p0.999:  14.194 ms/op
                 listUser·p0.9999: 29.263 ms/op
                 listUser·p1.00:   29.622 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 242357
  mean =      3.958 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2611 
    [ 2.500,  5.000) = 217639 
    [ 5.000,  7.500) = 20967 
    [ 7.500, 10.000) = 718 
    [10.000, 12.500) = 87 
    [12.500, 15.000) = 189 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.870 ms/op
     p(50.0000) =      3.809 ms/op
     p(90.0000) =      4.932 ms/op
     p(95.0000) =      5.489 ms/op
     p(99.0000) =      6.742 ms/op
     p(99.9000) =     13.363 ms/op
     p(99.9900) =     25.445 ms/op
     p(99.9990) =     29.524 ms/op
     p(99.9999) =     29.622 ms/op
    p(100.0000) =     29.622 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score    Error   Units
ClientGrpc.createUser                      thrpt       3  10.515 ± 10.418  ops/ms
ClientGrpc.existUser                       thrpt       3  10.879 ±  3.445  ops/ms
ClientGrpc.getUser                         thrpt       3  10.438 ±  1.974  ops/ms
ClientGrpc.listUser                        thrpt       3   8.157 ±  2.601  ops/ms
ClientGrpc.createUser                       avgt       3   3.092 ±  1.713   ms/op
ClientGrpc.existUser                        avgt       3   2.937 ±  1.165   ms/op
ClientGrpc.getUser                          avgt       3   3.029 ±  0.631   ms/op
ClientGrpc.listUser                         avgt       3   3.850 ±  1.763   ms/op
ClientGrpc.createUser                     sample  314291   3.053 ±  0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.282            ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.043            ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.662            ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.871            ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.202            ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.571            ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.582            ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.973            ms/op
ClientGrpc.existUser                      sample  325300   2.950 ±  0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.490            ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.941            ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.604            ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.797            ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.309            ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.569            ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.014            ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.072            ms/op
ClientGrpc.getUser                        sample  315234   3.046 ±  0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.287            ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.039            ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.584            ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.789            ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.243            ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.963            ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.858            ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.793            ms/op
ClientGrpc.listUser                       sample  242357   3.958 ±  0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.870            ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.809            ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.932            ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.489            ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.742            ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.363            ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.445            ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.622            ms/op
