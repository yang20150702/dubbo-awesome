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
# Warmup Iteration   1: 2.103 ops/ms
# Warmup Iteration   2: 5.607 ops/ms
# Warmup Iteration   3: 8.466 ops/ms
Iteration   1: 9.113 ops/ms
Iteration   2: 9.305 ops/ms
Iteration   3: 9.168 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.196 ±(99.9%) 1.804 ops/ms [Average]
  (min, avg, max) = (9.113, 9.196, 9.305), stdev = 0.099
  CI (99.9%): [7.391, 11.000] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 2.936 ops/ms
# Warmup Iteration   2: 8.282 ops/ms
# Warmup Iteration   3: 9.716 ops/ms
Iteration   1: 9.636 ops/ms
Iteration   2: 9.648 ops/ms
Iteration   3: 9.390 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.558 ±(99.9%) 2.652 ops/ms [Average]
  (min, avg, max) = (9.390, 9.558, 9.648), stdev = 0.145
  CI (99.9%): [6.906, 12.210] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.405 ops/ms
# Warmup Iteration   2: 7.807 ops/ms
# Warmup Iteration   3: 8.629 ops/ms
Iteration   1: 8.859 ops/ms
Iteration   2: 8.594 ops/ms
Iteration   3: 9.115 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.856 ±(99.9%) 4.753 ops/ms [Average]
  (min, avg, max) = (8.594, 8.856, 9.115), stdev = 0.261
  CI (99.9%): [4.103, 13.609] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 2.730 ops/ms
# Warmup Iteration   2: 6.956 ops/ms
# Warmup Iteration   3: 7.608 ops/ms
Iteration   1: 7.748 ops/ms
Iteration   2: 7.770 ops/ms
Iteration   3: 7.820 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.779 ±(99.9%) 0.676 ops/ms [Average]
  (min, avg, max) = (7.748, 7.779, 7.820), stdev = 0.037
  CI (99.9%): [7.103, 8.455] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 9.203 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.776 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.691 ±(99.9%) 0.005 ms/op
Iteration   1: 3.503 ±(99.9%) 0.007 ms/op
Iteration   2: 3.604 ±(99.9%) 0.005 ms/op
Iteration   3: 3.518 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.542 ±(99.9%) 0.993 ms/op [Average]
  (min, avg, max) = (3.503, 3.542, 3.604), stdev = 0.054
  CI (99.9%): [2.549, 4.535] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 9.373 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.747 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.431 ±(99.9%) 0.003 ms/op
Iteration   1: 3.417 ±(99.9%) 0.010 ms/op
Iteration   2: 3.421 ±(99.9%) 0.008 ms/op
Iteration   3: 3.384 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.407 ±(99.9%) 0.374 ms/op [Average]
  (min, avg, max) = (3.384, 3.407, 3.421), stdev = 0.021
  CI (99.9%): [3.033, 3.781] (assumes normal distribution)


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
# Warmup Iteration   1: 9.985 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.804 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.551 ±(99.9%) 0.005 ms/op
Iteration   1: 3.505 ±(99.9%) 0.007 ms/op
Iteration   2: 3.451 ±(99.9%) 0.006 ms/op
Iteration   3: 3.383 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.446 ±(99.9%) 1.116 ms/op [Average]
  (min, avg, max) = (3.383, 3.446, 3.505), stdev = 0.061
  CI (99.9%): [2.330, 4.562] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 12.437 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.684 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.196 ±(99.9%) 0.009 ms/op
Iteration   1: 4.239 ±(99.9%) 0.009 ms/op
Iteration   2: 4.113 ±(99.9%) 0.012 ms/op
Iteration   3: 4.102 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.151 ±(99.9%) 1.388 ms/op [Average]
  (min, avg, max) = (4.102, 4.151, 4.239), stdev = 0.076
  CI (99.9%): [2.763, 5.540] (assumes normal distribution)


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
# Warmup Iteration   1: 8.857 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 4.060 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.635 ±(99.9%) 0.011 ms/op
Iteration   1: 3.495 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.407 ms/op
                 createUser·p0.50:   3.334 ms/op
                 createUser·p0.90:   3.961 ms/op
                 createUser·p0.95:   4.710 ms/op
                 createUser·p0.99:   6.611 ms/op
                 createUser·p0.999:  21.103 ms/op
                 createUser·p0.9999: 24.206 ms/op
                 createUser·p1.00:   26.149 ms/op

Iteration   2: 3.543 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.376 ms/op
                 createUser·p0.50:   3.322 ms/op
                 createUser·p0.90:   4.030 ms/op
                 createUser·p0.95:   4.628 ms/op
                 createUser·p0.99:   6.914 ms/op
                 createUser·p0.999:  21.745 ms/op
                 createUser·p0.9999: 25.558 ms/op
                 createUser·p1.00:   26.608 ms/op

Iteration   3: 3.546 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.479 ms/op
                 createUser·p0.50:   3.432 ms/op
                 createUser·p0.90:   4.096 ms/op
                 createUser·p0.95:   4.440 ms/op
                 createUser·p0.99:   6.472 ms/op
                 createUser·p0.999:  23.221 ms/op
                 createUser·p0.9999: 25.786 ms/op
                 createUser·p1.00:   27.001 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 271863
  mean =      3.528 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5467 
    [ 2.500,  5.000) = 256583 
    [ 5.000,  7.500) = 8243 
    [ 7.500, 10.000) = 1116 
    [10.000, 12.500) = 90 
    [12.500, 15.000) = 12 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 123 
    [22.500, 25.000) = 146 
    [25.000, 27.500) = 74 

  Percentiles, ms/op:
      p(0.0000) =      1.376 ms/op
     p(50.0000) =      3.363 ms/op
     p(90.0000) =      4.039 ms/op
     p(95.0000) =      4.547 ms/op
     p(99.0000) =      6.701 ms/op
     p(99.9000) =     21.791 ms/op
     p(99.9900) =     25.592 ms/op
     p(99.9990) =     26.977 ms/op
     p(99.9999) =     27.001 ms/op
    p(100.0000) =     27.001 ms/op


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
# Warmup Iteration   1: 8.704 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 3.681 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.485 ±(99.9%) 0.009 ms/op
Iteration   1: 3.373 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.538 ms/op
                 existUser·p0.50:   3.301 ms/op
                 existUser·p0.90:   3.686 ms/op
                 existUser·p0.95:   4.129 ms/op
                 existUser·p0.99:   5.825 ms/op
                 existUser·p0.999:  19.629 ms/op
                 existUser·p0.9999: 25.100 ms/op
                 existUser·p1.00:   26.182 ms/op

Iteration   2: 3.463 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.000 ms/op
                 existUser·p0.50:   3.281 ms/op
                 existUser·p0.90:   4.276 ms/op
                 existUser·p0.95:   4.760 ms/op
                 existUser·p0.99:   6.767 ms/op
                 existUser·p0.999:  22.282 ms/op
                 existUser·p0.9999: 27.616 ms/op
                 existUser·p1.00:   28.279 ms/op

Iteration   3: 3.368 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.597 ms/op
                 existUser·p0.50:   3.191 ms/op
                 existUser·p0.90:   3.822 ms/op
                 existUser·p0.95:   4.686 ms/op
                 existUser·p0.99:   6.660 ms/op
                 existUser·p0.999:  18.159 ms/op
                 existUser·p0.9999: 26.051 ms/op
                 existUser·p1.00:   26.575 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 282225
  mean =      3.401 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13820 
    [ 2.500,  5.000) = 259797 
    [ 5.000,  7.500) = 7256 
    [ 7.500, 10.000) = 958 
    [10.000, 12.500) = 87 
    [12.500, 15.000) = 19 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 74 
    [22.500, 25.000) = 107 
    [25.000, 27.500) = 64 

  Percentiles, ms/op:
      p(0.0000) =      1.000 ms/op
     p(50.0000) =      3.265 ms/op
     p(90.0000) =      3.928 ms/op
     p(95.0000) =      4.555 ms/op
     p(99.0000) =      6.554 ms/op
     p(99.9000) =     18.900 ms/op
     p(99.9900) =     26.444 ms/op
     p(99.9990) =     27.886 ms/op
     p(99.9999) =     28.279 ms/op
    p(100.0000) =     28.279 ms/op


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
# Warmup Iteration   1: 10.149 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 3.960 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.603 ±(99.9%) 0.011 ms/op
Iteration   1: 3.636 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.739 ms/op
                 getUser·p0.50:   3.428 ms/op
                 getUser·p0.90:   3.920 ms/op
                 getUser·p0.95:   5.169 ms/op
                 getUser·p0.99:   7.635 ms/op
                 getUser·p0.999:  20.383 ms/op
                 getUser·p0.9999: 22.846 ms/op
                 getUser·p1.00:   25.559 ms/op

Iteration   2: 3.527 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.960 ms/op
                 getUser·p0.50:   3.445 ms/op
                 getUser·p0.90:   3.817 ms/op
                 getUser·p0.95:   3.969 ms/op
                 getUser·p0.99:   6.210 ms/op
                 getUser·p0.999:  21.417 ms/op
                 getUser·p0.9999: 24.049 ms/op
                 getUser·p1.00:   25.330 ms/op

Iteration   3: 3.599 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.708 ms/op
                 getUser·p0.50:   3.404 ms/op
                 getUser·p0.90:   4.002 ms/op
                 getUser·p0.95:   5.202 ms/op
                 getUser·p0.99:   7.201 ms/op
                 getUser·p0.999:  17.565 ms/op
                 getUser·p0.9999: 25.166 ms/op
                 getUser·p1.00:   26.149 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 267453
  mean =      3.587 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2139 
    [ 2.500,  5.000) = 253934 
    [ 5.000,  7.500) = 9201 
    [ 7.500, 10.000) = 1416 
    [10.000, 12.500) = 333 
    [12.500, 15.000) = 103 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 113 
    [22.500, 25.000) = 123 
    [25.000, 27.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      1.708 ms/op
     p(50.0000) =      3.424 ms/op
     p(90.0000) =      3.899 ms/op
     p(95.0000) =      4.497 ms/op
     p(99.0000) =      7.299 ms/op
     p(99.9000) =     19.759 ms/op
     p(99.9900) =     24.478 ms/op
     p(99.9990) =     25.751 ms/op
     p(99.9999) =     26.149 ms/op
    p(100.0000) =     26.149 ms/op


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
# Warmup Iteration   1: 10.191 ±(99.9%) 0.141 ms/op
# Warmup Iteration   2: 4.499 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.263 ±(99.9%) 0.014 ms/op
Iteration   1: 4.241 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.993 ms/op
                 listUser·p0.50:   4.080 ms/op
                 listUser·p0.90:   4.653 ms/op
                 listUser·p0.95:   5.284 ms/op
                 listUser·p0.99:   8.389 ms/op
                 listUser·p0.999:  17.747 ms/op
                 listUser·p0.9999: 21.279 ms/op
                 listUser·p1.00:   22.118 ms/op

Iteration   2: 4.096 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.915 ms/op
                 listUser·p0.50:   3.903 ms/op
                 listUser·p0.90:   4.473 ms/op
                 listUser·p0.95:   5.079 ms/op
                 listUser·p0.99:   7.856 ms/op
                 listUser·p0.999:  15.106 ms/op
                 listUser·p0.9999: 18.199 ms/op
                 listUser·p1.00:   18.678 ms/op

Iteration   3: 4.036 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.507 ms/op
                 listUser·p0.50:   3.838 ms/op
                 listUser·p0.90:   4.424 ms/op
                 listUser·p0.95:   4.727 ms/op
                 listUser·p0.99:   8.503 ms/op
                 listUser·p0.999:  17.269 ms/op
                 listUser·p0.9999: 19.628 ms/op
                 listUser·p1.00:   23.822 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 232609
  mean =      4.122 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24 
    [ 2.500,  5.000) = 220946 
    [ 5.000,  7.500) = 8166 
    [ 7.500, 10.000) = 2489 
    [10.000, 12.500) = 447 
    [12.500, 15.000) = 209 
    [15.000, 17.500) = 181 
    [17.500, 20.000) = 123 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.915 ms/op
     p(50.0000) =      3.912 ms/op
     p(90.0000) =      4.522 ms/op
     p(95.0000) =      5.005 ms/op
     p(99.0000) =      8.258 ms/op
     p(99.9000) =     15.892 ms/op
     p(99.9900) =     20.185 ms/op
     p(99.9990) =     22.076 ms/op
     p(99.9999) =     23.822 ms/op
    p(100.0000) =     23.822 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.196 ± 1.804  ops/ms
ClientPb.existUser                       thrpt       3   9.558 ± 2.652  ops/ms
ClientPb.getUser                         thrpt       3   8.856 ± 4.753  ops/ms
ClientPb.listUser                        thrpt       3   7.779 ± 0.676  ops/ms
ClientPb.createUser                       avgt       3   3.542 ± 0.993   ms/op
ClientPb.existUser                        avgt       3   3.407 ± 0.374   ms/op
ClientPb.getUser                          avgt       3   3.446 ± 1.116   ms/op
ClientPb.listUser                         avgt       3   4.151 ± 1.388   ms/op
ClientPb.createUser                     sample  271863   3.528 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.376           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.363           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.039           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.547           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.701           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.791           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.592           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.001           ms/op
ClientPb.existUser                      sample  282225   3.401 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.000           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.265           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.928           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.555           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.554           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.900           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.444           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.279           ms/op
ClientPb.getUser                        sample  267453   3.587 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.708           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.424           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.899           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.497           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.299           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.759           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.478           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.149           ms/op
ClientPb.listUser                       sample  232609   4.122 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.915           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.912           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.522           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.005           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.258           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.892           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.185           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.822           ms/op
