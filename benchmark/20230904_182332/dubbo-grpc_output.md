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
# Warmup Iteration   1: 3.486 ops/ms
# Warmup Iteration   2: 8.258 ops/ms
# Warmup Iteration   3: 9.505 ops/ms
Iteration   1: 10.180 ops/ms
Iteration   2: 10.285 ops/ms
Iteration   3: 10.161 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.209 ±(99.9%) 1.213 ops/ms [Average]
  (min, avg, max) = (10.161, 10.209, 10.285), stdev = 0.066
  CI (99.9%): [8.995, 11.422] (assumes normal distribution)


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
# Warmup Iteration   1: 6.424 ops/ms
# Warmup Iteration   2: 10.063 ops/ms
# Warmup Iteration   3: 10.554 ops/ms
Iteration   1: 10.737 ops/ms
Iteration   2: 10.652 ops/ms
Iteration   3: 10.649 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.679 ±(99.9%) 0.914 ops/ms [Average]
  (min, avg, max) = (10.649, 10.679, 10.737), stdev = 0.050
  CI (99.9%): [9.766, 11.593] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 6.474 ops/ms
# Warmup Iteration   2: 10.001 ops/ms
# Warmup Iteration   3: 10.145 ops/ms
Iteration   1: 10.234 ops/ms
Iteration   2: 10.254 ops/ms
Iteration   3: 10.166 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.218 ±(99.9%) 0.841 ops/ms [Average]
  (min, avg, max) = (10.166, 10.218, 10.254), stdev = 0.046
  CI (99.9%): [9.377, 11.058] (assumes normal distribution)


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
# Warmup Iteration   1: 4.725 ops/ms
# Warmup Iteration   2: 7.469 ops/ms
# Warmup Iteration   3: 7.567 ops/ms
Iteration   1: 7.702 ops/ms
Iteration   2: 7.738 ops/ms
Iteration   3: 7.659 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.700 ±(99.9%) 0.719 ops/ms [Average]
  (min, avg, max) = (7.659, 7.700, 7.738), stdev = 0.039
  CI (99.9%): [6.981, 8.419] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 4.732 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.404 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.197 ±(99.9%) 0.002 ms/op
Iteration   1: 3.127 ±(99.9%) 0.002 ms/op
Iteration   2: 3.128 ±(99.9%) 0.002 ms/op
Iteration   3: 3.145 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.133 ±(99.9%) 0.186 ms/op [Average]
  (min, avg, max) = (3.127, 3.133, 3.145), stdev = 0.010
  CI (99.9%): [2.948, 3.319] (assumes normal distribution)


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
# Warmup Iteration   1: 4.420 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.105 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.973 ±(99.9%) 0.004 ms/op
Iteration   1: 3.038 ±(99.9%) 0.002 ms/op
Iteration   2: 3.029 ±(99.9%) 0.002 ms/op
Iteration   3: 2.978 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.015 ±(99.9%) 0.586 ms/op [Average]
  (min, avg, max) = (2.978, 3.015, 3.038), stdev = 0.032
  CI (99.9%): [2.429, 3.600] (assumes normal distribution)


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
# Warmup Iteration   1: 4.538 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.322 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.183 ±(99.9%) 0.003 ms/op
Iteration   1: 3.179 ±(99.9%) 0.003 ms/op
Iteration   2: 3.151 ±(99.9%) 0.002 ms/op
Iteration   3: 3.146 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.159 ±(99.9%) 0.319 ms/op [Average]
  (min, avg, max) = (3.146, 3.159, 3.179), stdev = 0.017
  CI (99.9%): [2.840, 3.478] (assumes normal distribution)


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
# Warmup Iteration   1: 5.722 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 4.442 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.312 ±(99.9%) 0.023 ms/op
Iteration   1: 4.238 ±(99.9%) 0.019 ms/op
Iteration   2: 4.183 ±(99.9%) 0.010 ms/op
Iteration   3: 4.305 ±(99.9%) 0.024 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.242 ±(99.9%) 1.110 ms/op [Average]
  (min, avg, max) = (4.183, 4.242, 4.305), stdev = 0.061
  CI (99.9%): [3.132, 5.352] (assumes normal distribution)


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
# Warmup Iteration   1: 4.521 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.335 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.225 ±(99.9%) 0.008 ms/op
Iteration   1: 3.124 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.705 ms/op
                 createUser·p0.50:   3.101 ms/op
                 createUser·p0.90:   3.637 ms/op
                 createUser·p0.95:   3.932 ms/op
                 createUser·p0.99:   4.658 ms/op
                 createUser·p0.999:  9.026 ms/op
                 createUser·p0.9999: 15.868 ms/op
                 createUser·p1.00:   16.417 ms/op

Iteration   2: 3.103 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.980 ms/op
                 createUser·p0.50:   3.076 ms/op
                 createUser·p0.90:   3.490 ms/op
                 createUser·p0.95:   3.686 ms/op
                 createUser·p0.99:   4.573 ms/op
                 createUser·p0.999:  8.651 ms/op
                 createUser·p0.9999: 18.985 ms/op
                 createUser·p1.00:   19.300 ms/op

Iteration   3: 3.138 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.745 ms/op
                 createUser·p0.50:   3.088 ms/op
                 createUser·p0.90:   3.641 ms/op
                 createUser·p0.95:   3.895 ms/op
                 createUser·p0.99:   4.628 ms/op
                 createUser·p0.999:  9.617 ms/op
                 createUser·p0.9999: 19.458 ms/op
                 createUser·p1.00:   19.956 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 307522
  mean =      3.121 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 448 
    [ 1.250,  2.500) = 11504 
    [ 2.500,  3.750) = 275417 
    [ 3.750,  5.000) = 18059 
    [ 5.000,  6.250) = 1081 
    [ 6.250,  7.500) = 405 
    [ 7.500,  8.750) = 253 
    [ 8.750, 10.000) = 129 
    [10.000, 11.250) = 21 
    [11.250, 12.500) = 16 
    [12.500, 13.750) = 35 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 28 
    [16.250, 17.500) = 21 
    [17.500, 18.750) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.705 ms/op
     p(50.0000) =      3.084 ms/op
     p(90.0000) =      3.580 ms/op
     p(95.0000) =      3.863 ms/op
     p(99.0000) =      4.628 ms/op
     p(99.9000) =      9.052 ms/op
     p(99.9900) =     19.014 ms/op
     p(99.9990) =     19.908 ms/op
     p(99.9999) =     19.956 ms/op
    p(100.0000) =     19.956 ms/op


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
# Warmup Iteration   1: 4.079 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.251 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.120 ±(99.9%) 0.007 ms/op
Iteration   1: 3.093 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.857 ms/op
                 existUser·p0.50:   3.064 ms/op
                 existUser·p0.90:   3.654 ms/op
                 existUser·p0.95:   3.887 ms/op
                 existUser·p0.99:   4.579 ms/op
                 existUser·p0.999:  7.902 ms/op
                 existUser·p0.9999: 21.932 ms/op
                 existUser·p1.00:   22.381 ms/op

Iteration   2: 3.067 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.849 ms/op
                 existUser·p0.50:   3.052 ms/op
                 existUser·p0.90:   3.604 ms/op
                 existUser·p0.95:   3.822 ms/op
                 existUser·p0.99:   4.637 ms/op
                 existUser·p0.999:  8.370 ms/op
                 existUser·p0.9999: 14.706 ms/op
                 existUser·p1.00:   16.155 ms/op

Iteration   3: 3.070 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.748 ms/op
                 existUser·p0.50:   3.023 ms/op
                 existUser·p0.90:   3.535 ms/op
                 existUser·p0.95:   3.813 ms/op
                 existUser·p0.99:   5.014 ms/op
                 existUser·p0.999:  12.321 ms/op
                 existUser·p0.9999: 31.949 ms/op
                 existUser·p1.00:   33.522 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 312011
  mean =      3.077 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19062 
    [ 2.500,  5.000) = 290652 
    [ 5.000,  7.500) = 1719 
    [ 7.500, 10.000) = 317 
    [10.000, 12.500) = 66 
    [12.500, 15.000) = 95 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 29 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.748 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.600 ms/op
     p(95.0000) =      3.842 ms/op
     p(99.0000) =      4.727 ms/op
     p(99.9000) =      9.666 ms/op
     p(99.9900) =     31.156 ms/op
     p(99.9990) =     33.258 ms/op
     p(99.9999) =     33.522 ms/op
    p(100.0000) =     33.522 ms/op


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
# Warmup Iteration   1: 4.753 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.395 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.158 ±(99.9%) 0.006 ms/op
Iteration   1: 3.199 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.854 ms/op
                 getUser·p0.50:   3.138 ms/op
                 getUser·p0.90:   3.744 ms/op
                 getUser·p0.95:   4.051 ms/op
                 getUser·p0.99:   5.169 ms/op
                 getUser·p0.999:  10.929 ms/op
                 getUser·p0.9999: 14.271 ms/op
                 getUser·p1.00:   15.254 ms/op

Iteration   2: 3.190 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.622 ms/op
                 getUser·p0.50:   3.133 ms/op
                 getUser·p0.90:   3.703 ms/op
                 getUser·p0.95:   3.949 ms/op
                 getUser·p0.99:   4.825 ms/op
                 getUser·p0.999:  8.798 ms/op
                 getUser·p0.9999: 16.840 ms/op
                 getUser·p1.00:   17.236 ms/op

Iteration   3: 3.160 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.819 ms/op
                 getUser·p0.50:   3.138 ms/op
                 getUser·p0.90:   3.772 ms/op
                 getUser·p0.95:   4.022 ms/op
                 getUser·p0.99:   4.784 ms/op
                 getUser·p0.999:  9.087 ms/op
                 getUser·p0.9999: 18.051 ms/op
                 getUser·p1.00:   18.383 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 301551
  mean =      3.183 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 339 
    [ 1.250,  2.500) = 11496 
    [ 2.500,  3.750) = 260487 
    [ 3.750,  5.000) = 26405 
    [ 5.000,  6.250) = 1393 
    [ 6.250,  7.500) = 652 
    [ 7.500,  8.750) = 360 
    [ 8.750, 10.000) = 133 
    [10.000, 11.250) = 73 
    [11.250, 12.500) = 20 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 37 
    [15.000, 16.250) = 41 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 51 

  Percentiles, ms/op:
      p(0.0000) =      0.622 ms/op
     p(50.0000) =      3.138 ms/op
     p(90.0000) =      3.740 ms/op
     p(95.0000) =      4.006 ms/op
     p(99.0000) =      4.940 ms/op
     p(99.9000) =      9.607 ms/op
     p(99.9900) =     17.793 ms/op
     p(99.9990) =     18.251 ms/op
     p(99.9999) =     18.383 ms/op
    p(100.0000) =     18.383 ms/op


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
# Warmup Iteration   1: 5.125 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.351 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.229 ±(99.9%) 0.013 ms/op
Iteration   1: 4.143 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.233 ms/op
                 listUser·p0.50:   3.961 ms/op
                 listUser·p0.90:   5.177 ms/op
                 listUser·p0.95:   6.160 ms/op
                 listUser·p0.99:   7.504 ms/op
                 listUser·p0.999:  15.700 ms/op
                 listUser·p0.9999: 22.347 ms/op
                 listUser·p1.00:   24.281 ms/op

Iteration   2: 4.185 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.391 ms/op
                 listUser·p0.50:   4.002 ms/op
                 listUser·p0.90:   5.112 ms/op
                 listUser·p0.95:   5.874 ms/op
                 listUser·p0.99:   7.414 ms/op
                 listUser·p0.999:  18.448 ms/op
                 listUser·p0.9999: 27.111 ms/op
                 listUser·p1.00:   27.394 ms/op

Iteration   3: 4.132 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.184 ms/op
                 listUser·p0.50:   3.936 ms/op
                 listUser·p0.90:   5.169 ms/op
                 listUser·p0.95:   6.005 ms/op
                 listUser·p0.99:   7.733 ms/op
                 listUser·p0.999:  19.005 ms/op
                 listUser·p0.9999: 27.804 ms/op
                 listUser·p1.00:   29.295 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 231033
  mean =      4.153 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1002 
    [ 2.500,  5.000) = 204049 
    [ 5.000,  7.500) = 23561 
    [ 7.500, 10.000) = 1739 
    [10.000, 12.500) = 321 
    [12.500, 15.000) = 47 
    [15.000, 17.500) = 70 
    [17.500, 20.000) = 83 
    [20.000, 22.500) = 50 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 81 

  Percentiles, ms/op:
      p(0.0000) =      1.184 ms/op
     p(50.0000) =      3.969 ms/op
     p(90.0000) =      5.153 ms/op
     p(95.0000) =      6.013 ms/op
     p(99.0000) =      7.553 ms/op
     p(99.9000) =     18.250 ms/op
     p(99.9900) =     27.165 ms/op
     p(99.9990) =     29.199 ms/op
     p(99.9999) =     29.295 ms/op
    p(100.0000) =     29.295 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.209 ± 1.213  ops/ms
ClientGrpc.existUser                       thrpt       3  10.679 ± 0.914  ops/ms
ClientGrpc.getUser                         thrpt       3  10.218 ± 0.841  ops/ms
ClientGrpc.listUser                        thrpt       3   7.700 ± 0.719  ops/ms
ClientGrpc.createUser                       avgt       3   3.133 ± 0.186   ms/op
ClientGrpc.existUser                        avgt       3   3.015 ± 0.586   ms/op
ClientGrpc.getUser                          avgt       3   3.159 ± 0.319   ms/op
ClientGrpc.listUser                         avgt       3   4.242 ± 1.110   ms/op
ClientGrpc.createUser                     sample  307522   3.121 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.705           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.084           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.580           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.863           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.628           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.052           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.014           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.956           ms/op
ClientGrpc.existUser                      sample  312011   3.077 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.748           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.047           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.600           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.842           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.727           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.666           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          31.156           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          33.522           ms/op
ClientGrpc.getUser                        sample  301551   3.183 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.622           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.138           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.740           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.006           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.940           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.607           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.793           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.383           ms/op
ClientGrpc.listUser                       sample  231033   4.153 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.184           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.969           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.153           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.013           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.553           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.250           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.165           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.295           ms/op
