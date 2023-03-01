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
# Warmup Iteration   1: 4.400 ops/ms
# Warmup Iteration   2: 8.787 ops/ms
# Warmup Iteration   3: 9.993 ops/ms
Iteration   1: 9.796 ops/ms
Iteration   2: 10.008 ops/ms
Iteration   3: 9.763 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.856 ±(99.9%) 2.426 ops/ms [Average]
  (min, avg, max) = (9.763, 9.856, 10.008), stdev = 0.133
  CI (99.9%): [7.430, 12.282] (assumes normal distribution)


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
# Warmup Iteration   1: 7.454 ops/ms
# Warmup Iteration   2: 10.195 ops/ms
# Warmup Iteration   3: 10.501 ops/ms
Iteration   1: 10.340 ops/ms
Iteration   2: 10.605 ops/ms
Iteration   3: 10.477 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.474 ±(99.9%) 2.414 ops/ms [Average]
  (min, avg, max) = (10.340, 10.474, 10.605), stdev = 0.132
  CI (99.9%): [8.059, 12.888] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 6.886 ops/ms
# Warmup Iteration   2: 9.714 ops/ms
# Warmup Iteration   3: 9.896 ops/ms
Iteration   1: 9.952 ops/ms
Iteration   2: 9.972 ops/ms
Iteration   3: 10.275 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.067 ±(99.9%) 3.306 ops/ms [Average]
  (min, avg, max) = (9.952, 10.067, 10.275), stdev = 0.181
  CI (99.9%): [6.761, 13.372] (assumes normal distribution)


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
# Warmup Iteration   1: 6.196 ops/ms
# Warmup Iteration   2: 7.370 ops/ms
# Warmup Iteration   3: 7.842 ops/ms
Iteration   1: 7.833 ops/ms
Iteration   2: 7.907 ops/ms
Iteration   3: 7.784 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.842 ±(99.9%) 1.128 ops/ms [Average]
  (min, avg, max) = (7.784, 7.842, 7.907), stdev = 0.062
  CI (99.9%): [6.714, 8.969] (assumes normal distribution)


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
# Warmup Iteration   1: 4.388 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.236 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.149 ±(99.9%) 0.004 ms/op
Iteration   1: 3.059 ±(99.9%) 0.002 ms/op
Iteration   2: 3.238 ±(99.9%) 0.002 ms/op
Iteration   3: 3.223 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.173 ±(99.9%) 1.812 ms/op [Average]
  (min, avg, max) = (3.059, 3.173, 3.238), stdev = 0.099
  CI (99.9%): [1.361, 4.985] (assumes normal distribution)


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
# Warmup Iteration   1: 4.205 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.129 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.081 ±(99.9%) 0.002 ms/op
Iteration   1: 3.084 ±(99.9%) 0.004 ms/op
Iteration   2: 2.986 ±(99.9%) 0.002 ms/op
Iteration   3: 2.954 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.008 ±(99.9%) 1.234 ms/op [Average]
  (min, avg, max) = (2.954, 3.008, 3.084), stdev = 0.068
  CI (99.9%): [1.774, 4.242] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.250 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.267 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.157 ±(99.9%) 0.002 ms/op
Iteration   1: 3.167 ±(99.9%) 0.002 ms/op
Iteration   2: 3.209 ±(99.9%) 0.003 ms/op
Iteration   3: 3.155 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.177 ±(99.9%) 0.516 ms/op [Average]
  (min, avg, max) = (3.155, 3.177, 3.209), stdev = 0.028
  CI (99.9%): [2.661, 3.693] (assumes normal distribution)


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
# Warmup Iteration   1: 5.582 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.154 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 4.074 ±(99.9%) 0.015 ms/op
Iteration   1: 3.927 ±(99.9%) 0.031 ms/op
Iteration   2: 3.962 ±(99.9%) 0.011 ms/op
Iteration   3: 4.029 ±(99.9%) 0.031 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.973 ±(99.9%) 0.939 ms/op [Average]
  (min, avg, max) = (3.927, 3.973, 4.029), stdev = 0.051
  CI (99.9%): [3.034, 4.912] (assumes normal distribution)


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
# Warmup Iteration   1: 4.349 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.238 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.258 ±(99.9%) 0.007 ms/op
Iteration   1: 3.171 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.858 ms/op
                 createUser·p0.50:   3.133 ms/op
                 createUser·p0.90:   3.850 ms/op
                 createUser·p0.95:   4.063 ms/op
                 createUser·p0.99:   4.465 ms/op
                 createUser·p0.999:  6.817 ms/op
                 createUser·p0.9999: 18.510 ms/op
                 createUser·p1.00:   19.661 ms/op

Iteration   2: 3.287 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.675 ms/op
                 createUser·p0.50:   3.265 ms/op
                 createUser·p0.90:   3.985 ms/op
                 createUser·p0.95:   4.145 ms/op
                 createUser·p0.99:   4.456 ms/op
                 createUser·p0.999:  11.518 ms/op
                 createUser·p0.9999: 21.201 ms/op
                 createUser·p1.00:   23.462 ms/op

Iteration   3: 3.286 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.847 ms/op
                 createUser·p0.50:   3.232 ms/op
                 createUser·p0.90:   4.006 ms/op
                 createUser·p0.95:   4.186 ms/op
                 createUser·p0.99:   4.588 ms/op
                 createUser·p0.999:  14.998 ms/op
                 createUser·p0.9999: 22.905 ms/op
                 createUser·p1.00:   23.233 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 295510
  mean =      3.247 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16530 
    [ 2.500,  5.000) = 277771 
    [ 5.000,  7.500) = 726 
    [ 7.500, 10.000) = 210 
    [10.000, 12.500) = 77 
    [12.500, 15.000) = 3 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 79 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.675 ms/op
     p(50.0000) =      3.203 ms/op
     p(90.0000) =      3.957 ms/op
     p(95.0000) =      4.141 ms/op
     p(99.0000) =      4.497 ms/op
     p(99.9000) =      9.503 ms/op
     p(99.9900) =     22.344 ms/op
     p(99.9990) =     23.243 ms/op
     p(99.9999) =     23.462 ms/op
    p(100.0000) =     23.462 ms/op


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
# Warmup Iteration   1: 3.902 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.107 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.083 ±(99.9%) 0.006 ms/op
Iteration   1: 3.058 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.804 ms/op
                 existUser·p0.50:   3.043 ms/op
                 existUser·p0.90:   3.830 ms/op
                 existUser·p0.95:   3.998 ms/op
                 existUser·p0.99:   4.325 ms/op
                 existUser·p0.999:  6.840 ms/op
                 existUser·p0.9999: 12.756 ms/op
                 existUser·p1.00:   13.156 ms/op

Iteration   2: 3.104 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.701 ms/op
                 existUser·p0.50:   3.064 ms/op
                 existUser·p0.90:   3.822 ms/op
                 existUser·p0.95:   3.990 ms/op
                 existUser·p0.99:   4.284 ms/op
                 existUser·p0.999:  6.545 ms/op
                 existUser·p0.9999: 16.335 ms/op
                 existUser·p1.00:   16.679 ms/op

Iteration   3: 3.062 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.702 ms/op
                 existUser·p0.50:   3.047 ms/op
                 existUser·p0.90:   3.748 ms/op
                 existUser·p0.95:   3.949 ms/op
                 existUser·p0.99:   4.325 ms/op
                 existUser·p0.999:  6.549 ms/op
                 existUser·p0.9999: 28.115 ms/op
                 existUser·p1.00:   28.574 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 312199
  mean =      3.075 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 39820 
    [ 2.500,  5.000) = 271392 
    [ 5.000,  7.500) = 841 
    [ 7.500, 10.000) = 18 
    [10.000, 12.500) = 15 
    [12.500, 15.000) = 34 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.701 ms/op
     p(50.0000) =      3.052 ms/op
     p(90.0000) =      3.805 ms/op
     p(95.0000) =      3.981 ms/op
     p(99.0000) =      4.309 ms/op
     p(99.9000) =      6.658 ms/op
     p(99.9900) =     27.420 ms/op
     p(99.9990) =     28.471 ms/op
     p(99.9999) =     28.574 ms/op
    p(100.0000) =     28.574 ms/op


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
# Warmup Iteration   1: 4.282 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.294 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.200 ±(99.9%) 0.006 ms/op
Iteration   1: 3.167 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.611 ms/op
                 getUser·p0.50:   3.150 ms/op
                 getUser·p0.90:   3.830 ms/op
                 getUser·p0.95:   4.039 ms/op
                 getUser·p0.99:   4.448 ms/op
                 getUser·p0.999:  8.635 ms/op
                 getUser·p0.9999: 13.319 ms/op
                 getUser·p1.00:   13.664 ms/op

Iteration   2: 3.259 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.664 ms/op
                 getUser·p0.50:   3.211 ms/op
                 getUser·p0.90:   4.002 ms/op
                 getUser·p0.95:   4.162 ms/op
                 getUser·p0.99:   4.456 ms/op
                 getUser·p0.999:  7.256 ms/op
                 getUser·p0.9999: 15.128 ms/op
                 getUser·p1.00:   15.532 ms/op

Iteration   3: 3.243 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.797 ms/op
                 getUser·p0.50:   3.199 ms/op
                 getUser·p0.90:   3.994 ms/op
                 getUser·p0.95:   4.166 ms/op
                 getUser·p0.99:   4.497 ms/op
                 getUser·p0.999:  6.449 ms/op
                 getUser·p0.9999: 15.581 ms/op
                 getUser·p1.00:   16.171 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 297858
  mean =      3.223 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 441 
    [ 1.250,  2.500) = 15290 
    [ 2.500,  3.750) = 231277 
    [ 3.750,  5.000) = 49733 
    [ 5.000,  6.250) = 554 
    [ 6.250,  7.500) = 263 
    [ 7.500,  8.750) = 107 
    [ 8.750, 10.000) = 33 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 16 
    [12.500, 13.750) = 87 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 38 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.611 ms/op
     p(50.0000) =      3.187 ms/op
     p(90.0000) =      3.949 ms/op
     p(95.0000) =      4.133 ms/op
     p(99.0000) =      4.473 ms/op
     p(99.9000) =      7.528 ms/op
     p(99.9900) =     15.215 ms/op
     p(99.9990) =     16.155 ms/op
     p(99.9999) =     16.171 ms/op
    p(100.0000) =     16.171 ms/op


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
# Warmup Iteration   1: 4.716 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.199 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.068 ±(99.9%) 0.012 ms/op
Iteration   1: 4.085 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.208 ms/op
                 listUser·p0.50:   3.912 ms/op
                 listUser·p0.90:   5.226 ms/op
                 listUser·p0.95:   5.956 ms/op
                 listUser·p0.99:   7.135 ms/op
                 listUser·p0.999:  13.140 ms/op
                 listUser·p0.9999: 14.929 ms/op
                 listUser·p1.00:   15.237 ms/op

Iteration   2: 4.009 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.206 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   4.841 ms/op
                 listUser·p0.95:   5.685 ms/op
                 listUser·p0.99:   6.930 ms/op
                 listUser·p0.999:  17.899 ms/op
                 listUser·p0.9999: 22.646 ms/op
                 listUser·p1.00:   23.527 ms/op

Iteration   3: 4.040 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.797 ms/op
                 listUser·p0.50:   3.908 ms/op
                 listUser·p0.90:   4.760 ms/op
                 listUser·p0.95:   5.603 ms/op
                 listUser·p0.99:   6.865 ms/op
                 listUser·p0.999:  20.414 ms/op
                 listUser·p0.9999: 22.973 ms/op
                 listUser·p1.00:   23.069 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 237323
  mean =      4.044 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2077 
    [ 2.500,  5.000) = 212033 
    [ 5.000,  7.500) = 21857 
    [ 7.500, 10.000) = 896 
    [10.000, 12.500) = 63 
    [12.500, 15.000) = 145 
    [15.000, 17.500) = 64 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 118 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.797 ms/op
     p(50.0000) =      3.891 ms/op
     p(90.0000) =      4.973 ms/op
     p(95.0000) =      5.767 ms/op
     p(99.0000) =      6.971 ms/op
     p(99.9000) =     15.609 ms/op
     p(99.9900) =     22.678 ms/op
     p(99.9990) =     23.294 ms/op
     p(99.9999) =     23.527 ms/op
    p(100.0000) =     23.527 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.856 ± 2.426  ops/ms
ClientGrpc.existUser                       thrpt       3  10.474 ± 2.414  ops/ms
ClientGrpc.getUser                         thrpt       3  10.067 ± 3.306  ops/ms
ClientGrpc.listUser                        thrpt       3   7.842 ± 1.128  ops/ms
ClientGrpc.createUser                       avgt       3   3.173 ± 1.812   ms/op
ClientGrpc.existUser                        avgt       3   3.008 ± 1.234   ms/op
ClientGrpc.getUser                          avgt       3   3.177 ± 0.516   ms/op
ClientGrpc.listUser                         avgt       3   3.973 ± 0.939   ms/op
ClientGrpc.createUser                     sample  295510   3.247 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.675           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.203           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.957           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.141           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.497           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.503           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.344           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.462           ms/op
ClientGrpc.existUser                      sample  312199   3.075 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.701           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.052           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.805           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.981           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.309           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.658           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          27.420           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          28.574           ms/op
ClientGrpc.getUser                        sample  297858   3.223 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.611           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.187           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.949           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.133           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.473           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.528           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.215           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          16.171           ms/op
ClientGrpc.listUser                       sample  237323   4.044 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.797           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.891           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.973           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.767           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.971           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.609           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.678           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.527           ms/op
