# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.139 ops/ms
# Warmup Iteration   2: 5.482 ops/ms
# Warmup Iteration   3: 8.221 ops/ms
Iteration   1: 8.841 ops/ms
Iteration   2: 9.305 ops/ms
Iteration   3: 9.042 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.063 ±(99.9%) 4.250 ops/ms [Average]
  (min, avg, max) = (8.841, 9.063, 9.305), stdev = 0.233
  CI (99.9%): [4.813, 13.312] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.872 ops/ms
# Warmup Iteration   2: 8.109 ops/ms
# Warmup Iteration   3: 9.283 ops/ms
Iteration   1: 9.594 ops/ms
Iteration   2: 9.557 ops/ms
Iteration   3: 9.729 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.627 ±(99.9%) 1.647 ops/ms [Average]
  (min, avg, max) = (9.557, 9.627, 9.729), stdev = 0.090
  CI (99.9%): [7.980, 11.274] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.136 ops/ms
# Warmup Iteration   2: 8.307 ops/ms
# Warmup Iteration   3: 9.226 ops/ms
Iteration   1: 9.299 ops/ms
Iteration   2: 9.372 ops/ms
Iteration   3: 9.178 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.283 ±(99.9%) 1.789 ops/ms [Average]
  (min, avg, max) = (9.178, 9.283, 9.372), stdev = 0.098
  CI (99.9%): [7.494, 11.072] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.796 ops/ms
# Warmup Iteration   2: 6.664 ops/ms
# Warmup Iteration   3: 7.504 ops/ms
Iteration   1: 7.675 ops/ms
Iteration   2: 7.714 ops/ms
Iteration   3: 7.916 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.768 ±(99.9%) 2.363 ops/ms [Average]
  (min, avg, max) = (7.675, 7.768, 7.916), stdev = 0.130
  CI (99.9%): [5.405, 10.131] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 10.209 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.091 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.785 ±(99.9%) 0.003 ms/op
Iteration   1: 3.501 ±(99.9%) 0.008 ms/op
Iteration   2: 3.514 ±(99.9%) 0.009 ms/op
Iteration   3: 3.557 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.524 ±(99.9%) 0.536 ms/op [Average]
  (min, avg, max) = (3.501, 3.524, 3.557), stdev = 0.029
  CI (99.9%): [2.988, 4.060] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 7.716 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.604 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.503 ±(99.9%) 0.005 ms/op
Iteration   1: 3.423 ±(99.9%) 0.005 ms/op
Iteration   2: 3.326 ±(99.9%) 0.007 ms/op
Iteration   3: 3.281 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.343 ±(99.9%) 1.328 ms/op [Average]
  (min, avg, max) = (3.281, 3.343, 3.423), stdev = 0.073
  CI (99.9%): [2.015, 4.672] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 10.064 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.753 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.574 ±(99.9%) 0.005 ms/op
Iteration   1: 3.525 ±(99.9%) 0.004 ms/op
Iteration   2: 3.465 ±(99.9%) 0.007 ms/op
Iteration   3: 3.613 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.534 ±(99.9%) 1.360 ms/op [Average]
  (min, avg, max) = (3.465, 3.534, 3.613), stdev = 0.075
  CI (99.9%): [2.175, 4.894] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 10.312 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.381 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.136 ±(99.9%) 0.011 ms/op
Iteration   1: 4.155 ±(99.9%) 0.009 ms/op
Iteration   2: 3.984 ±(99.9%) 0.012 ms/op
Iteration   3: 3.969 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.036 ±(99.9%) 1.888 ms/op [Average]
  (min, avg, max) = (3.969, 4.036, 4.155), stdev = 0.103
  CI (99.9%): [2.148, 5.924] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 9.465 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 4.205 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.484 ±(99.9%) 0.012 ms/op
Iteration   1: 3.535 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.413 ms/op
                 createUser·p0.50:   3.346 ms/op
                 createUser·p0.90:   4.104 ms/op
                 createUser·p0.95:   4.530 ms/op
                 createUser·p0.99:   6.734 ms/op
                 createUser·p0.999:  19.792 ms/op
                 createUser·p0.9999: 22.870 ms/op
                 createUser·p1.00:   26.444 ms/op

Iteration   2: 3.516 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.473 ms/op
                 createUser·p0.50:   3.351 ms/op
                 createUser·p0.90:   4.063 ms/op
                 createUser·p0.95:   4.375 ms/op
                 createUser·p0.99:   6.210 ms/op
                 createUser·p0.999:  22.968 ms/op
                 createUser·p0.9999: 27.489 ms/op
                 createUser·p1.00:   28.410 ms/op

Iteration   3: 3.428 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.745 ms/op
                 createUser·p0.50:   3.367 ms/op
                 createUser·p0.90:   3.748 ms/op
                 createUser·p0.95:   4.071 ms/op
                 createUser·p0.99:   5.784 ms/op
                 createUser·p0.999:  22.011 ms/op
                 createUser·p0.9999: 27.603 ms/op
                 createUser·p1.00:   28.312 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 274820
  mean =      3.493 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6687 
    [ 2.500,  5.000) = 260920 
    [ 5.000,  7.500) = 5587 
    [ 7.500, 10.000) = 992 
    [10.000, 12.500) = 183 
    [12.500, 15.000) = 90 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 104 
    [22.500, 25.000) = 116 
    [25.000, 27.500) = 59 

  Percentiles, ms/op:
      p(0.0000) =      1.413 ms/op
     p(50.0000) =      3.363 ms/op
     p(90.0000) =      3.998 ms/op
     p(95.0000) =      4.317 ms/op
     p(99.0000) =      6.283 ms/op
     p(99.9000) =     20.453 ms/op
     p(99.9900) =     27.166 ms/op
     p(99.9990) =     28.312 ms/op
     p(99.9999) =     28.410 ms/op
    p(100.0000) =     28.410 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 8.514 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 3.712 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.495 ±(99.9%) 0.009 ms/op
Iteration   1: 3.342 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.918 ms/op
                 existUser·p0.50:   3.256 ms/op
                 existUser·p0.90:   3.707 ms/op
                 existUser·p0.95:   4.014 ms/op
                 existUser·p0.99:   5.734 ms/op
                 existUser·p0.999:  20.878 ms/op
                 existUser·p0.9999: 27.974 ms/op
                 existUser·p1.00:   29.000 ms/op

Iteration   2: 3.354 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.532 ms/op
                 existUser·p0.50:   3.207 ms/op
                 existUser·p0.90:   3.654 ms/op
                 existUser·p0.95:   3.973 ms/op
                 existUser·p0.99:   6.676 ms/op
                 existUser·p0.999:  22.223 ms/op
                 existUser·p0.9999: 29.015 ms/op
                 existUser·p1.00:   30.245 ms/op

Iteration   3: 3.309 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.698 ms/op
                 existUser·p0.50:   3.203 ms/op
                 existUser·p0.90:   3.576 ms/op
                 existUser·p0.95:   3.883 ms/op
                 existUser·p0.99:   5.841 ms/op
                 existUser·p0.999:  15.013 ms/op
                 existUser·p0.9999: 33.642 ms/op
                 existUser·p1.00:   35.062 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 287750
  mean =      3.335 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9641 
    [ 2.500,  5.000) = 271961 
    [ 5.000,  7.500) = 4548 
    [ 7.500, 10.000) = 1087 
    [10.000, 12.500) = 172 
    [12.500, 15.000) = 10 
    [15.000, 17.500) = 39 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 73 
    [25.000, 27.500) = 77 
    [27.500, 30.000) = 45 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 27 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.918 ms/op
     p(50.0000) =      3.224 ms/op
     p(90.0000) =      3.645 ms/op
     p(95.0000) =      3.957 ms/op
     p(99.0000) =      6.074 ms/op
     p(99.9000) =     21.143 ms/op
     p(99.9900) =     32.488 ms/op
     p(99.9990) =     34.611 ms/op
     p(99.9999) =     35.062 ms/op
    p(100.0000) =     35.062 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 10.225 ±(99.9%) 0.123 ms/op
# Warmup Iteration   2: 4.065 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.639 ±(99.9%) 0.011 ms/op
Iteration   1: 3.703 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.137 ms/op
                 getUser·p0.50:   3.482 ms/op
                 getUser·p0.90:   4.309 ms/op
                 getUser·p0.95:   5.415 ms/op
                 getUser·p0.99:   7.458 ms/op
                 getUser·p0.999:  20.349 ms/op
                 getUser·p0.9999: 23.507 ms/op
                 getUser·p1.00:   24.117 ms/op

Iteration   2: 3.511 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.212 ms/op
                 getUser·p0.50:   3.379 ms/op
                 getUser·p0.90:   3.891 ms/op
                 getUser·p0.95:   4.383 ms/op
                 getUser·p0.99:   6.267 ms/op
                 getUser·p0.999:  22.151 ms/op
                 getUser·p0.9999: 24.966 ms/op
                 getUser·p1.00:   25.199 ms/op

Iteration   3: 3.594 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.286 ms/op
                 getUser·p0.50:   3.469 ms/op
                 getUser·p0.90:   3.957 ms/op
                 getUser·p0.95:   4.506 ms/op
                 getUser·p0.99:   7.097 ms/op
                 getUser·p0.999:  20.930 ms/op
                 getUser·p0.9999: 27.387 ms/op
                 getUser·p1.00:   28.574 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 266491
  mean =      3.601 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4451 
    [ 2.500,  5.000) = 250152 
    [ 5.000,  7.500) = 9703 
    [ 7.500, 10.000) = 1562 
    [10.000, 12.500) = 240 
    [12.500, 15.000) = 65 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 123 
    [22.500, 25.000) = 131 
    [25.000, 27.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      1.137 ms/op
     p(50.0000) =      3.449 ms/op
     p(90.0000) =      4.067 ms/op
     p(95.0000) =      4.760 ms/op
     p(99.0000) =      7.127 ms/op
     p(99.9000) =     20.644 ms/op
     p(99.9900) =     25.112 ms/op
     p(99.9990) =     28.530 ms/op
     p(99.9999) =     28.574 ms/op
    p(100.0000) =     28.574 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 10.676 ±(99.9%) 0.146 ms/op
# Warmup Iteration   2: 4.667 ±(99.9%) 0.044 ms/op
# Warmup Iteration   3: 4.335 ±(99.9%) 0.015 ms/op
Iteration   1: 4.268 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.726 ms/op
                 listUser·p0.50:   4.096 ms/op
                 listUser·p0.90:   4.604 ms/op
                 listUser·p0.95:   5.317 ms/op
                 listUser·p0.99:   8.459 ms/op
                 listUser·p0.999:  21.500 ms/op
                 listUser·p0.9999: 25.249 ms/op
                 listUser·p1.00:   27.066 ms/op

Iteration   2: 4.217 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.421 ms/op
                 listUser·p0.50:   4.067 ms/op
                 listUser·p0.90:   4.571 ms/op
                 listUser·p0.95:   5.202 ms/op
                 listUser·p0.99:   8.501 ms/op
                 listUser·p0.999:  15.073 ms/op
                 listUser·p0.9999: 20.933 ms/op
                 listUser·p1.00:   22.086 ms/op

Iteration   3: 4.058 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.241 ms/op
                 listUser·p0.50:   3.830 ms/op
                 listUser·p0.90:   4.596 ms/op
                 listUser·p0.95:   4.899 ms/op
                 listUser·p0.99:   7.610 ms/op
                 listUser·p0.999:  14.125 ms/op
                 listUser·p0.9999: 20.447 ms/op
                 listUser·p1.00:   20.578 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 229560
  mean =      4.179 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24 
    [ 2.500,  5.000) = 217275 
    [ 5.000,  7.500) = 8830 
    [ 7.500, 10.000) = 2374 
    [10.000, 12.500) = 521 
    [12.500, 15.000) = 254 
    [15.000, 17.500) = 98 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 94 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      1.726 ms/op
     p(50.0000) =      4.022 ms/op
     p(90.0000) =      4.588 ms/op
     p(95.0000) =      5.079 ms/op
     p(99.0000) =      8.298 ms/op
     p(99.9000) =     15.435 ms/op
     p(99.9900) =     24.157 ms/op
     p(99.9990) =     25.858 ms/op
     p(99.9999) =     27.066 ms/op
    p(100.0000) =     27.066 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.063 ± 4.250  ops/ms
ClientPb.existUser                       thrpt       3   9.627 ± 1.647  ops/ms
ClientPb.getUser                         thrpt       3   9.283 ± 1.789  ops/ms
ClientPb.listUser                        thrpt       3   7.768 ± 2.363  ops/ms
ClientPb.createUser                       avgt       3   3.524 ± 0.536   ms/op
ClientPb.existUser                        avgt       3   3.343 ± 1.328   ms/op
ClientPb.getUser                          avgt       3   3.534 ± 1.360   ms/op
ClientPb.listUser                         avgt       3   4.036 ± 1.888   ms/op
ClientPb.createUser                     sample  274820   3.493 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.413           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.363           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.998           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.317           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.283           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.453           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.166           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.410           ms/op
ClientPb.existUser                      sample  287750   3.335 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.918           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.224           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.645           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.957           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.074           ms/op
ClientPb.existUser:existUser·p0.999     sample          21.143           ms/op
ClientPb.existUser:existUser·p0.9999    sample          32.488           ms/op
ClientPb.existUser:existUser·p1.00      sample          35.062           ms/op
ClientPb.getUser                        sample  266491   3.601 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.137           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.449           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.067           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.760           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.127           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.644           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.112           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.574           ms/op
ClientPb.listUser                       sample  229560   4.179 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.726           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.022           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.588           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.079           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.298           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.435           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.157           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.066           ms/op
