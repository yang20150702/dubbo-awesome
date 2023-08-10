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
# Warmup Iteration   1: 2.168 ops/ms
# Warmup Iteration   2: 4.570 ops/ms
# Warmup Iteration   3: 8.579 ops/ms
Iteration   1: 9.552 ops/ms
Iteration   2: 9.521 ops/ms
Iteration   3: 9.576 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.549 ±(99.9%) 0.500 ops/ms [Average]
  (min, avg, max) = (9.521, 9.549, 9.576), stdev = 0.027
  CI (99.9%): [9.050, 10.049] (assumes normal distribution)


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
# Warmup Iteration   1: 3.528 ops/ms
# Warmup Iteration   2: 9.040 ops/ms
# Warmup Iteration   3: 9.840 ops/ms
Iteration   1: 9.735 ops/ms
Iteration   2: 9.787 ops/ms
Iteration   3: 9.974 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.832 ±(99.9%) 2.289 ops/ms [Average]
  (min, avg, max) = (9.735, 9.832, 9.974), stdev = 0.125
  CI (99.9%): [7.543, 12.121] (assumes normal distribution)


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
# Warmup Iteration   1: 3.173 ops/ms
# Warmup Iteration   2: 8.200 ops/ms
# Warmup Iteration   3: 9.361 ops/ms
Iteration   1: 9.522 ops/ms
Iteration   2: 9.829 ops/ms
Iteration   3: 9.640 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.664 ±(99.9%) 2.825 ops/ms [Average]
  (min, avg, max) = (9.522, 9.664, 9.829), stdev = 0.155
  CI (99.9%): [6.839, 12.488] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 2.740 ops/ms
# Warmup Iteration   2: 7.093 ops/ms
# Warmup Iteration   3: 7.984 ops/ms
Iteration   1: 7.847 ops/ms
Iteration   2: 8.233 ops/ms
Iteration   3: 8.126 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.068 ±(99.9%) 3.636 ops/ms [Average]
  (min, avg, max) = (7.847, 8.068, 8.233), stdev = 0.199
  CI (99.9%): [4.433, 11.704] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 8.953 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.729 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.622 ±(99.9%) 0.004 ms/op
Iteration   1: 3.288 ±(99.9%) 0.007 ms/op
Iteration   2: 3.301 ±(99.9%) 0.005 ms/op
Iteration   3: 3.325 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.305 ±(99.9%) 0.345 ms/op [Average]
  (min, avg, max) = (3.288, 3.305, 3.325), stdev = 0.019
  CI (99.9%): [2.960, 3.649] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 9.175 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.514 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.403 ±(99.9%) 0.003 ms/op
Iteration   1: 3.264 ±(99.9%) 0.006 ms/op
Iteration   2: 3.177 ±(99.9%) 0.005 ms/op
Iteration   3: 3.122 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.188 ±(99.9%) 1.301 ms/op [Average]
  (min, avg, max) = (3.122, 3.188, 3.264), stdev = 0.071
  CI (99.9%): [1.887, 4.489] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 8.739 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.815 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.304 ±(99.9%) 0.002 ms/op
Iteration   1: 3.287 ±(99.9%) 0.003 ms/op
Iteration   2: 3.176 ±(99.9%) 0.001 ms/op
Iteration   3: 3.159 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.208 ±(99.9%) 1.265 ms/op [Average]
  (min, avg, max) = (3.159, 3.208, 3.287), stdev = 0.069
  CI (99.9%): [1.943, 4.472] (assumes normal distribution)


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
# Warmup Iteration   1: 9.545 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.031 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.947 ±(99.9%) 0.003 ms/op
Iteration   1: 3.737 ±(99.9%) 0.009 ms/op
Iteration   2: 3.857 ±(99.9%) 0.006 ms/op
Iteration   3: 3.741 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.778 ±(99.9%) 1.245 ms/op [Average]
  (min, avg, max) = (3.737, 3.778, 3.857), stdev = 0.068
  CI (99.9%): [2.534, 5.023] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 9.111 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 3.932 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.313 ±(99.9%) 0.009 ms/op
Iteration   1: 3.403 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.049 ms/op
                 createUser·p0.50:   3.301 ms/op
                 createUser·p0.90:   3.899 ms/op
                 createUser·p0.95:   4.293 ms/op
                 createUser·p0.99:   6.357 ms/op
                 createUser·p0.999:  18.173 ms/op
                 createUser·p0.9999: 21.692 ms/op
                 createUser·p1.00:   22.905 ms/op

Iteration   2: 3.260 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.753 ms/op
                 createUser·p0.50:   3.277 ms/op
                 createUser·p0.90:   3.445 ms/op
                 createUser·p0.95:   3.539 ms/op
                 createUser·p0.99:   5.571 ms/op
                 createUser·p0.999:  10.943 ms/op
                 createUser·p0.9999: 23.080 ms/op
                 createUser·p1.00:   24.773 ms/op

Iteration   3: 3.512 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.599 ms/op
                 createUser·p0.50:   3.322 ms/op
                 createUser·p0.90:   4.178 ms/op
                 createUser·p0.95:   5.169 ms/op
                 createUser·p0.99:   7.381 ms/op
                 createUser·p0.999:  17.105 ms/op
                 createUser·p0.9999: 23.393 ms/op
                 createUser·p1.00:   23.953 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 283116
  mean =      3.389 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22152 
    [ 2.500,  5.000) = 251767 
    [ 5.000,  7.500) = 7511 
    [ 7.500, 10.000) = 1232 
    [10.000, 12.500) = 52 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 85 
    [17.500, 20.000) = 104 
    [20.000, 22.500) = 128 
    [22.500, 25.000) = 41 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.049 ms/op
     p(50.0000) =      3.293 ms/op
     p(90.0000) =      3.822 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      6.668 ms/op
     p(99.9000) =     17.101 ms/op
     p(99.9900) =     22.993 ms/op
     p(99.9990) =     23.763 ms/op
     p(99.9999) =     24.773 ms/op
    p(100.0000) =     24.773 ms/op


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
# Warmup Iteration   1: 8.168 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 3.492 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.221 ±(99.9%) 0.009 ms/op
Iteration   1: 3.200 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.038 ms/op
                 existUser·p0.50:   3.117 ms/op
                 existUser·p0.90:   3.514 ms/op
                 existUser·p0.95:   4.047 ms/op
                 existUser·p0.99:   6.054 ms/op
                 existUser·p0.999:  9.716 ms/op
                 existUser·p0.9999: 20.317 ms/op
                 existUser·p1.00:   21.103 ms/op

Iteration   2: 3.227 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.122 ms/op
                 existUser·p0.50:   3.101 ms/op
                 existUser·p0.90:   3.465 ms/op
                 existUser·p0.95:   4.186 ms/op
                 existUser·p0.99:   6.447 ms/op
                 existUser·p0.999:  12.757 ms/op
                 existUser·p0.9999: 24.445 ms/op
                 existUser·p1.00:   25.002 ms/op

Iteration   3: 3.222 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.935 ms/op
                 existUser·p0.50:   3.183 ms/op
                 existUser·p0.90:   3.404 ms/op
                 existUser·p0.95:   3.752 ms/op
                 existUser·p0.99:   6.007 ms/op
                 existUser·p0.999:  14.594 ms/op
                 existUser·p0.9999: 27.525 ms/op
                 existUser·p1.00:   28.377 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 298248
  mean =      3.216 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18860 
    [ 2.500,  5.000) = 271000 
    [ 5.000,  7.500) = 6710 
    [ 7.500, 10.000) = 1133 
    [10.000, 12.500) = 172 
    [12.500, 15.000) = 83 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 79 
    [20.000, 22.500) = 91 
    [22.500, 25.000) = 71 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.935 ms/op
     p(50.0000) =      3.138 ms/op
     p(90.0000) =      3.457 ms/op
     p(95.0000) =      3.981 ms/op
     p(99.0000) =      6.193 ms/op
     p(99.9000) =     14.582 ms/op
     p(99.9900) =     26.259 ms/op
     p(99.9990) =     28.084 ms/op
     p(99.9999) =     28.377 ms/op
    p(100.0000) =     28.377 ms/op


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
# Warmup Iteration   1: 8.148 ±(99.9%) 0.102 ms/op
# Warmup Iteration   2: 3.590 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.361 ±(99.9%) 0.009 ms/op
Iteration   1: 3.374 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.313 ms/op
                 getUser·p0.50:   3.215 ms/op
                 getUser·p0.90:   3.772 ms/op
                 getUser·p0.95:   4.555 ms/op
                 getUser·p0.99:   6.717 ms/op
                 getUser·p0.999:  17.105 ms/op
                 getUser·p0.9999: 20.169 ms/op
                 getUser·p1.00:   22.741 ms/op

Iteration   2: 3.397 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.139 ms/op
                 getUser·p0.50:   3.178 ms/op
                 getUser·p0.90:   3.871 ms/op
                 getUser·p0.95:   4.932 ms/op
                 getUser·p0.99:   7.438 ms/op
                 getUser·p0.999:  18.510 ms/op
                 getUser·p0.9999: 21.627 ms/op
                 getUser·p1.00:   22.512 ms/op

Iteration   3: 3.400 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.665 ms/op
                 getUser·p0.50:   3.277 ms/op
                 getUser·p0.90:   3.805 ms/op
                 getUser·p0.95:   4.399 ms/op
                 getUser·p0.99:   6.734 ms/op
                 getUser·p0.999:  9.011 ms/op
                 getUser·p0.9999: 22.905 ms/op
                 getUser·p1.00:   23.495 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 282976
  mean =      3.390 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8848 
    [ 2.500,  5.000) = 263199 
    [ 5.000,  7.500) = 8916 
    [ 7.500, 10.000) = 1579 
    [10.000, 12.500) = 129 
    [12.500, 15.000) = 9 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 120 
    [20.000, 22.500) = 110 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.139 ms/op
     p(50.0000) =      3.228 ms/op
     p(90.0000) =      3.809 ms/op
     p(95.0000) =      4.612 ms/op
     p(99.0000) =      7.012 ms/op
     p(99.9000) =     16.696 ms/op
     p(99.9900) =     21.922 ms/op
     p(99.9990) =     23.244 ms/op
     p(99.9999) =     23.495 ms/op
    p(100.0000) =     23.495 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 9.736 ±(99.9%) 0.131 ms/op
# Warmup Iteration   2: 4.155 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.838 ±(99.9%) 0.011 ms/op
Iteration   1: 3.919 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.214 ms/op
                 listUser·p0.50:   3.699 ms/op
                 listUser·p0.90:   4.227 ms/op
                 listUser·p0.95:   5.349 ms/op
                 listUser·p0.99:   8.135 ms/op
                 listUser·p0.999:  16.849 ms/op
                 listUser·p0.9999: 21.618 ms/op
                 listUser·p1.00:   23.233 ms/op

Iteration   2: 3.889 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.142 ms/op
                 listUser·p0.50:   3.703 ms/op
                 listUser·p0.90:   4.383 ms/op
                 listUser·p0.95:   4.858 ms/op
                 listUser·p0.99:   7.684 ms/op
                 listUser·p0.999:  14.467 ms/op
                 listUser·p0.9999: 23.324 ms/op
                 listUser·p1.00:   23.429 ms/op

Iteration   3: 3.770 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.146 ms/op
                 listUser·p0.50:   3.617 ms/op
                 listUser·p0.90:   4.108 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   7.373 ms/op
                 listUser·p0.999:  11.903 ms/op
                 listUser·p0.9999: 20.336 ms/op
                 listUser·p1.00:   21.135 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 248573
  mean =      3.858 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 54 
    [ 2.500,  5.000) = 237911 
    [ 5.000,  7.500) = 7419 
    [ 7.500, 10.000) = 2408 
    [10.000, 12.500) = 392 
    [12.500, 15.000) = 150 
    [15.000, 17.500) = 117 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.214 ms/op
     p(50.0000) =      3.678 ms/op
     p(90.0000) =      4.243 ms/op
     p(95.0000) =      4.702 ms/op
     p(99.0000) =      7.856 ms/op
     p(99.9000) =     14.949 ms/op
     p(99.9900) =     22.582 ms/op
     p(99.9990) =     23.396 ms/op
     p(99.9999) =     23.429 ms/op
    p(100.0000) =     23.429 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.549 ± 0.500  ops/ms
ClientPb.existUser                       thrpt       3   9.832 ± 2.289  ops/ms
ClientPb.getUser                         thrpt       3   9.664 ± 2.825  ops/ms
ClientPb.listUser                        thrpt       3   8.068 ± 3.636  ops/ms
ClientPb.createUser                       avgt       3   3.305 ± 0.345   ms/op
ClientPb.existUser                        avgt       3   3.188 ± 1.301   ms/op
ClientPb.getUser                          avgt       3   3.208 ± 1.265   ms/op
ClientPb.listUser                         avgt       3   3.778 ± 1.245   ms/op
ClientPb.createUser                     sample  283116   3.389 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.049           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.293           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.822           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.334           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.668           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.101           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.993           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.773           ms/op
ClientPb.existUser                      sample  298248   3.216 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.935           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.138           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.457           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.981           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.193           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.582           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.259           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.377           ms/op
ClientPb.getUser                        sample  282976   3.390 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.139           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.228           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.809           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.612           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.012           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.696           ms/op
ClientPb.getUser:getUser·p0.9999        sample          21.922           ms/op
ClientPb.getUser:getUser·p1.00          sample          23.495           ms/op
ClientPb.listUser                       sample  248573   3.858 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.214           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.678           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.243           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.702           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.856           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.949           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.582           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.429           ms/op
